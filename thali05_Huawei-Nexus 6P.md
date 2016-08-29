#### Test 814185776bb1ff3_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-29 03:55:32.650   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:55:33.179  5406  5406 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 03:55:33.185  5406  5406 D AndroidRuntime: CheckJNI is OFF
08-29 03:55:33.209  5406  5406 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 03:55:33.253  5406  5406 I Radio-JNI: register_android_hardware_Radio DONE
08-29 03:55:33.268  5406  5406 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 03:55:33.285   928  3450 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 03:55:33.337   928  3450 I ActivityManager: Start proc 5415:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-29 03:55:33.343  5406  5406 D AndroidRuntime: Shutting down VM
08-29 03:55:33.438  5415  5415 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-29 03:55:33.471  5415  5415 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 03:55:33.495  5415  5415 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 757-777)
08-29 03:55:33.495  5415  5415 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 03:55:33.514  5415  5415 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {caa1361}
08-29 03:55:33.514  5415  5415 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 03:55:33.515  5415  5415 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 03:55:33.521  5415  5415 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 03:55:33.522  5415  5415 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 03:55:33.550  5415  5430 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-29 03:55:33.559  5415  5415 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 03:55:33.572  5415  5415 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 03:55:33.572  5415  5415 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 03:55:33.572  5415  5415 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 03:55:33.572  5415  5415 I Adreno  : Build Date                       : 10/21/15
08-29 03:55:33.572  5415  5415 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 03:55:33.572  5415  5415 I Adreno  : Local Branch                     : 
08-29 03:55:33.572  5415  5415 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 03:55:33.572  5415  5415 I Adreno  : Remote Branch                    : NONE
08-29 03:55:33.572  5415  5415 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 03:55:33.626   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c257e5:true
,08-29 03:55:33.651   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:55:33.681  5415  5415 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 03:55:33.691  5415  5415 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-29 03:55:33.722  5415  5452 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 03:55:33.733  5415  5439 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 03:55:33.772  5415  5452 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 03:55:33.859   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +473ms (total +553ms)
,08-29 03:55:33.884  5415  5415 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5415
,08-29 03:55:33.981  5415  5415 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 03:55:34.153  5415  5455 D jxcore_app_log: JniHelper::setJavaVM(0xf533c000), pthread_self() = -579598032
,08-29 03:55:34.160  5415  5455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 03:55:34.160  5415  5455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 03:55:34.160  5415  5455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 03:55:34.160  5415  5455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 03:55:34.160  5415  5455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 03:55:34.160  5415  5455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37bf7ff added. We now have 1 listener(s)
,08-29 03:55:34.163  5415  5455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,08-29 03:55:34.164  5415  5455 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,08-29 03:55:34.165  5415  5455 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 03:55:34.165  5415  5455 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 03:55:34.169  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 03:55:34.169  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 03:55:34.169  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 03:55:34.169  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
08-29 03:55:34.169  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 03:55:34.169  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 03:55:34.169  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 03:55:34.169  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 03:55:34.169  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 03:55:34.169  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 03:55:34.169  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 03:55:34.169  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 03:55:34.169  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 03:55:34.169  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 03:55:34.170  5415  5455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4cc32a added. We now have 1 listener(s)
08-29 03:55:34.170  5415  5455 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 03:55:34.173   928  2997 D WifiService: New client listening to asynchronous messages
,08-29 03:55:34.174  5415  5455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 03:55:34.174  5415  5455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 03:55:34.174  5415  5455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 03:55:34.175  5415  5455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 03:55:34.175  5415  5455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 03:55:34.178  5415  5455 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 03:55:34.178  5415  5455 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,08-29 03:55:34.182  5415  5455 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 03:55:34.182  5415  5455 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 03:55:34.182  5415  5455 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:34.182  5415  5455 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-29 03:55:34.182  5415  5455 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 03:55:34.182  5415  5455 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 03:55:34.182  5415  5455 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:34.182  5415  5455 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:34.182  5415  5455 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 03:55:34.182  5415  5455 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 03:55:34.182  5415  5455 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 03:55:34.183  5415  5455 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 03:55:34.209  5415  5415 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 03:55:34.652   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:55:34.712  5415  5461 W jxcore-log: Initializing JXcore engine
08-29 03:55:34.712  5415  5461 W jxcore-log: JXcore engine is ready
,08-29 03:55:34.718  5415  5424 I art     : Background sticky concurrent mark sweep GC freed 79790(8MB) AllocSpace objects, 18(2MB) LOS objects, 25% free, 24MB/32MB, paused 1.373ms total 300.778ms
,08-29 03:55:34.757  5461  5461 W Thread-49: type=1400 audit(0.0:66): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12707 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 03:55:34.757  5461  5461 W Thread-49: type=1400 audit(0.0:67): avc: denied { ioctl } for path="socket:[15378]" dev="sockfs" ino=15378 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 03:55:34.757  5461  5461 W Thread-49: type=1400 audit(0.0:68): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5905 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 03:55:34.757  5461  5461 W Thread-49: type=1400 audit(0.0:69): avc: denied { ioctl } for path="socket:[30105]" dev="sockfs" ino=30105 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 03:55:34.785  5415  5461 W jxcore-log: Starting JXcore engine
,08-29 03:55:34.880  5415  5461 W jxcore-log: Platform android
08-29 03:55:34.880  5415  5461 W jxcore-log: 
,08-29 03:55:34.880  5415  5461 W jxcore-log: Process ARCH arm
08-29 03:55:34.880  5415  5461 W jxcore-log: 
,08-29 03:55:34.976  5415  5461 I jxcore-log: JXcore Cordova bridge is ready!
08-29 03:55:34.976  5415  5461 I jxcore-log: 
,08-29 03:55:34.976  5415  5461 W jxcore-log: JXcore engine is started
,08-29 03:55:34.985  5415  5455 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 03:55:34.989  5415  5415 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 03:55:35.653   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:55:36.654   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:55:37.655   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 03:55:41.393  5415  5461 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 03:55:41.393  5415  5461 I jxcore-log: 
,08-29 03:55:41.395  5415  5461 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 03:55:41.395  5415  5461 I jxcore-log: 
,08-29 03:55:41.396  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 03:55:41.396  5415  5461 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 03:55:41.396  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:41.396  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-29 03:55:41.396  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 03:55:41.396  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 03:55:41.396  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:41.396  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:41.396  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 03:55:41.396  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 03:55:41.396  5415  5461 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 03:55:41.398  5415  5461 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 03:55:41.398  5415  5461 I jxcore-log: 
,08-29 03:55:41.399  5415  5461 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 03:55:41.399  5415  5461 I jxcore-log: 
,08-29 03:55:41.746  5415  5461 D executeNativeTests: Running unit tests
,08-29 03:55:41.785  5415  5461 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 03:55:41.785  5415  5461 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 added. We now have 2 listener(s)
08-29 03:55:41.786  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
08-29 03:55:41.786  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 03:55:41.786  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 03:55:41.786  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 03:55:41.786  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e added. We now have 2 listener(s)
08-29 03:55:41.786  5415  5461 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 03:55:41.787  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 03:55:41.789  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 03:55:41.789  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 03:55:41.789  5415  5461 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 03:55:41.789  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:41.789  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-29 03:55:41.789  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 03:55:41.789  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 03:55:41.789  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:41.789  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:41.789  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 03:55:41.789  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 03:55:41.789  5415  5461 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 03:55:41.789  5415  5461 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 03:55:41.791  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 03:55:41.791  5415  5461 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 03:55:41.791  5415  5461 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 03:55:41.792  5415  5461 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 03:55:41.792  5415  5461 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 03:55:41.792  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 03:55:41.792  5415  5461 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 03:55:41.792  5415  5461 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 03:55:41.793  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.793  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 03:55:41.793  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.793  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.793  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.793  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 03:55:41.793  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 03:55:41.793  5415  5461 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 removed from the list
08-29 03:55:41.793  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 03:55:41.793  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e removed from the list
08-29 03:55:41.793  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.793  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.794  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.794  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 03:55:41.794  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.794  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.794  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.794  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
,08-29 03:55:41.795  5415  5461 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 03:55:41.796  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.796  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.796  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.796  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 03:55:41.796  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.796  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.796  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.796  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.796  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
,08-29 03:55:41.796  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.796  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.796  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.796  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.796  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 03:55:41.797  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.797  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.797  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.797  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.799  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 03:55:41.799  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 03:55:41.799  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 03:55:41.799  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 03:55:41.799  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 03:55:41.799  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-29 03:55:41.799  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 03:55:41.800  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 03:55:41.801  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 03:55:41.801  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 03:55:41.801  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.801  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.801  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.801  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 03:55:41.801  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.801  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
,08-29 03:55:41.801  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.801  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.801  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.801  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.801  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.801  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 03:55:41.801  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.802  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.802  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.802  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.802  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.802  5415  5461 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 03:55:41.803  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 03:55:41.803  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:41.803  5415  5461 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 03:55:41.803  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:41.803  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-29 03:55:41.803  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 03:55:41.803  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 03:55:41.803  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:41.803  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:41.803  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 03:55:41.803  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:41.803  5415  5461 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 03:55:41.805  5415  5461 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 03:55:41.805  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 03:55:41.805  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 03:55:41.805  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 03:55:41.805  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 03:55:41.805  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 03:55:41.808  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,08-29 03:55:41.808  5415  5461 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-29 03:55:41.808  5415  5461 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 03:55:41.808  5415  5461 I io.jxcore.node.ConnectionHelper: start: OK
08-29 03:55:41.809  5415  5415 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-29 03:55:41.809  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:41.809  5415  5461 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-29 03:55:41.810  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.810  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.810  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 03:55:41.810  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.810  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 03:55:41.810  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 03:55:41.810  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 03:55:41.810  5415  5461 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 03:55:41.811  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 03:55:41.811  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 03:55:41.811  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 03:55:41.812  5415  5461 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 03:55:41.812  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.812  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.812  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 03:55:41.812  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.812  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.812  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.812  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.812  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.813  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.813  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.813  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.813  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.813  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.813  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.814  5415  5461 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 03:55:41.814  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 03:55:41.814  5415  5415 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 03:55:41.815  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:41.815  5415  5461 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 03:55:41.815  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:41.815  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-29 03:55:41.815  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 03:55:41.815  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 03:55:41.815  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:41.815  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:41.815  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 03:55:41.815  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:41.815  5415  5415 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 03:55:41.815  5415  5461 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 03:55:41.815  5415  5461 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 03:55:41.815  5415  5415 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 03:55:41.815  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 03:55:41.815  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 03:55:41.815  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 03:55:41.815  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 03:55:41.815  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 03:55:41.816  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-29 03:55:41.816  5415  5461 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-29 03:55:41.816  5415  5461 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 03:55:41.816  5415  5461 I io.jxcore.node.ConnectionHelper: start: OK
08-29 03:55:41.816  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.816  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.816  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 03:55:41.816  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.816  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 03:55:41.816  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 03:55:41.816  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 03:55:41.816  5415  5415 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-29 03:55:41.816  5415  5461 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 03:55:41.816  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 03:55:41.816  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 03:55:41.817  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 03:55:41.817  5415  5461 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 03:55:41.817  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.817  5415  5461 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 03:55:41.817  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.817  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.817  5415  5415 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 03:55:41.817  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.817  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.817  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 03:55:41.817  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.817  5415  5415 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 03:55:41.817  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.817  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.817  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.817  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.817  5415  5415 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 03:55:41.818  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.818  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.818  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.818  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.818  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.818  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.818  5415  5461 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 03:55:41.818  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.818  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.818  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.818  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.818  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.818  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.819  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.819  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.819  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.819  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.819  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.819  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.819  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.819  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.819  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.819  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.819  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.819  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.819  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 03:55:41.819  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.819  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.820  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.820  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.820  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.820  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.820  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.820  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.820  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.820  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.820  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.820  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.820  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.820  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.820  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.820  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.820  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.820  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.820  5415  5461 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 03:55:41.820  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.821  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.821  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.821  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.821  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.821  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.821  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.821  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.821  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.821  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.821  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.821  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.821  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.821  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.821  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.821  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.821  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.821  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.821  5415  5461 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 03:55:41.821  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.822  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.822  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.822  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.822  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.822  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.822  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.822  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.822  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.822  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.822  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.822  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.822  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.822  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.822  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.822  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.822  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.822  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.822  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 03:55:41.822  5415  5461 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 03:55:41.823  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 03:55:41.823  5415  5461 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 03:55:41.823  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 03:55:41.823  5415  5461 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 03:55:41.823  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.823  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.823  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.823  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.823  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.823  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.823  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.823  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.823  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.823  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.823  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.823  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.823  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.823  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.823  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.823  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.823  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.823  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.824  5415  5461 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 03:55:41.824  5415  5461 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 03:55:41.824  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 03:55:41.825  5415  5461 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 03:55:41.825  5415  5461 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 03:55:41.825  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 03:55:41.826  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 03:55:41.826  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 03:55:41.826  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 03:55:41.826  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 03:55:41.826  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 03:55:41.826  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 03:55:41.826  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 03:55:41.826  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 03:55:41.826  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 03:55:41.826  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 03:55:41.826  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 03:55:41.826  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 03:55:41.826  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 03:55:41.826  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 03:55:41.826  5415  5461 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 03:55:41.826  5415  5461 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 03:55:41.826  5415  5461 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 03:55:41.826  5415  5461 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 03:55:41.826  5415  5461 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 03:55:41.826  5415  5461 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 03:55:41.826  5415  5461 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 03:55:41.826  5415  5461 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 03:55:41.826  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 03:55:41.827  5415  5461 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-29 03:55:41.827  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 03:55:41.828  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 03:55:41.828  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 03:55:41.828  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 03:55:41.828  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 03:55:41.828  5415  5461 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 03:55:41.828  5415  5461 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 03:55:41.828  5415  5461 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 03:55:41.829  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.829  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.829  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.829  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.829  5415  5462 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 113)
08-29 03:55:41.829  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.829  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.829  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 03:55:41.829  5415  5462 E BluetoothDevice: Bluetooth is not enabled
08-29 03:55:41.829  5415  5462 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 113)
08-29 03:55:41.829  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.829  5415  5462 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 113)
08-29 03:55:41.829  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.829  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.829  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.829  5415  5462 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 113)
08-29 03:55:41.829  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.829  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.829  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.829  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.830  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.830  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.830  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.830  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.830  5415  5415 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
08-29 03:55:41.830  5415  5462 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 113
08-29 03:55:41.830  5415  5462 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 113)
,08-29 03:55:41.830  5415  5461 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 03:55:41.830  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.830  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.830  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.830  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.830  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.830  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.831  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.831  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.831  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.831  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.831  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.831  5415  5415 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
08-29 03:55:41.831  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.831  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.831  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.831  5415  5415 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 03:55:41.831  5415  5415 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 03:55:41.831  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.831  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.831  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.831  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.831  5415  5463 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 113
08-29 03:55:41.831  5415  5461 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 03:55:41.831  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.831  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.831  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.831  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.832  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.832  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.832  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.832  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.832  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.832  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.832  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.832  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.832  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.832  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.832  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.832  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.832  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.832  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.832  5415  5461 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 03:55:41.832  5415  5461 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 03:55:41.832  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 03:55:41.832  5415  5461 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 03:55:41.833  5415  5461 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 03:55:41.833  5415  5461 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 03:55:41.833  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 03:55:41.833  5415  5461 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 03:55:41.833  5415  5461 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 03:55:41.833  5415  5461 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 03:55:41.833  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 03:55:41.833  5415  5461 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 03:55:41.833  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.833  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.833  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.833  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.833  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.833  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.833  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.833  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.833  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.833  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.833  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.833  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.833  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.833  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.833  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.833  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.833  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.833  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.834  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.834  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.834  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.834  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.834  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.834  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.834  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.834  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.834  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.834  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.834  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.834  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.834  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.834  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.834  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.834  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.834  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.834  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.834  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.834  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.834  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.834  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.834  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.834  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.834  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.835  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.835  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.835  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.835  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.835  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.835  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.835  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.835  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.835  5415  5461 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 03:55:41.836  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 03:55:41.836  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-29 03:55:41.836  5415  5461 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-29 03:55:41.836  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 03:55:41.836  5415  5415 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-29 03:55:41.836  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.836  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 03:55:41.836  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.836  5415  5461 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-29 03:55:41.836  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.836  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.836  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 03:55:41.836  5415  5461 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 03:55:41.836  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 03:55:41.836  5415  5415 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 03:55:41.836  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.836  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.836  5415  5461 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 03:55:41.837  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.837  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.837  5415  5415 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 03:55:41.837  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.837  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.837  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.837  5415  5415 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 03:55:41.837  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.837  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.837  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.837  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.837  5415  5415 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 03:55:41.837  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.837  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.837  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.837  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.837  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.837  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.837  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.837  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.837  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.837  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.838  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 03:55:41.838  5415  5461 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 03:55:41.838  5415  5461 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 03:55:41.838  5415  5461 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 03:55:41.838  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 03:55:41.838  5415  5461 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 03:55:41.838  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.838  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.838  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.838  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.838  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.838  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.838  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.838  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.838  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.838  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.838  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.838  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.838  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.838  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.839  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.839  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.839  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.839  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.839  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.839  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.840  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.840  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.840  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.840  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.840  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.840  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.840  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.840  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.840  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.840  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.840  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.840  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.840  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.840  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.840  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.840  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.840  5415  5461 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 03:55:41.840  5415  5461 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 03:55:41.840  5415  5461 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 03:55:41.840  5415  5461 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 03:55:41.841  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.841  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.841  5415  5461 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d209e9 not in the list
08-29 03:55:41.841  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.841  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.841  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
08-29 03:55:41.841  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.841  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.841  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 03:55:41.841  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 03:55:41.841  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 03:55:41.841  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 03:55:41.841  5415  5461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 03:55:41.841  5415  5461 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a9666e not in the list
08-29 03:55:41.841  5415  5461 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 03:55:41.841  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 03:55:41.842  5415  5461 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 03:55:41.842  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 03:55:41.842  5415  5461 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 03:55:41.842  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 03:55:41.842  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 03:55:41.842  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 03:55:41.843  5415  5461 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 03:55:41.843  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 03:55:41.843  5415  5461 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 03:55:41.843  5415  5461 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 03:55:41.843  5415  5461 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 03:55:41.843  5415  5461 D io.jxcore.node.ConnectionModel: clos,eAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 03:55:41.843  5415  5461 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 03:55:41.843  5415  5461 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 03:55:41.843  5415  5461 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 03:55:41.843  5415  5461 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 03:55:41.843  5415  5461 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 03:55:41.843  5415  5461 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 03:55:41.844  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 03:55:41.844  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a3b1f88 added. We now have 2 listener(s)
08-29 03:55:41.844  5415  5461 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 03:55:41.844   928  4661 D WifiService: setWifiEnabled: true pid=5415, uid=10077
08-29 03:55:41.845   928  4661 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 03:55:41.847  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 03:55:41.847  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9f80d21 added. We now have 3 listener(s)
08-29 03:55:41.847  5415  5461 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 03:55:41.847  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:41.847  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:41.848  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 03:55:41.848  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b23d546 added. We now have 4 listener(s)
08-29 03:55:41.848  5415  5461 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 03:55:41.848  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 03:55:41.848  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3615307 added. We now have 5 listener(s)
08-29 03:55:41.848  5415  5461 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 03:55:41.849   928  3482 D WifiService: setWifiEnabled: true pid=5415, uid=10077
08-29 03:55:41.849   928  3482 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 03:55:41.850   507   922 D SoftapController: Softap fwReload - Ok
08-29 03:55:41.854   507   922 D CommandListener: Setting iface cfg
08-29 03:55:41.854   507   922 D CommandListener: Trying to bring down wlan0
08-29 03:55:41.855   507   922 D CommandListener: Clearing all IP addresses on wlan0
08-29 03:55:41.858   928  2996 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 03:55:41.862   928   945 I ActivityManager: Start proc 5465:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
08-29 03:55:41.863  5415  5461 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 03:55:41.864  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:41.864  5415  5461 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 03:55:41.864  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:41.864  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-29 03:55:41.864  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 03:55:41.864  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 03:55:41.864  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:41.864  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:41.864  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 03:55:41.864  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:41.864  5415  5461 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 03:55:41.864  5415  5461 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 03:55:41.931  5465  5465 D AdapterServiceConfig: Adding HeadsetService
08-29 03:55:41.931  5465  5465 D AdapterServiceConfig: Adding A2dpService
08-29 03:55:41.931  5465  5465 D AdapterServiceConfig: Adding HidService
08-29 03:55:41.931  5465  5465 D AdapterServiceConfig: Adding HealthService
08-29 03:55:41.931  5465  5465 D AdapterServiceConfig: Adding PanService
08-29 03:55:41.932  5465  5465 D AdapterServiceConfig: Adding GattService
08-29 03:55:41.932  5465  5465 D AdapterServiceConfig: Adding BluetoothMapService
08-29 03:55:41.932  5465  5465 D AdapterServiceConfig: Adding SapService
,08-29 03:55:41.952   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34ae9ca:true
,08-29 03:55:41.953  5465  5465 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 03:55:41.955  5465  5465 I bt_bluedroid: init
,08-29 03:55:41.955  5465  5477 I BluetoothAdapterState: Entering OffState
,08-29 03:55:41.958  5465  5478 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 03:55:41.959  5465  5478 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 03:55:41.959  5465  5478 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 03:55:41.959  5465  5478 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 03:55:41.960  5465  5465 I bt_bluedroid: get_profile_interface socket
,08-29 03:55:41.962  5465  5481 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
08-29 03:55:41.962  5465  5465 I bt_bluedroid: get_profile_interface sdp
,08-29 03:55:41.965  5465  5481 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 03:55:41.966  5465  5476 I bt_bluedroid: config_hci_snoop_log
,08-29 03:55:41.968   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-29 03:55:41.972  5465  5477 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 03:55:41.972  5465  5477 D BluetoothAdapterProperties: Setting state to 14
,08-29 03:55:41.972  5465  5477 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-29 03:55:41.973  5465  5477 D BluetoothBondStateMachine: make
,08-29 03:55:41.975  5465  5482 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 03:55:41.977  5465  5477 I BluetoothAdapterState: Entering PendingCommandState
,08-29 03:55:41.978  5465  5465 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 03:55:41.981  5465  5465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
08-29 03:55:41.981  5465  5465 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 03:55:41.982  5465  5465 D BtGatt.GattService: Received start request. Starting profile...
08-29 03:55:41.982  5465  5465 D BtGatt.GattService: start()
08-29 03:55:41.982  5465  5465 I bt_bluedroid: get_profile_interface gatt
08-29 03:55:41.983  5465  5465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
08-29 03:55:41.983  5465  5465 D BtGatt.AdvertiseManager: advertise manager created
,08-29 03:55:41.987  5465  5465 V BluetoothAdapterState: isTurningOff()=false
,08-29 03:55:41.987  5465  5465 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:41.987  5465  5465 V BluetoothAdapterState: isBleTurningOn()=true
08-29 03:55:41.987  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:41.988  5465  5477 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 03:55:41.988  5465  5477 I bt_bluedroid: enable
08-29 03:55:41.988  5465  5478 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 03:55:41.988  5465  5478 I bt_hci  : start_up
,08-29 03:55:41.995  5465  5478 I bt_vendor: alloc value 0xf3fe104d
08-29 03:55:41.995  5465  5478 I bt_vendor: init
,08-29 03:55:41.995  5465  5478 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 03:55:41.995  5465  5478 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 03:55:42.121  5465  5478 D bt_hci  : start_up starting async portion
,08-29 03:55:42.121  5465  5485 I bt_hci  : event_finish_startup
08-29 03:55:42.122  5465  5485 I bt_hci_h4: hal_open
08-29 03:55:42.122  5465  5485 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 03:55:42.107  5486  5486 W irq/448-msm_hs_: type=1400 audit(0.0:70): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 03:55:42.124  5465  5485 I bt_userial_vendor: device fd = 51 open
,08-29 03:55:42.141  5465  5485 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 03:55:42.143  5465  5485 D bt_hwcfg: Chipset BCM4358A3
,08-29 03:55:42.143  5465  5485 D bt_hwcfg: Target name = [BCM4358A3]
,08-29 03:55:42.144  5465  5485 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 03:55:42.216   388   388 I MSM-irqbalance: Discovered a new IRQ: 146
,08-29 03:55:42.220   388   388 I MSM-irqbalance: Discovered a new IRQ: 271
,08-29 03:55:42.338  5415  5415 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 03:55:42.453  5465  5485 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-29 03:55:42.453  5465  5485 D bt_hwcfg: Settlement delay -- 100 ms
08-29 03:55:42.453  5465  5485 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 03:55:42.534   928  2996 D wifi    : set interface wlan0 flags (UP)
,08-29 03:55:42.534   928  2996 I WifiHAL : Initializing wifi
08-29 03:55:42.534   928  2996 I WifiHAL : Creating socket
,08-29 03:55:42.537   928  2996 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-29 03:55:42.537   928  2996 D wifi    : Did set static halHandle = 0x7f5f4111c0
08-29 03:55:42.537   928  2996 D wifi    : halHandle = 0x7f5f4111c0, mVM = 0x7f7854d140, mCls = 0xb3a
08-29 03:55:42.537   928  2996 D wifi    : array field set
08-29 03:55:42.538   928  2996 I WifiNative-HAL: interface[0] = wlan0
,08-29 03:55:42.541   928  5488 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547058946496
,08-29 03:55:42.542   928  5488 D wifi    : waitForHalEvents called, vm = 0x7f7854d140, obj = 0xb3a, env = 0x7f5b67de40
08-29 03:55:42.543   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 03:55:42.577  5465  5485 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 03:55:42.577  5465  5485 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
08-29 03:55:42.578  5465  5485 I bt_hwcfg: vendor lib fwcfg completed
08-29 03:55:42.578  5465  5485 I bt_vendor: firmware callback
08-29 03:55:42.578  5465  5485 I bt_hci  : firmware_config_callback
,08-29 03:55:42.581  5465  5490 I bt_btu  : btu_task pending for preload complete event
,08-29 03:55:42.581  5465  5490 I bt_btu_task: Bluetooth chip preload is complete
08-29 03:55:42.581  5465  5490 I bt_btu  : btu_task received preload complete event
,08-29 03:55:42.584  5465  5490 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 03:55:42.584  5465  5490 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 03:55:42.584  5465  5490 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 03:55:42.584  5465  5490 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 03:55:42.585  5465  5490 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 03:55:42.585  5465  5490 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 03:55:42.585  5465  5490 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 03:55:42.585  5465  5490 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 03:55:42.585  5465  5490 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 03:55:42.585  5465  5490 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 03:55:42.585  5465  5490 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 03:55:42.585  5465  5490 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 03:55:42.585  5465  5490 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 03:55:42.585  5465  5490 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 03:55:42.585  5465  5490 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 03:55:42.629  5489  5489 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 03:55:42.648   928  2996 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 03:55:42.653  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:42.657  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:42.664  5465  5490 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f5ec99
,08-29 03:55:42.664  5465  5490 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f5ec99 
,08-29 03:55:42.668   928   941 I ActivityManager: Start proc 5492:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 03:55:42.672  5465  5481 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 03:55:42.673  5465  5481 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 03:55:42.673  5465  5481 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
08-29 03:55:42.675  5465  5481 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 03:55:42.675  5489  5489 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 03:55:42.676  5465  5481 D BluetoothAdapterProperties: Scan Mode:20
08-29 03:55:42.676  5465  5481 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 03:55:42.676  5465  5481 D bt_hci  : do_postload posting postload work item
,08-29 03:55:42.676  5465  5485 I bt_hci  : event_postload
08-29 03:55:42.676  5465  5485 I bt_vendor: sco_config_cb
08-29 03:55:42.676  5465  5485 I bt_hci  : sco_config_callback postload finished.
08-29 03:55:42.679  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 03:55:42.679  5465  5481 D bt_bte_conf: Device ID record 1 : primary
08-29 03:55:42.680  5465  5481 D bt_bte_conf:   vendorId            = 000f
08-29 03:55:42.680  5465  5481 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 03:55:42.680  5465  5481 D bt_bte_conf:   product             = 1200
,08-29 03:55:42.680  5465  5481 D bt_bte_conf:   version             = 1436
,08-29 03:55:42.680  5465  5481 D bt_bte_conf:   clientExecutableURL = 
,08-29 03:55:42.680  5465  5481 D bt_bte_conf:   serviceDescription  = 
08-29 03:55:42.680  5465  5481 D bt_bte_conf:   documentationURL    = 
08-29 03:55:42.680  5465  5481 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 03:55:42.680  5465  5478 D bt_stack_manager: event_start_up_stack finished
08-29 03:55:42.681  5465  5477 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 03:55:42.682  5465  5477 D BluetoothAdapterProperties: Setting state to 15
08-29 03:55:42.682  5465  5477 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 03:55:42.683  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 03:55:42.683  5465  5477 I BluetoothAdapterState: Entering BleOnState
08-29 03:55:42.686  5465  5485 I bt_vendor: low_power_mode_cb
,08-29 03:55:42.687  5465  5477 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 03:55:42.687  5465  5477 D BluetoothAdapterProperties: Setting state to 11
08-29 03:55:42.687  5465  5477 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 03:55:42.693  5465  5465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
,08-29 03:55:42.694  5465  5465 D HeadsetService: Received start request. Starting profile...
,08-29 03:55:42.695  5465  5465 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 03:55:42.695  5465  5465 D HeadsetStateMachine: make
,08-29 03:55:42.695  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:42.697  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:42.702  5465  5477 I BluetoothAdapterState: Entering PendingCommandState
,08-29 03:55:42.702  5465  5465 D HeadsetStateMachine: max_hf_connections = 1
,08-29 03:55:42.703  5465  5465 I bt_bluedroid: get_profile_interface handsfree
08-29 03:55:42.703  5465  5481 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 03:55:42.703  5465  5481 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-29 03:55:42.705  5465  5465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
08-29 03:55:42.706   928   928 D BluetoothA2dp: Proxy object connected
,08-29 03:55:42.707  5465  5465 D A2dpService: Received start request. Starting profile...
,08-29 03:55:42.708  5465  5465 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 03:55:42.708  5465  5465 I bt_bluedroid: get_profile_interface avrcp
08-29 03:55:42.708  5492  5492 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,08-29 03:55:42.712  5465  5465 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 03:55:42.713  5465  5465 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 03:55:42.713  5465  5465 D A2dpStateMachine: make
,08-29 03:55:42.714  5465  5465 I bt_bluedroid: get_profile_interface a2dp
,08-29 03:55:42.714  5465  5481 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 03:55:42.715  5465  5510 D A2dpStateMachine: Enter Disconnected: -2
08-29 03:55:42.715  5465  5465 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 03:55:42.716  5465  5465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
,08-29 03:55:42.718  5465  5465 D HidService: Received start request. Starting profile...
,08-29 03:55:42.718  5465  5465 I bt_bluedroid: get_profile_interface hidhost
08-29 03:55:42.718  5465  5481 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f402d9
08-29 03:55:42.718  5465  5465 D HidService: setHidService(): set to: null
08-29 03:55:42.718  5465  5465 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 03:55:42.719  3166  3166 D BluetoothInputDevice: Proxy object connected
,08-29 03:55:42.719  5465  5465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
08-29 03:55:42.719  3166  3166 D HidProfile: Bluetooth service connected
08-29 03:55:42.719  5465  5465 D HealthService: Received start request. Starting profile...
08-29 03:55:42.720  5465  5481 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 03:55:42.720  5465  5465 I bt_bluedroid: get_profile_interface health
08-29 03:55:42.720  5465  5465 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 03:55:42.721  5465  5465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
,08-29 03:55:42.722  3166  3166 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 03:55:42.722  5465  5465 D PanService: Received start request. Starting profile...
,08-29 03:55:42.722  5465  5465 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 03:55:42.722  5465  5465 I bt_bluedroid: get_profile_interface pan
08-29 03:55:42.722  3166  3166 D PanProfile: Bluetooth service connected
08-29 03:55:42.722  5465  5481 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 03:55:42.723  5465  5465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
,08-29 03:55:42.724  5465  5465 D BluetoothMapService: Received start request. Starting profile...
,08-29 03:55:42.724  5465  5465 D BluetoothMapService: start()
08-29 03:55:42.724  3166  3166 D BluetoothMap: Proxy object connected
08-29 03:55:42.725  3166  3166 D MapProfile: Bluetooth service connected
08-29 03:55:42.725  3166  3166 D BluetoothMap: getConnectedDevices()
08-29 03:55:42.726  3166  3166 D BluetoothMap: Bluetooth is Not enabled
,08-29 03:55:42.726  5465  5465 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 03:55:42.727  5465  5465 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 03:55:42.727  5465  5465 D BluetoothMapAppObserver: createReceiver()
08-29 03:55:42.728  5465  5465 D BluetoothMapAppObserver: initObservers()
08-29 03:55:42.728  5465  5465 D BluetoothMapAppObserver: getEnabledAccountItems()
08-29 03:55:42.734  5465  5465 V SapService: SapBinder()
08-29 03:55:42.734  5465  5465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
08-29 03:55:42.735  5465  5465 D SapService: Received start request. Starting profile...
08-29 03:55:42.735  5465  5465 V SapService: start()
08-29 03:55:42.736  5465  5465 V BluetoothAdapterState: isTurningOff()=false
08-29 03:55:42.736  5465  5465 V BluetoothAdapterState: isTurningOn()=true
,08-29 03:55:42.736  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:42.736  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:42.736  5465  5507 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
08-29 03:55:42.736  5465  5465 V BluetoothAdapterState: isTurningOff()=false
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isTurningOn()=true
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isTurningOff()=false
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isTurningOn()=true
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isTurningOff()=false
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isTurningOn()=true
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isTurningOff()=false
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isTurningOn()=true
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isTurningOff()=false
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isTurningOn()=true
08-29 03:55:42.737  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:42.738  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:42.738  5465  5465 V BluetoothAdapterState: isTurningOff()=false
08-29 03:55:42.738  5465  5465 V BluetoothAdapterState: isTurningOn()=true
08-29 03:55:42.738  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:42.738  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:42.738  5465  5477 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 03:55:42.738  5465  5477 D BluetoothAdapterProperties: ScanMode =  20
,08-29 03:55:42.738  5465  5477 D BluetoothAdapterProperties: State =  11
08-29 03:55:42.739  5465  5477 D BluetoothAdapterProperties: Setting state to 12
,08-29 03:55:42.739  5465  5477 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 03:55:42.739  5465  5477 I BluetoothAdapterState: Entering OnState
08-29 03:55:42.740  3166  3182 D BluetoothPan: onBluetoothStateChange on: true
08-29 03:55:42.740   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 03:55:42.740   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 03:55:42.741  3552  3567 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 03:55:42.742  5465  5481 D BluetoothAdapterProperties: Scan Mode:21
08-29 03:55:42.742  5415  5415 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-29 03:55:42.742   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 03:55:42.742  5465  5481 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 03:55:42.743  3166  3751 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 03:55:42.744  3166  3178 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 03:55:42.745   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 03:55:42.745  3166  3182 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 03:55:42.746  5415  5415 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 03:55:42.748   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 03:55:42.748  5465  5465 D BluetoothMapService: onReceive
08-29 03:55:42.748  5465  5465 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 03:55:42.748  5465  5465 D BluetoothMapService: STATE_ON
08-29 03:55:42.749  5415  5415 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 03:55:42.751  5489  5489 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 03:55:42.751  5489  5489 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 03:55:42.752  5492  5492 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
08-29 03:55:42.752  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:42.752  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:42.752  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:42.752  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 03:55:42.752  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 03:55:42.752  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:42.752  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:42.752  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 03:55:42.752  3166  3398 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 03:55:42.753  5465  5465 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 03:55:42.754  5465  5465 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-29 03:55:42.754  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 03:55:42.755  5465  5465 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 03:55:42.755  5465  5527 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 03:55:42.756   928  3450 I ActivityManager: Killing 5051:com.google.android.youtube/u0a75 (adj 15): empty #17
,08-29 03:55:42.759  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:42.759  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:42.759  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:42.759  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 03:55:42.759  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 03:55:42.759  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:42.759  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:42.759  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 03:55:42.761  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 03:55:42.762  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 03:55:42.763  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:42.804  3166  3166 D BluetoothA2dp: Proxy object connected
08-29 03:55:42.804  3166  3398 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 03:55:42.818   928  3582 I ActivityManager: Start proc 5532:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-29 03:55:42.822  5465  5465 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 03:55:42.824  5465  5465 D ObexServerSockets: Succeed to create listening sockets 
,08-29 03:55:42.824  5465  5527 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 03:55:42.824   928  2996 D WifiConfigStore: Loading config and enabling all networks 
,08-29 03:55:42.824  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:42.824  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:42.824  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:42.824  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 03:55:42.824  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 03:55:42.824  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:42.824  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:42.824  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 03:55:42.824  5465  5527 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 03:55:42.824  5465  5465 D ObexServerSockets0: startAccept()
08-29 03:55:42.825  5465  5465 D ObexServerSockets0: prepareForNewConnect()
08-29 03:55:42.826  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 03:55:42.827  5465  5465 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 03:55:42.827  5465  5465 D BluetoothSdpJni: SDP Create record success - handle: 1
08-29 03:55:42.830  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:42.830  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:42.830  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:42.830  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 03:55:42.830  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 03:55:42.830  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:42.830  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:42.830  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 03:55:42.832  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 03:55:42.834   928  2996 D WifiConfigStore: loaded 0 passpoint configs
08-29 03:55:42.834   928  2996 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 03:55:42.835   928  2996 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 03:55:42.836   928  2996 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 03:55:42.836   928  2996 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 03:55:42.836   928  2996 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-29 03:55:42.838  5465  5465 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 03:55:42.838  5465  5544 D ObexServerSockets0: Accepting socket connection...
08-29 03:55:42.838  5465  5465 D ObexServerSockets0: prepareForNewConnect()
08-29 03:55:42.838  5465  5543 D ObexServerSockets0: Accepting socket connection...
08-29 03:55:42.842   928   945 D BluetoothHeadset: Proxy object connected
08-29 03:55:42.843  3552  3565 D BluetoothHeadset: Proxy object connected
08-29 03:55:42.843   928  2996 D WifiNative-HAL: Setting external_sim to 1
08-29 03:55:42.844   928  2996 D wifi    : setting dfs flag to true, 0x7f61226d60
08-29 03:55:42.844   928   945 D BluetoothHeadset: Proxy object connected
08-29 03:55:42.844   928   945 D BluetoothHeadset: Proxy object connected
08-29 03:55:42.845   928  2996 D WifiStateMachine: Setting OUI to DA-A1-19
,08-29 03:55:42.845   928  2996 D wifi    : setting scan oui 0x7f61226d60
08-29 03:55:42.845   928  2996 D WifiHAL : Sending mac address OUI
08-29 03:55:42.845  4228  4228 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 03:55:42.854   928  2996 E native  : do suspend true
,08-29 03:55:42.860   928   928 D RttService: SCAN_AVAILABLE : 3
,08-29 03:55:42.860   928  2996 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 03:55:42.860   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 03:55:42.860   928  3105 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 03:55:42.861  5532  5532 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
08-29 03:55:42.861   507   922 D CommandListener: Setting iface cfg
,08-29 03:55:42.863   928  2995 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '30 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 30 Failed to set address (No such device)'
08-29 03:55:42.863   928  2995 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 03:55:42.869   928  2995 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 03:55:42.870   928  2995 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,08-29 03:55:42.871   928  3450 I ActivityManager: Killing 5147:org.codeaurora.ims/1001 (adj 15): empty #17
,08-29 03:55:42.890  3647  3647 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 03:55:42.904   928  3199 I ActivityManager: Start proc 5547:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 03:55:42.906  3166  3751 D BluetoothHeadset: Proxy object connected
,08-29 03:55:42.907  3166  3166 D HeadsetProfile: Bluetooth service connected
,08-29 03:55:42.939  5547  5547 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,08-29 03:55:43.118  5547  5547 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 03:55:43.118  5547  5547 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 03:55:43.118  5547  5547 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 03:55:43.119  5547  5547 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 03:55:43.119  5547  5547 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 03:55:43.119  5547  5547 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 03:55:43.128  5532  5532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 03:55:43.134   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@91cabdf:true
08-29 03:55:43.136  3647  3647 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 03:55:43.143  5532  5532 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-29 03:55:43.144  3166  3166 D BluetoothPbap: Proxy object connected
08-29 03:55:43.145  3166  3166 D PbapServerProfile: Bluetooth service connected
,08-29 03:55:43.154  5532  5532 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 03:55:43.155  5465  5576 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 03:55:43.168  5532  5532 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 03:55:43.169  5532  5532 D BluetoothMap: Create BluetoothMap proxy object
,08-29 03:55:43.173  5465  5580 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 03:55:43.175  5465  5580 I BtOppRfcommListener: Accept thread started.
,08-29 03:55:43.182  5532  5532 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 03:55:43.190  5532  5532 D DockEventReceiver: finishStartingService: stopping service
,08-29 03:55:43.191  5532  5532 D BluetoothA2dp: Proxy object connected
,08-29 03:55:43.193  5532  5532 D BluetoothInputDevice: Proxy object connected
,08-29 03:55:43.194  5532  5532 D HidProfile: Bluetooth service connected
,08-29 03:55:43.195  5532  5532 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 03:55:43.196  5532  5532 D PanProfile: Bluetooth service connected
,08-29 03:55:43.196  5532  5532 D BluetoothMap: Proxy object connected
08-29 03:55:43.196  5532  5532 D MapProfile: Bluetooth service connected
08-29 03:55:43.196  5532  5532 D BluetoothMap: getConnectedDevices()
,08-29 03:55:43.198  5532  5532 D BluetoothPbap: Proxy object connected
08-29 03:55:43.199  5532  5532 D PbapServerProfile: Bluetooth service connected
,08-29 03:55:43.200   928  4661 I ActivityManager: Killing 4722:com.google.android.calendar/u0a36 (adj 15): empty #17
,08-29 03:55:43.258  5532  5545 D BluetoothHeadset: Proxy object connected
,08-29 03:55:43.259  5532  5532 D HeadsetProfile: Bluetooth service connected
,08-29 03:55:43.332  5547  5562 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 03:55:43.343   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e4ce663:true
,08-29 03:55:44.661  5489  5489 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 03:55:44.708   928  2996 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-29 03:55:44.716   928  2996 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,08-29 03:55:44.720   928  2996 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 03:55:44.732   928  2996 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-29 03:55:44.771   928  2996 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-29 03:55:44.866   928  3482 D WifiService: setWifiEnabled: false pid=5415, uid=10077
,08-29 03:55:44.866   928  3482 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 03:55:44.880   928   928 D RttService: SCAN_AVAILABLE : 1
,08-29 03:55:44.880   928  3105 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 03:55:44.891   928  2996 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 03:55:44.892   507   922 D CommandListener: Clearing all IP addresses on wlan0
,08-29 03:55:44.897   928  2996 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 03:55:44.898  5489  5489 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-29 03:55:44.909  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:44.909  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:44.909  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:44.909  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 03:55:44.909  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 03:55:44.909  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:44.909  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:44.909  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 03:55:44.911  5489  5489 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 03:55:44.913  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 03:55:44.915  5489  5489 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,08-29 03:55:44.918  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:44.918  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:44.918  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:44.918  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 03:55:44.918  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 03:55:44.918  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:44.918  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:44.918  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 03:55:44.921  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 03:55:44.928  5489  5489 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 03:55:44.937  5489  5489 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 03:55:45.042   928  2996 D wifi    : In wifi stop Hal
,08-29 03:55:45.042   928  2996 D wifi    : halHandle = 0x7f5f4111c0, mVM = 0x7f7854d140, mCls = 0xb3a
08-29 03:55:45.042   928  5488 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 03:55:45.042   928  5488 D WifiHAL : Got a signal to exit!!!
08-29 03:55:45.043   928  5488 I WifiHAL : Exit wifi_event_loop
,08-29 03:55:45.044   928  2996 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,08-29 03:55:45.044   928  2996 E WifiHAL : Event processing terminated
08-29 03:55:45.045   928  2996 D wifi    : In wifi cleaned up handler
08-29 03:55:45.045   928  2996 I WifiHAL : Internal cleanup completed
08-29 03:55:45.051  3680  4010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 03:55:45.053  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:45.055  4228  4228 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 03:55:45.056  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:45.068   928  5488 D wifi    : set interface wlan0 flags (DOWN)
,08-29 03:55:45.068   928  2996 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 03:55:45.275   928   945 D Tethering: InitialState.processMessage what=4
,08-29 03:55:45.284   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 03:55:47.364   388   388 I MSM-irqbalance: Discovered a new IRQ: 304
,08-29 03:55:47.876   928  3483 D WifiService: setWifiEnabled: true pid=5415, uid=10077
08-29 03:55:47.876   928  3483 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 03:55:47.881   507   922 D SoftapController: Softap fwReload - Ok
,08-29 03:55:47.884   507   922 D CommandListener: Setting iface cfg
08-29 03:55:47.884   507   922 D CommandListener: Trying to bring down wlan0
,08-29 03:55:47.885   507   922 D CommandListener: Clearing all IP addresses on wlan0
,08-29 03:55:47.888   928  2996 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 03:55:48.500   928  2996 D wifi    : set interface wlan0 flags (UP)
,08-29 03:55:48.503   928  2996 I WifiHAL : Initializing wifi
08-29 03:55:48.503   928  2996 I WifiHAL : Creating socket
,08-29 03:55:48.508   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 03:55:48.509   928  2996 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-29 03:55:48.509   928  2996 D wifi    : Did set static halHandle = 0x7f5f4111c0
08-29 03:55:48.509   928  2996 D wifi    : halHandle = 0x7f5f4111c0, mVM = 0x7f7854d140, mCls = 0x18c2
08-29 03:55:48.509   928  2996 D wifi    : array field set
,08-29 03:55:48.510   928  2996 I WifiNative-HAL: interface[0] = wlan0
08-29 03:55:48.511   928  5589 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547058946496
08-29 03:55:48.511   928  5589 D wifi    : waitForHalEvents called, vm = 0x7f7854d140, obj = 0x18c2, env = 0x7f5f408380
,08-29 03:55:48.553  5590  5590 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 03:55:48.574  5590  5590 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 03:55:48.589  5590  5590 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 03:55:48.589  5590  5590 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 03:55:48.612   928  2996 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 03:55:48.622   928  2996 D WifiConfigStore: Loading config and enabling all networks 
08-29 03:55:48.621  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:48.627  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:48.627  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:48.627  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:48.627  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 03:55:48.627  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 03:55:48.627  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:48.627  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:48.627  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 03:55:48.629  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 03:55:48.629   928  2996 D WifiConfigStore: loaded 0 passpoint configs
,08-29 03:55:48.629   928  2996 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 03:55:48.630   928  2996 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 03:55:48.631   928  2996 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 03:55:48.631   928  2996 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
,08-29 03:55:48.631   928  2996 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 03:55:48.634  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:48.634  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:48.634  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:48.634  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 03:55:48.634  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 03:55:48.634  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:48.634  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:48.634  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 03:55:48.635   928  2996 D WifiNative-HAL: Setting external_sim to 1
08-29 03:55:48.635  4228  4228 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 03:55:48.635   928  2996 D wifi    : setting dfs flag to true, 0x7f613ff600
08-29 03:55:48.635  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 03:55:48.636   928  2996 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 03:55:48.636   928  2996 D wifi    : setting scan oui 0x7f613ff600
08-29 03:55:48.636   928  2996 D WifiHAL : Sending mac address OUI
08-29 03:55:48.637  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:48.651   928  2996 E native  : do suspend true
,08-29 03:55:48.656   928   928 D RttService: SCAN_AVAILABLE : 3
08-29 03:55:48.656   928  2996 D wifi    : android_net_wifi_setLinkLayerStats: 1
,08-29 03:55:48.656   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 03:55:48.656   928  3105 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 03:55:48.657   507   922 D CommandListener: Setting iface cfg
,08-29 03:55:48.662   928  2995 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '42 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 42 Failed to set address (No such device)'
,08-29 03:55:48.662   928  2995 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 03:55:48.663   928  2995 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 03:55:48.668   928  2995 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,08-29 03:55:48.685   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=205968 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,08-29 03:55:50.890  5465  5477 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 03:55:50.890  5465  5477 D BluetoothAdapterProperties: Setting state to 13
,08-29 03:55:50.891  5465  5477 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 03:55:50.892  5465  5477 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 03:55:50.894  5465  5477 I BluetoothAdapterState: Entering PendingCommandState
,08-29 03:55:50.901  5465  5465 D BluetoothMapService: onReceive
,08-29 03:55:50.901  5465  5465 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 03:55:50.901  5465  5465 D BluetoothMapService: STATE_TURNING_OFF
08-29 03:55:50.902  5465  5465 D BluetoothMapService: MAP Service closeService in
,08-29 03:55:50.903  5465  5465 D BluetoothMapMasInstance0: MAP Service shutdown
,08-29 03:55:50.903  5465  5465 D ObexServerSockets0: shutdown(block = true)
,08-29 03:55:50.904  5465  5543 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-29 03:55:50.905  5465  5465 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 03:55:50.906  5415  5415 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 03:55:50.906  5465  5544 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 03:55:50.906  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:50.906  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:50.906  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:50.906  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 03:55:50.906  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 03:55:50.906  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:50.906  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:50.906  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 03:55:50.908  5415  5415 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:50.908  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 03:55:50.908  5465  5502 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 03:55:50.909  5465  5481 D BluetoothAdapterProperties: Scan Mode:20
08-29 03:55:50.909  5465  5477 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 03:55:50.912  5465  5465 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 03:55:50.912  5415  5415 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:50.912  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:50.912  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:50.912  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:50.912  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 03:55:50.912  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 03:55:50.912  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 03:55:50.912  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 03:55:50.912  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 03:55:50.913  5415  5415 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 03:55:50.913  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 03:55:50.913  5532  5532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 03:55:50.913  5465  5465 I BtOppRfcommListener: stopping Accept Thread
08-29 03:55:50.914  5465  5580 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 03:55:50.914  5465  5580 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 03:55:50.916  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 03:55:50.919  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 03:55:50.921  5465  5465 D HeadsetService: Received stop request...Stopping profile...
,08-29 03:55:50.923  5532  5542 D BluetoothHeadset: Proxy object disconnected
08-29 03:55:50.924   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 03:55:50.924  5465  5465 D A2dpService: Received stop request...Stopping profile...
08-29 03:55:50.924  3552  3567 D BluetoothHeadset: Proxy object disconnected
08-29 03:55:50.924  5465  5510 D A2dpStateMachine: Exit Disconnected: -1
08-29 03:55:50.925   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 03:55:50.925  3166  3182 D BluetoothHeadset: Proxy object disconnected
08-29 03:55:50.925   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 03:55:50.926  3166  3166 D HeadsetProfile: Bluetooth service disconnected
,08-29 03:55:50.929   928   928 D BluetoothA2dp: Proxy object disconnected
,08-29 03:55:50.929  3166  3166 D BluetoothA2dp: Proxy object disconnected
08-29 03:55:50.930  5465  5465 D HidService: Received stop request...Stopping profile...
08-29 03:55:50.930  5465  5465 D HidService: Stopping Bluetooth HidService
08-29 03:55:50.931  3166  3166 D BluetoothInputDevice: Proxy object disconnected
08-29 03:55:50.931  3166  3166 D HidProfile: Bluetooth service disconnected
08-29 03:55:50.931  5465  5465 D HealthService: Received stop request...Stopping profile...
08-29 03:55:50.932  5532  5532 D DockEventReceiver: finishStartingService: stopping service
,08-29 03:55:50.934  5532  5532 D HeadsetProfile: Bluetooth service disconnected
08-29 03:55:50.934  5532  5532 D BluetoothA2dp: Proxy object disconnected
,08-29 03:55:50.934  5532  5532 D BluetoothInputDevice: Proxy object disconnected
08-29 03:55:50.935  5532  5532 D HidProfile: Bluetooth service disconnected
08-29 03:55:50.935  5465  5465 D PanService: Received stop request...Stopping profile...
08-29 03:55:50.936  3166  3166 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 03:55:50.936  3166  3166 D PanProfile: Bluetooth service disconnected
08-29 03:55:50.936  5465  5465 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 03:55:50.937  5465  5465 D BluetoothMapService: stop()
08-29 03:55:50.938  5532  5532 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 03:55:50.938  5532  5532 D PanProfile: Bluetooth service disconnected
08-29 03:55:50.938  5465  5465 D BluetoothMapAppObserver: deinitObservers()
,08-29 03:55:50.938  5465  5465 D BluetoothMapAppObserver: removeReceiver()
,08-29 03:55:50.939  3166  3166 D BluetoothMap: Proxy object disconnected
,08-29 03:55:50.940  3166  3166 D MapProfile: Bluetooth service disconnected
08-29 03:55:50.940  5532  5532 D BluetoothMap: Proxy object disconnected
08-29 03:55:50.940  5532  5532 D MapProfile: Bluetooth service disconnected
08-29 03:55:50.940  5465  5465 V BluetoothAdapterState: isTurningOff()=true
,08-29 03:55:50.940  5465  5465 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:50.940  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:50.940  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:50.942  5465  5465 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 03:55:50.942  5465  5465 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 03:55:50.942  5465  5490 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 03:55:50.942  5465  5490 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 03:55:50.942  5465  5490 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 03:55:50.942  5465  5481 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-29 03:55:50.942  5465  5465 D SapService: Received stop request...Stopping profile...
08-29 03:55:50.943  5465  5465 V SapService: stop()
08-29 03:55:50.943  5465  5481 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 03:55:50.945  5465  5465 V BluetoothAdapterState: isTurningOff()=true
08-29 03:55:50.945  5465  5465 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:50.945  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:50.945  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 03:55:50.948  5465  5490 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 03:55:50.948  5465  5465 V BluetoothAdapterState: isTurningOff()=true
,08-29 03:55:50.948  5465  5490 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 03:55:50.948  5465  5465 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:50.948  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:50.948  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:50.948  5465  5481 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 03:55:50.948  5465  5490 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 03:55:50.948  5465  5490 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 03:55:50.948  5465  5490 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 03:55:50.948  5465  5490 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 03:55:50.948  5465  5465 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 03:55:50.948  3647  3647 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 03:55:50.948  5465  5465 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 03:55:50.949  5465  5465 V BluetoothAdapterState: isTurningOff()=true
08-29 03:55:50.949  5465  5465 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:50.949  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 03:55:50.949  5465  5481 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 03:55:50.949  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:50.949  5465  5465 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 03:55:50.949  5465  5465 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 03:55:50.950  5465  5465 V BluetoothAdapterState: isTurningOff()=true
08-29 03:55:50.950  5465  5465 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:50.950  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:50.950  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:50.950  5465  5465 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-29 03:55:50.950  5465  5465 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 03:55:50.951  5465  5481 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 03:55:50.951  5465  5465 D BluetoothMapService: MAP Service closeService in
08-29 03:55:50.951  5465  5465 V BluetoothAdapterState: isTurningOff()=true
08-29 03:55:50.951  5465  5465 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:50.951  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:50.951  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:50.952  5465  5465 D BluetoothMapService: cleanup()
,08-29 03:55:50.952  5465  5465 D BluetoothMapService: MAP Service closeService in
08-29 03:55:50.952  5465  5465 V BluetoothAdapterState: isTurningOff()=true
08-29 03:55:50.952  5465  5465 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:50.952  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:50.952  5465  5465 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:50.952  5465  5477 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 03:55:50.952  5465  5477 D BluetoothAdapterProperties: Setting state to 15
08-29 03:55:50.952  5465  5477 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 03:55:50.953  5465  5477 I BluetoothAdapterState: Entering BleOnState
08-29 03:55:50.954  5532  5545 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 03:55:50.958  3166  3182 D BluetoothPan: onBluetoothStateChange on: false
08-29 03:55:50.958  5532  5542 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 03:55:50.959  5532  5545 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 03:55:50.959   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 03:55:50.959   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 03:55:50.960  5532  5542 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 03:55:50.960  3552  3769 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 03:55:50.961   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 03:55:50.961  3166  3751 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 03:55:50.961  5532  5545 D BluetoothPan: onBluetoothStateChange on: false
,08-29 03:55:50.962  3166  3178 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 03:55:50.963  5532  5542 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 03:55:50.963  3166  3182 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 03:55:50.964  3166  3751 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 03:55:50.964   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 03:55:50.964  3166  3178 D BluetoothMap: onBluetoothStateChange: up=false
08-29 03:55:50.965  5465  5477 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 03:55:50.965  5465  5477 D BluetoothAdapterProperties: Setting state to 16
08-29 03:55:50.965  5465  5477 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 03:55:50.966  5465  5477 D BluetoothAdapterProperties: onBleDisable
08-29 03:55:50.966  5465  5477 I BluetoothAdapterState: Entering PendingCommandState
08-29 03:55:50.966  5465  5478 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-29 03:55:50.967  5465  5490 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 03:55:50.967  5465  5490 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 03:55:50.969  5465  5481 D BluetoothAdapterProperties: Scan Mode:20
,08-29 03:55:50.969  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:50.971  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:50.973  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 03:55:50.974  5532  5532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 03:55:50.975  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:50.979  3647  3647 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 03:55:50.982  5532  5532 D DockEventReceiver: finishStartingService: stopping service
,08-29 03:55:51.183  5465  5481 I bt_hci  : shut_down
,08-29 03:55:51.193  5465  5485 I bt_vendor: low_power_mode_cb
,08-29 03:55:51.196  5465  5485 D bt_hwcfg: hw_epilog_process
,08-29 03:55:51.199  5465  5485 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 03:55:51.199  5465  5485 I bt_vendor: epilog_cb
08-29 03:55:51.199  5465  5485 I bt_hci  : epilog_finished_callback
,08-29 03:55:51.203  5465  5481 I bt_hci_h4: hal_close
,08-29 03:55:51.204  5465  5481 I bt_userial_vendor: device fd = 51 close
,08-29 03:55:51.318  5465  5478 D bt_stack_manager: event_shut_down_stack finished.
,08-29 03:55:51.319  5465  5477 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 03:55:51.324  5465  5477 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 03:55:51.324  5465  5465 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 03:55:51.325  5465  5465 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 03:55:51.325  5465  5465 D BtGatt.GattService: stop()
08-29 03:55:51.326  5465  5465 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 03:55:51.330  5465  5465 V BluetoothAdapterState: isTurningOff()=false
08-29 03:55:51.330  5465  5465 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:51.331  5465  5465 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:51.331  5465  5465 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 03:55:51.331  5465  5477 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 03:55:51.332  5465  5477 D BluetoothAdapterProperties: Setting state to 10
08-29 03:55:51.332  5465  5477 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 03:55:51.333  5465  5477 I BluetoothAdapterState: Entering OffState
,08-29 03:55:51.336   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 03:55:51.351  5465  5465 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 03:55:51.352  5465  5465 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 03:55:51.352  5465  5478 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 03:55:51.355  5465  5478 D bt_stack_manager: event_clean_up_stack finished.
,08-29 03:55:51.355  5465  5465 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 03:55:51.358  5465  5465 I art     : System.exit called, status: 0
,08-29 03:55:51.358  5465  5465 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 03:55:51.397   928  4661 I ActivityManager: Process com.android.bluetooth (pid 5465) has died
,08-29 03:55:51.884  5590  5590 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 03:55:51.920   928  2996 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-29 03:55:51.931   928  2996 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
08-29 03:55:51.932   928  2996 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 03:55:51.944   928  2996 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-29 03:55:51.984   928  2996 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-29 03:55:52.326  5590  5590 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 03:55:52.362  5590  5590 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 03:55:52.363  5590  5590 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 03:55:52.374   928  2996 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 03:55:52.375   928  2996 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 03:55:52.375   928  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 03:55:52.388   928  2996 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 03:55:52.397   507   922 D CommandListener: Setting iface cfg
,08-29 03:55:52.405   928  2996 D WifiStateMachine: Start Dhcp Watchdog 1
,08-29 03:55:52.411   928  2996 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 03:55:52.420   928  5600 D DhcpClient: Receive thread started
,08-29 03:55:52.502   928  2996 E native  : do suspend false
,08-29 03:55:52.513   928  5599 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 03:55:52.526   928  5600 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.112, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172800, domain null
,08-29 03:55:52.527   928  5599 D DhcpClient: Got pending lease: IP address 192.168.1.112/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 03:55:52.529   928  5599 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.112 serverid=192.168.1.1
,08-29 03:55:52.540   928  5600 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.112, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 03:55:52.541   928  5599 D DhcpClient: Confirmed lease: IP address 192.168.1.112/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-29 03:55:52.542   507   922 D CommandListener: Setting iface cfg
,08-29 03:55:52.546   928  2996 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-29 03:55:52.546   928  5599 D DhcpClient: Scheduling renewal in 86399s
,08-29 03:55:52.547   928  2996 E native  : do suspend true
,08-29 03:55:52.565   928  2996 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 03:55:52.566   928  2996 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 03:55:52.567   928  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 03:55:52.570   928  2998 D ConnectivityService: Adding iface wlan0 to network 100
08-29 03:55:52.571   928  2996 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 03:55:52.602   928  2998 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 03:55:52.602   928  2998 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-29 03:55:52.604   928  2998 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-29 03:55:52.606   928  2998 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-29 03:55:52.607   928  2998 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-29 03:55:52.616   928  2998 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 03:55:52.620   928  2998 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-29 03:55:52.620   928  2998 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
08-29 03:55:52.620   928  2996 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 03:55:52.622   928  2998 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
08-29 03:55:52.622   928  2998 D ConnectivityService:    accepting network in place of null
08-29 03:55:52.622   928  2996 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 03:55:52.623   928  2998 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 03:55:52.641   928  5598 D NetlinkSocketObserver: NeighborEvent{elapsedMs=209922, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 03:55:52.648   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 03:55:52.670   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 03:55:52.673   928  2998 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-29 03:55:52.677   928  2998 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 03:55:52.677   928  2998 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 03:55:52.678  3517  3665 W QCNEJ   : |CORE| network available: 100
08-29 03:55:52.679   928  2998 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-29 03:55:52.681   928   945 D Tethering: MasterInitialState.processMessage what=3
,08-29 03:55:52.683  3517  3665 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,08-29 03:55:52.684  5415  5415 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:52.684  5161  5161 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@8278bd2 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 03:55:52.684  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:52.684  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:52.684  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:52.684  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 03:55:52.684  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 03:55:52.684  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 03:55:52.684  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 03:55:52.684  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 03:55:52.684  5415  5415 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:52.684  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 03:55:52.688  3517  3665 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,08-29 03:55:52.690  3517  3665 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
08-29 03:55:52.693  5415  5415 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:52.693  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:52.693  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:52.693  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:52.693  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 03:55:52.693  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 03:55:52.693  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 03:55:52.693  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 03:55:52.693  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 03:55:52.693  5415  5415 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:52.693  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 03:55:52.700  4832  4858 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 03:55:52.700  4832  4858 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,08-29 03:55:52.700  4832  4858 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
08-29 03:55:52.700  4832  4858 E SarControlService: no key has been found,reset the power
08-29 03:55:52.701  4832  4883 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 03:55:52.701  4832  4883 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 03:55:52.702  4832  4883 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 03:55:52.705   928  5597 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.14,2a00:1450:4001:81b::200e
08-29 03:55:52.708  4871  4871 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 03:55:52.708  4871  4871 D QcrilMsgTunnelSocket: [1000] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 03:55:52.710  4674  4674 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
08-29 03:55:52.715  4832  4883 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 03:55:52.715  4832  4883 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 03:55:52.720  4871  4887 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a7456c8 HexData = [00000000e803000000000000ffffffff]
08-29 03:55:52.720  4871  4887 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 03:55:52.721  4871  4887 D QcrilMsgTunnelSocket: [1000] < OEM_HOOK_RAW [null]
08-29 03:55:52.722  4871  4871 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 03:55:52.722  4832  4843 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,08-29 03:55:52.728  4832  4883 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 03:55:52.732  4871  4871 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 03:55:52.732  4871  4871 D QcrilMsgTunnelSocket: [1001] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 03:55:52.735  4871  4887 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a7456c8 HexData = [00000000e903000000000000ffffffff]
08-29 03:55:52.736  4871  4887 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 03:55:52.736  4871  4887 D QcrilMsgTunnelSocket: [1001] < OEM_HOOK_RAW [null]
08-29 03:55:52.737  4871  4871 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 03:55:52.738  4832  4842 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-29 03:55:52.739  3915  3915 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 03:55:52.741  5161  5161 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-29 03:55:52.743  3915  3915 D SystemUpdateService: onCreate
,08-29 03:55:52.745   928  5610 D GpsLocationProvider: NTP server returned: 1472457351565 (Mon Aug 29 03:55:51 EDT 2016) reference: 210028 certainty: 10 system time offset: -1180
08-29 03:55:52.746   928  3504 D AlarmManagerService: Setting time of day to sec=1472457351
08-29 03:55:51.565   928  3504 W AlarmManagerService: Unable to set rtc to 1472457351: Invalid argument
,08-29 03:55:51.576   928  3582 I ActivityManager: Start proc 5621:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-29 03:55:51.584  3915  3915 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 03:55:51.591   928  5597 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 07:55:51 GMT], X-Android-Received-Millis=[1472457351590], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472457352737]}
08-29 03:55:51.593   928  2998 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 03:55:51.593   928  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
,08-29 03:55:51.593   928  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 03:55:51.594   928  2998 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 03:55:51.616  5621  5621 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,08-29 03:55:51.626  3915  5631 I SystemUpdateService: active receiver: enabled
,08-29 03:55:51.642  3915  5631 I SystemUpdateService: showing system update notification
,08-29 03:55:51.643  3915  5620 I CheckinService: Checking schedule, now: 1472457351643 next: 1472239969174
08-29 03:55:51.643  3915  5620 I CheckinService: active receiver: enabled
,08-29 03:55:51.648  3915  5620 I CheckinService: Preparing to send checkin request
,08-29 03:55:51.649  3915  5620 I EventLogService: Accumulating logs since 1472457175289
,08-29 03:55:51.679  3915  5631 V SystemUpdateService: retry (wakeup: false) in 3599949 ms
,08-29 03:55:51.679  3647  3647 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 03:55:51.681  3915  3915 D SystemUpdateService: onDestroy
,08-29 03:55:51.683  3647  3647 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 03:55:51.700  3915  3915 E MDM     : [1] SitrepService.a: No Google accounts; deferring server state update.
,08-29 03:55:51.707  5621  5641 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,08-29 03:55:51.710  3915  5649 I iu.SyncManager: SYNC; picasa accounts
,08-29 03:55:51.711  3915  5620 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,08-29 03:55:51.716   928  2997 D WifiService: New client listening to asynchronous messages
,08-29 03:55:51.729  3915  3915 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-29 03:55:51.732  3915  3915 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 03:55:51.727  3915  5620 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,08-29 03:55:51.757  3915  5649 I iu.UploadsManager: num queued entries: 0
,08-29 03:55:51.758  3915  5649 I iu.UploadsManager: num updated entries: 0
,08-29 03:55:51.759  3915  5649 I iu.SyncManager: NEXT; no task
,08-29 03:55:51.760  3915  3915 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 03:55:51.762  3915  3915 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 03:55:51.766  5621  5641 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-29 03:55:51.782   928  3482 I ActivityManager: Start proc 5659:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 03:55:51.810  5621  5641 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-29 03:55:51.821  5659  5659 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,08-29 03:55:51.825  5659  5659 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 03:55:51.833  5659  5659 D SprintDMHelper: simOperator: 
,08-29 03:55:51.833  5659  5659 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 03:55:51.846   928   939 I ActivityManager: Start proc 5677:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 03:55:51.856  5673  5673 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads977400017.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads977400017.dex
,08-29 03:55:51.861  5621  5621 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-29 03:55:51.945  5673  5673 I dex2oat : dex2oat took 89.873ms (threads: 2) arena alloc=177KB java alloc=37KB native alloc=1258KB free=1045KB
,08-29 03:55:51.982  5621  5621 W InstanceID/Rpc: Found 10012
,08-29 03:55:51.987   928  3582 I ActivityManager: Start proc 5716:com.google.android.gms.unstable/u0a12 for service com.google.android.gms/.droidguard.DroidGuardService
,08-29 03:55:52.026  5716  5716 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,08-29 03:55:52.033  5716  5716 I MultiDex: VM with version 2.1.0 has multidex support
,08-29 03:55:52.033  5716  5716 I MultiDex: install
,08-29 03:55:52.033  5716  5716 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 03:55:52.064  5716  5716 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-29 03:55:52.078  5716  5716 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-29 03:55:52.162   512  3047 D WVCdm   : Instantiating CDM.
,08-29 03:55:52.164   512   512 I WVCdm   : CdmEngine::OpenSession
08-29 03:55:52.164   512   512 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-29 03:55:52.169   512   512 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-29 03:55:52.175   512   512 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
08-29 03:55:52.175   512   512 D DrmWidevineDash: Service_Initialize: starts!
08-29 03:55:52.175   512   512 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-29 03:55:52.175   512   512 D QSEECOMAPI: : App is not loaded in QSEE
08-29 03:55:52.175  5716  5730 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 03:55:52.208   512   512 D QSEECOMAPI: : Loaded image: APP id = 5
,08-29 03:55:52.209   512   512 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-29 03:55:52.210   512   512 D DrmWidevineDash: Service_Initialize: function time: 34ms (0s 34341770ns)
,08-29 03:55:52.211   512   512 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-29 03:55:52.211   512   512 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-29 03:55:52.211   512   512 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf3252000
08-29 03:55:52.211   512   512 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf3252000
,08-29 03:55:52.215   392   400 D DrmLibTime: got the req here! ret=0
,08-29 03:55:52.216   392   400 D DrmLibTime: command id, time_cmd_id = 770
08-29 03:55:52.216   392   400 D DrmLibTime: time_getutcsec starts!
08-29 03:55:52.216   392   400 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-29 03:55:52.216   392   400 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-29 03:55:52.216   392   400 D DrmLibTime: QSEE Time Listener: time_get_modem_time
,08-29 03:55:52.216   392   400 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
08-29 03:55:52.216   392   400 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-29 03:55:52.216   392   400 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-29 03:55:52.216   392   400 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
08-29 03:55:52.216   392   400 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-29 03:55:52.216   550   630 D QC-time-services: Daemon: Connection accepted:time_genoff
08-29 03:55:52.217   550  5765 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
08-29 03:55:52.217   550  5765 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-29 03:55:52.217   550  5765 D QC-time-services: offset is: 0 for base: 13
,08-29 03:55:52.217   392   400 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-29 03:55:52.217   392   400 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-29 03:55:52.217   392   400 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1472457352
08-29 03:55:52.217   392   400 D DrmLibTime: time_getutcsec returns 0, sec = 1472457352; nsec = 0
08-29 03:55:52.217   392   400 D DrmLibTime: time_getutcsec finished! 
08-29 03:55:52.217   392   400 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-29 03:55:52.217   392   400 D DrmLibTime: before calling ioctl to read the next time_cmd
08-29 03:55:52.218   550   630 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-29 03:55:52.225   512   512 D DrmWidevineDash: OEMCrypto_ION_Malloc: function time: 4ms (0s 4908073ns)
,08-29 03:55:52.225   512   512 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-29 03:55:52.225   512   512 D DrmWidevineDash: _oecc01: function time: 49ms (0s 49692500ns)
08-29 03:55:52.225   512   512 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-29 03:55:52.226   512   512 D DrmWidevineDash: hlos api version =  10
08-29 03:55:52.226   512   512 D DrmWidevineDash: tz api version =  10
08-29 03:55:52.226   512   512 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-29 03:55:52.226   512   512 D DrmWidevineDash: _oecc22: function time: 1ms (0s 1075521ns)
,08-29 03:55:52.226   512   512 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-29 03:55:52.252  5716  5759 D NativeLibraryUtils: Install completed successfully. count=17 extracted=0
,08-29 03:55:52.264   512   512 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,08-29 03:55:52.264   512   512 D DrmWidevineDash: _oecc05: function time: 38ms (0s 38000521ns)
08-29 03:55:52.264   512   512 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-29 03:55:52.264   512   512 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xffed49fc
08-29 03:55:52.264   512   512 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-29 03:55:52.265   512   512 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,08-29 03:55:52.265   512   512 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-29 03:55:52.265   512   512 D DrmWidevineDash: _oecc09: function time: 0ms (0s 862188ns)
08-29 03:55:52.265   512   512 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xf33ab688, dataLength=8
,08-29 03:55:52.267   512   512 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-29 03:55:52.267   512   512 D DrmWidevineDash: _oecc06: function time: 1ms (0s 1781146ns)
08-29 03:55:52.267   512   512 W WVCdm   : DeviceFiles::RetrieveHashedFile: /data/mediadrm/IDM1013/L1/cert.bin does not exist
08-29 03:55:52.268   512   512 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-29 03:55:52.269   512   512 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-29 03:55:52.269   512   512 D DrmWidevineDash: _oecc10: function time: 0ms (0s 985156ns)
,08-29 03:55:52.269   512   512 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-29 03:55:52.269   512   512 D DrmWidevineDash: Service_Uninitialize: starts!
08-29 03:55:52.269   512   512 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-29 03:55:52.270   512   512 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 5
08-29 03:55:52.270   512   512 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-29 03:55:52.270   512   512 D DrmWidevineDash: Service_Uninitialize: function time: 0ms (0s 847291ns)
08-29 03:55:52.271   512   512 D DrmWidevineDash: OEMCrypto_ION_Free: function time: 0ms (0s 318021ns)
08-29 03:55:52.271   512   512 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
08-29 03:55:52.271   512   512 D DrmWidevineDash: _oecc02: function time: 2ms (0s 2223073ns)
,08-29 03:55:52.273  5716  5761 W DroidGuardService: Waiting for device certificate provisioning.
08-29 03:55:52.273  5716  5761 W DroidGuardService: com.google.android.gms.droidguard.e.c: Waiting for provisioning response from server.
08-29 03:55:52.273  5716  5761 W DroidGuardService: 	at com.google.android.gms.droidguard.p.run(SourceFile:99)
08-29 03:55:52.273  5716  5761 W DroidGuardService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 03:55:52.273  5716  5761 W DroidGuardService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 03:55:52.273  5716  5761 W DroidGuardService: 	at java.lang.Thread.run(Thread.java:818)
,08-29 03:55:52.276   512  3046 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-29 03:55:52.278   512  3046 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-29 03:55:52.279   512  3046 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,08-29 03:55:52.279   512  3046 D DrmWidevineDash: Service_Initialize: starts!
08-29 03:55:52.279   512  3046 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-29 03:55:52.280   512  3046 D QSEECOMAPI: : App is not loaded in QSEE
,08-29 03:55:52.300   928  4661 I ActivityManager: Start proc 5770:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 03:55:52.307   512  3046 D QSEECOMAPI: : Loaded image: APP id = 6
,08-29 03:55:52.312   512  3046 D DrmWidevineDash: Service_Initialize: ends! returns 0
08-29 03:55:52.312   512  3046 D DrmWidevineDash: Service_Initialize: function time: 32ms (0s 32620417ns)
,08-29 03:55:52.313   512  3046 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-29 03:55:52.313   512  3046 D QSAPPSVER: qsapps_get_capabilities: returns 0
,08-29 03:55:52.313   512  3046 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf3252000
08-29 03:55:52.313   512  3046 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf3252000
,08-29 03:55:52.319   392   400 D DrmLibTime: got the req here! ret=0
,08-29 03:55:52.319   392   400 D DrmLibTime: command id, time_cmd_id = 770
08-29 03:55:52.319   392   400 D DrmLibTime: time_getutcsec starts!
08-29 03:55:52.319   392   400 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-29 03:55:52.319   392   400 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-29 03:55:52.319   392   400 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-29 03:55:52.319   392   400 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
08-29 03:55:52.319   392   400 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-29 03:55:52.319   392   400 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
,08-29 03:55:52.320   392   400 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
08-29 03:55:52.320   392   400 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-29 03:55:52.320   550   630 D QC-time-services: Daemon: Connection accepted:time_genoff
08-29 03:55:52.320   550  5782 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
08-29 03:55:52.320   550  5782 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-29 03:55:52.320   550  5782 D QC-time-services: offset is: 0 for base: 13
08-29 03:55:52.320   392   400 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-29 03:55:52.320   392   400 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-29 03:55:52.320   392   400 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1472457352
,08-29 03:55:52.320   392   400 D DrmLibTime: time_getutcsec returns 0, sec = 1472457352; nsec = 0
08-29 03:55:52.320   392   400 D DrmLibTime: time_getutcsec finished! 
08-29 03:55:52.320   392   400 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-29 03:55:52.321   392   400 D DrmLibTime: before calling ioctl to read the next time_cmd
08-29 03:55:52.321   550   630 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-29 03:55:52.324   512  3046 D DrmWidevineDash: OEMCrypto_ION_Malloc: function time: 1ms (0s 1633385ns)
,08-29 03:55:52.324   512  3046 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-29 03:55:52.324   512  3046 D DrmWidevineDash: _oecc01: function time: 44ms (0s 44830834ns)
08-29 03:55:52.324   512  3046 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-29 03:55:52.325   512  3046 D DrmWidevineDash: hlos api version =  10
08-29 03:55:52.325   512  3046 D DrmWidevineDash: tz api version =  10
08-29 03:55:52.325   512  3046 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-29 03:55:52.325   512  3046 D DrmWidevineDash: _oecc22: function time: 0ms (0s 712969ns)
08-29 03:55:52.325   512  3046 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-29 03:55:52.344   512  3046 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,08-29 03:55:52.344   512  3046 D DrmWidevineDash: _oecc05: function time: 19ms (0s 19151250ns)
08-29 03:55:52.344   512  3046 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-29 03:55:52.344   512  3046 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xf3641124
08-29 03:55:52.344   512  3046 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-29 03:55:52.345   512  3046 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-29 03:55:52.345   512  3046 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-29 03:55:52.345   512  3046 D DrmWidevineDash: _oecc09: function time: 0ms (0s 688958ns)
08-29 03:55:52.345   512  3046 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xf68e4ae0, dataLength=8
08-29 03:55:52.346   512  3046 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
08-29 03:55:52.346   512  3046 D DrmWidevineDash: _oecc06: function time: 1ms (0s 1076354ns)
,08-29 03:55:52.346   512  3046 D DrmWidevineDash: OEMCrypto_GetKeyData: starts! keyData=0xf364111c, keyDataLength=0xf3641114
,08-29 03:55:52.365   512  3046 D DrmWidevineDash: OEMCrypto_GetKeyData: ends! returns 0
,08-29 03:55:52.365   512  3046 D DrmWidevineDash: _oecc04: function time: 18ms (0s 18827656ns)
08-29 03:55:52.365   512  3046 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf36411a4
08-29 03:55:52.366   512  3046 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-29 03:55:52.366   512  3046 D DrmWidevineDash: _oecc14: function time: 0ms (0s 815052ns)
08-29 03:55:52.366   512  3046 D DrmWidevineDash: OEMCrypto_GenerateDerivedKeys: starts! SID=1, mac_key_context=0xf3b15070
08-29 03:55:52.366   512  3046 D DrmWidevineDash: mac_key_context_length=109, enc_key_context=0xf3b150e0, enc_key_context_length=105
,08-29 03:55:52.387  5770  5770 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 03:55:52.389   512  3046 D DrmWidevineDash: OEMCrypto_GenerateDerivedKeys: ends! returns 0
08-29 03:55:52.389   512  3046 D DrmWidevineDash: _oecc12: function time: 22ms (0s 22909843ns)
,08-29 03:55:52.389   512  3046 D DrmWidevineDash: OEMCrypto_GenerateSignature: starts! SID=1, message=0xf4f338e0
08-29 03:55:52.389   512  3046 D DrmWidevineDash: message_length=90, signature=0xf36411cd, signature_length=0xf3641144
08-29 03:55:52.389   512  3046 E DrmWidevineDash: OEMCrypto_GenerateSignature : input wrapped_rsa_key == NULL!, return short buffer
08-29 03:55:52.389   512  3046 D DrmWidevineDash: OEMCrypto_GenerateSignature: ends! returns 7
08-29 03:55:52.389   512  3046 D DrmWidevineDash: _oecc13: function time: 0ms (0s 150886ns)
08-29 03:55:52.389   512  3046 D DrmWidevineDash: OEMCrypto_GenerateSignature: starts! SID=1, message=0xf4f338e0
08-29 03:55:52.389   512  3046 D DrmWidevineDash: message_length=90, signature=0xf4e52390, signature_length=0xf3641144
08-29 03:55:52.391   512  3046 D DrmWidevineDash: OEMCrypto_GenerateSignature: ends! returns 0
08-29 03:55:52.391   512  3046 D DrmWidevineDash: _oecc13: function time: 1ms (0s 1802448ns)
,08-29 03:55:52.393  5716  5768 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 03:55:52.488  4228  5769 I Babel   : connection state changed from UNKNOWN to CONNECTED
,08-29 03:55:52.493   928  3450 I ActivityManager: Killing 5016:com.google.android.gm/u0a68 (adj 15): empty #17
,08-29 03:55:52.701   928  3450 E libprocessgroup: failed to kill 1 processes for processgroup 5016
,08-29 03:55:52.705   512  3047 D DrmWidevineDash: OEMCrypto_RewrapDeviceRSAKey: starts! SID=1, message=0xf33a0c00, message_length=2521
,08-29 03:55:52.705   512  3047 D DrmWidevineDash: signature=0xf33ab480, signature_length=32, nonce=0xf33a15d5, enc_rsa_key=0xf33a0c03
,08-29 03:55:52.705   512  3047 D DrmWidevineDash: enc_rsa_key_length=1232, wrapped_rsa_key=0x0, wrapped_rsa_key_length=0xf3542120
08-29 03:55:52.706   512  3047 E DrmWidevineDash: OEMCrypto_RewrapDeviceRSAKey : input wrapped_rsa_key == NULL!, return short buffer
08-29 03:55:52.706   512  3047 D DrmWidevineDash: OEMCrypto_RewrapDeviceRSAKey: ends! returns 7
,08-29 03:55:52.706   512  3047 D DrmWidevineDash: _oecc18: function time: 0ms (0s 312500ns)
08-29 03:55:52.706   512  3047 D DrmWidevineDash: OEMCrypto_RewrapDeviceRSAKey: starts! SID=1, message=0xf33a0c00, message_length=2521
08-29 03:55:52.706   512  3047 D DrmWidevineDash: signature=0xf33ab480, signature_length=32, nonce=0xf33a15d5, enc_rsa_key=0xf33a0c03
08-29 03:55:52.706   512  3047 D DrmWidevineDash: enc_rsa_key_length=1232, wrapped_rsa_key=0xf31e9c00, wrapped_rsa_key_length=0xf3542120
08-29 03:55:52.717   512  3047 D DrmWidevineDash: OEMCrypto_RewrapDeviceRSAKey: ends! returns 0
08-29 03:55:52.717   512  3047 D DrmWidevineDash: _oecc18: function time: 11ms (0s 11309270ns)
,08-29 03:55:52.717   512  3047 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-29 03:55:52.718   512  3047 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-29 03:55:52.718   512  3047 D DrmWidevineDash: _oecc10: function time: 1ms (0s 1313333ns)
08-29 03:55:52.724   512  3047 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-29 03:55:52.725   512  3047 D DrmWidevineDash: Service_Uninitialize: starts!
08-29 03:55:52.725   512  3047 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-29 03:55:52.725   512  3047 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 6
,08-29 03:55:52.726   928   945 I ActivityManager: Start proc 5791:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
08-29 03:55:52.727   512  3047 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-29 03:55:52.727   512  3047 D DrmWidevineDash: Service_Uninitialize: function time: 1ms (0s 1612136ns)
08-29 03:55:52.727   512  3047 D DrmWidevineDash: OEMCrypto_ION_Free: function time: 0ms (0s 464791ns)
08-29 03:55:52.728   512  3047 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
08-29 03:55:52.728   512  3047 D DrmWidevineDash: _oecc02: function time: 3ms (0s 3749219ns)
,08-29 03:55:52.789  5791  5791 D AdapterServiceConfig: Adding HeadsetService
,08-29 03:55:52.789  5791  5791 D AdapterServiceConfig: Adding A2dpService
08-29 03:55:52.789  5791  5791 D AdapterServiceConfig: Adding HidService
08-29 03:55:52.789  5791  5791 D AdapterServiceConfig: Adding HealthService
08-29 03:55:52.789  5791  5791 D AdapterServiceConfig: Adding PanService
08-29 03:55:52.790  5791  5791 D AdapterServiceConfig: Adding GattService
08-29 03:55:52.790  5791  5791 D AdapterServiceConfig: Adding BluetoothMapService
08-29 03:55:52.790  5791  5791 D AdapterServiceConfig: Adding SapService
,08-29 03:55:52.799   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f52dc74:true
,08-29 03:55:52.800  5791  5791 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 03:55:52.803  5791  5791 I bt_bluedroid: init
,08-29 03:55:52.803  5791  5803 I BluetoothAdapterState: Entering OffState
,08-29 03:55:52.805  5791  5804 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 03:55:52.805  5791  5804 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 03:55:52.805  5791  5804 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 03:55:52.805  5791  5804 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 03:55:52.805  5791  5791 I bt_bluedroid: get_profile_interface socket
,08-29 03:55:52.807  5791  5807 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
08-29 03:55:52.808  5791  5791 I bt_bluedroid: get_profile_interface sdp
08-29 03:55:52.809  5791  5807 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 03:55:52.810  5791  5802 I bt_bluedroid: config_hci_snoop_log
,08-29 03:55:52.811   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 03:55:52.815  5791  5803 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 03:55:52.815  5791  5803 D BluetoothAdapterProperties: Setting state to 14
08-29 03:55:52.815  5791  5803 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 03:55:52.816  5791  5803 D BluetoothBondStateMachine: make
,08-29 03:55:52.818  5791  5808 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 03:55:52.820  5791  5803 I BluetoothAdapterState: Entering PendingCommandState
,08-29 03:55:52.821  5791  5791 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 03:55:52.823  5791  5791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
08-29 03:55:52.823  5791  5791 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 03:55:52.825  5791  5791 D BtGatt.GattService: Received start request. Starting profile...
08-29 03:55:52.825  5791  5791 D BtGatt.GattService: start()
08-29 03:55:52.825  5791  5791 I bt_bluedroid: get_profile_interface gatt
08-29 03:55:52.825  5791  5791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
08-29 03:55:52.825  5791  5791 D BtGatt.AdvertiseManager: advertise manager created
,08-29 03:55:52.830  5791  5791 V BluetoothAdapterState: isTurningOff()=false
,08-29 03:55:52.830  5791  5791 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:52.830  5791  5791 V BluetoothAdapterState: isBleTurningOn()=true
08-29 03:55:52.830  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:52.830  5791  5803 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 03:55:52.831  5791  5803 I bt_bluedroid: enable
08-29 03:55:52.831  5791  5804 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 03:55:52.831  5791  5804 I bt_hci  : start_up
,08-29 03:55:52.836  5791  5804 I bt_vendor: alloc value 0xf3fe104d
08-29 03:55:52.836  5791  5804 I bt_vendor: init
,08-29 03:55:52.836  5791  5804 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 03:55:52.836  5791  5804 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 03:55:52.924  5730  5730 W Binder_1: type=1400 audit(0.0:71): avc: denied { read } for name="/" dev="tmpfs" ino=1112 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=dir permissive=0
,08-29 03:55:52.958  5791  5804 D bt_hci  : start_up starting async portion
,08-29 03:55:52.958  5791  5811 I bt_hci  : event_finish_startup
,08-29 03:55:52.958  5791  5811 I bt_hci_h4: hal_open
08-29 03:55:52.959  5791  5811 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
08-29 03:55:52.954  5812  5812 W irq/448-msm_hs_: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
08-29 03:55:52.960  5791  5811 I bt_userial_vendor: device fd = 51 open
,08-29 03:55:52.974  5791  5811 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 03:55:52.976  5791  5811 D bt_hwcfg: Chipset BCM4358A3
,08-29 03:55:52.976  5791  5811 D bt_hwcfg: Target name = [BCM4358A3]
08-29 03:55:52.976  5791  5811 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 03:55:53.086  5814  5814 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-29 03:55:53.150  5814  5814 I dex2oat : dex2oat took 65.066ms (threads: 2) arena alloc=75KB java alloc=40KB native alloc=1282KB free=1277KB
,08-29 03:55:53.157  5716  5730 W System  : ClassLoader referenced unknown path: 
,08-29 03:55:53.192  5716  5730 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 03:55:53.192  5716  5730 I Adreno  : Build Date                       : 10/21/15
08-29 03:55:53.192  5716  5730 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 03:55:53.192  5716  5730 I Adreno  : Local Branch                     : 
08-29 03:55:53.192  5716  5730 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 03:55:53.192  5716  5730 I Adreno  : Remote Branch                    : NONE
08-29 03:55:53.192  5716  5730 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 03:55:53.270  5791  5811 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 03:55:53.270  5791  5811 D bt_hwcfg: Settlement delay -- 100 ms
08-29 03:55:53.270  5791  5811 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 03:55:53.296  5716  5730 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 03:55:53.296  5716  5730 I Adreno  : Build Date                       : 10/21/15
08-29 03:55:53.296  5716  5730 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 03:55:53.296  5716  5730 I Adreno  : Local Branch                     : 
08-29 03:55:53.296  5716  5730 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 03:55:53.296  5716  5730 I Adreno  : Remote Branch                    : NONE
08-29 03:55:53.296  5716  5730 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 03:55:53.371   512   512 I WVCdm   : CdmEngine::OpenSession
,08-29 03:55:53.371   512   512 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
08-29 03:55:53.373   512   512 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
08-29 03:55:53.374   512   512 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,08-29 03:55:53.374   512   512 D DrmWidevineDash: Service_Initialize: starts!
08-29 03:55:53.374   512   512 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-29 03:55:53.375   512   512 D QSEECOMAPI: : App is not loaded in QSEE
,08-29 03:55:53.394  5791  5811 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 03:55:53.394  5791  5811 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,08-29 03:55:53.395  5791  5811 I bt_hwcfg: vendor lib fwcfg completed
,08-29 03:55:53.395  5791  5811 I bt_vendor: firmware callback
,08-29 03:55:53.395  5791  5811 I bt_hci  : firmware_config_callback
08-29 03:55:53.399  5791  5820 I bt_btu  : btu_task pending for preload complete event
08-29 03:55:53.399  5791  5820 I bt_btu_task: Bluetooth chip preload is complete
08-29 03:55:53.399  5791  5820 I bt_btu  : btu_task received preload complete event
,08-29 03:55:53.402   512   512 D QSEECOMAPI: : Loaded image: APP id = 7
,08-29 03:55:53.403  5791  5820 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 03:55:53.403  5791  5820 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 03:55:53.403  5791  5820 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 03:55:53.403  5791  5820 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 03:55:53.404  5791  5820 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 03:55:53.404  5791  5820 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 03:55:53.404  5791  5820 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 03:55:53.404  5791  5820 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 03:55:53.404  5791  5820 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 03:55:53.404  5791  5820 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 03:55:53.404  5791  5820 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 03:55:53.404  5791  5820 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 03:55:53.404   512   512 D DrmWidevineDash: Service_Initialize: ends! returns 0
08-29 03:55:53.404  5791  5820 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 03:55:53.404  5791  5820 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 03:55:53.404   512   512 D DrmWidevineDash: Service_Initialize: function time: 29ms (0s 29722187ns)
08-29 03:55:53.404  5791  5820 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 03:55:53.405   512   512 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-29 03:55:53.405   512   512 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-29 03:55:53.405   512   512 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf3252000
08-29 03:55:53.405   512   512 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf3252000
,08-29 03:55:53.410   392   400 D DrmLibTime: got the req here! ret=0
08-29 03:55:53.410   392   400 D DrmLibTime: command id, time_cmd_id = 770
08-29 03:55:53.410   392   400 D DrmLibTime: time_getutcsec starts!
,08-29 03:55:53.410   392   400 D DrmLibTime: QSEE Time Listener: time_getutcsec
,08-29 03:55:53.410   392   400 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-29 03:55:53.410   392   400 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-29 03:55:53.410   392   400 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
08-29 03:55:53.411   392   400 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-29 03:55:53.411   392   400 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
,08-29 03:55:53.411   392   400 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
08-29 03:55:53.411   392   400 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-29 03:55:53.411   550   630 D QC-time-services: Daemon: Connection accepted:time_genoff
08-29 03:55:53.411   550  5822 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
08-29 03:55:53.412   550  5822 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-29 03:55:53.412   550  5822 D QC-time-services: offset is: 0 for base: 13
08-29 03:55:53.412   392   400 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-29 03:55:53.412   392   400 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-29 03:55:53.412   392   400 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1472457353
08-29 03:55:53.412   392   400 D DrmLibTime: time_getutcsec returns 0, sec = 1472457353; nsec = 0
08-29 03:55:53.412   392   400 D DrmLibTime: time_getutcsec finished! 
,08-29 03:55:53.412   392   400 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-29 03:55:53.412   392   400 D DrmLibTime: before calling ioctl to read the next time_cmd
08-29 03:55:53.413   550   630 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-29 03:55:53.415   512   512 D DrmWidevineDash: OEMCrypto_ION_Malloc: function time: 1ms (0s 1691354ns)
08-29 03:55:53.415   512   512 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-29 03:55:53.415   512   512 D DrmWidevineDash: _oecc01: function time: 40ms (0s 40609844ns)
08-29 03:55:53.415   512   512 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-29 03:55:53.416   512   512 D DrmWidevineDash: hlos api version =  10
,08-29 03:55:53.416   512   512 D DrmWidevineDash: tz api version =  10
08-29 03:55:53.416   512   512 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-29 03:55:53.416   512   512 D DrmWidevineDash: _oecc22: function time: 0ms (0s 880989ns)
08-29 03:55:53.416   512   512 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-29 03:55:53.463   512   512 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,08-29 03:55:53.463   512   512 D DrmWidevineDash: _oecc05: function time: 47ms (0s 47320156ns)
08-29 03:55:53.463   512   512 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-29 03:55:53.463   512   512 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xffed49fc
08-29 03:55:53.463   512   512 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-29 03:55:53.464   512   512 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-29 03:55:53.464   512   512 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-29 03:55:53.464   512   512 D DrmWidevineDash: _oecc09: function time: 0ms (0s 616145ns)
08-29 03:55:53.464   512   512 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xf33ab688, dataLength=8
08-29 03:55:53.465   512   512 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-29 03:55:53.465   512   512 D DrmWidevineDash: _oecc06: function time: 1ms (0s 1004532ns)
,08-29 03:55:53.474  5791  5820 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f5ec99
,08-29 03:55:53.474  5791  5820 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f5ec99 
,08-29 03:55:53.477   512   512 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xf68fe200, wrapped_rsa_key_length=1280
,08-29 03:55:53.482   512   512 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-29 03:55:53.482   512   512 D DrmWidevineDash: _oecc19: function time: 5ms (0s 5280209ns)
08-29 03:55:53.482   512   512 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-29 03:55:53.484   512  3045 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-29 03:55:53.484   512  3045 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-29 03:55:53.484   512  3045 I WVCdm   : CdmEngine::GenerateKeyRequest
08-29 03:55:53.484   512  3045 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xf3182c40, idLength=0xf373ff14
08-29 03:55:53.490  5791  5807 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-29 03:55:53.491  5791  5807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 03:55:53.491  5791  5807 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
08-29 03:55:53.492  5791  5807 D BluetoothAdapterProperties: Name is: Nexus 6P
08-29 03:55:53.493  5791  5807 D BluetoothAdapterProperties: Scan Mode:20
08-29 03:55:53.494  5791  5807 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 03:55:53.494  5791  5807 D bt_hci  : do_postload posting postload work item
08-29 03:55:53.494  5791  5811 I bt_hci  : event_postload
08-29 03:55:53.494  5791  5811 I bt_vendor: sco_config_cb
08-29 03:55:53.494  5791  5811 I bt_hci  : sco_config_callback postload finished.
08-29 03:55:53.495  5791  5807 D bt_bte_conf: Device ID record 1 : primary
08-29 03:55:53.495  5791  5807 D bt_bte_conf:   vendorId            = 000f
,08-29 03:55:53.495  5791  5807 D bt_bte_conf:   vendorIdSource      = 0001
08-29 03:55:53.495  5791  5807 D bt_bte_conf:   product             = 1200
08-29 03:55:53.495  5791  5807 D bt_bte_conf:   version             = 1436
08-29 03:55:53.495  5791  5807 D bt_bte_conf:   clientExecutableURL = 
08-29 03:55:53.495  5791  5807 D bt_bte_conf:   serviceDescription  = 
08-29 03:55:53.495  5791  5807 D bt_bte_conf:   documentationURL    = 
08-29 03:55:53.495  5791  5807 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 03:55:53.495  5791  5804 D bt_stack_manager: event_start_up_stack finished
08-29 03:55:53.496  5791  5803 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 03:55:53.496  5791  5803 D BluetoothAdapterProperties: Setting state to 15
08-29 03:55:53.496  5791  5803 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 03:55:53.497  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 03:55:53.497  5791  5803 I BluetoothAdapterState: Entering BleOnState
08-29 03:55:53.499  5791  5803 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 03:55:53.499  5791  5803 D BluetoothAdapterProperties: Setting state to 11
08-29 03:55:53.499  5791  5803 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 03:55:53.500  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 03:55:53.502  5791  5811 I bt_vendor: low_power_mode_cb
08-29 03:55:53.503  5791  5791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
08-29 03:55:53.504  5791  5791 D HeadsetService: Received start request. Starting profile...
08-29 03:55:53.506  5791  5791 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 03:55:53.506  5791  5791 D HeadsetStateMachine: make
,08-29 03:55:53.509  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:53.513  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 03:55:53.515  5791  5803 I BluetoothAdapterState: Entering PendingCommandState
08-29 03:55:53.516  5791  5791 D HeadsetStateMachine: max_hf_connections = 1
08-29 03:55:53.516  5791  5791 I bt_bluedroid: get_profile_interface handsfree
08-29 03:55:53.516  5791  5807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 03:55:53.516  5791  5807 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-29 03:55:53.518  5791  5791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
08-29 03:55:53.519  5791  5791 D A2dpService: Received start request. Starting profile...
,08-29 03:55:53.519  5791  5791 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 03:55:53.520  5791  5791 I bt_bluedroid: get_profile_interface avrcp
,08-29 03:55:53.524  5791  5791 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 03:55:53.524  5791  5791 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 03:55:53.524  5791  5791 D A2dpStateMachine: make
,08-29 03:55:53.526  5791  5791 I bt_bluedroid: get_profile_interface a2dp
,08-29 03:55:53.528  5791  5830 D A2dpStateMachine: Enter Disconnected: -2
,08-29 03:55:53.528  5791  5791 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 03:55:53.529  5791  5791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
08-29 03:55:53.530  5791  5807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 03:55:53.530  5791  5791 D HidService: Received start request. Starting profile...
,08-29 03:55:53.530  5791  5791 I bt_bluedroid: get_profile_interface hidhost
,08-29 03:55:53.530  5791  5791 D HidService: setHidService(): set to: null
08-29 03:55:53.530  5791  5807 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f402d9
08-29 03:55:53.530  5791  5807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 03:55:53.531  5791  5791 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 03:55:53.531  5791  5791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
08-29 03:55:53.532  5791  5791 D HealthService: Received start request. Starting profile...
,08-29 03:55:53.533  5791  5791 I bt_bluedroid: get_profile_interface health
,08-29 03:55:53.533  5791  5791 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 03:55:53.534  5791  5791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
,08-29 03:55:53.535  5791  5791 D PanService: Received start request. Starting profile...
08-29 03:55:53.535  5791  5791 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 03:55:53.535  5791  5791 I bt_bluedroid: get_profile_interface pan
08-29 03:55:53.535  5791  5807 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 03:55:53.537  5791  5791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
08-29 03:55:53.537  5791  5791 D BluetoothMapService: Received start request. Starting profile...
08-29 03:55:53.537  5791  5791 D BluetoothMapService: start()
,08-29 03:55:53.545   512  3045 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-29 03:55:53.546   512  3045 D DrmWidevineDash: _oecc07: function time: 61ms (0s 61265104ns)
08-29 03:55:53.546   512  3045 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-29 03:55:53.546  5791  5791 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 03:55:53.546   512  3045 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-29 03:55:53.546   512  3045 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x22
08-29 03:55:53.546   512  3045 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
,08-29 03:55:53.546   512  3045 D DrmWidevineDash: _oecc29: function time: 0ms (0s 745677ns)
08-29 03:55:53.546   512  3045 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
08-29 03:55:53.547  5791  5791 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 03:55:53.547  5791  5791 D BluetoothMapAppObserver: createReceiver()
08-29 03:55:53.547   512  3045 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
08-29 03:55:53.547   512  3045 D DrmWidevineDash: _oecc39: function time: 0ms (0s 706459ns)
,08-29 03:55:53.547   512  3045 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-29 03:55:53.548   512  3045 D DrmWidevineDash: hlos api version =  10
08-29 03:55:53.548   512  3045 D DrmWidevineDash: tz api version =  10
08-29 03:55:53.548   512  3045 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-29 03:55:53.548   512  3045 D DrmWidevineDash: _oecc22: function time: 0ms (0s 617136ns)
08-29 03:55:53.548   512  3045 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,08-29 03:55:53.548  5791  5791 D BluetoothMapAppObserver: initObservers()
08-29 03:55:53.548  5791  5791 D BluetoothMapAppObserver: getEnabledAccountItems()
08-29 03:55:53.548   512  3045 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
08-29 03:55:53.548   512  3045 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-29 03:55:53.548   512  3045 D DrmWidevineDash: _oecc44: function time: 0ms (0s 620469ns)
08-29 03:55:53.549   512  3045 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf3740048
08-29 03:55:53.549   512  3045 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-29 03:55:53.549   512  3045 D DrmWidevineDash: _oecc14: function time: 0ms (0s 712604ns)
,08-29 03:55:53.549   512  3045 D WVCdm   : PrepareKeyRequest: nonce=1062664386
08-29 03:55:53.549   512  3045 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xf68b0300
08-29 03:55:53.549   512  3045 D DrmWidevineDash: message_length=1656, signature=0xf323c180, signature_length=0xf373ffec
,08-29 03:55:53.555  5791  5791 V SapService: SapBinder()
,08-29 03:55:53.555  5791  5791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7dece3
,08-29 03:55:53.556  5791  5791 D SapService: Received start request. Starting profile...
,08-29 03:55:53.556  5791  5791 V SapService: start()
08-29 03:55:53.558  5791  5791 V BluetoothAdapterState: isTurningOff()=false
08-29 03:55:53.558  5791  5791 V BluetoothAdapterState: isTurningOn()=true
08-29 03:55:53.558  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:53.558  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:53.558  5791  5791 V BluetoothAdapterState: isTurningOff()=false
,08-29 03:55:53.558  5791  5791 V BluetoothAdapterState: isTurningOn()=true
08-29 03:55:53.558  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:53.558  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:53.558  5791  5827 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
08-29 03:55:53.558  5791  5791 V BluetoothAdapterState: isTurningOff()=false
08-29 03:55:53.558  5791  5791 V BluetoothAdapterState: isTurningOn()=true
08-29 03:55:53.559  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:53.559  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:53.559  5791  5791 V BluetoothAdapterState: isTurningOff()=false
,08-29 03:55:53.559  5791  5791 V BluetoothAdapterState: isTurningOn()=true
08-29 03:55:53.559  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:53.559  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:53.559  5791  5791 V BluetoothAdapterState: isTurningOff()=false
08-29 03:55:53.559  5791  5791 V BluetoothAdapterState: isTurningOn()=true
08-29 03:55:53.559  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:53.559  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:53.559  5791  5791 V BluetoothAdapterState: isTurningOff()=false
08-29 03:55:53.559  5791  5791 V BluetoothAdapterState: isTurningOn()=true
08-29 03:55:53.559  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 03:55:53.559  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:53.560  5791  5791 V BluetoothAdapterState: isTurningOff()=false
08-29 03:55:53.560  5791  5791 V BluetoothAdapterState: isTurningOn()=true
08-29 03:55:53.560  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:53.560  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:53.560  5791  5803 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 03:55:53.560  5791  5803 D BluetoothAdapterProperties: ScanMode =  20
08-29 03:55:53.560  5791  5803 D BluetoothAdapterProperties: State =  11
08-29 03:55:53.561  5791  5807 D BluetoothAdapterProperties: Scan Mode:21
,08-29 03:55:53.561  5791  5803 D BluetoothAdapterProperties: Setting state to 12
08-29 03:55:53.561  5791  5803 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 03:55:53.562  5791  5803 I BluetoothAdapterState: Entering OnState
08-29 03:55:53.562  5532  5748 D BluetoothMap: onBluetoothStateChange: up=true
08-29 03:55:53.562  5791  5807 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 03:55:53.564  3166  3178 D BluetoothPan: onBluetoothStateChange on: true
08-29 03:55:53.566  5532  5542 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 03:55:53.566  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:53.566  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:53.566  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:53.566  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 03:55:53.566  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 03:55:53.566  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 03:55:53.566  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 03:55:53.566  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 03:55:53.566  3166  3166 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 03:55:53.566  3166  3166 D PanProfile: Bluetooth service connected
08-29 03:55:53.567  5532  5748 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 03:55:53.568  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 03:55:53.569   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 03:55:53.569   928   928 D BluetoothA2dp: Proxy object connected
08-29 03:55:53.569   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 03:55:53.570  5532  5542 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 03:55:53.571  3552  3567 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 03:55:53.571  5532  5532 D BluetoothMap: Proxy object connected
,08-29 03:55:53.571   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 03:55:53.572  5532  5532 D MapProfile: Bluetooth service connected
08-29 03:55:53.572  5532  5532 D BluetoothMap: getConnectedDevices()
08-29 03:55:53.572  3166  3182 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 03:55:53.572  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:53.572  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:53.572  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:53.572  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 03:55:53.572  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 03:55:53.572  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 03:55:53.572  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 03:55:53.572  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 03:55:53.573  5532  5532 D BluetoothA2dp: Proxy object connected
08-29 03:55:53.573  3166  3166 D BluetoothA2dp: Proxy object connected
08-29 03:55:53.574  5791  5791 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 03:55:53.574  5532  5532 D BluetoothInputDevice: Proxy object connected
,08-29 03:55:53.574  5532  5532 D HidProfile: Bluetooth service connected
08-29 03:55:53.574  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 03:55:53.575  5791  5791 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 03:55:53.575  5532  5545 D BluetoothPan: onBluetoothStateChange on: true
08-29 03:55:53.576  5791  5791 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 03:55:53.577  3166  3751 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 03:55:53.578  5532  5748 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 03:55:53.578  3166  3178 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 03:55:53.578  5791  5791 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 03:55:53.580  3166  3182 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 03:55:53.580  5791  5791 D ObexServerSockets: Succeed to create listening sockets 
08-29 03:55:53.580  5791  5791 D ObexServerSockets0: startAccept()
08-29 03:55:53.580  5791  5791 D ObexServerSockets0: prepareForNewConnect()
,08-29 03:55:53.581   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 03:55:53.581  3166  3166 D BluetoothInputDevice: Proxy object connected
,08-29 03:55:53.581  3166  3166 D HidProfile: Bluetooth service connected
08-29 03:55:53.581  3166  3178 D BluetoothMap: onBluetoothStateChange: up=true
08-29 03:55:53.582  5532  5532 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 03:55:53.582  5532  5532 D PanProfile: Bluetooth service connected
08-29 03:55:53.583  5791  5791 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 03:55:53.583  5791  5791 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 03:55:53.583  3166  3166 D BluetoothMap: Proxy object connected
08-29 03:55:53.583  3166  3166 D MapProfile: Bluetooth service connected
08-29 03:55:53.583  3166  3166 D BluetoothMap: getConnectedDevices()
08-29 03:55:53.585   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 03:55:53.585  5791  5835 D ObexServerSockets0: Accepting socket connection...
08-29 03:55:53.585  5791  5836 D ObexServerSockets0: Accepting socket connection...
08-29 03:55:53.585  5791  5791 D BluetoothMapService: onReceive
08-29 03:55:53.585  5791  5791 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 03:55:53.585  5791  5791 D BluetoothMapService: STATE_ON
,08-29 03:55:53.587  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:53.588  5791  5837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 03:55:53.589  5791  5837 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 03:55:53.589  5791  5837 D BluetoothSdpJni: SDP Create record success - handle: 1
08-29 03:55:53.589  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:53.606  5791  5791 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 03:55:53.607  5791  5791 D ObexServerSockets0: prepareForNewConnect()
,08-29 03:55:53.642   512  3045 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-29 03:55:53.642   512  3045 D DrmWidevineDash: _oecc36: function time: 92ms (0s 92334010ns)
,08-29 03:55:53.643   512   512 I WVCdm   : CdmEngine::CloseSession
,08-29 03:55:53.643   512   512 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-29 03:55:53.643   512   512 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-29 03:55:53.644   512   512 D DrmWidevineDash: _oecc10: function time: 0ms (0s 578959ns)
08-29 03:55:53.644   512   512 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-29 03:55:53.644   512   512 D DrmWidevineDash: Service_Uninitialize: starts!
08-29 03:55:53.644   512   512 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-29 03:55:53.644   512   512 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 7
,08-29 03:55:53.645   512   512 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-29 03:55:53.645   512   512 D DrmWidevineDash: Service_Uninitialize: function time: 0ms (0s 588646ns)
08-29 03:55:53.645   512   512 D DrmWidevineDash: OEMCrypto_ION_Free: function time: 0ms (0s 209531ns)
08-29 03:55:53.645   512   512 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
08-29 03:55:53.645   512   512 D DrmWidevineDash: _oecc02: function time: 1ms (0s 1331302ns)
,08-29 03:55:53.668  3915  5620 I CheckinRequestBuilder: Classify the device as Phone.
,08-29 03:55:53.671  5532  5545 D BluetoothHeadset: Proxy object connected
,08-29 03:55:53.671   928   928 D BluetoothHeadset: Proxy object connected
,08-29 03:55:53.671  3552  3769 D BluetoothHeadset: Proxy object connected
,08-29 03:55:53.671   928   928 D BluetoothHeadset: Proxy object connected
08-29 03:55:53.672  3552  3567 D BluetoothHeadset: Proxy object connected
08-29 03:55:53.672  3166  3178 D BluetoothHeadset: Proxy object connected
,08-29 03:55:53.672  3166  3166 D HeadsetProfile: Bluetooth service connected
08-29 03:55:53.672   928   928 D BluetoothHeadset: Proxy object connected
08-29 03:55:53.672   928   945 D BluetoothHeadset: Proxy object connected
08-29 03:55:53.673  5532  5532 D HeadsetProfile: Bluetooth service connected
,08-29 03:55:53.677  3166  3751 D BluetoothHeadset: Proxy object connected
,08-29 03:55:53.678  3166  3166 D HeadsetProfile: Bluetooth service connected
08-29 03:55:53.678   928  4661 I ActivityManager: Killing 5161:com.google.android.music:main/u0a59 (adj 15): empty #17
08-29 03:55:53.678  5532  5748 D BluetoothHeadset: Proxy object connected
,08-29 03:55:53.681   928   945 D BluetoothHeadset: Proxy object connected
,08-29 03:55:53.686  5532  5532 D HeadsetProfile: Bluetooth service connected
,08-29 03:55:53.739   928   938 I ActivityManager: Killing 4419:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-29 03:55:53.830   928  3482 I ActivityManager: Start proc 5846:com.google.android.calendar/u0a36 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,08-29 03:55:53.867  5846  5846 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm64
,08-29 03:55:53.923   928  3199 I ActivityManager: Start proc 5862:com.android.providers.calendar/u0a1 for content provider com.android.providers.calendar/.CalendarProvider2
,08-29 03:55:53.967  5846  5846 E TimelyPrefService: Primary account is null
,08-29 03:55:53.966  5862  5862 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm64
,08-29 03:55:54.008  5862  5862 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@aa86347(com.android.providers.calendar.CalendarProvider2@7dc1774)
,08-29 03:55:54.019   928   938 I ActivityManager: Start proc 5877:com.google.android.deskclock/u0a66 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,08-29 03:55:54.020   928   938 I ActivityManager: Killing 4845:android.process.acore/u0a2 (adj 15): empty #17
,08-29 03:55:54.042   928   938 I ActivityManager: Killing 5299:com.android.defcontainer/u0a7 (adj 15): empty #18
,08-29 03:55:54.071  5846  5846 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,08-29 03:55:54.095  5877  5877 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,08-29 03:55:54.112  5877  5877 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-29 03:55:54.112  5877  5877 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 03:55:54.112  5877  5877 I GAv4    :   adb logcat -s GAv4
,08-29 03:55:54.139  5877  5877 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 03:55:54.146  5877  5877 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 03:55:54.165  5877  5893 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 03:55:54.222   928   938 I ActivityManager: Start proc 5895:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,08-29 03:55:54.254  5895  5895 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm64
,08-29 03:55:54.262  5895  5895 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1472457354262
,08-29 03:55:54.262  5895  5895 D         : TimeServiceNative: User Time to be set is 1472457354262
08-29 03:55:54.262  5895  5895 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-29 03:55:54.262  5895  5895 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-29 03:55:54.262  5895  5895 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1472457354262
,08-29 03:55:54.262   550   630 D QC-time-services: Daemon: Connection accepted:time_genoff
08-29 03:55:54.263  5895  5895 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,08-29 03:55:54.263   550  5907 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1472457354262
08-29 03:55:54.263   550  5907 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1472457354262, operation = 0
,08-29 03:55:54.263   550  5907 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/13/70 4:58:0
08-29 03:55:54.263   550  5907 D QC-time-services: Daemon:Value read from RTC seconds = 8830680000
08-29 03:55:54.263   550  5907 D QC-time-services: Daemon:new time 1472457354262 
08-29 03:55:54.263   550  5907 D QC-time-services: Daemon: delta 1463626674262 genoff 1463626674262 
08-29 03:55:54.263   550  5907 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1463626674262 to memory
08-29 03:55:54.263   550  5907 D QC-time-services: Daemon:Opening File: /data/time/ats_2
,08-29 03:55:54.263   550  5907 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-29 03:55:54.268   550  5907 D QC-time-services: Updating the TOD offset
,08-29 03:55:54.268   550  5907 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1463626674262 to memory
08-29 03:55:54.269   550  5907 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-29 03:55:54.269   550  5907 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-29 03:55:54.271   550  5907 E QC-time-services: Daemon:Update to modem bit set
08-29 03:55:54.271  5895  5895 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-29 03:55:54.271   550  5907 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-29 03:55:54.271   550  5907 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1147661874262
08-29 03:55:54.272   928  3582 I ActivityManager: Killing 5316:com.google.android.partnersetup/u0a18 (adj 15): empty #17
08-29 03:55:54.276   550   634 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-29 03:55:54.277   550   630 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-29 03:55:54.296  3647  5908 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-29 03:55:54.300  3647  3647 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-29 03:55:54.307  3647  3647 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 03:55:54.309  3647  3647 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 03:55:54.312  3915  3915 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-29 03:55:54.315  3915  5620 I CheckinTask: Sending checkin request (10845 bytes)
,08-29 03:55:54.325  5194  5194 D WearableService: callingUid 10012, callindPid: 5194
,08-29 03:55:54.331  3680  5910 E MDM     : [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-29 03:55:54.341  3915  5912 D LocationInitializer: Restart initialization of location
,08-29 03:55:54.349  3647  3647 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 03:55:54.358  5532  5532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 03:55:54.364  3647  3647 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 03:55:54.365  5532  5532 D DockEventReceiver: finishStartingService: stopping service
,08-29 03:55:54.368  3680  3935 W GCoreFlp: No location to return for getLastLocation()
08-29 03:55:54.368  3647  5913 W FusedLocationProvider: location=null
,08-29 03:55:54.371  3166  3166 D BluetoothPbap: Proxy object connected
,08-29 03:55:54.371  5532  5532 D BluetoothPbap: Proxy object connected
08-29 03:55:54.371  3166  3166 D PbapServerProfile: Bluetooth service connected
08-29 03:55:54.371  5532  5532 D PbapServerProfile: Bluetooth service connected
,08-29 03:55:54.376  5791  5917 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 03:55:54.388  5791  5922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 03:55:54.389  5791  5922 I BtOppRfcommListener: Accept thread started.
,08-29 03:55:54.565  3915  5620 I CheckinResponseProcessor: From server: 6 gservices updates and 1 deletes
,08-29 03:55:54.705  3647  4668 I GservicesProvider: main difference update completed
,08-29 03:55:54.722   928   941 I ActivityManager: Start proc 5929:com.google.android.configupdater/u0a5 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,08-29 03:55:54.724  3915  5620 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,08-29 03:55:54.745   928  3582 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-29 03:55:54.746  4228  4228 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-29 03:55:54.746  4228  4228 W Babel   : BAM#gBA: invalid account id: -1
08-29 03:55:54.746  4228  4228 W Babel   : BAM#gBA: invalid account id: -1
08-29 03:55:54.746  4228  4228 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
08-29 03:55:54.747  3915  5620 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,08-29 03:55:54.759  5929  5929 W System  : ClassLoader referenced unknown path: /system/priv-app/ConfigUpdater/lib/arm64
,08-29 03:55:54.776  5929  5929 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION intent_firewall: null null
,08-29 03:55:54.786  5929  5929 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION apn_db: null null
,08-29 03:55:54.789  5929  5929 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION tzdata: null null
,08-29 03:55:54.792  5929  5929 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION selinux: null null
,08-29 03:55:54.795  5929  5929 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION carrier_provisioning_urls: null null
,08-29 03:55:54.815  5492  5492 W InstanceID/Rpc: Found 10012
,08-29 03:55:54.831   928  3482 I ActivityManager: Start proc 5955:com.google.android.partnersetup/u0a18 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,08-29 03:55:54.859  3915  5620 I CheckinRequestBuilder: Classify the device as Phone.
,08-29 03:55:54.861  5955  5955 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm64
,08-29 03:55:54.884  3915  5620 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-29 03:55:54.899  3915  5620 I CheckinService: Checking schedule, now: 1472457354899 next: 1472498104884
,08-29 03:55:54.899  3915  5620 I CheckinService: active receiver: disabled
,08-29 03:55:54.910   928  3576 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,08-29 03:55:54.932  3915  3915 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,08-29 03:55:54.935  3915  5979 I CheckinService: Checking schedule, now: 1472457354935 next: 1472498104884
,08-29 03:55:54.935  3915  5979 I CheckinService: active receiver: disabled
,08-29 03:55:54.936  3915  3915 D SystemUpdateService: onCreate
,08-29 03:55:54.940  3915  3915 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 03:55:54.965  3647  4129 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,08-29 03:55:54.966  3915  3915 D OcrModelManager: Updating downloaded model state (gservices changed)
,08-29 03:55:54.971  3915  3915 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
,08-29 03:55:54.972  3915  3915 I OcrUtils: Updating ocr activity enabled=false
,08-29 03:55:54.976  3915  5980 I SystemUpdateService: active receiver: enabled
,08-29 03:55:54.992  3915  5980 I SystemUpdateService: showing system update notification
,08-29 03:55:54.994  3680  3680 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,08-29 03:55:55.004  3915  5980 V SystemUpdateService: retry (wakeup: false) in 3599967 ms
,08-29 03:55:55.005  3680  3680 I GCoreUlr: DispatchingService.onCreate()
,08-29 03:55:55.051  3680  5986 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,08-29 03:55:55.106   928  4661 I ActivityManager: Killing 5333:com.android.musicfx/u0a21 (adj 15): empty #17
,08-29 03:55:55.135  5862  5862 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
,08-29 03:55:55.135  5862  5862 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,08-29 03:55:55.139   928  4661 I ActivityManager: Killing 4674:com.google.android.googlequicksearchbox:search/u0a29 (adj 15): empty #17
,08-29 03:55:55.161   928  2997 D WifiService: Client connection lost with reason: 4
,08-29 03:55:55.170  3680  5986 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: (no Google accounts)
,08-29 03:55:55.177  3680  5986 I GCoreUlr: Unbound from all location providers
,08-29 03:55:55.184  3680  3680 I GCoreUlr: DispatchingService.onDestroy()
,08-29 03:55:55.184  3680  3680 I GCoreUlr: Stopping handler for UlrDispSvcFast
,08-29 03:55:55.188  3680  3680 I GCoreUlr: Unbound from all location providers
,08-29 03:55:55.241  3915  3915 D SystemUpdateService: onDestroy
,08-29 03:55:55.252  3915  4663 E Icing   : Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,08-29 03:55:55.290   928   938 I ActivityManager: Start proc 5991:com.google.android.googlequicksearchbox:search/u0a29 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver
,08-29 03:55:55.531   928  3199 I ActivityManager: Killing 5355:com.google.android.apps.docs/u0a43 (adj 15): empty #17
,08-29 03:55:55.651  3915  3915 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 03:55:55.654  5991  6021 I GservicesUpdateTask: Updating Gservices keys
,08-29 03:55:55.658  3915  3915 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 03:55:55.660  3647  4151 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-29 03:55:55.667  3647  4171 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-29 03:55:55.670  3915  3915 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 03:55:55.671  3915  3915 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 03:55:55.708  5415  5461 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 03:55:55.708  5415  5461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 03:55:58.711  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 03:55:58.711  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c3618a3 added. We now have 6 listener(s)
,08-29 03:55:58.712  5415  5461 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 03:55:58.717  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 03:55:58.718  5415  5461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f9c57a0 added. We now have 7 listener(s)
08-29 03:55:58.718  5415  5461 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 03:55:58.722  5415  5461 I System.out: IsBluetoothEnabled
,08-29 03:55:58.730  5791  5803 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 03:55:58.731  5791  5803 D BluetoothAdapterProperties: Setting state to 13
08-29 03:55:58.731  5791  5803 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 03:55:58.732  5791  5803 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 03:55:58.733  5791  5803 I BluetoothAdapterState: Entering PendingCommandState
,08-29 03:55:58.736  5791  5791 D BluetoothMapService: onReceive
08-29 03:55:58.737  5791  5791 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 03:55:58.737  5791  5791 D BluetoothMapService: STATE_TURNING_OFF
,08-29 03:55:58.737  5791  5791 D BluetoothMapService: MAP Service closeService in
08-29 03:55:58.737  5791  5791 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 03:55:58.737  5791  5791 D ObexServerSockets0: shutdown(block = true)
08-29 03:55:58.738  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:58.738  5791  5791 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 03:55:58.738  5415  5461 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:58.738  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:58.738  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:58.738  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 03:55:58.738  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 03:55:58.738  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 03:55:58.738  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 03:55:58.738  5415  5461 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 03:55:58.738  5791  5791 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 03:55:58.738  5791  5835 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 03:55:58.739  5791  5836 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 03:55:58.739  5791  5823 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 03:55:58.740  5415  5415 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 03:55:58.740  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 03:55:58.740  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 03:55:58.740  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 03:55:58.740  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 03:55:58.740  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 03:55:58.740  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 03:55:58.740  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 03:55:58.740  5415  5415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 03:55:58.741  5791  5807 D BluetoothAdapterProperties: Scan Mode:20
,08-29 03:55:58.741  5791  5803 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 03:55:58.742  5415  5461 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 03:55:58.742  5415  5461 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 03:55:58.742  5791  5791 I BtOppRfcommListener: stopping Accept Thread
08-29 03:55:58.743  5791  5922 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 03:55:58.744  5791  5922 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 03:55:58.744  5415  5415 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 03:55:58.744  5415  5415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 03:55:58.746  5791  5791 D HeadsetService: Received stop request...Stopping profile...
08-29 03:55:58.748  5532  5545 D BluetoothHeadset: Proxy object disconnected
08-29 03:55:58.749   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 03:55:58.749  3552  3769 D BluetoothHeadset: Proxy object disconnected
,08-29 03:55:58.750   928   928 D BluetoothHeadset: Proxy object disconnected
,08-29 03:55:58.750  3166  3178 D BluetoothHeadset: Proxy object disconnected
08-29 03:55:58.750  5791  5791 V BluetoothAdapterState: isTurningOff()=true
08-29 03:55:58.750  5791  5791 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:58.750  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:58.750   928   928 D BluetoothHeadset: Proxy object disconnected
,08-29 03:55:58.750  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:58.751  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 03:55:58.752  5532  5532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 03:55:58.752  5791  5791 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 03:55:58.752  5791  5791 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 03:55:58.753  5791  5807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-29 03:55:58.753  5791  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 03:55:58.753  5791  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 03:55:58.753  5791  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 03:55:58.753  5791  5807 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 03:55:58.753  5791  5791 D A2dpService: Received stop request...Stopping profile...
08-29 03:55:58.754  5791  5830 D A2dpStateMachine: Exit Disconnected: -1
08-29 03:55:58.754  5532  5532 D HeadsetProfile: Bluetooth service disconnected
08-29 03:55:58.756   928   928 D BluetoothA2dp: Proxy object disconnected
,08-29 03:55:58.757  5791  5791 D HidService: Received stop request...Stopping profile...
,08-29 03:55:58.757  5791  5791 D HidService: Stopping Bluetooth HidService
08-29 03:55:58.759  5791  5791 D HealthService: Received stop request...Stopping profile...
08-29 03:55:58.760  5791  5791 D PanService: Received stop request...Stopping profile...
08-29 03:55:58.760  3166  3166 D HeadsetProfile: Bluetooth service disconnected
08-29 03:55:58.760  3166  3166 D BluetoothA2dp: Proxy object disconnected
,08-29 03:55:58.761  3166  3166 D BluetoothInputDevice: Proxy object disconnected
08-29 03:55:58.761  3166  3166 D HidProfile: Bluetooth service disconnected
08-29 03:55:58.761  3166  3166 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 03:55:58.761  3166  3166 D PanProfile: Bluetooth service disconnected
,08-29 03:55:58.763  5791  5803 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,08-29 03:55:58.763  5791  5803 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
08-29 03:55:58.763  5791  5791 V BluetoothAdapterState: isTurningOff()=true
08-29 03:55:58.763  5532  5532 D DockEventReceiver: finishStartingService: stopping service
,08-29 03:55:58.764  5791  5791 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:58.764  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:58.764  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:58.764  5791  5791 D BluetoothMapService: Received stop request...Stopping profile...
08-29 03:55:58.764  5791  5791 D BluetoothMapService: stop()
08-29 03:55:58.764  5532  5532 D BluetoothA2dp: Proxy object disconnected
08-29 03:55:58.764  5532  5532 D BluetoothInputDevice: Proxy object disconnected
08-29 03:55:58.765  5532  5532 D HidProfile: Bluetooth service disconnected
,08-29 03:55:58.765  5532  5532 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 03:55:58.765  5532  5532 D PanProfile: Bluetooth service disconnected
08-29 03:55:58.765  5791  5791 D BluetoothMapAppObserver: deinitObservers()
08-29 03:55:58.765  5791  5791 D BluetoothMapAppObserver: removeReceiver()
08-29 03:55:58.766  3647  3647 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 03:55:58.769  3166  3166 D BluetoothMap: Proxy object disconnected
08-29 03:55:58.770  3166  3166 D MapProfile: Bluetooth service disconnected
08-29 03:55:58.770  5532  5532 D BluetoothMap: Proxy object disconnected
08-29 03:55:58.770  5532  5532 D MapProfile: Bluetooth service disconnected
08-29 03:55:58.770  5791  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 03:55:58.770  5791  5791 V BluetoothAdapterState: isTurningOff()=true
08-29 03:55:58.770  5791  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 03:55:58.770  5791  5791 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:58.770  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:58.770  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:58.770  5791  5807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 03:55:58.770  5791  5820 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 03:55:58.770  5791  5820 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 03:55:58.771  5791  5791 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 03:55:58.771  5791  5791 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 03:55:58.771  5791  5820 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 03:55:58.771  5791  5820 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 03:55:58.771  5791  5791 V BluetoothAdapterState: isTurningOff()=true
,08-29 03:55:58.771  5791  5791 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:58.771  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:58.771  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:58.771  5791  5807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 03:55:58.771  5791  5791 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 03:55:58.771  5791  5807 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-29 03:55:58.772  5791  5791 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 03:55:58.772  5791  5791 V BluetoothAdapterState: isTurningOff()=true
08-29 03:55:58.772  5791  5791 V BluetoothAdapterState: isTurningOn()=false
,08-29 03:55:58.772  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:58.772  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:58.773  5791  5791 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 03:55:58.773  5791  5791 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 03:55:58.774  5791  5791 D SapService: Received stop request...Stopping profile...
08-29 03:55:58.774  5791  5791 V SapService: stop()
08-29 03:55:58.777  5532  5532 D BluetoothPbap: Proxy object disconnected
08-29 03:55:58.777  5532  5532 D PbapServerProfile: Bluetooth service disconnected
08-29 03:55:58.777  5791  5791 D BluetoothMapService: MAP Service closeService in
08-29 03:55:58.777  3166  3166 D BluetoothPbap: Proxy object disconnected
,08-29 03:55:58.777  3166  3166 D PbapServerProfile: Bluetooth service disconnected
08-29 03:55:58.777  5791  5791 V BluetoothAdapterState: isTurningOff()=true
08-29 03:55:58.777  5791  5791 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:58.777  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:58.777  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:58.777  5791  5791 D BluetoothMapService: cleanup()
08-29 03:55:58.777  5791  5791 D BluetoothMapService: MAP Service closeService in
08-29 03:55:58.778  5791  5791 V BluetoothAdapterState: isTurningOff()=true
08-29 03:55:58.778  5791  5791 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:58.778  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 03:55:58.778  5791  5791 V BluetoothAdapterState: isBleTurningOff()=false
08-29 03:55:58.778  5791  5803 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 03:55:58.778  5791  5803 D BluetoothAdapterProperties: Setting state to 15
08-29 03:55:58.778  5791  5803 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 03:55:58.779  5791  5803 I BluetoothAdapterState: Entering BleOnState
08-29 03:55:58.779  5791  5803 D BluetoothAdapterState: Current state: BLE ON, message: 0
,08-29 03:55:58.780  5532  5542 D BluetoothMap: onBluetoothStateChange: up=false
08-29 03:55:58.781  3166  3182 D BluetoothPan: onBluetoothStateChange on: false
,08-29 03:55:58.781  5532  5545 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 03:55:58.782  5532  5748 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 03:55:58.782   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 03:55:58.782   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 03:55:58.783  5532  5542 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 03:55:58.783  3552  3567 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 03:55:58.783   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 03:55:58.783  3166  3178 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 03:55:58.784  5532  5545 D BluetoothPan: onBluetoothStateChange on: false
,08-29 03:55:58.785  3166  3751 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 03:55:58.785  5532  5748 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 03:55:58.785  3166  3182 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 03:55:58.786  3166  3178 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 03:55:58.786   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 03:55:58.787  3166  3751 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 03:55:58.787  5791  5803 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 03:55:58.787  5791  5803 D BluetoothAdapterProperties: Setting state to 16
08-29 03:55:58.787  5791  5803 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 03:55:58.788  5791  5803 D BluetoothAdapterProperties: onBleDisable
08-29 03:55:58.788  5791  5803 I BluetoothAdapterState: Entering PendingCommandState
08-29 03:55:58.788  5791  5804 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 03:55:58.789  5791  5807 D BluetoothAdapterProperties: Scan Mode:20
,08-29 03:55:58.791  5791  5820 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 03:55:58.791  5791  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 03:55:58.793  5532  5532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 03:55:58.794  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 03:55:58.796  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:58.797  3647  3647 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 03:55:58.799  5532  5532 D DockEventReceiver: finishStartingService: stopping service
,08-29 03:55:58.959  5846  5868 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-29 03:55:58.996  5791  5807 I bt_hci  : shut_down
,08-29 03:55:59.000  5791  5811 D bt_hwcfg: hw_epilog_process
,08-29 03:55:59.000  5791  5811 I bt_vendor: low_power_mode_cb
,08-29 03:55:59.002  5791  5811 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 03:55:59.002  5791  5811 I bt_vendor: epilog_cb
08-29 03:55:59.002  5791  5811 I bt_hci  : epilog_finished_callback
,08-29 03:55:59.004  5791  5807 I bt_hci_h4: hal_close
,08-29 03:55:59.005  5791  5807 I bt_userial_vendor: device fd = 51 close
,08-29 03:55:59.120  5791  5804 D bt_stack_manager: event_shut_down_stack finished.
,08-29 03:55:59.121  5791  5803 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 03:55:59.122  5791  5803 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 03:55:59.122  5791  5791 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 03:55:59.123  5791  5791 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 03:55:59.123  5791  5791 D BtGatt.GattService: stop()
08-29 03:55:59.123  5791  5791 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 03:55:59.125  5791  5791 V BluetoothAdapterState: isTurningOff()=false
,08-29 03:55:59.125  5791  5791 V BluetoothAdapterState: isTurningOn()=false
08-29 03:55:59.125  5791  5791 V BluetoothAdapterState: isBleTurningOn()=false
08-29 03:55:59.125  5791  5791 V BluetoothAdapterState: isBleTurningOff()=true
08-29 03:55:59.126  5791  5803 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 03:55:59.126  5791  5803 D BluetoothAdapterProperties: Setting state to 10
08-29 03:55:59.126  5791  5803 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 03:55:59.127  5791  5803 I BluetoothAdapterState: Entering OffState
,08-29 03:55:59.134  5415  5415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 03:55:59.134  5532  5532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 03:55:59.140  3647  3647 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 03:55:59.140  5532  5532 D DockEventReceiver: finishStartingService: stopping service
,08-29 03:55:59.339   928  3450 I ActivityManager: Killing 4561:com.android.vending/u0a22 (adj 15): empty #17
,08-29 03:55:59.444   928  2998 D ConnectivityService: handlePromptUnvalidated 100
,08-29 03:56:00.761   928  4661 I ActivityManager: Killing 5677:com.android.chrome/u0a39 (adj 15): empty #17
,08-29 03:56:00.788   928  4661 I ActivityManager: Killing 5659:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #18
,08-29 03:56:01.475   562   562 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 03:56:01.475   562   562 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 03:56:01.771   928  2988 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 03:56:01.800   928  3582 I ActivityManager: Start proc 6039:android.process.acore/u0a2 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-29 03:56:01.830  6039  6039 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
,08-29 03:56:01.832  3680  3680 V GmsNetworkLocationProvi: DISABLE
,08-29 03:56:01.838  3680  3680 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,08-29 03:56:01.897  6039  6039 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm64
,08-29 03:56:01.917   928  3483 I ActivityManager: Start proc 6057:com.android.vending/u0a22 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,08-29 03:56:01.951  6057  6057 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm64
,08-29 03:56:01.994  6057  6057 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 03:56:01.986  6039  6055 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,08-29 03:56:02.024  6057  6057 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-29 03:56:02.039  6057  6057 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 03:56:02.074  6057  6057 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 03:56:02.076  6057  6057 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 03:56:02.079  6057  6057 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 03:56:02.080  6057  6057 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 03:56:02.087  6057  6057 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 03:56:02.088  6057  6057 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 03:56:02.091  6057  6057 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-29 03:56:02.101  6057  6057 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 03:56:02.102  6057  6057 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 03:56:02.114  6057  6057 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 03:56:02.124  6057  6057 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 03:56:02.125  6057  6057 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-29 03:56:02.138  6057  6057 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 03:56:02.149  6057  6089 D Ads     : Skipping gmscore version check
,08-29 03:56:02.151  3915  6090 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-29 03:56:02.153  3915  6090 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-29 03:56:02.165  3915  4663 I Icing   : updateResources: need to parse f{com.google.android.gms}
,08-29 03:56:02.166  5991  6092 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-29 03:56:02.187  6057  6089 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186448
,08-29 03:56:02.209  6057  6057 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-29 03:56:02.221  6057  6057 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-29 03:56:02.266  5991  6092 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 99 ms] updated apps [took 99 ms] 
,08-29 03:56:02.278  6057  6057 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 03:56:02.279  6057  6057 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 03:56:06.849   928  3239 I ActivityManager: Killing 5621:com.google.android.youtube/u0a75 (adj 15): empty #17
,08-29 03:56:06.919   928  3576 I ActivityManager: Killing 5877:com.google.android.deskclock/u0a66 (adj 15): empty #17
,08-29 03:56:11.476   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:12.478   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:13.479   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:14.481   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:15.482   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:16.483   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 03:56:21.484   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:22.486   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:23.487   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:24.489   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:25.490   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:25.835   928  3482 I ActivityManager: Start proc 6096:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-29 03:56:25.871  6096  6096 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,08-29 03:56:25.977  6096  6108 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,08-29 03:56:26.055  6096  6108 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-29 03:56:26.113  6096  6108 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-29 03:56:26.136  6121  6121 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads568842657.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads568842657.dex
,08-29 03:56:26.150  6096  6096 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-29 03:56:26.171  6121  6121 I dex2oat : dex2oat took 35.812ms (threads: 2) arena alloc=200KB java alloc=37KB native alloc=1257KB free=1302KB
,08-29 03:56:26.319  6096  6096 W InstanceID/Rpc: Found 10012
,08-29 03:56:26.374   928  3582 I ActivityManager: Killing 5895:com.qualcomm.timeservice/1000 (adj 15): empty #17
,08-29 03:56:26.435  3647  6177 I VacuumService: Vacuum at: now=1472457386435 tag=VacuumService
,08-29 03:56:26.483  3647  6180 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,08-29 03:56:26.490   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 03:56:26.521  3647  6178 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-29 03:56:26.524  3647  6178 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 03:56:26.547  3647  6180 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 03:56:26.922  3647  6178 W Uploader:  no longer exists, so no auth token.
,08-29 03:56:26.931  3647  6182 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 03:56:27.009  3647  6180 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 03:56:27.167  3647  6182 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 03:56:27.243  3647  6178 W Uploader:  no longer exists, so no auth token.
,08-29 03:56:27.255  3647  6180 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 03:56:27.339  3647  6182 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 03:56:27.430  3647  6180 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 03:56:27.515  3647  6182 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 03:56:27.611  3647  6180 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 03:56:36.492   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:37.493   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:38.494   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:39.496   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:40.497   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:41.498   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 03:56:56.499   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:57.501   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:58.503   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:56:59.507   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:57:00.508   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:57:01.509   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 03:57:04.257   928  5598 D NetlinkSocketObserver: NeighborEvent{elapsedMs=282720, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 03:57:21.511   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:57:22.513   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:57:23.514   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:57:24.515   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:57:25.516   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:57:26.517   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 03:57:51.518   562   562 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 03:57:51.519   562   562 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 03:57:56.697   928  5598 D NetlinkSocketObserver: NeighborEvent{elapsedMs=335160, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 03:58:06.521   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:07.522   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:08.524   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:09.526   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:10.527   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:11.527   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 03:58:16.529   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:17.530   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:18.532   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:19.533   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:20.535   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:21.536   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 03:58:31.537   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:32.538   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:33.377   928  5598 D NetlinkSocketObserver: NeighborEvent{elapsedMs=371841, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 03:58:33.539   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:34.540   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:35.542   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:36.543   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 03:58:51.545   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:52.547   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:53.549   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:54.551   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:55.553   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:58:56.555   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 03:59:16.557   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:59:17.559   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:59:18.561   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:59:19.563   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:59:20.564   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 03:59:21.564   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 03:59:46.566   562   562 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 03:59:46.566   562   562 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 03:59:56.707   928  5598 D NetlinkSocketObserver: NeighborEvent{elapsedMs=455171, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 04:00:06.568   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:07.572   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:08.574   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:09.575   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:10.576   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:11.577   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 04:00:16.578   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:17.580   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:18.581   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:19.583   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:20.584   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:21.585   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 04:00:31.587   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:32.588   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:33.377   928  5598 D NetlinkSocketObserver: NeighborEvent{elapsedMs=491841, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 04:00:33.590   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:34.591   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:35.593   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:36.594   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 04:00:51.595   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:52.597   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:53.599   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:54.601   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:55.603   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:00:56.597   928  5598 D NetlinkSocketObserver: NeighborEvent{elapsedMs=515060, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 04:00:56.604   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 04:01:16.606   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:01:17.608   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:01:18.610   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:01:19.611   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:01:20.640   562   562 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:01:21.641   562   562 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 04:01:46.642   562   562 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 04:01:46.643   562   562 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 04:02:11.658   562  1296 E QC-QMI  : qmi_client [562] 9: failed to locate client data
,08-29 04:02:11.662   562   562 I Atfwd_Daemon: Stop the daemon....
08-29 04:02:11.662   519   519 E QC-QMI  : qmuxd: RX on fd=17 returned error=0 errno[2:No such file or directory]
08-29 04:02:11.663   519   519 E QC-QMI  : QMUX qmux_client_id=9 not found in qmux client list, unable to remove
,08-29 04:02:11.696  6199  6199 I libmdmdetect: ESOC framework not supported
,08-29 04:02:11.694  6199  6199 W ATFWD-daemon: type=1400 audit(0.0:73): avc: denied { read write } for name="diag" dev="tmpfs" ino=12646 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
08-29 04:02:11.697  6199  6199 I libmdmdetect: Found internal modem: modem
,08-29 04:02:11.698  6199  6199 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 04:02:11.703  6199  6199 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,08-29 04:02:11.703  6199  6199 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
08-29 04:02:11.704  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:12.706  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:13.708  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:14.710  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:15.712  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:16.714  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 04:02:21.715  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:22.717  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:23.718  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:24.719  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:25.538   928  5598 D NetlinkSocketObserver: NeighborEvent{elapsedMs=604001, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 04:02:25.721  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:26.722  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 04:02:36.723  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:37.725  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:38.726  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:39.728  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:40.729  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:41.730  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 04:02:56.733  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:57.734  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:58.737  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:02:59.739  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:03:00.741  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:03:01.741  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 04:03:21.744  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:03:22.746  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:03:23.748  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:03:24.749  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:03:25.750  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:03:26.656   928  3199 I ActivityManager: Start proc 6208:com.google.android.deskclock/u0a66 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,08-29 04:03:26.694  6208  6208 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,08-29 04:03:26.714  6208  6208 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-29 04:03:26.714  6208  6208 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 04:03:26.714  6208  6208 I GAv4    :   adb logcat -s GAv4
,08-29 04:03:26.731  6208  6208 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 04:03:26.737  6208  6208 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 04:03:26.750  6208  6223 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-29 04:03:26.751  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 04:03:26.766   928   938 I ActivityManager: Killing 5929:com.google.android.configupdater/u0a5 (adj 15): empty #17
,08-29 04:03:51.752  6199  6199 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 04:03:51.752  6199  6199 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 04:03:56.753  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:03:57.754  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:03:58.756  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:03:59.757  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:00.759  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:01.760  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 04:04:06.761  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:07.763  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:08.764  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:09.766  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:10.767  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:11.768  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 04:04:21.770  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:22.771  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:23.773  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:24.774  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:25.776  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:26.777  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 04:04:41.779  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:42.781  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:43.783  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:44.785  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:45.787  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:04:46.788  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 04:05:06.790  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:05:07.792  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:05:08.794  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:05:09.795  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:05:10.797  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:05:11.797  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 04:05:36.799  6199  6199 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 04:05:36.799  6199  6199 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 04:05:46.800  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:05:47.802  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:05:48.803  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:05:49.805  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:05:50.806  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:05:51.807  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 04:05:56.809  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:05:57.810  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:05:58.812  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:05:59.813  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:00.815  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:01.816  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 04:06:11.817  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:12.819  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:13.820  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:14.822  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:15.823  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:16.824  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 04:06:31.827  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:32.829  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:33.831  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:34.833  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:35.834  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:36.835  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 04:06:56.837  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:57.839  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:58.840  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:06:59.841  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:07:00.842  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:07:01.842  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 04:07:26.844  6199  6199 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 04:07:26.844  6199  6199 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 04:07:41.847  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:07:42.849  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:07:43.851  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:07:44.852  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:07:45.853  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:07:46.854  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 04:07:51.855  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:07:52.857  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:07:53.859  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:07:54.860  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:07:55.862  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:07:56.863  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 04:08:06.864  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:07.866  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:08.867  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:09.869  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:10.870  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:11.871  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 04:08:26.873  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:27.876  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:28.878  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:29.880  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:30.882  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:31.882  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 04:08:51.884  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:52.887  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:53.889  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:54.890  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:55.891  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:08:56.891  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 04:09:21.893  6199  6199 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 04:09:21.893  6199  6199 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 04:09:41.895  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:09:42.897  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:09:43.899  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:09:44.901  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:09:45.903  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:09:46.904  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 04:09:51.906  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:09:52.907  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:09:53.909  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:09:54.910  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:09:55.912  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:09:56.913  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 04:10:06.915  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:07.917  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:08.919  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:09.920  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:10.922  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:11.922  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 04:10:26.924  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:27.925  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:28.928  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:29.930  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:30.932  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:31.935  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 04:10:51.937  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:52.940  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:53.941  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:54.943  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:55.944  6199  6199 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:10:56.945  6199  6199 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 04:11:21.946  6199  6199 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 04:11:21.947  6199  6199 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 04:11:31.777   928  5598 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1150240, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 04:11:38.477   928  5598 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1156940, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 04:11:46.959  6199  6201 E QC-QMI  : qmi_client [6199] 16: failed to locate client data
,08-29 04:11:46.962   519   519 E QC-QMI  : qmuxd: RX on fd=17 returned error=0 errno[2:No such file or directory]
08-29 04:11:46.963   519   519 E QC-QMI  : QMUX qmux_client_id=16 not found in qmux client list, unable to remove
,08-29 04:11:46.965  6199  6199 I Atfwd_Daemon: Stop the daemon....
,08-29 04:11:47.014  6240  6240 I libmdmdetect: ESOC framework not supported
,08-29 04:11:47.015  6240  6240 I libmdmdetect: Found internal modem: modem
08-29 04:11:47.016  6240  6240 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-29 04:11:47.014  6240  6240 W ATFWD-daemon: type=1400 audit(0.0:74): avc: denied { read write } for name="diag" dev="tmpfs" ino=12646 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,08-29 04:11:47.026  6240  6240 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,08-29 04:11:47.026  6240  6240 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
08-29 04:11:47.027  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:11:48.029  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:11:49.030  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:11:50.032  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:11:51.033  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:11:52.034  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 04:11:57.035  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:11:58.037  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:11:59.038  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:00.040  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:01.041  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:02.042  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 04:12:12.044  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:13.045  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:14.047  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:15.048  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:16.049  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:17.049  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 04:12:32.051  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:33.053  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:34.056  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:35.058  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:36.060  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:37.062  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 04:12:41.489   928   940 I UsageStatsService: User[0] Flushing usage stats to disk
,08-29 04:12:57.064  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:58.066  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:12:59.068  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:00.070  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:01.072  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:02.072  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 04:13:27.074  6240  6240 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 04:13:27.074  6240  6240 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 04:13:32.075  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:33.077  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:34.078  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:35.079  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:36.081  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:37.082  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 04:13:42.084  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:43.085  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:44.087  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:45.088  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:46.090  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:47.091  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 04:13:57.093  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:58.095  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:13:59.097  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:14:00.098  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:14:01.099  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:14:02.100  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 04:14:17.102  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:14:18.104  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:14:19.106  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:14:20.108  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:14:21.110  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:14:22.112  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 04:14:42.114  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:14:43.117  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:14:44.119  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:14:45.121  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:14:46.122  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:14:47.123  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 04:15:12.124  6240  6240 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 04:15:12.125  6240  6240 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 04:15:22.127  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:23.129  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:24.130  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:25.131  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:26.133  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:27.134  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 04:15:32.135  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:33.137  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:34.138  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:35.140  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:36.141  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:37.142  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 04:15:47.144  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:48.147  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:49.149  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:50.150  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:51.151  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:15:52.151  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 04:16:07.153  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:16:08.155  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:16:09.157  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:16:10.159  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:16:11.161  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:16:12.163  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 04:16:32.165  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:16:33.167  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:16:34.169  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:16:35.171  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:16:36.172  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:16:37.173  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 04:17:02.174  6240  6240 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 04:17:02.175  6240  6240 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 04:17:17.176  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:18.178  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:19.179  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:20.181  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:21.182  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:22.183  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 04:17:27.185  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:28.186  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:29.188  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:30.189  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:31.191  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:32.192  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 04:17:42.193  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:43.195  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:44.196  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:45.198  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:46.199  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:17:47.200  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 04:18:02.202  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:18:03.204  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:18:04.207  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:18:05.209  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:18:06.211  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:18:07.212  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 04:18:27.214  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:18:28.217  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:18:29.219  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:18:30.220  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:18:31.221  6240  6240 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 04:18:32.221  6240  6240 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 04:18:57.223  6240  6240 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 04:18:57.223  6240  6240 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,TIME-OUT KILL (timeout was 1400000ms),08-29 04:19:02.854  6251  6251 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 04:19:02.861  6251  6251 D AndroidRuntime: CheckJNI is OFF
08-29 04:19:02.890  6251  6251 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 04:19:02.924  6251  6251 I Radio-JNI: register_android_hardware_Radio DONE
08-29 04:19:02.943  6251  6251 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-29 04:19:02.952   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
08-29 04:19:02.953   928   941 I ActivityManager: Killing 5415:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
08-29 04:19:03.058   928  5889 I WindowState: WIN DEATH: Window{8d20455 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 04:19:03.058   928  4661 D GraphicsStats: Buffer count: 2
08-29 04:19:03.059   928  2997 D WifiService: Client connection lost with reason: 4
08-29 04:19:03.074   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-29 04:19:03.074   928   951 I art     : Starting a blocking GC Explicit
08-29 04:19:03.075   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-29 04:19:03.078   928   941 E ActivityManager: Failure starting process com.test.thalitest
08-29 04:19:03.078   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 04:19:03.078   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 04:19:03.078   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 04:19:03.078   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 04:19:03.078   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 04:19:03.079   928   941 I ActivityManager:   Force finishing activity ActivityRecord{51b65d6 u0 com.test.thalitest/.MainActivity t9}
08-29 04:19:03.088   928  3483 W ActivityManager: Spurious death for ProcessRecord{87a246a 0:com.test.thalitest/u0a77}, curProc for 5415: null
08-29 04:19:03.147   928   951 I art     : Explicit concurrent mark sweep GC freed 27528(1899KB) AllocSpace objects, 27(588KB) LOS objects, 33% free, 28MB/43MB, paused 1.339ms total 72.767ms
08-29 04:19:03.165   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-29 04:19:03.168  6251  6251 I art     : System.exit called, status: 0
08-29 04:19:03.168  6251  6251 I AndroidRuntime: VM exiting with result code 0.
08-29 04:19:03.186   928   951 I ActivityManager: Start proc 6261:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-29 04:19:03.186   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
08-29 04:19:03.192   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-29 04:19:03.197  3453  3453 I Keyboard.Facilitator: resetDictionaries() : en_US
08-29 04:19:03.202  3453  6272 I Keyboard.Facilitator.DecoderInitializer: run()
08-29 04:19:03.204  3680  3955 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 04:19:03.204  3453  6272 I Decoder : createOrResetDecoder
08-29 04:19:03.207   928  2988 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 04:19:03.222  3552  3552 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-29 04:19:03.258  6039  6276 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-29 04:19:03.273   928  3576 I ActivityManager: Start proc 6278:com.android.musicfx/u0a21 for broadcast com.android.musicfx/.Compatibility$Receiver
08-29 04:19:03.279  3647  3647 I ConfigService: onCreate
08-29 04:19:03.274    28    28 W kworker/2:1: type=1400 audit(0.0:75): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
08-29 04:19:03.284    28    28 W kworker/2:1: type=1400 audit(0.0:76): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
08-29 04:19:03.288   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 04:19:03.304  3453  6272 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-29 04:19:03.304    28    28 W kworker/2:1: type=1400 audit(0.0:77): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
08-29 04:19:03.328  6039  6276 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
08-29 04:19:03.329  6039  6276 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 04:19:03.329  6039  6276 E AndroidRuntime: Process: android.process.acore, PID: 6039
08-29 04:19:03.329  6039  6276 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 04:19:03.329  6039  6276 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 04:19:03.338   928  3483 I ActivityManager: Start proc 6291:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-29 04:19:03.339  3575  3715 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 04:19:03.339  3575  3715 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3575
08-29 04:19:03.339  3575  3715 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-29 04:19:03.339  3575  3715 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 04:19:03.339  3575  3715 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 04:19:03.339  3575  3715 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 04:19:03.339  3575  3715 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 04:19:03.339  3575  3715 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 04:19:03.339  3575  3715 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 04:19:03.339  3575  3715 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 04:19:03.339  3575  3715 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 04:19:03.339  3575  3715 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 04:19:03.339  3575  3715 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 04:19:03.339  3575  3715 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 04:19:03.341   928   939 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 04:19:03.343   928  6300 E DropBoxManagerService: Can't write: system_app_crash
08-29 04:19:03.343   928  6300 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-29 04:19:03.343   928  6300 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 04:19:03.343   928  6300 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 04:19:03.343   928  6300 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 04:19:03.343   928  6300 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 04:19:03.343   928  6300 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 04:19:03.343   928  6300 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 04:19:03.343   928  6300 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 04:19:03.343   928  6300 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 04:19:03.343   928  6300 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 04:19:03.343   928  6300 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 04:19:03.343   928  6300 E DropBoxManagerService: 	... 5 more
08-29 04:19:03.343   928  6299 E DropBoxManagerService: Can't write: system_app_crash
08-29 04:19:03.343   928  6299 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-29 04:19:03.343   928  6299 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 04:19:03.343   928  6299 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 04:19:03.343   928  6299 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 04:19:03.343   928  6299 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 04:19:03.343   928  6299 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 04:19:03.343   928  6299 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 04:19:03.343   928  6299 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 04:19:03.343   928  6299 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 04:19:03.343   928  6299 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 04:19:03.343   928  6299 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 04:19:03.343   928  6299 E DropBoxManagerService: 	... 5 more
08-29 04:19:03.346  3575  3715 I Process : Sending signal. PID: 3575 SIG: 9
08-29 04:19:03.348  6039  6276 I Process : Sending signal. PID: 6039 SIG: 9
08-29 04:19:03.358  6278  6278 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm64
08-29 04:19:03.375  3453  6272 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-29 04:19:03.376  3647  3647 D GCM-PT  : Populating db of packages that use GCM
08-29 04:19:03.377  3453  6272 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-29 04:19:03.378  3453  6272 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-29 04:19:03.380  3453  6272 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-29 04:19:03.380  3453  6272 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-29 04:19:03.380  3453  6272 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict

```
