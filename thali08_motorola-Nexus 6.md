#### Test 7968977567f3672_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-04 15:06:37.203  1517  2081 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-04 15:06:37.203  1517  2081 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-04 15:06:37.203  1517  2081 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 15:06:37.203  1517  2081 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-04 15:06:37.218  1517  2081 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-04 15:06:37.218  1517  2081 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-04 15:06:37.218  1517  2081 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-04 15:06:37.218  1517  2081 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-04 15:06:37.218  1517  2081 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-04 15:06:37.218  1517  2081 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-04 15:06:37.218  1517  2081 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
08-04 15:06:37.221  3399  3432 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-04 15:06:37.221  3399  3432 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-04 15:06:37.221  3399  3432 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-04 15:06:37.221  3399  3432 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-04 15:06:37.221  3399  3432 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-04 15:06:37.221  3399  3432 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-04 15:06:37.221  3399  3432 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-04 15:06:38.191  3850  3850 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-04 15:06:38.197  3850  3850 D AndroidRuntime: CheckJNI is OFF
08-04 15:06:38.240  3850  3850 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-04 15:06:38.290  3850  3850 I Radio-JNI: register_android_hardware_Radio DONE
08-04 15:06:38.312  3850  3850 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-04 15:06:38.319   875  3004 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-04 15:06:38.368   875  3004 I ActivityManager: Start proc 3859:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-04 15:06:38.372  3850  3850 D AndroidRuntime: Shutting down VM
08-04 15:06:38.503  3859  3859 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-04 15:06:38.536  3859  3859 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-04 15:06:38.546  3859  3859 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4969-4973)
08-04 15:06:38.546  3859  3859 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 15:06:38.566  3859  3859 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6d02731}
08-04 15:06:38.566  3859  3859 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 15:06:38.567  3859  3859 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 15:06:38.578  3859  3859 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-04 15:06:38.583  3859  3859 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-04 15:06:38.625  3859  3859 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-04 15:06:38.650  3859  3859 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 15:06:38.651  3859  3859 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 15:06:38.651  3859  3859 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-04 15:06:38.651  3859  3859 I Adreno  : Build Date                       : 10/20/15
08-04 15:06:38.651  3859  3859 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-04 15:06:38.651  3859  3859 I Adreno  : Local Branch                     : M14
08-04 15:06:38.651  3859  3859 I Adreno  : Remote Branch                    : 
08-04 15:06:38.651  3859  3859 I Adreno  : Remote Branch                    : 
08-04 15:06:38.651  3859  3859 I Adreno  : Reconstruct Branch               : 
08-04 15:06:38.735   875   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@99b186b:true
08-04 15:06:38.781  3859  3859 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-04 15:06:38.799  3859  3859 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-04 15:06:38.871  3859  3897 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-04 15:06:38.902  3859  3884 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-04 15:06:38.939  3859  3897 I OpenGLRenderer: Initialized EGL, version 1.4
08-04 15:06:39.000  1662  1662 I Keyboard.Facilitator: onFinishInput()
08-04 15:06:39.070   875   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +614ms (total +722ms)
08-04 15:06:39.126  3859  3859 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3859
08-04 15:06:39.305  3859  3859 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-04 15:06:39.467  3859  3900 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1684862672
08-04 15:06:39.475  3859  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 15:06:39.475  3859  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 15:06:39.475  3859  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 15:06:39.475  3859  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 15:06:39.475  3859  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-04 15:06:39.475  3859  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a9fddc added. We now have 1 listener(s)
08-04 15:06:39.481  3859  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-04 15:06:39.481  3859  3900 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 15:06:39.482  3859  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 15:06:39.482  3859  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-04 15:06:39.487  3859  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e346b added. We now have 1 listener(s)
08-04 15:06:39.488  3859  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 15:06:39.496   875  1310 D WifiService: New client listening to asynchronous messages
08-04 15:06:39.499  3859  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 15:06:39.500  3859  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-04 15:06:39.500  3859  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 15:06:39.501  3859  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-04 15:06:39.501  3859  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-04 15:06:39.509  3859  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 15:06:39.510  3859  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-04 15:06:39.520  3859  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-04 15:06:39.521  3859  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 15:06:39.521  3859  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:06:39.521  3859  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:06:39.521  3859  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:06:39.521  3859  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:06:39.521  3859  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:06:39.521  3859  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:06:39.521  3859  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 15:06:39.521  3859  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-04 15:06:39.522  3859  3900 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 15:06:39.526  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:06:39.526  3859  3900 I io.jxcore.node.LifeCycleMonitor: start: OK
08-04 15:06:39.528  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:06:39.560  3859  3859 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-04 15:06:40.558  3859  3907 W jxcore-log: Initializing JXcore engine
,08-04 15:06:40.558  3859  3907 W jxcore-log: JXcore engine is ready
,08-04 15:06:40.594  3907  3907 W Thread-341: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8796 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-04 15:06:40.594  3907  3907 W Thread-341: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11747]" dev="sockfs" ino=11747 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-04 15:06:40.594  3907  3907 W Thread-341: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-04 15:06:40.594  3907  3907 W Thread-341: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27691]" dev="sockfs" ino=27691 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-04 15:06:40.609  3859  3907 W jxcore-log: Starting JXcore engine
,08-04 15:06:40.690  3859  3907 W jxcore-log: Platform android
08-04 15:06:40.690  3859  3907 W jxcore-log: 
,08-04 15:06:40.690  3859  3907 W jxcore-log: Process ARCH arm
08-04 15:06:40.690  3859  3907 W jxcore-log: 
,08-04 15:06:40.913  3859  3907 I jxcore-log: JXcore Cordova bridge is ready!
08-04 15:06:40.913  3859  3907 I jxcore-log: 
,08-04 15:06:40.913  3859  3907 W jxcore-log: JXcore engine is started
,08-04 15:06:40.925  3859  3900 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-04 15:06:40.930  3859  3859 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-04 15:06:56.370  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-04 15:06:56.370  3859  3907 I jxcore-log: 
08-04 15:06:56.372  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-04 15:06:56.372  3859  3907 I jxcore-log: 
,08-04 15:06:56.378  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 15:06:56.378  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:06:56.378  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:06:56.378  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:06:56.378  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:06:56.378  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:06:56.378  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:06:56.378  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 15:06:56.380  3859  3907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 15:06:56.383  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-04 15:06:56.383  3859  3907 I jxcore-log: 
,08-04 15:06:56.385  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-04 15:06:56.385  3859  3907 I jxcore-log: 
,08-04 15:06:56.731  3859  3907 D ExecuteNativeTests: Running unit tests
,08-04 15:06:56.790  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 15:06:56.790  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 added. We now have 2 listener(s)
,08-04 15:06:56.791  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 15:06:56.791  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 15:06:56.792  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 15:06:56.792  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 15:06:56.792  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a added. We now have 2 listener(s)
,08-04 15:06:56.792  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 15:06:56.792  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 15:06:56.796  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 15:06:56.804  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 15:06:56.804  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:06:56.804  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:06:56.804  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:06:56.804  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:06:56.804  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:06:56.804  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:06:56.804  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 15:06:56.805  3859  3907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 15:06:56.805  3859  3907 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 15:06:56.807  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:06:56.811  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:06:56.814  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 15:06:56.815  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 15:06:56.815  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-04 15:06:56.823  3859  3907 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-04 15:06:56.824  3859  3907 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-04 15:06:56.826  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-04 15:06:56.827  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-04 15:06:56.828  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-04 15:06:56.830  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 15:06:56.831  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 15:06:56.831  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:56.832  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:56.833  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:56.833  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 15:06:56.833  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 15:06:56.834  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 removed from the list
08-04 15:06:56.834  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:56.834  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a removed from the list
08-04 15:06:56.834  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:56.835  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 15:06:56.837  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:56.837  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 15:06:56.839  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:56.839  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:56.839  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 15:06:56.839  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:56.841  3859  3907 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-04 15:06:56.841  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:56.841  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:56.841  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:56.842  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:56.842  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:56.842  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:56.842  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:56.842  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 15:06:56.842  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:56.842  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:56.842  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:56.842  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:56.842  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:56.842  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:56.843  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:56.843  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:56.843  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:56.843  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
,08-04 15:06:56.849  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-04 15:06:56.849  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 15:06:56.849  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 15:06:56.849  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-04 15:06:56.849  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 15:06:56.849  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 15:06:56.849  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 15:06:56.849  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 15:06:56.850  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 15:06:56.850  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 15:06:56.850  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 15:06:56.850  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 15:06:56.850  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 15:06:56.850  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 15:06:56.850  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 15:06:56.850  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 15:06:56.850  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 15:06:56.850  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 15:06:56.850  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 15:06:56.850  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 15:06:56.850  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 15:06:56.850  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 15:06:56.851  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 15:06:56.851  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-04 15:06:56.851  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 15:06:56.851  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 15:06:56.851  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 15:06:56.851  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 15:06:56.851  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 15:06:56.851  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 15:06:56.851  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 15:06:56.851  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:56.851  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:56.851  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:56.851  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:56.852  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:56.852  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:56.852  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:56.852  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:56.852  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:56.852  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:56.852  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:56.852  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:56.852  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:56.852  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:56.854  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:56.854  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:56.854  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:56.854  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:56.855  3859  3907 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 15:06:56.856  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 15:06:56.864  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 15:06:56.864  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:06:56.864  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:06:56.864  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:06:56.864  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:06:56.864  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:06:56.864  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:06:56.864  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 15:06:56.868  3859  3907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 15:06:56.868  3859  3907 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 15:06:56.868  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 15:06:56.868  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 15:06:56.870  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:06:56.870  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 15:06:56.870  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 15:06:56.871  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 15:06:56.873  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:06:56.875  3859  3907 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 15:06:56.875  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 15:06:56.882  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 15:06:56.885  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 15:06:56.885  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 15:06:56.889  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-04 15:06:56.896  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-04 15:06:56.896  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 15:06:56.898  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 15:06:56.899  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 15:06:56.902  3859  3907 D BluetoothAdapter: STATE_ON
08-04 15:06:56.907  2339  2351 D BtGatt.GattService: registerClient() - UUID=9b98dcf5-589a-42dd-84f8-730a2941db5c
08-04 15:06:56.908  2339  2357 D BtGatt.GattService: onClientRegistered() - UUID=9b98dcf5-589a-42dd-84f8-730a2941db5c, clientIf=5
08-04 15:06:56.910  3859  3869 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 15:06:56.911  2339  2388 D BtGatt.GattService: start scan with filters
08-04 15:06:56.920  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 15:06:56.920  2339  2360 D BtGatt.ScanManager: handling starting scan
08-04 15:06:56.920  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 15:06:56.920  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 15:06:56.920  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-04 15:06:56.923  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 15:06:56.924  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 15:06:56.924  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 15:06:56.924  2339  2360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
,08-04 15:06:56.925  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 15:06:56.928  3859  3907 I io.jxcore.node.ConnectionHelper: start: OK
,08-04 15:06:56.931  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 15:06:56.931  3859  3907 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-04 15:06:56.932  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:56.932  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-04 15:06:56.932  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:56.932  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 15:06:56.932  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 15:06:56.932  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 15:06:56.932  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-04 15:06:56.932  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 15:06:56.932  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 15:06:56.933  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 15:06:56.933  3859  3907 D BluetoothAdapter: STATE_ON
,08-04 15:06:56.934  2339  2351 D BtGatt.GattService: stopScan() - queue size =1
08-04 15:06:56.936  2339  2388 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 15:06:56.936  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-04 15:06:56.936  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 15:06:56.937  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 15:06:56.937  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 15:06:56.937  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-04 15:06:56.939  2339  2357 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-04 15:06:56.939  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:06:56.939  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 15:06:56.940  2339  2360 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-04 15:06:56.940  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-04 15:06:56.940  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-04 15:06:56.946  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 15:06:56.947  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 15:06:56.948  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 15:06:56.949  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 15:06:56.949  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 15:06:56.949  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 15:06:56.949  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:56.949  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 15:06:56.949  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-04 15:06:56.949  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:56.950  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:56.950  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:56.950  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 15:06:56.950  3859  3907 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 15:06:56.953  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 15:06:56.958  2339  2357 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-04 15:06:56.958  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:06:56.959  2339  2360 D BtGatt.ScanManager: Starting BLE batch scan
,08-04 15:06:56.959  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 15:06:56.959  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:06:56.959  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:06:56.959  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:06:56.959  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:06:56.959  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:06:56.959  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:06:56.959  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 15:06:56.959  2339  2360 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-04 15:06:56.961  3859  3907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 15:06:56.961  3859  3907 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 15:06:56.962  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 15:06:56.962  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 15:06:56.962  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-04 15:06:56.962  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 15:06:56.962  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 15:06:56.968  3859  3907 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-04 15:06:56.969  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:06:56.968  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 15:06:56.973  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:06:56.976  2339  2357 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-04 15:06:56.976  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:06:56.980  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 15:06:56.981  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-04 15:06:56.981  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 15:06:56.987  2339  2357 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-04 15:06:56.987  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:06:56.990  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-04 15:06:56.990  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 15:06:56.990  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-04 15:06:56.991  3859  3907 D BluetoothAdapter: STATE_ON
,08-04 15:06:56.995  2339  2350 D BtGatt.GattService: registerClient() - UUID=4ca2cb58-cb91-4eaf-871e-e7fad7988dba
,08-04 15:06:56.996  2339  2357 D BtGatt.GattService: onClientRegistered() - UUID=4ca2cb58-cb91-4eaf-871e-e7fad7988dba, clientIf=5
,08-04 15:06:56.996  2339  2357 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 15:06:56.996  3859  3870 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 15:06:56.996  2339  2351 D BtGatt.GattService: start scan with filters
08-04 15:06:56.996  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:06:56.997  2339  2360 D BtGatt.ScanManager: stopping BLe Batch
,08-04 15:06:57.000  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-04 15:06:57.000  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-04 15:06:57.000  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 15:06:57.000  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 15:06:57.003  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 15:06:57.003  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 15:06:57.004  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-04 15:06:57.005  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 15:06:57.008  3859  3907 I io.jxcore.node.ConnectionHelper: start: OK
08-04 15:06:57.009  2339  2357 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 15:06:57.009  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:06:57.009  2339  2360 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-04 15:06:57.011  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.011  3859  3907 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-04 15:06:57.012  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-04 15:06:57.012  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-04 15:06:57.012  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.012  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 15:06:57.012  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 15:06:57.012  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 15:06:57.012  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 15:06:57.012  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 15:06:57.012  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 15:06:57.012  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-04 15:06:57.013  3859  3907 D BluetoothAdapter: STATE_ON
08-04 15:06:57.013  2339  2350 D BtGatt.GattService: stopScan() - queue size =0
,08-04 15:06:57.015  2339  2350 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-04 15:06:57.016  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-04 15:06:57.016  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 15:06:57.016  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 15:06:57.016  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 15:06:57.016  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 15:06:57.017  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 15:06:57.017  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 15:06:57.017  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-04 15:06:57.017  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 15:06:57.018  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 15:06:57.020  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 15:06:57.020  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.020  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 15:06:57.021  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 15:06:57.021  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.022  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 15:06:57.022  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.022  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.022  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.023  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.023  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 15:06:57.024  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 15:06:57.024  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 15:06:57.026  2339  2357 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-04 15:06:57.026  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:06:57.030  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.030  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.030  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 15:06:57.030  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.030  2339  2360 D BtGatt.ScanManager: handling starting scan
08-04 15:06:57.031  3859  3907 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-04 15:06:57.033  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 15:06:57.040  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 15:06:57.040  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:06:57.040  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:06:57.040  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:06:57.040  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:06:57.040  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:06:57.040  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:06:57.040  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 15:06:57.042  2339  2357 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 15:06:57.042  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:06:57.042  2339  2360 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-04 15:06:57.043  3859  3907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 15:06:57.044  3859  3907 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 15:06:57.044  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 15:06:57.044  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 15:06:57.044  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 15:06:57.044  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 15:06:57.044  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 15:06:57.047  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:06:57.049  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:06:57.050  2339  2357 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 15:06:57.050  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:06:57.051  3859  3907 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-04 15:06:57.051  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 15:06:57.052  2339  2360 D BtGatt.ScanManager: Starting BLE batch scan
,08-04 15:06:57.052  2339  2360 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-04 15:06:57.060  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 15:06:57.062  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 15:06:57.062  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 15:06:57.063  2339  2357 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 15:06:57.063  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:06:57.067  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-04 15:06:57.067  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 15:06:57.067  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-04 15:06:57.068  3859  3907 D BluetoothAdapter: STATE_ON
08-04 15:06:57.069  2339  2357 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-04 15:06:57.069  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:06:57.070  2339  2351 D BtGatt.GattService: registerClient() - UUID=4f13ee2c-0743-4792-aac0-19ca4f445269
,08-04 15:06:57.071  2339  2357 D BtGatt.GattService: onClientRegistered() - UUID=4f13ee2c-0743-4792-aac0-19ca4f445269, clientIf=5
,08-04 15:06:57.072  3859  3869 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 15:06:57.073  2339  2380 D BtGatt.GattService: start scan with filters
,08-04 15:06:57.077  2339  2357 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-04 15:06:57.078  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:06:57.078  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 15:06:57.078  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 15:06:57.078  2339  2360 D BtGatt.ScanManager: stopping BLe Batch
08-04 15:06:57.078  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 15:06:57.078  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 15:06:57.082  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 15:06:57.082  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 15:06:57.083  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-04 15:06:57.085  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 15:06:57.085  2339  2357 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 15:06:57.085  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:06:57.086  2339  2360 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-04 15:06:57.087  3859  3907 I io.jxcore.node.ConnectionHelper: start: OK
08-04 15:06:57.087  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 15:06:57.088  3859  3907 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-04 15:06:57.088  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.088  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-04 15:06:57.088  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.088  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-04 15:06:57.088  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-04 15:06:57.088  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 15:06:57.088  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 15:06:57.088  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 15:06:57.088  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 15:06:57.089  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 15:06:57.089  3859  3907 D BluetoothAdapter: STATE_ON
,08-04 15:06:57.090  2339  2380 D BtGatt.GattService: stopScan() - queue size =0
08-04 15:06:57.091  2339  2388 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-04 15:06:57.091  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 15:06:57.091  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 15:06:57.091  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 15:06:57.091  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 15:06:57.091  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-04 15:06:57.093  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 15:06:57.093  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 15:06:57.093  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 15:06:57.093  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 15:06:57.093  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 15:06:57.094  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 15:06:57.094  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 15:06:57.095  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 15:06:57.095  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.095  3859  3907 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-04 15:06:57.095  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 15:06:57.095  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.096  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 15:06:57.096  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.096  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 15:06:57.096  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.096  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.096  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.096  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.096  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.096  2339  2357 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 15:06:57.097  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:06:57.097  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.097  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.098  2339  2360 D BtGatt.ScanManager: handling starting scan
,08-04 15:06:57.098  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.098  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.098  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.098  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.099  3859  3907 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-04 15:06:57.100  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.100  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.100  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.100  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.100  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.100  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.100  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.100  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.100  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.100  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.101  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.101  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.101  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 15:06:57.101  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.102  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.102  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.102  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.102  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
,08-04 15:06:57.103  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 15:06:57.103  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.104  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.104  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.104  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.104  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.104  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.104  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.104  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.104  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.104  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.104  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.104  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.105  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.105  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.106  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.106  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.106  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.106  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
,08-04 15:06:57.107  3859  3907 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-04 15:06:57.107  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.107  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.107  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.107  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 15:06:57.108  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.108  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.108  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.108  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 15:06:57.108  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.108  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.108  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.108  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.108  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 15:06:57.108  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.110  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.110  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.110  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.110  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
,08-04 15:06:57.110  2339  2357 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 15:06:57.110  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:06:57.111  2339  2360 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-04 15:06:57.111  3859  3907 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-04 15:06:57.111  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.111  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.111  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.111  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 15:06:57.111  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.112  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.112  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.112  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.112  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.112  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 15:06:57.112  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.112  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.112  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.112  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.113  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.113  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.113  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 15:06:57.113  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.114  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 15:06:57.115  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-04 15:06:57.116  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 15:06:57.116  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 15:06:57.116  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 15:06:57.116  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-04 15:06:57.116  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.116  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.116  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.116  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 15:06:57.116  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.117  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.117  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.117  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.117  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
,08-04 15:06:57.117  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.117  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.117  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.117  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 15:06:57.117  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.118  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.118  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 15:06:57.118  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 15:06:57.118  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.119  3859  3907 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 15:06:57.119  3859  3907 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 15:06:57.119  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-04 15:06:57.120  2339  2357 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 15:06:57.120  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:06:57.121  2339  2360 D BtGatt.ScanManager: Starting BLE batch scan
08-04 15:06:57.121  2339  2360 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-04 15:06:57.124  3859  3907 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 15:06:57.124  3859  3907 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-04 15:06:57.124  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 15:06:57.124  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 15:06:57.124  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-04 15:06:57.124  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 15:06:57.124  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 15:06:57.124  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 15:06:57.125  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 15:06:57.125  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 15:06:57.125  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-04 15:06:57.125  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 15:06:57.125  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-04 15:06:57.125  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-04 15:06:57.125  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 15:06:57.125  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 15:06:57.125  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 15:06:57.125  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-04 15:06:57.125  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 15:06:57.125  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 15:06:57.125  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 15:06:57.125  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-04 15:06:57.126  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 15:06:57.126  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 15:06:57.126  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 15:06:57.126  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 15:06:57.126  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 15:06:57.126  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 15:06:57.126  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 15:06:57.126  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 15:06:57.126  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 15:06:57.126  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 15:06:57.126  3859  3907 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-04 15:06:57.127  3859  3907 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 15:06:57.127  3859  3907 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-04 15:06:57.127  3859  3907 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 15:06:57.127  3859  3907 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 15:06:57.127  3859  3907 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-04 15:06:57.127  3859  3907 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 15:06:57.127  3859  3907 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 15:06:57.127  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-04 15:06:57.131  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-04 15:06:57.131  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-04 15:06:57.131  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-04 15:06:57.132  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-04 15:06:57.132  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-04 15:06:57.132  3859  3907 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-04 15:06:57.132  3859  3907 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 15:06:57.133  3859  3907 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-04 15:06:57.133  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.133  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.134  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.134  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.134  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.134  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.134  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-04 15:06:57.135  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.135  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.135  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.135  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.135  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.135  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.135  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.135  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.136  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.136  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.136  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.136  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.137  3859  3907 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-04 15:06:57.138  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.138  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.138  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.139  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.139  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.139  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.140  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.140  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.140  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.140  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.140  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.140  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.140  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.140  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.141  3859  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 405
08-04 15:06:57.141  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.141  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.141  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.141  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.141  3859  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 405)
08-04 15:06:57.142  3859  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 405)
08-04 15:06:57.142  2339  2357 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 15:06:57.142  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:06:57.143  3859  3907 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-04 15:06:57.143  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.143  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.143  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.143  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.143  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.143  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.143  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.143  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.144  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.144  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.144  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.144  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.144  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.144  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.145  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.145  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.145  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.145  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.145  3859  3907 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-04 15:06:57.146  3859  3907 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-04 15:06:57.146  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 15:06:57.146  3859  3907 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-04 15:06:57.146  3859  3907 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 15:06:57.146  3859  3907 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-04 15:06:57.146  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 15:06:57.146  3859  3907 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-04 15:06:57.146  3859  3907 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 15:06:57.146  3859  3907 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 15:06:57.146  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 15:06:57.146  3859  3907 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-04 15:06:57.146  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.147  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.147  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.147  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.147  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.147  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.147  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.147  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.147  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.147  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.147  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.147  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.147  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 15:06:57.147  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.148  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.148  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.148  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.149  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.149  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.149  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.149  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.149  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.150  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.150  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.150  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.150  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.150  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.150  2339  2357 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 15:06:57.150  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:06:57.151  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.151  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.151  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.151  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.151  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.151  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.151  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.151  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.151  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.151  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.151  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.151  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.151  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.152  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.152  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.152  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.152  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.152  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.152  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.152  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.153  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.153  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.153  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.153  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.154  3859  3907 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-04 15:06:57.154  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 15:06:57.155  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-04 15:06:57.156  3859  3907 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-04 15:06:57.156  3859  3907 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-04 15:06:57.156  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-04 15:06:57.157  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-04 15:06:57.157  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 15:06:57.157  2339  2357 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 15:06:57.157  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.157  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:06:57.157  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-04 15:06:57.157  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-04 15:06:57.157  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-04 15:06:57.157  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.157  2339  2360 D BtGatt.ScanManager: stopping BLe Batch
08-04 15:06:57.157  3859  3907 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-04 15:06:57.158  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-04 15:06:57.158  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.158  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.158  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 15:06:57.158  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 15:06:57.158  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 15:06:57.158  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.158  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.159  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 15:06:57.159  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-04 15:06:57.159  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 15:06:57.160  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-04 15:06:57.160  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 15:06:57.160  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 15:06:57.160  3859  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-04 15:06:57.160  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.160  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.160  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.160  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.160  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.161  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.161  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.161  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.161  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.161  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.161  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.161  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.161  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.161  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.161  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.162  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.162  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.162  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.162  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.163  2339  2357 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 15:06:57.163  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:06:57.164  2339  2360 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 15:06:57.164  3859  3907 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-04 15:06:57.164  3859  3907 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 15:06:57.164  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 15:06:57.164  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 15:06:57.165  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.165  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.165  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.165  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.165  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.165  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.165  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.165  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.165  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.165  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.165  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.165  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.165  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.166  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.166  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.166  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.166  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.166  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.169  2339  2357 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 15:06:57.169  2339  2357 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:06:57.171  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.171  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.171  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.172  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.172  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.172  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.172  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.172  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.172  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.172  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.172  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.172  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.172  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.172  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.173  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.173  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.173  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.173  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.174  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:06:57.174  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:06:57.174  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:06:57.175  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:06:57.175  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.175  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.175  3859  3907 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b14afa5 not in the list
08-04 15:06:57.175  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.175  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.175  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:06:57.175  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.175  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.175  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:06:57.175  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:06:57.176  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:06:57.176  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:06:57.176  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:06:57.176  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f13f7a not in the list
08-04 15:06:57.177  3859  3907 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-04 15:06:57.177  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 15:06:57.177  3859  3907 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-04 15:06:57.178  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 15:06:57.178  3859  3907 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-04 15:06:57.178  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 15:06:57.180  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 15:06:57.180  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-04 15:06:57.180  3859  3907 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-04 15:06:57.180  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 15:06:57.180  3859  3907 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-04 15:06:57.180  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 15:06:57.181  3859  3907 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-04 15:06:57.181  3859  3907 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-04 15:06:57.182  3859  3907 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-04 15:06:57.182  3859  3907 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-04 15:06:57.183  3859  3907 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-04 15:06:57.183  3859  3907 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-04 15:06:57.183  3859  3907 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-04 15:06:57.183  3859  3907 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-04 15:06:57.184  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 15:06:57.184  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11971cc added. We now have 2 listener(s)
08-04 15:06:57.184  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 15:06:57.186  3859  3907 D BluetoothAdapter: enable(): BT is already enabled..!
08-04 15:06:57.187   875  1746 D WifiService: setWifiEnabled: true pid=3859, uid=10000
08-04 15:06:57.187   875  1746 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-04 15:06:57.187  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 15:06:57.188  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@849cc15 added. We now have 3 listener(s)
08-04 15:06:57.188  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 15:06:57.200  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 15:06:57.201  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d87b2a added. We now have 4 listener(s)
08-04 15:06:57.201  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 15:06:57.202  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 15:06:57.202  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e2f6d1b added. We now have 5 listener(s)
08-04 15:06:57.202  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 15:06:57.204   875  2997 D WifiService: setWifiEnabled: false pid=3859, uid=10000
08-04 15:06:57.204   875  2997 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-04 15:06:57.208  2339  2353 D BluetoothAdapterState: Current state: ON, message: 23
08-04 15:06:57.208  2339  2353 D BluetoothAdapterProperties: Setting state to 13
08-04 15:06:57.208  2339  2353 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 15:06:57.208  2339  2353 D BluetoothAdapterProperties: onBluetoothDisable()
08-04 15:06:57.209  2339  2353 I BluetoothAdapterState: Entering PendingCommandState
08-04 15:06:57.210  2339  2357 D BluetoothAdapterProperties: Scan Mode:20
08-04 15:06:57.210  2339  2353 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-04 15:06:57.211  2339  2339 D BluetoothMapService: onReceive
,08-04 15:06:57.211  2339  2339 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 15:06:57.211  2339  2339 D BluetoothMapService: STATE_TURNING_OFF
08-04 15:06:57.211  2339  2339 D BluetoothMapService: MAP Service closeService in
08-04 15:06:57.211  2339  2339 D BluetoothMapMasInstance0: MAP Service shutdown
08-04 15:06:57.211  2339  2339 D ObexServerSockets0: shutdown(block = true)
08-04 15:06:57.212  2339  2339 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-04 15:06:57.212  2339  2390 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-04 15:06:57.212  2339  2377 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-04 15:06:57.212  2339  2339 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-04 15:06:57.213  2339  2389 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-04 15:06:57.213  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 15:06:57.213  2339  2339 I BtOppRfcommListener: stopping Accept Thread
08-04 15:06:57.213  2339  3271 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 15:06:57.213  2339  3271 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-04 15:06:57.217  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:06:57.217  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 15:06:57.217  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:06:57.217  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:06:57.217  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:06:57.217  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:06:57.217  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:06:57.217  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:06:57.217  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 15:06:57.218  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 15:06:57.218  3859  3907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 15:06:57.218  3859  3907 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 15:06:57.219  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 15:06:57.221  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:06:57.221   875  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-04 15:06:57.221   875  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-04 15:06:57.221   875  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 15:06:57.221   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 15:06:57.223  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:06:57.223   875   889 I ActivityManager: Start proc 3913:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-04 15:06:57.226  2339  2339 D HeadsetService: Received stop request...Stopping profile...
08-04 15:06:57.226   875  1309 E native  : do suspend true
08-04 15:06:57.227  1381  1394 D BluetoothHeadset: Proxy object disconnected
08-04 15:06:57.228  1740  1761 D BluetoothHeadset: Proxy object disconnected
08-04 15:06:57.228   875   875 D BluetoothHeadset: Proxy object disconnected
,08-04 15:06:57.228   875   875 D BluetoothHeadset: Proxy object disconnected
08-04 15:06:57.228   875   875 D BluetoothHeadset: Proxy object disconnected
08-04 15:06:57.229  2339  2339 D A2dpService: Received stop request...Stopping profile...
08-04 15:06:57.229  2339  2383 D A2dpStateMachine: Exit Disconnected: -1
,08-04 15:06:57.230  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:06:57.230  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:06:57.230  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:06:57.230  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:06:57.230  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:06:57.230  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:06:57.230  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:06:57.230  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:06:57.230  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 15:06:57.230   875   875 D BluetoothA2dp: Proxy object disconnected
08-04 15:06:57.230  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:06:57.231  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 15:06:57.231  2339  2339 V BluetoothAdapterState: isTurningOff()=true
08-04 15:06:57.231  2339  2339 V BluetoothAdapterState: isTurningOn()=false
,08-04 15:06:57.231  2339  2339 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:06:57.231  2339  2339 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:06:57.233  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:06:57.234  2339  2339 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 15:06:57.234  2339  2339 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 15:06:57.234  2339  2357 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-04 15:06:57.234  2339  2373 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 15:06:57.234  2339  2373 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 15:06:57.234  2339  2373 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 15:06:57.235  2339  2357 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-04 15:06:57.235  2339  2339 D HidService: Received stop request...Stopping profile...
,08-04 15:06:57.235  2339  2339 D HidService: Stopping Bluetooth HidService
08-04 15:06:57.237  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:06:57.237  1381  1381 D HeadsetProfile: Bluetooth service disconnected
08-04 15:06:57.238  1381  1381 D BluetoothA2dp: Proxy object disconnected
,08-04 15:06:57.238  1381  1381 D BluetoothInputDevice: Proxy object disconnected
08-04 15:06:57.238  1381  1381 D HidProfile: Bluetooth service disconnected
08-04 15:06:57.237  2339  2339 D HealthService: Received stop request...Stopping profile...
08-04 15:06:57.239  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:06:57.240   875  1961 D DhcpClient: Clearing IP address
,08-04 15:06:57.240  2339  2339 D PanService: Received stop request...Stopping profile...
08-04 15:06:57.241   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-04 15:06:57.243  1381  1381 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 15:06:57.243  1381  1381 D PanProfile: Bluetooth service disconnected
08-04 15:06:57.243  2339  2339 D BluetoothMapService: Received stop request...Stopping profile...
08-04 15:06:57.243  2339  2339 D BluetoothMapService: stop()
08-04 15:06:57.243  2339  2339 D BluetoothMapAppObserver: deinitObservers()
08-04 15:06:57.243  2339  2339 D BluetoothMapAppObserver: removeReceiver()
08-04 15:06:57.244  1381  1381 D BluetoothMap: Proxy object disconnected
,08-04 15:06:57.244  1381  1381 D MapProfile: Bluetooth service disconnected
,08-04 15:06:57.245  2339  2339 V BluetoothAdapterState: isTurningOff()=true
08-04 15:06:57.245  2339  2339 V BluetoothAdapterState: isTurningOn()=false
08-04 15:06:57.245  2339  2339 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:06:57.245  2339  2339 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:06:57.245   373   873 D CommandListener: Setting iface cfg
08-04 15:06:57.246  2339  2339 V BluetoothAdapterState: isTurningOff()=true
,08-04 15:06:57.246  2339  2339 V BluetoothAdapterState: isTurningOn()=false
08-04 15:06:57.246  2339  2339 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:06:57.246  2339  2339 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:06:57.246  2339  2339 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 15:06:57.246  2339  2339 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 15:06:57.246  2339  2339 V BluetoothAdapterState: isTurningOff()=true
08-04 15:06:57.246  2339  2339 V BluetoothAdapterState: isTurningOn()=false
08-04 15:06:57.246  2339  2339 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:06:57.246  2339  2339 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 15:06:57.246  1517  2308 V NativeCrypto: Read error: ssl=0x9b672400: I/O error during system call, Connection timed out
,08-04 15:06:57.247  2339  2357 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 15:06:57.247  2339  2373 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 15:06:57.247  2339  2357 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 15:06:57.247  2339  2373 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 15:06:57.247  2339  2373 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 15:06:57.247  2339  2373 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-04 15:06:57.247  2339  2373 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 15:06:57.247   875  1964 D DhcpClient: Receive thread stopped
08-04 15:06:57.246  2339  2339 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 15:06:57.247  2339  2357 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-04 15:06:57.247  2339  2373 W bt_l2cap: btif_in_execute_service_request: Unknown service
08-04 15:06:57.248  2339  2339 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 15:06:57.249  2339  2339 V BluetoothAdapterState: isTurningOff()=true
08-04 15:06:57.249  2339  2339 V BluetoothAdapterState: isTurningOn()=false
08-04 15:06:57.249  2339  2339 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:06:57.249  2339  2339 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 15:06:57.249  2339  2339 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 15:06:57.250  2339  2339 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-04 15:06:57.250   875  1309 D WifiStateMachine: Start Disconnecting Watchdog 1
08-04 15:06:57.250   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-04 15:06:57.250   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-04 15:06:57.251   875  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 15:06:57.251   875  1309 E native  : do suspend true
08-04 15:06:57.252  2339  2339 D BluetoothMapService: MAP Service closeService in
08-04 15:06:57.252  2339  2339 V BluetoothAdapterState: isTurningOff()=true
08-04 15:06:57.252  2339  2339 V BluetoothAdapterState: isTurningOn()=false
,08-04 15:06:57.252  2339  2339 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:06:57.252  2339  2339 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:06:57.252  2339  2353 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-04 15:06:57.252  2339  2353 D BluetoothAdapterProperties: Setting state to 15
08-04 15:06:57.252  2339  2353 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-04 15:06:57.253  2339  2353 I BluetoothAdapterState: Entering BleOnState
08-04 15:06:57.253  2339  2339 D BluetoothMapService: cleanup()
08-04 15:06:57.253  2339  2339 D BluetoothMapService: MAP Service closeService in
08-04 15:06:57.254  1381  1765 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-04 15:06:57.254   875   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 15:06:57.254  1381  1765 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 15:06:57.254  1740  1934 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 15:06:57.255  1381  1394 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 15:06:57.256   403   403 E Parcel  : Reading a NULL string not supported here.
,08-04 15:06:57.257  1381  1765 D BluetoothPan: onBluetoothStateChange on: false
,08-04 15:06:57.258   875   893 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 15:06:57.258   875   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 15:06:57.258  1381  1395 D BluetoothMap: onBluetoothStateChange: up=false
08-04 15:06:57.258   875   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 15:06:57.259  1381  1394 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 15:06:57.260  2339  2353 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-04 15:06:57.260  2339  2353 D BluetoothAdapterProperties: Setting state to 16
08-04 15:06:57.260  2339  2353 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-04 15:06:57.261  2339  2353 D BluetoothAdapterProperties: onBleDisable
,08-04 15:06:57.262  2339  2354 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-04 15:06:57.262  2339  2353 I BluetoothAdapterState: Entering PendingCommandState
08-04 15:06:57.262  2339  2373 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-04 15:06:57.262  2339  2373 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 15:06:57.263  2339  2357 D BluetoothAdapterProperties: Scan Mode:20
08-04 15:06:57.270   875  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-04 15:06:57.271  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:06:57.271  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:06:57.271  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:06:57.271  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:06:57.271  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:06:57.271  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:06:57.271  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:06:57.271  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:06:57.271  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 15:06:57.271  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:06:57.271  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 15:06:57.271   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-04 15:06:57.273   875  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 15:06:57.273  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:06:57.273  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:06:57.273  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:06:57.273  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:06:57.273  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:06:57.273  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:06:57.273  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:06:57.273  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:06:57.273  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 15:06:57.274  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:06:57.274  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 15:06:57.275  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:06:57.276  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:06:57.277  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:06:57.277  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:06:57.277  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:06:57.277  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:06:57.277  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:06:57.277  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:06:57.277  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:06:57.277  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 15:06:57.289   875  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 15:06:57.293   875  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-04 15:06:57.294  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:06:57.294  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:06:57.294  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:06:57.294  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:06:57.294  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 15:06:57.294  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:06:57.294  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:06:57.294  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:06:57.294  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 15:06:57.294  1970  2125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 15:06:57.295  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:06:57.295  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 15:06:57.296   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-04 15:06:57.297  1517  2308 V NativeCrypto: SSL shutdown failed: ssl=0x9b672400: I/O error during system call, Broken pipe
08-04 15:06:57.297  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:06:57.297  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:06:57.297  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:06:57.297  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:06:57.297  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 15:06:57.297  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:06:57.297  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:06:57.297  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:06:57.297  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 15:06:57.298  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:06:57.298  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 15:06:57.316  3913  3913 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-04 15:06:57.323   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 15:06:57.324   875  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-04 15:06:57.325   875  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 15:06:57.327   875   893 D Tethering: MasterInitialState.processMessage what=3
,08-04 15:06:57.331  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:06:57.331  3294  3294 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ce24ee5 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-04 15:06:57.334  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:06:57.339  3913  3913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 15:06:57.344   875   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3868f04:true
,08-04 15:06:57.345  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 15:06:57.358   875  2997 I ActivityManager: Start proc 3931:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-04 15:06:57.365  3913  3913 D LocalBluetoothProfileManager: Adding local MAP profile
,08-04 15:06:57.369  3913  3913 D BluetoothMap: Create BluetoothMap proxy object
,08-04 15:06:57.373  3913  3913 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-04 15:06:57.379  3913  3913 D DockEventReceiver: finishStartingService: stopping service
,08-04 15:06:57.384   875  3004 I ActivityManager: Killing 3294:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-04 15:06:57.392   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-04 15:06:57.400  3931  3931 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-04 15:06:57.465  2339  2357 I bt_hci  : shut_down
,08-04 15:06:57.465  2339  2362 D bt_hwcfg: hw_epilog_process
08-04 15:06:57.466  2339  2362 I bt_vendor: low_power_mode_cb
,08-04 15:06:57.488  2339  2362 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-04 15:06:57.488  2339  2362 I bt_vendor: epilog_cb
08-04 15:06:57.488  2339  2362 I bt_hci  : epilog_finished_callback
,08-04 15:06:57.491  2339  2357 I bt_hci_h4: hal_close
,08-04 15:06:57.491  2339  2357 I bt_userial_vendor: device fd = 51 close
,08-04 15:06:57.599  3931  3931 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013),
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 15:06:57.599  3931  3931 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 15:06:57.599  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 15:06:57.600  3931  3931 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 15:06:57.600  ,3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 15:06:57.600  3931  3931 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.r.e.b(PG:170)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:869,3)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 15:06:57.600  3931  3931 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.r.k.d(PG:583)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.r.e.b(PG:170)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 15:06:57.600  3931  3931 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 15:06:57.600  3931  3931 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 15:06:57.600  3931  3931 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 15:06:57.600  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 15:06:57.605  3913  3913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 15:06:57.616  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 15:06:57.619  3913  3913 D DockEventReceiver: finishStartingService: stopping service
08-04 15:06:57.641  2339  2354 D bt_stack_manager: event_shut_down_stack finished.
08-04 15:06:57.641  2339  2353 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-04 15:06:57.642  2339  2353 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-04 15:06:57.643  2339  2339 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 15:06:57.644  2339  2339 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 15:06:57.644  2339  2339 D BtGatt.GattService: stop()
08-04 15:06:57.645  2339  2339 D BtGatt.AdvertiseManager: advertise clients cleared
08-04 15:06:57.657   875  1707 I ActivityManager: Start proc 3964:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-04 15:06:57.659  2339  2339 V BluetoothAdapterState: isTurningOff()=false
08-04 15:06:57.659  2339  2339 V BluetoothAdapterState: isTurningOn()=false
08-04 15:06:57.659  2339  2339 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:06:57.659  2339  2339 V BluetoothAdapterState: isBleTurningOff()=true
08-04 15:06:57.659   875  1745 I ActivityManager: Killing 3336:com.android.providers.calendar/u0a3 (adj 15): empty #17
08-04 15:06:57.660  2339  2353 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-04 15:06:57.660  2339  2353 D BluetoothAdapterProperties: Setting state to 10
08-04 15:06:57.660  2339  2353 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-04 15:06:57.660  2339  2353 I BluetoothAdapterState: Entering OffState
08-04 15:06:57.660  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-04 15:06:57.660   875   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-04 15:06:57.739  2339  2339 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-04 15:06:57.739  2339  2339 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-04 15:06:57.742  2339  2339 I BluetoothServiceJni: cleanupNative: return from cleanup
08-04 15:06:57.742  2339  2354 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-04 15:06:57.743  2339  2354 D bt_stack_manager: event_clean_up_stack finished.
,08-04 15:06:57.745  2339  2339 I art     : System.exit called, status: 0
,08-04 15:06:57.745  2339  2339 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 15:06:57.824  3964  3964 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-04 15:06:57.826   875  1739 I ActivityManager: Process com.android.bluetooth (pid 2339) has died
,08-04 15:06:58.033  3964  3985 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-04 15:06:58.034  3964  3985 I Babel_SMS: MmsConfig.loadMmsSettings
,08-04 15:06:58.036  3964  3985 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-04 15:06:58.036  3964  3985 I Babel_SMS: MmsConfig.loadFromDatabase
,08-04 15:06:58.077  3964  3985 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-04 15:06:58.077  3964  3985 I Babel_SMS: MmsConfig.loadFromResources
,08-04 15:06:58.079  3964  3985 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-04 15:06:58.080  3964  3985 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-04 15:06:58.100  3931  3953 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-04 15:06:58.173  3964  3964 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 15:06:58.183  3964  3964 I Babel_Crash: startup - clean
,08-04 15:06:58.221  3964  3964 I Babel_telephony: TeleModule.launchCompleted
,08-04 15:06:58.235   875   886 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-04 15:06:58.242  3964  3964 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-04 15:06:58.249  3964  3964 W Babel   : BAM#gBA: invalid account id: -1
,08-04 15:06:58.249  3964  3964 W Babel   : BAM#gBA: invalid account id: -1
08-04 15:06:58.250  3964  3964 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-04 15:06:58.255  3964  3990 I Babel   : deleted: false for 0
,08-04 15:06:58.259   875   885 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-04 15:06:58.292  1982  1982 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 15:06:58.307  1982  1982 D SystemUpdateService: onCreate
,08-04 15:06:58.330  1982  1982 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 15:06:58.345  1982  1982 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-04 15:06:58.351   875   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c5fa9e7:true
,08-04 15:06:58.352  1982  1982 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 15:06:58.354  1982  1982 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 15:06:58.355  1982  2413 I iu.UploadsManager: num queued entries: 0
,08-04 15:06:58.357  1982  3992 I SystemUpdateService: active receiver: enabled
,08-04 15:06:58.360  1982  3992 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 15:06:58.360  1982  2413 I iu.UploadsManager: num updated entries: 0
,08-04 15:06:58.362  1982  3992 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-04 15:06:58.362  1982  3992 I SystemUpdateService: now status is 0 (complete)
08-04 15:06:58.362  1982  3992 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 15:06:58.362  1982  3992 I SystemUpdateService: file has been verified
08-04 15:06:58.362  1982  3992 I SystemUpdateService: OTA package size = 12249756
,08-04 15:06:58.363  1982  2413 I iu.SyncManager: NEXT; no task
,08-04 15:06:58.367  1982  3992 I SystemUpdateService: showing system update notification
,08-04 15:06:58.372   875  1746 I ActivityManager: Start proc 3994:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-04 15:06:58.387  1982  1982 D SystemUpdateService: onDestroy
,08-04 15:06:58.407  3994  3994 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-04 15:06:58.411  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 15:06:58.420  3964  3964 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 15:06:58.427  3994  3994 D SprintDMHelper: simOperator: 
,08-04 15:06:58.427  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 15:06:58.452   875  1366 I ActivityManager: Start proc 4006:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-04 15:06:58.484  3964  3964 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-04 15:06:58.503  3964  3964 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 15:06:58.504  3964  3964 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 15:06:58.520  3964  3964 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 15:06:58.534  3964  3964 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 15:06:58.545   875   886 I ActivityManager: Killing 1696:android.process.acore/u0a5 (adj 15): empty #17
,08-04 15:06:58.608  3964  3964 I vclib   : onServiceConnected
,08-04 15:06:58.663   875  1366 I ActivityManager: Start proc 4021:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-04 15:06:58.667  3964  4020 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-04 15:06:58.673   875  1749 I ActivityManager: Killing 3544:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-04 15:06:58.734  4021  4021 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-04 15:06:58.779  4021  4021 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-04 15:06:58.779  4021  4021 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-04 15:06:58.779  4021  4021 I GAv4    :   adb logcat -s GAv4
,08-04 15:06:58.793  4021  4021 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-04 15:06:58.799  4021  4021 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-04 15:06:58.827  4021  4038 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-04 15:06:58.924  4021  4021 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-04 15:06:58.963  4021  4021 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-04 15:06:58.971  4021  4021 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5395-5398)
,08-04 15:06:58.971  4021  4021 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 15:06:58.984  4021  4021 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {15dbb55}
08-04 15:06:58.984  4021  4021 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 15:06:58.984  4021  4021 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-04 15:06:58.991  4021  4021 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-04 15:06:58.992  4021  4021 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-04 15:06:59.009  4021  4021 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-04 15:06:59.020  4021  4021 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 15:06:59.020  4021  4021 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-04 15:06:59.020  4021  4021 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-04 15:06:59.020  4021  4021 I Adreno  : Build Date                       : 10/20/15
08-04 15:06:59.020  4021  4021 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-04 15:06:59.020  4021  4021 I Adreno  : Local Branch                     : M14
08-04 15:06:59.020  4021  4021 I Adreno  : Remote Branch                    : 
08-04 15:06:59.020  4021  4021 I Adreno  : Remote Branch                    : 
08-04 15:06:59.020  4021  4021 I Adreno  : Reconstruct Branch               : 
,08-04 15:06:59.068  4021  4021 I NSApplication: Starting up...
,08-04 15:06:59.076  4021  4067 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-04 15:06:59.113   875  1401 I ActivityManager: Start proc 4072:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-04 15:06:59.116   875  1401 I ActivityManager: Killing 3559:com.android.musicfx/u0a18 (adj 15): empty #17
,08-04 15:06:59.189  4072  4072 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-04 15:06:59.363   875  1746 I ActivityManager: Killing 2087:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-04 15:07:00.222   875  1366 D WifiService: setWifiEnabled: true pid=3859, uid=10000
,08-04 15:07:00.222   875  1366 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 15:07:00.234   875  1309 D WifiConfigStore: Loading config and enabling all networks 
,08-04 15:07:00.242  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 15:07:00.243  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:00.243  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:00.243  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:00.243  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:07:00.243  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:07:00.243  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:07:00.243  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:07:00.243  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 15:07:00.243  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:00.243  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 15:07:00.247  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:00.247  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:00.247  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:00.247  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:00.247  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:07:00.247  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:07:00.247  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:07:00.247  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:07:00.247  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 15:07:00.248  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:00.248  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 15:07:00.259   875  1309 D WifiConfigStore: loaded 0 passpoint configs
,08-04 15:07:00.259   875  1309 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 15:07:00.260   875  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-04 15:07:00.260   875  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-04 15:07:00.261   875  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 15:07:00.262   875  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-04 15:07:00.262   875  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-04 15:07:00.262   875  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-04 15:07:00.283   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-04 15:07:00.284   875  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 15:07:00.285   373   873 D CommandListener: Setting iface cfg
08-04 15:07:00.286   875  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-04 15:07:00.287   875  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-04 15:07:00.295   875  1309 E native  : do suspend true
,08-04 15:07:00.310   875  1309 D WifiConfigStore: Retrieve network priorities after PNO.
08-04 15:07:00.310   875  1308 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 15:07:00.318   875  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-04 15:07:01.675   875  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 15:07:01.742   875  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.12 rxSuccessRate=13.75 delta 1000 -> 994
,08-04 15:07:01.747   875  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-04 15:07:01.747   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 15:07:01.761   875  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-04 15:07:01.839   875  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-04 15:07:01.842  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-04 15:07:02.268  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-04 15:07:02.303  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-04 15:07:02.303  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-04 15:07:02.309   875  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 15:07:02.322   875  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 15:07:02.323   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 15:07:02.324   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-04 15:07:02.353   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 15:07:02.374   373   873 D CommandListener: Setting iface cfg
,08-04 15:07:02.375   875  1309 D WifiStateMachine: Start Dhcp Watchdog 2
,08-04 15:07:02.392   875  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-04 15:07:02.419   875  4095 D DhcpClient: Receive thread started
,08-04 15:07:02.501   875  1309 E native  : do suspend false
,08-04 15:07:02.512   875  1961 D DhcpClient: Broadcasting DHCPDISCOVER
,08-04 15:07:02.523   875  4095 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172433, domain null
,08-04 15:07:02.523   875  1961 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172433 seconds
,08-04 15:07:02.524   875  1961 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-04 15:07:02.538   875  4095 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-04 15:07:02.539   875  1961 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-04 15:07:02.542   373   873 D CommandListener: Setting iface cfg
,08-04 15:07:02.550   875  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-04 15:07:02.552   875  1961 D DhcpClient: Scheduling renewal in 86399s
,08-04 15:07:02.554   875  1309 E native  : do suspend true
,08-04 15:07:02.573   875  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-04 15:07:02.574   875  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,08-04 15:07:02.575   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-04 15:07:02.579   875  1311 D ConnectivityService: Adding iface wlan0 to network 101
08-04 15:07:02.580   875  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-04 15:07:02.655   875  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-04 15:07:02.655   875  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-04 15:07:02.658   875  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-04 15:07:02.660   875  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-04 15:07:02.662   875  1311 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-04 15:07:02.672   875  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-04 15:07:02.678   875  1311 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-04 15:07:02.678   875  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-04 15:07:02.678   875  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-04 15:07:02.678   875  1311 D ConnectivityService:    accepting network in place of null
,08-04 15:07:02.679   875  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-04 15:07:02.680   875  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-04 15:07:02.681   875  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-04 15:07:02.698   875  4094 D NetlinkSocketObserver: NeighborEvent{elapsedMs=389125, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-04 15:07:02.730   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 15:07:02.770   875  4093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
,08-04 15:07:02.808   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 15:07:02.815   875  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-04 15:07:02.816   875  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 15:07:02.819   875  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-04 15:07:02.820   875   893 D Tethering: MasterInitialState.processMessage what=3
08-04 15:07:02.835  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:02.835  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:02.835  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:02.835  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:02.835  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:07:02.835  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:07:02.835  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:07:02.835  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:07:02.835  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 15:07:02.835  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:02.836  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 15:07:02.840  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 15:07:02.840  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:02.840  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:02.840  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:02.840  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:07:02.840  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:07:02.840  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:07:02.840  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:07:02.840  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 15:07:02.840  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:02.841  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 15:07:02.853  1982  1982 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 15:07:02.857  1982  1982 D SystemUpdateService: onCreate
,08-04 15:07:02.865  1982  1982 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 15:07:02.870  1982  4108 I SystemUpdateService: active receiver: enabled
,08-04 15:07:02.876  1982  4108 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 15:07:02.877   875  4093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 13:07:03 GMT], X-Android-Received-Millis=[1470316022875], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470316022831]}
,08-04 15:07:02.878   875  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false,
08-04 15:07:02.879   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-04 15:07:02.879   875  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-04 15:07:02.880   875  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-04 15:07:02.888  1982  4108 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-04 15:07:02.888  1982  4108 I SystemUpdateService: now status is 0 (complete)
08-04 15:07:02.888  1982  4108 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-04 15:07:02.888  1982  4108 I SystemUpdateService: file has been verified
,08-04 15:07:02.888  1982  4108 I SystemUpdateService: OTA package size = 12249756
,08-04 15:07:02.894  1982  4108 I SystemUpdateService: showing system update notification
,08-04 15:07:02.900  1982  1982 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-04 15:07:02.903  1982  2413 I iu.UploadsManager: num queued entries: 0
,08-04 15:07:02.903  1982  2413 I iu.UploadsManager: num updated entries: 0
08-04 15:07:02.904  1982  2413 I iu.SyncManager: NEXT; no task
,08-04 15:07:02.911  1982  1982 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 15:07:02.913  1982  4112 I MDM     : [220] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-04 15:07:02.913  1982  4112 W BaseAppContext: Using Auth Proxy for data requests.
,08-04 15:07:02.915  1982  4112 V GoogleAuthProtoRequest: [220] a.<init>: mAccountName set to: thalitester@gmail.com
,08-04 15:07:02.916  1982  1982 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 15:07:02.917  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 15:07:02.920  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 15:07:02.922  3994  3994 D SprintDMHelper: simOperator: 
08-04 15:07:02.922  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-04 15:07:02.922  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 15:07:02.927  1982  1982 D SystemUpdateService: onDestroy
,08-04 15:07:02.946  3964  3964 I art     : Waiting for a blocking GC DisableMovingGc
,08-04 15:07:02.949  3964  3964 I art     : Starting a blocking GC DisableMovingGc
,08-04 15:07:02.953  1517  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-04 15:07:02.953  1517  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-04 15:07:02.954  1517  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-04 15:07:02.954  1517  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 15:07:02.973  1982  4112 E MDM     : [220] SitrepService.a: Error sending sitrep.
,08-04 15:07:03.101  3964  4115 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-04 15:07:03.228   875   886 D WifiService: setWifiEnabled: false pid=3859, uid=10000
,08-04 15:07:03.228   875   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 15:07:03.231   875  1707 I ActivityManager: Killing 3508:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-04 15:07:03.250  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-04 15:07:03.252   875  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-04 15:07:03.252   875  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-04 15:07:03.253   875  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-04 15:07:03.253   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 15:07:03.264   875  1309 E native  : do suspend true
,08-04 15:07:03.270   875  1961 D DhcpClient: Clearing IP address
,08-04 15:07:03.270   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-04 15:07:03.273   373   873 D CommandListener: Setting iface cfg
,08-04 15:07:03.288   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-04 15:07:03.288   875  1309 D WifiStateMachine: Start Disconnecting Watchdog 2
08-04 15:07:03.288   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-04 15:07:03.294   875  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 15:07:03.294   875  1309 E native  : do suspend true
08-04 15:07:03.295   403   403 E Parcel  : Reading a NULL string not supported here.
08-04 15:07:03.297   875  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-04 15:07:03.303   875  4095 D DhcpClient: Receive thread stopped
,08-04 15:07:03.314  1517  4120 V NativeCrypto: Read error: ssl=0x9af55200: I/O error during system call, Connection timed out
,08-04 15:07:03.316  1517  4120 V NativeCrypto: SSL shutdown failed: ssl=0x9af55200: I/O error during system call, Broken pipe
,08-04 15:07:03.342   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 15:07:03.368   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-04 15:07:03.368   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-04 15:07:03.369   875  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-04 15:07:03.369   875  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 15:07:03.380   875   893 D Tethering: MasterInitialState.processMessage what=3
,08-04 15:07:03.381  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 15:07:03.381  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:03.381  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:03.381  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:03.381  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:07:03.381  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:07:03.381  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:07:03.381  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:07:03.381  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 15:07:03.382  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 15:07:03.382  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 15:07:03.383  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:03.383  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:03.383  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:03.383  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:03.383  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:07:03.383  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:07:03.383  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:07:03.383  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:07:03.383  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 15:07:03.383  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:03.383  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 15:07:03.376   875  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 15:07:03.397  1982  1982 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 15:07:03.401  1982  1982 D SystemUpdateService: onCreate
08-04 15:07:03.402   875  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 15:07:03.404   875  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-04 15:07:03.404  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:03.404  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:03.404  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:03.404  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:03.404  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 15:07:03.404  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:07:03.404  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:07:03.404  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:07:03.404  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 15:07:03.404  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:03.405  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 15:07:03.405  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:03.405  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:03.405  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:03.405  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:03.405  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 15:07:03.405  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:07:03.405  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:07:03.405  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:07:03.405  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 15:07:03.405  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:03.406  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 15:07:03.405  1982  1982 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-04 15:07:03.406  1970  2125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 15:07:03.415  1982  1982 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-04 15:07:03.421  1982  4129 I SystemUpdateService: active receiver: enabled
,08-04 15:07:03.421  1982  2413 I iu.UploadsManager: num queued entries: 0
,08-04 15:07:03.424  1982  1982 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 15:07:03.425  1982  1982 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 15:07:03.427  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 15:07:03.431  3994  3994 D SprintDMHelper: simOperator: 
,08-04 15:07:03.431  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 15:07:03.435  1982  2413 I iu.UploadsManager: num updated entries: 0
,08-04 15:07:03.448   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-04 15:07:03.470  3964  4133 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-04 15:07:03.477  1982  4129 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 15:07:03.485  1982  2413 I iu.SyncManager: NEXT; no task
,08-04 15:07:03.495  1982  4129 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-04 15:07:03.495  1982  4129 I SystemUpdateService: now status is 0 (complete)
08-04 15:07:03.495  1982  4129 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 15:07:03.495  1982  4129 I SystemUpdateService: file has been verified
08-04 15:07:03.495  1982  4129 I SystemUpdateService: OTA package size = 12249756
,08-04 15:07:03.500  1982  4129 I SystemUpdateService: showing system update notification
,08-04 15:07:03.510  1982  1982 D SystemUpdateService: onDestroy
,08-04 15:07:03.816   875  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-04 15:07:06.285   875   893 I ActivityManager: Start proc 4136:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-04 15:07:06.406  4136  4136 D AdapterServiceConfig: Adding HeadsetService
,08-04 15:07:06.407  4136  4136 D AdapterServiceConfig: Adding A2dpService
,08-04 15:07:06.407  4136  4136 D AdapterServiceConfig: Adding HidService
08-04 15:07:06.407  4136  4136 D AdapterServiceConfig: Adding HealthService
,08-04 15:07:06.407  4136  4136 D AdapterServiceConfig: Adding PanService
08-04 15:07:06.407  4136  4136 D AdapterServiceConfig: Adding GattService
08-04 15:07:06.408  4136  4136 D AdapterServiceConfig: Adding BluetoothMapService
,08-04 15:07:06.421   875   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c53a025:true
,08-04 15:07:06.421  4136  4136 D BluetoothAdapterState: make() - Creating AdapterState
,08-04 15:07:06.427  4136  4136 I bt_bluedroid: init
,08-04 15:07:06.428  4136  4148 I BluetoothAdapterState: Entering OffState
,08-04 15:07:06.433  4136  4149 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-04 15:07:06.434  4136  4149 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-04 15:07:06.434  4136  4149 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-04 15:07:06.434  4136  4149 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-04 15:07:06.436  4136  4136 I bt_bluedroid: get_profile_interface socket
,08-04 15:07:06.437  4136  4136 I bt_bluedroid: get_profile_interface sdp
,08-04 15:07:06.442  4136  4147 I bt_bluedroid: config_hci_snoop_log
,08-04 15:07:06.443  4136  4152 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 15:07:06.446   875   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-04 15:07:06.446  4136  4152 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 15:07:06.454  4136  4148 D BluetoothAdapterState: Current state: OFF, message: 0
,08-04 15:07:06.455  4136  4148 D BluetoothAdapterProperties: Setting state to 14
08-04 15:07:06.455  4136  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-04 15:07:06.456  4136  4148 D BluetoothBondStateMachine: make
,08-04 15:07:06.462  4136  4153 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-04 15:07:06.471  4136  4148 I BluetoothAdapterState: Entering PendingCommandState
,08-04 15:07:06.472  4136  4136 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-04 15:07:06.476  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
,08-04 15:07:06.477  4136  4136 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 15:07:06.477  4136  4136 D BtGatt.GattService: Received start request. Starting profile...
08-04 15:07:06.477  4136  4136 D BtGatt.GattService: start()
,08-04 15:07:06.478  4136  4136 I bt_bluedroid: get_profile_interface gatt
08-04 15:07:06.479  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
08-04 15:07:06.479  4136  4136 D BtGatt.AdvertiseManager: advertise manager created
,08-04 15:07:06.491  4136  4136 V BluetoothAdapterState: isTurningOff()=false
08-04 15:07:06.491  4136  4136 V BluetoothAdapterState: isTurningOn()=false
,08-04 15:07:06.491  4136  4136 V BluetoothAdapterState: isBleTurningOn()=true
08-04 15:07:06.491  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:07:06.492  4136  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-04 15:07:06.493  4136  4148 I bt_bluedroid: enable
08-04 15:07:06.493  4136  4149 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-04 15:07:06.494  4136  4149 I bt_hci  : start_up
,08-04 15:07:06.513  4136  4149 I bt_vendor: alloc value 0xb3a0d189
,08-04 15:07:06.514  4136  4149 I bt_vendor: init
08-04 15:07:06.514  4136  4149 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-04 15:07:06.514  4136  4149 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-04 15:07:06.621  4136  4149 D bt_hci  : start_up starting async portion
,08-04 15:07:06.622  4136  4156 I bt_hci  : event_finish_startup
,08-04 15:07:06.622  4136  4156 I bt_hci_h4: hal_open
08-04 15:07:06.622  4136  4156 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-04 15:07:06.632  4136  4156 I bt_userial_vendor: device fd = 51 open
,08-04 15:07:06.663  4136  4156 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 15:07:06.695  4136  4156 D bt_hwcfg: Chipset BCM4354A2
,08-04 15:07:06.695  4136  4156 D bt_hwcfg: Target name = [BCM4354A2]
08-04 15:07:06.696  4136  4156 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-04 15:07:07.354  4136  4156 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-04 15:07:07.356  4136  4156 D bt_hwcfg: Settlement delay -- 100 ms
08-04 15:07:07.356  4136  4156 I bt_hwcfg: Setting fw settlement delay to 100 
,08-04 15:07:07.473  4136  4156 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 15:07:07.474  4136  4156 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-04 15:07:07.503  4136  4156 I bt_hwcfg: vendor lib fwcfg completed
,08-04 15:07:07.504  4136  4156 I bt_vendor: firmware callback
08-04 15:07:07.504  4136  4156 I bt_hci  : firmware_config_callback
,08-04 15:07:07.516  4136  4158 I bt_btu  : btu_task pending for preload complete event
,08-04 15:07:07.516  4136  4158 I bt_btu_task: Bluetooth chip preload is complete
,08-04 15:07:07.516  4136  4158 I bt_btu  : btu_task received preload complete event
,08-04 15:07:07.527  4136  4158 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 15:07:07.528  4136  4158 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-04 15:07:07.528  4136  4158 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 15:07:07.528  4136  4158 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-04 15:07:07.529  4136  4158 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 15:07:07.529  4136  4158 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 15:07:07.530  4136  4158 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 15:07:07.530  4136  4158 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 15:07:07.530  4136  4158 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 15:07:07.530  4136  4158 I         : BTE_InitTraceLevels -- TRC_PAN
08-04 15:07:07.531  4136  4158 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 15:07:07.531  4136  4158 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 15:07:07.531  4136  4158 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 15:07:07.532  4136  4158 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 15:07:07.532  4136  4158 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 15:07:07.666  4136  4158 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb398ad9d
08-04 15:07:07.667  4136  4158 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb398ad9d 
,08-04 15:07:07.689  4136  4152 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-04 15:07:07.691  4136  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 15:07:07.692  4136  4152 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-04 15:07:07.696  4136  4152 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 15:07:07.700  4136  4152 D BluetoothAdapterProperties: Scan Mode:20
,08-04 15:07:07.700  4136  4152 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 15:07:07.701  4136  4152 D bt_hci  : do_postload posting postload work item
,08-04 15:07:07.701  4136  4156 I bt_hci  : event_postload
,08-04 15:07:07.702  4136  4156 I bt_vendor: sco_config_cb
08-04 15:07:07.702  4136  4156 I bt_hci  : sco_config_callback postload finished.
,08-04 15:07:07.706  4136  4152 D bt_bte_conf: Device ID record 1 : primary
,08-04 15:07:07.706  4136  4152 D bt_bte_conf:   vendorId            = 000f
08-04 15:07:07.707  4136  4152 D bt_bte_conf:   vendorIdSource      = 0001
08-04 15:07:07.707  4136  4152 D bt_bte_conf:   product             = 1200
08-04 15:07:07.707  4136  4152 D bt_bte_conf:   version             = 1436
08-04 15:07:07.707  4136  4152 D bt_bte_conf:   clientExecutableURL = 
08-04 15:07:07.707  4136  4152 D bt_bte_conf:   serviceDescription  = 
08-04 15:07:07.708  4136  4152 D bt_bte_conf:   documentationURL    = 
08-04 15:07:07.708  4136  4152 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-04 15:07:07.708  4136  4149 D bt_stack_manager: event_start_up_stack finished
08-04 15:07:07.709  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:07.710  4136  4156 I bt_vendor: low_power_mode_cb
08-04 15:07:07.710  4136  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-04 15:07:07.711  4136  4148 D BluetoothAdapterProperties: Setting state to 15
08-04 15:07:07.711  4136  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-04 15:07:07.712  4136  4148 I BluetoothAdapterState: Entering BleOnState
08-04 15:07:07.714  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:07:07.718  4136  4148 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-04 15:07:07.718  4136  4148 D BluetoothAdapterProperties: Setting state to 11
,08-04 15:07:07.718  4136  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-04 15:07:07.728  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:07:07.732  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
08-04 15:07:07.733  4136  4136 D HeadsetService: Received start request. Starting profile...
08-04 15:07:07.734  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:07.737  4136  4136 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 15:07:07.737  4136  4136 D HeadsetStateMachine: make
,08-04 15:07:07.742  4136  4148 I BluetoothAdapterState: Entering PendingCommandState
,08-04 15:07:07.749  4136  4136 D HeadsetStateMachine: max_hf_connections = 1
,08-04 15:07:07.749  4136  4136 I bt_bluedroid: get_profile_interface handsfree
08-04 15:07:07.750  4136  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-04 15:07:07.750  4136  4152 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-04 15:07:07.755  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
,08-04 15:07:07.756  4136  4136 D A2dpService: Received start request. Starting profile...
,08-04 15:07:07.756  4136  4136 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-04 15:07:07.757  4136  4136 I bt_bluedroid: get_profile_interface avrcp
,08-04 15:07:07.757  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 15:07:07.764  4136  4136 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-04 15:07:07.765  4136  4136 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 15:07:07.765  4136  4136 D A2dpStateMachine: make
08-04 15:07:07.767  4136  4136 I bt_bluedroid: get_profile_interface a2dp
,08-04 15:07:07.768  4136  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-04 15:07:07.769  4136  4167 D A2dpStateMachine: Enter Disconnected: -2
,08-04 15:07:07.769  4136  4136 I BluetoothHidServiceJni: classInitNative: succeeds
08-04 15:07:07.770  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
08-04 15:07:07.771  4136  4136 D HidService: Received start request. Starting profile...
08-04 15:07:07.771  4136  4136 I bt_bluedroid: get_profile_interface hidhost
08-04 15:07:07.771  4136  4136 D HidService: setHidService(): set to: null
08-04 15:07:07.772  4136  4152 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb396c3e5
08-04 15:07:07.772  4136  4136 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-04 15:07:07.772  4136  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-04 15:07:07.776  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
08-04 15:07:07.777  4136  4136 D HealthService: Received start request. Starting profile...
,08-04 15:07:07.779  3913  3913 D BluetoothInputDevice: Proxy object connected
,08-04 15:07:07.779  4136  4136 I bt_bluedroid: get_profile_interface health
08-04 15:07:07.780  4136  4136 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-04 15:07:07.780  3913  3913 D HidProfile: Bluetooth service connected
,08-04 15:07:07.781  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
,08-04 15:07:07.782  3913  3913 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 15:07:07.782  4136  4136 D PanService: Received start request. Starting profile...
08-04 15:07:07.782  4136  4136 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 15:07:07.782  4136  4136 I bt_bluedroid: get_profile_interface pan
08-04 15:07:07.783  3913  3913 D PanProfile: Bluetooth service connected
,08-04 15:07:07.785  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
,08-04 15:07:07.786  3913  3913 D BluetoothMap: Proxy object connected
,08-04 15:07:07.786  4136  4136 D BluetoothMapService: Received start request. Starting profile...
08-04 15:07:07.786  4136  4136 D BluetoothMapService: start()
08-04 15:07:07.786  3913  3913 D MapProfile: Bluetooth service connected
08-04 15:07:07.786  3913  3913 D BluetoothMap: getConnectedDevices()
08-04 15:07:07.787  4136  4152 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-04 15:07:07.787  3913  3913 D BluetoothMap: Bluetooth is Not enabled
08-04 15:07:07.789  4136  4136 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-04 15:07:07.790  4136  4136 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-04 15:07:07.790  4136  4136 D BluetoothMapAppObserver: createReceiver()
,08-04 15:07:07.791  4136  4136 D BluetoothMapAppObserver: initObservers(),
08-04 15:07:07.791  4136  4136 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-04 15:07:07.798  4136  4136 V BluetoothAdapterState: isTurningOff()=false
,08-04 15:07:07.798  4136  4136 V BluetoothAdapterState: isTurningOn()=true
08-04 15:07:07.798  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:07.798  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 15:07:07.800  4136  4165 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-04 15:07:07.803  4136  4136 V BluetoothAdapterState: isTurningOff()=false
,08-04 15:07:07.803  4136  4136 V BluetoothAdapterState: isTurningOn()=true
08-04 15:07:07.803  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:07.803  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:07:07.803  4136  4136 V BluetoothAdapterState: isTurningOff()=false
08-04 15:07:07.803  4136  4136 V BluetoothAdapterState: isTurningOn()=true
08-04 15:07:07.803  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:07.803  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:07:07.804  4136  4136 V BluetoothAdapterState: isTurningOff()=false
08-04 15:07:07.804  4136  4136 V BluetoothAdapterState: isTurningOn()=true
08-04 15:07:07.804  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 15:07:07.804  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:07:07.804  4136  4136 V BluetoothAdapterState: isTurningOff()=false
08-04 15:07:07.804  4136  4136 V BluetoothAdapterState: isTurningOn()=true
08-04 15:07:07.804  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:07.804  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:07:07.804  4136  4136 V BluetoothAdapterState: isTurningOff()=false
08-04 15:07:07.805  4136  4136 V BluetoothAdapterState: isTurningOn()=true
08-04 15:07:07.805  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:07.805  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:07:07.805  4136  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-04 15:07:07.806  4136  4148 D BluetoothAdapterProperties: ScanMode =  20
08-04 15:07:07.806  4136  4148 D BluetoothAdapterProperties: State =  11
08-04 15:07:07.806  4136  4148 D BluetoothAdapterProperties: Setting state to 12
08-04 15:07:07.806  4136  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-04 15:07:07.807  1381  1395 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 15:07:07.807  4136  4152 D BluetoothAdapterProperties: Scan Mode:21
08-04 15:07:07.807  4136  4148 I BluetoothAdapterState: Entering OnState
08-04 15:07:07.807  4136  4152 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 15:07:07.808  3913  3923 D BluetoothMap: onBluetoothStateChange: up=true
08-04 15:07:07.808   875   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 15:07:07.808  1381  1394 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 15:07:07.811  1740  1934 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 15:07:07.812  3913  3924 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 15:07:07.812  1381  1765 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 15:07:07.814  1381  1381 D BluetoothA2dp: Proxy object connected
,08-04 15:07:07.815  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:07.815  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:07.815  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:07.815  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 15:07:07.815  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:07:07.815  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:07:07.815  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:07:07.815  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 15:07:07.815  1381  1395 D BluetoothPan: onBluetoothStateChange on: true
08-04 15:07:07.816  1381  1381 D BluetoothInputDevice: Proxy object connected
08-04 15:07:07.816  1381  1381 D HidProfile: Bluetooth service connected
08-04 15:07:07.817   875   893 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 15:07:07.818   875   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 15:07:07.818   875   875 D BluetoothA2dp: Proxy object connected
08-04 15:07:07.818  1381  1765 D BluetoothMap: onBluetoothStateChange: up=true
08-04 15:07:07.818  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 15:07:07.819  1381  1381 D BluetoothPan: BluetoothPAN Proxy object connected
,08-04 15:07:07.819  1381  1381 D PanProfile: Bluetooth service connected
08-04 15:07:07.820  1381  1381 D BluetoothMap: Proxy object connected
08-04 15:07:07.820  3913  3923 D BluetoothPan: onBluetoothStateChange on: true
,08-04 15:07:07.820  1381  1381 D MapProfile: Bluetooth service connected
,08-04 15:07:07.820  1381  1381 D BluetoothMap: getConnectedDevices()
,08-04 15:07:07.820  4136  4136 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-04 15:07:07.820  3913  3924 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 15:07:07.822  4136  4136 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-04 15:07:07.823   875   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 15:07:07.823  1381  1395 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 15:07:07.823  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:07.823  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:07.823  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:07.823  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 15:07:07.823  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:07:07.823  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:07:07.823  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:07:07.823  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 15:07:07.824  4136  4136 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 15:07:07.826   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-04 15:07:07.828  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 15:07:07.829  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:07.830  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:07.830  4136  4136 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 15:07:07.831  4136  4136 D ObexServerSockets: Succeed to create listening sockets 
,08-04 15:07:07.832  4136  4136 D ObexServerSockets0: startAccept()
08-04 15:07:07.832  4136  4136 D ObexServerSockets0: prepareForNewConnect()
08-04 15:07:07.832  3913  3913 D LocalBluetoothProfileManager: Adding local A2DP profile
08-04 15:07:07.834  4136  4136 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-04 15:07:07.834  4136  4136 D BluetoothSdpJni: SDP Create record success - handle: 0
08-04 15:07:07.834  4136  4173 D ObexServerSockets0: Accepting socket connection...
08-04 15:07:07.834  4136  4136 D BluetoothMapService: onReceive
,08-04 15:07:07.834  4136  4136 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 15:07:07.835  4136  4136 D BluetoothMapService: STATE_ON
08-04 15:07:07.835  4136  4174 D ObexServerSockets0: Accepting socket connection...
08-04 15:07:07.836  3913  3913 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-04 15:07:07.841  3913  3913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 15:07:07.843  3913  3913 D BluetoothA2dp: Proxy object connected
,08-04 15:07:07.848  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 15:07:07.854  3913  3913 D DockEventReceiver: finishStartingService: stopping service
,08-04 15:07:07.855  1381  1381 D BluetoothPbap: Proxy object connected
,08-04 15:07:07.855  1381  1381 D PbapServerProfile: Bluetooth service connected
08-04 15:07:07.855  3913  3913 D BluetoothPbap: Proxy object connected
08-04 15:07:07.857  3913  3913 D PbapServerProfile: Bluetooth service connected
,08-04 15:07:07.861  4136  4136 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-04 15:07:07.861  4136  4136 D ObexServerSockets0: prepareForNewConnect()
,08-04 15:07:07.863  4136  4178 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 15:07:07.878  4136  4182 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 15:07:07.879  4136  4182 I BtOppRfcommListener: Accept thread started.
,08-04 15:07:07.908  1381  1394 D BluetoothHeadset: Proxy object connected
,08-04 15:07:07.908  1381  1381 D HeadsetProfile: Bluetooth service connected
,08-04 15:07:07.908  1740  1757 D BluetoothHeadset: Proxy object connected
08-04 15:07:07.909   875   875 D BluetoothHeadset: Proxy object connected
08-04 15:07:07.909   875   893 D BluetoothHeadset: Proxy object connected
08-04 15:07:07.909   875   875 D BluetoothHeadset: Proxy object connected
08-04 15:07:07.910   875   875 D BluetoothHeadset: Proxy object connected
08-04 15:07:07.912  1740  1761 D BluetoothHeadset: Proxy object connected
,08-04 15:07:07.918   875   893 D BluetoothHeadset: Proxy object connected
,08-04 15:07:07.923   875   893 D BluetoothHeadset: Proxy object connected
,08-04 15:07:07.938  3913  3923 D BluetoothHeadset: Proxy object connected
,08-04 15:07:07.940  3913  3913 D HeadsetProfile: Bluetooth service connected
,08-04 15:07:09.248  4136  4148 D BluetoothAdapterState: Current state: ON, message: 23
,08-04 15:07:09.249  4136  4148 D BluetoothAdapterProperties: Setting state to 13
,08-04 15:07:09.249  4136  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 15:07:09.251  4136  4148 D BluetoothAdapterProperties: onBluetoothDisable()
08-04 15:07:09.253  4136  4148 I BluetoothAdapterState: Entering PendingCommandState
,08-04 15:07:09.258  4136  4152 D BluetoothAdapterProperties: Scan Mode:20
08-04 15:07:09.259  4136  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-04 15:07:09.262  4136  4136 D BluetoothMapService: onReceive
08-04 15:07:09.263  4136  4136 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 15:07:09.263  4136  4136 D BluetoothMapService: STATE_TURNING_OFF
,08-04 15:07:09.264  4136  4136 D BluetoothMapService: MAP Service closeService in
08-04 15:07:09.264  4136  4136 D BluetoothMapMasInstance0: MAP Service shutdown
08-04 15:07:09.264  4136  4136 D ObexServerSockets0: shutdown(block = true)
,08-04 15:07:09.273  4136  4173 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-04 15:07:09.274  4136  4136 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-04 15:07:09.274  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:09.274  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:09.274  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:09.274  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:09.274  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 15:07:09.274  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:07:09.274  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:07:09.274  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:07:09.274  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 15:07:09.274  4136  4174 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-04 15:07:09.275  4136  4136 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-04 15:07:09.276  4136  4136 I BtOppRfcommListener: stopping Accept Thread
08-04 15:07:09.276  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:09.276  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 15:07:09.276  4136  4182 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-04 15:07:09.277  4136  4182 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-04 15:07:09.277  4136  4160 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-04 15:07:09.278  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:09.278  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:09.278  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:09.278  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:09.278  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 15:07:09.278  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 15:07:09.278  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:07:09.278  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:07:09.278  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 15:07:09.280  3859  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 15:07:09.281  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 15:07:09.282  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:07:09.283  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:09.284  4136  4136 D HeadsetService: Received stop request...Stopping profile...
,08-04 15:07:09.285  3913  3913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 15:07:09.291  1381  1765 D BluetoothHeadset: Proxy object disconnected
08-04 15:07:09.292  3913  3924 D BluetoothHeadset: Proxy object disconnected
,08-04 15:07:09.292  1740  1933 D BluetoothHeadset: Proxy object disconnected
08-04 15:07:09.293   875   875 D BluetoothHeadset: Proxy object disconnected
08-04 15:07:09.293   875   875 D BluetoothHeadset: Proxy object disconnected
08-04 15:07:09.293   875   875 D BluetoothHeadset: Proxy object disconnected
08-04 15:07:09.293  4136  4136 D A2dpService: Received stop request...Stopping profile...
08-04 15:07:09.294  4136  4167 D A2dpStateMachine: Exit Disconnected: -1
,08-04 15:07:09.296   875   875 D BluetoothA2dp: Proxy object disconnected
,08-04 15:07:09.297  4136  4136 V BluetoothAdapterState: isTurningOff()=true
08-04 15:07:09.297  4136  4136 V BluetoothAdapterState: isTurningOn()=false
08-04 15:07:09.297  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:09.297  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:07:09.297  1381  1381 D HeadsetProfile: Bluetooth service disconnected
08-04 15:07:09.298  1381  1381 D BluetoothA2dp: Proxy object disconnected
,08-04 15:07:09.298  3913  3913 D DockEventReceiver: finishStartingService: stopping service
08-04 15:07:09.299  4136  4136 D HidService: Received stop request...Stopping profile...
08-04 15:07:09.299  4136  4136 D HidService: Stopping Bluetooth HidService
08-04 15:07:09.302  1381  1381 D BluetoothInputDevice: Proxy object disconnected
08-04 15:07:09.302  1381  1381 D HidProfile: Bluetooth service disconnected
08-04 15:07:09.302  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 15:07:09.303  4136  4136 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 15:07:09.304  4136  4136 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-04 15:07:09.304  4136  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-04 15:07:09.304  4136  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-04 15:07:09.304  4136  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 15:07:09.304  4136  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 15:07:09.304  3913  3913 D HeadsetProfile: Bluetooth service disconnected
,08-04 15:07:09.304  4136  4152 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-04 15:07:09.305  3913  3913 D BluetoothA2dp: Proxy object disconnected
08-04 15:07:09.306  4136  4136 D HealthService: Received stop request...Stopping profile...
,08-04 15:07:09.308  3913  3913 D BluetoothInputDevice: Proxy object disconnected
08-04 15:07:09.308  4136  4136 D PanService: Received stop request...Stopping profile...
,08-04 15:07:09.308  3913  3913 D HidProfile: Bluetooth service disconnected
08-04 15:07:09.309  1381  1381 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 15:07:09.309  3913  3913 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 15:07:09.309  1381  1381 D PanProfile: Bluetooth service disconnected
08-04 15:07:09.309  3913  3913 D PanProfile: Bluetooth service disconnected
08-04 15:07:09.309  4136  4136 D BluetoothMapService: Received stop request...Stopping profile...
08-04 15:07:09.309  4136  4136 D BluetoothMapService: stop()
08-04 15:07:09.310  4136  4136 D BluetoothMapAppObserver: deinitObservers()
08-04 15:07:09.310  4136  4136 D BluetoothMapAppObserver: removeReceiver()
,08-04 15:07:09.311  1381  1381 D BluetoothMap: Proxy object disconnected
08-04 15:07:09.311  1381  1381 D MapProfile: Bluetooth service disconnected
,08-04 15:07:09.312  4136  4136 V BluetoothAdapterState: isTurningOff()=true
08-04 15:07:09.312  4136  4136 V BluetoothAdapterState: isTurningOn()=false
08-04 15:07:09.312  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:09.312  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:07:09.313  3913  3913 D BluetoothMap: Proxy object disconnected
08-04 15:07:09.313  3913  3913 D MapProfile: Bluetooth service disconnected
,08-04 15:07:09.313  4136  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-04 15:07:09.313  4136  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 15:07:09.313  4136  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 15:07:09.314  4136  4158 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 15:07:09.314  4136  4158 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 15:07:09.314  4136  4158 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 15:07:09.314  4136  4158 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-04 15:07:09.316  1381  1381 D BluetoothPbap: Proxy object disconnected
08-04 15:07:09.316  1381  1381 D PbapServerProfile: Bluetooth service disconnected
08-04 15:07:09.317  4136  4136 V BluetoothAdapterState: isTurningOff()=true
08-04 15:07:09.317  4136  4136 V BluetoothAdapterState: isTurningOn()=false
08-04 15:07:09.317  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:09.317  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:07:09.317  4136  4136 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-04 15:07:09.317  4136  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 15:07:09.317  4136  4136 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 15:07:09.319  4136  4136 V BluetoothAdapterState: isTurningOff()=true
,08-04 15:07:09.319  4136  4136 V BluetoothAdapterState: isTurningOn()=false
,08-04 15:07:09.319  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:09.319  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:07:09.319  4136  4136 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 15:07:09.320  4136  4152 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-04 15:07:09.320  4136  4136 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 15:07:09.321  4136  4136 V BluetoothAdapterState: isTurningOff()=true
08-04 15:07:09.321  4136  4136 V BluetoothAdapterState: isTurningOn()=false
08-04 15:07:09.321  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:09.321  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:07:09.321  4136  4136 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-04 15:07:09.322  4136  4136 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-04 15:07:09.323  4136  4136 D BluetoothMapService: MAP Service closeService in
08-04 15:07:09.323  4136  4136 V BluetoothAdapterState: isTurningOff()=true
08-04 15:07:09.323  4136  4136 V BluetoothAdapterState: isTurningOn()=false
08-04 15:07:09.323  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 15:07:09.323  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 15:07:09.325  4136  4136 D BluetoothMapService: cleanup()
,08-04 15:07:09.325  4136  4136 D BluetoothMapService: MAP Service closeService in
08-04 15:07:09.325  4136  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-04 15:07:09.325  4136  4148 D BluetoothAdapterProperties: Setting state to 15
08-04 15:07:09.325  4136  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-04 15:07:09.326  4136  4148 I BluetoothAdapterState: Entering BleOnState
,08-04 15:07:09.327  1381  1394 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 15:07:09.327  3913  3924 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 15:07:09.328  3913  3924 D BluetoothMap: onBluetoothStateChange: up=false
08-04 15:07:09.329   875   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 15:07:09.329  1381  1765 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 15:07:09.330  1740  1860 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 15:07:09.330  3913  3913 D BluetoothPbap: Proxy object disconnected
08-04 15:07:09.330  3913  3924 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 15:07:09.330  3913  3913 D PbapServerProfile: Bluetooth service disconnected
08-04 15:07:09.331  1381  1395 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-04 15:07:09.331  1381  1394 D BluetoothPan: onBluetoothStateChange on: false
,08-04 15:07:09.332   875   893 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 15:07:09.332   875   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 15:07:09.332  1381  1765 D BluetoothMap: onBluetoothStateChange: up=false
08-04 15:07:09.333  3913  3923 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 15:07:09.333  3913  3924 D BluetoothPan: onBluetoothStateChange on: false
,08-04 15:07:09.334  3913  3923 D BluetoothPbap: onBluetoothStateChange: up=false
,08-04 15:07:09.334   875   893 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-04 15:07:09.334  1381  1395 D BluetoothPbap: onBluetoothStateChange: up=false
,08-04 15:07:09.335  4136  4148 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-04 15:07:09.335  4136  4148 D BluetoothAdapterProperties: Setting state to 16
08-04 15:07:09.335  4136  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-04 15:07:09.336  4136  4148 D BluetoothAdapterProperties: onBleDisable
08-04 15:07:09.336  4136  4148 I BluetoothAdapterState: Entering PendingCommandState
08-04 15:07:09.336  4136  4149 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-04 15:07:09.337  4136  4158 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-04 15:07:09.337  4136  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-04 15:07:09.338  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:09.339  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:09.340  4136  4152 D BluetoothAdapterProperties: Scan Mode:20
08-04 15:07:09.341  3913  3913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 15:07:09.341  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:09.342  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:09.345  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 15:07:09.350  3913  3913 D DockEventReceiver: finishStartingService: stopping service
,08-04 15:07:09.539  4136  4152 I bt_hci  : shut_down
,08-04 15:07:09.558  4136  4156 D bt_hwcfg: hw_epilog_process
,08-04 15:07:09.559  4136  4156 I bt_vendor: low_power_mode_cb
,08-04 15:07:09.584  4136  4156 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-04 15:07:09.585  4136  4156 I bt_vendor: epilog_cb
08-04 15:07:09.585  4136  4156 I bt_hci  : epilog_finished_callback
,08-04 15:07:09.592  4136  4152 I bt_hci_h4: hal_close
,08-04 15:07:09.594  4136  4152 I bt_userial_vendor: device fd = 51 close
,08-04 15:07:09.721  4136  4149 D bt_stack_manager: event_shut_down_stack finished.
,08-04 15:07:09.721  4136  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-04 15:07:09.728  4136  4148 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-04 15:07:09.728  4136  4136 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 15:07:09.730  4136  4136 D BtGatt.GattService: Received stop request...Stopping profile...
,08-04 15:07:09.731  4136  4136 D BtGatt.GattService: stop()
08-04 15:07:09.731  4136  4136 D BtGatt.AdvertiseManager: advertise clients cleared
,08-04 15:07:09.736  4136  4136 V BluetoothAdapterState: isTurningOff()=false
,08-04 15:07:09.736  4136  4136 V BluetoothAdapterState: isTurningOn()=false
,08-04 15:07:09.736  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:09.736  4136  4136 V BluetoothAdapterState: isBleTurningOff()=true
08-04 15:07:09.738  4136  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-04 15:07:09.738  4136  4148 D BluetoothAdapterProperties: Setting state to 10
,08-04 15:07:09.738  4136  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-04 15:07:09.740  4136  4148 I BluetoothAdapterState: Entering OffState
08-04 15:07:09.742   875   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-04 15:07:09.766  4136  4136 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-04 15:07:09.767  4136  4136 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-04 15:07:09.767  4136  4136 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-04 15:07:09.770  4136  4149 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-04 15:07:09.777  4136  4149 D bt_stack_manager: event_clean_up_stack finished.
,08-04 15:07:09.780  4136  4136 I art     : System.exit called, status: 0
,08-04 15:07:09.780  4136  4136 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 15:07:09.859   875  1739 I ActivityManager: Process com.android.bluetooth (pid 4136) has died
,08-04 15:07:10.685   875  1311 D ConnectivityService: handlePromptUnvalidated 101
,08-04 15:07:12.246  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 15:07:12.246  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 15:07:15.254  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 15:07:15.254  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e081491 added. We now have 6 listener(s)
08-04 15:07:15.255  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 15:07:15.260  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 15:07:15.261  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8db1ff6 added. We now have 7 listener(s)
08-04 15:07:15.261  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 15:07:15.263  3859  3907 I System.out: IsBluetoothEnabled
,08-04 15:07:15.274  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:07:15.325   875   893 I ActivityManager: Start proc 4193:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-04 15:07:15.481  4193  4193 D AdapterServiceConfig: Adding HeadsetService
08-04 15:07:15.482  4193  4193 D AdapterServiceConfig: Adding A2dpService
,08-04 15:07:15.483  4193  4193 D AdapterServiceConfig: Adding HidService
,08-04 15:07:15.484  4193  4193 D AdapterServiceConfig: Adding HealthService
,08-04 15:07:15.487  4193  4193 D AdapterServiceConfig: Adding PanService
,08-04 15:07:15.488  4193  4193 D AdapterServiceConfig: Adding GattService
,08-04 15:07:15.490  4193  4193 D AdapterServiceConfig: Adding BluetoothMapService
,08-04 15:07:15.513  4193  4193 D BluetoothAdapterState: make() - Creating AdapterState
,08-04 15:07:15.513   875   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@84e33ae:true
,08-04 15:07:15.519  4193  4193 I bt_bluedroid: init
,08-04 15:07:15.519  4193  4205 I BluetoothAdapterState: Entering OffState
,08-04 15:07:15.524  4193  4206 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-04 15:07:15.525  4193  4206 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 15:07:15.525  4193  4206 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-04 15:07:15.526  4193  4206 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-04 15:07:15.528  4193  4193 I bt_bluedroid: get_profile_interface socket
,08-04 15:07:15.531  4193  4193 I bt_bluedroid: get_profile_interface sdp
,08-04 15:07:15.534  4193  4209 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 15:07:15.538  4193  4209 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 15:07:15.541  4193  4204 I bt_bluedroid: config_hci_snoop_log
,08-04 15:07:15.545   875   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-04 15:07:15.558  4193  4205 D BluetoothAdapterState: Current state: OFF, message: 0
,08-04 15:07:15.558  4193  4205 D BluetoothAdapterProperties: Setting state to 14
08-04 15:07:15.559  4193  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-04 15:07:15.564  4193  4205 D BluetoothBondStateMachine: make
,08-04 15:07:15.571  4193  4210 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-04 15:07:15.580  4193  4205 I BluetoothAdapterState: Entering PendingCommandState
,08-04 15:07:15.586  4193  4193 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-04 15:07:15.598  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
,08-04 15:07:15.602  4193  4193 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 15:07:15.604  4193  4193 D BtGatt.GattService: Received start request. Starting profile...
08-04 15:07:15.604  4193  4193 D BtGatt.GattService: start()
08-04 15:07:15.604  4193  4193 I bt_bluedroid: get_profile_interface gatt
,08-04 15:07:15.606  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233,
08-04 15:07:15.607  4193  4193 D BtGatt.AdvertiseManager: advertise manager created
,08-04 15:07:15.618  4193  4193 V BluetoothAdapterState: isTurningOff()=false
,08-04 15:07:15.618  4193  4193 V BluetoothAdapterState: isTurningOn()=false
08-04 15:07:15.618  4193  4193 V BluetoothAdapterState: isBleTurningOn()=true
08-04 15:07:15.618  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 15:07:15.619  4193  4205 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-04 15:07:15.619  4193  4205 I bt_bluedroid: enable
08-04 15:07:15.620  4193  4206 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-04 15:07:15.621  4193  4206 I bt_hci  : start_up
,08-04 15:07:15.641  4193  4206 I bt_vendor: alloc value 0xb3a0d189
,08-04 15:07:15.641  4193  4206 I bt_vendor: init
08-04 15:07:15.642  4193  4206 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-04 15:07:15.642  4193  4206 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-04 15:07:15.751  4193  4206 D bt_hci  : start_up starting async portion
,08-04 15:07:15.752  4193  4213 I bt_hci  : event_finish_startup
08-04 15:07:15.753  4193  4213 I bt_hci_h4: hal_open
08-04 15:07:15.753  4193  4213 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-04 15:07:15.764  4193  4213 I bt_userial_vendor: device fd = 51 open
,08-04 15:07:15.795  4193  4213 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 15:07:15.826  4193  4213 D bt_hwcfg: Chipset BCM4354A2
,08-04 15:07:15.826  4193  4213 D bt_hwcfg: Target name = [BCM4354A2]
08-04 15:07:15.827  4193  4213 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-04 15:07:16.718  4193  4213 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-04 15:07:16.720  4193  4213 D bt_hwcfg: Settlement delay -- 100 ms
,08-04 15:07:16.720  4193  4213 I bt_hwcfg: Setting fw settlement delay to 100 
,08-04 15:07:16.838  4193  4213 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 15:07:16.840  4193  4213 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-04 15:07:16.868  4193  4213 I bt_hwcfg: vendor lib fwcfg completed
08-04 15:07:16.868  4193  4213 I bt_vendor: firmware callback
,08-04 15:07:16.868  4193  4213 I bt_hci  : firmware_config_callback
,08-04 15:07:16.881  4193  4215 I bt_btu  : btu_task pending for preload complete event
08-04 15:07:16.881  4193  4215 I bt_btu_task: Bluetooth chip preload is complete
,08-04 15:07:16.881  4193  4215 I bt_btu  : btu_task received preload complete event
,08-04 15:07:16.892  4193  4215 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 15:07:16.893  4193  4215 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-04 15:07:16.893  4193  4215 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 15:07:16.893  4193  4215 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 15:07:16.894  4193  4215 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 15:07:16.894  4193  4215 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 15:07:16.894  4193  4215 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 15:07:16.894  4193  4215 I         : BTE_InitTraceLevels -- TRC_BTM
,08-04 15:07:16.895  4193  4215 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 15:07:16.895  4193  4215 I         : BTE_InitTraceLevels -- TRC_PAN
08-04 15:07:16.896  4193  4215 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 15:07:16.896  4193  4215 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 15:07:16.897  4193  4215 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 15:07:16.897  4193  4215 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 15:07:16.897  4193  4215 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 15:07:17.053  4193  4215 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb398ad9d
,08-04 15:07:17.054  4193  4215 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb398ad9d 
,08-04 15:07:17.067  4193  4209 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-04 15:07:17.069  4193  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 15:07:17.070  4193  4209 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 15:07:17.073  4193  4209 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 15:07:17.076  4193  4209 D BluetoothAdapterProperties: Scan Mode:20
,08-04 15:07:17.076  4193  4209 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 15:07:17.080  4193  4209 D bt_hci  : do_postload posting postload work item
,08-04 15:07:17.080  4193  4213 I bt_hci  : event_postload
,08-04 15:07:17.080  4193  4213 I bt_vendor: sco_config_cb
08-04 15:07:17.081  4193  4213 I bt_hci  : sco_config_callback postload finished.
08-04 15:07:17.083  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:07:17.087  4193  4209 D bt_bte_conf: Device ID record 1 : primary
08-04 15:07:17.087  4193  4209 D bt_bte_conf:   vendorId            = 000f
,08-04 15:07:17.087  4193  4209 D bt_bte_conf:   vendorIdSource      = 0001
08-04 15:07:17.088  4193  4209 D bt_bte_conf:   product             = 1200
08-04 15:07:17.088  4193  4209 D bt_bte_conf:   version             = 1436
08-04 15:07:17.088  4193  4209 D bt_bte_conf:   clientExecutableURL = 
08-04 15:07:17.088  4193  4209 D bt_bte_conf:   serviceDescription  = 
,08-04 15:07:17.088  4193  4209 D bt_bte_conf:   documentationURL    = 
08-04 15:07:17.089  4193  4213 I bt_vendor: low_power_mode_cb
08-04 15:07:17.089  4193  4209 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-04 15:07:17.089  4193  4206 D bt_stack_manager: event_start_up_stack finished
,08-04 15:07:17.090  4193  4205 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-04 15:07:17.090  4193  4205 D BluetoothAdapterProperties: Setting state to 15
08-04 15:07:17.090  4193  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-04 15:07:17.091  4193  4205 I BluetoothAdapterState: Entering BleOnState
08-04 15:07:17.097  4193  4205 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-04 15:07:17.097  4193  4205 D BluetoothAdapterProperties: Setting state to 11
08-04 15:07:17.097  4193  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-04 15:07:17.105  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
,08-04 15:07:17.106  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:07:17.111  4193  4193 D HeadsetService: Received start request. Starting profile...
,08-04 15:07:17.115  4193  4193 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-04 15:07:17.116  4193  4193 D HeadsetStateMachine: make
,08-04 15:07:17.126  4193  4193 D HeadsetStateMachine: max_hf_connections = 1
,08-04 15:07:17.126  4193  4193 I bt_bluedroid: get_profile_interface handsfree
08-04 15:07:17.127  4193  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-04 15:07:17.127  4193  4209 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-04 15:07:17.130  4193  4205 I BluetoothAdapterState: Entering PendingCommandState
,08-04 15:07:17.140  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 15:07:17.141  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
,08-04 15:07:17.142  4193  4193 D A2dpService: Received start request. Starting profile...
,08-04 15:07:17.142  4193  4193 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 15:07:17.143  4193  4193 I bt_bluedroid: get_profile_interface avrcp
,08-04 15:07:17.153  4193  4193 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-04 15:07:17.154  4193  4193 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 15:07:17.154  4193  4193 D A2dpStateMachine: make
,08-04 15:07:17.155  4193  4193 I bt_bluedroid: get_profile_interface a2dp
,08-04 15:07:17.157  4193  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-04 15:07:17.159  4193  4224 D A2dpStateMachine: Enter Disconnected: -2
08-04 15:07:17.160  4193  4193 I BluetoothHidServiceJni: classInitNative: succeeds
,08-04 15:07:17.161  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
08-04 15:07:17.162  4193  4193 D HidService: Received start request. Starting profile...
08-04 15:07:17.162  4193  4193 I bt_bluedroid: get_profile_interface hidhost
08-04 15:07:17.163  4193  4209 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb396c3e5
08-04 15:07:17.163  4193  4209 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-04 15:07:17.163  4193  4193 D HidService: setHidService(): set to: null
,08-04 15:07:17.166  4193  4193 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-04 15:07:17.167  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
08-04 15:07:17.168  4193  4193 D HealthService: Received start request. Starting profile...
,08-04 15:07:17.170  4193  4193 I bt_bluedroid: get_profile_interface health
,08-04 15:07:17.172  4193  4193 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-04 15:07:17.173  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
08-04 15:07:17.174  4193  4193 D PanService: Received start request. Starting profile...
,08-04 15:07:17.174  4193  4193 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 15:07:17.174  4193  4193 I bt_bluedroid: get_profile_interface pan
08-04 15:07:17.175  4193  4209 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-04 15:07:17.179  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
,08-04 15:07:17.180  4193  4193 D BluetoothMapService: Received start request. Starting profile...
08-04 15:07:17.180  4193  4193 D BluetoothMapService: start()
,08-04 15:07:17.183  4193  4193 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-04 15:07:17.184  4193  4193 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-04 15:07:17.184  4193  4193 D BluetoothMapAppObserver: createReceiver()
,08-04 15:07:17.186  4193  4193 D BluetoothMapAppObserver: initObservers()
08-04 15:07:17.186  4193  4193 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-04 15:07:17.193  4193  4193 V BluetoothAdapterState: isTurningOff()=false
,08-04 15:07:17.194  4193  4193 V BluetoothAdapterState: isTurningOn()=true
08-04 15:07:17.194  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:17.194  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:07:17.196  4193  4222 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-04 15:07:17.198  4193  4193 V BluetoothAdapterState: isTurningOff()=false
08-04 15:07:17.198  4193  4193 V BluetoothAdapterState: isTurningOn()=true
,08-04 15:07:17.198  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:17.198  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:07:17.198  4193  4193 V BluetoothAdapterState: isTurningOff()=false
,08-04 15:07:17.198  4193  4193 V BluetoothAdapterState: isTurningOn()=true
,08-04 15:07:17.198  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:17.198  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 15:07:17.198  4193  4193 V BluetoothAdapterState: isTurningOff()=false
08-04 15:07:17.198  4193  4193 V BluetoothAdapterState: isTurningOn()=true
08-04 15:07:17.199  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:17.199  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 15:07:17.199  4193  4193 V BluetoothAdapterState: isTurningOff()=false
08-04 15:07:17.199  4193  4193 V BluetoothAdapterState: isTurningOn()=true
08-04 15:07:17.199  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
08-04 15:07:17.199  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 15:07:17.199  4193  4193 V BluetoothAdapterState: isTurningOff()=false
08-04 15:07:17.199  4193  4193 V BluetoothAdapterState: isTurningOn()=true
08-04 15:07:17.199  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 15:07:17.200  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
08-04 15:07:17.200  4193  4205 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-04 15:07:17.200  4193  4205 D BluetoothAdapterProperties: ScanMode =  20
08-04 15:07:17.200  4193  4205 D BluetoothAdapterProperties: State =  11
08-04 15:07:17.203  4193  4209 D BluetoothAdapterProperties: Scan Mode:21
,08-04 15:07:17.203  4193  4205 D BluetoothAdapterProperties: Setting state to 12
08-04 15:07:17.203  4193  4205 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-04 15:07:17.204  4193  4209 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 15:07:17.204  1381  1394 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 15:07:17.205  3913  3923 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 15:07:17.205  4193  4205 I BluetoothAdapterState: Entering OnState
08-04 15:07:17.208  3913  3924 D BluetoothMap: onBluetoothStateChange: up=true
08-04 15:07:17.208  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:17.208  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:17.208  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:17.208  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 15:07:17.208  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:07:17.208  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:07:17.208  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:07:17.208  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 15:07:17.211   875   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 15:07:17.211  1381  1395 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 15:07:17.213  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 15:07:17.214  1381  1381 D BluetoothA2dp: Proxy object connected
08-04 15:07:17.214  1740  1933 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 15:07:17.214  4193  4193 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-04 15:07:17.215  3913  3924 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 15:07:17.215  4193  4193 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-04 15:07:17.217  3913  3913 D BluetoothA2dp: Proxy object connected
08-04 15:07:17.217  4193  4193 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 15:07:17.218  1381  1394 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 15:07:17.220  4193  4193 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 15:07:17.221  1381  1395 D BluetoothPan: onBluetoothStateChange on: true
08-04 15:07:17.222  4193  4193 D ObexServerSockets: Succeed to create listening sockets 
08-04 15:07:17.222  4193  4193 D ObexServerSockets0: startAccept()
08-04 15:07:17.222  4193  4193 D ObexServerSockets0: prepareForNewConnect()
08-04 15:07:17.223   875   893 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 15:07:17.224   875   875 D BluetoothA2dp: Proxy object connected
08-04 15:07:17.225  4193  4193 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-04 15:07:17.225   875   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 15:07:17.225  4193  4193 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-04 15:07:17.226  3913  3913 D BluetoothMap: Proxy object connected
08-04 15:07:17.226  3913  3913 D MapProfile: Bluetooth service connected
08-04 15:07:17.226  3913  3913 D BluetoothMap: getConnectedDevices()
08-04 15:07:17.226  1381  1765 D BluetoothMap: onBluetoothStateChange: up=true
08-04 15:07:17.226  4193  4230 D ObexServerSockets0: Accepting socket connection...
08-04 15:07:17.227  1381  1381 D BluetoothInputDevice: Proxy object connected
,08-04 15:07:17.227  1381  1381 D HidProfile: Bluetooth service connected
08-04 15:07:17.228  4193  4231 D ObexServerSockets0: Accepting socket connection...
08-04 15:07:17.229  3913  3913 D BluetoothInputDevice: Proxy object connected
08-04 15:07:17.229  3913  3913 D HidProfile: Bluetooth service connected
08-04 15:07:17.230  1381  1381 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 15:07:17.230  1381  1381 D PanProfile: Bluetooth service connected
,08-04 15:07:17.235  1381  1381 D BluetoothMap: Proxy object connected
,08-04 15:07:17.235  1381  1381 D MapProfile: Bluetooth service connected
08-04 15:07:17.235  1381  1381 D BluetoothMap: getConnectedDevices()
,08-04 15:07:17.236  3913  3924 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 15:07:17.238  3913  4229 D BluetoothPan: onBluetoothStateChange on: true
,08-04 15:07:17.242  3913  3913 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 15:07:17.242  3913  3913 D PanProfile: Bluetooth service connected
,08-04 15:07:17.242  3913  3924 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 15:07:17.244   875   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 15:07:17.244  1381  1395 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 15:07:17.247   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-04 15:07:17.248  4193  4193 D BluetoothMapService: onReceive
08-04 15:07:17.248  4193  4193 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 15:07:17.248  4193  4193 D BluetoothMapService: STATE_ON
08-04 15:07:17.251  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:07:17.256  3913  3913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 15:07:17.263  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 15:07:17.264  3913  3913 D DockEventReceiver: finishStartingService: stopping service
,08-04 15:07:17.273  3913  3913 D BluetoothPbap: Proxy object connected
,08-04 15:07:17.274  3913  3913 D PbapServerProfile: Bluetooth service connected
08-04 15:07:17.275  1381  1381 D BluetoothPbap: Proxy object connected
08-04 15:07:17.275  1381  1381 D PbapServerProfile: Bluetooth service connected
,08-04 15:07:17.276  4193  4193 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-04 15:07:17.276  4193  4193 D ObexServerSockets0: prepareForNewConnect()
,08-04 15:07:17.279  4193  4234 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 15:07:17.290  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:17.290  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:17.290  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:17.290  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 15:07:17.290  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:07:17.290  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:07:17.290  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:07:17.290  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 15:07:17.294  3859  3907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 15:07:17.295  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 15:07:17.296  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@74dbff7 added. We now have 8 listener(s)
,08-04 15:07:17.296  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 15:07:17.298   875  1366 D WifiService: setWifiEnabled: false pid=3859, uid=10000
,08-04 15:07:17.298   875  1366 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 15:07:17.303  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:17.303   875  1739 D WifiService: setWifiEnabled: true pid=3859, uid=10000
08-04 15:07:17.303   875  1739 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 15:07:17.311   875  1309 D WifiConfigStore: Loading config and enabling all networks 
,08-04 15:07:17.314  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:17.314  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:17.314  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:17.314  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:07:17.314  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:07:17.314  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:07:17.314  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:07:17.314  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 15:07:17.317  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 15:07:17.319  1381  1395 D BluetoothHeadset: Proxy object connected
08-04 15:07:17.320  1381  1381 D HeadsetProfile: Bluetooth service connected
,08-04 15:07:17.321  3913  4229 D BluetoothHeadset: Proxy object connected
,08-04 15:07:17.322  1740  1934 D BluetoothHeadset: Proxy object connected
,08-04 15:07:17.322   875   875 D BluetoothHeadset: Proxy object connected
08-04 15:07:17.322   875   875 D BluetoothHeadset: Proxy object connected
,08-04 15:07:17.322   875   875 D BluetoothHeadset: Proxy object connected
,08-04 15:07:17.325  3913  3913 D HeadsetProfile: Bluetooth service connected
08-04 15:07:17.328   875  1309 D WifiConfigStore: loaded 0 passpoint configs
08-04 15:07:17.329   875  1309 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-04 15:07:17.329   875   893 D BluetoothHeadset: Proxy object connected
,08-04 15:07:17.329   875  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-04 15:07:17.330   875  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-04 15:07:17.331   875  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-04 15:07:17.332   875  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-04 15:07:17.332   875  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-04 15:07:17.332   875  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-04 15:07:17.336  4193  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 15:07:17.338  3913  3924 D BluetoothHeadset: Proxy object connected
,08-04 15:07:17.341  4193  4243 I BtOppRfcommListener: Accept thread started.
08-04 15:07:17.341  3913  3913 D HeadsetProfile: Bluetooth service connected
,08-04 15:07:17.344   875   893 D BluetoothHeadset: Proxy object connected
08-04 15:07:17.345   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-04 15:07:17.346   875  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-04 15:07:17.346   373   873 D CommandListener: Setting iface cfg
08-04 15:07:17.346   875  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
08-04 15:07:17.346   875  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-04 15:07:17.398   875  1309 E native  : do suspend true
,08-04 15:07:17.403   875  1308 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 15:07:17.418   875  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-04 15:07:17.470   875  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 15:07:18.319  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:18.319  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:18.319  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:18.319  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:07:18.319  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:07:18.319  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 15:07:18.319  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 15:07:18.319  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 15:07:18.327  3859  3907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 15:07:18.340  3859  4246 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-04 15:07:18.341  3859  4246 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-04 15:07:18.850   875  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 15:07:18.983   875  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.69 rxSuccessRate=15.12 delta 1000 -> 994
,08-04 15:07:18.985   875  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-04 15:07:18.985   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 15:07:19.002   875  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-04 15:07:19.060   875  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-04 15:07:19.065  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-04 15:07:19.506  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-04 15:07:19.546  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-04 15:07:19.546  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-04 15:07:19.551   875  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 15:07:19.566   875  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 15:07:19.566   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-04 15:07:19.566   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 15:07:19.589   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 15:07:19.608   373   873 D CommandListener: Setting iface cfg
,08-04 15:07:19.612   875  1309 D WifiStateMachine: Start Dhcp Watchdog 3
,08-04 15:07:19.622   875  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-04 15:07:19.635   875  4249 D DhcpClient: Receive thread started
,08-04 15:07:19.720   875  1309 E native  : do suspend false
,08-04 15:07:19.740   875  1961 D DhcpClient: Broadcasting DHCPDISCOVER
,08-04 15:07:19.754   875  4249 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-04 15:07:19.755   875  1961 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-04 15:07:19.760   875  1961 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-04 15:07:19.772   875  4249 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-04 15:07:19.773   875  1961 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-04 15:07:19.780   373   873 D CommandListener: Setting iface cfg
,08-04 15:07:19.792   875  1961 D DhcpClient: Scheduling renewal in 86399s
,08-04 15:07:19.792   875  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-04 15:07:19.796   875  1309 E native  : do suspend true
,08-04 15:07:19.816   875  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-04 15:07:19.817   875  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,08-04 15:07:19.818   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-04 15:07:19.822   875  1311 D ConnectivityService: Adding iface wlan0 to network 102
,08-04 15:07:19.825   875  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-04 15:07:19.877   875  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-04 15:07:19.877   875  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-04 15:07:19.879   875  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-04 15:07:19.881   875  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-04 15:07:19.884   875  1311 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-04 15:07:19.900   875  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-04 15:07:19.906   875  1311 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-04 15:07:19.907   875  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-04 15:07:19.907   875  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-04 15:07:19.907   875  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-04 15:07:19.908   875  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-04 15:07:19.908   875  1311 D ConnectivityService:    accepting network in place of null
,08-04 15:07:19.909   875  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 15:07:19.919   875  4248 D NetlinkSocketObserver: NeighborEvent{elapsedMs=406346, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-04 15:07:19.958   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 15:07:19.992   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 15:07:19.995   875  4247 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
,08-04 15:07:19.999   875  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-04 15:07:19.999   875  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 15:07:20.004   875  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-04 15:07:20.005   875   893 D Tethering: MasterInitialState.processMessage what=3
08-04 15:07:20.029  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 15:07:20.029  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:20.029  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:20.029  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-04 15:07:20.029  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:07:20.029  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:07:20.029  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:07:20.029  3859  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 15:07:20.040  3859  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 15:07:20.043  1982  1982 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 15:07:20.057  1982  1982 D SystemUpdateService: onCreate
,08-04 15:07:20.062  1982  1982 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 15:07:20.088  1982  4258 I SystemUpdateService: active receiver: enabled
,08-04 15:07:20.090  1982  1982 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-04 15:07:20.098  1982  2413 I iu.UploadsManager: num queued entries: 0
,08-04 15:07:20.099  1982  2413 I iu.UploadsManager: num updated entries: 0
,08-04 15:07:20.101  1982  1982 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 15:07:20.102  1982  2413 I iu.SyncManager: NEXT; no task
,08-04 15:07:20.104   875  4247 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 13:07:20 GMT], X-Android-Received-Millis=[1470316040104], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470316040058]}
,08-04 15:07:20.109  1982  1982 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 15:07:20.110  1982  4258 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 15:07:20.114  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 15:07:20.115   875  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-04 15:07:20.116   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-04 15:07:20.116   875  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-04 15:07:20.123   875  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-04 15:07:20.137  1982  4260 I MDM     : [225] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-04 15:07:20.137  1982  4260 W BaseAppContext: Using Auth Proxy for data requests.
,08-04 15:07:20.140  3994  3994 D SprintDMHelper: simOperator: 
,08-04 15:07:20.140  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 15:07:20.147  1982  4260 V GoogleAuthProtoRequest: [225] a.<init>: mAccountName set to: thalitester@gmail.com
,08-04 15:07:20.168  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 15:07:20.169  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 15:07:20.170  1982  4258 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-04 15:07:20.171  1982  4258 I SystemUpdateService: now status is 0 (complete)
08-04 15:07:20.171  1982  4258 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 15:07:20.171  1982  4258 I SystemUpdateService: file has been verified
,08-04 15:07:20.171  1982  4258 I SystemUpdateService: OTA package size = 12249756
,08-04 15:07:20.195  1982  4258 I SystemUpdateService: showing system update notification
,08-04 15:07:20.217  1982  1982 D SystemUpdateService: onDestroy
,08-04 15:07:20.219  1517  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-04 15:07:20.219  1517  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-04 15:07:20.219  1517  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 15:07:20.220  1517  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 15:07:20.233  1982  4260 E MDM     : [225] SitrepService.a: Error sending sitrep.
,08-04 15:07:20.310  3964  4264 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-04 15:07:21.348  3859  4270 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-04 15:07:21.348  3859  4246 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-04 15:07:21.349  3859  4270 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-04 15:07:21.349  3859  4246 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-04 15:07:21.351  3859  4270 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-04 15:07:21.351  3859  4246 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-04 15:07:21.353  3859  4270 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-04 15:07:21.354  3859  4246 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-04 15:07:21.356  3859  4272 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: IncomingSocketThread/Sender)
08-04 15:07:21.358  3859  4246 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-04 15:07:21.361  3859  4270 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-04 15:07:21.364  3859  4273 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: OutgoingSocketThread/Sender)
,08-04 15:07:21.366  3859  4274 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: OutgoingSocketThread/Receiver)
,08-04 15:07:21.368  3859  4274 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: OutgoingSocketThread/Receiver)
,08-04 15:07:21.369  3859  4274 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-04 15:07:21.369  3859  4274 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-04 15:07:21.369  3859  4275 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: IncomingSocketThread/Receiver)
08-04 15:07:21.371  3859  4275 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: IncomingSocketThread/Receiver)
08-04 15:07:21.371  3859  4275 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-04 15:07:21.371  3859  4275 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-04 15:07:24.347  3859  3907 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-04 15:07:24.349  3859  3907 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-04 15:07:24.357  3859  3907 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@cff6e8f Bundle[{}],
,08-04 15:07:24.357  3859  3907 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-04 15:07:24.358  3859  3907 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-04 15:07:24.358  3859  3907 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-04 15:07:24.359  3859  3907 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-04 15:07:24.359  3859  3907 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-04 15:07:24.360  3859  3907 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-04 15:07:24.364  3859  3907 I System.out: Running OutgoingSocketThread
,08-04 15:07:24.368  3859  4276 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-04 15:07:24.368  3859  4276 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-04 15:07:27.376  3859  4277 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-04 15:07:27.377  3859  4277 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-04 15:07:27.377  3859  4276 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-04 15:07:27.377  3859  4277 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-04 15:07:27.377  3859  4276 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-04 15:07:27.378  3859  4277 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-04 15:07:27.379  3859  4276 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-04 15:07:27.381  3859  4279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: IncomingSocketThread/Sender)
,08-04 15:07:27.382  3859  4277 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-04 15:07:27.384  3859  4276 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-04 15:07:27.388  3859  4280 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 449, name: IncomingSocketThread/Receiver)
,08-04 15:07:27.390  3859  4276 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-04 15:07:27.393  3859  4280 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 449, thread name: IncomingSocketThread/Receiver)
,08-04 15:07:27.393  3859  4280 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-04 15:07:27.393  3859  4280 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 449, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-04 15:07:27.393  3859  4281 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 448, name: OutgoingSocketThread/Sender)
,08-04 15:07:27.395  3859  4282 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 450, name: OutgoingSocketThread/Receiver)
,08-04 15:07:27.397  3859  4282 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 450, thread name: OutgoingSocketThread/Receiver)
,08-04 15:07:27.397  3859  4282 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-04 15:07:27.397  3859  4282 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 450, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-04 15:07:27.916   875  1311 D ConnectivityService: handlePromptUnvalidated 102
,08-04 15:07:30.380  3859  3907 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 459)
,08-04 15:07:30.382  3859  3907 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-04 15:07:30.382  3859  3907 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 460)
,08-04 15:07:30.391  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 15:07:30.392  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca22e64 added. We now have 2 listener(s)
,08-04 15:07:30.396  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 15:07:30.396  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 15:07:30.396  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 15:07:30.396  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 15:07:30.396  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8868cd added. We now have 9 listener(s)
08-04 15:07:30.396  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 15:07:30.397  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 15:07:30.401  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 15:07:30.413  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 15:07:30.413  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:30.413  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:30.413  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:07:30.413  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:07:30.413  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:07:30.413  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:07:30.413  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 15:07:30.420  3859  3907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 15:07:30.420  3859  3907 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 15:07:30.421  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 15:07:30.421  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6946493 added. We now have 3 listener(s)
,08-04 15:07:30.426  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:07:30.427  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 15:07:30.427  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 15:07:30.427  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 15:07:30.428  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 15:07:30.428  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85ccd0 added. We now have 10 listener(s)
,08-04 15:07:30.428  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 15:07:30.429  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:07:30.429  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:07:30.429  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:07:30.430  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:07:30.430  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:07:30.430  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.430  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 15:07:30.431  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 15:07:30.431  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca22e64 removed from the list
08-04 15:07:30.431  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:07:30.431  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8868cd removed from the list
08-04 15:07:30.432  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:07:30.432  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:07:30.433  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.433  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:07:30.436  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:07:30.437  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:07:30.437  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:07:30.437  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8868cd not in the list
08-04 15:07:30.437  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.438  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:07:30.440  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 15:07:30.440  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 15:07:30.440  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:07:30.441  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85ccd0 removed from the list
08-04 15:07:30.441  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:07:30.441  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.441  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:07:30.441  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 15:07:30.441  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6946493 removed from the list
08-04 15:07:30.442  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 15:07:30.443  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63fc4c9 added. We now have 2 listener(s)
08-04 15:07:30.445  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 15:07:30.445  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 15:07:30.446  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 15:07:30.446  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 15:07:30.446  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39237ce added. We now have 9 listener(s)
,08-04 15:07:30.446  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 15:07:30.447  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 15:07:30.450  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 15:07:30.458  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 15:07:30.458  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:30.458  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:30.458  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:07:30.458  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:07:30.458  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:07:30.458  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:07:30.458  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 15:07:30.461  3859  3907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-04 15:07:30.461  3859  3907 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 15:07:30.461  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,08-04 15:07:30.461  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc2e5fc added. We now have 3 listener(s)
08-04 15:07:30.463  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 15:07:30.463  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 15:07:30.464  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 15:07:30.464  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 15:07:30.464  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df6e485 added. We now have 10 listener(s)
08-04 15:07:30.464  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 15:07:30.464  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 15:07:30.464  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-04 15:07:30.464  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:30.464  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 15:07:30.464  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 15:07:30.464  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 15:07:30.468  3859  3907 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-04 15:07:30.468  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 15:07:30.468  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:30.473  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 15:07:30.474  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-04 15:07:30.474  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 15:07:30.479  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-04 15:07:30.479  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 15:07:30.479  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 15:07:30.480  3859  3907 D BluetoothAdapter: STATE_ON
,08-04 15:07:30.484  4193  4203 D BtGatt.GattService: registerClient() - UUID=b0c841d9-d711-4e19-943b-b8ba8e45d395
,08-04 15:07:30.485  4193  4209 D BtGatt.GattService: onClientRegistered() - UUID=b0c841d9-d711-4e19-943b-b8ba8e45d395, clientIf=5
08-04 15:07:30.486  3859  3869 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-04 15:07:30.487  4193  4221 D BtGatt.GattService: start scan with filters
,08-04 15:07:30.493  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 15:07:30.494  4193  4212 D BtGatt.ScanManager: handling starting scan
,08-04 15:07:30.494  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-04 15:07:30.494  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
,08-04 15:07:30.494  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 15:07:30.497  4193  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@102e233
,08-04 15:07:30.504  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 15:07:30.505  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 15:07:30.505  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,08-04 15:07:30.508  4193  4209 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-04 15:07:30.508  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:07:30.509  4193  4212 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 15:07:30.512  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 15:07:30.518  3859  3907 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-04 15:07:30.518  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-04 15:07:30.518  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-04 15:07:30.518  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 15:07:30.518  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 15:07:30.519  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-04 15:07:30.519  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-04 15:07:30.519  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-04 15:07:30.519  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-04 15:07:30.520  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-04 15:07:30.520  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-04 15:07:30.521  3859  3907 D BluetoothAdapter: STATE_ON
,08-04 15:07:30.522  4193  4204 D BtGatt.GattService: stopScan() - queue size =1
,08-04 15:07:30.524  4193  4232 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-04 15:07:30.524  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-04 15:07:30.525  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-04 15:07:30.525  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 15:07:30.525  4193  4209 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
08-04 15:07:30.526  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:07:30.525  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
08-04 15:07:30.526  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 15:07:30.526  4193  4212 D BtGatt.ScanManager: Starting BLE batch scan
,08-04 15:07:30.527  4193  4212 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 15:07:30.529  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 15:07:30.530  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-04 15:07:30.530  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 15:07:30.530  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 15:07:30.532  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 15:07:30.535  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-04 15:07:30.535  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 15:07:30.535  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 15:07:30.540  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:07:30.541  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:07:30.541  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 15:07:30.541  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:07:30.541  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.541  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 15:07:30.541  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 15:07:30.542  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63fc4c9 removed from the list
,08-04 15:07:30.542  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:07:30.542  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39237ce removed from the list
08-04 15:07:30.542  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:07:30.542  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:07:30.543  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.544  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:07:30.546  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:07:30.546  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:07:30.546  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 15:07:30.546  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39237ce not in the list
08-04 15:07:30.547  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.547  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 15:07:30.549  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:07:30.549  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 15:07:30.549  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:07:30.550  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df6e485 removed from the list
08-04 15:07:30.550  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 15:07:30.550  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.550  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:07:30.550  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 15:07:30.550  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc2e5fc removed from the list
08-04 15:07:30.551  4193  4209 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 15:07:30.551  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:07:30.553  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 15:07:30.553  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@464401 added. We now have 2 listener(s)
,08-04 15:07:30.557  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 15:07:30.558  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 15:07:30.558  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 15:07:30.558  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 15:07:30.559  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6972a6 added. We now have 9 listener(s)
08-04 15:07:30.559  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 15:07:30.561  4193  4209 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 15:07:30.561  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:07:30.562  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 15:07:30.568  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 15:07:30.575  4193  4209 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-04 15:07:30.575  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:07:30.575  4193  4212 D BtGatt.ScanManager: stopping BLe Batch
,08-04 15:07:30.582  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 15:07:30.582  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:30.582  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:30.582  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:07:30.582  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:07:30.582  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:07:30.582  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:07:30.582  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 15:07:30.586  4193  4209 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-04 15:07:30.586  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:07:30.587  4193  4212 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-04 15:07:30.588  3859  3907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 15:07:30.589  3859  3907 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-04 15:07:30.589  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 15:07:30.590  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71ff894 added. We now have 3 listener(s),
,08-04 15:07:30.595  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 15:07:30.595  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 15:07:30.595  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 15:07:30.595  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:07:30.596  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 15:07:30.596  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd21f3d added. We now have 10 listener(s)
08-04 15:07:30.596  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 15:07:30.596  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 15:07:30.598  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 15:07:30.598  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-04 15:07:30.598  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 15:07:30.598  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 15:07:30.598  4193  4209 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 15:07:30.599  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:07:30.599  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 15:07:30.602  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 15:07:30.606  3859  3907 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-04 15:07:30.606  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 15:07:30.616  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 15:07:30.617  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-04 15:07:30.618  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 15:07:30.623  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-04 15:07:30.623  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 15:07:30.623  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-04 15:07:30.624  3859  3907 D BluetoothAdapter: STATE_ON
,08-04 15:07:30.628  4193  4203 D BtGatt.GattService: registerClient() - UUID=fba46300-9637-42dc-84a3-067fef417f7a
,08-04 15:07:30.628  4193  4209 D BtGatt.GattService: onClientRegistered() - UUID=fba46300-9637-42dc-84a3-067fef417f7a, clientIf=5
,08-04 15:07:30.629  3859  3870 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 15:07:30.629  4193  4204 D BtGatt.GattService: start scan with filters
,08-04 15:07:30.634  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 15:07:30.635  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-04 15:07:30.635  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 15:07:30.635  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 15:07:30.636  4193  4212 D BtGatt.ScanManager: handling starting scan
,08-04 15:07:30.643  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 15:07:30.643  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-04 15:07:30.644  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 15:07:30.647  4193  4209 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 15:07:30.648  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:07:30.648  4193  4212 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 15:07:30.650  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 15:07:30.658  4193  4209 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-04 15:07:30.658  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:07:30.658  4193  4212 D BtGatt.ScanManager: Starting BLE batch scan
08-04 15:07:30.658  4193  4212 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 15:07:30.660  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 15:07:30.660  3859  3907 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-04 15:07:30.661  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:07:30.661  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:07:30.661  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 15:07:30.662  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:07:30.662  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.663  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 15:07:30.663  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 15:07:30.663  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@464401 removed from the list
08-04 15:07:30.663  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:07:30.664  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6972a6 removed from the list
08-04 15:07:30.664  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 15:07:30.664  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 15:07:30.667  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.667  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-04 15:07:30.667  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 15:07:30.667  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 15:07:30.670  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:07:30.670  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 15:07:30.670  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:07:30.671  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6972a6 not in the list
,08-04 15:07:30.671  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 15:07:30.671  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 15:07:30.671  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 15:07:30.671  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 15:07:30.671  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-04 15:07:30.673  3859  3907 D BluetoothAdapter: STATE_ON
08-04 15:07:30.674  4193  4203 D BtGatt.GattService: stopScan() - queue size =1
,08-04 15:07:30.675  4193  4232 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 15:07:30.676  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 15:07:30.676  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 15:07:30.676  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-04 15:07:30.676  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 15:07:30.676  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 15:07:30.677  4193  4209 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 15:07:30.677  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:07:30.679  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 15:07:30.679  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-04 15:07:30.679  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 15:07:30.680  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 15:07:30.681  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 15:07:30.684  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 15:07:30.684  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:07:30.684  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:07:30.684  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 15:07:30.685  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd21f3d removed from the list
,08-04 15:07:30.685  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:07:30.685  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-04 15:07:30.685  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.685  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:07:30.685  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 15:07:30.685  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 15:07:30.685  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71ff894 removed from the list
,08-04 15:07:30.686  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 15:07:30.687  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f467239 added. We now have 2 listener(s)
08-04 15:07:30.689  4193  4209 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 15:07:30.689  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:07:30.691  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 15:07:30.691  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
,08-04 15:07:30.691  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 15:07:30.692  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 15:07:30.692  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e2307e added. We now have 9 listener(s)
08-04 15:07:30.692  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 15:07:30.693  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 15:07:30.696  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 15:07:30.700  4193  4209 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 15:07:30.700  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:07:30.701  4193  4212 D BtGatt.ScanManager: stopping BLe Batch
08-04 15:07:30.703  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 15:07:30.703  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:30.703  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:30.703  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:07:30.703  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:07:30.703  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:07:30.703  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:07:30.703  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 15:07:30.706  3859  3907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 15:07:30.706  3859  3907 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 15:07:30.706  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 15:07:30.706  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@589c62c added. We now have 3 listener(s)
,08-04 15:07:30.708  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 15:07:30.708  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 15:07:30.708  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 15:07:30.708  4193  4209 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 15:07:30.708  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 15:07:30.708  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:07:30.708  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@812f8f5 added. We now have 10 listener(s)
08-04 15:07:30.708  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 15:07:30.708  4193  4212 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 15:07:30.708  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 15:07:30.708  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 15:07:30.709  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 15:07:30.709  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 15:07:30.709  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 15:07:30.709  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:30.713  3859  3907 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-04 15:07:30.714  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 15:07:30.715  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:30.715  4193  4209 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 15:07:30.715  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:07:30.722  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 15:07:30.722  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 15:07:30.722  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 15:07:30.728  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 15:07:30.729  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 15:07:30.729  3859  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-04 15:07:30.730  3859  3907 D BluetoothAdapter: STATE_ON
,08-04 15:07:30.734  4193  4204 D BtGatt.GattService: registerClient() - UUID=d67b4d2c-4a9f-46c3-8cfd-8a945c066527
,08-04 15:07:30.734  4193  4209 D BtGatt.GattService: onClientRegistered() - UUID=d67b4d2c-4a9f-46c3-8cfd-8a945c066527, clientIf=5
08-04 15:07:30.735  3859  3869 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-04 15:07:30.735  4193  4221 D BtGatt.GattService: start scan with filters
,08-04 15:07:30.742  4193  4212 D BtGatt.ScanManager: handling starting scan
,08-04 15:07:30.743  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-04 15:07:30.743  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 15:07:30.743  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 15:07:30.743  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 15:07:30.746  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 15:07:30.746  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 15:07:30.746  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 15:07:30.749  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 15:07:30.755  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 15:07:30.755  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 15:07:30.755  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:07:30.755  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:07:30.755  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.756  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-04 15:07:30.756  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 15:07:30.756  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f467239 removed from the list
,08-04 15:07:30.756  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:07:30.756  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e2307e removed from the list
08-04 15:07:30.756  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 15:07:30.756  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 15:07:30.756  4193  4209 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 15:07:30.756  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:07:30.757  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.756  4193  4212 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 15:07:30.757  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-04 15:07:30.757  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.757  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 15:07:30.758  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:07:30.758  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:07:30.758  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 15:07:30.758  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e2307e not in the list
08-04 15:07:30.758  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 15:07:30.759  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 15:07:30.759  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 15:07:30.759  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-04 15:07:30.759  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 15:07:30.760  3859  3907 D BluetoothAdapter: STATE_ON
08-04 15:07:30.761  4193  4221 D BtGatt.GattService: stopScan() - queue size =1
08-04 15:07:30.762  4193  4203 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 15:07:30.763  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-04 15:07:30.763  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 15:07:30.763  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 15:07:30.764  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 15:07:30.764  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-04 15:07:30.766  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 15:07:30.766  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 15:07:30.767  3859  3907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-04 15:07:30.767  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 15:07:30.769  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 15:07:30.770  4193  4209 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 15:07:30.770  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:07:30.770  4193  4212 D BtGatt.ScanManager: Starting BLE batch scan
,08-04 15:07:30.770  4193  4212 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-04 15:07:30.772  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 15:07:30.772  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 15:07:30.773  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 15:07:30.773  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:07:30.773  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 15:07:30.773  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 15:07:30.773  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@812f8f5 removed from the list
08-04 15:07:30.773  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:07:30.773  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.773  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 15:07:30.773  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 15:07:30.773  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@589c62c removed from the list
,08-04 15:07:30.776  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 15:07:30.777  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e72f71 added. We now have 2 listener(s)
,08-04 15:07:30.779  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 15:07:30.779  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 15:07:30.780  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 15:07:30.780  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 15:07:30.780  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@949d156 added. We now have 9 listener(s)
,08-04 15:07:30.780  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 15:07:30.783  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 15:07:30.784  4193  4209 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 15:07:30.784  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:07:30.787  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 15:07:30.791  3859  3907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 15:07:30.791  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 15:07:30.791  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 15:07:30.791  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 15:07:30.791  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 15:07:30.791  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 15:07:30.791  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 15:07:30.791  3859  3907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 15:07:30.793  4193  4209 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-04 15:07:30.793  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 15:07:30.795  3859  3907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 15:07:30.796  3859  3907 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 15:07:30.797  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 15:07:30.797  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7caec4 added. We now have 3 listener(s)
08-04 15:07:30.800  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 15:07:30.800  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 15:07:30.800  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 15:07:30.800  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 15:07:30.800  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:30.800  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ee51ad added. We now have 10 listener(s)
08-04 15:07:30.800  3859  3907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 15:07:30.800  4193  4209 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 15:07:30.800  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:07:30.801  3859  3907 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 15:07:30.801  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 15:07:30.801  4193  4212 D BtGatt.ScanManager: stopping BLe Batch
08-04 15:07:30.801  3859  3907 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 15:07:30.801  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:07:30.801  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 15:07:30.801  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 15:07:30.801  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 15:07:30.801  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e72f71 removed from the list
08-04 15:07:30.801  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:07:30.801  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@949d156 removed from the list
,08-04 15:07:30.804  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 15:07:30.805  3859  3907 D io.jxcore.node.ConnectivityMonitor: stop
08-04 15:07:30.805  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:07:30.805  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 15:07:30.805  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:07:30.807  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 15:07:30.807  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:07:30.807  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:07:30.807  3859  3907 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@949d156 not in the list
08-04 15:07:30.807  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 15:07:30.807  4193  4209 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 15:07:30.807  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:07:30.807  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:07:30.807  4193  4212 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 15:07:30.809  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 15:07:30.809  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 15:07:30.810  3859  3907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 15:07:30.810  3859  3907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ee51ad removed from the list
08-04 15:07:30.810  3859  3907 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 15:07:30.810  3859  3907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 15:07:30.810  3859  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 15:07:30.811  3859  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 15:07:30.811  3859  3907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7caec4 removed from the list
,08-04 15:07:30.812  4193  4209 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 15:07:30.813  4193  4209 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 15:07:30.813  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-04 15:07:30.814  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-04 15:07:30.814  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-04 15:07:30.814  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 15:07:30.815  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-04 15:07:30.815  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-04 15:07:30.831  3859  4283 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 468, name: My test thread name)
,08-04 15:07:31.036  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 15:07:31.186  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 15:07:31.273  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 15:07:32.830  3859  3907 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 468
,08-04 15:07:32.831  3859  3907 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 468, name: My test thread name)
,08-04 15:07:32.837  3859  4284 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 469, name: My test thread name)
,08-04 15:07:32.837  3859  4284 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 469, thread name: My test thread name)
,08-04 15:07:32.838  3859  4284 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 469, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-04 15:07:32.842  3859  3907 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-04 15:07:32.851  3859  4285 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 473, name: My test thread name)
,08-04 15:07:32.853  3859  4285 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 473, thread name: My test thread name): Test exception.
,08-04 15:07:32.853  3859  4285 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 473, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-04 15:07:32.856  3859  3907 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
,08-04 15:07:32.856  3859  3907 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 82
,08-04 15:07:32.857  3859  3907 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-04 15:07:32.857  3859  3907 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-04 15:07:32.857  3859  3907 D com.test.thalitest.ThaliTestRunner: Total duration: 36067 ms
,08-04 15:07:32.863  3859  3907 I jxcore-log: Total number of executed tests:  82
08-04 15:07:32.863  3859  3907 I jxcore-log: 
,08-04 15:07:32.864  3859  3907 I jxcore-log: Number of passed tests:  82
08-04 15:07:32.864  3859  3907 I jxcore-log: 
,08-04 15:07:32.864  3859  3907 I jxcore-log: Number of failed tests:  0
08-04 15:07:32.864  3859  3907 I jxcore-log: 
,08-04 15:07:32.865  3859  3907 I jxcore-log: Number of ignored tests:  0
08-04 15:07:32.865  3859  3907 I jxcore-log: 
,08-04 15:07:32.866  3859  3907 I jxcore-log: Total duration:  36067
08-04 15:07:32.866  3859  3907 I jxcore-log: 
08-04 15:07:32.871  3859  4283 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 468, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,08-04 15:07:32.874  3859  3907 I jxcore-log: Unit Test app is loaded
08-04 15:07:32.874  3859  3907 I jxcore-log: 
,08-04 15:07:32.898  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.898  3859  3907 I jxcore-log: 
,08-04 15:07:32.901  3859  3859 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-04 15:07:32.910  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.910  3859  3907 I jxcore-log: 
,08-04 15:07:32.911  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.911  3859  3907 I jxcore-log: 
,08-04 15:07:32.912  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.912  3859  3907 I jxcore-log: 
,08-04 15:07:32.913  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.913  3859  3907 I jxcore-log: 
,08-04 15:07:32.915  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.915  3859  3907 I jxcore-log: 
,08-04 15:07:32.917  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.917  3859  3907 I jxcore-log: 
,08-04 15:07:32.919  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 15:07:32.919  3859  3907 I jxcore-log: 
,08-04 15:07:32.920  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 15:07:32.920  3859  3907 I jxcore-log: 
,08-04 15:07:32.921  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 15:07:32.921  3859  3907 I jxcore-log: 
,08-04 15:07:32.922  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 15:07:32.922  3859  3907 I jxcore-log: 
,08-04 15:07:32.923  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 15:07:32.923  3859  3907 I jxcore-log: 
,08-04 15:07:32.924  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 15:07:32.924  3859  3907 I jxcore-log: 
,08-04 15:07:32.925  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 15:07:32.925  3859  3907 I jxcore-log: 
08-04 15:07:32.926  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.926  3859  3907 I jxcore-log: 
08-04 15:07:32.927  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.927  3859  3907 I jxcore-log: 
08-04 15:07:32.927  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 15:07:32.927  3859  3907 I jxcore-log: 
08-04 15:07:32.928  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 15:07:32.928  3859  3907 I jxcore-log: 
,08-04 15:07:32.929  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 15:07:32.929  3859  3907 I jxcore-log: 
08-04 15:07:32.930  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 15:07:32.930  3859  3907 I jxcore-log: 
,08-04 15:07:32.932  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 15:07:32.932  3859  3907 I jxcore-log: 
,08-04 15:07:32.933  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 15:07:32.933  3859  3907 I jxcore-log: 
,08-04 15:07:32.934  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 15:07:32.934  3859  3907 I jxcore-log: 
,08-04 15:07:32.935  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 15:07:32.935  3859  3907 I jxcore-log: 
08-04 15:07:32.935  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 15:07:32.935  3859  3907 I jxcore-log: ,
,08-04 15:07:32.936  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 15:07:32.936  3859  3907 I jxcore-log: 
08-04 15:07:32.937  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 15:07:32.937  3859  3907 I jxcore-log: 
,08-04 15:07:32.938  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 15:07:32.938  3859  3907 I jxcore-log: 
08-04 15:07:32.939  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.939  3859  3907 I jxcore-log: 
,08-04 15:07:32.939  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.939  3859  3907 I jxcore-log: 
,08-04 15:07:32.940  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.940  3859  3907 I jxcore-log: 
,08-04 15:07:32.941  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.941  3859  3907 I jxcore-log: 
08-04 15:07:32.942  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.942  3859  3907 I jxcore-log: 
08-04 15:07:32.943  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 15:07:32.943  3859  3907 I jxcore-log: 
,08-04 15:07:32.943  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 15:07:32.943  3859  3907 I jxcore-log: 
08-04 15:07:32.944  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 15:07:32.944  3859  3907 I jxcore-log: 
08-04 15:07:32.945  3859  3907 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 15:07:32.945  3859  3907 I jxcore-log: 
,08-04 15:07:32.952  3859  3907 I jxcore-log: My device name is: motorola-Nexus 6
08-04 15:07:32.952  3859  3907 I jxcore-log: 
,08-04 15:07:35.244  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-04 15:07:35.244  3859  3907 I jxcore-log: 
,08-04 15:07:35.863  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-04 15:07:35.863  3859  3907 I jxcore-log: 
,08-04 15:07:35.888  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-04 15:07:35.888  3859  3907 I jxcore-log: 
,08-04 15:07:37.238  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-04 15:07:37.238  3859  3907 I jxcore-log: 
,08-04 15:07:37.465  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-04 15:07:37.465  3859  3907 I jxcore-log: 
,08-04 15:07:37.470  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeTestMethod.js
08-04 15:07:37.470  3859  3907 I jxcore-log: 
,08-04 15:07:37.474  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-04 15:07:37.474  3859  3907 I jxcore-log: 
,08-04 15:07:37.491  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-04 15:07:37.491  3859  3907 I jxcore-log: 
,08-04 15:07:37.496  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-04 15:07:37.496  3859  3907 I jxcore-log: 
,08-04 15:07:38.166  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-04 15:07:38.166  3859  3907 I jxcore-log: 
,08-04 15:07:38.179  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-04 15:07:38.179  3859  3907 I jxcore-log: 
,08-04 15:07:38.190  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-04 15:07:38.190  3859  3907 I jxcore-log: 
,08-04 15:07:38.197  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-04 15:07:38.197  3859  3907 I jxcore-log: 
,08-04 15:07:38.245  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-04 15:07:38.245  3859  3907 I jxcore-log: 
,08-04 15:07:38.299  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-04 15:07:38.299  3859  3907 I jxcore-log: 
,08-04 15:07:38.307  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-04 15:07:38.307  3859  3907 I jxcore-log: 
,08-04 15:07:38.470  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-04 15:07:38.470  3859  3907 I jxcore-log: 
,08-04 15:07:38.497  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-04 15:07:38.497  3859  3907 I jxcore-log: 
,08-04 15:07:38.503  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-04 15:07:38.503  3859  3907 I jxcore-log: 
,08-04 15:07:38.508  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-04 15:07:38.508  3859  3907 I jxcore-log: 
,08-04 15:07:38.527  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-04 15:07:38.527  3859  3907 I jxcore-log: 
,08-04 15:07:38.612  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-04 15:07:38.612  3859  3907 I jxcore-log: 
,08-04 15:07:38.624  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-04 15:07:38.624  3859  3907 I jxcore-log: 
,08-04 15:07:38.651  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-04 15:07:38.651  3859  3907 I jxcore-log: 
,08-04 15:07:38.664  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-04 15:07:38.664  3859  3907 I jxcore-log: 
,08-04 15:07:38.683  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-04 15:07:38.683  3859  3907 I jxcore-log: 
,08-04 15:07:38.719  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-04 15:07:38.719  3859  3907 I jxcore-log: 
,08-04 15:07:38.920  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-04 15:07:38.920  3859  3907 I jxcore-log: 
,08-04 15:07:38.948  3859  3907 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-04 15:07:38.948  3859  3907 I jxcore-log: 
,08-04 15:07:38.958  3859  3907 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-04 15:07:38.960  3859  3907 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-04 15:07:38.960  3859  3907 I jxcore-log: 
,08-04 15:07:39.006  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 15:07:39.006  3859  3907 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
08-04 15:07:39.007  3859  3907 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 15:07:39.007  3859  3907 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-04 15:07:39.041  1662  1788 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-04 15:07:39.042  1662  1788 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-04 15:07:39.080  1517  1517 I ConfigService: onCreate
,08-04 15:07:44.128  1517  1517 I ConfigService: onDestroy
,08-04 15:07:50.278  3859  3907 I jxcore-log: TAP version 13
08-04 15:07:50.278  3859  3907 I jxcore-log: 
,08-04 15:07:50.283  3859  3907 I jxcore-log: # setup
08-04 15:07:50.283  3859  3907 I jxcore-log: 
,08-04 15:07:50.342  3859  3907 I jxcore-log: # 1. calling createNativeListener directly rejects
08-04 15:07:50.342  3859  3907 I jxcore-log: 
,08-04 15:07:51.008  3859  3907 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 15:07:51.008  3859  3907 I jxcore-log: 
08-04 15:07:51.012  3859  3907 I jxcore-log: DEBUG createNativeListener: listening 49845
08-04 15:07:51.012  3859  3907 I jxcore-log: 
,08-04 15:07:51.019  3859  3907 I jxcore-log: ok 1 Should throw
08-04 15:07:51.019  3859  3907 I jxcore-log: 
,08-04 15:07:51.022  3859  3907 I jxcore-log: # teardown
08-04 15:07:51.022  3859  3907 I jxcore-log: 
,08-04 15:07:51.941  3859  3907 I jxcore-log: # setup
08-04 15:07:51.941  3859  3907 I jxcore-log: 
,08-04 15:07:55.213  3859  3907 I jxcore-log: # 2. emits incomingConnectionState
08-04 15:07:55.213  3859  3907 I jxcore-log: 
,08-04 15:07:56.115  3859  3907 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 15:07:56.115  3859  3907 I jxcore-log: 
,08-04 15:07:56.118  3859  3907 I jxcore-log: DEBUG createNativeListener: listening 43460
08-04 15:07:56.118  3859  3907 I jxcore-log: 
,08-04 15:07:56.128  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:07:56.128  3859  3907 I jxcore-log: 
,08-04 15:07:56.131  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:07:56.131  3859  3907 I jxcore-log: 
,08-04 15:07:56.141  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:07:56.141  3859  3907 I jxcore-log: 
,08-04 15:07:56.147  3859  3907 I jxcore-log: ok 2 initial connection state should be CONNECTED
08-04 15:07:56.147  3859  3907 I jxcore-log: 
,08-04 15:07:56.174  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:07:56.174  3859  3907 I jxcore-log: 
,08-04 15:07:56.175  3859  3907 I jxcore-log: ok 3 final connection state should be DISCONNECTED
08-04 15:07:56.175  3859  3907 I jxcore-log: 
,08-04 15:07:56.183  3859  3907 I jxcore-log: # teardown
08-04 15:07:56.183  3859  3907 I jxcore-log: 
,08-04 15:08:00.961  3859  3907 I jxcore-log: # setup
08-04 15:08:00.961  3859  3907 I jxcore-log: 
,08-04 15:08:02.226  3859  3907 I jxcore-log: # 3. emits routerPortConnectionFailed
08-04 15:08:02.226  3859  3907 I jxcore-log: 
,08-04 15:08:05.800  3859  3907 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 15:08:05.800  3859  3907 I jxcore-log: 
,08-04 15:08:05.803  3859  3907 I jxcore-log: DEBUG createNativeListener: listening 38415
08-04 15:08:05.803  3859  3907 I jxcore-log: 
,08-04 15:08:05.817  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:05.817  3859  3907 I jxcore-log: 
,08-04 15:08:05.822  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:05.822  3859  3907 I jxcore-log: 
,08-04 15:08:05.827  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:05.827  3859  3907 I jxcore-log: 
,08-04 15:08:05.862  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:05.862  3859  3907 I jxcore-log: 
,08-04 15:08:05.866  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:05.866  3859  3907 I jxcore-log: 
,08-04 15:08:05.874  3859  3907 I jxcore-log: DEBUG createNativeListener: 
08-04 15:08:05.874  3859  3907 I jxcore-log: 
,08-04 15:08:05.875  3859  3907 I jxcore-log: ok 4 tried to connect to right port
08-04 15:08:05.875  3859  3907 I jxcore-log: 
,08-04 15:08:05.876  3859  3907 I jxcore-log: ok 5 failed due to refused connection
08-04 15:08:05.876  3859  3907 I jxcore-log: 
08-04 15:08:05.877  3859  3907 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
08-04 15:08:05.877  3859  3907 I jxcore-log: 
,08-04 15:08:05.880  3859  3907 I jxcore-log: # teardown
08-04 15:08:05.880  3859  3907 I jxcore-log: 
08-04 15:08:05.882  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:05.882  3859  3907 I jxcore-log: 
,08-04 15:08:10.249  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:10.249  3859  3907 I jxcore-log: 
,08-04 15:08:10.261  3859  3907 I jxcore-log: # setup
08-04 15:08:10.261  3859  3907 I jxcore-log: 
,08-04 15:08:10.262  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:10.262  3859  3907 I jxcore-log: 
,08-04 15:08:27.553  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 15:08:27.555  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 15:08:27.567  3794  4300 V GoogleAuthProtoRequest: [329] a.<init>: mAccountName set to: thalitester@gmail.com
,08-04 15:08:27.586  1517  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-04 15:08:27.586  1517  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-04 15:08:27.586  1517  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 15:08:27.586  1517  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 15:08:27.599  3794  4300 W ExperimentUpdateService: [329] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-04 15:08:27.599  3794  4300 W ExperimentUpdateService: [329] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-04 15:08:27.599  3794  4300 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-04 15:08:27.599  3794  4300 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-04 15:08:27.599  3794  4300 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-04 15:08:27.599  3794  4300 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-04 15:08:27.599  3794  4300 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-04 15:08:27.599  3794  4300 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-04 15:08:27.599  3794  4300 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-04 15:08:27.599  3794  4300 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-04 15:08:27.599  3794  4300 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-04 15:08:27.599  3794  4300 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-04 15:08:28.386  3859  3907 I jxcore-log: # 4. native server connections all up
08-04 15:08:28.386  3859  3907 I jxcore-log: 
,08-04 15:08:33.602  3859  3907 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 15:08:33.602  3859  3907 I jxcore-log: 
,08-04 15:08:33.605  3859  3907 I jxcore-log: DEBUG createNativeListener: listening 46934
08-04 15:08:33.605  3859  3907 I jxcore-log: 
,08-04 15:08:33.613  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:33.613  3859  3907 I jxcore-log: 
,08-04 15:08:33.615  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:33.615  3859  3907 I jxcore-log: 
,08-04 15:08:33.616  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:33.616  3859  3907 I jxcore-log: 
,08-04 15:08:33.647  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:33.647  3859  3907 I jxcore-log: 
,08-04 15:08:33.651  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:33.651  3859  3907 I jxcore-log: 
,08-04 15:08:33.655  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:33.655  3859  3907 I jxcore-log: 
,08-04 15:08:33.657  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:33.657  3859  3907 I jxcore-log: 
,08-04 15:08:33.681  3859  3907 I jxcore-log: ok 7 Send/recvd #1 should be equal length
08-04 15:08:33.681  3859  3907 I jxcore-log: 
,08-04 15:08:33.682  3859  3907 I jxcore-log: ok 8 Send/recvd #1 should be same
08-04 15:08:33.682  3859  3907 I jxcore-log: 
,08-04 15:08:33.684  3859  3907 I jxcore-log: ok 9 Send/recvd #2 should be equal length
08-04 15:08:33.684  3859  3907 I jxcore-log: 
08-04 15:08:33.685  3859  3907 I jxcore-log: ok 10 Send/recvd #2 should be same
08-04 15:08:33.685  3859  3907 I jxcore-log: 
,08-04 15:08:33.687  3859  3907 I jxcore-log: ok 11 Should be exactly 2 client sockets
08-04 15:08:33.687  3859  3907 I jxcore-log: 
,08-04 15:08:33.694  3859  3907 I jxcore-log: # teardown
08-04 15:08:33.694  3859  3907 I jxcore-log: 
,08-04 15:08:48.577  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:48.577  3859  3907 I jxcore-log: 
,08-04 15:08:48.586  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:48.586  3859  3907 I jxcore-log: 
,08-04 15:08:48.588  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:48.588  3859  3907 I jxcore-log: 
,08-04 15:08:48.592  3859  3907 I jxcore-log: # setup
08-04 15:08:48.592  3859  3907 I jxcore-log: 
,08-04 15:08:48.593  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:48.593  3859  3907 I jxcore-log: 
,08-04 15:08:49.062  3859  3907 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
08-04 15:08:49.062  3859  3907 I jxcore-log: 
,08-04 15:08:50.081  3859  3907 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 15:08:50.081  3859  3907 I jxcore-log: 
,08-04 15:08:50.089  3859  3907 I jxcore-log: DEBUG createNativeListener: listening 45734
08-04 15:08:50.089  3859  3907 I jxcore-log: 
,08-04 15:08:50.103  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:50.103  3859  3907 I jxcore-log: 
,08-04 15:08:50.106  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:50.106  3859  3907 I jxcore-log: 
,08-04 15:08:50.109  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:50.109  3859  3907 I jxcore-log: 
,08-04 15:08:50.133  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:50.133  3859  3907 I jxcore-log: 
,08-04 15:08:50.137  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:50.137  3859  3907 I jxcore-log: 
,08-04 15:08:50.152  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:50.152  3859  3907 I jxcore-log: 
,08-04 15:08:50.169  3859  3907 I jxcore-log: ok 12 socket shouldn't close until after stream
08-04 15:08:50.169  3859  3907 I jxcore-log: 
,08-04 15:08:50.170  3859  3907 I jxcore-log: ok 13 incoming remains open
08-04 15:08:50.170  3859  3907 I jxcore-log: 
,08-04 15:08:50.174  3859  3907 I jxcore-log: # teardown
08-04 15:08:50.174  3859  3907 I jxcore-log: 
,08-04 15:08:50.251  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:50.251  3859  3907 I jxcore-log: 
,08-04 15:08:50.256  3859  3907 I jxcore-log: # setup
08-04 15:08:50.256  3859  3907 I jxcore-log: 
,08-04 15:08:50.257  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:50.257  3859  3907 I jxcore-log: 
,08-04 15:08:50.378  3859  3907 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
08-04 15:08:50.378  3859  3907 I jxcore-log: 
,08-04 15:08:50.458  3859  3907 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 15:08:50.458  3859  3907 I jxcore-log: 
,08-04 15:08:50.465  3859  3907 I jxcore-log: DEBUG createNativeListener: listening 44287
08-04 15:08:50.465  3859  3907 I jxcore-log: 
,08-04 15:08:50.472  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:50.472  3859  3907 I jxcore-log: 
,08-04 15:08:50.473  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:50.473  3859  3907 I jxcore-log: 
,08-04 15:08:50.475  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:50.475  3859  3907 I jxcore-log: 
,08-04 15:08:50.486  3859  3907 I jxcore-log: ok 14 we should not have gotten an error
08-04 15:08:50.486  3859  3907 I jxcore-log: 
,08-04 15:08:50.494  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:50.494  3859  3907 I jxcore-log: 
,08-04 15:08:50.500  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:50.500  3859  3907 I jxcore-log: 
,08-04 15:08:50.526  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:50.526  3859  3907 I jxcore-log: 
,08-04 15:08:50.533  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:50.533  3859  3907 I jxcore-log: 
,08-04 15:08:50.542  3859  3907 I jxcore-log: ok 15 socket shouldn't close until after incoming
08-04 15:08:50.542  3859  3907 I jxcore-log: 
08-04 15:08:50.542  3859  3907 I jxcore-log: ok 16 incoming is cleaned up
08-04 15:08:50.542  3859  3907 I jxcore-log: 
,08-04 15:08:50.545  3859  3907 I jxcore-log: # teardown
08-04 15:08:50.545  3859  3907 I jxcore-log: 
,08-04 15:08:50.666  3859  3907 I jxcore-log: # setup
08-04 15:08:50.666  3859  3907 I jxcore-log: 
,08-04 15:08:50.776  3859  3907 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
08-04 15:08:50.776  3859  3907 I jxcore-log: 
,08-04 15:08:50.867  3859  3907 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 15:08:50.867  3859  3907 I jxcore-log: 
,08-04 15:08:50.876  3859  3907 I jxcore-log: DEBUG createNativeListener: listening 37216
08-04 15:08:50.876  3859  3907 I jxcore-log: 
,08-04 15:08:50.888  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:50.888  3859  3907 I jxcore-log: 
,08-04 15:08:50.890  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:50.890  3859  3907 I jxcore-log: 
,08-04 15:08:50.893  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:50.893  3859  3907 I jxcore-log: 
,08-04 15:08:50.908  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:50.908  3859  3907 I jxcore-log: 
,08-04 15:08:50.911  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:50.911  3859  3907 I jxcore-log: 
,08-04 15:08:50.933  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:50.933  3859  3907 I jxcore-log: 
,08-04 15:08:50.943  3859  3907 I jxcore-log: ok 17 stream was closed
08-04 15:08:50.943  3859  3907 I jxcore-log: 
,08-04 15:08:50.944  3859  3907 I jxcore-log: ok 18 incoming should survive
08-04 15:08:50.944  3859  3907 I jxcore-log: 
,08-04 15:08:50.944  3859  3907 I jxcore-log: ok 19 mux should have no streams
08-04 15:08:50.944  3859  3907 I jxcore-log: 
,08-04 15:08:50.950  3859  3907 I jxcore-log: # teardown
08-04 15:08:50.950  3859  3907 I jxcore-log: 
,08-04 15:08:51.010  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:51.010  3859  3907 I jxcore-log: 
,08-04 15:08:51.015  3859  3907 I jxcore-log: # setup
08-04 15:08:51.015  3859  3907 I jxcore-log: 
,08-04 15:08:51.017  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:51.017  3859  3907 I jxcore-log: 
,08-04 15:08:51.072  3859  3907 I jxcore-log: # 8. native server - closing the whole server cleans everything up
08-04 15:08:51.072  3859  3907 I jxcore-log: 
,08-04 15:08:51.166  3859  3907 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 15:08:51.166  3859  3907 I jxcore-log: 
,08-04 15:08:51.169  3859  3907 I jxcore-log: DEBUG createNativeListener: listening 45763
08-04 15:08:51.169  3859  3907 I jxcore-log: 
,08-04 15:08:51.176  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:51.176  3859  3907 I jxcore-log: 
,08-04 15:08:51.178  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:51.178  3859  3907 I jxcore-log: 
,08-04 15:08:51.179  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:51.179  3859  3907 I jxcore-log: 
,08-04 15:08:51.189  3859  3907 I jxcore-log: ok 20 we should not have gotten an error
08-04 15:08:51.189  3859  3907 I jxcore-log: 
,08-04 15:08:51.205  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:51.205  3859  3907 I jxcore-log: 
,08-04 15:08:51.208  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:51.208  3859  3907 I jxcore-log: 
,08-04 15:08:51.217  3859  3907 I jxcore-log: ok 21 Buffers are identical
08-04 15:08:51.217  3859  3907 I jxcore-log: 
,08-04 15:08:51.220  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:51.220  3859  3907 I jxcore-log: 
,08-04 15:08:51.222  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:51.222  3859  3907 I jxcore-log: 
,08-04 15:08:51.224  3859  3907 I jxcore-log: ok 22 native server is nulled out
08-04 15:08:51.224  3859  3907 I jxcore-log: 
,08-04 15:08:51.225  3859  3907 I jxcore-log: ok 23 native server should be closed
08-04 15:08:51.225  3859  3907 I jxcore-log: 
,08-04 15:08:51.225  3859  3907 I jxcore-log: ok 24 incoming has been removed
08-04 15:08:51.225  3859  3907 I jxcore-log: 
08-04 15:08:51.225  3859  3907 I jxcore-log: ok 25 Incoming should be done
08-04 15:08:51.225  3859  3907 I jxcore-log: 
,08-04 15:08:51.226  3859  3907 I jxcore-log: ok 26 The mux object should be closed
08-04 15:08:51.226  3859  3907 I jxcore-log: 
08-04 15:08:51.226  3859  3907 I jxcore-log: ok 27 The mux stream should be closed
08-04 15:08:51.226  3859  3907 I jxcore-log: 
,08-04 15:08:51.227  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:51.227  3859  3907 I jxcore-log: 
,08-04 15:08:51.240  3859  3907 I jxcore-log: # teardown
08-04 15:08:51.240  3859  3907 I jxcore-log: 
,08-04 15:08:51.334  3859  3907 I jxcore-log: # setup
08-04 15:08:51.334  3859  3907 I jxcore-log: 
,08-04 15:08:51.466  3859  3907 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
08-04 15:08:51.466  3859  3907 I jxcore-log: 
,08-04 15:08:52.537  3859  3907 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 15:08:52.537  3859  3907 I jxcore-log: 
,08-04 15:08:52.545  3859  3907 I jxcore-log: DEBUG createNativeListener: listening 43775
08-04 15:08:52.545  3859  3907 I jxcore-log: 
,08-04 15:08:52.571  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:52.571  3859  3907 I jxcore-log: 
,08-04 15:08:52.573  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:52.573  3859  3907 I jxcore-log: 
08-04 15:08:52.574  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:52.574  3859  3907 I jxcore-log: 
,08-04 15:08:52.578  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:52.578  3859  3907 I jxcore-log: 
08-04 15:08:52.578  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:52.578  3859  3907 I jxcore-log: 
,08-04 15:08:52.580  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:52.580  3859  3907 I jxcore-log: 
,08-04 15:08:52.583  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:52.583  3859  3907 I jxcore-log: 
,08-04 15:08:52.583  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:52.583  3859  3907 I jxcore-log: 
08-04 15:08:52.585  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:52.585  3859  3907 I jxcore-log: 
,08-04 15:08:52.593  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:52.593  3859  3907 I jxcore-log: 
,08-04 15:08:52.594  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:52.594  3859  3907 I jxcore-log: 
,08-04 15:08:52.596  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:52.596  3859  3907 I jxcore-log: 
,08-04 15:08:52.599  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:52.599  3859  3907 I jxcore-log: 
,08-04 15:08:52.600  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:52.600  3859  3907 I jxcore-log: 
,08-04 15:08:52.601  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:52.601  3859  3907 I jxcore-log: 
,08-04 15:08:52.605  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:52.605  3859  3907 I jxcore-log: 
,08-04 15:08:52.610  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:52.610  3859  3907 I jxcore-log: 
,08-04 15:08:52.611  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:52.611  3859  3907 I jxcore-log: 
,08-04 15:08:52.615  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:52.615  3859  3907 I jxcore-log: 
,08-04 15:08:52.616  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:52.616  3859  3907 I jxcore-log: 
,08-04 15:08:52.617  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:52.617  3859  3907 I jxcore-log: 
08-04 15:08:52.618  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:52.618  3859  3907 I jxcore-log: 
,08-04 15:08:52.618  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:52.618  3859  3907 I jxcore-log: 
08-04 15:08:52.619  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:52.619  3859  3907 I jxcore-log: 
,08-04 15:08:52.621  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:52.621  3859  3907 I jxcore-log: 
08-04 15:08:52.621  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:52.621  3859  3907 I jxcore-log: 
,08-04 15:08:52.623  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:52.623  3859  3907 I jxcore-log: 
,08-04 15:08:52.624  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:52.624  3859  3907 I jxcore-log: 
08-04 15:08:52.625  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:52.625  3859  3907 I jxcore-log: 
08-04 15:08:52.625  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:52.625  3859  3907 I jxcore-log: 
,08-04 15:08:52.704  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.704  3859  3907 I jxcore-log: 
,08-04 15:08:52.707  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.707  3859  3907 I jxcore-log: 
,08-04 15:08:52.709  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.709  3859  3907 I jxcore-log: 
,08-04 15:08:52.711  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.711  3859  3907 I jxcore-log: 
,08-04 15:08:52.713  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.713  3859  3907 I jxcore-log: 
,08-04 15:08:52.715  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.715  3859  3907 I jxcore-log: 
,08-04 15:08:52.717  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.717  3859  3907 I jxcore-log: 
,08-04 15:08:52.719  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.719  3859  3907 I jxcore-log: 
,08-04 15:08:52.722  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.722  3859  3907 I jxcore-log: 
,08-04 15:08:52.724  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.724  3859  3907 I jxcore-log: 
,08-04 15:08:52.725  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.725  3859  3907 I jxcore-log: 
,08-04 15:08:52.727  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.727  3859  3907 I jxcore-log: 
08-04 15:08:52.728  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.728  3859  3907 I jxcore-log: 
,08-04 15:08:52.730  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.730  3859  3907 I jxcore-log: 
,08-04 15:08:52.732  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.732  3859  3907 I jxcore-log: 
,08-04 15:08:52.734  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.734  3859  3907 I jxcore-log: 
,08-04 15:08:52.736  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.736  3859  3907 I jxcore-log: 
,08-04 15:08:52.738  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.738  3859  3907 I jxcore-log: 
08-04 15:08:52.739  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.739  3859  3907 I jxcore-log: 
,08-04 15:08:52.741  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.741  3859  3907 I jxcore-log: 
,08-04 15:08:52.743  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.743  3859  3907 I jxcore-log: 
,08-04 15:08:52.746  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.746  3859  3907 I jxcore-log: 
,08-04 15:08:52.747  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.747  3859  3907 I jxcore-log: 
,08-04 15:08:52.750  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.750  3859  3907 I jxcore-log: 
,08-04 15:08:52.752  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.752  3859  3907 I jxcore-log: 
,08-04 15:08:52.754  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.754  3859  3907 I jxcore-log: 
08-04 15:08:52.755  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.755  3859  3907 I jxcore-log: 
,08-04 15:08:52.757  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.757  3859  3907 I jxcore-log: 
,08-04 15:08:52.758  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.758  3859  3907 I jxcore-log: 
,08-04 15:08:52.760  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.760  3859  3907 I jxcore-log: 
,08-04 15:08:52.761  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.761  3859  3907 I jxcore-log: 
,08-04 15:08:52.763  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.763  3859  3907 I jxcore-log: 
,08-04 15:08:52.765  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.765  3859  3907 I jxcore-log: 
,08-04 15:08:52.767  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.767  3859  3907 I jxcore-log: 
08-04 15:08:52.768  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.768  3859  3907 I jxcore-log: 
,08-04 15:08:52.770  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.770  3859  3907 I jxcore-log: 
,08-04 15:08:52.771  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.771  3859  3907 I jxcore-log: 
,08-04 15:08:52.773  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.773  3859  3907 I jxcore-log: 
,08-04 15:08:52.780  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.780  3859  3907 I jxcore-log: 
,08-04 15:08:52.782  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.782  3859  3907 I jxcore-log: 
,08-04 15:08:52.784  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.784  3859  3907 I jxcore-log: 
,08-04 15:08:52.787  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.787  3859  3907 I jxcore-log: 
,08-04 15:08:52.788  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.788  3859  3907 I jxcore-log: 
,08-04 15:08:52.789  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.789  3859  3907 I jxcore-log: 
08-04 15:08:52.790  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.790  3859  3907 I jxcore-log: 
,08-04 15:08:52.792  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.792  3859  3907 I jxcore-log: 
,08-04 15:08:52.793  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.793  3859  3907 I jxcore-log: 
,08-04 15:08:52.795  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.795  3859  3907 I jxcore-log: 
,08-04 15:08:52.797  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.797  3859  3907 I jxcore-log: 
08-04 15:08:52.799  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.799  3859  3907 I jxcore-log: 
,08-04 15:08:52.800  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.800  3859  3907 I jxcore-log: 
,08-04 15:08:52.802  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.802  3859  3907 I jxcore-log: 
08-04 15:08:52.803  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.803  3859  3907 I jxcore-log: 
,08-04 15:08:52.804  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.804  3859  3907 I jxcore-log: 
,08-04 15:08:52.805  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.805  3859  3907 I jxcore-log: 
,08-04 15:08:52.807  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.807  3859  3907 I jxcore-log: 
08-04 15:08:52.809  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.809  3859  3907 I jxcore-log: 
,08-04 15:08:52.811  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.811  3859  3907 I jxcore-log: 
08-04 15:08:52.812  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.812  3859  3907 I jxcore-log: 
,08-04 15:08:52.816  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.816  3859  3907 I jxcore-log: 
,08-04 15:08:52.820  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.820  3859  3907 I jxcore-log: 
,08-04 15:08:52.825  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.825  3859  3907 I jxcore-log: 
,08-04 15:08:52.830  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.830  3859  3907 I jxcore-log: 
,08-04 15:08:52.835  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.835  3859  3907 I jxcore-log: 
,08-04 15:08:52.841  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.841  3859  3907 I jxcore-log: 
,08-04 15:08:52.842  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.842  3859  3907 I jxcore-log: 
,08-04 15:08:52.844  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.844  3859  3907 I jxcore-log: 
,08-04 15:08:52.846  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.846  3859  3907 I jxcore-log: 
08-04 15:08:52.847  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.847  3859  3907 I jxcore-log: 
,08-04 15:08:52.849  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.849  3859  3907 I jxcore-log: 
,08-04 15:08:52.850  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.850  3859  3907 I jxcore-log: 
08-04 15:08:52.852  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.852  3859  3907 I jxcore-log: 
,08-04 15:08:52.854  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.854  3859  3907 I jxcore-log: 
,08-04 15:08:52.856  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.856  3859  3907 I jxcore-log: 
,08-04 15:08:52.857  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.857  3859  3907 I jxcore-log: 
,08-04 15:08:52.859  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.859  3859  3907 I jxcore-log: 
,08-04 15:08:52.861  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.861  3859  3907 I jxcore-log: 
,08-04 15:08:52.862  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.862  3859  3907 I jxcore-log: 
08-04 15:08:52.864  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:52.864  3859  3907 I jxcore-log: 
,08-04 15:08:52.866  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:52.866  3859  3907 I jxcore-log: 
,08-04 15:08:52.960  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.960  3859  3907 I jxcore-log: 
,08-04 15:08:52.962  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.962  3859  3907 I jxcore-log: 
08-04 15:08:52.963  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.963  3859  3907 I jxcore-log: 
,08-04 15:08:52.964  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.964  3859  3907 I jxcore-log: 
,08-04 15:08:52.971  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:52.971  3859  3907 I jxcore-log: 
,08-04 15:08:52.972  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.972  3859  3907 I jxcore-log: 
08-04 15:08:52.973  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.973  3859  3907 I jxcore-log: 
08-04 15:08:52.974  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.974  3859  3907 I jxcore-log: 
,08-04 15:08:52.975  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.975  3859  3907 I jxcore-log: 
,08-04 15:08:52.976  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:52.976  3859  3907 I jxcore-log: 
08-04 15:08:52.977  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.977  3859  3907 I jxcore-log: 
,08-04 15:08:52.980  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.980  3859  3907 I jxcore-log: 
08-04 15:08:52.981  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.981  3859  3907 I jxcore-log: 
,08-04 15:08:52.982  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.982  3859  3907 I jxcore-log: 
,08-04 15:08:52.984  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:52.984  3859  3907 I jxcore-log: 
,08-04 15:08:52.989  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.989  3859  3907 I jxcore-log: 
,08-04 15:08:52.991  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.991  3859  3907 I jxcore-log: 
08-04 15:08:52.992  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.992  3859  3907 I jxcore-log: 
,08-04 15:08:52.993  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.993  3859  3907 I jxcore-log: 
08-04 15:08:52.994  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:52.994  3859  3907 I jxcore-log: 
,08-04 15:08:52.994  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.994  3859  3907 I jxcore-log: 
08-04 15:08:52.995  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.995  3859  3907 I jxcore-log: 
,08-04 15:08:52.996  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.996  3859  3907 I jxcore-log: 
08-04 15:08:52.997  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.997  3859  3907 I jxcore-log: 
08-04 15:08:52.998  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:52.998  3859  3907 I jxcore-log: 
,08-04 15:08:52.999  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:52.999  3859  3907 I jxcore-log: 
08-04 15:08:53.000  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.000  3859  3907 I jxcore-log: 
,08-04 15:08:53.001  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.001  3859  3907 I jxcore-log: 
08-04 15:08:53.002  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.002  3859  3907 I jxcore-log: 
,08-04 15:08:53.003  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:53.003  3859  3907 I jxcore-log: 
08-04 15:08:53.004  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.004  3859  3907 I jxcore-log: 
,08-04 15:08:53.005  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.005  3859  3907 I jxcore-log: 
08-04 15:08:53.006  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.006  3859  3907 I jxcore-log: 
08-04 15:08:53.006  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.006  3859  3907 I jxcore-log: 
,08-04 15:08:53.007  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:53.007  3859  3907 I jxcore-log: 
08-04 15:08:53.008  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.008  3859  3907 I jxcore-log: 
08-04 15:08:53.009  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.009  3859  3907 I jxcore-log: 
,08-04 15:08:53.009  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.009  3859  3907 I jxcore-log: 
08-04 15:08:53.010  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.010  3859  3907 I jxcore-log: 
,08-04 15:08:53.011  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:53.011  3859  3907 I jxcore-log: 
08-04 15:08:53.012  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.012  3859  3907 I jxcore-log: 
08-04 15:08:53.013  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.013  3859  3907 I jxcore-log: 
,08-04 15:08:53.013  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.013  3859  3907 I jxcore-log: 
08-04 15:08:53.014  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.014  3859  3907 I jxcore-log: 
,08-04 15:08:53.015  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:53.015  3859  3907 I jxcore-log: 
08-04 15:08:53.016  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.016  3859  3907 I jxcore-log: 
08-04 15:08:53.016  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.016  3859  3907 I jxcore-log: 
,08-04 15:08:53.017  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.017  3859  3907 I jxcore-log: 
08-04 15:08:53.018  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:53.018  3859  3907 I jxcore-log: 
08-04 15:08:53.019  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:53.019  3859  3907 I jxcore-log: 
,08-04 15:08:53.022  3859  3907 I jxcore-log: ok 28 native server is nulled out
08-04 15:08:53.022  3859  3907 I jxcore-log: 
,08-04 15:08:53.022  3859  3907 I jxcore-log: ok 29 native server should be closed
08-04 15:08:53.022  3859  3907 I jxcore-log: 
08-04 15:08:53.023  3859  3907 I jxcore-log: ok 30 incoming has been removed
08-04 15:08:53.023  3859  3907 I jxcore-log: 
08-04 15:08:53.023  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:53.023  3859  3907 I jxcore-log: 
,08-04 15:08:53.024  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:53.024  3859  3907 I jxcore-log: 
08-04 15:08:53.025  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:53.025  3859  3907 I jxcore-log: 
08-04 15:08:53.025  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:53.025  3859  3907 I jxcore-log: 
,08-04 15:08:53.026  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:53.026  3859  3907 I jxcore-log: 
08-04 15:08:53.026  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:53.026  3859  3907 I jxcore-log: 
08-04 15:08:53.026  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:53.026  3859  3907 I jxcore-log: 
08-04 15:08:53.027  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:53.027  3859  3907 I jxcore-log: 
,08-04 15:08:53.027  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:53.027  3859  3907 I jxcore-log: 
08-04 15:08:53.027  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:53.027  3859  3907 I jxcore-log: 
,08-04 15:08:53.134  3859  3907 I jxcore-log: # teardown
08-04 15:08:53.134  3859  3907 I jxcore-log: 
,08-04 15:08:54.282  3859  3907 I jxcore-log: # setup
08-04 15:08:54.282  3859  3907 I jxcore-log: 
,08-04 15:08:54.344  3859  3907 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
08-04 15:08:54.344  3859  3907 I jxcore-log: 
,08-04 15:08:55.404  3859  3907 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 15:08:55.404  3859  3907 I jxcore-log: 
,08-04 15:08:55.411  3859  3907 I jxcore-log: DEBUG createNativeListener: listening 41637
08-04 15:08:55.411  3859  3907 I jxcore-log: 
,08-04 15:08:55.417  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:55.417  3859  3907 I jxcore-log: 
,08-04 15:08:55.419  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:55.419  3859  3907 I jxcore-log: 
,08-04 15:08:55.420  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:55.420  3859  3907 I jxcore-log: 
,08-04 15:08:55.427  3859  3907 I jxcore-log: ok 31 we should not have gotten an error
08-04 15:08:55.427  3859  3907 I jxcore-log: 
,08-04 15:08:55.434  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:55.434  3859  3907 I jxcore-log: 
,08-04 15:08:55.437  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:55.437  3859  3907 I jxcore-log: 
,08-04 15:08:55.444  3859  3907 I jxcore-log: ok 32 Buffers are identical
08-04 15:08:55.444  3859  3907 I jxcore-log: 
,08-04 15:08:55.445  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:55.445  3859  3907 I jxcore-log: 
,08-04 15:08:55.447  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:55.447  3859  3907 I jxcore-log: 
,08-04 15:08:55.458  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:55.458  3859  3907 I jxcore-log: 
,08-04 15:08:55.459  3859  3907 I jxcore-log: ok 33 server should be fine
08-04 15:08:55.459  3859  3907 I jxcore-log: 
08-04 15:08:55.460  3859  3907 I jxcore-log: ok 34 server should be open
08-04 15:08:55.460  3859  3907 I jxcore-log: 
,08-04 15:08:55.460  3859  3907 I jxcore-log: ok 35 incoming has been removed
08-04 15:08:55.460  3859  3907 I jxcore-log: 
08-04 15:08:55.461  3859  3907 I jxcore-log: ok 36 The mux object should be closed
08-04 15:08:55.461  3859  3907 I jxcore-log: 
08-04 15:08:55.461  3859  3907 I jxcore-log: ok 37 The mux stream should be closed
08-04 15:08:55.461  3859  3907 I jxcore-log: 
,08-04 15:08:55.466  3859  3907 I jxcore-log: # teardown
08-04 15:08:55.466  3859  3907 I jxcore-log: 
,08-04 15:08:55.919  3859  3907 I jxcore-log: # setup
08-04 15:08:55.919  3859  3907 I jxcore-log: 
,08-04 15:08:56.946  3859  3907 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
08-04 15:08:56.946  3859  3907 I jxcore-log: 
,08-04 15:08:57.004  3859  3907 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 15:08:57.004  3859  3907 I jxcore-log: 
,08-04 15:08:57.010  3859  3907 I jxcore-log: DEBUG createNativeListener: listening 47955
08-04 15:08:57.010  3859  3907 I jxcore-log: 
,08-04 15:08:57.019  3859  3907 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 15:08:57.019  3859  3907 I jxcore-log: 
,08-04 15:08:57.021  3859  3907 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 15:08:57.021  3859  3907 I jxcore-log: 
,08-04 15:08:57.023  3859  3907 I jxcore-log: DEBUG createNativeListener: new mux
08-04 15:08:57.023  3859  3907 I jxcore-log: 
,08-04 15:08:57.034  3859  3907 I jxcore-log: ok 38 we should not have gotten an error
08-04 15:08:57.034  3859  3907 I jxcore-log: 
,08-04 15:08:57.041  3859  3907 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 15:08:57.041  3859  3907 I jxcore-log: 
,08-04 15:08:57.043  3859  3907 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 15:08:57.043  3859  3907 I jxcore-log: 
,08-04 15:08:57.050  3859  3907 I jxcore-log: ok 39 Buffers are identical
08-04 15:08:57.050  3859  3907 I jxcore-log: 
,08-04 15:08:57.055  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
08-04 15:08:57.055  3859  3907 I jxcore-log: 
,08-04 15:08:57.056  3859  3907 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 15:08:57.056  3859  3907 I jxcore-log: 
,08-04 15:08:57.058  3859  3907 I jxcore-log: DEBUG createNativeListener: mux close
08-04 15:08:57.058  3859  3907 I jxcore-log: 
,08-04 15:08:57.062  3859  3907 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 15:08:57.062  3859  3907 I jxcore-log: 
,08-04 15:08:57.063  3859  3907 I jxcore-log: ok 40 server should be fine
08-04 15:08:57.063  3859  3907 I jxcore-log: 
08-04 15:08:57.063  3859  3907 I jxcore-log: ok 41 server should be open
08-04 15:08:57.063  3859  3907 I jxcore-log: 
08-04 15:08:57.064  3859  3907 I jxcore-log: ok 42 incoming has been removed
08-04 15:08:57.064  3859  3907 I jxcore-log: 
,08-04 15:08:57.064  3859  3907 I jxcore-log: ok 43 The mux object should be closed
08-04 15:08:57.064  3859  3907 I jxcore-log: 
08-04 15:08:57.065  3859  3907 I jxcore-log: ok 44 The mux stream should be closed
08-04 15:08:57.065  3859  3907 I jxcore-log: 
,08-04 15:08:57.071  3859  3907 I jxcore-log: # teardown
08-04 15:08:57.071  3859  3907 I jxcore-log: 
,08-04 15:08:57.224  3859  3907 I jxcore-log: # setup
08-04 15:08:57.224  3859  3907 I jxcore-log: 
,08-04 15:08:57.282  3859  3907 I jxcore-log: # 12. #_doImmediateSeqUpdate - server is not there
08-04 15:08:57.282  3859  3907 I jxcore-log: 
,08-04 15:08:57.460  3859  3907 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
08-04 15:08:57.460  3859  3907 I jxcore-log: 
,08-04 15:08:57.461  3859  3907 I jxcore-log: ok 45 Got right error
08-04 15:08:57.461  3859  3907 I jxcore-log: 
,08-04 15:08:57.466  3859  3907 I jxcore-log: # teardown
08-04 15:08:57.466  3859  3907 I jxcore-log: 
,08-04 15:08:57.639  3859  3907 I jxcore-log: # setup
08-04 15:08:57.639  3859  3907 I jxcore-log: 
,08-04 15:08:57.816  3859  3907 I jxcore-log: # 13. #_doImmediateSeqUpdate - server accepts & closes connection
08-04 15:08:57.816  3859  3907 I jxcore-log: 
,08-04 15:08:57.955  3859  3907 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
08-04 15:08:57.955  3859  3907 I jxcore-log: 
,08-04 15:08:57.956  3859  3907 I jxcore-log: ok 46 Got socket hang up
08-04 15:08:57.956  3859  3907 I jxcore-log: 
,08-04 15:08:57.959  3859  3907 I jxcore-log: # teardown
08-04 15:08:57.959  3859  3907 I jxcore-log: 
,08-04 15:08:58.060  3859  3907 I jxcore-log: # setup
08-04 15:08:58.060  3859  3907 I jxcore-log: ,
,08-04 15:08:58.112  3859  3907 I jxcore-log: # 14. #_doImmediateSeqUpdate - server always returns 500
08-04 15:08:58.112  3859  3907 I jxcore-log: 
,08-04 15:08:58.176  3859  3907 E jxcore  : Error!: Missing PFX or certificate + private key.
,08-04 15:08:58.176  3859  3907 E jxcore  : Stack: [{"_fileName":"tls.js","_functionName":"$0v","_lineNumber":"1065","_columnNumber":"1","_msg":"    at $0v@tls.js:1065:1"},{"_fileName":"https.js","_functionName":"$5","_lineNumber":"16","_columnNumber":"1","_msg":"    at $5@https.js:16:1"},{"_fileName":"https.js","_functionName":"exports.createServer","_lineNumber":"33","_columnNumber":"8","_msg":"    at exports.createServer@https.js:33:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js","_functionName":"","_lineNumber":"101","_columnNumber":"1","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js:101:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js","_functionName":"declareTest/</<","_lineNumber":"115","_columnNumber":"7","_msg":"    at declareTest/</<@/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js:115:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"on","_lineNumber":"66","_columnNumber":"5","_msg":"    at on@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:66:5"}]
,08-04 15:08:58.210  3859  3907 I jxcore-log: [ { _fileName: 'tls.js',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _functionName: '$0v',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _lineNumber: '1065',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _columnNumber: '1',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _msg: '    at $0v@tls.js:1065:1' },
08-04 15:08:58.210  3859  3907 I jxcore-log:   { _fileName: 'https.js',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _functionName: '$5',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _lineNumber: '16',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _columnNumber: '1',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _msg: '    at $5@https.js:16:1' },
08-04 15:08:58.210  3859  3907 I jxcore-log:   { _fileName: 'https.js',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _functionName: 'exports.createServer',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _lineNumber: '33',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _columnNumber: '8',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _msg: '    at exports.createServer@https.js:33:8' },
08-04 15:08:58.210  3859  3907 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _functionName: '',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _lineNumber: '101',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _columnNumber: '1',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js:101:1' },
08-04 15:08:58.210  3859  3907 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _functionName: 'declareTest/</<',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _lineNumber: '115',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _columnNumber: '7',
08-04 15:08:58.210  3859  3907 I jxcore-log:     _msg: '    at declareTest/</<@/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js:115:7' },
08-04 15:08:58.210  3859  3907 I jxcore-log:   { _fileName: '/da
08-04 15:08:58.211  3859  3907 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-04 15:08:58.211  3859  3907 I jxcore-log: 
08-04 15:08:58.214  3859  3907 E jxcore-log: Error: 
08-04 15:08:58.214  3859  3907 E jxcore-log: Missing PFX or certificate + private key.
08-04 15:08:58.214  3859  3907 E jxcore-log:  (tls.js 1065:1)
08-04 15:08:58.214  3859  3907 E jxcore-log: 
,08-04 15:08:58.878  4302  4302 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-04 15:08:58.883  4302  4302 D AndroidRuntime: CheckJNI is OFF
,08-04 15:08:58.926  4302  4302 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-04 15:08:58.973  4302  4302 I Radio-JNI: register_android_hardware_Radio DONE
,08-04 15:08:58.998  4302  4302 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 15:08:59.010   875   889 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-04 15:08:59.011   875   889 I ActivityManager: Killing 3859:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-04 15:08:59.113   875  1310 D WifiService: Client connection lost with reason: 4
08-04 15:08:59.114   875  1745 D GraphicsStats: Buffer count: 2
,08-04 15:08:59.114   875   885 I WindowState: WIN DEATH: Window{d56f25b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-04 15:08:59.131   875   899 W PackageSettings: Skipping PackageSetting{4f01bd4 com.example.hello/10273} due to missing metadata
,08-04 15:08:59.161   875   889 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-04 15:08:59.161   875   889 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-04 15:08:59.161   875   889 E ActivityManager: Failure starting process com.test.thalitest
08-04 15:08:59.161   875   889 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-04 15:08:59.161   875   889 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:08:59.161   875   889 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:08:59.161   875   889 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 15:08:59.161   875   889 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-04 15:08:59.162   875   889 I ActivityManager:   Force finishing activity ActivityRecord{406fe44 u0 com.test.thalitest/.MainActivity t2}
,08-04 15:08:59.163   875   899 I art     : Starting a blocking GC Explicit
,08-04 15:08:59.169   875  1745 W ActivityManager: Spurious death for ProcessRecord{5b16d65 0:com.test.thalitest/u0a0}, curProc for 3859: null
,08-04 15:08:59.220   875   899 I art     : Explicit concurrent mark sweep GC freed 26185(1692KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 765us total 55.516ms
,08-04 15:08:59.245   875   899 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-04 15:08:59.248  4302  4302 I art     : System.exit called, status: 0
,08-04 15:08:59.248  4302  4302 I AndroidRuntime: VM exiting with result code 0.
,08-04 15:08:59.262   875   899 I ActivityManager: Start proc 4312:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-04 15:08:59.265   875   899 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-04 15:08:59.301   875   889 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-04 15:08:59.311  4193  4193 D BluetoothMapAppObserver: onReceive
,08-04 15:08:59.311  4193  4193 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-04 15:08:59.315  1970  2071 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-04 15:08:59.318   875  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-04 15:08:59.330  1662  1662 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-04 15:08:59.336  3529  3529 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-04 15:08:59.347  1662  4327 I Keyboard.Facilitator.DecoderInitializer: run()
,08-04 15:08:59.351  1662  4327 I Decoder : createOrResetDecoder
,08-04 15:08:59.373   875  1746 I ActivityManager: Start proc 4329:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-04 15:08:59.375  1740  1740 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-04 15:08:59.376   875   886 I ActivityManager: Killing 3583:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-04 15:08:59.406   875  1366 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3859 uid 10000
,08-04 15:08:59.407  1662  1662 I Keyboard.Facilitator: onFinishInput()
,08-04 15:08:59.431  1517  1517 I ConfigService: onCreate
08-04 15:08:59.432   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-04 15:08:59.438  1517  4341 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-04 15:08:59.438  1517  4341 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-04 15:08:59.441  4329  4329 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-04 15:08:59.445  1755  1831 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-04 15:08:59.446   875   888 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-04 15:08:59.446   875   888 E PackageManager: Failed to write settings, restoring backup
08-04 15:08:59.446   875   888 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-04 15:08:59.446   875   888 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-04 15:08:59.446   875   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-04 15:08:59.446   875   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-04 15:08:59.446   875   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-04 15:08:59.446   875   888 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:08:59.446   875   888 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:08:59.446   875   888 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-04 15:08:59.447  1517  4341 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-04 15:08:59.451   875   889 E DropBoxManagerService: Can't write: system_server_wtf
08-04 15:08:59.451   875   889 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-04 15:08:59.451   875   889 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 15:08:59.451   875   889 E DropBoxManagerService: 	... 13 more
,08-04 15:08:59.457  1517  4341 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-04 15:08:59.460   875  1707 I ActivityManager: Start proc 4342:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-04 15:08:59.461  1755  1831 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-04 15:08:59.461  1755  1831 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1755
08-04 15:08:59.461  1755  1831 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 15:08:59.461  1755  1831 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-04 15:08:59.461  1755  1831 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-04 15:08:59.461  1755  1831 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-04 15:08:59.461  1755  1831 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-04 15:08:59.461  1755  1831 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-04 15:08:59.461  1755  1831 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-04 15:08:59.461  1755  1831 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-04 15:08:59.461  1755  1831 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 15:08:59.461  1755  1831 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 15:08:59.461  1755  1831 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:08:59.461  1755  1831 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 15:08:59.463   875  1739 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-04 15:08:59.463   875  4347 E DropBoxManagerService: Can't write: system_app_crash
08-04 15:08:59.463   875  4347 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-04 15:08:59.463   875  4347 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 15:08:59.463   875  4347 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 15:08:59.463   875  4347 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 15:08:59.463   875  4347 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 15:08:59.463   875  4347 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 15:08:59.463   875  4347 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 15:08:59.463   875  4347 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 15:08:59.463   875  4347 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 15:08:59.463   875  4347 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 15:08:59.463   875  4347 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 15:08:59.463   875  4347 E DropBoxManagerService: 	... 5 more
,08-04 15:08:59.466  1755  1831 I Process : Sending signal. PID: 1755 SIG: 9
,08-04 15:08:59.476  1662  4327 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-04 15:08:59.511  1662  4327 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-04 15:08:59.514  1662  4327 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-04 15:08:59.514  1662  4327 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-04 15:08:59.515  1662  4327 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-04 15:08:59.515  1662  4327 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-04 15:08:59.516  1662  4327 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-04 15:08:59.516  1662  4327 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-04 15:08:59.523  1662  4327 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-04 15:08:59.523  1662  4327 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-04 15:08:59.523  1662  4327 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-04 15:08:59.523  1662  4327 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-04 15:08:59.523  1662  4327 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-04 15:08:59.525  1662  4327 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-04 15:08:59.543  4329  4329 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-04 15:08:59.547   279   279 E lowmemorykiller: Error writing /proc/1755/oom_score_adj; errno=22
,08-04 15:08:59.562   875  2997 I ActivityManager: Start proc 4363:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-04 15:08:59.562   279   279 E lowmemorykiller: Error writing /proc/1755/oom_score_adj; errno=22
,08-04 15:08:59.568   875  1749 D GraphicsStats: Buffer count: 1
08-04 15:08:59.568   875  2997 I WindowState: WIN DEATH: Window{39c7300 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-04 15:08:59.579   875  1749 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1755) has died
,08-04 15:08:59.580   875  1749 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-04 15:08:59.581   875  1749 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-04 15:08:59.591  4329  4362 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-04 15:08:59.598  4329  4358 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:08:59.598  4329  4358 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 15:08:59.600   875   889 I ActivityManager: Start proc 4376:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-04 15:08:59.622  4363  4363 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-04 15:08:59.626  1982  4375 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-04 15:08:59.627  1982  4375 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-04 15:08:59.641  1517  1517 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-04 15:08:59.643  4376  4376 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 15:08:59.643  4376  4376 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 15:08:59.643  4376  4376 D AndroidRuntime: Shutting down VM
,08-04 15:08:59.645  1517  1517 D AndroidRuntime: Shutting down VM
,08-04 15:08:59.646  1517  1517 E AndroidRuntime: FATAL EXCEPTION: main
08-04 15:08:59.646  1517  1517 E AndroidRuntime: Process: com.google.process.gapps, PID: 1517
08-04 15:08:59.646  1517  1517 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-04 15:08:59.646  1517  1517 E AndroidRuntime: 	... 8 more
,08-04 15:08:59.652  1517  1517 I Process : Sending signal. PID: 1517 SIG: 9
,08-04 15:08:59.652  4376  4376 E AndroidRuntime: FATAL EXCEPTION: main
08-04 15:08:59.652  4376  4376 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4376
08-04 15:08:59.652  4376  4376 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-04 15:08:59.652  4376  4376 E AndroidRuntime: 	... 10 more
08-04 15:08:59.653   875  4391 E DropBoxManagerService: Can't write: system_app_crash
08-04 15:08:59.653   875  4391 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-04 15:08:59.653   875  4391 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 15:08:59.653   875  4391 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 15:08:59.653   875  4391 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 15:08:59.653   875  4391 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 15:08:59.653   875  4391 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 15:08:59.653   875  4391 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 15:08:59.653   875  4391 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 15:08:59.653   875  4391 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 15:08:59.653   875  4391 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 15:08:59.653   875  4391 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 15:08:59.653   875  4391 E DropBoxManagerService: 	... 5 more
,08-04 15:08:59.658   875  1746 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-04 15:08:59.659  4376  4376 I Process : Sending signal. PID: 4376 SIG: 9
08-04 15:08:59.660   875  4392 E DropBoxManagerService: Can't write: system_app_crash
08-04 15:08:59.660   875  4392 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-04 15:08:59.660   875  4392 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 15:08:59.660   875  4392 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 15:08:59.660   875  4392 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 15:08:59.660   875  4392 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 15:08:59.660   875  4392 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 15:08:59.660   875  4392 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 15:08:59.660   875  4392 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 15:08:59.660   875  4392 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 15:08:59.660   875  4392 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 15:08:59.660   875  4392 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 15:08:59.660   875  4392 E DropBoxManagerService: 	... 5 more
08-04 15:08:59.664  1982  4375 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-04 15:08:59.665  1982  4375 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-04 15:08:59.669   875  2997 I ActivityManager: Killing 1800:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:08:59.668  4329  4358 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 15:08:59.683   875  1310 D WifiService: Client connection lost with reason: 4
,08-04 15:08:59.705  4329  4358 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-04 15:08:59.709  4329  4362 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:08:59.709  4329  4362 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 15:08:59.710  4329  4362 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-04 15:08:59.710  4329  4362 E AndroidRuntime: Process: android.process.acore, PID: 4329
08-04 15:08:59.710  4329  4362 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 15:08:59.710  4329  4362 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 15:08:59.710  4329  4358 I Process : Sending signal. PID: 4329 SIG: 9
,08-04 15:08:59.713   875  1310 D WifiService: Client connection lost with reason: 4
,08-04 15:08:59.716   875  1745 I ActivityManager: Process com.google.process.gapps (pid 1517) has died
,08-04 15:08:59.717   875  1745 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-04 15:08:59.717   875  1745 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-04 15:08:59.717   875  1745 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
,08-04 15:08:59.718   875   886 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4376) has died
,08-04 15:08:59.720   875   886 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-04 15:08:59.726   875  4394 E DropBoxManagerService: Can't write: system_app_crash
08-04 15:08:59.726   875  4394 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-04 15:08:59.726   875  4394 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 15:08:59.726   875  4394 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 15:08:59.726   875  4394 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 15:08:59.726   875  4394 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 15:08:59.726   875  4394 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 15:08:59.726   875  4394 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 15:08:59.726   875  4394 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 15:08:59.726   875  4394 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 15:08:59.726   875  4394 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 15:08:59.726   875  4394 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 15:08:59.726   875  4394 E DropBoxManagerService: 	... 5 more
,08-04 15:08:59.731  1982  1982 W RocketImpressions: ClearcutLogger connection suspended: 1

```
