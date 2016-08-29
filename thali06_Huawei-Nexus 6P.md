#### Test 8289468293e136b_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-29 07:13:20.235   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:13:20.692  5618  5618 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 07:13:20.699  5618  5618 D AndroidRuntime: CheckJNI is OFF
08-29 07:13:20.727  5618  5618 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 07:13:20.762  5618  5618 I Radio-JNI: register_android_hardware_Radio DONE
08-29 07:13:20.780  5618  5618 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 07:13:20.789   931  3540 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 07:13:20.836   931  3540 I ActivityManager: Start proc 5627:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-29 07:13:20.841  5618  5618 D AndroidRuntime: Shutting down VM
08-29 07:13:20.924  5627  5627 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-29 07:13:20.956  5627  5627 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 07:13:20.981  5627  5627 I LibraryLoader: Time to load native libraries: 21 ms (timestamps 6057-6078)
08-29 07:13:20.981  5627  5627 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 07:13:21.000  5627  5627 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b7aab16}
08-29 07:13:21.001  5627  5627 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 07:13:21.001  5627  5627 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 07:13:21.006  5627  5627 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 07:13:21.007  5627  5627 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 07:13:21.042  5627  5627 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 07:13:21.055  5627  5627 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 07:13:21.056  5627  5627 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 07:13:21.056  5627  5627 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 07:13:21.056  5627  5627 I Adreno  : Build Date                       : 10/21/15
08-29 07:13:21.056  5627  5627 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 07:13:21.056  5627  5627 I Adreno  : Local Branch                     : 
08-29 07:13:21.056  5627  5627 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 07:13:21.056  5627  5627 I Adreno  : Remote Branch                    : NONE
08-29 07:13:21.056  5627  5627 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 07:13:21.111   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37bb519:true
,08-29 07:13:21.166  5627  5627 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 07:13:21.181  5627  5627 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-29 07:13:21.216  5627  5665 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 07:13:21.225  5627  5652 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 07:13:21.236   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:13:21.258  5627  5665 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 07:13:21.352   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +472ms (total +544ms)
,08-29 07:13:21.378  5627  5627 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5627
,08-29 07:13:21.469  5627  5627 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 07:13:21.626  5627  5668 D jxcore_app_log: JniHelper::setJavaVM(0xf527c000), pthread_self() = -564127440
,08-29 07:13:21.633  5627  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 07:13:21.633  5627  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 07:13:21.633  5627  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 07:13:21.633  5627  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 07:13:21.633  5627  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 07:13:21.633  5627  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a542dc added. We now have 1 listener(s)
,08-29 07:13:21.638  5627  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,08-29 07:13:21.640  5627  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 07:13:21.640  5627  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 07:13:21.641  5627  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 07:13:21.645  5627  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c61fd6b added. We now have 1 listener(s)
08-29 07:13:21.645  5627  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:13:21.648   931  3065 D WifiService: New client listening to asynchronous messages
,08-29 07:13:21.649  5627  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 07:13:21.649  5627  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 07:13:21.649  5627  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-29 07:13:21.649  5627  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 07:13:21.650  5627  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 07:13:21.653  5627  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:13:21.653  5627  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-29 07:13:21.660  5627  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-29 07:13:21.660  5627  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:13:21.660  5627  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:21.660  5627  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:21.660  5627  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:21.660  5627  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:21.660  5627  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:13:21.660  5627  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:13:21.660  5627  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 07:13:21.660  5627  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 07:13:21.660  5627  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:13:21.661  5627  5668 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 07:13:21.663  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:21.666  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:21.686  5627  5627 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 07:13:22.158  5627  5636 I art     : Background sticky concurrent mark sweep GC freed 77308(8MB) AllocSpace objects, 19(2MB) LOS objects, 27% free, 23MB/32MB, paused 1.757ms total 250.415ms
,08-29 07:13:22.237   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:13:22.289  5627  5674 W jxcore-log: Initializing JXcore engine
08-29 07:13:22.289  5627  5674 W jxcore-log: JXcore engine is ready
,08-29 07:13:22.330  5674  5674 W Thread-57: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11768 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 07:13:22.330  5674  5674 W Thread-57: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[15447]" dev="sockfs" ino=15447 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 07:13:22.330  5674  5674 W Thread-57: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5235 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 07:13:22.330  5674  5674 W Thread-57: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[31378]" dev="sockfs" ino=31378 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 07:13:22.354  5627  5674 W jxcore-log: Starting JXcore engine
,08-29 07:13:22.415  5627  5674 W jxcore-log: Platform android
08-29 07:13:22.415  5627  5674 W jxcore-log: 
,08-29 07:13:22.415  5627  5674 W jxcore-log: Process ARCH arm
08-29 07:13:22.415  5627  5674 W jxcore-log: 
,08-29 07:13:22.510  5627  5674 I jxcore-log: JXcore Cordova bridge is ready!
08-29 07:13:22.510  5627  5674 I jxcore-log: 
,08-29 07:13:22.510  5627  5674 W jxcore-log: JXcore engine is started
,08-29 07:13:22.522  5627  5668 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 07:13:22.530  5627  5627 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 07:13:23.214   931  5355 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168310, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 07:13:23.238   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:13:24.239   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:13:25.239   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 07:13:29.226  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 07:13:29.226  5627  5674 I jxcore-log: 
,08-29 07:13:29.228  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 07:13:29.228  5627  5674 I jxcore-log: 
,08-29 07:13:29.232  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:13:29.232  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:29.232  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:29.232  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:29.232  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:29.232  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:13:29.232  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:13:29.232  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 07:13:29.233  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 07:13:29.235  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 07:13:29.235  5627  5674 I jxcore-log: 
,08-29 07:13:29.236  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 07:13:29.236  5627  5674 I jxcore-log: 
,08-29 07:13:29.582  5627  5674 D executeNativeTests: Running unit tests
,08-29 07:13:29.620  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 07:13:29.621  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac added. We now have 2 listener(s)
,08-29 07:13:29.621  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:13:29.621  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 07:13:29.621  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:13:29.621  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 07:13:29.621  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 added. We now have 2 listener(s)
08-29 07:13:29.622  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:13:29.622  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 07:13:29.624  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:13:29.627  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:13:29.627  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:29.627  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:29.627  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:29.627  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:29.627  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:13:29.627  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:13:29.627  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 07:13:29.628  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 07:13:29.628  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:13:29.630  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 07:13:29.630  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 07:13:29.630  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 07:13:29.631  5627  5674 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 07:13:29.632  5627  5674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 07:13:29.632  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 07:13:29.632  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 07:13:29.632  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 07:13:29.632  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.632  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.632  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.632  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.633  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.633  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:13:29.633  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:13:29.634  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac removed from the list
08-29 07:13:29.634  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.634  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 removed from the list
,08-29 07:13:29.635  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:29.641  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.642  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.642  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.642  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:13:29.642  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.643  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.643  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.643  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.643  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.644  5627  5674 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 07:13:29.645  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 07:13:29.645  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.645  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.645  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.645  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.645  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.645  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
,08-29 07:13:29.645  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.645  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.645  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.645  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.645  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.645  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.645  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.646  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.646  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.646  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.646  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
,08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-29 07:13:29.650  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 07:13:29.651  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 07:13:29.651  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 07:13:29.651  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.651  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.651  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.651  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.651  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:13:29.651  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.651  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.651  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.651  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.651  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.651  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:13:29.651  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.651  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.651  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.651  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.652  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.652  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 07:13:29.652  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.652  5627  5674 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 07:13:29.653  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:13:29.659  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:13:29.659  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:29.659  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:29.659  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:29.659  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:29.659  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:13:29.659  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:13:29.659  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 07:13:29.662  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 07:13:29.662  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 07:13:29.663  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 07:13:29.663  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 07:13:29.664  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:13:29.664  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:13:29.664  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:13:29.665  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 07:13:29.666  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 07:13:29.666  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.668  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 07:13:29.669  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 07:13:29.669  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 07:13:29.669  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.670  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 07:13:29.671  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 07:13:29.671  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 07:13:29.672  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 07:13:29.672  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:13:29.672  5627  5674 D BluetoothAdapter: STATE_ON
,08-29 07:13:29.674  4445  4507 D BtGatt.GattService: registerClient() - UUID=ca64a44a-0bdd-4231-a99e-8ba2a0a608bf
08-29 07:13:29.675  4445  4506 D BtGatt.GattService: onClientRegistered() - UUID=ca64a44a-0bdd-4231-a99e-8ba2a0a608bf, clientIf=5
,08-29 07:13:29.676  5627  5637 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 07:13:29.677  4445  4460 D BtGatt.GattService: start scan with filters
,08-29 07:13:29.682  4445  4512 D BtGatt.ScanManager: handling starting scan
08-29 07:13:29.682  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 07:13:29.682  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:13:29.682  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 07:13:29.682  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 07:13:29.684  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:13:29.685  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:13:29.685  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:13:29.685  4445  4512 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
,08-29 07:13:29.685  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 07:13:29.686  5627  5674 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 07:13:29.687  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.687  5627  5674 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 07:13:29.687  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.688  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 07:13:29.688  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.688  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:13:29.688  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 07:13:29.688  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 07:13:29.688  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:13:29.688  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:13:29.688  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:13:29.688  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 07:13:29.688  5627  5674 D BluetoothAdapter: STATE_ON
,08-29 07:13:29.689  4445  4662 D BtGatt.GattService: stopScan() - queue size =1
08-29 07:13:29.689  4445  4660 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 07:13:29.689  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:13:29.689  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:13:29.689  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:13:29.689  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 07:13:29.689  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:13:29.690  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:13:29.690  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:13:29.690  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:13:29.690  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 07:13:29.690  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:13:29.691  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.691  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:13:29.691  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:13:29.691  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.691  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.691  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.691  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:13:29.691  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 07:13:29.691  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.691  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:13:29.692  5627  5674 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 07:13:29.692  4445  4506 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:13:29.692  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.692  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:13:29.693  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:13:29.693  4445  4512 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 07:13:29.697  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:13:29.697  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:29.697  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:29.697  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:29.697  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:29.697  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:13:29.697  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:13:29.697  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 07:13:29.697  4445  4506 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:13:29.697  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.697  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 07:13:29.698  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:13:29.698  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:13:29.698  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:13:29.698  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:13:29.698  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:13:29.698  4445  4512 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:13:29.698  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:13:29.698  4445  4512 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 07:13:29.700  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 07:13:29.700  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 07:13:29.702  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.705  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 07:13:29.705  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.706  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 07:13:29.706  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 07:13:29.706  4445  4506 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:13:29.706  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.707  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 07:13:29.707  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:13:29.707  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:13:29.707  5627  5674 D BluetoothAdapter: STATE_ON
08-29 07:13:29.710  4445  4460 D BtGatt.GattService: registerClient() - UUID=9f9ad945-4be7-47cc-a326-9d3a9b18edfc
08-29 07:13:29.710  4445  4506 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:13:29.710  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.710  4445  4506 D BtGatt.GattService: onClientRegistered() - UUID=9f9ad945-4be7-47cc-a326-9d3a9b18edfc, clientIf=5
08-29 07:13:29.711  5627  5637 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 07:13:29.711  4445  4660 D BtGatt.GattService: start scan with filters
08-29 07:13:29.714  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 07:13:29.714  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:13:29.714  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:13:29.714  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 07:13:29.715  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:13:29.715  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:13:29.716  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:13:29.716  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 07:13:29.717  5627  5674 I io.jxcore.node.ConnectionHelper: start: OK
08-29 07:13:29.718  4445  4506 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:13:29.718  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.719  4445  4512 D BtGatt.ScanManager: stopping BLe Batch
08-29 07:13:29.719  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.719  5627  5674 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 07:13:29.719  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.719  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 07:13:29.719  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.719  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:13:29.719  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 07:13:29.719  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:13:29.719  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:13:29.719  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:13:29.720  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:13:29.720  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 07:13:29.720  5627  5674 D BluetoothAdapter: STATE_ON
08-29 07:13:29.721  4445  4458 D BtGatt.GattService: stopScan() - queue size =0
08-29 07:13:29.721  4445  4460 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 07:13:29.721  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:13:29.722  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:13:29.722  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:13:29.722  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:13:29.722  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:13:29.723  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:13:29.723  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:13:29.723  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:13:29.723  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 07:13:29.724  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:13:29.724  4445  4506 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:13:29.724  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.724  4445  4512 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 07:13:29.725  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.725  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:13:29.725  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.725  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:13:29.725  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:13:29.725  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:13:29.725  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.725  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.726  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.726  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.726  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.727  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.727  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.730  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.730  4445  4506 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:13:29.730  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.730  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.730  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.730  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.731  5627  5674 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 07:13:29.732  4445  4512 D BtGatt.ScanManager: handling starting scan
08-29 07:13:29.732  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:13:29.735  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:13:29.735  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:29.735  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:29.735  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:29.735  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:29.735  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:13:29.735  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:13:29.735  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 07:13:29.737  4445  4506 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:13:29.737  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.737  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 07:13:29.737  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:13:29.737  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:13:29.737  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:13:29.737  4445  4512 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 07:13:29.737  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:13:29.737  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:13:29.737  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:13:29.739  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 07:13:29.739  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 07:13:29.739  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.741  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 07:13:29.742  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.743  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 07:13:29.743  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 07:13:29.744  4445  4506 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:13:29.744  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.744  4445  4512 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:13:29.744  4445  4512 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:13:29.744  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 07:13:29.744  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:13:29.744  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:13:29.745  5627  5674 D BluetoothAdapter: STATE_ON
08-29 07:13:29.745  4445  4460 D BtGatt.GattService: registerClient() - UUID=3407f33d-f620-4607-9e22-dca44bf1693f
08-29 07:13:29.746  4445  4506 D BtGatt.GattService: onClientRegistered() - UUID=3407f33d-f620-4607-9e22-dca44bf1693f, clientIf=5
08-29 07:13:29.747  5627  5638 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 07:13:29.747  4445  4507 D BtGatt.GattService: start scan with filters
08-29 07:13:29.752  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 07:13:29.752  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:13:29.752  4445  4506 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:13:29.752  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:13:29.752  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.752  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 07:13:29.753  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:13:29.753  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:13:29.753  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:13:29.754  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 07:13:29.756  4445  4506 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:13:29.756  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.756  5627  5674 I io.jxcore.node.ConnectionHelper: start: OK
08-29 07:13:29.756  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.756  5627  5674 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 07:13:29.756  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.756  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 07:13:29.756  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.756  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:13:29.756  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 07:13:29.756  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:13:29.756  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:13:29.756  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:13:29.756  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:13:29.756  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 07:13:29.757  5627  5674 D BluetoothAdapter: STATE_ON
08-29 07:13:29.757  4445  4662 D BtGatt.GattService: stopScan() - queue size =1
08-29 07:13:29.757  4445  4458 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 07:13:29.757  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:13:29.757  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:13:29.757  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:13:29.757  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:13:29.758  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:13:29.760  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:13:29.760  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:13:29.760  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:13:29.760  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 07:13:29.760  4445  4506 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:13:29.760  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.760  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:13:29.760  4445  4512 D BtGatt.ScanManager: stopping BLe Batch
08-29 07:13:29.760  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.760  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:13:29.760  5627  5674 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 07:13:29.761  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.761  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.761  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:13:29.761  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.761  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.761  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:13:29.761  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:13:29.761  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.761  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.761  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.761  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.761  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.761  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.761  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.762  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.762  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.762  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.762  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.762  5627  5674 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 07:13:29.762  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.762  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.762  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.762  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.762  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.762  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.762  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.762  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.762  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.763  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.763  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.763  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.763  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.763  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.763  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.763  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.763  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.763  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.764  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 07:13:29.764  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.764  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.764  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.764  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.764  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.764  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.764  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.764  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.764  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.764  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.764  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.764  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.764  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.764  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.765  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.765  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.765  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.765  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.765  4445  4506 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:13:29.765  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.765  4445  4512 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 07:13:29.766  5627  5674 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 07:13:29.766  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.766  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.766  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.766  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.766  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.766  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.766  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.766  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.766  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.766  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.766  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.766  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.766  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.766  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.768  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.768  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.768  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.768  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.768  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 07:13:29.768  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.768  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.769  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.769  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.769  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:13:29.769  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.769  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.769  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.769  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.769  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.769  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.769  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.769  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.769  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.771  4445  4506 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:13:29.771  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.771  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.771  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.771  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.771  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.771  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 07:13:29.771  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 07:13:29.771  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 07:13:29.772  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 07:13:29.772  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 07:13:29.772  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 07:13:29.772  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.772  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.772  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.772  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.772  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.772  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.772  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.772  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.772  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.772  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.772  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.772  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.773  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.773  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.774  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.774  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.774  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.774  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.774  4445  4512 D BtGatt.ScanManager: handling starting scan
08-29 07:13:29.774  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 07:13:29.774  5627  5674 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 07:13:29.774  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 07:13:29.776  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 07:13:29.776  5627  5674 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 07:13:29.776  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 07:13:29.776  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 07:13:29.777  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 07:13:29.777  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 07:13:29.777  5627  5674 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 07:13:29.778  5627  5674 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 07:13:29.778  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 07:13:29.778  5627  5674 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 07:13:29.778  5627  5674 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 07:13:29.778  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 07:13:29.778  5627  5674 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 07:13:29.778  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 07:13:29.779  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 07:13:29.780  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 07:13:29.780  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 07:13:29.780  4445  4506 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:13:29.780  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.781  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 07:13:29.781  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 07:13:29.781  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 07:13:29.781  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 07:13:29.781  4445  4512 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 07:13:29.781  5627  5674 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 07:13:29.781  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.781  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.781  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.781  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.781  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.781  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.782  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 07:13:29.782  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.782  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.782  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.782  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.782  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.782  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.782  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.782  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.782  5627  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
08-29 07:13:29.782  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.783  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.783  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.783  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.783  5627  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
08-29 07:13:29.786  4445  4506 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:13:29.786  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.786  4445  4512 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:13:29.786  5627  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
08-29 07:13:29.786  4445  4512 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:13:29.787  5627  5674 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 07:13:29.787  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.787  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.787  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.787  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.787  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.787  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.787  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.787  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.787  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.787  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.787  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.787  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.787  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.787  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.794  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.794  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.794  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.794  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.795  5627  5674 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 07:13:29.795  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.795  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.795  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.795  4445  4506 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:13:29.795  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.795  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.795  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.795  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.795  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.795  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.795  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.795  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.795  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.795  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.795  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.795  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.797  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.797  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.797  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.797  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.798  5627  5674 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 07:13:29.798  5627  5674 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 07:13:29.798  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 07:13:29.798  5627  5674 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 07:13:29.798  5627  5674 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 07:13:29.798  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 07:13:29.798  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 07:13:29.798  5627  5674 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:,22:33:44:55
08-29 07:13:29.798  5627  5674 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 07:13:29.798  5627  5674 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 07:13:29.798  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 07:13:29.798  5627  5674 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 07:13:29.798  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.798  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.798  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.799  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.799  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.799  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.799  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.799  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.799  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.799  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.799  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.799  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.799  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.799  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.800  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.800  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.800  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.800  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.801  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.801  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.801  4445  4506 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:13:29.801  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.801  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.801  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.801  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.801  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.801  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.801  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.801  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.801  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.801  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.801  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.801  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.801  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.801  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.801  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.801  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.801  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.801  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.801  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.801  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.801  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.802  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.802  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.802  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.802  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.802  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.802  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.802  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.802  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.802  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.802  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.802  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.803  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 07:13:29.803  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:13:29.803  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 07:13:29.804  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 07:13:29.804  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 07:13:29.804  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 07:13:29.804  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 07:13:29.804  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.804  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 07:13:29.804  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 07:13:29.804  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 07:13:29.804  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 07:13:29.804  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.804  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 07:13:29.804  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.804  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.804  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:13:29.804  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:13:29.804  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:13:29.804  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 07:13:29.804  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.804  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.805  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:13:29.805  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.805  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.805  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.805  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.805  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.805  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.805  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.805  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.805  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:13:29.805  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.805  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.805  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.805  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.805  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:13:29.805  5627  5677 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:13:29.805  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.805  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.805  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.805  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:13:29.806  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.806  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.806  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.806  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.806  5627  5674 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 07:13:29.806  5627  5674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 07:13:29.807  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 07:13:29.807  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 07:13:29.807  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.807  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.807  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.807  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.807  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.807  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.807  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.807  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.807  4445  4506 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:13:29.807  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.807  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.807  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.807  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.807  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.807  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.807  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.808  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.808  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.808  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.808  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.808  5627  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 07:13:29.808  5627  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 07:13:29.808  5627  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 07:13:29.808  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 07:13:29.809  4445  4512 D BtGatt.ScanManager: stopping BLe Batch
08-29 07:13:29.809  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.809  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.809  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.809  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.809  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.809  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.809  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.809  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.809  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.809  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 07:13:29.809  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.809  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.809  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.809  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.811  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.811  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.811  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.811  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.812  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:29.812  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:29.812  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:29.812  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:29.812  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.812  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.812  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@747aaac not in the list
08-29 07:13:29.812  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.812  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.812  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:29.812  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.812  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.812  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:29.812  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:29.812  4445  4506 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:13:29.812  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.812  4445  4512 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 07:13:29.813  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:29.813  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:29.813  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:29.813  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c4375 not in the list
08-29 07:13:29.813  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 07:13:29.813  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 07:13:29.813  5627  5674 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 07:13:29.813  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 07:13:29.813  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 07:13:29.813  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 07:13:29.814  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 07:13:29.814  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 07:13:29.814  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 07:13:29.814  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 07:13:29.814  5627  5674 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 07:13:29.814  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 07:13:29.814  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 07:13:29.814  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 07:13:29.815  5627  5674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 07:13:29.815  5627  5674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 07:13:29.815  5627  5674 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 07:13:29.815  5627  5674 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 07:13:29.815  5627  5674 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 07:13:29.815  5627  5674 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 07:13:29.815  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:29.815  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3d9f4f added. We now have 2 listener(s)
08-29 07:13:29.815  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:13:29.816  5627  5674 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 07:13:29.816  4445  4506 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:13:29.816  4445  4506 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:29.816   931  3631 D WifiService: setWifiEnabled: true pid=5627, uid=10077
08-29 07:13:29.816   931  3631 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 07:13:29.817  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:29.817  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ce116dc added. We now have 3 listener(s)
08-29 07:13:29.817  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:13:29.821  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:29.821  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@af5f3e5 added. We now have 4 listener(s)
08-29 07:13:29.821  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:13:29.823  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:29.823  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@326ceba added. We now have 5 listener(s)
08-29 07:13:29.823  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:13:29.824   931  3656 D WifiService: setWifiEnabled: false pid=5627, uid=10077
08-29 07:13:29.824   931  3656 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 07:13:29.827   931  3054 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 07:13:29.828   931  3054 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 07:13:29.828   931  3054 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 07:13:29.828   931  3054 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 07:13:29.829  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:13:29.829  4445  4502 D BluetoothAdapterState: Current state: ON, message: 23
08-29 07:13:29.829  4445  4502 D BluetoothAdapterProperties: Setting state to 13
08-29 07:13:29.829  4445  4502 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 07:13:29.830  4445  4502 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 07:13:29.830  4445  4502 I BluetoothAdapterState: Entering PendingCommandState
08-29 07:13:29.831  4445  4506 D BluetoothAdapterProperties: Scan Mode:20
08-29 07:13:29.831  4445  4502 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 07:13:29.832  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:29.832  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:13:29.832  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:29.832  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:29.832  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:29.832  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:13:29.832  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:13:29.832  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:13:29.832  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 07:13:29.832  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:29.832  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 07:13:29.832  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:13:29.835  4445  4445 D HeadsetService: Received stop request...Stopping profile...
08-29 07:13:29.835  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.838  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.839   931  3054 E native  : do suspend true
08-29 07:13:29.841  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:29.841  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:29.841  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:29.841  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:29.841  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:29.841  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:13:29.841  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:13:29.841  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:13:29.841  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 07:13:29.841  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:29.841  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 07:13:29.843  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.846  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.848  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.853   931   944 I ActivityManager: Start proc 5680:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-29 07:13:29.854  3613  3653 D BluetoothHeadset: Proxy object disconnected
,08-29 07:13:29.854   931   931 D BluetoothHeadset: Proxy object disconnected
08-29 07:13:29.854   931   931 D BluetoothHeadset: Proxy object disconnected
,08-29 07:13:29.854   931   931 D BluetoothHeadset: Proxy object disconnected
08-29 07:13:29.855  3237  3254 D BluetoothHeadset: Proxy object disconnected
08-29 07:13:29.859  3237  3237 D HeadsetProfile: Bluetooth service disconnected
,08-29 07:13:29.862  4445  4445 D A2dpService: Received stop request...Stopping profile...
,08-29 07:13:29.863  4445  4655 D A2dpStateMachine: Exit Disconnected: -1
08-29 07:13:29.864   931   931 D BluetoothA2dp: Proxy object disconnected
08-29 07:13:29.864  3237  3237 D BluetoothA2dp: Proxy object disconnected
08-29 07:13:29.865  4445  4445 D BluetoothMapService: onReceive
08-29 07:13:29.865  4445  4445 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 07:13:29.865  4445  4445 D BluetoothMapService: STATE_TURNING_OFF
,08-29 07:13:29.865  4445  4445 V BluetoothAdapterState: isTurningOff()=true
08-29 07:13:29.865  4445  4445 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:29.865  4445  4445 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:29.865  4445  4445 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 07:13:29.866  4445  4445 D HidService: Received stop request...Stopping profile...
08-29 07:13:29.866  4445  4445 D HidService: Stopping Bluetooth HidService
08-29 07:13:29.867  3237  3237 D BluetoothInputDevice: Proxy object disconnected
08-29 07:13:29.867  3237  3237 D HidProfile: Bluetooth service disconnected
,08-29 07:13:29.868  4445  4445 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 07:13:29.869  4445  4445 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 07:13:29.869  4445  4649 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:13:29.869  4445  4649 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 07:13:29.869  4445  4649 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 07:13:29.869  4445  4445 D HealthService: Received stop request...Stopping profile...
08-29 07:13:29.869  4445  4506 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 07:13:29.870  4445  4506 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 07:13:29.872   508   925 D CommandListener: Clearing all IP addresses on wlan0
,08-29 07:13:29.872   931  5356 D DhcpClient: Clearing IP address
08-29 07:13:29.874  4445  4445 D PanService: Received stop request...Stopping profile...
08-29 07:13:29.875  3237  3237 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 07:13:29.875  3237  3237 D PanProfile: Bluetooth service disconnected
08-29 07:13:29.876  4445  4445 D BluetoothMapService: Received stop request...Stopping profile...
08-29 07:13:29.876  4445  4445 D BluetoothMapService: stop()
08-29 07:13:29.878  4445  4445 D BluetoothMapAppObserver: deinitObservers()
08-29 07:13:29.878  4445  4445 D BluetoothMapAppObserver: removeReceiver()
08-29 07:13:29.879  3237  3237 D BluetoothMap: Proxy object disconnected
,08-29 07:13:29.879  3237  3237 D MapProfile: Bluetooth service disconnected
08-29 07:13:29.879  4445  4445 V BluetoothAdapterState: isTurningOff()=true
08-29 07:13:29.879  4445  4445 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:29.879  4445  4445 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:29.879  4445  4445 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:29.880  4445  4445 D SapService: Received stop request...Stopping profile...
08-29 07:13:29.880  4445  4445 V SapService: stop()
08-29 07:13:29.880   508   925 D CommandListener: Setting iface cfg
08-29 07:13:29.883  4445  4506 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 07:13:29.883  4445  4649 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:13:29.883  4445  4649 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:13:29.883  4445  4649 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 07:13:29.883  4445  4649 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 07:13:29.883  4445  4649 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 07:13:29.883  4445  4649 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 07:13:29.884  4445  4445 I BtOppRfcommListener: stopping Accept Thread
08-29 07:13:29.884  4445  5264 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 07:13:29.884  4445  5264 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 07:13:29.885  4445  4445 V BluetoothAdapterState: isTurningOff()=true
,08-29 07:13:29.885  4445  4445 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:29.885  4445  4445 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:29.885  4445  4445 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:29.886   931  5357 D DhcpClient: Receive thread stopped
08-29 07:13:29.886  4445  4445 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 07:13:29.886  4445  4445 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 07:13:29.886  4445  4445 V BluetoothAdapterState: isTurningOff()=true
08-29 07:13:29.886  4445  4445 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:29.886  4445  4445 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:29.886  4445  4445 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:29.886  4445  4506 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 07:13:29.886  4445  4445 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 07:13:29.886  4445  4506 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 07:13:29.887  4445  4445 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 07:13:29.887  4445  4445 V BluetoothAdapterState: isTurningOff()=true
08-29 07:13:29.887  4445  4445 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:29.887  4445  4445 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:29.887  4445  4445 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:29.887  4445  4445 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 07:13:29.887  4445  4445 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 07:13:29.888  4445  4445 D BluetoothMapService: MAP Service closeService in
,08-29 07:13:29.888  4445  4445 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 07:13:29.889  4445  4445 D ObexServerSockets0: shutdown(block = true)
08-29 07:13:29.889  4445  4445 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 07:13:29.889  4445  4663 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 07:13:29.889  4445  4664 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 07:13:29.889  5680  5680 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
08-29 07:13:29.890  4445  4651 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 07:13:29.890  4445  4445 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 07:13:29.892  3701  5419 V NativeCrypto: Read error: ssl=0x7f8aaf7a80: I/O error during system call, Connection timed out
08-29 07:13:29.894  4445  4445 V BluetoothAdapterState: isTurningOff()=true
08-29 07:13:29.894  4445  4445 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:29.894  4445  4445 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:29.894  4445  4445 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:29.894  4445  4445 D BluetoothMapService: cleanup()
08-29 07:13:29.894  4445  4445 D BluetoothMapService: MAP Service closeService in
08-29 07:13:29.895  3701  5419 V NativeCrypto: SSL shutdown failed: ssl=0x7f8aaf7a80: I/O error during system call, Broken pipe
08-29 07:13:29.895  4445  4445 V BluetoothAdapterState: isTurningOff()=true
08-29 07:13:29.895  4445  4445 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:29.895  4445  4445 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:29.895  4445  4445 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 07:13:29.896  4445  4502 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 07:13:29.896  4445  4502 D BluetoothAdapterProperties: Setting state to 15
08-29 07:13:29.896  4445  4502 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 07:13:29.896   931  3069 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 07:13:29.896   931  3069 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 07:13:29.897  4445  4502 I BluetoothAdapterState: Entering BleOnState
,08-29 07:13:29.899   540   540 E Parcel  : Reading a NULL string not supported here.
08-29 07:13:29.900   931  3069 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 07:13:29.900  3237  3252 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 07:13:29.901  3613  3653 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:13:29.902   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:13:29.902  3237  3252 D BluetoothMap: onBluetoothStateChange: up=false
08-29 07:13:29.902  3583  3706 W QCNEJ   : |CORE| network lost: 100
08-29 07:13:29.902  3237  3254 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 07:13:29.903  3583  3706 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,08-29 07:13:29.904  3237  3801 D BluetoothPan: onBluetoothStateChange on: false
08-29 07:13:29.904   931   931 D RttService: SCAN_AVAILABLE : 1
08-29 07:13:29.905   931  3164 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 07:13:29.905   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 07:13:29.905   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:13:29.905   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:13:29.905  3237  3252 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 07:13:29.906  3237  3254 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:13:29.906  4445  4502 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 07:13:29.906  4445  4502 D BluetoothAdapterProperties: Setting state to 16
08-29 07:13:29.906  4445  4502 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 07:13:29.909  5680  5680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 07:13:29.910  4445  4502 D BluetoothAdapterProperties: onBleDisable
08-29 07:13:29.910  4445  4502 I BluetoothAdapterState: Entering PendingCommandState
08-29 07:13:29.910  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:29.910  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:29.910  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:29.910  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:29.910  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:29.910  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:13:29.910  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:29.910  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:29.910  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:13:29.910  4445  4503 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-29 07:13:29.911  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 07:13:29.911  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:13:29.912  4445  4649 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 07:13:29.912  4445  4649 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:13:29.914  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:29.914  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:29.914  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:29.914  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:29.914  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:29.914  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:13:29.914  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:29.914  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:29.914  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:13:29.914  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:29.914  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:13:29.916  4445  4506 D BluetoothAdapterProperties: Scan Mode:20
08-29 07:13:29.917   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@89c3108:true
08-29 07:13:29.918  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 07:13:29.918  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.919  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:29.924   931  3054 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 07:13:29.930   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 07:13:29.947   931  5046 I ActivityManager: Start proc 5698:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 07:13:29.949   931  3054 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 07:13:29.949   931  3054 E native  : do suspend true
,08-29 07:13:29.965   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 07:13:29.966   508   925 D TetherController: Setting IP forward enable = 0
,08-29 07:13:29.966   931  3069 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 07:13:29.966   931  3069 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 07:13:29.970   931   948 D Tethering: MasterInitialState.processMessage what=3
08-29 07:13:29.971  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.973  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:29.973  4767  4767 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-29 07:13:29.976  4871  4921 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 07:13:29.976  4871  4921 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 07:13:29.976  4871  4921 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 07:13:29.976  4871  4921 E SarControlService: no key has been found,reset the power
08-29 07:13:29.976  4871  4938 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 07:13:29.976  4871  4938 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,08-29 07:13:29.976  4871  4938 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 07:13:29.977  4926  4926 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 07:13:29.977  4926  4926 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 07:13:29.978  4871  4938 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 07:13:29.978  4871  4938 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,08-29 07:13:29.978  4871  4938 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,08-29 07:13:29.979  4926  4926 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 07:13:29.979  4926  4926 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 07:13:29.981  4926  4941 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5d05831 HexData = [00000000ea03000000000000ffffffff]
,08-29 07:13:29.981  4926  4941 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 07:13:29.981  4926  4941 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
08-29 07:13:29.981  4926  4926 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 07:13:29.982  4871  4885 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 07:13:29.984  4926  4941 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5d05831 HexData = [00000000eb03000000000000ffffffff]
08-29 07:13:29.984  4926  4941 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 07:13:29.984  4926  4941 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
08-29 07:13:29.984  4926  4926 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 07:13:29.985  4871  4882 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-29 07:13:29.991  5698  5698 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
08-29 07:13:29.993  5680  5680 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 07:13:29.995  5680  5680 D BluetoothMap: Create BluetoothMap proxy object
,08-29 07:13:30.006  5680  5680 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 07:13:30.022   508   925 E Netd    : netlink response contains error (No such file or directory)
,08-29 07:13:30.022   931  3069 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 07:13:30.023   508   925 D CommandListener: Clearing all IP addresses on wlan0
08-29 07:13:30.024   508   925 D TetherController: Setting IP forward enable = 0
08-29 07:13:30.024  5680  5680 D DockEventReceiver: finishStartingService: stopping service
,08-29 07:13:30.026   931  3054 D DhcpClient: doQuit
08-29 07:13:30.026   931  3054 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 07:13:30.027  3725  3725 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-29 07:13:30.032  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:30.032  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:30.032  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:30.032  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:30.032  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:13:30.032  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:13:30.032  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:30.032  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:30.032  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:13:30.033  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:30.033  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:13:30.034   931  5356 D DhcpClient: onQuitting
08-29 07:13:30.036  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:30.036  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:30.036  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:30.036  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:30.036  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:13:30.036  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:13:30.036  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:30.036  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:30.036  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:13:30.036   931  3628 I ActivityManager: Killing 5406:com.android.chrome/u0a39 (adj 15): empty #17
08-29 07:13:30.036  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:30.036  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:13:30.062  3725  3725 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 07:13:30.068  3725  3725 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 07:13:30.119  4445  4506 I bt_hci  : shut_down
,08-29 07:13:30.122  4445  4513 D bt_hwcfg: hw_epilog_process
,08-29 07:13:30.122  4445  4513 I bt_vendor: low_power_mode_cb
,08-29 07:13:30.125  4445  4513 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 07:13:30.125  4445  4513 I bt_vendor: epilog_cb
,08-29 07:13:30.125  4445  4513 I bt_hci  : epilog_finished_callback
08-29 07:13:30.127  4445  4506 I bt_hci_h4: hal_close
08-29 07:13:30.128  4445  4506 I bt_userial_vendor: device fd = 51 close
,08-29 07:13:30.136  3725  3725 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 07:13:30.154  3725  3725 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 07:13:30.235  4445  4503 D bt_stack_manager: event_shut_down_stack finished.
,08-29 07:13:30.235  4445  4502 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 07:13:30.238  4445  4445 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 07:13:30.238  4445  4502 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 07:13:30.238  4445  4445 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 07:13:30.238  4445  4445 D BtGatt.GattService: stop()
08-29 07:13:30.238  4445  4445 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 07:13:30.240  4445  4445 V BluetoothAdapterState: isTurningOff()=false
,08-29 07:13:30.240  4445  4445 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:30.240  4445  4445 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 07:13:30.240  4445  4445 V BluetoothAdapterState: isBleTurningOff()=true
08-29 07:13:30.241  4445  4502 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 07:13:30.241  4445  4502 D BluetoothAdapterProperties: Setting state to 10
08-29 07:13:30.241  4445  4502 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 07:13:30.241  4445  4502 I BluetoothAdapterState: Entering OffState
,08-29 07:13:30.243   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 07:13:30.252  4445  4445 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 07:13:30.252  4445  4445 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 07:13:30.253  4445  4445 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 07:13:30.254  4445  4503 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 07:13:30.255  4445  4503 D bt_stack_manager: event_clean_up_stack finished.
08-29 07:13:30.257  4312  4312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 07:13:30.257   931  3054 D wifi    : In wifi stop Hal
08-29 07:13:30.257   931  3054 D wifi    : halHandle = 0x7f8a387080, mVM = 0x7fa62cd140, mCls = 0x100b2e
08-29 07:13:30.257   931  3720 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 07:13:30.257   931  3720 D WifiHAL : Got a signal to exit!!!
08-29 07:13:30.257   931  3720 I WifiHAL : Exit wifi_event_loop
08-29 07:13:30.259  3727  4070 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 07:13:30.259   931  3054 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 07:13:30.259  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:30.259   931  3054 E WifiHAL : Event processing terminated
08-29 07:13:30.259   931  3054 D wifi    : In wifi cleaned up handler
08-29 07:13:30.259   931  3054 I WifiHAL : Internal cleanup completed
08-29 07:13:30.260  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:30.264  4445  4445 I art     : System.exit called, status: 0
08-29 07:13:30.265  4445  4445 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 07:13:30.282  5698  5698 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 07:13:30.282   931  3720 D wifi    : set interface wlan0 flags (DOWN)
08-29 07:13:30.282  5698  5698 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:13:30.282  5698  5698 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 0,7:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:13:30.282  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:13:30.283  5698  5698 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:13:3,0.283  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:13:30.283   931  3054 D WifiNative-HAL: HAL event thread stopped successfully
08-29 07:13:30.283  5698  5698 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:13:30.283  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:13:30.288  5698  5698 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:13:30.288  5698  5698 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:13:30.288  5698  5698 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:13:30.288  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:13:30.305  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 07:13:30.349   931  3309 I ActivityManager: Process com.android.bluetooth (pid 4445) has died
08-29 07:13:30.354  5680  5680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 07:13:30.371   931  3656 I ActivityManager: Start proc 5743:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-29 07:13:30.372  5680  5680 D DockEventReceiver: finishStartingService: stopping service
,08-29 07:13:30.374   931  3628 I ActivityManager: Killing 4808:com.google.android.calendar/u0a36 (adj 15): empty #17
,08-29 07:13:30.426  5698  5729 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 07:13:30.483   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@73af449:true
,08-29 07:13:30.487  5743  5743 D AdapterServiceConfig: Adding HeadsetService
,08-29 07:13:30.487  5743  5743 D AdapterServiceConfig: Adding A2dpService
08-29 07:13:30.487  5743  5743 D AdapterServiceConfig: Adding HidService
08-29 07:13:30.487  5743  5743 D AdapterServiceConfig: Adding HealthService
,08-29 07:13:30.488  5743  5743 D AdapterServiceConfig: Adding PanService
08-29 07:13:30.488  5743  5743 D AdapterServiceConfig: Adding GattService
08-29 07:13:30.488  5743  5743 D AdapterServiceConfig: Adding BluetoothMapService
08-29 07:13:30.488  5743  5743 D AdapterServiceConfig: Adding SapService
08-29 07:13:30.490   931   948 D Tethering: InitialState.processMessage what=4
,08-29 07:13:30.493   931  3511 I ActivityManager: Killing 5439:com.google.android.deskclock/u0a66 (adj 15): empty #17
,08-29 07:13:30.558   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 07:13:30.558  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 07:13:30.573  3982  3982 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 07:13:30.577  3982  3982 D SystemUpdateService: onCreate
,08-29 07:13:30.580  3982  3982 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 07:13:30.589  3982  3982 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 07:13:30.593  3982  5389 I iu.UploadsManager: num queued entries: 0
08-29 07:13:30.594  3982  5389 I iu.UploadsManager: num updated entries: 0
08-29 07:13:30.594  3982  5389 I iu.SyncManager: NEXT; no task
,08-29 07:13:30.596  3982  3982 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 07:13:30.598  3982  3982 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 07:13:30.603  3982  5757 I SystemUpdateService: active receiver: enabled
,08-29 07:13:30.609  3982  5757 I SystemUpdateService: showing system update notification
,08-29 07:13:30.613   931  3540 I ActivityManager: Start proc 5759:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 07:13:30.630  3982  5757 V SystemUpdateService: retry (wakeup: false) in 3599975 ms
08-29 07:13:30.632  3982  3982 D SystemUpdateService: onDestroy
,08-29 07:13:30.658  5759  5759 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,08-29 07:13:30.660  5759  5759 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 07:13:30.666  5759  5759 D SprintDMHelper: simOperator: 
08-29 07:13:30.666  5759  5759 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 07:13:30.679   931  3234 I ActivityManager: Start proc 5771:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 07:13:30.680   931  3234 I ActivityManager: Killing 5456:com.qualcomm.timeservice/1000 (adj 15): empty #17
,08-29 07:13:30.754  4312  5785 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 07:13:30.757   931  3234 I ActivityManager: Killing 4517:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-29 07:13:30.790   931  3234 I ActivityManager: Start proc 5786:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 07:13:30.822  5786  5786 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,08-29 07:13:30.872  5786  5786 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 07:13:30.875   931  5046 I ActivityManager: Killing 5502:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-29 07:13:32.834   931   942 D WifiService: setWifiEnabled: true pid=5627, uid=10077
,08-29 07:13:32.834   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 07:13:32.842   508   925 D SoftapController: Softap fwReload - Ok
,08-29 07:13:32.846   508   925 D CommandListener: Setting iface cfg
08-29 07:13:32.847   508   925 D CommandListener: Trying to bring down wlan0
08-29 07:13:32.848   508   925 D CommandListener: Clearing all IP addresses on wlan0
,08-29 07:13:32.852   931  3054 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 07:13:33.471   931  3054 D wifi    : set interface wlan0 flags (UP)
,08-29 07:13:33.476   931  3054 I WifiHAL : Initializing wifi
08-29 07:13:33.476   931  3054 I WifiHAL : Creating socket
08-29 07:13:33.480   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 07:13:33.486   931  3054 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-29 07:13:33.486   931  3054 D wifi    : Did set static halHandle = 0x7f8a387080
08-29 07:13:33.486   931  3054 D wifi    : halHandle = 0x7f8a387080, mVM = 0x7fa62cd140, mCls = 0x1816
08-29 07:13:33.486   931  3054 D wifi    : array field set
08-29 07:13:33.486   931  3054 I WifiNative-HAL: interface[0] = wlan0
,08-29 07:13:33.488   931  5811 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547779801216
08-29 07:13:33.489   931  5811 D wifi    : waitForHalEvents called, vm = 0x7fa62cd140, obj = 0x1816, env = 0x7f8ad1b640
,08-29 07:13:33.553  5812  5812 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 07:13:33.574  5812  5812 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 07:13:33.583  5812  5812 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 07:13:33.584  5812  5812 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 07:13:33.590   931  3054 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 07:13:33.600  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:33.602  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:33.609   931  3054 D WifiConfigStore: Loading config and enabling all networks 
,08-29 07:13:33.610  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 07:13:33.610  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:33.610  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:33.610  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:33.610  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:33.610  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:13:33.610  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:33.610  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:33.610  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:13:33.610  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:33.610  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:13:33.611  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:33.611  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:33.611  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:33.611  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:33.611  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:33.611  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:13:33.611  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:33.611  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:33.611  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:13:33.611  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:33.612  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:13:33.617   931  3054 D WifiConfigStore: loaded 0 passpoint configs
,08-29 07:13:33.617   931  3054 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 07:13:33.618   931  3054 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 07:13:33.619   931  3054 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 07:13:33.619   931  3054 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 07:13:33.619   931  3054 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 07:13:33.622   931  3054 D WifiNative-HAL: Setting external_sim to 1
,08-29 07:13:33.623  4312  4312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 07:13:33.623   931  3054 D wifi    : setting dfs flag to true, 0x7f8c2961e0
08-29 07:13:33.623   931  3054 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 07:13:33.624   931  3054 D wifi    : setting scan oui 0x7f8c2961e0
,08-29 07:13:33.624   931  3054 D WifiHAL : Sending mac address OUI
,08-29 07:13:33.638   931  3054 E native  : do suspend true
,08-29 07:13:33.643   931  3054 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 07:13:33.643   508   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 07:13:33.644   931   931 D RttService: SCAN_AVAILABLE : 3
08-29 07:13:33.644   931  3164 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 07:13:33.645   508   925 D CommandListener: Setting iface cfg
,08-29 07:13:33.650   931  3053 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,08-29 07:13:33.650   931  3053 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 07:13:33.652   931  3053 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 07:13:33.657   931  3053 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 07:13:33.673   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=178770 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,08-29 07:13:35.841   931  3540 D WifiService: setWifiEnabled: false pid=5627, uid=10077
,08-29 07:13:35.841   931  3540 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 07:13:35.857   931   931 D RttService: SCAN_AVAILABLE : 1
,08-29 07:13:35.857   931  3164 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 07:13:35.867   931  3054 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 07:13:35.868   508   925 D CommandListener: Clearing all IP addresses on wlan0
,08-29 07:13:35.869   931  3054 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 07:13:35.870  5812  5812 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-29 07:13:35.874  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:35.874  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:35.874  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:35.874  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:35.874  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:13:35.874  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:13:35.874  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:35.874  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:35.874  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:13:35.874  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:35.874  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:13:35.875  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:35.876  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:35.876  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:35.876  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:35.876  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:13:35.876  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:13:35.876  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:35.876  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:35.876  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:13:35.876  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:35.876  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:13:35.886  5812  5812 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 07:13:35.893  5812  5812 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 07:13:35.903  5812  5812 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 07:13:35.909   931  3054 D wifi    : In wifi stop Hal
,08-29 07:13:35.909   931  3054 D wifi    : halHandle = 0x7f8a387080, mVM = 0x7fa62cd140, mCls = 0x1816
08-29 07:13:35.909   931  5811 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 07:13:35.910   931  5811 D WifiHAL : Got a signal to exit!!!
08-29 07:13:35.910   931  5811 I WifiHAL : Exit wifi_event_loop
08-29 07:13:35.910   931  3054 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 07:13:35.911   931  3054 E WifiHAL : Event processing terminated
08-29 07:13:35.911   931  3054 D wifi    : In wifi cleaned up handler
08-29 07:13:35.911   931  3054 I WifiHAL : Internal cleanup completed
08-29 07:13:35.911  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:35.909  4312  4312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 07:13:35.912  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:35.915  3727  4070 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 07:13:35.938   931  5811 D wifi    : set interface wlan0 flags (DOWN)
08-29 07:13:35.939   931  3054 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 07:13:36.146   931   948 D Tethering: InitialState.processMessage what=4
,08-29 07:13:36.152   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 07:13:38.879   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c1a880a:true
,08-29 07:13:38.880  5743  5743 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 07:13:38.885  5743  5743 I bt_bluedroid: init
,08-29 07:13:38.885  5743  5818 I BluetoothAdapterState: Entering OffState
,08-29 07:13:38.889  5743  5819 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 07:13:38.889  5743  5819 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 07:13:38.889  5743  5819 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 07:13:38.889  5743  5819 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 07:13:38.890  5743  5743 I bt_bluedroid: get_profile_interface socket
,08-29 07:13:38.894  5743  5822 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 07:13:38.895  5743  5743 I bt_bluedroid: get_profile_interface sdp
08-29 07:13:38.897  5743  5822 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 07:13:38.900  5743  5753 I bt_bluedroid: config_hci_snoop_log
08-29 07:13:38.902   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 07:13:38.907  5743  5818 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 07:13:38.907  5743  5818 D BluetoothAdapterProperties: Setting state to 14
08-29 07:13:38.907  5743  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 07:13:38.909  5743  5818 D BluetoothBondStateMachine: make
,08-29 07:13:38.911  5743  5823 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 07:13:38.915  5743  5818 I BluetoothAdapterState: Entering PendingCommandState
,08-29 07:13:38.916  5743  5743 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 07:13:38.919  5743  5743 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
08-29 07:13:38.920  5743  5743 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 07:13:38.920  5743  5743 D BtGatt.GattService: Received start request. Starting profile...
08-29 07:13:38.921  5743  5743 D BtGatt.GattService: start()
08-29 07:13:38.921  5743  5743 I bt_bluedroid: get_profile_interface gatt
,08-29 07:13:38.922  5743  5743 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
08-29 07:13:38.922  5743  5743 D BtGatt.AdvertiseManager: advertise manager created
,08-29 07:13:38.929  5743  5743 V BluetoothAdapterState: isTurningOff()=false
08-29 07:13:38.929  5743  5743 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:38.929  5743  5743 V BluetoothAdapterState: isBleTurningOn()=true
08-29 07:13:38.929  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 07:13:38.929  5743  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 07:13:38.930  5743  5818 I bt_bluedroid: enable
08-29 07:13:38.930  5743  5819 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 07:13:38.930  5743  5819 I bt_hci  : start_up
,08-29 07:13:38.937  5743  5819 I bt_vendor: alloc value 0xf3ef904d
,08-29 07:13:38.937  5743  5819 I bt_vendor: init
08-29 07:13:38.937  5743  5819 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 07:13:38.937  5743  5819 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 07:13:39.057  5743  5819 D bt_hci  : start_up starting async portion
,08-29 07:13:39.058  5743  5826 I bt_hci  : event_finish_startup
08-29 07:13:39.058  5743  5826 I bt_hci_h4: hal_open
08-29 07:13:39.058  5743  5826 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 07:13:39.050  5827  5827 W irq/448-msm_hs_: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 07:13:39.061  5743  5826 I bt_userial_vendor: device fd = 51 open
,08-29 07:13:39.075  5743  5826 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 07:13:39.078  5743  5826 D bt_hwcfg: Chipset BCM4358A3
,08-29 07:13:39.078  5743  5826 D bt_hwcfg: Target name = [BCM4358A3]
08-29 07:13:39.078  5743  5826 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 07:13:39.472  5743  5826 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-29 07:13:39.473  5743  5826 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 07:13:39.473  5743  5826 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 07:13:39.607  5743  5826 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 07:13:39.607  5743  5826 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 07:13:39.609  5743  5826 I bt_hwcfg: vendor lib fwcfg completed
08-29 07:13:39.609  5743  5826 I bt_vendor: firmware callback
08-29 07:13:39.609  5743  5826 I bt_hci  : firmware_config_callback
,08-29 07:13:39.618  5743  5829 I bt_btu  : btu_task pending for preload complete event
,08-29 07:13:39.618  5743  5829 I bt_btu_task: Bluetooth chip preload is complete
08-29 07:13:39.618  5743  5829 I bt_btu  : btu_task received preload complete event
,08-29 07:13:39.626  5743  5829 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 07:13:39.627  5743  5829 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 07:13:39.627  5743  5829 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 07:13:39.627  5743  5829 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-29 07:13:39.627  5743  5829 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 07:13:39.627  5743  5829 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 07:13:39.627  5743  5829 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 07:13:39.627  5743  5829 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 07:13:39.627  5743  5829 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 07:13:39.627  5743  5829 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 07:13:39.628  5743  5829 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 07:13:39.628  5743  5829 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 07:13:39.628  5743  5829 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 07:13:39.628  5743  5829 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 07:13:39.628  5743  5829 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 07:13:39.710  5743  5829 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e76c99
08-29 07:13:39.710  5743  5829 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e76c99 
,08-29 07:13:39.728  5743  5822 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 07:13:39.729  5743  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 07:13:39.730  5743  5822 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-29 07:13:39.732  5743  5822 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 07:13:39.735  5743  5822 D BluetoothAdapterProperties: Scan Mode:20
,08-29 07:13:39.736  5743  5822 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 07:13:39.736  5743  5822 D bt_hci  : do_postload posting postload work item
08-29 07:13:39.736  5743  5826 I bt_hci  : event_postload
08-29 07:13:39.736  5743  5826 I bt_vendor: sco_config_cb
08-29 07:13:39.736  5743  5826 I bt_hci  : sco_config_callback postload finished.
,08-29 07:13:39.740  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:39.743  5743  5822 D bt_bte_conf: Device ID record 1 : primary
,08-29 07:13:39.743  5743  5822 D bt_bte_conf:   vendorId            = 000f
08-29 07:13:39.743  5743  5822 D bt_bte_conf:   vendorIdSource      = 0001
08-29 07:13:39.743  5743  5822 D bt_bte_conf:   product             = 1200
08-29 07:13:39.743  5743  5822 D bt_bte_conf:   version             = 1436
,08-29 07:13:39.743  5743  5822 D bt_bte_conf:   clientExecutableURL = 
08-29 07:13:39.743  5743  5822 D bt_bte_conf:   serviceDescription  = 
08-29 07:13:39.743  5743  5822 D bt_bte_conf:   documentationURL    = 
08-29 07:13:39.744  5743  5822 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 07:13:39.744  5743  5819 D bt_stack_manager: event_start_up_stack finished
08-29 07:13:39.745  5743  5826 I bt_vendor: low_power_mode_cb
08-29 07:13:39.745  5743  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 07:13:39.745  5743  5818 D BluetoothAdapterProperties: Setting state to 15
08-29 07:13:39.745  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:39.745  5743  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 07:13:39.747  5743  5818 I BluetoothAdapterState: Entering BleOnState
,08-29 07:13:39.751  5743  5818 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 07:13:39.751  5743  5818 D BluetoothAdapterProperties: Setting state to 11
08-29 07:13:39.751  5743  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 07:13:39.760  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:39.762  5743  5743 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
,08-29 07:13:39.763  5743  5743 D HeadsetService: Received start request. Starting profile...
08-29 07:13:39.764  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:39.765  5743  5743 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 07:13:39.766  5743  5743 D HeadsetStateMachine: make
,08-29 07:13:39.773  5743  5818 I BluetoothAdapterState: Entering PendingCommandState
,08-29 07:13:39.780  5743  5743 D HeadsetStateMachine: max_hf_connections = 1
,08-29 07:13:39.780  5743  5743 I bt_bluedroid: get_profile_interface handsfree
08-29 07:13:39.780  5743  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 07:13:39.780  5743  5822 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,08-29 07:13:39.784  5743  5743 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
08-29 07:13:39.785  5743  5743 D A2dpService: Received start request. Starting profile...
08-29 07:13:39.785  5743  5743 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 07:13:39.786  5743  5743 I bt_bluedroid: get_profile_interface avrcp
,08-29 07:13:39.791  5743  5743 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 07:13:39.792  5743  5743 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 07:13:39.792  5743  5743 D A2dpStateMachine: make
,08-29 07:13:39.793  5743  5743 I bt_bluedroid: get_profile_interface a2dp
,08-29 07:13:39.793  5743  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 07:13:39.795  5743  5836 D A2dpStateMachine: Enter Disconnected: -2
08-29 07:13:39.795  5743  5743 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 07:13:39.796  5743  5743 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
08-29 07:13:39.797  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 07:13:39.798  5680  5680 D BluetoothInputDevice: Proxy object connected
08-29 07:13:39.799  5680  5680 D HidProfile: Bluetooth service connected
,08-29 07:13:39.800  5743  5743 D HidService: Received start request. Starting profile...
,08-29 07:13:39.800  5743  5743 I bt_bluedroid: get_profile_interface hidhost
08-29 07:13:39.800  5743  5822 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e582d9
08-29 07:13:39.800  5743  5743 D HidService: setHidService(): set to: null
08-29 07:13:39.801  5743  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 07:13:39.801  5743  5743 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 07:13:39.801  5743  5743 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
08-29 07:13:39.802  5743  5743 D HealthService: Received start request. Starting profile...
,08-29 07:13:39.803  5743  5743 I bt_bluedroid: get_profile_interface health
08-29 07:13:39.804  5743  5743 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 07:13:39.805  5743  5743 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
,08-29 07:13:39.806  5680  5680 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 07:13:39.806  5743  5743 D PanService: Received start request. Starting profile...
08-29 07:13:39.806  5743  5743 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 07:13:39.806  5743  5743 I bt_bluedroid: get_profile_interface pan
08-29 07:13:39.807  5680  5680 D PanProfile: Bluetooth service connected
08-29 07:13:39.807  5743  5822 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 07:13:39.809  5743  5743 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
,08-29 07:13:39.810  5743  5743 D BluetoothMapService: Received start request. Starting profile...
,08-29 07:13:39.810  5743  5743 D BluetoothMapService: start()
08-29 07:13:39.813  5680  5680 D BluetoothMap: Proxy object connected
08-29 07:13:39.813  5743  5743 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 07:13:39.814  5743  5743 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 07:13:39.814  5743  5743 D BluetoothMapAppObserver: createReceiver()
08-29 07:13:39.816  5743  5743 D BluetoothMapAppObserver: initObservers()
08-29 07:13:39.816  5743  5743 D BluetoothMapAppObserver: getEnabledAccountItems()
08-29 07:13:39.821  5743  5743 V SapService: SapBinder()
,08-29 07:13:39.822  5743  5743 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
,08-29 07:13:39.822  5680  5680 D MapProfile: Bluetooth service connected
08-29 07:13:39.823  5680  5680 D BluetoothMap: getConnectedDevices()
08-29 07:13:39.823  5743  5743 D SapService: Received start request. Starting profile...
08-29 07:13:39.823  5743  5743 V SapService: start()
08-29 07:13:39.824  5680  5680 D BluetoothMap: Bluetooth is Not enabled
,08-29 07:13:39.826  5743  5743 V BluetoothAdapterState: isTurningOff()=false
,08-29 07:13:39.826  5743  5743 V BluetoothAdapterState: isTurningOn()=true
08-29 07:13:39.826  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:39.826  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:39.826  5743  5743 V BluetoothAdapterState: isTurningOff()=false
08-29 07:13:39.826  5743  5743 V BluetoothAdapterState: isTurningOn()=true
08-29 07:13:39.826  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:39.826  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:39.826  5743  5834 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isTurningOff()=false
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isTurningOn()=true
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isTurningOff()=false
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isTurningOn()=true
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isTurningOff()=false
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isTurningOn()=true
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isTurningOff()=false
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isTurningOn()=true
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:39.827  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:39.828  5743  5743 V BluetoothAdapterState: isTurningOff()=false
08-29 07:13:39.829  5743  5743 V BluetoothAdapterState: isTurningOn()=true
08-29 07:13:39.829  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:39.829  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:39.829  5743  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 07:13:39.829  5743  5818 D BluetoothAdapterProperties: ScanMode =  20
08-29 07:13:39.829  5743  5818 D BluetoothAdapterProperties: State =  11
08-29 07:13:39.829  5743  5818 D BluetoothAdapterProperties: Setting state to 12
08-29 07:13:39.829  5743  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 07:13:39.830  5743  5818 I BluetoothAdapterState: Entering OnState
08-29 07:13:39.830  3237  3252 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 07:13:39.832  5680  5691 D BluetoothMap: onBluetoothStateChange: up=true
08-29 07:13:39.832  3613  3634 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:13:39.833  3237  3237 D BluetoothA2dp: Proxy object connected
08-29 07:13:39.833   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 07:13:39.833  3237  3801 D BluetoothMap: onBluetoothStateChange: up=true
08-29 07:13:39.833  5743  5822 D BluetoothAdapterProperties: Scan Mode:21
08-29 07:13:39.833  5743  5822 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 07:13:39.835  3237  3254 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 07:13:39.837  3237  3237 D BluetoothMap: Proxy object connected
08-29 07:13:39.837  3237  3237 D MapProfile: Bluetooth service connected
08-29 07:13:39.837  3237  3237 D BluetoothMap: getConnectedDevices()
08-29 07:13:39.837  5680  5690 D BluetoothPan: onBluetoothStateChange on: true
,08-29 07:13:39.837  3237  3801 D BluetoothPan: onBluetoothStateChange on: true
08-29 07:13:39.838  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:39.838  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:39.838  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:39.838  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:13:39.838  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:39.838  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:39.838  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:39.838  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:13:39.839   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 07:13:39.839   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 07:13:39.839   931   931 D BluetoothA2dp: Proxy object connected
08-29 07:13:39.840  5680  5691 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 07:13:39.840  3237  3237 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 07:13:39.840  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:13:39.840  3237  3237 D PanProfile: Bluetooth service connected
08-29 07:13:39.840  5743  5743 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 07:13:39.841  5743  5743 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 07:13:39.841   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:13:39.842  3237  3254 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 07:13:39.843  5743  5743 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:13:39.844  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:39.844  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:39.844  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:39.844  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:13:39.844  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:39.844  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:39.844  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:39.844  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:13:39.845  3237  3237 D BluetoothInputDevice: Proxy object connected
08-29 07:13:39.845  5680  5690 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 07:13:39.845  3237  3237 D HidProfile: Bluetooth service connected
08-29 07:13:39.845  3237  3252 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:13:39.846  5743  5743 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:13:39.847  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:13:39.847   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 07:13:39.849  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:39.851  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:39.851  5743  5743 D ObexServerSockets: Succeed to create listening sockets 
08-29 07:13:39.851  5680  5680 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 07:13:39.851  5743  5743 D ObexServerSockets0: startAccept()
08-29 07:13:39.851  5743  5743 D ObexServerSockets0: prepareForNewConnect()
,08-29 07:13:39.853  5743  5743 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-29 07:13:39.853  5743  5743 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 07:13:39.854  5743  5845 D ObexServerSockets0: Accepting socket connection...
08-29 07:13:39.854  5743  5743 D BluetoothMapService: onReceive
08-29 07:13:39.854  5743  5743 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 07:13:39.854  5743  5743 D BluetoothMapService: STATE_ON
,08-29 07:13:39.855  5743  5846 D ObexServerSockets0: Accepting socket connection...
,08-29 07:13:39.855  5680  5680 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 07:13:39.857  5743  5847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:13:39.858  5743  5847 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 07:13:39.858  5743  5847 D BluetoothSdpJni: SDP Create record success - handle: 1
08-29 07:13:39.861  5680  5680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 07:13:39.863  5680  5680 D BluetoothA2dp: Proxy object connected
,08-29 07:13:39.867  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 07:13:39.874  3237  3237 D BluetoothPbap: Proxy object connected
,08-29 07:13:39.874  3237  3237 D PbapServerProfile: Bluetooth service connected
,08-29 07:13:39.877  5680  5680 D DockEventReceiver: finishStartingService: stopping service
,08-29 07:13:39.878  5680  5680 D BluetoothPbap: Proxy object connected
,08-29 07:13:39.878  5680  5680 D PbapServerProfile: Bluetooth service connected
,08-29 07:13:39.879  5743  5743 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 07:13:39.879  5743  5743 D ObexServerSockets0: prepareForNewConnect()
08-29 07:13:39.881  5743  5851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:13:39.894  5743  5855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:13:39.895  5743  5855 I BtOppRfcommListener: Accept thread started.
,08-29 07:13:39.934  3613  3922 D BluetoothHeadset: Proxy object connected
,08-29 07:13:39.935   931   931 D BluetoothHeadset: Proxy object connected
08-29 07:13:39.935   931   931 D BluetoothHeadset: Proxy object connected
08-29 07:13:39.935   931   931 D BluetoothHeadset: Proxy object connected
08-29 07:13:39.935  3237  3254 D BluetoothHeadset: Proxy object connected
08-29 07:13:39.935  3237  3237 D HeadsetProfile: Bluetooth service connected
,08-29 07:13:39.939   931   948 D BluetoothHeadset: Proxy object connected
,08-29 07:13:39.942   931   948 D BluetoothHeadset: Proxy object connected
,08-29 07:13:39.945  3237  3801 D BluetoothHeadset: Proxy object connected
,08-29 07:13:39.945  3237  3237 D HeadsetProfile: Bluetooth service connected
,08-29 07:13:39.958  5680  5691 D BluetoothHeadset: Proxy object connected
,08-29 07:13:39.959  5680  5680 D HeadsetProfile: Bluetooth service connected
,08-29 07:13:41.858  5743  5818 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 07:13:41.858  5743  5818 D BluetoothAdapterProperties: Setting state to 13
08-29 07:13:41.858  5743  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 07:13:41.859  5743  5818 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 07:13:41.862  5743  5818 I BluetoothAdapterState: Entering PendingCommandState
08-29 07:13:41.864  5743  5822 D BluetoothAdapterProperties: Scan Mode:20
,08-29 07:13:41.867  5743  5743 D BluetoothMapService: onReceive
,08-29 07:13:41.867  5743  5743 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 07:13:41.867  5743  5743 D BluetoothMapService: STATE_TURNING_OFF
,08-29 07:13:41.867  5743  5743 D BluetoothMapService: MAP Service closeService in
08-29 07:13:41.868  5743  5743 D BluetoothMapMasInstance0: MAP Service shutdown
,08-29 07:13:41.868  5743  5743 D ObexServerSockets0: shutdown(block = true)
,08-29 07:13:41.868  5743  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 07:13:41.868  5743  5743 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 07:13:41.868  5743  5743 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 07:13:41.869  5743  5845 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 07:13:41.869  5743  5846 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 07:13:41.872  5743  5831 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 07:13:41.874  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:41.874  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:41.874  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:41.874  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:41.874  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:13:41.874  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:13:41.874  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:41.874  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:41.874  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:13:41.876  5743  5743 I BtOppRfcommListener: stopping Accept Thread
08-29 07:13:41.877  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:41.877  5743  5855 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 07:13:41.877  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:13:41.877  5743  5855 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 07:13:41.881  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 07:13:41.881  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:41.881  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:41.881  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:41.881  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:13:41.881  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:13:41.881  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:41.881  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:41.881  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:13:41.882  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:13:41.882  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:13:41.884  5743  5743 D HeadsetService: Received stop request...Stopping profile...
08-29 07:13:41.886  5680  5680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 07:13:41.887  3613  3653 D BluetoothHeadset: Proxy object disconnected
08-29 07:13:41.887  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:41.888  5743  5743 D A2dpService: Received stop request...Stopping profile...
08-29 07:13:41.889   931   931 D BluetoothHeadset: Proxy object disconnected
,08-29 07:13:41.889   931   931 D BluetoothHeadset: Proxy object disconnected
,08-29 07:13:41.889   931   931 D BluetoothHeadset: Proxy object disconnected
08-29 07:13:41.889  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:41.889  3237  3254 D BluetoothHeadset: Proxy object disconnected
08-29 07:13:41.890  5743  5836 D A2dpStateMachine: Exit Disconnected: -1
08-29 07:13:41.892  5680  5691 D BluetoothHeadset: Proxy object disconnected
08-29 07:13:41.893   931   931 D BluetoothA2dp: Proxy object disconnected
08-29 07:13:41.894  5743  5743 D HidService: Received stop request...Stopping profile...
08-29 07:13:41.894  5743  5743 D HidService: Stopping Bluetooth HidService
08-29 07:13:41.896  5743  5743 D HealthService: Received stop request...Stopping profile...
08-29 07:13:41.896  3237  3237 D HeadsetProfile: Bluetooth service disconnected
08-29 07:13:41.896  3237  3237 D BluetoothA2dp: Proxy object disconnected
08-29 07:13:41.896  3237  3237 D BluetoothInputDevice: Proxy object disconnected
08-29 07:13:41.897  3237  3237 D HidProfile: Bluetooth service disconnected
,08-29 07:13:41.897  5680  5680 D HeadsetProfile: Bluetooth service disconnected
08-29 07:13:41.897  5743  5743 D PanService: Received stop request...Stopping profile...
08-29 07:13:41.899  3237  3237 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 07:13:41.899  3237  3237 D PanProfile: Bluetooth service disconnected
,08-29 07:13:41.900  5743  5743 D BluetoothMapService: Received stop request...Stopping profile...
08-29 07:13:41.900  5743  5743 D BluetoothMapService: stop()
,08-29 07:13:41.901  5743  5743 D BluetoothMapAppObserver: deinitObservers()
08-29 07:13:41.901  5743  5743 D BluetoothMapAppObserver: removeReceiver()
08-29 07:13:41.902  3237  3237 D BluetoothMap: Proxy object disconnected
08-29 07:13:41.903  3237  3237 D MapProfile: Bluetooth service disconnected
08-29 07:13:41.904  5743  5743 D SapService: Received stop request...Stopping profile...
08-29 07:13:41.904  5743  5743 V SapService: stop()
08-29 07:13:41.906  5743  5743 V BluetoothAdapterState: isTurningOff()=true
08-29 07:13:41.906  5743  5743 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:41.906  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 07:13:41.906  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:41.907  5743  5743 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 07:13:41.907  5743  5743 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 07:13:41.908  5743  5829 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:13:41.908  5743  5743 V BluetoothAdapterState: isTurningOff()=true
08-29 07:13:41.908  5743  5829 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:13:41.908  5743  5743 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:41.908  5743  5829 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:13:41.908  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:41.908  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:41.908  5743  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 07:13:41.908  5743  5822 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-29 07:13:41.908  5680  5680 D DockEventReceiver: finishStartingService: stopping service
,08-29 07:13:41.909  5680  5680 D BluetoothA2dp: Proxy object disconnected
,08-29 07:13:41.909  5680  5680 D BluetoothInputDevice: Proxy object disconnected
08-29 07:13:41.909  5680  5680 D HidProfile: Bluetooth service disconnected
08-29 07:13:41.909  5680  5680 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 07:13:41.910  5680  5680 D PanProfile: Bluetooth service disconnected
08-29 07:13:41.910  5680  5680 D BluetoothMap: Proxy object disconnected
08-29 07:13:41.910  5743  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 07:13:41.910  5680  5680 D MapProfile: Bluetooth service disconnected
08-29 07:13:41.910  5743  5829 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:13:41.910  5743  5829 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 07:13:41.910  5743  5829 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 07:13:41.911  5743  5829 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 07:13:41.911  5743  5743 V BluetoothAdapterState: isTurningOff()=true
08-29 07:13:41.911  5743  5829 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 07:13:41.911  5743  5743 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:41.911  5743  5829 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 07:13:41.911  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:41.911  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:41.911  5743  5743 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 07:13:41.911  5743  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 07:13:41.911  5743  5743 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 07:13:41.912  5743  5743 V BluetoothAdapterState: isTurningOff()=true
08-29 07:13:41.912  5743  5743 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:41.912  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:41.912  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:41.912  5743  5743 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 07:13:41.912  5743  5822 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 07:13:41.913  5743  5743 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 07:13:41.913  5743  5743 V BluetoothAdapterState: isTurningOff()=true
08-29 07:13:41.913  5743  5743 V BluetoothAdapterState: isTurningOn()=false
,08-29 07:13:41.913  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:41.913  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:41.914  5743  5743 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 07:13:41.914  5743  5743 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 07:13:41.915  5743  5743 D BluetoothMapService: MAP Service closeService in
08-29 07:13:41.915  5743  5743 V BluetoothAdapterState: isTurningOff()=true
08-29 07:13:41.915  5743  5743 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:41.915  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:41.915  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:41.916  5743  5743 D BluetoothMapService: cleanup()
08-29 07:13:41.916  5743  5743 D BluetoothMapService: MAP Service closeService in
08-29 07:13:41.916  5743  5743 V BluetoothAdapterState: isTurningOff()=true
08-29 07:13:41.916  5743  5743 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:41.916  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 07:13:41.916  5743  5743 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:41.916  5743  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 07:13:41.916  5743  5818 D BluetoothAdapterProperties: Setting state to 15
08-29 07:13:41.916  5743  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 07:13:41.917  3237  3254 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 07:13:41.918  3237  3237 D BluetoothPbap: Proxy object disconnected
08-29 07:13:41.918  3237  3237 D PbapServerProfile: Bluetooth service disconnected
08-29 07:13:41.918  5680  5690 D BluetoothMap: onBluetoothStateChange: up=false
08-29 07:13:41.919  3613  3634 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:13:41.919   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:13:41.919  3237  3254 D BluetoothMap: onBluetoothStateChange: up=false
08-29 07:13:41.920  3237  3252 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 07:13:41.921  5680  5691 D BluetoothPan: onBluetoothStateChange on: false
08-29 07:13:41.921  3237  3801 D BluetoothPan: onBluetoothStateChange on: false
08-29 07:13:41.922   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 07:13:41.922  5743  5818 I BluetoothAdapterState: Entering BleOnState
08-29 07:13:41.923  5680  5680 D BluetoothPbap: Proxy object disconnected
,08-29 07:13:41.923  5680  5680 D PbapServerProfile: Bluetooth service disconnected
,08-29 07:13:41.924  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 07:13:41.924   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:13:41.925  5680  5690 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 07:13:41.926   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:13:41.926  3237  3254 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 07:13:41.927  5680  5691 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 07:13:41.927  5680  5858 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:13:41.928  5680  5690 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 07:13:41.928  3237  3252 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:13:41.929  5743  5818 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 07:13:41.929  5743  5818 D BluetoothAdapterProperties: Setting state to 16
08-29 07:13:41.929  5743  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 07:13:41.930  5743  5818 D BluetoothAdapterProperties: onBleDisable
08-29 07:13:41.930  5743  5818 I BluetoothAdapterState: Entering PendingCommandState
08-29 07:13:41.930  5743  5819 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 07:13:41.932  5743  5829 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 07:13:41.932  5743  5829 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 07:13:41.933  5743  5822 D BluetoothAdapterProperties: Scan Mode:20
08-29 07:13:41.934  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:41.937  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:41.938  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:41.938  5680  5680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 07:13:41.940  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:41.942  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 07:13:41.945  5680  5680 D DockEventReceiver: finishStartingService: stopping service
,08-29 07:13:42.147  5743  5822 I bt_hci  : shut_down
,08-29 07:13:42.152  5743  5826 D bt_hwcfg: hw_epilog_process
,08-29 07:13:42.152  5743  5826 I bt_vendor: low_power_mode_cb
,08-29 07:13:42.154  5743  5826 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 07:13:42.154  5743  5826 I bt_vendor: epilog_cb
08-29 07:13:42.155  5743  5826 I bt_hci  : epilog_finished_callback
,08-29 07:13:42.158  5743  5822 I bt_hci_h4: hal_close
,08-29 07:13:42.158  5743  5822 I bt_userial_vendor: device fd = 51 close
,08-29 07:13:42.268  5743  5819 D bt_stack_manager: event_shut_down_stack finished.
,08-29 07:13:42.268  5743  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 07:13:42.270  5743  5818 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 07:13:42.271  5743  5743 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 07:13:42.271  5743  5743 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 07:13:42.271  5743  5743 D BtGatt.GattService: stop()
08-29 07:13:42.272  5743  5743 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 07:13:42.274  5743  5743 V BluetoothAdapterState: isTurningOff()=false
,08-29 07:13:42.274  5743  5743 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:42.274  5743  5743 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:42.274  5743  5743 V BluetoothAdapterState: isBleTurningOff()=true
08-29 07:13:42.274  5743  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 07:13:42.275  5743  5818 D BluetoothAdapterProperties: Setting state to 10
08-29 07:13:42.275  5743  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 07:13:42.276  5743  5818 I BluetoothAdapterState: Entering OffState
08-29 07:13:42.277   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 07:13:42.282  5743  5743 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 07:13:42.283  5743  5743 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 07:13:42.283  5743  5743 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 07:13:42.284  5743  5819 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 07:13:42.285  5743  5819 D bt_stack_manager: event_clean_up_stack finished.
,08-29 07:13:42.286  5743  5743 I art     : System.exit called, status: 0
08-29 07:13:42.286  5743  5743 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 07:13:42.308   931  3628 I ActivityManager: Process com.android.bluetooth (pid 5743) has died
,08-29 07:13:44.854  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 07:13:44.855  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:13:45.240   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:13:46.241   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:13:47.242   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:13:47.861  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 07:13:47.861  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd6c4c8 added. We now have 6 listener(s)
,08-29 07:13:47.861  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:13:47.865  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:47.865  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@216e961 added. We now have 7 listener(s)
,08-29 07:13:47.865  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:13:47.868  5627  5674 I System.out: IsBluetoothEnabled
,08-29 07:13:47.875  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:47.899   931   948 I ActivityManager: Start proc 5864:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 07:13:47.976  5864  5864 D AdapterServiceConfig: Adding HeadsetService
,08-29 07:13:47.976  5864  5864 D AdapterServiceConfig: Adding A2dpService
08-29 07:13:47.976  5864  5864 D AdapterServiceConfig: Adding HidService
08-29 07:13:47.976  5864  5864 D AdapterServiceConfig: Adding HealthService
08-29 07:13:47.976  5864  5864 D AdapterServiceConfig: Adding PanService
08-29 07:13:47.977  5864  5864 D AdapterServiceConfig: Adding GattService
08-29 07:13:47.977  5864  5864 D AdapterServiceConfig: Adding BluetoothMapService
08-29 07:13:47.977  5864  5864 D AdapterServiceConfig: Adding SapService
,08-29 07:13:47.987   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d4b483b:true
,08-29 07:13:47.987  5864  5864 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 07:13:47.990  5864  5864 I bt_bluedroid: init
,08-29 07:13:47.990  5864  5876 I BluetoothAdapterState: Entering OffState
,08-29 07:13:47.992  5864  5877 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 07:13:47.992  5864  5877 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 07:13:47.992  5864  5877 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 07:13:47.992  5864  5877 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 07:13:47.993  5864  5864 I bt_bluedroid: get_profile_interface socket
,08-29 07:13:47.995  5864  5880 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 07:13:47.995  5864  5864 I bt_bluedroid: get_profile_interface sdp
08-29 07:13:47.996  5864  5880 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 07:13:47.998  5864  5874 I bt_bluedroid: config_hci_snoop_log
,08-29 07:13:48.000   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 07:13:48.004  5864  5876 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 07:13:48.004  5864  5876 D BluetoothAdapterProperties: Setting state to 14
08-29 07:13:48.004  5864  5876 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-29 07:13:48.005  5864  5876 D BluetoothBondStateMachine: make
,08-29 07:13:48.007  5864  5881 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 07:13:48.009  5864  5876 I BluetoothAdapterState: Entering PendingCommandState
,08-29 07:13:48.010  5864  5864 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 07:13:48.012  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
08-29 07:13:48.013  5864  5864 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 07:13:48.014  5864  5864 D BtGatt.GattService: Received start request. Starting profile...
08-29 07:13:48.014  5864  5864 D BtGatt.GattService: start()
08-29 07:13:48.014  5864  5864 I bt_bluedroid: get_profile_interface gatt
08-29 07:13:48.015  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
,08-29 07:13:48.015  5864  5864 D BtGatt.AdvertiseManager: advertise manager created
,08-29 07:13:48.020  5864  5864 V BluetoothAdapterState: isTurningOff()=false
,08-29 07:13:48.021  5864  5864 V BluetoothAdapterState: isTurningOn()=false
08-29 07:13:48.021  5864  5864 V BluetoothAdapterState: isBleTurningOn()=true
08-29 07:13:48.021  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:48.021  5864  5876 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 07:13:48.021  5864  5876 I bt_bluedroid: enable
08-29 07:13:48.021  5864  5877 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 07:13:48.022  5864  5877 I bt_hci  : start_up
,08-29 07:13:48.027  5864  5877 I bt_vendor: alloc value 0xf3f4704d
,08-29 07:13:48.027  5864  5877 I bt_vendor: init
08-29 07:13:48.027  5864  5877 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 07:13:48.027  5864  5877 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 07:13:48.147  5864  5877 D bt_hci  : start_up starting async portion
,08-29 07:13:48.148  5864  5884 I bt_hci  : event_finish_startup
08-29 07:13:48.148  5864  5884 I bt_hci_h4: hal_open
08-29 07:13:48.148  5864  5884 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 07:13:48.140  5885  5885 W irq/448-msm_hs_: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 07:13:48.151  5864  5884 I bt_userial_vendor: device fd = 51 open
,08-29 07:13:48.165  5864  5884 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 07:13:48.167  5864  5884 D bt_hwcfg: Chipset BCM4358A3
,08-29 07:13:48.168  5864  5884 D bt_hwcfg: Target name = [BCM4358A3]
08-29 07:13:48.168  5864  5884 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 07:13:48.243   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:13:48.568  5864  5884 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 07:13:48.568  5864  5884 D bt_hwcfg: Settlement delay -- 100 ms
08-29 07:13:48.568  5864  5884 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 07:13:48.702  5864  5884 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 07:13:48.702  5864  5884 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
08-29 07:13:48.704  5864  5884 I bt_hwcfg: vendor lib fwcfg completed
08-29 07:13:48.704  5864  5884 I bt_vendor: firmware callback
,08-29 07:13:48.704  5864  5884 I bt_hci  : firmware_config_callback
,08-29 07:13:48.712  5864  5887 I bt_btu  : btu_task pending for preload complete event
,08-29 07:13:48.712  5864  5887 I bt_btu_task: Bluetooth chip preload is complete
08-29 07:13:48.713  5864  5887 I bt_btu  : btu_task received preload complete event
,08-29 07:13:48.719  5864  5887 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 07:13:48.719  5864  5887 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 07:13:48.719  5864  5887 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 07:13:48.719  5864  5887 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 07:13:48.719  5864  5887 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 07:13:48.719  5864  5887 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 07:13:48.719  5864  5887 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 07:13:48.720  5864  5887 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 07:13:48.720  5864  5887 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 07:13:48.720  5864  5887 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 07:13:48.720  5864  5887 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 07:13:48.720  5864  5887 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 07:13:48.720  5864  5887 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 07:13:48.720  5864  5887 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 07:13:48.720  5864  5887 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 07:13:48.799  5864  5887 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ec4c99
,08-29 07:13:48.799  5864  5887 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ec4c99 
,08-29 07:13:48.820  5864  5880 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 07:13:48.822  5864  5880 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 07:13:48.822  5864  5880 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 07:13:48.824  5864  5880 D BluetoothAdapterProperties: Name is: Nexus 6P
08-29 07:13:48.827  5864  5880 D BluetoothAdapterProperties: Scan Mode:20
08-29 07:13:48.827  5864  5880 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 07:13:48.827  5864  5880 D bt_hci  : do_postload posting postload work item
,08-29 07:13:48.827  5864  5884 I bt_hci  : event_postload
08-29 07:13:48.827  5864  5884 I bt_vendor: sco_config_cb
08-29 07:13:48.828  5864  5884 I bt_hci  : sco_config_callback postload finished.
08-29 07:13:48.830  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:48.832  5864  5880 D bt_bte_conf: Device ID record 1 : primary
08-29 07:13:48.832  5864  5880 D bt_bte_conf:   vendorId            = 000f
08-29 07:13:48.832  5864  5880 D bt_bte_conf:   vendorIdSource      = 0001
08-29 07:13:48.832  5864  5880 D bt_bte_conf:   product             = 1200
08-29 07:13:48.832  5864  5880 D bt_bte_conf:   version             = 1436
08-29 07:13:48.832  5864  5880 D bt_bte_conf:   clientExecutableURL = 
08-29 07:13:48.833  5864  5880 D bt_bte_conf:   serviceDescription  = 
,08-29 07:13:48.833  5864  5880 D bt_bte_conf:   documentationURL    = 
08-29 07:13:48.833  5864  5880 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 07:13:48.834  5864  5877 D bt_stack_manager: event_start_up_stack finished
08-29 07:13:48.834  5864  5876 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 07:13:48.835  5864  5876 D BluetoothAdapterProperties: Setting state to 15
08-29 07:13:48.835  5864  5876 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 07:13:48.836  5864  5884 I bt_vendor: low_power_mode_cb
08-29 07:13:48.836  5864  5876 I BluetoothAdapterState: Entering BleOnState
08-29 07:13:48.840  5864  5876 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 07:13:48.841  5864  5876 D BluetoothAdapterProperties: Setting state to 11
08-29 07:13:48.841  5864  5876 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 07:13:48.846  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
,08-29 07:13:48.847  5864  5864 D HeadsetService: Received start request. Starting profile...
08-29 07:13:48.849  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:48.850  5864  5864 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 07:13:48.850  5864  5864 D HeadsetStateMachine: make
,08-29 07:13:48.859  5864  5876 I BluetoothAdapterState: Entering PendingCommandState
,08-29 07:13:48.861  5864  5864 D HeadsetStateMachine: max_hf_connections = 1
,08-29 07:13:48.861  5864  5864 I bt_bluedroid: get_profile_interface handsfree
08-29 07:13:48.862  5864  5880 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-29 07:13:48.862  5864  5880 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 07:13:48.866  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
,08-29 07:13:48.866  5864  5864 D A2dpService: Received start request. Starting profile...
,08-29 07:13:48.867  5864  5864 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 07:13:48.867  5864  5864 I bt_bluedroid: get_profile_interface avrcp
,08-29 07:13:48.873  5864  5864 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 07:13:48.873  5864  5864 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-29 07:13:48.873  5864  5864 D A2dpStateMachine: make
08-29 07:13:48.874  5864  5864 I bt_bluedroid: get_profile_interface a2dp
,08-29 07:13:48.875  5864  5880 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 07:13:48.876  5864  5896 D A2dpStateMachine: Enter Disconnected: -2
08-29 07:13:48.878  5864  5864 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 07:13:48.879  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
08-29 07:13:48.879  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 07:13:48.879  5864  5864 D HidService: Received start request. Starting profile...
,08-29 07:13:48.879  5864  5864 I bt_bluedroid: get_profile_interface hidhost
08-29 07:13:48.880  5864  5864 D HidService: setHidService(): set to: null
08-29 07:13:48.880  5864  5880 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ea62d9
08-29 07:13:48.880  5864  5880 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 07:13:48.880  5864  5864 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 07:13:48.881  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
08-29 07:13:48.881  5864  5864 D HealthService: Received start request. Starting profile...
08-29 07:13:48.882  5864  5864 I bt_bluedroid: get_profile_interface health
,08-29 07:13:48.883  5864  5864 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 07:13:48.884  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
,08-29 07:13:48.885  5864  5864 D PanService: Received start request. Starting profile...
,08-29 07:13:48.885  5864  5864 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 07:13:48.885  5864  5864 I bt_bluedroid: get_profile_interface pan
08-29 07:13:48.885  5864  5880 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 07:13:48.887  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
,08-29 07:13:48.888  5864  5864 D BluetoothMapService: Received start request. Starting profile...
08-29 07:13:48.888  5864  5864 D BluetoothMapService: start()
,08-29 07:13:48.890  5864  5864 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 07:13:48.891  5864  5864 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 07:13:48.891  5864  5864 D BluetoothMapAppObserver: createReceiver()
08-29 07:13:48.892  5864  5864 D BluetoothMapAppObserver: initObservers()
08-29 07:13:48.892  5864  5864 D BluetoothMapAppObserver: getEnabledAccountItems()
08-29 07:13:48.900  5864  5864 V SapService: SapBinder()
08-29 07:13:48.900  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
08-29 07:13:48.900  5864  5864 D SapService: Received start request. Starting profile...
08-29 07:13:48.900  5864  5864 V SapService: start()
,08-29 07:13:48.902  5864  5864 V BluetoothAdapterState: isTurningOff()=false
08-29 07:13:48.902  5864  5864 V BluetoothAdapterState: isTurningOn()=true
08-29 07:13:48.902  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:48.902  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 07:13:48.902  5864  5864 V BluetoothAdapterState: isTurningOff()=false
08-29 07:13:48.902  5864  5864 V BluetoothAdapterState: isTurningOn()=true
,08-29 07:13:48.903  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:48.903  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:48.903  5864  5864 V BluetoothAdapterState: isTurningOff()=false
08-29 07:13:48.903  5864  5894 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 07:13:48.903  5864  5864 V BluetoothAdapterState: isTurningOn()=true
08-29 07:13:48.903  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:48.903  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:48.903  5864  5864 V BluetoothAdapterState: isTurningOff()=false
08-29 07:13:48.903  5864  5864 V BluetoothAdapterState: isTurningOn()=true
08-29 07:13:48.903  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:48.904  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:48.904  5864  5864 V BluetoothAdapterState: isTurningOff()=false
08-29 07:13:48.904  5864  5864 V BluetoothAdapterState: isTurningOn()=true
08-29 07:13:48.904  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:48.904  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:48.904  5864  5864 V BluetoothAdapterState: isTurningOff()=false
08-29 07:13:48.904  5864  5864 V BluetoothAdapterState: isTurningOn()=true
08-29 07:13:48.904  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:48.904  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:48.905  5864  5864 V BluetoothAdapterState: isTurningOff()=false
08-29 07:13:48.905  5864  5864 V BluetoothAdapterState: isTurningOn()=true
08-29 07:13:48.905  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:13:48.905  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:13:48.905  5864  5876 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-29 07:13:48.905  5864  5876 D BluetoothAdapterProperties: ScanMode =  20
08-29 07:13:48.905  5864  5876 D BluetoothAdapterProperties: State =  11
08-29 07:13:48.906  5864  5876 D BluetoothAdapterProperties: Setting state to 12
08-29 07:13:48.906  5864  5876 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 07:13:48.906  5864  5876 I BluetoothAdapterState: Entering OnState
08-29 07:13:48.906  3237  3254 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 07:13:48.908  5864  5880 D BluetoothAdapterProperties: Scan Mode:21
08-29 07:13:48.909  5680  5858 D BluetoothMap: onBluetoothStateChange: up=true
08-29 07:13:48.909  5864  5880 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 07:13:48.910  3237  3237 D BluetoothA2dp: Proxy object connected
08-29 07:13:48.911  3613  3634 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 07:13:48.912   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 07:13:48.912  3237  3801 D BluetoothMap: onBluetoothStateChange: up=true
08-29 07:13:48.914  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:48.914  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:48.914  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:48.914  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:13:48.914  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:48.914  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:48.914  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:48.914  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:13:48.914  3237  3237 D BluetoothMap: Proxy object connected
08-29 07:13:48.914  3237  3252 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 07:13:48.914  3237  3237 D MapProfile: Bluetooth service connected
08-29 07:13:48.914  3237  3237 D BluetoothMap: getConnectedDevices()
08-29 07:13:48.915  5680  5691 D BluetoothPan: onBluetoothStateChange on: true
08-29 07:13:48.916  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:13:48.917  3237  3801 D BluetoothPan: onBluetoothStateChange on: true
08-29 07:13:48.918  5864  5864 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 07:13:48.918   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 07:13:48.919  3237  3237 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 07:13:48.919  3237  3237 D PanProfile: Bluetooth service connected
08-29 07:13:48.919  5864  5864 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 07:13:48.919   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:13:48.919   931   931 D BluetoothA2dp: Proxy object connected
08-29 07:13:48.919  5680  5690 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 07:13:48.919  5680  5680 D BluetoothMap: Proxy object connected
08-29 07:13:48.919  5680  5680 D MapProfile: Bluetooth service connected
08-29 07:13:48.920  5680  5680 D BluetoothMap: getConnectedDevices()
,08-29 07:13:48.920  5864  5864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:13:48.921   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:13:48.921  3237  3252 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 07:13:48.922  5864  5864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:13:48.923  5680  5691 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 07:13:48.923  5864  5864 D ObexServerSockets: Succeed to create listening sockets 
08-29 07:13:48.923  5864  5864 D ObexServerSockets0: startAccept()
08-29 07:13:48.923  5864  5864 D ObexServerSockets0: prepareForNewConnect()
08-29 07:13:48.924  5680  5858 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:13:48.925  5680  5690 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 07:13:48.925  5864  5864 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-29 07:13:48.925  5864  5864 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 07:13:48.926  5864  5902 D ObexServerSockets0: Accepting socket connection...
08-29 07:13:48.926  5864  5903 D ObexServerSockets0: Accepting socket connection...
08-29 07:13:48.927  3237  3237 D BluetoothInputDevice: Proxy object connected
08-29 07:13:48.927  3237  3237 D HidProfile: Bluetooth service connected
08-29 07:13:48.927  3237  3254 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:13:48.928  5680  5680 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 07:13:48.928  5680  5680 D PanProfile: Bluetooth service connected
08-29 07:13:48.928  5680  5680 D BluetoothA2dp: Proxy object connected
08-29 07:13:48.929   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 07:13:48.930  5864  5864 D BluetoothMapService: onReceive
08-29 07:13:48.930  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:48.930  5864  5864 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 07:13:48.930  5864  5864 D BluetoothMapService: STATE_ON
08-29 07:13:48.931  5680  5680 D BluetoothInputDevice: Proxy object connected
08-29 07:13:48.931  5680  5680 D HidProfile: Bluetooth service connected
08-29 07:13:48.932  5864  5904 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:13:48.933  5864  5904 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 07:13:48.933  5864  5904 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 07:13:48.936  5680  5680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 07:13:48.942  5680  5680 D DockEventReceiver: finishStartingService: stopping service
08-29 07:13:48.942  3701  3701 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 07:13:48.949  5680  5680 D BluetoothPbap: Proxy object connected
,08-29 07:13:48.949  5680  5680 D PbapServerProfile: Bluetooth service connected
,08-29 07:13:48.954  5864  5864 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 07:13:48.954  5864  5864 D ObexServerSockets0: prepareForNewConnect()
,08-29 07:13:48.956  3237  3237 D BluetoothPbap: Proxy object connected
08-29 07:13:48.956  3237  3237 D PbapServerProfile: Bluetooth service connected
,08-29 07:13:48.959  5864  5908 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:13:48.972  5864  5912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:13:48.973  5864  5912 I BtOppRfcommListener: Accept thread started.
,08-29 07:13:49.013  3613  3922 D BluetoothHeadset: Proxy object connected
,08-29 07:13:49.014   931   931 D BluetoothHeadset: Proxy object connected
08-29 07:13:49.014   931   931 D BluetoothHeadset: Proxy object connected
08-29 07:13:49.014   931   931 D BluetoothHeadset: Proxy object connected
08-29 07:13:49.014  3237  3252 D BluetoothHeadset: Proxy object connected
08-29 07:13:49.014  3237  3237 D HeadsetProfile: Bluetooth service connected
08-29 07:13:49.015  5680  5858 D BluetoothHeadset: Proxy object connected
08-29 07:13:49.016  5680  5680 D HeadsetProfile: Bluetooth service connected
,08-29 07:13:49.019   931   948 D BluetoothHeadset: Proxy object connected
,08-29 07:13:49.021   931   948 D BluetoothHeadset: Proxy object connected
,08-29 07:13:49.025  5680  5691 D BluetoothHeadset: Proxy object connected
,08-29 07:13:49.025  5680  5680 D HeadsetProfile: Bluetooth service connected
,08-29 07:13:49.028  3237  3801 D BluetoothHeadset: Proxy object connected
08-29 07:13:49.028  3237  3237 D HeadsetProfile: Bluetooth service connected
,08-29 07:13:49.244   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:13:49.890  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:49.890  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:49.890  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:49.890  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:13:49.890  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:49.890  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:49.890  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:49.890  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:13:49.895  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:13:49.897  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:49.898  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e31c86 added. We now have 8 listener(s)
08-29 07:13:49.898  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:13:49.901   931   942 D WifiService: setWifiEnabled: false pid=5627, uid=10077
,08-29 07:13:49.902   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 07:13:49.908  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:49.908   931  3309 D WifiService: setWifiEnabled: true pid=5627, uid=10077
08-29 07:13:49.908   931  3309 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 07:13:49.913   508   925 D SoftapController: Softap fwReload - Ok
,08-29 07:13:49.917   508   925 D CommandListener: Setting iface cfg
,08-29 07:13:49.917   508   925 D CommandListener: Trying to bring down wlan0
,08-29 07:13:49.918   508   925 D CommandListener: Clearing all IP addresses on wlan0
08-29 07:13:49.921   931  3054 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 07:13:50.245   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 07:13:50.530   931  3054 D wifi    : set interface wlan0 flags (UP)
,08-29 07:13:50.530   931  3054 I WifiHAL : Initializing wifi
08-29 07:13:50.531   931  3054 I WifiHAL : Creating socket
,08-29 07:13:50.536   931  3054 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-29 07:13:50.536   931  3054 D wifi    : Did set static halHandle = 0x7f8a387080
08-29 07:13:50.537   931  3054 D wifi    : halHandle = 0x7f8a387080, mVM = 0x7fa62cd140, mCls = 0x187a
08-29 07:13:50.537   931  3054 D wifi    : array field set
08-29 07:13:50.537   931  3054 I WifiNative-HAL: interface[0] = wlan0
08-29 07:13:50.538   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 07:13:50.539   931  5917 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547779801216
08-29 07:13:50.539   931  5917 D wifi    : waitForHalEvents called, vm = 0x7fa62cd140, obj = 0x187a, env = 0x7f8ad190c0
,08-29 07:13:50.585  5918  5918 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 07:13:50.605  5918  5918 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 07:13:50.614  5918  5918 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 07:13:50.614  5918  5918 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 07:13:50.641   931  3054 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 07:13:50.648  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:50.655   931  3054 D WifiConfigStore: Loading config and enabling all networks 
,08-29 07:13:50.658  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:50.658  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:50.658  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:50.658  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:50.658  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:50.658  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:50.658  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:50.658  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:13:50.660  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:13:50.662   931  3054 D WifiConfigStore: loaded 0 passpoint configs
,08-29 07:13:50.662   931  3054 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 07:13:50.663   931  3054 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 07:13:50.665   931  3054 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 07:13:50.666   931  3054 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 07:13:50.666   931  3054 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 07:13:50.669   931  3054 D WifiNative-HAL: Setting external_sim to 1
,08-29 07:13:50.669  4312  4312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 07:13:50.670   931  3054 D wifi    : setting dfs flag to true, 0x7f8a7ac260
08-29 07:13:50.670   931  3054 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 07:13:50.671   931  3054 D wifi    : setting scan oui 0x7f8a7ac260
08-29 07:13:50.671   931  3054 D WifiHAL : Sending mac address OUI
,08-29 07:13:50.685   931  3054 E native  : do suspend true
,08-29 07:13:50.691   931   931 D RttService: SCAN_AVAILABLE : 3
,08-29 07:13:50.691   931  3054 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 07:13:50.691   508   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 07:13:50.691   931  3164 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 07:13:50.692   508   925 D CommandListener: Setting iface cfg
,08-29 07:13:50.697   931  3053 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '75 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 75 Failed to set address (No such device)'
08-29 07:13:50.697   931  3053 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 07:13:50.699   931  3053 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 07:13:50.704   931  3053 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 07:13:50.724   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=195821 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=20 mControllerEnergyUsed=76 }
,08-29 07:13:50.924  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:13:50.924  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:50.924  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:50.924  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:50.924  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:50.924  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:50.924  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:50.924  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:13:50.929  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:13:50.936  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 07:13:50.937  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 07:13:50.941  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ba1a1c Bundle[{}]
,08-29 07:13:50.942  5627  5674 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 07:13:50.942  5627  5674 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 07:13:50.943  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 07:13:50.944  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 07:13:50.945  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 07:13:50.946  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 07:13:50.954  5627  5674 I System.out: Running OutgoingSocketThread
,08-29 07:13:50.956  5627  5920 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 151)
,08-29 07:13:50.957  5627  5920 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48165
,08-29 07:13:50.957  5627  5920 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 07:13:51.957  5627  5674 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 152)
,08-29 07:13:51.957  5627  5674 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 152)
08-29 07:13:51.962  5627  5674 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 157)
08-29 07:13:51.964  5627  5674 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 07:13:51.964  5627  5674 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,08-29 07:13:51.971  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 07:13:51.972  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9082947 added. We now have 2 listener(s)
08-29 07:13:51.975  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 07:13:51.975  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:13:51.975  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:13:51.975  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:51.975  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f76574 added. We now have 9 listener(s)
08-29 07:13:51.976  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:13:51.976  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 07:13:51.980  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:13:51.984  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:13:51.984  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:51.984  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:51.984  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:51.984  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:51.984  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:51.984  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:51.984  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:13:51.986  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:13:51.986  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:13:51.986  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 07:13:51.986  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc47b12 added. We now have 3 listener(s)
08-29 07:13:51.987  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:51.988  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 07:13:51.988  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 07:13:51.988  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:13:51.989  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:51.989  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61412e3 added. We now have 10 listener(s)
,08-29 07:13:51.989  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:13:51.989  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:51.989  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 07:13:51.989  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:51.989  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:51.989  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 07:13:51.989  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:51.989  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:13:51.990  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:13:51.990  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9082947 removed from the list
08-29 07:13:51.990  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 07:13:51.990  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f76574 removed from the list
08-29 07:13:51.990  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:51.990  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:51.991  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:13:51.991  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:51.992  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:51.992  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:51.993  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 07:13:51.993  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f76574 not in the list
08-29 07:13:51.993  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:51.993  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:13:51.995  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:51.995  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:51.995  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:51.995  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61412e3 removed from the list
08-29 07:13:51.995  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:51.995  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:51.995  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:13:51.995  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:13:51.995  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc47b12 removed from the list
08-29 07:13:51.996  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:13:51.996  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df64e0 added. We now have 2 listener(s)
08-29 07:13:51.998  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:13:51.998  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:13:51.999  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 07:13:51.999  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:51.999  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1a6399 added. We now have 9 listener(s)
08-29 07:13:51.999  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:13:52.000  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 07:13:52.004  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:13:52.006  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:13:52.006  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:52.006  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:52.006  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:52.006  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:52.006  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:52.006  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:52.006  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:13:52.008  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:13:52.008  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:13:52.008  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:13:52.008  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6afa3f added. We now have 3 listener(s)
08-29 07:13:52.009  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:52.009  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:13:52.010  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:13:52.010  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 07:13:52.010  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:52.010  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@785ef0c added. We now have 10 listener(s)
08-29 07:13:52.010  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:13:52.010  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:13:52.010  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:13:52.010  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:52.010  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:13:52.010  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:13:52.010  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:13:52.014  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 07:13:52.014  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 07:13:52.017  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 07:13:52.017  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 07:13:52.018  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 07:13:52.020  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 07:13:52.020  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:13:52.020  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:13:52.020  5627  5674 D BluetoothAdapter: STATE_ON
08-29 07:13:52.023  5864  5874 D BtGatt.GattService: registerClient() - UUID=8c4ba177-2100-43f2-8ceb-e7ca4841edf1
08-29 07:13:52.024  5864  5880 D BtGatt.GattService: onClientRegistered() - UUID=8c4ba177-2100-43f2-8ceb-e7ca4841edf1, clientIf=5
08-29 07:13:52.024  5627  5638 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 07:13:52.025  5864  5892 D BtGatt.GattService: start scan with filters
,08-29 07:13:52.028  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 07:13:52.028  5864  5883 D BtGatt.ScanManager: handling starting scan
08-29 07:13:52.028  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:13:52.028  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:13:52.028  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 07:13:52.029  5864  5883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57bfef0
,08-29 07:13:52.031  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:13:52.031  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:13:52.031  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 07:13:52.032  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 07:13:52.035  5627  5674 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 07:13:52.035  5864  5880 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:13:52.035  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:52.035  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:13:52.035  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 07:13:52.035  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.035  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:13:52.035  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 07:13:52.035  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:13:52.035  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:13:52.035  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:13:52.036  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:13:52.036  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 07:13:52.036  5864  5883 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 07:13:52.037  5627  5674 D BluetoothAdapter: STATE_ON
08-29 07:13:52.037  5864  5874 D BtGatt.GattService: stopScan() - queue size =1
08-29 07:13:52.038  5864  5892 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 07:13:52.038  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:13:52.038  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:13:52.038  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:13:52.038  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:13:52.038  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:13:52.039  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:13:52.040  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:13:52.040  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:13:52.040  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 07:13:52.040  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 07:13:52.041  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:13:52.041  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:13:52.041  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:13:52.042  5864  5880 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:13:52.042  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.042  5864  5883 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:13:52.043  5864  5883 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:13:52.043  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:52.043  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 07:13:52.043  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 07:13:52.043  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:52.043  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.043  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:13:52.043  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:13:52.043  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df64e0 removed from the list
08-29 07:13:52.043  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:52.043  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1a6399 removed from the list
08-29 07:13:52.044  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:52.044  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:52.044  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:13:52.044  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:52.045  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:52.045  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:52.045  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:52.045  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1a6399 not in the list
08-29 07:13:52.045  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.045  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:52.046  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:52.046  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:52.046  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:52.046  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@785ef0c removed from the list
,08-29 07:13:52.046  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:52.046  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.046  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:52.046  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:13:52.046  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6afa3f removed from the list
08-29 07:13:52.047  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 07:13:52.047  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a28eff8 added. We now have 2 listener(s)
08-29 07:13:52.048  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:13:52.048  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:13:52.048  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:13:52.048  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:52.049  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5becd1 added. We now have 9 listener(s)
,08-29 07:13:52.049  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:13:52.049  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 07:13:52.051  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:13:52.052  5864  5880 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:13:52.052  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.054  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:13:52.054  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:52.054  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:52.054  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:52.054  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:52.054  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:52.054  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:52.054  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:13:52.056  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:13:52.057  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 07:13:52.057  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:13:52.057  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@247f237 added. We now have 3 listener(s)
08-29 07:13:52.057  5864  5880 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:13:52.057  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.058  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:13:52.058  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:13:52.058  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:13:52.058  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:52.058  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f913a4 added. We now have 10 listener(s)
08-29 07:13:52.058  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:13:52.059  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 07:13:52.059  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:52.059  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:13:52.059  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:13:52.059  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:13:52.059  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:13:52.060  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:13:52.060  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:13:52.062  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 07:13:52.062  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 07:13:52.065  5864  5880 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:13:52.065  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.065  5864  5883 D BtGatt.ScanManager: stopping BLe Batch
08-29 07:13:52.065  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 07:13:52.066  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 07:13:52.067  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 07:13:52.069  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 07:13:52.070  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:13:52.070  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:13:52.070  5864  5880 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:13:52.070  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.070  5864  5883 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 07:13:52.070  5627  5674 D BluetoothAdapter: STATE_ON
,08-29 07:13:52.072  5864  5874 D BtGatt.GattService: registerClient() - UUID=07ea7dc0-0a78-4ed5-8443-277f4f19b1fa
08-29 07:13:52.072  5864  5880 D BtGatt.GattService: onClientRegistered() - UUID=07ea7dc0-0a78-4ed5-8443-277f4f19b1fa, clientIf=5
,08-29 07:13:52.073  5627  5637 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 07:13:52.073  5864  5875 D BtGatt.GattService: start scan with filters
08-29 07:13:52.074  5864  5880 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:13:52.074  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.075  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 07:13:52.075  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:13:52.075  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:13:52.075  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 07:13:52.076  5864  5883 D BtGatt.ScanManager: handling starting scan
,08-29 07:13:52.077  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 07:13:52.078  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:13:52.078  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:13:52.079  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 07:13:52.081  5864  5880 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:13:52.081  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.081  5864  5883 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 07:13:52.082  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:13:52.082  5627  5674 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 07:13:52.082  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:13:52.082  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:52.082  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:52.082  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:52.082  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.082  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:13:52.082  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:13:52.082  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a28eff8 removed from the list
08-29 07:13:52.082  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:52.082  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5becd1 removed from the list
08-29 07:13:52.082  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:52.082  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 07:13:52.083  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.083  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 07:13:52.083  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.083  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:13:52.084  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:52.084  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 07:13:52.084  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:52.084  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5becd1 not in the list
08-29 07:13:52.084  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:13:52.084  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:13:52.084  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:13:52.085  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 07:13:52.085  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 07:13:52.085  5627  5674 D BluetoothAdapter: STATE_ON
,08-29 07:13:52.085  5864  5892 D BtGatt.GattService: stopScan() - queue size =1
08-29 07:13:52.086  5864  5880 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-29 07:13:52.086  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.086  5864  5883 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:13:52.086  5864  5883 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:13:52.086  5864  5893 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 07:13:52.086  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:13:52.086  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:13:52.086  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:13:52.086  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:13:52.086  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:13:52.087  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 07:13:52.087  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:13:52.087  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:13:52.087  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 07:13:52.088  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:52.088  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:52.088  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:52.089  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 07:13:52.089  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:13:52.089  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f913a4 removed from the list
08-29 07:13:52.089  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:52.089  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:13:52.089  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.089  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:13:52.089  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:52.089  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:13:52.089  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@247f237 removed from the list
08-29 07:13:52.089  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:13:52.089  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@685c610 added. We now have 2 listener(s)
08-29 07:13:52.091  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 07:13:52.091  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:13:52.091  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:13:52.091  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:52.091  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ae6509 added. We now have 9 listener(s)
08-29 07:13:52.091  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:13:52.092  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 07:13:52.094  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:13:52.095  5864  5880 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:13:52.095  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.097  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:13:52.097  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:52.097  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:52.097  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:52.097  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:52.097  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:52.097  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:52.097  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:13:52.099  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:13:52.099  5864  5880 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:13:52.099  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.099  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:13:52.099  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:13:52.099  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6dcf12f added. We now have 3 listener(s)
08-29 07:13:52.100  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:52.100  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:13:52.100  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:13:52.101  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 07:13:52.101  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:52.101  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e9333c added. We now have 10 listener(s)
08-29 07:13:52.101  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:13:52.101  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:13:52.101  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:13:52.101  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:13:52.101  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:13:52.101  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:13:52.101  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:52.104  5864  5880 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,08-29 07:13:52.104  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.104  5864  5883 D BtGatt.ScanManager: stopping BLe Batch
08-29 07:13:52.105  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 07:13:52.106  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 07:13:52.108  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 07:13:52.109  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 07:13:52.109  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 07:13:52.109  5864  5880 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:13:52.109  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.109  5864  5883 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 07:13:52.111  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 07:13:52.111  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:13:52.111  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:13:52.111  5627  5674 D BluetoothAdapter: STATE_ON
08-29 07:13:52.113  5864  5875 D BtGatt.GattService: registerClient() - UUID=9f0425ca-0301-4908-b3e2-e79c49762809
08-29 07:13:52.113  5864  5880 D BtGatt.GattService: onClientRegistered() - UUID=9f0425ca-0301-4908-b3e2-e79c49762809, clientIf=5
08-29 07:13:52.114  5864  5880 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:13:52.114  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:13:52.114  5627  5638 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 07:13:52.114  5864  5893 D BtGatt.GattService: start scan with filters
08-29 07:13:52.116  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 07:13:52.116  5864  5883 D BtGatt.ScanManager: handling starting scan
08-29 07:13:52.116  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 07:13:52.116  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 07:13:52.116  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 07:13:52.118  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:13:52.118  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:13:52.118  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:13:52.119  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 07:13:52.121  5864  5880 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 07:13:52.121  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.121  5864  5883 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 07:13:52.122  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 07:13:52.123  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:52.123  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 07:13:52.123  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:52.123  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.123  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:13:52.123  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:13:52.123  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@685c610 removed from the list
08-29 07:13:52.123  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:52.123  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ae6509 removed from the list
08-29 07:13:52.123  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:52.123  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 07:13:52.124  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.124  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 07:13:52.124  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.124  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:13:52.124  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:52.124  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:52.124  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 07:13:52.125  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ae6509 not in the list
08-29 07:13:52.125  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:13:52.125  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:13:52.125  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:13:52.125  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:13:52.125  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 07:13:52.125  5627  5674 D BluetoothAdapter: STATE_ON
08-29 07:13:52.125  5864  5880 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:13:52.125  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.125  5864  5883 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:13:52.126  5864  5901 D BtGatt.GattService: stopScan() - queue size =1
08-29 07:13:52.126  5864  5883 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:13:52.126  5864  5875 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 07:13:52.126  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:13:52.126  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:13:52.126  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:13:52.126  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:13:52.126  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:13:52.127  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:13:52.127  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:13:52.127  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:13:52.127  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 07:13:52.128  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:52.128  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:52.129  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:52.129  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:52.129  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e9333c removed from the list
08-29 07:13:52.129  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:52.129  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:13:52.129  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.129  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 07:13:52.129  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:52.129  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:13:52.129  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 07:13:52.129  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6dcf12f removed from the list
,08-29 07:13:52.129  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:13:52.129  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b44728 added. We now have 2 listener(s)
08-29 07:13:52.131  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:13:52.131  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:13:52.131  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:13:52.131  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:52.131  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@660ac41 added. We now have 9 listener(s)
08-29 07:13:52.131  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:13:52.132  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 07:13:52.134  5864  5880 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:13:52.134  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.135  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:13:52.137  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:13:52.137  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:13:52.137  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:13:52.137  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:13:52.137  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:13:52.137  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:13:52.137  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:13:52.137  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:13:52.138  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:13:52.138  5864  5880 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:13:52.138  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:13:52.138  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:13:52.138  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:13:52.139  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c43d727 added. We now have 3 listener(s)
08-29 07:13:52.140  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:52.140  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:13:52.140  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:13:52.140  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:13:52.140  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:13:52.140  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39aadd4 added. We now have 10 listener(s)
08-29 07:13:52.141  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:13:52.141  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 07:13:52.141  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:13:52.141  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:13:52.141  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:13:52.141  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:52.141  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.141  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:13:52.141  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:13:52.141  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b44728 removed from the list
08-29 07:13:52.141  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:52.141  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@660ac41 removed from the list
,08-29 07:13:52.141  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:13:52.141  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:52.142  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.142  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:52.144  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:52.144  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:52.144  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:52.144  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@660ac41 not in the list
08-29 07:13:52.144  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.144  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:13:52.144  5864  5880 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:13:52.144  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:13:52.144  5864  5883 D BtGatt.ScanManager: stopping BLe Batch
,08-29 07:13:52.145  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:13:52.145  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:13:52.145  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:13:52.146  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39aadd4 removed from the list
08-29 07:13:52.146  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:13:52.146  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:13:52.146  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:13:52.146  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:13:52.146  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c43d727 removed from the list
08-29 07:13:52.147  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 07:13:52.147  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 07:13:52.147  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-29 07:13:52.147  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:13:52.147  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 07:13:52.147  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 07:13:52.149  5864  5880 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 07:13:52.149  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:13:52.149  5864  5883 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 07:13:52.152  5627  5921 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: My test thread name)
,08-29 07:13:52.152  5627  5921 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: My test thread name)
08-29 07:13:52.152  5627  5921 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 07:13:52.154  5627  5922 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name)
08-29 07:13:52.154  5627  5922 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: My test thread name)
08-29 07:13:52.154  5864  5880 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:13:52.154  5627  5922 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 07:13:52.154  5864  5880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:13:52.156  5627  5674 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-29 07:13:52.156  5627  5674 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 07:13:52.156  5627  5674 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 07:13:52.156  5627  5674 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 07:13:52.156  5627  5674 D com.test.thalitest.ThaliTestRunner: Total duration: 22537 ms
08-29 07:13:52.158  5627  5674 I jxcore-log: *Native tests were executed*
08-29 07:13:52.158  5627  5674 I jxcore-log: 
08-29 07:13:52.158  5627  5674 I jxcore-log: Total number of executed tests:  80
08-29 07:13:52.158  5627  5674 I jxcore-log: 
08-29 07:13:52.158  5627  5674 I jxcore-log: Number of passed tests:  80
08-29 07:13:52.158  5627  5674 I jxcore-log: 
08-29 07:13:52.158  5627  5674 I jxcore-log: Number of failed tests:  0
08-29 07:13:52.158  5627  5674 I jxcore-log: 
08-29 07:13:52.158  5627  5674 I jxcore-log: Number of ignored tests:  0
08-29 07:13:52.158  5627  5674 I jxcore-log: 
08-29 07:13:52.158  5627  5674 I jxcore-log: Total duration:  22537
08-29 07:13:52.158  5627  5674 I jxcore-log: 
,08-29 07:13:52.159  5627  5674 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 07:13:52.159  5627  5674 I jxcore-log: 
08-29 07:13:52.161  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 07:13:52.161  5627  5674 I jxcore-log: 
,08-29 07:13:52.164  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 07:13:52.164  5627  5674 I jxcore-log: 
08-29 07:13:52.165  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 07:13:52.165  5627  5674 I jxcore-log: 
08-29 07:13:52.167  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 07:13:52.167  5627  5674 I jxcore-log: 
08-29 07:13:52.168  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 07:13:52.168  5627  5674 I jxcore-log: 
08-29 07:13:52.168  5627  5627 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 07:13:52.170  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 07:13:52.170  5627  5674 I jxcore-log: 
08-29 07:13:52.172  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 07:13:52.172  5627  5674 I jxcore-log: 
08-29 07:13:52.174  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 07:13:52.174  5627  5674 I jxcore-log: 
08-29 07:13:52.175  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 07:13:52.175  5627  5674 I jxcore-log: 
08-29 07:13:52.175  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:13:52.175  5627  5674 I jxcore-log: 
08-29 07:13:52.176  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:13:52.176  5627  5674 I jxcore-log: 
08-29 07:13:52.178  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 07:13:52.178  5627  5674 I jxcore-log: 
08-29 07:13:52.178  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 07:13:52.178  5627  5674 I jxcore-log: 
08-29 07:13:52.179  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 07:13:52.179  5627  5674 I jxcore-log: 
08-29 07:13:52.180  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:13:52.180  5627  5674 I jxcore-log: 
,08-29 07:13:52.180  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:13:52.180  5627  5674 I jxcore-log: 
08-29 07:13:52.181  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 07:13:52.181  5627  5674 I jxcore-log: 
,08-29 07:13:52.182  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 07:13:52.182  5627  5674 I jxcore-log: 
,08-29 07:13:52.182  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:13:52.182  5627  5674 I jxcore-log: 
,08-29 07:13:52.183  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:13:52.183  5627  5674 I jxcore-log: 
,08-29 07:13:52.184  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 07:13:52.184  5627  5674 I jxcore-log: 
08-29 07:13:52.184  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 07:13:52.184  5627  5674 I jxcore-log: 
,08-29 07:13:52.185  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:13:52.185  5627  5674 I jxcore-log: 
,08-29 07:13:52.185  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:13:52.185  5627  5674 I jxcore-log: 
,08-29 07:13:52.186  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:13:52.186  5627  5674 I jxcore-log: 
,08-29 07:13:52.187  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:13:52.187  5627  5674 I jxcore-log: 
,08-29 07:13:52.187  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:13:52.187  5627  5674 I jxcore-log: 
08-29 07:13:52.188  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:13:52.188  5627  5674 I jxcore-log: 
,08-29 07:13:52.189  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:13:52.189  5627  5674 I jxcore-log: 
,08-29 07:13:52.542  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 07:13:52.546  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 07:13:52.546  5627  5674 I jxcore-log: 
,08-29 07:13:52.590  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 07:13:52.594  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 07:13:52.594  5627  5674 I jxcore-log: 
,08-29 07:13:52.616  5923  5923 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 07:13:52.623  5923  5923 D AndroidRuntime: CheckJNI is OFF
,08-29 07:13:52.630  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 07:13:52.633  5627  5674 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 07:13:52.633  5627  5674 I jxcore-log: 
,08-29 07:13:52.652  5923  5923 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 07:13:52.684  5923  5923 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 07:13:52.700  5923  5923 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 07:13:52.708   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,08-29 07:13:52.709   931   944 I ActivityManager: Killing 5627:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,08-29 07:13:52.792   931  3628 D GraphicsStats: Buffer count: 2
08-29 07:13:52.792   931   942 I WindowState: WIN DEATH: Window{438b2bc u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 07:13:52.794   931  3065 D WifiService: Client connection lost with reason: 4
,08-29 07:13:52.852   931   944 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-29 07:13:52.852   931   944 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-29 07:13:52.853   931   954 I art     : Starting a blocking GC Explicit
08-29 07:13:52.853   931   944 E ActivityManager: Failure starting process com.test.thalitest
08-29 07:13:52.853   931   944 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 07:13:52.853   931   944 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:13:52.853   931   944 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:13:52.853   931   944 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 07:13:52.853   931   944 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-29 07:13:52.854   931   944 I ActivityManager:   Force finishing activity ActivityRecord{758ae1 u0 com.test.thalitest/.MainActivity t4}
,08-29 07:13:52.862   931  3509 W ActivityManager: Spurious death for ProcessRecord{84b718c 0:com.test.thalitest/u0a77}, curProc for 5627: null
,08-29 07:13:52.928   931   954 I art     : Explicit concurrent mark sweep GC freed 25262(1555KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 1.525ms total 75.077ms
,08-29 07:13:52.948   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 07:13:52.951  5923  5923 I art     : System.exit called, status: 0
,08-29 07:13:52.951  5923  5923 I AndroidRuntime: VM exiting with result code 0.
,08-29 07:13:52.966   931   954 I ActivityManager: Start proc 5933:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-29 07:13:52.966   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,08-29 07:13:52.971   931   944 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-29 07:13:52.976  5864  5864 D BluetoothMapAppObserver: onReceive
08-29 07:13:52.976  5864  5864 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-29 07:13:52.979  3727  4015 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 07:13:52.983   931  3044 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 07:13:52.984  3512  3512 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 07:13:53.014  3512  5945 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 07:13:53.022  4889  5947 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 07:13:53.028  3701  3701 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-29 07:13:53.028  3701  3701 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-29 07:13:53.030  3613  3613 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 07:13:53.036  3512  5945 I Decoder : createOrResetDecoder
,08-29 07:13:53.042   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 07:13:53.054  3982  5952 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-29 07:13:53.055  3982  5952 D AccountUtils: Clearing selected account for com.test.thalitest
,08-29 07:13:53.057  3701  3701 I ConfigService: onCreate
,08-29 07:13:53.070    27    27 W kworker/2:1: type=1400 audit(0.0:73): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 07:13:53.081  3512  5945 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 07:13:53.080    27    27 W kworker/2:1: type=1400 audit(0.0:74): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 07:13:53.103  3982  5952 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-29 07:13:53.100    27    27 W kworker/2:1: type=1400 audit(0.0:75): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 07:13:53.144  3982  5952 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:13:53.144  3982  5952 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:13:53.144  3982  5952 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 07:13:53.145  3982  5952 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,08-29 07:13:53.156  4889  5947 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
08-29 07:13:53.157  4889  5947 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 07:13:53.157  4889  5947 E AndroidRuntime: Process: android.process.acore, PID: 4889
08-29 07:13:53.157  4889  5947 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:13:53.157  4889  5947 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 07:13:53.161   931  5957 E DropBoxManagerService: Can't write: system_app_crash
08-29 07:13:53.161   931  5957 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-29 07:13:53.161   931  5957 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 07:13:53.161   931  5957 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 07:13:53.161   931  5957 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 07:13:53.161   931  5957 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 07:13:53.161   931  5957 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 07:13:53.161   931  5957 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 07:13:53.161   931  5957 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 07:13:53.161   931  5957 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 07:13:53.161   931  5957 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 07:13:53.161   931  5957 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 07:13:53.161   931  5957 E DropBoxManagerService: 	... 5 more
,08-29 07:13:53.162  4889  5947 I Process : Sending signal. PID: 4889 SIG: 9
,08-29 07:13:53.179   384   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
