#### Test 798805944e41806_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-03 12:37:12.939  1875  3385 I EventLogService: Opted in for usage reporting
,08-03 12:37:12.941  1875  3385 I EventLogService: Aggregate from 1470218789932 (log), 1470218789932 (data)
08-03 12:37:13.024  1875  3385 W EventLogAggregator: Unknown tag: snet_gcore
08-03 12:37:13.024  1875  3385 W EventLogAggregator: Unknown tag: snet_launch_service
08-03 12:37:13.146  1875  3385 I ServiceDumpSys: dumping service [account]
08-03 12:37:13.638  3386  3386 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-03 12:37:13.643  3386  3386 D AndroidRuntime: CheckJNI is OFF
08-03 12:37:13.678  3386  3386 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-03 12:37:13.721  3386  3386 I Radio-JNI: register_android_hardware_Radio DONE
08-03 12:37:13.740  3386  3386 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-03 12:37:13.745   873  1745 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-03 12:37:13.815   873  1745 I ActivityManager: Start proc 3396:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-03 12:37:13.819  3386  3386 D AndroidRuntime: Shutting down VM
08-03 12:37:13.961  3396  3396 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-03 12:37:13.992  3396  3396 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-03 12:37:14.004  3396  3396 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 7190-7196)
08-03 12:37:14.004  3396  3396 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 12:37:14.024  3396  3396 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b160ab0}
08-03 12:37:14.025  3396  3396 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 12:37:14.026  3396  3396 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 12:37:14.036  3396  3396 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-03 12:37:14.038  3396  3396 E SysUtils: ApplicationContext is null in ApplicationStatus
08-03 12:37:14.055  3396  3411 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,08-03 12:37:14.066  3396  3396 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-03 12:37:14.081  3396  3396 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-03 12:37:14.081  3396  3396 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 12:37:14.081  3396  3396 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-03 12:37:14.081  3396  3396 I Adreno  : Build Date                       : 10/20/15
08-03 12:37:14.081  3396  3396 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-03 12:37:14.081  3396  3396 I Adreno  : Local Branch                     : M14
08-03 12:37:14.081  3396  3396 I Adreno  : Remote Branch                    : 
08-03 12:37:14.081  3396  3396 I Adreno  : Remote Branch                    : 
08-03 12:37:14.081  3396  3396 I Adreno  : Reconstruct Branch               : 
,08-03 12:37:14.160   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6bd094a:true
,08-03 12:37:14.231  3396  3396 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-03 12:37:14.250  3396  3396 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-03 12:37:14.337  3396  3433 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-03 12:37:14.363  3396  3420 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-03 12:37:14.410  3396  3433 I OpenGLRenderer: Initialized EGL, version 1.4
,08-03 12:37:14.508   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +620ms (total +731ms)
,08-03 12:37:14.517  1660  1660 I Keyboard.Facilitator: onFinishInput()
,08-03 12:37:14.584  3396  3396 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3396
,08-03 12:37:14.746  3396  3396 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-03 12:37:14.925  3396  3435 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1697711824
,08-03 12:37:14.933  3396  3435 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 12:37:14.933  3396  3435 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 12:37:14.933  3396  3435 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 12:37:14.933  3396  3435 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 12:37:14.933  3396  3435 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-03 12:37:14.933  3396  3435 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a542c07 added. We now have 1 listener(s)
,08-03 12:37:14.937  3396  3435 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-03 12:37:14.938  3396  3435 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 12:37:14.939  3396  3435 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:37:14.939  3396  3435 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-03 12:37:14.942  3396  3435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4476cd2 added. We now have 1 listener(s)
08-03 12:37:14.942  3396  3435 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 12:37:14.949  3396  3435 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 12:37:14.949  3396  3435 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-03 12:37:14.949  3396  3435 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-03 12:37:14.949  3396  3435 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-03 12:37:14.949  3396  3435 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-03 12:37:14.950   873  1313 D WifiService: New client listening to asynchronous messages
08-03 12:37:14.951  3396  3435 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:37:14.951  3396  3435 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-03 12:37:14.953  3396  3435 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:14.953  3396  3435 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:37:14.953  3396  3435 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:14.953  3396  3435 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-03 12:37:14.953  3396  3435 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:14.953  3396  3435 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:37:14.953  3396  3435 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:14.953  3396  3435 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:14.953  3396  3435 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:37:14.953  3396  3435 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-03 12:37:14.953  3396  3435 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:37:14.954  3396  3435 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 12:37:14.955  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:14.981  3396  3396 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-03 12:37:16.287  3396  3442 W jxcore-log: Initializing JXcore engine
,08-03 12:37:16.288  3396  3442 W jxcore-log: JXcore engine is ready
,08-03 12:37:16.326  3442  3442 W Thread-289: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-03 12:37:16.326  3442  3442 W Thread-289: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9581]" dev="sockfs" ino=9581 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-03 12:37:16.326  3442  3442 W Thread-289: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-03 12:37:16.326  3442  3442 W Thread-289: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[22353]" dev="sockfs" ino=22353 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-03 12:37:16.339  3396  3442 W jxcore-log: Starting JXcore engine
,08-03 12:37:16.418  3396  3442 W jxcore-log: Platform android
08-03 12:37:16.418  3396  3442 W jxcore-log: 
,08-03 12:37:16.418  3396  3442 W jxcore-log: Process ARCH arm
08-03 12:37:16.418  3396  3442 W jxcore-log: 
,08-03 12:37:16.629  3396  3442 I jxcore-log: JXcore Cordova bridge is ready!
08-03 12:37:16.629  3396  3442 I jxcore-log: 
,08-03 12:37:16.630  3396  3442 W jxcore-log: JXcore engine is started
,08-03 12:37:16.640  3396  3435 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-03 12:37:16.645  3396  3396 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-03 12:37:31.933  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-03 12:37:31.933  3396  3442 I jxcore-log: 
,08-03 12:37:31.936  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-03 12:37:31.936  3396  3442 I jxcore-log: 
,08-03 12:37:31.938  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:31.938  3396  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:37:31.938  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:31.938  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-03 12:37:31.938  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:31.938  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:37:31.938  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:31.938  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:31.938  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:31.938  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:31.938  3396  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:37:31.940  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-03 12:37:31.940  3396  3442 I jxcore-log: 
,08-03 12:37:31.942  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-03 12:37:31.942  3396  3442 I jxcore-log: 
,08-03 12:37:32.278  3396  3442 D ExecuteNativeTests: Running unit tests
,08-03 12:37:32.335  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:37:32.335  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 added. We now have 2 listener(s)
,08-03 12:37:32.336  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 12:37:32.337  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:37:32.337  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 12:37:32.337  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:37:32.337  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 added. We now have 2 listener(s)
08-03 12:37:32.337  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 12:37:32.337  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 12:37:32.342  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 12:37:32.346  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 12:37:32.346  3396  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:37:32.346  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:32.346  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-03 12:37:32.346  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:32.346  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:37:32.346  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:32.346  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:32.346  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:37:32.346  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:32.347  3396  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:32.347  3396  3442 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:37:32.349  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:32.355  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 12:37:32.356  3396  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-03 12:37:32.356  3396  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-03 12:37:32.361  3396  3442 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-03 12:37:32.362  3396  3442 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-03 12:37:32.362  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-03 12:37:32.363  3396  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-03 12:37:32.363  3396  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-03 12:37:32.364  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 12:37:32.368  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 12:37:32.369  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 12:37:32.369  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 12:37:32.369  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 12:37:32.369  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 12:37:32.369  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:37:32.369  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 removed from the list
08-03 12:37:32.369  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.370  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 removed from the list
08-03 12:37:32.370  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.370  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:37:32.370  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.370  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.371  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.371  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.371  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.371  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.373  3396  3442 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-03 12:37:32.374  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.374  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.374  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.374  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.374  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.374  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.374  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.374  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.374  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.375  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.375  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.375  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.375  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.375  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.375  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.376  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.376  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.376  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.381  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 12:37:32.381  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 12:37:32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 12:37:,32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 12:37:32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 12:37:32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 12:37:32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 12:37:32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 12:37:32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 12:37:32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 12:37:32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 12:37:32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 12:37:32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 12:37:32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 12:37:32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 12:37:32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 12:37:32.382  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 12:37:32.383  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 12:37:32.383  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 12:37:32.383  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 12:37:32.383  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 12:37:32.383  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 12:37:32.383  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 12:37:32.383  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 12:37:32.383  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 12:37:32.383  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 12:37:32.383  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 12:37:32.383  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 12:37:32.383  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 12:37:32.383  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 12:37:32.383  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 12:37:32.384  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.384  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.384  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.384  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.384  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.384  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.384  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.384  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.384  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.384  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.384  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.384  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.384  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.384  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.385  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.385  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.385  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.385  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.386  3396  3442 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 12:37:32.387  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:37:32.388  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:32.388  3396  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:37:32.388  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:32.388  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-03 12:37:32.388  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:32.388  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:37:32.388  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:32.388  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:32.388  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:37:32.388  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:32.388  3396  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:37:32.389  3396  3442 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:37:32.389  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:37:32.389  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 12:37:32.389  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:32.389  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 12:37:32.389  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:37:32.389  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 12:37:32.392  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-03 12:37:32.392  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-03 12:37:32.393  3396  3442 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 12:37:32.393  3396  3396 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-03 12:37:32.393  3396  3442 I io.jxcore.node.ConnectionHelper: start: OK
08-03 12:37:32.394  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:32.394  3396  3442 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-03 12:37:32.395  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.395  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.395  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-03 12:37:32.396  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.396  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 12:37:32.396  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 12:37:32.396  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 12:37:32.396  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 12:37:32.396  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 12:37:32.397  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 12:37:32.397  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:37:32.397  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 12:37:32.398  3396  3396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 12:37:32.398  3396  3396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 12:37:32.398  3396  3396 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 12:37:32.398  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.398  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.398  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:37:32.398  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.398  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.398  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.398  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.398  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.399  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.399  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.399  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.399  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.399  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.399  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.400  3396  3442 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 12:37:32.402  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:37:32.403  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:32.403  3396  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:37:32.403  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:32.403  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-03 12:37:32.403  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:32.403  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:37:32.403  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:32.403  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:32.403  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:37:32.403  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:32.403  3396  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:37:32.403  3396  3442 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:37:32.404  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:37:32.404  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 12:37:32.404  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 12:37:32.404  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:37:32.404  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 12:37:32.404  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:32.406  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-03 12:37:32.406  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-03 12:37:32.406  3396  3442 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 12:37:32.406  3396  3396 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-03 12:37:32.406  3396  3442 I io.jxcore.node.ConnectionHelper: start: OK
08-03 12:37:32.406  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.406  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.406  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-03 12:37:32.406  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.406  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 12:37:32.406  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 12:37:32.407  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 12:37:32.407  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 12:37:32.407  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 12:37:32.407  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 12:37:32.407  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:37:32.408  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 12:37:32.408  3396  3396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 12:37:32.408  3396  3396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 12:37:32.408  3396  3396 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 12:37:32.408  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.408  3396  3442 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 12:37:32.408  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.408  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.408  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.408  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.408  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:37:32.409  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.409  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.409  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.409  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.409  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.409  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.409  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.410  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.410  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.410  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.410  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.410  3396  3442 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-03 12:37:32.411  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.411  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.411  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.411  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.411  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.411  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.411  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.411  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.411  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.411  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.412  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.412  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.412  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.412  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.412  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.412  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.412  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.412  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.413  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 12:37:32.413  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.413  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.413  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.413  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.413  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.413  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.414  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.414  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.414  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.414  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.414  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.414  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.414  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.414  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.415  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.415  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.415  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.415  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.415  3396  3442 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-03 12:37:32.415  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.415  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.415  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.416  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.416  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.416  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.416  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.416  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.416  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.416  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.416  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.416  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.416  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.416  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.416  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.416  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.417  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.417  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.417  3396  3442 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-03 12:37:32.417  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.417  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.417  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.417  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.417  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.418  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.418  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.418  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.418  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.418  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.418  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.418  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.418  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.418  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.418  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.418  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.418  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.418  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.419  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 12:37:32.419  3396  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 12:37:32.419  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 12:37:32.419  3396  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 12:37:32.419  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 12:37:32.419  3396  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 12:37:32.419  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.420  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.420  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.420  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.420  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.420  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.420  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.420  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.420  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.420  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.420  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.420  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.420  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.420  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.421  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.421  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.421  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.421  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.422  3396  3442 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 12:37:32.422  3396  3442 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 12:37:32.422  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 12:37:32.432  3396  3442 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 12:37:32.433  3396  3442 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-03 12:37:32.433  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 12:37:32.433  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 12:37:32.434  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 12:37:32.434  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 12:37:32.434  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 12:37:32.435  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 12:37:32.437  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 12:37:32.438  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 12:37:32.438  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 12:37:32.438  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 12:37:32.438  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 12:37:32.438  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 12:37:32.438  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 12:37:32.438  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 12:37:32.438  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 12:37:32.438  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 12:37:32.438  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 12:37:32.438  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 12:37:32.438  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 12:37:32.439  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 12:37:32.439  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 12:37:32.439  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 12:37:32.439  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 12:37:32.439  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 12:37:32.439  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 12:37:32.439  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 12:37:32.439  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 12:37:32.439  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 12:37:32.439  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 12:37:32.439  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 12:37:32.439  3396  3442 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-03 12:37:32.440  3396  3442 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 12:37:32.440  3396  3442 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-03 12:37:32.440  3396  3442 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 12:37:32.440  3396  3442 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 12:37:32.440  3396  3442 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-03 12:37:32.440  3396  3442 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 12:37:32.440  3396  3442 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 12:37:32.440  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-03 12:37:32.442  3396  3442 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-03 12:37:32.442  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-03 12:37:32.442  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-03 12:37:32.442  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-03 12:37:32.443  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-03 12:37:32.443  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-03 12:37:32.443  3396  3442 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-03 12:37:32.443  3396  3442 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 12:37:32.443  3396  3442 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-03 12:37:32.443  3396  3443 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 353)
08-03 12:37:32.444  3396  3443 E BluetoothDevice: Bluetooth is not enabled
08-03 12:37:32.444  3396  3443 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 353)
08-03 12:37:32.444  3396  3443 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 353)
08-03 12:37:32.444  3396  3443 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 353)
08-03 12:37:32.444  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.444  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.444  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.444  3396  3396 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
08-03 12:37:32.444  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.444  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.444  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.445  3396  3396 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
08-03 12:37:32.445  3396  3396 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 12:37:32.445  3396  3396 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 12:37:32.445  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-03 12:37:32.446  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.446  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.446  3396  3443 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 353
08-03 12:37:32.446  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.446  3396  3443 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 353)
08-03 12:37:32.446  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.446  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.446  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.446  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.446  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.447  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.447  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.447  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.447  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.447  3396  3444 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 353
08-03 12:37:32.448  3396  3442 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-03 12:37:32.450  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.450  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.450  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.450  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.450  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.450  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.450  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.451  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.451  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.451  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.451  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 12:37:32.451  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.451  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.451  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.451  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.451  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 12:37:32.452  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.452  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.452  3396  3442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-03 12:37:32.452  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-03 12:37:32.452  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.453  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.453  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.453  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 12:37:32.453  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.453  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.453  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 12:37:32.453  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.453  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 12:37:32.453  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 12:37:32.453  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.453  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.453  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.454  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 12:37:32.454  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 12:37:32.454  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.454  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.454  3396  3442 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-03 12:37:32.454  3396  3442 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-03 12:37:32.454  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 12:37:32.455  3396  3442 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-03 12:37:32.455  3396  3442 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 12:37:32.455  3396  3442 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,08-03 12:37:32.455  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 12:37:32.455  3396  3442 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-03 12:37:32.455  3396  3442 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 12:37:32.455  3396  3442 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 12:37:32.455  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 12:37:32.455  3396  3442 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-03 12:37:32.455  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.455  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 12:37:32.455  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.455  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.456  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.456  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:37:32.456  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.456  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 12:37:32.456  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.456  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.456  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.456  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:37:32.456  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.456  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.456  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 12:37:32.456  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.457  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.457  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.457  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 12:37:32.457  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.457  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.457  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
,08-03 12:37:32.457  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.458  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.458  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.458  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 12:37:32.458  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.458  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.458  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
,08-03 12:37:32.458  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.458  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.458  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.458  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.458  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.458  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.458  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.458  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.459  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.459  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:37:32.459  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.459  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.459  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.459  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.459  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.459  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.459  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.459  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:37:32.460  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.460  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.460  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 12:37:32.460  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.461  3396  3442 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-03 12:37:32.461  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:37:32.461  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-03 12:37:32.462  3396  3442 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-03 12:37:32.462  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
08-03 12:37:32.462  3396  3396 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-03 12:37:32.462  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.462  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-03 12:37:32.462  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.462  3396  3442 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
,08-03 12:37:32.462  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.462  3396  3396 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-03 12:37:32.462  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.463  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-03 12:37:32.463  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 12:37:32.463  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 12:37:32.463  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 12:37:32.463  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.464  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 12:37:32.464  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
,08-03 12:37:32.464  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.464  3396  3396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 12:37:32.464  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.464  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.464  3396  3396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 12:37:32.464  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.464  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-03 12:37:32.464  3396  3396 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 12:37:32.464  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.464  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.464  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.464  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.464  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.464  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 12:37:32.465  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.465  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.465  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.465  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.465  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 12:37:32.465  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.465  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.466  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 12:37:32.466  3396  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-03 12:37:32.466  3396  3442 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-03 12:37:32.466  3396  3442 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 12:37:32.466  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 12:37:32.467  3396  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 12:37:32.467  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 12:37:32.467  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.467  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.467  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.467  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.467  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.467  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.467  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.467  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.467  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.467  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.467  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.467  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.468  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.469  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 12:37:32.469  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.469  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.469  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.474  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.475  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:32.477  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.478  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.478  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.478  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.478  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.478  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.478  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.478  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.478  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 12:37:32.479  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.479  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.479  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.479  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.479  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.479  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.479  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.480  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:32.480  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 12:37:32.480  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:32.481  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:32.481  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.481  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.481  3396  3442 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@556ae1 not in the list
08-03 12:37:32.481  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.481  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.481  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:32.481  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.481  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:32.481  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:32.482  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:37:32.482  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:32.482  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:32.482  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:32.482  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f54006 not in the list
08-03 12:37:32.483  3396  3442 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-03 12:37:32.483  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 12:37:32.483  3396  3442 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-03 12:37:32.483  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 12:37:32.484  3396  3442 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-03 12:37:32.484  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 12:37:32.486  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-03 12:37:32.486  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-03 12:37:32.487  3396  3442 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-03 12:37:32.487  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 12:37:32.487  3396  3442 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-03 12:37:32.487  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 12:37:32.487  3396  3442 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-03 12:37:32.487  3396  3442 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-03 12:37:32.488  3396  3442 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-03 12:37:32.488  3396  3442 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-03 12:37:32.489  3396  3442 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-03 12:37:32.489  3396  3442 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-03 12:37:32.489  3396  3442 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-03 12:37:32.489  3396  3442 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-03 12:37:32.490  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:37:32.490  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d946c60 added. We now have 2 listener(s)
08-03 12:37:32.490  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:37:32.493   873  1767 D WifiService: setWifiEnabled: true pid=3396, uid=10000
08-03 12:37:32.493   873  1767 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 12:37:32.505  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 12:37:32.505  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3779519 added. We now have 3 listener(s)
08-03 12:37:32.505  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:37:32.506  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:32.506  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 12:37:32.507  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 12:37:32.507  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ae49de added. We now have 4 listener(s)
,08-03 12:37:32.507  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:37:32.509   873   890 I ActivityManager: Start proc 3446:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
08-03 12:37:32.509  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:37:32.509  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b6b47bf added. We now have 5 listener(s)
08-03 12:37:32.509  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:37:32.511   873  1687 D WifiService: setWifiEnabled: false pid=3396, uid=10000
08-03 12:37:32.511   873  1687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 12:37:32.511   873  1312 D WifiConfigStore: Loading config and enabling all networks 
,08-03 12:37:32.515  3396  3396 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:32.515  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:32.515  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:32.515  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-03 12:37:32.515  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:32.515  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:37:32.515  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:32.515  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:32.515  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:37:32.515  3396  3396 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:32.515  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:32.525   873   886 I ActivityManager: Start proc 3457:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-03 12:37:32.527  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 12:37:32.528  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 12:37:32.528  3396  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:37:32.528  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:32.528  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-03 12:37:32.528  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:32.528  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:37:32.528  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:32.528  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:32.528  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:37:32.528  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:32.528  3396  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:37:32.528  3396  3442 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:37:32.529  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:32.535   873  1312 D WifiConfigStore: loaded 0 passpoint configs
,08-03 12:37:32.536   873  1312 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-03 12:37:32.536   873  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-03 12:37:32.537   873  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-03 12:37:32.538   873  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-03 12:37:32.538   873  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-03 12:37:32.538   873  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-03 12:37:32.538   873  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-03 12:37:32.561  3457  3457 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-03 12:37:32.587   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-03 12:37:32.588   873  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 12:37:32.588   371   871 D CommandListener: Setting iface cfg
,08-03 12:37:32.589   873  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
08-03 12:37:32.589   873  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-03 12:37:32.598   873  1312 E native  : do suspend true
,08-03 12:37:32.598   873  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-03 12:37:32.600  3457  3457 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-03 12:37:32.605   873  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-03 12:37:32.620   873   884 I ActivityManager: Killing 2683:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-03 12:37:32.624  1477  1477 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,08-03 12:37:32.624  1477  1477 W wpa_supplicant: wlan0: Failed to initiate AP scan
,08-03 12:37:32.661   873  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 12:37:32.663  3446  3446 D AdapterServiceConfig: Adding HeadsetService
,08-03 12:37:32.663  3446  3446 D AdapterServiceConfig: Adding A2dpService
,08-03 12:37:32.663  3446  3446 D AdapterServiceConfig: Adding HidService
,08-03 12:37:32.663  3446  3446 D AdapterServiceConfig: Adding HealthService
,08-03 12:37:32.664  3446  3446 D AdapterServiceConfig: Adding PanService
08-03 12:37:32.664  3446  3446 D AdapterServiceConfig: Adding GattService
08-03 12:37:32.664  3446  3446 D AdapterServiceConfig: Adding BluetoothMapService
08-03 12:37:32.668  3396  3396 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:32.668  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:32.668  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:32.668  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-03 12:37:32.668  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:32.668  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:37:32.668  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:32.668  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:32.668  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:37:32.668  3396  3396 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:32.668  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:37:32.672  3396  3396 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:32.672  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:32.672  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:32.672  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-03 12:37:32.672  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:32.672  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:37:32.672  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:32.672  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:32.672  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:37:32.672  3396  3396 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:32.672  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:37:32.673  1841  2068 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 12:37:32.697   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5f96426:true
08-03 12:37:32.697  3446  3446 D BluetoothAdapterState: make() - Creating AdapterState
,08-03 12:37:32.700  3446  3446 I bt_bluedroid: init
,08-03 12:37:32.700  3446  3486 I BluetoothAdapterState: Entering OffState
,08-03 12:37:32.703  3446  3487 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-03 12:37:32.704  3446  3487 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 12:37:32.704  3446  3487 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-03 12:37:32.704  3446  3487 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-03 12:37:32.705  3446  3446 I bt_bluedroid: get_profile_interface socket
,08-03 12:37:32.707  3446  3446 I bt_bluedroid: get_profile_interface sdp
,08-03 12:37:32.707  3446  3490 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 12:37:32.708  3446  3490 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 12:37:32.709  3446  3462 I bt_bluedroid: config_hci_snoop_log
08-03 12:37:32.710   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-03 12:37:32.713  3446  3486 D BluetoothAdapterState: Current state: OFF, message: 0
,08-03 12:37:32.714  3446  3486 D BluetoothAdapterProperties: Setting state to 14
08-03 12:37:32.714  3446  3486 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-03 12:37:32.716  3446  3486 D BluetoothBondStateMachine: make
,08-03 12:37:32.718  3446  3491 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-03 12:37:32.721  3446  3486 I BluetoothAdapterState: Entering PendingCommandState
,08-03 12:37:32.722  3446  3446 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-03 12:37:32.724  3446  3446 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:32.725  3446  3446 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 12:37:32.725  3446  3446 D BtGatt.GattService: Received start request. Starting profile...
08-03 12:37:32.725  3446  3446 D BtGatt.GattService: start()
08-03 12:37:32.725  3446  3446 I bt_bluedroid: get_profile_interface gatt
08-03 12:37:32.726  3446  3446 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
08-03 12:37:32.726  3446  3446 D BtGatt.AdvertiseManager: advertise manager created
,08-03 12:37:32.732  3446  3446 V BluetoothAdapterState: isTurningOff()=false
08-03 12:37:32.732  3446  3446 V BluetoothAdapterState: isTurningOn()=false
08-03 12:37:32.732  3446  3446 V BluetoothAdapterState: isBleTurningOn()=true
,08-03 12:37:32.732  3446  3446 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:32.732  3446  3486 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-03 12:37:32.733  3446  3486 I bt_bluedroid: enable
,08-03 12:37:32.733  3446  3487 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-03 12:37:32.734  3446  3487 I bt_hci  : start_up
,08-03 12:37:32.742  3446  3487 I bt_vendor: alloc value 0xb39f1189
08-03 12:37:32.742  3446  3487 I bt_vendor: init
08-03 12:37:32.742  3446  3487 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-03 12:37:32.742  3446  3487 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-03 12:37:32.848  3446  3487 D bt_hci  : start_up starting async portion
,08-03 12:37:32.849  3446  3494 I bt_hci  : event_finish_startup
,08-03 12:37:32.849  3446  3494 I bt_hci_h4: hal_open
,08-03 12:37:32.850  3446  3494 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-03 12:37:32.859  3446  3494 I bt_userial_vendor: device fd = 51 open
,08-03 12:37:32.893  3446  3494 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 12:37:32.925  3446  3494 D bt_hwcfg: Chipset BCM4354A2
,08-03 12:37:32.925  3446  3494 D bt_hwcfg: Target name = [BCM4354A2]
08-03 12:37:32.926  3446  3494 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-03 12:37:32.965  3396  3396 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 12:37:33.590  3446  3494 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-03 12:37:33.591  3446  3494 D bt_hwcfg: Settlement delay -- 100 ms
,08-03 12:37:33.592  3446  3494 I bt_hwcfg: Setting fw settlement delay to 100 
,08-03 12:37:33.708  3446  3494 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 12:37:33.710  3446  3494 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-03 12:37:33.740  3446  3494 I bt_hwcfg: vendor lib fwcfg completed
,08-03 12:37:33.740  3446  3494 I bt_vendor: firmware callback
08-03 12:37:33.740  3446  3494 I bt_hci  : firmware_config_callback
,08-03 12:37:33.751  3446  3496 I bt_btu  : btu_task pending for preload complete event
,08-03 12:37:33.751  3446  3496 I bt_btu_task: Bluetooth chip preload is complete
,08-03 12:37:33.752  3446  3496 I bt_btu  : btu_task received preload complete event
,08-03 12:37:33.765  3446  3496 I         : BTE_InitTraceLevels -- TRC_HCI
,08-03 12:37:33.765  3446  3496 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-03 12:37:33.765  3446  3496 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-03 12:37:33.766  3446  3496 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-03 12:37:33.766  3446  3496 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 12:37:33.766  3446  3496 I         : BTE_InitTraceLevels -- TRC_A2D
,08-03 12:37:33.767  3446  3496 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-03 12:37:33.768  3446  3496 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 12:37:33.769  3446  3496 I         : BTE_InitTraceLevels -- TRC_GAP
,08-03 12:37:33.769  3446  3496 I         : BTE_InitTraceLevels -- TRC_PAN
08-03 12:37:33.770  3446  3496 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 12:37:33.771  3446  3496 I         : BTE_InitTraceLevels -- TRC_GATT
,08-03 12:37:33.771  3446  3496 I         : BTE_InitTraceLevels -- TRC_SMP
,08-03 12:37:33.772  3446  3496 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 12:37:33.772  3446  3496 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-03 12:37:33.904  3446  3496 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb396ed9d
,08-03 12:37:33.904  3446  3496 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb396ed9d 
,08-03 12:37:33.935  3446  3490 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-03 12:37:33.937  3446  3490 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-03 12:37:33.939  3446  3490 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 12:37:33.945  3446  3490 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 12:37:33.949  3446  3490 D BluetoothAdapterProperties: Scan Mode:20
08-03 12:37:33.949  3446  3490 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-03 12:37:33.950  3446  3490 D bt_hci  : do_postload posting postload work item
08-03 12:37:33.950  3446  3494 I bt_hci  : event_postload
,08-03 12:37:33.950  3446  3494 I bt_vendor: sco_config_cb
,08-03 12:37:33.950  3446  3494 I bt_hci  : sco_config_callback postload finished.
,08-03 12:37:33.954  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:33.958  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:33.960  3446  3490 D bt_bte_conf: Device ID record 1 : primary
,08-03 12:37:33.961  3446  3490 D bt_bte_conf:   vendorId            = 000f
08-03 12:37:33.961  3446  3490 D bt_bte_conf:   vendorIdSource      = 0001
,08-03 12:37:33.961  3446  3490 D bt_bte_conf:   product             = 1200
,08-03 12:37:33.961  3446  3490 D bt_bte_conf:   version             = 1436
,08-03 12:37:33.962  3446  3490 D bt_bte_conf:   clientExecutableURL = 
08-03 12:37:33.962  3446  3490 D bt_bte_conf:   serviceDescription  = 
,08-03 12:37:33.962  3446  3490 D bt_bte_conf:   documentationURL    = 
,08-03 12:37:33.962  3446  3490 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-03 12:37:33.963  3446  3494 I bt_vendor: low_power_mode_cb
,08-03 12:37:33.963  3446  3487 D bt_stack_manager: event_start_up_stack finished
08-03 12:37:33.968  3446  3486 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-03 12:37:33.968  3446  3486 D BluetoothAdapterProperties: Setting state to 15
,08-03 12:37:33.968  3446  3486 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-03 12:37:33.969  3446  3486 I BluetoothAdapterState: Entering BleOnState
,08-03 12:37:33.973  3446  3486 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-03 12:37:33.973  3446  3486 D BluetoothAdapterProperties: Setting state to 11
08-03 12:37:33.973  3446  3486 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-03 12:37:33.978  3446  3446 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:33.981  3446  3446 D HeadsetService: Received start request. Starting profile...
,08-03 12:37:33.983  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:33.985  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:33.986  3446  3446 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-03 12:37:33.986  3446  3446 D HeadsetStateMachine: make
,08-03 12:37:33.998   873   886 I ActivityManager: Start proc 3504:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-03 12:37:34.003  3446  3446 D HeadsetStateMachine: max_hf_connections = 1
,08-03 12:37:34.003  3446  3446 I bt_bluedroid: get_profile_interface handsfree
08-03 12:37:34.003  3446  3490 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-03 12:37:34.004  3446  3490 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-03 12:37:34.011  3446  3486 I BluetoothAdapterState: Entering PendingCommandState
,08-03 12:37:34.013  3446  3446 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:34.013   873   873 D BluetoothA2dp: Proxy object connected
,08-03 12:37:34.014  3446  3446 D A2dpService: Received start request. Starting profile...
,08-03 12:37:34.015  3446  3446 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 12:37:34.015  3446  3446 I bt_bluedroid: get_profile_interface avrcp
,08-03 12:37:34.023  3446  3446 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-03 12:37:34.023  3446  3446 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 12:37:34.023  3446  3446 D A2dpStateMachine: make
,08-03 12:37:34.025  3446  3446 I bt_bluedroid: get_profile_interface a2dp
,08-03 12:37:34.025  3446  3490 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-03 12:37:34.028  3446  3517 D A2dpStateMachine: Enter Disconnected: -2
08-03 12:37:34.029  3446  3446 I BluetoothHidServiceJni: classInitNative: succeeds
08-03 12:37:34.030  3446  3446 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba,
08-03 12:37:34.031  1360  1360 D BluetoothInputDevice: Proxy object connected
,08-03 12:37:34.032  3446  3446 D HidService: Received start request. Starting profile...
,08-03 12:37:34.032  3446  3446 I bt_bluedroid: get_profile_interface hidhost
,08-03 12:37:34.032  3446  3446 D HidService: setHidService(): set to: null
,08-03 12:37:34.032  1360  1360 D HidProfile: Bluetooth service connected
08-03 12:37:34.032  3446  3490 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39503e5
,08-03 12:37:34.032  3446  3490 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-03 12:37:34.034  3446  3446 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-03 12:37:34.034  3446  3446 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:34.035  3446  3446 D HealthService: Received start request. Starting profile...
,08-03 12:37:34.036  3446  3446 I bt_bluedroid: get_profile_interface health
,08-03 12:37:34.037  3446  3446 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-03 12:37:34.038  3446  3446 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:34.039  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 12:37:34.039  3446  3446 D PanService: Received start request. Starting profile...
08-03 12:37:34.039  3446  3446 D BluetoothPanServiceJni: initializeNative(L110): pan,
08-03 12:37:34.039  3446  3446 I bt_bluedroid: get_profile_interface pan
,08-03 12:37:34.039  1360  1360 D PanProfile: Bluetooth service connected
08-03 12:37:34.040  3446  3490 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan,
08-03 12:37:34.041  3446  3446 V BluetoothAdapterState: isTurningOff()=false
08-03 12:37:34.041  3446  3446 V BluetoothAdapterState: isTurningOn()=true
,08-03 12:37:34.041  3446  3446 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 12:37:34.041  3446  3446 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 12:37:34.043  3446  3503 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-03 12:37:34.045  3446  3446 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
08-03 12:37:34.046  1360  1360 D BluetoothMap: Proxy object connected
08-03 12:37:34.046  3446  3446 D BluetoothMapService: Received start request. Starting profile...
08-03 12:37:34.046  3446  3446 D BluetoothMapService: start()
08-03 12:37:34.046  1360  1360 D MapProfile: Bluetooth service connected
08-03 12:37:34.047  1360  1360 D BluetoothMap: getConnectedDevices()
08-03 12:37:34.048  1360  1360 D BluetoothMap: Bluetooth is Not enabled
,08-03 12:37:34.049  3446  3446 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-03 12:37:34.049  3446  3446 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-03 12:37:34.049  3446  3446 D BluetoothMapAppObserver: createReceiver()
,08-03 12:37:34.050  3446  3446 D BluetoothMapAppObserver: initObservers()
,08-03 12:37:34.050  3446  3446 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-03 12:37:34.056  3446  3446 V BluetoothAdapterState: isTurningOff()=false
,08-03 12:37:34.056  3446  3446 V BluetoothAdapterState: isTurningOn()=true
08-03 12:37:34.056  3446  3446 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:34.057  3446  3446 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:34.057  3446  3446 V BluetoothAdapterState: isTurningOff()=false
08-03 12:37:34.057  3446  3446 V BluetoothAdapterState: isTurningOn()=true
08-03 12:37:34.057  3446  3446 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:34.057  3446  3446 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 12:37:34.057  3446  3446 V BluetoothAdapterState: isTurningOff()=false
08-03 12:37:34.057  3446  3446 V BluetoothAdapterState: isTurningOn()=true
08-03 12:37:34.057  3446  3446 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:34.057  3446  3446 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:34.057  3446  3446 V BluetoothAdapterState: isTurningOff()=false
08-03 12:37:34.058  3446  3446 V BluetoothAdapterState: isTurningOn()=true
08-03 12:37:34.058  3446  3446 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:34.058  3446  3446 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 12:37:34.058  3446  3446 V BluetoothAdapterState: isTurningOff()=false
08-03 12:37:34.058  3446  3446 V BluetoothAdapterState: isTurningOn()=true
08-03 12:37:34.058  3446  3446 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:34.058  3446  3446 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:34.058  3504  3504 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-03 12:37:34.058  3446  3486 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-03 12:37:34.058  3446  3486 D BluetoothAdapterProperties: ScanMode =  20
08-03 12:37:34.058  3446  3486 D BluetoothAdapterProperties: State =  11
,08-03 12:37:34.060  3446  3490 D BluetoothAdapterProperties: Scan Mode:21
08-03 12:37:34.060  3446  3486 D BluetoothAdapterProperties: Setting state to 12
,08-03 12:37:34.060  3446  3486 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-03 12:37:34.060  1360  1853 D BluetoothPan: onBluetoothStateChange on: true
08-03 12:37:34.060  3446  3490 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 12:37:34.061  3446  3486 I BluetoothAdapterState: Entering OnState
08-03 12:37:34.061  1360  1379 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-03 12:37:34.062  1360  1383 D BluetoothMap: onBluetoothStateChange: up=true
08-03 12:37:34.062  1748  1938 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:37:34.063  3396  3396 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-03 12:37:34.064  1360  1853 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 12:37:34.065   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true,
,08-03 12:37:34.065   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:37:34.065   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 12:37:34.065   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 12:37:34.066   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-03 12:37:34.067  3396  3396 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-03 12:37:34.067  3446  3446 D BluetoothMapService: onReceive
,08-03 12:37:34.067  3446  3446 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-03 12:37:34.068  3446  3446 D BluetoothMapService: STATE_ON
,08-03 12:37:34.069  3396  3396 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-03 12:37:34.072  1360  1675 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-03 12:37:34.073  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:34.073  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:34.073  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:34.073  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:34.073  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:34.073  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:34.073  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:34.073  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:34.076  3446  3446 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-03 12:37:34.077  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:37:34.077  1360  1360 D BluetoothA2dp: Proxy object connected
08-03 12:37:34.077  1360  1675 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-03 12:37:34.077  3446  3446 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-03 12:37:34.078  3446  3446 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 12:37:34.081  3446  3446 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 12:37:34.082  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:34.082  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:34.082  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:34.082  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:34.082  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:34.082  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:34.082  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:34.082  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:34.082  3446  3446 D ObexServerSockets: Succeed to create listening sockets 
08-03 12:37:34.083  3446  3446 D ObexServerSockets0: startAccept()
08-03 12:37:34.083  3446  3446 D ObexServerSockets0: prepareForNewConnect()
,08-03 12:37:34.084  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:34.086  3446  3446 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-03 12:37:34.086  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:34.086  3446  3446 D BluetoothSdpJni: SDP Create record success - handle: 0
08-03 12:37:34.086  3446  3524 D ObexServerSockets0: Accepting socket connection...
08-03 12:37:34.087  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:34.088  3446  3525 D ObexServerSockets0: Accepting socket connection...
,08-03 12:37:34.089  3446  3446 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-03 12:37:34.089  3446  3446 D ObexServerSockets0: prepareForNewConnect()
,08-03 12:37:34.091   873  1392 I ActivityManager: Killing 2863:com.google.android.gm/u0a78 (adj 15): empty #17
,08-03 12:37:34.129  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 12:37:34.162   873  1753 I ActivityManager: Start proc 3526:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-03 12:37:34.163  1748  2030 D BluetoothHeadset: Proxy object connected
,08-03 12:37:34.165   873   890 D BluetoothHeadset: Proxy object connected
,08-03 12:37:34.165   873   890 D BluetoothHeadset: Proxy object connected
,08-03 12:37:34.166   873   890 D BluetoothHeadset: Proxy object connected
,08-03 12:37:34.180  1360  1379 D BluetoothHeadset: Proxy object connected
,08-03 12:37:34.180  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-03 12:37:34.196  3526  3526 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-03 12:37:34.345  3526  3526 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-03 12:37:34.345  3526  3526 D StrictMode: 	,at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 12:37:34.345  3526  3526 D StrictMode: 	,at com.google.android.apps.gmm.shared.i.h.a(PG:250),
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 12:37:34.345  3526  3526 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 12:37:34.345  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 12:37:34.346  3526  3526 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 12:37:34.346  3526  3526 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.r.e.b(PG:170)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 12:37:34.346  3526  3526 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.r.k.d(PG:583)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.r.e.b(PG:170)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 12:37:34.346  3526  3526 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 12:37:34.346  3526  3526 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 12:37:34.346  3526  3526 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 12:37:34.346  3526  3526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 12:37:34.353  3504  3504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-03 12:37:34.373  1360  1360 D BluetoothPbap: Proxy object connected
08-03 12:37:34.371  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 12:37:34.374  1360  1360 D PbapServerProfile: Bluetooth service connected
08-03 12:37:34.379   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a9a2f37:true
08-03 12:37:34.379  3446  3552 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 12:37:34.389  3504  3504 D LocalBluetoothProfileManager: Adding local A2DP profile
08-03 12:37:34.393  3504  3504 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-03 12:37:34.422  3446  3559 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 12:37:34.423  3446  3559 I BtOppRfcommListener: Accept thread started.
,08-03 12:37:34.458  3504  3504 D LocalBluetoothProfileManager: Adding local MAP profile
,08-03 12:37:34.458  3504  3504 D BluetoothMap: Create BluetoothMap proxy object
,08-03 12:37:34.472  3504  3504 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-03 12:37:34.481  3504  3504 D DockEventReceiver: finishStartingService: stopping service
,08-03 12:37:34.482  3504  3504 D BluetoothA2dp: Proxy object connected
,08-03 12:37:34.485  3504  3504 D BluetoothInputDevice: Proxy object connected
,08-03 12:37:34.485  3504  3504 D HidProfile: Bluetooth service connected
,08-03 12:37:34.488  3504  3504 D BluetoothPan: BluetoothPAN Proxy object connected
,08-03 12:37:34.488  3504  3504 D PanProfile: Bluetooth service connected
,08-03 12:37:34.489  3504  3504 D BluetoothMap: Proxy object connected
,08-03 12:37:34.489  3504  3504 D MapProfile: Bluetooth service connected
,08-03 12:37:34.489  3504  3504 D BluetoothMap: getConnectedDevices()
,08-03 12:37:34.490  3504  3504 D BluetoothPbap: Proxy object connected
,08-03 12:37:34.491  3504  3504 D PbapServerProfile: Bluetooth service connected
,08-03 12:37:34.495  3504  3515 D BluetoothHeadset: Proxy object connected
08-03 12:37:34.496  3504  3504 D HeadsetProfile: Bluetooth service connected
,08-03 12:37:34.500   873   883 I ActivityManager: Killing 3043:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-03 12:37:34.669  3526  3542 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-03 12:37:34.688   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a07522:true
,08-03 12:37:35.533   873  1715 D WifiService: setWifiEnabled: true pid=3396, uid=10000
,08-03 12:37:35.533   873  1715 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 12:37:35.551   873  1312 D WifiConfigStore: Loading config and enabling all networks 
,08-03 12:37:35.567  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:35.567  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:35.567  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:35.567  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:35.567  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:35.567  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:35.567  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:35.567  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:35.573  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:35.582  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:35.582  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:35.582  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:35.582  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:35.582  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:35.582  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:35.582  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:35.582  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:35.584   873  1312 D WifiConfigStore: loaded 0 passpoint configs
,08-03 12:37:35.585   873  1312 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 12:37:35.585   873  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-03 12:37:35.586   873  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-03 12:37:35.587   873  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-03 12:37:35.587   873  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-03 12:37:35.587   873  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-03 12:37:35.587  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:37:35.587   873  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-03 12:37:35.589  1477  1477 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-03 12:37:35.671   873  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 12:37:35.672   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-03 12:37:35.673  1477  1477 E wpa_supplicant: PNO: In assoc process
,08-03 12:37:35.674   873  1312 E WifiStateMachine:  Fail to set up pno, want true now false
,08-03 12:37:35.676   371   871 D CommandListener: Setting iface cfg
,08-03 12:37:35.677   873  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '36 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 36 Failed to set address (No such device)'
,08-03 12:37:35.678   873  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-03 12:37:35.681   873  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-03 12:37:35.681   873  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-03 12:37:35.681   873  1312 E native  : do suspend true
,08-03 12:37:35.721   873  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 12:37:36.048  1477  1477 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 12:37:36.089  1477  1477 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-03 12:37:36.091  1477  1477 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-03 12:37:36.097   873  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 12:37:36.115   873  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 12:37:36.116   873  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 12:37:36.116   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-03 12:37:36.140   873  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 12:37:36.159   371   871 D CommandListener: Setting iface cfg
,08-03 12:37:36.172   873  1312 D WifiStateMachine: Start Dhcp Watchdog 1
,08-03 12:37:36.186   873  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-03 12:37:36.224   873  3570 D DhcpClient: Receive thread started
,08-03 12:37:36.315   873  1312 E native  : do suspend false
,08-03 12:37:36.342   873  3569 D DhcpClient: Broadcasting DHCPDISCOVER
,08-03 12:37:36.374   873  3570 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 90607, domain null
,08-03 12:37:36.376   873  3569 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 90607 seconds
,08-03 12:37:36.380   873  3569 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-03 12:37:36.399   873  3570 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-03 12:37:36.400   873  3569 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-03 12:37:36.405   371   871 D CommandListener: Setting iface cfg
,08-03 12:37:36.416   873  3569 D DhcpClient: Scheduling renewal in 86399s
,08-03 12:37:36.416   873  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-03 12:37:36.420   873  1312 E native  : do suspend true
,08-03 12:37:36.441   873  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-03 12:37:36.444   873  1312 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-03 12:37:36.446   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-03 12:37:36.454   873  1314 D ConnectivityService: Adding iface wlan0 to network 100
,08-03 12:37:36.455   873  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-03 12:37:36.500   873  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-03 12:37:36.501   873  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-03 12:37:36.504   873  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-03 12:37:36.506   873  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-03 12:37:36.509   873  1314 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-03 12:37:36.519   873  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-03 12:37:36.523   873  1314 D ConnectivityService: scheduleUnvalidatedPrompt 100
08-03 12:37:36.523   873  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,08-03 12:37:36.525   873  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
08-03 12:37:36.525   873  1314 D ConnectivityService:    accepting network in place of null
08-03 12:37:36.525   873  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-03 12:37:36.526   873  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 12:37:36.528   873  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 12:37:36.535   873  3568 D NetlinkSocketObserver: NeighborEvent{elapsedMs=419724, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-03 12:37:36.571   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 12:37:36.603   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 12:37:36.608   873  3567 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,08-03 12:37:36.609   873  1314 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-03 12:37:36.618   873  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-03 12:37:36.619   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 12:37:36.627   873  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-03 12:37:36.631   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-03 12:37:36.637   873  1687 V BackupManagerService: Scheduling immediate backup pass
,08-03 12:37:36.637   873   873 V BackupManagerService: Running a backup pass
08-03 12:37:36.639   873  1332 V BackupManagerService: clearing pending backups
,08-03 12:37:36.652  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:36.652  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:36.652  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:36.652  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:36.652  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:36.652  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 12:37:36.652  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 12:37:36.652  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 12:37:36.653   873  1332 V PerformBackupTask: Beginning backup of 16 targets
,08-03 12:37:36.655  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 12:37:36.655  1817  1817 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-03 12:37:36.672   873  1332 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-03 12:37:36.676  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:36.676  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:36.676  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:36.676  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:36.676  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:36.676  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 12:37:36.676  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 12:37:36.676  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 12:37:36.678  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 12:37:36.682   873  1332 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,08-03 12:37:36.695  1875  1875 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 12:37:36.696   873  1714 D AlarmManagerService: Setting time of day to sec=1470220656
08-03 12:37:36.864   873  1714 W AlarmManagerService: Unable to set rtc to 1470220656: Invalid argument
,08-03 12:37:36.874  1875  1875 D SystemUpdateService: onCreate
,08-03 12:37:36.874  1875  3588 I CheckinService: Checking schedule, now: 1470220656873 next: 1470138676785
08-03 12:37:36.874  1875  3588 I CheckinService: active receiver: enabled
08-03 12:37:36.875   873  3591 D GpsLocationProvider: NTP server returned: 1470220656864 (Wed Aug 03 12:37:36 GMT+02:00 2016) reference: 419888 certainty: 8 system time offset: -11
08-03 12:37:36.875   873  3591 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,08-03 12:37:36.878  1875  1875 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 12:37:36.881  1875  3592 I SystemUpdateService: active receiver: enabled
,08-03 12:37:36.883  1875  3588 I CheckinService: Preparing to send checkin request
,08-03 12:37:36.885  1875  3588 I EventLogService: Accumulating logs since 1470220633024
,08-03 12:37:36.883  1875  3592 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 12:37:36.888  1875  3592 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-03 12:37:36.888  1875  3592 I SystemUpdateService: now status is 0 (complete)
08-03 12:37:36.888  1875  3592 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-03 12:37:36.888  1875  3592 I SystemUpdateService: file has been verified
08-03 12:37:36.888  1875  3592 I SystemUpdateService: OTA package size = 12249756
,08-03 12:37:36.895   873  3567 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 10:37:36 GMT], X-Android-Received-Millis=[1470220656893], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470220656678]}
,08-03 12:37:36.897  1875  3592 I SystemUpdateService: showing system update notification
,08-03 12:37:36.899   873  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-03 12:37:36.900   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
,08-03 12:37:36.901   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-03 12:37:36.903   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-03 12:37:36.912   873  1332 I BackupRestoreController: Getting widget state for user: 0
,08-03 12:37:36.912  1875  3588 I EventLogService: Opted in for usage reporting
,08-03 12:37:36.929  1875  1875 D SystemUpdateService: onDestroy
,08-03 12:37:36.935  1875  3588 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,08-03 12:37:36.939   873  1313 D WifiService: New client listening to asynchronous messages
,08-03 12:37:36.946   873  1715 I ActivityManager: Start proc 3602:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-03 12:37:36.948  1875  3588 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,08-03 12:37:36.960  1875  3590 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-03 12:37:36.959  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-03 12:37:36.961  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 12:37:36.978  1875  3617 I iu.SyncManager: SYNC; picasa accounts
,08-03 12:37:36.979  3602  3602 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-03 12:37:36.986  1875  1875 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-03 12:37:36.988  1875  1875 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-03 12:37:37.000  1526  2025 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
,08-03 12:37:37.000  1526  2025 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud.
08-03 12:37:37.001  1526  2025 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 12:37:37.001  1526  2025 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 12:37:37.011  3457  3599 V GoogleAuthProtoRequest: [286] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 12:37:37.011  1875  3598 I GcmGroups: Failed to subscribe to group.
08-03 12:37:37.011  1875  3598 I GcmGroups: com.google.android.gms.auth.ae: BadAuthentication
08-03 12:37:37.011  1875  3598 I GcmGroups: 	at com.google.android.gms.auth.p.b(SourceFile:480)
08-03 12:37:37.011  1875  3598 I GcmGroups: 	at com.google.android.gms.auth.p.a(SourceFile:397)
08-03 12:37:37.011  1875  3598 I GcmGroups: 	at com.google.android.gms.auth.p.a(SourceFile:350)
08-03 12:37:37.011  1875  3598 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:444)
08-03 12:37:37.011  1875  3598 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:334)
08-03 12:37:37.011  1875  3598 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:241)
08-03 12:37:37.011  1875  3598 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:48)
08-03 12:37:37.011  1875  3598 I GcmGroups: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 12:37:37.011  1875  3598 I GcmGroups: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 12:37:37.011  1875  3598 I GcmGroups: 	at android.os.Looper.loop(Looper.java:148)
08-03 12:37:37.011  1875  3598 I GcmGroups: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 12:37:37.016  1875  3598 I GcmGroups: Groups upload failed, retrying in 24000:00:00
,08-03 12:37:37.030  1875  1875 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-03 12:37:37.031  1875  1875 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-03 12:37:37.031  3602  3619 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-03 12:37:37.052   873  1685 I ActivityManager: Start proc 3628:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-03 12:37:37.064  1875  3616 I MDM     : [189] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-03 12:37:37.066  1875  3616 W BaseAppContext: Using Auth Proxy for data requests.
,08-03 12:37:37.079  3602  3619 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-03 12:37:37.080  1875  3616 V GoogleAuthProtoRequest: [189] a.<init>: mAccountName set to: thalitester@gmail.com
08-03 12:37:37.099  1841  2072 W GmsBackupTransport: Unknown package in backup request: @pm@
08-03 12:37:37.101  1841  2072 V GmsBackupTransport: starting performBackup for @pm@
,08-03 12:37:37.105  1875  3617 I iu.UploadsManager: num queued entries: 0
,08-03 12:37:37.106  3602  3619 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-03 12:37:37.106  1875  3617 I iu.UploadsManager: num updated entries: 0
08-03 12:37:37.106  1875  3617 I iu.SyncManager: NEXT; no task
,08-03 12:37:37.116  3628  3628 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-03 12:37:37.119  3628  3628 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 12:37:37.130  3628  3628 D SprintDMHelper: simOperator: 
,08-03 12:37:37.130  3628  3628 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 12:37:37.131  1841  2072 V GmsBackupTransport: performBackup done for @pm@
,08-03 12:37:37.136  1526  1897 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-03 12:37:37.138  1526  1897 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.,
08-03 12:37:37.138  1526  1897 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 12:37:37.138  1526  1897 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 12:37:37.149   873  1764 I ActivityManager: Start proc 3650:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-03 12:37:37.164  1526  3645 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-03 12:37:37.164  1526  3645 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-03 12:37:37.165  1526  3645 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 12:37:37.165  1526  3645 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 12:37:37.170  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 12:37:37.184  3602  3602 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-03 12:37:37.191  1526  2700 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-03 12:37:37.191  1526  2700 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
,08-03 12:37:37.191  1526  2700 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 12:37:37.191  1526  2700 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 12:37:37.196  3457  3599 W ExperimentUpdateService: [286] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-03 12:37:37.197  3457  3599 W ExperimentUpdateService: [286] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 12:37:37.197  3457  3599 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 12:37:37.197  3457  3599 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-03 12:37:37.197  3457  3599 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-03 12:37:37.197  3457  3599 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-03 12:37:37.197  3457  3599 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-03 12:37:37.197  3457  3599 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-03 12:37:37.197  3457  3599 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-03 12:37:37.197  3457  3599 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-03 12:37:37.197  3457  3599 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-03 12:37:37.197  3457  3599 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-03 12:37:37.201  1526  2700 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-03 12:37:37.201  1526  2700 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-03 12:37:37.201  1526  2700 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-03 12:37:37.201  1526  2700 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-03 12:37:37.201  1526  2700 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-03 12:37:37.201  1526  2700 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-03 12:37:37.201  1526  2700 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-03 12:37:37.202  1875  3616 E MDM     : [189] SitrepService.a: Error sending sitrep.
,08-03 12:37:37.211  1841  2071 W GmsBackupTransport: Error sending final backup to server: 
08-03 12:37:37.211  1841  2071 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-03 12:37:37.211  1841  2071 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-03 12:37:37.211  1841  2071 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-03 12:37:37.211  1841  2071 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-03 12:37:37.211  1841  2071 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-03 12:37:37.211  1841  2071 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-03 12:37:37.211  1841  2071 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-03 12:37:37.211  1841  2071 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-03 12:37:37.211  1841  2071 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-03 12:37:37.211  1841  2071 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-03 12:37:37.211  1841  2071 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-03 12:37:37.211  1841  2071 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-03 12:37:37.211  1841  2071 W GmsBackupTransport: 	... 1 more
,08-03 12:37:37.214  1841  1856 I GmsBackupTransport: Next backup will happen in 43199989 millis.
08-03 12:37:37.214   873  1332 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-03 12:37:37.224   873  1392 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1875 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-03 12:37:37.316  3673  3673 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1537252365.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1537252365.dex
,08-03 12:37:37.361  1526  3645 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,08-03 12:37:37.361  1526  3645 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
,08-03 12:37:37.361  1526  3645 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 12:37:37.361  1526  3645 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 12:37:37.387  3602  3602 W InstanceID/Rpc: Found 10011
,08-03 12:37:37.403  1875  3588 W CheckinRequestBuilder: awaiting user notification for token
,08-03 12:37:37.408  3673  3673 I dex2oat : dex2oat took 92.538ms (threads: 4) arena alloc=219KB java alloc=29KB native alloc=1529KB free=1542KB
,08-03 12:37:37.436   873  1332 I BackupManagerService: Backup pass finished.
,08-03 12:37:37.448  1875  3596 W DriveInitializer: Awaiting to be initialized
,08-03 12:37:37.448  1875  3718 W DriveInitializer: Background init thread started
,08-03 12:37:37.470  1526  1526 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-03 12:37:37.475  1526  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-03 12:37:37.476  1526  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 12:37:37.476  1526  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 12:37:37.476  1526  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 12:37:37.482   873   883 I ActivityManager: Start proc 3722:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,08-03 12:37:37.506   873  1694 I ActivityManager: Start proc 3738:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-03 12:37:37.528  3722  3722 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-03 12:37:37.535   873   885 I ActivityManager: Start proc 3754:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-03 12:37:37.541  3722  3722 I MultiDex: VM with version 2.1.0 has multidex support
08-03 12:37:37.541  3722  3722 I MultiDex: install
,08-03 12:37:37.542  3722  3722 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-03 12:37:37.550  3162  3625 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-03 12:37:37.550  3162  3625 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at jdm.a(PG:82)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at jcs.o(PG:406)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at jcn.a(PG:1379)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at jcs.i(PG:143)
08-03 12:37:37.550  3162  3625 E HttpOperation: ,	at blb.a(PG:3937)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at czp.a(PG:18188)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at czp.a(PG:9081)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at czq.run(PG:1686)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 12:37:37.550  3162  3625 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at jdj.a(PG:4091)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at jdj.a(PG:1125)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at jdm.a(PG:77)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	... 12 more
08-03 12:37:37.550  3162  3625 E HttpOperation: Caused by: faj: BadAuthentication
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at fal.a(PG:38)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	at jdj.a(PG:4089)
08-03 12:37:37.550  3162  3625 E HttpOperation: 	... 14 more
,08-03 12:37:37.567  1875  3718 W DriveInitializer: Background init thread ended
,08-03 12:37:37.574  3754  3754 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-03 12:37:37.584  1526  3645 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 12:37:37.584  1526  3645 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-03 12:37:37.584  1526  3645 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 12:37:37.584  1526  3645 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 12:37:37.604  3162  3625 E HttpOperation: [getmobileexperiments] Unexpected exception
08-03 12:37:37.604  3162  3625 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at jdm.a(PG:82)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at jcs.o(PG:406)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at jcn.a(PG:1379)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at jcs.i(PG:143)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at hec.a(PG:42)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at hee.a(PG:102)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at czr.a(PG:65)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at kka.a(PG:108)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at czp.a(PG:19176)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at czp.a(PG:9081)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at czq.run(PG:1686)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 12:37:37.604  3162  3625 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at jdj.a(PG:4091)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at jdj.a(PG:1125)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at jdm.a(PG:77)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	... 15 more
08-03 12:37:37.604  3162  3625 E HttpOperation: Caused by: faj: BadAuthentication
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at fal.a(PG:38)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	at jdj.a(PG:4089)
08-03 12:37:37.604  3162  3625 E HttpOperation: 	... 17 more
,08-03 12:37:37.605  3162  3625 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-03 12:37:37.605  3162  3625 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at jdm.a(PG:82)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at jcs.o(PG:406)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at jcn.a(PG:1379)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at jcs.i(PG:143)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at hec.a(PG:42)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at hee.a(PG:102)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at czr.a(PG:65)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at kka.a(PG:108)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at czp.a(PG:19176)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at czp.a(PG:9081)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at czq.run(PG:1686)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at jdj.a(PG:4091)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at jdj.a(PG:1125)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at jdm.a(PG:77)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	... 15 more
08-03 12:37:37.605  3162  3625 E ExperimentLoader: Caused by: faj: BadAuthentication
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at fal.a(PG:38)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	at jdj.a(PG:4089)
08-03 12:37:37.605  3162  3625 E ExperimentLoader: 	... 17 more
,08-03 12:37:37.626  3722  3722 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-03 12:37:37.640  3738  3738 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-03 12:37:37.650  3722  3722 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-03 12:37:37.686  3722  3782 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,08-03 12:37:37.759   375  1285 D WVCdm   : Instantiating CDM.
,08-03 12:37:37.760   375   375 I WVCdm   : CdmEngine::OpenSession
08-03 12:37:37.760   375   375 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-03 12:37:37.772   375   375 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-03 12:37:37.777   375   375 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
,08-03 12:37:37.777   375   375 D DrmWidevineDash: Service_Initialize: starts!
08-03 12:37:37.777   375   375 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-03 12:37:37.777   375   375 D QSEECOMAPI: : App is not loaded in QSEE
,08-03 12:37:37.788  3722  3735 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-03 12:37:37.802  3754  3754 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-03 12:37:37.813  3754  3754 I BooksApp: Created application version: 3.6.9 (30609)
,08-03 12:37:37.878   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 23746, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-03 12:37:37.913  3754  3793 I BooksSync: Starting books sync for 61035162, extras: ade
,08-03 12:37:37.962  2899  3797 V KeepSync: Connecting to GoogleApiClient
,08-03 12:37:37.962   873  1745 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-03 12:37:38.008   375   375 D QSEECOMAPI: : Loaded image: APP id = 3
,08-03 12:37:38.009   375   375 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-03 12:37:38.009   375   375 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2a66000
08-03 12:37:38.009   375   375 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2a66000
,08-03 12:37:38.012  1526  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-03 12:37:38.012  1526  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-03 12:37:38.012  1526  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 12:37:38.012  1526  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 12:37:38.015   331   338 D DrmLibTime: got the req here! ret=0
,08-03 12:37:38.015   331   338 D DrmLibTime: command id, time_cmd_id = 770
08-03 12:37:38.015   331   338 D DrmLibTime: time_getutcsec starts!
08-03 12:37:38.015   331   338 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-03 12:37:38.015   331   338 D DrmLibTime: QSEE Time Listener: get_utc_seconds
,08-03 12:37:38.015   331   338 D DrmLibTime: QSEE Time Listener: seconds: 1470220658
08-03 12:37:38.016   331   338 D DrmLibTime: QSEE Time Listener: nano seconds: 15981468
,08-03 12:37:38.016   331   338 D DrmLibTime: time_getutcsec returns 0, sec = 1470220658; nsec = 15981468
,08-03 12:37:38.016   331   338 D DrmLibTime: time_getutcsec finished! 
,08-03 12:37:38.016   331   338 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-03 12:37:38.016   331   338 D DrmLibTime: before calling ioctl to read the next time_cmd
,08-03 12:37:38.020  3738  3738 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-03 12:37:38.020  3738  3738 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-03 12:37:38.020  3738  3738 I GAv4    :   adb logcat -s GAv4
08-03 12:37:38.020   375   375 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-03 12:37:38.020   375   375 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-03 12:37:38.021   375   375 D DrmWidevineDash: hlos api version =  10
08-03 12:37:38.021   375   375 D DrmWidevineDash: tz api version =  10
08-03 12:37:38.021   375   375 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-03 12:37:38.021   375   375 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-03 12:37:38.026  1875  3801 V BaseAuthAsyncOperation: access token request failed
08-03 12:37:38.027  2899  3797 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-03 12:37:38.035  3738  3738 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-03 12:37:38.038   375   375 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-03 12:37:38.038   375   375 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-03 12:37:38.038   375   375 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbeb86214
,08-03 12:37:38.038   375   375 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-03 12:37:38.038   375   375 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-03 12:37:38.038   375   375 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb608d1b8, dataLength=8
,08-03 12:37:38.039   375   375 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-03 12:37:38.043   375   375 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb60be200, wrapped_rsa_key_length=1280
,08-03 12:37:38.044  3738  3738 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-03 12:37:38.046   375   375 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-03 12:37:38.046   375   375 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-03 12:37:38.046   375  1320 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-03 12:37:38.046   375  1320 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-03 12:37:38.046   375  1320 I WVCdm   : CdmEngine::GenerateKeyRequest
08-03 12:37:38.046   375  1320 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb31bfb00, idLength=0xb2e7df2c
,08-03 12:37:38.057   375  1320 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,08-03 12:37:38.058   375  1320 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-03 12:37:38.058   375  1320 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-03 12:37:38.058   375  1320 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
,08-03 12:37:38.058   375  1320 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
08-03 12:37:38.058   375  1320 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
08-03 12:37:38.059   375  1320 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
08-03 12:37:38.059   375  1320 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-03 12:37:38.059   375  1320 D DrmWidevineDash: hlos api version =  10
08-03 12:37:38.059   375  1320 D DrmWidevineDash: tz api version =  10
08-03 12:37:38.059   375  1320 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-03 12:37:38.060   375  1320 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,08-03 12:37:38.060   375  1320 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
08-03 12:37:38.060   375  1320 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-03 12:37:38.060   375  1320 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
08-03 12:37:38.061   375  1320 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-03 12:37:38.061   375  1320 D WVCdm   : PrepareKeyRequest: nonce=2033646379,
08-03 12:37:38.061   375  1320 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4848c00
08-03 12:37:38.061   375  1320 D DrmWidevineDash: message_length=1624, signature=0xb60b7240, signature_length=3001540612
,08-03 12:37:38.062  3738  3806 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-03 12:37:38.123   375  1320 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-03 12:37:38.124   375  1321 I WVCdm   : CdmEngine::CloseSession
08-03 12:37:38.124   375  1321 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-03 12:37:38.125   375  1321 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,08-03 12:37:38.125   375  1321 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-03 12:37:38.125   375  1321 D DrmWidevineDash: Service_Uninitialize: starts!
08-03 12:37:38.125   375  1321 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-03 12:37:38.125   375  1321 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
08-03 12:37:38.126   375  1321 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-03 12:37:38.126   375  1321 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-03 12:37:38.214  3738  3738 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-03 12:37:38.253  3738  3738 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-03 12:37:38.261  3738  3738 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1283-1286)
,08-03 12:37:38.270  3738  3738 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-03 12:37:38.315  3738  3738 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {da0ae82}
,08-03 12:37:38.315  3738  3738 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-03 12:37:38.317  3738  3738 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-03 12:37:38.329  3738  3738 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-03 12:37:38.331  3738  3738 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-03 12:37:38.371  3754  3832 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-03 12:37:38.382  3738  3738 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-03 12:37:38.412  3738  3738 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-03 12:37:38.412  3738  3738 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-03 12:37:38.412  3738  3738 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-03 12:37:38.412  3738  3738 I Adreno  : Build Date                       : 10/20/15
08-03 12:37:38.412  3738  3738 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-03 12:37:38.412  3738  3738 I Adreno  : Local Branch                     : M14
08-03 12:37:38.412  3738  3738 I Adreno  : Remote Branch                    : 
08-03 12:37:38.412  3738  3738 I Adreno  : Remote Branch                    : 
08-03 12:37:38.412  3738  3738 I Adreno  : Reconstruct Branch               : 
,08-03 12:37:38.453  1526  2700 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 12:37:38.453  1526  2700 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-03 12:37:38.453  1526  2700 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 12:37:38.454  1526  2700 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 12:37:38.525  1526  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-03 12:37:38.525  1526  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-03 12:37:38.525  1526  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 12:37:38.525  1526  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 12:37:38.531  3738  3840 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-03 12:37:38.542  3738  3738 I NSApplication: Starting up...
,08-03 12:37:38.567   873  1687 I ActivityManager: Start proc 3845:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-03 12:37:38.569  3754  3832 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-03 12:37:38.572  3754  3793 E BooksSync: Soft error
08-03 12:37:38.572  3754  3793 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 12:37:38.572  3754  3793 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-03 12:37:38.572  3754  3793 E BooksSync: Sync error
08-03 12:37:38.572  3754  3793 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 12:37:38.572  3754  3793 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-03 12:37:38.572  3754  3793 I BooksSync: Finished books sync
08-03 12:37:38.577   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 23755, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 12:37:38.578   873  1767 I ActivityManager: Killing 2477:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-03 12:37:38.660  3845  3845 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-03 12:37:38.669  1526  2025 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-03 12:37:38.669  1526  2025 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-03 12:37:38.670  1526  2025 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 12:37:38.670  1526  2025 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 12:37:38.696  2899  3797 E KeepSync: IOException
08-03 12:37:38.696  2899  3797 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-03 12:37:38.696  2899  3797 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-03 12:37:38.696  2899  3797 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-03 12:37:38.696  2899  3797 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-03 12:37:38.696  2899  3797 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-03 12:37:38.696  2899  3797 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-03 12:37:38.696  2899  3797 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-03 12:37:38.696  2899  3797 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-03 12:37:38.696  2899  3797 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-03 12:37:38.696  2899  3797 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-03 12:37:38.696  2899  3797 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-03 12:37:38.696  2899  3797 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-03 12:37:38.696  2899  3797 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-03 12:37:38.696  2899  3797 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-03 12:37:38.696  2899  3797 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 12:37:38.696  2899  3797 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 12:37:38.696  2899  3797 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-03 12:37:38.696  2899  3797 E KeepSync: 	... 10 more
08-03 12:37:38.697  2899  3797 W KeepSync: Sync result 2
,08-03 12:37:38.703   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 23755, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-03 12:37:38.703   873  1392 I ActivityManager: Killing 2768:android.process.acore/u0a5 (adj 15): empty #17
,08-03 12:37:38.706   873  1687 D WifiService: setWifiEnabled: false pid=3396, uid=10000
08-03 12:37:38.707   873  1687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 12:37:38.722  1477  1477 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-03 12:37:38.724   873  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 12:37:38.724   873  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-03 12:37:38.724   873  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-03 12:37:38.724   873  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 12:37:38.800   873  1312 E native  : do suspend true
,08-03 12:37:38.808   873  3569 D DhcpClient: Clearing IP address
,08-03 12:37:38.808   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-03 12:37:38.812   371   871 D CommandListener: Setting iface cfg
,08-03 12:37:38.826   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-03 12:37:38.827   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-03 12:37:38.832   873  1312 D WifiStateMachine: Start Disconnecting Watchdog 1
08-03 12:37:38.833   873  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-03 12:37:38.833   873  1312 E native  : do suspend true
,08-03 12:37:38.835   873  3570 D DhcpClient: Receive thread stopped
,08-03 12:37:38.836   443   443 E Parcel  : Reading a NULL string not supported here.
,08-03 12:37:38.837   873  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-03 12:37:38.867   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 12:37:38.894   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 12:37:38.894   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-03 12:37:38.895   873  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-03 12:37:38.895   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 12:37:38.896   873  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 12:37:38.900   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-03 12:37:38.903  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:38.903  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:38.903  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:38.903  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:38.903  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:38.903  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:38.903  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:38.903  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:37:38.904  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:38.908  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:38.908  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:38.908  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:38.908  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:38.908  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:38.908  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:38.908  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:38.908  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:38.910  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:37:38.911   873  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 12:37:38.913  1841  2068 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:37:38.916  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:38.916  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:38.916  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:38.916  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:38.916  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:38.916  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:38.916  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:38.916  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:38.917   873  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-03 12:37:38.918  1817  1817 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-03 12:37:38.919  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:38.922  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:38.922  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:38.922  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:38.922  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:38.922  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:38.922  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:38.922  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:38.922  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:38.925  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:38.957   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-03 12:37:38.958   873  1314 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-03 12:37:38.969  3602  3717 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Failed to fetch settings
,08-03 12:37:38.972   873  1745 I ActivityManager: Killing 3249:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-03 12:37:39.065  3873  3873 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-03 12:37:39.076  1526  3875 I VacuumService: Vacuum at: now=1470220659076 tag=VacuumService
,08-03 12:37:39.110  3873  3873 I dex2oat : dex2oat took 45.847ms (threads: 4) arena alloc=206KB java alloc=39KB native alloc=1536KB free=1535KB
,08-03 12:37:39.115  3722  3735 W System  : ClassLoader referenced unknown path: 
,08-03 12:37:39.134  3722  3735 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-03 12:37:39.134  3722  3735 I Adreno  : Build Date                       : 10/20/15
08-03 12:37:39.134  3722  3735 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-03 12:37:39.134  3722  3735 I Adreno  : Local Branch                     : M14
08-03 12:37:39.134  3722  3735 I Adreno  : Remote Branch                    : 
08-03 12:37:39.134  3722  3735 I Adreno  : Remote Branch                    : 
08-03 12:37:39.134  3722  3735 I Adreno  : Reconstruct Branch               : 
,08-03 12:37:39.167   873   884 I ActivityManager: Killing 3264:com.android.musicfx/u0a18 (adj 15): empty #17
,08-03 12:37:39.223   375  1285 I WVCdm   : CdmEngine::OpenSession
,08-03 12:37:39.223   375  1285 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-03 12:37:39.225   375  1285 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
08-03 12:37:39.225  1526  2314 D GCM     : GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,08-03 12:37:39.226   375  1285 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
08-03 12:37:39.226   375  1285 D DrmWidevineDash: Service_Initialize: starts!
08-03 12:37:39.226   375  1285 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-03 12:37:39.226   375  1285 D QSEECOMAPI: : App is not loaded in QSEE
,08-03 12:37:39.233  1526  1526 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-03 12:37:39.240  1526  2314 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-03 12:37:39.243  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 12:37:39.245  1875  1875 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-03 12:37:39.259  3078  3078 D WearableService: callingUid 10011, callindPid: 3078
,08-03 12:37:39.266  1841  2204 E MDM     : [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-03 12:37:39.267  1875  3883 D LocationInitializer: Restart initialization of location
,08-03 12:37:39.284  1841  1946 W GCoreFlp: No location to return for getLastLocation()
,08-03 12:37:39.285  1526  3884 W FusedLocationProvider: location=null
,08-03 12:37:39.287  1875  1875 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 12:37:39.290  1875  1875 D SystemUpdateService: onCreate
,08-03 12:37:39.292  1875  1875 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 12:37:39.295  1875  3885 I SystemUpdateService: active receiver: enabled
,08-03 12:37:39.298  1875  3885 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 12:37:39.299  1875  3885 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-03 12:37:39.299  1875  3885 I SystemUpdateService: now status is 0 (complete)
,08-03 12:37:39.299  1875  1875 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-03 12:37:39.299  1875  3885 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-03 12:37:39.299  1875  3885 I SystemUpdateService: file has been verified
08-03 12:37:39.300  1875  3617 I iu.UploadsManager: num queued entries: 0
08-03 12:37:39.301  1875  3617 I iu.UploadsManager: num updated entries: 0
,08-03 12:37:39.301  1875  3617 I iu.SyncManager: NEXT; no task
,08-03 12:37:39.300  1875  3885 I SystemUpdateService: OTA package size = 12249756
08-03 12:37:39.303  1875  1875 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-03 12:37:39.304  1875  1875 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 12:37:39.307  1875  3885 I SystemUpdateService: showing system update notification
,08-03 12:37:39.309  3628  3628 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 12:37:39.312  3628  3628 D SprintDMHelper: simOperator: 
08-03 12:37:39.312  3628  3628 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 12:37:39.321  1875  1875 D SystemUpdateService: onDestroy
,08-03 12:37:39.439   375  1285 D QSEECOMAPI: : Loaded image: APP id = 3
,08-03 12:37:39.441   375  1285 D DrmWidevineDash: Service_Initialize: ends! returns 0
08-03 12:37:39.441   375  1285 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2a66000
08-03 12:37:39.441   375  1285 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2a66000
,08-03 12:37:39.448   331   338 D DrmLibTime: got the req here! ret=0
,08-03 12:37:39.448   331   338 D DrmLibTime: command id, time_cmd_id = 770
08-03 12:37:39.448   331   338 D DrmLibTime: time_getutcsec starts!
08-03 12:37:39.449   331   338 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-03 12:37:39.449   331   338 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-03 12:37:39.449   331   338 D DrmLibTime: QSEE Time Listener: seconds: 1470220659
08-03 12:37:39.449   331   338 D DrmLibTime: QSEE Time Listener: nano seconds: 449394007
,08-03 12:37:39.449   331   338 D DrmLibTime: time_getutcsec returns 0, sec = 1470220659; nsec = 449394007
08-03 12:37:39.450   331   338 D DrmLibTime: time_getutcsec finished! 
08-03 12:37:39.450   331   338 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-03 12:37:39.450   331   338 D DrmLibTime: before calling ioctl to read the next time_cmd
,08-03 12:37:39.456   375  1285 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-03 12:37:39.456   375  1285 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-03 12:37:39.457   375  1285 D DrmWidevineDash: hlos api version =  10
08-03 12:37:39.457   375  1285 D DrmWidevineDash: tz api version =  10
08-03 12:37:39.457   375  1285 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-03 12:37:39.457   375  1285 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-03 12:37:39.468   375  1285 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-03 12:37:39.468   375  1285 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,08-03 12:37:39.468   375  1285 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb2f80134
08-03 12:37:39.468   375  1285 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-03 12:37:39.468   375  1285 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-03 12:37:39.468   375  1285 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb608c618, dataLength=8
,08-03 12:37:39.469   375  1285 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
08-03 12:37:39.470   375  1285 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb2ab2c00, wrapped_rsa_key_length=1280
,08-03 12:37:39.473   375  1285 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,08-03 12:37:39.473   375  1285 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-03 12:37:39.476   375  1321 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-03 12:37:39.476   375  1321 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-03 12:37:39.476   375  1321 I WVCdm   : CdmEngine::GenerateKeyRequest
08-03 12:37:39.476   375  1321 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb2a8e780, idLength=0xb2cfef2c
,08-03 12:37:39.487   375  1321 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,08-03 12:37:39.487   375  1321 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-03 12:37:39.487   375  1321 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-03 12:37:39.488   375  1321 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
08-03 12:37:39.488   375  1321 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
,08-03 12:37:39.488   375  1321 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
08-03 12:37:39.488   375  1321 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
08-03 12:37:39.488   375  1321 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-03 12:37:39.489   375  1321 D DrmWidevineDash: hlos api version =  10
08-03 12:37:39.489   375  1321 D DrmWidevineDash: tz api version =  10
08-03 12:37:39.489   375  1321 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-03 12:37:39.489   375  1321 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
08-03 12:37:39.490   375  1321 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,08-03 12:37:39.490   375  1321 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-03 12:37:39.490   375  1321 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
08-03 12:37:39.490   375  1321 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-03 12:37:39.490   375  1321 D WVCdm   : PrepareKeyRequest: nonce=1201889302
08-03 12:37:39.491   375  1321 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4849300
08-03 12:37:39.491   375  1321 D DrmWidevineDash: message_length=1658, signature=0xb3790500, signature_length=2999971844
,08-03 12:37:39.549   375  1321 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-03 12:37:39.550   375  1285 I WVCdm   : CdmEngine::CloseSession
08-03 12:37:39.550   375  1285 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-03 12:37:39.551   375  1285 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,08-03 12:37:39.551   375  1285 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-03 12:37:39.551   375  1285 D DrmWidevineDash: Service_Uninitialize: starts!
08-03 12:37:39.551   375  1285 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-03 12:37:39.551   375  1285 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,08-03 12:37:39.552   375  1285 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-03 12:37:39.552   375  1285 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-03 12:37:39.568  1875  3588 I CheckinRequestBuilder: Classify the device as Phone.
,08-03 12:37:39.583  1875  3588 I EventLogService: Opted in for usage reporting
,08-03 12:37:39.937  1875  3588 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-03 12:37:39.960  1875  3588 I CheckinService: Checking schedule, now: 1470220659960 next: 1470220669939
,08-03 12:37:39.960  1875  3588 I CheckinService: active receiver: disabled
,08-03 12:37:39.979  1875  3896 I CheckinService: Checking schedule, now: 1470220659979 next: 1470220669939
,08-03 12:37:39.980  1875  3896 I CheckinService: active receiver: disabled
,08-03 12:37:40.009  1526  2651 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-03 12:37:40.017  1875  1875 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-03 12:37:40.022  1875  1875 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 12:37:41.726  3446  3486 D BluetoothAdapterState: Current state: ON, message: 23
08-03 12:37:41.726  3446  3486 D BluetoothAdapterProperties: Setting state to 13
08-03 12:37:41.726  3446  3486 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 12:37:41.728  3446  3486 D BluetoothAdapterProperties: onBluetoothDisable()
,08-03 12:37:41.736  3446  3486 I BluetoothAdapterState: Entering PendingCommandState
,08-03 12:37:41.738  3446  3446 D BluetoothMapService: onReceive
,08-03 12:37:41.738  3446  3446 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:37:41.739  3446  3446 D BluetoothMapService: STATE_TURNING_OFF
,08-03 12:37:41.739  3446  3446 D BluetoothMapService: MAP Service closeService in
,08-03 12:37:41.740  3446  3446 D BluetoothMapMasInstance0: MAP Service shutdown
,08-03 12:37:41.740  3446  3446 D ObexServerSockets0: shutdown(block = true)
,08-03 12:37:41.743  3446  3524 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-03 12:37:41.747  3396  3396 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:41.744  3446  3446 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-03 12:37:41.747  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:41.747  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:41.747  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:41.747  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:41.747  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:37:41.747  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:41.747  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:41.747  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:41.749  3446  3525 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-03 12:37:41.751  3396  3396 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 12:37:41.751  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:37:41.753  3446  3499 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-03 12:37:41.753  3446  3446 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-03 12:37:41.754  3446  3446 I BtOppRfcommListener: stopping Accept Thread
08-03 12:37:41.755  3446  3559 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 12:37:41.755  3446  3559 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 12:37:41.756  3396  3396 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:41.756  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:41.756  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:41.756  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:41.756  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:41.756  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:37:41.756  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:41.756  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:41.756  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:41.757  3396  3396 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:41.757  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:41.757  3446  3490 D BluetoothAdapterProperties: Scan Mode:20
08-03 12:37:41.758  3446  3486 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-03 12:37:41.760  3446  3446 D HeadsetService: Received stop request...Stopping profile...
,08-03 12:37:41.760  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:41.763  1748  2030 D BluetoothHeadset: Proxy object disconnected
08-03 12:37:41.763  3446  3446 V BluetoothAdapterState: isTurningOff()=true
08-03 12:37:41.763  3446  3446 V BluetoothAdapterState: isTurningOn()=false
08-03 12:37:41.763  3446  3446 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:41.763  3446  3446 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:41.763  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:41.763  1360  1853 D BluetoothHeadset: Proxy object disconnected
08-03 12:37:41.764   873   873 D BluetoothHeadset: Proxy object disconnected
08-03 12:37:41.764   873   873 D BluetoothHeadset: Proxy object disconnected
,08-03 12:37:41.764   873   873 D BluetoothHeadset: Proxy object disconnected
,08-03 12:37:41.764  3446  3446 D A2dpService: Received stop request...Stopping profile...
08-03 12:37:41.764  3504  3514 D BluetoothHeadset: Proxy object disconnected
,08-03 12:37:41.764  3446  3517 D A2dpStateMachine: Exit Disconnected: -1
,08-03 12:37:41.766   873   873 D BluetoothA2dp: Proxy object disconnected
,08-03 12:37:41.769  3446  3446 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 12:37:41.769  3446  3446 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-03 12:37:41.769  3446  3490 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-03 12:37:41.769  3446  3496 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 12:37:41.769  3446  3496 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 12:37:41.769  3446  3496 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 12:37:41.769  3446  3490 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-03 12:37:41.769  3504  3504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
08-03 12:37:41.772  3446  3446 D HidService: Received stop request...Stopping profile...
,08-03 12:37:41.772  3446  3446 D HidService: Stopping Bluetooth HidService
08-03 12:37:41.773  1360  1360 D HeadsetProfile: Bluetooth service disconnected
08-03 12:37:41.773  1360  1360 D BluetoothA2dp: Proxy object disconnected
08-03 12:37:41.774  3504  3504 D HeadsetProfile: Bluetooth service disconnected
,08-03 12:37:41.775  3504  3504 D BluetoothA2dp: Proxy object disconnected
08-03 12:37:41.776  3446  3446 D HealthService: Received stop request...Stopping profile...
08-03 12:37:41.777  3446  3446 V BluetoothAdapterState: isTurningOff()=true
08-03 12:37:41.777  3446  3446 V BluetoothAdapterState: isTurningOn()=false
08-03 12:37:41.777  3446  3446 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 12:37:41.777  3446  3446 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:41.778  1360  1360 D BluetoothInputDevice: Proxy object disconnected
08-03 12:37:41.779  3504  3504 D DockEventReceiver: finishStartingService: stopping service
08-03 12:37:41.779  1360  1360 D HidProfile: Bluetooth service disconnected
,08-03 12:37:41.779  3446  3490 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-03 12:37:41.779  3446  3496 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 12:37:41.779  3446  3496 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 12:37:41.780  3446  3446 D PanService: Received stop request...Stopping profile...
08-03 12:37:41.780  3446  3496 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-03 12:37:41.780  3446  3496 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 12:37:41.780  3446  3496 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 12:37:41.780  3446  3496 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 12:37:41.781  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 12:37:41.781  1360  1360 D PanProfile: Bluetooth service disconnected
,08-03 12:37:41.781  3446  3446 D BluetoothMapService: Received stop request...Stopping profile...
08-03 12:37:41.781  3446  3446 D BluetoothMapService: stop()
08-03 12:37:41.782  3446  3446 D BluetoothMapAppObserver: deinitObservers()
08-03 12:37:41.782  3504  3504 D BluetoothInputDevice: Proxy object disconnected
,08-03 12:37:41.782  3504  3504 D HidProfile: Bluetooth service disconnected
08-03 12:37:41.782  3446  3446 D BluetoothMapAppObserver: removeReceiver()
08-03 12:37:41.784  3504  3504 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-03 12:37:41.784  3504  3504 D PanProfile: Bluetooth service disconnected
08-03 12:37:41.785  3446  3446 V BluetoothAdapterState: isTurningOff()=true
08-03 12:37:41.785  3446  3446 V BluetoothAdapterState: isTurningOn()=false
08-03 12:37:41.785  1360  1360 D BluetoothMap: Proxy object disconnected
08-03 12:37:41.785  3504  3504 D BluetoothMap: Proxy object disconnected
08-03 12:37:41.785  3446  3446 V BluetoothAdapterState: isBleTurningOn()=false,
08-03 12:37:41.785  3504  3504 D MapProfile: Bluetooth service disconnected
08-03 12:37:41.785  1360  1360 D MapProfile: Bluetooth service disconnected
08-03 12:37:41.785  3446  3446 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:41.786  3446  3446 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 12:37:41.786  3446  3446 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 12:37:41.786  3446  3490 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-03 12:37:41.787  3446  3446 V BluetoothAdapterState: isTurningOff()=true
08-03 12:37:41.787  3446  3446 V BluetoothAdapterState: isTurningOn()=false
08-03 12:37:41.787  3446  3446 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 12:37:41.787  3446  3446 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 12:37:41.788  3446  3446 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-03 12:37:41.788  3446  3490 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-03 12:37:41.788  3446  3446 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 12:37:41.789  3446  3446 V BluetoothAdapterState: isTurningOff()=true
08-03 12:37:41.789  3446  3446 V BluetoothAdapterState: isTurningOn()=false
08-03 12:37:41.789  3446  3446 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:41.789  3446  3446 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:41.789  3446  3446 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 12:37:41.790  3446  3446 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-03 12:37:41.790  3446  3446 D BluetoothMapService: MAP Service closeService in
08-03 12:37:41.790  3446  3446 V BluetoothAdapterState: isTurningOff()=true
08-03 12:37:41.790  3446  3446 V BluetoothAdapterState: isTurningOn()=false
08-03 12:37:41.790  3446  3446 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:41.791  3446  3446 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:41.791  3446  3486 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-03 12:37:41.791  3446  3486 D BluetoothAdapterProperties: Setting state to 15
08-03 12:37:41.791  3446  3486 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-03 12:37:41.792  3446  3486 I BluetoothAdapterState: Entering BleOnState
08-03 12:37:41.792  3446  3446 D BluetoothMapService: cleanup()
,08-03 12:37:41.792  3446  3446 D BluetoothMapService: MAP Service closeService in
08-03 12:37:41.793  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 12:37:41.793  3504  3514 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 12:37:41.794  1360  1360 D BluetoothPbap: Proxy object disconnected
08-03 12:37:41.794  1360  1360 D PbapServerProfile: Bluetooth service disconnected
08-03 12:37:41.797  3504  3515 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 12:37:41.798  1360  1383 D BluetoothPan: onBluetoothStateChange on: false
08-03 12:37:41.802  1360  1853 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-03 12:37:41.803  1360  1379 D BluetoothMap: onBluetoothStateChange: up=false
08-03 12:37:41.803  1360  1383 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 12:37:41.804  1360  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:37:41.804  1748  1765 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:37:41.804  3504  3514 D BluetoothPan: onBluetoothStateChange on: false
08-03 12:37:41.805  3504  3515 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:37:41.805  1360  1379 D BluetoothPbap: onBluetoothStateChange: up=false
,08-03 12:37:41.805   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:37:41.806   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:37:41.806  3504  3900 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 12:37:41.806  3504  3514 D BluetoothMap: onBluetoothStateChange: up=false
08-03 12:37:41.807   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 12:37:41.807   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 12:37:41.807  3446  3486 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-03 12:37:41.807  3446  3486 D BluetoothAdapterProperties: Setting state to 16
08-03 12:37:41.807  3446  3486 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-03 12:37:41.808  3446  3486 D BluetoothAdapterProperties: onBleDisable
08-03 12:37:41.808  3446  3486 I BluetoothAdapterState: Entering PendingCommandState
08-03 12:37:41.808  3446  3487 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-03 12:37:41.809  3446  3496 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-03 12:37:41.809  3446  3496 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 12:37:41.811  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:41.812  3446  3490 D BluetoothAdapterProperties: Scan Mode:20
,08-03 12:37:41.812  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:41.814  3504  3504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-03 12:37:41.814  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:41.815  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:41.820  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 12:37:41.820  3504  3504 D DockEventReceiver: finishStartingService: stopping service
,08-03 12:37:42.014  3446  3490 I bt_hci  : shut_down
,08-03 12:37:42.034  3446  3494 I bt_vendor: low_power_mode_cb
,08-03 12:37:42.040  3446  3494 D bt_hwcfg: hw_epilog_process
,08-03 12:37:42.050  3446  3494 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-03 12:37:42.050  3446  3494 I bt_vendor: epilog_cb
,08-03 12:37:42.050  3446  3494 I bt_hci  : epilog_finished_callback
,08-03 12:37:42.056  3446  3490 I bt_hci_h4: hal_close
,08-03 12:37:42.057  3446  3490 I bt_userial_vendor: device fd = 51 close
,08-03 12:37:42.173  3446  3487 D bt_stack_manager: event_shut_down_stack finished.
08-03 12:37:42.173  3446  3486 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-03 12:37:42.176  3446  3486 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-03 12:37:42.176  3446  3446 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 12:37:42.177  3446  3446 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 12:37:42.178  3446  3446 D BtGatt.GattService: stop()
08-03 12:37:42.178  3446  3446 D BtGatt.AdvertiseManager: advertise clients cleared
,08-03 12:37:42.181  3446  3446 V BluetoothAdapterState: isTurningOff()=false
08-03 12:37:42.181  3446  3446 V BluetoothAdapterState: isTurningOn()=false
,08-03 12:37:42.181  3446  3446 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:42.182  3446  3446 V BluetoothAdapterState: isBleTurningOff()=true
08-03 12:37:42.182  3446  3486 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-03 12:37:42.182  3446  3486 D BluetoothAdapterProperties: Setting state to 10
08-03 12:37:42.182  3446  3486 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-03 12:37:42.183  3446  3486 I BluetoothAdapterState: Entering OffState
,08-03 12:37:42.185   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-03 12:37:42.201  3446  3446 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-03 12:37:42.201  3446  3446 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-03 12:37:42.202  3446  3487 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-03 12:37:42.203  3446  3487 D bt_stack_manager: event_clean_up_stack finished.
08-03 12:37:42.203  3446  3446 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-03 12:37:42.205  3446  3446 I art     : System.exit called, status: 0
,08-03 12:37:42.205  3446  3446 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-03 12:37:42.267   873  1715 I ActivityManager: Process com.android.bluetooth (pid 3446) has died
,08-03 12:37:42.539  2347  3734 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,08-03 12:37:42.539  2347  3734 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-03 12:37:42.545  2347  3734 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-03 12:37:42.556  1526  3728 W PhenotypeConfigurator: IOException while sending for: 
,08-03 12:37:42.637  3602  3719 E GoogleConversionReporter: Error sending ping
,08-03 12:37:42.665  1526  3728 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-03 12:37:42.810  3754  3790 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-03 12:37:44.284   873  1767 I ActivityManager: Killing 3213:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-03 12:37:44.578   873  1755 I ActivityManager: Killing 3287:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-03 12:37:44.696   873  1314 D ConnectivityService: handlePromptUnvalidated 100
,08-03 12:37:44.771   873   890 I ActivityManager: Start proc 3912:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-03 12:37:44.911  3912  3912 D AdapterServiceConfig: Adding HeadsetService
,08-03 12:37:44.912  3912  3912 D AdapterServiceConfig: Adding A2dpService
08-03 12:37:44.913  3912  3912 D AdapterServiceConfig: Adding HidService
,08-03 12:37:44.913  3912  3912 D AdapterServiceConfig: Adding HealthService
08-03 12:37:44.914  3912  3912 D AdapterServiceConfig: Adding PanService
08-03 12:37:44.914  3912  3912 D AdapterServiceConfig: Adding GattService
,08-03 12:37:44.915  3912  3912 D AdapterServiceConfig: Adding BluetoothMapService
,08-03 12:37:44.946  3912  3912 D BluetoothAdapterState: make() - Creating AdapterState
,08-03 12:37:44.946   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a5fa6db:true
,08-03 12:37:44.952  3912  3912 I bt_bluedroid: init
,08-03 12:37:44.952  3912  3924 I BluetoothAdapterState: Entering OffState
,08-03 12:37:44.959  3912  3925 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-03 12:37:44.959  3912  3925 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 12:37:44.959  3912  3925 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-03 12:37:44.960  3912  3925 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-03 12:37:44.962  3912  3912 I bt_bluedroid: get_profile_interface socket
,08-03 12:37:44.965  3912  3912 I bt_bluedroid: get_profile_interface sdp
,08-03 12:37:44.970  3912  3923 I bt_bluedroid: config_hci_snoop_log
,08-03 12:37:44.972  3912  3928 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 12:37:44.973   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-03 12:37:44.976  3912  3928 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 12:37:44.985  3912  3924 D BluetoothAdapterState: Current state: OFF, message: 0
,08-03 12:37:44.985  3912  3924 D BluetoothAdapterProperties: Setting state to 14
,08-03 12:37:44.986  3912  3924 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-03 12:37:44.990  3912  3924 D BluetoothBondStateMachine: make
,08-03 12:37:44.996  3912  3929 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-03 12:37:45.005  3912  3924 I BluetoothAdapterState: Entering PendingCommandState
,08-03 12:37:45.009  3912  3912 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-03 12:37:45.023  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:45.027  3912  3912 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 12:37:45.028  3912  3912 D BtGatt.GattService: Received start request. Starting profile...
,08-03 12:37:45.029  3912  3912 D BtGatt.GattService: start()
08-03 12:37:45.029  3912  3912 I bt_bluedroid: get_profile_interface gatt
,08-03 12:37:45.032  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:45.033  3912  3912 D BtGatt.AdvertiseManager: advertise manager created
,08-03 12:37:45.047  3912  3912 V BluetoothAdapterState: isTurningOff()=false
,08-03 12:37:45.048  3912  3912 V BluetoothAdapterState: isTurningOn()=false
08-03 12:37:45.048  3912  3912 V BluetoothAdapterState: isBleTurningOn()=true
,08-03 12:37:45.048  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:45.049  3912  3924 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-03 12:37:45.050  3912  3924 I bt_bluedroid: enable
08-03 12:37:45.051  3912  3925 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-03 12:37:45.052  3912  3925 I bt_hci  : start_up
,08-03 12:37:45.072  3912  3925 I bt_vendor: alloc value 0xb39f1189
,08-03 12:37:45.073  3912  3925 I bt_vendor: init
08-03 12:37:45.073  3912  3925 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-03 12:37:45.073  3912  3925 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-03 12:37:45.184  3912  3925 D bt_hci  : start_up starting async portion
,08-03 12:37:45.185  3912  3932 I bt_hci  : event_finish_startup
,08-03 12:37:45.185  3912  3932 I bt_hci_h4: hal_open
08-03 12:37:45.185  3912  3932 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-03 12:37:45.195  3912  3932 I bt_userial_vendor: device fd = 51 open
,08-03 12:37:45.225  3912  3932 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 12:37:45.257  3912  3932 D bt_hwcfg: Chipset BCM4354A2
,08-03 12:37:45.258  3912  3932 D bt_hwcfg: Target name = [BCM4354A2]
08-03 12:37:45.259  3912  3932 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-03 12:37:45.917  3912  3932 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-03 12:37:45.918  3912  3932 D bt_hwcfg: Settlement delay -- 100 ms
,08-03 12:37:45.919  3912  3932 I bt_hwcfg: Setting fw settlement delay to 100 
,08-03 12:37:46.035  3912  3932 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 12:37:46.036  3912  3932 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-03 12:37:46.066  3912  3932 I bt_hwcfg: vendor lib fwcfg completed
,08-03 12:37:46.066  3912  3932 I bt_vendor: firmware callback
08-03 12:37:46.066  3912  3932 I bt_hci  : firmware_config_callback
,08-03 12:37:46.078  3912  3934 I bt_btu  : btu_task pending for preload complete event
,08-03 12:37:46.079  3912  3934 I bt_btu_task: Bluetooth chip preload is complete
,08-03 12:37:46.079  3912  3934 I bt_btu  : btu_task received preload complete event
,08-03 12:37:46.090  3912  3934 I         : BTE_InitTraceLevels -- TRC_HCI
,08-03 12:37:46.090  3912  3934 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-03 12:37:46.091  3912  3934 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
08-03 12:37:46.091  3912  3934 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 12:37:46.091  3912  3934 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 12:37:46.092  3912  3934 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 12:37:46.092  3912  3934 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 12:37:46.092  3912  3934 I         : BTE_InitTraceLevels -- TRC_BTM
,08-03 12:37:46.093  3912  3934 I         : BTE_InitTraceLevels -- TRC_GAP
08-03 12:37:46.093  3912  3934 I         : BTE_InitTraceLevels -- TRC_PAN
08-03 12:37:46.093  3912  3934 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 12:37:46.094  3912  3934 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 12:37:46.094  3912  3934 I         : BTE_InitTraceLevels -- TRC_SMP
,08-03 12:37:46.094  3912  3934 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 12:37:46.095  3912  3934 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-03 12:37:46.225  3912  3934 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb396ed9d
,08-03 12:37:46.225  3912  3934 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb396ed9d 
,08-03 12:37:46.238  3912  3928 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,08-03 12:37:46.241  3912  3928 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-03 12:37:46.242  3912  3928 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-03 12:37:46.249  3912  3928 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 12:37:46.252  3912  3928 D BluetoothAdapterProperties: Scan Mode:20
,08-03 12:37:46.252  3912  3928 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 12:37:46.253  3912  3928 D bt_hci  : do_postload posting postload work item
08-03 12:37:46.253  3912  3932 I bt_hci  : event_postload
08-03 12:37:46.253  3912  3932 I bt_vendor: sco_config_cb
,08-03 12:37:46.253  3912  3932 I bt_hci  : sco_config_callback postload finished.
,08-03 12:37:46.256  3912  3928 D bt_bte_conf: Device ID record 1 : primary
08-03 12:37:46.256  3912  3928 D bt_bte_conf:   vendorId            = 000f
08-03 12:37:46.256  3912  3928 D bt_bte_conf:   vendorIdSource      = 0001
08-03 12:37:46.256  3912  3928 D bt_bte_conf:   product             = 1200
08-03 12:37:46.257  3912  3928 D bt_bte_conf:   version             = 1436
,08-03 12:37:46.257  3912  3928 D bt_bte_conf:   clientExecutableURL = 
08-03 12:37:46.257  3912  3928 D bt_bte_conf:   serviceDescription  = 
08-03 12:37:46.257  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:46.257  3912  3928 D bt_bte_conf:   documentationURL    = 
08-03 12:37:46.258  3912  3932 I bt_vendor: low_power_mode_cb
08-03 12:37:46.261  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:46.259  3912  3928 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-03 12:37:46.262  3912  3925 D bt_stack_manager: event_start_up_stack finished
08-03 12:37:46.262  3912  3924 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-03 12:37:46.263  3912  3924 D BluetoothAdapterProperties: Setting state to 15
08-03 12:37:46.263  3912  3924 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-03 12:37:46.265  3912  3924 I BluetoothAdapterState: Entering BleOnState
,08-03 12:37:46.269  3912  3924 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-03 12:37:46.269  3912  3924 D BluetoothAdapterProperties: Setting state to 11
,08-03 12:37:46.270  3912  3924 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-03 12:37:46.282  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:46.286  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:46.286  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:46.288  3912  3912 D HeadsetService: Received start request. Starting profile...
,08-03 12:37:46.291  3912  3912 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-03 12:37:46.292  3912  3912 D HeadsetStateMachine: make
,08-03 12:37:46.296  3912  3924 I BluetoothAdapterState: Entering PendingCommandState
,08-03 12:37:46.304  3912  3912 D HeadsetStateMachine: max_hf_connections = 1
,08-03 12:37:46.304  3912  3912 I bt_bluedroid: get_profile_interface handsfree
08-03 12:37:46.304  3912  3928 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-03 12:37:46.305  3912  3928 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-03 12:37:46.308  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:46.309  3912  3912 D A2dpService: Received start request. Starting profile...
08-03 12:37:46.309  3912  3912 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-03 12:37:46.310  3912  3912 I bt_bluedroid: get_profile_interface avrcp
,08-03 12:37:46.316  3912  3912 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-03 12:37:46.316  3912  3912 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 12:37:46.317  3912  3912 D A2dpStateMachine: make
,08-03 12:37:46.319  3912  3912 I bt_bluedroid: get_profile_interface a2dp
,08-03 12:37:46.319  3912  3928 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-03 12:37:46.321  3912  3943 D A2dpStateMachine: Enter Disconnected: -2
,08-03 12:37:46.323  3912  3912 I BluetoothHidServiceJni: classInitNative: succeeds
,08-03 12:37:46.324  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:46.324  3912  3912 D HidService: Received start request. Starting profile...
,08-03 12:37:46.324  3912  3912 I bt_bluedroid: get_profile_interface hidhost
08-03 12:37:46.325  3912  3912 D HidService: setHidService(): set to: null
08-03 12:37:46.325  3912  3928 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39503e5
08-03 12:37:46.325  3912  3912 I BluetoothHealthServiceJni: classInitNative: succeeds,
08-03 12:37:46.325  3912  3928 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-03 12:37:46.326  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:46.326  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 12:37:46.328  3912  3912 D HealthService: Received start request. Starting profile...
,08-03 12:37:46.329  3912  3912 I bt_bluedroid: get_profile_interface health
,08-03 12:37:46.330  3912  3912 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-03 12:37:46.331  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
08-03 12:37:46.332  3912  3912 D PanService: Received start request. Starting profile...
,08-03 12:37:46.332  3912  3912 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 12:37:46.332  3912  3912 I bt_bluedroid: get_profile_interface pan
08-03 12:37:46.333  3912  3928 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-03 12:37:46.335  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:46.335  3912  3912 D BluetoothMapService: Received start request. Starting profile...
08-03 12:37:46.335  3912  3912 D BluetoothMapService: start()
,08-03 12:37:46.338  3912  3912 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-03 12:37:46.339  3912  3912 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-03 12:37:46.339  3912  3912 D BluetoothMapAppObserver: createReceiver()
,08-03 12:37:46.340  3912  3912 D BluetoothMapAppObserver: initObservers()
08-03 12:37:46.340  3912  3912 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-03 12:37:46.348  3912  3912 V BluetoothAdapterState: isTurningOff()=false
,08-03 12:37:46.348  3912  3912 V BluetoothAdapterState: isTurningOn()=true
08-03 12:37:46.348  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:46.349  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 12:37:46.350  3912  3912 V BluetoothAdapterState: isTurningOff()=false
,08-03 12:37:46.350  3912  3912 V BluetoothAdapterState: isTurningOn()=true
08-03 12:37:46.350  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:46.350  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 12:37:46.350  3912  3912 V BluetoothAdapterState: isTurningOff()=false
,08-03 12:37:46.350  3912  3912 V BluetoothAdapterState: isTurningOn()=true
,08-03 12:37:46.351  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:46.351  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 12:37:46.351  3912  3941 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 12:37:46.351  3912  3912 V BluetoothAdapterState: isTurningOff()=false
08-03 12:37:46.351  3912  3912 V BluetoothAdapterState: isTurningOn()=true
08-03 12:37:46.351  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:46.351  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 12:37:46.352  3912  3912 V BluetoothAdapterState: isTurningOff()=false
08-03 12:37:46.352  3912  3912 V BluetoothAdapterState: isTurningOn()=true
08-03 12:37:46.352  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:46.352  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 12:37:46.352  3912  3912 V BluetoothAdapterState: isTurningOff()=false
08-03 12:37:46.352  3912  3912 V BluetoothAdapterState: isTurningOn()=true
08-03 12:37:46.352  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:46.352  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:46.352  3912  3924 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-03 12:37:46.352  3912  3924 D BluetoothAdapterProperties: ScanMode =  20
08-03 12:37:46.353  3912  3924 D BluetoothAdapterProperties: State =  11
08-03 12:37:46.353  3912  3924 D BluetoothAdapterProperties: Setting state to 12
08-03 12:37:46.353  3912  3924 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-03 12:37:46.354  3504  3514 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 12:37:46.354  3912  3924 I BluetoothAdapterState: Entering OnState
08-03 12:37:46.357  3912  3928 D BluetoothAdapterProperties: Scan Mode:21
,08-03 12:37:46.357  3912  3928 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-03 12:37:46.359  3504  3515 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 12:37:46.361  1360  1379 D BluetoothPan: onBluetoothStateChange on: true
08-03 12:37:46.364  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:46.364  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:46.364  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:46.364  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:46.364  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:46.364  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:46.364  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:46.364  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:37:46.364  1360  1853 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-03 12:37:46.365  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 12:37:46.365  1360  1360 D PanProfile: Bluetooth service connected
08-03 12:37:46.366  3912  3912 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-03 12:37:46.367  1360  1379 D BluetoothMap: onBluetoothStateChange: up=true
,08-03 12:37:46.367  3912  3912 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-03 12:37:46.369  1360  1383 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 12:37:46.369  3504  3504 D BluetoothA2dp: Proxy object connected
08-03 12:37:46.369  3912  3912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 12:37:46.371  1360  1383 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:37:46.371  1360  1360 D BluetoothA2dp: Proxy object connected
,08-03 12:37:46.371  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:46.374  1748  1765 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 12:37:46.374  3912  3912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 12:37:46.374  3504  3514 D BluetoothPan: onBluetoothStateChange on: true
,08-03 12:37:46.377  3504  3515 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 12:37:46.378  1360  1379 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 12:37:46.378  3912  3912 D ObexServerSockets: Succeed to create listening sockets 
,08-03 12:37:46.379  3912  3912 D ObexServerSockets0: startAccept()
,08-03 12:37:46.379  3912  3912 D ObexServerSockets0: prepareForNewConnect()
08-03 12:37:46.380  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:46.380  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-03 12:37:46.380  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:46.380  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:46.380  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:46.380  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:46.380  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:46.380  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:46.380   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 12:37:46.380   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:37:46.380  3504  3900 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 12:37:46.382  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:46.383  3504  3514 D BluetoothMap: onBluetoothStateChange: up=true
,08-03 12:37:46.384   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:37:46.384   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 12:37:46.385  3912  3912 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-03 12:37:46.385  3912  3912 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-03 12:37:46.385   873   873 D BluetoothA2dp: Proxy object connected
08-03 12:37:46.386  3912  3948 D ObexServerSockets0: Accepting socket connection...
08-03 12:37:46.386  3912  3949 D ObexServerSockets0: Accepting socket connection...
,08-03 12:37:46.378  3504  3504 D BluetoothPan: BluetoothPAN Proxy object connected
,08-03 12:37:46.387  3504  3504 D PanProfile: Bluetooth service connected
,08-03 12:37:46.387  1360  1360 D BluetoothInputDevice: Proxy object connected
08-03 12:37:46.387  1360  1360 D HidProfile: Bluetooth service connected
08-03 12:37:46.389  3504  3504 D BluetoothInputDevice: Proxy object connected,
08-03 12:37:46.389  3504  3504 D HidProfile: Bluetooth service connected
08-03 12:37:46.390   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-03 12:37:46.392  1360  1360 D BluetoothMap: Proxy object connected,
,08-03 12:37:46.392  3912  3912 D BluetoothMapService: onReceive
08-03 12:37:46.393  1360  1360 D MapProfile: Bluetooth service connected
,08-03 12:37:46.393  1360  1360 D BluetoothMap: getConnectedDevices()
08-03 12:37:46.393  3912  3912 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:37:46.393  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:46.393  3912  3912 D BluetoothMapService: STATE_ON
,08-03 12:37:46.395  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:46.397  3504  3504 D BluetoothMap: Proxy object connected
08-03 12:37:46.397  3504  3504 D MapProfile: Bluetooth service connected
,08-03 12:37:46.397  3504  3504 D BluetoothMap: getConnectedDevices()
,08-03 12:37:46.406  3504  3504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 12:37:46.419  3912  3912 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-03 12:37:46.419  3912  3912 D ObexServerSockets0: prepareForNewConnect()
,08-03 12:37:46.424  3504  3504 D DockEventReceiver: finishStartingService: stopping service
,08-03 12:37:46.426  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 12:37:46.435  1360  1360 D BluetoothPbap: Proxy object connected
,08-03 12:37:46.435  1360  1360 D PbapServerProfile: Bluetooth service connected
08-03 12:37:46.435  3504  3504 D BluetoothPbap: Proxy object connected
,08-03 12:37:46.436  3504  3504 D PbapServerProfile: Bluetooth service connected
,08-03 12:37:46.444  3912  3954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 12:37:46.467  3912  3958 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 12:37:46.473  3912  3958 I BtOppRfcommListener: Accept thread started.
,08-03 12:37:46.475  1748  1938 D BluetoothHeadset: Proxy object connected
,08-03 12:37:46.476  1360  1379 D BluetoothHeadset: Proxy object connected
08-03 12:37:46.476  1360  1360 D HeadsetProfile: Bluetooth service connected
08-03 12:37:46.476   873   873 D BluetoothHeadset: Proxy object connected
08-03 12:37:46.476   873   873 D BluetoothHeadset: Proxy object connected
08-03 12:37:46.476   873   873 D BluetoothHeadset: Proxy object connected
,08-03 12:37:46.476  3504  3900 D BluetoothHeadset: Proxy object connected
,08-03 12:37:46.477  3504  3504 D HeadsetProfile: Bluetooth service connected
,08-03 12:37:46.478  3504  3515 D BluetoothHeadset: Proxy object connected
,08-03 12:37:46.480   873   890 D BluetoothHeadset: Proxy object connected
,08-03 12:37:46.480   873   890 D BluetoothHeadset: Proxy object connected
,08-03 12:37:46.481  3504  3504 D HeadsetProfile: Bluetooth service connected
,08-03 12:37:46.484   873   890 D BluetoothHeadset: Proxy object connected
,08-03 12:37:47.727  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 12:37:47.728  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:37:47.898  2598  2609 D Finsky  : [177] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-03 12:37:47.917  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 12:37:47.930  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 12:37:47.934  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 12:37:47.993  1526  3645 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-03 12:37:47.993  1526  3645 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-03 12:37:47.993  1526  3645 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 12:37:47.993  1526  3645 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 12:37:48.039  2598  2609 D Finsky  : [177] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-03 12:37:48.191   873  1745 I ActivityManager: Killing 1817:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-03 12:37:48.270   873  1313 D WifiService: Client connection lost with reason: 4
,08-03 12:37:50.076   873  1303 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 12:37:50.098   873   886 I ActivityManager: Start proc 3963:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher
,08-03 12:37:50.190  1841  1841 V GmsNetworkLocationProvi: DISABLE
,08-03 12:37:50.196  1841  1841 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,08-03 12:37:50.399   873   884 I ActivityManager: Start proc 3982:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,08-03 12:37:50.456   873  1392 I ActivityManager: Start proc 3997:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-03 12:37:50.487  3982  3982 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,08-03 12:37:50.537  3997  3997 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-03 12:37:50.570  3997  3997 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-03 12:37:50.580   873  1767 I ActivityManager: Killing 3602:com.google.android.youtube/u0a86 (adj 15): empty #17
,08-03 12:37:50.650  1875  4018 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-03 12:37:50.658  3963  4019 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-03 12:37:50.662  1875  4018 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-03 12:37:50.693  1875  2162 I Icing   : updateResources: need to parse f{com.google.android.gms}
,08-03 12:37:50.733  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 12:37:50.734  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@196a0db added. We now have 6 listener(s)
08-03 12:37:50.734  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 12:37:50.737  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:37:50.737  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6876778 added. We now have 7 listener(s)
08-03 12:37:50.737  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 12:37:50.738  3396  3442 I System.out: IsBluetoothEnabled
,08-03 12:37:50.744  3912  3924 D BluetoothAdapterState: Current state: ON, message: 23
,08-03 12:37:50.744  3912  3924 D BluetoothAdapterProperties: Setting state to 13
,08-03 12:37:50.744  3912  3924 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-03 12:37:50.745  3912  3924 D BluetoothAdapterProperties: onBluetoothDisable()
,08-03 12:37:50.745  3912  3924 I BluetoothAdapterState: Entering PendingCommandState
,08-03 12:37:50.747  3912  3928 D BluetoothAdapterProperties: Scan Mode:20
,08-03 12:37:50.747  3912  3924 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-03 12:37:50.752  3912  3912 D BluetoothMapService: onReceive
,08-03 12:37:50.752  3912  3912 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:37:50.752  3912  3912 D BluetoothMapService: STATE_TURNING_OFF
08-03 12:37:50.753  3912  3912 D BluetoothMapService: MAP Service closeService in
,08-03 12:37:50.753  3912  3912 D BluetoothMapMasInstance0: MAP Service shutdown
08-03 12:37:50.753  3912  3912 D ObexServerSockets0: shutdown(block = true)
08-03 12:37:50.754  3912  3912 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 12:37:50.754  3912  3912 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 12:37:50.755  3912  3948 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-03 12:37:50.755  3912  3936 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-03 12:37:50.756  3396  3396 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:37:50.756  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:50.756  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:50.756  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:50.756  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:50.756  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:37:50.756  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:50.756  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:50.756  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:37:50.756  3912  3949 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-03 12:37:50.757  3396  3396 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 12:37:50.757  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:37:50.758  3912  3912 I BtOppRfcommListener: stopping Accept Thread
08-03 12:37:50.758  3912  3958 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-03 12:37:50.760  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:50.762  3504  3504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-03 12:37:50.762  3912  3958 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 12:37:50.768  3912  3912 D HeadsetService: Received stop request...Stopping profile...
,08-03 12:37:50.770  1748  2030 D BluetoothHeadset: Proxy object disconnected
08-03 12:37:50.770  1360  1853 D BluetoothHeadset: Proxy object disconnected
08-03 12:37:50.770  3912  3912 D A2dpService: Received stop request...Stopping profile...
08-03 12:37:50.770   873   873 D BluetoothHeadset: Proxy object disconnected
08-03 12:37:50.770   873   873 D BluetoothHeadset: Proxy object disconnected
,08-03 12:37:50.770   873   873 D BluetoothHeadset: Proxy object disconnected
08-03 12:37:50.770  3912  3943 D A2dpStateMachine: Exit Disconnected: -1
08-03 12:37:50.771  3504  3900 D BluetoothHeadset: Proxy object disconnected
,08-03 12:37:50.771   873   873 D BluetoothA2dp: Proxy object disconnected
08-03 12:37:50.772  3912  3912 D HidService: Received stop request...Stopping profile...
08-03 12:37:50.772  3912  3912 D HidService: Stopping Bluetooth HidService
,08-03 12:37:50.773  3912  3912 D HealthService: Received stop request...Stopping profile...
,08-03 12:37:50.774  3912  3912 D PanService: Received stop request...Stopping profile...
,08-03 12:37:50.777  1360  1360 D HeadsetProfile: Bluetooth service disconnected
08-03 12:37:50.777  1360  1360 D BluetoothA2dp: Proxy object disconnected
08-03 12:37:50.778  1360  1360 D BluetoothInputDevice: Proxy object disconnected
08-03 12:37:50.778  1360  1360 D HidProfile: Bluetooth service disconnected
,08-03 12:37:50.779  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 12:37:50.779  1360  1360 D PanProfile: Bluetooth service disconnected
,08-03 12:37:50.781  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 12:37:50.782  3912  3912 D BluetoothMapService: Received stop request...Stopping profile...
08-03 12:37:50.782  3912  3912 D BluetoothMapService: stop()
08-03 12:37:50.783  3912  3912 D BluetoothMapAppObserver: deinitObservers()
,08-03 12:37:50.783  3912  3912 D BluetoothMapAppObserver: removeReceiver()
,08-03 12:37:50.784  1360  1360 D BluetoothMap: Proxy object disconnected
,08-03 12:37:50.784  3912  3912 V BluetoothAdapterState: isTurningOff()=true
08-03 12:37:50.784  1360  1360 D MapProfile: Bluetooth service disconnected
08-03 12:37:50.784  3912  3912 V BluetoothAdapterState: isTurningOn()=false
08-03 12:37:50.784  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:50.784  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:50.785  3912  3912 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-03 12:37:50.785  3912  3912 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 12:37:50.785  3504  3504 D DockEventReceiver: finishStartingService: stopping service
08-03 12:37:50.785  3912  3928 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-03 12:37:50.786  3912  3934 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 12:37:50.786  3912  3934 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 12:37:50.786  3912  3934 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 12:37:50.786  3912  3928 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-03 12:37:50.786  3912  3912 V BluetoothAdapterState: isTurningOff()=true
08-03 12:37:50.786  3912  3912 V BluetoothAdapterState: isTurningOn()=false
,08-03 12:37:50.786  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:50.786  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 12:37:50.787  3504  3504 D HeadsetProfile: Bluetooth service disconnected
08-03 12:37:50.787  3504  3504 D BluetoothA2dp: Proxy object disconnected
08-03 12:37:50.787  3912  3934 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 12:37:50.787  3504  3504 D BluetoothInputDevice: Proxy object disconnected
08-03 12:37:50.787  3504  3504 D HidProfile: Bluetooth service disconnected
08-03 12:37:50.787  3912  3934 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 12:37:50.787  3504  3504 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 12:37:50.787  3504  3504 D PanProfile: Bluetooth service disconnected
,08-03 12:37:50.787  3912  3934 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 12:37:50.787  3912  3934 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 12:37:50.787  3912  3934 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 12:37:50.787  3504  3504 D BluetoothMap: Proxy object disconnected
08-03 12:37:50.787  3912  3934 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 12:37:50.787  3504  3504 D MapProfile: Bluetooth service disconnected
08-03 12:37:50.787  3912  3928 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-03 12:37:50.788  3912  3912 V BluetoothAdapterState: isTurningOff()=true
08-03 12:37:50.788  3912  3912 V BluetoothAdapterState: isTurningOn()=false
,08-03 12:37:50.788  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:50.788  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:50.788  3912  3912 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 12:37:50.788  3912  3928 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-03 12:37:50.789  3912  3912 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 12:37:50.789  3912  3912 V BluetoothAdapterState: isTurningOff()=true
,08-03 12:37:50.789  3912  3912 V BluetoothAdapterState: isTurningOn()=false
08-03 12:37:50.789  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:50.789  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:50.789  3912  3912 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 12:37:50.789  3912  3928 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-03 12:37:50.790  3912  3912 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 12:37:50.790  3912  3912 V BluetoothAdapterState: isTurningOff()=true
,08-03 12:37:50.790  3912  3912 V BluetoothAdapterState: isTurningOn()=false
08-03 12:37:50.791  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:50.791  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:50.791  3912  3912 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-03 12:37:50.791  3912  3912 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 12:37:50.794  1360  1360 D BluetoothPbap: Proxy object disconnected
08-03 12:37:50.794  3912  3912 D BluetoothMapService: MAP Service closeService in
08-03 12:37:50.794  3912  3912 V BluetoothAdapterState: isTurningOff()=true
,08-03 12:37:50.794  3912  3912 V BluetoothAdapterState: isTurningOn()=false
08-03 12:37:50.794  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 12:37:50.794  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 12:37:50.795  3912  3924 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-03 12:37:50.795  3912  3924 D BluetoothAdapterProperties: Setting state to 15
,08-03 12:37:50.795  3912  3924 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-03 12:37:50.795  3912  3924 I BluetoothAdapterState: Entering BleOnState
,08-03 12:37:50.796  3912  3912 D BluetoothMapService: cleanup()
,08-03 12:37:50.796  3912  3912 D BluetoothMapService: MAP Service closeService in
,08-03 12:37:50.797  3504  3900 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-03 12:37:50.798  3504  3515 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 12:37:50.799  1360  1853 D BluetoothPan: onBluetoothStateChange on: false
,08-03 12:37:50.799  1360  1360 D PbapServerProfile: Bluetooth service disconnected
,08-03 12:37:50.799  1360  1379 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-03 12:37:50.801  1360  1383 D BluetoothMap: onBluetoothStateChange: up=false
,08-03 12:37:50.801  1360  1853 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 12:37:50.802  1360  1379 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:37:50.802  1748  1765 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:37:50.802  3504  3514 D BluetoothPan: onBluetoothStateChange on: false
,08-03 12:37:50.803  3504  3900 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:37:50.803  1360  1383 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 12:37:50.804   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 12:37:50.804   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:37:50.804  3504  3515 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 12:37:50.805  3504  3514 D BluetoothMap: onBluetoothStateChange: up=false
,08-03 12:37:50.805   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:37:50.805   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 12:37:50.806  3912  3924 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-03 12:37:50.806  3912  3924 D BluetoothAdapterProperties: Setting state to 16
08-03 12:37:50.809  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-03 12:37:50.806  3912  3924 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-03 12:37:50.809  3504  3504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-03 12:37:50.810  3912  3924 D BluetoothAdapterProperties: onBleDisable
08-03 12:37:50.810  3912  3924 I BluetoothAdapterState: Entering PendingCommandState
08-03 12:37:50.810  3912  3925 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-03 12:37:50.811  3912  3928 D BluetoothAdapterProperties: Scan Mode:20
08-03 12:37:50.812  3912  3934 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-03 12:37:50.812  3912  3934 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 12:37:50.813  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:50.814  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 12:37:50.817  3504  3504 D DockEventReceiver: finishStartingService: stopping service
,08-03 12:37:50.833  3997  4016 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,08-03 12:37:50.882  3963  4019 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 223 ms] updated apps [took 223 ms] 
,08-03 12:37:51.017  3912  3928 I bt_hci  : shut_down
,08-03 12:37:51.026  3912  3932 D bt_hwcfg: hw_epilog_process
,08-03 12:37:51.027  3912  3932 I bt_vendor: low_power_mode_cb
,08-03 12:37:51.048  3912  3932 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-03 12:37:51.048  3912  3932 I bt_vendor: epilog_cb
,08-03 12:37:51.048  3912  3932 I bt_hci  : epilog_finished_callback
,08-03 12:37:51.065  3912  3928 I bt_hci_h4: hal_close
,08-03 12:37:51.066  3912  3928 I bt_userial_vendor: device fd = 51 close
,08-03 12:37:51.102  3997  4016 D ContactDirectoryManager: Found com.google.contacts.gal.provider
,08-03 12:37:51.102  3997  4016 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,08-03 12:37:51.127   873  1715 I ActivityManager: Start proc 4028:com.google.android.gm.exchange/u0a77 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,08-03 12:37:51.192   873  1754 I ActivityManager: Killing 3754:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-03 12:37:51.253  3912  3925 D bt_stack_manager: event_shut_down_stack finished.
,08-03 12:37:51.254  3912  3924 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-03 12:37:51.256  4028  4028 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,08-03 12:37:51.257  3912  3912 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 12:37:51.257  3912  3924 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-03 12:37:51.258  3912  3912 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 12:37:51.258  3912  3912 D BtGatt.GattService: stop()
08-03 12:37:51.258  3912  3912 D BtGatt.AdvertiseManager: advertise clients cleared
08-03 12:37:51.260  3912  3912 V BluetoothAdapterState: isTurningOff()=false
08-03 12:37:51.260  3912  3912 V BluetoothAdapterState: isTurningOn()=false
08-03 12:37:51.260  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:51.260  3912  3912 V BluetoothAdapterState: isBleTurningOff()=true
,08-03 12:37:51.260  3912  3924 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-03 12:37:51.261  3912  3924 D BluetoothAdapterProperties: Setting state to 10
08-03 12:37:51.261  3912  3924 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-03 12:37:51.262  3912  3924 I BluetoothAdapterState: Entering OffState
08-03 12:37:51.263   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-03 12:37:51.272  3912  3912 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-03 12:37:51.273  3912  3912 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-03 12:37:51.273  3912  3912 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-03 12:37:51.275  3912  3925 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-03 12:37:51.278  3912  3925 D bt_stack_manager: event_clean_up_stack finished.
,08-03 12:37:51.285  3912  3912 I art     : System.exit called, status: 0
08-03 12:37:51.285  3912  3912 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-03 12:37:51.320   873  1685 I ActivityManager: Start proc 4041:com.google.android.gm/u0a78 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,08-03 12:37:51.349   873  1687 I ActivityManager: Start proc 4053:com.google.process.gapps/u0a99 for content provider com.google.android.syncadapters.contacts/.GalProvider
,08-03 12:37:51.355   873  1754 I ActivityManager: Killing 3628:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,08-03 12:37:51.415   873  1745 I ActivityManager: Process com.android.bluetooth (pid 3912) has died,
,08-03 12:37:51.427   873  1694 I ActivityManager: Killing 3650:com.android.chrome/u0a40 (adj 15): empty #17
,08-03 12:37:51.429  4041  4041 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,08-03 12:37:51.509  4041  4067 I Gmail   : getAccountsCursor
,08-03 12:37:51.545  4041  4068 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,08-03 12:37:51.549  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 12:37:51.572  4053  4053 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,08-03 12:37:51.622  4053  4053 I GoogleHttpClient: GMS http client unavailable, use old client
,08-03 12:37:51.651  4041  4041 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-03 12:37:51.664  3997  4016 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,08-03 12:37:51.690  3997  4016 I ContactDirectoryManager: Discovered 0 contact directories in 771ms
,08-03 12:37:51.731  4041  4082 E Gmail   : Error finding the version of the Email provider.....
08-03 12:37:51.731  4041  4082 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
08-03 12:37:51.731  4041  4082 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
08-03 12:37:51.731  4041  4082 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
08-03 12:37:51.731  4041  4082 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
08-03 12:37:51.731  4041  4082 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 12:37:51.731  4041  4082 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 12:37:51.731  4041  4082 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
08-03 12:37:51.731  4041  4082 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 12:37:51.732  4041  4082 W EmailMigration: We do not support migrating this version of the Email provider.
,08-03 12:37:51.746  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 12:37:51.746  3396  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:51.746  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:51.746  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:51.746  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:51.746  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:37:51.746  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:51.746  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:51.746  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:51.746  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 12:37:51.746  3396  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:51.753  4041  4084 I Gmail   : getAccountsCursor
,08-03 12:37:51.779   873   890 I ActivityManager: Start proc 4087:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-03 12:37:51.795  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 12:37:51.821   873  1685 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,08-03 12:37:51.850  4028  4028 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-03 12:37:51.853  4041  4100 I Gmail   : Observing account changes for notifications
,08-03 12:37:51.871  4028  4028 I Exchange: EasService.onCreate
,08-03 12:37:51.882  4087  4087 D AdapterServiceConfig: Adding HeadsetService
08-03 12:37:51.882  4087  4087 D AdapterServiceConfig: Adding A2dpService
08-03 12:37:51.882  4087  4087 D AdapterServiceConfig: Adding HidService
,08-03 12:37:51.882  4087  4087 D AdapterServiceConfig: Adding HealthService
08-03 12:37:51.882  4087  4087 D AdapterServiceConfig: Adding PanService
08-03 12:37:51.883  4087  4087 D AdapterServiceConfig: Adding GattService
08-03 12:37:51.883  4087  4087 D AdapterServiceConfig: Adding BluetoothMapService
,08-03 12:37:51.887  4028  4104 I Exchange: RestartPingTask
,08-03 12:37:51.893  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 12:37:51.894   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9d6fb2c:true
,08-03 12:37:51.895  4087  4087 D BluetoothAdapterState: make() - Creating AdapterState
,08-03 12:37:51.897  4087  4087 I bt_bluedroid: init
,08-03 12:37:51.897  4087  4107 I BluetoothAdapterState: Entering OffState
,08-03 12:37:51.899  4087  4109 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-03 12:37:51.899  4087  4109 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 12:37:51.899  4087  4109 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-03 12:37:51.899  4087  4109 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-03 12:37:51.899  4087  4087 I bt_bluedroid: get_profile_interface socket
,08-03 12:37:51.901  4087  4087 I bt_bluedroid: get_profile_interface sdp
,08-03 12:37:51.903  4087  4101 I bt_bluedroid: config_hci_snoop_log
,08-03 12:37:51.903  4087  4112 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-03 12:37:51.904   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-03 12:37:51.904  4087  4112 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 12:37:51.907  4087  4107 D BluetoothAdapterState: Current state: OFF, message: 0
,08-03 12:37:51.907  4087  4107 D BluetoothAdapterProperties: Setting state to 14
08-03 12:37:51.907  4087  4107 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-03 12:37:51.908  4087  4107 D BluetoothBondStateMachine: make
,08-03 12:37:51.910  4087  4113 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-03 12:37:51.912  4087  4107 I BluetoothAdapterState: Entering PendingCommandState
,08-03 12:37:51.912  4028  4028 I Exchange: RestartPingsTask did not start any pings.
,08-03 12:37:51.912  4028  4028 I Exchange: PSS stopIfIdle
08-03 12:37:51.912  4028  4028 I Exchange: PSS has no active accounts; stopping service.
08-03 12:37:51.913  4087  4087 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-03 12:37:51.913  4028  4028 I Exchange: onDestroy
,08-03 12:37:51.915  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:51.916  4087  4087 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 12:37:51.916  4087  4087 D BtGatt.GattService: Received start request. Starting profile...
,08-03 12:37:51.916  4087  4087 D BtGatt.GattService: start()
08-03 12:37:51.916  4087  4087 I bt_bluedroid: get_profile_interface gatt
,08-03 12:37:51.917  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
08-03 12:37:51.917  4087  4087 D BtGatt.AdvertiseManager: advertise manager created
,08-03 12:37:51.921  4087  4087 V BluetoothAdapterState: isTurningOff()=false
,08-03 12:37:51.921  4087  4087 V BluetoothAdapterState: isTurningOn()=false
08-03 12:37:51.921  4087  4087 V BluetoothAdapterState: isBleTurningOn()=true
08-03 12:37:51.921  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:51.921  4087  4107 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-03 12:37:51.922  4087  4107 I bt_bluedroid: enable
08-03 12:37:51.922  4087  4109 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-03 12:37:51.922  4087  4109 I bt_hci  : start_up
,08-03 12:37:51.926  4087  4109 I bt_vendor: alloc value 0xb39f1189
,08-03 12:37:51.926  4087  4109 I bt_vendor: init
08-03 12:37:51.926  4087  4109 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-03 12:37:51.926  4087  4109 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-03 12:37:51.974  4041  4114 I Gmail   : notifyAccountChanged
,08-03 12:37:51.975  4041  4080 I Gmail   : getAccountsCursor
,08-03 12:37:51.978  4041  4114 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
08-03 12:37:51.981  4041  4114 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,08-03 12:37:51.986  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 12:37:51.996  4041  4114 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,08-03 12:37:52.000  4041  4114 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,08-03 12:37:52.032  4087  4109 D bt_hci  : start_up starting async portion
,08-03 12:37:52.032  4087  4117 I bt_hci  : event_finish_startup
08-03 12:37:52.033  4087  4117 I bt_hci_h4: hal_open
08-03 12:37:52.033  4087  4117 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-03 12:37:52.038  4087  4117 I bt_userial_vendor: device fd = 51 open
,08-03 12:37:52.075  4087  4117 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 12:37:52.107  4087  4117 D bt_hwcfg: Chipset BCM4354A2
,08-03 12:37:52.107  4087  4117 D bt_hwcfg: Target name = [BCM4354A2]
08-03 12:37:52.108  4087  4117 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-03 12:37:52.113  4041  4068 I Gmail   : getAccountsCursor
,08-03 12:37:52.123  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 12:37:52.745  4087  4117 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-03 12:37:52.746  4087  4117 D bt_hwcfg: Settlement delay -- 100 ms
,08-03 12:37:52.747  4087  4117 I bt_hwcfg: Setting fw settlement delay to 100 
,08-03 12:37:52.863  4087  4117 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 12:37:52.865  4087  4117 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-03 12:37:52.893  4087  4117 I bt_hwcfg: vendor lib fwcfg completed
,08-03 12:37:52.893  4087  4117 I bt_vendor: firmware callback
,08-03 12:37:52.894  4087  4117 I bt_hci  : firmware_config_callback
,08-03 12:37:52.904  4087  4120 I bt_btu  : btu_task pending for preload complete event
,08-03 12:37:52.905  4087  4120 I bt_btu_task: Bluetooth chip preload is complete
08-03 12:37:52.905  4087  4120 I bt_btu  : btu_task received preload complete event
,08-03 12:37:52.915  4087  4120 I         : BTE_InitTraceLevels -- TRC_HCI
,08-03 12:37:52.915  4087  4120 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-03 12:37:52.915  4087  4120 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-03 12:37:52.916  4087  4120 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 12:37:52.916  4087  4120 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-03 12:37:52.916  4087  4120 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 12:37:52.917  4087  4120 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 12:37:52.917  4087  4120 I         : BTE_InitTraceLevels -- TRC_BTM
,08-03 12:37:52.917  4087  4120 I         : BTE_InitTraceLevels -- TRC_GAP
08-03 12:37:52.917  4087  4120 I         : BTE_InitTraceLevels -- TRC_PAN
,08-03 12:37:52.918  4087  4120 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 12:37:52.918  4087  4120 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 12:37:52.918  4087  4120 I         : BTE_InitTraceLevels -- TRC_SMP
,08-03 12:37:52.919  4087  4120 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 12:37:52.919  4087  4120 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-03 12:37:53.051  4087  4120 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb396ed9d
,08-03 12:37:53.052  4087  4120 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb396ed9d 
,08-03 12:37:53.063  4087  4112 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-03 12:37:53.064  4087  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-03 12:37:53.066  4087  4112 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 12:37:53.070  4087  4112 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 12:37:53.073  4087  4112 D BluetoothAdapterProperties: Scan Mode:20
,08-03 12:37:53.075  4087  4112 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-03 12:37:53.075  4087  4112 D bt_hci  : do_postload posting postload work item
,08-03 12:37:53.075  4087  4117 I bt_hci  : event_postload
,08-03 12:37:53.075  4087  4117 I bt_vendor: sco_config_cb
,08-03 12:37:53.075  4087  4117 I bt_hci  : sco_config_callback postload finished.
08-03 12:37:53.078  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:53.079  4087  4112 D bt_bte_conf: Device ID record 1 : primary
08-03 12:37:53.079  4087  4112 D bt_bte_conf:   vendorId            = 000f
08-03 12:37:53.079  4087  4112 D bt_bte_conf:   vendorIdSource      = 0001
08-03 12:37:53.080  4087  4112 D bt_bte_conf:   product             = 1200
08-03 12:37:53.080  4087  4112 D bt_bte_conf:   version             = 1436
08-03 12:37:53.080  4087  4112 D bt_bte_conf:   clientExecutableURL = 
08-03 12:37:53.080  4087  4112 D bt_bte_conf:   serviceDescription  = 
08-03 12:37:53.080  4087  4112 D bt_bte_conf:   documentationURL    = 
08-03 12:37:53.081  4087  4112 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-03 12:37:53.081  4087  4109 D bt_stack_manager: event_start_up_stack finished
08-03 12:37:53.082  4087  4117 I bt_vendor: low_power_mode_cb
08-03 12:37:53.083  4087  4107 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-03 12:37:53.084  4087  4107 D BluetoothAdapterProperties: Setting state to 15
,08-03 12:37:53.084  4087  4107 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-03 12:37:53.086  4087  4107 I BluetoothAdapterState: Entering BleOnState
,08-03 12:37:53.092  4087  4107 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-03 12:37:53.092  4087  4107 D BluetoothAdapterProperties: Setting state to 11
,08-03 12:37:53.092  4087  4107 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-03 12:37:53.100  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:53.103  4087  4087 D HeadsetService: Received start request. Starting profile...
,08-03 12:37:53.104  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:53.107  4087  4087 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-03 12:37:53.107  4087  4087 D HeadsetStateMachine: make
,08-03 12:37:53.119  4087  4087 D HeadsetStateMachine: max_hf_connections = 1
,08-03 12:37:53.119  4087  4087 I bt_bluedroid: get_profile_interface handsfree
,08-03 12:37:53.120  4087  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-03 12:37:53.120  4087  4112 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-03 12:37:53.124  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:53.125  4087  4107 I BluetoothAdapterState: Entering PendingCommandState
,08-03 12:37:53.125  4087  4087 D A2dpService: Received start request. Starting profile...
08-03 12:37:53.125  4087  4087 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 12:37:53.126  4087  4087 I bt_bluedroid: get_profile_interface avrcp
,08-03 12:37:53.132  4087  4087 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-03 12:37:53.132  4087  4087 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 12:37:53.132  4087  4087 D A2dpStateMachine: make
,08-03 12:37:53.133  4087  4087 I bt_bluedroid: get_profile_interface a2dp
08-03 12:37:53.134  4087  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-03 12:37:53.136  4087  4129 D A2dpStateMachine: Enter Disconnected: -2
,08-03 12:37:53.139  4087  4087 I BluetoothHidServiceJni: classInitNative: succeeds
,08-03 12:37:53.139  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 12:37:53.140  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:53.140  4087  4087 D HidService: Received start request. Starting profile...
08-03 12:37:53.141  4087  4087 I bt_bluedroid: get_profile_interface hidhost
08-03 12:37:53.141  4087  4087 D HidService: setHidService(): set to: null
,08-03 12:37:53.141  4087  4112 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39503e5
08-03 12:37:53.141  4087  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-03 12:37:53.141  4087  4087 I BluetoothHealthServiceJni: classInitNative: succeeds
08-03 12:37:53.142  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:53.143  4087  4087 D HealthService: Received start request. Starting profile...
,08-03 12:37:53.144  4087  4087 I bt_bluedroid: get_profile_interface health
,08-03 12:37:53.145  4087  4087 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-03 12:37:53.146  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
08-03 12:37:53.146  4087  4087 D PanService: Received start request. Starting profile...
08-03 12:37:53.146  4087  4087 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 12:37:53.146  4087  4087 I bt_bluedroid: get_profile_interface pan
,08-03 12:37:53.147  4087  4112 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-03 12:37:53.149  4087  4087 V BluetoothAdapterState: isTurningOff()=false
,08-03 12:37:53.149  4087  4087 V BluetoothAdapterState: isTurningOn()=true
08-03 12:37:53.150  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:53.150  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 12:37:53.152  4087  4127 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-03 12:37:53.153  4087  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
,08-03 12:37:53.154  4087  4087 D BluetoothMapService: Received start request. Starting profile...
08-03 12:37:53.154  4087  4087 D BluetoothMapService: start()
,08-03 12:37:53.156  4087  4087 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-03 12:37:53.157  4087  4087 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-03 12:37:53.157  4087  4087 D BluetoothMapAppObserver: createReceiver()
,08-03 12:37:53.158  4087  4087 D BluetoothMapAppObserver: initObservers()
08-03 12:37:53.158  4087  4087 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-03 12:37:53.164  4087  4087 V BluetoothAdapterState: isTurningOff()=false
,08-03 12:37:53.164  4087  4087 V BluetoothAdapterState: isTurningOn()=true,
,08-03 12:37:53.164  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:53.164  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 12:37:53.164  4087  4087 V BluetoothAdapterState: isTurningOff()=false
08-03 12:37:53.164  4087  4087 V BluetoothAdapterState: isTurningOn()=true
,08-03 12:37:53.165  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:53.165  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:53.165  4087  4087 V BluetoothAdapterState: isTurningOff()=false
08-03 12:37:53.165  4087  4087 V BluetoothAdapterState: isTurningOn()=true
08-03 12:37:53.165  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:53.165  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:53.165  4087  4087 V BluetoothAdapterState: isTurningOff()=false
,08-03 12:37:53.166  4087  4087 V BluetoothAdapterState: isTurningOn()=true
08-03 12:37:53.166  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:53.166  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
08-03 12:37:53.166  4087  4087 V BluetoothAdapterState: isTurningOff()=false
08-03 12:37:53.166  4087  4087 V BluetoothAdapterState: isTurningOn()=true
08-03 12:37:53.166  4087  4087 V BluetoothAdapterState: isBleTurningOn()=false
08-03 12:37:53.166  4087  4087 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 12:37:53.167  4087  4107 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-03 12:37:53.167  4087  4107 D BluetoothAdapterProperties: ScanMode =  20
08-03 12:37:53.167  4087  4107 D BluetoothAdapterProperties: State =  11
08-03 12:37:53.168  4087  4112 D BluetoothAdapterProperties: Scan Mode:21
08-03 12:37:53.169  4087  4112 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-03 12:37:53.170  4087  4107 D BluetoothAdapterProperties: Setting state to 12
08-03 12:37:53.170  4087  4107 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 12:37:53.170  4087  4107 I BluetoothAdapterState: Entering OnState
08-03 12:37:53.170  3504  3900 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 12:37:53.173  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:53.173  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:53.173  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:53.173  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:53.173  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:53.173  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:53.173  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:53.173  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:37:53.173  3504  3515 D BluetoothPbap: onBluetoothStateChange: up=true
08-03 12:37:53.175  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:53.176  1360  1379 D BluetoothPan: onBluetoothStateChange on: true
08-03 12:37:53.177  1360  1383 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 12:37:53.177  3504  3504 D BluetoothA2dp: Proxy object connected
08-03 12:37:53.178  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 12:37:53.178  1360  1360 D PanProfile: Bluetooth service connected
,08-03 12:37:53.179  1360  1853 D BluetoothMap: onBluetoothStateChange: up=true
08-03 12:37:53.179  1360  1360 D BluetoothInputDevice: Proxy object connected
08-03 12:37:53.180  1360  1360 D HidProfile: Bluetooth service connected
08-03 12:37:53.181  1360  1383 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 12:37:53.182  1360  1360 D BluetoothMap: Proxy object connected
,08-03 12:37:53.182  1360  1360 D MapProfile: Bluetooth service connected
08-03 12:37:53.182  1360  1360 D BluetoothMap: getConnectedDevices()
08-03 12:37:53.183  1360  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:37:53.183  1748  2030 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 12:37:53.184  1360  1360 D BluetoothA2dp: Proxy object connected
08-03 12:37:53.184  3504  3900 D BluetoothPan: onBluetoothStateChange on: true
08-03 12:37:53.185  4087  4087 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-03 12:37:53.185  4087  4087 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-03 12:37:53.186  3504  3515 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:37:53.187  4087  4087 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 12:37:53.187  1360  1379 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 12:37:53.189  4087  4087 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 12:37:53.190   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 12:37:53.190  4087  4087 D ObexServerSockets: Succeed to create listening sockets 
08-03 12:37:53.190  4087  4087 D ObexServerSockets0: startAccept()
08-03 12:37:53.190   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:37:53.190  4087  4087 D ObexServerSockets0: prepareForNewConnect()
,08-03 12:37:53.190  3504  3514 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-03 12:37:53.192  4087  4087 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-03 12:37:53.193  4087  4087 D BluetoothSdpJni: SDP Create record success - handle: 0
08-03 12:37:53.193  3504  3515 D BluetoothMap: onBluetoothStateChange: up=true
,08-03 12:37:53.194  4087  4135 D ObexServerSockets0: Accepting socket connection...
08-03 12:37:53.194  4087  4134 D ObexServerSockets0: Accepting socket connection...
,08-03 12:37:53.196   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 12:37:53.191  3504  3504 D BluetoothPan: BluetoothPAN Proxy object connected
,08-03 12:37:53.197   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 12:37:53.198   873   873 D BluetoothA2dp: Proxy object connected
08-03 12:37:53.201  4087  4087 D BluetoothMapService: onReceive
08-03 12:37:53.201  4087  4087 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-03 12:37:53.201  4087  4087 D BluetoothMapService: STATE_ON
08-03 12:37:53.197  3504  3504 D PanProfile: Bluetooth service connected
08-03 12:37:53.202  3504  3504 D BluetoothInputDevice: Proxy object connected
08-03 12:37:53.202  3504  3504 D HidProfile: Bluetooth service connected
08-03 12:37:53.202   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-03 12:37:53.203  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:53.204  3504  3504 D BluetoothMap: Proxy object connected
08-03 12:37:53.204  3504  3504 D MapProfile: Bluetooth service connected
08-03 12:37:53.204  3504  3504 D BluetoothMap: getConnectedDevices()
,08-03 12:37:53.211  3504  3504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 12:37:53.216  3504  3504 D DockEventReceiver: finishStartingService: stopping service
,08-03 12:37:53.218  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 12:37:53.229  1360  1360 D BluetoothPbap: Proxy object connected
,08-03 12:37:53.229  1360  1360 D PbapServerProfile: Bluetooth service connected
08-03 12:37:53.229  3504  3504 D BluetoothPbap: Proxy object connected
08-03 12:37:53.229  3504  3504 D PbapServerProfile: Bluetooth service connected
08-03 12:37:53.230  4087  4087 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-03 12:37:53.230  4087  4087 D ObexServerSockets0: prepareForNewConnect()
,08-03 12:37:53.244  4087  4141 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 12:37:53.270  4087  4145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 12:37:53.277  4087  4145 I BtOppRfcommListener: Accept thread started.
,08-03 12:37:53.286  1748  1765 D BluetoothHeadset: Proxy object connected
,08-03 12:37:53.287  1360  1383 D BluetoothHeadset: Proxy object connected
,08-03 12:37:53.287  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-03 12:37:53.287   873   873 D BluetoothHeadset: Proxy object connected
08-03 12:37:53.288   873   873 D BluetoothHeadset: Proxy object connected
,08-03 12:37:53.288   873   873 D BluetoothHeadset: Proxy object connected
08-03 12:37:53.288  3504  3515 D BluetoothHeadset: Proxy object connected
,08-03 12:37:53.289  3504  3515 D BluetoothHeadset: Proxy object connected
08-03 12:37:53.290  3504  3504 D HeadsetProfile: Bluetooth service connected
08-03 12:37:53.290   873   890 D BluetoothHeadset: Proxy object connected
,08-03 12:37:53.291   873   890 D BluetoothHeadset: Proxy object connected
08-03 12:37:53.293  3504  3504 D HeadsetProfile: Bluetooth service connected
,08-03 12:37:53.297   873   890 D BluetoothHeadset: Proxy object connected
,08-03 12:37:53.766  3396  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:53.766  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:53.766  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:53.766  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:37:53.766  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:53.766  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:53.766  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:53.766  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:53.773  3396  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:53.776  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:37:53.777  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7fdce51 added. We now have 8 listener(s)
,08-03 12:37:53.777  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 12:37:53.783   873  1767 D WifiService: setWifiEnabled: false pid=3396, uid=10000
,08-03 12:37:53.783   873  1767 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 12:37:53.795  3396  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:53.798   873  1754 D WifiService: setWifiEnabled: true pid=3396, uid=10000
,08-03 12:37:53.798   873  1754 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 12:37:53.813   873  1312 D WifiConfigStore: Loading config and enabling all networks 
,08-03 12:37:53.831  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:53.831  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:53.831  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:53.831  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:53.831  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:53.831  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:53.831  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:53.831  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:53.839  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:53.847   873  1312 D WifiConfigStore: loaded 0 passpoint configs
,08-03 12:37:53.848   873  1312 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-03 12:37:53.848   873  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-03 12:37:53.849   873  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-03 12:37:53.850   873  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 12:37:53.850   873  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-03 12:37:53.850   873  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-03 12:37:53.851   873  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-03 12:37:53.860   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-03 12:37:53.860   873  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-03 12:37:53.861   371   871 D CommandListener: Setting iface cfg
,08-03 12:37:53.912   873  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '61 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 61 Failed to set address (No such device)'
,08-03 12:37:53.912   873  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-03 12:37:53.914   873  1312 E native  : do suspend true
,08-03 12:37:53.940   873  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-03 12:37:53.941   873  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-03 12:37:53.942   873  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 12:37:54.824  3396  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:54.824  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:54.824  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:54.824  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:54.824  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:54.824  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:54.824  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:54.824  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:54.831  3396  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:54.844  3396  3442 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-03 12:37:54.847  3396  3442 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-03 12:37:54.851  3396  3442 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2d2cf86 Bundle[{}]
,08-03 12:37:54.852  3396  3442 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 12:37:54.852  3396  3442 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-03 12:37:54.853  3396  3442 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-03 12:37:54.853  3396  3442 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-03 12:37:54.854  3396  3442 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-03 12:37:54.855  3396  3442 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-03 12:37:54.861  3396  3442 I System.out: Running OutgoingSocketThread
,08-03 12:37:54.864  3396  4152 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 382)
,08-03 12:37:54.866  3396  4152 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46157
,08-03 12:37:54.866  3396  4152 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-03 12:37:55.268   873  1745 I ActivityManager: Killing 3738:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,08-03 12:37:55.361   873  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 12:37:55.484   873  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=1.50 rxSuccessRate=1.00 delta 1000 -> 1000
,08-03 12:37:55.487   873  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-03 12:37:55.487   873  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 12:37:55.507   873  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-03 12:37:55.558   873  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-03 12:37:55.560  1477  1477 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-03 12:37:55.864  3396  3442 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 383)
,08-03 12:37:55.864  3396  3442 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 383)
,08-03 12:37:55.877  3396  3442 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 388)
,08-03 12:37:55.880  3396  3442 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-03 12:37:55.882  3396  3442 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 389)
,08-03 12:37:55.889  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:37:55.889  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f93b6b6 added. We now have 2 listener(s)
,08-03 12:37:55.895  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 12:37:55.895  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:37:55.896  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:37:55.896  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 12:37:55.896  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a546fb7 added. We now have 9 listener(s)
08-03 12:37:55.897  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:37:55.898  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 12:37:55.904  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 12:37:55.912  3396  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:37:55.912  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:55.912  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:55.912  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:55.912  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:55.912  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:55.912  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:55.912  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:55.916  3396  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:55.916  3396  3442 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 12:37:55.916  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 12:37:55.916  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7ffe8d added. We now have 3 listener(s)
08-03 12:37:55.918  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 12:37:55.918  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:37:55.919  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 12:37:55.919  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:37:55.919  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31c8842 added. We now have 10 listener(s)
08-03 12:37:55.919  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:37:55.919  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:55.919  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:55.919  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:55.920  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 12:37:55.920  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:55.920  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:55.920  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:37:55.920  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:37:55.920  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f93b6b6 removed from the list
08-03 12:37:55.920  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:55.920  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a546fb7 removed from the list
,08-03 12:37:55.922  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:55.922  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:55.923  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:55.923  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:55.923  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:55.926  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 12:37:55.926  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:55.926  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:55.926  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a546fb7 not in the list
08-03 12:37:55.927  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:55.927  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:37:55.929  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:55.930  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:55.930  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 12:37:55.930  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31c8842 removed from the list
08-03 12:37:55.930  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:55.931  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:55.931  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:55.931  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 12:37:55.932  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7ffe8d removed from the list
08-03 12:37:55.934  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 12:37:55.934  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b65053 added. We now have 2 listener(s)
,08-03 12:37:55.939  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 12:37:55.940  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:37:55.940  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:37:55.941  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 12:37:55.941  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24bad90 added. We now have 9 listener(s)
08-03 12:37:55.941  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:37:55.943  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 12:37:55.947  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 12:37:55.952  3396  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:37:55.952  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:55.952  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:55.952  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:55.952  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:55.952  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:55.952  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:55.952  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:55.954  3396  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:55.954  3396  3442 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:37:55.955  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:37:55.955  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ee68e added. We now have 3 listener(s)
,08-03 12:37:55.957  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:55.957  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 12:37:55.958  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:37:55.958  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 12:37:55.958  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:37:55.958  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b9eaf added. We now have 10 listener(s)
08-03 12:37:55.958  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:37:55.958  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:37:55.958  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-03 12:37:55.959  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 12:37:55.959  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:37:55.959  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 12:37:55.962  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:55.963  3396  3442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 12:37:55.963  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 12:37:55.969  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 12:37:55.973  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-03 12:37:55.973  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 12:37:55.976  1477  1477 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 12:37:55.982  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-03 12:37:55.985  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-03 12:37:55.986  3396  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 12:37:55.987  3396  3442 D BluetoothAdapter: STATE_ON
,08-03 12:37:55.993  4087  4137 D BtGatt.GattService: registerClient() - UUID=e9817075-5531-4ad0-83ad-d9b475bc5176
,08-03 12:37:55.995  4087  4112 D BtGatt.GattService: onClientRegistered() - UUID=e9817075-5531-4ad0-83ad-d9b475bc5176, clientIf=5
,08-03 12:37:55.997  3396  3407 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-03 12:37:55.999  4087  4101 D BtGatt.GattService: start scan with filters
,08-03 12:37:56.002  4087  4116 D BtGatt.ScanManager: handling starting scan
,08-03 12:37:56.002  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 12:37:56.003  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-03 12:37:56.004  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 12:37:56.004  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-03 12:37:56.004  4087  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77151ba
08-03 12:37:56.008  4087  4112 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-03 12:37:56.008  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.009  4087  4116 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 12:37:56.011  1477  1477 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 12:37:56.012  1477  1477 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-03 12:37:56.015  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 12:37:56.015  4087  4112 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 12:37:56.015  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.016  3396  3396 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 12:37:56.016   873  1312 D WifiConfigStore: Retrieve network priorities after PNO.
08-03 12:37:56.016  4087  4116 D BtGatt.ScanManager: Starting BLE batch scan
08-03 12:37:56.016  4087  4116 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 12:37:56.016  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-03 12:37:56.023  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 12:37:56.025   873  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-03 12:37:56.025   873  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 12:37:56.025   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-03 12:37:56.029  3396  3442 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-03 12:37:56.029  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:56.029  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-03 12:37:56.029  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.029  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-03 12:37:56.029  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 12:37:56.029  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 12:37:56.029  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 12:37:56.030  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 12:37:56.030  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 12:37:56.030  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 12:37:56.031  3396  3442 D BluetoothAdapter: STATE_ON
,08-03 12:37:56.032  4087  4137 D BtGatt.GattService: stopScan() - queue size =1
08-03 12:37:56.032  4087  4101 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 12:37:56.032  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:37:56.033  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 12:37:56.033  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 12:37:56.033  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 12:37:56.033  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
,08-03 12:37:56.034  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 12:37:56.035  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 12:37:56.035  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 12:37:56.035  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-03 12:37:56.035  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 12:37:56.037  3396  3396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 12:37:56.037  3396  3396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 12:37:56.037  3396  3396 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 12:37:56.037  4087  4112 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 12:37:56.037  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 12:37:56.039  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 12:37:56.039  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:56.039  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:37:56.039  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:56.040  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.040  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:37:56.040  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:37:56.040  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b65053 removed from the list
08-03 12:37:56.040  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 12:37:56.040  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24bad90 removed from the list
08-03 12:37:56.040  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:56.040  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:56.040  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.040  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:56.041  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:56.041  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:56.041  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:56.041  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24bad90 not in the list
08-03 12:37:56.042  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.042  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:56.043  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:56.043  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:56.043  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:56.043  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94b9eaf removed from the list
08-03 12:37:56.043  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:56.043  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.043  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:37:56.043  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 12:37:56.043  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ee68e removed from the list
08-03 12:37:56.044  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:37:56.044  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23d76cb added. We now have 2 listener(s)
08-03 12:37:56.046  4087  4112 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 12:37:56.046   873  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 12:37:56.046  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.048  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 12:37:56.048  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:37:56.049  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:37:56.049  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:37:56.049  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5f9ea8 added. We now have 9 listener(s)
,08-03 12:37:56.049  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:37:56.049  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 12:37:56.051  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 12:37:56.053  4087  4112 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-03 12:37:56.053  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.054   371   871 D CommandListener: Setting iface cfg
08-03 12:37:56.054  4087  4116 D BtGatt.ScanManager: stopping BLe Batch
08-03 12:37:56.055  3396  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:37:56.055  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:56.055  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:56.055  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:56.055  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:56.055  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:56.055  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:56.055  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:37:56.056   873  1312 D WifiStateMachine: Start Dhcp Watchdog 2
,08-03 12:37:56.057  3396  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:37:56.057  3396  3442 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 12:37:56.057  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:37:56.057  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d53966 added. We now have 3 listener(s)
,08-03 12:37:56.058  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:56.059  4087  4112 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 12:37:56.059  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 12:37:56.059  4087  4116 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-03 12:37:56.060  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:56.060  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 12:37:56.060  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:37:56.060  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:37:56.060  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:37:56.061  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2ab4a7 added. We now have 10 listener(s)
08-03 12:37:56.061  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 12:37:56.061  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:37:56.061  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:37:56.062  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 12:37:56.062  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 12:37:56.062  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:37:56.062  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 12:37:56.062   873  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
08-03 12:37:56.064  3396  3442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 12:37:56.064  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 12:37:56.065  4087  4112 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-03 12:37:56.065  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.068  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 12:37:56.068  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 12:37:56.068  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 12:37:56.071  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-03 12:37:56.071  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 12:37:56.071  3396  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 12:37:56.071  3396  3442 D BluetoothAdapter: STATE_ON
,08-03 12:37:56.073  4087  4137 D BtGatt.GattService: registerClient() - UUID=b065142a-037b-474d-b90e-379c2081895b
,08-03 12:37:56.073  4087  4112 D BtGatt.GattService: onClientRegistered() - UUID=b065142a-037b-474d-b90e-379c2081895b, clientIf=5
08-03 12:37:56.073  3396  3406 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 12:37:56.074  4087  4101 D BtGatt.GattService: start scan with filters
,08-03 12:37:56.076  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 12:37:56.076  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 12:37:56.076  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 12:37:56.076  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-03 12:37:56.076   873  4155 D DhcpClient: Receive thread started
08-03 12:37:56.076  4087  4116 D BtGatt.ScanManager: handling starting scan
08-03 12:37:56.078  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 12:37:56.079  3396  3396 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 12:37:56.079  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-03 12:37:56.080  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 12:37:56.082  4087  4112 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-03 12:37:56.082  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.082  4087  4116 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-03 12:37:56.083  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:37:56.083  3396  3442 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-03 12:37:56.083  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:56.084  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:56.084  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 12:37:56.084  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:56.084  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.084  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 12:37:56.084  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:37:56.084  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23d76cb removed from the list
08-03 12:37:56.084  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 12:37:56.084  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5f9ea8 removed from the list
08-03 12:37:56.084  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:56.084  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:37:56.085  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.085  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-03 12:37:56.085  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.085  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:37:56.086  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:56.086  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 12:37:56.086  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:56.086  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5f9ea8 not in the list
08-03 12:37:56.086  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 12:37:56.086  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 12:37:56.086  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 12:37:56.086  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 12:37:56.086  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-03 12:37:56.087  3396  3442 D BluetoothAdapter: STATE_ON
08-03 12:37:56.087  4087  4112 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 12:37:56.087  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.087  4087  4116 D BtGatt.ScanManager: Starting BLE batch scan
08-03 12:37:56.087  4087  4101 D BtGatt.GattService: stopScan() - queue size =1
08-03 12:37:56.088  4087  4116 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 12:37:56.088  4087  4099 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-03 12:37:56.088  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:37:56.089  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 12:37:56.089  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 12:37:56.089  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 12:37:56.089  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 12:37:56.090  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 12:37:56.090  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-03 12:37:56.090  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 12:37:56.090  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 12:37:56.090  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:56.091  3396  3396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 12:37:56.091  3396  3396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 12:37:56.091  3396  3396 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 12:37:56.091  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:56.091  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:56.091  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:56.092  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2ab4a7 removed from the list
08-03 12:37:56.092  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 12:37:56.092  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.092  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:56.092  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:37:56.092  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d53966 removed from the list
08-03 12:37:56.093  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:37:56.093  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3f443 added. We now have 2 listener(s)
,08-03 12:37:56.094  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 12:37:56.094  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:37:56.094  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:37:56.095  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:37:56.095  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dad9ac0 added. We now have 9 listener(s)
08-03 12:37:56.095  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:37:56.095  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 12:37:56.097  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 12:37:56.097  4087  4112 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 12:37:56.097  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 12:37:56.100  3396  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:37:56.100  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:56.100  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:56.100  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:56.100  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:56.100  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:56.100  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:56.100  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:56.102  3396  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:56.102  3396  3442 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:37:56.102  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:37:56.102  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca80f3e added. We now have 3 listener(s)
,08-03 12:37:56.102  4087  4112 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 12:37:56.103  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.103  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:56.104  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 12:37:56.104  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:37:56.104  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:37:56.104  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:56.104  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:37:56.104  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27919f added. We now have 10 listener(s)
08-03 12:37:56.104  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:37:56.104  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:37:56.104  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 12:37:56.105  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 12:37:56.105  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:37:56.111  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 12:37:56.111  4087  4112 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 12:37:56.111  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.111  4087  4116 D BtGatt.ScanManager: stopping BLe Batch
,08-03 12:37:56.116  4087  4112 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 12:37:56.117  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 12:37:56.117  4087  4116 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-03 12:37:56.117  3396  3442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-03 12:37:56.117  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 12:37:56.122  4087  4112 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-03 12:37:56.122  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.123  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 12:37:56.123  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-03 12:37:56.123  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 12:37:56.127  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-03 12:37:56.127  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-03 12:37:56.127  3396  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 12:37:56.127  3396  3442 D BluetoothAdapter: STATE_ON
,08-03 12:37:56.129  4087  4101 D BtGatt.GattService: registerClient() - UUID=f8c8822d-8632-4b05-b77e-3e5535820a9c
08-03 12:37:56.130  4087  4112 D BtGatt.GattService: onClientRegistered() - UUID=f8c8822d-8632-4b05-b77e-3e5535820a9c, clientIf=5
,08-03 12:37:56.130  3396  3406 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 12:37:56.131  4087  4136 D BtGatt.GattService: start scan with filters
,08-03 12:37:56.133  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-03 12:37:56.133  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 12:37:56.133  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 12:37:56.133  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 12:37:56.133  4087  4116 D BtGatt.ScanManager: handling starting scan
,08-03 12:37:56.137  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 12:37:56.137  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 12:37:56.137  3396  3396 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 12:37:56.139  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 12:37:56.142  4087  4112 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-03 12:37:56.143  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.143  4087  4116 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 12:37:56.144  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:56.144  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:56.144  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 12:37:56.144  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:56.144  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.144  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 12:37:56.144  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:37:56.144  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3f443 removed from the list
08-03 12:37:56.145  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 12:37:56.145  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dad9ac0 removed from the list
08-03 12:37:56.145  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:56.145  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:37:56.145  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.145  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-03 12:37:56.145  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.145  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 12:37:56.147  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:56.147  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:56.147  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:56.147  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dad9ac0 not in the list
08-03 12:37:56.147  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-03 12:37:56.147  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 12:37:56.147  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 12:37:56.147  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 12:37:56.147  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 12:37:56.148  3396  3442 D BluetoothAdapter: STATE_ON
08-03 12:37:56.148  4087  4126 D BtGatt.GattService: stopScan() - queue size =1
08-03 12:37:56.149  4087  4101 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-03 12:37:56.149  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:37:56.149  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 12:37:56.150  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-03 12:37:56.150  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 12:37:56.150  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 12:37:56.151  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 12:37:56.151  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 12:37:56.151  3396  3442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 12:37:56.151  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-03 12:37:56.152  4087  4112 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 12:37:56.152  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.152  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:56.152  4087  4116 D BtGatt.ScanManager: Starting BLE batch scan
08-03 12:37:56.152  4087  4116 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 12:37:56.153  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:56.153  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:56.153  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:56.153  3396  3396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 12:37:56.153  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27919f removed from the list
08-03 12:37:56.153  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:56.153  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.153  3396  3396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 12:37:56.153  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:56.153  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:37:56.153  3396  3396 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 12:37:56.154  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca80f3e removed from the list
,08-03 12:37:56.154  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:37:56.154  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fda8bb added. We now have 2 listener(s)
,08-03 12:37:56.156  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 12:37:56.156  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:37:56.157  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:37:56.157  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 12:37:56.157  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20c01d8 added. We now have 9 listener(s)
08-03 12:37:56.157  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:37:56.157  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 12:37:56.159  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 12:37:56.163  3396  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:37:56.163  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:56.163  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:56.163  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:56.163  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:56.163  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:37:56.163  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:37:56.163  3396  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:37:56.164   873  1312 E native  : do suspend false
,08-03 12:37:56.165  3396  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:37:56.165  3396  3442 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 12:37:56.166  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 12:37:56.166  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e94c816 added. We now have 3 listener(s)
,08-03 12:37:56.167  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:37:56.168  4087  4112 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-03 12:37:56.168  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 12:37:56.168  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 12:37:56.168  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:37:56.169  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:37:56.169  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:37:56.169  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:37:56.169  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1541597 added. We now have 10 listener(s)
08-03 12:37:56.169  3396  3442 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 12:37:56.169  3396  3442 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:37:56.169  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:56.169  3396  3442 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 12:37:56.169  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:56.170  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.170  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:37:56.170  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:37:56.170  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fda8bb removed from the list
08-03 12:37:56.170  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 12:37:56.170  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20c01d8 removed from the list
08-03 12:37:56.170  3396  3442 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:37:56.170  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:56.173  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.173  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:56.174  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 12:37:56.174  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:37:56.174  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:56.174  3396  3442 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20c01d8 not in the list
08-03 12:37:56.174  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.174  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:37:56.175  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 12:37:56.175  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:37:56.175  3396  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:37:56.175  3396  3442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1541597 removed from the list
08-03 12:37:56.175  3396  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:37:56.175  3396  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:37:56.175  4087  4112 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 12:37:56.176  3396  3442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:37:56.176  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.176  3396  3442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 12:37:56.176  3396  3442 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e94c816 removed from the list
,08-03 12:37:56.177  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-03 12:37:56.177   873  3569 D DhcpClient: Broadcasting DHCPDISCOVER
08-03 12:37:56.178  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-03 12:37:56.178  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-03 12:37:56.178  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:37:56.178  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-03 12:37:56.178  3396  3442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 12:37:56.184  4087  4112 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 12:37:56.184  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 12:37:56.184  4087  4116 D BtGatt.ScanManager: stopping BLe Batch
08-03 12:37:56.184  3396  4156 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 396, name: My test thread name)
08-03 12:37:56.185  3396  4156 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 396, thread name: My test thread name)
08-03 12:37:56.185  3396  4156 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 396, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-03 12:37:56.187  3396  4157 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 398, name: My test thread name)
,08-03 12:37:56.187  3396  4157 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 398, thread name: My test thread name)
08-03 12:37:56.187  3396  4157 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 398, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-03 12:37:56.189  3396  3442 E com.test.thalitest.ThaliTestRunner: DiscoveryManager1 isRunning should return true
08-03 12:37:56.189  3396  3442 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
08-03 12:37:56.189  3396  3442 E com.test.thalitest.ThaliTestRunner:      but: was <false>
08-03 12:37:56.189  3396  3442 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-03 12:37:56.189  3396  3442 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 79
08-03 12:37:56.189  3396  3442 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  1
08-03 12:37:56.189  3396  3442 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-03 12:37:56.189  3396  3442 D com.test.thalitest.ThaliTestRunner: Total duration: 23856 ms
,08-03 12:37:56.190  4087  4112 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 12:37:56.190  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.190  4087  4116 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-03 12:37:56.191  3396  3442 I jxcore-log: Total number of executed tests:  80
08-03 12:37:56.191  3396  3442 I jxcore-log: 
08-03 12:37:56.191  3396  3442 I jxcore-log: Number of passed tests:  79
08-03 12:37:56.191  3396  3442 I jxcore-log: 
08-03 12:37:56.191  3396  3442 I jxcore-log: Number of failed tests:  1
08-03 12:37:56.191  3396  3442 I jxcore-log: 
,08-03 12:37:56.192  3396  3442 I jxcore-log: Number of ignored tests:  0
08-03 12:37:56.192  3396  3442 I jxcore-log: 
08-03 12:37:56.192  3396  3442 I jxcore-log: Total duration:  23856
08-03 12:37:56.192  3396  3442 I jxcore-log: 
08-03 12:37:56.192  3396  3442 I jxcore-log: Failed to execute UT.
08-03 12:37:56.192  3396  3442 I jxcore-log: 
08-03 12:37:56.192  3396  3442 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-03 12:37:56.192  3396  3442 I jxcore-log: 
,08-03 12:37:56.196  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.196  3396  3442 I jxcore-log: 
08-03 12:37:56.196  4087  4112 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 12:37:56.196  4087  4112 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 12:37:56.199  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.199  3396  3442 I jxcore-log: 
08-03 12:37:56.200  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.200  3396  3442 I jxcore-log: 
08-03 12:37:56.201   873  4155 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172780, domain null
08-03 12:37:56.202   873  3569 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172780 seconds
08-03 12:37:56.202   873  3569 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
08-03 12:37:56.203  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.203  3396  3442 I jxcore-log: 
08-03 12:37:56.204  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 12:37:56.204  3396  3442 I jxcore-log: 
08-03 12:37:56.205  3396  3396 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-03 12:37:56.206  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 12:37:56.206  3396  3442 I jxcore-log: 
08-03 12:37:56.209  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.209  3396  3442 I jxcore-log: 
08-03 12:37:56.211  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.211  3396  3442 I jxcore-log: 
08-03 12:37:56.212  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 12:37:56.212  3396  3442 I jxcore-log: 
08-03 12:37:56.213  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.213  3396  3442 I jxcore-log: 
08-03 12:37:56.214   873  4155 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
08-03 12:37:56.214   873  3569 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-03 12:37:56.216   371   871 D CommandListener: Setting iface cfg
08-03 12:37:56.216  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.216  3396  3442 I jxcore-log: 
08-03 12:37:56.220  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:37:56.220  3396  3442 I jxcore-log: 
08-03 12:37:56.220   873  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-03 12:37:56.220   873  3569 D DhcpClient: Scheduling renewal in 86399s
08-03 12:37:56.221   873  1312 E native  : do suspend true
08-03 12:37:56.221  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:37:56.221  3396  3442 I jxcore-log: 
08-03 12:37:56.222  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 12:37:56.222  3396  3442 I jxcore-log: 
08-03 12:37:56.223  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 12:37:56.223  3396  3442 I jxcore-log: 
08-03 12:37:56.224  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:37:56.224  3396  3442 I jxcore-log: 
08-03 12:37:56.224  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:37:56.224  3396  3442 I jxcore-log: 
08-03 12:37:56.225  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.225  3396  3442 I jxcore-log: 
08-03 12:37:56.226  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.226  3396  3442 I jxcore-log: 
08-03 12:37:56.227  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.227  3396  3442 I jxcore-log: 
08-03 12:37:56.227  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.227  3396  3442 I jxcore-log: 
08-03 12:37:56.228  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.228  3396  3442 I jxcore-log: 
08-03 12:37:56.229  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.229  3396  3442 I jxcore-log: 
08-03 12:37:56.229  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.229  3396  3442 I jxcore-log: 
08-03 12:37:56.230  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.230  3396  3442 I jxcore-log: 
08-03 12:37:56.231  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.231  3396  3442 I jxcore-log: 
08-03 12:37:56.232  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 12:37:56.232  3396  3442 I jxcore-log: 
08-03 12:37:56.233  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:37:56.233  3396  3442 I jxcore-log: 
08-03 12:37:56.234  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:37:56.234  3396  3442 I jxcore-log: 
08-03 12:37:56.234   873  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-03 12:37:56.234  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:37:56.234  3396  3442 I jxcore-log: 
08-03 12:37:56.235  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:37:56.235  3396  3442 I jxcore-log: 
08-03 12:37:56.236   873  1312 D WifiConfigStore: No blacklist allowed without epno enabled
08-03 12:37:56.236  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:37:56.236  3396  3442 I jxcore-log: 
08-03 12:37:56.236   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-03 12:37:56.236  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:37:56.236  3396  3442 I jxcore-log: 
08-03 12:37:56.237  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:37:56.237  3396  3442 I jxcore-log: 
08-03 12:37:56.237   873  1314 D ConnectivityService: Adding iface wlan0 to network 101
08-03 12:37:56.243   873  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-03 12:37:56.279   873  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-03 12:37:56.280   873  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-03 12:37:56.280   873  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-03 12:37:56.282   873  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-03 12:37:56.284   873  1314 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-03 12:37:56.290   873  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-03 12:37:56.294   873  1314 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-03 12:37:56.294   873  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-03 12:37:56.294   873  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-03 12:37:56.294   873  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-03 12:37:56.294   873  1314 D ConnectivityService:    accepting network in place of null
,08-03 12:37:56.295   873  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 12:37:56.295   873  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 12:37:56.304   873  4154 D NetlinkSocketObserver: NeighborEvent{elapsedMs=439329, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-03 12:37:56.319   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 12:37:56.342   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 12:37:56.344   873  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-03 12:37:56.344   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 12:37:56.346   873  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-03 12:37:56.347   873   890 D Tethering: MasterInitialState.processMessage what=3
08-03 12:37:56.355  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:37:56.355  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:37:56.355  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 12:37:56.355  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:37:56.355  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:37:56.355  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 12:37:56.355  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 12:37:56.355  3396  3396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 12:37:56.357  3396  3396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 12:37:56.358  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 12:37:56.358  3396  3442 I jxcore-log: 
,08-03 12:37:56.372   873  4153 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,08-03 12:37:56.382  1875  1875 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-03 12:37:56.388  1875  1875 D SystemUpdateService: onCreate
,08-03 12:37:56.394  1875  1875 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 12:37:56.426  1875  4168 I SystemUpdateService: active receiver: enabled
,08-03 12:37:56.430   873  1745 I ActivityManager: Start proc 4169:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-03 12:37:56.489   873  4153 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 10:37:56 GMT], X-Android-Received-Millis=[1470220676489], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470220676439]}
,08-03 12:37:56.490   873  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-03 12:37:56.490   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-03 12:37:56.491   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-03 12:37:56.494   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-03 12:37:56.498  1875  4168 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 12:37:56.513  4169  4169 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-03 12:37:56.519  1875  1875 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-03 12:37:56.537  3396  3396 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 12:37:56.538  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 12:37:56.538  3396  3442 I jxcore-log: 
,08-03 12:37:56.545  1526  1526 I ConfigService: onCreate
,08-03 12:37:56.561  1875  4183 I ConfigFetchService: running network task: configservice_periodic
,08-03 12:37:56.569  1875  1875 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-03 12:37:56.588  1875  4183 E WakeLock: callingPackage is not supposed to be empty for wakelock Config Service fetch!
08-03 12:37:56.588  1875  4183 E WakeLock: java.lang.IllegalArgumentException
08-03 12:37:56.588  1875  4183 E WakeLock: 	at com.google.android.gms.stats.d.<init>(SourceFile:135)
08-03 12:37:56.588  1875  4183 E WakeLock: 	at com.google.android.gms.config.ConfigFetchService.a(SourceFile:341)
08-03 12:37:56.588  1875  4183 E WakeLock: 	at com.google.android.gms.config.ConfigFetchService.a(SourceFile:159)
08-03 12:37:56.588  1875  4183 E WakeLock: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-03 12:37:56.591  3396  3396 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 12:37:56.592  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 12:37:56.592  3396  3442 I jxcore-log: 
,08-03 12:37:56.594  1875  4183 I ConfigFetchService: launchTask
08-03 12:37:56.596  1875  1875 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-03 12:37:56.597  1875  1875 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 12:37:56.600  1875  4168 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-03 12:37:56.611  1875  4168 I SystemUpdateService: now status is 0 (complete)
08-03 12:37:56.611  1875  4168 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-03 12:37:56.611  1875  4168 I SystemUpdateService: file has been verified
,08-03 12:37:56.611  1875  4168 I SystemUpdateService: OTA package size = 12249756
,08-03 12:37:56.571  1875  3617 I iu.UploadsManager: num queued entries: 0
,08-03 12:37:56.631  1875  3617 I iu.UploadsManager: num updated entries: 0
,08-03 12:37:56.632  1875  3617 I iu.SyncManager: NEXT; no task
,08-03 12:37:56.637   873   884 I ActivityManager: Start proc 4189:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-03 12:37:56.642  1875  1875 I ConfigFetchService: service connected
08-03 12:37:56.647  1875  4185 I MDM     : [222] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-03 12:37:56.647  1875  4185 W BaseAppContext: Using Auth Proxy for data requests.
08-03 12:37:56.649  1875  1875 D ConfigFetchService: ConfigApi connection successful.
08-03 12:37:56.650  1875  4185 V GoogleAuthProtoRequest: [222] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 12:37:56.654  3396  3396 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 12:37:56.655  3396  3442 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 12:37:56.655  3396  3442 I jxcore-log: 
,08-03 12:37:56.673  1875  4168 I SystemUpdateService: showing system update notification
,08-03 12:37:56.688  1875  4188 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UFWuReLIDWTAAEOqctNwBFsOR0414GCw_qG7mg4n60FuS0Y1cKBjLlUKDLjThWBH6KhjJPATjYMn_sjeVqe1K-SXDKQ__YFxFSHp_VskzQ4BW7J1U3pih7J5rQxb9VSmpKwxqIZXN-a2o2BGnIm2o8T7thjv3tHo-XIbKcemdf8NZnUJMuVj1dO7FA4vFtk2oLJzvx
,08-03 12:37:56.699  4041  4075 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-03 12:37:56.718  4189  4189 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-03 12:37:56.744  4189  4189 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 12:37:56.767  4189  4189 D SprintDMHelper: simOperator: 
,08-03 12:37:56.767  4189  4189 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 12:37:56.790   873  1764 I ActivityManager: Start proc 4210:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-03 12:37:56.797  4169  4200 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-03 12:37:56.901  4163  4163 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-03 12:37:56.902  1526  3645 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-03 12:37:56.902  1526  3645 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-03 12:37:56.902  1526  3645 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 12:37:56.902  1526  3645 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 12:37:56.906  4163  4163 D AndroidRuntime: CheckJNI is OFF
,08-03 12:37:56.925  4028  4103 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-03 12:37:56.951  4163  4163 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-03 12:37:56.998  4163  4163 I Radio-JNI: register_android_hardware_Radio DONE
,08-03 12:37:57.015  1875  1875 D SystemUpdateService: onDestroy
,08-03 12:37:57.020  4163  4163 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-03 12:37:57.028   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-03 12:37:57.029   873   886 I ActivityManager: Killing 3396:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-03 12:37:57.051  4169  4200 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-03 12:37:57.096  4169  4200 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-03 12:37:57.106   873  1764 D GraphicsStats: Buffer count: 2
,08-03 12:37:57.106   873  1764 I WindowState: WIN DEATH: Window{55258fa u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-03 12:37:57.108   873  1313 D WifiService: Client connection lost with reason: 4
,08-03 12:37:57.142   873   896 W PackageSettings: Skipping PackageSetting{15c41df com.example.hello/10273} due to missing metadata
,08-03 12:37:57.172   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-03 12:37:57.172   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-03 12:37:57.173   873   896 I art     : Starting a blocking GC Explicit
,08-03 12:37:57.175   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-03 12:37:57.175   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-03 12:37:57.175   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 12:37:57.175   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-03 12:37:57.175   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 12:37:57.175   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-03 12:37:57.177   873   886 I ActivityManager:   Force finishing activity ActivityRecord{e013ca7 u0 com.test.thalitest/.MainActivity t2}
,08-03 12:37:57.200   873  1685 W ActivityManager: Spurious death for ProcessRecord{3484b6b 0:com.test.thalitest/u0a0}, curProc for 3396: null
,08-03 12:37:57.214  1875  4188 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-03 12:37:57.226   873  1745 I ActivityManager: Killing 3845:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,08-03 12:37:57.228   873   896 I art     : Explicit concurrent mark sweep GC freed 22104(1553KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.045ms total 53.045ms
,08-03 12:37:57.263   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-03 12:37:57.266  4163  4163 I art     : System.exit called, status: 0
,08-03 12:37:57.266  4163  4163 I AndroidRuntime: VM exiting with result code 0.
,08-03 12:37:57.319   873  1685 I ActivityManager: Start proc 4249:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-03 12:37:57.345   873  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-03 12:37:57.358   873   896 I ActivityManager: Start proc 4263:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-03 12:37:57.370   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-03 12:37:57.391   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-03 12:37:57.398  1841  2028 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-03 12:37:57.400  4087  4087 D BluetoothMapAppObserver: onReceive
08-03 12:37:57.400  4087  4087 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-03 12:37:57.404   873  1303 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-03 12:37:57.406   873  1310 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-03 12:37:57.409   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-03 12:37:57.410   873   885 E PackageManager: Failed to write settings, restoring backup
08-03 12:37:57.410   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-03 12:37:57.410   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-03 12:37:57.410   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-03 12:37:57.410   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-03 12:37:57.410   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-03 12:37:57.410   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 12:37:57.410   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-03 12:37:57.410   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 12:37:57.426   873  1392 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3396 uid 10000
,08-03 12:37:57.439   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-03 12:37:57.439   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-03 12:37:57.439   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 12:37:57.439   873   886 E DropBoxManagerService: 	... 13 more
,08-03 12:37:57.448  1748  1748 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-03 12:37:57.450  1660  1660 I Keyboard.Facilitator: resetDictionaries() : en_US
08-03 12:37:57.482  1660  1660 I Keyboard.Facilitator: onFinishInput()
,08-03 12:37:57.493  1875  4185 E MDM     : [222] SitrepService.a: Error sending sitrep.
08-03 12:37:57.494   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-03 12:37:57.526  1766  1846 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-03 12:37:57.538   873  1685 I ActivityManager: Start proc 4279:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-03 12:37:57.539  1766  1846 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-03 12:37:57.539  1766  1846 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1766
08-03 12:37:57.539  1766  1846 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 12:37:57.539  1766  1846 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-03 12:37:57.539  1766  1846 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-03 12:37:57.539  1766  1846 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-03 12:37:57.539  1766  1846 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-03 12:37:57.539  1766  1846 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-03 12:37:57.539  1766  1846 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-03 12:37:57.539  1766  1846 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-03 12:37:57.539  1766  1846 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 12:37:57.539  1766  1846 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 12:37:57.539  1766  1846 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 12:37:57.539  1766  1846 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 12:37:57.542   873  1753 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-03 12:37:57.542   873  4285 E DropBoxManagerService: Can't write: system_app_crash
08-03 12:37:57.542   873  4285 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-03 12:37:57.542   873  4285 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 12:37:57.542   873  4285 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 12:37:57.542   873  4285 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 12:37:57.542   873  4285 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 12:37:57.542   873  4285 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 12:37:57.542   873  4285 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 12:37:57.542   873  4285 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 12:37:57.542   873  4285 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 12:37:57.542   873  4285 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 12:37:57.542   873  4285 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 12:37:57.542   873  4285 E DropBoxManagerService: 	... 5 more
08-03 12:37:57.546  1766  1846 I Process : Sending signal. PID: 1766 SIG: 9
08-03 12:37:57.550   873  1694 I ActivityManager: Killing 3722:com.google.android.gms.unstable/u0a11 (adj 15): empty #17
08-03 12:37:57.559  1660  4278 I Keyboard.Facilitator.DecoderInitializer: run()
,08-03 12:37:57.562  1660  4278 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,08-03 12:37:57.562  1660  4278 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-03 12:37:57.563  1660  4278 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-03 12:37:57.563  1660  4278 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-03 12:37:57.563  1660  4278 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-03 12:37:57.563  1660  4278 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/playlog.db'.
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at com.google.android.gms.playlog.store.h.b(SourceFile:527)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at com.google.android.gms.playlog.store.h.a(SourceFile:389)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at com.google.android.gms.playlog.service.c.a(SourceFile:95)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 12:37:57.567  1526  4277 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-03 12:37:57.567  1526  4277 E PlayLogIntentService: not an error (code 0): Could not open the database in read/write mode.
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at com.google.android.gms.playlog.store.h.b(SourceFile:527)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at com.google.android.gms.playlog.store.h.a(SourceFile:389)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at com.google.android.gms.playlog.service.c.a(SourceFile:95)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 12:37:57.567  1526  4277 E PlayLogIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-03 12:37:57.572  4249  4249 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
08-03 12:37:57.576  1660  4278 I Decoder : createOrResetDecoder
,08-03 12:37:57.614  2347  4246 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-03 12:37:57.624  1660  4278 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-03 12:37:57.658  4169  4169 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-03 12:37:57.699  1660  4278 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-03 12:37:57.700  1660  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-03 12:37:57.700  1660  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-03 12:37:57.711   373   595 E QMI_FW  : xport_send: Sendto failed for port 3328
,08-03 12:37:57.722  1660  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-03 12:37:57.722  1660  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-03 12:37:57.723  1660  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-03 12:37:57.723  1660  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-03 12:37:57.724  1660  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-03 12:37:57.724  1660  4278 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-03 12:37:57.724  1660  4278 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-03 12:37:57.724  1660  4278 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-03 12:37:57.724  1660  4278 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-03 12:37:57.763   873  1685 I ActivityManager: Killing 3982:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-03 12:37:57.768  1526  2700 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
08-03 12:37:57.768  1526  2700 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
08-03 12:37:57.768  1526  2700 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 12:37:57.768  1526  2700 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 12:37:57.775   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-03 12:37:57.724  1660  4278 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-03 12:37:57.789   873  1687 D GraphicsStats: Buffer count: 1
08-03 12:37:57.790   873  1755 I WindowState: WIN DEATH: Window{99bf895 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-03 12:37:57.789   873  1302 W InputDispatcher: channel '99bf895 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-03 12:37:57.790   873  1302 E InputDispatcher: channel '99bf895 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
08-03 12:37:57.790   873  1755 W InputDispatcher: Attempted to unregister already unregistered input channel '99bf895 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'

```
