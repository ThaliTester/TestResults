#### Test 82728424c383411_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-26 04:53:45.340   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 04:53:45.971  5403  5403 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 04:53:45.979  5403  5403 D AndroidRuntime: CheckJNI is OFF
08-26 04:53:46.008  5403  5403 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 04:53:46.043  5403  5403 I Radio-JNI: register_android_hardware_Radio DONE
08-26 04:53:46.060  5403  5403 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 04:53:46.064   931  3500 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 04:53:46.113   931  3500 I ActivityManager: Start proc 5412:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-26 04:53:46.119  5403  5403 D AndroidRuntime: Shutting down VM
08-26 04:53:46.209  5412  5412 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-26 04:53:46.241  5412  5412 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 04:53:46.265  5412  5412 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 6562-6581)
08-26 04:53:46.265  5412  5412 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 04:53:46.283  5412  5412 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {39f27de}
08-26 04:53:46.283  5412  5412 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 04:53:46.284  5412  5412 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 04:53:46.289  5412  5412 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 04:53:46.290  5412  5412 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 04:53:46.315  5412  5427 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-26 04:53:46.323  5412  5412 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-26 04:53:46.336  5412  5412 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 04:53:46.336  5412  5412 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 04:53:46.336  5412  5412 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-26 04:53:46.336  5412  5412 I Adreno  : Build Date                       : 10/21/15
08-26 04:53:46.336  5412  5412 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 04:53:46.336  5412  5412 I Adreno  : Local Branch                     : 
08-26 04:53:46.336  5412  5412 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-26 04:53:46.336  5412  5412 I Adreno  : Remote Branch                    : NONE
08-26 04:53:46.336  5412  5412 I Adreno  : Reconstruct Branch               : NOTHING
,08-26 04:53:46.340   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 04:53:46.384   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@45032ec:true
,08-26 04:53:46.426  5412  5412 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 04:53:46.434  5412  5412 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-26 04:53:46.459  5412  5449 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 04:53:46.467  5412  5436 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-26 04:53:46.501  5412  5449 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 04:53:46.588   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +431ms (total +502ms)
,08-26 04:53:46.611  5412  5412 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5412
,08-26 04:53:46.694  5412  5412 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 04:53:46.801  5412  5452 D jxcore_app_log: JniHelper::setJavaVM(0xf547c000), pthread_self() = -576714448
,08-26 04:53:46.804  5412  5452 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 04:53:46.804  5412  5452 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 04:53:46.804  5412  5452 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 04:53:46.804  5412  5452 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 04:53:46.804  5412  5452 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 04:53:46.805  5412  5452 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46fc1e4 added. We now have 1 listener(s)
,08-26 04:53:46.807  5412  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,08-26 04:53:46.807  5412  5452 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-26 04:53:46.807  5412  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 04:53:46.808  5412  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 04:53:46.809  5412  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bfae13 added. We now have 1 listener(s)
08-26 04:53:46.810  5412  5452 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 04:53:46.812   931  3071 D WifiService: New client listening to asynchronous messages
,08-26 04:53:46.812  5412  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 04:53:46.812  5412  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 04:53:46.812  5412  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 04:53:46.813  5412  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 04:53:46.813  5412  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 04:53:46.814  5412  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 04:53:46.814  5412  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-26 04:53:46.815  5412  5452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 04:53:46.815  5412  5452 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 04:53:46.815  5412  5452 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:53:46.815  5412  5452 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-26 04:53:46.815  5412  5452 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 04:53:46.815  5412  5452 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 04:53:46.815  5412  5452 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:53:46.815  5412  5452 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:53:46.815  5412  5452 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 04:53:46.815  5412  5452 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 04:53:46.815  5412  5452 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 04:53:46.816  5412  5452 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 04:53:46.829  5412  5412 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 04:53:47.064  5412  5458 W jxcore-log: Initializing JXcore engine
08-26 04:53:47.064  5412  5458 W jxcore-log: JXcore engine is ready
,08-26 04:53:47.080  5458  5458 W Thread-49: type=1400 audit(0.0:66): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=13604 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-26 04:53:47.080  5458  5458 W Thread-49: type=1400 audit(0.0:67): avc: denied { ioctl } for path="socket:[14781]" dev="sockfs" ino=14781 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-26 04:53:47.080  5458  5458 W Thread-49: type=1400 audit(0.0:68): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5905 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-26 04:53:47.080  5458  5458 W Thread-49: type=1400 audit(0.0:69): avc: denied { ioctl } for path="socket:[31936]" dev="sockfs" ino=31936 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-26 04:53:47.097  5412  5458 W jxcore-log: Starting JXcore engine
,08-26 04:53:47.146  5412  5458 W jxcore-log: Platform android
08-26 04:53:47.146  5412  5458 W jxcore-log: 
,08-26 04:53:47.146  5412  5458 W jxcore-log: Process ARCH arm
08-26 04:53:47.146  5412  5458 W jxcore-log: 
,08-26 04:53:47.238  5412  5458 I jxcore-log: JXcore Cordova bridge is ready!
08-26 04:53:47.238  5412  5458 I jxcore-log: 
08-26 04:53:47.238  5412  5458 W jxcore-log: JXcore engine is started
,08-26 04:53:47.242  5412  5452 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 04:53:47.245  5412  5412 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 04:53:47.341   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 04:53:48.342   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 04:53:49.343   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-26 04:53:53.782  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 04:53:53.782  5412  5458 I jxcore-log: 
,08-26 04:53:53.784  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 04:53:53.784  5412  5458 I jxcore-log: 
,08-26 04:53:53.785  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:53.785  5412  5458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 04:53:53.785  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:53:53.785  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-26 04:53:53.785  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 04:53:53.785  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 04:53:53.785  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:53:53.785  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:53:53.785  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 04:53:53.786  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:53.786  5412  5458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 04:53:53.787  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 04:53:53.787  5412  5458 I jxcore-log: 
,08-26 04:53:53.788  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 04:53:53.788  5412  5458 I jxcore-log: 
,08-26 04:53:54.140  5412  5458 D executeNativeTests: Running unit tests
,08-26 04:53:54.178  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 04:53:54.178  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 added. We now have 2 listener(s)
,08-26 04:53:54.179  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-26 04:53:54.179  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 04:53:54.179  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 04:53:54.179  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 04:53:54.179  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 added. We now have 2 listener(s)
08-26 04:53:54.180  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 04:53:54.180  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 04:53:54.181  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 04:53:54.182  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:54.182  5412  5458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 04:53:54.182  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:53:54.182  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-26 04:53:54.182  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 04:53:54.182  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 04:53:54.182  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:53:54.182  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:53:54.182  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 04:53:54.182  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 04:53:54.182  5412  5458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 04:53:54.182  5412  5458 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 04:53:54.184  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 04:53:54.184  5412  5458 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 04:53:54.184  5412  5458 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 04:53:54.185  5412  5458 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 04:53:54.185  5412  5458 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 04:53:54.185  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 04:53:54.185  5412  5458 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 04:53:54.185  5412  5458 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 04:53:54.186  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.186  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.186  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.186  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 04:53:54.186  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.186  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 04:53:54.186  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 04:53:54.186  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 removed from the list
08-26 04:53:54.186  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 04:53:54.186  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 removed from the list
08-26 04:53:54.186  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.186  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.187  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.187  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 04:53:54.187  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.187  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.187  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.187  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.188  5412  5458 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 04:53:54.189  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 04:53:54.189  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.189  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.189  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.189  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.189  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.189  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
,08-26 04:53:54.189  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.189  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.189  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.189  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.189  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 04:53:54.189  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.189  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.189  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.189  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 04:53:54.189  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.190  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 04:53:54.192  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 04:53:54.193  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.193  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.193  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.193  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.193  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 04:53:54.193  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.193  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.193  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.193  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.193  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.193  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.193  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 04:53:54.194  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.194  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.194  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.194  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.194  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.194  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.194  5412  5458 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 04:53:54.196  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 04:53:54.196  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:54.196  5412  5458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 04:53:54.196  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:53:54.196  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-26 04:53:54.196  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 04:53:54.196  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 04:53:54.196  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:53:54.196  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:53:54.196  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 04:53:54.196  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:54.196  5412  5458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 04:53:54.196  5412  5458 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 04:53:54.196  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 04:53:54.196  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 04:53:54.197  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 04:53:54.197  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 04:53:54.197  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 04:53:54.198  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-26 04:53:54.199  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-26 04:53:54.199  5412  5458 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-26 04:53:54.199  5412  5458 I io.jxcore.node.ConnectionHelper: start: OK
08-26 04:53:54.199  5412  5412 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-26 04:53:54.200  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:54.200  5412  5458 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-26 04:53:54.201  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.201  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.201  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 04:53:54.201  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.201  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 04:53:54.201  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 04:53:54.201  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 04:53:54.201  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 04:53:54.201  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 04:53:54.202  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 04:53:54.202  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 04:53:54.202  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 04:53:54.203  5412  5412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 04:53:54.203  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.203  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.203  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 04:53:54.203  5412  5412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 04:53:54.203  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.203  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.203  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.203  5412  5412 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 04:53:54.203  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.203  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 04:53:54.203  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.203  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.204  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.204  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.204  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.204  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.204  5412  5458 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 04:53:54.205  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 04:53:54.205  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 04:53:54.205  5412  5458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 04:53:54.205  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:53:54.205  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-26 04:53:54.205  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 04:53:54.205  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 04:53:54.205  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:53:54.205  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:53:54.205  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 04:53:54.205  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:54.205  5412  5458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 04:53:54.206  5412  5458 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 04:53:54.206  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 04:53:54.206  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 04:53:54.206  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 04:53:54.206  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 04:53:54.206  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 04:53:54.206  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-26 04:53:54.207  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-26 04:53:54.207  5412  5458 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 04:53:54.207  5412  5458 I io.jxcore.node.ConnectionHelper: start: OK
08-26 04:53:54.207  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.207  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.207  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 04:53:54.207  5412  5412 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-26 04:53:54.207  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.207  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 04:53:54.207  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 04:53:54.207  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 04:53:54.207  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 04:53:54.207  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 04:53:54.207  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 04:53:54.207  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 04:53:54.207  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 04:53:54.208  5412  5412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 04:53:54.208  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.208  5412  5458 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 04:53:54.208  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.208  5412  5412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 04:53:54.208  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.208  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.208  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.208  5412  5412 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 04:53:54.208  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 04:53:54.208  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.208  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.208  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.208  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.208  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.208  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.208  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.208  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.208  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.208  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.208  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.209  5412  5458 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 04:53:54.209  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.209  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.209  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.209  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.209  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.209  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.209  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.209  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.209  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.209  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.209  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.209  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.209  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.209  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.210  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.210  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.210  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.210  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.210  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 04:53:54.210  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.210  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.210  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.210  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.210  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.210  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.210  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.210  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.210  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.211  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.211  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.211  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.211  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.211  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.211  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.211  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.211  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.211  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.211  5412  5458 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 04:53:54.211  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.211  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.211  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.211  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.211  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.211  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.211  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.211  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.211  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.212  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.212  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.212  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.212  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.212  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.212  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.212  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.212  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.212  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.212  5412  5458 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 04:53:54.212  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.212  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.212  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.212  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.212  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.212  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.212  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.212  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.212  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.213  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.213  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.213  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.213  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.213  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.213  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.213  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.213  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.213  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.213  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 04:53:54.213  5412  5458 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 04:53:54.213  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 04:53:54.213  5412  5458 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 04:53:54.213  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 04:53:54.213  5412  5458 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 04:53:54.213  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.214  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.214  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.214  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.214  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.214  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.214  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.214  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.214  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.214  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.214  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.214  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.214  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.214  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.214  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.214  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.214  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.214  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.214  5412  5458 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 04:53:54.214  5412  5458 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 04:53:54.215  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 04:53:54.216  5412  5458 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 04:53:54.216  5412  5458 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910,:1910:1910]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 04:53:54.216  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 04:53:54.217  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 04:53:54.217  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 04:53:54.217  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 04:53:54.217  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 04:53:54.217  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 04:53:54.217  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 04:53:54.217  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 04:53:54.217  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 04:53:54.217  5412  5458 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 04:53:54.217  5412  5458 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 04:53:54.217  5412  5458 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 04:53:54.217  5412  5458 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 04:53:54.217  5412  5458 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 04:53:54.217  5412  5458 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 04:53:54.217  5412  5458 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 04:53:54.217  5412  5458 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 04:53:54.217  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 04:53:54.218  5412  5458 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-26 04:53:54.218  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 04:53:54.219  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 04:53:54.219  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 04:53:54.219  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 04:53:54.219  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 04:53:54.219  5412  5458 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 04:53:54.219  5412  5458 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 04:53:54.219  5412  5458 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 04:53:54.219  5412  5459 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 113)
08-26 04:53:54.219  5412  5459 E BluetoothDevice: Bluetooth is not enabled
08-26 04:53:54.219  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.220  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.220  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.220  5412  5459 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 113)
08-26 04:53:54.220  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.220  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.220  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.220  5412  5459 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 113)
08-26 04:53:54.220  5412  5459 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 113)
08-26 04:53:54.220  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 04:53:54.220  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.220  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.220  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.220  5412  5412 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
08-26 04:53:54.220  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.220  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.220  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.220  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.220  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.221  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.221  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.221  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.221  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.221  5412  5412 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
08-26 04:53:54.221  5412  5459 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 113
08-26 04:53:54.221  5412  5460 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 113
08-26 04:53:54.221  5412  5458 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 04:53:54.221  5412  5459 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 113)
08-26 04:53:54.221  5412  5412 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 04:53:54.221  5412  5412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 04:53:54.222  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.222  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.222  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.222  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.222  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.222  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.222  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.222  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.222  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.222  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.222  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.222  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.222  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.222  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.222  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.222  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.222  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.222  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.223  5412  5458 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 04:53:54.223  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.223  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.223  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.223  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.223  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.223  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.223  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.223  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.223  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.223  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.223  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.223  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.223  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.223  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.223  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.223  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.223  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.223  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.224  5412  5458 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 04:53:54.224  5412  5458 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 04:53:54.224  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 04:53:54.224  5412  5458 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 04:53:54.224  5412  5458 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 04:53:54.224  5412  5458 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 04:53:54.224  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 04:53:54.224  5412  5458 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 04:53:54.224  5412  5458 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 04:53:54.224  5412  5458 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 04:53:54.224  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 04:53:54.224  5412  5458 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 04:53:54.224  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.224  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.224  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.224  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.224  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.224  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.224  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.224  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.224  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.224  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.224  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.225  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.225  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.225  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.225  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.225  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.225  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.225  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.225  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.225  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.225  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.225  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.225  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.225  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.225  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.225  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.225  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.225  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.225  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.225  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.225  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.226  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.226  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.226  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.226  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.226  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.226  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.226  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.226  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.226  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.226  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.226  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.226  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.226  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.226  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.226  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.226  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.226  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.226  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.226  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.226  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.227  5412  5458 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 04:53:54.227  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 04:53:54.227  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-26 04:53:54.227  5412  5458 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-26 04:53:54.227  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 04:53:54.227  5412  5412 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-26 04:53:54.227  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.227  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 04:53:54.227  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.227  5412  5458 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-26 04:53:54.228  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.228  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.228  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 04:53:54.228  5412  5412 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 04:53:54.228  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 04:53:54.228  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 04:53:54.228  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.228  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.228  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 04:53:54.228  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
,08-26 04:53:54.228  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.228  5412  5412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 04:53:54.228  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.228  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.228  5412  5412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 04:53:54.228  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.228  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.228  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.228  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.228  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.228  5412  5412 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 04:53:54.228  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.228  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.228  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.229  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.229  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.229  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.229  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.229  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.229  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.229  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.229  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 04:53:54.229  5412  5458 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 04:53:54.229  5412  5458 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 04:53:54.229  5412  5458 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 04:53:54.229  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 04:53:54.229  5412  5458 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 04:53:54.229  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.229  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.230  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.230  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.230  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.230  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.230  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.230  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.230  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.230  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.230  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.230  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.230  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.230  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.230  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.230  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.230  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.230  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.231  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.231  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.231  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.231  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.231  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.231  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.231  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.231  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.231  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.231  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.231  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.231  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.231  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.231  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.232  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.232  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.232  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.232  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.232  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:53:54.232  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:53:54.232  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:53:54.232  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:53:54.232  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.232  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.232  5412  5458 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fb4c6 not in the list
08-26 04:53:54.232  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.232  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.232  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:53:54.232  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.232  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.233  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:53:54.233  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:53:54.233  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:53:54.233  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:53:54.233  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:53:54.233  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f87c87 not in the list
08-26 04:53:54.233  5412  5458 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 04:53:54.233  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 04:53:54.233  5412  5458 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 04:53:54.233  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 04:53:54.233  5412  5458 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 04:53:54.233  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 04:53:54.234  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 04:53:54.234  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 04:53:54.235  5412  5458 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 04:53:54.235  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 04:53:54.235  5412  5458 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 04:53:54.235  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 04:53:54.235  5412  5458 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 04:53:54.235  5412  5458 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 04:53:54.235  5412  5458 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 04:53:54.235  5412  5458 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 04:53:54.236  5412  5458 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 04:53:54.236  5412  5458 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 04:53:54.236  5412  5458 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 04:53:54.236  5412  5458 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 04:53:54.236  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 04:53:54.236  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7261cd9 added. We now have 2 listener(s)
08-26 04:53:54.236  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 04:53:54.237   931  3635 D WifiService: setWifiEnabled: true pid=5412, uid=10077
08-26 04:53:54.237   931  3635 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 04:53:54.240  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 04:53:54.240  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@da969e added. We now have 3 listener(s)
08-26 04:53:54.240  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 04:53:54.240  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:54.240  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:54.240  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 04:53:54.240  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32a757f added. We now have 4 listener(s)
08-26 04:53:54.240  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 04:53:54.241  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 04:53:54.241  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@81ae94c added. We now have 5 listener(s)
08-26 04:53:54.241  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 04:53:54.241   931  3526 D WifiService: setWifiEnabled: true pid=5412, uid=10077
08-26 04:53:54.241   931  3526 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 04:53:54.241   506   925 D SoftapController: Softap fwReload - Ok
08-26 04:53:54.245   506   925 D CommandListener: Setting iface cfg
08-26 04:53:54.245   506   925 D CommandListener: Trying to bring down wlan0
08-26 04:53:54.247   506   925 D CommandListener: Clearing all IP addresses on wlan0
08-26 04:53:54.249   931  3070 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-26 04:53:54.255   931   948 I ActivityManager: Start proc 5462:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
08-26 04:53:54.256  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 04:53:54.256  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:54.256  5412  5458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 04:53:54.256  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:53:54.256  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-26 04:53:54.256  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 04:53:54.256  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 04:53:54.256  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:53:54.256  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:53:54.256  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 04:53:54.257  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:54.257  5412  5458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 04:53:54.257  5412  5458 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 04:53:54.319  5462  5462 D AdapterServiceConfig: Adding HeadsetService
08-26 04:53:54.319  5462  5462 D AdapterServiceConfig: Adding A2dpService
08-26 04:53:54.319  5462  5462 D AdapterServiceConfig: Adding HidService
08-26 04:53:54.319  5462  5462 D AdapterServiceConfig: Adding HealthService
08-26 04:53:54.320  5462  5462 D AdapterServiceConfig: Adding PanService
08-26 04:53:54.320  5462  5462 D AdapterServiceConfig: Adding GattService
08-26 04:53:54.320  5462  5462 D AdapterServiceConfig: Adding BluetoothMapService
08-26 04:53:54.320  5462  5462 D AdapterServiceConfig: Adding SapService
,08-26 04:53:54.340   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e66bc05:true
,08-26 04:53:54.341  5462  5462 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 04:53:54.343  5462  5462 I bt_bluedroid: init
08-26 04:53:54.343  5462  5474 I BluetoothAdapterState: Entering OffState
,08-26 04:53:54.345  5462  5475 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 04:53:54.346  5462  5475 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-26 04:53:54.346  5462  5475 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 04:53:54.346  5462  5475 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 04:53:54.347  5462  5462 I bt_bluedroid: get_profile_interface socket
,08-26 04:53:54.349  5462  5478 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-26 04:53:54.349  5462  5462 I bt_bluedroid: get_profile_interface sdp
,08-26 04:53:54.351  5462  5478 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-26 04:53:54.353  5462  5473 I bt_bluedroid: config_hci_snoop_log
,08-26 04:53:54.355   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-26 04:53:54.358  5462  5474 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 04:53:54.358  5462  5474 D BluetoothAdapterProperties: Setting state to 14
,08-26 04:53:54.358  5462  5474 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-26 04:53:54.360  5462  5474 D BluetoothBondStateMachine: make
,08-26 04:53:54.362  5462  5479 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 04:53:54.364  5462  5474 I BluetoothAdapterState: Entering PendingCommandState
,08-26 04:53:54.365  5462  5462 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 04:53:54.367  5462  5462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:53:54.368  5462  5462 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 04:53:54.368  5462  5462 D BtGatt.GattService: Received start request. Starting profile...
08-26 04:53:54.368  5462  5462 D BtGatt.GattService: start()
08-26 04:53:54.368  5462  5462 I bt_bluedroid: get_profile_interface gatt
08-26 04:53:54.369  5462  5462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:53:54.369  5462  5462 D BtGatt.AdvertiseManager: advertise manager created
,08-26 04:53:54.374  5462  5462 V BluetoothAdapterState: isTurningOff()=false
,08-26 04:53:54.374  5462  5462 V BluetoothAdapterState: isTurningOn()=false
08-26 04:53:54.374  5462  5462 V BluetoothAdapterState: isBleTurningOn()=true
08-26 04:53:54.374  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:53:54.375  5462  5474 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-26 04:53:54.375  5462  5474 I bt_bluedroid: enable
08-26 04:53:54.375  5462  5475 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 04:53:54.376  5462  5475 I bt_hci  : start_up
,08-26 04:53:54.382  5462  5475 I bt_vendor: alloc value 0xf412104d
,08-26 04:53:54.382  5462  5475 I bt_vendor: init
08-26 04:53:54.382  5462  5475 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 04:53:54.382  5462  5475 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 04:53:54.507  5462  5475 D bt_hci  : start_up starting async portion
,08-26 04:53:54.507  5462  5482 I bt_hci  : event_finish_startup
08-26 04:53:54.507  5462  5482 I bt_hci_h4: hal_open
,08-26 04:53:54.507  5462  5482 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
08-26 04:53:54.510  5462  5482 I bt_userial_vendor: device fd = 51 open
,08-26 04:53:54.500  5483  5483 W irq/448-msm_hs_: type=1400 audit(0.0:70): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-26 04:53:54.518   387   387 I MSM-irqbalance: Discovered a new IRQ: 146
,08-26 04:53:54.520   387   387 I MSM-irqbalance: Discovered a new IRQ: 271
,08-26 04:53:54.525  5462  5482 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 04:53:54.527  5462  5482 D bt_hwcfg: Chipset BCM4358A3
,08-26 04:53:54.528  5462  5482 D bt_hwcfg: Target name = [BCM4358A3]
08-26 04:53:54.528  5462  5482 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-26 04:53:54.729  5412  5412 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 04:53:54.842  5462  5482 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 04:53:54.842  5462  5482 D bt_hwcfg: Settlement delay -- 100 ms
08-26 04:53:54.842  5462  5482 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 04:53:54.908   931  3070 D wifi    : set interface wlan0 flags (UP)
,08-26 04:53:54.913   931  3070 I WifiHAL : Initializing wifi
,08-26 04:53:54.913   931  3070 I WifiHAL : Creating socket
,08-26 04:53:54.918   931  3070 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-26 04:53:54.918   931  3070 D wifi    : Did set static halHandle = 0x7f71b2d240
08-26 04:53:54.919   931  3070 D wifi    : halHandle = 0x7f71b2d240, mVM = 0x7f887cd140, mCls = 0xae2
,08-26 04:53:54.919   931  3070 D wifi    : array field set
08-26 04:53:54.919   931  3070 I WifiNative-HAL: interface[0] = wlan0
08-26 04:53:54.920   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 04:53:54.924   931  5485 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547368391232
08-26 04:53:54.924   931  5485 D wifi    : waitForHalEvents called, vm = 0x7f887cd140, obj = 0xae2, env = 0x7f6ef87180
,08-26 04:53:54.966  5462  5482 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 04:53:54.966  5462  5482 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-26 04:53:54.967  5462  5482 I bt_hwcfg: vendor lib fwcfg completed
08-26 04:53:54.967  5462  5482 I bt_vendor: firmware callback
08-26 04:53:54.967  5462  5482 I bt_hci  : firmware_config_callback
,08-26 04:53:54.971  5462  5487 I bt_btu  : btu_task pending for preload complete event
,08-26 04:53:54.971  5462  5487 I bt_btu_task: Bluetooth chip preload is complete
08-26 04:53:54.971  5462  5487 I bt_btu  : btu_task received preload complete event
,08-26 04:53:54.974  5462  5487 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 04:53:54.974  5462  5487 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 04:53:54.974  5462  5487 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 04:53:54.974  5462  5487 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 04:53:54.974  5462  5487 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 04:53:54.975  5462  5487 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 04:53:54.975  5462  5487 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 04:53:54.975  5462  5487 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 04:53:54.975  5462  5487 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 04:53:54.975  5462  5487 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 04:53:54.975  5462  5487 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 04:53:54.975  5462  5487 I         : BTE_InitTraceLevels -- TRC_GATT
,08-26 04:53:54.975  5462  5487 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 04:53:54.975  5462  5487 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 04:53:54.975  5462  5487 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 04:53:55.010  5486  5486 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 04:53:55.029   931  3070 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 04:53:55.035  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:53:55.038  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:53:55.050  5462  5487 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf409ec99
08-26 04:53:55.050  5462  5487 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf409ec99 
08-26 04:53:55.053  5486  5486 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 04:53:55.054   931   944 I ActivityManager: Start proc 5489:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-26 04:53:55.070  5462  5478 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-26 04:53:55.071  5462  5478 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 04:53:55.072  5462  5478 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-26 04:53:55.075  5462  5478 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-26 04:53:55.076  5462  5478 D BluetoothAdapterProperties: Scan Mode:20
,08-26 04:53:55.076  5462  5478 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 04:53:55.078  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:53:55.080  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:53:55.080  5462  5478 D bt_hci  : do_postload posting postload work item
08-26 04:53:55.080  5462  5482 I bt_hci  : event_postload
08-26 04:53:55.080  5462  5482 I bt_vendor: sco_config_cb
08-26 04:53:55.080  5462  5482 I bt_hci  : sco_config_callback postload finished.
08-26 04:53:55.082  5462  5478 D bt_bte_conf: Device ID record 1 : primary
08-26 04:53:55.083  5462  5478 D bt_bte_conf:   vendorId            = 000f
08-26 04:53:55.083  5462  5478 D bt_bte_conf:   vendorIdSource      = 0001
08-26 04:53:55.083  5462  5478 D bt_bte_conf:   product             = 1200
08-26 04:53:55.083  5462  5478 D bt_bte_conf:   version             = 1436
08-26 04:53:55.083  5462  5478 D bt_bte_conf:   clientExecutableURL = 
08-26 04:53:55.083  5462  5478 D bt_bte_conf:   serviceDescription  = 
08-26 04:53:55.083  5462  5478 D bt_bte_conf:   documentationURL    = 
08-26 04:53:55.083  5462  5478 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 04:53:55.083  5462  5475 D bt_stack_manager: event_start_up_stack finished
,08-26 04:53:55.083  5462  5474 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 04:53:55.084  5462  5474 D BluetoothAdapterProperties: Setting state to 15
08-26 04:53:55.084  5462  5474 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 04:53:55.084  5462  5474 I BluetoothAdapterState: Entering BleOnState
,08-26 04:53:55.087  5462  5482 I bt_vendor: low_power_mode_cb
,08-26 04:53:55.088  5462  5474 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-26 04:53:55.088  5462  5474 D BluetoothAdapterProperties: Setting state to 11
08-26 04:53:55.088  5462  5474 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 04:53:55.091  5489  5489 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,08-26 04:53:55.094  5462  5462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
,08-26 04:53:55.094  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:53:55.094  5462  5462 D HeadsetService: Received start request. Starting profile...
08-26 04:53:55.095  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:53:55.097  5462  5462 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 04:53:55.097  5462  5462 D HeadsetStateMachine: make
08-26 04:53:55.102  5462  5474 I BluetoothAdapterState: Entering PendingCommandState
,08-26 04:53:55.106  5462  5462 D HeadsetStateMachine: max_hf_connections = 1
,08-26 04:53:55.106  5462  5462 I bt_bluedroid: get_profile_interface handsfree
08-26 04:53:55.106  5462  5478 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 04:53:55.106  5462  5478 E bt_btif : btif_hf_upstreams_evt: Invalid index 250
08-26 04:53:55.106  5489  5489 W InstanceID/Rpc: Found 10012
,08-26 04:53:55.110  5462  5462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
,08-26 04:53:55.112   931   931 D BluetoothA2dp: Proxy object connected
,08-26 04:53:55.112  5462  5462 D A2dpService: Received start request. Starting profile...
08-26 04:53:55.113  5462  5462 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 04:53:55.113  5462  5462 I bt_bluedroid: get_profile_interface avrcp
,08-26 04:53:55.122  5462  5462 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 04:53:55.123  5462  5462 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 04:53:55.123  5462  5462 D A2dpStateMachine: make
08-26 04:53:55.124  5462  5462 I bt_bluedroid: get_profile_interface a2dp
,08-26 04:53:55.124  5462  5478 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 04:53:55.126  5462  5513 D A2dpStateMachine: Enter Disconnected: -2
,08-26 04:53:55.126  5462  5462 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 04:53:55.127  5462  5462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
,08-26 04:53:55.127  5486  5486 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 04:53:55.127  5486  5486 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-26 04:53:55.129  5462  5462 D HidService: Received start request. Starting profile...
,08-26 04:53:55.129  5462  5462 I bt_bluedroid: get_profile_interface hidhost
,08-26 04:53:55.129  5462  5462 D HidService: setHidService(): set to: null
08-26 04:53:55.129  5462  5478 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40802d9
,08-26 04:53:55.129  5462  5478 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 04:53:55.130  5462  5462 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 04:53:55.131  5462  5462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:53:55.131  5462  5462 D HealthService: Received start request. Starting profile...
08-26 04:53:55.132  5462  5462 I bt_bluedroid: get_profile_interface health
08-26 04:53:55.133  5462  5462 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 04:53:55.134  5462  5462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:53:55.136  3239  3239 D BluetoothInputDevice: Proxy object connected
08-26 04:53:55.136  5462  5462 D PanService: Received start request. Starting profile...
08-26 04:53:55.136  5462  5462 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 04:53:55.136  3239  3239 D HidProfile: Bluetooth service connected
,08-26 04:53:55.136  5462  5462 I bt_bluedroid: get_profile_interface pan
08-26 04:53:55.137  5462  5478 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 04:53:55.138  3239  3239 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 04:53:55.138  3239  3239 D PanProfile: Bluetooth service connected
08-26 04:53:55.139  5462  5462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:53:55.140  3239  3239 D BluetoothMap: Proxy object connected
08-26 04:53:55.141  5462  5462 D BluetoothMapService: Received start request. Starting profile...
08-26 04:53:55.141  3239  3239 D MapProfile: Bluetooth service connected
08-26 04:53:55.141  5462  5462 D BluetoothMapService: start()
08-26 04:53:55.141  3239  3239 D BluetoothMap: getConnectedDevices()
08-26 04:53:55.142  3239  3239 D BluetoothMap: Bluetooth is Not enabled
08-26 04:53:55.144  5462  5462 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-26 04:53:55.145  5462  5462 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-26 04:53:55.145  5462  5462 D BluetoothMapAppObserver: createReceiver()
,08-26 04:53:55.149   931  3070 D WifiConfigStore: Loading config and enabling all networks 
,08-26 04:53:55.151  5412  5412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:55.151  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:53:55.151  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:53:55.151  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-26 04:53:55.151  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:53:55.151  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 04:53:55.151  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:53:55.151  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:53:55.151  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 04:53:55.152  5412  5412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:55.152  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 04:53:55.153  5462  5462 D BluetoothMapAppObserver: initObservers()
08-26 04:53:55.153  5462  5462 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 04:53:55.155  5412  5412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:55.155  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:53:55.155  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:53:55.155  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-26 04:53:55.155  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:53:55.155  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 04:53:55.155  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:53:55.155  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:53:55.155  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 04:53:55.156  5412  5412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:53:55.156  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 04:53:55.156   931  3070 D WifiConfigStore: loaded 0 passpoint configs
08-26 04:53:55.157   931  3070 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 04:53:55.158   931  3070 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 04:53:55.158   931  3070 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-26 04:53:55.159   931  3070 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-26 04:53:55.159  5462  5462 V SapService: SapBinder()
08-26 04:53:55.159  5462  5462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:53:55.159   931  3070 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 04:53:55.159  5462  5462 D SapService: Received start request. Starting profile...
08-26 04:53:55.159  5462  5462 V SapService: start()
,08-26 04:53:55.162   931  3070 D WifiNative-HAL: Setting external_sim to 1
,08-26 04:53:55.162  4300  4300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 04:53:55.162   931  3070 D wifi    : setting dfs flag to true, 0x7f6d6e0d00
,08-26 04:53:55.163  5462  5462 V BluetoothAdapterState: isTurningOff()=false
08-26 04:53:55.163  5462  5462 V BluetoothAdapterState: isTurningOn()=true
08-26 04:53:55.163   931  3070 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 04:53:55.163  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:53:55.163   931  3070 D wifi    : setting scan oui 0x7f6d6e0d00
08-26 04:53:55.163  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 04:53:55.163  5462  5504 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=2
08-26 04:53:55.163   931  3070 D WifiHAL : Sending mac address OUI
08-26 04:53:55.163  5462  5462 V BluetoothAdapterState: isTurningOff()=false
08-26 04:53:55.163  5462  5462 V BluetoothAdapterState: isTurningOn()=true
08-26 04:53:55.163  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:53:55.163  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:53:55.163  5462  5462 V BluetoothAdapterState: isTurningOff()=false
08-26 04:53:55.163  5462  5462 V BluetoothAdapterState: isTurningOn()=true
08-26 04:53:55.163  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:53:55.163  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:53:55.164  5462  5462 V BluetoothAdapterState: isTurningOff()=false
08-26 04:53:55.164  5462  5462 V BluetoothAdapterState: isTurningOn()=true
08-26 04:53:55.164  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:53:55.164  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 04:53:55.164  5462  5462 V BluetoothAdapterState: isTurningOff()=false
08-26 04:53:55.164  5462  5462 V BluetoothAdapterState: isTurningOn()=true
08-26 04:53:55.164  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:53:55.164  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:53:55.164  5462  5462 V BluetoothAdapterState: isTurningOff()=false
08-26 04:53:55.164  5462  5462 V BluetoothAdapterState: isTurningOn()=true
08-26 04:53:55.165  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:53:55.165  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:53:55.165  5462  5462 V BluetoothAdapterState: isTurningOff()=false
08-26 04:53:55.165  5462  5462 V BluetoothAdapterState: isTurningOn()=true
08-26 04:53:55.165  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:53:55.165  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 04:53:55.166  5462  5474 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-26 04:53:55.167  5462  5474 D BluetoothAdapterProperties: ScanMode =  20
08-26 04:53:55.167  5462  5474 D BluetoothAdapterProperties: State =  11
08-26 04:53:55.167  5462  5474 D BluetoothAdapterProperties: Setting state to 12
08-26 04:53:55.167  5462  5474 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 04:53:55.167  5462  5474 I BluetoothAdapterState: Entering OnState
08-26 04:53:55.168  3603  3620 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 04:53:55.168  5462  5478 D BluetoothAdapterProperties: Scan Mode:21
08-26 04:53:55.168  5462  5478 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 04:53:55.169   931  3070 E native  : do suspend true
,08-26 04:53:55.171   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 04:53:55.171  3239  3251 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 04:53:55.171   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 04:53:55.171   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 04:53:55.172  3239  3250 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 04:53:55.172  5412  5412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-26 04:53:55.173   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 04:53:55.173  3239  3811 D BluetoothPan: onBluetoothStateChange on: true
08-26 04:53:55.173  3239  3803 D BluetoothMap: onBluetoothStateChange: up=true
08-26 04:53:55.175  5412  5412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 04:53:55.175   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 04:53:55.175  5462  5462 D BluetoothMapService: onReceive
08-26 04:53:55.175  5462  5462 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 04:53:55.176  5489  5489 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-26 04:53:55.176  5462  5462 D BluetoothMapService: STATE_ON
,08-26 04:53:55.179  5462  5462 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 04:53:55.179  5462  5462 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 04:53:55.179  5412  5412 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 04:53:55.180   931   931 D RttService: SCAN_AVAILABLE : 3
08-26 04:53:55.180   931  3070 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-26 04:53:55.180   506   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-26 04:53:55.180   931  3179 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 04:53:55.180   931  3236 I ActivityManager: Killing 5126:org.codeaurora.ims/1001 (adj 15): empty #17
08-26 04:53:55.181   506   925 D CommandListener: Setting iface cfg
08-26 04:53:55.181  5462  5462 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 04:53:55.182  5462  5526 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 04:53:55.182   931  3069 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '30 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 30 Failed to set address (No such device)'
,08-26 04:53:55.182   931  3069 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 04:53:55.183  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:53:55.183  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:53:55.183  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:53:55.183  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:53:55.183  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:53:55.183  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:53:55.183  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:53:55.183  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 04:53:55.187  3239  3468 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-26 04:53:55.187  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 04:53:55.191  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:53:55.191  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:53:55.191  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:53:55.191  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:53:55.191  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:53:55.191  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:53:55.191  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:53:55.191  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 04:53:55.192  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 04:53:55.194  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:53:55.195  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:53:55.204  5462  5526 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,08-26 04:53:55.204  5462  5526 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 04:53:55.204  3239  3239 D BluetoothA2dp: Proxy object connected
,08-26 04:53:55.207  3239  3468 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-26 04:53:55.211   931  3069 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 04:53:55.212   931  3069 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-26 04:53:55.217   931  3526 I ActivityManager: Start proc 5529:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-26 04:53:55.218  5462  5462 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 04:53:55.221  5462  5462 D ObexServerSockets: Succeed to create listening sockets 
,08-26 04:53:55.221  5462  5462 D ObexServerSockets0: startAccept()
08-26 04:53:55.221  5462  5462 D ObexServerSockets0: prepareForNewConnect()
08-26 04:53:55.223  5462  5462 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 04:53:55.223  5462  5462 D BluetoothSdpJni: SDP Create record success - handle: 1
08-26 04:53:55.223  5462  5462 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 04:53:55.224  5462  5462 D ObexServerSockets0: prepareForNewConnect()
08-26 04:53:55.223  5462  5535 D ObexServerSockets0: Accepting socket connection...
,08-26 04:53:55.225  5462  5536 D ObexServerSockets0: Accepting socket connection...
,08-26 04:53:55.251  5529  5529 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,08-26 04:53:55.259   931  3623 I ActivityManager: Killing 4704:com.google.android.calendar/u0a36 (adj 15): empty #17
,08-26 04:53:55.270  3603  3628 D BluetoothHeadset: Proxy object connected
,08-26 04:53:55.271   931   948 D BluetoothHeadset: Proxy object connected
08-26 04:53:55.271   931   948 D BluetoothHeadset: Proxy object connected
,08-26 04:53:55.273   931   948 D BluetoothHeadset: Proxy object connected
,08-26 04:53:55.279  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 04:53:55.292   931   941 I ActivityManager: Start proc 5543:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-26 04:53:55.309  3239  3251 D BluetoothHeadset: Proxy object connected
,08-26 04:53:55.310  3239  3239 D HeadsetProfile: Bluetooth service connected
,08-26 04:53:55.325  5543  5543 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,08-26 04:53:55.515  5543  5543 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 04:53:55.515  5543  5543 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 04:53:55.515  5543  5543 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 04:53:55.517   931  3621 I ActivityManager: Killing 4920:com.google.android.gm/u0a68 (adj 15): empty #17
,08-26 04:53:55.599  5529  5529 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 04:53:55.605   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ad0c209:true
,08-26 04:53:55.607  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 04:53:55.607  3701  3701 E AuthorizationBluetoothService: Proximity feature is not enabled.
,08-26 04:53:55.613  5529  5529 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-26 04:53:55.615  3239  3239 D BluetoothPbap: Proxy object connected
08-26 04:53:55.616  3239  3239 D PbapServerProfile: Bluetooth service connected
,08-26 04:53:55.619  5529  5529 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-26 04:53:55.625  5462  5573 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 04:53:55.641  5462  5577 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 04:53:55.643  5462  5577 I BtOppRfcommListener: Accept thread started.
,08-26 04:53:55.647  5529  5529 D LocalBluetoothProfileManager: Adding local MAP profile
08-26 04:53:55.648  5529  5529 D BluetoothMap: Create BluetoothMap proxy object
,08-26 04:53:55.655  5529  5529 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-26 04:53:55.660  5529  5529 D DockEventReceiver: finishStartingService: stopping service
,08-26 04:53:55.661  5529  5529 D BluetoothA2dp: Proxy object connected
,08-26 04:53:55.664  5529  5529 D BluetoothInputDevice: Proxy object connected
,08-26 04:53:55.664  5529  5529 D HidProfile: Bluetooth service connected
,08-26 04:53:55.666  5529  5529 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 04:53:55.667  5529  5529 D PanProfile: Bluetooth service connected
08-26 04:53:55.667  5529  5529 D BluetoothMap: Proxy object connected
08-26 04:53:55.667  5529  5529 D MapProfile: Bluetooth service connected
08-26 04:53:55.667  5529  5529 D BluetoothMap: getConnectedDevices()
,08-26 04:53:55.669  5529  5529 D BluetoothPbap: Proxy object connected
08-26 04:53:55.670  5529  5529 D PbapServerProfile: Bluetooth service connected
,08-26 04:53:55.718  5543  5559 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 04:53:55.722  5529  5542 D BluetoothHeadset: Proxy object connected
,08-26 04:53:55.723  5529  5529 D HeadsetProfile: Bluetooth service connected
,08-26 04:53:55.729   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d9b9aed:true
,08-26 04:53:56.983  5486  5486 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 04:53:57.031   931  3070 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-26 04:53:57.042   931  3070 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,08-26 04:53:57.043   931  3070 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 04:53:57.057   931  3070 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-26 04:53:57.094   931  3070 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-26 04:53:57.096   931  3070 E WifiConfigStore:  rewrite network history for "NG700"WPA_PSK
,08-26 04:53:57.259   931   941 D WifiService: setWifiEnabled: false pid=5412, uid=10077
08-26 04:53:57.259   931   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 04:53:57.270   931   931 D RttService: SCAN_AVAILABLE : 1
,08-26 04:53:57.271   931  3179 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 04:53:57.283   931  3070 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 04:53:57.287   506   925 D CommandListener: Clearing all IP addresses on wlan0
,08-26 04:53:57.296   931  3070 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-26 04:53:57.298  5486  5486 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-26 04:53:57.313  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:53:57.313  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:53:57.313  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:53:57.313  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 04:53:57.313  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:53:57.313  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:53:57.313  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:53:57.313  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 04:53:57.317  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 04:53:57.320  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:53:57.320  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:53:57.320  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:53:57.320  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 04:53:57.320  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:53:57.320  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:53:57.320  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:53:57.320  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 04:53:57.322  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 04:53:57.326  5486  5486 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-26 04:53:57.329  5486  5486 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,08-26 04:53:57.335  5486  5486 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-26 04:53:57.366  5486  5486 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-26 04:53:57.472   931  3070 D wifi    : In wifi stop Hal
,08-26 04:53:57.472  4300  4300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 04:53:57.474   931  3070 D wifi    : halHandle = 0x7f71b2d240, mVM = 0x7f887cd140, mCls = 0xae2
08-26 04:53:57.475   931  5485 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-26 04:53:57.475   931  5485 D WifiHAL : Got a signal to exit!!!
08-26 04:53:57.475   931  5485 I WifiHAL : Exit wifi_event_loop
08-26 04:53:57.476   931  3070 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-26 04:53:57.476   931  3070 E WifiHAL : Event processing terminated
08-26 04:53:57.477   931  3070 D wifi    : In wifi cleaned up handler
08-26 04:53:57.477   931  3070 I WifiHAL : Internal cleanup completed
08-26 04:53:57.478  3731  4050 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 04:53:57.486  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:53:57.489  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:53:57.511   931  5485 D wifi    : set interface wlan0 flags (DOWN)
,08-26 04:53:57.511   931  3070 D WifiNative-HAL: HAL event thread stopped successfully
,08-26 04:53:57.717   931   948 D Tethering: InitialState.processMessage what=4
,08-26 04:53:57.725   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 04:53:59.591   387   387 I MSM-irqbalance: Discovered a new IRQ: 304
,08-26 04:54:00.265   931   941 D WifiService: setWifiEnabled: true pid=5412, uid=10077
,08-26 04:54:00.265   931   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 04:54:00.272   506   925 D SoftapController: Softap fwReload - Ok
,08-26 04:54:00.277   506   925 D CommandListener: Setting iface cfg
,08-26 04:54:00.278   506   925 D CommandListener: Trying to bring down wlan0
08-26 04:54:00.279   506   925 D CommandListener: Clearing all IP addresses on wlan0
,08-26 04:54:00.282   931  3070 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-26 04:54:00.898   931  3070 D wifi    : set interface wlan0 flags (UP)
,08-26 04:54:00.901   931  3070 I WifiHAL : Initializing wifi
08-26 04:54:00.901   931  3070 I WifiHAL : Creating socket
08-26 04:54:00.907   931  3070 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-26 04:54:00.907   931  3070 D wifi    : Did set static halHandle = 0x7f71b2d240
08-26 04:54:00.907   931  3070 D wifi    : halHandle = 0x7f71b2d240, mVM = 0x7f887cd140, mCls = 0x17ea
,08-26 04:54:00.908   931  3070 D wifi    : array field set
08-26 04:54:00.908   931  3070 I WifiNative-HAL: interface[0] = wlan0
08-26 04:54:00.910   931  5586 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547368391232
08-26 04:54:00.910   931  5586 D wifi    : waitForHalEvents called, vm = 0x7f887cd140, obj = 0x17ea, env = 0x7f6ef88680
08-26 04:54:00.911   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 04:54:00.959  5587  5587 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 04:54:00.979  5587  5587 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 04:54:00.988  5587  5587 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 04:54:00.988  5587  5587 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-26 04:54:01.012   931  3070 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 04:54:01.019  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:54:01.021  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:54:01.023   931  3070 D WifiConfigStore: Loading config and enabling all networks 
,08-26 04:54:01.027  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:01.027  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:01.027  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:01.027  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:01.027  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:01.027  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:54:01.027  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:54:01.027  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 04:54:01.028   931  3070 D WifiConfigStore: loaded 0 passpoint configs
08-26 04:54:01.028   931  3070 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 04:54:01.029   931  3070 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-26 04:54:01.029  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 04:54:01.030   931  3070 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-26 04:54:01.030   931  3070 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-26 04:54:01.030   931  3070 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 04:54:01.034  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:01.034  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:01.034  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:01.034  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:01.034  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:01.034  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:54:01.034  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:54:01.034  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 04:54:01.035   931  3070 D WifiNative-HAL: Setting external_sim to 1
08-26 04:54:01.035   931  3070 D wifi    : setting dfs flag to true, 0x7f82642840
,08-26 04:54:01.035   931  3070 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 04:54:01.036   931  3070 D wifi    : setting scan oui 0x7f82642840
08-26 04:54:01.036   931  3070 D WifiHAL : Sending mac address OUI
08-26 04:54:01.036  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 04:54:01.037  4300  4300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 04:54:01.050   931  3070 E native  : do suspend true
,08-26 04:54:01.056   931   931 D RttService: SCAN_AVAILABLE : 3
08-26 04:54:01.056   931  3070 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-26 04:54:01.056   506   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-26 04:54:01.056   931  3179 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 04:54:01.057   506   925 D CommandListener: Setting iface cfg
,08-26 04:54:01.061   931  3069 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '42 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 42 Failed to set address (No such device)'
,08-26 04:54:01.061   931  3069 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 04:54:01.063   931  3069 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 04:54:01.068   931  3069 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-26 04:54:01.085   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=181401 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,08-26 04:54:03.276  5462  5474 D BluetoothAdapterState: Current state: ON, message: 23
08-26 04:54:03.277  5462  5474 D BluetoothAdapterProperties: Setting state to 13
,08-26 04:54:03.277  5462  5474 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 04:54:03.278  5462  5474 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 04:54:03.280  5462  5474 I BluetoothAdapterState: Entering PendingCommandState
08-26 04:54:03.282  5462  5462 D BluetoothMapService: onReceive
08-26 04:54:03.283  5462  5462 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 04:54:03.283  5462  5462 D BluetoothMapService: STATE_TURNING_OFF
08-26 04:54:03.285  5462  5462 D BluetoothMapService: MAP Service closeService in
08-26 04:54:03.286  5462  5462 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 04:54:03.286  5462  5462 D ObexServerSockets0: shutdown(block = true)
08-26 04:54:03.289  5462  5462 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 04:54:03.290  5462  5535 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
08-26 04:54:03.290  5462  5462 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 04:54:03.291  5462  5501 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 04:54:03.291  5462  5536 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 04:54:03.292  5462  5478 D BluetoothAdapterProperties: Scan Mode:20
08-26 04:54:03.292  5462  5474 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 04:54:03.295  5462  5462 I BtOppRfcommListener: stopping Accept Thread
08-26 04:54:03.296  5462  5577 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 04:54:03.296  5462  5577 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 04:54:03.297  5529  5529 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 04:54:03.299  5412  5412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:54:03.299  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:03.299  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:03.299  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:03.299  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:03.299  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 04:54:03.299  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:54:03.299  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:54:03.299  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 04:54:03.300  5412  5412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:54:03.300  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 04:54:03.301  5462  5462 D HeadsetService: Received stop request...Stopping profile...
,08-26 04:54:03.304   931   931 D BluetoothHeadset: Proxy object disconnected
,08-26 04:54:03.305  5412  5412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:54:03.305  3239  3251 D BluetoothHeadset: Proxy object disconnected
08-26 04:54:03.305  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:03.305  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:03.305  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:03.305  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:03.305  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 04:54:03.305  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:54:03.305  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:54:03.305  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 04:54:03.305  5462  5462 D A2dpService: Received stop request...Stopping profile...
08-26 04:54:03.305  3603  3628 D BluetoothHeadset: Proxy object disconnected
08-26 04:54:03.306  5412  5412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:54:03.306   931   931 D BluetoothHeadset: Proxy object disconnected
08-26 04:54:03.306  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 04:54:03.306   931   931 D BluetoothHeadset: Proxy object disconnected
08-26 04:54:03.306  5529  5542 D BluetoothHeadset: Proxy object disconnected
08-26 04:54:03.306  5462  5513 D A2dpStateMachine: Exit Disconnected: -1
08-26 04:54:03.306  5529  5529 D DockEventReceiver: finishStartingService: stopping service
08-26 04:54:03.308   931   931 D BluetoothA2dp: Proxy object disconnected
,08-26 04:54:03.309  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:03.311  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:54:03.312  3239  3239 D HeadsetProfile: Bluetooth service disconnected
08-26 04:54:03.313  5462  5462 D HidService: Received stop request...Stopping profile...
08-26 04:54:03.313  5462  5462 D HidService: Stopping Bluetooth HidService
08-26 04:54:03.313  3239  3239 D BluetoothA2dp: Proxy object disconnected
08-26 04:54:03.314  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 04:54:03.315  5462  5462 V BluetoothAdapterState: isTurningOff()=true
08-26 04:54:03.315  3239  3239 D BluetoothInputDevice: Proxy object disconnected
08-26 04:54:03.315  5462  5462 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:03.315  3239  3239 D HidProfile: Bluetooth service disconnected
,08-26 04:54:03.315  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:03.315  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 04:54:03.318  5462  5462 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 04:54:03.318  5462  5462 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 04:54:03.318  5462  5478 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-26 04:54:03.318  5462  5462 V BluetoothAdapterState: isTurningOff()=true
08-26 04:54:03.318  5462  5487 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 04:54:03.318  5462  5462 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:03.318  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:03.318  5462  5487 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 04:54:03.318  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:03.318  5462  5487 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 04:54:03.318  5462  5478 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-26 04:54:03.319  5462  5462 D HealthService: Received stop request...Stopping profile...
,08-26 04:54:03.320  5462  5478 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 04:54:03.320  5462  5487 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 04:54:03.321  5462  5487 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 04:54:03.321  5462  5487 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 04:54:03.321  5462  5462 D PanService: Received stop request...Stopping profile...
,08-26 04:54:03.321  5462  5487 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 04:54:03.321  5462  5487 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 04:54:03.321  5462  5487 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 04:54:03.322  3239  3239 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 04:54:03.322  5462  5462 D BluetoothMapService: Received stop request...Stopping profile...
08-26 04:54:03.322  3239  3239 D PanProfile: Bluetooth service disconnected
,08-26 04:54:03.322  5462  5462 D BluetoothMapService: stop()
08-26 04:54:03.324  5462  5462 D BluetoothMapAppObserver: deinitObservers()
08-26 04:54:03.324  5462  5462 D BluetoothMapAppObserver: removeReceiver()
08-26 04:54:03.325  3239  3239 D BluetoothMap: Proxy object disconnected
08-26 04:54:03.325  3239  3239 D MapProfile: Bluetooth service disconnected
08-26 04:54:03.326  5462  5462 D SapService: Received stop request...Stopping profile...
,08-26 04:54:03.326  5462  5462 V SapService: stop()
,08-26 04:54:03.335  5462  5462 V BluetoothAdapterState: isTurningOff()=true
08-26 04:54:03.335  5462  5462 V BluetoothAdapterState: isTurningOn()=false
,08-26 04:54:03.335  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:03.335  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:03.335  5462  5462 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 04:54:03.335  5462  5462 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 04:54:03.335  5529  5529 D HeadsetProfile: Bluetooth service disconnected
08-26 04:54:03.336  5462  5462 V BluetoothAdapterState: isTurningOff()=true
08-26 04:54:03.336  5462  5462 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:03.336  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:03.336  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:03.336  5462  5462 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 04:54:03.335  3239  3239 D BluetoothPbap: Proxy object disconnected
08-26 04:54:03.336  5462  5462 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 04:54:03.336  3239  3239 D PbapServerProfile: Bluetooth service disconnected
08-26 04:54:03.336  5529  5529 D BluetoothA2dp: Proxy object disconnected
08-26 04:54:03.337  5529  5529 D BluetoothInputDevice: Proxy object disconnected
08-26 04:54:03.337  5462  5462 V BluetoothAdapterState: isTurningOff()=true
08-26 04:54:03.337  5529  5529 D HidProfile: Bluetooth service disconnected
08-26 04:54:03.337  5462  5462 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:03.337  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:03.337  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:03.337  5462  5462 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 04:54:03.337  5462  5462 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 04:54:03.337  5529  5529 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 04:54:03.337  5529  5529 D PanProfile: Bluetooth service disconnected
,08-26 04:54:03.338  5462  5462 D BluetoothMapService: MAP Service closeService in
08-26 04:54:03.338  5462  5462 V BluetoothAdapterState: isTurningOff()=true
08-26 04:54:03.338  5462  5462 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:03.338  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:03.338  5462  5478 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 04:54:03.338  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:03.338  5462  5478 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 04:54:03.338  5462  5462 D BluetoothMapService: cleanup()
08-26 04:54:03.338  5462  5462 D BluetoothMapService: MAP Service closeService in
08-26 04:54:03.338  5462  5462 V BluetoothAdapterState: isTurningOff()=true
08-26 04:54:03.339  5462  5462 V BluetoothAdapterState: isTurningOn()=false
,08-26 04:54:03.339  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:03.339  5462  5462 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:03.339  5462  5474 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 04:54:03.339  5462  5474 D BluetoothAdapterProperties: Setting state to 15
08-26 04:54:03.339  5462  5474 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 04:54:03.339  5462  5474 I BluetoothAdapterState: Entering BleOnState
,08-26 04:54:03.340  5529  5529 D BluetoothMap: Proxy object disconnected
,08-26 04:54:03.340  3603  3869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 04:54:03.340  5529  5529 D MapProfile: Bluetooth service disconnected
08-26 04:54:03.341  5529  5529 D BluetoothPbap: Proxy object disconnected
08-26 04:54:03.341  5529  5529 D PbapServerProfile: Bluetooth service disconnected
08-26 04:54:03.341   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 04:54:03.341  5529  5542 D BluetoothPan: onBluetoothStateChange on: false
08-26 04:54:03.342  5529  5541 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 04:54:03.343  3239  3803 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 04:54:03.343  5529  5542 D BluetoothMap: onBluetoothStateChange: up=false
08-26 04:54:03.344   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 04:54:03.344  3239  3251 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 04:54:03.344   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 04:54:03.344  5529  5541 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 04:54:03.345  3239  3250 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 04:54:03.346  5529  5542 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 04:54:03.346   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 04:54:03.346  3239  3811 D BluetoothPan: onBluetoothStateChange on: false
08-26 04:54:03.346  3239  3803 D BluetoothMap: onBluetoothStateChange: up=false
08-26 04:54:03.347  5529  5541 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 04:54:03.347  3239  3251 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 04:54:03.348  5462  5474 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 04:54:03.348  5462  5474 D BluetoothAdapterProperties: Setting state to 16
08-26 04:54:03.348  5462  5474 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 04:54:03.349  5462  5474 D BluetoothAdapterProperties: onBleDisable
08-26 04:54:03.349  5462  5474 I BluetoothAdapterState: Entering PendingCommandState
08-26 04:54:03.349  5462  5475 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 04:54:03.350  5462  5487 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 04:54:03.350  5462  5487 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 04:54:03.350  5462  5478 D BluetoothAdapterProperties: Scan Mode:20
08-26 04:54:03.351  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:03.352  5529  5529 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 04:54:03.353  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:03.356  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:03.357  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:03.357  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 04:54:03.358  5529  5529 D DockEventReceiver: finishStartingService: stopping service
,08-26 04:54:03.554  5462  5478 I bt_hci  : shut_down
,08-26 04:54:03.563  5462  5482 D bt_hwcfg: hw_epilog_process
,08-26 04:54:03.565  5462  5482 I bt_vendor: low_power_mode_cb
,08-26 04:54:03.567  5462  5482 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-26 04:54:03.567  5462  5482 I bt_vendor: epilog_cb
08-26 04:54:03.568  5462  5482 I bt_hci  : epilog_finished_callback
,08-26 04:54:03.570  5462  5478 I bt_hci_h4: hal_close
,08-26 04:54:03.571  5462  5478 I bt_userial_vendor: device fd = 51 close
,08-26 04:54:03.677  5462  5475 D bt_stack_manager: event_shut_down_stack finished.
,08-26 04:54:03.678  5462  5474 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 04:54:03.682  5462  5462 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 04:54:03.683  5462  5462 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 04:54:03.683  5462  5462 D BtGatt.GattService: stop()
,08-26 04:54:03.684  5462  5462 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 04:54:03.684  5462  5474 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-26 04:54:03.687  5462  5462 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:03.687  5462  5462 V BluetoothAdapterState: isTurningOn()=false
,08-26 04:54:03.687  5462  5462 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:03.687  5462  5462 V BluetoothAdapterState: isBleTurningOff()=true
08-26 04:54:03.688  5462  5474 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 04:54:03.688  5462  5474 D BluetoothAdapterProperties: Setting state to 10
08-26 04:54:03.688  5462  5474 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 04:54:03.690  5462  5474 I BluetoothAdapterState: Entering OffState
08-26 04:54:03.691   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 04:54:03.706  5462  5462 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 04:54:03.706  5462  5462 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 04:54:03.706  5462  5462 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 04:54:03.709  5462  5475 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 04:54:03.712  5462  5475 D bt_stack_manager: event_clean_up_stack finished.
,08-26 04:54:03.714  5462  5462 I art     : System.exit called, status: 0
,08-26 04:54:03.714  5462  5462 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 04:54:03.753   931   942 I ActivityManager: Process com.android.bluetooth (pid 5462) has died
,08-26 04:54:04.290  5587  5587 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 04:54:04.321   931  3070 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-26 04:54:04.333   931  3070 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,08-26 04:54:04.333   931  3070 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 04:54:04.350   931  3070 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-26 04:54:04.396   931  3070 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-26 04:54:04.749  5587  5587 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 04:54:04.790  5587  5587 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 04:54:04.792  5587  5587 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-26 04:54:04.812   931  3070 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 04:54:04.813   931  3070 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 04:54:04.813   931  3072 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 04:54:04.833   931  3070 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 04:54:04.845   506   925 D CommandListener: Setting iface cfg
,08-26 04:54:04.855   931  3070 D WifiStateMachine: Start Dhcp Watchdog 1
,08-26 04:54:04.863   931  3070 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 04:54:04.889   931  5597 D DhcpClient: Receive thread started
,08-26 04:54:04.973   931  3070 E native  : do suspend false
,08-26 04:54:04.991   931  5596 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 04:54:05.021   931  5597 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 170430, domain null
,08-26 04:54:05.023   931  5596 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 170430 seconds
,08-26 04:54:05.029   931  5596 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,08-26 04:54:05.054   931  5597 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 04:54:05.055   931  5596 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 04:54:05.060   506   925 D CommandListener: Setting iface cfg
,08-26 04:54:05.069   931  5596 D DhcpClient: Scheduling renewal in 86399s
,08-26 04:54:05.071   931  3070 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 04:54:05.073   931  3070 E native  : do suspend true
,08-26 04:54:05.088   931  3070 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-26 04:54:05.090   931  3070 D WifiConfigStore: No blacklist allowed without epno enabled
08-26 04:54:05.090   931  3072 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 04:54:05.092   931  3070 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 04:54:05.100   931  3072 D ConnectivityService: Adding iface wlan0 to network 100
,08-26 04:54:05.132   931  3072 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 04:54:05.132   931  3072 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-26 04:54:05.135   931  3072 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-26 04:54:05.137   931  3072 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-26 04:54:05.139   931  3072 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-26 04:54:05.146   931  3072 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 04:54:05.150   931  3072 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-26 04:54:05.150   931  3072 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
08-26 04:54:05.150   931  3070 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-26 04:54:05.151   931  3070 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 04:54:05.151   931  3072 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
08-26 04:54:05.152   931  3072 D ConnectivityService:    accepting network in place of null
08-26 04:54:05.153   931  3072 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 04:54:05.166   931  5595 D NetlinkSocketObserver: NeighborEvent{elapsedMs=185480, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 04:54:05.176   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 04:54:05.196   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 04:54:05.198   931  3072 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-26 04:54:05.202   931  3072 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 04:54:05.202   931  3072 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 04:54:05.203  3577  3741 W QCNEJ   : |CORE| network available: 100
08-26 04:54:05.204   931  3072 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-26 04:54:05.204   931   948 D Tethering: MasterInitialState.processMessage what=3
08-26 04:54:05.205  3577  3741 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
08-26 04:54:05.208  5140  5140 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@b01364d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-26 04:54:05.208  3577  3741 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
08-26 04:54:05.208  3577  3741 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,08-26 04:54:05.213  5412  5412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:54:05.213  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:05.213  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:05.213  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:05.213  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:05.213  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 04:54:05.213  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 04:54:05.213  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 04:54:05.213  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 04:54:05.213  5412  5412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:54:05.213  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 04:54:05.216  5412  5412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 04:54:05.216  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:05.216  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:05.216  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:05.216  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:05.216  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 04:54:05.216  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 04:54:05.216  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 04:54:05.216  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 04:54:05.216  5412  5412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:54:05.216  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 04:54:05.219  4766  4779 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,08-26 04:54:05.219  4766  4779 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-26 04:54:05.219  4766  4779 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
08-26 04:54:05.220  4766  4779 E SarControlService: no key has been found,reset the power
08-26 04:54:05.220  4766  4804 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-26 04:54:05.220  4766  4804 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-26 04:54:05.222  4766  4804 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,08-26 04:54:05.223  4792  4792 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,08-26 04:54:05.225  4792  4792 D QcrilMsgTunnelSocket: [1000] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-26 04:54:05.237  4766  4804 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-26 04:54:05.237  4766  4804 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-26 04:54:05.237  4766  4804 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-26 04:54:05.238  4792  4792 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-26 04:54:05.238  4792  4792 D QcrilMsgTunnelSocket: [1001] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,08-26 04:54:05.251  4792  4806 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7492b19 HexData = [00000000e803000000000000ffffffff]
,08-26 04:54:05.252  4792  4806 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-26 04:54:05.252  4792  4806 D QcrilMsgTunnelSocket: [1000] < OEM_HOOK_RAW [null]
08-26 04:54:05.252  4792  4792 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-26 04:54:05.253  4766  4777 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-26 04:54:05.258  5140  5140 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-26 04:54:05.259  4792  4806 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7492b19 HexData = [00000000e903000000000000ffffffff]
08-26 04:54:05.260  4792  4806 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-26 04:54:05.260  4792  4806 D QcrilMsgTunnelSocket: [1001] < OEM_HOOK_RAW [null]
08-26 04:54:05.260  4792  4792 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-26 04:54:05.260  4766  4776 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-26 04:54:05.274   931  3621 I ActivityManager: Start proc 5617:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-26 04:54:05.290   931  5594 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.14,2a00:1450:4001:816::200e
,08-26 04:54:05.314  5617  5617 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,08-26 04:54:05.326  3963  3963 E MDM     : [1] SitrepService.a: No Google accounts; deferring server state update.
,08-26 04:54:05.327  3963  5614 I CheckinService: Checking schedule, now: 1472201645327 next: 30000
,08-26 04:54:05.327  3963  5614 I CheckinService: active receiver: enabled
,08-26 04:54:05.333  3963  5614 I CheckinService: Preparing to send checkin request
,08-26 04:54:05.333  3963  5614 I EventLogService: Accumulating logs since 1472201076562
,08-26 04:54:05.337  3963  5633 I iu.SyncManager: SYNC; picasa accounts
,08-26 04:54:05.347  3963  3963 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-26 04:54:05.353  3963  3963 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 04:54:05.357  3963  5633 I iu.UploadsManager: num queued entries: 0
,08-26 04:54:05.358  3963  5633 I iu.UploadsManager: num updated entries: 0
08-26 04:54:05.358  3963  5633 I iu.SyncManager: NEXT; no task
,08-26 04:54:05.366  3963  3963 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 04:54:05.385   931   941 I ActivityManager: Start proc 5642:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-26 04:54:05.386  3963  3963 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 04:54:05.394   931  5607 D GpsLocationProvider: NTP server returned: 1472201645236 (Fri Aug 26 04:54:05 EDT 2016) reference: 185710 certainty: 51 system time offset: -158
,08-26 04:54:05.394   931  3561 D AlarmManagerService: Setting time of day to sec=1472201645
08-26 04:54:05.237   931  3561 W AlarmManagerService: Unable to set rtc to 1472201645: Invalid argument
,08-26 04:54:05.242  3701  3701 E GCM     : Missing checkin config file
,08-26 04:54:05.243  3701  3701 W GCM     : GCM FAILED TO INITIALIZE - missing checkin
,08-26 04:54:05.247  3701  5659 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,08-26 04:54:05.247  5617  5636 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,08-26 04:54:05.258  3701  3701 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 04:54:05.260  3701  3701 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 04:54:05.265  3701  3701 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 04:54:05.271  3701  5659 E GCM     : Missing checkin config file
,08-26 04:54:05.272  3701  5659 W GCM     : GCM FAILED TO INITIALIZE - missing checkin
,08-26 04:54:05.278  3701  3701 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 04:54:05.288  3963  5631 E GCM     : Failed registration AUTHENTICATION_FAILED alarm=600000
,08-26 04:54:05.297  5642  5642 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,08-26 04:54:05.302  5642  5642 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 04:54:05.312  5617  5636 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-26 04:54:05.317  5642  5642 D SprintDMHelper: simOperator: 
,08-26 04:54:05.317  5642  5642 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 04:54:05.332  3226  5657 D DownloadManager: [8] Starting
,08-26 04:54:05.334   931  3526 I ActivityManager: Start proc 5670:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-26 04:54:05.360  5617  5636 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 04:54:05.382  3701  5688 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,08-26 04:54:05.384  3701  5688 E GCM     : Missing checkin config file
,08-26 04:54:05.385  3701  5688 W GCM     : GCM FAILED TO INITIALIZE - missing checkin
08-26 04:54:05.386  5489  5683 E Gcs.GcmRegService: [243] e.a: Unable to register for GCM
08-26 04:54:05.386  5489  5683 E Gcs.GcmRegService: java.io.IOException: AUTHENTICATION_FAILED
08-26 04:54:05.386  5489  5683 E Gcs.GcmRegService: 	at com.google.android.gms.gcm.e.a(Unknown Source)
08-26 04:54:05.386  5489  5683 E Gcs.GcmRegService: 	at com.google.android.apps.gcs.service.GcmRegistrationService.a(SourceFile:41)
08-26 04:54:05.386  5489  5683 E Gcs.GcmRegService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-26 04:54:05.394  5617  5617 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-26 04:54:05.405  5682  5682 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads1830544752.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1830544752.dex
,08-26 04:54:05.405   931  5594 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 08:54:05 GMT], X-Android-Received-Millis=[1472201645404], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472201645237]}
08-26 04:54:05.405   931  3072 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-26 04:54:05.406   931  3072 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-26 04:54:05.406   931  3072 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-26 04:54:05.407   931  3072 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 04:54:05.413  3226  5657 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 04:54:05.421  3226  5669 D DownloadManager: [9] Starting
,08-26 04:54:05.465  3963  5614 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,08-26 04:54:05.470   931  3071 D WifiService: New client listening to asynchronous messages
,08-26 04:54:05.470  3963  5614 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,08-26 04:54:05.482  5617  5662 W InstanceID/Rpc: Found 10012
,08-26 04:54:05.496  5682  5682 I dex2oat : dex2oat took 92.090ms (threads: 2) arena alloc=180KB java alloc=37KB native alloc=1259KB free=1300KB
,08-26 04:54:05.504  3701  4157 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,08-26 04:54:05.508  3701  4157 E GCM     : Missing checkin config file
,08-26 04:54:05.510  3701  4157 W GCM     : GCM FAILED TO INITIALIZE - missing checkin
,08-26 04:54:05.554  5617  5662 W YouTube : (unknown) Could not register with GCM: 
08-26 04:54:05.554  5617  5662 W YouTube : java.io.IOException: AUTHENTICATION_FAILED
08-26 04:54:05.554  5617  5662 W YouTube : 	at evw.a(Unknown Source)
08-26 04:54:05.554  5617  5662 W YouTube : 	at fza.a(SourceFile:1038)
08-26 04:54:05.554  5617  5662 W YouTube : 	at itm.run(SourceFile:1100)
08-26 04:54:05.554  5617  5662 W YouTube : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 04:54:05.554  5617  5662 W YouTube : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 04:54:05.554  5617  5662 W YouTube : 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-26 04:54:05.554  5617  5662 W YouTube : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 04:54:05.554  5617  5662 W YouTube : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 04:54:05.554  5617  5662 W YouTube : 	at hgy.run(SourceFile:40)
08-26 04:54:05.554  5617  5662 W YouTube : 	at java.lang.Thread.run(Thread.java:818)
,08-26 04:54:05.639   931  3623 I ActivityManager: Start proc 5756:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-26 04:54:05.681  5756  5756 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-26 04:54:05.789   931  3665 I ActivityManager: Start proc 5773:com.google.android.gms.unstable/u0a12 for service com.google.android.gms/.droidguard.DroidGuardService
,08-26 04:54:05.810  3701  5750 E GCM     : Missing checkin config file
08-26 04:54:05.811  3701  5750 W GCM     : GCM FAILED TO INITIALIZE - missing checkin
,08-26 04:54:05.833  5773  5773 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,08-26 04:54:05.868  5773  5773 I MultiDex: VM with version 2.1.0 has multidex support
,08-26 04:54:05.868  5773  5773 I MultiDex: install
08-26 04:54:05.868  5773  5773 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 04:54:05.988  5773  5773 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-26 04:54:06.057  5773  5773 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 04:54:06.086  4300  5754 I Babel   : connection state changed from UNKNOWN to CONNECTED
,08-26 04:54:06.092   931  3665 I ActivityManager: Killing 5140:com.google.android.music:main/u0a59 (adj 15): empty #17
,08-26 04:54:06.206   931   948 I ActivityManager: Start proc 5793:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 04:54:06.237   931  3665 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,08-26 04:54:06.238   931  5594 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
08-26 04:54:06.238   931  5594 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.14,2a00:1450:4001:816::200e
,08-26 04:54:06.267  5793  5793 D AdapterServiceConfig: Adding HeadsetService
,08-26 04:54:06.267  5793  5793 D AdapterServiceConfig: Adding A2dpService
08-26 04:54:06.268  5793  5793 D AdapterServiceConfig: Adding HidService
08-26 04:54:06.268  5793  5793 D AdapterServiceConfig: Adding HealthService
08-26 04:54:06.268  5793  5793 D AdapterServiceConfig: Adding PanService
08-26 04:54:06.268  5793  5793 D AdapterServiceConfig: Adding GattService
08-26 04:54:06.268  5793  5793 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 04:54:06.268  5793  5793 D AdapterServiceConfig: Adding SapService
,08-26 04:54:06.275   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@edfc5ab:true
,08-26 04:54:06.275  5793  5793 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 04:54:06.277  5793  5793 I bt_bluedroid: init
,08-26 04:54:06.277  5793  5807 I BluetoothAdapterState: Entering OffState
,08-26 04:54:06.279  5793  5808 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 04:54:06.279  5793  5808 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 04:54:06.279  5793  5808 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 04:54:06.279  5793  5808 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 04:54:06.280  5793  5793 I bt_bluedroid: get_profile_interface socket
,08-26 04:54:06.280   931  5594 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 08:54:06 GMT], X-Android-Received-Millis=[1472201646279], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472201646240]}
,08-26 04:54:06.280   931  3072 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-26 04:54:06.281   931  3072 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-26 04:54:06.281  5793  5793 I bt_bluedroid: get_profile_interface sdp
08-26 04:54:06.281  5793  5811 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-26 04:54:06.282  5793  5811 D BluetoothAdapterProperties: Name is: Nexus 6P
08-26 04:54:06.283  5793  5806 I bt_bluedroid: config_hci_snoop_log
08-26 04:54:06.284   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-26 04:54:06.288  5793  5807 D BluetoothAdapterState: Current state: OFF, message: 0
08-26 04:54:06.288  5793  5807 D BluetoothAdapterProperties: Setting state to 14
08-26 04:54:06.288  5793  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 04:54:06.289  5793  5807 D BluetoothBondStateMachine: make
,08-26 04:54:06.290  5793  5812 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 04:54:06.292  5793  5807 I BluetoothAdapterState: Entering PendingCommandState
08-26 04:54:06.293  5793  5793 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-26 04:54:06.294  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:54:06.295  5793  5793 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 04:54:06.295  5793  5793 D BtGatt.GattService: Received start request. Starting profile...
08-26 04:54:06.295  5793  5793 D BtGatt.GattService: start()
08-26 04:54:06.295  5793  5793 I bt_bluedroid: get_profile_interface gatt
08-26 04:54:06.295  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:54:06.296  5793  5793 D BtGatt.AdvertiseManager: advertise manager created
08-26 04:54:06.299  5793  5793 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:06.299  5793  5793 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:06.299  5793  5793 V BluetoothAdapterState: isBleTurningOn()=true
08-26 04:54:06.299  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:06.300  5793  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-26 04:54:06.300  5793  5807 I bt_bluedroid: enable
08-26 04:54:06.300  5793  5808 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 04:54:06.300  5793  5808 I bt_hci  : start_up
,08-26 04:54:06.308  5793  5808 I bt_vendor: alloc value 0xf412104d
,08-26 04:54:06.308  5793  5808 I bt_vendor: init
08-26 04:54:06.308  5793  5808 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 04:54:06.308  5793  5808 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 04:54:06.425  5793  5808 D bt_hci  : start_up starting async portion
,08-26 04:54:06.416  5817  5817 W irq/448-msm_hs_: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
08-26 04:54:06.425  5793  5815 I bt_hci  : event_finish_startup
08-26 04:54:06.425  5793  5815 I bt_hci_h4: hal_open
08-26 04:54:06.425  5793  5815 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
08-26 04:54:06.426  5793  5815 I bt_userial_vendor: device fd = 51 open
,08-26 04:54:06.438  5793  5815 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 04:54:06.440  5793  5815 D bt_hwcfg: Chipset BCM4358A3
,08-26 04:54:06.440  5793  5815 D bt_hwcfg: Target name = [BCM4358A3]
08-26 04:54:06.440  5793  5815 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-26 04:54:06.696  5783  5783 W Binder_1: type=1400 audit(0.0:72): avc: denied { read } for name="/" dev="tmpfs" ino=11508 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=dir permissive=0
,08-26 04:54:06.732  5793  5815 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 04:54:06.732  5793  5815 D bt_hwcfg: Settlement delay -- 100 ms
08-26 04:54:06.732  5793  5815 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 04:54:06.815  5773  5801 D NativeLibraryUtils: Install completed successfully. count=17 extracted=0
,08-26 04:54:06.856  5793  5815 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 04:54:06.856  5793  5815 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-26 04:54:06.857  5793  5815 I bt_hwcfg: vendor lib fwcfg completed
08-26 04:54:06.857  5793  5815 I bt_vendor: firmware callback
08-26 04:54:06.857  5793  5815 I bt_hci  : firmware_config_callback
,08-26 04:54:06.862  5793  5821 I bt_btu  : btu_task pending for preload complete event
,08-26 04:54:06.863  5793  5821 I bt_btu_task: Bluetooth chip preload is complete
08-26 04:54:06.863  5793  5821 I bt_btu  : btu_task received preload complete event
,08-26 04:54:06.865  5793  5821 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 04:54:06.865  5793  5821 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 04:54:06.865  5793  5821 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 04:54:06.865  5793  5821 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 04:54:06.865  5793  5821 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 04:54:06.865  5793  5821 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 04:54:06.866  5793  5821 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 04:54:06.866  5793  5821 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 04:54:06.866  5793  5821 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 04:54:06.866  5793  5821 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 04:54:06.866  5793  5821 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 04:54:06.866  5793  5821 I         : BTE_InitTraceLevels -- TRC_GATT
,08-26 04:54:06.866  5793  5821 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 04:54:06.866  5793  5821 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 04:54:06.866  5793  5821 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 04:54:06.867   931  3621 I ActivityManager: Killing 4409:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-26 04:54:06.880   511   511 D WVCdm   : Instantiating CDM.
,08-26 04:54:06.882   511  3105 I WVCdm   : CdmEngine::OpenSession
,08-26 04:54:06.882   511  3105 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-26 04:54:06.895   511  3105 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-26 04:54:06.902   511  3105 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
08-26 04:54:06.902   511  3105 D DrmWidevineDash: Service_Initialize: starts!
08-26 04:54:06.902   511  3105 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-26 04:54:06.902   511  3105 D QSEECOMAPI: : App is not loaded in QSEE
,08-26 04:54:06.936   511  3105 D QSEECOMAPI: : Loaded image: APP id = 5
,08-26 04:54:06.938   511  3105 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-26 04:54:06.938   511  3105 D DrmWidevineDash: Service_Initialize: function time: 35ms (0s 35748750ns)
08-26 04:54:06.939   511  3105 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-26 04:54:06.939   511  3105 D QSAPPSVER: qsapps_get_capabilities: returns 0
,08-26 04:54:06.939   511  3105 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf2e12000
08-26 04:54:06.939   511  3105 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf2e12000
08-26 04:54:06.942  5793  5821 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf409ec99
08-26 04:54:06.942  5793  5821 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf409ec99 
08-26 04:54:06.944   392   398 D DrmLibTime: got the req here! ret=0
08-26 04:54:06.944   392   398 D DrmLibTime: command id, time_cmd_id = 770
08-26 04:54:06.944   392   398 D DrmLibTime: time_getutcsec starts!
,08-26 04:54:06.944   392   398 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-26 04:54:06.944   392   398 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-26 04:54:06.944   392   398 D DrmLibTime: QSEE Time Listener: time_get_modem_time
,08-26 04:54:06.944   392   398 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,08-26 04:54:06.944   392   398 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-26 04:54:06.944   392   398 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-26 04:54:06.944   392   398 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
,08-26 04:54:06.944   392   398 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-26 04:54:06.944   586   611 D QC-time-services: Daemon: Connection accepted:time_genoff
08-26 04:54:06.945   586  5823 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
,08-26 04:54:06.945   586  5823 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-26 04:54:06.945   586  5823 D QC-time-services: offset is: 0 for base: 13
,08-26 04:54:06.946   392   398 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
,08-26 04:54:06.946   392   398 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
,08-26 04:54:06.946   392   398 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1472201646
08-26 04:54:06.946   392   398 D DrmLibTime: time_getutcsec returns 0, sec = 1472201646; nsec = 0
08-26 04:54:06.946   392   398 D DrmLibTime: time_getutcsec finished! 
08-26 04:54:06.946   392   398 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-26 04:54:06.946   392   398 D DrmLibTime: before calling ioctl to read the next time_cmd
08-26 04:54:06.947   586   611 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-26 04:54:06.952  5793  5811 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-26 04:54:06.953  5793  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 04:54:06.954  5793  5811 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-26 04:54:06.955  5793  5811 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-26 04:54:06.957  5793  5811 D BluetoothAdapterProperties: Scan Mode:20
,08-26 04:54:06.957  5793  5811 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 04:54:06.958  5793  5811 D bt_hci  : do_postload posting postload work item
08-26 04:54:06.958  5793  5815 I bt_hci  : event_postload
08-26 04:54:06.958  5793  5815 I bt_vendor: sco_config_cb
08-26 04:54:06.958  5793  5815 I bt_hci  : sco_config_callback postload finished.
,08-26 04:54:06.958  5793  5811 D bt_bte_conf: Device ID record 1 : primary
08-26 04:54:06.959  5793  5811 D bt_bte_conf:   vendorId            = 000f
08-26 04:54:06.959  5793  5811 D bt_bte_conf:   vendorIdSource      = 0001
08-26 04:54:06.959  5793  5811 D bt_bte_conf:   product             = 1200
08-26 04:54:06.959  5793  5811 D bt_bte_conf:   version             = 1436
08-26 04:54:06.959  5793  5811 D bt_bte_conf:   clientExecutableURL = 
08-26 04:54:06.959  5793  5811 D bt_bte_conf:   serviceDescription  = 
08-26 04:54:06.959  5793  5811 D bt_bte_conf:   documentationURL    = 
08-26 04:54:06.959  5793  5811 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 04:54:06.959  5793  5808 D bt_stack_manager: event_start_up_stack finished
08-26 04:54:06.961  5793  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 04:54:06.961  5793  5807 D BluetoothAdapterProperties: Setting state to 15
08-26 04:54:06.961  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:06.961  5793  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-26 04:54:06.962  3701  4199 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-26 04:54:06.965   511  3105 D DrmWidevineDash: OEMCrypto_ION_Malloc: function time: 18ms (0s 18048750ns)
,08-26 04:54:06.966  3701  3701 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-26 04:54:06.966   511  3105 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-26 04:54:06.966   511  3105 D DrmWidevineDash: _oecc01: function time: 64ms (0s 64557448ns)
08-26 04:54:06.967   511  3105 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-26 04:54:06.967  5793  5807 I BluetoothAdapterState: Entering BleOnState
08-26 04:54:06.967  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:06.967  3701  3701 E AuthorizationBluetoothService: Proximity feature is not enabled.
,08-26 04:54:06.967  5617  5824 W MplexGcmListener: GCM error: AUTHENTICATION_FAILED
08-26 04:54:06.968   511  3105 D DrmWidevineDash: hlos api version =  10
08-26 04:54:06.968   511  3105 D DrmWidevineDash: tz api version =  10
08-26 04:54:06.968   511  3105 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,08-26 04:54:06.968   511  3105 D DrmWidevineDash: _oecc22: function time: 1ms (0s 1225052ns)
08-26 04:54:06.968   511  3105 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-26 04:54:06.970  5793  5807 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-26 04:54:06.970  5793  5807 D BluetoothAdapterProperties: Setting state to 11
08-26 04:54:06.970  5793  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-26 04:54:06.974  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:54:06.975  5793  5815 I bt_vendor: low_power_mode_cb
08-26 04:54:06.975  5793  5793 D HeadsetService: Received start request. Starting profile...
,08-26 04:54:06.977  5793  5793 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 04:54:06.977  5793  5793 D HeadsetStateMachine: make
08-26 04:54:06.981  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:54:06.983  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:54:06.987  3701  3701 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 04:54:06.989  3701  3701 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 04:54:06.989  5793  5807 I BluetoothAdapterState: Entering PendingCommandState
,08-26 04:54:06.990  5793  5793 D HeadsetStateMachine: max_hf_connections = 1
08-26 04:54:06.990  5793  5793 I bt_bluedroid: get_profile_interface handsfree
08-26 04:54:06.990  5793  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-26 04:54:06.990  5793  5811 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-26 04:54:06.992  3963  3963 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
08-26 04:54:06.993  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:54:06.994  5793  5793 D A2dpService: Received start request. Starting profile...
08-26 04:54:06.994  5793  5793 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 04:54:06.995  5793  5793 I bt_bluedroid: get_profile_interface avrcp
,08-26 04:54:07.000  5793  5793 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 04:54:07.000  5793  5793 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 04:54:07.000  5793  5793 D A2dpStateMachine: make
08-26 04:54:07.001  5793  5793 I bt_bluedroid: get_profile_interface a2dp
08-26 04:54:07.002  5793  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-26 04:54:07.003  5793  5833 D A2dpStateMachine: Enter Disconnected: -2
08-26 04:54:07.003  5793  5793 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 04:54:07.004  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:54:07.005  5793  5793 D HidService: Received start request. Starting profile...
08-26 04:54:07.005  5793  5793 I bt_bluedroid: get_profile_interface hidhost
08-26 04:54:07.005  5793  5793 D HidService: setHidService(): set to: null
08-26 04:54:07.005  4013  4013 D WearableService: callingUid 10012, callindPid: 4013
08-26 04:54:07.005  5793  5811 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40802d9
08-26 04:54:07.005  5793  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 04:54:07.005  5793  5793 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 04:54:07.006  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:54:07.007  5793  5793 D HealthService: Received start request. Starting profile...
,08-26 04:54:07.009  3731  5832 E MDM     : [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-26 04:54:07.009  5793  5793 I bt_bluedroid: get_profile_interface health
,08-26 04:54:07.011  5793  5793 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 04:54:07.012  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
,08-26 04:54:07.012  5793  5793 D PanService: Received start request. Starting profile...
,08-26 04:54:07.013  5793  5793 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 04:54:07.013  5793  5793 I bt_bluedroid: get_profile_interface pan
,08-26 04:54:07.014  5793  5811 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 04:54:07.015  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
,08-26 04:54:07.017  5793  5793 D BluetoothMapService: Received start request. Starting profile...
08-26 04:54:07.017  5793  5793 D BluetoothMapService: start()
08-26 04:54:07.018   511  3105 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,08-26 04:54:07.018   511  3105 D DrmWidevineDash: _oecc05: function time: 49ms (0s 49935781ns)
08-26 04:54:07.018   511  3105 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,08-26 04:54:07.018   511  3105 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xf330011c
08-26 04:54:07.018   511  3105 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-26 04:54:07.019   511  3105 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,08-26 04:54:07.019   511  3105 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-26 04:54:07.019   511  3105 D DrmWidevineDash: _oecc09: function time: 1ms (0s 1033282ns)
08-26 04:54:07.019   511  3105 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xf648cd38, dataLength=8
08-26 04:54:07.020   511  3105 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
08-26 04:54:07.020   511  3105 D DrmWidevineDash: _oecc06: function time: 0ms (0s 964740ns)
08-26 04:54:07.020  5793  5793 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-26 04:54:07.021   511  3105 W WVCdm   : DeviceFiles::RetrieveHashedFile: /data/mediadrm/IDM1013/L1/cert.bin does not exist
,08-26 04:54:07.021   511  3105 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-26 04:54:07.021  5793  5793 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-26 04:54:07.021  5793  5793 D BluetoothMapAppObserver: createReceiver()
08-26 04:54:07.022   511  3105 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-26 04:54:07.022   511  3105 D DrmWidevineDash: _oecc10: function time: 0ms (0s 864688ns)
08-26 04:54:07.022   511  3105 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-26 04:54:07.022  5793  5793 D BluetoothMapAppObserver: initObservers()
,08-26 04:54:07.022   511  3105 D DrmWidevineDash: Service_Uninitialize: starts!
08-26 04:54:07.022  5793  5793 D BluetoothMapAppObserver: getEnabledAccountItems()
08-26 04:54:07.023   511  3105 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-26 04:54:07.023   511  3105 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 5
08-26 04:54:07.023   511  3105 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-26 04:54:07.023   511  3105 D DrmWidevineDash: Service_Uninitialize: function time: 0ms (0s 818229ns)
08-26 04:54:07.024   511  3105 D DrmWidevineDash: OEMCrypto_ION_Free: function time: 0ms (0s 286406ns)
08-26 04:54:07.024   511  3105 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
08-26 04:54:07.024   511  3105 D DrmWidevineDash: _oecc02: function time: 2ms (0s 2062188ns)
08-26 04:54:07.028  5793  5793 V SapService: SapBinder()
08-26 04:54:07.028  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:54:07.035  5793  5793 D SapService: Received start request. Starting profile...
08-26 04:54:07.035  5793  5793 V SapService: start()
,08-26 04:54:07.036  5793  5793 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:07.036  5793  5793 V BluetoothAdapterState: isTurningOn()=true
08-26 04:54:07.036  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:07.036  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:07.036  5793  5793 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:07.036  5793  5793 V BluetoothAdapterState: isTurningOn()=true
08-26 04:54:07.036  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:07.036  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:07.036  5793  5829 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=2
08-26 04:54:07.037  5793  5793 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:07.037  5793  5793 V BluetoothAdapterState: isTurningOn()=true
08-26 04:54:07.037  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 04:54:07.037  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:07.037  5793  5793 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:07.037  5793  5793 V BluetoothAdapterState: isTurningOn()=true
08-26 04:54:07.037  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:07.037  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:07.037  5793  5793 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:07.037  5793  5793 V BluetoothAdapterState: isTurningOn()=true
08-26 04:54:07.037  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:07.037  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:07.038  5793  5793 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:07.038  5793  5793 V BluetoothAdapterState: isTurningOn()=true
08-26 04:54:07.038  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:07.038  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:07.038  5793  5793 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:07.038  5793  5793 V BluetoothAdapterState: isTurningOn()=true
08-26 04:54:07.038  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:07.038  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:07.039  5793  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 04:54:07.039  5793  5807 D BluetoothAdapterProperties: ScanMode =  20
08-26 04:54:07.039  5793  5807 D BluetoothAdapterProperties: State =  11
08-26 04:54:07.040  5793  5811 D BluetoothAdapterProperties: Scan Mode:21
08-26 04:54:07.040  5793  5811 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 04:54:07.040  5793  5807 D BluetoothAdapterProperties: Setting state to 12
08-26 04:54:07.040  5793  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 04:54:07.040  3603  3620 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 04:54:07.041   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 04:54:07.041  5793  5807 I BluetoothAdapterState: Entering OnState
08-26 04:54:07.042  5529  5541 D BluetoothPan: onBluetoothStateChange on: true
08-26 04:54:07.042   931   931 D BluetoothA2dp: Proxy object connected
08-26 04:54:07.045  5529  5542 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 04:54:07.045  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:07.045  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:07.045  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:07.045  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:07.045  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:07.045  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 04:54:07.045  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 04:54:07.045  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 04:54:07.047  3239  3251 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 04:54:07.047  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 04:54:07.048  5793  5793 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 04:54:07.048  5793  5793 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 04:54:07.049  5529  5542 D BluetoothMap: onBluetoothStateChange: up=true
08-26 04:54:07.050  5793  5793 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 04:54:07.050   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 04:54:07.051  3239  3250 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 04:54:07.051   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 04:54:07.051  5529  5541 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 04:54:07.052  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:07.052  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:07.052  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:07.052  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:07.052  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:07.052  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 04:54:07.052  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 04:54:07.052  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 04:54:07.052  3239  3811 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 04:54:07.054  5793  5793 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 04:54:07.054  5529  5542 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 04:54:07.054  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 04:54:07.055   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 04:54:07.055  3239  3803 D BluetoothPan: onBluetoothStateChange on: true
08-26 04:54:07.055  5793  5793 D ObexServerSockets: Succeed to create listening sockets 
08-26 04:54:07.055  5793  5793 D ObexServerSockets0: startAccept()
08-26 04:54:07.055  5793  5793 D ObexServerSockets0: prepareForNewConnect()
08-26 04:54:07.056  3239  3251 D BluetoothMap: onBluetoothStateChange: up=true
08-26 04:54:07.056  3239  3239 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 04:54:07.056  3239  3239 D PanProfile: Bluetooth service connected
08-26 04:54:07.057  5793  5793 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 04:54:07.057  5793  5793 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-26 04:54:07.057  5793  5842 D ObexServerSockets0: Accepting socket connection...
08-26 04:54:07.058  5793  5841 D ObexServerSockets0: Accepting socket connection...
08-26 04:54:07.058  5529  5541 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 04:54:07.058  3239  3239 D BluetoothInputDevice: Proxy object connected
08-26 04:54:07.058  3239  3239 D HidProfile: Bluetooth service connected
08-26 04:54:07.060  3239  3239 D BluetoothMap: Proxy object connected
08-26 04:54:07.060  3239  3239 D MapProfile: Bluetooth service connected
08-26 04:54:07.060  3239  3239 D BluetoothMap: getConnectedDevices()
08-26 04:54:07.060  3239  3250 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 04:54:07.062  3239  3239 D BluetoothA2dp: Proxy object connected
08-26 04:54:07.062   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 04:54:07.063  5793  5793 D BluetoothMapService: onReceive
08-26 04:54:07.063  5793  5793 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 04:54:07.063  5793  5793 D BluetoothMapService: STATE_ON
08-26 04:54:07.064  5529  5529 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 04:54:07.064  5529  5529 D PanProfile: Bluetooth service connected
08-26 04:54:07.064  5529  5529 D BluetoothA2dp: Proxy object connected
08-26 04:54:07.066  5793  5843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 04:54:07.066  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:07.067  5793  5843 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-26 04:54:07.067  5793  5843 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-26 04:54:07.068  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:07.083  5793  5793 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 04:54:07.083  5793  5793 D ObexServerSockets0: prepareForNewConnect()
,08-26 04:54:07.085  5529  5529 D BluetoothInputDevice: Proxy object connected
,08-26 04:54:07.085  5529  5529 D HidProfile: Bluetooth service connected
08-26 04:54:07.092  5529  5529 D BluetoothMap: Proxy object connected
08-26 04:54:07.093  5529  5529 D MapProfile: Bluetooth service connected
08-26 04:54:07.093  5529  5529 D BluetoothMap: getConnectedDevices()
,08-26 04:54:07.139  5844  5844 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-26 04:54:07.143   931   931 D BluetoothHeadset: Proxy object connected
08-26 04:54:07.143  3239  3250 D BluetoothHeadset: Proxy object connected
08-26 04:54:07.143  3239  3239 D HeadsetProfile: Bluetooth service connected
08-26 04:54:07.144  3603  3628 D BluetoothHeadset: Proxy object connected
08-26 04:54:07.144   931   931 D BluetoothHeadset: Proxy object connected
08-26 04:54:07.144   931   931 D BluetoothHeadset: Proxy object connected
08-26 04:54:07.145  5529  5541 D BluetoothHeadset: Proxy object connected
08-26 04:54:07.151   931   948 D BluetoothHeadset: Proxy object connected
08-26 04:54:07.151  3239  3251 D BluetoothHeadset: Proxy object connected
08-26 04:54:07.152  3239  3239 D HeadsetProfile: Bluetooth service connected
08-26 04:54:07.152   931   948 D BluetoothHeadset: Proxy object connected
,08-26 04:54:07.165  5529  5542 D BluetoothHeadset: Proxy object connected
08-26 04:54:07.165   931   948 D BluetoothHeadset: Proxy object connected
,08-26 04:54:07.197  5529  5529 D HeadsetProfile: Bluetooth service connected
,08-26 04:54:07.198  5529  5529 D HeadsetProfile: Bluetooth service connected
,08-26 04:54:07.205  3963  5838 D LocationInitializer: Restart initialization of location
,08-26 04:54:07.218  3701  4253 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,08-26 04:54:07.222  3701  4253 E GCM     : Missing checkin config file
,08-26 04:54:07.223  3701  4253 W GCM     : GCM FAILED TO INITIALIZE - missing checkin
,08-26 04:54:07.225  5844  5844 I dex2oat : dex2oat took 87.206ms (threads: 2) arena alloc=86KB java alloc=40KB native alloc=1282KB free=1277KB
,08-26 04:54:07.229  3731  3977 W GCoreFlp: No location to return for getLastLocation()
08-26 04:54:07.230  3701  5848 W FusedLocationProvider: location=null
,08-26 04:54:07.233  5773  5783 W System  : ClassLoader referenced unknown path: 
,08-26 04:54:07.237  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 04:54:07.238  5617  5662 W YouTube : (unknown) Could not register with GCM: 
08-26 04:54:07.238  5617  5662 W YouTube : java.io.IOException: AUTHENTICATION_FAILED
08-26 04:54:07.238  5617  5662 W YouTube : 	at evw.a(Unknown Source)
08-26 04:54:07.238  5617  5662 W YouTube : 	at fza.a(SourceFile:1038)
08-26 04:54:07.238  5617  5662 W YouTube : 	at itm.run(SourceFile:1100)
08-26 04:54:07.238  5617  5662 W YouTube : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 04:54:07.238  5617  5662 W YouTube : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 04:54:07.238  5617  5662 W YouTube : 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-26 04:54:07.238  5617  5662 W YouTube : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 04:54:07.238  5617  5662 W YouTube : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 04:54:07.238  5617  5662 W YouTube : 	at hgy.run(SourceFile:40)
08-26 04:54:07.238  5617  5662 W YouTube : 	at java.lang.Thread.run(Thread.java:818)
08-26 04:54:07.245  5529  5529 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 04:54:07.247  5773  5783 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-26 04:54:07.247  5773  5783 I Adreno  : Build Date                       : 10/21/15
08-26 04:54:07.247  5773  5783 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 04:54:07.247  5773  5783 I Adreno  : Local Branch                     : 
08-26 04:54:07.247  5773  5783 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-26 04:54:07.247  5773  5783 I Adreno  : Remote Branch                    : NONE
08-26 04:54:07.247  5773  5783 I Adreno  : Reconstruct Branch               : NOTHING
,08-26 04:54:07.250  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 04:54:07.250  3701  3701 E AuthorizationBluetoothService: Proximity feature is not enabled.
,08-26 04:54:07.256  3239  3239 D BluetoothPbap: Proxy object connected
,08-26 04:54:07.256  3239  3239 D PbapServerProfile: Bluetooth service connected
,08-26 04:54:07.259  5529  5529 D DockEventReceiver: finishStartingService: stopping service
,08-26 04:54:07.260  5529  5529 D BluetoothPbap: Proxy object connected
08-26 04:54:07.260  5529  5529 D PbapServerProfile: Bluetooth service connected
,08-26 04:54:07.263  5793  5856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 04:54:07.278  5793  5862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 04:54:07.279  5617  5858 W MplexGcmListener: GCM error: AUTHENTICATION_FAILED
,08-26 04:54:07.280  5793  5862 I BtOppRfcommListener: Accept thread started.
,08-26 04:54:07.319  5773  5783 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-26 04:54:07.319  5773  5783 I Adreno  : Build Date                       : 10/21/15
08-26 04:54:07.319  5773  5783 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 04:54:07.319  5773  5783 I Adreno  : Local Branch                     : 
08-26 04:54:07.319  5773  5783 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-26 04:54:07.319  5773  5783 I Adreno  : Remote Branch                    : NONE
08-26 04:54:07.319  5773  5783 I Adreno  : Reconstruct Branch               : NOTHING
,08-26 04:54:07.387  3963  5614 I CheckinRequestBuilder: Classify the device as Phone.
,08-26 04:54:07.441  3701  5869 I VacuumService: Vacuum at: now=1472201647441 tag=VacuumService
,08-26 04:54:07.497  3701  5873 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,08-26 04:54:07.523  3701  5870 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-26 04:54:07.525  3701  5870 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 04:54:07.546  3701  5873 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-26 04:54:07.898  3963  5614 I CheckinTask: Sending checkin request (8479 bytes)
,08-26 04:54:08.024  3701  5870 W Uploader:  no longer exists, so no auth token.
,08-26 04:54:08.035  3701  5874 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-26 04:54:08.137  3701  5873 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-26 04:54:08.256  3701  5874 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-26 04:54:08.361  3963  5614 I CheckinResponseProcessor: From server: 993 gservices [full]
,08-26 04:54:08.370  3701  5873 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-26 04:54:08.456  3701  5870 W Uploader:  no longer exists, so no auth token.
,08-26 04:54:08.462  3701  5874 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-26 04:54:08.489   931  5881 I CertBlacklister: Certificate blacklist changed, updating...
,08-26 04:54:08.493   931  5881 I CertBlacklister: Certificate blacklist updated
,08-26 04:54:08.527   931  5882 I CertBlacklister: Certificate blacklist changed, updating...
,08-26 04:54:08.533   931  5882 I CertBlacklister: Certificate blacklist updated
,08-26 04:54:08.593  3701  5873 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-26 04:54:08.723  3701  4530 I GservicesProvider: main update completed
,08-26 04:54:08.748   931   944 I ActivityManager: Start proc 5891:com.google.android.configupdater/u0a5 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,08-26 04:54:08.752  3963  5614 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,08-26 04:54:08.753  3963  5614 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,08-26 04:54:08.777   931  3635 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-26 04:54:08.778  4300  4300 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-26 04:54:08.779  4300  4300 W Babel   : BAM#gBA: invalid account id: -1
08-26 04:54:08.779  4300  4300 W Babel   : BAM#gBA: invalid account id: -1
08-26 04:54:08.779  4300  4300 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-26 04:54:08.785  5891  5891 W System  : ClassLoader referenced unknown path: /system/priv-app/ConfigUpdater/lib/arm64
,08-26 04:54:08.811  5891  5906 I ConfigUpdater: Update started
,08-26 04:54:08.851  3963  5614 I CheckinRequestBuilder: Classify the device as Phone.
,08-26 04:54:08.872  3963  5614 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-26 04:54:08.879  5891  5891 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION intent_firewall: null null
,08-26 04:54:08.891  3963  5614 I CheckinService: Checking schedule, now: 1472201648891 next: 1472241873872
,08-26 04:54:08.891  3963  5614 I CheckinService: active receiver: disabled
,08-26 04:54:08.898  5891  5915 I ConfigUpdater: Update started
,08-26 04:54:08.943  3226  5910 D DownloadManager: [10] Starting
,08-26 04:54:08.947  5891  5891 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION apn_db: null null
,08-26 04:54:08.952  5891  5891 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION tzdata: null null
,08-26 04:54:08.955  5891  5891 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION selinux: null null
,08-26 04:54:08.958  5891  5891 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION carrier_provisioning_urls: null null
,08-26 04:54:09.017   931  3635 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,08-26 04:54:09.042  3963  5932 I CheckinService: Checking schedule, now: 1472201649042 next: 1472241873872
,08-26 04:54:09.042  3963  5932 I CheckinService: active receiver: disabled
08-26 04:54:09.042  3963  3963 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,08-26 04:54:09.047  3963  3963 D SystemUpdateService: onCreate
,08-26 04:54:09.050  3963  3963 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 04:54:09.061  3963  5935 I SystemUpdateService: active receiver: enabled
,08-26 04:54:09.061  3963  3963 D OcrModelManager: Updating downloaded model state (gservices changed)
,08-26 04:54:09.073  3963  3963 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
,08-26 04:54:09.073  3963  3963 I OcrUtils: Updating ocr activity enabled=false
,08-26 04:54:09.080  3701  3701 I GCM     : GCM config loaded
,08-26 04:54:09.083  3963  5935 I SystemUpdateService: cancelUpdate (update URL has changed)
,08-26 04:54:09.084  3701  4262 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,08-26 04:54:09.089   931   954 I ActivityManager: Force stopping com.google.android.apps.maps appid=10058 user=0: pkg changed
,08-26 04:54:09.090   931   954 I ActivityManager: Killing 5543:com.google.android.apps.maps/u0a58 (adj 9): stop com.google.android.apps.maps
,08-26 04:54:09.129  3226  5941 D DownloadManager: [11] Starting
,08-26 04:54:09.152   931  3030 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 04:54:09.153   931   954 I ActivityManager: Force stopping com.google.android.youtube appid=10075 user=0: pkg changed
08-26 04:54:09.153   931   954 I ActivityManager: Killing 5617:com.google.android.youtube/u0a75 (adj 9): stop com.google.android.youtube
,08-26 04:54:09.183  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 04:54:09.183  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:54:09.185   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 04:54:09.202   931   941 W ActivityManager: Spurious death for ProcessRecord{723f8e9 0:com.google.android.apps.maps/u0a58}, curProc for 5543: null
,08-26 04:54:09.205   931  3030 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 04:54:09.208   931   954 I ActivityManager: Force stopping com.google.android.apps.walletnfcrel appid=10073 user=0: pkg changed
,08-26 04:54:09.208   931   954 I ActivityManager: Killing 4978:com.google.android.apps.walletnfcrel/u0a73 (adj 11): stop com.google.android.apps.walletnfcrel
,08-26 04:54:09.262  3731  3731 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,08-26 04:54:09.263  3226  5941 D DownloadManager: [11] Finished with status SUCCESS
,08-26 04:54:09.266   931  3623 W ActivityManager: Spurious death for ProcessRecord{20908e3 0:com.google.android.apps.walletnfcrel/u0a73}, curProc for 4978: null
,08-26 04:54:09.268   931   954 I ActivityManager: Force stopping com.google.android.videos appid=10072 user=0: pkg changed
,08-26 04:54:09.269  3590  3590 D RegisteredServicesCache: Service removed: ComponentInfo{com.google.android.apps.walletnfcrel/com.google.commerce.tapandpay.android.hce.service.ValuableApduService}
08-26 04:54:09.270   931   954 I ActivityManager: Force stopping com.android.vending appid=10022 user=0: pkg changed
08-26 04:54:09.270   931   954 I ActivityManager: Killing 4552:com.android.vending/u0a22 (adj 11): stop com.android.vending
,08-26 04:54:09.310   931  5943 W ActivityManager: Spurious death for ProcessRecord{679d0af 0:com.android.vending/u0a22}, curProc for 4552: null
,08-26 04:54:09.321   931  3030 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 04:54:09.323   931  3030 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 04:54:09.324   931  3500 W ActivityManager: Spurious death for ProcessRecord{6165624 0:com.google.android.youtube/u0a75}, curProc for 5617: null
08-26 04:54:09.325  3963  5935 I SystemUpdateService: showing system update notification
,08-26 04:54:09.325   931  3030 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 04:54:09.336  3731  3731 I GCoreUlr: DispatchingService.onCreate()
,08-26 04:54:09.353  3963  5935 V SystemUpdateService: retry (wakeup: false) in 3599705 ms
,08-26 04:54:09.380   931  5947 I sensors : activate
,08-26 04:54:09.385   931  3635 I sensors : batch
,08-26 04:54:09.385   931  3635 I sensors : activate
08-26 04:54:09.387   931  2902 I hubconnection: sensorhub said: 'activate 21 enable:0'
,08-26 04:54:09.390   931  2902 I hubconnection: sensorhub said: 'batch 6 flags:0, sampling_rate_Hz:5.00, max_report_latency_us:0'
08-26 04:54:09.390   931  2902 I hubconnection: sensorhub said: 'activate 6 enable:1'
,08-26 04:54:09.454   511  5956 E WVMExtractor: Failed to open libwvm.so: dlopen failed: library "libwvm.so" not found
,08-26 04:54:09.471   511  5955 D NuPlayerDriver: notifyListener_l(0xf30ef240), (1, 0, 0)
08-26 04:54:09.471  3239  5954 D MediaPlayer: setSubtitleAnchor in MediaPlayer
,08-26 04:54:09.477   931  5947 I MediaFocusControl:  AudioFocus  requestAudioFocus() from android.media.AudioManager@595e95 req=3flags=0x0
,08-26 04:54:09.479   511  3106 D NuPlayerDriver: start(0xf30ef240), state is 4, eos is 0
,08-26 04:54:09.479   511  5955 I GenericSource: start
,08-26 04:54:09.487   511  5962 E OMXNodeInstance: setConfig(2d:google.vorbis.decoder, ConfigPriority(0x6f800002)) ERROR: Undefined(0x80001001)
,08-26 04:54:09.487   511  5962 I ACodec  : codec does not support config priority (err -2147483648)
,08-26 04:54:09.488   511  5962 I MediaCodec: MediaCodec will operate in async mode
,08-26 04:54:09.491  3731  5957 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,08-26 04:54:09.505   511  3082 D audio_hw_primary: out_set_parameters: enter: usecase(1: low-latency-playback) kvpairs: routing=2
,08-26 04:54:09.506   511  5955 D NuPlayerDriver: notifyListener_l(0xf30ef240), (6, 0, 0)
,08-26 04:54:09.518   511  3082 D audio_hw_primary: select_devices: out_snd_device(2: speaker) in_snd_device(0: none)
,08-26 04:54:09.518   511  3082 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(2) acdb_id(15)
08-26 04:54:09.519   511  3082 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 1
,08-26 04:54:09.533  3731  5957 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: (no Google accounts)
,08-26 04:54:09.536   511  3082 D audio_hw_primary: enable_snd_device: snd_device(2: speaker)
,08-26 04:54:09.538  3731  5957 I GCoreUlr: Unbound from all location providers
08-26 04:54:09.538   511  3082 D audio_hw_primary: enable_audio_route: apply and update mixer path: low-latency-playback speaker
,08-26 04:54:09.546  3731  3731 I GCoreUlr: DispatchingService.onDestroy()
,08-26 04:54:09.546  3731  3731 I GCoreUlr: Stopping handler for UlrDispSvcFast
,08-26 04:54:09.548  3731  3731 I GCoreUlr: Unbound from all location providers
,08-26 04:54:09.554  3963  3963 D SystemUpdateService: onDestroy
,08-26 04:54:09.578  3963  4648 E Icing   : Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,08-26 04:54:09.596   931  3665 I sensors : activate
,08-26 04:54:09.597   931  3635 I sensors : batch
,08-26 04:54:09.598   931  3635 I sensors : activate
,08-26 04:54:09.599   931   951 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,08-26 04:54:09.599   931   951 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@11c181)
,08-26 04:54:09.600   931  2902 I hubconnection: sensorhub said: 'activate 6 enable:0'
08-26 04:54:09.600   931   949 I DisplayManagerService: Display device changed state: "Built-in Screen", DOZE
08-26 04:54:09.600   381   381 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa27c3c00
,08-26 04:54:09.601   381   381 D qdhwcomposer: hwc_setPowerMode: Setting mode 1 on display: 0
,08-26 04:54:09.586  5967  5967 W mdss_fb0: type=1400 audit(0.0:73): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
08-26 04:54:09.604   931  3236 V KeyguardServiceDelegate: **** SHOWN CALLED ****
08-26 04:54:09.606   931  2902 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
08-26 04:54:09.607   931  2902 I hubconnection: sensorhub said: 'activate 21 enable:1'
,08-26 04:54:09.616   511  3082 D AudioFlinger: mixer(0xf4300000) throttle end: throttle time(6)
,08-26 04:54:09.628  3239  3239 W PathParser: Points are too far apart 4.030360828967057
08-26 04:54:09.628  3239  3239 W PathParser: Points are too far apart 4.030360538880159
,08-26 04:54:09.646  3226  5910 D DownloadManager: [10] Finished with status SUCCESS
,08-26 04:54:09.664   931   951 I DisplayPowerController: Unblocked screen on after 65 ms
,08-26 04:54:09.666   931   951 V KeyguardServiceDelegate: onScreenTurnedOn()
,08-26 04:54:09.682  4666  5973 I GservicesUpdateTask: Updating Gservices keys
,08-26 04:54:09.698  3963  3963 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 04:54:09.703  3963  3963 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-26 04:54:09.705  3701  4355 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-26 04:54:09.705  3701  4355 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,08-26 04:54:09.728  3963  3963 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-26 04:54:09.730  3963  3963 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-26 04:54:09.737  3963  5979 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.apps.maps
,08-26 04:54:09.753  3963  5982 I PeopleContactsSync: CP2 sync disabled
,08-26 04:54:09.755  4666  5981 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.apps.maps, CONTACTS=MAYBE
,08-26 04:54:09.770  3963  5983 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.youtube
,08-26 04:54:09.776   381   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 2
,08-26 04:54:09.766  5985  5985 W irq/504-synapti: type=1400 audit(0.0:74): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-26 04:54:09.779   381   381 D qdhwcomposer: hwc_setPowerMode: Done setting mode 1 on display 0
,08-26 04:54:09.780   931  3182 D SurfaceControl: Excessive delay in setPowerMode(): 179ms
08-26 04:54:09.801  3963  5986 I PeopleContactsSync: CP2 sync disabled
,08-26 04:54:09.804  3963  5983 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.apps.walletnfcrel
,08-26 04:54:09.810  3963  5988 I PeopleContactsSync: CP2 sync disabled
,08-26 04:54:09.817  3963  4648 I Icing   : doRemovePackageData com.google.android.apps.walletnfcrel
,08-26 04:54:09.819  3963  5989 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,08-26 04:54:09.834  3963  5991 I PeopleContactsSync: CP2 sync disabled
,08-26 04:54:09.861   931   941 I ActivityManager: Start proc 5992:com.android.vending/u0a22 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,08-26 04:54:09.867  4666  5981 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 110 ms] updated apps [took 110 ms] 
,08-26 04:54:09.870  4666  5981 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.youtube, CONTACTS=MAYBE
,08-26 04:54:09.939  4666  5981 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 70 ms] updated apps [took 70 ms] 
,08-26 04:54:09.941  4666  5981 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.apps.walletnfcrel, CONTACTS=MAYBE
,08-26 04:54:09.943  5992  5992 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm64
,08-26 04:54:10.064  4666  5981 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 122 ms] updated apps [took 122 ms] 
,08-26 04:54:10.065  4666  5981 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,08-26 04:54:10.127  4666  5981 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 62 ms] updated apps [took 62 ms] 
,08-26 04:54:10.136  3701  4355 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-26 04:54:10.170  5992  5992 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 04:54:10.185   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 04:54:10.278  5992  5992 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-26 04:54:10.290  5992  5992 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 04:54:10.302   511  5961 I NuPlayerDecoder: [audio] saw output EOS
,08-26 04:54:10.383  4666  5973 I GStaticConfiguration: #getNewConfigurationUrl [pref=2013_10_04_22_22_03, gservice=2016_07_22_15_03_49]
,08-26 04:54:10.447  5992  5992 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 04:54:10.450  5992  5992 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 04:54:10.463  5992  5992 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 04:54:10.470  5992  5992 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 04:54:10.496  5992  5992 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 04:54:10.497  5992  5992 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 04:54:10.500  5992  5992 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 04:54:10.524  5992  5992 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 04:54:10.527  5992  5992 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 04:54:10.567  5992  5992 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 04:54:10.571  5992  5992 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 04:54:10.571  5992  5992 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-26 04:54:10.587  5992  5992 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 04:54:10.630  3963  6029 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.android.vending
,08-26 04:54:10.638  3963  6032 I PeopleContactsSync: CP2 sync disabled
,08-26 04:54:10.689  4666  6031 I UpdateIcingCorporaServi: Updating corpora: APPS=com.android.vending, CONTACTS=MAYBE
,08-26 04:54:10.709  5992  6027 D Ads     : Skipping gmscore version check
,08-26 04:54:10.790  4666  6031 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 100 ms] updated apps [took 100 ms] 
,08-26 04:54:10.847  3963  3963 V AuthZen : Received broadcast action: com.google.android.gms.gcm.REGISTERED
,08-26 04:54:10.852  3963  6038 V AuthZen : Handling intent: com.google.android.gms.gcm.REGISTERED
,08-26 04:54:10.852  3963  6038 D AuthZenEventHandler: Handling event: com.google.android.gms.gcm.REGISTERED
,08-26 04:54:10.866   511  5955 D NuPlayerDriver: notifyListener_l(0xf30ef240), (2, 0, 0)
,08-26 04:54:10.867   931  5943 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManager@595e95
,08-26 04:54:10.875  5992  6027 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186448
,08-26 04:54:10.938  5992  5992 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 04:54:10.939  5992  5992 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 04:54:10.952  5992  5992 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-26 04:54:10.973  5992  5992 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-26 04:54:10.999  3731  3731 I GCoreUlr: GCM registration ID changed
,08-26 04:54:11.007  3963  3963 E MDM     : [1] SitrepService.a: No Google accounts; deferring server state update.
,08-26 04:54:11.065  3963  4648 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
,08-26 04:54:11.097   931  3071 D WifiService: New client listening to asynchronous messages
,08-26 04:54:11.142  3963  4648 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
,08-26 04:54:11.146   511  3082 D audio_hw_primary: disable_audio_route: reset and update mixer path: low-latency-playback speaker
,08-26 04:54:11.147   511  3082 D audio_hw_primary: disable_snd_device: snd_device(2: speaker)
,08-26 04:54:11.155   511  3082 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 0
,08-26 04:54:11.169  3226  6043 D DownloadManager: [12] Starting
,08-26 04:54:11.185  3226  5941 D DownloadManager: [13] Starting
,08-26 04:54:11.186   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 04:54:11.348  3226  6043 D DownloadManager: [12] Finished with status SUCCESS
,08-26 04:54:11.416  5891  6060 I ConfigUpdater: Update downloaded, starting installation
,08-26 04:54:11.463  5891  6060 I ConfigUpdater: doneInstall
,08-26 04:54:11.470   931  6062 I ConfigUpdateInstallReceiver: Couldn't find current metadata, assuming first update
,08-26 04:54:11.470   931  6062 I ConfigUpdateInstallReceiver: Failed to read current content, assuming first update!
08-26 04:54:11.470   931  6062 I ConfigUpdateInstallReceiver: Found new update, installing...
,08-26 04:54:11.482   931  6062 I ConfigUpdateInstallReceiver: Installation successful
,08-26 04:54:11.532  3226  5613 V DownloadManager: Deleting /data/user/0/com.android.providers.downloads/cache/06012016-sms-blacklist-metadata.txt via provider delete
,08-26 04:54:11.543  3226  5941 D DownloadManager: [13] Finished with status SUCCESS
,08-26 04:54:11.590  3226  5613 V DownloadManager: Deleting /data/user/0/com.android.providers.downloads/cache/06012016-sms-blacklist.txt via provider delete
08-26 04:54:11.601  5891  6063 I ConfigUpdater: Update downloaded, starting installation
08-26 04:54:11.608  5891  6063 I ConfigUpdater: doneInstall
08-26 04:54:11.614   931  6064 I ConfigUpdateInstallReceiver: Couldn't find current metadata, assuming first update
08-26 04:54:11.614   931  6064 I ConfigUpdateInstallReceiver: Failed to read current content, assuming first update!
08-26 04:54:11.614   931  6064 I ConfigUpdateInstallReceiver: Found new update, installing...
08-26 04:54:11.627   931  6064 I ConfigUpdateInstallReceiver: Installation successful
,08-26 04:54:11.644  3226  5910 D DownloadManager: [13] Already finished; skipping
,08-26 04:54:11.646  3226  5613 V DownloadManager: Deleting /data/user/0/com.android.providers.downloads/cache/08202014-metadata.txt via provider delete
,08-26 04:54:11.659  3226  5613 V DownloadManager: Deleting /data/user/0/com.android.providers.downloads/cache/08202014-pins.txt via provider delete
,08-26 04:54:12.186   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 04:54:12.263  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 04:54:12.263  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a7d8e11 added. We now have 6 listener(s)
08-26 04:54:12.263  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 04:54:12.266  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 04:54:12.266  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ae4db76 added. We now have 7 listener(s)
08-26 04:54:12.266  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 04:54:12.268  5412  5458 I System.out: IsBluetoothEnabled
,08-26 04:54:12.271  5793  5807 D BluetoothAdapterState: Current state: ON, message: 23
,08-26 04:54:12.272  5793  5807 D BluetoothAdapterProperties: Setting state to 13
08-26 04:54:12.272  5793  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 04:54:12.272  5793  5807 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 04:54:12.273  5793  5807 I BluetoothAdapterState: Entering PendingCommandState
,08-26 04:54:12.274  5793  5793 D BluetoothMapService: onReceive
08-26 04:54:12.275  5793  5793 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 04:54:12.275  5793  5793 D BluetoothMapService: STATE_TURNING_OFF
08-26 04:54:12.275  5793  5793 D BluetoothMapService: MAP Service closeService in
08-26 04:54:12.275  5793  5793 D BluetoothMapMasInstance0: MAP Service shutdown
,08-26 04:54:12.275  5793  5793 D ObexServerSockets0: shutdown(block = true)
08-26 04:54:12.276  5793  5793 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 04:54:12.276  5793  5841 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 04:54:12.276  5793  5793 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 04:54:12.277  5793  5825 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 04:54:12.277  5793  5842 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 04:54:12.279  5793  5811 D BluetoothAdapterProperties: Scan Mode:20
08-26 04:54:12.280  5412  5412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:54:12.280  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:12.280  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:12.280  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:12.280  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:12.280  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 04:54:12.280  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 04:54:12.280  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 04:54:12.280  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 04:54:12.280  5793  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 04:54:12.281  5793  5793 I BtOppRfcommListener: stopping Accept Thread
,08-26 04:54:12.281  5793  5862 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 04:54:12.281  5412  5412 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:54:12.281  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 04:54:12.281  5793  5862 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 04:54:12.283  5529  5529 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 04:54:12.286  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:54:12.290  5793  5793 D HeadsetService: Received stop request...Stopping profile...
,08-26 04:54:12.290  5529  5529 D DockEventReceiver: finishStartingService: stopping service
,08-26 04:54:12.293   931   931 D BluetoothHeadset: Proxy object disconnected
08-26 04:54:12.293  3239  3811 D BluetoothHeadset: Proxy object disconnected
08-26 04:54:12.295  3603  3869 D BluetoothHeadset: Proxy object disconnected
08-26 04:54:12.296   931   931 D BluetoothHeadset: Proxy object disconnected
08-26 04:54:12.296   931   931 D BluetoothHeadset: Proxy object disconnected
08-26 04:54:12.296  5793  5793 D A2dpService: Received stop request...Stopping profile...
08-26 04:54:12.296  5529  5542 D BluetoothHeadset: Proxy object disconnected
08-26 04:54:12.296  5793  5833 D A2dpStateMachine: Exit Disconnected: -1
08-26 04:54:12.297  5529  5529 D HeadsetProfile: Bluetooth service disconnected
08-26 04:54:12.298  5529  5529 D BluetoothA2dp: Proxy object disconnected
,08-26 04:54:12.298  5793  5793 D HidService: Received stop request...Stopping profile...
08-26 04:54:12.298  5793  5793 D HidService: Stopping Bluetooth HidService
08-26 04:54:12.299  5529  5529 D BluetoothInputDevice: Proxy object disconnected
,08-26 04:54:12.299  5529  5529 D HidProfile: Bluetooth service disconnected
08-26 04:54:12.300  5793  5793 D HealthService: Received stop request...Stopping profile...
08-26 04:54:12.301   931   931 D BluetoothA2dp: Proxy object disconnected
08-26 04:54:12.302  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 04:54:12.302  3239  3239 D HeadsetProfile: Bluetooth service disconnected
08-26 04:54:12.303  3239  3239 D BluetoothA2dp: Proxy object disconnected
,08-26 04:54:12.303  3239  3239 D BluetoothInputDevice: Proxy object disconnected
08-26 04:54:12.304  3239  3239 D HidProfile: Bluetooth service disconnected
,08-26 04:54:12.304  5793  5793 D PanService: Received stop request...Stopping profile...
,08-26 04:54:12.305  3239  3239 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 04:54:12.305  3239  3239 D PanProfile: Bluetooth service disconnected
08-26 04:54:12.305  5529  5529 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 04:54:12.305  5793  5793 V BluetoothAdapterState: isTurningOff()=true
08-26 04:54:12.306  5529  5529 D PanProfile: Bluetooth service disconnected
08-26 04:54:12.306  5793  5793 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:12.306  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:12.306  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:12.306  5793  5793 D BluetoothMapService: Received stop request...Stopping profile...
08-26 04:54:12.306  5793  5793 D BluetoothMapService: stop()
08-26 04:54:12.307  5793  5793 D BluetoothMapAppObserver: deinitObservers()
08-26 04:54:12.307  5793  5793 D BluetoothMapAppObserver: removeReceiver()
08-26 04:54:12.308  5529  5529 D BluetoothMap: Proxy object disconnected
08-26 04:54:12.308  3239  3239 D BluetoothMap: Proxy object disconnected
08-26 04:54:12.308  3239  3239 D MapProfile: Bluetooth service disconnected
08-26 04:54:12.308  5529  5529 D MapProfile: Bluetooth service disconnected
08-26 04:54:12.309  5793  5793 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 04:54:12.309  5793  5793 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 04:54:12.309  5793  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 04:54:12.309  5793  5821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 04:54:12.309  5793  5821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 04:54:12.309  5793  5821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 04:54:12.310  5793  5811 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-26 04:54:12.310  5793  5793 D SapService: Received stop request...Stopping profile...
08-26 04:54:12.310  5793  5793 V SapService: stop()
,08-26 04:54:12.313  5793  5793 V BluetoothAdapterState: isTurningOff()=true
,08-26 04:54:12.313  5793  5793 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:12.313  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:12.313  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:12.314  5793  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 04:54:12.314  5793  5821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 04:54:12.314  5793  5793 V BluetoothAdapterState: isTurningOff()=true
,08-26 04:54:12.314  5793  5793 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:12.314  5793  5821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 04:54:12.314  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:12.315  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:12.315  5793  5821 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 04:54:12.315  5793  5821 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 04:54:12.315  5793  5821 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 04:54:12.315  5793  5821 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 04:54:12.315  5793  5793 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 04:54:12.315  5793  5793 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 04:54:12.315  5793  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 04:54:12.316  3239  3239 D BluetoothPbap: Proxy object disconnected
08-26 04:54:12.316  3239  3239 D PbapServerProfile: Bluetooth service disconnected
08-26 04:54:12.316  5529  5529 D BluetoothPbap: Proxy object disconnected
08-26 04:54:12.316  5529  5529 D PbapServerProfile: Bluetooth service disconnected
08-26 04:54:12.317  5793  5793 V BluetoothAdapterState: isTurningOff()=true
08-26 04:54:12.317  5793  5793 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:12.317  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:12.317  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:12.317  5793  5793 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 04:54:12.317  5793  5811 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 04:54:12.317  5793  5793 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 04:54:12.318  5793  5793 V BluetoothAdapterState: isTurningOff()=true
08-26 04:54:12.318  5793  5793 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:12.318  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:12.318  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:12.318  5793  5793 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 04:54:12.318  5793  5793 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 04:54:12.319  5793  5793 D BluetoothMapService: MAP Service closeService in
08-26 04:54:12.319  5793  5793 V BluetoothAdapterState: isTurningOff()=true
08-26 04:54:12.320  5793  5793 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:12.320  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:12.320  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:12.320  5793  5793 D BluetoothMapService: cleanup()
08-26 04:54:12.320  5793  5793 D BluetoothMapService: MAP Service closeService in
08-26 04:54:12.320  5793  5793 V BluetoothAdapterState: isTurningOff()=true
08-26 04:54:12.320  5793  5793 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:12.320  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:12.320  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:12.320  5793  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 04:54:12.320  5793  5807 D BluetoothAdapterProperties: Setting state to 15
08-26 04:54:12.320  5793  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 04:54:12.321  5793  5807 I BluetoothAdapterState: Entering BleOnState
08-26 04:54:12.331   931  5947 I ActivityManager: Start proc 6069:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-26 04:54:12.332  3603  3620 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 04:54:12.332   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 04:54:12.333  5529  5541 D BluetoothPan: onBluetoothStateChange on: false
08-26 04:54:12.334  5529  5542 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 04:54:12.334  3239  3811 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 04:54:12.335  5529  5840 D BluetoothMap: onBluetoothStateChange: up=false
08-26 04:54:12.336   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 04:54:12.336  3239  3251 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 04:54:12.337   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 04:54:12.337  5529  5541 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 04:54:12.337  3239  3803 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 04:54:12.338  5529  5542 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 04:54:12.338   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 04:54:12.338  3239  3250 D BluetoothPan: onBluetoothStateChange on: false
08-26 04:54:12.339  3239  3811 D BluetoothMap: onBluetoothStateChange: up=false
08-26 04:54:12.340  5529  5840 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 04:54:12.340  3239  3251 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 04:54:12.342  5793  5807 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 04:54:12.342  5793  5807 D BluetoothAdapterProperties: Setting state to 16
08-26 04:54:12.342  5793  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 04:54:12.343  5793  5807 D BluetoothAdapterProperties: onBleDisable
08-26 04:54:12.344  5793  5807 I BluetoothAdapterState: Entering PendingCommandState
08-26 04:54:12.344  5793  5808 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 04:54:12.346  5793  5821 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 04:54:12.346  5793  5821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 04:54:12.347  5793  5811 D BluetoothAdapterProperties: Scan Mode:20
08-26 04:54:12.348  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:12.351  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:12.373  6069  6069 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,08-26 04:54:12.552  5793  5811 I bt_hci  : shut_down
,08-26 04:54:12.557  5793  5815 D bt_hwcfg: hw_epilog_process
,08-26 04:54:12.557  5793  5815 I bt_vendor: low_power_mode_cb
,08-26 04:54:12.559  5793  5815 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-26 04:54:12.559  5793  5815 I bt_vendor: epilog_cb
08-26 04:54:12.559  5793  5815 I bt_hci  : epilog_finished_callback
,08-26 04:54:12.562  5793  5811 I bt_hci_h4: hal_close
,08-26 04:54:12.562  5793  5811 I bt_userial_vendor: device fd = 51 close
,08-26 04:54:12.571  6069  6069 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 04:54:12.571  6069  6069 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 04:54:12.571  6069  6069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 04:54:12.590  5529  5529 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 04:54:12.595  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 04:54:12.595  5529  5529 D DockEventReceiver: finishStartingService: stopping service
,08-26 04:54:12.596   931  5948 I ActivityManager: Killing 5285:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-26 04:54:12.667  5793  5808 D bt_stack_manager: event_shut_down_stack finished.
,08-26 04:54:12.667  5793  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 04:54:12.669  5793  5793 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 04:54:12.669  5793  5807 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 04:54:12.669  5793  5793 D BtGatt.GattService: Received stop request...Stopping profile...
,08-26 04:54:12.669  5793  5793 D BtGatt.GattService: stop()
08-26 04:54:12.669  5793  5793 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 04:54:12.671  5793  5793 V BluetoothAdapterState: isTurningOff()=false
,08-26 04:54:12.671  5793  5793 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:12.671  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:12.671  5793  5793 V BluetoothAdapterState: isBleTurningOff()=true
08-26 04:54:12.671  5793  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-26 04:54:12.671  5793  5807 D BluetoothAdapterProperties: Setting state to 10
08-26 04:54:12.671  5793  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 04:54:12.672  5793  5807 I BluetoothAdapterState: Entering OffState
08-26 04:54:12.672   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-26 04:54:12.680  5793  5793 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 04:54:12.680  5793  5793 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 04:54:12.680  5793  5793 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 04:54:12.681  5793  5808 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-26 04:54:12.682  5793  5808 D bt_stack_manager: event_clean_up_stack finished.
,08-26 04:54:12.684  5793  5793 I art     : System.exit called, status: 0
08-26 04:54:12.684  5793  5793 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 04:54:12.726  6069  6098 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 04:54:12.733   931  5947 I ActivityManager: Process com.android.bluetooth (pid 5793) has died
,08-26 04:54:12.818  6069  6091 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 04:54:12.835   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@87c071f:true
,08-26 04:54:12.995   931  3072 D ConnectivityService: handlePromptUnvalidated 100
,08-26 04:54:13.187   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 04:54:13.269  3701  6105 V NQFileLogger: [175] e.a: about to write to file
,08-26 04:54:13.274  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 04:54:13.274  5412  5458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:13.274  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:13.274  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:13.274  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:13.274  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 04:54:13.274  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 04:54:13.274  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 04:54:13.274  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 04:54:13.274  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 04:54:13.274  5412  5458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 04:54:13.275  3701  6105 V ProcessReports: [175] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,08-26 04:54:13.289   931   948 I ActivityManager: Start proc 6108:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 04:54:13.343  6108  6108 D AdapterServiceConfig: Adding HeadsetService
,08-26 04:54:13.343  6108  6108 D AdapterServiceConfig: Adding A2dpService
08-26 04:54:13.343  6108  6108 D AdapterServiceConfig: Adding HidService
08-26 04:54:13.344  6108  6108 D AdapterServiceConfig: Adding HealthService
08-26 04:54:13.344  6108  6108 D AdapterServiceConfig: Adding PanService
08-26 04:54:13.344  6108  6108 D AdapterServiceConfig: Adding GattService
08-26 04:54:13.344  6108  6108 D AdapterServiceConfig: Adding BluetoothMapService
08-26 04:54:13.344  6108  6108 D AdapterServiceConfig: Adding SapService
,08-26 04:54:13.352   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28e08a5:true
,08-26 04:54:13.353  6108  6108 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 04:54:13.355  6108  6108 I bt_bluedroid: init
,08-26 04:54:13.356  6108  6120 I BluetoothAdapterState: Entering OffState
,08-26 04:54:13.357  6108  6121 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 04:54:13.358  6108  6121 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 04:54:13.358  6108  6121 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 04:54:13.358  6108  6121 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 04:54:13.358  6108  6108 I bt_bluedroid: get_profile_interface socket
,08-26 04:54:13.360  6108  6124 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-26 04:54:13.360  6108  6108 I bt_bluedroid: get_profile_interface sdp
,08-26 04:54:13.361  6108  6124 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-26 04:54:13.362  6108  6119 I bt_bluedroid: config_hci_snoop_log
,08-26 04:54:13.363   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 04:54:13.367  6108  6120 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 04:54:13.367  6108  6120 D BluetoothAdapterProperties: Setting state to 14
08-26 04:54:13.368  6108  6120 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-26 04:54:13.369  6108  6120 D BluetoothBondStateMachine: make
08-26 04:54:13.370  6108  6125 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 04:54:13.372  6108  6120 I BluetoothAdapterState: Entering PendingCommandState
,08-26 04:54:13.373  6108  6108 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 04:54:13.376  6108  6108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
,08-26 04:54:13.376  6108  6108 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 04:54:13.377  6108  6108 D BtGatt.GattService: Received start request. Starting profile...
08-26 04:54:13.377  6108  6108 D BtGatt.GattService: start()
08-26 04:54:13.377  6108  6108 I bt_bluedroid: get_profile_interface gatt
08-26 04:54:13.378  6108  6108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:54:13.378  6108  6108 D BtGatt.AdvertiseManager: advertise manager created
,08-26 04:54:13.382  6108  6108 V BluetoothAdapterState: isTurningOff()=false
,08-26 04:54:13.382  6108  6108 V BluetoothAdapterState: isTurningOn()=false
08-26 04:54:13.382  6108  6108 V BluetoothAdapterState: isBleTurningOn()=true
08-26 04:54:13.382  6108  6108 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:13.382  6108  6120 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 04:54:13.383  6108  6120 I bt_bluedroid: enable
08-26 04:54:13.383  6108  6121 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 04:54:13.383  6108  6121 I bt_hci  : start_up
,08-26 04:54:13.388  6108  6121 I bt_vendor: alloc value 0xf412104d
08-26 04:54:13.388  6108  6121 I bt_vendor: init
08-26 04:54:13.388  6108  6121 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 04:54:13.388  6108  6121 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 04:54:13.505  6108  6121 D bt_hci  : start_up starting async portion
,08-26 04:54:13.505  6108  6128 I bt_hci  : event_finish_startup
08-26 04:54:13.505  6108  6128 I bt_hci_h4: hal_open
08-26 04:54:13.505  6108  6128 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 04:54:13.506  6108  6128 I bt_userial_vendor: device fd = 51 open
08-26 04:54:13.496  6129  6129 W irq/448-msm_hs_: type=1400 audit(0.0:75): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-26 04:54:13.519  6108  6128 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 04:54:13.521  6108  6128 D bt_hwcfg: Chipset BCM4358A3
,08-26 04:54:13.521  6108  6128 D bt_hwcfg: Target name = [BCM4358A3]
08-26 04:54:13.522  6108  6128 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-26 04:54:13.839  6108  6128 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-26 04:54:13.839  6108  6128 D bt_hwcfg: Settlement delay -- 100 ms
08-26 04:54:13.839  6108  6128 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 04:54:13.963  6108  6128 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 04:54:13.964  6108  6128 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-26 04:54:13.965  6108  6128 I bt_hwcfg: vendor lib fwcfg completed
08-26 04:54:13.965  6108  6128 I bt_vendor: firmware callback
08-26 04:54:13.965  6108  6128 I bt_hci  : firmware_config_callback
08-26 04:54:13.970  6108  6131 I bt_btu  : btu_task pending for preload complete event
08-26 04:54:13.970  6108  6131 I bt_btu_task: Bluetooth chip preload is complete
08-26 04:54:13.970  6108  6131 I bt_btu  : btu_task received preload complete event
,08-26 04:54:13.973  6108  6131 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 04:54:13.973  6108  6131 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 04:54:13.974  6108  6131 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 04:54:13.974  6108  6131 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 04:54:13.974  6108  6131 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 04:54:13.974  6108  6131 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 04:54:13.974  6108  6131 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 04:54:13.974  6108  6131 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 04:54:13.974  6108  6131 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 04:54:13.974  6108  6131 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 04:54:13.974  6108  6131 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 04:54:13.974  6108  6131 I         : BTE_InitTraceLevels -- TRC_GATT
,08-26 04:54:13.974  6108  6131 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 04:54:13.974  6108  6131 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 04:54:13.974  6108  6131 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 04:54:14.061  6108  6131 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf409ec99
,08-26 04:54:14.061  6108  6131 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf409ec99 
,08-26 04:54:14.073  6108  6124 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 04:54:14.075  6108  6124 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 04:54:14.076  6108  6124 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-26 04:54:14.077  6108  6124 D BluetoothAdapterProperties: Name is: Nexus 6P
08-26 04:54:14.079  6108  6124 D BluetoothAdapterProperties: Scan Mode:20
08-26 04:54:14.079  6108  6124 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 04:54:14.079  6108  6124 D bt_hci  : do_postload posting postload work item
,08-26 04:54:14.079  6108  6128 I bt_hci  : event_postload
08-26 04:54:14.079  6108  6128 I bt_vendor: sco_config_cb
,08-26 04:54:14.079  6108  6128 I bt_hci  : sco_config_callback postload finished.
08-26 04:54:14.086  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:54:14.086  6108  6124 D bt_bte_conf: Device ID record 1 : primary
,08-26 04:54:14.086  6108  6124 D bt_bte_conf:   vendorId            = 000f
08-26 04:54:14.086  6108  6124 D bt_bte_conf:   vendorIdSource      = 0001
08-26 04:54:14.087  6108  6124 D bt_bte_conf:   product             = 1200
08-26 04:54:14.087  6108  6124 D bt_bte_conf:   version             = 1436
08-26 04:54:14.087  6108  6124 D bt_bte_conf:   clientExecutableURL = 
08-26 04:54:14.087  6108  6124 D bt_bte_conf:   serviceDescription  = 
08-26 04:54:14.087  6108  6124 D bt_bte_conf:   documentationURL    = 
08-26 04:54:14.087  6108  6124 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 04:54:14.088  6108  6121 D bt_stack_manager: event_start_up_stack finished
08-26 04:54:14.089  6108  6120 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 04:54:14.090  6108  6120 D BluetoothAdapterProperties: Setting state to 15
08-26 04:54:14.090  6108  6120 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 04:54:14.091  6108  6120 I BluetoothAdapterState: Entering BleOnState
,08-26 04:54:14.095  6108  6120 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-26 04:54:14.096  6108  6120 D BluetoothAdapterProperties: Setting state to 11
08-26 04:54:14.096  6108  6120 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-26 04:54:14.098  6108  6128 I bt_vendor: low_power_mode_cb
,08-26 04:54:14.103  6108  6108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
,08-26 04:54:14.107  6108  6108 D HeadsetService: Received start request. Starting profile...
,08-26 04:54:14.110  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:14.111  6108  6108 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 04:54:14.111  6108  6108 D HeadsetStateMachine: make
,08-26 04:54:14.123  6108  6108 D HeadsetStateMachine: max_hf_connections = 1
08-26 04:54:14.123  6108  6108 I bt_bluedroid: get_profile_interface handsfree
08-26 04:54:14.125  6108  6120 I BluetoothAdapterState: Entering PendingCommandState
,08-26 04:54:14.125  6108  6124 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-26 04:54:14.126  6108  6124 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-26 04:54:14.127  6108  6108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:54:14.127  6108  6108 D A2dpService: Received start request. Starting profile...
08-26 04:54:14.128  6108  6108 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 04:54:14.128  6108  6108 I bt_bluedroid: get_profile_interface avrcp
,08-26 04:54:14.134  6108  6108 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 04:54:14.134  6108  6108 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 04:54:14.134  6108  6108 D A2dpStateMachine: make
,08-26 04:54:14.137  6108  6108 I bt_bluedroid: get_profile_interface a2dp
,08-26 04:54:14.138  6108  6124 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 04:54:14.139  6108  6139 D A2dpStateMachine: Enter Disconnected: -2
08-26 04:54:14.139  6108  6108 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 04:54:14.140  6108  6108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
,08-26 04:54:14.141  6108  6108 D HidService: Received start request. Starting profile...
08-26 04:54:14.141  6108  6108 I bt_bluedroid: get_profile_interface hidhost
08-26 04:54:14.141  6108  6108 D HidService: setHidService(): set to: null
08-26 04:54:14.141  6108  6124 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40802d9
08-26 04:54:14.142  6108  6124 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 04:54:14.142  6108  6108 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 04:54:14.143  6108  6108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
,08-26 04:54:14.144  6108  6108 D HealthService: Received start request. Starting profile...
,08-26 04:54:14.145  6108  6108 I bt_bluedroid: get_profile_interface health
,08-26 04:54:14.147  6108  6108 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 04:54:14.148  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 04:54:14.148  6108  6108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:54:14.149  6108  6108 D PanService: Received start request. Starting profile...
,08-26 04:54:14.149  6108  6108 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 04:54:14.149  6108  6108 I bt_bluedroid: get_profile_interface pan
08-26 04:54:14.149  6108  6124 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 04:54:14.151  6108  6108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:54:14.151  6108  6108 D BluetoothMapService: Received start request. Starting profile...
08-26 04:54:14.151  6108  6108 D BluetoothMapService: start()
,08-26 04:54:14.154  6108  6108 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 04:54:14.155  6108  6108 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 04:54:14.155  6108  6108 D BluetoothMapAppObserver: createReceiver()
08-26 04:54:14.156  6108  6108 D BluetoothMapAppObserver: initObservers()
08-26 04:54:14.156  6108  6108 D BluetoothMapAppObserver: getEnabledAccountItems()
08-26 04:54:14.162  6108  6108 V SapService: SapBinder()
08-26 04:54:14.162  6108  6108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
,08-26 04:54:14.162  6108  6108 D SapService: Received start request. Starting profile...
08-26 04:54:14.163  6108  6108 V SapService: start()
,08-26 04:54:14.164  6108  6108 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:14.164  6108  6108 V BluetoothAdapterState: isTurningOn()=true
08-26 04:54:14.164  6108  6108 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:14.164  6108  6108 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:14.164  6108  6108 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:14.164  6108  6108 V BluetoothAdapterState: isTurningOn()=true
08-26 04:54:14.164  6108  6136 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=2
08-26 04:54:14.164  6108  6108 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:14.164  6108  6108 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:14.165  6108  6108 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:14.165  6108  6108 V BluetoothAdapterState: isTurningOn()=true
,08-26 04:54:14.165  6108  6108 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:14.165  6108  6108 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:14.165  6108  6108 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:14.165  6108  6108 V BluetoothAdapterState: isTurningOn()=true
08-26 04:54:14.165  6108  6108 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:14.165  6108  6108 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:14.166  6108  6108 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:14.166  6108  6108 V BluetoothAdapterState: isTurningOn()=true
08-26 04:54:14.166  6108  6108 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:14.166  6108  6108 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:14.166  6108  6108 V BluetoothAdapterState: isTurningOff()=false
,08-26 04:54:14.166  6108  6108 V BluetoothAdapterState: isTurningOn()=true
08-26 04:54:14.167  6108  6108 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:14.167  6108  6108 V BluetoothAdapterState: isBleTurningOff()=false
08-26 04:54:14.168  6108  6108 V BluetoothAdapterState: isTurningOff()=false
08-26 04:54:14.168  6108  6108 V BluetoothAdapterState: isTurningOn()=true
,08-26 04:54:14.168  6108  6108 V BluetoothAdapterState: isBleTurningOn()=false
08-26 04:54:14.168  6108  6108 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 04:54:14.168  6108  6120 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 04:54:14.168  6108  6120 D BluetoothAdapterProperties: ScanMode =  20
08-26 04:54:14.168  6108  6120 D BluetoothAdapterProperties: State =  11
08-26 04:54:14.171  6108  6124 D BluetoothAdapterProperties: Scan Mode:21
,08-26 04:54:14.171  6108  6120 D BluetoothAdapterProperties: Setting state to 12
08-26 04:54:14.171  6108  6120 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 04:54:14.171  6108  6124 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 04:54:14.172  3603  3869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 04:54:14.172  6108  6120 I BluetoothAdapterState: Entering OnState
08-26 04:54:14.175   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 04:54:14.176  5529  5542 D BluetoothPan: onBluetoothStateChange on: true
,08-26 04:54:14.177   931   931 D BluetoothA2dp: Proxy object connected
08-26 04:54:14.177  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:14.177  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:14.177  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:14.177  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:14.177  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:14.177  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 04:54:14.177  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 04:54:14.177  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 04:54:14.178  5529  5840 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 04:54:14.179  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 04:54:14.179  5529  5529 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 04:54:14.180  5529  5529 D PanProfile: Bluetooth service connected
08-26 04:54:14.180  3239  3251 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 04:54:14.181  6108  6108 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 04:54:14.182  6108  6108 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 04:54:14.182  5529  5541 D BluetoothMap: onBluetoothStateChange: up=true
08-26 04:54:14.183  6108  6108 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 04:54:14.183  5529  5529 D BluetoothA2dp: Proxy object connected
,08-26 04:54:14.187   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-26 04:54:14.187   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 04:54:14.188  3239  3803 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 04:54:14.188   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 04:54:14.188  6108  6108 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 04:54:14.188  5529  5542 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 04:54:14.189  6108  6108 D ObexServerSockets: Succeed to create listening sockets 
08-26 04:54:14.189  6108  6108 D ObexServerSockets0: startAccept()
08-26 04:54:14.189  6108  6108 D ObexServerSockets0: prepareForNewConnect()
,08-26 04:54:14.192  6108  6108 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-26 04:54:14.192  6108  6108 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 04:54:14.192  6108  6145 D ObexServerSockets0: Accepting socket connection...
08-26 04:54:14.193  6108  6146 D ObexServerSockets0: Accepting socket connection...
08-26 04:54:14.193  3239  3251 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 04:54:14.193  3239  3239 D BluetoothInputDevice: Proxy object connected
08-26 04:54:14.193  3239  3239 D HidProfile: Bluetooth service connected
08-26 04:54:14.195  5529  5529 D BluetoothInputDevice: Proxy object connected
08-26 04:54:14.195  5529  5529 D HidProfile: Bluetooth service connected
08-26 04:54:14.196  5529  5542 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 04:54:14.196   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 04:54:14.197  3239  3250 D BluetoothPan: onBluetoothStateChange on: true
08-26 04:54:14.199  3239  3239 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 04:54:14.199  3239  3811 D BluetoothMap: onBluetoothStateChange: up=true
08-26 04:54:14.199  3239  3239 D PanProfile: Bluetooth service connected
08-26 04:54:14.200  3239  3239 D BluetoothMap: Proxy object connected
,08-26 04:54:14.201  3239  3239 D MapProfile: Bluetooth service connected
08-26 04:54:14.201  5529  5840 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 04:54:14.201  3239  3239 D BluetoothMap: getConnectedDevices()
08-26 04:54:14.202  3239  3250 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 04:54:14.204   931   951 V KeyguardServiceDelegate: onScreenTurnedOff()
08-26 04:54:14.200  5529  5529 D BluetoothMap: Proxy object connected
08-26 04:54:14.204  5529  5529 D MapProfile: Bluetooth service connected
08-26 04:54:14.204  5529  5529 D BluetoothMap: getConnectedDevices()
08-26 04:54:14.205  3239  3239 D BluetoothA2dp: Proxy object connected
08-26 04:54:14.206   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 04:54:14.206  6108  6108 D BluetoothMapService: onReceive
08-26 04:54:14.206  6108  6108 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 04:54:14.207  6108  6108 D BluetoothMapService: STATE_ON
,08-26 04:54:14.209  6108  6147 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 04:54:14.211  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:54:14.213  6108  6147 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,08-26 04:54:14.213  6108  6147 D BluetoothSdpJni: SDP Create record success - handle: 1
08-26 04:54:14.214  5529  5529 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 04:54:14.216   931   949 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-26 04:54:14.219   381   381 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fa27c3c00
08-26 04:54:14.219   381   381 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-26 04:54:14.221  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 04:54:14.227  5529  5529 D DockEventReceiver: finishStartingService: stopping service
,08-26 04:54:14.228  5529  5529 D BluetoothPbap: Proxy object connected
08-26 04:54:14.229  5529  5529 D PbapServerProfile: Bluetooth service connected
08-26 04:54:14.229  3239  3239 D BluetoothPbap: Proxy object connected
08-26 04:54:14.229  3239  3239 D PbapServerProfile: Bluetooth service connected
08-26 04:54:14.229  6108  6108 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 04:54:14.229  6108  6108 D ObexServerSockets0: prepareForNewConnect()
,08-26 04:54:14.231  6108  6149 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 04:54:14.248  3701  3701 D a       : Creating database auth.proximity.permit_store...
08-26 04:54:14.249  3701  3701 D c       : Creating table: permit
,08-26 04:54:14.250  3701  3701 D c       : Creating table: permit__requester_access
,08-26 04:54:14.263  3701  3701 D a       : Opening database auth.proximity.permit_store...
,08-26 04:54:14.281  5412  5458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:14.281  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:14.281  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:14.281  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:14.281  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:14.281  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 04:54:14.281  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 04:54:14.281  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 04:54:14.281   931   931 D BluetoothHeadset: Proxy object connected
,08-26 04:54:14.282  3239  3811 D BluetoothHeadset: Proxy object connected
08-26 04:54:14.282  3239  3239 D HeadsetProfile: Bluetooth service connected
,08-26 04:54:14.282  3603  3628 D BluetoothHeadset: Proxy object connected
,08-26 04:54:14.283   931   931 D BluetoothHeadset: Proxy object connected
08-26 04:54:14.283   931   931 D BluetoothHeadset: Proxy object connected
08-26 04:54:14.283  5529  5541 D BluetoothHeadset: Proxy object connected
08-26 04:54:14.283  5412  5458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 04:54:14.284  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 04:54:14.284  5529  5529 D HeadsetProfile: Bluetooth service connected
,08-26 04:54:14.284  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1939577 added. We now have 8 listener(s)
08-26 04:54:14.285  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 04:54:14.287   931  3500 D WifiService: setWifiEnabled: false pid=5412, uid=10077
08-26 04:54:14.287   931  3500 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 04:54:14.288   931   948 D BluetoothHeadset: Proxy object connected
,08-26 04:54:14.289  3239  3803 D BluetoothHeadset: Proxy object connected
08-26 04:54:14.289  3239  3239 D HeadsetProfile: Bluetooth service connected
08-26 04:54:14.289   931   948 D BluetoothHeadset: Proxy object connected
08-26 04:54:14.289   931  3070 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 04:54:14.289   931  3070 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 04:54:14.290   931  3070 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 04:54:14.290   931  3070 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 04:54:14.293  6108  6158 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 04:54:14.294  6108  6158 I BtOppRfcommListener: Accept thread started.
,08-26 04:54:14.296   931  3070 E native  : do suspend true
,08-26 04:54:14.296  5529  5542 D BluetoothHeadset: Proxy object connected
08-26 04:54:14.297   931   948 D BluetoothHeadset: Proxy object connected
08-26 04:54:14.297  5529  5529 D HeadsetProfile: Bluetooth service connected
,08-26 04:54:14.303   931  5596 D DhcpClient: Clearing IP address
,08-26 04:54:14.303   506   925 D CommandListener: Clearing all IP addresses on wlan0
,08-26 04:54:14.304   506   925 D CommandListener: Setting iface cfg
,08-26 04:54:14.306   931  5597 D DhcpClient: Receive thread stopped
08-26 04:54:14.307  3701  5951 V NativeCrypto: Read error: ssl=0x7f8267a880: I/O error during system call, Connection timed out
08-26 04:54:14.308  3701  5951 V NativeCrypto: SSL shutdown failed: ssl=0x7f8267a880: I/O error during system call, Broken pipe
08-26 04:54:14.310   931   941 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
08-26 04:54:14.310   931  5594 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
08-26 04:54:14.312   931  5594 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-26 04:54:14.312   931  3072 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-26 04:54:14.313   931  3072 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 04:54:14.314   931  3072 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 04:54:14.318   931  3072 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 04:54:14.318   931  3072 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-26 04:54:14.321   590   590 E Parcel  : Reading a NULL string not supported here.
08-26 04:54:14.322   931   931 D RttService: SCAN_AVAILABLE : 1
08-26 04:54:14.322   931  3179 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 04:54:14.323   931  3072 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 04:54:14.324   931  3070 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 04:54:14.325  3577  3741 W QCNEJ   : |CORE| network lost: 100
08-26 04:54:14.325  3577  3741 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
08-26 04:54:14.329   931  3070 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 04:54:14.329   931  3070 E native  : do suspend true
,08-26 04:54:14.332  3226  5657 W DownloadManager: [8] Stop requested with status HTTP_DATA_ERROR: Failed reading response: javax.net.ssl.SSLException: Read error: ssl=0x7f82677380: I/O error during system call, Connection timed out
,08-26 04:54:14.334  3226  5669 W DownloadManager: [9] Stop requested with status HTTP_DATA_ERROR: Failed reading response: javax.net.ssl.SSLException: Read error: ssl=0x7f7debb180: I/O error during system call, Connection timed out
,08-26 04:54:14.335  3226  5669 D DownloadManager: [9] Finished with status CANNOT_RESUME
08-26 04:54:14.336  3226  5657 D DownloadManager: [8] Finished with status CANNOT_RESUME
,08-26 04:54:14.345   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 04:54:14.364   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 04:54:14.364   506   925 D CommandListener: Clearing all IP addresses on wlan0
08-26 04:54:14.364   506   925 D TetherController: Setting IP forward enable = 0
,08-26 04:54:14.365   931  3072 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 04:54:14.365   931  3072 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 04:54:14.366   931  3070 D DhcpClient: doQuit
08-26 04:54:14.366   931  3070 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-26 04:54:14.367   931  5596 D DhcpClient: onQuitting
08-26 04:54:14.367  5587  5587 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
08-26 04:54:14.368   931   948 D Tethering: MasterInitialState.processMessage what=3
,08-26 04:54:14.377  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:14.377  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:14.377  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:14.377  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 04:54:14.377  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:14.377  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:54:14.377  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:54:14.377  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 04:54:14.379  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 04:54:14.380  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:14.381  4666  4666 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-26 04:54:14.385  4766  4779 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,08-26 04:54:14.385  4766  4779 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,08-26 04:54:14.385  4766  4779 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-26 04:54:14.385  4766  4779 E SarControlService: no key has been found,reset the power
08-26 04:54:14.385  3963  3963 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-26 04:54:14.385  4766  4804 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-26 04:54:14.385  4766  4804 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-26 04:54:14.385  4766  4804 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-26 04:54:14.386  4792  4792 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-26 04:54:14.386  4792  4792 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-26 04:54:14.387  4766  4804 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-26 04:54:14.388  4766  4804 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-26 04:54:14.388  4766  4804 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-26 04:54:14.388  4792  4792 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-26 04:54:14.388  3963  3963 D SystemUpdateService: onCreate
,08-26 04:54:14.388  4792  4792 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,08-26 04:54:14.389  4792  4806 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7492b19 HexData = [00000000ea03000000000000ffffffff]
,08-26 04:54:14.389  4792  4806 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-26 04:54:14.389  4792  4806 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
08-26 04:54:14.389  4792  4792 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-26 04:54:14.390  4766  4776 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-26 04:54:14.390  4792  4806 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7492b19 HexData = [00000000eb03000000000000ffffffff]
08-26 04:54:14.390  4792  4806 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-26 04:54:14.390  4792  4806 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
08-26 04:54:14.391  4792  4792 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-26 04:54:14.391  3963  3963 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-26 04:54:14.391  4766  4777 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-26 04:54:14.394  3963  6172 I SystemUpdateService: active receiver: enabled
08-26 04:54:14.399  3963  6172 I SystemUpdateService: showing system update notification
08-26 04:54:14.402  3963  3963 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 04:54:14.403  3963  5633 I iu.UploadsManager: num queued entries: 0
,08-26 04:54:14.404  3963  5633 I iu.UploadsManager: num updated entries: 0
08-26 04:54:14.414  3963  3963 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-26 04:54:14.414  3963  5633 I iu.SyncManager: NEXT; no task
08-26 04:54:14.415  3963  3963 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-26 04:54:14.418  5642  5642 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 04:54:14.422  3963  6172 V SystemUpdateService: retry (wakeup: false) in 3599982 ms
08-26 04:54:14.422   506   925 E Netd    : netlink response contains error (No such file or directory)
,08-26 04:54:14.423  5642  5642 D SprintDMHelper: simOperator: 
,08-26 04:54:14.423  5642  5642 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-26 04:54:14.424  3963  3963 D SystemUpdateService: onDestroy
08-26 04:54:14.424   506   925 D TetherController: Setting IP forward enable = 0
08-26 04:54:14.424   931  3072 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-26 04:54:14.426  5587  5587 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
08-26 04:54:14.429  5587  5587 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 04:54:14.438  4300  6180 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 04:54:14.462  3510  6183 I DictionaryProvider:UpdateHandler: downloadFinished() : DownloadId = 9
,08-26 04:54:14.475  5587  5587 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-26 04:54:14.478  3510  6183 E DictionaryProvider:UpdateHandler: Permanent failure of download 9 with error code: 1008
,08-26 04:54:14.484  3510  6183 I DictionaryProvider:UpdateHandler: downloadFinished() : WordList Failure
,08-26 04:54:14.495  5587  5587 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-26 04:54:14.499  3510  3510 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-26 04:54:14.503  3510  6184 I Keyboard.Facilitator.DecoderInitializer: run()
,08-26 04:54:14.506  3510  6184 I Decoder : createOrResetDecoder
,08-26 04:54:14.517   381   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-26 04:54:14.517   381   381 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-26 04:54:14.518   931  3182 D SurfaceControl: Excessive delay in setPowerMode(): 301ms
,08-26 04:54:14.522  3701  3701 I ConfigService: onCreate
,08-26 04:54:14.530  3510  6183 I DictionaryProvider:UpdateHandler: downloadFinished() : DownloadId = 8
,08-26 04:54:14.535  3510  6183 E DictionaryProvider:UpdateHandler: Permanent failure of download 8 with error code: 1008
,08-26 04:54:14.538  3510  6183 I DictionaryProvider:UpdateHandler: downloadFinished() : WordList Failure
,08-26 04:54:14.544  3510  6184 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 04:54:14.554  3510  3510 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-26 04:54:14.577  3510  6184 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /system/app/LatinImeGoogle/LatinImeGoogle.apk (offset=3195532, length=4014912) with up to date LoudsLmContentVersion = 20150512
,08-26 04:54:14.579  3510  6184 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-26 04:54:14.580  3510  6184 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-26 04:54:14.587  3510  6188 I Keyboard.Facilitator.DecoderInitializer: run()
,08-26 04:54:14.587  3510  6188 I Decoder : createOrResetDecoder
,08-26 04:54:14.597   931  3070 D wifi    : In wifi stop Hal
,08-26 04:54:14.598   931  3070 D wifi    : halHandle = 0x7f71b2d240, mVM = 0x7f887cd140, mCls = 0x17ea
08-26 04:54:14.598  4300  4300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 04:54:14.599   931  5586 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-26 04:54:14.599   931  5586 D WifiHAL : Got a signal to exit!!!
,08-26 04:54:14.599   931  5586 I WifiHAL : Exit wifi_event_loop
08-26 04:54:14.599   931  3070 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
08-26 04:54:14.600   931  3070 E WifiHAL : Event processing terminated
08-26 04:54:14.600   931  3070 D wifi    : In wifi cleaned up handler
08-26 04:54:14.600   931  3070 I WifiHAL : Internal cleanup completed
08-26 04:54:14.600  3731  4050 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 04:54:14.601  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:54:14.605  3510  6188 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 04:54:14.617   931  5586 D wifi    : set interface wlan0 flags (DOWN)
,08-26 04:54:14.618   931  3070 D WifiNative-HAL: HAL event thread stopped successfully
,08-26 04:54:14.626  3510  6188 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /system/app/LatinImeGoogle/LatinImeGoogle.apk (offset=3195532, length=4014912) with up to date LoudsLmContentVersion = 20150512
,08-26 04:54:14.628  3510  6188 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-26 04:54:14.628  3510  6188 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-26 04:54:14.631  3510  6188 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-26 04:54:14.632  3510  6188 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-26 04:54:14.632  3510  6188 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-26 04:54:14.632  3510  6188 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-26 04:54:14.633  3510  6188 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-26 04:54:14.633  3510  6188 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-26 04:54:14.633  3510  6188 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-26 04:54:14.633  3510  6188 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-26 04:54:14.634  3510  6188 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-26 04:54:14.634  3510  6188 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-26 04:54:14.828   931   948 D Tethering: InitialState.processMessage what=4
,08-26 04:54:14.835   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 04:54:15.237   931  3030 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 04:54:15.288  3963  6192 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-26 04:54:15.297  3963  6192 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-26 04:54:15.300  5412  5458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:15.300  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:15.300  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:15.300  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 04:54:15.300  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:15.300  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:54:15.300  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:54:15.300  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 04:54:15.301  4666  6195 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-26 04:54:15.320  5412  5458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 04:54:15.322   931   941 D WifiService: setWifiEnabled: true pid=5412, uid=10077
,08-26 04:54:15.322   931   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 04:54:15.326   506   925 D SoftapController: Softap fwReload - Ok
08-26 04:54:15.329   506   925 D CommandListener: Setting iface cfg
08-26 04:54:15.329   506   925 D CommandListener: Trying to bring down wlan0
08-26 04:54:15.330   506   925 D CommandListener: Clearing all IP addresses on wlan0
08-26 04:54:15.332   931  3070 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-26 04:54:15.336  3731  3731 V GmsNetworkLocationProvi: DISABLE
08-26 04:54:15.338  4666  6195 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 37 ms] updated apps [took 37 ms] 
08-26 04:54:15.338  3963  4648 I Icing   : updateResources: need to parse f{com.google.android.gms}
,08-26 04:54:15.343  3731  3731 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,08-26 04:54:15.937   931  3070 D wifi    : set interface wlan0 flags (UP)
08-26 04:54:15.940   931  3070 I WifiHAL : Initializing wifi
08-26 04:54:15.940   931  3070 I WifiHAL : Creating socket
,08-26 04:54:15.946   931  3070 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-26 04:54:15.946   931  3070 D wifi    : Did set static halHandle = 0x7f71b2d240
08-26 04:54:15.946   931  3070 D wifi    : halHandle = 0x7f71b2d240, mVM = 0x7f887cd140, mCls = 0x2013c6
08-26 04:54:15.946   931  3070 D wifi    : array field set
08-26 04:54:15.947   931  3070 I WifiNative-HAL: interface[0] = wlan0
08-26 04:54:15.949   931  6201 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547368391232
08-26 04:54:15.950   931  6201 D wifi    : waitForHalEvents called, vm = 0x7f887cd140, obj = 0x2013c6, env = 0x7f6ef88e00
,08-26 04:54:15.950   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 04:54:15.953   931  3070 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 04:54:15.957   931  3070 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-26 04:54:15.960  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:54:16.009  6202  6202 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 04:54:16.029  6202  6202 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 04:54:16.037  6202  6202 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 04:54:16.037  6202  6202 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-26 04:54:16.980   931  3070 D WifiConfigStore: Loading config and enabling all networks 
,08-26 04:54:16.987  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:16.987  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:16.987  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:16.987  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:16.987  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:16.987  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:54:16.987  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:54:16.987  5412  5412 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 04:54:16.990  5412  5412 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 04:54:16.993   931  3070 D WifiConfigStore: loaded 0 passpoint configs
,08-26 04:54:16.994   931  3070 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 04:54:16.996   931  3070 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-26 04:54:16.997   931  3070 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-26 04:54:16.997   931  3070 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-26 04:54:16.998   931  3070 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-26 04:54:17.002   931  3070 D WifiNative-HAL: Setting external_sim to 1
08-26 04:54:17.003   931  3070 D wifi    : setting dfs flag to true, 0x7f71e355a0
08-26 04:54:17.004   931  3070 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 04:54:17.004   931  3070 D wifi    : setting scan oui 0x7f71e355a0
08-26 04:54:17.004   931  3070 D WifiHAL : Sending mac address OUI
08-26 04:54:17.006  4300  4300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 04:54:17.025   931  3070 E native  : do suspend true
,08-26 04:54:17.031   931  3070 D wifi    : android_net_wifi_setLinkLayerStats: 1
,08-26 04:54:17.031   931   931 D RttService: SCAN_AVAILABLE : 3
08-26 04:54:17.031   506   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-26 04:54:17.031   931  3179 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 04:54:17.032   506   925 D CommandListener: Setting iface cfg
,08-26 04:54:17.037   931  3069 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '83 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 83 Failed to set address (No such device)'
,08-26 04:54:17.037   931  3069 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 04:54:17.044   931  3069 D WifiNative-HAL: p2pGetDeviceAddress
08-26 04:54:17.045   931  3069 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-26 04:54:17.049   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=197524 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,08-26 04:54:17.348  5412  5458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 04:54:17.348  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:17.348  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:17.348  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:17.348  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:17.348  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:54:17.348  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:54:17.348  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 04:54:17.353  5412  5458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 04:54:17.362  5412  5458 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-26 04:54:17.363  5412  5458 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 04:54:17.368  5412  5458 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ff25124 Bundle[{}]
,08-26 04:54:17.370  5412  5458 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 04:54:17.371  5412  5458 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 04:54:17.372  5412  5458 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 04:54:17.373  5412  5458 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 04:54:17.373  5412  5458 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-26 04:54:17.374  5412  5458 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 04:54:17.379  5412  5458 I System.out: Running OutgoingSocketThread
,08-26 04:54:17.380  5412  6204 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 143)
,08-26 04:54:17.381  5412  6204 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46180
08-26 04:54:17.381  5412  6204 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 04:54:18.382  5412  5458 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 144)
,08-26 04:54:18.382  5412  5458 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 144)
,08-26 04:54:18.389  5412  5458 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 149)
,08-26 04:54:18.391  5412  5458 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 04:54:18.391  5412  5458 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 150)
,08-26 04:54:18.397  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 04:54:18.397  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46b15e4 added. We now have 2 listener(s)
,08-26 04:54:18.400  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-26 04:54:18.401  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 04:54:18.401  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 04:54:18.401  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 04:54:18.401  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49bfa4d added. We now have 9 listener(s)
08-26 04:54:18.401  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 04:54:18.402  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 04:54:18.407  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 04:54:18.411  5412  5458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 04:54:18.411  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:18.411  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:18.411  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:18.411  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:18.411  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:54:18.411  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:54:18.411  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 04:54:18.414  5412  5458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 04:54:18.415  5412  5458 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 04:54:18.415  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 04:54:18.415  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b221213 added. We now have 3 listener(s)
,08-26 04:54:18.417  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-26 04:54:18.417  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 04:54:18.417  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 04:54:18.418  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 04:54:18.418  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb5ac50 added. We now have 10 listener(s)
08-26 04:54:18.418  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:18.418  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 04:54:18.418  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:54:18.418  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:54:18.418  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:54:18.419  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:54:18.419  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.419  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 04:54:18.419  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 04:54:18.419  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46b15e4 removed from the list
08-26 04:54:18.419  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:54:18.419  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49bfa4d removed from the list
,08-26 04:54:18.421  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:18.421  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:54:18.421  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:54:18.422  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.422  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 04:54:18.423  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 04:54:18.423  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:54:18.423  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:54:18.423  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49bfa4d not in the list
08-26 04:54:18.423  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.423  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 04:54:18.424  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:54:18.424  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:54:18.424  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:54:18.424  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb5ac50 removed from the list
08-26 04:54:18.424  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:54:18.424  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 04:54:18.425  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:54:18.425  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 04:54:18.425  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b221213 removed from the list
08-26 04:54:18.425  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 04:54:18.425  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9baee49 added. We now have 2 listener(s)
08-26 04:54:18.427  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-26 04:54:18.427  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 04:54:18.427  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 04:54:18.427  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 04:54:18.427  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea7e34e added. We now have 9 listener(s)
08-26 04:54:18.427  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 04:54:18.428  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 04:54:18.431  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 04:54:18.434  5412  5458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 04:54:18.434  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:18.434  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:18.434  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:18.434  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:18.434  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:54:18.434  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:54:18.434  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 04:54:18.436  5412  5458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 04:54:18.436  5412  5458 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 04:54:18.436  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 04:54:18.437  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d13d7c added. We now have 3 listener(s)
08-26 04:54:18.438  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:18.438  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-26 04:54:18.438  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 04:54:18.438  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 04:54:18.438  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 04:54:18.438  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbb2605 added. We now have 10 listener(s)
,08-26 04:54:18.438  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 04:54:18.439  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 04:54:18.439  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 04:54:18.439  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 04:54:18.439  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 04:54:18.439  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 04:54:18.439  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:18.442  5412  5458 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 04:54:18.442  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 04:54:18.447  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 04:54:18.449  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 04:54:18.449  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 04:54:18.452  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 04:54:18.453  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 04:54:18.453  5412  5458 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 04:54:18.454  5412  5458 D BluetoothAdapter: STATE_ON
,08-26 04:54:18.459  6108  6155 D BtGatt.GattService: registerClient() - UUID=745fe770-d918-4d57-8014-c657cddde332
,08-26 04:54:18.460  6108  6124 D BtGatt.GattService: onClientRegistered() - UUID=745fe770-d918-4d57-8014-c657cddde332, clientIf=5
,08-26 04:54:18.461  5412  5528 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 04:54:18.462  6108  6118 D BtGatt.GattService: start scan with filters
,08-26 04:54:18.466  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 04:54:18.466  6108  6127 D BtGatt.ScanManager: handling starting scan
08-26 04:54:18.466  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 04:54:18.466  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 04:54:18.466  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 04:54:18.467  6108  6127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b415578
08-26 04:54:18.469  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 04:54:18.470  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 04:54:18.470  5412  5412 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 04:54:18.471  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 04:54:18.473  5412  5458 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 04:54:18.473  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 04:54:18.473  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 04:54:18.473  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.473  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 04:54:18.473  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 04:54:18.473  6108  6124 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 04:54:18.473  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 04:54:18.474  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.474  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 04:54:18.474  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 04:54:18.474  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 04:54:18.474  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 04:54:18.474  6108  6127 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 04:54:18.475  5412  5458 D BluetoothAdapter: STATE_ON
,08-26 04:54:18.476  6108  6155 D BtGatt.GattService: stopScan() - queue size =1
08-26 04:54:18.476  6108  6137 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 04:54:18.477  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 04:54:18.477  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 04:54:18.477  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 04:54:18.477  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 04:54:18.477  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 04:54:18.478  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 04:54:18.479  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 04:54:18.479  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 04:54:18.479  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 04:54:18.479  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 04:54:18.480  6108  6124 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-26 04:54:18.480  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.480  6108  6127 D BtGatt.ScanManager: Starting BLE batch scan
08-26 04:54:18.480  5412  5412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 04:54:18.481  5412  5412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 04:54:18.481  6108  6127 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 04:54:18.481  5412  5412 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 04:54:18.483  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 04:54:18.483  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:54:18.483  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:54:18.483  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:54:18.483  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.483  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 04:54:18.483  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 04:54:18.483  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9baee49 removed from the list
08-26 04:54:18.483  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:54:18.483  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea7e34e removed from the list
,08-26 04:54:18.483  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:54:18.483  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:54:18.485  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.485  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:54:18.485  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:54:18.486  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:54:18.486  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:54:18.486  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea7e34e not in the list
,08-26 04:54:18.486  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.486  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 04:54:18.487  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:54:18.487  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:54:18.487  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 04:54:18.487  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbb2605 removed from the list
08-26 04:54:18.487  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:54:18.487  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.487  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:54:18.487  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 04:54:18.488  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d13d7c removed from the list
08-26 04:54:18.488  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 04:54:18.488  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcd1d81 added. We now have 2 listener(s)
08-26 04:54:18.490  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-26 04:54:18.490  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 04:54:18.490  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 04:54:18.490  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 04:54:18.490  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c190e26 added. We now have 9 listener(s)
08-26 04:54:18.490  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 04:54:18.490  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 04:54:18.491  6108  6124 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 04:54:18.491  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 04:54:18.494  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 04:54:18.497  5412  5458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 04:54:18.497  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:18.497  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:18.497  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:18.497  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:18.497  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:54:18.497  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:54:18.497  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 04:54:18.497  6108  6124 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 04:54:18.497  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.499  5412  5458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 04:54:18.499  5412  5458 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 04:54:18.499  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 04:54:18.499  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb1c014 added. We now have 3 listener(s)
08-26 04:54:18.500  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:18.500  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-26 04:54:18.500  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 04:54:18.500  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 04:54:18.500  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 04:54:18.501  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ad10bd added. We now have 10 listener(s)
08-26 04:54:18.501  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 04:54:18.501  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 04:54:18.501  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:18.501  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 04:54:18.501  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 04:54:18.501  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 04:54:18.502  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 04:54:18.502  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 04:54:18.505  5412  5458 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 04:54:18.505  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 04:54:18.508  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 04:54:18.509  6108  6124 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-26 04:54:18.509  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.509  6108  6127 D BtGatt.ScanManager: stopping BLe Batch
08-26 04:54:18.509  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 04:54:18.509  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 04:54:18.513  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 04:54:18.513  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 04:54:18.513  5412  5458 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 04:54:18.514  5412  5458 D BluetoothAdapter: STATE_ON
,08-26 04:54:18.514  6108  6124 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 04:54:18.514  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.514  6108  6127 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 04:54:18.516  6108  6119 D BtGatt.GattService: registerClient() - UUID=7a837db5-aeaa-49ce-9f70-4acebca74293
08-26 04:54:18.517  6108  6124 D BtGatt.GattService: onClientRegistered() - UUID=7a837db5-aeaa-49ce-9f70-4acebca74293, clientIf=5
08-26 04:54:18.517  5412  5422 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 04:54:18.517  6108  6144 D BtGatt.GattService: start scan with filters
,08-26 04:54:18.519  6108  6124 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 04:54:18.519  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.519  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 04:54:18.519  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 04:54:18.520  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 04:54:18.520  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 04:54:18.521  6108  6127 D BtGatt.ScanManager: handling starting scan
08-26 04:54:18.522  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 04:54:18.522  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 04:54:18.522  5412  5412 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 04:54:18.523  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 04:54:18.525  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 04:54:18.526  5412  5458 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-26 04:54:18.526  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 04:54:18.526  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 04:54:18.526  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:54:18.526  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:54:18.526  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.526  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 04:54:18.526  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 04:54:18.526  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcd1d81 removed from the list
08-26 04:54:18.526  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:54:18.526  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c190e26 removed from the list
08-26 04:54:18.526  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:54:18.526  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 04:54:18.526  6108  6124 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 04:54:18.527  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.527  6108  6127 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 04:54:18.527  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.527  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 04:54:18.527  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.527  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 04:54:18.529  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 04:54:18.529  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:54:18.529  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:54:18.529  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c190e26 not in the list
08-26 04:54:18.529  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 04:54:18.529  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 04:54:18.530  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 04:54:18.530  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 04:54:18.530  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 04:54:18.531  5412  5458 D BluetoothAdapter: STATE_ON
08-26 04:54:18.532  6108  6124 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-26 04:54:18.532  6108  6144 D BtGatt.GattService: stopScan() - queue size =1
08-26 04:54:18.532  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.532  6108  6127 D BtGatt.ScanManager: Starting BLE batch scan
08-26 04:54:18.532  6108  6127 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 04:54:18.532  6108  6137 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 04:54:18.533  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 04:54:18.533  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 04:54:18.533  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 04:54:18.533  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 04:54:18.533  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 04:54:18.534  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 04:54:18.534  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 04:54:18.534  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 04:54:18.534  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 04:54:18.536  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:54:18.536  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:54:18.536  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:54:18.537  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:54:18.537  5412  5412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 04:54:18.537  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ad10bd removed from the list
08-26 04:54:18.537  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:54:18.537  5412  5412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 04:54:18.537  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.537  5412  5412 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 04:54:18.537  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:54:18.537  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 04:54:18.537  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb1c014 removed from the list
,08-26 04:54:18.537  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 04:54:18.537  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a9efbb9 added. We now have 2 listener(s)
08-26 04:54:18.539  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-26 04:54:18.539  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 04:54:18.539  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 04:54:18.539  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 04:54:18.539  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79bbfe added. We now have 9 listener(s)
08-26 04:54:18.539  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 04:54:18.539  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 04:54:18.541  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 04:54:18.542  6108  6124 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 04:54:18.542  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 04:54:18.545  5412  5458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 04:54:18.545  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:18.545  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:18.545  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:18.545  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:18.545  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:54:18.545  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:54:18.545  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 04:54:18.547  6108  6124 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 04:54:18.547  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 04:54:18.548  5412  5458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 04:54:18.548  5412  5458 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 04:54:18.548  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 04:54:18.548  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cfdac added. We now have 3 listener(s)
08-26 04:54:18.550  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:18.550  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-26 04:54:18.550  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 04:54:18.550  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 04:54:18.550  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 04:54:18.550  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2a9a75 added. We now have 10 listener(s)
08-26 04:54:18.550  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 04:54:18.550  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 04:54:18.550  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 04:54:18.550  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 04:54:18.550  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 04:54:18.550  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 04:54:18.551  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:18.553  5412  5458 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 04:54:18.553  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 04:54:18.556  6108  6124 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-26 04:54:18.557  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.557  6108  6127 D BtGatt.ScanManager: stopping BLe Batch
,08-26 04:54:18.557  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 04:54:18.558  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 04:54:18.558  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 04:54:18.562  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 04:54:18.562  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 04:54:18.562  5412  5458 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 04:54:18.562  6108  6124 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 04:54:18.562  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.563  6108  6127 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 04:54:18.563  5412  5458 D BluetoothAdapter: STATE_ON
08-26 04:54:18.564  6108  6137 D BtGatt.GattService: registerClient() - UUID=8c1dd1ad-cd07-40c6-885a-8f8c7321678d
08-26 04:54:18.565  6108  6124 D BtGatt.GattService: onClientRegistered() - UUID=8c1dd1ad-cd07-40c6-885a-8f8c7321678d, clientIf=5
08-26 04:54:18.565  5412  5422 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 04:54:18.565  6108  6144 D BtGatt.GattService: start scan with filters
,08-26 04:54:18.567  6108  6124 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 04:54:18.567  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 04:54:18.568  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 04:54:18.568  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 04:54:18.568  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 04:54:18.568  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 04:54:18.569  6108  6127 D BtGatt.ScanManager: handling starting scan
,08-26 04:54:18.570  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 04:54:18.570  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 04:54:18.570  5412  5412 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 04:54:18.571  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 04:54:18.575  6108  6124 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 04:54:18.575  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.575  6108  6127 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 04:54:18.577  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:54:18.577  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 04:54:18.577  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:54:18.577  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:54:18.577  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.577  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 04:54:18.577  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 04:54:18.577  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a9efbb9 removed from the list
08-26 04:54:18.577  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:54:18.577  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79bbfe removed from the list
08-26 04:54:18.577  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:54:18.577  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 04:54:18.578  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.578  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 04:54:18.578  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.578  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 04:54:18.579  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 04:54:18.579  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:54:18.579  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:54:18.579  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79bbfe not in the list
08-26 04:54:18.579  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 04:54:18.579  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 04:54:18.579  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 04:54:18.579  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 04:54:18.579  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 04:54:18.579  6108  6124 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-26 04:54:18.579  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.580  6108  6127 D BtGatt.ScanManager: Starting BLE batch scan
08-26 04:54:18.580  6108  6127 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 04:54:18.580  5412  5458 D BluetoothAdapter: STATE_ON
08-26 04:54:18.581  6108  6137 D BtGatt.GattService: stopScan() - queue size =1
08-26 04:54:18.582  6108  6144 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 04:54:18.582  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 04:54:18.582  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 04:54:18.582  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 04:54:18.582  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 04:54:18.582  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 04:54:18.583  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 04:54:18.583  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 04:54:18.583  5412  5458 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 04:54:18.583  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 04:54:18.584  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 04:54:18.585  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:54:18.585  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 04:54:18.585  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:54:18.585  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2a9a75 removed from the list
08-26 04:54:18.585  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:54:18.585  5412  5412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 04:54:18.585  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.585  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:54:18.585  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 04:54:18.585  5412  5412 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 04:54:18.585  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cfdac removed from the list
,08-26 04:54:18.585  5412  5412 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 04:54:18.586  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 04:54:18.586  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9768f1 added. We now have 2 listener(s)
08-26 04:54:18.587  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-26 04:54:18.587  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 04:54:18.587  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 04:54:18.587  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 04:54:18.587  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d74cd6 added. We now have 9 listener(s)
08-26 04:54:18.587  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 04:54:18.588  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 04:54:18.589  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 04:54:18.590  6108  6124 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 04:54:18.590  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.592  5412  5458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 04:54:18.592  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 04:54:18.592  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 04:54:18.592  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 04:54:18.592  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 04:54:18.592  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 04:54:18.592  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 04:54:18.592  5412  5458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 04:54:18.594  5412  5458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 04:54:18.594  5412  5458 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 04:54:18.594  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 04:54:18.595  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6cf5644 added. We now have 3 listener(s)
,08-26 04:54:18.595  6108  6124 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 04:54:18.595  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 04:54:18.596  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 04:54:18.596  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-26 04:54:18.596  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 04:54:18.596  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 04:54:18.597  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 04:54:18.597  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f28a32d added. We now have 10 listener(s)
08-26 04:54:18.597  5412  5458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 04:54:18.597  5412  5412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 04:54:18.597  5412  5458 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 04:54:18.597  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 04:54:18.597  5412  5458 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 04:54:18.597  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:54:18.597  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.597  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 04:54:18.598  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 04:54:18.598  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9768f1 removed from the list
08-26 04:54:18.598  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:54:18.598  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d74cd6 removed from the list
08-26 04:54:18.598  5412  5458 D io.jxcore.node.ConnectivityMonitor: stop
08-26 04:54:18.598  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 04:54:18.599  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.599  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 04:54:18.600  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 04:54:18.600  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:54:18.600  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:54:18.600  5412  5458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d74cd6 not in the list
,08-26 04:54:18.600  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.600  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 04:54:18.601  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 04:54:18.602  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 04:54:18.602  5412  5458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 04:54:18.602  5412  5458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f28a32d removed from the list
08-26 04:54:18.602  5412  5458 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 04:54:18.602  5412  5458 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 04:54:18.602  5412  5458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 04:54:18.602  5412  5458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 04:54:18.602  5412  5458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6cf5644 removed from the list
08-26 04:54:18.602  6108  6124 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-26 04:54:18.602  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.603  6108  6127 D BtGatt.ScanManager: stopping BLe Batch
,08-26 04:54:18.603  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 04:54:18.603  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 04:54:18.603  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 04:54:18.603  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 04:54:18.604  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 04:54:18.604  5412  5458 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 04:54:18.607  6108  6124 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 04:54:18.607  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.607  6108  6127 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 04:54:18.609  5412  6205 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: My test thread name)
08-26 04:54:18.609  5412  6205 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 157, thread name: My test thread name)
08-26 04:54:18.609  5412  6205 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 04:54:18.610  5412  6206 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name)
,08-26 04:54:18.610  5412  6206 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: My test thread name)
08-26 04:54:18.611  5412  6206 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 04:54:18.612  5412  5458 E com.test.thalitest.ThaliTestRunner: DiscoveryManager1 isRunning should return true
08-26 04:54:18.612  5412  5458 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
08-26 04:54:18.612  5412  5458 E com.test.thalitest.ThaliTestRunner:      but: was <false>
08-26 04:54:18.612  5412  5458 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 04:54:18.612  5412  5458 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 79
08-26 04:54:18.612  6108  6124 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 04:54:18.612  5412  5458 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  1
08-26 04:54:18.612  6108  6124 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 04:54:18.612  5412  5458 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-26 04:54:18.613  5412  5458 D com.test.thalitest.ThaliTestRunner: Total duration: 24435 ms
08-26 04:54:18.614  5412  5458 I jxcore-log: *Native tests were executed*
08-26 04:54:18.614  5412  5458 I jxcore-log: 
08-26 04:54:18.615  5412  5458 I jxcore-log: Total number of executed tests:  80
08-26 04:54:18.615  5412  5458 I jxcore-log: 
08-26 04:54:18.615  5412  5458 I jxcore-log: Number of passed tests:  79
08-26 04:54:18.615  5412  5458 I jxcore-log: 
,08-26 04:54:18.615  5412  5458 I jxcore-log: Number of failed tests:  1
08-26 04:54:18.615  5412  5458 I jxcore-log: 
08-26 04:54:18.615  5412  5458 I jxcore-log: Number of ignored tests:  0
08-26 04:54:18.615  5412  5458 I jxcore-log: 
08-26 04:54:18.616  5412  5458 I jxcore-log: Total duration:  24435
08-26 04:54:18.616  5412  5458 I jxcore-log: 
08-26 04:54:18.616  5412  5458 I jxcore-log: Failed to execute UT.
08-26 04:54:18.616  5412  5458 I jxcore-log: 
08-26 04:54:18.616  5412  5458 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 04:54:18.616  5412  5458 I jxcore-log: 
,08-26 04:54:18.619  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 04:54:18.619  5412  5458 I jxcore-log: 
08-26 04:54:18.621  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 04:54:18.621  5412  5458 I jxcore-log: 
08-26 04:54:18.623  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 04:54:18.623  5412  5458 I jxcore-log: 
08-26 04:54:18.624  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 04:54:18.624  5412  5458 I jxcore-log: 
08-26 04:54:18.626  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 04:54:18.626  5412  5458 I jxcore-log: 
08-26 04:54:18.626  5412  5412 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 04:54:18.627  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 04:54:18.627  5412  5458 I jxcore-log: 
08-26 04:54:18.630  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.630  5412  5458 I jxcore-log: 
08-26 04:54:18.632  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.632  5412  5458 I jxcore-log: 
08-26 04:54:18.632  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.632  5412  5458 I jxcore-log: 
08-26 04:54:18.633  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.633  5412  5458 I jxcore-log: 
08-26 04:54:18.634  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 04:54:18.634  5412  5458 I jxcore-log: 
08-26 04:54:18.635  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 04:54:18.635  5412  5458 I jxcore-log: 
08-26 04:54:18.636  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.636  5412  5458 I jxcore-log: 
08-26 04:54:18.637  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.637  5412  5458 I jxcore-log: 
08-26 04:54:18.637  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.637  5412  5458 I jxcore-log: 
08-26 04:54:18.638  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.638  5412  5458 I jxcore-log: 
08-26 04:54:18.639  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 04:54:18.639  5412  5458 I jxcore-log: 
08-26 04:54:18.639  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 04:54:18.639  5412  5458 I jxcore-log: 
08-26 04:54:18.640  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 04:54:18.640  5412  5458 I jxcore-log: 
08-26 04:54:18.641  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 04:54:18.641  5412  5458 I jxcore-log: 
08-26 04:54:18.641  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 04:54:18.641  5412  5458 I jxcore-log: 
08-26 04:54:18.642  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 04:54:18.642  5412  5458 I jxcore-log: 
08-26 04:54:18.643  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 04:54:18.643  5412  5458 I jxcore-log: 
08-26 04:54:18.643  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 04:54:18.643  5412  5458 I jxcore-log: 
08-26 04:54:18.644  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 04:54:18.644  5412  5458 I jxcore-log: 
08-26 04:54:18.645  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 04:54:18.645  5412  5458 I jxcore-log: 
08-26 04:54:18.645  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.645  5412  5458 I jxcore-log: 
08-26 04:54:18.646  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.646  5412  5458 I jxcore-log: 
08-26 04:54:18.646  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.646  5412  5458 I jxcore-log: 
08-26 04:54:18.646  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.646  5412  5458 I jxcore-log: 
08-26 04:54:18.647  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.647  5412  5458 I jxcore-log: 
08-26 04:54:18.647  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.647  5412  5458 I jxcore-log: 
08-26 04:54:18.647  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 04:54:18.647  5412  5458 I jxcore-log: 
,08-26 04:54:18.982  5412  5412 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 04:54:18.987  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 04:54:18.987  5412  5458 I jxcore-log: 
,08-26 04:54:19.037  5412  5412 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 04:54:19.040  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 04:54:19.040  5412  5458 I jxcore-log: 
,08-26 04:54:19.055  6207  6207 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-26 04:54:19.061  6207  6207 D AndroidRuntime: CheckJNI is OFF
,08-26 04:54:19.085  6207  6207 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-26 04:54:19.086  5412  5412 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 04:54:19.088  5412  5458 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 04:54:19.088  5412  5458 I jxcore-log: 
,08-26 04:54:19.111  6207  6207 I Radio-JNI: register_android_hardware_Radio DONE
,08-26 04:54:19.126  6207  6207 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 04:54:19.135   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,08-26 04:54:19.136   931   944 I ActivityManager: Killing 5412:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,08-26 04:54:19.198   931  3071 D WifiService: Client connection lost with reason: 4
08-26 04:54:19.198   931  3500 I WindowState: WIN DEATH: Window{e3c2f1c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 04:54:19.198   931  5942 D GraphicsStats: Buffer count: 2
,08-26 04:54:19.231   931   944 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-26 04:54:19.233   931   944 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-26 04:54:19.233   931   954 I art     : Starting a blocking GC Explicit
,08-26 04:54:19.234   931   944 E ActivityManager: Failure starting process com.test.thalitest
08-26 04:54:19.234   931   944 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-26 04:54:19.234   931   944 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 04:54:19.234   931   944 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 04:54:19.234   931   944 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 04:54:19.234   931   944 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-26 04:54:19.234   931   944 I ActivityManager:   Force finishing activity ActivityRecord{6123dc1 u0 com.test.thalitest/.MainActivity t10}
,08-26 04:54:19.242   931  3623 W ActivityManager: Spurious death for ProcessRecord{985a3f1 0:com.test.thalitest/u0a77}, curProc for 5412: null
,08-26 04:54:19.312   931   954 I art     : Explicit concurrent mark sweep GC freed 72740(4MB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 29MB/43MB, paused 1.313ms total 78.917ms
,08-26 04:54:19.333   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-26 04:54:19.336  6207  6207 I art     : System.exit called, status: 0
08-26 04:54:19.336  6207  6207 I AndroidRuntime: VM exiting with result code 0.
,08-26 04:54:19.351   931   954 I ActivityManager: Start proc 6217:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-26 04:54:19.352   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,08-26 04:54:19.358   931   944 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-26 04:54:19.363  6108  6108 D BluetoothMapAppObserver: onReceive
,08-26 04:54:19.364  6108  6108 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-26 04:54:19.366  3731  3993 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 04:54:19.362  3510  3510 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-26 04:54:19.372  3510  6229 I Keyboard.Facilitator.DecoderInitializer: run()
,08-26 04:54:19.383   931  3030 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 04:54:19.384  3510  6229 I Decoder : createOrResetDecoder
,08-26 04:54:19.406   931   942 I sensors : activate
,08-26 04:54:19.406  4899  6232 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 04:54:19.407   931  3621 I sensors : batch
,08-26 04:54:19.408   931  3621 I sensors : activate
,08-26 04:54:19.414   931  2902 I hubconnection: sensorhub said: 'activate 21 enable:0'
,08-26 04:54:19.417   931  2902 I hubconnection: sensorhub said: 'batch 6 flags:0, sampling_rate_Hz:5.00, max_report_latency_us:0'
08-26 04:54:19.417  3603  3603 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-26 04:54:19.418   931  2902 I hubconnection: sensorhub said: 'activate 6 enable:1'
,08-26 04:54:19.428  3510  6229 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 04:54:19.435  3701  3701 D GCM-PT  : Populating db of packages that use GCM
,08-26 04:54:19.416    17    17 W kworker/2:0: type=1400 audit(0.0:76): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-26 04:54:19.426    17    17 W kworker/2:0: type=1400 audit(0.0:77): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-26 04:54:19.447   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 04:54:19.460  3633  3788 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-26 04:54:19.460  4899  6232 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
08-26 04:54:19.461  4899  6232 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 04:54:19.461  4899  6232 E AndroidRuntime: Process: android.process.acore, PID: 4899
08-26 04:54:19.461  4899  6232 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 04:54:19.461  4899  6232 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 04:54:19.456    17    17 W kworker/2:0: type=1400 audit(0.0:78): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: Error inserting uid=0 package_name=android
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:780)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1471)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1341)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker.c(SourceFile:292)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:219)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:124)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 04:54:19.467  3701  3701 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 04:54:19.467  3701  3701 W GCM-PT  : Unable to add package to the database
08-26 04:54:19.467  3510  6229 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /system/app/LatinImeGoogle/LatinImeGoogle.apk (offset=3195532, length=4014912) with up to date LoudsLmContentVersion = 20150512
08-26 04:54:19.467  3701  3701 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-26 04:54:19.468  3701  3701 D AndroidRuntime: Shutting down VM
08-26 04:54:19.469  3701  3701 E AndroidRuntime: FATAL EXCEPTION: main
08-26 04:54:19.469  3701  3701 E AndroidRuntime: Process: com.google.process.gapps, PID: 3701
08-26 04:54:19.469  3701  3701 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 04:54:19.469  3701  3701 E AndroidRuntime,: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 04:54:19.469  3701  3701 E AndroidRuntime: 	... 8 more
08-26 04:54:19.469  3510  6229 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-26 04:54:19.470  3510  6229 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-26 04:54:19.473  3510  6229 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-26 04:54:19.474  3510  6229 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-26 04:54:19.475   931  3500 I ActivityManager: Start proc 6237:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-26 04:54:19.475  3510  6229 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-26 04:54:19.475  3510  6229 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-26 04:54:19.475  3633  3788 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-26 04:54:19.475  3633  3788 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3633
08-26 04:54:19.475  3633  3788 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 04:54:19.475  3633  3788 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 04:54:19.475  3633  3788 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 04:54:19.475  3633  3788 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 04:54:19.475  3633  3788 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 04:54:19.475  3633  3788 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 04:54:19.475  3633  3788 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-26 04:54:19.475  3633  3788 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-26 04:54:19.475  3633  3788 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 04:54:19.475  3633  3788 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 04:54:19.475  3633  3788 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 04:54:19.475  3633  3788 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 04:54:19.476  3510  6229 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-26 04:54:19.476  3510  6229 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-26 04:54:19.476  3510  6229 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-26 04:54:19.476  3510  6229 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-26 04:54:19.477  3510  6229 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-26 04:54:19.477  3510  6229 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-26 04:54:19.479   931  6242 E DropBoxManagerService: Can't write: system_app_crash
08-26 04:54:19.479   931  6242 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
08-26 04:54:19.479   931  6242 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 04:54:19.479   931  6242 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 04:54:19.479   931  6242 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 04:54:19.479   931  6242 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 04:54:19.479   931  6242 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 04:54:19.479   931  6242 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 04:54:19.479   931  6242 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 04:54:19.479   931  6242 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 04:54:19.479   931  6242 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 04:54:19.479   931  6242 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 04:54:19.479   931  6242 E DropBoxManagerService: 	... 5 more
08-26 04:54:19.483   931  5945 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 04:54:19.486   931  6247 E DropBoxManagerService: Can't write: system_app_crash
08-26 04:54:19.486   931  6247 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
08-26 04:54:19.486   931  6247 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 04:54:19.486   931  6247 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 04:54:19.486   931  6247 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 04:54:19.486   931  6247 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 04:54:19.486   931  6247 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 04:54:19.486   931  6247 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 04:54:19.486   931  6247 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 04:54:19.486   931  6247 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 04:54:19.486   931  6247 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 04:54:19.486   931  6247 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 04:54:19.486   931  6247 E DropBoxManagerService: 	... 5 more
08-26 04:54:19.487  4899  6232 I Process : Sending signal. PID: 4899 SIG: 9
08-26 04:54:19.488  3701  3701 I Process : Sending signal. PID: 3701 SIG: 9
08-26 04:54:19.489  3633  3788 I Process : Sending signal. PID: 3633 SIG: 9
08-26 04:54:19.494   931  6245 E DropBoxManagerService: Can't write: system_app_crash
08-26 04:54:19.494   931  6245 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
08-26 04:54:19.494   931  6245 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 04:54:19.494   931  6245 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 04:54:19.494   931  6245 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 04:54:19.494   931  6245 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 04:54:19.494   931  6245 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 04:54:19.494   931  6245 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 04:54:19.494   931  6245 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 04:54:19.494   931  6245 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 04:54:19.494   931  6245 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 04:54:19.494   931  6245 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 04:54:19.494   931  6245 E DropBoxManagerService: 	... 5 more

```
