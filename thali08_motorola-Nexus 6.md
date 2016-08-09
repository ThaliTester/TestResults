#### Test 79751015ccfe79c_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-09 15:04:40.277  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:04:40.301  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-09 15:04:40.302  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-09 15:04:40.355  1526  2697 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-09 15:04:40.355  1526  2697 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-09 15:04:40.356  1526  2697 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:04:40.356  1526  2697 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-09 15:04:40.375  1526  2697 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 15:04:40.375  1526  2697 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 15:04:40.375  1526  2697 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 15:04:40.375  1526  2697 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 15:04:40.375  1526  2697 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 15:04:40.375  1526  2697 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 15:04:40.375  1526  2697 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
08-09 15:04:40.380  2594  2623 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 15:04:40.380  2594  2623 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-09 15:04:40.380  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-09 15:04:40.380  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-09 15:04:40.380  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-09 15:04:40.380  2594  2623 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-09 15:04:40.380  2594  2623 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
08-09 15:04:40.874  3356  3356 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-09 15:04:40.878  3356  3356 D AndroidRuntime: CheckJNI is OFF
08-09 15:04:40.913  3356  3356 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-09 15:04:40.955  3356  3356 I Radio-JNI: register_android_hardware_Radio DONE
08-09 15:04:40.975  3356  3356 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-09 15:04:40.979   873  1379 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-09 15:04:41.048   873  1379 I ActivityManager: Start proc 3366:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-09 15:04:41.057  3356  3356 D AndroidRuntime: Shutting down VM
08-09 15:04:41.162  3366  3366 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-09 15:04:41.182  3366  3366 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-09 15:04:41.264  3366  3366 I LibraryLoader: Time to load native libraries: 79 ms (timestamps 2330-2409)
08-09 15:04:41.264  3366  3366 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-09 15:04:41.298  3366  3366 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f07ebed}
08-09 15:04:41.299  3366  3366 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-09 15:04:41.299  3366  3366 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-09 15:04:41.312  3366  3366 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-09 15:04:41.315  3366  3366 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-09 15:04:41.355  3366  3382 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,08-09 15:04:41.363  3366  3366 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-09 15:04:41.374  3366  3366 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-09 15:04:41.374  3366  3366 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-09 15:04:41.374  3366  3366 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-09 15:04:41.374  3366  3366 I Adreno  : Build Date                       : 10/20/15
08-09 15:04:41.374  3366  3366 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-09 15:04:41.374  3366  3366 I Adreno  : Local Branch                     : M14
08-09 15:04:41.374  3366  3366 I Adreno  : Remote Branch                    : 
08-09 15:04:41.374  3366  3366 I Adreno  : Remote Branch                    : 
08-09 15:04:41.374  3366  3366 I Adreno  : Reconstruct Branch               : 
,08-09 15:04:41.458   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b77bf8f:true
,08-09 15:04:41.515  3366  3366 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-09 15:04:41.531  3366  3366 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-09 15:04:41.580  3366  3404 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-09 15:04:41.599  3366  3391 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-09 15:04:41.642  3366  3404 I OpenGLRenderer: Initialized EGL, version 1.4
,08-09 15:04:41.720   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +592ms (total +712ms)
,08-09 15:04:41.724  1662  1662 I Keyboard.Facilitator: onFinishInput()
,08-09 15:04:41.816  3366  3366 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3366
,08-09 15:04:41.967  3366  3366 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-09 15:04:42.169  3366  3406 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1682769616
,08-09 15:04:42.176  3366  3406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-09 15:04:42.176  3366  3406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-09 15:04:42.176  3366  3406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-09 15:04:42.176  3366  3406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-09 15:04:42.176  3366  3406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-09 15:04:42.177  3366  3406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6db2448 added. We now have 1 listener(s)
,08-09 15:04:42.180  3366  3406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-09 15:04:42.180  3366  3406 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-09 15:04:42.181  3366  3406 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 15:04:42.181  3366  3406 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-09 15:04:42.185  3366  3406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c1aec7 added. We now have 1 listener(s)
,08-09 15:04:42.186  3366  3406 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 15:04:42.195   873  1316 D WifiService: New client listening to asynchronous messages
,08-09 15:04:42.196  3366  3406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 15:04:42.196  3366  3406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-09 15:04:42.196  3366  3406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-09 15:04:42.196  3366  3406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-09 15:04:42.196  3366  3406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-09 15:04:42.201  3366  3406 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 15:04:42.201  3366  3406 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-09 15:04:42.208  3366  3406 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:04:42.208  3366  3406 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:04:42.208  3366  3406 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:04:42.208  3366  3406 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:04:42.208  3366  3406 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:04:42.208  3366  3406 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:04:42.208  3366  3406 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:04:42.208  3366  3406 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:04:42.208  3366  3406 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:04:42.208  3366  3406 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-09 15:04:42.208  3366  3406 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 15:04:42.209  3366  3406 I io.jxcore.node.LifeCycleMonitor: start: OK
08-09 15:04:42.214  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:04:42.234  3366  3366 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-09 15:04:43.844  3366  3413 W jxcore-log: Initializing JXcore engine
,08-09 15:04:43.844  3366  3413 W jxcore-log: JXcore engine is ready
,08-09 15:04:43.881  3413  3413 W Thread-290: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8934 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-09 15:04:43.881  3413  3413 W Thread-290: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11781]" dev="sockfs" ino=11781 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-09 15:04:43.881  3413  3413 W Thread-290: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-09 15:04:43.881  3413  3413 W Thread-290: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21259]" dev="sockfs" ino=21259 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-09 15:04:43.892  3366  3413 W jxcore-log: Starting JXcore engine
,08-09 15:04:43.969  3366  3413 W jxcore-log: Platform android
08-09 15:04:43.969  3366  3413 W jxcore-log: 
08-09 15:04:43.969  3366  3413 W jxcore-log: Process ARCH arm
08-09 15:04:43.969  3366  3413 W jxcore-log: 
,08-09 15:04:44.217  3366  3413 I jxcore-log: JXcore Cordova bridge is ready!
08-09 15:04:44.217  3366  3413 I jxcore-log: 
08-09 15:04:44.217  3366  3413 W jxcore-log: JXcore engine is started
,08-09 15:04:44.226  3366  3406 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-09 15:04:44.233  3366  3366 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-09 15:04:59.827  3366  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-09 15:04:59.827  3366  3413 I jxcore-log: 
,08-09 15:04:59.830  3366  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-09 15:04:59.830  3366  3413 I jxcore-log: 
,08-09 15:04:59.832  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:04:59.832  3366  3413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:04:59.832  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:04:59.832  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:04:59.832  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:04:59.832  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:04:59.832  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:04:59.832  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:04:59.832  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:04:59.833  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:04:59.833  3366  3413 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:04:59.835  3366  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-09 15:04:59.835  3366  3413 I jxcore-log: 
08-09 15:04:59.837  3366  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-09 15:04:59.837  3366  3413 I jxcore-log: 
,08-09 15:05:00.177  3366  3413 D ExecuteNativeTests: Running unit tests
,08-09 15:05:00.234  3366  3413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 15:05:00.234  3366  3413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa added. We now have 2 listener(s)
08-09 15:05:00.235  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 15:05:00.235  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-09 15:05:00.235  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 15:05:00.235  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:05:00.236  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab added. We now have 2 listener(s)
,08-09 15:05:00.236  3366  3413 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 15:05:00.236  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-09 15:05:00.237  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 15:05:00.243  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:05:00.243  3366  3413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:05:00.243  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:00.243  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:05:00.243  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:00.243  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:05:00.243  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:00.243  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:00.243  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:05:00.243  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.243  3366  3413 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:05:00.244  3366  3413 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-09 15:05:00.246  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:05:00.251  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-09 15:05:00.252  3366  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 15:05:00.252  3366  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-09 15:05:00.256  3366  3413 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-09 15:05:00.258  3366  3413 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-09 15:05:00.258  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 15:05:00.259  3366  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 15:05:00.259  3366  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 15:05:00.259  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 15:05:00.260  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.260  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.260  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.260  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.260  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:05:00.260  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 15:05:00.261  3366  3413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa removed from the list
08-09 15:05:00.261  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:05:00.261  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab removed from the list
08-09 15:05:00.261  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.261  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.262  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.262  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 15:05:00.262  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.262  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.262  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.262  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
,08-09 15:05:00.264  3366  3413 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-09 15:05:00.265  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.265  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-09 15:05:00.265  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.265  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 15:05:00.265  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.265  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.265  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
,08-09 15:05:00.265  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.265  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.265  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 15:05:00.265  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.266  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.266  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.266  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.266  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 15:05:00.266  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.266  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.266  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
,08-09 15:05:00.272  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-09 15:05:00.272  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-09 15:05:00.272  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-09 15:05:00.272  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-09 15:05:00.273  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-09 15:05:00.273  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-09 15:05:00.273  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-09 15:05:00.273  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-09 15:05:00.273  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-09 15:05:00.273  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-09 15:05:00.273  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-09 15:05:00.273  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-09 15:05:00.273  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-09 15:05:00.273  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-09 15:05:00.273  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-09 15:05:00.273  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-09 15:05:00.273  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-09 15:05:00.273  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-09 15:05:00.274  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-09 15:05:00.274  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-09 15:05:00.274  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-09 15:05:00.274  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-09 15:05:00.274  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-09 15:05:00.274  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-09 15:05:00.274  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-09 15:05:00.274  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-09 15:05:00.274  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-09 15:05:00.274  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-09 15:05:00.274  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-09 15:05:00.274  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-09 15:05:00.274  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-09 15:05:00.274  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.275  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.275  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.275  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.275  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.275  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.275  3366  3413 E org.thal,iproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.275  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.275  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.275  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.275  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.275  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.275  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.275  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.276  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.276  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.276  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.276  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.277  3366  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-09 15:05:00.278  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 15:05:00.279  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.279  3366  3413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:05:00.279  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:00.279  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:05:00.279  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:00.279  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:05:00.279  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:00.279  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:00.279  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:05:00.279  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.279  3366  3413 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:05:00.280  3366  3413 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 15:05:00.280  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 15:05:00.280  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 15:05:00.280  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 15:05:00.280  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 15:05:00.280  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 15:05:00.281  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:05:00.283  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-09 15:05:00.283  3366  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-09 15:05:00.284  3366  3413 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 15:05:00.284  3366  3413 I io.jxcore.node.ConnectionHelper: start: OK
08-09 15:05:00.284  3366  3366 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-09 15:05:00.285  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.285  3366  3413 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-09 15:05:00.287  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.287  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.287  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-09 15:05:00.287  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.287  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 15:05:00.287  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 15:05:00.287  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 15:05:00.287  3366  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 15:05:00.287  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 15:05:00.288  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 15:05:00.289  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:05:00.289  3366  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 15:05:00.289  3366  3366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:05:00.289  3366  3366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:05:00.289  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.289  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.289  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:05:00.289  3366  3366 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 15:05:00.290  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.290  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.290  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.290  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.290  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.290  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.290  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.291  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.291  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.291  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.291  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.292  3366  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-09 15:05:00.293  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 15:05:00.294  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.294  3366  3413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:05:00.294  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:00.294  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:05:00.294  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:00.294  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:05:00.294  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:00.294  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:00.294  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:05:00.294  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.294  3366  3413 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:05:00.295  3366  3413 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 15:05:00.295  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 15:05:00.295  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 15:05:00.295  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 15:05:00.295  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 15:05:00.295  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 15:05:00.295  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:05:00.296  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-09 15:05:00.297  3366  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-09 15:05:00.297  3366  3413 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 15:05:00.297  3366  3413 I io.jxcore.node.ConnectionHelper: start: OK
08-09 15:05:00.297  3366  3366 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-09 15:05:00.297  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.297  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.297  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-09 15:05:00.297  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.297  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 15:05:00.297  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 15:05:00.297  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 15:05:00.298  3366  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 15:05:00.298  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 15:05:00.298  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 15:05:00.298  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:05:00.299  3366  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 15:05:00.299  3366  3366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:05:00.299  3366  3366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:05:00.299  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.299  3366  3366 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 15:05:00.299  3366  3413 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-09 15:05:00.299  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.299  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.299  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.299  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.299  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:05:00.299  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.300  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.300  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.300  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.300  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.300  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.300  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.300  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.300  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.301  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.301  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.301  3366  3413 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-09 15:05:00.302  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.302  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.302  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.302  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.302  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.302  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.302  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.302  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.302  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.302  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.302  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.303  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.303  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.303  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.303  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.303  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.303  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.303  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.304  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-09 15:05:00.304  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.304  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.304  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.305  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.305  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.305  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.305  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.305  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.305  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.305  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.305  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.305  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.305  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.305  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.305  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.306  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.306  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.306  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.306  3366  3413 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-09 15:05:00.306  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.306  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.306  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.307  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.307  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.307  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.307  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.307  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.307  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.307  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.307  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.307  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.307  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.307  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.307  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.308  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.308  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.308  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
,08-09 15:05:00.308  3366  3413 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-09 15:05:00.308  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.308  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.308  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.309  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.309  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.309  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.309  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.309  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.309  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.309  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.309  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.309  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.309  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.309  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.310  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.310  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.310  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.310  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.310  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-09 15:05:00.311  3366  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 15:05:00.311  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 15:05:00.311  3366  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 15:05:00.311  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-09 15:05:00.311  3366  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 15:05:00.311  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.311  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.311  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.311  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.311  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.312  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.312  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.312  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.312  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.312  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.312  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.312  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.312  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.312  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.313  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.313  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.313  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.313  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.313  3366  3413 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 15:05:00.314  3366  3413 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-09 15:05:00.314  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-09 15:05:00.317  3366  3413 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 15:05:00.317  3366  3413 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-09 15:05:00.317  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-09 15:05:00.317  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-09 15:05:00.317  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-09 15:05:00.317  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-09 15:05:00.317  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-09 15:05:00.317  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-09 15:05:00.317  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-09 15:05:00.317  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-09 15:05:00.317  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-09 15:05:00.317  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-09 15:05:00.317  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-09 15:05:00.317  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-09 15:05:00.318  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-09 15:05:00.318  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-09 15:05:00.318  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-09 15:05:00.318  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-09 15:05:00.318  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-09 15:05:00.318  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-09 15:05:00.318  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-09 15:05:00.318  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-09 15:05:00.318  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-09 15:05:00.318  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-09 15:05:00.318  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-09 15:05:00.318  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-09 15:05:00.318  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-09 15:05:00.319  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-09 15:05:00.319  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-09 15:05:00.319  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-09 15:05:00.319  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-09 15:05:00.319  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-09 15:05:00.319  3366  3413 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-09 15:05:00.319  3366  3413 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 15:05:00.319  3366  3413 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-09 15:05:00.319  3366  3413 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 15:05:00.319  3366  3413 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 15:05:00.320  3366  3413 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-09 15:05:00.320  3366  3413 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 15:05:00.320  3366  3413 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 15:05:00.320  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-09 15:05:00.321  3366  3413 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-09 15:05:00.321  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-09 15:05:00.322  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-09 15:05:00.322  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-09 15:05:00.323  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-09 15:05:00.323  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-09 15:05:00.323  3366  3413 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-09 15:05:00.323  3366  3413 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 15:05:00.323  3366  3413 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-09 15:05:00.324  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.324  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.324  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.324  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.324  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.324  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.324  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-09 15:05:00.328  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.328  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.328  3366  3416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 354)
08-09 15:05:00.328  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.328  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.328  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.328  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.328  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.328  3366  3416 E BluetoothDevice: Bluetooth is not enabled
08-09 15:05:00.328  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.329  3366  3416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 354)
08-09 15:05:00.329  3366  3416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 354)
08-09 15:05:00.329  3366  3416 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 354)
08-09 15:05:00.329  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.329  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.329  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.329  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.330  3366  3366 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
08-09 15:05:00.330  3366  3413 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-09 15:05:00.330  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.330  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.330  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.330  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.331  3366  3366 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
08-09 15:05:00.331  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.331  3366  3366 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 15:05:00.331  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.331  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.331  3366  3366 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 15:05:00.331  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.331  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.331  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.331  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.331  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.331  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.331  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.331  3366  3416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 354
08-09 15:05:00.331  3366  3416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 354)
08-09 15:05:00.332  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.332  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.332  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.332  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.332  3366  3413 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-09 15:05:00.333  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.333  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.333  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.333  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.333  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.333  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.333  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.333  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.333  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.333  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.333  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.333  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.333  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.334  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.334  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.334  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.334  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.335  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.335  3366  3413 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-09 15:05:00.335  3366  3413 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-09 15:05:00.335  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 15:05:00.335  3366  3413 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-09 15:05:00.336  3366  3413 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-09 15:05:00.336  3366  3413 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-09 15:05:00.336  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 15:05:00.336  3366  3413 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-09 15:05:00.336  3366  3413 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-09 15:05:00.336  3366  3413 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-09 15:05:00.336  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 15:05:00.336  3366  3413 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-09 15:05:00.336  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.336  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.336  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.336  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.337  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.337  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.337  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.337  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.337  3366  3417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 354
08-09 15:05:00.338  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.338  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.338  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.338  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.338  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.339  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.339  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.339  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.339  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.339  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.340  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.340  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.340  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.340  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.340  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.340  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.340  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.340  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.340  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.340  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.340  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.341  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.341  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.341  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.341  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.341  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.341  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.341  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.341  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.341  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.341  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 15:05:00.341  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.341  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.341  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.341  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.342  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.342  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.342  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.342  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.342  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.342  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.342  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.342  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.343  3366  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-09 15:05:00.344  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 15:05:00.344  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-09 15:05:00.344  3366  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-09 15:05:00.344  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 15:05:00.344  3366  3366 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-09 15:05:00.344  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.344  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-09 15:05:00.344  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.344  3366  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-09 15:05:00.345  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.345  3366  3366 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-09 15:05:00.345  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.345  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 15:05:00.345  3366  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 15:05:00.345  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 15:05:00.345  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.345  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.345  3366  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 15:05:00.346  3366  3366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:05:00.346  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.346  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.346  3366  3366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:05:00.346  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.346  3366  3366 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 15:05:00.346  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.346  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.346  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.346  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.346  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.346  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.346  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.346  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.346  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.346  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.346  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.347  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.347  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.347  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.347  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.347  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.348  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-09 15:05:00.349  3366  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 15:05:00.349  3366  3413 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-09 15:05:00.349  3366  3413 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-09 15:05:00.349  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 15:05:00.350  3366  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 15:05:00.350  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.350  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.350  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.350  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.350  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.350  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.352  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.352  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.352  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.352  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.352  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.352  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.352  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.352  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.354  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.354  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.354  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.354  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.356  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.356  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.356  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.356  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.356  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.356  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.356  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.356  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.356  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.357  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.357  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.357  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.357  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.357  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.357  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.357  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.357  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.357  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.358  3366  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:05:00.358  3366  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:05:00.358  3366  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:05:00.358  3366  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:05:00.358  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.358  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.358  3366  3413 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4973fa not in the list
08-09 15:05:00.358  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.359  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.359  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:05:00.359  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.359  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.359  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:05:00.359  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 15:05:00.359  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:05:00.359  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:05:00.359  3366  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:05:00.359  3366  3413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f8bdab not in the list
08-09 15:05:00.360  3366  3413 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-09 15:05:00.360  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 15:05:00.360  3366  3413 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-09 15:05:00.360  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 15:05:00.360  3366  3413 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-09 15:05:00.361  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 15:05:00.362  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-09 15:05:00.362  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-09 15:05:00.363  3366  3413 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-09 15:05:00.363  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-09 15:05:00.363  3366  3413 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-09 15:05:00.363  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-09 15:05:00.363  3366  3413 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-09 15:05:00.363  3366  3413 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-09 15:05:00.364  3366  3413 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-09 15:05:00.364  3366  3413 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-09 15:05:00.364  3366  3413 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-09 15:05:00.364  3366  3413 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-09 15:05:00.364  3366  3413 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-09 15:05:00.365  3366  3413 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-09 15:05:00.365  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:05:00.365  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d78b4dd added. We now have 2 listener(s)
08-09 15:05:00.365  3366  3413 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 15:05:00.368   873  1379 D WifiService: setWifiEnabled: true pid=3366, uid=10000
08-09 15:05:00.368   873  1379 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-09 15:05:00.371  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:05:00.371  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener ,io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36e8852 added. We now have 3 listener(s)
08-09 15:05:00.371  3366  3413 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 15:05:00.371  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.371  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.372  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:05:00.372  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5053723 added. We now have 4 listener(s)
08-09 15:05:00.372  3366  3413 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 15:05:00.373  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:05:00.373  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2175420 added. We now have 5 listener(s)
08-09 15:05:00.373  3366  3413 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 15:05:00.374   873  1910 D WifiService: setWifiEnabled: false pid=3366, uid=10000
08-09 15:05:00.374   873  1910 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-09 15:05:00.383   873   890 I ActivityManager: Start proc 3421:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
08-09 15:05:00.383   873  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-09 15:05:00.387  3366  3366 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.387  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:00.387  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:00.387  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:05:00.387  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:05:00.387  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:05:00.387  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:00.387  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:00.387  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:05:00.387  3366  3366 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.387  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:05:00.401   873   886 I ActivityManager: Start proc 3432:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-09 15:05:00.404  3366  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 15:05:00.405   873  1315 D WifiConfigStore: loaded 0 passpoint configs
08-09 15:05:00.405  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.405   873  1315 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-09 15:05:00.405  3366  3413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:05:00.405  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:00.405  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:05:00.405  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:05:00.405  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:05:00.405  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:00.405  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:00.405  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:05:00.405  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.405  3366  3413 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:05:00.406   873  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-09 15:05:00.406  3366  3413 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 15:05:00.406   873  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-09 15:05:00.406  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:05:00.407   873  1315 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
08-09 15:05:00.408   873  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-09 15:05:00.408   873  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 3
08-09 15:05:00.408   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-09 15:05:00.409   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-09 15:05:00.409   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "ktwtestwifi"WPA_EAP
,08-09 15:05:00.461  3432  3432 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-09 15:05:00.470   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-09 15:05:00.471   372   871 D CommandListener: Setting iface cfg
,08-09 15:05:00.471   873  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
08-09 15:05:00.471   873  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-09 15:05:00.472   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 3
,08-09 15:05:00.484   873  1315 E native  : do suspend true
,08-09 15:05:00.488  3421  3421 D AdapterServiceConfig: Adding HeadsetService
,08-09 15:05:00.488  3421  3421 D AdapterServiceConfig: Adding A2dpService
08-09 15:05:00.488  3421  3421 D AdapterServiceConfig: Adding HidService
08-09 15:05:00.489  3421  3421 D AdapterServiceConfig: Adding HealthService
,08-09 15:05:00.489  3421  3421 D AdapterServiceConfig: Adding PanService
08-09 15:05:00.489  3421  3421 D AdapterServiceConfig: Adding GattService
08-09 15:05:00.489  3421  3421 D AdapterServiceConfig: Adding BluetoothMapService
,08-09 15:05:00.492   873  1314 D WifiNative-HAL: p2pGetDeviceAddress
,08-09 15:05:00.492   873  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-09 15:05:00.515  1479  1479 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
08-09 15:05:00.515  1479  1479 W wpa_supplicant: wlan0: Failed to initiate AP scan
,08-09 15:05:00.516   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 15:05:00.519  3366  3366 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.519  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:00.519  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:00.519  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:05:00.519  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:00.519  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:05:00.519  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:00.519  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:00.519  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:05:00.519  3366  3366 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.519  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:05:00.520  3366  3366 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:05:00.520  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:00.520  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:00.520  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:05:00.520  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:00.520  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:05:00.520  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:00.520  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:00.520  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:05:00.520  3366  3366 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:00.520  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:05:00.521  1860  2069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 15:05:00.522   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cdfd775:true
08-09 15:05:00.522  3421  3421 D BluetoothAdapterState: make() - Creating AdapterState
,08-09 15:05:00.525  3421  3421 I bt_bluedroid: init
,08-09 15:05:00.525  3421  3455 I BluetoothAdapterState: Entering OffState
,08-09 15:05:00.528  3421  3456 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-09 15:05:00.528  3432  3432 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-09 15:05:00.529  3421  3456 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-09 15:05:00.529  3421  3456 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-09 15:05:00.529  3421  3456 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-09 15:05:00.531  3421  3421 I bt_bluedroid: get_profile_interface socket
,08-09 15:05:00.533  3421  3421 I bt_bluedroid: get_profile_interface sdp
,08-09 15:05:00.533  3421  3460 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 15:05:00.534  3421  3460 D BluetoothAdapterProperties: Name is: Nexus 6
,08-09 15:05:00.535  3421  3437 I bt_bluedroid: config_hci_snoop_log
,08-09 15:05:00.536   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-09 15:05:00.542  3421  3455 D BluetoothAdapterState: Current state: OFF, message: 0
,08-09 15:05:00.542  3421  3455 D BluetoothAdapterProperties: Setting state to 14
08-09 15:05:00.542  3421  3455 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-09 15:05:00.544  3421  3455 D BluetoothBondStateMachine: make
,08-09 15:05:00.546  3421  3463 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-09 15:05:00.550  3421  3455 I BluetoothAdapterState: Entering PendingCommandState
,08-09 15:05:00.550  3421  3421 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-09 15:05:00.551   873  1379 I ActivityManager: Killing 2683:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-09 15:05:00.552  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
08-09 15:05:00.552  3421  3421 D BtGatt.DebugUtils: handleDebugAction() action=null
08-09 15:05:00.553  3421  3421 D BtGatt.GattService: Received start request. Starting profile...
08-09 15:05:00.553  3421  3421 D BtGatt.GattService: start()
08-09 15:05:00.553  3421  3421 I bt_bluedroid: get_profile_interface gatt
,08-09 15:05:00.553  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
08-09 15:05:00.554  3421  3421 D BtGatt.AdvertiseManager: advertise manager created
,08-09 15:05:00.583  3421  3421 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:05:00.583  3421  3421 V BluetoothAdapterState: isTurningOn()=false
08-09 15:05:00.583  3421  3421 V BluetoothAdapterState: isBleTurningOn()=true
08-09 15:05:00.583  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:05:00.584  3421  3455 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-09 15:05:00.584  3421  3455 I bt_bluedroid: enable
08-09 15:05:00.584  3421  3456 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-09 15:05:00.585  3421  3456 I bt_hci  : start_up
,08-09 15:05:00.597  3421  3456 I bt_vendor: alloc value 0xb39b0189
08-09 15:05:00.597  3421  3456 I bt_vendor: init
08-09 15:05:00.597  3421  3456 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-09 15:05:00.597  3421  3456 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-09 15:05:00.701  3421  3456 D bt_hci  : start_up starting async portion
,08-09 15:05:00.703  3421  3466 I bt_hci  : event_finish_startup
08-09 15:05:00.704  3421  3466 I bt_hci_h4: hal_open
08-09 15:05:00.704  3421  3466 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-09 15:05:00.713  3421  3466 I bt_userial_vendor: device fd = 51 open
,08-09 15:05:00.746  3421  3466 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 15:05:00.778  3421  3466 D bt_hwcfg: Chipset BCM4354A2
,08-09 15:05:00.778  3421  3466 D bt_hwcfg: Target name = [BCM4354A2]
08-09 15:05:00.779  3421  3466 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-09 15:05:00.846  3366  3366 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 15:05:01.630  3421  3466 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-09 15:05:01.631  3421  3466 D bt_hwcfg: Settlement delay -- 100 ms
,08-09 15:05:01.632  3421  3466 I bt_hwcfg: Setting fw settlement delay to 100 
,08-09 15:05:01.749  3421  3466 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 15:05:01.751  3421  3466 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-09 15:05:01.779  3421  3466 I bt_hwcfg: vendor lib fwcfg completed
,08-09 15:05:01.779  3421  3466 I bt_vendor: firmware callback
08-09 15:05:01.780  3421  3466 I bt_hci  : firmware_config_callback
,08-09 15:05:01.792  3421  3468 I bt_btu  : btu_task pending for preload complete event
,08-09 15:05:01.793  3421  3468 I bt_btu_task: Bluetooth chip preload is complete
,08-09 15:05:01.793  3421  3468 I bt_btu  : btu_task received preload complete event
,08-09 15:05:01.803  3421  3468 I         : BTE_InitTraceLevels -- TRC_HCI
,08-09 15:05:01.803  3421  3468 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-09 15:05:01.804  3421  3468 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-09 15:05:01.804  3421  3468 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-09 15:05:01.804  3421  3468 I         : BTE_InitTraceLevels -- TRC_AVRC
08-09 15:05:01.805  3421  3468 I         : BTE_InitTraceLevels -- TRC_A2D
,08-09 15:05:01.805  3421  3468 I         : BTE_InitTraceLevels -- TRC_BNEP
08-09 15:05:01.805  3421  3468 I         : BTE_InitTraceLevels -- TRC_BTM
08-09 15:05:01.805  3421  3468 I         : BTE_InitTraceLevels -- TRC_GAP
08-09 15:05:01.806  3421  3468 I         : BTE_InitTraceLevels -- TRC_PAN
,08-09 15:05:01.806  3421  3468 I         : BTE_InitTraceLevels -- TRC_SDP
08-09 15:05:01.806  3421  3468 I         : BTE_InitTraceLevels -- TRC_GATT
08-09 15:05:01.807  3421  3468 I         : BTE_InitTraceLevels -- TRC_SMP
08-09 15:05:01.807  3421  3468 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-09 15:05:01.807  3421  3468 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-09 15:05:01.954  3421  3468 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392dd9d
08-09 15:05:01.954  3421  3468 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392dd9d 
,08-09 15:05:01.966  3421  3460 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-09 15:05:01.968  3421  3460 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-09 15:05:01.969  3421  3460 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-09 15:05:01.972  3421  3460 D BluetoothAdapterProperties: Name is: Nexus 6
,08-09 15:05:01.975  3421  3460 D BluetoothAdapterProperties: Scan Mode:20
,08-09 15:05:01.976  3421  3460 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-09 15:05:01.976  3421  3460 D bt_hci  : do_postload posting postload work item
,08-09 15:05:01.977  3421  3466 I bt_hci  : event_postload
,08-09 15:05:01.977  3421  3466 I bt_vendor: sco_config_cb
08-09 15:05:01.977  3421  3466 I bt_hci  : sco_config_callback postload finished.
,08-09 15:05:01.984  3421  3460 D bt_bte_conf: Device ID record 1 : primary
08-09 15:05:01.984  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:05:01.985  3421  3460 D bt_bte_conf:   vendorId            = 000f
,08-09 15:05:01.985  3421  3460 D bt_bte_conf:   vendorIdSource      = 0001
08-09 15:05:01.986  3421  3460 D bt_bte_conf:   product             = 1200
,08-09 15:05:01.986  3421  3460 D bt_bte_conf:   version             = 1436
,08-09 15:05:01.987  3421  3460 D bt_bte_conf:   clientExecutableURL = 
08-09 15:05:01.987  3421  3460 D bt_bte_conf:   serviceDescription  = 
08-09 15:05:01.987  3421  3460 D bt_bte_conf:   documentationURL    = ,
08-09 15:05:01.987  3421  3466 I bt_vendor: low_power_mode_cb
08-09 15:05:01.988  3421  3460 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-09 15:05:01.988  3421  3456 D bt_stack_manager: event_start_up_stack finished
,08-09 15:05:01.988  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:05:01.990  3421  3455 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-09 15:05:01.991  3421  3455 D BluetoothAdapterProperties: Setting state to 15
08-09 15:05:01.991  3421  3455 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-09 15:05:01.992  3421  3455 I BluetoothAdapterState: Entering BleOnState
,08-09 15:05:01.998  3421  3455 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-09 15:05:01.998  3421  3455 D BluetoothAdapterProperties: Setting state to 11
,08-09 15:05:01.998  3421  3455 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-09 15:05:02.003  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
,08-09 15:05:02.003  3421  3421 D HeadsetService: Received start request. Starting profile...
,08-09 15:05:02.008  3421  3421 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 15:05:02.008  3421  3421 D HeadsetStateMachine: make
,08-09 15:05:02.016  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:05:02.017  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:05:02.033   873   886 I ActivityManager: Start proc 3476:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-09 15:05:02.035  3421  3455 I BluetoothAdapterState: Entering PendingCommandState
,08-09 15:05:02.036  3421  3421 D HeadsetStateMachine: max_hf_connections = 1
,08-09 15:05:02.036  3421  3421 I bt_bluedroid: get_profile_interface handsfree
,08-09 15:05:02.036  3421  3460 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-09 15:05:02.039  3421  3460 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-09 15:05:02.040  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
,08-09 15:05:02.041   873   873 D BluetoothA2dp: Proxy object connected
08-09 15:05:02.042  3421  3421 D A2dpService: Received start request. Starting profile...
08-09 15:05:02.042  3421  3421 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-09 15:05:02.043  3421  3421 I bt_bluedroid: get_profile_interface avrcp
,08-09 15:05:02.048  3421  3421 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-09 15:05:02.049  3421  3421 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-09 15:05:02.049  3421  3421 D A2dpStateMachine: make
,08-09 15:05:02.050  3421  3421 I bt_bluedroid: get_profile_interface a2dp
,08-09 15:05:02.052  3421  3460 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-09 15:05:02.052  3421  3421 I BluetoothHidServiceJni: classInitNative: succeeds
,08-09 15:05:02.053  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
08-09 15:05:02.054  3421  3489 D A2dpStateMachine: Enter Disconnected: -2
,08-09 15:05:02.055  3421  3421 D HidService: Received start request. Starting profile...
,08-09 15:05:02.055  1373  1373 D BluetoothInputDevice: Proxy object connected
08-09 15:05:02.055  3421  3421 I bt_bluedroid: get_profile_interface hidhost
08-09 15:05:02.055  3421  3421 D HidService: setHidService(): set to: null
08-09 15:05:02.055  3421  3460 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390f3e5
08-09 15:05:02.055  3421  3460 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-09 15:05:02.055  1373  1373 D HidProfile: Bluetooth service connected
,08-09 15:05:02.056  3421  3421 I BluetoothHealthServiceJni: classInitNative: succeeds
08-09 15:05:02.056  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
08-09 15:05:02.057  3421  3421 D HealthService: Received start request. Starting profile...
08-09 15:05:02.058  3421  3421 I bt_bluedroid: get_profile_interface health
08-09 15:05:02.058  3421  3421 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-09 15:05:02.059  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
08-09 15:05:02.060  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 15:05:02.060  1373  1373 D PanProfile: Bluetooth service connected
08-09 15:05:02.061  3421  3421 D PanService: Received start request. Starting profile...
08-09 15:05:02.061  3421  3421 D BluetoothPanServiceJni: initializeNative(L110): pan
08-09 15:05:02.061  3421  3421 I bt_bluedroid: get_profile_interface pan
08-09 15:05:02.062  3421  3460 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-09 15:05:02.066  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
,08-09 15:05:02.070  1373  1373 D BluetoothMap: Proxy object connected
,08-09 15:05:02.070  1373  1373 D MapProfile: Bluetooth service connected
,08-09 15:05:02.070  1373  1373 D BluetoothMap: getConnectedDevices()
08-09 15:05:02.071  3421  3421 D BluetoothMapService: Received start request. Starting profile...
08-09 15:05:02.071  3421  3421 D BluetoothMapService: start()
,08-09 15:05:02.072  1373  1373 D BluetoothMap: Bluetooth is Not enabled
,08-09 15:05:02.074  3421  3421 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-09 15:05:02.074  3421  3421 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-09 15:05:02.074  3421  3421 D BluetoothMapAppObserver: createReceiver()
,08-09 15:05:02.075  3421  3421 D BluetoothMapAppObserver: initObservers()
,08-09 15:05:02.075  3421  3421 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-09 15:05:02.080  3421  3421 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:05:02.080  3421  3421 V BluetoothAdapterState: isTurningOn()=true
08-09 15:05:02.080  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:02.081  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:05:02.083  3421  3421 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:05:02.083  3421  3421 V BluetoothAdapterState: isTurningOn()=true
08-09 15:05:02.083  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:02.083  3421  3474 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-09 15:05:02.083  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:02.083  3421  3421 V BluetoothAdapterState: isTurningOff()=false
08-09 15:05:02.083  3421  3421 V BluetoothAdapterState: isTurningOn()=true
08-09 15:05:02.083  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:05:02.083  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:02.084  3421  3421 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:05:02.084  3421  3421 V BluetoothAdapterState: isTurningOn()=true
08-09 15:05:02.084  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:02.084  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:02.084  3421  3421 V BluetoothAdapterState: isTurningOff()=false
08-09 15:05:02.084  3421  3421 V BluetoothAdapterState: isTurningOn()=true
08-09 15:05:02.084  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:02.084  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:02.084  3421  3421 V BluetoothAdapterState: isTurningOff()=false
08-09 15:05:02.084  3421  3421 V BluetoothAdapterState: isTurningOn()=true
,08-09 15:05:02.084  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:02.084  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:02.085  3421  3455 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-09 15:05:02.085  3421  3455 D BluetoothAdapterProperties: ScanMode =  20
,08-09 15:05:02.085  3421  3455 D BluetoothAdapterProperties: State =  11
08-09 15:05:02.085  3421  3455 D BluetoothAdapterProperties: Setting state to 12
08-09 15:05:02.085  3421  3455 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-09 15:05:02.085  3421  3455 I BluetoothAdapterState: Entering OnState
08-09 15:05:02.086  1373  1390 D BluetoothPbap: onBluetoothStateChange: up=true
08-09 15:05:02.086  3421  3460 D BluetoothAdapterProperties: Scan Mode:21
08-09 15:05:02.087  3421  3460 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-09 15:05:02.087   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 15:05:02.087   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:05:02.088  3366  3366 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-09 15:05:02.090  3366  3366 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-09 15:05:02.091  1373  1835 D BluetoothMap: onBluetoothStateChange: up=true
08-09 15:05:02.091  1373  1393 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-09 15:05:02.092   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 15:05:02.092   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:05:02.092  1373  1390 D BluetoothPan: onBluetoothStateChange on: true
08-09 15:05:02.092  3366  3366 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-09 15:05:02.093  1744  1765 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:05:02.095  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:02.095  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:02.095  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:05:02.095  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:02.095  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:05:02.095  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:02.095  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:02.095  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:05:02.096   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-09 15:05:02.096  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:05:02.096  3421  3421 D BluetoothMapService: onReceive
08-09 15:05:02.096  3421  3421 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 15:05:02.097  3421  3421 D BluetoothMapService: STATE_ON
,08-09 15:05:02.099  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:02.099  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:02.099  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:05:02.099  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:02.099  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:05:02.099  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:02.099  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:02.099  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:05:02.100  3421  3421 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-09 15:05:02.101  3421  3421 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-09 15:05:02.101  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:05:02.102  1373  1678 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-09 15:05:02.102  3421  3421 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 15:05:02.102  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:05:02.103  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:05:02.104  3421  3421 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 15:05:02.105  1373  1373 D BluetoothA2dp: Proxy object connected
,08-09 15:05:02.106  3421  3421 D ObexServerSockets: Succeed to create listening sockets 
08-09 15:05:02.107  3421  3421 D ObexServerSockets0: startAccept()
08-09 15:05:02.107  3421  3421 D ObexServerSockets0: prepareForNewConnect()
08-09 15:05:02.107  1373  1678 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-09 15:05:02.108  3476  3476 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-09 15:05:02.109  3421  3421 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-09 15:05:02.109  3421  3421 D BluetoothSdpJni: SDP Create record success - handle: 0
08-09 15:05:02.110  3421  3495 D ObexServerSockets0: Accepting socket connection...
08-09 15:05:02.110  3421  3496 D ObexServerSockets0: Accepting socket connection...
,08-09 15:05:02.117  3421  3421 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-09 15:05:02.117  3421  3421 D ObexServerSockets0: prepareForNewConnect()
08-09 15:05:02.118   873  1794 I ActivityManager: Killing 2812:com.google.android.gm/u0a78 (adj 15): empty #17
,08-09 15:05:02.181  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 15:05:02.190   873   890 D BluetoothHeadset: Proxy object connected
,08-09 15:05:02.192   873   890 D BluetoothHeadset: Proxy object connected
,08-09 15:05:02.192   873   890 D BluetoothHeadset: Proxy object connected
08-09 15:05:02.194   873  1379 I ActivityManager: Start proc 3497:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-09 15:05:02.196  1744  1756 D BluetoothHeadset: Proxy object connected
,08-09 15:05:02.209  1373  1835 D BluetoothHeadset: Proxy object connected
,08-09 15:05:02.210  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-09 15:05:02.265  3497  3497 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-09 15:05:02.406  3497  3497 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at java.io.File.exists(File.java:361)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 15:05:02.406  3497  3497 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 15:05:02.406  3497  3497 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:05:02.406  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 15:05:02.407  3497  3497 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.r.k.d(PG:1187)
,08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.r.e.b(PG:170)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 15:05:02.407  3497  3497 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.r.k.d(PG:583)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.r.e.b(PG:170)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.shared.i,.h.a(PG:251)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 15:05:02.407  3497  3497 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.io.File.exists(File.java:361)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(Act,ivityThread.java:1405)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 15:05:02.407  3497  3497 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.io.File.exists(File.java:361)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 15:05:02.407  3497  3497 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:05:02.407  3497  3497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 15:05:02.415  3476  3476 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-09 15:05:02.445   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6e0254b:true
,08-09 15:05:02.456  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 15:05:02.465  3476  3476 D LocalBluetoothProfileManager: Adding local A2DP profile
08-09 15:05:02.471  3476  3476 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-09 15:05:02.482  1373  1373 D BluetoothPbap: Proxy object connected
08-09 15:05:02.482  1373  1373 D PbapServerProfile: Bluetooth service connected
,08-09 15:05:02.498  3476  3476 D LocalBluetoothProfileManager: Adding local MAP profile
,08-09 15:05:02.499  3476  3476 D BluetoothMap: Create BluetoothMap proxy object
,08-09 15:05:02.511  3421  3525 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 15:05:02.517  3476  3476 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-09 15:05:02.528  3421  3531 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 15:05:02.528  3476  3476 D DockEventReceiver: finishStartingService: stopping service
08-09 15:05:02.529  3476  3476 D BluetoothA2dp: Proxy object connected
08-09 15:05:02.529  3421  3531 I BtOppRfcommListener: Accept thread started.
08-09 15:05:02.531  3476  3476 D BluetoothInputDevice: Proxy object connected
08-09 15:05:02.531  3476  3476 D HidProfile: Bluetooth service connected
,08-09 15:05:02.534  3476  3476 D BluetoothPan: BluetoothPAN Proxy object connected
,08-09 15:05:02.535  3476  3476 D PanProfile: Bluetooth service connected
08-09 15:05:02.535  3476  3476 D BluetoothMap: Proxy object connected
08-09 15:05:02.535  3476  3476 D MapProfile: Bluetooth service connected
08-09 15:05:02.535  3476  3476 D BluetoothMap: getConnectedDevices()
,08-09 15:05:02.537  3476  3476 D BluetoothPbap: Proxy object connected
,08-09 15:05:02.538  3476  3476 D PbapServerProfile: Bluetooth service connected
08-09 15:05:02.539   873  1701 I ActivityManager: Killing 3007:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-09 15:05:02.574  3476  3487 D BluetoothHeadset: Proxy object connected
,08-09 15:05:02.575  3476  3476 D HeadsetProfile: Bluetooth service connected
,08-09 15:05:02.683  3497  3513 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-09 15:05:02.709   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e530346:true
,08-09 15:05:03.410   873   884 D WifiService: setWifiEnabled: true pid=3366, uid=10000
,08-09 15:05:03.411   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 15:05:03.422   873  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-09 15:05:03.438  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:03.438  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:03.438  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:05:03.438  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:05:03.438  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:05:03.438  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:03.438  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:03.438  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:05:03.444  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:05:03.453  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:03.453  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:03.453  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:05:03.453  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:05:03.453  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:05:03.453  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:03.453  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:03.453  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:05:03.456  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:05:03.467   873  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-09 15:05:03.467   873  1315 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-09 15:05:03.468   873  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-09 15:05:03.470   873  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-09 15:05:03.471   873  1315 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,08-09 15:05:03.473   873  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-09 15:05:03.473   873  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 3
,08-09 15:05:03.473   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-09 15:05:03.474   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-09 15:05:03.474   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "ktwtestwifi"WPA_EAP
08-09 15:05:03.475  1479  1479 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-09 15:05:03.554   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-09 15:05:03.554   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 3
,08-09 15:05:03.556   372   871 D CommandListener: Setting iface cfg
,08-09 15:05:03.558   873  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '36 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 36 Failed to set address (No such device)'
,08-09 15:05:03.558   873  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-09 15:05:03.558  1479  1479 E wpa_supplicant: PNO: In assoc process
,08-09 15:05:03.559   873  1315 E WifiStateMachine:  Fail to set up pno, want true now false
,08-09 15:05:03.566   873  1314 D WifiNative-HAL: p2pGetDeviceAddress
08-09 15:05:03.567   873  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-09 15:05:03.567   873  1315 E native  : do suspend true
,08-09 15:05:03.603   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 15:05:03.935  1479  1479 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-09 15:05:03.973  1479  1479 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-09 15:05:03.973  1479  1479 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-09 15:05:03.981   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 15:05:04.001   873  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-09 15:05:04.001   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 15:05:04.002   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-09 15:05:04.031   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-09 15:05:04.044   372   871 D CommandListener: Setting iface cfg
,08-09 15:05:04.058   873  1315 D WifiStateMachine: Start Dhcp Watchdog 1
,08-09 15:05:04.069   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-09 15:05:04.122   873  3542 D DhcpClient: Receive thread started
,08-09 15:05:04.212   873  1315 E native  : do suspend false
,08-09 15:05:04.238   873  3541 D DhcpClient: Broadcasting DHCPDISCOVER
,08-09 15:05:04.254   873  3542 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 170909, domain null
,08-09 15:05:04.258   873  3541 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 170909 seconds
,08-09 15:05:04.264   873  3541 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-09 15:05:04.277   873  3542 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-09 15:05:04.278   873  3541 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-09 15:05:04.285   372   871 D CommandListener: Setting iface cfg
,08-09 15:05:04.296   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-09 15:05:04.297   873  1315 E native  : do suspend true
,08-09 15:05:04.297   873  3541 D DhcpClient: Scheduling renewal in 86399s
,08-09 15:05:04.310   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-09 15:05:04.311   873  1315 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-09 15:05:04.311   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-09 15:05:04.318   873  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-09 15:05:04.319   873  1317 D ConnectivityService: Adding iface wlan0 to network 100
,08-09 15:05:04.358   873  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-09 15:05:04.359   873  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-09 15:05:04.363   873  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-09 15:05:04.365   873  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-09 15:05:04.368   873  1317 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-09 15:05:04.384   873  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-09 15:05:04.389   873  1317 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-09 15:05:04.389   873  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,08-09 15:05:04.390   873  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-09 15:05:04.391   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-09 15:05:04.392   873  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,08-09 15:05:04.392   873  1317 D ConnectivityService:    accepting network in place of null
,08-09 15:05:04.395   873  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-09 15:05:04.429   873  3540 D NetlinkSocketObserver: NeighborEvent{elapsedMs=355568, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 15:05:04.441   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 15:05:04.476   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 15:05:04.483   873  1317 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-09 15:05:04.498   873  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-09 15:05:04.499   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-09 15:05:04.509   873  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-09 15:05:04.509   873  3539 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.46,2a00:1450:4001:813::200e
08-09 15:05:04.516   873   890 D Tethering: MasterInitialState.processMessage what=3
08-09 15:05:04.521   873  1402 V BackupManagerService: Scheduling immediate backup pass
08-09 15:05:04.526  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:04.526  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:04.526  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:05:04.526  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:05:04.526  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:05:04.526  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 15:05:04.526  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 15:05:04.526  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 15:05:04.529  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 15:05:04.529   873   873 V BackupManagerService: Running a backup pass
08-09 15:05:04.532   873  1334 V BackupManagerService: clearing pending backups
08-09 15:05:04.536  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:04.536  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:04.536  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:05:04.536  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:05:04.536  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:05:04.536  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 15:05:04.536  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 15:05:04.536  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 15:05:04.538  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 15:05:04.540   873  1334 V PerformBackupTask: Beginning backup of 16 targets
,08-09 15:05:04.574   873  1334 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-09 15:05:04.579  1917  1917 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-09 15:05:04.581  1917  1917 D SystemUpdateService: onCreate
,08-09 15:05:04.582   873  1715 D AlarmManagerService: Setting time of day to sec=1470747904
,08-09 15:05:04.426   873  1715 W AlarmManagerService: Unable to set rtc to 1470747904: Invalid argument
08-09 15:05:04.427  1917  1917 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-09 15:05:04.432   873  1334 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,08-09 15:05:04.433  1917  3556 I SystemUpdateService: active receiver: enabled
,08-09 15:05:04.442  1917  3556 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-09 15:05:04.444  1917  3556 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-09 15:05:04.444  1917  3556 I SystemUpdateService: now status is 0 (complete)
08-09 15:05:04.444  1917  3556 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-09 15:05:04.444  1917  3556 I SystemUpdateService: file has been verified
08-09 15:05:04.444  1917  3556 I SystemUpdateService: OTA package size = 12249756
,08-09 15:05:04.446  1917  3556 I SystemUpdateService: showing system update notification
,08-09 15:05:04.463   873  3539 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Aug 2016 13:05:04 GMT], X-Android-Received-Millis=[1470747904461], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470747904577]}
,08-09 15:05:04.464   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-09 15:05:04.465   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-09 15:05:04.465   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-09 15:05:04.466   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-09 15:05:04.488  1917  1917 D SystemUpdateService: onDestroy
,08-09 15:05:04.488   873  1334 I BackupRestoreController: Getting widget state for user: 0
,08-09 15:05:04.502   873  3569 D GpsLocationProvider: NTP server returned: 1470747904426 (Tue Aug 09 15:05:04 GMT+02:00 2016) reference: 355727 certainty: 8 system time offset: -76
,08-09 15:05:04.502   873  3569 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,08-09 15:05:04.524   873   884 I ActivityManager: Start proc 3570:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-09 15:05:04.548  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:05:04.551  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-09 15:05:04.556  3570  3570 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-09 15:05:04.569  1917  3586 I iu.SyncManager: SYNC; picasa accounts
,08-09 15:05:04.573  1917  1917 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-09 15:05:04.574  1917  1917 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-09 15:05:04.575  1860  2064 W GmsBackupTransport: Unknown package in backup request: @pm@
,08-09 15:05:04.582  1917  3585 I MDM     : [190] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-09 15:05:04.582  1917  3585 W BaseAppContext: Using Auth Proxy for data requests.
08-09 15:05:04.585  1917  1917 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-09 15:05:04.586  1917  1917 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-09 15:05:04.587  1860  2064 V GmsBackupTransport: starting performBackup for @pm@
,08-09 15:05:04.592  1917  3585 V GoogleAuthProtoRequest: [190] a.<init>: mAccountName set to: thalitester@gmail.com
,08-09 15:05:04.593  1917  3586 I iu.UploadsManager: num queued entries: 0
,08-09 15:05:04.600   873   883 I ActivityManager: Start proc 3593:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-09 15:05:04.611  1917  3586 I iu.UploadsManager: num updated entries: 0
,08-09 15:05:04.614  1917  3567 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-09 15:05:04.629  3570  3587 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-09 15:05:04.646  1917  3586 I iu.SyncManager: NEXT; no task
,08-09 15:05:04.652  1860  2064 V GmsBackupTransport: performBackup done for @pm@
,08-09 15:05:04.666  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:05:04.672  3432  3566 V GoogleAuthProtoRequest: [286] a.<init>: mAccountName set to: thalitester@gmail.com
,08-09 15:05:04.678  3570  3587 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-09 15:05:04.687  1526  2693 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-09 15:05:04.687  1526  2693 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
08-09 15:05:04.687  1526  2693 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:05:04.687  1526  2693 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:05:04.696  1526  2693 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 15:05:04.696  1526  2693 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 15:05:04.696  1526  2693 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 15:05:04.696  1526  2693 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 15:05:04.696  1526  2693 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 15:05:04.696  1526  2693 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 15:05:04.696  1526  2693 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 15:05:04.701  1860  2099 W GmsBackupTransport: Error sending final backup to server: 
08-09 15:05:04.701  1860  2099 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-09 15:05:04.701  1860  2099 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-09 15:05:04.701  1860  2099 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-09 15:05:04.701  1860  2099 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-09 15:05:04.701  1860  2099 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-09 15:05:04.701  1860  2099 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-09 15:05:04.701  1860  2099 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-09 15:05:04.701  1860  2099 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-09 15:05:04.701  1860  2099 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-09 15:05:04.701  1860  2099 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-09 15:05:04.701  1860  2099 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-09 15:05:04.701  1860  2099 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-09 15:05:04.701  1860  2099 W GmsBackupTransport: 	... 1 more
,08-09 15:05:04.701  3593  3593 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-09 15:05:04.709  3570  3587 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-09 15:05:04.710  1860  1870 I GmsBackupTransport: Next backup will happen in 43199990 millis.
,08-09 15:05:04.711   873  1334 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-09 15:05:04.714  1526  2697 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-09 15:05:04.714  1526  2697 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-09 15:05:04.715  1526  2697 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:05:04.715  1526  2697 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:05:04.715  3593  3593 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-09 15:05:04.727  3593  3593 D SprintDMHelper: simOperator: 
,08-09 15:05:04.727  3593  3593 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-09 15:05:04.728  1917  1917 E ConnectivityChangeReceiver: Ignoring connectivity change
,08-09 15:05:04.741   873  1402 I ActivityManager: Start proc 3616:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-09 15:05:04.758   873  1379 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1917 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-09 15:05:04.774  1917  3585 E MDM     : [190] SitrepService.a: Error sending sitrep.
,08-09 15:05:04.787  1526  2693 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-09 15:05:04.787  1526  2693 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-09 15:05:04.787  1526  2693 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:05:04.787  1526  2693 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:05:04.812  3570  3570 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-09 15:05:04.823   873  1334 I BackupManagerService: Backup pass finished.
,08-09 15:05:04.853  3432  3566 W ExperimentUpdateService: [286] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-09 15:05:04.854  3432  3566 W ExperimentUpdateService: [286] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 15:05:04.854  3432  3566 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 15:05:04.854  3432  3566 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-09 15:05:04.854  3432  3566 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-09 15:05:04.854  3432  3566 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-09 15:05:04.854  3432  3566 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-09 15:05:04.854  3432  3566 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-09 15:05:04.854  3432  3566 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-09 15:05:04.854  3432  3566 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-09 15:05:04.854  3432  3566 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-09 15:05:04.854  3432  3566 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-09 15:05:04.890  3639  3639 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads1267787856.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1267787856.dex
,08-09 15:05:04.910  1917  3568 W DriveInitializer: Awaiting to be initialized,
,08-09 15:05:04.910  1917  3652 W DriveInitializer: Background init thread started
,08-09 15:05:04.970  1917  3652 W DriveInitializer: Background init thread ended
08-09 15:05:04.972  1526  2695 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-09 15:05:04.972  1526  2695 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-09 15:05:04.972  1526  2695 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:05:04.972  1526  2695 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:05:05.003  3570  3570 W InstanceID/Rpc: Found 10011
,08-09 15:05:05.003  3131  3590 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-09 15:05:05.003  3131  3590 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at jdm.a(PG:82)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at jcs.o(PG:406)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at jcn.a(PG:1379)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at jcs.i(PG:143)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at blb.a(PG:3937)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at czp.a(PG:18188)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at czp.a(PG:9081)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at czq.run(PG:1686)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 15:05:05.003  3131  3590 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at jdj.a(PG:4091)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at jdj.a(PG:1125)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at jdm.a(PG:77)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	... 12 more
08-09 15:05:05.003  3131  3590 E HttpOperation: Caused by: faj: BadAuthentication
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at fal.a(PG:38)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	at jdj.a(PG:4089)
08-09 15:05:05.003  3131  3590 E HttpOperation: 	... 14 more
,08-09 15:05:05.024   873  1402 I ActivityManager: Start proc 3678:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider,
,08-09 15:05:05.039  3639  3639 I dex2oat : dex2oat took 149.846ms (threads: 4) arena alloc=294KB java alloc=37KB native alloc=1515KB free=1556KB
,08-09 15:05:05.078   873   885 I ActivityManager: Start proc 3712:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-09 15:05:05.090  3678  3678 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-09 15:05:05.109  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:05:05.119  3712  3712 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-09 15:05:05.133  1526  2693 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 15:05:05.133  1526  2693 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-09 15:05:05.133  1526  2693 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:05:05.133  1526  2693 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:05:05.147  2362  3677 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-09 15:05:05.194  1526  1526 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-09 15:05:05.211  3131  3590 E HttpOperation: [getmobileexperiments] Unexpected exception
08-09 15:05:05.211  3131  3590 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at jdm.a(PG:82)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at jcs.o(PG:406)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at jcn.a(PG:1379)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at jcs.i(PG:143)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at hec.a(PG:42)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at hee.a(PG:102)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at czr.a(PG:65)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at kka.a(PG:108)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at czp.a(PG:19176)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at czp.a(PG:9081)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at czq.run(PG:1686)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 15:05:05.211  3131  3590 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at jdj.a(PG:4091)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at jdj.a(PG:1125)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at jdm.a(PG:77)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	... 15 more
08-09 15:05:05.211  3131  3590 E HttpOperation: Caused by: faj: BadAuthentication
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at fal.a(PG:38)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	at jdj.a(PG:4089)
08-09 15:05:05.211  3131  3590 E HttpOperation: 	... 17 more
,08-09 15:05:05.211  3131  3590 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-09 15:05:05.211  3131  3590 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at jdm.a(PG:82)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at jcs.o(PG:406)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at jcn.a(PG:1379)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at jcs.i(PG:143)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at hec.a(PG:42)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at hee.a(PG:102)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at czr.a(PG:65)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at kka.a(PG:108)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at czp.a(PG:19176)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at czp.a(PG:9081)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at czq.run(PG:1686)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at jdj.a(PG:4091)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at jdj.a(PG:1125)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at jdm.a(PG:77)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	... 15 more
08-09 15:05:05.211  3131  3590 E ExperimentLoader: Caused by: faj: BadAuthentication
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at fal.a(PG:38)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	at jdj.a(PG:4089)
08-09 15:05:05.211  3131  3590 E ExperimentLoader: 	... 17 more
,08-09 15:05:05.363  3712  3712 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-09 15:05:05.371  3712  3712 I BooksApp: Created application version: 3.6.9 (30609)
,08-09 15:05:05.385   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 23632, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-09 15:05:05.386   873  1794 I ActivityManager: Killing 2473:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-09 15:05:05.477  3712  3746 I BooksSync: Starting books sync for 61035162, extras: ade
,08-09 15:05:05.527  1526  3733 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-09 15:05:05.573  3678  3678 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-09 15:05:05.573  3678  3678 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-09 15:05:05.573  3678  3678 I GAv4    :   adb logcat -s GAv4
,08-09 15:05:05.577  2857  3748 V KeepSync: Connecting to GoogleApiClient
,08-09 15:05:05.582   873  1794 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-09 15:05:05.587  3678  3678 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-09 15:05:05.593  3678  3678 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-09 15:05:05.637  3678  3755 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-09 15:05:05.680  1526  2697 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-09 15:05:05.680  1526  2697 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-09 15:05:05.681  1526  2697 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:05:05.681  1526  2697 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:05:05.701  1917  3757 V BaseAuthAsyncOperation: access token request failed
,08-09 15:05:05.703  2857  3748 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-09 15:05:05.804  3678  3678 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-09 15:05:05.877  3678  3678 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-09 15:05:05.889  3678  3678 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 7185-7191)
,08-09 15:05:05.889  3678  3678 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-09 15:05:05.917  3678  3678 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12dd7b7}
08-09 15:05:05.917  3678  3678 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-09 15:05:05.918  3678  3678 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-09 15:05:05.927  3678  3678 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-09 15:05:05.928  3678  3678 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-09 15:05:05.972  3678  3678 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-09 15:05:05.998  3678  3678 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-09 15:05:05.998  3678  3678 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-09 15:05:05.998  3678  3678 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-09 15:05:05.998  3678  3678 I Adreno  : Build Date                       : 10/20/15
08-09 15:05:05.998  3678  3678 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-09 15:05:05.998  3678  3678 I Adreno  : Local Branch                     : M14
08-09 15:05:05.998  3678  3678 I Adreno  : Remote Branch                    : 
08-09 15:05:05.998  3678  3678 I Adreno  : Remote Branch                    : 
08-09 15:05:05.998  3678  3678 I Adreno  : Reconstruct Branch               : 
,08-09 15:05:06.050  3712  3782 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-09 15:05:06.130  1526  2695 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 15:05:06.130  1526  2695 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 15:05:06.131  1526  2695 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:05:06.131  1526  2695 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:05:06.155  3678  3791 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-09 15:05:06.193  3678  3678 I NSApplication: Starting up...
,08-09 15:05:06.224   873  1909 I ActivityManager: Start proc 3797:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-09 15:05:06.225  1526  2697 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-09 15:05:06.225  1526  2697 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-09 15:05:06.226  1526  2697 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 15:05:06.226  1526  2697 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:05:06.242  3712  3782 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-09 15:05:06.250  3712  3746 E BooksSync: Soft error
08-09 15:05:06.250  3712  3746 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 15:05:06.250  3712  3746 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-09 15:05:06.250  3712  3746 E BooksSync: Sync error
08-09 15:05:06.250  3712  3746 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 15:05:06.250  3712  3746 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-09 15:05:06.250  3712  3746 I BooksSync: Finished books sync
,08-09 15:05:06.255   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 23644, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 15:05:06.256   873  1792 I ActivityManager: Killing 3107:android.process.acore/u0a5 (adj 15): empty #17
,08-09 15:05:06.259   873  1402 D WifiService: setWifiEnabled: false pid=3366, uid=10000
,08-09 15:05:06.259   873  1402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 15:05:06.274  1479  1479 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-09 15:05:06.275   873  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-09 15:05:06.275   873  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-09 15:05:06.275   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-09 15:05:06.275   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 15:05:06.281   873  1315 E native  : do suspend true
,08-09 15:05:06.285  3797  3797 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-09 15:05:06.292   873  3541 D DhcpClient: Clearing IP address
,08-09 15:05:06.292   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-09 15:05:06.295   372   871 D CommandListener: Setting iface cfg
,08-09 15:05:06.298  1526  3615 V NativeCrypto: Read error: ssl=0x9a953c00: I/O error during system call, Connection timed out
,08-09 15:05:06.302  1526  3615 V NativeCrypto: SSL shutdown failed: ssl=0x9a953c00: I/O error during system call, Broken pipe
,08-09 15:05:06.302   873  3542 D DhcpClient: Receive thread stopped
,08-09 15:05:06.305  3570  3711 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Failed to fetch settings
08-09 15:05:06.305  3570  3711 E YouTube : izh: java.util.concurrent.ExecutionException: ahm
08-09 15:05:06.305  3570  3711 E YouTube : 	at iyz.a(SourceFile:100)
08-09 15:05:06.305  3570  3711 E YouTube : 	at iza.b(SourceFile:178)
08-09 15:05:06.305  3570  3711 E YouTube : 	at cch.a(SourceFile:2101)
08-09 15:05:06.305  3570  3711 E YouTube : 	at com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask(SourceFile:1033)
08-09 15:05:06.305  3570  3711 E YouTube : 	at com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator.a(SourceFile:65)
08-09 15:05:06.305  3570  3711 E YouTube : 	at evv.run(Unknown Source)
08-09 15:05:06.305  3570  3711 E YouTube : Caused by: java.util.concurrent.ExecutionException: ahm
08-09 15:05:06.305  3570  3711 E YouTube : 	at ain.a(SourceFile:117)
08-09 15:05:06.305  3570  3711 E YouTube : 	at ain.get(SourceFile:88)
08-09 15:05:06.305  3570  3711 E YouTube : 	at kdf.get(SourceFile:69)
08-09 15:05:06.305  3570  3711 E YouTube : 	at iyz.a(SourceFile:98)
08-09 15:05:06.305  3570  3711 E YouTube : 	... 5 more
08-09 15:05:06.305  3570  3711 E YouTube : Caused by: ahm
08-09 15:05:06.305  3570  3711 E YouTube : 	at ahr.a(SourceFile:142)
08-09 15:05:06.305  3570  3711 E YouTube : 	at kcq.a(SourceFile:49)
08-09 15:05:06.305  3570  3711 E YouTube : 	at agx.run(SourceFile:112)
,08-09 15:05:06.307   873  1795 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-09 15:05:06.308   873  3539 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-09 15:05:06.308   873  3539 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.46,2a00:1450:4001:813::200e
08-09 15:05:06.312   873  3539 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:813::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-09 15:05:06.314   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-09 15:05:06.314   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-09 15:05:06.316   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-09 15:05:06.328   873  1795 I ActivityManager: Killing 3230:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-09 15:05:06.322   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-09 15:05:06.329   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-09 15:05:06.330   395   395 E Parcel  : Reading a NULL string not supported here.
08-09 15:05:06.325   873  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-09 15:05:06.332   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-09 15:05:06.332   873  1315 E native  : do suspend true
,08-09 15:05:06.342   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-09 15:05:06.376   873  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-09 15:05:06.379   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 3
,08-09 15:05:06.398   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 15:05:06.400   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 15:05:06.405  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:06.405  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:06.405  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:05:06.405  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:06.405  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:05:06.405  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:06.405  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:06.405  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:05:06.406  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:05:06.407  1860  2069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 15:05:06.411   873  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-09 15:05:06.414  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:06.414  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:06.414  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:05:06.414  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:06.414  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:05:06.414  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:06.414  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:06.414  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:05:06.416  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:05:06.441   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 15:05:06.442   873  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-09 15:05:06.442   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-09 15:05:06.444   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-09 15:05:06.450  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:05:06.451  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:05:06.467  1526  3817 I VacuumService: Vacuum at: now=1470747906467 tag=VacuumService
,08-09 15:05:06.477  1526  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-09 15:05:06.478  1526  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-09 15:05:06.478  1526  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:05:06.478  1526  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:05:06.509  2857  3748 E KeepSync: IOException
08-09 15:05:06.509  2857  3748 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-09 15:05:06.509  2857  3748 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-09 15:05:06.509  2857  3748 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-09 15:05:06.509  2857  3748 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-09 15:05:06.509  2857  3748 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-09 15:05:06.509  2857  3748 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-09 15:05:06.509  2857  3748 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-09 15:05:06.509  2857  3748 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-09 15:05:06.509  2857  3748 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-09 15:05:06.509  2857  3748 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-09 15:05:06.509  2857  3748 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-09 15:05:06.509  2857  3748 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-09 15:05:06.509  2857  3748 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-09 15:05:06.509  2857  3748 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-09 15:05:06.509  2857  3748 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 15:05:06.509  2857  3748 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 15:05:06.509  2857  3748 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-09 15:05:06.509  2857  3748 E KeepSync: 	... 10 more
,08-09 15:05:06.509  2857  3748 W KeepSync: Sync result 2
08-09 15:05:06.510   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-09 15:05:06.511   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-09 15:05:06.555   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 23645, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 15:05:06.557   873  1903 I ActivityManager: Killing 3247:com.android.musicfx/u0a18 (adj 15): empty #17
,08-09 15:05:06.803   873  1402 I ActivityManager: Killing 3035:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-09 15:05:06.892  2362  3826 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-09 15:05:06.939  1917  1917 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-09 15:05:06.942  1917  1917 D SystemUpdateService: onCreate
,08-09 15:05:06.945  1917  1917 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-09 15:05:06.948  1917  3829 I SystemUpdateService: active receiver: enabled
,08-09 15:05:06.950  1917  3829 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-09 15:05:06.951  1917  3829 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-09 15:05:06.953  1917  3829 I SystemUpdateService: now status is 0 (complete)
,08-09 15:05:06.953  1917  3829 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-09 15:05:06.953  1917  3829 I SystemUpdateService: file has been verified
08-09 15:05:06.953  1917  3829 I SystemUpdateService: OTA package size = 12249756
,08-09 15:05:06.958  1917  3829 I SystemUpdateService: showing system update notification
,08-09 15:05:06.966  1917  1917 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-09 15:05:06.973  1917  1917 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-09 15:05:06.977  1917  3586 I iu.UploadsManager: num queued entries: 0
08-09 15:05:06.977  1917  1917 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-09 15:05:06.979  3593  3593 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-09 15:05:06.979  1917  3586 I iu.UploadsManager: num updated entries: 0
,08-09 15:05:06.980  1917  1917 D SystemUpdateService: onDestroy
,08-09 15:05:06.981  1917  3586 I iu.SyncManager: NEXT; no task
08-09 15:05:06.983  3593  3593 D SprintDMHelper: simOperator: 
08-09 15:05:06.983  3593  3593 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-09 15:05:09.270  3421  3455 D BluetoothAdapterState: Current state: ON, message: 23
,08-09 15:05:09.270  3421  3455 D BluetoothAdapterProperties: Setting state to 13
,08-09 15:05:09.271  3421  3455 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-09 15:05:09.272  3421  3455 D BluetoothAdapterProperties: onBluetoothDisable()
08-09 15:05:09.276  3421  3455 I BluetoothAdapterState: Entering PendingCommandState
08-09 15:05:09.282  3421  3421 D BluetoothMapService: onReceive
08-09 15:05:09.282  3421  3421 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-09 15:05:09.283  3421  3421 D BluetoothMapService: STATE_TURNING_OFF
08-09 15:05:09.284  3421  3421 D BluetoothMapService: MAP Service closeService in
08-09 15:05:09.288  3421  3421 D BluetoothMapMasInstance0: MAP Service shutdown
08-09 15:05:09.289  3421  3421 D ObexServerSockets0: shutdown(block = true)
,08-09 15:05:09.290  3421  3495 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-09 15:05:09.291  3421  3460 D BluetoothAdapterProperties: Scan Mode:20
08-09 15:05:09.291  3421  3455 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-09 15:05:09.294  3366  3366 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:09.295  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:09.295  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:09.295  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:05:09.295  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:09.295  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:05:09.295  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:09.295  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:09.295  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:05:09.296  3421  3421 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-09 15:05:09.297  3421  3496 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-09 15:05:09.299  3366  3366 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:09.299  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:05:09.299  3421  3470 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-09 15:05:09.300  3421  3421 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-09 15:05:09.301  3421  3421 I BtOppRfcommListener: stopping Accept Thread
08-09 15:05:09.302  3421  3531 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 15:05:09.302  3421  3531 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-09 15:05:09.303  3476  3476 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-09 15:05:09.306  3366  3366 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:09.306  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:09.306  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:09.306  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:05:09.306  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:09.306  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:05:09.306  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:09.306  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:09.306  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:05:09.311  3421  3421 D HeadsetService: Received stop request...Stopping profile...
,08-09 15:05:09.312  3366  3366 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:09.312  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:05:09.314  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:05:09.316  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:05:09.316   873   873 D BluetoothHeadset: Proxy object disconnected
08-09 15:05:09.317  3476  3488 D BluetoothHeadset: Proxy object disconnected,
,08-09 15:05:09.317  3421  3421 D A2dpService: Received stop request...Stopping profile...
,08-09 15:05:09.317  1373  1393 D BluetoothHeadset: Proxy object disconnected
08-09 15:05:09.317   873   873 D BluetoothHeadset: Proxy object disconnected
,08-09 15:05:09.317  3421  3489 D A2dpStateMachine: Exit Disconnected: -1
,08-09 15:05:09.318  1744  1922 D BluetoothHeadset: Proxy object disconnected
08-09 15:05:09.318   873   873 D BluetoothHeadset: Proxy object disconnected,
08-09 15:05:09.318   873   873 D BluetoothA2dp: Proxy object disconnected
08-09 15:05:09.319  3421  3421 D HidService: Received stop request...Stopping profile...
,08-09 15:05:09.319  3421  3421 D HidService: Stopping Bluetooth HidService
08-09 15:05:09.321  3421  3421 D HealthService: Received stop request...Stopping profile...
08-09 15:05:09.321  3476  3476 D DockEventReceiver: finishStartingService: stopping service
,08-09 15:05:09.323  3476  3476 D HeadsetProfile: Bluetooth service disconnected
08-09 15:05:09.323  3476  3476 D BluetoothA2dp: Proxy object disconnected
,08-09 15:05:09.324  3476  3476 D BluetoothInputDevice: Proxy object disconnected
08-09 15:05:09.324  3476  3476 D HidProfile: Bluetooth service disconnected
08-09 15:05:09.325  1373  1373 D HeadsetProfile: Bluetooth service disconnected
,08-09 15:05:09.325  1373  1373 D BluetoothA2dp: Proxy object disconnected
08-09 15:05:09.325  1373  1373 D BluetoothInputDevice: Proxy object disconnected
,08-09 15:05:09.325  1373  1373 D HidProfile: Bluetooth service disconnected
08-09 15:05:09.327  3421  3421 D PanService: Received stop request...Stopping profile...
08-09 15:05:09.328  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-09 15:05:09.328  1373  1373 D PanProfile: Bluetooth service disconnected
,08-09 15:05:09.329  3421  3421 D BluetoothMapService: Received stop request...Stopping profile...
,08-09 15:05:09.328  3476  3476 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-09 15:05:09.329  3421  3421 D BluetoothMapService: stop()
08-09 15:05:09.329  3476  3476 D PanProfile: Bluetooth service disconnected
08-09 15:05:09.329  3421  3421 D BluetoothMapAppObserver: deinitObservers()
08-09 15:05:09.329  3421  3421 D BluetoothMapAppObserver: removeReceiver()
08-09 15:05:09.331  1373  1373 D BluetoothMap: Proxy object disconnected
08-09 15:05:09.331  1373  1373 D MapProfile: Bluetooth service disconnected
,08-09 15:05:09.331  3476  3476 D BluetoothMap: Proxy object disconnected
08-09 15:05:09.331  3476  3476 D MapProfile: Bluetooth service disconnected
08-09 15:05:09.332  3421  3421 V BluetoothAdapterState: isTurningOff()=true
08-09 15:05:09.332  3421  3421 V BluetoothAdapterState: isTurningOn()=false
08-09 15:05:09.332  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:09.332  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:09.334  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 15:05:09.337  3421  3421 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-09 15:05:09.337  3421  3421 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 15:05:09.337  3421  3460 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-09 15:05:09.337  3421  3468 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-09 15:05:09.337  3421  3468 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:05:09.337  3421  3468 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:05:09.338  3421  3460 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-09 15:05:09.338  3421  3421 V BluetoothAdapterState: isTurningOff()=true
08-09 15:05:09.338  3421  3421 V BluetoothAdapterState: isTurningOn()=false
,08-09 15:05:09.339  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:09.339  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:05:09.340  3421  3421 V BluetoothAdapterState: isTurningOff()=true
08-09 15:05:09.340  3421  3468 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:05:09.340  3421  3421 V BluetoothAdapterState: isTurningOn()=false
,08-09 15:05:09.340  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:05:09.340  3421  3468 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-09 15:05:09.340  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:05:09.340  3421  3468 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-09 15:05:09.340  3421  3468 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 15:05:09.340  3421  3468 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-09 15:05:09.340  3421  3468 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 15:05:09.340  3421  3421 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-09 15:05:09.340  3421  3460 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-09 15:05:09.340  3421  3421 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-09 15:05:09.341  3421  3421 V BluetoothAdapterState: isTurningOff()=true
08-09 15:05:09.341  3421  3421 V BluetoothAdapterState: isTurningOn()=false
08-09 15:05:09.341  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:09.341  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:05:09.341  3421  3460 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-09 15:05:09.341  3421  3421 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-09 15:05:09.341  3421  3460 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-09 15:05:09.341  3421  3421 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-09 15:05:09.342  3421  3421 V BluetoothAdapterState: isTurningOff()=true
,08-09 15:05:09.342  3421  3421 V BluetoothAdapterState: isTurningOn()=false
,08-09 15:05:09.342  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:09.342  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:09.343  3421  3421 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-09 15:05:09.343  3421  3421 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object,
08-09 15:05:09.344  3421  3421 D BluetoothMapService: MAP Service closeService in
,08-09 15:05:09.344  3421  3421 V BluetoothAdapterState: isTurningOff()=true
08-09 15:05:09.344  3421  3421 V BluetoothAdapterState: isTurningOn()=false
08-09 15:05:09.344  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:05:09.344  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:09.344  3421  3455 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-09 15:05:09.345  3421  3455 D BluetoothAdapterProperties: Setting state to 15
08-09 15:05:09.345  3421  3455 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-09 15:05:09.345  3421  3455 I BluetoothAdapterState: Entering BleOnState
08-09 15:05:09.345  3421  3421 D BluetoothMapService: cleanup()
,08-09 15:05:09.346  3421  3421 D BluetoothMapService: MAP Service closeService in
08-09 15:05:09.346  1373  1390 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 15:05:09.346  3476  3487 D BluetoothPan: onBluetoothStateChange on: false
08-09 15:05:09.347  1373  1373 D BluetoothPbap: Proxy object disconnected
,08-09 15:05:09.347  1373  1373 D PbapServerProfile: Bluetooth service disconnected
08-09 15:05:09.348  1373  1390 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 15:05:09.348   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 15:05:09.348   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-09 15:05:09.349  1373  1393 D BluetoothMap: onBluetoothStateChange: up=false
08-09 15:05:09.349  3476  3488 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:05:09.349  1373  1835 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-09 15:05:09.350  3476  3487 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 15:05:09.351  1373  1390 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-09 15:05:09.352   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:05:09.352   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:05:09.352  1373  1393 D BluetoothPan: onBluetoothStateChange on: false
,08-09 15:05:09.352  3476  3488 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 15:05:09.353  1744  1765 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-09 15:05:09.353  3476  3487 D BluetoothMap: onBluetoothStateChange: up=false
08-09 15:05:09.354  3476  3488 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 15:05:09.356  3421  3455 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-09 15:05:09.356  3421  3455 D BluetoothAdapterProperties: Setting state to 16
,08-09 15:05:09.356  3421  3455 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-09 15:05:09.357  3421  3455 D BluetoothAdapterProperties: onBleDisable
,08-09 15:05:09.357  3421  3455 I BluetoothAdapterState: Entering PendingCommandState
08-09 15:05:09.357  3421  3456 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-09 15:05:09.358  3476  3476 D BluetoothPbap: Proxy object disconnected
,08-09 15:05:09.358  3476  3476 D PbapServerProfile: Bluetooth service disconnected
08-09 15:05:09.358  3421  3468 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-09 15:05:09.358  3421  3468 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:05:09.359  3421  3460 D BluetoothAdapterProperties: Scan Mode:20
08-09 15:05:09.359  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:05:09.360  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:05:09.361  3476  3476 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-09 15:05:09.361  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:05:09.363  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:05:09.366  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 15:05:09.371  3476  3476 D DockEventReceiver: finishStartingService: stopping service
,08-09 15:05:09.560  3421  3460 I bt_hci  : shut_down
,08-09 15:05:09.560  3421  3466 D bt_hwcfg: hw_epilog_process
08-09 15:05:09.561  3421  3466 I bt_vendor: low_power_mode_cb
,08-09 15:05:09.590  3421  3466 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-09 15:05:09.590  3421  3466 I bt_vendor: epilog_cb
,08-09 15:05:09.590  3421  3466 I bt_hci  : epilog_finished_callback
,08-09 15:05:09.599  3421  3460 I bt_hci_h4: hal_close
,08-09 15:05:09.600  3421  3460 I bt_userial_vendor: device fd = 51 close
,08-09 15:05:09.718  3421  3456 D bt_stack_manager: event_shut_down_stack finished.
,08-09 15:05:09.718  3421  3455 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-09 15:05:09.720  3421  3455 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-09 15:05:09.720  3421  3421 D BtGatt.DebugUtils: handleDebugAction() action=null
08-09 15:05:09.721  3421  3421 D BtGatt.GattService: Received stop request...Stopping profile...
,08-09 15:05:09.721  3421  3421 D BtGatt.GattService: stop()
08-09 15:05:09.721  3421  3421 D BtGatt.AdvertiseManager: advertise clients cleared
,08-09 15:05:09.723  3421  3421 V BluetoothAdapterState: isTurningOff()=false
08-09 15:05:09.723  3421  3421 V BluetoothAdapterState: isTurningOn()=false
,08-09 15:05:09.723  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:05:09.723  3421  3421 V BluetoothAdapterState: isBleTurningOff()=true
,08-09 15:05:09.723  3421  3455 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-09 15:05:09.724  3421  3455 D BluetoothAdapterProperties: Setting state to 10
,08-09 15:05:09.724  3421  3455 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-09 15:05:09.725  3421  3455 I BluetoothAdapterState: Entering OffState
08-09 15:05:09.727   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-09 15:05:09.742  3421  3421 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-09 15:05:09.742  3421  3421 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-09 15:05:09.742  3421  3421 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-09 15:05:09.743  3421  3456 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-09 15:05:09.745  3421  3456 D bt_stack_manager: event_clean_up_stack finished.
,08-09 15:05:09.747  3421  3421 I art     : System.exit called, status: 0
,08-09 15:05:09.747  3421  3421 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-09 15:05:09.815   873   884 I ActivityManager: Process com.android.bluetooth (pid 3421) has died
,08-09 15:05:10.386  3712  3741 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-09 15:05:12.238   873  1317 D ConnectivityService: handlePromptUnvalidated 100
,08-09 15:05:12.317   873   890 I ActivityManager: Start proc 3849:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-09 15:05:12.445  3849  3849 D AdapterServiceConfig: Adding HeadsetService
,08-09 15:05:12.445  3849  3849 D AdapterServiceConfig: Adding A2dpService
,08-09 15:05:12.446  3849  3849 D AdapterServiceConfig: Adding HidService
,08-09 15:05:12.446  3849  3849 D AdapterServiceConfig: Adding HealthService
,08-09 15:05:12.446  3849  3849 D AdapterServiceConfig: Adding PanService
,08-09 15:05:12.446  3849  3849 D AdapterServiceConfig: Adding GattService
,08-09 15:05:12.446  3849  3849 D AdapterServiceConfig: Adding BluetoothMapService
,08-09 15:05:12.463   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d6133eb:true
,08-09 15:05:12.464  3849  3849 D BluetoothAdapterState: make() - Creating AdapterState
,08-09 15:05:12.473  3849  3849 I bt_bluedroid: init
,08-09 15:05:12.473  3849  3861 I BluetoothAdapterState: Entering OffState
,08-09 15:05:12.476  3849  3862 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-09 15:05:12.476  3849  3862 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-09 15:05:12.476  3849  3862 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-09 15:05:12.476  3849  3862 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-09 15:05:12.477  3849  3849 I bt_bluedroid: get_profile_interface socket
,08-09 15:05:12.482  3849  3849 I bt_bluedroid: get_profile_interface sdp
,08-09 15:05:12.488  3849  3865 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 15:05:12.488  3849  3860 I bt_bluedroid: config_hci_snoop_log
,08-09 15:05:12.492   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-09 15:05:12.492  3849  3865 D BluetoothAdapterProperties: Name is: Nexus 6
,08-09 15:05:12.501  3849  3861 D BluetoothAdapterState: Current state: OFF, message: 0
,08-09 15:05:12.502  3849  3861 D BluetoothAdapterProperties: Setting state to 14
08-09 15:05:12.502  3849  3861 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-09 15:05:12.507  3849  3861 D BluetoothBondStateMachine: make
,08-09 15:05:12.510  3849  3866 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-09 15:05:12.516  3849  3861 I BluetoothAdapterState: Entering PendingCommandState
,08-09 15:05:12.518  3849  3849 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-09 15:05:12.522  3849  3849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
,08-09 15:05:12.523  3849  3849 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-09 15:05:12.524  3849  3849 D BtGatt.GattService: Received start request. Starting profile...
,08-09 15:05:12.524  3849  3849 D BtGatt.GattService: start()
08-09 15:05:12.524  3849  3849 I bt_bluedroid: get_profile_interface gatt
,08-09 15:05:12.525  3849  3849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
08-09 15:05:12.526  3849  3849 D BtGatt.AdvertiseManager: advertise manager created
,08-09 15:05:12.534  3849  3849 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:05:12.534  3849  3849 V BluetoothAdapterState: isTurningOn()=false
08-09 15:05:12.534  3849  3849 V BluetoothAdapterState: isBleTurningOn()=true
08-09 15:05:12.534  3849  3849 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:12.535  3849  3861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-09 15:05:12.535  3849  3861 I bt_bluedroid: enable
08-09 15:05:12.536  3849  3862 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-09 15:05:12.536  3849  3862 I bt_hci  : start_up
,08-09 15:05:12.545  3849  3862 I bt_vendor: alloc value 0xb39b0189
,08-09 15:05:12.545  3849  3862 I bt_vendor: init
08-09 15:05:12.545  3849  3862 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-09 15:05:12.546  3849  3862 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-09 15:05:12.652  3849  3862 D bt_hci  : start_up starting async portion
,08-09 15:05:12.653  3849  3869 I bt_hci  : event_finish_startup
,08-09 15:05:12.653  3849  3869 I bt_hci_h4: hal_open
08-09 15:05:12.653  3849  3869 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-09 15:05:12.663  3849  3869 I bt_userial_vendor: device fd = 51 open
,08-09 15:05:12.695  3849  3869 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 15:05:12.727  3849  3869 D bt_hwcfg: Chipset BCM4354A2
,08-09 15:05:12.728  3849  3869 D bt_hwcfg: Target name = [BCM4354A2]
08-09 15:05:12.729  3849  3869 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-09 15:05:13.390  3849  3869 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-09 15:05:13.392  3849  3869 D bt_hwcfg: Settlement delay -- 100 ms
,08-09 15:05:13.392  3849  3869 I bt_hwcfg: Setting fw settlement delay to 100 
,08-09 15:05:13.510  3849  3869 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 15:05:13.511  3849  3869 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-09 15:05:13.540  3849  3869 I bt_hwcfg: vendor lib fwcfg completed
,08-09 15:05:13.540  3849  3869 I bt_vendor: firmware callback
08-09 15:05:13.541  3849  3869 I bt_hci  : firmware_config_callback
,08-09 15:05:13.554  3849  3871 I bt_btu  : btu_task pending for preload complete event
,08-09 15:05:13.554  3849  3871 I bt_btu_task: Bluetooth chip preload is complete
08-09 15:05:13.554  3849  3871 I bt_btu  : btu_task received preload complete event
,08-09 15:05:13.564  3849  3871 I         : BTE_InitTraceLevels -- TRC_HCI
,08-09 15:05:13.565  3849  3871 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-09 15:05:13.565  3849  3871 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-09 15:05:13.565  3849  3871 I         : BTE_InitTraceLevels -- TRC_AVDT
08-09 15:05:13.566  3849  3871 I         : BTE_InitTraceLevels -- TRC_AVRC
08-09 15:05:13.566  3849  3871 I         : BTE_InitTraceLevels -- TRC_A2D
,08-09 15:05:13.566  3849  3871 I         : BTE_InitTraceLevels -- TRC_BNEP
08-09 15:05:13.566  3849  3871 I         : BTE_InitTraceLevels -- TRC_BTM
08-09 15:05:13.567  3849  3871 I         : BTE_InitTraceLevels -- TRC_GAP
,08-09 15:05:13.567  3849  3871 I         : BTE_InitTraceLevels -- TRC_PAN
08-09 15:05:13.567  3849  3871 I         : BTE_InitTraceLevels -- TRC_SDP
08-09 15:05:13.568  3849  3871 I         : BTE_InitTraceLevels -- TRC_GATT
08-09 15:05:13.568  3849  3871 I         : BTE_InitTraceLevels -- TRC_SMP
,08-09 15:05:13.568  3849  3871 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-09 15:05:13.568  3849  3871 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-09 15:05:13.704  3849  3871 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392dd9d
,08-09 15:05:13.705  3849  3871 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392dd9d 
,08-09 15:05:13.715  3849  3865 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-09 15:05:13.718  3849  3865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-09 15:05:13.718  3849  3865 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 15:05:13.722  3849  3865 D BluetoothAdapterProperties: Name is: Nexus 6
,08-09 15:05:13.728  3849  3865 D BluetoothAdapterProperties: Scan Mode:20
,08-09 15:05:13.728  3849  3865 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-09 15:05:13.728  3849  3865 D bt_hci  : do_postload posting postload work item
,08-09 15:05:13.729  3849  3869 I bt_hci  : event_postload
,08-09 15:05:13.729  3849  3869 I bt_vendor: sco_config_cb
,08-09 15:05:13.729  3849  3869 I bt_hci  : sco_config_callback postload finished.
08-09 15:05:13.731  3849  3865 D bt_bte_conf: Device ID record 1 : primary
,08-09 15:05:13.731  3849  3865 D bt_bte_conf:   vendorId            = 000f
08-09 15:05:13.731  3849  3865 D bt_bte_conf:   vendorIdSource      = 0001
,08-09 15:05:13.732  3849  3865 D bt_bte_conf:   product             = 1200
08-09 15:05:13.732  3849  3865 D bt_bte_conf:   version             = 1436
08-09 15:05:13.732  3849  3865 D bt_bte_conf:   clientExecutableURL = 
,08-09 15:05:13.732  3849  3865 D bt_bte_conf:   serviceDescription  = 
08-09 15:05:13.732  3849  3865 D bt_bte_conf:   documentationURL    = 
08-09 15:05:13.733  3849  3865 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-09 15:05:13.733  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:05:13.733  3849  3862 D bt_stack_manager: event_start_up_stack finished
08-09 15:05:13.734  3849  3861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-09 15:05:13.735  3849  3861 D BluetoothAdapterProperties: Setting state to 15
08-09 15:05:13.735  3849  3861 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-09 15:05:13.737  3849  3869 I bt_vendor: low_power_mode_cb
08-09 15:05:13.738  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:05:13.739  3849  3861 I BluetoothAdapterState: Entering BleOnState
08-09 15:05:13.743  3849  3861 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-09 15:05:13.743  3849  3861 D BluetoothAdapterProperties: Setting state to 11
,08-09 15:05:13.743  3849  3861 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-09 15:05:13.754  3849  3849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
,08-09 15:05:13.757  3849  3849 D HeadsetService: Received start request. Starting profile...
08-09 15:05:13.757  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-09 15:05:13.760  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:05:13.763  3849  3849 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 15:05:13.763  3849  3849 D HeadsetStateMachine: make
,08-09 15:05:13.769  3849  3861 I BluetoothAdapterState: Entering PendingCommandState
,08-09 15:05:13.771  3849  3849 D HeadsetStateMachine: max_hf_connections = 1
,08-09 15:05:13.771  3849  3849 I bt_bluedroid: get_profile_interface handsfree
08-09 15:05:13.771  3849  3865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-09 15:05:13.771  3849  3865 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-09 15:05:13.776  3849  3849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
,08-09 15:05:13.777  3849  3849 D A2dpService: Received start request. Starting profile...
,08-09 15:05:13.778  3849  3849 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-09 15:05:13.778  3849  3849 I bt_bluedroid: get_profile_interface avrcp
,08-09 15:05:13.784  3849  3849 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-09 15:05:13.784  3849  3849 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-09 15:05:13.784  3849  3849 D A2dpStateMachine: make
,08-09 15:05:13.785  3849  3849 I bt_bluedroid: get_profile_interface a2dp
,08-09 15:05:13.786  3849  3865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-09 15:05:13.788  3849  3880 D A2dpStateMachine: Enter Disconnected: -2
,08-09 15:05:13.791  3849  3849 I BluetoothHidServiceJni: classInitNative: succeeds
,08-09 15:05:13.792  3849  3849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
08-09 15:05:13.792  3849  3849 D HidService: Received start request. Starting profile...
08-09 15:05:13.793  3849  3849 I bt_bluedroid: get_profile_interface hidhost
,08-09 15:05:13.793  3849  3865 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390f3e5
08-09 15:05:13.793  3849  3865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-09 15:05:13.793  3849  3849 D HidService: setHidService(): set to: null
,08-09 15:05:13.794  3849  3849 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-09 15:05:13.795  3849  3849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
08-09 15:05:13.796  3849  3849 D HealthService: Received start request. Starting profile...
,08-09 15:05:13.791  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 15:05:13.797  3849  3849 I bt_bluedroid: get_profile_interface health
,08-09 15:05:13.798  3849  3849 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-09 15:05:13.798  3849  3849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
08-09 15:05:13.799  3849  3849 D PanService: Received start request. Starting profile...
,08-09 15:05:13.799  3849  3849 D BluetoothPanServiceJni: initializeNative(L110): pan
08-09 15:05:13.799  3849  3849 I bt_bluedroid: get_profile_interface pan
08-09 15:05:13.800  3849  3865 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-09 15:05:13.803  3849  3849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad210f
,08-09 15:05:13.804  3849  3849 D BluetoothMapService: Received start request. Starting profile...
08-09 15:05:13.804  3849  3849 D BluetoothMapService: start()
,08-09 15:05:13.806  3849  3849 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-09 15:05:13.807  3849  3849 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-09 15:05:13.807  3849  3849 D BluetoothMapAppObserver: createReceiver()
,08-09 15:05:13.808  3849  3849 D BluetoothMapAppObserver: initObservers()
08-09 15:05:13.808  3849  3849 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-09 15:05:13.815  3849  3878 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-09 15:05:13.816  3849  3849 V BluetoothAdapterState: isTurningOff()=false
08-09 15:05:13.816  3849  3849 V BluetoothAdapterState: isTurningOn()=true
08-09 15:05:13.816  3849  3849 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:13.816  3849  3849 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:05:13.817  3849  3849 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:05:13.817  3849  3849 V BluetoothAdapterState: isTurningOn()=true
08-09 15:05:13.817  3849  3849 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:13.818  3849  3849 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:13.818  3849  3849 V BluetoothAdapterState: isTurningOff()=false
08-09 15:05:13.818  3849  3849 V BluetoothAdapterState: isTurningOn()=true
08-09 15:05:13.818  3849  3849 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:05:13.818  3849  3849 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:13.818  3849  3849 V BluetoothAdapterState: isTurningOff()=false
08-09 15:05:13.818  3849  3849 V BluetoothAdapterState: isTurningOn()=true
08-09 15:05:13.818  3849  3849 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:13.818  3849  3849 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:05:13.820  3849  3849 V BluetoothAdapterState: isTurningOff()=false
08-09 15:05:13.820  3849  3849 V BluetoothAdapterState: isTurningOn()=true
,08-09 15:05:13.820  3849  3849 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:13.820  3849  3849 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:13.821  3849  3849 V BluetoothAdapterState: isTurningOff()=false
08-09 15:05:13.821  3849  3849 V BluetoothAdapterState: isTurningOn()=true
08-09 15:05:13.821  3849  3849 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:13.821  3849  3849 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:05:13.821  3849  3861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-09 15:05:13.821  3849  3861 D BluetoothAdapterProperties: ScanMode =  20
08-09 15:05:13.821  3849  3861 D BluetoothAdapterProperties: State =  11
,08-09 15:05:13.823  3849  3865 D BluetoothAdapterProperties: Scan Mode:21
,08-09 15:05:13.823  3849  3865 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-09 15:05:13.824  3849  3861 D BluetoothAdapterProperties: Setting state to 12
08-09 15:05:13.824  3849  3861 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-09 15:05:13.825  1373  1393 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-09 15:05:13.828  3849  3861 I BluetoothAdapterState: Entering OnState
,08-09 15:05:13.828  3476  3487 D BluetoothPan: onBluetoothStateChange on: true
,08-09 15:05:13.829  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:13.829  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:13.829  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:05:13.829  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:13.829  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:05:13.829  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:13.829  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:13.829  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:05:13.829  1373  1373 D BluetoothA2dp: Proxy object connected
,08-09 15:05:13.831  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:05:13.832  1373  1835 D BluetoothPbap: onBluetoothStateChange: up=true
,08-09 15:05:13.833  3476  3476 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 15:05:13.833  3476  3476 D PanProfile: Bluetooth service connected
08-09 15:05:13.834   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 15:05:13.834  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:13.834  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:13.834  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:05:13.834  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:13.834  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:05:13.834  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:13.834  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:13.834  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:05:13.834  3849  3849 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-09 15:05:13.835   873   873 D BluetoothA2dp: Proxy object connected
,08-09 15:05:13.835  3849  3849 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-09 15:05:13.836  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:05:13.837  3849  3849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 15:05:13.836   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:05:13.838  1373  1393 D BluetoothMap: onBluetoothStateChange: up=true
08-09 15:05:13.839  3849  3849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 15:05:13.840  3476  3841 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 15:05:13.840  3849  3849 D ObexServerSockets: Succeed to create listening sockets 
08-09 15:05:13.840  3849  3849 D ObexServerSockets0: startAccept()
08-09 15:05:13.840  3849  3849 D ObexServerSockets0: prepareForNewConnect()
08-09 15:05:13.841  1373  1390 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 15:05:13.843  3849  3849 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-09 15:05:13.843  3849  3849 D BluetoothSdpJni: SDP Create record success - handle: 0
08-09 15:05:13.843  3849  3886 D ObexServerSockets0: Accepting socket connection...
,08-09 15:05:13.845  3849  3887 D ObexServerSockets0: Accepting socket connection...
08-09 15:05:13.845  1373  1373 D BluetoothMap: Proxy object connected
08-09 15:05:13.845  1373  1373 D MapProfile: Bluetooth service connected
08-09 15:05:13.845  1373  1373 D BluetoothMap: getConnectedDevices()
08-09 15:05:13.846  3476  3487 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-09 15:05:13.849  3476  3476 D BluetoothA2dp: Proxy object connected
08-09 15:05:13.849  1373  1393 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-09 15:05:13.850   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 15:05:13.850   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:05:13.851  1373  1390 D BluetoothPan: onBluetoothStateChange on: true
08-09 15:05:13.851  1373  1373 D BluetoothInputDevice: Proxy object connected
08-09 15:05:13.851  1373  1373 D HidProfile: Bluetooth service connected
08-09 15:05:13.853  3476  3841 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-09 15:05:13.853  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 15:05:13.853  1373  1373 D PanProfile: Bluetooth service connected
,08-09 15:05:13.855  1744  1756 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:05:13.855  3476  3476 D BluetoothInputDevice: Proxy object connected
08-09 15:05:13.855  3476  3476 D HidProfile: Bluetooth service connected
08-09 15:05:13.856  3476  3487 D BluetoothMap: onBluetoothStateChange: up=true
,08-09 15:05:13.858  3476  3841 D BluetoothPbap: onBluetoothStateChange: up=true
,08-09 15:05:13.859  3476  3476 D BluetoothMap: Proxy object connected
,08-09 15:05:13.860  3476  3476 D MapProfile: Bluetooth service connected
,08-09 15:05:13.860  3476  3476 D BluetoothMap: getConnectedDevices()
,08-09 15:05:13.861   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-09 15:05:13.863  3849  3849 D BluetoothMapService: onReceive
,08-09 15:05:13.863  3849  3849 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-09 15:05:13.863  3849  3849 D BluetoothMapService: STATE_ON
08-09 15:05:13.863  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:05:13.865  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:05:13.870  3476  3476 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-09 15:05:13.877  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 15:05:13.878  3476  3476 D DockEventReceiver: finishStartingService: stopping service
,08-09 15:05:13.889  1373  1373 D BluetoothPbap: Proxy object connected
08-09 15:05:13.889  1373  1373 D PbapServerProfile: Bluetooth service connected
,08-09 15:05:13.889  3476  3476 D BluetoothPbap: Proxy object connected
08-09 15:05:13.889  3476  3476 D PbapServerProfile: Bluetooth service connected
,08-09 15:05:13.895  3849  3849 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-09 15:05:13.895  3849  3849 D ObexServerSockets0: prepareForNewConnect()
,08-09 15:05:13.897  3849  3892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 15:05:13.921  3849  3896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 15:05:13.924  3849  3896 I BtOppRfcommListener: Accept thread started.
,08-09 15:05:13.938   873   873 D BluetoothHeadset: Proxy object connected
,08-09 15:05:13.939  3476  3487 D BluetoothHeadset: Proxy object connected
,08-09 15:05:13.939  3476  3476 D HeadsetProfile: Bluetooth service connected
08-09 15:05:13.939  1373  1393 D BluetoothHeadset: Proxy object connected
08-09 15:05:13.940  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-09 15:05:13.940   873   873 D BluetoothHeadset: Proxy object connected
08-09 15:05:13.940  1744  1922 D BluetoothHeadset: Proxy object connected
,08-09 15:05:13.941   873   873 D BluetoothHeadset: Proxy object connected
08-09 15:05:13.942  3476  3841 D BluetoothHeadset: Proxy object connected
,08-09 15:05:13.944  3476  3476 D HeadsetProfile: Bluetooth service connected
,08-09 15:05:13.944  1373  1390 D BluetoothHeadset: Proxy object connected
,08-09 15:05:13.945  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-09 15:05:13.951   873   890 D BluetoothHeadset: Proxy object connected
,08-09 15:05:13.952   873   890 D BluetoothHeadset: Proxy object connected
,08-09 15:05:13.956  1744  1765 D BluetoothHeadset: Proxy object connected
,08-09 15:05:15.271  3366  3413 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 15:05:15.271  3366  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 15:05:15.446  2594  2604 D Finsky  : [176] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-09 15:05:15.463  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:05:15.477  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:05:15.483  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:05:15.551  1526  1890 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-09 15:05:15.552  1526  1890 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-09 15:05:15.552  1526  1890 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:05:15.552  1526  1890 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:05:15.623  2594  2604 D Finsky  : [176] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-09 15:05:18.279  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 15:05:18.279  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@56d924c added. We now have 6 listener(s)
08-09 15:05:18.280  3366  3413 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 15:05:18.288  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 15:05:18.288  3366  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@502a295 added. We now have 7 listener(s)
08-09 15:05:18.289  3366  3413 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 15:05:18.292  3366  3413 I System.out: IsBluetoothEnabled
,08-09 15:05:18.302  3849  3861 D BluetoothAdapterState: Current state: ON, message: 23
,08-09 15:05:18.302  3849  3861 D BluetoothAdapterProperties: Setting state to 13
,08-09 15:05:18.303  3849  3861 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-09 15:05:18.304  3849  3861 D BluetoothAdapterProperties: onBluetoothDisable()
,08-09 15:05:18.312  3849  3849 D BluetoothMapService: onReceive
,08-09 15:05:18.313  3849  3849 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 15:05:18.313  3849  3849 D BluetoothMapService: STATE_TURNING_OFF
,08-09 15:05:18.314  3849  3849 D BluetoothMapService: MAP Service closeService in
,08-09 15:05:18.314  3849  3849 D BluetoothMapMasInstance0: MAP Service shutdown
,08-09 15:05:18.314  3849  3849 D ObexServerSockets0: shutdown(block = true)
,08-09 15:05:18.315  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:18.315  3366  3413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:18.315  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:18.315  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:05:18.315  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:18.315  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:05:18.315  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:18.315  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:18.315  3366  3413 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:05:18.315  3849  3886 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-09 15:05:18.317  3849  3849 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-09 15:05:18.318  3849  3887 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-09 15:05:18.320  3366  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:05:18.320  3366  3413 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:05:18.320  3366  3366 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:18.322  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:05:18.322  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:05:18.322  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:05:18.322  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:05:18.322  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:05:18.322  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:05:18.322  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:05:18.322  3366  3366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:05:18.323  3849  3861 I BluetoothAdapterState: Entering PendingCommandState
,08-09 15:05:18.323  3849  3873 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-09 15:05:18.325  3849  3849 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-09 15:05:18.325  3849  3849 I BtOppRfcommListener: stopping Accept Thread
08-09 15:05:18.325  3366  3366 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:05:18.325  3366  3366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:05:18.325  3849  3896 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 15:05:18.326  3849  3896 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-09 15:05:18.328  3849  3865 D BluetoothAdapterProperties: Scan Mode:20
,08-09 15:05:18.329  3849  3861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-09 15:05:18.330  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:05:18.333  3849  3849 D HeadsetService: Received stop request...Stopping profile...
,08-09 15:05:18.337   873   873 D BluetoothHeadset: Proxy object disconnected
08-09 15:05:18.338  3476  3841 D BluetoothHeadset: Proxy object disconnected
08-09 15:05:18.338  1373  1393 D BluetoothHeadset: Proxy object disconnected
,08-09 15:05:18.339   873   873 D BluetoothHeadset: Proxy object disconnected
08-09 15:05:18.339  1744  1922 D BluetoothHeadset: Proxy object disconnected
08-09 15:05:18.339   873   873 D BluetoothHeadset: Proxy object disconnected
08-09 15:05:18.339  3849  3849 D A2dpService: Received stop request...Stopping profile...
08-09 15:05:18.340  3849  3861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
08-09 15:05:18.340  3849  3861 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
08-09 15:05:18.340  3849  3880 D A2dpStateMachine: Exit Disconnected: -1
,08-09 15:05:18.340  3476  3476 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-09 15:05:18.341  1373  1373 D HeadsetProfile: Bluetooth service disconnected
,08-09 15:05:18.345   873   873 D BluetoothA2dp: Proxy object disconnected
,08-09 15:05:18.345  1373  1373 D BluetoothA2dp: Proxy object disconnected
08-09 15:05:18.346  3849  3849 D HidService: Received stop request...Stopping profile...
08-09 15:05:18.346  3849  3849 D HidService: Stopping Bluetooth HidService
,08-09 15:05:18.348  1373  1373 D BluetoothInputDevice: Proxy object disconnected
,08-09 15:05:18.348  1373  1373 D HidProfile: Bluetooth service disconnected
08-09 15:05:18.348  3849  3849 D HealthService: Received stop request...Stopping profile...
08-09 15:05:18.349  3476  3476 D HeadsetProfile: Bluetooth service disconnected
08-09 15:05:18.349  3849  3849 V BluetoothAdapterState: isTurningOff()=true
,08-09 15:05:18.350  3849  3849 V BluetoothAdapterState: isTurningOn()=false
08-09 15:05:18.350  3849  3849 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:18.350  3849  3849 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:05:18.351  3849  3849 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-09 15:05:18.351  3849  3849 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 15:05:18.352  3849  3865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-09 15:05:18.352  3849  3871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:05:18.352  3849  3871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-09 15:05:18.352  3849  3849 D PanService: Received stop request...Stopping profile...
,08-09 15:05:18.352  3849  3871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-09 15:05:18.352  3476  3476 D DockEventReceiver: finishStartingService: stopping service
08-09 15:05:18.352  3849  3865 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-09 15:05:18.353  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-09 15:05:18.354  3849  3849 D BluetoothMapService: Received stop request...Stopping profile...
,08-09 15:05:18.354  3849  3849 D BluetoothMapService: stop()
,08-09 15:05:18.354  1373  1373 D PanProfile: Bluetooth service disconnected
,08-09 15:05:18.353  3476  3476 D BluetoothA2dp: Proxy object disconnected
08-09 15:05:18.354  3476  3476 D BluetoothInputDevice: Proxy object disconnected
08-09 15:05:18.354  3476  3476 D HidProfile: Bluetooth service disconnected
08-09 15:05:18.354  3849  3849 D BluetoothMapAppObserver: deinitObservers()
08-09 15:05:18.355  3849  3849 D BluetoothMapAppObserver: removeReceiver()
08-09 15:05:18.355  3476  3476 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-09 15:05:18.355  3476  3476 D PanProfile: Bluetooth service disconnected
08-09 15:05:18.356  1373  1373 D BluetoothMap: Proxy object disconnected
08-09 15:05:18.357  1373  1373 D MapProfile: Bluetooth service disconnected
08-09 15:05:18.357  3849  3849 V BluetoothAdapterState: isTurningOff()=true
08-09 15:05:18.357  3849  3849 V BluetoothAdapterState: isTurningOn()=false
08-09 15:05:18.357  3849  3849 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:18.357  3849  3849 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:18.357  3476  3476 D BluetoothMap: Proxy object disconnected
08-09 15:05:18.358  3476  3476 D MapProfile: Bluetooth service disconnected
,08-09 15:05:18.358  3849  3849 V BluetoothAdapterState: isTurningOff()=true
,08-09 15:05:18.358  3849  3849 V BluetoothAdapterState: isTurningOn()=false
08-09 15:05:18.358  3849  3849 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:18.358  3849  3849 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:05:18.359  3849  3865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-09 15:05:18.359  3849  3871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-09 15:05:18.359  3849  3871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:05:18.359  3849  3871 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-09 15:05:18.359  3849  3871 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 15:05:18.359  3849  3871 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-09 15:05:18.359  3849  3871 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 15:05:18.360  3849  3849 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-09 15:05:18.360  3849  3849 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-09 15:05:18.360  3849  3849 V BluetoothAdapterState: isTurningOff()=true
,08-09 15:05:18.360  3849  3849 V BluetoothAdapterState: isTurningOn()=false
08-09 15:05:18.360  3849  3849 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:18.360  3849  3849 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:05:18.360  3849  3849 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-09 15:05:18.361  3849  3865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-09 15:05:18.361  3849  3865 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-09 15:05:18.361  3849  3849 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-09 15:05:18.361  3849  3849 V BluetoothAdapterState: isTurningOff()=true
08-09 15:05:18.361  3849  3849 V BluetoothAdapterState: isTurningOn()=false,
08-09 15:05:18.361  3849  3849 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:18.362  3849  3849 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:18.362  3849  3849 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-09 15:05:18.362  3849  3849 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-09 15:05:18.362  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 15:05:18.363  3849  3849 D BluetoothMapService: MAP Service closeService in
08-09 15:05:18.363  3849  3849 V BluetoothAdapterState: isTurningOff()=true,
08-09 15:05:18.363  3849  3849 V BluetoothAdapterState: isTurningOn()=false
08-09 15:05:18.363  3849  3849 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:05:18.363  3849  3849 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:05:18.363  3849  3849 D BluetoothMapService: cleanup()
08-09 15:05:18.364  3849  3849 D BluetoothMapService: MAP Service closeService in
08-09 15:05:18.364  3849  3861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-09 15:05:18.364  3849  3861 D BluetoothAdapterProperties: Setting state to 15
08-09 15:05:18.364  3849  3861 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-09 15:05:18.365  3849  3861 I BluetoothAdapterState: Entering BleOnState
,08-09 15:05:18.365  3849  3861 D BluetoothAdapterState: Current state: BLE ON, message: 0
08-09 15:05:18.365  1373  1393 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 15:05:18.366  1373  1373 D BluetoothPbap: Proxy object disconnected,
08-09 15:05:18.366  1373  1373 D PbapServerProfile: Bluetooth service disconnected
08-09 15:05:18.367  3476  3488 D BluetoothPan: onBluetoothStateChange on: false
,08-09 15:05:18.369  1373  1835 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 15:05:18.370   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 15:05:18.370   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-09 15:05:18.370  1373  1390 D BluetoothMap: onBluetoothStateChange: up=false
08-09 15:05:18.371  3476  3487 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:05:18.371  1373  1393 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-09 15:05:18.371  3476  3841 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 15:05:18.372  1373  1835 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 15:05:18.372   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-09 15:05:18.372   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-09 15:05:18.373  1373  1390 D BluetoothPan: onBluetoothStateChange on: false
08-09 15:05:18.375  3476  3476 D BluetoothPbap: Proxy object disconnected
08-09 15:05:18.375  3476  3476 D PbapServerProfile: Bluetooth service disconnected
,08-09 15:05:18.376  3476  3488 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 15:05:18.376  1744  1765 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:05:18.377  3476  3487 D BluetoothMap: onBluetoothStateChange: up=false
,08-09 15:05:18.377  3476  3841 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 15:05:18.378  3849  3861 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-09 15:05:18.379  3849  3861 D BluetoothAdapterProperties: Setting state to 16,
08-09 15:05:18.379  3849  3861 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-09 15:05:18.380  3849  3861 D BluetoothAdapterProperties: onBleDisable
08-09 15:05:18.380  3849  3862 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-09 15:05:18.381  3849  3861 I BluetoothAdapterState: Entering PendingCommandState
,08-09 15:05:18.381  3849  3871 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-09 15:05:18.381  3849  3871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:05:18.383  3849  3865 D BluetoothAdapterProperties: Scan Mode:20
,08-09 15:05:18.386  3476  3476 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-09 15:05:18.387  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:05:18.389  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:05:18.393  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 15:05:18.400  3476  3476 D DockEventReceiver: finishStartingService: stopping service
,08-09 15:05:18.588  3849  3865 I bt_hci  : shut_down
,08-09 15:05:18.589  3849  3869 D bt_hwcfg: hw_epilog_process
,08-09 15:05:18.590  3849  3869 I bt_vendor: low_power_mode_cb
,08-09 15:05:18.609  3849  3869 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-09 15:05:18.609  3849  3869 I bt_vendor: epilog_cb
,08-09 15:05:18.609  3849  3869 I bt_hci  : epilog_finished_callback
,08-09 15:05:18.619  3849  3865 I bt_hci_h4: hal_close
,08-09 15:05:18.620  3849  3865 I bt_userial_vendor: device fd = 51 close
,08-09 15:05:18.742  3849  3862 D bt_stack_manager: event_shut_down_stack finished.
,08-09 15:05:18.743  3849  3861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-09 15:05:18.749  3849  3849 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-09 15:05:18.751  3849  3849 D BtGatt.GattService: Received stop request...Stopping profile...
08-09 15:05:18.751  3849  3849 D BtGatt.GattService: stop()
,08-09 15:05:18.751  3849  3849 D BtGatt.AdvertiseManager: advertise clients cleared
,08-09 15:05:18.752  3849  3861 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-09 15:05:18.756  3849  3849 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:05:18.757  3849  3849 V BluetoothAdapterState: isTurningOn()=false
,08-09 15:05:18.757  3849  3849 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:05:18.758  3849  3849 V BluetoothAdapterState: isBleTurningOff()=true
08-09 15:05:18.759  3849  3861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-09 15:05:18.760  3849  3861 D BluetoothAdapterProperties: Setting state to 10
,08-09 15:05:18.761  3849  3861 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-09 15:05:18.763  3849  3861 I BluetoothAdapterState: Entering OffState
,08-09 15:05:18.773  3366  3366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:05:18.778  3476  3476 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-09 15:05:18.788  3476  3476 D DockEventReceiver: finishStartingService: stopping service
,08-09 15:05:18.792  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 15:05:19.189   873  1903 I ActivityManager: Killing 3196:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-09 15:05:41.611  1662  1776 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-09 15:05:41.612  1662  1776 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-09 15:05:41.667  1526  1526 I ConfigService: onCreate
,08-09 15:05:46.739  1526  1526 I ConfigService: onDestroy
,08-09 15:06:06.500   873  1317 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-09 15:07:05.251  1526  2017 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-09 15:09:40.382  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:09:40.408  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:09:40.417  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:09:40.524  1526  1890 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-09 15:09:40.524  1526  1890 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-09 15:09:40.525  1526  1890 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:09:40.525  1526  1890 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:09:40.576  1526  1890 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 15:09:40.576  1526  1890 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 15:09:40.576  1526  1890 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 15:09:40.576  1526  1890 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 15:09:40.576  1526  1890 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 15:09:40.576  1526  1890 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 15:09:40.576  1526  1890 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 15:09:40.588  2594  2623 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 15:09:40.588  2594  2623 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-09 15:09:40.588  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-09 15:09:40.588  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-09 15:09:40.588  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-09 15:09:40.588  2594  2623 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-09 15:09:40.588  2594  2623 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 15:14:40.741  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:14:40.765  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:14:40.774  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:14:40.898  1526  2695 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-09 15:14:40.898  1526  2695 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-09 15:14:40.899  1526  2695 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:14:40.899  1526  2695 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:14:40.912  1526  2695 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 15:14:40.912  1526  2695 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 15:14:40.912  1526  2695 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 15:14:40.912  1526  2695 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 15:14:40.912  1526  2695 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 15:14:40.912  1526  2695 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 15:14:40.912  1526  2695 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 15:14:40.918  2594  2623 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 15:14:40.918  2594  2623 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-09 15:14:40.918  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-09 15:14:40.918  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-09 15:14:40.918  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-09 15:14:40.918  2594  2623 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-09 15:14:40.918  2594  2623 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 15:16:40.953  1526  2017 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-09 15:19:27.227   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,08-09 15:19:41.057  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:19:41.082  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:19:41.089  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:19:41.197  1526  2697 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-09 15:19:41.198  1526  2697 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-09 15:19:41.198  1526  2697 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 15:19:41.199  1526  2697 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:19:41.252  1526  2697 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 15:19:41.252  1526  2697 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 15:19:41.252  1526  2697 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 15:19:41.252  1526  2697 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 15:19:41.252  1526  2697 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 15:19:41.252  1526  2697 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 15:19:41.252  1526  2697 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 15:19:41.270  2594  2623 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 15:19:41.270  2594  2623 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-09 15:19:41.270  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-09 15:19:41.270  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-09 15:19:41.270  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-09 15:19:41.270  2594  2623 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-09 15:19:41.270  2594  2623 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 15:24:41.425  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:24:41.443  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:24:41.445  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:24:41.527  1526  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-09 15:24:41.528  1526  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-09 15:24:41.528  1526  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:24:41.529  1526  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:24:41.571  1526  1538 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 15:24:41.571  1526  1538 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 15:24:41.571  1526  1538 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 15:24:41.571  1526  1538 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 15:24:41.571  1526  1538 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 15:24:41.571  1526  1538 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 15:24:41.571  1526  1538 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 15:24:41.581  2594  2623 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 15:24:41.581  2594  2623 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-09 15:24:41.581  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-09 15:24:41.581  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-09 15:24:41.581  2594  2623 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-09 15:24:41.581  2594  2623 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-09 15:24:41.581  2594  2623 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms)
```
