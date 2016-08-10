#### Test 79751015c075caf_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main,
08-10 14:14:27.273  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 14:14:27.286  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 14:14:27.290  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 14:14:27.341  1511  2687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-10 14:14:27.341  1511  2687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 14:14:27.341  1511  2687 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:14:27.342  1511  2687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 14:14:27.373  1511  2687 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 14:14:27.373  1511  2687 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 14:14:27.373  1511  2687 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 14:14:27.373  1511  2687 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 14:14:27.373  1511  2687 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 14:14:27.373  1511  2687 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 14:14:27.373  1511  2687 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
08-10 14:14:27.383  2588  2621 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 14:14:27.383  2588  2621 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 14:14:27.383  2588  2621 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 14:14:27.383  2588  2621 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 14:14:27.383  2588  2621 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 14:14:27.383  2588  2621 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 14:14:27.383  2588  2621 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
08-10 14:14:27.923  3335  3335 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 14:14:27.927  3335  3335 D AndroidRuntime: CheckJNI is OFF
08-10 14:14:27.962  3335  3335 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 14:14:28.005  3335  3335 I Radio-JNI: register_android_hardware_Radio DONE
08-10 14:14:28.024  3335  3335 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 14:14:28.030   875  2827 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 14:14:28.089   875  2827 I ActivityManager: Start proc 3345:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-10 14:14:28.099  3335  3335 D AndroidRuntime: Shutting down VM
08-10 14:14:28.225  3345  3345 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-10 14:14:28.262  3345  3345 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-10 14:14:28.347  3345  3345 I LibraryLoader: Time to load native libraries: 78 ms (timestamps 2071-2149)
08-10 14:14:28.348  3345  3345 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 14:14:28.378  3345  3345 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {717a24c}
,08-10 14:14:28.379  3345  3345 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 14:14:28.379  3345  3345 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 14:14:28.388  3345  3345 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-10 14:14:28.390  3345  3345 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-10 14:14:28.475  3345  3360 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,08-10 14:14:28.486  3345  3345 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-10 14:14:28.496  3345  3345 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-10 14:14:28.496  3345  3345 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 14:14:28.496  3345  3345 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 14:14:28.496  3345  3345 I Adreno  : Build Date                       : 10/20/15
08-10 14:14:28.496  3345  3345 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 14:14:28.496  3345  3345 I Adreno  : Local Branch                     : M14
08-10 14:14:28.496  3345  3345 I Adreno  : Remote Branch                    : 
08-10 14:14:28.496  3345  3345 I Adreno  : Remote Branch                    : 
08-10 14:14:28.496  3345  3345 I Adreno  : Reconstruct Branch               : 
,08-10 14:14:28.584   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e4b3a21:true
,08-10 14:14:28.637  3345  3345 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-10 14:14:28.652  3345  3345 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-10 14:14:28.657   875   888 W ActivityManager: Activity pause timeout for ActivityRecord{78e4322 u0 com.test.thalitest/.MainActivity t8}
,08-10 14:14:28.780  3345  3382 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-10 14:14:28.816  3345  3369 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-10 14:14:28.872  3345  3382 I OpenGLRenderer: Initialized EGL, version 1.4
,08-10 14:14:28.988   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +832ms (total +924ms)
,08-10 14:14:28.997  1663  1663 I Keyboard.Facilitator: onFinishInput()
,08-10 14:14:29.075  3345  3345 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3345
,08-10 14:14:29.232  3345  3345 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 14:14:29.433  3345  3385 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1697117904
,08-10 14:14:29.443  3345  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 14:14:29.443  3345  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 14:14:29.443  3345  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 14:14:29.443  3345  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 14:14:29.443  3345  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-10 14:14:29.443  3345  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edf6d3 added. We now have 1 listener(s)
,08-10 14:14:29.449  3345  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-10 14:14:29.449  3345  3385 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 14:14:29.451  3345  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
,08-10 14:14:29.451  3345  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
,08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-10 14:14:29.457  3345  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48d9f0e added. We now have 1 listener(s)
08-10 14:14:29.458  3345  3385 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 14:14:29.465   875  1317 D WifiService: New client listening to asynchronous messages
,08-10 14:14:29.468  3345  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 14:14:29.469  3345  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-10 14:14:29.470  3345  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-10 14:14:29.470  3345  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-10 14:14:29.472  3345  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-10 14:14:29.478  3345  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 14:14:29.479  3345  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-10 14:14:29.482  3345  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 14:14:29.482  3345  3385 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 14:14:29.482  3345  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:29.482  3345  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:14:29.482  3345  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:14:29.482  3345  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:14:29.482  3345  3385 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:29.482  3345  3385 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:29.482  3345  3385 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 14:14:29.482  3345  3385 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 14:14:29.482  3345  3385 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 14:14:29.484  3345  3385 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 14:14:29.484  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:14:29.515  3345  3345 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 14:14:30.081  3345  3354 I art     : Background sticky concurrent mark sweep GC freed 75644(7MB) AllocSpace objects, 17(1584KB) LOS objects, 27% free, 23MB/32MB, paused 3.098ms total 209.097ms
,08-10 14:14:30.950  3345  3392 W jxcore-log: Initializing JXcore engine
,08-10 14:14:30.951  3345  3392 W jxcore-log: JXcore engine is ready
,08-10 14:14:30.986  3392  3392 W Thread-286: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-10 14:14:30.986  3392  3392 W Thread-286: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10621]" dev="sockfs" ino=10621 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-10 14:14:30.986  3392  3392 W Thread-286: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-10 14:14:30.986  3392  3392 W Thread-286: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24668]" dev="sockfs" ino=24668 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-10 14:14:30.998  3345  3392 W jxcore-log: Starting JXcore engine
,08-10 14:14:31.076  3345  3392 W jxcore-log: Platform android
08-10 14:14:31.076  3345  3392 W jxcore-log: 
,08-10 14:14:31.077  3345  3392 W jxcore-log: Process ARCH arm
08-10 14:14:31.077  3345  3392 W jxcore-log: 
,08-10 14:14:31.293  3345  3392 I jxcore-log: JXcore Cordova bridge is ready!
08-10 14:14:31.293  3345  3392 I jxcore-log: 
,08-10 14:14:31.293  3345  3392 W jxcore-log: JXcore engine is started
,08-10 14:14:31.302  3345  3385 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-10 14:14:31.308  3345  3345 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 14:14:46.476  3345  3392 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 14:14:46.476  3345  3392 I jxcore-log: 
,08-10 14:14:46.478  3345  3392 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 14:14:46.478  3345  3392 I jxcore-log: 
,08-10 14:14:46.479  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:46.479  3345  3392 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 14:14:46.479  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:46.479  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:14:46.479  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:14:46.479  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:14:46.479  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:46.479  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:46.479  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 14:14:46.480  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:46.480  3345  3392 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:14:46.482  3345  3392 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 14:14:46.482  3345  3392 I jxcore-log: 
,08-10 14:14:46.484  3345  3392 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 14:14:46.484  3345  3392 I jxcore-log: 
,08-10 14:14:46.814  3345  3392 D ExecuteNativeTests: Running unit tests
,08-10 14:14:46.873  3345  3392 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 14:14:46.873  3345  3392 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd added. We now have 2 listener(s)
08-10 14:14:46.874  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 14:14:46.874  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 14:14:46.874  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 14:14:46.874  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 14:14:46.874  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 added. We now have 2 listener(s)
,08-10 14:14:46.874  3345  3392 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 14:14:46.875  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 14:14:46.876  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 14:14:46.877  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 14:14:46.877  3345  3392 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 14:14:46.877  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:46.877  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:14:46.877  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:14:46.877  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:14:46.877  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:46.877  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:46.877  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:14:46.877  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-10 14:14:46.877  3345  3392 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 14:14:46.877  3345  3392 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 14:14:46.879  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 14:14:46.879  3345  3392 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 14:14:46.879  3345  3392 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 14:14:46.881  3345  3392 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-10 14:14:46.881  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:14:46.882  3345  3392 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 14:14:46.882  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 14:14:46.882  3345  3392 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 14:14:46.882  3345  3392 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 14:14:46.882  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 14:14:46.883  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.883  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.883  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.883  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 14:14:46.883  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 14:14:46.883  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-10 14:14:46.883  3345  3392 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd removed from the list
08-10 14:14:46.883  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.883  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 removed from the list
,08-10 14:14:46.883  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.884  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.884  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.884  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.885  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.885  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.885  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 14:14:46.885  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.886  3345  3392 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-10 14:14:46.887  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.887  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.887  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.887  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 14:14:46.887  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.887  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.887  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.887  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.887  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.887  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 14:14:46.887  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.887  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.887  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.887  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.888  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.888  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.888  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.888  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
,08-10 14:14:46.892  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 14:14:46.892  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 14:14:46.892  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 14:14:46.892  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 14:14:46.892  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 14:14:46.892  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 14:14:46.892  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 14:14:46.892  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 14:14:46.892  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710],
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-10 14:14:46.893  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 14:14:46.894  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 14:14:46.894  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 14:14:46.894  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 14:14:46.894  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 14:14:46.894  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.894  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.895  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.895  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.895  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-10 14:14:46.895  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.895  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.895  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.895  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.895  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-10 14:14:46.895  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.895  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.895  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.895  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.895  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 14:14:46.895  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.896  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.896  3345  3392 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 14:14:46.897  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 14:14:46.898  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 14:14:46.898  3345  3392 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 14:14:46.898  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:46.898  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:14:46.898  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:14:46.898  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:14:46.898  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:46.898  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:46.898  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
08-10 14:14:46.898  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:46.898  3345  3392 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:14:46.898  3345  3392 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 14:14:46.899  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:14:46.899  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 14:14:46.899  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 14:14:46.899  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 14:14:46.899  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 14:14:46.899  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-10 14:14:46.902  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-10 14:14:46.902  3345  3392 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-10 14:14:46.902  3345  3345 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-10 14:14:46.903  3345  3392 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 14:14:46.903  3345  3392 I io.jxcore.node.ConnectionHelper: start: OK,
08-10 14:14:46.903  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:46.904  3345  3392 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-10 14:14:46.904  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.905  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 14:14:46.905  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 14:14:46.905  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.905  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 14:14:46.905  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-10 14:14:46.905  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 14:14:46.905  3345  3392 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 14:14:46.905  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 14:14:46.905  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 14:14:46.906  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 14:14:46.906  3345  3392 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 14:14:46.906  3345  3345 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 14:14:46.906  3345  3345 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 14:14:46.906  3345  3345 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 14:14:46.907  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.907  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.907  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 14:14:46.907  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.907  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 14:14:46.907  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.907  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.907  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.907  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.907  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.907  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.908  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.908  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.908  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.908  3345  3392 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 14:14:46.909  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 14:14:46.910  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:46.910  3345  3392 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 14:14:46.910  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:46.910  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:14:46.910  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:14:46.910  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:14:46.910  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:46.910  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:46.910  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:14:46.910  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:46.910  3345  3392 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:14:46.910  3345  3392 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 14:14:46.910  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:14:46.911  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 14:14:46.911  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 14:14:46.911  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 14:14:46.911  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 14:14:46.911  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 14:14:46.912  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-10 14:14:46.912  3345  3392 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-10 14:14:46.913  3345  3345 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-10 14:14:46.913  3345  3392 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 14:14:46.913  3345  3392 I io.jxcore.node.ConnectionHelper: start: OK
08-10 14:14:46.913  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.913  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.913  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 14:14:46.913  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.913  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 14:14:46.913  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 14:14:46.913  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 14:14:46.913  3345  3392 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 14:14:46.913  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 14:14:46.913  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 14:14:46.914  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 14:14:46.914  3345  3392 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 14:14:46.914  3345  3345 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 14:14:46.914  3345  3345 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 14:14:46.914  3345  3345 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 14:14:46.915  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.915  3345  3392 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-10 14:14:46.915  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.915  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.915  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.915  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.915  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 14:14:46.915  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.915  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.915  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.915  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.915  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.915  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.916  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.916  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.916  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.916  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.916  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.916  3345  3392 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-10 14:14:46.917  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.917  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.917  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.917  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.917  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.917  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.917  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.917  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.917  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.917  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.917  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.917  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.917  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.917  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.918  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.918  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.918  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.918  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.918  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 14:14:46.918  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.918  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.918  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.919  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.919  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.919  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.919  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.919  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.919  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.919  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.919  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.919  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.919  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.919  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.919  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.919  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.919  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.920  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.920  3345  3392 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-10 14:14:46.920  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.920  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.920  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.920  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.920  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.920  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.920  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.920  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.921  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.921  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.921  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.921  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.921  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.921  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.921  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.921  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.921  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.921  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.922  3345  3392 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-10 14:14:46.922  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.922  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.922  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.922  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.922  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.922  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.922  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.922  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.922  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.922  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.922  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.922  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.922  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.922  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.923  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.923  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.923  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.923  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.923  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 14:14:46.924  3345  3392 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 14:14:46.924  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 14:14:46.924  3345  3392 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 14:14:46.924  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 14:14:46.925  3345  3392 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 14:14:46.925  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.925  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.925  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.925  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.925  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.925  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.925  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.925  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.925  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.925  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.925  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.925  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.925  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.925  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.926  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.926  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.926  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.926  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.926  3345  3392 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 14:14:46.926  3345  3392 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 14:14:46.927  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 14:14:46.929  3345  3392 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 14:14:46.929  3345  3392 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-10 14:14:46.929  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 14:14:46.929  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 14:14:46.929  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 14:14:46.929  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 14:14:46.929  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 14:14:46.929  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 14:14:46.929  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 14:14:46.929  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 14:14:46.929  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 14:14:46.929  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 14:14:46.929  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 14:14:46.929  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 14:14:46.929  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 14:14:46.929  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.Con,nectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 14:14:46.930  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 14:14:46.930  3345  3392 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-10 14:14:46.931  3345  3392 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 14:14:46.931  3345  3392 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-10 14:14:46.931  3345  3392 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 14:14:46.931  3345  3392 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 14:14:46.931  3345  3392 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-10 14:14:46.931  3345  3392 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 14:14:46.931  3345  3392 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 14:14:46.931  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-10 14:14:46.932  3345  3392 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-10 14:14:46.932  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-10 14:14:46.934  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-10 14:14:46.934  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-10 14:14:46.934  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-10 14:14:46.934  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-10 14:14:46.934  3345  3392 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-10 14:14:46.935  3345  3392 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 14:14:46.935  3345  3392 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-10 14:14:46.935  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.936  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.936  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.936  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.936  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.936  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.936  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-10 14:14:46.938  3345  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 350)
08-10 14:14:46.939  3345  3394 E BluetoothDevice: Bluetooth is not enabled
08-10 14:14:46.939  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.939  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.939  3345  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 350)
08-10 14:14:46.939  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.940  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.940  3345  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 350)
08-10 14:14:46.940  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.940  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.941  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.941  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.941  3345  3394 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 350)
08-10 14:14:46.941  3345  3395 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 350
08-10 14:14:46.942  3345  3345 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
08-10 14:14:46.942  3345  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 350
08-10 14:14:46.942  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.942  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.942  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.942  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.942  3345  3345 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
08-10 14:14:46.942  3345  3345 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 14:14:46.943  3345  3345 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 14:14:46.943  3345  3392 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-10 14:14:46.942  3345  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 350)
08-10 14:14:46.943  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.943  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.943  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.943  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.944  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.944  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.944  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.944  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.944  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.944  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.944  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.944  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.944  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.944  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.945  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.945  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.945  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.945  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.947  3345  3392 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-10 14:14:46.948  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.948  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.948  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.948  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.948  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.948  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.948  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.948  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.948  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.948  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.948  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.948  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.948  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.948  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.949  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.949  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 14:14:46.949  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.949  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.951  3345  3392 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-10 14:14:46.951  3345  3392 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-10 14:14:46.951  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 14:14:46.951  3345  3392 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-10 14:14:46.952  3345  3392 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 14:14:46.952  3345  3392 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-10 14:14:46.952  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 14:14:46.953  3345  3392 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-10 14:14:46.953  3345  3392 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 14:14:46.953  3345  3392 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 14:14:46.953  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 14:14:46.953  3345  3392 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-10 14:14:46.953  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.954  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.954  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.955  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.955  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.955  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.955  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.955  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.955  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.956  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.956  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.956  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.956  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.956  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.957  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.957  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.957  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.957  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.957  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.957  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.958  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.958  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.958  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.958  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.958  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.958  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.958  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.958  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.958  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.958  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.958  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.958  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.958  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.958  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.958  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.958  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.958  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.959  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.959  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.959  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.959  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.959  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.959  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.959  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.959  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.959  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.959  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.959  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.959  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.959  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.959  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.960  3345  3392 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-10 14:14:46.960  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 14:14:46.960  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-10 14:14:46.960  3345  3392 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-10 14:14:46.961  3345  3345 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-10 14:14:46.961  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 14:14:46.961  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.961  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-10 14:14:46.961  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.961  3345  3392 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-10 14:14:46.961  3345  3345 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-10 14:14:46.961  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.961  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.961  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 14:14:46.962  3345  3392 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 14:14:46.962  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 14:14:46.962  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.962  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.962  3345  3392 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 14:14:46.962  3345  3345 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 14:14:46.962  3345  3345 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 14:14:46.962  3345  3345 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 14:14:46.962  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.962  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.963  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.963  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.963  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.963  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.963  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.963  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.963  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.963  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.963  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.963  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.963  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.963  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.963  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.963  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.963  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.963  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.964  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.964  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 14:14:46.965  3345  3392 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 14:14:46.965  3345  3392 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-10 14:14:46.965  3345  3392 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 14:14:46.965  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 14:14:46.965  3345  3392 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 14:14:46.966  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.966  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.966  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.966  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.966  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.966  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.966  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.966  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.966  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.966  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.966  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.966  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.967  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.967  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.967  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.967  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.967  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.967  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.969  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.969  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.969  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.969  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.969  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.969  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.969  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.969  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.969  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.969  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.969  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.969  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.969  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.969  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.970  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.970  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.970  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.970  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.971  3345  3392 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 14:14:46.971  3345  3392 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 14:14:46.971  3345  3392 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 14:14:46.972  3345  3392 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 14:14:46.972  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.972  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.972  3345  3392 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90709cd not in the list
08-10 14:14:46.972  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.972  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.972  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
08-10 14:14:46.972  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.972  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.972  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 14:14:46.973  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 14:14:46.973  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 14:14:46.973  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 14:14:46.973  3345  3392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 14:14:46.974  3345  3392 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d282 not in the list
08-10 14:14:46.975  3345  3392 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-10 14:14:46.975  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 14:14:46.975  3345  3392 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-10 14:14:46.975  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 14:14:46.975  3345  3392 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-10 14:14:46.975  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 14:14:46.977  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 14:14:46.977  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-10 14:14:46.978  3345  3392 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-10 14:14:46.978  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 14:14:46.978  3345  3392 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-10 14:14:46.978  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 14:14:46.978  3345  3392 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-10 14:14:46.979  3345  3392 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-10 14:14:46.979  3345  3392 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-10 14:14:46.979  3345  3392 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-10 14:14:46.980  3345  3392 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-10 14:14:46.980  3345  3392 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-10 14:14:46.980  3345  3392 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-10 14:14:46.980  3345  3392 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-10 14:14:46.981  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 14:14:46.981  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a6f0afc added. We now have 2 listener(s)
08-10 14:14:46.981  3345  3392 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 14:14:46.982   875  1398 D WifiService: setWifiEnabled: true pid=3345, uid=10000
08-10 14:14:46.983   875  1398 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 14:14:46.986  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 14:14:46.986  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@188a585 added. We now have 3 listener(s,)
08-10 14:14:46.986  3345  3392 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 14:14:46.987  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:46.987  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:46.987  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 14:14:46.988  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37b2fda added. We now have 4 listener(s)
08-10 14:14:46.988  3345  3392 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 14:14:46.989  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 14:14:46.989  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a3fc0b added. We now have 5 listener(s)
08-10 14:14:46.989  3345  3392 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 14:14:46.990   875  1724 D WifiService: setWifiEnabled: false pid=3345, uid=10000
08-10 14:14:46.990   875  1724 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 14:14:47.000   875   892 I ActivityManager: Start proc 3398:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-10 14:14:47.001   875  1316 D WifiConfigStore: Loading config and enabling all networks 
08-10 14:14:47.003  3345  3345 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:47.003  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:14:47.003  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:47.003  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:14:47.003  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:14:47.003  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:14:47.003  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:47.003  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:47.003  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:14:47.003  3345  3345 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:47.003  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 14:14:47.011   875  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-10 14:14:47.012   875  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-10 14:14:47.013   875  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-10 14:14:47.013   875  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-10 14:14:47.013   875  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-10 14:14:47.013   875  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-10 14:14:47.013   875  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-10 14:14:47.023   875   888 I ActivityManager: Start proc 3410:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-10 14:14:47.029  3345  3392 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 14:14:47.029  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 14:14:47.029  3345  3392 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 14:14:47.029  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:47.029  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:14:47.029  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:14:47.029  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:14:47.029  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:47.029  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:47.029  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:14:47.029  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:47.029  3345  3392 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:14:47.030  3345  3392 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 14:14:47.030  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:14:47.069  3410  3410 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-10 14:14:47.073   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-10 14:14:47.074   875  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-10 14:14:47.076   373   873 D CommandListener: Setting iface cfg
,08-10 14:14:47.084   875  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
,08-10 14:14:47.084   875  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-10 14:14:47.084   875  1316 E native  : do suspend true
,08-10 14:14:47.095   875  1315 D WifiNative-HAL: p2pGetDeviceAddress
,08-10 14:14:47.095   875  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-10 14:14:47.106  3398  3398 D AdapterServiceConfig: Adding HeadsetService
,08-10 14:14:47.106  3398  3398 D AdapterServiceConfig: Adding A2dpService
08-10 14:14:47.106  3398  3398 D AdapterServiceConfig: Adding HidService
,08-10 14:14:47.107  3398  3398 D AdapterServiceConfig: Adding HealthService
08-10 14:14:47.107  3398  3398 D AdapterServiceConfig: Adding PanService
08-10 14:14:47.107  3398  3398 D AdapterServiceConfig: Adding GattService
08-10 14:14:47.107  3398  3398 D AdapterServiceConfig: Adding BluetoothMapService
,08-10 14:14:47.114  1459  1459 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,08-10 14:14:47.114  1459  1459 W wpa_supplicant: wlan0: Failed to initiate AP scan
,08-10 14:14:47.120   875  1316 D WifiConfigStore: Retrieve network priorities after PNO.
08-10 14:14:47.120  3345  3345 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 14:14:47.120  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:14:47.120  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:47.120  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:14:47.120  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:14:47.120  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:14:47.120  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:47.120  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:47.120  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:14:47.120  3345  3345 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:47.120  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:14:47.121  3345  3345 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:47.121  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:14:47.121  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:47.121  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 14:14:47.121  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:14:47.121  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:14:47.121  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:47.121  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:47.121  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 14:14:47.121  3345  3345 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:47.121  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:14:47.122  1841  2066 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 14:14:47.130   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31706d7:true
,08-10 14:14:47.130  3398  3398 D BluetoothAdapterState: make() - Creating AdapterState
,08-10 14:14:47.132  3398  3398 I bt_bluedroid: init
,08-10 14:14:47.134  3398  3434 I BluetoothAdapterState: Entering OffState
,08-10 14:14:47.136  3398  3435 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-10 14:14:47.137  3410  3410 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-10 14:14:47.137  3398  3435 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 14:14:47.137  3398  3435 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 14:14:47.137  3398  3435 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-10 14:14:47.138  3398  3398 I bt_bluedroid: get_profile_interface socket
,08-10 14:14:47.139  3398  3438 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 14:14:47.139  3398  3398 I bt_bluedroid: get_profile_interface sdp
,08-10 14:14:47.140  3398  3438 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 14:14:47.141  3398  3409 I bt_bluedroid: config_hci_snoop_log
,08-10 14:14:47.142   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-10 14:14:47.145  3398  3434 D BluetoothAdapterState: Current state: OFF, message: 0
,08-10 14:14:47.145  3398  3434 D BluetoothAdapterProperties: Setting state to 14
08-10 14:14:47.145  3398  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-10 14:14:47.147  3398  3434 D BluetoothBondStateMachine: make
,08-10 14:14:47.148  3398  3441 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-10 14:14:47.151  3398  3398 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-10 14:14:47.151  3398  3434 I BluetoothAdapterState: Entering PendingCommandState
,08-10 14:14:47.152  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
08-10 14:14:47.153  3398  3398 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 14:14:47.153  3398  3398 D BtGatt.GattService: Received start request. Starting profile...
08-10 14:14:47.153  3398  3398 D BtGatt.GattService: start()
08-10 14:14:47.153  3398  3398 I bt_bluedroid: get_profile_interface gatt
,08-10 14:14:47.154  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
,08-10 14:14:47.154  3398  3398 D BtGatt.AdvertiseManager: advertise manager created
,08-10 14:14:47.160  3398  3398 V BluetoothAdapterState: isTurningOff()=false
,08-10 14:14:47.160  3398  3398 V BluetoothAdapterState: isTurningOn()=false
08-10 14:14:47.160   875   886 I ActivityManager: Killing 2677:com.google.android.calendar/u0a37 (adj 15): empty #17
08-10 14:14:47.160  3398  3398 V BluetoothAdapterState: isBleTurningOn()=true
,08-10 14:14:47.160  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:14:47.161  3398  3434 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-10 14:14:47.161  3398  3434 I bt_bluedroid: enable
08-10 14:14:47.161  3398  3435 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-10 14:14:47.161  3398  3435 I bt_hci  : start_up
,08-10 14:14:47.233  3398  3435 I bt_vendor: alloc value 0xb39be189
,08-10 14:14:47.234  3398  3435 I bt_vendor: init
08-10 14:14:47.234  3398  3435 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-10 14:14:47.234  3398  3435 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-10 14:14:47.344  3398  3435 D bt_hci  : start_up starting async portion
,08-10 14:14:47.345  3398  3445 I bt_hci  : event_finish_startup
,08-10 14:14:47.345  3398  3445 I bt_hci_h4: hal_open
,08-10 14:14:47.345  3398  3445 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-10 14:14:47.352  3398  3445 I bt_userial_vendor: device fd = 51 open
,08-10 14:14:47.386  3398  3445 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 14:14:47.418  3398  3445 D bt_hwcfg: Chipset BCM4354A2
,08-10 14:14:47.418  3398  3445 D bt_hwcfg: Target name = [BCM4354A2]
08-10 14:14:47.419  3398  3445 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-10 14:14:47.464  3345  3345 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 14:14:48.495  3398  3445 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-10 14:14:48.497  3398  3445 D bt_hwcfg: Settlement delay -- 100 ms
08-10 14:14:48.497  3398  3445 I bt_hwcfg: Setting fw settlement delay to 100 
,08-10 14:14:48.619  3398  3445 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 14:14:48.621  3398  3445 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-10 14:14:48.646  3398  3445 I bt_hwcfg: vendor lib fwcfg completed
08-10 14:14:48.646  3398  3445 I bt_vendor: firmware callback
08-10 14:14:48.646  3398  3445 I bt_hci  : firmware_config_callback
,08-10 14:14:48.659  3398  3447 I bt_btu  : btu_task pending for preload complete event
,08-10 14:14:48.659  3398  3447 I bt_btu_task: Bluetooth chip preload is complete
08-10 14:14:48.660  3398  3447 I bt_btu  : btu_task received preload complete event
,08-10 14:14:48.671  3398  3447 I         : BTE_InitTraceLevels -- TRC_HCI
08-10 14:14:48.672  3398  3447 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-10 14:14:48.672  3398  3447 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-10 14:14:48.672  3398  3447 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-10 14:14:48.673  3398  3447 I         : BTE_InitTraceLevels -- TRC_AVRC
08-10 14:14:48.673  3398  3447 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 14:14:48.673  3398  3447 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-10 14:14:48.673  3398  3447 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 14:14:48.674  3398  3447 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 14:14:48.674  3398  3447 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 14:14:48.674  3398  3447 I         : BTE_InitTraceLevels -- TRC_SDP
,08-10 14:14:48.674  3398  3447 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 14:14:48.675  3398  3447 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 14:14:48.675  3398  3447 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 14:14:48.675  3398  3447 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 14:14:48.828  3398  3447 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb393bd9d
,08-10 14:14:48.829  3398  3447 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb393bd9d 
,08-10 14:14:48.841  3398  3438 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-10 14:14:48.843  3398  3438 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 14:14:48.844  3398  3438 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 14:14:48.847  3398  3438 D BluetoothAdapterProperties: Name is: Nexus 6
08-10 14:14:48.851  3398  3438 D BluetoothAdapterProperties: Scan Mode:20
,08-10 14:14:48.851  3398  3438 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-10 14:14:48.852  3398  3438 D bt_hci  : do_postload posting postload work item
,08-10 14:14:48.852  3398  3445 I bt_hci  : event_postload
,08-10 14:14:48.853  3398  3445 I bt_vendor: sco_config_cb
,08-10 14:14:48.853  3398  3445 I bt_hci  : sco_config_callback postload finished.
,08-10 14:14:48.861  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:14:48.863  3398  3438 D bt_bte_conf: Device ID record 1 : primary
,08-10 14:14:48.863  3398  3438 D bt_bte_conf:   vendorId            = 000f
08-10 14:14:48.863  3398  3438 D bt_bte_conf:   vendorIdSource      = 0001
08-10 14:14:48.863  3398  3438 D bt_bte_conf:   product             = 1200
,08-10 14:14:48.864  3398  3438 D bt_bte_conf:   version             = 1436
08-10 14:14:48.864  3398  3438 D bt_bte_conf:   clientExecutableURL = 
08-10 14:14:48.864  3398  3438 D bt_bte_conf:   serviceDescription  = 
,08-10 14:14:48.864  3398  3438 D bt_bte_conf:   documentationURL    = 
08-10 14:14:48.865  3398  3438 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-10 14:14:48.865  3398  3445 I bt_vendor: low_power_mode_cb
,08-10 14:14:48.865  3398  3435 D bt_stack_manager: event_start_up_stack finished
,08-10 14:14:48.867  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:14:48.867  3398  3434 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-10 14:14:48.867  3398  3434 D BluetoothAdapterProperties: Setting state to 15
08-10 14:14:48.868  3398  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-10 14:14:48.871  3398  3434 I BluetoothAdapterState: Entering BleOnState
08-10 14:14:48.878  3398  3434 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-10 14:14:48.878  3398  3434 D BluetoothAdapterProperties: Setting state to 11
08-10 14:14:48.878  3398  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-10 14:14:48.891  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
,08-10 14:14:48.891  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:14:48.893  3398  3398 D HeadsetService: Received start request. Starting profile...
08-10 14:14:48.894  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:14:48.896  3398  3398 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 14:14:48.896  3398  3398 D HeadsetStateMachine: make
,08-10 14:14:48.904   875   888 I ActivityManager: Start proc 3455:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-10 14:14:48.911  3398  3398 D HeadsetStateMachine: max_hf_connections = 1
,08-10 14:14:48.911  3398  3398 I bt_bluedroid: get_profile_interface handsfree
,08-10 14:14:48.912  3398  3438 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-10 14:14:48.912  3398  3438 E bt_btif : btif_hf_upstreams_evt: Invalid index 1024
,08-10 14:14:48.914  3398  3434 I BluetoothAdapterState: Entering PendingCommandState
,08-10 14:14:48.918  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
,08-10 14:14:48.920   875   875 D BluetoothA2dp: Proxy object connected
08-10 14:14:48.920  3398  3398 D A2dpService: Received start request. Starting profile...,
08-10 14:14:48.921  3398  3398 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-10 14:14:48.921  3398  3398 I bt_bluedroid: get_profile_interface avrcp
,08-10 14:14:48.927  3398  3398 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-10 14:14:48.927  3398  3398 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 14:14:48.927  3398  3398 D A2dpStateMachine: make
,08-10 14:14:48.928  3398  3398 I bt_bluedroid: get_profile_interface a2dp
,08-10 14:14:48.932  3398  3438 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-10 14:14:48.934  3398  3467 D A2dpStateMachine: Enter Disconnected: -2
,08-10 14:14:48.935  3398  3398 I BluetoothHidServiceJni: classInitNative: succeeds
,08-10 14:14:48.937  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
,08-10 14:14:48.939  1352  1352 D BluetoothInputDevice: Proxy object connected
,08-10 14:14:48.939  1352  1352 D HidProfile: Bluetooth service connected
,08-10 14:14:48.940  3398  3398 D HidService: Received start request. Starting profile...
08-10 14:14:48.940  3398  3398 I bt_bluedroid: get_profile_interface hidhost
,08-10 14:14:48.941  3398  3438 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb391d3e5
,08-10 14:14:48.941  3398  3438 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-10 14:14:48.941  3398  3398 D HidService: setHidService(): set to: null
,08-10 14:14:48.944  3398  3398 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-10 14:14:48.946  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
,08-10 14:14:48.947  3398  3398 D HealthService: Received start request. Starting profile...
,08-10 14:14:48.950  3398  3398 I bt_bluedroid: get_profile_interface health
,08-10 14:14:48.951  3398  3398 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-10 14:14:48.952  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
,08-10 14:14:48.953  3398  3398 D PanService: Received start request. Starting profile...
,08-10 14:14:48.953  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 14:14:48.953  3398  3398 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-10 14:14:48.953  3398  3398 I bt_bluedroid: get_profile_interface pan
,08-10 14:14:48.954  1352  1352 D PanProfile: Bluetooth service connected
08-10 14:14:48.954  3398  3438 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-10 14:14:48.959  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
,08-10 14:14:48.960  1352  1352 D BluetoothMap: Proxy object connected
,08-10 14:14:48.961  1352  1352 D MapProfile: Bluetooth service connected
08-10 14:14:48.961  1352  1352 D BluetoothMap: getConnectedDevices()
08-10 14:14:48.961  3398  3398 D BluetoothMapService: Received start request. Starting profile...
,08-10 14:14:48.961  3398  3398 D BluetoothMapService: start()
08-10 14:14:48.961  1352  1352 D BluetoothMap: Bluetooth is Not enabled
,08-10 14:14:48.963  3398  3398 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-10 14:14:48.963  3398  3398 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-10 14:14:48.963  3398  3398 D BluetoothMapAppObserver: createReceiver()
08-10 14:14:48.964  3398  3398 D BluetoothMapAppObserver: initObservers()
,08-10 14:14:48.964  3398  3398 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-10 14:14:48.967  3455  3455 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-10 14:14:48.969  3398  3454 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-10 14:14:48.969  3398  3398 V BluetoothAdapterState: isTurningOff()=false
08-10 14:14:48.969  3398  3398 V BluetoothAdapterState: isTurningOn()=true
08-10 14:14:48.969  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:14:48.969  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:14:48.971  3398  3398 V BluetoothAdapterState: isTurningOff()=false
,08-10 14:14:48.971  3398  3398 V BluetoothAdapterState: isTurningOn()=true
,08-10 14:14:48.971  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 14:14:48.971  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 14:14:48.971  3398  3398 V BluetoothAdapterState: isTurningOff()=false
,08-10 14:14:48.971  3398  3398 V BluetoothAdapterState: isTurningOn()=true
,08-10 14:14:48.971  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 14:14:48.971  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 14:14:48.971  3398  3398 V BluetoothAdapterState: isTurningOff()=false
,08-10 14:14:48.971  3398  3398 V BluetoothAdapterState: isTurningOn()=true
,08-10 14:14:48.971  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 14:14:48.971  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:14:48.971  3398  3398 V BluetoothAdapterState: isTurningOff()=false
08-10 14:14:48.972  3398  3398 V BluetoothAdapterState: isTurningOn()=true
08-10 14:14:48.972  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:14:48.972  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:14:48.972  3398  3398 V BluetoothAdapterState: isTurningOff()=false
08-10 14:14:48.972  3398  3398 V BluetoothAdapterState: isTurningOn()=true
08-10 14:14:48.972  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:14:48.972  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:14:48.972  3398  3434 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-10 14:14:48.972  3398  3434 D BluetoothAdapterProperties: ScanMode =  20
08-10 14:14:48.972  3398  3434 D BluetoothAdapterProperties: State =  11
08-10 14:14:48.972  3398  3434 D BluetoothAdapterProperties: Setting state to 12
08-10 14:14:48.972  3398  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 14:14:48.973   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:14:48.973  3398  3434 I BluetoothAdapterState: Entering OnState
08-10 14:14:48.974  1728  2032 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:14:48.974  3398  3438 D BluetoothAdapterProperties: Scan Mode:21
08-10 14:14:48.975  3398  3438 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 14:14:48.975   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:14:48.976  3345  3345 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-10 14:14:48.976  1352  1383 D BluetoothPan: onBluetoothStateChange on: true
08-10 14:14:48.976   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:14:48.976  1352  1374 D BluetoothMap: onBluetoothStateChange: up=true
08-10 14:14:48.976   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 14:14:48.976  1352  1804 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 14:14:48.977  1352  1383 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 14:14:48.978  3345  3345 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-10 14:14:48.979   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-10 14:14:48.979  3398  3398 D BluetoothMapService: onReceive
08-10 14:14:48.979  3398  3398 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:14:48.979  3398  3398 D BluetoothMapService: STATE_ON
08-10 14:14:48.980  3345  3345 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-10 14:14:48.983  1352  1675 D LocalBluetoothProfileManager: Adding local A2DP profile
08-10 14:14:48.985   875  1770 I ActivityManager: Killing 2810:com.google.android.gm/u0a78 (adj 15): empty #17
08-10 14:14:48.987  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:14:48.987  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:48.987  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 14:14:48.987  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:14:48.987  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:14:48.987  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:48.987  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:48.987  3345  3345 V io.jxcore.node.ConnectivityM,onitor:     - active network type is Wi-Fi: false
08-10 14:14:48.988  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:14:48.989  3398  3398 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-10 14:14:48.990  3398  3398 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-10 14:14:48.991  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:14:48.991  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:48.991  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 14:14:48.991  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:14:48.991  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:14:48.991  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:48.991  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:48.991  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:14:48.992  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:14:48.993  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:14:48.994  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:14:49.050  1352  1352 D BluetoothA2dp: Proxy object connected
08-10 14:14:49.050  3398  3398 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 14:14:49.052  1352  1675 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-10 14:14:49.053  3398  3398 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 14:14:49.054  3398  3398 D ObexServerSockets: Succeed to create listening sockets 
08-10 14:14:49.054  3398  3398 D ObexServerSockets0: startAccept()
08-10 14:14:49.054  3398  3398 D ObexServerSockets0: prepareForNewConnect()
,08-10 14:14:49.056  3398  3398 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-10 14:14:49.056  3398  3398 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-10 14:14:49.057  3398  3398 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 14:14:49.057  3398  3398 D ObexServerSockets0: prepareForNewConnect()
08-10 14:14:49.058  3398  3475 D ObexServerSockets0: Accepting socket connection...
08-10 14:14:49.058  3398  3474 D ObexServerSockets0: Accepting socket connection...
,08-10 14:14:49.061  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 14:14:49.074   875   892 D BluetoothHeadset: Proxy object connected
,08-10 14:14:49.075  1728  1741 D BluetoothHeadset: Proxy object connected
,08-10 14:14:49.076   875   892 D BluetoothHeadset: Proxy object connected
,08-10 14:14:49.076   875   892 D BluetoothHeadset: Proxy object connected
08-10 14:14:49.076   875  1724 I ActivityManager: Start proc 3476:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-10 14:14:49.106  3476  3476 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-10 14:14:49.158  1352  1374 D BluetoothHeadset: Proxy object connected
,08-10 14:14:49.158  1352  1352 D HeadsetProfile: Bluetooth service connected
,08-10 14:14:49.234  3476  3476 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 14:14:49.234  3476  3476 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 14:14:49.234  3476  3476 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 14:14:49.234  3476  3476 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.r.e.b(PG:170)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 14:14:49.234  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 14:14:49.235  3476  3476 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.r.k.d(PG:583)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.r.e.b(PG:170)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 14:14:49.235  3476  3476 D StrictMode: StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 14:14:49.235  3476  3476 D StrictMode: StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 14:14:49.235  3476  3476 D StrictMode: StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread$H.,handleMessage(ActivityThread.java:1405)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 14:14:49.235  3476  3476 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 14:14:49.240  3455  3455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 14:14:49.256  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 14:14:49.259  1352  1352 D BluetoothPbap: Proxy object connected
,08-10 14:14:49.259  1352  1352 D PbapServerProfile: Bluetooth service connected
08-10 14:14:49.262   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c3779fd:true
,08-10 14:14:49.265  3398  3501 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 14:14:49.270  3455  3455 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-10 14:14:49.276  3455  3455 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-10 14:14:49.304  3455  3455 D LocalBluetoothProfileManager: Adding local MAP profile
08-10 14:14:49.305  3455  3455 D BluetoothMap: Create BluetoothMap proxy object
,08-10 14:14:49.310  3455  3455 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-10 14:14:49.312  3398  3509 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 14:14:49.313  3398  3509 I BtOppRfcommListener: Accept thread started.
,08-10 14:14:49.317  3455  3455 D DockEventReceiver: finishStartingService: stopping service
,08-10 14:14:49.318  3455  3455 D BluetoothA2dp: Proxy object connected
,08-10 14:14:49.321  3455  3455 D BluetoothInputDevice: Proxy object connected
,08-10 14:14:49.322  3455  3455 D HidProfile: Bluetooth service connected
,08-10 14:14:49.324  3455  3455 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 14:14:49.325  3455  3455 D PanProfile: Bluetooth service connected
,08-10 14:14:49.325  3455  3455 D BluetoothMap: Proxy object connected
,08-10 14:14:49.326  3455  3455 D MapProfile: Bluetooth service connected
08-10 14:14:49.326  3455  3455 D BluetoothMap: getConnectedDevices()
,08-10 14:14:49.328  3455  3455 D BluetoothPbap: Proxy object connected
,08-10 14:14:49.330  3455  3455 D PbapServerProfile: Bluetooth service connected
,08-10 14:14:49.331   875  1398 I ActivityManager: Killing 3007:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-10 14:14:49.379  3455  3465 D BluetoothHeadset: Proxy object connected
,08-10 14:14:49.380  3455  3455 D HeadsetProfile: Bluetooth service connected
,08-10 14:14:49.498  3476  3498 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-10 14:14:49.510   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b2c9220:true
,08-10 14:14:50.034   875  1747 D WifiService: setWifiEnabled: true pid=3345, uid=10000
,08-10 14:14:50.035   875  1747 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 14:14:50.046   875  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-10 14:14:50.060  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:14:50.060  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:50.060  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 14:14:50.060  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:14:50.060  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:14:50.060  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:50.060  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:50.060  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 14:14:50.066  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-10 14:14:50.068   875  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-10 14:14:50.069   875  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-10 14:14:50.070   875  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-10 14:14:50.071   875  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-10 14:14:50.071   875  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-10 14:14:50.071   875  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-10 14:14:50.071   875  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-10 14:14:50.073  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:14:50.073  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:50.073  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 14:14:50.073  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:14:50.073  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:14:50.073  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:50.073  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:50.073  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 14:14:50.076  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
08-10 14:14:50.077  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 14:14:50.153   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-10 14:14:50.155   373   873 D CommandListener: Setting iface cfg
,08-10 14:14:50.156   875  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-10 14:14:50.156   875  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '36 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 36 Failed to set address (No such device)'
,08-10 14:14:50.157   875  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-10 14:14:50.160  1459  1459 E wpa_supplicant: PNO: In assoc process
,08-10 14:14:50.161   875  1316 E WifiStateMachine:  Fail to set up pno, want true now false
,08-10 14:14:50.163   875  1316 E native  : do suspend true
,08-10 14:14:50.171   875  1315 D WifiNative-HAL: p2pGetDeviceAddress
,08-10 14:14:50.177   875  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-10 14:14:50.183   875  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 14:14:50.538  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 14:14:50.577  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-10 14:14:50.578  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-10 14:14:50.584   875  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 14:14:50.603   875  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-10 14:14:50.603   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-10 14:14:50.603   875  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 14:14:50.636   875  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 14:14:50.655   373   873 D CommandListener: Setting iface cfg
,08-10 14:14:50.666   875  1316 D WifiStateMachine: Start Dhcp Watchdog 1
,08-10 14:14:50.682   875  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-10 14:14:50.703   875  3521 D DhcpClient: Receive thread started
,08-10 14:14:50.790   875  1316 E native  : do suspend false
,08-10 14:14:50.819   875  3520 D DhcpClient: Broadcasting DHCPDISCOVER
,08-10 14:14:50.834   875  3521 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172199, domain null
,08-10 14:14:50.836   875  3520 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172199 seconds
,08-10 14:14:50.841   875  3520 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-10 14:14:50.855   875  3521 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-10 14:14:50.856   875  3520 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-10 14:14:50.861   373   873 D CommandListener: Setting iface cfg
,08-10 14:14:50.871   875  3520 D DhcpClient: Scheduling renewal in 86399s
,08-10 14:14:50.872   875  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-10 14:14:50.877   875  1316 E native  : do suspend true
,08-10 14:14:50.893   875  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-10 14:14:50.897   875  1316 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-10 14:14:50.899   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-10 14:14:50.902   875  1318 D ConnectivityService: Adding iface wlan0 to network 100
,08-10 14:14:50.910   875  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-10 14:14:50.945   875  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-10 14:14:50.946   875  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-10 14:14:50.949   875  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-10 14:14:50.950   875  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-10 14:14:50.951   875  1318 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-10 14:14:50.959   875  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-10 14:14:50.965   875  1318 D ConnectivityService: scheduleUnvalidatedPrompt 100
08-10 14:14:50.965   875  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,08-10 14:14:50.966   875  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-10 14:14:50.967   875  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 14:14:50.968   875  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
08-10 14:14:50.968   875  1318 D ConnectivityService:    accepting network in place of null
,08-10 14:14:50.969   875  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 14:14:50.977   875  3519 D NetlinkSocketObserver: NeighborEvent{elapsedMs=354777, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 14:14:51.008   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 14:14:51.045   875  3518 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.46,2a00:1450:4001:816::200e
,08-10 14:14:51.075   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 14:14:51.077   875  1318 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-10 14:14:51.087   875  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-10 14:14:51.090   875  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 14:14:51.097   875  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-10 14:14:51.098   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-10 14:14:51.107   875  1725 V BackupManagerService: Scheduling immediate backup pass
,08-10 14:14:51.116   875   875 V BackupManagerService: Running a backup pass
,08-10 14:14:51.118  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:14:51.118  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:51.118  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 14:14:51.118  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:14:51.118  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:14:51.118  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 14:14:51.118  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 14:14:51.118  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 14:14:51.120   875  3518 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 12:14:52 GMT], X-Android-Received-Millis=[1470831291115], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470831291091]}
08-10 14:14:51.122   875  1334 V BackupManagerService: clearing pending backups
,08-10 14:14:51.123  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 14:14:51.123   875  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 14:14:51.124   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-10 14:14:51.124   875  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-10 14:14:51.125   875  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-10 14:14:51.130  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:14:51.130  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:51.130  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 14:14:51.130  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 14:14:51.130  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:14:51.130  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 14:14:51.130  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 14:14:51.130  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 14:14:51.132  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 14:14:51.133   875  1334 V PerformBackupTask: Beginning backup of 16 targets
08-10 14:14:51.135  1856  1856 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 14:14:51.149   875  1696 D AlarmManagerService: Setting time of day to sec=1470831292
08-10 14:14:52.050   875  1696 W AlarmManagerService: Unable to set rtc to 1470831292: Invalid argument
,08-10 14:14:52.059   875  1334 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-10 14:14:52.060  1856  1856 D SystemUpdateService: onCreate
,08-10 14:14:52.064  1856  1856 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 14:14:52.066  1856  3538 I SystemUpdateService: active receiver: enabled
,08-10 14:14:52.075  1856  3538 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 14:14:52.076   875  1334 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,08-10 14:14:52.078  1856  3538 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-10 14:14:52.082  1856  3538 I SystemUpdateService: now status is 0 (complete)
,08-10 14:14:52.082  1856  3538 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-10 14:14:52.082  1856  3538 I SystemUpdateService: file has been verified
,08-10 14:14:52.083  1856  3538 I SystemUpdateService: OTA package size = 12249756
,08-10 14:14:52.087  1856  3538 I SystemUpdateService: showing system update notification
,08-10 14:14:52.104  1856  1856 D SystemUpdateService: onDestroy
,08-10 14:14:52.108   875  1334 I BackupRestoreController: Getting widget state for user: 0
,08-10 14:14:52.115   875  3547 D GpsLocationProvider: NTP server returned: 1470831292050 (Wed Aug 10 14:14:52 GMT+02:00 2016) reference: 354951 certainty: 4 system time offset: -65
,08-10 14:14:52.115   875  3547 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,08-10 14:14:52.140   875  1725 I ActivityManager: Start proc 3549:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-10 14:14:52.164  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:14:52.165  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:14:52.176  3549  3549 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-10 14:14:52.187  1841  2072 W GmsBackupTransport: Unknown package in backup request: @pm@
,08-10 14:14:52.191  1841  2072 V GmsBackupTransport: starting performBackup for @pm@
,08-10 14:14:52.196  1841  2072 V GmsBackupTransport: performBackup done for @pm@
,08-10 14:14:52.205  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:14:52.218  1856  3568 I iu.SyncManager: SYNC; picasa accounts
,08-10 14:14:52.222  3410  3544 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 14:14:52.235  3549  3563 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-10 14:14:52.236  1856  3546 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-10 14:14:52.237  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
08-10 14:14:52.237  1856  1856 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-10 14:14:52.237  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
08-10 14:14:52.237  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:14:52.237  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 14:14:52.238  1856  1856 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-10 14:14:52.247  1856  3568 I iu.UploadsManager: num queued entries: 0
,08-10 14:14:52.251  1856  3568 I iu.UploadsManager: num updated entries: 0
,08-10 14:14:52.252  1856  3568 I iu.SyncManager: NEXT; no task
,08-10 14:14:52.253  1511  1524 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.,
08-10 14:14:52.253  1511  1524 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 14:14:52.253  1511  1524 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 14:14:52.253  1511  1524 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 14:14:52.253  1511  1524 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 14:14:52.253  1511  1524 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 14:14:52.253  1511  1524 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 14:14:52.256  1856  1856 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 14:14:52.257  1856  1856 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 14:14:52.268   875  1725 I ActivityManager: Start proc 3574:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-10 14:14:52.270  1856  3567 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-10 14:14:52.270  1856  3567 W BaseAppContext: Using Auth Proxy for data requests.
,08-10 14:14:52.282  1856  3567 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 14:14:52.287  1841  1851 W GmsBackupTransport: Error sending final backup to server: 
08-10 14:14:52.287  1841  1851 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-10 14:14:52.287  1841  1851 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-10 14:14:52.287  1841  1851 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-10 14:14:52.287  1841  1851 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-10 14:14:52.287  1841  1851 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-10 14:14:52.287  1841  1851 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-10 14:14:52.287  1841  1851 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-10 14:14:52.287  1841  1851 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 14:14:52.287  1841  1851 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 14:14:52.287  1841  1851 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 14:14:52.287  1841  1851 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 14:14:52.287  1841  1851 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 14:14:52.287  1841  1851 W GmsBackupTransport: 	... 1 more
,08-10 14:14:52.288  1841  1854 I GmsBackupTransport: Next backup will happen in 43199968 millis.
,08-10 14:14:52.288   875  1334 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-10 14:14:52.310  3574  3574 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-10 14:14:52.314  3574  3574 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 14:14:52.315  3549  3563 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-10 14:14:52.321  3574  3574 D SprintDMHelper: simOperator: 
,08-10 14:14:52.321  3574  3574 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 14:14:52.333  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-10 14:14:52.334  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-10 14:14:52.334  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 14:14:52.334  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:14:52.336   875  1725 I ActivityManager: Start proc 3592:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-10 14:14:52.349  3549  3563 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-10 14:14:52.361  1511  2687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-10 14:14:52.361  1511  2687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-10 14:14:52.361  1511  2687 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 14:14:52.363  3410  3544 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 14:14:52.361  1511  2687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:14:52.371  3410  3544 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 14:14:52.371  3410  3544 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 14:14:52.371  3410  3544 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 14:14:52.371  3410  3544 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 14:14:52.371  3410  3544 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 14:14:52.371  3410  3544 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 14:14:52.371  3410  3544 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 14:14:52.371  3410  3544 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 14:14:52.371  3410  3544 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 14:14:52.371  3410  3544 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 14:14:52.371  3410  3544 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 14:14:52.381  1856  3567 E MDM     : [185] SitrepService.a: Error sending sitrep.
,08-10 14:14:52.407  1856  1856 E ConnectivityChangeReceiver: Ignoring connectivity change
,08-10 14:14:52.428   875  1334 I BackupManagerService: Backup pass finished.
,08-10 14:14:52.435   875  1725 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1856 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-10 14:14:52.450  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:14:52.465  3549  3549 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-10 14:14:52.541  3614  3614 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads2119332946.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads2119332946.dex
,08-10 14:14:52.596  1511  1904 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 14:14:52.596  1511  1904 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 14:14:52.596  1511  1904 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:14:52.596  1511  1904 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:14:52.614  3121  3572 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 14:14:52.614  3121  3572 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at jdm.a(PG:82)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at jcs.o(PG:406)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at jcn.a(PG:1379)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at jcs.i(PG:143)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at blb.a(PG:3937)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at czp.a(PG:18188)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at czp.a(PG:9081)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at czq.run(PG:1686)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 14:14:52.614  3121  3572 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at jdj.a(PG:4091)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at jdj.a(PG:1125)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at jdm.a(PG:77)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	... 12 more
08-10 14:14:52.614  3121  3572 E HttpOperation: Caused by: faj: BadAuthentication
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at fal.a(PG:38)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	at jdj.a(PG:4089)
08-10 14:14:52.614  3121  3572 E HttpOperation: 	... 14 more
,08-10 14:14:52.614  3549  3549 W InstanceID/Rpc: Found 10011
,08-10 14:14:52.642   875  1770 I ActivityManager: Start proc 3653:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-10 14:14:52.659  3614  3614 I dex2oat : dex2oat took 119.689ms (threads: 4) arena alloc=326KB java alloc=37KB native alloc=1528KB free=1543KB
,08-10 14:14:52.672  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 14:14:52.672  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 14:14:52.672  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:14:52.672  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:14:52.678  1856  3548 W DriveInitializer: Awaiting to be initialized
,08-10 14:14:52.678  1856  3677 W DriveInitializer: Background init thread started
,08-10 14:14:52.688  3653  3653 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-10 14:14:52.696  3121  3572 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 14:14:52.696  3121  3572 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at jdm.a(PG:82)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at jcs.o(PG:406)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at jcn.a(PG:1379)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at jcs.i(PG:143)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at hec.a(PG:42)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at hee.a(PG:102)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at czr.a(PG:65)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at kka.a(PG:108)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at czp.a(PG:19176)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at czp.a(PG:9081)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at czq.run(PG:1686)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 14:14:52.696  3121  3572 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at jdj.a(PG:4091)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at jdj.a(PG:1125)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at jdm.a(PG:77)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	... 15 more
08-10 14:14:52.696  3121  3572 E HttpOperation: Caused by: faj: BadAuthentication
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at fal.a(PG:38)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	at jdj.a(PG:4089)
08-10 14:14:52.696  3121  3572 E HttpOperation: 	... 17 more
,08-10 14:14:52.696  3121  3572 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 14:14:52.696  3121  3572 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at hec.a(PG:42)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at hee.a(PG:102)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at czr.a(PG:65)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at kka.a(PG:108)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	... 15 more
08-10 14:14:52.696  3121  3572 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at fal.a(PG:38)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 14:14:52.696  3121  3572 E ExperimentLoader: 	... 17 more
08-10 14:14:52.740  1856  3677 W DriveInitializer: Background init thread ended
,08-10 14:14:52.764  2359  3650 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-10 14:14:52.825  2859  3689 V KeepSync: Connecting to GoogleApiClient
,08-10 14:14:52.826   875  2827 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 14:14:52.893  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 14:14:52.893  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 14:14:52.893  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:14:52.893  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:14:52.904   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 22975, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 14:14:52.904  1856  3700 V BaseAuthAsyncOperation: access token request failed
08-10 14:14:52.905   875  1695 I ActivityManager: Killing 2470:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-10 14:14:52.914  2859  3689 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 14:14:52.996   875   887 I ActivityManager: Start proc 3704:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-10 14:14:53.018  3704  3704 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-10 14:14:53.051  3653  3653 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-10 14:14:53.051  3653  3653 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-10 14:14:53.051  3653  3653 I GAv4    :   adb logcat -s GAv4
,08-10 14:14:53.082  3653  3653 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-10 14:14:53.088  3653  3653 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-10 14:14:53.118  3653  3719 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-10 14:14:53.233  3653  3653 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-10 14:14:53.262  3704  3704 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-10 14:14:53.269  3704  3704 I BooksApp: Created application version: 3.6.9 (30609)
,08-10 14:14:53.281  3653  3653 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-10 14:14:53.292  3653  3653 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6192-6194)
,08-10 14:14:53.292  3653  3653 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 14:14:53.318  3653  3653 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c25e7be}
,08-10 14:14:53.318  3653  3653 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 14:14:53.319  3653  3653 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 14:14:53.327  3653  3653 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-10 14:14:53.329  3653  3653 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-10 14:14:53.337  3704  3740 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 14:14:53.361  3653  3653 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-10 14:14:53.372  3653  3653 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-10 14:14:53.372  3653  3653 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 14:14:53.372  3653  3653 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 14:14:53.372  3653  3653 I Adreno  : Build Date                       : 10/20/15
08-10 14:14:53.372  3653  3653 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 14:14:53.372  3653  3653 I Adreno  : Local Branch                     : M14
08-10 14:14:53.372  3653  3653 I Adreno  : Remote Branch                    : 
08-10 14:14:53.372  3653  3653 I Adreno  : Remote Branch                    : 
08-10 14:14:53.372  3653  3653 I Adreno  : Reconstruct Branch               : 
,08-10 14:14:53.469  3653  3653 I NSApplication: Starting up...
,08-10 14:14:53.480  3653  3756 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-10 14:14:53.512   875  1695 I ActivityManager: Start proc 3761:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-10 14:14:53.526   875  1695 I ActivityManager: Killing 2731:android.process.acore/u0a5 (adj 15): empty #17
,08-10 14:14:53.611  3761  3761 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-10 14:14:53.615  1511  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 14:14:53.616  1511  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-10 14:14:53.616  1511  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 14:14:53.616  1511  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:14:53.649  2859  3689 E KeepSync: IOException
08-10 14:14:53.649  2859  3689 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 14:14:53.649  2859  3689 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 14:14:53.649  2859  3689 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 14:14:53.649  2859  3689 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 14:14:53.649  2859  3689 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 14:14:53.649  2859  3689 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 14:14:53.649  2859  3689 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 14:14:53.649  2859  3689 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 14:14:53.649  2859  3689 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 14:14:53.649  2859  3689 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 14:14:53.649  2859  3689 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 14:14:53.649  2859  3689 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 14:14:53.649  2859  3689 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 14:14:53.649  2859  3689 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 14:14:53.649  2859  3689 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 14:14:53.649  2859  3689 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 14:14:53.649  2859  3689 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 14:14:53.649  2859  3689 E KeepSync: 	... 10 more
,08-10 14:14:53.649  2859  3689 W KeepSync: Sync result 2
,08-10 14:14:53.655   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 22986, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 14:14:53.656   875   886 I ActivityManager: Killing 3205:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-10 14:14:53.824  3704  3778 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 14:14:53.880  1511  2687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 14:14:53.880  1511  2687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 14:14:53.880  1511  2687 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:14:53.880  1511  2687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:14:53.920  1511  1904 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 14:14:53.920  1511  1904 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 14:14:53.920  1511  1904 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 14:14:53.920  1511  1904 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:14:53.934  3704  3778 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 14:14:53.936  3704  3740 E BooksSync: Soft error
08-10 14:14:53.936  3704  3740 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 14:14:53.936  3704  3740 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 14:14:53.936  3704  3740 E BooksSync: Sync error
08-10 14:14:53.936  3704  3740 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 14:14:53.936  3704  3740 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 14:14:53.936  3704  3740 I BooksSync: Finished books sync
,08-10 14:14:53.939   875  1770 D WifiService: setWifiEnabled: false pid=3345, uid=10000
,08-10 14:14:53.939   875  1770 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 14:14:53.943   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 22986, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-10 14:14:53.945   875  1754 I ActivityManager: Killing 3220:com.android.musicfx/u0a18 (adj 15): empty #17
08-10 14:14:53.954  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 14:14:53.956   875  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 14:14:53.956   875  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-10 14:14:53.957   875  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 14:14:53.957   875  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 14:14:53.962   875  1316 E native  : do suspend true
,08-10 14:14:53.971   875  3520 D DhcpClient: Clearing IP address
08-10 14:14:53.971   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-10 14:14:53.974   373   873 D CommandListener: Setting iface cfg
,08-10 14:14:53.976  1511  3591 V NativeCrypto: Read error: ssl=0x9a5ff800: I/O error during system call, Connection timed out
,08-10 14:14:53.978   875  3521 D DhcpClient: Receive thread stopped
08-10 14:14:53.978  1511  3591 V NativeCrypto: SSL shutdown failed: ssl=0x9a5ff800: I/O error during system call, Broken pipe
,08-10 14:14:53.980   875   885 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-10 14:14:53.980   875  3518 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-10 14:14:53.982   875  3518 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-10 14:14:53.983   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,08-10 14:14:53.983   875  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-10 14:14:53.984   875  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-10 14:14:53.985   875  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-10 14:14:53.985   875  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 14:14:53.985   875  1316 E native  : do suspend true
,08-10 14:14:53.987   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-10 14:14:53.987   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-10 14:14:53.991   402   402 E Parcel  : Reading a NULL string not supported here.
08-10 14:14:53.993   875  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-10 14:14:53.996   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-10 14:14:53.998   875  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-10 14:14:54.015   875  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 14:14:54.018  1841  2066 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 14:14:54.018   875  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 14:14:54.019  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:14:54.019  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:54.019  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 14:14:54.019  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:14:54.019  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:14:54.019  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:54.019  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:54.019  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:14:54.021  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 14:14:54.027  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:14:54.027  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:54.027  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 14:14:54.027  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:14:54.027  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:14:54.027  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:54.027  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:54.027  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:14:54.029  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 14:14:54.030   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 14:14:54.046  1511  3785 I VacuumService: Vacuum at: now=1470831294046 tag=VacuumService
,08-10 14:14:54.054   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-10 14:14:54.055   875  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-10 14:14:54.055   875  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-10 14:14:54.056   875   892 D Tethering: MasterInitialState.processMessage what=3
08-10 14:14:54.060  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:14:54.062  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:14:54.121   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-10 14:14:54.122   875  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 14:14:54.235   875  2827 I ActivityManager: Killing 3036:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-10 14:14:54.358   875  1527 I ActivityManager: Start proc 3794:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,08-10 14:14:54.438  3794  3794 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm
,08-10 14:14:54.499   875  1754 I ActivityManager: Start proc 3809:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,08-10 14:14:54.555  3794  3794 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,08-10 14:14:54.581   875  1747 I ActivityManager: Start proc 3824:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,08-10 14:14:54.585   875  1747 I ActivityManager: Killing 3243:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-10 14:14:54.633   875  1724 I ActivityManager: Killing 3170:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-10 14:14:54.734  3809  3809 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm
,08-10 14:14:54.740  3824  3824 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,08-10 14:14:54.786  3824  3824 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-10 14:14:54.786  3824  3824 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-10 14:14:54.786  3824  3824 I GAv4    :   adb logcat -s GAv4
,08-10 14:14:54.806  3809  3809 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@717a24c(com.android.providers.calendar.CalendarProvider2@b4b7295)
,08-10 14:14:54.824  3824  3824 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-10 14:14:54.830  3824  3824 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-10 14:14:54.845  3824  3840 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-10 14:14:54.943   875  1527 I ActivityManager: Start proc 3843:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,08-10 14:14:54.984  3843  3843 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm
,08-10 14:14:54.993  3843  3843 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1470831294993
08-10 14:14:54.993  3843  3843 D         : TimeServiceNative: User Time to be set is 1470831294993
08-10 14:14:54.993  3843  3843 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
,08-10 14:14:54.994  3843  3843 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-10 14:14:54.994  3843  3843 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1470831294993
08-10 14:14:54.994  3843  3843 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-10 14:14:54.994   399  1001 D QC-time-services: Daemon: Connection accepted:time_genoff
08-10 14:14:54.995   399  3855 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1470831294993
08-10 14:14:54.995   399  3855 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1470831294993, operation = 0
,08-10 14:14:54.995   399  3855 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/27/70 8:25:14
08-10 14:14:54.996   399  3855 D QC-time-services: Daemon:Value read from RTC seconds = 31134314000
08-10 14:14:54.996   399  3855 D QC-time-services: Daemon:new time 1470831294993 
08-10 14:14:54.996   399  3855 D QC-time-services: Daemon: delta 1439696980993 genoff 1439696980993 
,08-10 14:14:54.996   399  3855 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696980993 to memory
08-10 14:14:54.997   399  3855 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-10 14:14:54.997   399  3855 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation ,
,08-10 14:14:55.012   399  3855 D QC-time-services: Updating the TOD offset
,08-10 14:14:55.013   399  3855 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696980993 to memory
08-10 14:14:55.013   399  3855 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-10 14:14:55.013   399  3855 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-10 14:14:55.018  3843  3843 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-10 14:14:55.018   399  3855 E QC-time-services: Daemon:Update to modem bit set
08-10 14:14:55.021   399  3855 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
,08-10 14:14:55.021   399  3855 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1154866494993
,08-10 14:14:55.022   875  1747 I ActivityManager: Killing 1818:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-10 14:14:55.091   875  1317 D WifiService: Client connection lost with reason: 4
08-10 14:14:55.092   399  1001 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-10 14:14:55.097   399   999 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-10 14:14:55.135  2359  3858 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-10 14:14:55.185  1856  1856 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 14:14:55.188  1856  1856 D SystemUpdateService: onCreate
,08-10 14:14:55.192  1856  1856 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 14:14:55.194  1856  3861 I SystemUpdateService: active receiver: enabled
,08-10 14:14:55.197  1856  3861 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 14:14:55.198  1856  3861 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-10 14:14:55.199  1856  3861 I SystemUpdateService: now status is 0 (complete)
,08-10 14:14:55.199  1856  3861 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-10 14:14:55.199  1856  3861 I SystemUpdateService: file has been verified
08-10 14:14:55.199  1856  3861 I SystemUpdateService: OTA package size = 12249756
,08-10 14:14:55.202  1856  3861 I SystemUpdateService: showing system update notification
,08-10 14:14:55.215  1856  1856 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-10 14:14:55.217  1856  3568 I iu.UploadsManager: num queued entries: 0
08-10 14:14:55.218  1856  3568 I iu.UploadsManager: num updated entries: 0
,08-10 14:14:55.219  1856  3568 I iu.SyncManager: NEXT; no task
,08-10 14:14:55.220  1856  1856 D SystemUpdateService: onDestroy
,08-10 14:14:55.225  1856  1856 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 14:14:55.227  1856  1856 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 14:14:55.229  3574  3574 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 14:14:55.236  3574  3574 D SprintDMHelper: simOperator: 
08-10 14:14:55.236  3574  3574 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 14:14:55.903  3809  3809 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
,08-10 14:14:55.904  3809  3809 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,08-10 14:14:56.951  3398  3434 D BluetoothAdapterState: Current state: ON, message: 23
,08-10 14:14:56.951  3398  3434 D BluetoothAdapterProperties: Setting state to 13
,08-10 14:14:56.952  3398  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-10 14:14:56.953  3398  3434 D BluetoothAdapterProperties: onBluetoothDisable()
,08-10 14:14:56.959  3398  3434 I BluetoothAdapterState: Entering PendingCommandState
,08-10 14:14:56.960  3398  3438 D BluetoothAdapterProperties: Scan Mode:20
08-10 14:14:56.961  3398  3434 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-10 14:14:56.971  3345  3345 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 14:14:56.972  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:14:56.972  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:56.972  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 14:14:56.972  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:14:56.972  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:14:56.972  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:56.972  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:56.972  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:14:56.973  3398  3398 D HeadsetService: Received stop request...Stopping profile...
,08-10 14:14:56.975  3345  3345 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:56.975  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 14:14:56.982  3345  3345 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:56.983  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:14:56.983  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:14:56.983  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 14:14:56.983  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:14:56.983  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:14:56.983  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:14:56.983  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:14:56.983  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 14:14:56.984  3345  3345 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:14:56.984  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 14:14:56.989   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 14:14:56.989  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:14:56.989   875   875 D BluetoothHeadset: Proxy object disconnected
,08-10 14:14:56.989   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 14:14:56.989  3455  3455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 14:14:56.990  1352  1374 D BluetoothHeadset: Proxy object disconnected
,08-10 14:14:56.991  3455  3465 D BluetoothHeadset: Proxy object disconnected
,08-10 14:14:56.991  1728  1741 D BluetoothHeadset: Proxy object disconnected
08-10 14:14:56.992  3398  3398 D BluetoothMapService: onReceive
08-10 14:14:56.992  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:14:56.992  3398  3398 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 14:14:56.992  3398  3398 D BluetoothMapService: STATE_TURNING_OFF
,08-10 14:14:56.993  3398  3398 V BluetoothAdapterState: isTurningOff()=true
08-10 14:14:56.993  3398  3398 V BluetoothAdapterState: isTurningOn()=false
08-10 14:14:56.993  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:14:56.993  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 14:14:57.000  3455  3455 D HeadsetProfile: Bluetooth service disconnected
,08-10 14:14:57.001  3398  3398 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...,
08-10 14:14:57.001  3398  3398 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-10 14:14:57.001  3398  3447 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 14:14:57.003  3398  3447 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 14:14:57.002  3398  3398 D BluetoothMapService: MAP Service closeService in
08-10 14:14:57.004  3398  3447 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 14:14:57.004  3398  3398 D BluetoothMapMasInstance0: MAP Service shutdown
08-10 14:14:57.005  3398  3398 D ObexServerSockets0: shutdown(block = true)
08-10 14:14:57.005  3398  3398 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 14:14:57.005  3398  3398 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-10 14:14:57.006  3398  3475 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-10 14:14:57.001  3398  3438 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-10 14:14:57.006  3398  3438 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-10 14:14:57.006  3398  3449 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-10 14:14:57.006  3455  3455 D DockEventReceiver: finishStartingService: stopping service
08-10 14:14:57.006  3398  3474 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-10 14:14:57.008  1352  1352 D HeadsetProfile: Bluetooth service disconnected
08-10 14:14:57.008  3398  3398 I BtOppRfcommListener: stopping Accept Thread
,08-10 14:14:57.008  3398  3509 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 14:14:57.009  3398  3509 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 14:14:57.011  3398  3398 D A2dpService: Received stop request...Stopping profile...
08-10 14:14:57.011  3398  3467 D A2dpStateMachine: Exit Disconnected: -1
08-10 14:14:57.013   875   875 D BluetoothA2dp: Proxy object disconnected
08-10 14:14:57.014  1352  1352 D BluetoothA2dp: Proxy object disconnected
08-10 14:14:57.016  3398  3398 D HidService: Received stop request...Stopping profile...
08-10 14:14:57.016  3398  3398 D HidService: Stopping Bluetooth HidService
,08-10 14:14:57.017  1352  1352 D BluetoothInputDevice: Proxy object disconnected
08-10 14:14:57.017  1352  1352 D HidProfile: Bluetooth service disconnected
,08-10 14:14:57.020  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 14:14:57.019  3455  3455 D BluetoothA2dp: Proxy object disconnected
08-10 14:14:57.021  3398  3398 D HealthService: Received stop request...Stopping profile...
,08-10 14:14:57.023  3455  3455 D BluetoothInputDevice: Proxy object disconnected,
08-10 14:14:57.024  3455  3455 D HidProfile: Bluetooth service disconnected
,08-10 14:14:57.025  3398  3398 D PanService: Received stop request...Stopping profile...
,08-10 14:14:57.026  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 14:14:57.026  3455  3455 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 14:14:57.026  1352  1352 D PanProfile: Bluetooth service disconnected
08-10 14:14:57.026  3455  3455 D PanProfile: Bluetooth service disconnected
08-10 14:14:57.027  3398  3398 D BluetoothMapService: Received stop request...Stopping profile...
08-10 14:14:57.027  3398  3398 D BluetoothMapService: stop()
,08-10 14:14:57.027  3398  3398 D BluetoothMapAppObserver: deinitObservers()
08-10 14:14:57.027  3398  3398 D BluetoothMapAppObserver: removeReceiver()
,08-10 14:14:57.028  3455  3455 D BluetoothMap: Proxy object disconnected
,08-10 14:14:57.029  3455  3455 D MapProfile: Bluetooth service disconnected
08-10 14:14:57.029  1352  1352 D BluetoothMap: Proxy object disconnected
08-10 14:14:57.029  1352  1352 D MapProfile: Bluetooth service disconnected
,08-10 14:14:57.030  3398  3398 V BluetoothAdapterState: isTurningOff()=true
,08-10 14:14:57.031  3398  3398 V BluetoothAdapterState: isTurningOn()=false
08-10 14:14:57.031  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:14:57.031  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 14:14:57.033  3398  3438 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-10 14:14:57.033  3398  3447 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 14:14:57.033  3398  3447 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 14:14:57.033  3398  3447 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 14:14:57.033  3398  3447 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 14:14:57.033  3398  3447 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 14:14:57.033  3398  3447 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-10 14:14:57.033  3398  3398 V BluetoothAdapterState: isTurningOff()=true
08-10 14:14:57.034  3398  3398 V BluetoothAdapterState: isTurningOn()=false
08-10 14:14:57.034  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:14:57.034  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 14:14:57.035  3398  3398 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 14:14:57.035  3398  3398 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 14:14:57.035  3398  3438 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 14:14:57.037  1352  1352 D BluetoothPbap: Proxy object disconnected
,08-10 14:14:57.038  1352  1352 D PbapServerProfile: Bluetooth service disconnected
08-10 14:14:57.038  3398  3398 V BluetoothAdapterState: isTurningOff()=true
08-10 14:14:57.038  3398  3398 V BluetoothAdapterState: isTurningOn()=false
08-10 14:14:57.038  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:14:57.038  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:14:57.038  3455  3455 D BluetoothPbap: Proxy object disconnected
08-10 14:14:57.038  3455  3455 D PbapServerProfile: Bluetooth service disconnected
,08-10 14:14:57.040  3398  3398 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-10 14:14:57.040  3398  3438 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-10 14:14:57.040  3398  3398 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 14:14:57.041  3398  3398 V BluetoothAdapterState: isTurningOff()=true
08-10 14:14:57.041  3398  3398 V BluetoothAdapterState: isTurningOn()=false
08-10 14:14:57.041  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:14:57.041  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 14:14:57.041  3398  3398 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-10 14:14:57.041  3398  3398 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 14:14:57.042  3398  3398 D BluetoothMapService: MAP Service closeService in
08-10 14:14:57.042  3398  3398 V BluetoothAdapterState: isTurningOff()=true
08-10 14:14:57.042  3398  3398 V BluetoothAdapterState: isTurningOn()=false
08-10 14:14:57.042  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:14:57.042  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:14:57.042  3398  3398 D BluetoothMapService: cleanup()
08-10 14:14:57.042  3398  3398 D BluetoothMapService: MAP Service closeService in
,08-10 14:14:57.046  3398  3434 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-10 14:14:57.046  3398  3434 D BluetoothAdapterProperties: Setting state to 15
08-10 14:14:57.046  3398  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-10 14:14:57.047  3455  3468 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:14:57.047  3398  3434 I BluetoothAdapterState: Entering BleOnState
08-10 14:14:57.047  3455  3465 D BluetoothMap: onBluetoothStateChange: up=false
08-10 14:14:57.048   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:14:57.048  1728  2041 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 14:14:57.048   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 14:14:57.049  1352  1804 D BluetoothPan: onBluetoothStateChange on: false
08-10 14:14:57.050  3455  3468 D BluetoothPan: onBluetoothStateChange on: false
08-10 14:14:57.051  1352  1374 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:14:57.051  3455  3465 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 14:14:57.051   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 14:14:57.052  1352  1383 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 14:14:57.053  1352  1804 D BluetoothMap: onBluetoothStateChange: up=false
,08-10 14:14:57.054  3455  3468 D BluetoothPbap: onBluetoothStateChange: up=false
,08-10 14:14:57.055   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 14:14:57.055  1352  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 14:14:57.057  1352  1383 D BluetoothPbap: onBluetoothStateChange: up=false
,08-10 14:14:57.058  3455  3465 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-10 14:14:57.059  3398  3434 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-10 14:14:57.059  3398  3434 D BluetoothAdapterProperties: Setting state to 16
08-10 14:14:57.059  3398  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-10 14:14:57.060  3398  3434 D BluetoothAdapterProperties: onBleDisable
08-10 14:14:57.060  3398  3434 I BluetoothAdapterState: Entering PendingCommandState
,08-10 14:14:57.061  3398  3435 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-10 14:14:57.062  3398  3447 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-10 14:14:57.062  3398  3447 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 14:14:57.064  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:14:57.064  3398  3438 D BluetoothAdapterProperties: Scan Mode:20
,08-10 14:14:57.065  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:14:57.067  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:14:57.068  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:14:57.068  3455  3455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 14:14:57.074  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 14:14:57.075  3455  3455 D DockEventReceiver: finishStartingService: stopping service
,08-10 14:14:57.279  3398  3438 I bt_hci  : shut_down
,08-10 14:14:57.292  3398  3445 I bt_vendor: low_power_mode_cb
,08-10 14:14:57.300  3398  3445 D bt_hwcfg: hw_epilog_process
,08-10 14:14:57.312  3398  3445 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-10 14:14:57.312  3398  3445 I bt_vendor: epilog_cb
08-10 14:14:57.312  3398  3445 I bt_hci  : epilog_finished_callback
,08-10 14:14:57.316  3398  3438 I bt_hci_h4: hal_close
,08-10 14:14:57.317  3398  3438 I bt_userial_vendor: device fd = 51 close
,08-10 14:14:57.445  3398  3435 D bt_stack_manager: event_shut_down_stack finished.
08-10 14:14:57.446  3398  3434 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-10 14:14:57.451  3398  3398 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 14:14:57.451  3398  3434 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-10 14:14:57.452  3398  3398 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 14:14:57.452  3398  3398 D BtGatt.GattService: stop()
08-10 14:14:57.452  3398  3398 D BtGatt.AdvertiseManager: advertise clients cleared
,08-10 14:14:57.457  3398  3398 V BluetoothAdapterState: isTurningOff()=false
,08-10 14:14:57.457  3398  3398 V BluetoothAdapterState: isTurningOn()=false
08-10 14:14:57.457  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 14:14:57.457  3398  3398 V BluetoothAdapterState: isBleTurningOff()=true
08-10 14:14:57.458  3398  3434 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-10 14:14:57.458  3398  3434 D BluetoothAdapterProperties: Setting state to 10
08-10 14:14:57.459  3398  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-10 14:14:57.460  3398  3434 I BluetoothAdapterState: Entering OffState
,08-10 14:14:57.461   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-10 14:14:57.483  3398  3398 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-10 14:14:57.484  3398  3398 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-10 14:14:57.484  3398  3435 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-10 14:14:57.484  3398  3398 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-10 14:14:57.490  3398  3435 D bt_stack_manager: event_clean_up_stack finished.
,08-10 14:14:57.493  3398  3398 I art     : System.exit called, status: 0
,08-10 14:14:57.493  3398  3398 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-10 14:14:57.553   875  1725 I ActivityManager: Process com.android.bluetooth (pid 3398) has died
,08-10 14:14:58.299  3704  3738 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-10 14:14:59.582  3794  3815 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-10 14:14:59.871   875  1318 D ConnectivityService: handlePromptUnvalidated 100
,08-10 14:14:59.980   875   892 I ActivityManager: Start proc 3885:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-10 14:15:00.050  3885  3885 D AdapterServiceConfig: Adding HeadsetService
08-10 14:15:00.051  3885  3885 D AdapterServiceConfig: Adding A2dpService
08-10 14:15:00.051  3885  3885 D AdapterServiceConfig: Adding HidService
,08-10 14:15:00.051  3885  3885 D AdapterServiceConfig: Adding HealthService
08-10 14:15:00.051  3885  3885 D AdapterServiceConfig: Adding PanService
08-10 14:15:00.051  3885  3885 D AdapterServiceConfig: Adding GattService
08-10 14:15:00.051  3885  3885 D AdapterServiceConfig: Adding BluetoothMapService
,08-10 14:15:00.061   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b739f6a:true
,08-10 14:15:00.062  3885  3885 D BluetoothAdapterState: make() - Creating AdapterState
,08-10 14:15:00.066  3885  3885 I bt_bluedroid: init
,08-10 14:15:00.066  3885  3897 I BluetoothAdapterState: Entering OffState
,08-10 14:15:00.072  3885  3898 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-10 14:15:00.073  3885  3898 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-10 14:15:00.073  3885  3898 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-10 14:15:00.075  3885  3898 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-10 14:15:00.078  3885  3885 I bt_bluedroid: get_profile_interface socket
,08-10 14:15:00.079  3885  3885 I bt_bluedroid: get_profile_interface sdp
,08-10 14:15:00.083  3885  3896 I bt_bluedroid: config_hci_snoop_log
08-10 14:15:00.083  3885  3901 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 14:15:00.084   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-10 14:15:00.086  3885  3901 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 14:15:00.089  3885  3897 D BluetoothAdapterState: Current state: OFF, message: 0
,08-10 14:15:00.089  3885  3897 D BluetoothAdapterProperties: Setting state to 14
08-10 14:15:00.090  3885  3897 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-10 14:15:00.093  3885  3897 D BluetoothBondStateMachine: make
,08-10 14:15:00.097  3885  3902 I BluetoothBondStateMachine: StableState(): Entering Off State
08-10 14:15:00.099  3885  3897 I BluetoothAdapterState: Entering PendingCommandState
,08-10 14:15:00.102  3885  3885 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-10 14:15:00.105  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
,08-10 14:15:00.106  3885  3885 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 14:15:00.107  3885  3885 D BtGatt.GattService: Received start request. Starting profile...
,08-10 14:15:00.107  3885  3885 D BtGatt.GattService: start()
08-10 14:15:00.107  3885  3885 I bt_bluedroid: get_profile_interface gatt
,08-10 14:15:00.108  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
08-10 14:15:00.108  3885  3885 D BtGatt.AdvertiseManager: advertise manager created
,08-10 14:15:00.116  3885  3885 V BluetoothAdapterState: isTurningOff()=false
08-10 14:15:00.116  3885  3885 V BluetoothAdapterState: isTurningOn()=false
,08-10 14:15:00.116  3885  3885 V BluetoothAdapterState: isBleTurningOn()=true
08-10 14:15:00.116  3885  3885 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:15:00.117  3885  3897 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-10 14:15:00.117  3885  3897 I bt_bluedroid: enable
08-10 14:15:00.118  3885  3898 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-10 14:15:00.119  3885  3898 I bt_hci  : start_up
,08-10 14:15:00.139  3885  3898 I bt_vendor: alloc value 0xb39be189
08-10 14:15:00.139  3885  3898 I bt_vendor: init
,08-10 14:15:00.140  3885  3898 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-10 14:15:00.141  3885  3898 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-10 14:15:00.253  3885  3898 D bt_hci  : start_up starting async portion
,08-10 14:15:00.254  3885  3905 I bt_hci  : event_finish_startup
08-10 14:15:00.254  3885  3905 I bt_hci_h4: hal_open
08-10 14:15:00.255  3885  3905 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-10 14:15:00.265  3885  3905 I bt_userial_vendor: device fd = 51 open
,08-10 14:15:00.295  3885  3905 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 14:15:00.327  3885  3905 D bt_hwcfg: Chipset BCM4354A2
,08-10 14:15:00.327  3885  3905 D bt_hwcfg: Target name = [BCM4354A2]
,08-10 14:15:00.328  3885  3905 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-10 14:15:00.913  3885  3905 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-10 14:15:00.914  3885  3905 D bt_hwcfg: Settlement delay -- 100 ms
08-10 14:15:00.915  3885  3905 I bt_hwcfg: Setting fw settlement delay to 100 
,08-10 14:15:01.031  3885  3905 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 14:15:01.031  3885  3905 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-10 14:15:01.062  3885  3905 I bt_hwcfg: vendor lib fwcfg completed
08-10 14:15:01.062  3885  3905 I bt_vendor: firmware callback
,08-10 14:15:01.062  3885  3905 I bt_hci  : firmware_config_callback
,08-10 14:15:01.072  3885  3908 I bt_btu  : btu_task pending for preload complete event
,08-10 14:15:01.072  3885  3908 I bt_btu_task: Bluetooth chip preload is complete
08-10 14:15:01.072  3885  3908 I bt_btu  : btu_task received preload complete event
08-10 14:15:01.074   875  1732 I ActivityManager: Killing 2588:com.android.vending/u0a19 (adj 15): empty #17
,08-10 14:15:01.081  3885  3908 I         : BTE_InitTraceLevels -- TRC_HCI
,08-10 14:15:01.081  3885  3908 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-10 14:15:01.081  3885  3908 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-10 14:15:01.081  3885  3908 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 14:15:01.082  3885  3908 I         : BTE_InitTraceLevels -- TRC_AVRC
08-10 14:15:01.082  3885  3908 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 14:15:01.082  3885  3908 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-10 14:15:01.082  3885  3908 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 14:15:01.082  3885  3908 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 14:15:01.083  3885  3908 I         : BTE_InitTraceLevels -- TRC_PAN
,08-10 14:15:01.083  3885  3908 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 14:15:01.083  3885  3908 I         : BTE_InitTraceLevels -- TRC_GATT
,08-10 14:15:01.083  3885  3908 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 14:15:01.083  3885  3908 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 14:15:01.084  3885  3908 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 14:15:01.219  3885  3908 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb393bd9d
,08-10 14:15:01.219  3885  3908 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb393bd9d 
,08-10 14:15:01.228  3885  3901 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-10 14:15:01.229  3885  3901 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 14:15:01.229  3885  3901 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 14:15:01.232  3885  3901 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 14:15:01.236  3885  3901 D BluetoothAdapterProperties: Scan Mode:20
,08-10 14:15:01.236  3885  3901 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 14:15:01.237  3885  3901 D bt_hci  : do_postload posting postload work item
,08-10 14:15:01.237  3885  3905 I bt_hci  : event_postload
08-10 14:15:01.237  3885  3905 I bt_vendor: sco_config_cb
08-10 14:15:01.238  3885  3905 I bt_hci  : sco_config_callback postload finished.
,08-10 14:15:01.245  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:15:01.246  3885  3905 I bt_vendor: low_power_mode_cb
08-10 14:15:01.247  3885  3901 D bt_bte_conf: Device ID record 1 : primary
,08-10 14:15:01.247  3885  3901 D bt_bte_conf:   vendorId            = 000f
08-10 14:15:01.247  3885  3901 D bt_bte_conf:   vendorIdSource      = 0001
08-10 14:15:01.247  3885  3901 D bt_bte_conf:   product             = 1200
,08-10 14:15:01.247  3885  3901 D bt_bte_conf:   version             = 1436
08-10 14:15:01.247  3885  3901 D bt_bte_conf:   clientExecutableURL = 
08-10 14:15:01.247  3885  3901 D bt_bte_conf:   serviceDescription  = 
,08-10 14:15:01.247  3885  3901 D bt_bte_conf:   documentationURL    = 
08-10 14:15:01.248  3885  3901 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-10 14:15:01.248  3885  3898 D bt_stack_manager: event_start_up_stack finished
,08-10 14:15:01.248  3885  3897 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-10 14:15:01.248  3885  3897 D BluetoothAdapterProperties: Setting state to 15
08-10 14:15:01.248  3885  3897 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-10 14:15:01.249  3885  3897 I BluetoothAdapterState: Entering BleOnState
08-10 14:15:01.251  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:15:01.253  3885  3897 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-10 14:15:01.253  3885  3897 D BluetoothAdapterProperties: Setting state to 11
08-10 14:15:01.253  3885  3897 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-10 14:15:01.260  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
,08-10 14:15:01.261  3885  3885 D HeadsetService: Received start request. Starting profile...
08-10 14:15:01.265  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:15:01.267  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:15:01.271  3885  3885 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-10 14:15:01.272  3885  3885 D HeadsetStateMachine: make
,08-10 14:15:01.278  3885  3897 I BluetoothAdapterState: Entering PendingCommandState
,08-10 14:15:01.281  3885  3885 D HeadsetStateMachine: max_hf_connections = 1
,08-10 14:15:01.281  3885  3885 I bt_bluedroid: get_profile_interface handsfree
08-10 14:15:01.281  3885  3901 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-10 14:15:01.281  3885  3901 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-10 14:15:01.286  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
,08-10 14:15:01.287  3885  3885 D A2dpService: Received start request. Starting profile...
,08-10 14:15:01.288  3885  3885 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 14:15:01.288  3885  3885 I bt_bluedroid: get_profile_interface avrcp
,08-10 14:15:01.294  3885  3885 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-10 14:15:01.294  3885  3885 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 14:15:01.294  3885  3885 D A2dpStateMachine: make
,08-10 14:15:01.296  3885  3885 I bt_bluedroid: get_profile_interface a2dp
,08-10 14:15:01.296  3885  3901 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-10 14:15:01.298  3885  3919 D A2dpStateMachine: Enter Disconnected: -2
,08-10 14:15:01.300  3885  3885 I BluetoothHidServiceJni: classInitNative: succeeds
,08-10 14:15:01.301  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
,08-10 14:15:01.302  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 14:15:01.302  3885  3885 D HidService: Received start request. Starting profile...
,08-10 14:15:01.302  3885  3885 I bt_bluedroid: get_profile_interface hidhost
08-10 14:15:01.302  3885  3885 D HidService: setHidService(): set to: null
08-10 14:15:01.302  3885  3901 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb391d3e5
,08-10 14:15:01.302  3885  3901 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-10 14:15:01.303  3885  3885 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-10 14:15:01.304  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
08-10 14:15:01.305  3885  3885 D HealthService: Received start request. Starting profile...
,08-10 14:15:01.306  3885  3885 I bt_bluedroid: get_profile_interface health
,08-10 14:15:01.307  3885  3885 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-10 14:15:01.308  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
,08-10 14:15:01.308  3885  3885 D PanService: Received start request. Starting profile...
,08-10 14:15:01.309  3885  3885 D BluetoothPanServiceJni: initializeNative(L110): pan
08-10 14:15:01.309  3885  3885 I bt_bluedroid: get_profile_interface pan
,08-10 14:15:01.309  3885  3901 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-10 14:15:01.312  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d93cc76
,08-10 14:15:01.313  3885  3885 D BluetoothMapService: Received start request. Starting profile...
,08-10 14:15:01.313  3885  3885 D BluetoothMapService: start()
,08-10 14:15:01.316  3885  3885 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-10 14:15:01.316  3885  3885 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-10 14:15:01.317  3885  3885 D BluetoothMapAppObserver: createReceiver()
,08-10 14:15:01.318  3885  3885 D BluetoothMapAppObserver: initObservers()
,08-10 14:15:01.318  3885  3885 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-10 14:15:01.326  3885  3885 V BluetoothAdapterState: isTurningOff()=false
,08-10 14:15:01.326  3885  3885 V BluetoothAdapterState: isTurningOn()=true
08-10 14:15:01.326  3885  3885 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:15:01.327  3885  3885 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 14:15:01.328  3885  3885 V BluetoothAdapterState: isTurningOff()=false
,08-10 14:15:01.328  3885  3885 V BluetoothAdapterState: isTurningOn()=true
08-10 14:15:01.329  3885  3885 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 14:15:01.329  3885  3885 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:15:01.329  3885  3885 V BluetoothAdapterState: isTurningOff()=false
08-10 14:15:01.329  3885  3885 V BluetoothAdapterState: isTurningOn()=true
08-10 14:15:01.329  3885  3917 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-10 14:15:01.329  3885  3885 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:15:01.329  3885  3885 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 14:15:01.331  3885  3885 V BluetoothAdapterState: isTurningOff()=false
08-10 14:15:01.331  3885  3885 V BluetoothAdapterState: isTurningOn()=true
08-10 14:15:01.331  3885  3885 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:15:01.331  3885  3885 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:15:01.331  3885  3885 V BluetoothAdapterState: isTurningOff()=false
08-10 14:15:01.331  3885  3885 V BluetoothAdapterState: isTurningOn()=true
08-10 14:15:01.331  3885  3885 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 14:15:01.331  3885  3885 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 14:15:01.332  3885  3885 V BluetoothAdapterState: isTurningOff()=false
08-10 14:15:01.332  3885  3885 V BluetoothAdapterState: isTurningOn()=true
08-10 14:15:01.332  3885  3885 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:15:01.332  3885  3885 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 14:15:01.332  3885  3897 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-10 14:15:01.332  3885  3897 D BluetoothAdapterProperties: ScanMode =  20
08-10 14:15:01.332  3885  3897 D BluetoothAdapterProperties: State =  11
08-10 14:15:01.335  3885  3901 D BluetoothAdapterProperties: Scan Mode:21
,08-10 14:15:01.335  3885  3897 D BluetoothAdapterProperties: Setting state to 12
08-10 14:15:01.335  3885  3897 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 14:15:01.336  3885  3901 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 14:15:01.336  3455  3465 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:15:01.337  3885  3897 I BluetoothAdapterState: Entering OnState
08-10 14:15:01.338  3455  3468 D BluetoothMap: onBluetoothStateChange: up=true
08-10 14:15:01.340  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:15:01.340  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:15:01.340  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 14:15:01.340  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:15:01.340  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:15:01.340  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:15:01.340  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:15:01.340  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 14:15:01.341   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 14:15:01.342  1728  1741 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:15:01.343   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:15:01.343  1352  1374 D BluetoothPan: onBluetoothStateChange on: true
08-10 14:15:01.343  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:15:01.345  3885  3885 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 14:15:01.346  3885  3885 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-10 14:15:01.347  3455  3468 D BluetoothPan: onBluetoothStateChange on: true
08-10 14:15:01.348  3885  3885 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 14:15:01.349  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:15:01.349  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:15:01.349  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 14:15:01.349  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:15:01.349  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 14:15:01.349  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:15:01.349  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:15:01.349  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 14:15:01.349  1352  1804 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 14:15:01.350  3455  3465 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 14:15:01.351  3885  3885 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 14:15:01.351  3455  3455 D BluetoothMap: Proxy object connected
08-10 14:15:01.351  3455  3455 D MapProfile: Bluetooth service connected
08-10 14:15:01.352  3455  3455 D BluetoothMap: getConnectedDevices()
08-10 14:15:01.352  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 14:15:01.352  3885  3885 D ObexServerSockets: Succeed to create listening sockets 
08-10 14:15:01.352  3885  3885 D ObexServerSockets0: startAccept()
08-10 14:15:01.352  3885  3885 D ObexServerSockets0: prepareForNewConnect()
08-10 14:15:01.353   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 14:15:01.354  1352  1383 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 14:15:01.355  3885  3885 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-10 14:15:01.355  3885  3885 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-10 14:15:01.356  3885  3924 D ObexServerSockets0: Accepting socket connection...
08-10 14:15:01.356  1352  1374 D BluetoothMap: onBluetoothStateChange: up=true
08-10 14:15:01.358  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 14:15:01.358  1352  1352 D PanProfile: Bluetooth service connected
08-10 14:15:01.358  3455  3455 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 14:15:01.359  3455  3455 D PanProfile: Bluetooth service connected
08-10 14:15:01.359  1352  1352 D BluetoothA2dp: Proxy object connected
08-10 14:15:01.359  3455  3455 D BluetoothA2dp: Proxy object connected
08-10 14:15:01.359  3885  3925 D ObexServerSockets0: Accepting socket connection...
,08-10 14:15:01.361  3455  3468 D BluetoothPbap: onBluetoothStateChange: up=true
,08-10 14:15:01.362  1352  1352 D BluetoothMap: Proxy object connected
08-10 14:15:01.362  1352  1352 D MapProfile: Bluetooth service connected
08-10 14:15:01.362  1352  1352 D BluetoothMap: getConnectedDevices()
,08-10 14:15:01.364   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 14:15:01.365   875   875 D BluetoothA2dp: Proxy object connected
,08-10 14:15:01.365  1352  1383 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 14:15:01.368  1352  1804 D BluetoothPbap: onBluetoothStateChange: up=true
,08-10 14:15:01.368  1352  1352 D BluetoothInputDevice: Proxy object connected
08-10 14:15:01.369  1352  1352 D HidProfile: Bluetooth service connected
,08-10 14:15:01.371  3455  3465 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 14:15:01.373  3455  3455 D BluetoothInputDevice: Proxy object connected
,08-10 14:15:01.373  3455  3455 D HidProfile: Bluetooth service connected
,08-10 14:15:01.375   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-10 14:15:01.376  3885  3885 D BluetoothMapService: onReceive
08-10 14:15:01.377  3885  3885 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-10 14:15:01.377  3885  3885 D BluetoothMapService: STATE_ON
,08-10 14:15:01.378  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:15:01.380  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:15:01.385  3455  3455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 14:15:01.391  3455  3455 D DockEventReceiver: finishStartingService: stopping service
,08-10 14:15:01.392  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 14:15:01.401  3455  3455 D BluetoothPbap: Proxy object connected
,08-10 14:15:01.401  3455  3455 D PbapServerProfile: Bluetooth service connected
08-10 14:15:01.402  3885  3885 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-10 14:15:01.402  1352  1352 D BluetoothPbap: Proxy object connected
,08-10 14:15:01.402  1352  1352 D PbapServerProfile: Bluetooth service connected
08-10 14:15:01.402  3885  3885 D ObexServerSockets0: prepareForNewConnect()
,08-10 14:15:01.412  3885  3931 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 14:15:01.430  3885  3935 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 14:15:01.431  3885  3935 I BtOppRfcommListener: Accept thread started.
,08-10 14:15:01.439   875   875 D BluetoothHeadset: Proxy object connected
08-10 14:15:01.439   875   875 D BluetoothHeadset: Proxy object connected
,08-10 14:15:01.439   875   875 D BluetoothHeadset: Proxy object connected
,08-10 14:15:01.440  1352  1374 D BluetoothHeadset: Proxy object connected
08-10 14:15:01.440  1352  1352 D HeadsetProfile: Bluetooth service connected
08-10 14:15:01.440  3455  3465 D BluetoothHeadset: Proxy object connected
08-10 14:15:01.441  3455  3455 D HeadsetProfile: Bluetooth service connected
08-10 14:15:01.441  1728  2041 D BluetoothHeadset: Proxy object connected
,08-10 14:15:01.442   875   892 D BluetoothHeadset: Proxy object connected
08-10 14:15:01.443  1728  1744 D BluetoothHeadset: Proxy object connected
08-10 14:15:01.444   875   892 D BluetoothHeadset: Proxy object connected
,08-10 14:15:01.452  1352  1383 D BluetoothHeadset: Proxy object connected
,08-10 14:15:01.452  1352  1352 D HeadsetProfile: Bluetooth service connected
,08-10 14:15:01.453   875   892 D BluetoothHeadset: Proxy object connected
,08-10 14:15:02.957  3345  3392 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 14:15:02.958  3345  3392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 14:15:03.364   875  1747 I ActivityManager: Start proc 3939:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,08-10 14:15:03.457  3939  3939 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
,08-10 14:15:03.551  3939  3939 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-10 14:15:03.618  3939  3939 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,08-10 14:15:03.633  3939  3939 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-10 14:15:03.635  3939  3939 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-10 14:15:03.690  3939  3949 D Finsky  : [324] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-10 14:15:03.690   875  1695 I ActivityManager: Killing 3549:com.google.android.youtube/u0a86 (adj 15): empty #17
,08-10 14:15:03.793  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:15:03.793  3939  3973 D Ads     : Skipping gmscore version check
,08-10 14:15:03.804  3939  3939 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,08-10 14:15:03.805  3939  3939 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,08-10 14:15:03.810  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:15:03.815  3939  3973 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-10 14:15:03.817  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:15:03.831  3939  3939 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-10 14:15:03.852  3939  3939 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-10 14:15:03.874  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-10 14:15:03.874  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 14:15:03.875  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 14:15:03.875  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:15:03.896  3939  3949 D Finsky  : [324] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-10 14:15:05.965  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 14:15:05.966  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d944de7 added. We now have 6 listener(s)
08-10 14:15:05.966  3345  3392 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 14:15:05.972  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 14:15:05.973  3345  3392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8bbd94 added. We now have 7 listener(s)
08-10 14:15:05.973  3345  3392 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 14:15:05.977  3345  3392 I System.out: IsBluetoothEnabled
,08-10 14:15:05.991  3885  3897 D BluetoothAdapterState: Current state: ON, message: 23
08-10 14:15:05.991  3885  3897 D BluetoothAdapterProperties: Setting state to 13
08-10 14:15:05.991  3885  3897 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-10 14:15:05.993  3885  3897 D BluetoothAdapterProperties: onBluetoothDisable()
,08-10 14:15:05.997  3885  3897 I BluetoothAdapterState: Entering PendingCommandState
08-10 14:15:06.003  3885  3885 D BluetoothMapService: onReceive
,08-10 14:15:06.003  3885  3885 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-10 14:15:06.003  3885  3885 D BluetoothMapService: STATE_TURNING_OFF
08-10 14:15:06.004  3885  3885 D BluetoothMapService: MAP Service closeService in
08-10 14:15:06.005  3885  3885 D BluetoothMapMasInstance0: MAP Service shutdown
08-10 14:15:06.005  3885  3885 D ObexServerSockets0: shutdown(block = true)
08-10 14:15:06.006  3885  3924 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-10 14:15:06.009  3885  3885 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-10 14:15:06.009  3885  3925 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-10 14:15:06.012  3345  3345 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:15:06.012  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:15:06.012  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:15:06.012  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 14:15:06.012  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:15:06.012  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:15:06.012  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:15:06.012  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:15:06.012  3345  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 14:15:06.013  3885  3912 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-10 14:15:06.013  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:15:06.014  3345  3392 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 14:15:06.014  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 14:15:06.014  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 14:15:06.014  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 14:15:06.014  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 14:15:06.014  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 14:15:06.014  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 14:15:06.014  3345  3392 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 14:15:06.014  3885  3885 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 14:15:06.015  3885  3885 I BtOppRfcommListener: stopping Accept Thread
08-10 14:15:06.016  3345  3345 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:15:06.016  3885  3935 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 14:15:06.016  3345  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:15:06.017  3885  3935 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 14:15:06.019  3345  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 14:15:06.019  3345  3392 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 14:15:06.020  3885  3901 D BluetoothAdapterProperties: Scan Mode:20
,08-10 14:15:06.021  3885  3897 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-10 14:15:06.023  3455  3455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 14:15:06.027  3939  3939 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
08-10 14:15:06.030  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 14:15:06.033  3885  3885 D HeadsetService: Received stop request...Stopping profile...
08-10 14:15:06.037   875   875 D BluetoothHeadset: Proxy object disconnected
,08-10 14:15:06.037   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 14:15:06.038   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 14:15:06.038  1352  1374 D BluetoothHeadset: Proxy object disconnected
08-10 14:15:06.038  3885  3885 D A2dpService: Received stop request...Stopping profile...
08-10 14:15:06.038  1352  1352 D HeadsetProfile: Bluetooth service disconnected
08-10 14:15:06.039  3455  3465 D BluetoothHeadset: Proxy object disconnected
08-10 14:15:06.039  3885  3919 D A2dpStateMachine: Exit Disconnected: -1
08-10 14:15:06.039  1728  2041 D BluetoothHeadset: Proxy object disconnected
,08-10 14:15:06.044   875   875 D BluetoothA2dp: Proxy object disconnected
,08-10 14:15:06.044  1352  1352 D BluetoothA2dp: Proxy object disconnected
08-10 14:15:06.045  3885  3897 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
08-10 14:15:06.045  3885  3897 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
,08-10 14:15:06.045  3885  3885 D HidService: Received stop request...Stopping profile...
08-10 14:15:06.046  3885  3885 D HidService: Stopping Bluetooth HidService
,08-10 14:15:06.050  3455  3455 D DockEventReceiver: finishStartingService: stopping service
,08-10 14:15:06.050  3885  3885 V BluetoothAdapterState: isTurningOff()=true
08-10 14:15:06.050  3885  3885 V BluetoothAdapterState: isTurningOn()=false
08-10 14:15:06.050  3885  3885 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:15:06.050  1352  1352 D BluetoothInputDevice: Proxy object disconnected
08-10 14:15:06.051  3885  3885 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:15:06.051  1352  1352 D HidProfile: Bluetooth service disconnected
08-10 14:15:06.051  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:15:06.051  3885  3885 D HealthService: Received stop request...Stopping profile...
,08-10 14:15:06.053  3455  3455 D HeadsetProfile: Bluetooth service disconnected
,08-10 14:15:06.056  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 14:15:06.057  3885  3885 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-10 14:15:06.057  3885  3885 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-10 14:15:06.058  3885  3901 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-10 14:15:06.058  3885  3908 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 14:15:06.058  3885  3908 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 14:15:06.058  3885  3885 D PanService: Received stop request...Stopping profile...
08-10 14:15:06.058  3455  3455 D BluetoothA2dp: Proxy object disconnected
,08-10 14:15:06.058  3885  3908 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 14:15:06.059  3885  3901 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-10 14:15:06.059  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-10 14:15:06.059  1352  1352 D PanProfile: Bluetooth service disconnected
,08-10 14:15:06.061  3885  3885 V BluetoothAdapterState: isTurningOff()=true
08-10 14:15:06.061  3885  3885 V BluetoothAdapterState: isTurningOn()=false
,08-10 14:15:06.061  3885  3885 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:15:06.061  3455  3455 D BluetoothInputDevice: Proxy object disconnected
08-10 14:15:06.061  3885  3885 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:15:06.061  3455  3455 D HidProfile: Bluetooth service disconnected
,08-10 14:15:06.061  3455  3455 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 14:15:06.061  3455  3455 D PanProfile: Bluetooth service disconnected
08-10 14:15:06.062  3885  3901 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-10 14:15:06.062  3885  3908 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 14:15:06.062  3885  3908 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 14:15:06.063  3885  3908 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-10 14:15:06.063  3885  3908 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 14:15:06.063  3885  3908 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 14:15:06.063  3885  3908 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 14:15:06.063  3885  3885 D BluetoothMapService: Received stop request...Stopping profile...
,08-10 14:15:06.063  3885  3885 D BluetoothMapService: stop()
08-10 14:15:06.066  3885  3885 D BluetoothMapAppObserver: deinitObservers()
08-10 14:15:06.069  3885  3885 D BluetoothMapAppObserver: removeReceiver()
,08-10 14:15:06.071  1352  1352 D BluetoothMap: Proxy object disconnected
,08-10 14:15:06.071  1352  1352 D MapProfile: Bluetooth service disconnected
08-10 14:15:06.071  3885  3885 V BluetoothAdapterState: isTurningOff()=true
08-10 14:15:06.071  3885  3885 V BluetoothAdapterState: isTurningOn()=false
08-10 14:15:06.071  3885  3885 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 14:15:06.071  3885  3885 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:15:06.072  3885  3885 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...,
08-10 14:15:06.072  3885  3901 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 14:15:06.072  3885  3885 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 14:15:06.072  3885  3885 V BluetoothAdapterState: isTurningOff()=true
,08-10 14:15:06.072  3885  3885 V BluetoothAdapterState: isTurningOn()=false
08-10 14:15:06.072  3885  3885 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:15:06.073  3885  3885 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 14:15:06.073  3885  3885 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-10 14:15:06.073  3885  3901 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-10 14:15:06.073  3885  3885 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 14:15:06.075  1352  1352 D BluetoothPbap: Proxy object disconnected
08-10 14:15:06.075  1352  1352 D PbapServerProfile: Bluetooth service disconnected
,08-10 14:15:06.076  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-10 14:15:06.076  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 14:15:06.077  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 14:15:06.077  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 14:15:06.077  3885  3885 V BluetoothAdapterState: isTurningOff()=true
08-10 14:15:06.077  3885  3885 V BluetoothAdapterState: isTurningOn()=false
08-10 14:15:06.077  3885  3885 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 14:15:06.078  3885  3885 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:15:06.078  3885  3885 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-10 14:15:06.078  3885  3885 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-10 14:15:06.082  3885  3885 D BluetoothMapService: MAP Service closeService in
,08-10 14:15:06.082  3885  3885 V BluetoothAdapterState: isTurningOff()=true
08-10 14:15:06.082  3885  3885 V BluetoothAdapterState: isTurningOn()=false,
08-10 14:15:06.082  3885  3885 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 14:15:06.082  3885  3885 V BluetoothAdapterState: isBleTurningOff()=false
08-10 14:15:06.082  3885  3897 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-10 14:15:06.082  3885  3897 D BluetoothAdapterProperties: Setting state to 15
08-10 14:15:06.082  3885  3897 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-10 14:15:06.083  3885  3897 I BluetoothAdapterState: Entering BleOnState
,08-10 14:15:06.083  3885  3897 D BluetoothAdapterState: Current state: BLE ON, message: 0
,08-10 14:15:06.083  3885  3885 D BluetoothMapService: cleanup()
08-10 14:15:06.083  3885  3885 D BluetoothMapService: MAP Service closeService in
,08-10 14:15:06.084  3455  3926 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 14:15:06.085  3455  3468 D BluetoothMap: onBluetoothStateChange: up=false
,08-10 14:15:06.085   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:15:06.085  1728  1744 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 14:15:06.076  3455  3455 D BluetoothMap: Proxy object disconnected
08-10 14:15:06.085  3455  3455 D MapProfile: Bluetooth service disconnected
08-10 14:15:06.085   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 14:15:06.086  3455  3455 D BluetoothPbap: Proxy object disconnected
,08-10 14:15:06.086  3455  3455 D PbapServerProfile: Bluetooth service disconnected
08-10 14:15:06.086  1352  1383 D BluetoothPan: onBluetoothStateChange on: false
08-10 14:15:06.086  3455  3926 D BluetoothPan: onBluetoothStateChange on: false
,08-10 14:15:06.087  1352  1374 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 14:15:06.087  3455  3468 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 14:15:06.088   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 14:15:06.088  1352  1804 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 14:15:06.091  1352  1383 D BluetoothMap: onBluetoothStateChange: up=false
,08-10 14:15:06.094  3455  3465 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 14:15:06.094   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 14:15:06.095  1352  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 14:15:06.095  1352  1804 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 14:15:06.095  3939  3939 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
08-10 14:15:06.096  3455  3926 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-10 14:15:06.097  3885  3897 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-10 14:15:06.097  3885  3897 D BluetoothAdapterProperties: Setting state to 16
08-10 14:15:06.097  3885  3897 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-10 14:15:06.097  3885  3897 D BluetoothAdapterProperties: onBleDisable
08-10 14:15:06.098  3885  3897 I BluetoothAdapterState: Entering PendingCommandState
,08-10 14:15:06.098  3885  3898 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-10 14:15:06.099  3885  3908 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-10 14:15:06.099  3885  3901 D BluetoothAdapterProperties: Scan Mode:20
08-10 14:15:06.099  3885  3908 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 14:15:06.101  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:15:06.105  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:15:06.106  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:15:06.108  3455  3455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 14:15:06.113  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 14:15:06.118  3455  3455 D DockEventReceiver: finishStartingService: stopping service
,08-10 14:15:06.127  1511  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 14:15:06.127  1511  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 14:15:06.127  1511  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:15:06.127  1511  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:15:06.153  3939  3983 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-10 14:15:06.157  3939  3939 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
,08-10 14:15:06.157  3939  3939 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
08-10 14:15:06.157  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:15:06.181  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 14:15:06.181  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 14:15:06.181  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:15:06.181  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:15:06.206  3939  3939 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-10 14:15:06.314  3885  3901 I bt_hci  : shut_down
,08-10 14:15:06.315  3885  3905 D bt_hwcfg: hw_epilog_process
,08-10 14:15:06.326  3885  3905 I bt_vendor: low_power_mode_cb
,08-10 14:15:06.355  3885  3905 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-10 14:15:06.356  3885  3905 I bt_vendor: epilog_cb
08-10 14:15:06.356  3885  3905 I bt_hci  : epilog_finished_callback
,08-10 14:15:06.360  3885  3901 I bt_hci_h4: hal_close
,08-10 14:15:06.362  3885  3901 I bt_userial_vendor: device fd = 51 close
,08-10 14:15:06.368  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:15:06.402  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 14:15:06.402  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-10 14:15:06.402  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 14:15:06.402  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:15:06.423  3939  3939 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-10 14:15:06.425  3939  3939 D Finsky  : [1] WearSupportService.startHygiene: disabled
,08-10 14:15:06.426  3939  3939 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-10 14:15:06.430  3939  3939 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 804 minutes (failures=5)
,08-10 14:15:06.438  3939  3985 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-10 14:15:06.480  3885  3898 D bt_stack_manager: event_shut_down_stack finished.
,08-10 14:15:06.481  3885  3897 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-10 14:15:06.486  3885  3885 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 14:15:06.486  3885  3885 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 14:15:06.486  3885  3897 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-10 14:15:06.486  3885  3885 D BtGatt.GattService: stop()
08-10 14:15:06.486  3885  3885 D BtGatt.AdvertiseManager: advertise clients cleared
08-10 14:15:06.488  3885  3885 V BluetoothAdapterState: isTurningOff()=false
08-10 14:15:06.488  3885  3885 V BluetoothAdapterState: isTurningOn()=false
08-10 14:15:06.488  3885  3885 V BluetoothAdapterState: isBleTurningOn()=false
08-10 14:15:06.488  3885  3885 V BluetoothAdapterState: isBleTurningOff()=true
,08-10 14:15:06.488  3885  3897 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-10 14:15:06.488  3885  3897 D BluetoothAdapterProperties: Setting state to 10
08-10 14:15:06.488  3885  3897 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-10 14:15:06.489  3885  3897 I BluetoothAdapterState: Entering OffState
,08-10 14:15:06.503  3345  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 14:15:06.508  3455  3455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 14:15:06.513  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 14:15:06.517  3455  3455 D DockEventReceiver: finishStartingService: stopping service
,08-10 14:15:07.425   875  1732 I ActivityManager: Killing 3704:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-10 14:15:27.694  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:15:27.704  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:15:27.708  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:15:27.742  1511  1904 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 14:15:27.742  1511  1904 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 14:15:27.742  1511  1904 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:15:27.742  1511  1904 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:15:27.774  3939  3939 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-10 14:15:27.774  3939  3939 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 14:15:27.775  3939  3939 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-10 14:15:29.939  1663  1740 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-10 14:15:29.940  1663  1740 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-10 14:15:29.976  1511  1511 I ConfigService: onCreate
,08-10 14:15:35.045  1511  1511 I ConfigService: onDestroy
,08-10 14:15:54.112   875  1318 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-10 14:16:02.555  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:16:02.563  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:16:02.565  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:16:02.608  1511  2687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 14:16:02.608  1511  2687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 14:16:02.608  1511  2687 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:16:02.609  1511  2687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:16:02.640  3939  3939 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 14:16:02.641  3939  3939 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 14:16:02.641  3939  3939 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-10 14:16:22.953  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:16:22.968  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:16:22.975  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:16:23.060  1511  1904 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 14:16:23.061  1511  1904 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 14:16:23.061  1511  1904 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:16:23.061  1511  1904 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:16:23.078  3939  3939 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 14:16:23.079  3939  3939 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 14:16:23.079  3939  3939 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-10 14:16:43.304  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:16:43.317  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:16:43.323  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:16:43.389  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 14:16:43.389  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 14:16:43.389  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:16:43.389  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:16:43.435  3939  3939 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-10 14:16:43.436  3939  3939 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 14:16:43.436  3939  3939 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-10 14:17:12.691  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:17:12.703  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:17:12.705  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:17:12.768  1511  2687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 14:17:12.768  1511  2687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 14:17:12.769  1511  2687 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:17:12.769  1511  2687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:17:12.828  3939  3939 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-10 14:17:12.828  3939  3939 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 14:17:12.829  3939  3939 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-10 14:17:33.177  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:17:33.185  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:17:33.187  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:17:33.241  1511  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 14:17:33.242  1511  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-10 14:17:33.242  1511  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:17:33.243  1511  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:17:33.289  3939  3939 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 14:17:33.289  3939  3939 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 14:17:33.290  3939  3939 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-10 14:20:03.753  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:20:03.776  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:20:03.785  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:20:03.889  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 14:20:03.890  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 14:20:03.891  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:20:03.891  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:20:03.942  1511  1524 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 14:20:03.942  1511  1524 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 14:20:03.942  1511  1524 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 14:20:03.942  1511  1524 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 14:20:03.942  1511  1524 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 14:20:03.942  1511  1524 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 14:20:03.942  1511  1524 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 14:20:03.956  3939  3968 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 14:20:03.956  3939  3968 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 14:20:03.956  3939  3968 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 14:20:03.956  3939  3968 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 14:20:03.956  3939  3968 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 14:20:03.956  3939  3968 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 14:20:03.956  3939  3968 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 14:25:04.124  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:25:04.137  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:25:04.139  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:25:04.194  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 14:25:04.194  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 14:25:04.195  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 14:25:04.195  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:25:04.225  1511  1524 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 14:25:04.225  1511  1524 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 14:25:04.225  1511  1524 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 14:25:04.225  1511  1524 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 14:25:04.225  1511  1524 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 14:25:04.225  1511  1524 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 14:25:04.225  1511  1524 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 14:25:04.235  3939  3968 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 14:25:04.235  3939  3968 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 14:25:04.235  3939  3968 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 14:25:04.235  3939  3968 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 14:25:04.235  3939  3968 E PlayEventLogger: 	,at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 14:25:04.235  3939  3968 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 14:25:04.235  3939  3968 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 14:29:15.035   875   887 I UsageStatsService: User[0] Flushing usage stats to disk
,08-10 14:30:04.380  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:30:04.405  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:30:04.412  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:30:04.517  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 14:30:04.517  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-10 14:30:04.518  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 14:30:04.518  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:30:04.571  1511  1524 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 14:30:04.571  1511  1524 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 14:30:04.571  1511  1524 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 14:30:04.571  1511  1524 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 14:30:04.571  1511  1524 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 14:30:04.571  1511  1524 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 14:30:04.571  1511  1524 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 14:30:04.586  3939  3968 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 14:30:04.586  3939  3968 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 14:30:04.586  3939  3968 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 14:30:04.586  3939  3968 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 14:30:04.586  3939  3968 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 14:30:04.586  3939  3968 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 14:30:04.586  3939  3968 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 14:35:04.732  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:35:04.747  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:35:04.754  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 14:35:04.836  1511  2687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 14:35:04.837  1511  2687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-10 14:35:04.837  1511  2687 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 14:35:04.838  1511  2687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 14:35:04.875  1511  2687 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 14:35:04.875  1511  2687 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 14:35:04.875  1511  2687 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 14:35:04.875  1511  2687 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 14:35:04.875  1511  2687 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 14:35:04.875  1511  2687 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 14:35:04.875  1511  2687 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 14:35:04.885  3939  3968 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 14:35:04.885  3939  3968 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 14:35:04.885  3939  3968 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 14:35:04.885  3939  3968 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 14:35:04.885  3939  3968 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 14:35:04.885  3939  3968 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 14:35:04.885  3939  3968 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),08-10 14:37:59.982  4068  4068 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 14:37:59.986  4068  4068 D AndroidRuntime: CheckJNI is OFF
08-10 14:38:00.021  4068  4068 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 14:38:00.062  4068  4068 I Radio-JNI: register_android_hardware_Radio DONE
08-10 14:38:00.083  4068  4068 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-10 14:38:00.097   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-10 14:38:00.098   875   888 I ActivityManager: Killing 3345:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-10 14:38:00.191   875  2827 D GraphicsStats: Buffer count: 2
08-10 14:38:00.189   875   885 I WindowState: WIN DEATH: Window{fa5ed91 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 14:38:00.194   875  1305 W Looper  : Ignoring unexpected epoll events 0x11 on fd 135 that is no longer registered.
08-10 14:38:00.198   875  1317 D WifiService: Client connection lost with reason: 4
08-10 14:38:00.219   875   899 W PackageSettings: Skipping PackageSetting{c82202b com.example.hello/10273} due to missing metadata
08-10 14:38:00.256   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-10 14:38:00.256   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-10 14:38:00.257   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-10 14:38:00.257   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-10 14:38:00.257   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 14:38:00.257   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-10 14:38:00.257   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 14:38:00.257   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-10 14:38:00.257   875   888 I ActivityManager:   Force finishing activity ActivityRecord{78e4322 u0 com.test.thalitest/.MainActivity t8}
08-10 14:38:00.263   875   899 I art     : Starting a blocking GC Explicit
08-10 14:38:00.281   875  1770 W ActivityManager: Spurious death for ProcessRecord{932933c 0:com.test.thalitest/u0a0}, curProc for 3345: null
08-10 14:38:00.309   875   899 I art     : Explicit concurrent mark sweep GC freed 39065(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 650us total 46.336ms
08-10 14:38:00.364   875   899 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-10 14:38:00.368  4068  4068 I art     : System.exit called, status: 0
08-10 14:38:00.368  4068  4068 I AndroidRuntime: VM exiting with result code 0.
08-10 14:38:00.408   875   899 I ActivityManager: Start proc 4081:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-10 14:38:00.412   875   899 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-10 14:38:00.442   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-10 14:38:00.457  1663  1663 I Keyboard.Facilitator: resetDictionaries() : en_US
08-10 14:38:00.462  1663  4094 I Keyboard.Facilitator.DecoderInitializer: run()
08-10 14:38:00.465  1841  2030 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-10 14:38:00.472  3191  3191 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-10 14:38:00.473   875  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-10 14:38:00.483  1663  4094 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-10 14:38:00.484  1663  4094 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-10 14:38:00.488  1663  4094 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-10 14:38:00.488  1663  4094 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-10 14:38:00.489  1663  4094 I Decoder : createOrResetDecoder
08-10 14:38:00.524   875  1770 I ActivityManager: Start proc 4098:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-10 14:38:00.529  1728  1728 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-10 14:38:00.532   875  1754 I ActivityManager: Killing 3843:com.qualcomm.timeservice/1000 (adj 15): empty #17
08-10 14:38:00.558   875  1770 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3345 uid 10000
08-10 14:38:00.570  1663  1663 I Keyboard.Facilitator: onFinishInput()
08-10 14:38:00.593   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-10 14:38:00.598   875  1313 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-10 14:38:00.603  1511  1511 I ConfigService: onCreate
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-10 14:38:00.618  1511  4110 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-10 14:38:00.618  1511  4110 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-10 14:38:00.619   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-10 14:38:00.620  1511  4110 W SQLiteOpenHelper: Opened config.db in read-only mode
08-10 14:38:00.620   875   887 E PackageManager: Failed to write settings, restoring backup
08-10 14:38:00.620   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-10 14:38:00.620   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-10 14:38:00.620   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-10 14:38:00.620   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-10 14:38:00.620   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-10 14:38:00.620   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 14:38:00.620   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-10 14:38:00.620   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 14:38:00.624  1748  1840 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-10 14:38:00.625   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-10 14:38:00.625   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-10 14:38:00.625   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 14:38:00.625   875   888 E DropBoxManagerService: 	... 13 more
08-10 14:38:00.629  4098  4098 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-10 14:38:00.639   875   885 I ActivityManager: Start proc 4111:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-10 14:38:00.640  1748  1840 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-10 14:38:00.640  1748  1840 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1748
08-10 14:38:00.640  1748  1840 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 14:38:00.640  1748  1840 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 14:38:00.640  1748  1840 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 14:38:00.640  1748  1840 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 14:38:00.640  1748  1840 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 14:38:00.640  1748  1840 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 14:38:00.640  1748  1840 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-10 14:38:00.640  1748  1840 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-10 14:38:00.640  1748  1840 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 14:38:00.640  1748  1840 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 14:38:00.640  1748  1840 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 14:38:00.640  1748  1840 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 14:38:00.642   875  1747 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 14:38:00.645  1748  1840 I Process : Sending signal. PID: 1748 SIG: 9
08-10 14:38:00.651   875  4117 E DropBoxManagerService: Can't write: system_app_crash
08-10 14:38:00.651   875  4117 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-10 14:38:00.651   875  4117 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 14:38:00.651   875  4117 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 14:38:00.651   875  4117 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 14:38:00.651   875  4117 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 14:38:00.651   875  4117 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 14:38:00.651   875  4117 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 14:38:00.651   875  4117 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 14:38:00.651   875  4117 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 14:38:00.651   875  4117 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 14:38:00.651   875  4117 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 14:38:00.651   875  4117 E DropBoxManagerService: 	... 5 more
08-10 14:38:00.670  1663  4094 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-10 14:38:00.699  1663  4094 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-10 14:38:00.701  1663  4094 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-10 14:38:00.701  1663  4094 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-10 14:38:00.703  1663  4094 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-10 14:38:00.703  1663  4094 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-10 14:38:00.704  1663  4094 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-10 14:38:00.704  1663  4094 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-10 14:38:00.706  1663  4094 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-10 14:38:00.706  1663  4094 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-10 14:38:00.706  1663  4094 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-10 14:38:00.706  1663  4094 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-10 14:38:00.706  1663  4094 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-10 14:38:00.707  1663  4094 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-10 14:38:00.709   875  1695 D GraphicsStats: Buffer count: 1
08-10 14:38:00.710   875  1724 I WindowState: WIN DEATH: Window{e16f08d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-10 14:38:00.715   875  1732 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1748) has died
08-10 14:38:00.716   875  1732 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-10 14:38:00.718   875  1732 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-10 14:38:00.742   875   888 I ActivityManager: Start proc 4129:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 14:38:00.760  4098  4098 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-10 14:38:00.781   875  1754 I ActivityManager: Start proc 4143:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 14:38:00.795  4129  4129 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 14:38:00.795  4129  4129 D AndroidRuntime: Shutting down VM
08-10 14:38:00.799  4098  4142 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-10 14:38:00.804  4129  4129 E AndroidRuntime: FATAL EXCEPTION: main
08-10 14:38:00.804  4129  4129 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4129
08-10 14:38:00.804  4129  4129 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-10 14:38:00.804  4129  4129 E AndroidRuntime: 	... 10 more
08-10 14:38:00.806   875  1695 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 14:38:00.808  4129  4129 I Process : Sending signal. PID: 4129 SIG: 9
08-10 14:38:00.808   875  4156 E DropBoxManagerService: Can't write: system_app_crash
08-10 14:38:00.808   875  4156 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-10 14:38:00.808   875  4156 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 14:38:00.808   875  4156 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 14:38:00.808   875  4156 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 14:38:00.808   875  4156 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 14:38:00.808   875  4156 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 14:38:00.808   875  4156 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 14:38:00.808   875  4156 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 14:38:00.808   875  4156 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 14:38:00.808   875  4156 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 14:38:00.808   875  4156 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 14:38:00.808   875  4156 E DropBoxManagerService: 	... 5 more
08-10 14:38:00.826  1856  4153 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-10 14:38:00.826  1856  4153 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-10 14:38:00.828   875  1732 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4129) has died
08-10 14:38:00.829   875  1732 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-10 14:38:00.837  4143  4143 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-10 14:38:00.844   875   888 I ActivityManager: Start proc 4158:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 14:38:00.846  1856  4153 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-10 14:38:00.847  1856  4153 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-10 14:38:00.865  1511  1511 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-10 14:38:00.866   281   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
