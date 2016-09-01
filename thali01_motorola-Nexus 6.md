#### Test 8286536280ed803_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-01 20:53:39.003  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:53:39.011  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-01 20:53:39.016  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-01 20:53:39.069  1535  2822 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-01 20:53:39.069  1535  2822 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-01 20:53:39.069  1535  2822 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:53:39.069  1535  2822 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-01 20:53:39.095  1535  2822 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-01 20:53:39.095  1535  2822 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-01 20:53:39.095  1535  2822 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-01 20:53:39.095  1535  2822 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-01 20:53:39.095  1535  2822 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-01 20:53:39.095  1535  2822 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-01 20:53:39.095  1535  2822 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
09-01 20:53:39.105  2716  2749 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-01 20:53:39.105  2716  2749 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-01 20:53:39.105  2716  2749 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-01 20:53:39.105  2716  2749 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-01 20:53:39.105  2716  2749 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-01 20:53:39.105  2716  2749 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-01 20:53:39.105  2716  2749 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
09-01 20:53:39.631  3496  3496 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-01 20:53:39.636  3496  3496 D AndroidRuntime: CheckJNI is OFF
09-01 20:53:39.671  3496  3496 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-01 20:53:39.754  3496  3496 I Radio-JNI: register_android_hardware_Radio DONE
09-01 20:53:39.779  3496  3496 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-01 20:53:39.784   872  1557 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-01 20:53:39.828   872  1557 I ActivityManager: Start proc 3506:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-01 20:53:39.836  3496  3496 D AndroidRuntime: Shutting down VM
09-01 20:53:39.899  3506  3506 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-01 20:53:39.921  3506  3506 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-01 20:53:39.928  3506  3506 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2030-2033)
09-01 20:53:39.928  3506  3506 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 20:53:39.940  3506  3506 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ad083ef}
09-01 20:53:39.940  3506  3506 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 20:53:39.940  3506  3506 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-01 20:53:39.946  3506  3506 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-01 20:53:39.947  3506  3506 E SysUtils: ApplicationContext is null in ApplicationStatus
09-01 20:53:39.969  3506  3521 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
09-01 20:53:39.975  3506  3506 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-01 20:53:39.984  3506  3506 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-01 20:53:39.984  3506  3506 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-01 20:53:39.984  3506  3506 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 20:53:39.984  3506  3506 I Adreno  : Build Date                       : 10/20/15
09-01 20:53:39.984  3506  3506 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 20:53:39.984  3506  3506 I Adreno  : Local Branch                     : M14
09-01 20:53:39.984  3506  3506 I Adreno  : Remote Branch                    : 
09-01 20:53:39.984  3506  3506 I Adreno  : Remote Branch                    : 
09-01 20:53:39.984  3506  3506 I Adreno  : Reconstruct Branch               : 
09-01 20:53:40.059   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9f95698:true
,09-01 20:53:40.100  3506  3506 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-01 20:53:40.116  3506  3506 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-01 20:53:40.194  3506  3544 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-01 20:53:40.213  3506  3530 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-01 20:53:40.245  3506  3544 I OpenGLRenderer: Initialized EGL, version 1.4
,09-01 20:53:40.281  1870  1870 I Keyboard.Facilitator: onFinishInput()
,09-01 20:53:40.342   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +480ms (total +531ms)
,09-01 20:53:40.412  3506  3506 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3506
,09-01 20:53:40.509  3506  3506 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-01 20:53:40.722  3506  3547 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1680410320
,09-01 20:53:40.736  3506  3547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-01 20:53:40.736  3506  3547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-01 20:53:40.736  3506  3547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-01 20:53:40.736  3506  3547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-01 20:53:40.736  3506  3547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-01 20:53:40.736  3506  3547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@acf52f2 added. We now have 1 listener(s)
,09-01 20:53:40.742  3506  3547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-01 20:53:40.743  3506  3547 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 20:53:40.744  3506  3547 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 20:53:40.744  3506  3547 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-01 20:53:40.749  3506  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cad84f9 added. We now have 1 listener(s)
09-01 20:53:40.750  3506  3547 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 20:53:40.764   872  1308 D WifiService: New client listening to asynchronous messages
,09-01 20:53:40.769  3506  3547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 20:53:40.770  3506  3547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-01 20:53:40.770  3506  3547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-01 20:53:40.771  3506  3547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-01 20:53:40.771  3506  3547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-01 20:53:40.779  3506  3547 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 20:53:40.779  3506  3547 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-01 20:53:40.787  3506  3547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:53:40.788  3506  3547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 20:53:40.788  3506  3547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:53:40.788  3506  3547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 20:53:40.788  3506  3547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:53:40.788  3506  3547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:53:40.788  3506  3547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:53:40.788  3506  3547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:53:40.788  3506  3547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:53:40.789  3506  3547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-01 20:53:40.789  3506  3547 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 20:53:40.790  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:53:40.790  3506  3547 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-01 20:53:40.819  3506  3506 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-01 20:53:42.060  3506  3553 W jxcore-log: Initializing JXcore engine
09-01 20:53:42.060  3506  3553 W jxcore-log: JXcore engine is ready
,09-01 20:53:42.095  3553  3553 W Thread-286: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8950 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-01 20:53:42.098  3553  3553 W Thread-286: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10763]" dev="sockfs" ino=10763 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-01 20:53:42.098  3553  3553 W Thread-286: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-01 20:53:42.098  3553  3553 W Thread-286: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24970]" dev="sockfs" ino=24970 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-01 20:53:42.116  3506  3553 W jxcore-log: Starting JXcore engine
,09-01 20:53:42.198  3506  3553 W jxcore-log: Platform android
09-01 20:53:42.198  3506  3553 W jxcore-log: 
,09-01 20:53:42.199  3506  3553 W jxcore-log: Process ARCH arm
09-01 20:53:42.199  3506  3553 W jxcore-log: 
,09-01 20:53:42.404  3506  3553 I jxcore-log: JXcore Cordova bridge is ready!
09-01 20:53:42.404  3506  3553 I jxcore-log: 
,09-01 20:53:42.404  3506  3553 W jxcore-log: JXcore engine is started
,09-01 20:53:42.413  3506  3547 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-01 20:53:42.417  3506  3506 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-01 20:53:55.977  3506  3553 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-01 20:53:55.977  3506  3553 I jxcore-log: 
,09-01 20:53:55.980  3506  3553 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-01 20:53:55.980  3506  3553 I jxcore-log: 
09-01 20:53:55.981  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:53:55.981  3506  3553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 20:53:55.981  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:53:55.981  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 20:53:55.981  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:53:55.981  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:53:55.981  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:53:55.981  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:53:55.981  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 20:53:55.982  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:53:55.982  3506  3553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:53:55.986  3506  3553 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-01 20:53:55.986  3506  3553 I jxcore-log: 
,09-01 20:53:55.988  3506  3553 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-01 20:53:55.988  3506  3553 I jxcore-log: 
,09-01 20:53:56.329  3506  3553 I jxcore-log: Running unit tests
09-01 20:53:56.329  3506  3553 I jxcore-log: 
,09-01 20:53:56.330  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 20:53:56.330  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff2cfc3 added. We now have 2 listener(s)
,09-01 20:53:56.332  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 20:53:56.332  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 20:53:56.332  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 20:53:56.332  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 20:53:56.333  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9821040 added. We now have 2 listener(s)
09-01 20:53:56.333  3506  3553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 20:53:56.334  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 20:53:56.336  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 20:53:56.337  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:53:56.338  3506  3553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 20:53:56.338  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:53:56.338  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 20:53:56.338  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:53:56.338  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:53:56.338  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:53:56.338  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:53:56.338  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:53:56.338  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:53:56.339  3506  3553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:53:56.339  3506  3553 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 20:53:56.340  3506  3553 D executeNativeTests: Running unit tests
,09-01 20:53:56.341  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:53:56.434  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 20:53:56.435  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e added. We now have 3 listener(s)
,09-01 20:53:56.436  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 20:53:56.436  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 20:53:56.436  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 20:53:56.436  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 20:53:56.436  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f added. We now have 3 listener(s)
,09-01 20:53:56.436  3506  3553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 20:53:56.437  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 20:53:56.438  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 20:53:56.441  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:53:56.441  3506  3553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 20:53:56.441  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:53:56.441  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 20:53:56.441  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:53:56.441  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:53:56.441  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:53:56.441  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:53:56.441  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 20:53:56.442  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:53:56.442  3506  3553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:53:56.442  3506  3553 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 20:53:56.444  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 20:53:56.445  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 20:53:56.445  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 20:53:56.445  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 20:53:56.445  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:53:56.446  3506  3553 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-01 20:53:56.446  3506  3553 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 20:53:56.446  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 20:53:56.446  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 20:53:56.446  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 20:53:56.446  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 20:53:56.447  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:53:56.447  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:53:56.448  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:53:56.448  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:53:56.448  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:53:56.448  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 20:53:56.448  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 20:53:56.448  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e removed from the list
09-01 20:53:56.448  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:53:56.448  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f removed from the list
09-01 20:53:56.448  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:53:56.448  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:53:56.449  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:53:56.449  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:53:56.450  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:53:56.450  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:53:56.450  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:53:56.450  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:53:56.452  3506  3553 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-01 20:53:56.452  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:53:56.452  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:53:56.452  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:53:56.453  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:53:56.453  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:53:56.453  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:53:56.453  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:53:56.453  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:53:56.453  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:53:56.453  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:53:56.453  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:53:56.453  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:53:56.453  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:53:56.453  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:53:56.454  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:53:56.454  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:53:56.454  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 20:53:56.454  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:53:56.460  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 20:53:56.460  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 20:53:56.460  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 20:53:56.460  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 20:53:56.460  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 20:53:56.460  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 20:53:56.460  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 20:53:56.460  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 20:53:56.460  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 20:53:56.460  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 20:53:56.460  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 20:53:56.461  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 20:53:56.461  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 20:53:56.461  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 20:53:56.461  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 20:53:56.461  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 20:53:56.461  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 20:53:56.461  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 20:53:56.461  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 20:53:56.461  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 20:53:56.461  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 20:53:56.461  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 20:53:56.461  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 20:53:56.462  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 20:53:56.462  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 20:53:56.462  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 20:53:56.462  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 20:53:56.462  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 20:53:56.462  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 20:53:56.462  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 20:53:56.462  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 20:53:56.462  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:53:56.462  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:53:56.462  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:53:56.462  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:53:56.463  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:53:56.463  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:53:56.463  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:53:56.463  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:53:56.463  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:53:56.463  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:53:56.463  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:53:56.463  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:53:56.463  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:53:56.463  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:53:56.464  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:53:56.464  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:53:56.464  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:53:56.464  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:53:56.464  3506  3553 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 20:53:56.465  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 20:53:56.466  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:53:56.466  3506  3553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 20:53:56.466  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:53:56.466  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 20:53:56.466  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:53:56.466  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:53:56.466  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:53:56.466  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:53:56.466  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:53:56.466  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:53:56.466  3506  3553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:53:56.466  3506  3553 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 20:53:56.466  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 20:53:56.466  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 20:53:56.467  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 20:53:56.467  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 20:53:56.467  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 20:53:56.467  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:53:56.468  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-01 20:53:56.469  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-01 20:53:56.469  3506  3553 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 20:53:56.469  3506  3553 I io.jxcore.node.ConnectionHelper: start: OK
09-01 20:53:56.469  3506  3506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-01 20:53:56.971  3506  3506 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 20:54:01.473  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:54:01.474  3506  3553 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
,09-01 20:54:01.479  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 20:54:01.480  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:54:01.480  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 20:54:01.480  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:01.481  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-01 20:54:01.481  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-01 20:54:01.481  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 20:54:01.482  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 20:54:01.482  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 20:54:01.484  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 20:54:01.486  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-01 20:54:01.487  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 20:54:01.488  3506  3506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 20:54:01.489  3506  3506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 20:54:01.489  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:01.490  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:01.489  3506  3506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 20:54:01.490  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 20:54:01.490  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:01.490  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:01.490  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:01.490  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:01.490  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:01.491  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:01.491  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:01.491  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:54:01.491  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:54:01.491  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:01.491  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:01.493  3506  3553 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 20:54:01.494  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 20:54:01.495  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:01.495  3506  3553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 20:54:01.495  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:01.495  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 20:54:01.495  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:01.495  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:01.495  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:01.495  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:01.495  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 20:54:01.496  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:54:01.496  3506  3553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:54:01.496  3506  3553 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 20:54:01.496  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 20:54:01.496  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 20:54:01.496  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-01 20:54:01.496  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 20:54:01.496  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 20:54:01.499  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:01.499  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-01 20:54:01.500  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-01 20:54:01.500  3506  3553 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 20:54:01.500  3506  3553 I io.jxcore.node.ConnectionHelper: start: OK
09-01 20:54:01.500  3506  3506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-01 20:54:02.002  3506  3506 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 20:54:06.501  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:54:06.502  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 20:54:06.502  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 20:54:06.502  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:06.503  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-01 20:54:06.503  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 20:54:06.503  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-01 20:54:06.504  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 20:54:06.504  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 20:54:06.504  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 20:54:06.506  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-01 20:54:06.508  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 20:54:06.508  3506  3506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 20:54:06.509  3506  3506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 20:54:06.510  3506  3506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 20:54:07.011  3506  3506 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-01 20:54:07.012  3506  3506 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 20:54:07.012  3506  3506 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-01 20:54:11.510  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:54:11.510  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:54:11.511  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 20:54:11.511  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:11.512  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.512  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 20:54:11.512  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
,09-01 20:54:11.513  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.513  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.513  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:11.514  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:11.515  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.516  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.517  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 20:54:11.517  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:54:11.518  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.518  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.521  3506  3553 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-01 20:54:11.523  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 20:54:11.524  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:54:11.524  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:54:11.524  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:11.525  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.525  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.525  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:11.526  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.526  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.526  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:11.527  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.527  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.527  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.527  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:11.530  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:54:11.530  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:54:11.530  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.530  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.531  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-01 20:54:11.531  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:54:11.531  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:54:11.531  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:54:11.532  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:11.532  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.532  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.532  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:11.532  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.532  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.532  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:11.532  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 20:54:11.532  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.532  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.532  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.533  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:54:11.533  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:54:11.533  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.533  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.533  3506  3553 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-01 20:54:11.534  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:54:11.534  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:54:11.534  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:54:11.534  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:11.534  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.534  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:11.534  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:11.534  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.534  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.534  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:11.534  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.535  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.535  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.535  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.535  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:54:11.535  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:54:11.535  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.535  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.536  3506  3553 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-01 20:54:11.536  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 20:54:11.536  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:54:11.536  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:54:11.536  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:11.536  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.536  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.537  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:11.537  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.537  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.537  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:11.537  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.537  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.537  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.537  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:11.537  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:54:11.537  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:54:11.538  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.538  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.538  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 20:54:11.539  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 20:54:11.539  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-01 20:54:11.539  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 20:54:11.539  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 20:54:11.539  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 20:54:11.539  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 20:54:11.539  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 20:54:11.539  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 20:54:11.539  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:54:11.539  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:54:11.539  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:54:11.540  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 20:54:11.540  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.540  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.540  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:11.540  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.540  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.540  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:11.540  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.540  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.540  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.540  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.541  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:54:11.541  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 20:54:11.541  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.541  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.542  3506  3553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 20:54:11.542  3506  3553 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 20:54:11.542  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 20:54:11.546  3506  3553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 20:54:11.546  3506  3553 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-01 20:54:11.547  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 20:54:11.547  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 20:54:11.547  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-01 20:54:11.547  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 20:54:11.547  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 20:54:11.547  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 20:54:11.547  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 20:54:11.547  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 20:54:11.547  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 20:54:11.548  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 20:54:11.548  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 20:54:11.548  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 20:54:11.548  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 20:54:11.548  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 20:54:11.548  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 20:54:11.549  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 20:54:11.549  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 20:54:11.549  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 20:54:11.549  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 20:54:11.549  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 20:54:11.549  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 20:54:11.549  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 20:54:11.549  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 20:54:11.549  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 20:54:11.549  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 20:54:11.549  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 20:54:11.549  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 20:54:11.550  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 20:54:11.550  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 20:54:11.550  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections,: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 20:54:11.550  3506  3553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-01 20:54:11.551  3506  3553 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 20:54:11.551  3506  3553 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-01 20:54:11.551  3506  3553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 20:54:11.552  3506  3553 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 20:54:11.552  3506  3553 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-01 20:54:11.552  3506  3553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 20:54:11.552  3506  3553 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 20:54:11.552  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-01 20:54:11.555  3506  3553 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
09-01 20:54:11.555  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-01 20:54:11.557  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-01 20:54:11.557  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-01 20:54:11.558  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-01 20:54:11.558  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-01 20:54:11.558  3506  3553 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-01 20:54:11.558  3506  3553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 20:54:11.558  3506  3553 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-01 20:54:11.559  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:54:11.559  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:54:11.559  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:54:11.559  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 20:54:11.559  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.560  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.560  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-01 20:54:11.561  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:11.561  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.562  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
,09-01 20:54:11.562  3506  3556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 350)
,09-01 20:54:11.562  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:11.563  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 20:54:11.563  3506  3556 E BluetoothDevice: Bluetooth is not enabled
,09-01 20:54:11.563  3506  3557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 350
09-01 20:54:11.563  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.563  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.563  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.564  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:54:11.564  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-01 20:54:11.564  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.564  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.566  3506  3556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 350)
09-01 20:54:11.567  3506  3553 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-01 20:54:11.568  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:54:11.569  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 20:54:11.569  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:54:11.569  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:11.569  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 20:54:11.569  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.569  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:11.569  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.570  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.570  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 20:54:11.570  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.570  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.570  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.570  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-01 20:54:11.570  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:54:11.570  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:54:11.570  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.570  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.571  3506  3553 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-01 20:54:11.571  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:54:11.572  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 20:54:11.572  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:54:11.572  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:11.572  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.572  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.572  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:11.572  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.572  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.572  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:11.572  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.572  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:11.572  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.572  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.573  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:54:11.573  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:54:11.573  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.573  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.573  3506  3553 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-01 20:54:11.574  3506  3553 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-01 20:54:11.574  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 20:54:11.574  3506  3553 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-01 20:54:11.574  3506  3553 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 20:54:11.574  3506  3553 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-01 20:54:11.574  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 20:54:11.574  3506  3553 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-01 20:54:11.574  3506  3553 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 20:54:11.574  3506  3553 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-01 20:54:11.574  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 20:54:11.574  3506  3553 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-01 20:54:11.574  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:54:11.575  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:54:11.575  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:54:11.575  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:11.575  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.575  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:11.575  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:11.575  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.575  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.575  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:11.575  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.575  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.576  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.576  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:11.576  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:54:11.576  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:54:11.576  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.576  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:11.577  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:11.578  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.578  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:11.578  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:11.578  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:11.578  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
,09-01 20:54:11.578  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:11.578  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:11.578  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:16.579  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 20:54:16.580  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:16.580  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:16.580  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:16.581  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:16.581  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:16.582  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 20:54:16.582  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 20:54:16.582  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 20:54:16.583  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 20:54:16.583  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:16.583  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:16.584  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:16.584  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 20:54:16.584  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
,09-01 20:54:16.585  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 20:54:16.585  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:16.585  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:16.586  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 20:54:16.586  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:16.587  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 20:54:16.587  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:54:16.588  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:16.588  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:16.593  3506  3553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-01 20:54:16.594  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 20:54:16.594  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
09-01 20:54:16.595  3506  3553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
,09-01 20:54:16.596  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 20:54:16.596  3506  3506 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-01 20:54:16.597  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:16.597  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-01 20:54:16.597  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:16.598  3506  3553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-01 20:54:16.598  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:16.598  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:16.599  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 20:54:16.599  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 20:54:16.599  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 20:54:16.598  3506  3506 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-01 20:54:16.600  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:16.600  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:16.601  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 20:54:16.601  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:16.601  3506  3506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 20:54:16.601  3506  3506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 20:54:16.601  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:54:16.601  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:54:16.601  3506  3506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 20:54:16.601  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:54:16.601  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:16.602  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:16.602  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:16.602  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:16.602  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:16.602  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:16.602  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:16.602  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:16.602  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:16.602  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:16.602  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:16.603  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:54:16.603  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:54:16.603  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:16.603  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:16.604  3506  3553 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-01 20:54:16.605  3506  3553 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-01 20:54:16.605  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 20:54:16.605  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 20:54:16.605  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 20:54:16.605  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:54:16.605  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:54:16.605  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:54:16.606  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:16.606  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 20:54:16.606  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:16.606  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:16.606  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:16.606  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:16.606  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:16.606  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 20:54:16.606  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:16.606  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:16.606  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:16.607  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:54:16.607  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:54:16.607  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 20:54:16.607  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:16.610  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:54:16.610  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:54:16.611  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 20:54:16.611  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:54:16.611  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:16.611  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:16.611  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
,09-01 20:54:16.611  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:16.611  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:16.611  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 20:54:16.611  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:16.611  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:16.611  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 20:54:16.612  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:16.612  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:54:16.612  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 20:54:16.612  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:16.612  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:16.613  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 20:54:16.613  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:54:16.614  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:54:16.614  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 20:54:16.614  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:16.614  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:16.614  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@357556e not in the list
09-01 20:54:16.614  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 20:54:16.614  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
09-01 20:54:16.614  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:16.614  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:16.614  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-01 20:54:16.614  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:16.614  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:16.615  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 20:54:16.615  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:54:16.615  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:54:16.615  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b140f not in the list
,09-01 20:54:16.616  3506  3553 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-01 20:54:16.616  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 20:54:16.617  3506  3553 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-01 20:54:16.617  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 20:54:16.617  3506  3553 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-01 20:54:16.617  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 20:54:16.620  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
09-01 20:54:16.620  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-01 20:54:16.621  3506  3553 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-01 20:54:16.621  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-01 20:54:16.621  3506  3553 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-01 20:54:16.621  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 20:54:16.621  3506  3553 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-01 20:54:16.621  3506  3553 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left,
09-01 20:54:16.622  3506  3553 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-01 20:54:16.622  3506  3553 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-01 20:54:16.623  3506  3553 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-01 20:54:16.623  3506  3553 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing,
09-01 20:54:16.623  3506  3553 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-01 20:54:16.623  3506  3553 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-01 20:54:16.624  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 20:54:16.625  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9dab821 added. We now have 3 listener(s),
09-01 20:54:16.625  3506  3553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 20:54:16.628   872  2827 D WifiService: setWifiEnabled: true pid=3506, uid=10000
09-01 20:54:16.629   872  2827 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 20:54:16.646   872   889 I ActivityManager: Start proc 3561:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-01 20:54:16.646   872  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-01 20:54:16.655  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:54:16.655  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:16.655  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:16.655  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 20:54:16.655  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:16.655  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:16.655  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:16.655  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:16.655  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:16.655  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:16.655  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:54:16.656  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:16.656  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:16.656  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:16.656  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 20:54:16.656  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:16.656  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:16.656  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:16.656  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:16.656  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:16.656  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:16.656  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:54:16.659   872  1307 D WifiConfigStore: loaded 0 passpoint configs
,09-01 20:54:16.660   872  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-01 20:54:16.660   872  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-01 20:54:16.661   872  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-01 20:54:16.661   872  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-01 20:54:16.661   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-01 20:54:16.661   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-01 20:54:16.673   872   885 I ActivityManager: Start proc 3572:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-01 20:54:16.704  3572  3572 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-01 20:54:16.736  3572  3572 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-01 20:54:16.743   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-01 20:54:16.743   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-01 20:54:16.744   372   871 D CommandListener: Setting iface cfg
,09-01 20:54:16.751   872  1943 I ActivityManager: Killing 2808:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-01 20:54:16.753   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '109 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 109 Failed to set address (No such device)'
09-01 20:54:16.753   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-01 20:54:16.754   872  1307 E native  : do suspend true
,09-01 20:54:16.801   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-01 20:54:16.801   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
09-01 20:54:16.802   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-01 20:54:16.806  1470  1470 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,09-01 20:54:16.807  1470  1470 W wpa_supplicant: wlan0: Failed to initiate AP scan
,09-01 20:54:16.816  3561  3561 D AdapterServiceConfig: Adding HeadsetService
09-01 20:54:16.816  3561  3561 D AdapterServiceConfig: Adding A2dpService
,09-01 20:54:16.816  3561  3561 D AdapterServiceConfig: Adding HidService
09-01 20:54:16.816  3561  3561 D AdapterServiceConfig: Adding HealthService
09-01 20:54:16.816  3561  3561 D AdapterServiceConfig: Adding PanService
09-01 20:54:16.816  3561  3561 D AdapterServiceConfig: Adding GattService
09-01 20:54:16.816  3561  3561 D AdapterServiceConfig: Adding BluetoothMapService
,09-01 20:54:16.863   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c4e1c27:true
,09-01 20:54:16.863  3561  3561 D BluetoothAdapterState: make() - Creating AdapterState
,09-01 20:54:16.865  3561  3561 I bt_bluedroid: init
09-01 20:54:16.865  3561  3600 I BluetoothAdapterState: Entering OffState
,09-01 20:54:16.867  3561  3601 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-01 20:54:16.869  3561  3601 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 20:54:16.869  3561  3601 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-01 20:54:16.869  3561  3601 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-01 20:54:16.870  3561  3561 I bt_bluedroid: get_profile_interface socket
09-01 20:54:16.871  3561  3561 I bt_bluedroid: get_profile_interface sdp
09-01 20:54:16.871  3561  3604 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 20:54:16.872  3561  3604 D BluetoothAdapterProperties: Name is: Nexus 6
09-01 20:54:16.873  3561  3573 I bt_bluedroid: config_hci_snoop_log
,09-01 20:54:16.874   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,09-01 20:54:16.876  3561  3600 D BluetoothAdapterState: Current state: OFF, message: 0
,09-01 20:54:16.876  3561  3600 D BluetoothAdapterProperties: Setting state to 14
09-01 20:54:16.876  3561  3600 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-01 20:54:16.877  3561  3600 D BluetoothBondStateMachine: make
,09-01 20:54:16.878  3561  3605 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-01 20:54:16.881  3561  3561 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-01 20:54:16.883  3561  3561 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
,09-01 20:54:16.883  3561  3561 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 20:54:16.883  3561  3600 I BluetoothAdapterState: Entering PendingCommandState
09-01 20:54:16.883  3561  3561 D BtGatt.GattService: Received start request. Starting profile...
,09-01 20:54:16.883  3561  3561 D BtGatt.GattService: start()
09-01 20:54:16.883  3561  3561 I bt_bluedroid: get_profile_interface gatt
09-01 20:54:16.884  3561  3561 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
09-01 20:54:16.884  3561  3561 D BtGatt.AdvertiseManager: advertise manager created
,09-01 20:54:16.888  3561  3561 V BluetoothAdapterState: isTurningOff()=false
,09-01 20:54:16.888  3561  3561 V BluetoothAdapterState: isTurningOn()=false
09-01 20:54:16.888  3561  3561 V BluetoothAdapterState: isBleTurningOn()=true
09-01 20:54:16.888  3561  3561 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:16.888  3561  3600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-01 20:54:16.888  3561  3600 I bt_bluedroid: enable
09-01 20:54:16.888  3561  3601 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-01 20:54:16.889  3561  3601 I bt_hci  : start_up
,09-01 20:54:16.896  3561  3601 I bt_vendor: alloc value 0xb3a1f189
,09-01 20:54:16.896  3561  3601 I bt_vendor: init
09-01 20:54:16.896  3561  3601 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-01 20:54:16.896  3561  3601 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-01 20:54:17.002  3561  3601 D bt_hci  : start_up starting async portion
,09-01 20:54:17.003  3561  3608 I bt_hci  : event_finish_startup
09-01 20:54:17.003  3561  3608 I bt_hci_h4: hal_open
09-01 20:54:17.003  3561  3608 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-01 20:54:17.010  3561  3608 I bt_userial_vendor: device fd = 51 open
,09-01 20:54:17.045  3561  3608 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 20:54:17.077  3561  3608 D bt_hwcfg: Chipset BCM4354A2
,09-01 20:54:17.077  3561  3608 D bt_hwcfg: Target name = [BCM4354A2]
09-01 20:54:17.078  3561  3608 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-01 20:54:17.103  3506  3506 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 20:54:17.738  3561  3608 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-01 20:54:17.739  3561  3608 D bt_hwcfg: Settlement delay -- 100 ms
09-01 20:54:17.739  3561  3608 I bt_hwcfg: Setting fw settlement delay to 100 
,09-01 20:54:17.808  1470  1470 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,09-01 20:54:17.809  1470  1470 W wpa_supplicant: wlan0: Failed to initiate AP scan
,09-01 20:54:17.856  3561  3608 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 20:54:17.857  3561  3608 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-01 20:54:17.887  3561  3608 I bt_hwcfg: vendor lib fwcfg completed
,09-01 20:54:17.887  3561  3608 I bt_vendor: firmware callback
09-01 20:54:17.888  3561  3608 I bt_hci  : firmware_config_callback
,09-01 20:54:17.899  3561  3610 I bt_btu  : btu_task pending for preload complete event
,09-01 20:54:17.899  3561  3610 I bt_btu_task: Bluetooth chip preload is complete
,09-01 20:54:17.899  3561  3610 I bt_btu  : btu_task received preload complete event
,09-01 20:54:17.913  3561  3610 I         : BTE_InitTraceLevels -- TRC_HCI
,09-01 20:54:17.913  3561  3610 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 20:54:17.914  3561  3610 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-01 20:54:17.914  3561  3610 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-01 20:54:17.914  3561  3610 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-01 20:54:17.914  3561  3610 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 20:54:17.915  3561  3610 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-01 20:54:17.915  3561  3610 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 20:54:17.915  3561  3610 I         : BTE_InitTraceLevels -- TRC_GAP
,09-01 20:54:17.915  3561  3610 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 20:54:17.916  3561  3610 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 20:54:17.916  3561  3610 I         : BTE_InitTraceLevels -- TRC_GATT
09-01 20:54:17.916  3561  3610 I         : BTE_InitTraceLevels -- TRC_SMP
,09-01 20:54:17.916  3561  3610 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 20:54:17.917  3561  3610 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-01 20:54:18.049  3561  3610 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb399cd9d
,09-01 20:54:18.049  3561  3610 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb399cd9d 
,09-01 20:54:18.063  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-01 20:54:18.071  3561  3604 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-01 20:54:18.074  3561  3604 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-01 20:54:18.074  3561  3604 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 20:54:18.077  3561  3604 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 20:54:18.084  3561  3604 D BluetoothAdapterProperties: Scan Mode:20
,09-01 20:54:18.084  3561  3604 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 20:54:18.084  3561  3604 D bt_hci  : do_postload posting postload work item
09-01 20:54:18.084  3561  3608 I bt_hci  : event_postload
,09-01 20:54:18.085  3561  3608 I bt_vendor: sco_config_cb,
09-01 20:54:18.085  3561  3608 I bt_hci  : sco_config_callback postload finished.
09-01 20:54:18.090  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:18.090  3561  3608 I bt_vendor: low_power_mode_cb
,09-01 20:54:18.093  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:18.094  3561  3604 D bt_bte_conf: Device ID record 1 : primary
09-01 20:54:18.094  3561  3604 D bt_bte_conf:   vendorId            = 000f
09-01 20:54:18.094  3561  3604 D bt_bte_conf:   vendorIdSource      = 0001
,09-01 20:54:18.094  3561  3604 D bt_bte_conf:   product             = 1200
09-01 20:54:18.094  3561  3604 D bt_bte_conf:   version             = 1436
09-01 20:54:18.094  3561  3604 D bt_bte_conf:   clientExecutableURL = 
09-01 20:54:18.094  3561  3604 D bt_bte_conf:   serviceDescription  = 
09-01 20:54:18.094  3561  3604 D bt_bte_conf:   documentationURL    = 
,09-01 20:54:18.094  3561  3604 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-01 20:54:18.094  3561  3601 D bt_stack_manager: event_start_up_stack finished
09-01 20:54:18.095  3561  3600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-01 20:54:18.095  3561  3600 D BluetoothAdapterProperties: Setting state to 15
09-01 20:54:18.095  3561  3600 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-01 20:54:18.096  3561  3600 I BluetoothAdapterState: Entering BleOnState
,09-01 20:54:18.103  3561  3600 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-01 20:54:18.103  3561  3600 D BluetoothAdapterProperties: Setting state to 11
09-01 20:54:18.103  3561  3600 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-01 20:54:18.109  3561  3561 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
,09-01 20:54:18.111  3561  3561 D HeadsetService: Received start request. Starting profile...
09-01 20:54:18.114  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:18.115  3561  3561 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 20:54:18.115  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:18.115  3561  3561 D HeadsetStateMachine: make
,09-01 20:54:18.130   872   885 I ActivityManager: Start proc 3618:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-01 20:54:18.138  3561  3561 D HeadsetStateMachine: max_hf_connections = 1
,09-01 20:54:18.139  3561  3561 I bt_bluedroid: get_profile_interface handsfree
,09-01 20:54:18.141  3561  3604 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-01 20:54:18.141  3561  3604 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-01 20:54:18.146   872  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-01 20:54:18.151  3561  3561 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
,09-01 20:54:18.152   872   872 D BluetoothA2dp: Proxy object connected
09-01 20:54:18.153  3561  3561 D A2dpService: Received start request. Starting profile...
09-01 20:54:18.153  3561  3561 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 20:54:18.153  3561  3561 I bt_bluedroid: get_profile_interface avrcp
,09-01 20:54:18.154   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-01 20:54:18.154   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 20:54:18.156  3561  3600 I BluetoothAdapterState: Entering PendingCommandState
09-01 20:54:18.161  3561  3561 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-01 20:54:18.161  3561  3561 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 20:54:18.161  3561  3561 D A2dpStateMachine: make
09-01 20:54:18.162   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-01 20:54:18.162  3561  3561 I bt_bluedroid: get_profile_interface a2dp
,09-01 20:54:18.163  3561  3604 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-01 20:54:18.164  3561  3631 D A2dpStateMachine: Enter Disconnected: -2
,09-01 20:54:18.164  3561  3561 I BluetoothHidServiceJni: classInitNative: succeeds
09-01 20:54:18.165  3561  3561 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
09-01 20:54:18.166  1353  1353 D BluetoothInputDevice: Proxy object connected
,09-01 20:54:18.166  1353  1353 D HidProfile: Bluetooth service connected
,09-01 20:54:18.167  3561  3561 D HidService: Received start request. Starting profile...
,09-01 20:54:18.167  3561  3561 I bt_bluedroid: get_profile_interface hidhost
,09-01 20:54:18.167  3561  3604 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397e3e5
09-01 20:54:18.167  3561  3604 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-01 20:54:18.167  3561  3561 D HidService: setHidService(): set to: null
09-01 20:54:18.167  3561  3561 V BluetoothAdapterState: isTurningOff()=false
09-01 20:54:18.167  3561  3561 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:18.167  3561  3561 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 20:54:18.167  3561  3561 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 20:54:18.168  3561  3617 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-01 20:54:18.169  3561  3561 I BluetoothHealthServiceJni: classInitNative: succeeds
09-01 20:54:18.169  3561  3561 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
09-01 20:54:18.170  3561  3561 D HealthService: Received start request. Starting profile...
,09-01 20:54:18.171  3561  3561 I bt_bluedroid: get_profile_interface health
09-01 20:54:18.172  3561  3561 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-01 20:54:18.172  3561  3561 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
09-01 20:54:18.173  1353  1353 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 20:54:18.173  3561  3561 D PanService: Received start request. Starting profile...
09-01 20:54:18.173  3561  3561 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 20:54:18.173  3561  3561 I bt_bluedroid: get_profile_interface pan
09-01 20:54:18.173  1353  1353 D PanProfile: Bluetooth service connected
,09-01 20:54:18.174  3561  3604 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-01 20:54:18.176  3561  3561 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
09-01 20:54:18.176  1353  1353 D BluetoothMap: Proxy object connected
09-01 20:54:18.176  3561  3561 D BluetoothMapService: Received start request. Starting profile...
09-01 20:54:18.176  3561  3561 D BluetoothMapService: start()
09-01 20:54:18.177  1353  1353 D MapProfile: Bluetooth service connected
09-01 20:54:18.177  1353  1353 D BluetoothMap: getConnectedDevices()
09-01 20:54:18.177  1353  1353 D BluetoothMap: Bluetooth is Not enabled
09-01 20:54:18.178  3561  3561 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-01 20:54:18.178  3561  3561 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-01 20:54:18.178  3561  3561 D BluetoothMapAppObserver: createReceiver()
09-01 20:54:18.179  3561  3561 D BluetoothMapAppObserver: initObservers()
09-01 20:54:18.179  3561  3561 D BluetoothMapAppObserver: getEnabledAccountItems()
09-01 20:54:18.183  3561  3561 V BluetoothAdapterState: isTurningOff()=false
09-01 20:54:18.183  3561  3561 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:18.183  3561  3561 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:18.183  3561  3561 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:18.183  3561  3561 V BluetoothAdapterState: isTurningOff()=false
,09-01 20:54:18.183  3561  3561 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:18.183  3561  3561 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:18.183  3561  3561 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:18.183  3561  3561 V BluetoothAdapterState: isTurningOff()=false
09-01 20:54:18.183  3561  3561 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:18.183  3561  3561 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:18.184  3561  3561 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:18.184  3561  3561 V BluetoothAdapterState: isTurningOff()=false
09-01 20:54:18.184  3561  3561 V BluetoothAdapterState: isTurningOn()=true
,09-01 20:54:18.184  3561  3561 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:18.184  3561  3561 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:18.184  3561  3561 V BluetoothAdapterState: isTurningOff()=false
09-01 20:54:18.184  3561  3561 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:18.184  3561  3561 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:18.184  3561  3561 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:18.184  3561  3600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-01 20:54:18.184  3561  3600 D BluetoothAdapterProperties: ScanMode =  20
09-01 20:54:18.184  3561  3600 D BluetoothAdapterProperties: State =  11
,09-01 20:54:18.185  3561  3600 D BluetoothAdapterProperties: Setting state to 12
09-01 20:54:18.185  3561  3600 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-01 20:54:18.185   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 20:54:18.185   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 20:54:18.185  3561  3604 D BluetoothAdapterProperties: Scan Mode:21
,09-01 20:54:18.186  3561  3604 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 20:54:18.186  1924  1937 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 20:54:18.186  3561  3600 I BluetoothAdapterState: Entering OnState
09-01 20:54:18.187  1353  1365 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 20:54:18.187  1353  1364 D BluetoothMap: onBluetoothStateChange: up=true
09-01 20:54:18.188   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 20:54:18.188  3506  3506 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-01 20:54:18.188  1353  2067 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 20:54:18.189  1353  1365 D BluetoothPan: onBluetoothStateChange on: true
09-01 20:54:18.189   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 20:54:18.191  3506  3506 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-01 20:54:18.191   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-01 20:54:18.191  3561  3561 D BluetoothMapService: onReceive
,09-01 20:54:18.191  3561  3561 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 20:54:18.191  3561  3561 D BluetoothMapService: STATE_ON
09-01 20:54:18.193  3506  3506 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-01 20:54:18.193  1353  1666 D LocalBluetoothProfileManager: Adding local A2DP profile
09-01 20:54:18.195  1353  1353 D BluetoothA2dp: Proxy object connected
09-01 20:54:18.196  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:18.196  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:18.196  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:18.196  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:18.196  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:54:18.196  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:18.196  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:18.196  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:18.197  1353  1666 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-01 20:54:18.198  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:54:18.201  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:18.201  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:18.201  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:18.201  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:18.201  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:54:18.201  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:18.201  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:18.201  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:18.203  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:54:18.204  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:18.204  3561  3561 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 20:54:18.205  3561  3561 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-01 20:54:18.205  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:18.206  3561  3561 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 20:54:18.207  3561  3561 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 20:54:18.208  3561  3561 D ObexServerSockets: Succeed to create listening sockets 
09-01 20:54:18.208  3561  3561 D ObexServerSockets0: startAccept()
09-01 20:54:18.208  3561  3561 D ObexServerSockets0: prepareForNewConnect()
09-01 20:54:18.209  3561  3561 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-01 20:54:18.209  3561  3561 D BluetoothSdpJni: SDP Create record success - handle: 0
09-01 20:54:18.210  3561  3637 D ObexServerSockets0: Accepting socket connection...
09-01 20:54:18.210  3561  3638 D ObexServerSockets0: Accepting socket connection...
09-01 20:54:18.211  3561  3561 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-01 20:54:18.211  3561  3561 D ObexServerSockets0: prepareForNewConnect()
09-01 20:54:18.214   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-01 20:54:18.224  3618  3618 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-01 20:54:18.231   872  1950 I ActivityManager: Killing 3001:com.google.android.gm/u0a78 (adj 15): empty #17
,09-01 20:54:18.286   872   889 D BluetoothHeadset: Proxy object connected
,09-01 20:54:18.287  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 20:54:18.287  1924  1938 D BluetoothHeadset: Proxy object connected
,09-01 20:54:18.288   872   889 D BluetoothHeadset: Proxy object connected
,09-01 20:54:18.290   872   889 D BluetoothHeadset: Proxy object connected
,09-01 20:54:18.298  1353  2067 D BluetoothHeadset: Proxy object connected
,09-01 20:54:18.299  1353  1353 D HeadsetProfile: Bluetooth service connected
,09-01 20:54:18.306   872  1950 I ActivityManager: Start proc 3639:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-01 20:54:18.334  3639  3639 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-01 20:54:18.542  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-01 20:54:18.564  3639  3639 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 20:54:18.564  3639  3639 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:18.564  3639  3639 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:18.564  3639  3639 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.r.e.b(PG:170)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:18.564  3639  3639 D StrictMode: StrictMode policy violation; ~duration=168 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.r.k.d(PG:583)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.r.e.b(PG:170)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArg,sCaller.run(ZygoteInit.java:726)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:18.564  3639  3639 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:18.564  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:18.565  3639  3639 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(,PG:2265)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:18.565  3639  3639 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:18.565  3639  3639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:18.575  3618  3618 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onRe,ceive:115 
,09-01 20:54:18.583  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 20:54:18.584   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ea12564:true
,09-01 20:54:18.592  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 20:54:18.592  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
09-01 20:54:18.592  1353  1353 D BluetoothPbap: Proxy object connected
09-01 20:54:18.593  1353  1353 D PbapServerProfile: Bluetooth service connected
,09-01 20:54:18.598   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 20:54:18.600  3618  3618 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-01 20:54:18.608  3618  3618 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-01 20:54:18.612  3561  3668 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 20:54:18.613   872  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-01 20:54:18.614   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-01 20:54:18.615   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 20:54:18.625   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 20:54:18.633   372   871 D CommandListener: Setting iface cfg
,09-01 20:54:18.640   872  1307 D WifiStateMachine: Start Dhcp Watchdog 1
09-01 20:54:18.644  3618  3618 D LocalBluetoothProfileManager: Adding local MAP profile
,09-01 20:54:18.645  3618  3618 D BluetoothMap: Create BluetoothMap proxy object
09-01 20:54:18.645   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-01 20:54:18.647  3561  3675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 20:54:18.648  3561  3675 I BtOppRfcommListener: Accept thread started.
,09-01 20:54:18.655  3618  3618 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-01 20:54:18.670   872  3678 D DhcpClient: Receive thread started
,09-01 20:54:18.674  3618  3618 D DockEventReceiver: finishStartingService: stopping service
,09-01 20:54:18.675  3618  3618 D BluetoothA2dp: Proxy object connected
,09-01 20:54:18.677  3618  3618 D BluetoothInputDevice: Proxy object connected
,09-01 20:54:18.677  3618  3618 D HidProfile: Bluetooth service connected
,09-01 20:54:18.679  3618  3618 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 20:54:18.679  3618  3618 D PanProfile: Bluetooth service connected
,09-01 20:54:18.680  3618  3618 D BluetoothMap: Proxy object connected
09-01 20:54:18.680  3618  3618 D MapProfile: Bluetooth service connected
09-01 20:54:18.680  3618  3618 D BluetoothMap: getConnectedDevices()
,09-01 20:54:18.681  3618  3618 D BluetoothPbap: Proxy object connected
,09-01 20:54:18.682  3618  3618 D PbapServerProfile: Bluetooth service connected
,09-01 20:54:18.683   872  1557 I ActivityManager: Killing 3197:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-01 20:54:18.715  3618  3629 D BluetoothHeadset: Proxy object connected
,09-01 20:54:18.718  3618  3618 D HeadsetProfile: Bluetooth service connected
,09-01 20:54:18.751   872  1307 E native  : do suspend false
,09-01 20:54:18.765   872  3673 D DhcpClient: Broadcasting DHCPDISCOVER
,09-01 20:54:18.783   872  3678 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 165295, domain null
,09-01 20:54:18.783   872  3673 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 165295 seconds
09-01 20:54:18.784   872  3673 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-01 20:54:18.796   872  3678 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-01 20:54:18.796   872  3673 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-01 20:54:18.797   372   871 D CommandListener: Setting iface cfg
,09-01 20:54:18.807   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-01 20:54:18.810   872  1307 E native  : do suspend true
,09-01 20:54:18.811   872  3673 D DhcpClient: Scheduling renewal in 86399s
,09-01 20:54:18.813  3639  3657 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-01 20:54:18.821   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-01 20:54:18.822   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-01 20:54:18.823   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-01 20:54:18.824   872  1309 D ConnectivityService: Adding iface wlan0 to network 100
09-01 20:54:18.824   872  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-01 20:54:18.852   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-01 20:54:18.853   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,09-01 20:54:18.854   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dac94c1:true
,09-01 20:54:18.854   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,09-01 20:54:18.856   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,09-01 20:54:18.857   872  1309 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,09-01 20:54:18.862   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-01 20:54:18.866   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 100
,09-01 20:54:18.867   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
09-01 20:54:18.867   872  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-01 20:54:18.868   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 20:54:18.868   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
09-01 20:54:18.868   872  1309 D ConnectivityService:    accepting network in place of null
,09-01 20:54:18.869   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-01 20:54:18.883   872  3670 D NetlinkSocketObserver: NeighborEvent{elapsedMs=370986, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-01 20:54:18.891   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 20:54:18.912   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 20:54:18.914   872  1309 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,09-01 20:54:18.917   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-01 20:54:18.918   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 20:54:18.920   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
09-01 20:54:18.923   872  1951 V BackupManagerService: Scheduling immediate backup pass
09-01 20:54:18.923   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-01 20:54:18.924   872   872 V BackupManagerService: Running a backup pass
,09-01 20:54:18.928   872  1327 V BackupManagerService: clearing pending backups
,09-01 20:54:18.932   872  1327 V PerformBackupTask: Beginning backup of 16 targets
,09-01 20:54:18.934  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:18.934  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:18.934  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:18.934  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:18.934  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:54:18.934  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 20:54:18.934  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:54:18.934  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 20:54:18.937  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 20:54:18.941  2014  2014 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-01 20:54:18.943  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:18.943  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:18.943  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:18.943  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:18.943  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:54:18.943  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 20:54:18.943  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:54:18.943  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 20:54:18.948   872  3669 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.88,2a00:1450:400d:802::200e
,09-01 20:54:18.964   872  1327 D PerformBackupTask: invokeAgentForBackup on @pm@
,09-01 20:54:18.966  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 20:54:18.970   872  1327 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,09-01 20:54:18.978  1753  1753 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 20:54:18.989   872  3669 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 18:54:18 GMT], X-Android-Received-Millis=[1472756058988], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472756058978]}
,09-01 20:54:18.990  1753  1753 D SystemUpdateService: onCreate
,09-01 20:54:18.991   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-01 20:54:18.991   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
09-01 20:54:18.992   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-01 20:54:18.992   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-01 20:54:18.994  1753  1753 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 20:54:18.999   872  1895 D AlarmManagerService: Setting time of day to sec=1472756059
,09-01 20:54:19.007   872  1895 W AlarmManagerService: Unable to set rtc to 1472756059: Invalid argument
,09-01 20:54:19.011  1753  3703 I SystemUpdateService: active receiver: enabled
,09-01 20:54:19.012  1753  3698 I CheckinService: Checking schedule, now: 1472756059012 next: 1472753764045
09-01 20:54:19.013  1753  3698 I CheckinService: active receiver: enabled
,09-01 20:54:19.015  1753  3703 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 20:54:19.019  1753  3698 I CheckinService: Preparing to send checkin request
,09-01 20:54:19.019  1753  3698 I EventLogService: Accumulating logs since 1472755719427
,09-01 20:54:19.020   872  3707 D GpsLocationProvider: NTP server returned: 1472756059007 (Thu Sep 01 20:54:19 GMT+02:00 2016) reference: 371105 certainty: 10 system time offset: -13
,09-01 20:54:19.020   872  3707 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
09-01 20:54:19.024  1753  3703 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-01 20:54:19.024  1753  3703 I SystemUpdateService: now status is 0 (complete)
,09-01 20:54:19.024  1753  3703 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 20:54:19.024  1753  3703 I SystemUpdateService: file has been verified
,09-01 20:54:19.027  1753  3698 I EventLogService: Opted in for usage reporting
,09-01 20:54:19.026  1753  3703 I SystemUpdateService: OTA package size = 12249756
,09-01 20:54:19.038  1753  3703 I SystemUpdateService: showing system update notification
,09-01 20:54:19.060  1753  1753 D SystemUpdateService: onDestroy
,09-01 20:54:19.074   872  1327 I BackupRestoreController: Getting widget state for user: 0
,09-01 20:54:19.074  1535  1535 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-01 20:54:19.079  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:19.081  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:19.094  1753  3715 I iu.SyncManager: SYNC; picasa accounts
,09-01 20:54:19.103  1753  3701 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,09-01 20:54:19.103  1753  3698 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,09-01 20:54:19.109  1753  1753 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-01 20:54:19.110  1753  1753 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-01 20:54:19.120  1753  3714 I MDM     : [151] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-01 20:54:19.120  1753  3714 W BaseAppContext: Using Auth Proxy for data requests.
,09-01 20:54:19.124  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 20:54:19.125  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-01 20:54:19.128  1753  3715 I iu.UploadsManager: num queued entries: 0
09-01 20:54:19.129  1753  3715 I iu.UploadsManager: num updated entries: 0
09-01 20:54:19.130  1753  3715 I iu.SyncManager: NEXT; no task
,09-01 20:54:19.133   872  1308 D WifiService: New client listening to asynchronous messages
,09-01 20:54:19.137   872  1950 I ActivityManager: Start proc 3723:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-01 20:54:19.152  1753  3714 V GoogleAuthProtoRequest: [151] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 20:54:19.160  1753  3698 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,09-01 20:54:19.165  2134  2180 W GmsBackupTransport: Unknown package in backup request: @pm@
,09-01 20:54:19.165  2134  2180 V GmsBackupTransport: starting performBackup for @pm@
09-01 20:54:19.173  3572  3708 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 20:54:19.182  2134  2180 V GmsBackupTransport: performBackup done for @pm@
09-01 20:54:19.189  3723  3723 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
09-01 20:54:19.191  3723  3723 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 20:54:19.202  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:19.207  3723  3723 D SprintDMHelper: simOperator: 
,09-01 20:54:19.207  3723  3723 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 20:54:19.219   872  1373 I ActivityManager: Start proc 3738:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-01 20:54:19.232  1535  2091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,09-01 20:54:19.233  1535  2091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
09-01 20:54:19.233  1535  2091 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:54:19.233  1535  2091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:54:19.240  1535  2376 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-01 20:54:19.240  1535  2376 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-01 20:54:19.240  1535  2376 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:54:19.240  1535  2376 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-01 20:54:19.241  1535  1549 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
09-01 20:54:19.241  1535  1549 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-01 20:54:19.241  1535  1549 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:54:19.241  1535  1549 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:54:19.248  1535  2091 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-01 20:54:19.248  1535  2091 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-01 20:54:19.248  1535  2091 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-01 20:54:19.248  1535  2091 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-01 20:54:19.248  1535  2091 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-01 20:54:19.248  1535  2091 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-01 20:54:19.248  1535  2091 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-01 20:54:19.261  2134  2829 W GmsBackupTransport: Error sending final backup to server: 
09-01 20:54:19.261  2134  2829 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
09-01 20:54:19.261  2134  2829 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
09-01 20:54:19.261  2134  2829 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
09-01 20:54:19.261  2134  2829 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
09-01 20:54:19.261  2134  2829 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
09-01 20:54:19.261  2134  2829 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
09-01 20:54:19.261  2134  2829 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
09-01 20:54:19.261  2134  2829 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-01 20:54:19.261  2134  2829 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-01 20:54:19.261  2134  2829 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-01 20:54:19.261  2134  2829 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-01 20:54:19.261  2134  2829 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-01 20:54:19.261  2134  2829 W GmsBackupTransport: 	... 1 more
,09-01 20:54:19.264  2134  2820 I GmsBackupTransport: Next backup will happen in 43199985 millis.
09-01 20:54:19.264   872  1327 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,09-01 20:54:19.281  3572  3708 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-01 20:54:19.281  3572  3708 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-01 20:54:19.281  3572  3708 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-01 20:54:19.281  3572  3708 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-01 20:54:19.281  3572  3708 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-01 20:54:19.281  3572  3708 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-01 20:54:19.281  3572  3708 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-01 20:54:19.281  3572  3708 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-01 20:54:19.281  3572  3708 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-01 20:54:19.281  3572  3708 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-01 20:54:19.281  3572  3708 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-01 20:54:19.281  3572  3708 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-01 20:54:19.286  1753  3714 E MDM     : [151] SitrepService.a: Error sending sitrep.
,09-01 20:54:19.310   872   882 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1753 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-01 20:54:19.364  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:19.416   872  1327 I BackupManagerService: Backup pass finished.
,09-01 20:54:19.433  1535  1549 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
09-01 20:54:19.433  1535  1549 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
09-01 20:54:19.433  1535  1549 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:54:19.433  1535  1549 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:54:19.450  1753  3698 W CheckinRequestBuilder: awaiting user notification for token
,09-01 20:54:19.467   872   884 I ActivityManager: Start proc 3760:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-01 20:54:19.491   872  2827 I ActivityManager: Start proc 3773:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-01 20:54:19.508   872   883 I ActivityManager: Start proc 3787:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,09-01 20:54:19.520  1535  2376 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-01 20:54:19.523  3760  3760 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
09-01 20:54:19.524  1535  2376 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-01 20:54:19.524  1535  2376 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:54:19.524  1535  2376 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:54:19.538  1753  3710 W DriveInitializer: Awaiting to be initialized
,09-01 20:54:19.539  1753  3801 W DriveInitializer: Background init thread started
,09-01 20:54:19.545  3787  3787 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-01 20:54:19.553  3286  3721 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-01 20:54:19.553  3286  3721 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at jdm.a(PG:82)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at jcs.o(PG:406)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at jcn.a(PG:1379)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at jcs.i(PG:143)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at blb.a(PG:3937)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at czp.a(PG:18188)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at czp.a(PG:9081)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at czq.run(PG:1686)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 20:54:19.553  3286  3721 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at jdj.a(PG:4091)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at jdj.a(PG:1125)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at jdm.a(PG:77)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	... 12 more
09-01 20:54:19.553  3286  3721 E HttpOperation: Caused by: faj: BadAuthentication
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at fal.a(PG:38)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	at jdj.a(PG:4089)
09-01 20:54:19.553  3286  3721 E HttpOperation: 	... 14 more
,09-01 20:54:19.569  3787  3787 I MultiDex: VM with version 2.1.0 has multidex support
,09-01 20:54:19.569  3787  3787 I MultiDex: install
09-01 20:54:19.569  3787  3787 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-01 20:54:19.573  3773  3773 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-01 20:54:19.587  2883  3772 I Babel   : connection state changed from UNKNOWN to CONNECTED
,09-01 20:54:19.629  3787  3787 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-01 20:54:19.632  1535  3711 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,09-01 20:54:19.672  3787  3787 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-01 20:54:19.713  1753  3801 W DriveInitializer: Background init thread ended
,09-01 20:54:19.725  1535  3750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-01 20:54:19.725  1535  3750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-01 20:54:19.725  1535  3750 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:54:19.725  1535  3750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:54:19.739  3286  3721 E HttpOperation: [getmobileexperiments] Unexpected exception
09-01 20:54:19.739  3286  3721 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at jdm.a(PG:82)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at jcs.o(PG:406)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at jcn.a(PG:1379)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at jcs.i(PG:143)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at hec.a(PG:42)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at hee.a(PG:102)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at czr.a(PG:65)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at kka.a(PG:108)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at czp.a(PG:19176)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at czp.a(PG:9081)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at czq.run(PG:1686)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 20:54:19.739  3286  3721 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at jdj.a(PG:4091)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at jdj.a(PG:1125)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at jdm.a(PG:77)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	... 15 more
09-01 20:54:19.739  3286  3721 E HttpOperation: Caused by: faj: BadAuthentication
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at fal.a(PG:38)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	at jdj.a(PG:4089)
09-01 20:54:19.739  3286  3721 E HttpOperation: 	... 17 more
,09-01 20:54:19.739  3286  3721 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-01 20:54:19.739  3286  3721 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at jdm.a(PG:82)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at jcs.o(PG:406)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at jcn.a(PG:1379)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at jcs.i(PG:143)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at hec.a(PG:42)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at hee.a(PG:102)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at czr.a(PG:65)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at kka.a(PG:108)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at czp.a(PG:19176)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at czp.a(PG:9081)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at czq.run(PG:1686)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at jdj.a(PG:4091)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at jdj.a(PG:1125)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at jdm.a(PG:77)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	... 15 more
09-01 20:54:19.739  3286  3721 E ExperimentLoader: Caused by: faj: BadAuthentication
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at fal.a(PG:38)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	at jdj.a(PG:4089)
09-01 20:54:19.739  3286  3721 E ExperimentLoader: 	... 17 more
,09-01 20:54:19.747  3760  3760 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-01 20:54:19.751  3787  3814 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,09-01 20:54:19.757  3760  3760 I BooksApp: Created application version: 3.6.9 (30609)
,09-01 20:54:19.819   376  1279 D WVCdm   : Instantiating CDM.
,09-01 20:54:19.819   376  1279 I WVCdm   : CdmEngine::OpenSession
09-01 20:54:19.820   376  1279 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,09-01 20:54:19.827   376  1279 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-01 20:54:19.840   376  1279 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
,09-01 20:54:19.840   376  1279 D DrmWidevineDash: Service_Initialize: starts!
09-01 20:54:19.840   376  1279 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-01 20:54:19.840   376  1279 D QSEECOMAPI: : App is not loaded in QSEE
,09-01 20:54:19.855  3787  3799 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-01 20:54:19.914   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 25080, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-01 20:54:19.914   872  1373 I ActivityManager: Killing 2610:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-01 20:54:19.926  3760  3827 I BooksSync: Starting books sync for 61035162, extras: ade
,09-01 20:54:19.982  3773  3773 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-01 20:54:19.982  3773  3773 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-01 20:54:19.982  3773  3773 I GAv4    :   adb logcat -s GAv4
,09-01 20:54:19.995  3773  3773 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-01 20:54:20.000  3773  3773 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-01 20:54:20.012  3773  3838 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-01 20:54:20.058   376  1279 D QSEECOMAPI: : Loaded image: APP id = 3
,09-01 20:54:20.064   376  1279 D DrmWidevineDash: Service_Initialize: ends! returns 0
09-01 20:54:20.064   376  1279 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2aa6000
09-01 20:54:20.064   376  1279 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2aa6000
,09-01 20:54:20.070   331   338 D DrmLibTime: got the req here! ret=0
09-01 20:54:20.070   331   338 D DrmLibTime: command id, time_cmd_id = 770
09-01 20:54:20.070   331   338 D DrmLibTime: time_getutcsec starts!
,09-01 20:54:20.070   331   338 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-01 20:54:20.070   331   338 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-01 20:54:20.070   331   338 D DrmLibTime: QSEE Time Listener: seconds: 1472756060
09-01 20:54:20.070   331   338 D DrmLibTime: QSEE Time Listener: nano seconds: 70829585
09-01 20:54:20.070   331   338 D DrmLibTime: time_getutcsec returns 0, sec = 1472756060; nsec = 70829585
09-01 20:54:20.070   331   338 D DrmLibTime: time_getutcsec finished! 
09-01 20:54:20.071   331   338 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-01 20:54:20.071   331   338 D DrmLibTime: before calling ioctl to read the next time_cmd
,09-01 20:54:20.076   376  1279 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,09-01 20:54:20.076   376  1279 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-01 20:54:20.076   376  1279 D DrmWidevineDash: hlos api version =  10
09-01 20:54:20.076   376  1279 D DrmWidevineDash: tz api version =  10
09-01 20:54:20.076   376  1279 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-01 20:54:20.077   376  1279 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,09-01 20:54:20.079  3048  3837 V KeepSync: Connecting to GoogleApiClient
,09-01 20:54:20.086   872  1967 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-01 20:54:20.098   376  1279 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,09-01 20:54:20.098   376  1279 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-01 20:54:20.098   376  1279 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb3000134
09-01 20:54:20.099   376  1279 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-01 20:54:20.099   376  1279 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
,09-01 20:54:20.099   376  1279 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb3b03018, dataLength=8
09-01 20:54:20.099   376  1279 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-01 20:54:20.105   376  1279 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb2be2c00, wrapped_rsa_key_length=1280
,09-01 20:54:20.109   376  1279 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,09-01 20:54:20.109   376  1279 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-01 20:54:20.109   376  1315 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-01 20:54:20.110   376  1315 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
09-01 20:54:20.110   376  1315 I WVCdm   : CdmEngine::GenerateKeyRequest
09-01 20:54:20.110   376  1315 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb3aff700, idLength=0xb2f00f2c
,09-01 20:54:20.120   376  1315 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,09-01 20:54:20.120   376  1315 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-01 20:54:20.121   376  1315 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-01 20:54:20.121   376  1315 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
09-01 20:54:20.121   376  1315 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
09-01 20:54:20.121   376  1315 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
09-01 20:54:20.122   376  1315 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
09-01 20:54:20.122   376  1315 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,09-01 20:54:20.122   376  1315 D DrmWidevineDash: hlos api version =  10
09-01 20:54:20.123   376  1315 D DrmWidevineDash: tz api version =  10
09-01 20:54:20.123   376  1315 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-01 20:54:20.123   376  1315 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,09-01 20:54:20.123   376  1315 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,09-01 20:54:20.123   376  1315 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
09-01 20:54:20.123   376  1315 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
09-01 20:54:20.124   376  1315 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-01 20:54:20.124   376  1315 D WVCdm   : PrepareKeyRequest: nonce=4255602393
09-01 20:54:20.124   376  1315 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4888c00
09-01 20:54:20.124   376  1315 D DrmWidevineDash: message_length=1624, signature=0xb60f7100, signature_length=3002077188
,09-01 20:54:20.188   376  1315 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
09-01 20:54:20.189   376   376 I WVCdm   : CdmEngine::CloseSession
09-01 20:54:20.189   376   376 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-01 20:54:20.189   376   376 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-01 20:54:20.189   376   376 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-01 20:54:20.190   376   376 D DrmWidevineDash: Service_Uninitialize: starts!
09-01 20:54:20.190   376   376 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-01 20:54:20.190   376   376 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
09-01 20:54:20.191   376   376 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
09-01 20:54:20.191   376   376 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-01 20:54:20.206  3773  3773 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-01 20:54:20.238  1535  3861 I VacuumService: Vacuum at: now=1472756060238 tag=VacuumService
09-01 20:54:20.239  1535  2828 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-01 20:54:20.239  1535  2828 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-01 20:54:20.239  1535  2828 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:54:20.239  1535  2828 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-01 20:54:20.251  1753  3854 V BaseAuthAsyncOperation: access token request failed
09-01 20:54:20.255  3048  3837 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-01 20:54:20.266  3773  3773 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-01 20:54:20.302  3773  3773 I LibraryLoader: Time to load native libraries: 21 ms (timestamps 2378-2399),
09-01 20:54:20.302  3773  3773 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 20:54:20.336  3773  3773 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {27c9e69}
,09-01 20:54:20.337  3773  3773 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 20:54:20.337  3773  3773 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-01 20:54:20.345  3773  3773 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-01 20:54:20.347  3773  3773 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-01 20:54:20.372  3773  3773 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-01 20:54:20.400  3773  3773 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-01 20:54:20.400  3773  3773 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-01 20:54:20.400  3773  3773 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 20:54:20.400  3773  3773 I Adreno  : Build Date                       : 10/20/15
09-01 20:54:20.400  3773  3773 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 20:54:20.400  3773  3773 I Adreno  : Local Branch                     : M14
09-01 20:54:20.400  3773  3773 I Adreno  : Remote Branch                    : 
09-01 20:54:20.400  3773  3773 I Adreno  : Remote Branch                    : 
09-01 20:54:20.400  3773  3773 I Adreno  : Reconstruct Branch               : 
,09-01 20:54:20.429  1535  3868 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
09-01 20:54:20.431  1535  3868 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-01 20:54:20.447  3760  3874 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-01 20:54:20.484  1535  2822 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-01 20:54:20.484  1535  2822 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-01 20:54:20.485  1535  2822 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:54:20.485  1535  2822 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:54:20.487  3875  3875 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,09-01 20:54:20.509  1535  2091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-01 20:54:20.509  1535  2091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-01 20:54:20.510  1535  2091 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:54:20.510  1535  2091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-01 20:54:20.515  3773  3890 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-01 20:54:20.520  3760  3874 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-01 20:54:20.521  3875  3875 I dex2oat : dex2oat took 34.305ms (threads: 4) arena alloc=77KB java alloc=67KB native alloc=1534KB free=1793KB
,09-01 20:54:20.523  3760  3827 E BooksSync: Soft error
09-01 20:54:20.523  3760  3827 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-01 20:54:20.523  3760  3827 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-01 20:54:20.523  3760  3827 E BooksSync: Sync error
09-01 20:54:20.523  3760  3827 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-01 20:54:20.523  3760  3827 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-01 20:54:20.525  3787  3799 W System  : ClassLoader referenced unknown path: 
09-01 20:54:20.530  3773  3773 I NSApplication: Starting up...
,09-01 20:54:20.539  3760  3827 I BooksSync: Finished books sync
,09-01 20:54:20.547   872  1950 I ActivityManager: Start proc 3895:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-01 20:54:20.547  3787  3799 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 20:54:20.547  3787  3799 I Adreno  : Build Date                       : 10/20/15
09-01 20:54:20.547  3787  3799 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 20:54:20.547  3787  3799 I Adreno  : Local Branch                     : M14
09-01 20:54:20.547  3787  3799 I Adreno  : Remote Branch                    : 
09-01 20:54:20.547  3787  3799 I Adreno  : Remote Branch                    : 
09-01 20:54:20.547  3787  3799 I Adreno  : Reconstruct Branch               : 
,09-01 20:54:20.555   872  1373 I ActivityManager: Killing 2981:android.process.acore/u0a5 (adj 15): empty #17
,09-01 20:54:20.558   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 25096, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-01 20:54:20.629  3787  3799 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 20:54:20.629  3787  3799 I Adreno  : Build Date                       : 10/20/15
09-01 20:54:20.629  3787  3799 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 20:54:20.629  3787  3799 I Adreno  : Local Branch                     : M14
09-01 20:54:20.629  3787  3799 I Adreno  : Remote Branch                    : 
09-01 20:54:20.629  3787  3799 I Adreno  : Remote Branch                    : 
09-01 20:54:20.629  3787  3799 I Adreno  : Reconstruct Branch               : 
,09-01 20:54:20.659  3895  3895 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-01 20:54:20.674  1535  2822 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-01 20:54:20.674  1535  2822 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-01 20:54:20.675  1535  2822 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 20:54:20.675  1535  2822 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:54:20.700   376  1316 I WVCdm   : CdmEngine::OpenSession
09-01 20:54:20.700   376  1316 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,09-01 20:54:20.701  3048  3837 E KeepSync: IOException
09-01 20:54:20.701  3048  3837 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-01 20:54:20.701  3048  3837 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-01 20:54:20.701  3048  3837 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-01 20:54:20.701  3048  3837 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-01 20:54:20.701  3048  3837 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-01 20:54:20.701  3048  3837 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-01 20:54:20.701  3048  3837 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-01 20:54:20.701  3048  3837 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-01 20:54:20.701  3048  3837 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-01 20:54:20.701  3048  3837 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-01 20:54:20.701  3048  3837 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195),
09-01 20:54:20.701  3048  3837 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-01 20:54:20.701  3048  3837 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-01 20:54:20.701  3048  3837 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-01 20:54:20.701  3048  3837 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-01 20:54:20.701  3048  3837 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-01 20:54:20.701  3048  3837 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-01 20:54:20.701  3048  3837 E KeepSync: 	... 10 more
09-01 20:54:20.701   376  1316 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-01 20:54:20.703  3048  3837 W KeepSync: Sync result 2
09-01 20:54:20.703   376  1316 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
09-01 20:54:20.703   376  1316 D DrmWidevineDash: Service_Initialize: starts!
,09-01 20:54:20.703   376  1316 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-01 20:54:20.703   376  1316 D QSEECOMAPI: : App is not loaded in QSEE
,09-01 20:54:20.711   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 25096, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-01 20:54:20.712   872  2827 I ActivityManager: Killing 3360:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-01 20:54:20.756  1535  3868 W Uploader:  no longer exists, so no auth token.
,09-01 20:54:20.923   376  1316 D QSEECOMAPI: : Loaded image: APP id = 3
,09-01 20:54:20.924   376  1316 D DrmWidevineDash: Service_Initialize: ends! returns 0
09-01 20:54:20.925   376  1316 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2aa6000
09-01 20:54:20.925   376  1316 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2aa6000
,09-01 20:54:20.932   331   338 D DrmLibTime: got the req here! ret=0
,09-01 20:54:20.932   331   338 D DrmLibTime: command id, time_cmd_id = 770
,09-01 20:54:20.932   331   338 D DrmLibTime: time_getutcsec starts!
09-01 20:54:20.932   331   338 D DrmLibTime: QSEE Time Listener: time_getutcsec
,09-01 20:54:20.932   331   338 D DrmLibTime: QSEE Time Listener: get_utc_seconds
,09-01 20:54:20.932   331   338 D DrmLibTime: QSEE Time Listener: seconds: 1472756060
09-01 20:54:20.932   331   338 D DrmLibTime: QSEE Time Listener: nano seconds: 932294097
09-01 20:54:20.932   331   338 D DrmLibTime: time_getutcsec returns 0, sec = 1472756060; nsec = 932294097
09-01 20:54:20.932   331   338 D DrmLibTime: time_getutcsec finished! 
09-01 20:54:20.932   331   338 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-01 20:54:20.932   331   338 D DrmLibTime: before calling ioctl to read the next time_cmd
09-01 20:54:20.937   376  1316 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
09-01 20:54:20.938   376  1316 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,09-01 20:54:20.938   376  1316 D DrmWidevineDash: hlos api version =  10
09-01 20:54:20.938   376  1316 D DrmWidevineDash: tz api version =  10
09-01 20:54:20.938   376  1316 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-01 20:54:20.938   376  1316 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,09-01 20:54:20.949   376  1316 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,09-01 20:54:20.949   376  1316 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-01 20:54:20.949   376  1316 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb2e02134
09-01 20:54:20.950   376  1316 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-01 20:54:20.950   376  1316 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
,09-01 20:54:20.950   376  1316 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb60cc9d8, dataLength=8
09-01 20:54:20.951   376  1316 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
09-01 20:54:20.951   376  1316 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb2ad9800, wrapped_rsa_key_length=1280
09-01 20:54:20.954   376  1316 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-01 20:54:20.954   376  1316 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-01 20:54:20.955   376   376 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-01 20:54:20.955   376   376 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
09-01 20:54:20.955   376   376 I WVCdm   : CdmEngine::GenerateKeyRequest
09-01 20:54:20.955   376   376 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb3aff780, idLength=0xbecd200c
,09-01 20:54:20.966   376   376 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,09-01 20:54:20.966   376   376 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-01 20:54:20.967   376   376 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-01 20:54:20.967   376   376 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
09-01 20:54:20.967   376   376 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
09-01 20:54:20.967   376   376 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
09-01 20:54:20.968   376   376 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1,
09-01 20:54:20.968   376   376 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-01 20:54:20.968   376   376 D DrmWidevineDash: hlos api version =  10
09-01 20:54:20.968   376   376 D DrmWidevineDash: tz api version =  10
09-01 20:54:20.968   376   376 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-01 20:54:20.968   376   376 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
09-01 20:54:20.969   376   376 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,09-01 20:54:20.969   376   376 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
09-01 20:54:20.969   376   376 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
09-01 20:54:20.970   376   376 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-01 20:54:20.970   376   376 D WVCdm   : PrepareKeyRequest: nonce=1769918818
09-01 20:54:20.970   376   376 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4889300
09-01 20:54:20.970   376   376 D DrmWidevineDash: message_length=1655, signature=0xb60f6d40, signature_length=3201114340
,09-01 20:54:21.005   872   883 I ActivityManager: Killing 3375:com.android.musicfx/u0a18 (adj 15): empty #17
,09-01 20:54:21.029   376   376 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-01 20:54:21.030   376  1316 I WVCdm   : CdmEngine::CloseSession
,09-01 20:54:21.030   376  1316 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-01 20:54:21.031   376  1316 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-01 20:54:21.031   376  1316 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-01 20:54:21.032   376  1316 D DrmWidevineDash: Service_Uninitialize: starts!
09-01 20:54:21.032   376  1316 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-01 20:54:21.032   376  1316 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
09-01 20:54:21.032   376  1316 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
09-01 20:54:21.032   376  1316 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-01 20:54:21.098  1535  1535 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-01 20:54:21.101  1535  2261 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-01 20:54:21.105  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:21.108  1753  1753 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-01 20:54:21.130  2228  2228 D WearableService: callingUid 10011, callindPid: 2228
,09-01 20:54:21.135  1753  3920 D LocationInitializer: Restart initialization of location
,09-01 20:54:21.135  2134  3919 E MDM     : [151] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-01 20:54:21.157  2134  2212 W GCoreFlp: No location to return for getLastLocation()
,09-01 20:54:21.157  1535  3921 W FusedLocationProvider: location=null
,09-01 20:54:21.237  3799  3799 W Binder_2: type=1400 audit(0.0:8): avc: denied { read } for name="/" dev="tmpfs" ino=11265 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=dir permissive=0
,09-01 20:54:21.296  1753  3698 I CheckinRequestBuilder: Classify the device as Phone.
,09-01 20:54:21.305  1753  3698 I EventLogService: Opted in for usage reporting
,09-01 20:54:21.525  1753  3698 W System.err: java.lang.Exception: Error converting session
,09-01 20:54:21.527  1753  3698 W System.err: 	at com.google.android.gms.org.conscrypt.a.log(SourceFile:302)
,09-01 20:54:21.527  1753  3698 W System.err: 	at com.google.android.gms.org.conscrypt.a.toSession(SourceFile:268)
09-01 20:54:21.527  1753  3698 W System.err: 	at com.google.android.gms.org.conscrypt.ClientSessionContext.getSession(SourceFile:87)
09-01 20:54:21.527  1753  3698 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getCachedClientSession(SourceFile:711)
09-01 20:54:21.527  1753  3698 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getSessionToReuse(SourceFile:377)
09-01 20:54:21.527  1753  3698 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.startHandshake(SourceFile:296)
09-01 20:54:21.528  1753  3698 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.a(SourceFile:258)
,09-01 20:54:21.528  1753  3698 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.createSocket(SourceFile:558)
09-01 20:54:21.529  1753  3698 W System.err: 	at com.android.okhttp.internal.http.SocketConnector.connectTls(SocketConnector.java:89)
09-01 20:54:21.530  1753  3698 W System.err: 	at com.android.okhttp.Connection.connect(Connection.java:143)
09-01 20:54:21.530  1753  3698 W System.err: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
,09-01 20:54:21.530  1753  3698 W System.err: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
09-01 20:54:21.530  1753  3698 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
09-01 20:54:21.531  1753  3698 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
09-01 20:54:21.531  1753  3698 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
09-01 20:54:21.531  1753  3698 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
,09-01 20:54:21.532  1753  3698 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:114)
09-01 20:54:21.532  1753  3698 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:245)
09-01 20:54:21.532  1753  3698 W System.err: 	at com.android.okhttp.internal.huc.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
09-01 20:54:21.532  1753  3698 W System.err: 	at com.android.okhttp.internal.huc.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java)
,09-01 20:54:21.533  1753  3698 W System.err: 	at com.google.android.gms.checkin.k.a(SourceFile:360)
09-01 20:54:21.533  1753  3698 W System.err: 	at com.google.android.gms.checkin.k.a(SourceFile:235)
09-01 20:54:21.533  1753  3698 W System.err: 	at com.google.android.gms.checkin.g.a(SourceFile:571)
09-01 20:54:21.534  1753  3698 W System.err: 	at com.google.android.gms.checkin.g.doInBackground(SourceFile:544)
09-01 20:54:21.534  1753  3698 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
,09-01 20:54:21.534  1753  3698 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 20:54:21.534  1753  3698 W System.err: 	at java.lang.Thread.run(Thread.java:818)
09-01 20:54:21.535  1753  3698 W System.err: Caused by: java.io.IOException: Invalid session data
,09-01 20:54:21.536  1753  3698 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.<init>(SourceFile:88)
,09-01 20:54:21.536  1753  3698 W System.err: 	at com.google.android.gms.org.conscrypt.a.toSession(SourceFile:267)
09-01 20:54:21.537  1753  3698 W System.err: 	... 25 more
,09-01 20:54:21.650  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 20:54:21.650  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5fd9334 added. We now have 4 listener(s)
,09-01 20:54:21.650  3506  3553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 20:54:21.662  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 20:54:21.662  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5fd9334 removed from the list
09-01 20:54:21.662  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:21.662  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:21.662  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:21.663  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 20:54:21.663  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e09b55d added. We now have 4 listener(s)
09-01 20:54:21.663  3506  3553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 20:54:21.665  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 20:54:21.665  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e09b55d removed from the list
09-01 20:54:21.665  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:21.665  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:21.665  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:21.666  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 20:54:21.666  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@252bed2 added. We now have 4 listener(s)
09-01 20:54:21.666  3506  3553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 20:54:21.671   872  1373 D WifiService: setWifiEnabled: false pid=3506, uid=10000
,09-01 20:54:21.672   872  1373 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 20:54:21.681  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 20:54:21.681  3561  3600 D BluetoothAdapterState: Current state: ON, message: 23
,09-01 20:54:21.681  3561  3600 D BluetoothAdapterProperties: Setting state to 13
,09-01 20:54:21.681  3561  3600 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 20:54:21.682  3561  3600 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 20:54:21.682  3561  3600 I BluetoothAdapterState: Entering PendingCommandState
09-01 20:54:21.685  3561  3561 D BluetoothMapService: onReceive
,09-01 20:54:21.685  3561  3561 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-01 20:54:21.685  3561  3561 D BluetoothMapService: STATE_TURNING_OFF
09-01 20:54:21.685  3561  3561 D BluetoothMapService: MAP Service closeService in
09-01 20:54:21.685  3561  3561 D BluetoothMapMasInstance0: MAP Service shutdown
09-01 20:54:21.685  3561  3561 D ObexServerSockets0: shutdown(block = true)
09-01 20:54:21.686  3561  3561 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-01 20:54:21.686  3561  3561 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-01 20:54:21.686  3561  3637 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-01 20:54:21.686  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-01 20:54:21.687  3561  3613 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-01 20:54:21.687  3561  3638 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-01 20:54:21.688  3561  3604 D BluetoothAdapterProperties: Scan Mode:20
09-01 20:54:21.688   872  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-01 20:54:21.689   872  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-01 20:54:21.689   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-01 20:54:21.689   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 20:54:21.689  3561  3600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-01 20:54:21.692  3561  3561 I BtOppRfcommListener: stopping Accept Thread
09-01 20:54:21.692  3561  3675 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 20:54:21.692  3561  3675 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-01 20:54:21.692  3618  3618 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 20:54:21.695  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.695  3506  3553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 20:54:21.695  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:21.695  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:21.695  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:21.695  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:21.695  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 20:54:21.695  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:54:21.695  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 20:54:21.697  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.697  3506  3553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 20:54:21.697  3561  3561 D HeadsetService: Received stop request...Stopping profile...
,09-01 20:54:21.697  3506  3553 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 20:54:21.700  3561  3561 D A2dpService: Received stop request...Stopping profile...
09-01 20:54:21.700  3618  3628 D BluetoothHeadset: Proxy object disconnected
09-01 20:54:21.700  3561  3631 D A2dpStateMachine: Exit Disconnected: -1
,09-01 20:54:21.701   872   872 D BluetoothHeadset: Proxy object disconnected
09-01 20:54:21.701   872   872 D BluetoothHeadset: Proxy object disconnected
09-01 20:54:21.702   872  1307 E native  : do suspend true
09-01 20:54:21.702  1353  1365 D BluetoothHeadset: Proxy object disconnected
09-01 20:54:21.702  3561  3561 D HidService: Received stop request...Stopping profile...
09-01 20:54:21.702  3561  3561 D HidService: Stopping Bluetooth HidService
09-01 20:54:21.702  1924  1937 D BluetoothHeadset: Proxy object disconnected
09-01 20:54:21.702   872   872 D BluetoothHeadset: Proxy object disconnected
09-01 20:54:21.702   872   872 D BluetoothA2dp: Proxy object disconnected
09-01 20:54:21.703  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:21.703  1753  3698 I CheckinTask: Sending checkin request (10343 bytes)
09-01 20:54:21.703  1353  1353 D BluetoothA2dp: Proxy object disconnected
09-01 20:54:21.703  1353  1353 D HeadsetProfile: Bluetooth service disconnected
09-01 20:54:21.704  1353  1353 D BluetoothInputDevice: Proxy object disconnected
09-01 20:54:21.704  1353  1353 D HidProfile: Bluetooth service disconnected
09-01 20:54:21.704  3561  3561 D HealthService: Received stop request...Stopping profile...
09-01 20:54:21.705  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:21.705  3561  3561 V BluetoothAdapterState: isTurningOff()=true
09-01 20:54:21.705  3561  3561 V BluetoothAdapterState: isTurningOn()=false
09-01 20:54:21.705  3561  3561 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:21.706  3561  3561 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:21.706  3561  3561 D PanService: Received stop request...Stopping profile...
09-01 20:54:21.707  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 20:54:21.708  3561  3561 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 20:54:21.708  3561  3561 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 20:54:21.709   872  3673 D DhcpClient: Clearing IP address
09-01 20:54:21.709   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-01 20:54:21.709  3561  3561 D BluetoothMapService: Received stop request...Stopping profile...
09-01 20:54:21.709  3561  3610 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 20:54:21.709  3561  3610 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 20:54:21.709  3561  3561 D BluetoothMapService: stop()
09-01 20:54:21.709  3561  3610 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 20:54:21.709  3561  3604 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-01 20:54:21.709  3561  3604 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-01 20:54:21.710  3561  3561 D BluetoothMapAppObserver: deinitObservers()
09-01 20:54:21.710  3561  3561 D BluetoothMapAppObserver: removeReceiver()
,09-01 20:54:21.710  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.710  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:21.710  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:21.710  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:21.710  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:21.710  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:21.710  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 20:54:21.710  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:54:21.710  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 20:54:21.710  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.711  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 20:54:21.711   372   871 D CommandListener: Setting iface cfg
09-01 20:54:21.711  3561  3561 V BluetoothAdapterState: isTurningOff()=true
09-01 20:54:21.711  3561  3561 V BluetoothAdapterState: isTurningOn()=false
,09-01 20:54:21.711  3561  3561 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:21.711  3561  3561 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:21.713  3561  3561 V BluetoothAdapterState: isTurningOff()=true
09-01 20:54:21.713  3561  3561 V BluetoothAdapterState: isTurningOn()=false
09-01 20:54:21.713  3561  3561 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:21.713  3561  3561 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:21.713  3561  3561 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 20:54:21.713  3561  3561 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 20:54:21.713  3561  3561 V BluetoothAdapterState: isTurningOff()=true
09-01 20:54:21.713  3561  3561 V BluetoothAdapterState: isTurningOn()=false
,09-01 20:54:21.713  3561  3610 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 20:54:21.714  3561  3610 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 20:54:21.714  3561  3610 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 20:54:21.714  3561  3610 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 20:54:21.714  1535  3755 V NativeCrypto: Read error: ssl=0x9b4cfc00: I/O error during system call, Connection timed out
09-01 20:54:21.714  3561  3610 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 20:54:21.714  3561  3610 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 20:54:21.714  3561  3604 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-01 20:54:21.714  3561  3604 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-01 20:54:21.715  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.715  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:21.715  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:21.715  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:21.715  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:21.715  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:21.715  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 20:54:21.715  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:54:21.715  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 20:54:21.713  3561  3561 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:21.715  3561  3561 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:21.715  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.715  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 20:54:21.715  3561  3561 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 20:54:21.716  3561  3604 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-01 20:54:21.716  1535  3755 V NativeCrypto: SSL shutdown failed: ssl=0x9b4cfc00: I/O error during system call, Broken pipe
09-01 20:54:21.717  3561  3561 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 20:54:21.717  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:21.722  3618  3618 D DockEventReceiver: finishStartingService: stopping service
09-01 20:54:21.723  1353  1353 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 20:54:21.723  1353  1353 D PanProfile: Bluetooth service disconnected
09-01 20:54:21.723  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:21.723  1353  1353 D BluetoothMap: Proxy object disconnected
09-01 20:54:21.723  1353  1353 D MapProfile: Bluetooth service disconnected
09-01 20:54:21.723  1353  1353 D BluetoothPbap: Proxy object disconnected
09-01 20:54:21.723  1353  1353 D PbapServerProfile: Bluetooth service disconnected
09-01 20:54:21.724   872  1950 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-01 20:54:21.724   872  3669 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-01 20:54:21.725  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.726  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:21.726  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:21.726  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:21.726  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:21.726  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:21.726  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:21.726  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:54:21.726  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 20:54:21.726   872  3669 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-01 20:54:21.726  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.726  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:54:21.727   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-01 20:54:21.728   872  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
09-01 20:54:21.729   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-01 20:54:21.729   872  1307 E native  : do suspend true
09-01 20:54:21.730  3561  3561 V BluetoothAdapterState: isTurningOff()=true
09-01 20:54:21.730   448   448 E Parcel  : Reading a NULL string not supported here.
09-01 20:54:21.730  3561  3561 V BluetoothAdapterState: isTurningOn()=false
09-01 20:54:21.730  3561  3561 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:21.732  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:54:21.732  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:21.732  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:21.732  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:21.732  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:21.732  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:21.732  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:21.732  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:54:21.732  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 20:54:21.733   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-01 20:54:21.733  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.733  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:54:21.730  3561  3561 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:21.733   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-01 20:54:21.734   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-01 20:54:21.734  3561  3561 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 20:54:21.734   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-01 20:54:21.734  3561  3561 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 20:54:21.737  3561  3561 D BluetoothMapService: MAP Service closeService in
09-01 20:54:21.737  3561  3561 V BluetoothAdapterState: isTurningOff()=true
09-01 20:54:21.737  3561  3561 V BluetoothAdapterState: isTurningOn()=false
,09-01 20:54:21.737  3561  3561 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:21.737  3561  3561 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:21.738  3561  3600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-01 20:54:21.738  3561  3600 D BluetoothAdapterProperties: Setting state to 15
09-01 20:54:21.738  3561  3600 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-01 20:54:21.738  3561  3600 I BluetoothAdapterState: Entering BleOnState
09-01 20:54:21.738  3618  3933 D BluetoothPan: onBluetoothStateChange on: false
09-01 20:54:21.738  3561  3561 D BluetoothMapService: cleanup()
09-01 20:54:21.739  3561  3561 D BluetoothMapService: MAP Service closeService in
09-01 20:54:21.739  3618  3628 D BluetoothMap: onBluetoothStateChange: up=false
09-01 20:54:21.740   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 20:54:21.740  3618  3629 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 20:54:21.740   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-01 20:54:21.740  3618  3933 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 20:54:21.741  1924  1938 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 20:54:21.741  1353  2067 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 20:54:21.741  1353  1365 D BluetoothMap: onBluetoothStateChange: up=false
09-01 20:54:21.741   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-01 20:54:21.741   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 20:54:21.742  1353  3934 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 20:54:21.742  1353  1364 D BluetoothPan: onBluetoothStateChange on: false
09-01 20:54:21.744  1753  3698 V NativeCrypto: Write error: ssl=0x930a0800: I/O error during system call, Connection timed out
09-01 20:54:21.744   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-01 20:54:21.744  1753  3698 E CheckinTask: SSL error, attempting time correction: javax.net.ssl.SSLException: Write error: ssl=0x930a0800: I/O error during system call, Connection timed out
09-01 20:54:21.745   872  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-01 20:54:21.753  3618  3618 D HeadsetProfile: Bluetooth service disconnected
09-01 20:54:21.757   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
09-01 20:54:21.759  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.759  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:21.759  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:21.759  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:21.759  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:21.759  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:21.759  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:21.759  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:21.759  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:21.760  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.760  3618  3618 D BluetoothA2dp: Proxy object disconnected
,09-01 20:54:21.760  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:54:21.761  3618  3618 D BluetoothInputDevice: Proxy object disconnected
09-01 20:54:21.761  3618  3618 D HidProfile: Bluetooth service disconnected
09-01 20:54:21.762  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.762  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:21.762  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:21.762  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:21.762  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:21.762  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:21.762  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:21.762  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:21.762  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:21.762  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.762  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:54:21.764  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.764  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:21.764  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:21.764  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:21.764  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:21.764  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:21.764  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:21.764  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:21.764  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:21.764  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:21.764  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:54:21.767   872  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 20:54:21.780   872  3678 D DhcpClient: Receive thread stopped
09-01 20:54:21.782  1353  2067 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 20:54:21.783  3618  3628 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 20:54:21.783  1753  3698 I AuthdNetTimeProvider: Attempting to get network time from https://android.clients.google.com/checkin
09-01 20:54:21.783  3618  3629 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 20:54:21.783   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 20:54:21.784  1353  1365 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 20:54:21.784  3561  3600 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-01 20:54:21.784  3561  3600 D BluetoothAdapterProperties: Setting state to 16
09-01 20:54:21.784  3561  3600 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-01 20:54:21.785  3561  3600 D BluetoothAdapterProperties: onBleDisable
09-01 20:54:21.785  3561  3601 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-01 20:54:21.786  3561  3610 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-01 20:54:21.787  3561  3610 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 20:54:21.787  3561  3604 D BluetoothAdapterProperties: Scan Mode:20
09-01 20:54:21.787  3561  3600 I BluetoothAdapterState: Entering PendingCommandState
,09-01 20:54:21.788  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:21.789  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:21.790  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:21.791  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:21.792  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:21.793  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:21.799  1753  3698 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.ConnectException: failed to connect to android.clients.google.com/216.58.210.14 (port 443) after 120000ms: connect failed: ENETUNREACH (Network is unreachable)
09-01 20:54:21.800  2134  2308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 20:54:21.806   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-01 20:54:21.808  1753  3698 I CheckinService: Checking schedule, now: 1472756061808 next: 1472756071799
09-01 20:54:21.808  1753  3698 I CheckinService: active receiver: disabled
09-01 20:54:21.819  3618  3618 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 20:54:21.823  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 20:54:21.826   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-01 20:54:21.827   872  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-01 20:54:21.827   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-01 20:54:21.830   872   889 D Tethering: MasterInitialState.processMessage what=3
09-01 20:54:21.831  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:21.833  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:21.835  2014  2014 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-01 20:54:21.836  1535  2479 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-01 20:54:21.837  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-01 20:54:21.838  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:21.838  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-01 20:54:21.844  1753  1753 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-01 20:54:21.846  1753  1753 D SystemUpdateService: onCreate
09-01 20:54:21.848  1753  1753 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 20:54:21.850  1753  3947 I SystemUpdateService: active receiver: enabled
09-01 20:54:21.853  3618  3618 D DockEventReceiver: finishStartingService: stopping service
09-01 20:54:21.854  1753  3947 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-01 20:54:21.861  1753  1753 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-01 20:54:21.862  1753  3715 I iu.UploadsManager: num queued entries: 0
09-01 20:54:21.862  1753  3715 I iu.UploadsManager: num updated entries: 0
09-01 20:54:21.862  1753  3715 I iu.SyncManager: NEXT; no task
09-01 20:54:21.867  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-01 20:54:21.868  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-01 20:54:21.869  1535  3868 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-01 20:54:21.869  1535  3868 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-01 20:54:21.869  1535  3868 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:54:21.869  1535  3868 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-01 20:54:21.869  1753  3947 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-01 20:54:21.869  1753  3947 I SystemUpdateService: now status is 0 (complete)
09-01 20:54:21.869  1753  3947 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 20:54:21.870  1753  3947 I SystemUpdateService: file has been verified
09-01 20:54:21.870  1753  3947 I SystemUpdateService: OTA package size = 12249756
09-01 20:54:21.870  3723  3723 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-01 20:54:21.873  3723  3723 D SprintDMHelper: simOperator: 
09-01 20:54:21.873  3723  3723 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 20:54:21.879  1753  3947 I SystemUpdateService: showing system update notification
,09-01 20:54:21.882  1535  3868 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-01 20:54:21.882  1535  3868 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-01 20:54:21.882  1535  3868 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-01 20:54:21.882  1535  3868 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-01 20:54:21.882  1535  3868 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-01 20:54:21.882  1535  3868 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-01 20:54:21.882  1535  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-01 20:54:21.882  1535  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-01 20:54:21.882  1535  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-01 20:54:21.882  1535  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-01 20:54:21.882  1535  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-01 20:54:21.882  1535  3868 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-01 20:54:21.882  1535  3868 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-01 20:54:21.886   372   871 E Netd    : netlink response contains error (No such file or directory)
,09-01 20:54:21.887   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-01 20:54:21.894  2883  3951 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-01 20:54:21.897  1535  3868 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/74.125.206.95 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
09-01 20:54:21.897  1753  1753 D SystemUpdateService: onDestroy
,09-01 20:54:21.988  3561  3604 I bt_hci  : shut_down
,09-01 20:54:22.003  3561  3608 D bt_hwcfg: hw_epilog_process
,09-01 20:54:22.004  3561  3608 I bt_vendor: low_power_mode_cb
,09-01 20:54:22.025  3561  3608 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-01 20:54:22.026  3561  3608 I bt_vendor: epilog_cb
,09-01 20:54:22.026  3561  3608 I bt_hci  : epilog_finished_callback
,09-01 20:54:22.029  3561  3604 I bt_hci_h4: hal_close
09-01 20:54:22.030  3561  3604 I bt_userial_vendor: device fd = 51 close
,09-01 20:54:22.158  3561  3601 D bt_stack_manager: event_shut_down_stack finished.
,09-01 20:54:22.159  3561  3600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-01 20:54:22.164  3561  3600 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-01 20:54:22.164  3561  3561 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 20:54:22.166  3561  3561 D BtGatt.GattService: Received stop request...Stopping profile...
09-01 20:54:22.166  3561  3561 D BtGatt.GattService: stop()
,09-01 20:54:22.167  3561  3561 D BtGatt.AdvertiseManager: advertise clients cleared
,09-01 20:54:22.171  3561  3561 V BluetoothAdapterState: isTurningOff()=false
,09-01 20:54:22.171  3561  3561 V BluetoothAdapterState: isTurningOn()=false
09-01 20:54:22.171  3561  3561 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:22.172  3561  3561 V BluetoothAdapterState: isBleTurningOff()=true
,09-01 20:54:22.173  3561  3600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-01 20:54:22.173  3561  3600 D BluetoothAdapterProperties: Setting state to 10
09-01 20:54:22.173  3561  3600 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-01 20:54:22.177  3561  3600 I BluetoothAdapterState: Entering OffState
,09-01 20:54:22.178   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-01 20:54:22.204  3561  3561 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-01 20:54:22.205  3561  3561 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-01 20:54:22.205  3561  3601 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-01 20:54:22.215  3561  3601 D bt_stack_manager: event_clean_up_stack finished.
,09-01 20:54:22.215  3561  3561 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-01 20:54:22.224  3561  3561 I art     : System.exit called, status: 0
,09-01 20:54:22.224  3561  3561 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-01 20:54:22.262   872   883 I ActivityManager: Process com.android.bluetooth (pid 3561) has died
,09-01 20:54:24.780  3760  3822 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-01 20:54:26.178   872  1967 I ActivityManager: Killing 3325:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-01 20:54:26.239   872  1967 I ActivityManager: Killing 3399:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,09-01 20:54:26.702   872  1932 D WifiService: setWifiEnabled: true pid=3506, uid=10000
,09-01 20:54:26.702   872  1932 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 20:54:26.723   872  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-01 20:54:26.724  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:26.725  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:26.725  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:26.725  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:26.725  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:26.725  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:26.725  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:26.725  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:26.725  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:26.725  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:26.725  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:54:26.727  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:26.727  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:26.727  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:26.727  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:26.727  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:26.727  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:26.727  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:26.727  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:26.727  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:26.727  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:54:26.728  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:54:26.729  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:26.729  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:26.729  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:26.729  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:26.729  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:26.729  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:26.729  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:26.729  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:26.729  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:26.729  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:26.729  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:54:26.739   872  1307 D WifiConfigStore: loaded 0 passpoint configs
,09-01 20:54:26.740   872  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-01 20:54:26.741   872  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-01 20:54:26.742   872  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-01 20:54:26.742   872  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-01 20:54:26.742   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-01 20:54:26.742   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-01 20:54:26.764   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-01 20:54:26.815   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device),
,09-01 20:54:26.820   372   871 D CommandListener: Setting iface cfg
,09-01 20:54:26.823   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-01 20:54:26.824   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-01 20:54:26.824   872  1307 E native  : do suspend true
,09-01 20:54:26.849   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-01 20:54:26.849   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 20:54:26.850   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-01 20:54:26.878   872  1309 D ConnectivityService: handlePromptUnvalidated 100
,09-01 20:54:28.227   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-01 20:54:28.337   872  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.94 rxSuccessRate=6.00 delta 1000 -> 994
,09-01 20:54:28.340   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-01 20:54:28.340   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 20:54:28.361   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-01 20:54:28.414   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-01 20:54:28.415  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-01 20:54:28.850  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-01 20:54:28.904  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-01 20:54:28.906  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-01 20:54:28.913   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 20:54:28.934   872  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-01 20:54:28.934   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 20:54:28.935   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-01 20:54:28.952   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 20:54:28.965   372   871 D CommandListener: Setting iface cfg
09-01 20:54:28.967   872  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,09-01 20:54:28.974   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-01 20:54:28.995   872  3965 D DhcpClient: Receive thread started
,09-01 20:54:29.094   872  1307 E native  : do suspend false
,09-01 20:54:29.120   872  3673 D DhcpClient: Broadcasting DHCPDISCOVER
,09-01 20:54:29.146   872  3965 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172790, domain null
,09-01 20:54:29.148   872  3673 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172790 seconds
,09-01 20:54:29.153   872  3673 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-01 20:54:29.188   872  3965 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-01 20:54:29.189   872  3673 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-01 20:54:29.197   372   871 D CommandListener: Setting iface cfg
,09-01 20:54:29.208   872  3673 D DhcpClient: Scheduling renewal in 86399s
,09-01 20:54:29.209   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-01 20:54:29.213   872  1307 E native  : do suspend true
,09-01 20:54:29.234   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-01 20:54:29.237   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-01 20:54:29.238   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-01 20:54:29.241   872  1309 D ConnectivityService: Adding iface wlan0 to network 101
,09-01 20:54:29.247   872  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-01 20:54:29.310   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-01 20:54:29.311   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-01 20:54:29.314   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-01 20:54:29.320   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-01 20:54:29.324   872  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-01 20:54:29.341   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-01 20:54:29.347   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-01 20:54:29.347   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-01 20:54:29.347   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-01 20:54:29.348   872  1309 D ConnectivityService:    accepting network in place of null
09-01 20:54:29.348   872  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-01 20:54:29.348   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-01 20:54:29.350   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 20:54:29.360   872  3964 D NetlinkSocketObserver: NeighborEvent{elapsedMs=381457, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-01 20:54:29.385   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 20:54:29.433   872  3963 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.92,2a00:1450:400d:802::200e
,09-01 20:54:29.445   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 20:54:29.455   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-01 20:54:29.455   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 20:54:29.460   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-01 20:54:29.463   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-01 20:54:29.466   872  3963 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 18:54:29 GMT], X-Android-Received-Millis=[1472756069466], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472756069457]}
,09-01 20:54:29.481  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:54:29.481  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:29.481  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:29.481  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:29.481  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:29.481  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:29.481  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 20:54:29.481  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:54:29.481  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 20:54:29.481  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:54:29.482  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 20:54:29.485   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-01 20:54:29.485   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-01 20:54:29.485   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-01 20:54:29.487   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-01 20:54:29.488  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:54:29.489  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:29.489  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:29.489  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:29.489  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:29.489  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:29.489  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 20:54:29.489  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:54:29.489  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 20:54:29.491  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:54:29.491  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 20:54:29.495  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:29.495  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:29.495  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:29.495  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:29.495  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:29.495  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:29.495  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 20:54:29.495  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:54:29.495  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 20:54:29.495  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:29.495  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 20:54:29.502  1753  1753 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 20:54:29.504  2014  2014 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-01 20:54:29.508  1753  1753 D SystemUpdateService: onCreate
,09-01 20:54:29.512  1753  1753 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 20:54:29.527  1753  3975 I SystemUpdateService: active receiver: enabled
,09-01 20:54:29.532  1753  1753 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-01 20:54:29.540  1753  3715 I iu.UploadsManager: num queued entries: 0
,09-01 20:54:29.540  1753  3715 I iu.UploadsManager: num updated entries: 0
,09-01 20:54:29.543  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 20:54:29.544  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 20:54:29.546  3723  3723 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 20:54:29.560  1753  3977 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-01 20:54:29.560  1753  3977 W BaseAppContext: Using Auth Proxy for data requests.
,09-01 20:54:29.562  1753  3977 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 20:54:29.568  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:29.569  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:29.570  3723  3723 D SprintDMHelper: simOperator: 
09-01 20:54:29.571  3723  3723 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-01 20:54:29.553  1753  3975 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 20:54:29.541  1753  3715 I iu.SyncManager: NEXT; no task
,09-01 20:54:29.586  1753  3975 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-01 20:54:29.586  1753  3975 I SystemUpdateService: now status is 0 (complete)
09-01 20:54:29.586  1753  3975 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 20:54:29.586  1753  3975 I SystemUpdateService: file has been verified
09-01 20:54:29.586  1753  3975 I SystemUpdateService: OTA package size = 12249756
,09-01 20:54:29.636  1753  3975 I SystemUpdateService: showing system update notification
,09-01 20:54:29.692  2883  3980 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-01 20:54:29.707  1753  1753 D SystemUpdateService: onDestroy
,09-01 20:54:29.709  1535  2828 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-01 20:54:29.709  1535  2828 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-01 20:54:29.709  1535  2828 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 20:54:29.709  1535  2828 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:54:29.728  1753  3977 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-01 20:54:29.859  2716  2726 D Finsky  : [172] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-01 20:54:29.891  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:29.941  1535  2822 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-01 20:54:29.941  1535  2822 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-01 20:54:29.941  1535  2822 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:54:29.941  1535  2822 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:54:29.993  2716  2726 D Finsky  : [172] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-01 20:54:30.454   872  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-01 20:54:31.365  1753  1760 E System  : Uncaught exception thrown by finalizer
,09-01 20:54:31.365  1753  1760 E System  : java.lang.NullPointerException: ssl_session == null
09-01 20:54:31.365  1753  1760 E System  : 	at com.google.android.gms.org.conscrypt.NativeCrypto.SSL_SESSION_free(Native Method)
09-01 20:54:31.365  1753  1760 E System  : 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.finalize(SourceFile:485)
09-01 20:54:31.365  1753  1760 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:202)
09-01 20:54:31.365  1753  1760 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:185)
09-01 20:54:31.365  1753  1760 E System  : 	at java.lang.Thread.run(Thread.java:818)
,09-01 20:54:31.727   872  1373 D WifiService: setWifiEnabled: false pid=3506, uid=10000
,09-01 20:54:31.728   872  1373 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 20:54:31.750  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-01 20:54:31.756   872  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-01 20:54:31.756   872  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-01 20:54:31.757   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-01 20:54:31.757   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 20:54:31.766   872  1307 E native  : do suspend true
,09-01 20:54:31.776   872  3673 D DhcpClient: Clearing IP address
,09-01 20:54:31.776   372   871 D CommandListener: Setting iface cfg
,09-01 20:54:31.781   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-01 20:54:31.782   872  3965 D DhcpClient: Receive thread stopped
,09-01 20:54:31.786  1535  3986 V NativeCrypto: Read error: ssl=0x9b4cfc00: I/O error during system call, Connection timed out
,09-01 20:54:31.791  1535  3986 V NativeCrypto: SSL shutdown failed: ssl=0x9b4cfc00: I/O error during system call, Broken pipe
,09-01 20:54:31.800   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-01 20:54:31.800   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-01 20:54:31.804   448   448 E Parcel  : Reading a NULL string not supported here.,
,09-01 20:54:31.805   872  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-01 20:54:31.814   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 20:54:31.816   872  1307 E native  : do suspend true
,09-01 20:54:31.820   872  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-01 20:54:31.849   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 20:54:31.886   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 20:54:31.886   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-01 20:54:31.888   872  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-01 20:54:31.888   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 20:54:31.890   872  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-01 20:54:31.897   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-01 20:54:31.904  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:54:31.904  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:31.904  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:31.904  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:31.904  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:31.904  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:31.904  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:31.904  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:31.904  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:31.904  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:31.904  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:54:31.910  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:31.910  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:31.910  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:31.910  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:31.910  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:31.910  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:31.910  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:31.910  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:31.910  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:31.910  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:54:31.910  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:54:31.911  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:31.911  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:31.911  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:31.911  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:31.911  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:54:31.911  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:31.911  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:31.911  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:31.911  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:31.911  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:31.911  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:54:31.920   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 20:54:31.923  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:31.923  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:31.923  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:31.923  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:31.923  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:31.923  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:31.923  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:31.923  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:31.923  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:31.923  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:31.923  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:54:31.925  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 20:54:31.925  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:31.925  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:31.925  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:31.925  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:31.925  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:31.925  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:31.925  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:31.925  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:31.925  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:31.925  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:54:31.926  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:31.926  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:31.926  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:31.926  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:31.926  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:31.926  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:31.926  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:31.926  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:31.926  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:31.926  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:31.926  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:54:31.930   872  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 20:54:31.932  2014  2014 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-01 20:54:31.947  2134  2308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 20:54:31.948   872  1950 I ActivityManager: Start proc 4000:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-01 20:54:31.975   372   871 E Netd    : netlink response contains error (No such file or directory)
,09-01 20:54:31.976   872  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-01 20:54:31.985  4000  4000 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-01 20:54:31.990   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-01 20:54:32.014  2134  2134 V GmsNetworkLocationProvi: DISABLE
,09-01 20:54:32.017  4000  4000 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-01 20:54:32.021  2134  2134 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,09-01 20:54:32.043  1753  4020 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-01 20:54:32.048  1753  4020 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-01 20:54:32.049  2014  4021 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-01 20:54:32.080  1753  2340 I Icing   : updateResources: need to parse f{com.google.android.gms}
,09-01 20:54:32.102  2014  4021 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 53 ms] updated apps [took 53 ms] 
,09-01 20:54:32.111  1753  1753 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-01 20:54:32.113  1753  1753 D SystemUpdateService: onCreate
,09-01 20:54:32.116  1753  1753 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 20:54:32.118  1753  4025 I SystemUpdateService: active receiver: enabled
,09-01 20:54:32.124  1753  4025 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-01 20:54:32.125  1753  1753 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-01 20:54:32.127  1753  4025 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-01 20:54:32.128  1753  4025 I SystemUpdateService: now status is 0 (complete)
09-01 20:54:32.128  1753  4025 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 20:54:32.128  1753  4025 I SystemUpdateService: file has been verified
09-01 20:54:32.129  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-01 20:54:32.129  1753  4025 I SystemUpdateService: OTA package size = 12249756
09-01 20:54:32.131  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 20:54:32.128  1753  3715 I iu.UploadsManager: num queued entries: 0
09-01 20:54:32.132  1753  3715 I iu.UploadsManager: num updated entries: 0
,09-01 20:54:32.132  3723  3723 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-01 20:54:32.133  1753  3715 I iu.SyncManager: NEXT; no task
,09-01 20:54:32.136  3723  3723 D SprintDMHelper: simOperator: 
,09-01 20:54:32.136  3723  3723 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 20:54:32.138  1753  4025 I SystemUpdateService: showing system update notification
,09-01 20:54:32.152  1753  1753 D SystemUpdateService: onDestroy
,09-01 20:54:32.172  2883  4027 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-01 20:54:32.194  4000  4017 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,09-01 20:54:32.397  4000  4017 D ContactDirectoryManager: Found com.google.contacts.gal.provider
,09-01 20:54:32.397  4000  4017 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,09-01 20:54:32.439   872  1951 I ActivityManager: Start proc 4030:com.google.android.gm.exchange/u0a77 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,09-01 20:54:32.490  4030  4030 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,09-01 20:54:32.528   872   883 I ActivityManager: Start proc 4042:com.google.android.gm/u0a78 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,09-01 20:54:32.600   872  1967 I ActivityManager: Start proc 4054:com.google.process.gapps/u0a99 for content provider com.google.android.syncadapters.contacts/.GalProvider
,09-01 20:54:32.606   872  1951 I ActivityManager: Killing 3760:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-01 20:54:32.664   872   882 I ActivityManager: Killing 3618:com.android.settings/1000 (adj 15): empty #17
,09-01 20:54:32.679  4042  4042 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,09-01 20:54:32.743  4042  4069 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,09-01 20:54:32.753  4054  4054 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,09-01 20:54:32.793  4054  4054 I GoogleHttpClient: GMS http client unavailable, use old client
,09-01 20:54:32.839  4000  4017 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,09-01 20:54:32.845  4042  4042 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-01 20:54:32.861  4042  4068 I Gmail   : getAccountsCursor
,09-01 20:54:32.877  4000  4017 I ContactDirectoryManager: Discovered 0 contact directories in 615ms
,09-01 20:54:32.915  4042  4081 E Gmail   : Error finding the version of the Email provider.....
09-01 20:54:32.915  4042  4081 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
09-01 20:54:32.915  4042  4081 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
09-01 20:54:32.915  4042  4081 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
09-01 20:54:32.915  4042  4081 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
09-01 20:54:32.915  4042  4081 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-01 20:54:32.915  4042  4081 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:32.915  4042  4081 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:32.915  4042  4081 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 20:54:32.915  4042  4081 W EmailMigration: We do not support migrating this version of the Email provider.
,09-01 20:54:32.922  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:32.996   872   882 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,09-01 20:54:33.022  4030  4030 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-01 20:54:33.025  4042  4086 I Gmail   : Observing account changes for notifications
,09-01 20:54:33.039  4030  4030 I Exchange: EasService.onCreate
,09-01 20:54:33.047  4030  4089 I Exchange: RestartPingTask
,09-01 20:54:33.063  4030  4030 I Exchange: RestartPingsTask did not start any pings.
09-01 20:54:33.063  4030  4030 I Exchange: PSS stopIfIdle
09-01 20:54:33.063  4030  4030 I Exchange: PSS has no active accounts; stopping service.
,09-01 20:54:33.064  4030  4030 I Exchange: onDestroy
,09-01 20:54:36.803   872   889 I ActivityManager: Start proc 4092:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-01 20:54:36.913  4092  4092 D AdapterServiceConfig: Adding HeadsetService
09-01 20:54:36.914  4092  4092 D AdapterServiceConfig: Adding A2dpService
09-01 20:54:36.914  4092  4092 D AdapterServiceConfig: Adding HidService
09-01 20:54:36.914  4092  4092 D AdapterServiceConfig: Adding HealthService
09-01 20:54:36.914  4092  4092 D AdapterServiceConfig: Adding PanService
09-01 20:54:36.914  4092  4092 D AdapterServiceConfig: Adding GattService
09-01 20:54:36.915  4092  4092 D AdapterServiceConfig: Adding BluetoothMapService
,09-01 20:54:36.930   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a1991f5:true
09-01 20:54:36.930  4092  4092 D BluetoothAdapterState: make() - Creating AdapterState
,09-01 20:54:36.936  4092  4092 I bt_bluedroid: init
,09-01 20:54:36.936  4092  4104 I BluetoothAdapterState: Entering OffState
,09-01 20:54:36.944  4092  4105 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-01 20:54:36.944  4092  4105 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 20:54:36.944  4092  4105 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-01 20:54:36.945  4092  4105 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-01 20:54:36.948  4092  4092 I bt_bluedroid: get_profile_interface socket
,09-01 20:54:36.952  4092  4092 I bt_bluedroid: get_profile_interface sdp
,09-01 20:54:36.954  4092  4108 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 20:54:36.958  4092  4108 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 20:54:36.958  4092  4103 I bt_bluedroid: config_hci_snoop_log
,09-01 20:54:36.962   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-01 20:54:36.972  4092  4104 D BluetoothAdapterState: Current state: OFF, message: 0
,09-01 20:54:36.973  4092  4104 D BluetoothAdapterProperties: Setting state to 14
09-01 20:54:36.974  4092  4104 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-01 20:54:36.978  4092  4104 D BluetoothBondStateMachine: make
,09-01 20:54:36.984  4092  4109 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-01 20:54:36.991  4092  4104 I BluetoothAdapterState: Entering PendingCommandState
,09-01 20:54:36.993  4092  4092 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-01 20:54:37.000  4092  4092 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
,09-01 20:54:37.002  4092  4092 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 20:54:37.003  4092  4092 D BtGatt.GattService: Received start request. Starting profile...
09-01 20:54:37.003  4092  4092 D BtGatt.GattService: start()
09-01 20:54:37.003  4092  4092 I bt_bluedroid: get_profile_interface gatt
,09-01 20:54:37.005  4092  4092 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
09-01 20:54:37.005  4092  4092 D BtGatt.AdvertiseManager: advertise manager created
,09-01 20:54:37.016  4092  4092 V BluetoothAdapterState: isTurningOff()=false
09-01 20:54:37.016  4092  4092 V BluetoothAdapterState: isTurningOn()=false
09-01 20:54:37.017  4092  4092 V BluetoothAdapterState: isBleTurningOn()=true
09-01 20:54:37.017  4092  4092 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:37.017  4092  4104 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-01 20:54:37.018  4092  4104 I bt_bluedroid: enable
,09-01 20:54:37.018  4092  4105 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-01 20:54:37.019  4092  4105 I bt_hci  : start_up
09-01 20:54:37.020   872  2827 I ActivityManager: Killing 3639:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,09-01 20:54:37.028  4000  4011 W art     : Suspending all threads took: 5.221ms
,09-01 20:54:37.146   872  1950 I ActivityManager: Killing 3787:com.google.android.gms.unstable/u0a11 (adj 15): empty #17
,09-01 20:54:37.211  4092  4105 I bt_vendor: alloc value 0xb3a1f189
09-01 20:54:37.211  4092  4105 I bt_vendor: init
09-01 20:54:37.211  4092  4105 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-01 20:54:37.211  4092  4105 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-01 20:54:37.318  4092  4105 D bt_hci  : start_up starting async portion
,09-01 20:54:37.319  4092  4112 I bt_hci  : event_finish_startup
09-01 20:54:37.319  4092  4112 I bt_hci_h4: hal_open
09-01 20:54:37.321  4092  4112 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-01 20:54:37.333  4092  4112 I bt_userial_vendor: device fd = 51 open
,09-01 20:54:37.352   872  1309 D ConnectivityService: handlePromptUnvalidated 101
,09-01 20:54:37.361  4092  4112 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 20:54:37.392  4092  4112 D bt_hwcfg: Chipset BCM4354A2
,09-01 20:54:37.392  4092  4112 D bt_hwcfg: Target name = [BCM4354A2]
,09-01 20:54:37.393  4092  4112 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-01 20:54:37.932  4042  4075 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-01 20:54:37.994  4092  4112 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-01 20:54:37.996  4092  4112 D bt_hwcfg: Settlement delay -- 100 ms
,09-01 20:54:37.996  4092  4112 I bt_hwcfg: Setting fw settlement delay to 100 
,09-01 20:54:38.098  4030  4088 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-01 20:54:38.112  4092  4112 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 20:54:38.113  4092  4112 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-01 20:54:38.143  4092  4112 I bt_hwcfg: vendor lib fwcfg completed
,09-01 20:54:38.144  4092  4112 I bt_vendor: firmware callback
,09-01 20:54:38.144  4092  4112 I bt_hci  : firmware_config_callback
,09-01 20:54:38.158  4092  4118 I bt_btu  : btu_task pending for preload complete event
,09-01 20:54:38.158  4092  4118 I bt_btu_task: Bluetooth chip preload is complete
,09-01 20:54:38.159  4092  4118 I bt_btu  : btu_task received preload complete event
,09-01 20:54:38.168  4092  4118 I         : BTE_InitTraceLevels -- TRC_HCI
,09-01 20:54:38.168  4092  4118 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-01 20:54:38.169  4092  4118 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-01 20:54:38.169  4092  4118 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-01 20:54:38.169  4092  4118 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 20:54:38.170  4092  4118 I         : BTE_InitTraceLevels -- TRC_A2D
,09-01 20:54:38.170  4092  4118 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 20:54:38.170  4092  4118 I         : BTE_InitTraceLevels -- TRC_BTM
,09-01 20:54:38.170  4092  4118 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 20:54:38.171  4092  4118 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 20:54:38.171  4092  4118 I         : BTE_InitTraceLevels -- TRC_SDP
,09-01 20:54:38.171  4092  4118 I         : BTE_InitTraceLevels -- TRC_GATT
,09-01 20:54:38.171  4092  4118 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 20:54:38.172  4092  4118 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-01 20:54:38.172  4092  4118 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-01 20:54:38.313  4092  4118 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb399cd9d
,09-01 20:54:38.313  4092  4118 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb399cd9d 
,09-01 20:54:38.321  4092  4108 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-01 20:54:38.323  4092  4108 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-01 20:54:38.323  4092  4108 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 20:54:38.328  4092  4108 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 20:54:38.333  4092  4108 D BluetoothAdapterProperties: Scan Mode:20
,09-01 20:54:38.333  4092  4108 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 20:54:38.334  4092  4108 D bt_hci  : do_postload posting postload work item
09-01 20:54:38.334  4092  4112 I bt_hci  : event_postload
09-01 20:54:38.334  4092  4112 I bt_vendor: sco_config_cb
09-01 20:54:38.334  4092  4112 I bt_hci  : sco_config_callback postload finished.
,09-01 20:54:38.335  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:38.336  4092  4108 D bt_bte_conf: Device ID record 1 : primary
09-01 20:54:38.336  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:38.336  4092  4108 D bt_bte_conf:   vendorId            = 000f
09-01 20:54:38.336  4092  4108 D bt_bte_conf:   vendorIdSource      = 0001
09-01 20:54:38.336  4092  4108 D bt_bte_conf:   product             = 1200
,09-01 20:54:38.336  4092  4108 D bt_bte_conf:   version             = 1436
09-01 20:54:38.337  4092  4108 D bt_bte_conf:   clientExecutableURL = 
09-01 20:54:38.337  4092  4108 D bt_bte_conf:   serviceDescription  = 
09-01 20:54:38.337  4092  4108 D bt_bte_conf:   documentationURL    = 
,09-01 20:54:38.337  4092  4108 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-01 20:54:38.337  4092  4105 D bt_stack_manager: event_start_up_stack finished
09-01 20:54:38.337  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:38.338  4092  4104 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-01 20:54:38.338  4092  4104 D BluetoothAdapterProperties: Setting state to 15
09-01 20:54:38.338  4092  4104 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-01 20:54:38.339  4092  4104 I BluetoothAdapterState: Entering BleOnState
09-01 20:54:38.341  4092  4112 I bt_vendor: low_power_mode_cb
09-01 20:54:38.342  4092  4104 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-01 20:54:38.342  4092  4104 D BluetoothAdapterProperties: Setting state to 11
09-01 20:54:38.342  4092  4104 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-01 20:54:38.348  4092  4092 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
,09-01 20:54:38.350  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:38.352  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:38.353  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:38.352  4092  4092 D HeadsetService: Received start request. Starting profile...
09-01 20:54:38.357  4092  4092 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 20:54:38.357  4092  4092 D HeadsetStateMachine: make
09-01 20:54:38.370   872   885 I ActivityManager: Start proc 4125:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-01 20:54:38.372  4092  4092 D HeadsetStateMachine: max_hf_connections = 1
,09-01 20:54:38.372  4092  4092 I bt_bluedroid: get_profile_interface handsfree
09-01 20:54:38.374  4092  4108 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-01 20:54:38.374  4092  4108 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-01 20:54:38.378  4092  4092 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
09-01 20:54:38.378  4092  4104 I BluetoothAdapterState: Entering PendingCommandState
,09-01 20:54:38.378  4092  4092 D A2dpService: Received start request. Starting profile...
09-01 20:54:38.379  4092  4092 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 20:54:38.379  4092  4092 I bt_bluedroid: get_profile_interface avrcp
,09-01 20:54:38.384  4092  4092 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-01 20:54:38.384  4092  4092 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-01 20:54:38.384  4092  4092 D A2dpStateMachine: make
09-01 20:54:38.385  4092  4092 I bt_bluedroid: get_profile_interface a2dp
09-01 20:54:38.386  4092  4108 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-01 20:54:38.390  4092  4132 D A2dpStateMachine: Enter Disconnected: -2
,09-01 20:54:38.391  4092  4092 I BluetoothHidServiceJni: classInitNative: succeeds
,09-01 20:54:38.392  4092  4092 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
09-01 20:54:38.392  4092  4092 V BluetoothAdapterState: isTurningOff()=false
09-01 20:54:38.392  4092  4092 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:38.393  4092  4092 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:38.393  4092  4092 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 20:54:38.394  4092  4092 D HidService: Received start request. Starting profile...
,09-01 20:54:38.395  4092  4092 I bt_bluedroid: get_profile_interface hidhost
09-01 20:54:38.395  4092  4092 D HidService: setHidService(): set to: null
09-01 20:54:38.395  4092  4092 I BluetoothHealthServiceJni: classInitNative: succeeds
09-01 20:54:38.396  4092  4092 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
09-01 20:54:38.396  4092  4108 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397e3e5
,09-01 20:54:38.396  4092  4108 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-01 20:54:38.397  4092  4092 D HealthService: Received start request. Starting profile...
,09-01 20:54:38.399  4092  4092 I bt_bluedroid: get_profile_interface health
,09-01 20:54:38.399  4092  4124 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-01 20:54:38.399  4092  4092 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-01 20:54:38.400  4092  4092 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
,09-01 20:54:38.401  4092  4092 D PanService: Received start request. Starting profile...
,09-01 20:54:38.401  4092  4092 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 20:54:38.401  4092  4092 I bt_bluedroid: get_profile_interface pan
09-01 20:54:38.402  4092  4108 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-01 20:54:38.405  4092  4092 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901,
,09-01 20:54:38.406  4092  4092 D BluetoothMapService: Received start request. Starting profile...
,09-01 20:54:38.406  4092  4092 D BluetoothMapService: start()
,09-01 20:54:38.410  4092  4092 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-01 20:54:38.410  4092  4092 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-01 20:54:38.411  4092  4092 D BluetoothMapAppObserver: createReceiver()
,09-01 20:54:38.412  4092  4092 D BluetoothMapAppObserver: initObservers()
09-01 20:54:38.412  4092  4092 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-01 20:54:38.419  4092  4092 V BluetoothAdapterState: isTurningOff()=false
,09-01 20:54:38.419  4092  4092 V BluetoothAdapterState: isTurningOn()=true
,09-01 20:54:38.419  4092  4092 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 20:54:38.420  4092  4092 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:38.420  4092  4092 V BluetoothAdapterState: isTurningOff()=false
09-01 20:54:38.420  4092  4092 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:38.420  4092  4092 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:38.420  4092  4092 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 20:54:38.420  4092  4092 V BluetoothAdapterState: isTurningOff()=false
,09-01 20:54:38.421  4092  4092 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:38.421  4092  4092 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 20:54:38.421  4092  4092 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:38.421  4092  4092 V BluetoothAdapterState: isTurningOff()=false
09-01 20:54:38.421  4092  4092 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:38.421  4092  4092 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:38.422  4092  4092 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:38.422  4092  4092 V BluetoothAdapterState: isTurningOff()=false
,09-01 20:54:38.422  4092  4092 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:38.422  4092  4092 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:38.422  4092  4092 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:38.423  4092  4104 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-01 20:54:38.423  4092  4104 D BluetoothAdapterProperties: ScanMode =  20
09-01 20:54:38.423  4092  4104 D BluetoothAdapterProperties: State =  11
09-01 20:54:38.423  4092  4104 D BluetoothAdapterProperties: Setting state to 12
09-01 20:54:38.423  4092  4104 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-01 20:54:38.424   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 20:54:38.424  4092  4108 D BluetoothAdapterProperties: Scan Mode:21
09-01 20:54:38.424  4092  4104 I BluetoothAdapterState: Entering OnState
09-01 20:54:38.425  4092  4108 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 20:54:38.425   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 20:54:38.425  1924  2195 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 20:54:38.426  1353  2067 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-01 20:54:38.426   872   872 D BluetoothA2dp: Proxy object connected
09-01 20:54:38.428  1353  1365 D BluetoothMap: onBluetoothStateChange: up=true
09-01 20:54:38.428  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:38.428  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:38.428  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:38.428  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:38.428  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:54:38.428  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:38.428  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:38.428  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:38.429  1353  1353 D BluetoothInputDevice: Proxy object connected
09-01 20:54:38.429  1353  1353 D HidProfile: Bluetooth service connected
09-01 20:54:38.429   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 20:54:38.430  1353  2067 D BluetoothPbap: onBluetoothStateChange: up=true
,09-01 20:54:38.431  1353  1353 D BluetoothMap: Proxy object connected
09-01 20:54:38.431  1353  1353 D MapProfile: Bluetooth service connected
09-01 20:54:38.431  1353  1353 D BluetoothMap: getConnectedDevices()
09-01 20:54:38.431  1353  1365 D BluetoothPan: onBluetoothStateChange on: true
09-01 20:54:38.431  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:54:38.432  1353  3934 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 20:54:38.433   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 20:54:38.433  1353  1353 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 20:54:38.433  1353  1365 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 20:54:38.433  1353  1353 D PanProfile: Bluetooth service connected
09-01 20:54:38.435  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:38.435  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:38.435  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:38.435  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:38.435  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:54:38.435  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:38.435  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:38.435  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:38.435  1353  1353 D BluetoothA2dp: Proxy object connected
09-01 20:54:38.436   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-01 20:54:38.437  4092  4092 D BluetoothMapService: onReceive
09-01 20:54:38.437  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:54:38.437  4092  4092 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-01 20:54:38.437  4092  4092 D BluetoothMapService: STATE_ON
09-01 20:54:38.439  4092  4092 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 20:54:38.440  4092  4092 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-01 20:54:38.440  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:38.440  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:38.440  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:38.440  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:38.440  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:54:38.440  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:38.440  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:38.440  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:38.441  4092  4092 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 20:54:38.442  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:54:38.443  4092  4092 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 20:54:38.443  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:38.445  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:38.445  4092  4092 D ObexServerSockets: Succeed to create listening sockets 
09-01 20:54:38.445  4092  4092 D ObexServerSockets0: startAccept()
,09-01 20:54:38.445  4092  4092 D ObexServerSockets0: prepareForNewConnect()
09-01 20:54:38.446  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:38.447  4092  4092 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-01 20:54:38.447  4092  4092 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-01 20:54:38.448  4092  4145 D ObexServerSockets0: Accepting socket connection...
09-01 20:54:38.448  4092  4146 D ObexServerSockets0: Accepting socket connection...
,09-01 20:54:38.451  4125  4125 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-01 20:54:38.457  4092  4092 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-01 20:54:38.457  4092  4092 D ObexServerSockets0: prepareForNewConnect()
,09-01 20:54:38.460   872  2827 I ActivityManager: Killing 2716:com.android.vending/u0a19 (adj 15): empty #17
,09-01 20:54:38.506  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 20:54:38.529   872  1932 I ActivityManager: Start proc 4147:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-01 20:54:38.534   872   872 D BluetoothHeadset: Proxy object connected
,09-01 20:54:38.534   872   872 D BluetoothHeadset: Proxy object connected
,09-01 20:54:38.535  1353  1364 D BluetoothHeadset: Proxy object connected
,09-01 20:54:38.536  1353  1353 D HeadsetProfile: Bluetooth service connected
,09-01 20:54:38.537  1924  1938 D BluetoothHeadset: Proxy object connected
09-01 20:54:38.538   872   872 D BluetoothHeadset: Proxy object connected
,09-01 20:54:38.592  4147  4147 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-01 20:54:38.788  4147  4147 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:38.788  4147  4147 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:38.788  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:38.789  4147  4147 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:38.789  4147  4147 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:38.789  4147  4147 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.r.e.b(PG:170)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:38.789  4147  4147 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.r.k.d(PG:583)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.r.e.b(PG:170)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:38.789  4147  4147 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:38.789  4147  4147 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:38.789  4147  4147 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:54:38.789  4147  4147 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:54:38.810  4125  4125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 20:54:38.830   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4dd91a7:true
,09-01 20:54:38.833  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 20:54:38.845  4125  4125 D LocalBluetoothProfileManager: Adding local A2DP profile
09-01 20:54:38.849  4125  4125 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-01 20:54:38.852  1353  1353 D BluetoothPbap: Proxy object connected
09-01 20:54:38.852  1353  1353 D PbapServerProfile: Bluetooth service connected
09-01 20:54:38.863  4125  4125 D LocalBluetoothProfileManager: Adding local MAP profile
09-01 20:54:38.865  4092  4176 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 20:54:38.867  4125  4125 D BluetoothMap: Create BluetoothMap proxy object
,09-01 20:54:38.877  4125  4125 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-01 20:54:38.889  4092  4181 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 20:54:38.890  4092  4181 I BtOppRfcommListener: Accept thread started.
,09-01 20:54:38.893  4125  4125 D DockEventReceiver: finishStartingService: stopping service
,09-01 20:54:38.894  4125  4125 D BluetoothA2dp: Proxy object connected
,09-01 20:54:38.897  4125  4125 D BluetoothInputDevice: Proxy object connected
,09-01 20:54:38.897  4125  4125 D HidProfile: Bluetooth service connected
,09-01 20:54:38.899  4125  4125 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 20:54:38.899  4125  4125 D PanProfile: Bluetooth service connected
,09-01 20:54:38.900  4125  4125 D BluetoothMap: Proxy object connected
09-01 20:54:38.900  4125  4125 D MapProfile: Bluetooth service connected
,09-01 20:54:38.900  4125  4125 D BluetoothMap: getConnectedDevices()
,09-01 20:54:38.902  4125  4125 D BluetoothPbap: Proxy object connected
,09-01 20:54:38.902  4125  4125 D PbapServerProfile: Bluetooth service connected
,09-01 20:54:38.904   872  1950 I ActivityManager: Killing 2228:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-01 20:54:38.956  4125  4143 D BluetoothHeadset: Proxy object connected
,09-01 20:54:38.957  4125  4125 D HeadsetProfile: Bluetooth service connected
,09-01 20:54:39.039  4147  4167 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-01 20:54:39.056   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@143a652:true
,09-01 20:54:40.030  1753  1753 V CheckinService: unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
,09-01 20:54:40.095  1753  4187 I CheckinService: Checking schedule, now: 1472756080094 next: 1472756071799
,09-01 20:54:40.095  1753  4187 I CheckinService: active receiver: enabled
,09-01 20:54:40.137  1535  2502 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-01 20:54:40.147  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 20:54:40.153  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 20:54:40.330  1870  1981 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-01 20:54:40.330  1870  1981 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-01 20:54:40.377  1535  1535 I ConfigService: onCreate
,09-01 20:54:41.749  4092  4104 D BluetoothAdapterState: Current state: ON, message: 23
,09-01 20:54:41.750  4092  4104 D BluetoothAdapterProperties: Setting state to 13
,09-01 20:54:41.750  4092  4104 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-01 20:54:41.752  4092  4104 D BluetoothAdapterProperties: onBluetoothDisable()
,09-01 20:54:41.760  4092  4092 D BluetoothMapService: onReceive
09-01 20:54:41.760  4092  4092 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 20:54:41.761  4092  4092 D BluetoothMapService: STATE_TURNING_OFF
09-01 20:54:41.761  4092  4092 D BluetoothMapService: MAP Service closeService in
09-01 20:54:41.762  4092  4092 D BluetoothMapMasInstance0: MAP Service shutdown
09-01 20:54:41.762  4092  4092 D ObexServerSockets0: shutdown(block = true)
09-01 20:54:41.763  4092  4145 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-01 20:54:41.765  4092  4092 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-01 20:54:41.765  4092  4120 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-01 20:54:41.766  4092  4108 D BluetoothAdapterProperties: Scan Mode:20
09-01 20:54:41.766  4092  4104 I BluetoothAdapterState: Entering PendingCommandState
09-01 20:54:41.766  4092  4104 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-01 20:54:41.767  4092  4146 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-01 20:54:41.769  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:41.769  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:41.769  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:41.769  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:41.769  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:41.769  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:41.769  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:41.769  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:41.769  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:41.766  4092  4092 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-01 20:54:41.771  4092  4092 D HeadsetService: Received stop request...Stopping profile...
09-01 20:54:41.773  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:41.773  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:54:41.778   872   872 D BluetoothHeadset: Proxy object disconnected,
,09-01 20:54:41.778   872   872 D BluetoothHeadset: Proxy object disconnected
,09-01 20:54:41.779  1353  2067 D BluetoothHeadset: Proxy object disconnected
,09-01 20:54:41.779  1924  2119 D BluetoothHeadset: Proxy object disconnected
09-01 20:54:41.780  4092  4092 D A2dpService: Received stop request...Stopping profile...
09-01 20:54:41.780   872   872 D BluetoothHeadset: Proxy object disconnected
09-01 20:54:41.780  1353  1353 D HeadsetProfile: Bluetooth service disconnected
09-01 20:54:41.780  4092  4132 D A2dpStateMachine: Exit Disconnected: -1
09-01 20:54:41.781  4125  4142 D BluetoothHeadset: Proxy object disconnected
09-01 20:54:41.781  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:41.781  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:41.781  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:41.781  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:41.781  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:41.781  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:41.781  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:41.781  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:41.781  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 20:54:41.782  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:41.782  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 20:54:41.782  4092  4092 I BtOppRfcommListener: stopping Accept Thread
09-01 20:54:41.782   872   872 D BluetoothA2dp: Proxy object disconnected
,09-01 20:54:41.783  4092  4181 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 20:54:41.783  4092  4181 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-01 20:54:41.784  4125  4125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 20:54:41.784  4092  4092 D HidService: Received stop request...Stopping profile...
09-01 20:54:41.784  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:41.784  4092  4092 D HidService: Stopping Bluetooth HidService
09-01 20:54:41.784  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:41.784  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:41.784  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:41.784  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:41.784  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 20:54:41.784  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:41.784  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:41.784  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:41.785  3506  3506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 20:54:41.785  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:54:41.787  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:41.788  4092  4092 V BluetoothAdapterState: isTurningOff()=true
09-01 20:54:41.788  4092  4092 V BluetoothAdapterState: isTurningOn()=false
09-01 20:54:41.788  4092  4092 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:41.788  4092  4092 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:41.788  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:41.789  4092  4092 D HealthService: Received stop request...Stopping profile...
,09-01 20:54:41.789  4125  4125 D HeadsetProfile: Bluetooth service disconnected
09-01 20:54:41.790  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:41.791  4125  4125 D BluetoothA2dp: Proxy object disconnected
09-01 20:54:41.791  4092  4092 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-01 20:54:41.791  4092  4092 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 20:54:41.791  4125  4125 D BluetoothInputDevice: Proxy object disconnected
09-01 20:54:41.791  4125  4125 D HidProfile: Bluetooth service disconnected
09-01 20:54:41.792  4092  4108 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-01 20:54:41.792  4092  4092 D PanService: Received stop request...Stopping profile...
09-01 20:54:41.792  4092  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 20:54:41.792  4092  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 20:54:41.792  4092  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 20:54:41.793  4092  4108 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-01 20:54:41.793  4092  4092 V BluetoothAdapterState: isTurningOff()=true
,09-01 20:54:41.793  4092  4092 V BluetoothAdapterState: isTurningOn()=false
,09-01 20:54:41.793  4092  4092 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 20:54:41.793  4092  4092 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:41.794  4092  4108 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-01 20:54:41.795  4092  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 20:54:41.795  4092  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 20:54:41.795  4092  4118 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 20:54:41.795  4092  4118 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 20:54:41.795  4092  4092 D BluetoothMapService: Received stop request...Stopping profile...
09-01 20:54:41.795  4092  4118 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 20:54:41.795  4092  4092 D BluetoothMapService: stop()
09-01 20:54:41.795  4092  4118 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 20:54:41.796  4092  4092 D BluetoothMapAppObserver: deinitObservers()
09-01 20:54:41.796  4092  4092 D BluetoothMapAppObserver: removeReceiver()
,09-01 20:54:41.799  4125  4125 D DockEventReceiver: finishStartingService: stopping service
09-01 20:54:41.800  1353  1353 D BluetoothA2dp: Proxy object disconnected
09-01 20:54:41.801  1353  1353 D BluetoothInputDevice: Proxy object disconnected
09-01 20:54:41.801  1353  1353 D HidProfile: Bluetooth service disconnected
,09-01 20:54:41.802  1353  1353 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-01 20:54:41.802  1353  1353 D PanProfile: Bluetooth service disconnected
09-01 20:54:41.802  1353  1353 D BluetoothMap: Proxy object disconnected
09-01 20:54:41.802  1353  1353 D MapProfile: Bluetooth service disconnected
09-01 20:54:41.803  4125  4125 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 20:54:41.803  4125  4125 D PanProfile: Bluetooth service disconnected
09-01 20:54:41.804  4125  4125 D BluetoothMap: Proxy object disconnected
09-01 20:54:41.804  4125  4125 D MapProfile: Bluetooth service disconnected
09-01 20:54:41.804  4092  4092 V BluetoothAdapterState: isTurningOff()=true
09-01 20:54:41.804  4092  4092 V BluetoothAdapterState: isTurningOn()=false
09-01 20:54:41.804  4092  4092 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:41.804  4092  4092 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:41.804  4092  4092 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-01 20:54:41.804  4092  4108 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-01 20:54:41.804  4092  4092 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 20:54:41.805  4092  4092 V BluetoothAdapterState: isTurningOff()=true
09-01 20:54:41.805  4092  4092 V BluetoothAdapterState: isTurningOn()=false
09-01 20:54:41.805  4092  4092 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:41.805  4092  4092 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:41.806  4092  4092 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 20:54:41.806  4092  4108 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-01 20:54:41.807  4092  4092 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 20:54:41.807  4092  4092 V BluetoothAdapterState: isTurningOff()=true
,09-01 20:54:41.807  4092  4092 V BluetoothAdapterState: isTurningOn()=false
09-01 20:54:41.807  4092  4092 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:41.807  4092  4092 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:41.807  4092  4092 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 20:54:41.808  4092  4092 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 20:54:41.809  4092  4092 D BluetoothMapService: MAP Service closeService in
09-01 20:54:41.809  4092  4092 V BluetoothAdapterState: isTurningOff()=true
09-01 20:54:41.809  4092  4092 V BluetoothAdapterState: isTurningOn()=false
09-01 20:54:41.809  4092  4092 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:41.809  4092  4092 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:41.809  4092  4092 D BluetoothMapService: cleanup()
09-01 20:54:41.809  4092  4092 D BluetoothMapService: MAP Service closeService in
09-01 20:54:41.809  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 20:54:41.809  4092  4104 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-01 20:54:41.809  4092  4104 D BluetoothAdapterProperties: Setting state to 15
09-01 20:54:41.810  4092  4104 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-01 20:54:41.810  4092  4104 I BluetoothAdapterState: Entering BleOnState
09-01 20:54:41.810  4125  4143 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 20:54:41.812  1353  1353 D BluetoothPbap: Proxy object disconnected
09-01 20:54:41.812  1353  1353 D PbapServerProfile: Bluetooth service disconnected
09-01 20:54:41.813  4125  4142 D BluetoothPan: onBluetoothStateChange on: false
09-01 20:54:41.817  4125  4191 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 20:54:41.818   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 20:54:41.818  4125  4143 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 20:54:41.819   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-01 20:54:41.820  1924  2195 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 20:54:41.820  4125  4125 D BluetoothPbap: Proxy object disconnected
09-01 20:54:41.820  1353  2067 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 20:54:41.821  1353  1365 D BluetoothMap: onBluetoothStateChange: up=false
,09-01 20:54:41.820  4125  4125 D PbapServerProfile: Bluetooth service disconnected
,09-01 20:54:41.823   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 20:54:41.823  4125  4191 D BluetoothMap: onBluetoothStateChange: up=false
09-01 20:54:41.823  1353  3934 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 20:54:41.824  1353  1364 D BluetoothPan: onBluetoothStateChange on: false
09-01 20:54:41.824  1353  2067 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 20:54:41.825  4125  4142 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-01 20:54:41.825   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-01 20:54:41.825  1353  1365 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 20:54:41.826  4092  4104 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-01 20:54:41.826  4092  4104 D BluetoothAdapterProperties: Setting state to 16
09-01 20:54:41.826  4092  4104 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-01 20:54:41.826  4092  4104 D BluetoothAdapterProperties: onBleDisable
09-01 20:54:41.827  4092  4104 I BluetoothAdapterState: Entering PendingCommandState
09-01 20:54:41.827  4092  4105 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-01 20:54:41.827  4092  4118 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-01 20:54:41.828  4092  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 20:54:41.829  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:41.829  4092  4108 D BluetoothAdapterProperties: Scan Mode:20
09-01 20:54:41.831  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:41.831  4125  4125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 20:54:41.832  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:41.835  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:41.836  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:41.836  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 20:54:41.838  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:41.844  4125  4125 D DockEventReceiver: finishStartingService: stopping service
,09-01 20:54:42.031  4092  4108 I bt_hci  : shut_down
09-01 20:54:42.031  4092  4112 D bt_hwcfg: hw_epilog_process
,09-01 20:54:42.044  4092  4112 I bt_vendor: low_power_mode_cb
,09-01 20:54:42.074  4092  4112 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-01 20:54:42.074  4092  4112 I bt_vendor: epilog_cb
09-01 20:54:42.075  4092  4112 I bt_hci  : epilog_finished_callback
,09-01 20:54:42.082  4092  4108 I bt_hci_h4: hal_close
,09-01 20:54:42.083  4092  4108 I bt_userial_vendor: device fd = 51 close
,09-01 20:54:42.217  4092  4105 D bt_stack_manager: event_shut_down_stack finished.
,09-01 20:54:42.218  4092  4104 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-01 20:54:42.225  4092  4092 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 20:54:42.226  4092  4104 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-01 20:54:42.227  4092  4092 D BtGatt.GattService: Received stop request...Stopping profile...
09-01 20:54:42.227  4092  4092 D BtGatt.GattService: stop()
,09-01 20:54:42.228  4092  4092 D BtGatt.AdvertiseManager: advertise clients cleared
,09-01 20:54:42.232  4092  4092 V BluetoothAdapterState: isTurningOff()=false
,09-01 20:54:42.233  4092  4092 V BluetoothAdapterState: isTurningOn()=false
09-01 20:54:42.233  4092  4092 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:42.233  4092  4092 V BluetoothAdapterState: isBleTurningOff()=true
09-01 20:54:42.234  4092  4104 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-01 20:54:42.235  4092  4104 D BluetoothAdapterProperties: Setting state to 10
09-01 20:54:42.235  4092  4104 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-01 20:54:42.237  4092  4104 I BluetoothAdapterState: Entering OffState
,09-01 20:54:42.239   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-01 20:54:42.268  4092  4092 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-01 20:54:42.269  4092  4092 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-01 20:54:42.270  4092  4105 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-01 20:54:42.272  4092  4092 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-01 20:54:42.279  4092  4105 D bt_stack_manager: event_clean_up_stack finished.
,09-01 20:54:42.281  4092  4092 I art     : System.exit called, status: 0
,09-01 20:54:42.281  4092  4092 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-01 20:54:42.323   872  1943 I ActivityManager: Process com.android.bluetooth (pid 4092) has died
,09-01 20:54:45.475  1535  1535 I ConfigService: onDestroy
,09-01 20:54:46.746  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 20:54:46.747  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:46.752  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 20:54:46.752  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@252bed2 removed from the list
09-01 20:54:46.752  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:46.753  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:46.753  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:46.756  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 20:54:46.757  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37aaea0 added. We now have 4 listener(s)
09-01 20:54:46.757  3506  3553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 20:54:46.758  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 20:54:46.759  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37aaea0 removed from the list
09-01 20:54:46.759  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:46.760  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 20:54:46.760  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:54:46.762  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 20:54:46.763  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c314a59 added. We now have 4 listener(s)
,09-01 20:54:46.763  3506  3553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 20:54:50.209   872  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-01 20:54:50.248   872  1950 I ActivityManager: Start proc 4200:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,09-01 20:54:50.299  4200  4200 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
,09-01 20:54:50.340  2134  2134 V GmsNetworkLocationProvi: DISABLE
,09-01 20:54:50.345  2134  2134 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,09-01 20:54:50.388  4200  4200 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-01 20:54:50.437  4200  4200 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,09-01 20:54:50.448  4200  4200 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-01 20:54:50.448  4200  4200 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-01 20:54:50.496  4200  4200 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,09-01 20:54:50.496  4200  4200 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,09-01 20:54:50.500  4200  4237 D Ads     : Skipping gmscore version check
,09-01 20:54:50.510  1753  4238 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-01 20:54:50.513  2014  4239 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-01 20:54:50.527  4200  4237 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-01 20:54:50.543   872  1373 I ActivityManager: Start proc 4240:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
,09-01 20:54:50.544  1753  4238 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-01 20:54:50.564  2014  4239 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 51 ms] updated apps [took 51 ms] 
,09-01 20:54:50.563  1753  2340 I Icing   : updateResources: need to parse f{com.google.android.gms}
,09-01 20:54:50.598  4240  4240 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-01 20:54:50.603  4200  4200 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-01 20:54:50.609  4240  4240 I MultiDex: VM with version 2.1.0 has multidex support
,09-01 20:54:50.609  4240  4240 I MultiDex: install
09-01 20:54:50.609  4240  4240 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-01 20:54:50.621  4200  4200 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-01 20:54:50.656  4240  4240 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-01 20:54:50.681  4240  4240 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-01 20:54:50.688  1535  2773 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-01 20:54:50.696  1535  1535 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-01 20:54:50.708  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:50.710  1753  1753 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-01 20:54:50.726  4240  4240 D WearableService: callingUid 10011, callindPid: 4240
,09-01 20:54:50.734  4240  4258 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,09-01 20:54:50.752  1753  4262 D LocationInitializer: Restart initialization of location
,09-01 20:54:50.753  2134  2242 E MDM     : [121] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-01 20:54:50.765  2134  2212 W GCoreFlp: No location to return for getLastLocation()
,09-01 20:54:50.765  1535  4263 W FusedLocationProvider: location=null
,09-01 20:54:51.453  4200  4200 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,09-01 20:54:51.501  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:51.522  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:51.529  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:51.601  1535  2376 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-01 20:54:51.601  1535  2376 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-01 20:54:51.601  1535  2376 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 20:54:51.602  1535  2376 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:54:51.634  4200  4200 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-01 20:54:51.651  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:51.696  1535  1549 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-01 20:54:51.697  1535  1549 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-01 20:54:51.697  1535  1549 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 20:54:51.698  1535  1549 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:54:51.773  3506  3553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:51.790  4200  4267 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-01 20:54:51.799  4200  4200 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
09-01 20:54:51.799   872   889 I ActivityManager: Start proc 4268:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-01 20:54:51.804  4200  4200 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,09-01 20:54:51.813  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:51.840  1535  3750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-01 20:54:51.841  1535  3750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-01 20:54:51.841  1535  3750 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:54:51.841  1535  3750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:54:51.859  4200  4200 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-01 20:54:51.861  4268  4268 D AdapterServiceConfig: Adding HeadsetService
,09-01 20:54:51.861  4268  4268 D AdapterServiceConfig: Adding A2dpService
,09-01 20:54:51.862  4268  4268 D AdapterServiceConfig: Adding HidService
,09-01 20:54:51.862  4268  4268 D AdapterServiceConfig: Adding HealthService
,09-01 20:54:51.862  4268  4268 D AdapterServiceConfig: Adding PanService
,09-01 20:54:51.862  4268  4268 D AdapterServiceConfig: Adding GattService
09-01 20:54:51.862  4268  4268 D AdapterServiceConfig: Adding BluetoothMapService
,09-01 20:54:51.873  4268  4268 D BluetoothAdapterState: make() - Creating AdapterState
,09-01 20:54:51.873   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c3e45d7:true
,09-01 20:54:51.875  4268  4268 I bt_bluedroid: init
,09-01 20:54:51.875  4268  4281 I BluetoothAdapterState: Entering OffState
,09-01 20:54:51.880  4268  4282 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-01 20:54:51.880  4268  4282 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-01 20:54:51.881  4268  4282 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-01 20:54:51.881  4268  4282 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-01 20:54:51.882  4268  4268 I bt_bluedroid: get_profile_interface socket
,09-01 20:54:51.883  4268  4268 I bt_bluedroid: get_profile_interface sdp
,09-01 20:54:51.885  4268  4285 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 20:54:51.886  4268  4279 I bt_bluedroid: config_hci_snoop_log
09-01 20:54:51.887  4268  4285 D BluetoothAdapterProperties: Name is: Nexus 6
09-01 20:54:51.888   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-01 20:54:51.892  4268  4281 D BluetoothAdapterState: Current state: OFF, message: 0
,09-01 20:54:51.892  4268  4281 D BluetoothAdapterProperties: Setting state to 14
,09-01 20:54:51.892  4268  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-01 20:54:51.893  4268  4281 D BluetoothBondStateMachine: make
09-01 20:54:51.895  4268  4286 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-01 20:54:51.897  4268  4281 I BluetoothAdapterState: Entering PendingCommandState
09-01 20:54:51.898  4268  4268 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-01 20:54:51.900  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
,09-01 20:54:51.900  4268  4268 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 20:54:51.901  4268  4268 D BtGatt.GattService: Received start request. Starting profile...
09-01 20:54:51.901  4268  4268 D BtGatt.GattService: start()
09-01 20:54:51.901  4268  4268 I bt_bluedroid: get_profile_interface gatt
,09-01 20:54:51.902  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
09-01 20:54:51.902  4268  4268 D BtGatt.AdvertiseManager: advertise manager created
,09-01 20:54:51.906  4268  4268 V BluetoothAdapterState: isTurningOff()=false
,09-01 20:54:51.906  4268  4268 V BluetoothAdapterState: isTurningOn()=false
09-01 20:54:51.906  4268  4268 V BluetoothAdapterState: isBleTurningOn()=true
09-01 20:54:51.906  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 20:54:51.907  4268  4281 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-01 20:54:51.907  4268  4281 I bt_bluedroid: enable
09-01 20:54:51.907  4268  4282 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-01 20:54:51.908  4268  4282 I bt_hci  : start_up
,09-01 20:54:51.915  4268  4282 I bt_vendor: alloc value 0xb3a1f189
,09-01 20:54:51.915  4268  4282 I bt_vendor: init
09-01 20:54:51.915  4268  4282 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-01 20:54:51.915  4268  4282 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-01 20:54:51.999  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:54:52.020  4268  4282 D bt_hci  : start_up starting async portion
,09-01 20:54:52.020  4268  4289 I bt_hci  : event_finish_startup
,09-01 20:54:52.021  4268  4289 I bt_hci_h4: hal_open
09-01 20:54:52.021  4268  4289 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-01 20:54:52.027  4268  4289 I bt_userial_vendor: device fd = 51 open
,09-01 20:54:52.043  1535  2828 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-01 20:54:52.043  1535  2828 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-01 20:54:52.043  1535  2828 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:54:52.043  1535  2828 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:54:52.063  4268  4289 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 20:54:52.069  4200  4200 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-01 20:54:52.070  4200  4200 D Finsky  : [1] WearSupportService.startHygiene: disabled
,09-01 20:54:52.072  4200  4200 D Finsky  : [1] DailyHygiene.access$600: Logging device features
09-01 20:54:52.076  4200  4200 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,09-01 20:54:52.088  4200  4291 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-01 20:54:52.095  4268  4289 D bt_hwcfg: Chipset BCM4354A2
,09-01 20:54:52.095  4268  4289 D bt_hwcfg: Target name = [BCM4354A2]
09-01 20:54:52.096  4268  4289 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-01 20:54:52.739  4268  4289 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-01 20:54:52.741  4268  4289 D bt_hwcfg: Settlement delay -- 100 ms
09-01 20:54:52.741  4268  4289 I bt_hwcfg: Setting fw settlement delay to 100 
,09-01 20:54:52.858  4268  4289 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-01 20:54:52.859  4268  4289 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-01 20:54:52.889  4268  4289 I bt_hwcfg: vendor lib fwcfg completed
,09-01 20:54:52.889  4268  4289 I bt_vendor: firmware callback,
,09-01 20:54:52.889  4268  4289 I bt_hci  : firmware_config_callback
,09-01 20:54:52.902  4268  4292 I bt_btu  : btu_task pending for preload complete event
,09-01 20:54:52.903  4268  4292 I bt_btu_task: Bluetooth chip preload is complete
,09-01 20:54:52.903  4268  4292 I bt_btu  : btu_task received preload complete event
,09-01 20:54:52.910  4268  4292 I         : BTE_InitTraceLevels -- TRC_HCI
09-01 20:54:52.910  4268  4292 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 20:54:52.911  4268  4292 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-01 20:54:52.911  4268  4292 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 20:54:52.911  4268  4292 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 20:54:52.911  4268  4292 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 20:54:52.911  4268  4292 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 20:54:52.911  4268  4292 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 20:54:52.911  4268  4292 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 20:54:52.911  4268  4292 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 20:54:52.911  4268  4292 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 20:54:52.911  4268  4292 I         : BTE_InitTraceLevels -- TRC_GATT
09-01 20:54:52.911  4268  4292 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 20:54:52.911  4268  4292 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 20:54:52.911  4268  4292 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-01 20:54:53.041  4268  4292 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb399cd9d,
,09-01 20:54:53.042  4268  4292 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb399cd9d 
,09-01 20:54:53.054  4268  4285 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-01 20:54:53.056  4268  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-01 20:54:53.057  4268  4285 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 20:54:53.061  4268  4285 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 20:54:53.065  4268  4285 D BluetoothAdapterProperties: Scan Mode:20
,09-01 20:54:53.065  4268  4285 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 20:54:53.066  4268  4285 D bt_hci  : do_postload posting postload work item
,09-01 20:54:53.068  4268  4289 I bt_hci  : event_postload,
09-01 20:54:53.068  4268  4289 I bt_vendor: sco_config_cb
09-01 20:54:53.068  4268  4289 I bt_hci  : sco_config_callback postload finished.
09-01 20:54:53.069  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-01 20:54:53.070  4268  4289 I bt_vendor: low_power_mode_cb
09-01 20:54:53.070  4268  4285 D bt_bte_conf: Device ID record 1 : primary
09-01 20:54:53.070  4268  4285 D bt_bte_conf:   vendorId            = 000f
09-01 20:54:53.070  4268  4285 D bt_bte_conf:   vendorIdSource      = 0001
,09-01 20:54:53.071  4268  4285 D bt_bte_conf:   product             = 1200
09-01 20:54:53.071  4268  4285 D bt_bte_conf:   version             = 1436
09-01 20:54:53.071  4268  4285 D bt_bte_conf:   clientExecutableURL = ,
09-01 20:54:53.071  4268  4285 D bt_bte_conf:   serviceDescription  = 
09-01 20:54:53.071  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:53.071  4268  4285 D bt_bte_conf:   documentationURL    = 
09-01 20:54:53.072  4268  4285 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-01 20:54:53.072  4268  4282 D bt_stack_manager: event_start_up_stack finished
09-01 20:54:53.073  4268  4281 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-01 20:54:53.073  4268  4281 D BluetoothAdapterProperties: Setting state to 15
,09-01 20:54:53.073  4268  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-01 20:54:53.074  4268  4281 I BluetoothAdapterState: Entering BleOnState
,09-01 20:54:53.079  4268  4281 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-01 20:54:53.079  4268  4281 D BluetoothAdapterProperties: Setting state to 11
09-01 20:54:53.079  4268  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-01 20:54:53.087  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:53.090  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:53.092  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
,09-01 20:54:53.093  4268  4268 D HeadsetService: Received start request. Starting profile...
,09-01 20:54:53.096  4268  4268 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-01 20:54:53.097  4268  4268 D HeadsetStateMachine: make
,09-01 20:54:53.109  4268  4268 D HeadsetStateMachine: max_hf_connections = 1
,09-01 20:54:53.110  4268  4268 I bt_bluedroid: get_profile_interface handsfree
09-01 20:54:53.110  4268  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-01 20:54:53.111  4268  4281 I BluetoothAdapterState: Entering PendingCommandState
09-01 20:54:53.110  4268  4285 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-01 20:54:53.116  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
,09-01 20:54:53.123  4268  4268 D A2dpService: Received start request. Starting profile...
,09-01 20:54:53.124  4268  4268 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 20:54:53.124  4268  4268 I bt_bluedroid: get_profile_interface avrcp
,09-01 20:54:53.133  4268  4268 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 20:54:53.133  4268  4268 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 20:54:53.133  4268  4268 D A2dpStateMachine: make
,09-01 20:54:53.136  4268  4268 I bt_bluedroid: get_profile_interface a2dp
09-01 20:54:53.136  4268  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-01 20:54:53.138  4268  4268 I BluetoothHidServiceJni: classInitNative: succeeds
,09-01 20:54:53.138  4268  4302 D A2dpStateMachine: Enter Disconnected: -2
,09-01 20:54:53.139  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
09-01 20:54:53.140  4268  4268 D HidService: Received start request. Starting profile...
09-01 20:54:53.140  4268  4268 I bt_bluedroid: get_profile_interface hidhost
09-01 20:54:53.140  4268  4268 D HidService: setHidService(): set to: null
09-01 20:54:53.141  4268  4285 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397e3e5
09-01 20:54:53.141  4268  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-01 20:54:53.142  4268  4268 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-01 20:54:53.143  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
09-01 20:54:53.144  4268  4268 D HealthService: Received start request. Starting profile...
09-01 20:54:53.145  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 20:54:53.147  4268  4268 I bt_bluedroid: get_profile_interface health
,09-01 20:54:53.150  4268  4268 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-01 20:54:53.151  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
,09-01 20:54:53.152  4268  4268 D PanService: Received start request. Starting profile...
,09-01 20:54:53.152  4268  4268 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 20:54:53.153  4268  4268 I bt_bluedroid: get_profile_interface pan
09-01 20:54:53.153  4268  4285 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-01 20:54:53.160  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
09-01 20:54:53.160  4268  4268 D BluetoothMapService: Received start request. Starting profile...
09-01 20:54:53.161  4268  4268 D BluetoothMapService: start()
,09-01 20:54:53.163  4268  4268 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-01 20:54:53.164  4268  4268 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-01 20:54:53.165  4268  4268 D BluetoothMapAppObserver: createReceiver()
,09-01 20:54:53.166  4268  4268 D BluetoothMapAppObserver: initObservers()
09-01 20:54:53.166  4268  4268 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-01 20:54:53.172  4268  4268 V BluetoothAdapterState: isTurningOff()=false
,09-01 20:54:53.172  4268  4268 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:53.172  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:53.172  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 20:54:53.175  4268  4300 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-01 20:54:53.175  4268  4268 V BluetoothAdapterState: isTurningOff()=false
,09-01 20:54:53.175  4268  4268 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:53.175  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:53.175  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 20:54:53.175  4268  4268 V BluetoothAdapterState: isTurningOff()=false
,09-01 20:54:53.176  4268  4268 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:53.176  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 20:54:53.176  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 20:54:53.177  4268  4268 V BluetoothAdapterState: isTurningOff()=false
,09-01 20:54:53.178  4268  4268 V BluetoothAdapterState: isTurningOn()=true
,09-01 20:54:53.178  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:53.178  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:53.179  4268  4268 V BluetoothAdapterState: isTurningOff()=false
09-01 20:54:53.179  4268  4268 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:53.179  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:53.179  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:53.179  4268  4268 V BluetoothAdapterState: isTurningOff()=false
,09-01 20:54:53.179  4268  4268 V BluetoothAdapterState: isTurningOn()=true
09-01 20:54:53.180  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
09-01 20:54:53.180  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
09-01 20:54:53.182  4268  4281 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-01 20:54:53.182  4268  4281 D BluetoothAdapterProperties: ScanMode =  20
09-01 20:54:53.182  4268  4281 D BluetoothAdapterProperties: State =  11
,09-01 20:54:53.182  4268  4281 D BluetoothAdapterProperties: Setting state to 12
09-01 20:54:53.182  4268  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-01 20:54:53.184  4268  4281 I BluetoothAdapterState: Entering OnState
09-01 20:54:53.185  4268  4285 D BluetoothAdapterProperties: Scan Mode:21
09-01 20:54:53.185  4125  4191 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 20:54:53.185  4268  4285 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 20:54:53.188  4125  4142 D BluetoothPan: onBluetoothStateChange on: true
09-01 20:54:53.190  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:53.190  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:53.190  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:53.190  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:53.190  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:54:53.190  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:53.190  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:53.190  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 20:54:53.191  4125  4143 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 20:54:53.192  4125  4125 D BluetoothA2dp: Proxy object connected
,09-01 20:54:53.195  4268  4268 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-01 20:54:53.196  4268  4268 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-01 20:54:53.196   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 20:54:53.197  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:54:53.198  4268  4268 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 20:54:53.198   872   872 D BluetoothA2dp: Proxy object connected
09-01 20:54:53.198  4125  4142 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 20:54:53.201   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 20:54:53.201  1924  1937 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 20:54:53.201  4268  4268 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 20:54:53.201  1353  3934 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-01 20:54:53.203  1353  2067 D BluetoothMap: onBluetoothStateChange: up=true
09-01 20:54:53.204  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:53.204  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:53.204  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:53.204  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:53.204  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:54:53.204  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:53.204  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:53.204  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 20:54:53.205  4268  4268 D ObexServerSockets: Succeed to create listening sockets 
09-01 20:54:53.205   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 20:54:53.205  4268  4268 D ObexServerSockets0: startAccept()
,09-01 20:54:53.205  4125  4191 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 20:54:53.205  4268  4268 D ObexServerSockets0: prepareForNewConnect()
,09-01 20:54:53.206  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:54:53.207  1353  1365 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 20:54:53.208  4125  4125 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 20:54:53.208  4125  4125 D PanProfile: Bluetooth service connected
09-01 20:54:53.209  1353  1364 D BluetoothPan: onBluetoothStateChange on: true
,09-01 20:54:53.210  1353  1353 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 20:54:53.211  1353  1353 D PanProfile: Bluetooth service connected
09-01 20:54:53.211  1353  2067 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 20:54:53.211  4125  4143 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 20:54:53.212  4268  4307 D ObexServerSockets0: Accepting socket connection...
09-01 20:54:53.212  4268  4268 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-01 20:54:53.212  4268  4268 D BluetoothSdpJni: SDP Create record success - handle: 0
09-01 20:54:53.213   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 20:54:53.213  1353  1365 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 20:54:53.215  1353  1353 D BluetoothInputDevice: Proxy object connected
09-01 20:54:53.215  1353  1353 D HidProfile: Bluetooth service connected
,09-01 20:54:53.216  4125  4125 D BluetoothInputDevice: Proxy object connected
09-01 20:54:53.217  4125  4125 D HidProfile: Bluetooth service connected
09-01 20:54:53.218  1353  1353 D BluetoothMap: Proxy object connected
09-01 20:54:53.218  1353  1353 D MapProfile: Bluetooth service connected
09-01 20:54:53.218  1353  1353 D BluetoothMap: getConnectedDevices()
09-01 20:54:53.218  4125  4125 D BluetoothMap: Proxy object connected
09-01 20:54:53.219  4125  4125 D MapProfile: Bluetooth service connected
09-01 20:54:53.219  4125  4125 D BluetoothMap: getConnectedDevices()
,09-01 20:54:53.218  4268  4308 D ObexServerSockets0: Accepting socket connection...
09-01 20:54:53.220   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,09-01 20:54:53.222  1353  1353 D BluetoothA2dp: Proxy object connected
09-01 20:54:53.224  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:54:53.224  4268  4268 D BluetoothMapService: onReceive
09-01 20:54:53.224  4268  4268 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 20:54:53.224  4268  4268 D BluetoothMapService: STATE_ON
09-01 20:54:53.225  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:54:53.229  4125  4125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 20:54:53.236  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 20:54:53.240  4125  4125 D DockEventReceiver: finishStartingService: stopping service
09-01 20:54:53.244  4125  4125 D BluetoothPbap: Proxy object connected
09-01 20:54:53.244  4125  4125 D PbapServerProfile: Bluetooth service connected
09-01 20:54:53.248  1353  1353 D BluetoothPbap: Proxy object connected
09-01 20:54:53.248  1353  1353 D PbapServerProfile: Bluetooth service connected
,09-01 20:54:53.250  4268  4268 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 20:54:53.250  4268  4268 D ObexServerSockets0: prepareForNewConnect()
09-01 20:54:53.255  4268  4313 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 20:54:53.271  4268  4317 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 20:54:53.272  4268  4317 I BtOppRfcommListener: Accept thread started.
,09-01 20:54:53.296   872   872 D BluetoothHeadset: Proxy object connected
,09-01 20:54:53.296   872   872 D BluetoothHeadset: Proxy object connected
09-01 20:54:53.297  1353  1365 D BluetoothHeadset: Proxy object connected
09-01 20:54:53.297  1353  1353 D HeadsetProfile: Bluetooth service connected
09-01 20:54:53.297  1924  2119 D BluetoothHeadset: Proxy object connected
09-01 20:54:53.297   872   872 D BluetoothHeadset: Proxy object connected
09-01 20:54:53.297  4125  4191 D BluetoothHeadset: Proxy object connected
,09-01 20:54:53.298  4125  4125 D HeadsetProfile: Bluetooth service connected
,09-01 20:54:53.301   872   889 D BluetoothHeadset: Proxy object connected
,09-01 20:54:53.302  1924  2195 D BluetoothHeadset: Proxy object connected
,09-01 20:54:53.305   872   889 D BluetoothHeadset: Proxy object connected
,09-01 20:54:53.311  1353  2067 D BluetoothHeadset: Proxy object connected
,09-01 20:54:53.311  1353  1353 D HeadsetProfile: Bluetooth service connected
,09-01 20:54:53.313   872   889 D BluetoothHeadset: Proxy object connected
,09-01 20:54:55.789   872   883 I ActivityManager: Killing 3723:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-01 20:54:55.849   872   883 I ActivityManager: Killing 3738:com.android.chrome/u0a40 (adj 15): empty #17
,09-01 20:54:56.790  3506  3553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:54:56.790  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:54:56.790  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:54:56.790  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 20:54:56.790  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:54:56.790  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:54:56.790  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:54:56.790  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 20:54:56.797  3506  3553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:54:56.798  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 20:54:56.798  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c314a59 removed from the list
,09-01 20:54:56.799  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:54:56.799  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:54:56.799  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:54:56.802  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 20:54:56.802  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f79f61e added. We now have 4 listener(s)
,09-01 20:54:56.803  3506  3553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 20:54:56.806   872  1557 D WifiService: setWifiEnabled: false pid=3506, uid=10000
09-01 20:54:56.807   872  1557 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 20:55:01.823  3506  3553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:55:01.824   872  1932 D WifiService: setWifiEnabled: true pid=3506, uid=10000
,09-01 20:55:01.824   872  1932 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 20:55:01.836   872  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-01 20:55:01.857  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:55:01.857  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:55:01.857  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:55:01.857  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:55:01.857  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:55:01.857  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:55:01.857  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:55:01.857  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 20:55:01.863  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:55:01.868   872  1307 D WifiConfigStore: loaded 0 passpoint configs
,09-01 20:55:01.869   872  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-01 20:55:01.870   872  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-01 20:55:01.870  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:55:01.870  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:55:01.870  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:55:01.870  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:55:01.870  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:55:01.870  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 20:55:01.870  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 20:55:01.870  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 20:55:01.871   872  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-01 20:55:01.871   872  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-01 20:55:01.871   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-01 20:55:01.872   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-01 20:55:01.875  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 20:55:01.889   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-01 20:55:01.891   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-01 20:55:01.891   372   871 D CommandListener: Setting iface cfg
09-01 20:55:01.891   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-01 20:55:01.891   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-01 20:55:01.951   872  1307 E native  : do suspend true
,09-01 20:55:01.952   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-01 20:55:01.968   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-01 20:55:01.987   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 20:55:03.385   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-01 20:55:05.077   872  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=3.88 rxSuccessRate=3.75 delta 1000 -> 1000
,09-01 20:55:05.087   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-01 20:55:05.087   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 20:55:05.107   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-01 20:55:05.175   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-01 20:55:05.177  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-01 20:55:05.615  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-01 20:55:05.667  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-01 20:55:05.668  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-01 20:55:05.671   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 20:55:05.682   872  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-01 20:55:05.682   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 20:55:05.683   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-01 20:55:05.704   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 20:55:05.724   372   871 D CommandListener: Setting iface cfg
,09-01 20:55:05.730   872  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,09-01 20:55:05.737   872  4325 D DhcpClient: Receive thread started
,09-01 20:55:05.746   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-01 20:55:05.854   872  1307 E native  : do suspend false
,09-01 20:55:05.878   872  3673 D DhcpClient: Broadcasting DHCPDISCOVER
,09-01 20:55:05.908   872  4325 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172763, domain null
,09-01 20:55:05.910   872  3673 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172763 seconds
,09-01 20:55:05.913   872  3673 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-01 20:55:05.927   872  4325 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-01 20:55:05.929   872  3673 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-01 20:55:05.934   372   871 D CommandListener: Setting iface cfg
,09-01 20:55:05.944   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-01 20:55:05.945   872  3673 D DhcpClient: Scheduling renewal in 86399s
,09-01 20:55:05.947   872  1307 E native  : do suspend true
,09-01 20:55:05.977   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-01 20:55:05.977   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-01 20:55:05.978   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-01 20:55:05.980   872  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-01 20:55:05.981   872  1309 D ConnectivityService: Adding iface wlan0 to network 102
,09-01 20:55:06.023   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-01 20:55:06.024   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-01 20:55:06.025   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-01 20:55:06.027   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-01 20:55:06.028   872  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-01 20:55:06.038   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-01 20:55:06.046   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-01 20:55:06.046   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-01 20:55:06.047   872  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-01 20:55:06.049   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 20:55:06.049   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-01 20:55:06.049   872  1309 D ConnectivityService:    accepting network in place of null
,09-01 20:55:06.052   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-01 20:55:06.067   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=418164, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-01 20:55:06.088   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 20:55:06.137   872  4323 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.91,2a00:1450:400d:802::200e
,09-01 20:55:06.148   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 20:55:06.158   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-01 20:55:06.158   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 20:55:06.167   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-01 20:55:06.169   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-01 20:55:06.185   872  4323 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 18:55:06 GMT], X-Android-Received-Millis=[1472756106184], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472756106173]}
,09-01 20:55:06.187  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:55:06.187  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:55:06.187  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:55:06.187  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:55:06.187  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:55:06.187  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 20:55:06.187  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:55:06.187  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 20:55:06.188   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-01 20:55:06.188   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-01 20:55:06.188   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-01 20:55:06.190  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 20:55:06.190   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-01 20:55:06.197  2014  2014 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-01 20:55:06.198  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:55:06.198  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:55:06.198  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:55:06.198  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:55:06.198  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:55:06.198  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 20:55:06.198  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:55:06.198  3506  3506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 20:55:06.200  3506  3506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 20:55:06.217  1753  1753 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 20:55:06.220  1753  1753 D SystemUpdateService: onCreate
,09-01 20:55:06.223  1753  1753 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 20:55:06.241  1753  4336 I SystemUpdateService: active receiver: enabled
,09-01 20:55:06.247  1753  1753 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-01 20:55:06.248  1753  3715 I iu.UploadsManager: num queued entries: 0
09-01 20:55:06.248  1753  3715 I iu.UploadsManager: num updated entries: 0
,09-01 20:55:06.255  1753  4335 I CheckinService: Checking schedule, now: 1472756106255 next: 1472756071799
,09-01 20:55:06.255  1753  4335 I CheckinService: active receiver: enabled
09-01 20:55:06.256  1753  4336 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 20:55:06.257  1753  4335 I CheckinService: Preparing to send checkin request
09-01 20:55:06.257  1753  4335 I EventLogService: Accumulating logs since 1472756059027
,09-01 20:55:06.260  1753  3715 I iu.SyncManager: NEXT; no task
,09-01 20:55:06.261  1753  4336 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true,
09-01 20:55:06.261  1753  4336 I SystemUpdateService: now status is 0 (complete)
09-01 20:55:06.261  1753  4336 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 20:55:06.261  1753  4336 I SystemUpdateService: file has been verified
09-01 20:55:06.261  1753  4336 I SystemUpdateService: OTA package size = 12249756
,09-01 20:55:06.264  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 20:55:06.265  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 20:55:06.269  1753  4336 I SystemUpdateService: showing system update notification
,09-01 20:55:06.281   872  2827 I ActivityManager: Start proc 4341:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-01 20:55:06.287  1753  4338 I MDM     : [193] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-01 20:55:06.287  1753  4338 W BaseAppContext: Using Auth Proxy for data requests.
09-01 20:55:06.288  1753  4335 I EventLogService: Opted in for usage reporting
09-01 20:55:06.289  1753  4338 V GoogleAuthProtoRequest: [193] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 20:55:06.299  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:06.301  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:06.329  1753  1753 D SystemUpdateService: onDestroy
,09-01 20:55:06.339  4341  4341 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-01 20:55:06.342  4341  4341 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 20:55:06.342  1535  2091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-01 20:55:06.346  1535  2091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-01 20:55:06.346  1535  2091 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:06.346  1535  2091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:06.357  4341  4341 D SprintDMHelper: simOperator: 
,09-01 20:55:06.357  4341  4341 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 20:55:06.354  1753  4335 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,09-01 20:55:06.370   872  1373 I ActivityManager: Start proc 4354:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-01 20:55:06.374  1753  4335 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,09-01 20:55:06.405  1753  4338 E MDM     : [193] SitrepService.a: Error sending sitrep.
,09-01 20:55:06.497  3572  4369 V GoogleAuthProtoRequest: [283] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 20:55:06.540  1535  2376 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-01 20:55:06.540  1535  2376 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-01 20:55:06.540  1535  2376 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 20:55:06.540  1535  2376 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:06.586  3286  4370 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-01 20:55:06.586  3286  4370 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at jdm.a(PG:82)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at jcs.o(PG:406)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at jcn.a(PG:1379)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at jcs.i(PG:143)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at blb.a(PG:3937)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at czp.a(PG:18188)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at czp.a(PG:9087)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at czq.run(PG:1686)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 20:55:06.586  3286  4370 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at jdj.a(PG:4091)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at jdj.a(PG:1125)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at jdm.a(PG:77)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	... 12 more
09-01 20:55:06.586  3286  4370 E HttpOperation: Caused by: faj: BadAuthentication
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at fal.a(PG:38)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	at jdj.a(PG:4089)
09-01 20:55:06.586  3286  4370 E HttpOperation: 	... 14 more
,09-01 20:55:06.665  1535  2091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-01 20:55:06.665  1535  2091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-01 20:55:06.665  1535  2091 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 20:55:06.665  1535  2091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:06.790  2883  4374 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-01 20:55:06.823  3572  4369 W ExperimentUpdateService: [283] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
09-01 20:55:06.824  3572  4369 W ExperimentUpdateService: [283] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-01 20:55:06.824  3572  4369 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-01 20:55:06.824  3572  4369 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-01 20:55:06.824  3572  4369 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-01 20:55:06.824  3572  4369 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-01 20:55:06.824  3572  4369 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-01 20:55:06.824  3572  4369 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-01 20:55:06.824  3572  4369 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-01 20:55:06.824  3572  4369 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-01 20:55:06.824  3572  4369 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-01 20:55:06.824  3572  4369 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-01 20:55:06.880  3506  3553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 20:55:06.880  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:55:06.880  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:55:06.880  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:55:06.880  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:55:06.880  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 20:55:06.880  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:55:06.880  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 20:55:06.886  3506  3553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 20:55:06.886  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 20:55:06.886  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f79f61e removed from the list
09-01 20:55:06.886  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:55:06.886  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:55:06.886  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:55:06.895  3506  4381 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-01 20:55:06.895  3506  4381 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-01 20:55:06.931  3048  4368 V KeepSync: Connecting to GoogleApiClient
,09-01 20:55:06.943   872  1951 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-01 20:55:07.005  1535  3750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-01 20:55:07.005  1535  3750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-01 20:55:07.005  1535  3750 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 20:55:07.005  1535  3750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:07.039  3286  4376 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-01 20:55:07.039  3286  4376 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at jdm.a(PG:82)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at jcs.o(PG:406)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at jcn.a(PG:1379)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at jcs.i(PG:143)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at blb.a(PG:3937)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at czp.a(PG:18188)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at czp.a(PG:9081)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at czq.run(PG:1686)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 20:55:07.039  3286  4376 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at jdj.a(PG:4091)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at jdj.a(PG:1125)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at jdm.a(PG:77)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	... 12 more
09-01 20:55:07.039  3286  4376 E HttpOperation: Caused by: faj: BadAuthentication
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at fal.a(PG:38)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	at jdj.a(PG:4089)
09-01 20:55:07.039  3286  4376 E HttpOperation: 	... 14 more
,09-01 20:55:07.102  1535  2091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-01 20:55:07.102  1535  2091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-01 20:55:07.103  1535  2091 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:07.103  1535  2091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:07.104  1535  1549 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-01 20:55:07.104  1535  1549 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-01 20:55:07.104  1535  1549 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:07.104  1535  1549 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:07.131  1753  4382 V BaseAuthAsyncOperation: access token request failed
,09-01 20:55:07.132  3048  4368 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-01 20:55:07.148  3286  4376 E HttpOperation: [getmobileexperiments] Unexpected exception
09-01 20:55:07.148  3286  4376 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at jdm.a(PG:82)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at jcs.o(PG:406)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at jcn.a(PG:1379)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at jcs.i(PG:143)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at hec.a(PG:42)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at hee.a(PG:102)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at czr.a(PG:65)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at kka.a(PG:108)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at czp.a(PG:19176)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at czp.a(PG:9081)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at czq.run(PG:1686)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 20:55:07.148  3286  4376 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at jdj.a(PG:4091)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at jdj.a(PG:1125)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at jdm.a(PG:77)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	... 15 more
09-01 20:55:07.148  3286  4376 E HttpOperation: Caused by: faj: BadAuthentication
09-01 20:55:07.148  3286  4376 E HttpOperation: 	at fal.a(PG:38)
09-01 20:5,5:07.148  3286  4376 E HttpOperation: 	at jdj.a(PG:4089)
09-01 20:55:07.148  3286  4376 E HttpOperation: 	... 17 more
09-01 20:55:07.148  3286  4376 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-01 20:55:07.148  3286  4376 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at jdm.a(PG:82)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at jcs.o(PG:406)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at jcn.a(PG:1379)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at jcs.i(PG:143)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at hec.a(PG:42)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at hee.a(PG:102)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at czr.a(PG:65)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at kka.a(PG:108)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at czp.a(PG:19176)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at czp.a(PG:9081)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at czq.run(PG:1686)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at jdj.a(PG:4091)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at jdj.a(PG:1125)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at jdm.a(PG:77)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	... 15 more
09-01 20:55:07.148  3286  4376 E ExperimentLoader: Caused by: faj: BadAuthentication
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at fal.a(PG:38)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	at jdj.a(PG:4089)
09-01 20:55:07.148  3286  4376 E ExperimentLoader: 	... 17 more
,09-01 20:55:07.156   872  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network,
,09-01 20:55:07.255  1535  2376 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
09-01 20:55:07.255  1535  2376 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
,09-01 20:55:07.255  1535  2376 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:07.255  1535  2376 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:07.281   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 372012, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-01 20:55:07.290  1753  4335 W CheckinRequestBuilder: awaiting user notification for token
,09-01 20:55:07.326  1535  2091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-01 20:55:07.327  1535  2091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-01 20:55:07.327  1535  2091 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:07.327  1535  2091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:07.366   872   884 I ActivityManager: Start proc 4383:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-01 20:55:07.384   872  1950 I ActivityManager: Start proc 4394:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,09-01 20:55:07.418  4383  4383 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-01 20:55:07.429  3048  4368 E KeepSync: IOException
09-01 20:55:07.429  3048  4368 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-01 20:55:07.429  3048  4368 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-01 20:55:07.429  3048  4368 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-01 20:55:07.429  3048  4368 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-01 20:55:07.429  3048  4368 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-01 20:55:07.429  3048  4368 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-01 20:55:07.429  3048  4368 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-01 20:55:07.429  3048  4368 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-01 20:55:07.429  3048  4368 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-01 20:55:07.429  3048  4368 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-01 20:55:07.429  3048  4368 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-01 20:55:07.429  3048  4368 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-01 20:55:07.429  3048  4368 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-01 20:55:07.429  3048  4368 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-01 20:55:07.429  3048  4368 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-01 20:55:07.429  3048  4368 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-01 20:55:07.429  3048  4368 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-01 20:55:07.429  3048  4368 E KeepSync: 	... 10 more
,09-01 20:55:07.437  4394  4394 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-01 20:55:07.429  3048  4368 W KeepSync: Sync result 2
,09-01 20:55:07.449   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 404213, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-01 20:55:07.456  4394  4394 I MultiDex: VM with version 2.1.0 has multidex support
,09-01 20:55:07.456  4394  4394 I MultiDex: install
09-01 20:55:07.457  4394  4394 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-01 20:55:07.495  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:07.506  4383  4383 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-01 20:55:07.516  4383  4383 I BooksApp: Created application version: 3.6.9 (30609)
,09-01 20:55:07.519  1535  1549 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-01 20:55:07.519  1535  1549 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-01 20:55:07.520  1535  1549 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:07.520  1535  1549 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:07.540  4394  4394 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-01 20:55:07.541  4200  4200 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-01 20:55:07.542  4200  4200 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-01 20:55:07.542  4200  4200 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-01 20:55:07.551   872  1951 I ActivityManager: Killing 4054:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-01 20:55:07.579  4394  4394 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-01 20:55:07.614  1535  2112 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-01 20:55:07.621  1535  1535 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-01 20:55:07.635  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:07.641  1753  1753 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-01 20:55:07.681  4240  4240 D WearableService: callingUid 10011, callindPid: 4240
,09-01 20:55:07.692  2134  2266 E MDM     : [122] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-01 20:55:07.747  1753  4418 D LocationInitializer: Restart initialization of location
,09-01 20:55:07.777  4383  4414 I BooksSync: Starting books sync for 61035162, extras: ade
,09-01 20:55:07.826   376  1316 D WVCdm   : Instantiating CDM.
,09-01 20:55:07.828   376   376 I WVCdm   : CdmEngine::OpenSession
,09-01 20:55:07.828   376   376 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,09-01 20:55:07.837   376   376 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-01 20:55:07.843   376   376 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
,09-01 20:55:07.843   376   376 D DrmWidevineDash: Service_Initialize: starts!
,09-01 20:55:07.843   376   376 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-01 20:55:07.844   376   376 D QSEECOMAPI: : App is not loaded in QSEE
,09-01 20:55:08.045  4421  4421 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,09-01 20:55:08.102  2134  2212 W GCoreFlp: No location to return for getLastLocation()
,09-01 20:55:08.105  1535  4419 W FusedLocationProvider: location=null
,09-01 20:55:08.108  4421  4421 I dex2oat : dex2oat took 64.485ms (threads: 4) arena alloc=50KB java alloc=43KB native alloc=1281KB free=1534KB
,09-01 20:55:08.117  4394  4405 W System  : ClassLoader referenced unknown path: 
,09-01 20:55:08.127  4394  4405 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 20:55:08.127  4394  4405 I Adreno  : Build Date                       : 10/20/15
09-01 20:55:08.127  4394  4405 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 20:55:08.127  4394  4405 I Adreno  : Local Branch                     : M14
09-01 20:55:08.127  4394  4405 I Adreno  : Remote Branch                    : 
09-01 20:55:08.127  4394  4405 I Adreno  : Remote Branch                    : 
09-01 20:55:08.127  4394  4405 I Adreno  : Reconstruct Branch               : 
,09-01 20:55:08.188   376   376 D QSEECOMAPI: : Loaded image: APP id = 3
,09-01 20:55:08.190   376   376 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-01 20:55:08.190   376   376 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2aa6000
09-01 20:55:08.191   376   376 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2aa6000
,09-01 20:55:08.196   331   338 D DrmLibTime: got the req here! ret=0
,09-01 20:55:08.196   331   338 D DrmLibTime: command id, time_cmd_id = 770
09-01 20:55:08.196   331   338 D DrmLibTime: time_getutcsec starts!
09-01 20:55:08.196   331   338 D DrmLibTime: QSEE Time Listener: time_getutcsec
,09-01 20:55:08.196   331   338 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-01 20:55:08.196   331   338 D DrmLibTime: QSEE Time Listener: seconds: 1472756108
09-01 20:55:08.196   331   338 D DrmLibTime: QSEE Time Listener: nano seconds: 196564587
,09-01 20:55:08.196   331   338 D DrmLibTime: time_getutcsec returns 0, sec = 1472756108; nsec = 196564587
09-01 20:55:08.196   331   338 D DrmLibTime: time_getutcsec finished! 
,09-01 20:55:08.196   331   338 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-01 20:55:08.196   331   338 D DrmLibTime: before calling ioctl to read the next time_cmd
09-01 20:55:08.202   376   376 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,09-01 20:55:08.202   376   376 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-01 20:55:08.202   376   376 D DrmWidevineDash: hlos api version =  10
09-01 20:55:08.202   376   376 D DrmWidevineDash: tz api version =  10
,09-01 20:55:08.202   376   376 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-01 20:55:08.203   376   376 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,09-01 20:55:08.214   376   376 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,09-01 20:55:08.215   376   376 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-01 20:55:08.215   376   376 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbecd2214
,09-01 20:55:08.215   376   376 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-01 20:55:08.215   376   376 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-01 20:55:08.215   376   376 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb3b03018, dataLength=8
09-01 20:55:08.216   376   376 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-01 20:55:08.216   376   376 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb60fe200, wrapped_rsa_key_length=1280
09-01 20:55:08.219   376   376 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,09-01 20:55:08.219   376   376 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-01 20:55:08.220   376  1279 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-01 20:55:08.220   376  1279 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
09-01 20:55:08.220   376  1279 I WVCdm   : CdmEngine::GenerateKeyRequest
09-01 20:55:08.220   376  1279 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb2cded20, idLength=0xb2ffff2c
,09-01 20:55:08.248   376  1279 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
09-01 20:55:08.249   376  1279 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,09-01 20:55:08.249  4394  4405 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 20:55:08.249  4394  4405 I Adreno  : Build Date                       : 10/20/15
09-01 20:55:08.249  4394  4405 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 20:55:08.249  4394  4405 I Adreno  : Local Branch                     : M14
09-01 20:55:08.249  4394  4405 I Adreno  : Remote Branch                    : 
09-01 20:55:08.249  4394  4405 I Adreno  : Remote Branch                    : 
09-01 20:55:08.249  4394  4405 I Adreno  : Reconstruct Branch               : 
09-01 20:55:08.251   376  1279 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-01 20:55:08.251   376  1279 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
09-01 20:55:08.252   376  1279 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
09-01 20:55:08.252   376  1279 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
09-01 20:55:08.254   376  1279 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
09-01 20:55:08.257   376  1279 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-01 20:55:08.258   376  1279 D DrmWidevineDash: hlos api version =  10
09-01 20:55:08.258   376  1279 D DrmWidevineDash: tz api version =  10
09-01 20:55:08.258   376  1279 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-01 20:55:08.258   376  1279 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
09-01 20:55:08.259   376  1279 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
09-01 20:55:08.259   376  1279 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
09-01 20:55:08.259   376  1279 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
09-01 20:55:08.259   376  1279 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,09-01 20:55:08.260   376  1279 D WVCdm   : PrepareKeyRequest: nonce=3891917008
09-01 20:55:08.260   376  1279 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb2af9000
09-01 20:55:08.261   376  1279 D DrmWidevineDash: message_length=1624, signature=0xb3b1a500, signature_length=3003121668
09-01 20:55:08.338   376  1279 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
09-01 20:55:08.339   376  1316 I WVCdm   : CdmEngine::CloseSession
09-01 20:55:08.340   376  1316 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-01 20:55:08.340   376  1316 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-01 20:55:08.340   376  1316 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-01 20:55:08.341   376  1316 D DrmWidevineDash: Service_Uninitialize: starts!
09-01 20:55:08.341   376  1316 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-01 20:55:08.341   376  1316 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
09-01 20:55:08.342   376  1316 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,09-01 20:55:08.342   376  1316 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
09-01 20:55:08.343   376  1315 I WVCdm   : CdmEngine::OpenSession
09-01 20:55:08.343   376  1315 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,09-01 20:55:08.345   376  1315 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-01 20:55:08.347   376  1315 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
09-01 20:55:08.347   376  1315 D DrmWidevineDash: Service_Initialize: starts!
,09-01 20:55:08.347   376  1315 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-01 20:55:08.347   376  1315 D QSEECOMAPI: : App is not loaded in QSEE
,09-01 20:55:08.357  4394  4416 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,09-01 20:55:08.486  4383  4436 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-01 20:55:08.524  1535  2822 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-01 20:55:08.524  1535  2822 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-01 20:55:08.524  1535  2822 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:08.524  1535  2822 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:08.555  1535  2376 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-01 20:55:08.555  1535  2376 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-01 20:55:08.555  1535  2376 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:08.555  1535  2376 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:08.569  4383  4436 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-01 20:55:08.570  4383  4414 E BooksSync: Soft error
09-01 20:55:08.570  4383  4414 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-01 20:55:08.570  4383  4414 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-01 20:55:08.571  4383  4414 E BooksSync: Sync error
09-01 20:55:08.571  4383  4414 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-01 20:55:08.571  4383  4414 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-01 20:55:08.571  4383  4414 I BooksSync: Finished books sync
,09-01 20:55:08.578   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 404679, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-01 20:55:08.662   376  1315 D QSEECOMAPI: : Loaded image: APP id = 3
,09-01 20:55:08.664   376  1315 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-01 20:55:08.664   376  1315 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2aa6000
09-01 20:55:08.664   376  1315 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2aa6000
,09-01 20:55:08.671   331   338 D DrmLibTime: got the req here! ret=0
09-01 20:55:08.671   331   338 D DrmLibTime: command id, time_cmd_id = 770
09-01 20:55:08.671   331   338 D DrmLibTime: time_getutcsec starts!
09-01 20:55:08.671   331   338 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-01 20:55:08.671   331   338 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-01 20:55:08.671   331   338 D DrmLibTime: QSEE Time Listener: seconds: 1472756108
09-01 20:55:08.671   331   338 D DrmLibTime: QSEE Time Listener: nano seconds: 671344634
09-01 20:55:08.671   331   338 D DrmLibTime: time_getutcsec returns 0, sec = 1472756108; nsec = 671344634
09-01 20:55:08.671   331   338 D DrmLibTime: time_getutcsec finished! 
09-01 20:55:08.671   331   338 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-01 20:55:08.671   331   338 D DrmLibTime: before calling ioctl to read the next time_cmd
,09-01 20:55:08.679   376  1315 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,09-01 20:55:08.679   376  1315 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-01 20:55:08.680   376  1315 D DrmWidevineDash: hlos api version =  10
09-01 20:55:08.680   376  1315 D DrmWidevineDash: tz api version =  10
,09-01 20:55:08.680   376  1315 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-01 20:55:08.680   376  1315 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,09-01 20:55:08.692   376  1315 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
09-01 20:55:08.692   376  1315 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-01 20:55:08.692   376  1315 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb2f01134
,09-01 20:55:08.693   376  1315 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-01 20:55:08.693   376  1315 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-01 20:55:08.693   376  1315 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb60cc588, dataLength=8
,09-01 20:55:08.694   376  1315 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
09-01 20:55:08.694   376  1315 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb6088800, wrapped_rsa_key_length=1280
,09-01 20:55:08.697   376  1315 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-01 20:55:08.697   376  1315 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-01 20:55:08.699   376  1316 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-01 20:55:08.700   376  1316 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
09-01 20:55:08.700   376  1316 I WVCdm   : CdmEngine::GenerateKeyRequest
09-01 20:55:08.700   376  1316 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb2cded00, idLength=0xb2e01f2c
,09-01 20:55:08.730   376  1316 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,09-01 20:55:08.732   376  1316 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,09-01 20:55:08.735   376  1316 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-01 20:55:08.735   376  1316 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
09-01 20:55:08.736   376  1316 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
,09-01 20:55:08.736   376  1316 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,09-01 20:55:08.738   376  1316 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
09-01 20:55:08.739   376  1316 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,09-01 20:55:08.741   376  1316 D DrmWidevineDash: hlos api version =  10
09-01 20:55:08.741   376  1316 D DrmWidevineDash: tz api version =  10
,09-01 20:55:08.741   376  1316 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,09-01 20:55:08.741   376  1316 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
09-01 20:55:08.743   376  1316 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,09-01 20:55:08.744   376  1316 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
,09-01 20:55:08.745   376  1316 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
09-01 20:55:08.746   376  1316 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-01 20:55:08.747   376  1316 D WVCdm   : PrepareKeyRequest: nonce=1432746962
09-01 20:55:08.747   376  1316 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb2af9700
,09-01 20:55:08.747   376  1316 D DrmWidevineDash: message_length=1655, signature=0xb3b1ab40, signature_length=3001032708
,09-01 20:55:08.846   376  1316 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-01 20:55:08.849   376  1315 I WVCdm   : CdmEngine::CloseSession
,09-01 20:55:08.849   376  1315 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,09-01 20:55:08.852   376  1315 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-01 20:55:08.853   376  1315 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,09-01 20:55:08.856   376  1315 D DrmWidevineDash: Service_Uninitialize: starts!
09-01 20:55:08.856   376  1315 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-01 20:55:08.857   376  1315 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
09-01 20:55:08.859   376  1315 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,09-01 20:55:08.861   376  1315 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-01 20:55:09.067  4405  4405 W Binder_1: type=1400 audit(0.0:9): avc: denied { read } for name="/" dev="tmpfs" ino=11265 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=dir permissive=0
,09-01 20:55:09.121  1753  4335 I CheckinRequestBuilder: Classify the device as Phone.
,09-01 20:55:09.129  1753  4335 I EventLogService: Opted in for usage reporting
,09-01 20:55:09.434  1753  4335 I CheckinTask: Sending checkin request (10369 bytes)
,09-01 20:55:09.902  3506  4442 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-01 20:55:09.903  3506  4442 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-01 20:55:09.903  3506  4381 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-01 20:55:09.904  3506  4381 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-01 20:55:09.904  3506  4442 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-01 20:55:09.905  3506  4381 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-01 20:55:09.908  3506  4381 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-01 20:55:09.908  3506  4442 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-01 20:55:09.911  3506  4444 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 381, name: OutgoingSocketThread/Sender)
09-01 20:55:09.911  3506  4442 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-01 20:55:09.913  3506  4445 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 380, name: IncomingSocketThread/Sender)
09-01 20:55:09.914  3506  4381 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-01 20:55:09.917  3506  4446 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 383, name: IncomingSocketThread/Receiver)
,09-01 20:55:09.919  3506  4447 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 382, name: OutgoingSocketThread/Receiver)
09-01 20:55:09.919  3506  4446 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 383, thread name: IncomingSocketThread/Receiver)
,09-01 20:55:09.920  3506  4446 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-01 20:55:09.920  3506  4446 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 383, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-01 20:55:09.920  3506  4447 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 382, thread name: OutgoingSocketThread/Receiver)
09-01 20:55:09.921  3506  4447 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-01 20:55:09.921  3506  4447 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 382, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-01 20:55:10.001  1753  4335 I CheckinResponseProcessor: From server: 2 gservices updates and 0 deletes,
,09-01 20:55:10.126  1535  3750 I GservicesProvider: main difference update completed
,09-01 20:55:10.167   872   885 I ActivityManager: Start proc 4450:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,09-01 20:55:10.168  1753  4335 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,09-01 20:55:10.174   872  2827 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
09-01 20:55:10.177  2883  2883 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
09-01 20:55:10.178  2883  2883 W Babel   : BAM#gBA: invalid account id: -1
09-01 20:55:10.178  2883  2883 W Babel   : BAM#gBA: invalid account id: -1
09-01 20:55:10.178  2883  2883 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-01 20:55:10.183  1753  4335 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,09-01 20:55:10.222  4450  4450 W System  : ClassLoader referenced unknown path: /system/priv-app/ConfigUpdater/lib/arm
,09-01 20:55:10.241  4450  4450 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION intent_firewall: null null
,09-01 20:55:10.253  4450  4450 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION apn_db: null null
,09-01 20:55:10.257  4450  4450 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION tzdata: null null
,09-01 20:55:10.262  4450  4450 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION selinux: null null
,09-01 20:55:10.265  4450  4450 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION carrier_provisioning_urls: null null
,09-01 20:55:10.283  3572  3572 W InstanceID/Rpc: Found 10011
,09-01 20:55:10.316   872  1950 I ActivityManager: Start proc 4476:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,09-01 20:55:10.318   872  1950 I ActivityManager: Killing 4042:com.google.android.gm/u0a78 (adj 15): empty #17
,09-01 20:55:10.379  4476  4476 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,09-01 20:55:10.465  1535  1549 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
09-01 20:55:10.465  1535  1549 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
09-01 20:55:10.465  1535  1549 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 20:55:10.465  1535  1549 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:10.471   872  1558 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,09-01 20:55:10.496  1753  4335 W CheckinRequestBuilder: awaiting user notification for token
,09-01 20:55:10.510  1753  4335 I CheckinRequestBuilder: Classify the device as Phone.
,09-01 20:55:10.510  1753  1753 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,09-01 20:55:10.512  1753  1753 D SystemUpdateService: onCreate
,09-01 20:55:10.516  1753  1753 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 20:55:10.525  1753  1753 D OcrModelManager: Updating downloaded model state (gservices changed)
,09-01 20:55:10.529  1753  4335 I EventLogService: Opted in for usage reporting
,09-01 20:55:10.530  1753  1753 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
09-01 20:55:10.531  1753  1753 I OcrUtils: Updating ocr activity enabled=false
09-01 20:55:10.531  1535  2261 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,09-01 20:55:10.538  1753  4499 I SystemUpdateService: active receiver: enabled
,09-01 20:55:10.547  1753  4335 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,09-01 20:55:10.558  1753  4499 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 20:55:10.560  1753  4335 I CheckinService: Checking schedule, now: 1472756110560 next: 1472797253547
,09-01 20:55:10.561  1753  4335 I CheckinService: active receiver: disabled
,09-01 20:55:10.566  1753  4499 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-01 20:55:10.566  2134  2134 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
09-01 20:55:10.566  1753  4499 I SystemUpdateService: now status is 0 (complete)
,09-01 20:55:10.566  1753  4499 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-01 20:55:10.568  1753  4499 I SystemUpdateService: file has been verified
,09-01 20:55:10.568  1753  4499 I SystemUpdateService: OTA package size = 12249756
09-01 20:55:10.577  1753  4505 I CheckinService: Checking schedule, now: 1472756110577 next: 1472797253547
09-01 20:55:10.578  1753  4505 I CheckinService: active receiver: disabled
09-01 20:55:10.580  2134  2134 I GCoreUlr: DispatchingService.onCreate()
,09-01 20:55:10.591  1753  4499 I SystemUpdateService: showing system update notification
,09-01 20:55:10.641   872  1967 I ActivityManager: Killing 4030:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,09-01 20:55:10.701  2134  4506 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,09-01 20:55:10.781  2134  4506 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,09-01 20:55:10.785  2134  4506 I GCoreUlr: Unbound from all location providers
,09-01 20:55:10.801  2134  2134 I GCoreUlr: DispatchingService.onDestroy()
,09-01 20:55:10.801  2134  2134 I GCoreUlr: Stopping handler for UlrDispSvcFast
,09-01 20:55:10.804  2134  2134 I GCoreUlr: Unbound from all location providers
,09-01 20:55:10.849  1753  1753 D SystemUpdateService: onDestroy
,09-01 20:55:10.926  2014  4517 I GservicesUpdateTask: Updating Gservices keys
,09-01 20:55:10.964  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 20:55:10.969  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 20:55:10.973  1535  2479 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-01 20:55:12.522  4383  4412 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-01 20:55:12.705   872  2827 I ActivityManager: Killing 4000:android.process.acore/u0a5 (adj 15): empty #17
,09-01 20:55:12.901  3506  3553 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-01 20:55:12.903  3506  3553 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-01 20:55:12.911  3506  3553 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a06d43d Bundle[{}]
09-01 20:55:12.912  3506  3553 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-01 20:55:12.912  3506  3553 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-01 20:55:12.912  3506  3553 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-01 20:55:12.913  3506  3553 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-01 20:55:12.914  3506  3553 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-01 20:55:12.914  3506  3553 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-01 20:55:12.919  3506  3553 I System.out: Running OutgoingSocketThread
,09-01 20:55:12.924  3506  4525 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-01 20:55:12.924  3506  4525 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-01 20:55:14.050   872  1309 D ConnectivityService: handlePromptUnvalidated 102
,09-01 20:55:14.133   872  1951 I ActivityManager: Killing 4125:com.android.settings/1000 (adj 15): empty #17
,09-01 20:55:15.770   872  1950 I ActivityManager: Killing 4147:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,09-01 20:55:15.932  3506  4528 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-01 20:55:15.933  3506  4528 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-01 20:55:15.933  3506  4528 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-01 20:55:15.934  3506  4525 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-01 20:55:15.934  3506  4525 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-01 20:55:15.934  3506  4525 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-01 20:55:15.934  3506  4528 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-01 20:55:15.937  3506  4530 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 392, name: IncomingSocketThread/Sender)
09-01 20:55:15.938  3506  4528 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-01 20:55:15.941  3506  4525 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-01 20:55:15.941  3506  4531 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 394, name: IncomingSocketThread/Receiver)
09-01 20:55:15.942  3506  4525 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-01 20:55:15.943  3506  4531 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 394, thread name: IncomingSocketThread/Receiver)
09-01 20:55:15.943  3506  4531 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-01 20:55:15.943  3506  4531 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 394, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-01 20:55:15.946  3506  4533 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 395, name: OutgoingSocketThread/Receiver)
,09-01 20:55:15.946  3506  4533 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 395, thread name: OutgoingSocketThread/Receiver)
,09-01 20:55:15.947  3506  4533 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-01 20:55:15.947  3506  4533 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 395, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-01 20:55:15.950  3506  4532 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 393, name: OutgoingSocketThread/Sender)
,09-01 20:55:17.625  4200  4212 D Finsky  : [333] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-01 20:55:17.661  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:17.684  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:17.693  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:17.789  1535  3750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-01 20:55:17.789  1535  3750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-01 20:55:17.790  1535  3750 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:17.790  1535  3750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:17.844  4200  4212 D Finsky  : [333] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-01 20:55:18.934  3506  3553 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 404)
,09-01 20:55:18.937  3506  3553 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-01 20:55:18.938  3506  3553 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 405)
,09-01 20:55:18.943  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 20:55:18.943  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f1eff added. We now have 3 listener(s)
09-01 20:55:18.945  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 20:55:18.945  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 20:55:18.945  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 20:55:18.945  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 20:55:18.945  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ec14cc added. We now have 4 listener(s)
09-01 20:55:18.946  3506  3553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 20:55:18.947  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 20:55:18.952  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 20:55:18.961  3506  3553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 20:55:18.961  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:55:18.961  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:55:18.961  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:55:18.961  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:55:18.961  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 20:55:18.961  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:55:18.961  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 20:55:18.966  3506  3553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 20:55:18.967  3506  3553 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 20:55:18.967  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:55:18.968  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:55:18.968  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 20:55:18.968  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:55:18.969  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:55:18.969  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-01 20:55:18.969  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 20:55:18.969  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f1eff removed from the list
09-01 20:55:18.970  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:55:18.970  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ec14cc removed from the list
,09-01 20:55:18.975  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:55:18.983  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:55:18.984  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:55:18.985  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:55:18.986  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:55:18.986  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:55:18.989  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 20:55:18.990  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:55:18.990  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:55:18.990  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ec14cc not in the list
09-01 20:55:18.990  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:55:18.991  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:55:18.993  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:55:18.994  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 20:55:18.994  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:55:18.994  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ec14cc not in the list
09-01 20:55:18.994  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:55:18.995  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:55:18.995  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:55:18.995  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f1eff not in the list
,09-01 20:55:18.997  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 20:55:18.998  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74b562a added. We now have 3 listener(s)
,09-01 20:55:19.004  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 20:55:19.004  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 20:55:19.005  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 20:55:19.005  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 20:55:19.005  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd0ac1b added. We now have 4 listener(s)
09-01 20:55:19.006  3506  3553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 20:55:19.007  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 20:55:19.015  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 20:55:19.029  3506  3553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 20:55:19.029  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:55:19.029  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:55:19.029  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 20:55:19.029  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:55:19.029  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 20:55:19.029  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:55:19.029  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 20:55:19.037  3506  3553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 20:55:19.038  3506  3553 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 20:55:19.038  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 20:55:19.039  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-01 20:55:19.039  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 20:55:19.040  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 20:55:19.040  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 20:55:19.047  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:55:19.050  3506  3553 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-01 20:55:19.051  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 20:55:19.056  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 20:55:19.068  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 20:55:19.072  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-01 20:55:19.074  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 20:55:19.087  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 20:55:19.087  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-01 20:55:19.091  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 20:55:19.093  3506  3553 D BluetoothAdapter: STATE_ON
,09-01 20:55:19.103  4268  4309 D BtGatt.GattService: registerClient() - UUID=0568f363-b8ed-4e97-92dd-2bd33288398c
,09-01 20:55:19.105  4268  4285 D BtGatt.GattService: onClientRegistered() - UUID=0568f363-b8ed-4e97-92dd-2bd33288398c, clientIf=5
,09-01 20:55:19.108  3506  3545 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-01 20:55:19.111  4268  4299 D BtGatt.GattService: start scan with filters
,09-01 20:55:19.121  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-01 20:55:19.122  4268  4288 D BtGatt.ScanManager: handling starting scan
,09-01 20:55:19.123  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-01 20:55:19.123  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-01 20:55:19.123  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-01 20:55:19.128  4268  4288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@229a901
09-01 20:55:19.133  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 20:55:19.134  3506  3506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 20:55:19.134  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 20:55:19.141  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 20:55:19.145  4268  4285 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-01 20:55:19.145  4268  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 20:55:19.146  3506  3553 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-01 20:55:19.146  4268  4288 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-01 20:55:19.147  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 20:55:19.147  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 20:55:19.147  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:55:19.147  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-01 20:55:19.147  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 20:55:19.147  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 20:55:19.147  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 20:55:19.147  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 20:55:19.147  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-01 20:55:19.148  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 20:55:19.148  3506  3553 D BluetoothAdapter: STATE_ON
09-01 20:55:19.150  4268  4299 D BtGatt.GattService: stopScan() - queue size =1
09-01 20:55:19.151  4268  4279 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 20:55:19.152  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 20:55:19.152  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-01 20:55:19.152  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 20:55:19.152  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 20:55:19.152  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 20:55:19.153  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 20:55:19.154  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 20:55:19.154  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 20:55:19.154  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 20:55:19.155  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 20:55:19.156  3506  3506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 20:55:19.156  3506  3506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 20:55:19.156  3506  3506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 20:55:19.161  4268  4285 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-01 20:55:19.162  4268  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 20:55:19.163  4268  4288 D BtGatt.ScanManager: Starting BLE batch scan
,09-01 20:55:19.163  4268  4288 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-01 20:55:19.178  4268  4285 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-01 20:55:19.178  4268  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 20:55:19.187  4268  4285 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-01 20:55:19.187  4268  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 20:55:19.200  4268  4285 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-01 20:55:19.200  4268  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 20:55:19.201  4268  4288 D BtGatt.ScanManager: stopping BLe Batch
,09-01 20:55:19.210  4268  4285 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
09-01 20:55:19.210  4268  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 20:55:19.210  4268  4288 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-01 20:55:19.218  4268  4285 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-01 20:55:19.218  4268  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 20:55:19.657  3506  3506 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 20:55:19.658  3506  3506 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:55:19.658  3506  3506 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-01 20:55:20.602   872   895 W PackageSettings: Skipping PackageSetting{ede18aa com.example.hello/10273} due to missing metadata
,09-01 20:55:20.669   872  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-01 20:55:20.710   872  1557 I ActivityManager: Start proc 4538:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-01 20:55:20.754  4538  4538 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-01 20:55:20.763  2134  2134 V GmsNetworkLocationProvi: DISABLE
,09-01 20:55:20.767  2134  2134 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,09-01 20:55:20.817  4538  4538 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-01 20:55:20.845  1753  4555 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-01 20:55:20.848  1753  4555 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-01 20:55:20.868  1753  2340 I Icing   : updateResources: need to parse f{com.google.android.gms}
,09-01 20:55:20.872  2014  4557 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-01 20:55:20.907  2014  4557 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 35 ms] updated apps [took 35 ms] 
,09-01 20:55:20.927  4538  4553 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,09-01 20:55:21.145  4538  4553 D ContactDirectoryManager: Found com.google.contacts.gal.provider
09-01 20:55:21.145  4538  4553 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,09-01 20:55:21.169   872  1932 I ActivityManager: Start proc 4560:com.google.android.gm.exchange/u0a77 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,09-01 20:55:21.251  4560  4560 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,09-01 20:55:21.291   872   882 I ActivityManager: Start proc 4572:com.google.android.gm/u0a78 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,09-01 20:55:21.335   872  1932 I ActivityManager: Start proc 4584:com.google.process.gapps/u0a99 for content provider com.google.android.syncadapters.contacts/.GalProvider
,09-01 20:55:21.340   872  2827 I ActivityManager: Killing 4341:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-01 20:55:21.387   872  1557 I ActivityManager: Killing 4354:com.android.chrome/u0a40 (adj 15): empty #17
,09-01 20:55:21.403  4572  4572 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,09-01 20:55:21.466  4572  4599 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,09-01 20:55:21.495  4584  4584 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,09-01 20:55:21.537  4584  4584 I GoogleHttpClient: GMS http client unavailable, use old client
,09-01 20:55:21.548  4572  4572 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-01 20:55:21.577  4538  4553 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,09-01 20:55:21.600  4572  4598 I Gmail   : getAccountsCursor
,09-01 20:55:21.604  4538  4553 I ContactDirectoryManager: Discovered 0 contact directories in 616ms
,09-01 20:55:21.609  4572  4610 E Gmail   : Error finding the version of the Email provider.....
09-01 20:55:21.609  4572  4610 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
09-01 20:55:21.609  4572  4610 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
09-01 20:55:21.609  4572  4610 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
09-01 20:55:21.609  4572  4610 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
09-01 20:55:21.609  4572  4610 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-01 20:55:21.609  4572  4610 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 20:55:21.609  4572  4610 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
09-01 20:55:21.609  4572  4610 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-01 20:55:21.616  4572  4610 W EmailMigration: We do not support migrating this version of the Email provider.
,09-01 20:55:21.653  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:21.685  4572  4614 I Gmail   : getAccountsCursor
,09-01 20:55:21.694  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:21.726   872   882 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,09-01 20:55:21.738  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:21.764  4560  4560 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-01 20:55:21.793  4572  4617 I Gmail   : Observing account changes for notifications
,09-01 20:55:21.796  4560  4560 I Exchange: EasService.onCreate
,09-01 20:55:21.810  4560  4622 I Exchange: RestartPingTask
,09-01 20:55:21.848  4560  4560 I Exchange: RestartPingsTask did not start any pings.
,09-01 20:55:21.848  4560  4560 I Exchange: PSS stopIfIdle
09-01 20:55:21.848  4560  4560 I Exchange: PSS has no active accounts; stopping service.
09-01 20:55:21.849  4560  4560 I Exchange: onDestroy
,09-01 20:55:21.878  4572  4621 I Gmail   : notifyAccountChanged
,09-01 20:55:21.881  4572  4609 I Gmail   : getAccountsCursor
,09-01 20:55:21.886  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:21.897  4572  4621 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,09-01 20:55:21.906  4572  4621 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,09-01 20:55:21.921  4572  4621 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,09-01 20:55:21.922  4572  4621 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,09-01 20:55:22.058  4572  4614 I Gmail   : getAccountsCursor
,09-01 20:55:22.064  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:22.157  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 20:55:22.157  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 20:55:22.157  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 20:55:22.158  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 20:55:22.159  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:55:22.159  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-01 20:55:22.159  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 20:55:22.160  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74b562a removed from the list
09-01 20:55:22.160  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 20:55:22.161  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd0ac1b removed from the list
09-01 20:55:22.161  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:55:22.161  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:55:22.163  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:55:22.164  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 20:55:22.168  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:55:22.169  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:55:22.169  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:55:22.169  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd0ac1b not in the list
09-01 20:55:22.170  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 20:55:22.170  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:55:22.173  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 20:55:22.174  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:55:22.174  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:55:22.174  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd0ac1b not in the list
09-01 20:55:22.175  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:55:22.175  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 20:55:22.175  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:55:22.176  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74b562a not in the list
09-01 20:55:22.178  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 20:55:22.178  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec63164 added. We now have 3 listener(s)
,09-01 20:55:22.184  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 20:55:22.184  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 20:55:22.185  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 20:55:22.185  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 20:55:22.185  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c7afcd added. We now have 4 listener(s)
,09-01 20:55:22.186  3506  3553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 20:55:22.187  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 20:55:22.192  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 20:55:22.198  3506  3553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 20:55:22.198  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 20:55:22.198  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 20:55:22.198  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,09-01 20:55:22.198  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 20:55:22.198  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 20:55:22.198  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 20:55:22.198  3506  3553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 20:55:22.201  3506  3553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 20:55:22.201  3506  3553 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 20:55:22.202  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-01 20:55:22.203  3506  3553 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-01 20:55:22.203  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-01 20:55:22.205  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-01 20:55:22.205  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-01 20:55:22.205  3506  3553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-01 20:55:22.206  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 20:55:22.207  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-01 20:55:22.208  3506  3553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-01 20:55:22.208  3506  3553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-01 20:55:22.208  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-01 20:55:22.208  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-01 20:55:22.209  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 20:55:22.209  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 20:55:22.208  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:55:22.216  3506  3553 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-01 20:55:22.217  3506  4625 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 20:55:22.216  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 20:55:22.217  3506  3506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 20:55:22.217  3506  3506 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-01 20:55:22.221  3506  4625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-01 20:55:22.223  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 20:55:22.223  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 20:55:22.224  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 20:55:22.227  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-01 20:55:22.227  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 20:55:22.228  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-01 20:55:22.229  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-01 20:55:22.229  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-01 20:55:22.229  3506  3553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-01 20:55:22.230  3506  3553 D BluetoothAdapter: STATE_ON
,09-01 20:55:22.235  4268  4309 D BtGatt.GattService: registerClient() - UUID=2437e913-ccc6-4931-b2a6-ccc6464154f1
,09-01 20:55:22.236  4268  4285 D BtGatt.GattService: onClientRegistered() - UUID=2437e913-ccc6-4931-b2a6-ccc6464154f1, clientIf=5
09-01 20:55:22.237  3506  3516 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-01 20:55:22.240  4268  4287 D BtGatt.AdvertiseManager: message : 0
,09-01 20:55:22.245  4268  4287 D BtGatt.AdvertiseManager: starting multi advertising
,09-01 20:55:22.269  4268  4285 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-01 20:55:22.283  4268  4285 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-01 20:55:22.285  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-01 20:55:22.286  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 20:55:22.289  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 20:55:22.291  3506  3506 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-01 20:55:22.292  3506  3506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-01 20:55:22.292  3506  3506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-01 20:55:22.292  3506  3506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-01 20:55:22.293  3506  3506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-01 20:55:22.293  3506  3506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-01 20:55:22.295  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-01 20:55:22.301  3506  3506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-01 20:55:22.302  3506  3506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-01 20:55:22.803  3506  3506 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-01 20:55:22.804  3506  3506 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-01 20:55:22.804  3506  3506 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-01 20:55:25.296  3506  3553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 20:55:25.297  3506  3553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-01 20:55:25.297  3506  3553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 20:55:25.297  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-01 20:55:25.298  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-01 20:55:25.298  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-01 20:55:25.299  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-01 20:55:25.299  3506  3553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-01 20:55:25.299  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 20:55:25.300  3506  3506 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-01 20:55:25.300  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 20:55:25.300  3506  4625 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-01 20:55:25.300  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 20:55:25.300  3506  4625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-01 20:55:25.300  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 20:55:25.300  3506  4625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-01 20:55:25.301  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-01 20:55:25.304  3506  3553 D BluetoothAdapter: STATE_ON
09-01 20:55:25.305  3506  3553 D BluetoothLeScanner: could not find callback wrapper
09-01 20:55:25.305  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-01 20:55:25.306  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-01 20:55:25.309  4268  4287 D BtGatt.AdvertiseManager: message : 1
,09-01 20:55:25.311  4268  4287 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-01 20:55:25.319  4268  4285 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-01 20:55:25.319  4268  4285 D BtGatt.GattService: Client app is not null!
,09-01 20:55:25.321  4268  4279 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 20:55:25.322  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,09-01 20:55:25.322  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-01 20:55:25.323  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-01 20:55:25.323  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-01 20:55:25.323  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-01 20:55:25.326  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 20:55:25.326  3506  3553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-01 20:55:25.326  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 20:55:25.328  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-01 20:55:25.333  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:55:25.333  3506  3506 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-01 20:55:25.333  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 20:55:25.334  3506  3506 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-01 20:55:25.334  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
09-01 20:55:25.334  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 20:55:25.334  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec63164 removed from the list
09-01 20:55:25.335  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:55:25.335  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c7afcd removed from the list
,09-01 20:55:25.335  3506  3506 D AndroidRuntime: Shutting down VM
09-01 20:55:25.335  3506  3553 D io.jxcore.node.ConnectivityMonitor: stop
09-01 20:55:25.335  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
--------- beginning of crash
,09-01 20:55:25.337  3506  3506 E AndroidRuntime: FATAL EXCEPTION: main
09-01 20:55:25.337  3506  3506 E AndroidRuntime: Process: com.test.thalitest, PID: 3506
09-01 20:55:25.337  3506  3506 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-01 20:55:25.337  3506  3506 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
09-01 20:55:25.337  3506  3506 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper.onConnectionManagerStateChanged(ConnectionHelper.java:360)
09-01 20:55:25.337  3506  3506 E AndroidRuntime: 	at org.thaliproject.p2p.btconnectorlib.ConnectionManager$4.run(ConnectionManager.java:447)
09-01 20:55:25.337  3506  3506 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 20:55:25.337  3506  3506 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 20:55:25.337  3506  3506 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 20:55:25.337  3506  3506 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 20:55:25.337  3506  3506 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 20:55:25.337  3506  3506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 20:55:25.337  3506  3506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 20:55:25.337  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:55:25.337  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:55:25.339  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:55:25.340  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 20:55:25.340  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:55:25.340  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c7afcd not in the list
09-01 20:55:25.340  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:55:25.341  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:55:25.343  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 20:55:25.343  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 20:55:25.343  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 20:55:25.344  3506  3553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c7afcd not in the list
09-01 20:55:25.344  3506  3553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 20:55:25.344  3506  3553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 20:55:25.346  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 20:55:25.346  3506  3553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec63164 not in the list
09-01 20:55:25.346   872  1932 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
09-01 20:55:25.348  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 20:55:25.348  3506  3553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@99e22ce added. We now have 3 listener(s)
09-01 20:55:25.355  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 20:55:25.355  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 20:55:25.355  3506  3553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 20:55:25.356  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 20:55:25.356  3506  3553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43c5ef added. We now have 4 listener(s)
09-01 20:55:25.356  3506  3553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 20:55:25.357  3506  3553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 20:55:25.360   872  1932 I ActivityManager: Killing 3773:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,09-01 20:55:25.451  3506  3553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 20:55:25.451   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{e123da5 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{524e30f 3506 com.test.thalitest/10000/u0 remote:84b006e}: process crashing
,09-01 20:55:25.452   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{f2ab57a u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{524e30f 3506 com.test.thalitest/10000/u0 remote:84b006e}: process crashing
,09-01 20:55:25.455  3506  3506 I Process : Sending signal. PID: 3506 SIG: 9
,09-01 20:55:25.570   872  1373 I WindowState: WIN DEATH: Window{3b95c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-01 20:55:25.573   872  1557 D GraphicsStats: Buffer count: 2
,09-01 20:55:25.576   872  1308 D WifiService: Client connection lost with reason: 4
,09-01 20:55:25.601   872  1950 I ActivityManager: Process com.test.thalitest (pid 3506) has died
,09-01 20:55:25.650   872  1558 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3506 uid 10000
,09-01 20:55:25.653  1870  1870 I Keyboard.Facilitator: onFinishInput()
,09-01 20:55:25.858   872  1557 I ActivityManager: Killing 3048:com.google.android.keep/u0a79 (adj 15): empty #17
,09-01 20:55:26.609  4572  4604 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-01 20:55:26.831  4560  4620 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-01 20:55:27.851  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:27.866  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:27.870  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:27.926  1535  2376 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-01 20:55:27.926  1535  2376 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-01 20:55:27.926  1535  2376 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:27.927  1535  2376 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:27.972  4200  4200 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-01 20:55:27.972  4200  4200 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-01 20:55:27.973  4200  4200 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-01 20:55:29.580   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=441677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-01 20:55:38.234   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=450330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-01 20:55:41.098   872   884 I ActivityManager: Start proc 4631:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,09-01 20:55:41.172  4631  4631 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,09-01 20:55:41.367  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:41.369  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:41.456  1535  2091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-01 20:55:41.456  1535  2091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-01 20:55:41.456  1535  2091 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:41.456  1535  2091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:41.529  3286  4645 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-01 20:55:41.529  3286  4645 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at jdm.a(PG:82)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at jcs.o(PG:406)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at jcn.a(PG:1379)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at jcs.i(PG:143)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at blb.a(PG:3937)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at czp.a(PG:18188)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at czp.a(PG:9081)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at czq.run(PG:1686)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 20:55:41.529  3286  4645 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at jdj.a(PG:4091)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at jdj.a(PG:1125)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at jdm.a(PG:77)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	... 12 more
09-01 20:55:41.529  3286  4645 E HttpOperation: Caused by: faj: BadAuthentication
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at fal.a(PG:38)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	at jdj.a(PG:4089)
09-01 20:55:41.529  3286  4645 E HttpOperation: 	... 14 more
,09-01 20:55:41.608  1535  3750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-01 20:55:41.608  1535  3750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-01 20:55:41.608  1535  3750 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:41.608  1535  3750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:41.642  3286  4645 E HttpOperation: [getmobileexperiments] Unexpected exception
09-01 20:55:41.642  3286  4645 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at jdm.a(PG:82)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at jcs.o(PG:406)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at jcn.a(PG:1379)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at jcs.i(PG:143)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at hec.a(PG:42)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at hee.a(PG:102)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at czr.a(PG:65)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at kka.a(PG:108)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at czp.a(PG:19176)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at czp.a(PG:9081)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at czq.run(PG:1686)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 20:55:41.642  3286  4645 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at jdj.a(PG:4091)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at jdj.a(PG:1125)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at jdm.a(PG:77)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	... 15 more
09-01 20:55:41.642  3286  4645 E HttpOperation: Caused by: faj: BadAuthentication
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at fal.a(PG:38)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	at jdj.a(PG:4089)
09-01 20:55:41.642  3286  4645 E HttpOperation: 	... 17 more
,09-01 20:55:41.643  3286  4645 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-01 20:55:41.643  3286  4645 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at jdm.a(PG:82)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at jcs.o(PG:406)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at jcn.a(PG:1379)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at jcs.i(PG:143)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at hec.a(PG:42)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at hee.a(PG:102)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at czr.a(PG:65)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at kka.a(PG:108)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at czp.a(PG:19176)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at czp.a(PG:9081)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at czq.run(PG:1686)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at jdj.a(PG:4091)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at jdj.a(PG:1125)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at jdm.a(PG:77)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	... 15 more
09-01 20:55:41.643  3286  4645 E ExperimentLoader: Caused by: faj: BadAuthentication
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at fal.a(PG:38)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	at jdj.a(PG:4089)
09-01 20:55:41.643  3286  4645 E ExperimentLoader: 	... 17 more
,09-01 20:55:41.659  4631  4649 V KeepSync: Connecting to GoogleApiClient
,09-01 20:55:41.660   872  1557 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-01 20:55:41.752  1535  2091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-01 20:55:41.752  1535  2091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-01 20:55:41.752  1535  2091 I GLSUser : [GLSUser] Extracting token using key: Auth,
09-01 20:55:41.752  1535  2091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:41.782  1753  4655 V BaseAuthAsyncOperation: access token request failed
,09-01 20:55:41.784  4631  4649 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-01 20:55:41.844   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 451011, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-01 20:55:41.929  1535  2091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-01 20:55:41.930  1535  2091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-01 20:55:41.930  1535  2091 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:41.930  1535  2091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:41.941  4383  4656 I BooksSync: Starting books sync for 61035162, extras: ade
,09-01 20:55:41.962  4631  4649 E KeepSync: IOException
09-01 20:55:41.962  4631  4649 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-01 20:55:41.962  4631  4649 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-01 20:55:41.962  4631  4649 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-01 20:55:41.962  4631  4649 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-01 20:55:41.962  4631  4649 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-01 20:55:41.962  4631  4649 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-01 20:55:41.962  4631  4649 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-01 20:55:41.962  4631  4649 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-01 20:55:41.962  4631  4649 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-01 20:55:41.962  4631  4649 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-01 20:55:41.962  4631  4649 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-01 20:55:41.962  4631  4649 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-01 20:55:41.962  4631  4649 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-01 20:55:41.962  4631  4649 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-01 20:55:41.962  4631  4649 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-01 20:55:41.962  4631  4649 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-01 20:55:41.962  4631  4649 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-01 20:55:41.962  4631  4649 E KeepSync: 	... 10 more
,09-01 20:55:41.965  4631  4649 W KeepSync: Sync result 2
,09-01 20:55:41.970  4383  4658 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-01 20:55:41.990   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 450757, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-01 20:55:42.040  1535  3750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-01 20:55:42.040  1535  3750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-01 20:55:42.041  1535  3750 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:42.041  1535  3750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:42.131  1535  2091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-01 20:55:42.131  1535  2091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-01 20:55:42.131  1535  2091 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 20:55:42.131  1535  2091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:42.151  4383  4658 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-01 20:55:42.151  4383  4656 E BooksSync: Soft error
09-01 20:55:42.151  4383  4656 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-01 20:55:42.151  4383  4656 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-01 20:55:42.151  4383  4656 E BooksSync: Sync error
09-01 20:55:42.151  4383  4656 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-01 20:55:42.151  4383  4656 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-01 20:55:42.151  4383  4656 I BooksSync: Finished books sync
,09-01 20:55:42.170   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 451258, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-01 20:55:42.335   872  1951 I ActivityManager: Killing 4450:com.google.android.configupdater/u0a42 (adj 15): empty #17
,09-01 20:55:46.230  4631  4638 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@969495b)
,09-01 20:55:48.218  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:48.232  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:48.237  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:55:48.291  1535  2822 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-01 20:55:48.292  1535  2822 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-01 20:55:48.292  1535  2822 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:55:48.292  1535  2822 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:55:48.348  4200  4200 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-01 20:55:48.350  4200  4200 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-01 20:55:48.352  4200  4200 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-01 20:55:57.874   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=469970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-01 20:56:08.583  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:56:08.584  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:56:08.634  3572  4661 V GoogleAuthProtoRequest: [284] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 20:56:08.695  1535  1549 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
09-01 20:56:08.695  1535  1549 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-01 20:56:08.695  1535  1549 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:56:08.695  1535  1549 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:56:08.741  3572  4661 W ExperimentUpdateService: [284] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-01 20:56:08.742  3572  4661 W ExperimentUpdateService: [284] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-01 20:56:08.742  3572  4661 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-01 20:56:08.742  3572  4661 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-01 20:56:08.742  3572  4661 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-01 20:56:08.742  3572  4661 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-01 20:56:08.742  3572  4661 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-01 20:56:08.742  3572  4661 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-01 20:56:08.742  3572  4661 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-01 20:56:08.742  3572  4661 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-01 20:56:08.742  3572  4661 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-01 20:56:08.742  3572  4661 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-01 20:56:08.891  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:56:08.922  1535  1550 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-01 20:56:08.922  1535  1550 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-01 20:56:08.922  1535  1550 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:56:08.922  1535  1550 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:56:08.953  4200  4200 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-01 20:56:08.953  4200  4200 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-01 20:56:08.953  4200  4200 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-01 20:56:11.474   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=483571, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-01 20:56:25.696  1870  1981 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-01 20:56:25.696  1870  1981 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-01 20:56:25.726  1535  1535 I ConfigService: onCreate
,09-01 20:56:29.126  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:56:29.132  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:56:29.136  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:56:29.173  1535  2828 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-01 20:56:29.173  1535  2828 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-01 20:56:29.174  1535  2828 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 20:56:29.174  1535  2828 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:56:29.197  4200  4200 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-01 20:56:29.197  4200  4200 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-01 20:56:29.197  4200  4200 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-01 20:56:30.797  1535  1535 I ConfigService: onDestroy
,09-01 20:56:31.100   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=503197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-01 20:56:43.405  4383  4665 I BooksSync: Starting books sync for 61035162, extras: ade
,09-01 20:56:43.424  4383  4666 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-01 20:56:43.447  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:56:43.449  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:56:43.473  1535  1550 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-01 20:56:43.473  1535  1550 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-01 20:56:43.473  1535  1550 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:56:43.473  1535  1550 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:56:43.513  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-01 20:56:43.515  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:56:43.546  1535  2091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-01 20:56:43.546  1535  2091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-01 20:56:43.547  1535  2091 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:56:43.547  1535  2091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:56:43.562  4383  4666 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-01 20:56:43.563  4383  4665 E BooksSync: Soft error
09-01 20:56:43.563  4383  4665 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-01 20:56:43.563  4383  4665 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-01 20:56:43.563  4383  4665 E BooksSync: Sync error
09-01 20:56:43.563  4383  4665 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-01 20:56:43.563  4383  4665 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-01 20:56:43.563  4383  4665 I BooksSync: Finished books sync
,09-01 20:56:43.574   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 515431, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-01 20:56:49.395  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:56:49.404  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:56:49.408  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:56:49.453  1535  3750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-01 20:56:49.454  1535  3750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-01 20:56:49.454  1535  3750 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:56:49.454  1535  3750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:56:49.494  4200  4200 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-01 20:56:49.495  4200  4200 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-01 20:56:49.495  4200  4200 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-01 20:57:13.969  4631  4669 V KeepSync: Connecting to GoogleApiClient
09-01 20:57:13.970   872  1557 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-01 20:57:13.983  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:57:14.019  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:57:14.086  1535  2828 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-01 20:57:14.086  1535  2828 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-01 20:57:14.086  1535  2828 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:57:14.086  1535  2828 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:57:14.108  1535  2822 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-01 20:57:14.108  1535  2822 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-01 20:57:14.108  1535  2822 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:57:14.108  1535  2822 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:57:14.118  3286  4671 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-01 20:57:14.118  3286  4671 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at jdm.a(PG:82)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at jcs.o(PG:406)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at jcn.a(PG:1379)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at jcs.i(PG:143)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at blb.a(PG:3937)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at czp.a(PG:18188)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at czp.a(PG:9081)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at czq.run(PG:1686)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 20:57:14.118  3286  4671 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at jdj.a(PG:4091)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at jdj.a(PG:1125)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at jdm.a(PG:77)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	... 12 more
09-01 20:57:14.118  3286  4671 E HttpOperation: Caused by: faj: BadAuthentication
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at fal.a(PG:38)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	at jdj.a(PG:4089)
09-01 20:57:14.118  3286  4671 E HttpOperation: 	... 14 more
,09-01 20:57:14.140  1753  4672 V BaseAuthAsyncOperation: access token request failed
,09-01 20:57:14.144  4631  4669 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-01 20:57:14.198  1535  1550 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-01 20:57:14.198  1535  1550 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-01 20:57:14.198  1535  1550 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:57:14.198  1535  1550 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:57:14.240  3286  4671 E HttpOperation: [getmobileexperiments] Unexpected exception
09-01 20:57:14.240  3286  4671 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at jdm.a(PG:82)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at jcs.o(PG:406)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at jcn.a(PG:1379)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at jcs.i(PG:143)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at hec.a(PG:42)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at hee.a(PG:102)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at czr.a(PG:65)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at kka.a(PG:108)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at czp.a(PG:19176)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at czp.a(PG:9081)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at czq.run(PG:1686)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 20:57:14.240  3286  4671 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at jdj.a(PG:4091)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at jdj.a(PG:1125)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at jdm.a(PG:77)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	... 15 more
09-01 20:57:14.240  3286  4671 E HttpOperation: Caused by: faj: BadAuthentication
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at fal.a(PG:38)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	at jdj.a(PG:4089)
09-01 20:57:14.240  3286  4671 E HttpOperation: 	... 17 more
,09-01 20:57:14.240  3286  4671 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-01 20:57:14.240  3286  4671 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at jdm.a(PG:82)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at jcs.o(PG:406)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at jcn.a(PG:1379)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at jcs.i(PG:143)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at hec.a(PG:42)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at hee.a(PG:102)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at czr.a(PG:65)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at kka.a(PG:108)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at czp.a(PG:19176)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at czp.a(PG:9081)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at czq.run(PG:1686)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at jdj.a(PG:4091)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at jdj.a(PG:1125)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at jdm.a(PG:77)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	... 15 more
09-01 20:57:14.240  3286  4671 E ExperimentLoader: Caused by: faj: BadAuthentication
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at fal.a(PG:38)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	at jdj.a(PG:4089)
09-01 20:57:14.240  3286  4671 E ExperimentLoader: 	... 17 more
,09-01 20:57:14.305  1535  2822 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-01 20:57:14.306  1535  2822 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-01 20:57:14.306  1535  2822 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 20:57:14.306  1535  2822 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:57:14.321  4631  4669 E KeepSync: IOException
09-01 20:57:14.321  4631  4669 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-01 20:57:14.321  4631  4669 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-01 20:57:14.321  4631  4669 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-01 20:57:14.321  4631  4669 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-01 20:57:14.321  4631  4669 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-01 20:57:14.321  4631  4669 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-01 20:57:14.321  4631  4669 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-01 20:57:14.321  4631  4669 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-01 20:57:14.321  4631  4669 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-01 20:57:14.321  4631  4669 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-01 20:57:14.321  4631  4669 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-01 20:57:14.321  4631  4669 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-01 20:57:14.321  4631  4669 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-01 20:57:14.321  4631  4669 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-01 20:57:14.321  4631  4669 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-01 20:57:14.321  4631  4669 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-01 20:57:14.321  4631  4669 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-01 20:57:14.321  4631  4669 E KeepSync: 	... 10 more
09-01 20:57:14.321  4631  4669 W KeepSync: Sync result 2
,09-01 20:57:14.328   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 516507, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-01 20:57:14.450   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 517207, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-01 20:58:08.756  1535  2196 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-01 20:58:08.948  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:58:08.951  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:58:08.961  3572  4675 V GoogleAuthProtoRequest: [285] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 20:58:08.980  1535  1550 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-01 20:58:08.980  1535  1550 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-01 20:58:08.980  1535  1550 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 20:58:08.980  1535  1550 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:58:08.996  3572  4675 W ExperimentUpdateService: [285] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-01 20:58:08.996  3572  4675 W ExperimentUpdateService: [285] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-01 20:58:08.996  3572  4675 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-01 20:58:08.996  3572  4675 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-01 20:58:08.996  3572  4675 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97),
09-01 20:58:08.996  3572  4675 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-01 20:58:08.996  3572  4675 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-01 20:58:08.996  3572  4675 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-01 20:58:08.996  3572  4675 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-01 20:58:08.996  3572  4675 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-01 20:58:08.996  3572  4675 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-01 20:58:08.996  3572  4675 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-01 20:58:24.755   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=616852, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-01 20:58:44.382   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=636478, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-01 20:59:15.076   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=667172, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-01 20:59:34.675   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=686772, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-01 20:59:50.563  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:59:50.575  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:59:50.577  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 20:59:50.626  1535  2376 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-01 20:59:50.627  1535  2376 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-01 20:59:50.627  1535  2376 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 20:59:50.627  1535  2376 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 20:59:50.667  1535  2376 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-01 20:59:50.667  1535  2376 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-01 20:59:50.667  1535  2376 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-01 20:59:50.667  1535  2376 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-01 20:59:50.667  1535  2376 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-01 20:59:50.667  1535  2376 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-01 20:59:50.667  1535  2376 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-01 20:59:50.675  4200  4233 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-01 20:59:50.675  4200  4233 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-01 20:59:50.675  4200  4233 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-01 20:59:50.675  4200  4233 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-01 20:59:50.675  4200  4233 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-01 20:59:50.675  4200  4233 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-01 20:59:50.675  4200  4233 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-01 20:59:55.740   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=707837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-01 21:00:10.729   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=722825, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-01 21:00:18.154   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=730251, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-01 21:00:37.772   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=749868, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-01 21:01:06.623   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=778720, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-01 21:01:26.250   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=798346, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-01 21:02:09.187  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 21:02:09.189  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 21:02:09.201  3572  4694 V GoogleAuthProtoRequest: [286] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 21:02:09.244  1535  3750 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
09-01 21:02:09.245  1535  3750 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-01 21:02:09.245  1535  3750 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 21:02:09.245  1535  3750 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 21:02:09.263  3572  4694 W ExperimentUpdateService: [286] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-01 21:02:09.263  3572  4694 W ExperimentUpdateService: [286] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
,09-01 21:02:09.263  3572  4694 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-01 21:02:09.263  3572  4694 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-01 21:02:09.263  3572  4694 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-01 21:02:09.263  3572  4694 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-01 21:02:09.263  3572  4694 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-01 21:02:09.263  3572  4694 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-01 21:02:09.263  3572  4694 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-01 21:02:09.263  3572  4694 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-01 21:02:09.263  3572  4694 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-01 21:02:09.263  3572  4694 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-01 21:03:56.370   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=948467, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-01 21:04:18.836   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=970932, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-01 21:04:56.116   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1008212, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-01 21:05:18.569   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1030665, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-01 21:08:00.201  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 21:08:00.216  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 21:08:00.219  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 21:08:00.255  1535  1550 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,09-01 21:08:00.255  1535  1550 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud.
,09-01 21:08:00.255  1535  1550 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 21:08:00.256  1535  1550 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 21:08:00.275  1753  4711 E Ads     : [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ae: BadAuthentication
,09-01 21:08:26.392   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,09-01 21:10:09.452  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 21:10:09.455  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 21:10:09.464  3572  4718 V GoogleAuthProtoRequest: [287] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 21:10:09.488  1535  2376 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-01 21:10:09.488  1535  2376 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-01 21:10:09.488  1535  2376 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 21:10:09.488  1535  2376 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 21:10:09.503  3572  4718 W ExperimentUpdateService: [287] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
09-01 21:10:09.504  3572  4718 W ExperimentUpdateService: [287] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-01 21:10:09.504  3572  4718 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-01 21:10:09.504  3572  4718 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-01 21:10:09.504  3572  4718 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-01 21:10:09.504  3572  4718 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-01 21:10:09.504  3572  4718 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-01 21:10:09.504  3572  4718 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-01 21:10:09.504  3572  4718 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-01 21:10:09.504  3572  4718 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-01 21:10:09.504  3572  4718 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-01 21:10:09.504  3572  4718 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-01 21:10:14.300   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1326397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-01 21:10:27.849   872  4324 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1339945, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),09-01 21:17:10.759  4737  4737 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-01 21:17:10.764  4737  4737 D AndroidRuntime: CheckJNI is OFF
09-01 21:17:10.799  4737  4737 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-01 21:17:10.840  4737  4737 I Radio-JNI: register_android_hardware_Radio DONE
09-01 21:17:10.861  4737  4737 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-01 21:17:10.872   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-01 21:17:11.016   872   895 W PackageSettings: Skipping PackageSetting{ede18aa com.example.hello/10273} due to missing metadata
09-01 21:17:11.061   872   895 I art     : Starting a blocking GC Explicit
09-01 21:17:11.117   872   895 I art     : Explicit concurrent mark sweep GC freed 17578(1217KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 745us total 55.894ms
09-01 21:17:11.149   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-01 21:17:11.154  4737  4737 I art     : System.exit called, status: 0
09-01 21:17:11.154  4737  4737 I AndroidRuntime: VM exiting with result code 0.
09-01 21:17:11.211   872   895 I ActivityManager: Start proc 4750:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-01 21:17:11.212   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-01 21:17:11.236  4268  4268 D BluetoothMapAppObserver: onReceive
09-01 21:17:11.236  4268  4268 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-01 21:17:11.240  2134  2275 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-01 21:17:11.260  3346  3346 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-01 21:17:11.264   872  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-01 21:17:11.275  1870  1870 I Keyboard.Facilitator: resetDictionaries() : en_US
09-01 21:17:11.295  1924  1924 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-01 21:17:11.301   872  1305 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
09-01 21:17:11.313  4538  4553 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-01 21:17:11.314   872  1557 I ActivityManager: Start proc 4768:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-01 21:17:11.314  4538  4553 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-01 21:17:11.314  4538  4553 E AndroidRuntime: Process: android.process.acore, PID: 4538
09-01 21:17:11.314  4538  4553 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 21:17:11.314  4538  4553 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-01 21:17:11.314  4538  4553 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-01 21:17:11.314  4538  4553 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-01 21:17:11.314  4538  4553 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-01 21:17:11.314  4538  4553 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-01 21:17:11.314  4538  4553 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-01 21:17:11.314  4538  4553 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
09-01 21:17:11.314  4538  4553 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-01 21:17:11.314  4538  4553 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-01 21:17:11.314  4538  4553 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-01 21:17:11.314  4538  4553 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 21:17:11.314  4538  4553 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 21:17:11.314  4538  4553 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 21:17:11.319  1870  4765 I Keyboard.Facilitator.DecoderInitializer: run()
09-01 21:17:11.321  1870  4765 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
09-01 21:17:11.321  1870  4765 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
09-01 21:17:11.321  1870  4765 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
09-01 21:17:11.321  1870  4765 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
09-01 21:17:11.321  1870  4765 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
09-01 21:17:11.321  1870  4765 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
09-01 21:17:11.340  1870  4765 I Decoder : createOrResetDecoder
09-01 21:17:11.343  4538  4766 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-01 21:17:11.350   872  4780 E DropBoxManagerService: Can't write: system_app_crash
09-01 21:17:11.350   872  4780 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-01 21:17:11.350   872  4780 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 21:17:11.350   872  4780 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 21:17:11.350   872  4780 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 21:17:11.350   872  4780 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 21:17:11.350   872  4780 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 21:17:11.350   872  4780 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 21:17:11.350   872  4780 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 21:17:11.350   872  4780 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 21:17:11.350   872  4780 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 21:17:11.350   872  4780 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 21:17:11.350   872  4780 E DropBoxManagerService: 	... 5 more
09-01 21:17:11.369   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-01 21:17:11.378  1535  1535 I ConfigService: onCreate
09-01 21:17:11.384  4538  4766 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
09-01 21:17:11.385  4538  4766 I Process : Sending signal. PID: 4538 SIG: 9
09-01 21:17:11.371  4538  4553 I Process : Sending signal. PID: 4538 SIG: 9
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-01 21:17:11.394  1535  4781 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-01 21:17:11.394  1535  4781 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-01 21:17:11.395  1535  4781 W SQLiteOpenHelper: Opened config.db in read-only mode
09-01 21:17:11.399  1939  2025 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-01 21:17:11.400   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-01 21:17:11.401   872   884 E PackageManager: Failed to write settings, restoring backup
09-01 21:17:11.401   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-01 21:17:11.401   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-01 21:17:11.401   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-01 21:17:11.401   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-01 21:17:11.401   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-01 21:17:11.401   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 21:17:11.401   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-01 21:17:11.401   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 21:17:11.404   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-01 21:17:11.404   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-01 21:17:11.404   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 21:17:11.404   872   885 E DropBoxManagerService: 	... 13 more
09-01 21:17:11.414  4768  4768 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-01 21:17:11.415   872  1967 I ActivityManager: Start proc 4782:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-01 21:17:11.415  1939  2025 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-01 21:17:11.415  1939  2025 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1939
09-01 21:17:11.415  1939  2025 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 21:17:11.415  1939  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-01 21:17:11.415  1939  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-01 21:17:11.415  1939  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-01 21:17:11.415  1939  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-01 21:17:11.415  1939  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-01 21:17:11.415  1939  2025 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-01 21:17:11.415  1939  2025 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-01 21:17:11.415  1939  2025 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 21:17:11.415  1939  2025 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 21:17:11.415  1939  2025 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 21:17:11.415  1939  2025 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 21:17:11.417   872  1950 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-01 21:17:11.418   872  4789 E DropBoxManagerService: Can't write: system_app_crash
09-01 21:17:11.418   872  4789 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-01 21:17:11.418   872  4789 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 21:17:11.418   872  4789 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 21:17:11.418   872  4789 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 21:17:11.418   872  4789 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 21:17:11.418   872  4789 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 21:17:11.418   872  4789 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 21:17:11.418   872  4789 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 21:17:11.418   872  4789 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 21:17:11.418   872  4789 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 21:17:11.418   872  4789 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 21:17:11.418   872  4789 E DropBoxManagerService: 	... 5 more
09-01 21:17:11.421  1939  2025 I Process : Sending signal. PID: 1939 SIG: 9
09-01 21:17:11.446  1870  4765 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-01 21:17:11.469  1535  1535 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-01 21:17:11.470   279   279 E lowmemorykiller: Error writing /proc/4538/oom_score_adj; errno=22
09-01 21:17:11.471   279   279 E lowmemorykiller: Error writing /proc/4538/oom_score_adj; errno=22
09-01 21:17:11.471  1535  1535 D AndroidRuntime: Shutting down VM
09-01 21:17:11.472  1535  1535 E AndroidRuntime: FATAL EXCEPTION: main
09-01 21:17:11.472  1535  1535 E AndroidRuntime: Process: com.google.process.gapps, PID: 1535
09-01 21:17:11.472  1535  1535 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-01 21:17:11.472  1535  1535 E AndroidRuntime: 	... 8 more
09-01 21:17:11.475  1535  1535 I Process : Sending signal. PID: 1535 SIG: 9
09-01 21:17:11.477   872   885 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2600)
09-01 21:17:11.479   872   885 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.app.receiver.SystemBroadcastReceiver}
09-01 21:17:11.479   872   885 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-01 21:17:11.479   872   885 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-01 21:17:11.479   872   885 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-01 21:17:11.479   872   885 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-01 21:17:11.479   872   885 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-01 21:17:11.479   872   885 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-01 21:17:11.479   872   885 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
09-01 21:17:11.479   872   885 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 21:17:11.479   872   885 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
09-01 21:17:11.479   872   885 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 21:17:11.479   872   885 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-01 21:17:11.483   872  4799 E DropBoxManagerService: Can't write: system_app_crash
09-01 21:17:11.483   872  4799 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-01 21:17:11.483   872  4799 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 21:17:11.483   872  4799 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 21:17:11.483   872  4799 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 21:17:11.483   872  4799 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 21:17:11.483   872  4799 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 21:17:11.483   872  4799 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 21:17:11.483   872  4799 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 21:17:11.483   872  4799 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 21:17:11.483   872  4799 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 21:17:11.483   872  4799 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 21:17:11.483   872  4799 E DropBoxManagerService: 	... 5 more
09-01 21:17:11.499  1870  4765 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-01 21:17:11.501  1870  4765 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-01 21:17:11.502  1870  4765 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-01 21:17:11.503  1870  4765 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-01 21:17:11.503  1870  4765 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-01 21:17:11.505  1870  4765 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-01 21:17:11.505  1870  4765 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-01 21:17:11.506  1870  4765 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-01 21:17:11.506  1870  4765 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-01 21:17:11.506  1870  4765 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-01 21:17:11.506  1870  4765 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-01 21:17:11.507  1870  4765 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-01 21:17:11.507  1870  4765 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-01 21:17:11.554   872   883 D GraphicsStats: Buffer count: 1
09-01 21:17:11.554   872  1967 I WindowState: WIN DEATH: Window{6752b2b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-01 21:17:11.557   872  1308 D WifiService: Client connection lost with reason: 4
09-01 21:17:11.568   872   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
09-01 21:17:11.568   872   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
09-01 21:17:11.569   872   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
09-01 21:17:11.586   872   885 I ActivityManager: Start proc 4803:com.google.process.gapps/u0a11 for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver
09-01 21:17:11.591   872  1943 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1939) has died
09-01 21:17:11.591   872  1943 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 30977ms
09-01 21:17:11.592   872  1943 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-01 21:17:11.596   872   882 W ActivityManager: Spurious death for ProcessRecord{63453c 4803:com.google.process.gapps/u0a11}, curProc for 1535: null
09-01 21:17:11.596   872  1932 I ActivityManager: Process android.process.acore (pid 4538) has died
09-01 21:17:11.597   872  1932 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30971ms
09-01 21:17:11.608   872   885 I ActivityManager: Start proc 4815:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-01 21:17:11.621  1753  1753 W RocketImpressions: ClearcutLogger connection suspended: 1
09-01 21:17:11.631  4803  4803 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
09-01 21:17:11.653   872  1932 I ActivityManager: Killing 4476:com.google.android.partnersetup/u0a16 (adj 15): empty #17

```
