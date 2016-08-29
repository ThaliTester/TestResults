#### Test 82914073a7b15c1_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-29 12:40:56.714   620   620 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 12:40:57.198  5675  5675 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 12:40:57.204  5675  5675 D AndroidRuntime: CheckJNI is OFF
08-29 12:40:57.231  5675  5675 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 12:40:57.262  5675  5675 I Radio-JNI: register_android_hardware_Radio DONE
08-29 12:40:57.277  5675  5675 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 12:40:57.281   928  3644 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 12:40:57.331   928  3644 I ActivityManager: Start proc 5684:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-29 12:40:57.336  5675  5675 D AndroidRuntime: Shutting down VM
08-29 12:40:57.427  5684  5684 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-29 12:40:57.459  5684  5684 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 12:40:57.482  5684  5684 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 4939-4958)
08-29 12:40:57.482  5684  5684 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 12:40:57.501  5684  5684 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c64261f}
08-29 12:40:57.502  5684  5684 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 12:40:57.502  5684  5684 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 12:40:57.508  5684  5684 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 12:40:57.509  5684  5684 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 12:40:57.552  5684  5684 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 12:40:57.567  5684  5684 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 12:40:57.567  5684  5684 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 12:40:57.567  5684  5684 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 12:40:57.567  5684  5684 I Adreno  : Build Date                       : 10/21/15
08-29 12:40:57.567  5684  5684 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 12:40:57.567  5684  5684 I Adreno  : Local Branch                     : 
08-29 12:40:57.567  5684  5684 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 12:40:57.567  5684  5684 I Adreno  : Remote Branch                    : NONE
08-29 12:40:57.567  5684  5684 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 12:40:57.629   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@141ff31:true
,08-29 12:40:57.692  5684  5684 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 12:40:57.707  5684  5684 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-29 12:40:57.714   620   620 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 12:40:57.738  5684  5721 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 12:40:57.750  5684  5708 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 12:40:57.784  5684  5721 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 12:40:57.881   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +500ms (total +578ms)
,08-29 12:40:57.905  5684  5684 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5684
,08-29 12:40:57.990  5684  5684 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 12:40:58.109  5684  5724 D jxcore_app_log: JniHelper::setJavaVM(0xf4e7c000), pthread_self() = -582481616
,08-29 12:40:58.113  5684  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 12:40:58.113  5684  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 12:40:58.113  5684  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 12:40:58.113  5684  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 12:40:58.113  5684  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 12:40:58.113  5684  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4421ad added. We now have 1 listener(s)
,08-29 12:40:58.116  5684  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,08-29 12:40:58.116  5684  5724 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 12:40:58.117  5684  5724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 12:40:58.117  5684  5724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 12:40:58.119  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d640330 added. We now have 1 listener(s)
08-29 12:40:58.119  5684  5724 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 12:40:58.122   928  3054 D WifiService: New client listening to asynchronous messages
08-29 12:40:58.122  5684  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 12:40:58.122  5684  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 12:40:58.122  5684  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 12:40:58.122  5684  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 12:40:58.122  5684  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 12:40:58.125  5684  5724 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 12:40:58.125  5684  5724 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-29 12:40:58.129  5684  5724 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 12:40:58.129  5684  5724 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 12:40:58.129  5684  5724 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:40:58.129  5684  5724 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:40:58.129  5684  5724 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:40:58.129  5684  5724 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:40:58.129  5684  5724 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 12:40:58.129  5684  5724 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 12:40:58.129  5684  5724 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 12:40:58.129  5684  5724 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-29 12:40:58.129  5684  5724 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 12:40:58.130  5684  5724 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 12:40:58.131  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:40:58.134  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:40:58.146  5684  5684 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 12:40:58.395  5684  5730 W jxcore-log: Initializing JXcore engine
08-29 12:40:58.395  5684  5730 W jxcore-log: JXcore engine is ready
,08-29 12:40:58.412  5730  5730 W Thread-57: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12713 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 12:40:58.412  5730  5730 W Thread-57: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[14715]" dev="sockfs" ino=14715 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 12:40:58.412  5730  5730 W Thread-57: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5905 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 12:40:58.412  5730  5730 W Thread-57: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[32890]" dev="sockfs" ino=32890 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 12:40:58.427  5684  5730 W jxcore-log: Starting JXcore engine
,08-29 12:40:58.477  5684  5730 W jxcore-log: Platform android
08-29 12:40:58.477  5684  5730 W jxcore-log: 
08-29 12:40:58.477  5684  5730 W jxcore-log: Process ARCH arm
08-29 12:40:58.477  5684  5730 W jxcore-log: 
,08-29 12:40:58.571  5684  5730 I jxcore-log: JXcore Cordova bridge is ready!
08-29 12:40:58.571  5684  5730 I jxcore-log: 
,08-29 12:40:58.572  5684  5730 W jxcore-log: JXcore engine is started
,08-29 12:40:58.579  5684  5724 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 12:40:58.582  5684  5684 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 12:40:58.715   620   620 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 12:40:59.716   620   620 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 12:40:59.764   928  5354 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167240, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 12:41:00.717   620   620 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 12:41:01.718   620   620 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 12:41:05.302  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 12:41:05.302  5684  5730 I jxcore-log: 
,08-29 12:41:05.304  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 12:41:05.304  5684  5730 I jxcore-log: 
,08-29 12:41:05.307  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 12:41:05.307  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:05.307  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:05.307  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:05.307  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:05.307  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 12:41:05.307  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 12:41:05.307  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 12:41:05.309  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 12:41:05.310  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 12:41:05.310  5684  5730 I jxcore-log: 
,08-29 12:41:05.312  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 12:41:05.312  5684  5730 I jxcore-log: 
,08-29 12:41:05.674  5684  5730 D executeNativeTests: Running unit tests
,08-29 12:41:05.713  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 12:41:05.713  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d added. We now have 2 listener(s)
,08-29 12:41:05.714  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 12:41:05.714  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 12:41:05.714  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 12:41:05.714  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:05.714  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 added. We now have 2 listener(s)
08-29 12:41:05.714  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:05.715  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 12:41:05.716  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 12:41:05.729  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 12:41:05.729  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:05.729  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:05.729  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:05.729  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:05.729  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 12:41:05.729  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 12:41:05.729  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 12:41:05.733  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 12:41:05.734  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 12:41:05.739  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 12:41:05.739  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:05.740  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 12:41:05.740  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 12:41:05.744  5684  5730 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 12:41:05.745  5684  5730 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 12:41:05.745  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 12:41:05.745  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 12:41:05.745  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 12:41:05.745  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:05.746  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.746  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.746  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.746  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 12:41:05.746  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.746  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 12:41:05.746  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 12:41:05.747  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d removed from the list
08-29 12:41:05.747  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.747  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 removed from the list
,08-29 12:41:05.747  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.747  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 12:41:05.747  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.747  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.748  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.748  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.748  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 12:41:05.748  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.749  5684  5730 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 12:41:05.750  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.750  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.750  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.750  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 12:41:05.750  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.750  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.750  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.750  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.750  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.750  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.750  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.750  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.750  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.750  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.751  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.751  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.751  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.751  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 12:41:05.753  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 12:41:05.754  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.754  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 12:41:05.754  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.754  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.754  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.754  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.754  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.754  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 12:41:05.754  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.754  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.754  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.754  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.755  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.755  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.755  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.755  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.755  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.755  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.755  5684  5730 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 12:41:05.756  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 12:41:05.758  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 12:41:05.758  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:05.758  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:05.758  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:05.758  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:05.758  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 12:41:05.758  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 12:41:05.758  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 12:41:05.759  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 12:41:05.759  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 12:41:05.759  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 12:41:05.760  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 12:41:05.760  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 12:41:05.760  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 12:41:05.760  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 12:41:05.761  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:05.762  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:05.763  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 12:41:05.763  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 12:41:05.766  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 12:41:05.766  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 12:41:05.767  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 12:41:05.768  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 12:41:05.769  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 12:41:05.769  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 12:41:05.769  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 12:41:05.770  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 12:41:05.770  5684  5730 D BluetoothAdapter: STATE_ON
,08-29 12:41:05.772  4501  4515 D BtGatt.GattService: registerClient() - UUID=dbb13c04-ee66-4bef-9ec5-ce79ea3f9d35
,08-29 12:41:05.773  4501  4577 D BtGatt.GattService: onClientRegistered() - UUID=dbb13c04-ee66-4bef-9ec5-ce79ea3f9d35, clientIf=5
08-29 12:41:05.774  5684  5695 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 12:41:05.774  4501  4771 D BtGatt.GattService: start scan with filters
,08-29 12:41:05.779  4501  4585 D BtGatt.ScanManager: handling starting scan
,08-29 12:41:05.779  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 12:41:05.779  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 12:41:05.779  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 12:41:05.779  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 12:41:05.782  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 12:41:05.782  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 12:41:05.782  4501  4585 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
08-29 12:41:05.782  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 12:41:05.783  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 12:41:05.784  5684  5730 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 12:41:05.786  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.786  5684  5730 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 12:41:05.786  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 12:41:05.786  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 12:41:05.786  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.786  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 12:41:05.786  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 12:41:05.786  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 12:41:05.786  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 12:41:05.786  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 12:41:05.786  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 12:41:05.786  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 12:41:05.786  5684  5730 D BluetoothAdapter: STATE_ON
08-29 12:41:05.787  4501  4515 D BtGatt.GattService: stopScan() - queue size =1
08-29 12:41:05.787  4501  4771 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 12:41:05.787  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 12:41:05.787  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 12:41:05.787  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 12:41:05.787  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 12:41:05.787  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 12:41:05.788  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 12:41:05.788  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 12:41:05.788  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 12:41:05.788  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 12:41:05.788  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 12:41:05.789  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.789  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.789  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 12:41:05.789  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.789  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.789  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.789  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.789  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 12:41:05.789  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.789  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 12:41:05.789  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 12:41:05.790  5684  5730 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 12:41:05.790  4501  4577 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 12:41:05.790  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.790  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 12:41:05.790  4501  4585 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 12:41:05.793  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 12:41:05.793  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:05.793  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:05.793  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:05.793  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:05.793  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 12:41:05.793  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 12:41:05.793  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 12:41:05.794  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 12:41:05.794  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 12:41:05.794  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 12:41:05.794  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 12:41:05.794  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 12:41:05.794  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 12:41:05.794  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 12:41:05.795  4501  4577 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 12:41:05.795  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.795  4501  4585 D BtGatt.ScanManager: Starting BLE batch scan
08-29 12:41:05.796  4501  4585 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 12:41:05.796  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 12:41:05.796  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 12:41:05.801  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 12:41:05.801  4501  4577 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 12:41:05.801  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.801  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:05.803  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 12:41:05.803  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 12:41:05.806  4501  4577 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 12:41:05.806  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 12:41:05.806  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:05.808  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 12:41:05.808  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 12:41:05.808  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 12:41:05.808  5684  5730 D BluetoothAdapter: STATE_ON
,08-29 12:41:05.811  4501  4577 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,08-29 12:41:05.811  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.811  4501  4516 D BtGatt.GattService: registerClient() - UUID=57823834-7f0b-496f-b8b7-215666fd36fe
08-29 12:41:05.811  4501  4585 D BtGatt.ScanManager: stopping BLe Batch
08-29 12:41:05.811  4501  4577 D BtGatt.GattService: onClientRegistered() - UUID=57823834-7f0b-496f-b8b7-215666fd36fe, clientIf=5
,08-29 12:41:05.812  5684  5694 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 12:41:05.812  4501  4515 D BtGatt.GattService: start scan with filters
,08-29 12:41:05.816  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 12:41:05.816  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 12:41:05.816  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 12:41:05.816  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 12:41:05.816  4501  4577 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 12:41:05.817  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.817  4501  4585 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 12:41:05.818  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 12:41:05.818  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 12:41:05.818  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 12:41:05.818  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 12:41:05.819  5684  5730 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 12:41:05.821  4501  4577 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 12:41:05.821  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.821  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 12:41:05.822  5684  5730 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 12:41:05.822  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.822  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 12:41:05.822  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.822  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 12:41:05.822  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 12:41:05.822  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 12:41:05.822  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 12:41:05.822  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 12:41:05.822  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 12:41:05.822  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 12:41:05.822  5684  5730 D BluetoothAdapter: STATE_ON
08-29 12:41:05.822  4501  4516 D BtGatt.GattService: stopScan() - queue size =0
08-29 12:41:05.823  4501  4585 D BtGatt.ScanManager: handling starting scan
08-29 12:41:05.823  4501  4515 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 12:41:05.823  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 12:41:05.823  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 12:41:05.823  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 12:41:05.823  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 12:41:05.824  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 12:41:05.824  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 12:41:05.824  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 12:41:05.824  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 12:41:05.825  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 12:41:05.825  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 12:41:05.826  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.826  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.826  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 12:41:05.826  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 12:41:05.826  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.826  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 12:41:05.826  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.826  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 12:41:05.826  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.826  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.826  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.827  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.827  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 12:41:05.828  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.828  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.828  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.828  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.828  5684  5730 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 12:41:05.829  4501  4577 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 12:41:05.829  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.829  4501  4585 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 12:41:05.830  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 12:41:05.834  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 12:41:05.834  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:05.834  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:05.834  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:05.834  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:05.834  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 12:41:05.834  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 12:41:05.834  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 12:41:05.835  4501  4577 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 12:41:05.835  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.835  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 12:41:05.835  4501  4585 D BtGatt.ScanManager: Starting BLE batch scan
08-29 12:41:05.835  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 12:41:05.835  4501  4585 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 12:41:05.835  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 12:41:05.835  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 12:41:05.835  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 12:41:05.835  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 12:41:05.835  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 12:41:05.836  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 12:41:05.836  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 12:41:05.837  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:05.840  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 12:41:05.840  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:05.840  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 12:41:05.840  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 12:41:05.842  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 12:41:05.842  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 12:41:05.842  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 12:41:05.842  5684  5730 D BluetoothAdapter: STATE_ON
08-29 12:41:05.843  4501  4771 D BtGatt.GattService: registerClient() - UUID=72759a9e-4cee-4c78-a224-70f11b04eda9
,08-29 12:41:05.844  4501  4577 D BtGatt.GattService: onClientRegistered() - UUID=72759a9e-4cee-4c78-a224-70f11b04eda9, clientIf=5
,08-29 12:41:05.844  5684  5694 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 12:41:05.844  4501  4515 D BtGatt.GattService: start scan with filters
08-29 12:41:05.845  4501  4577 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 12:41:05.845  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.847  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 12:41:05.847  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 12:41:05.847  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 12:41:05.847  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 12:41:05.849  4501  4577 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 12:41:05.849  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.849  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 12:41:05.849  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 12:41:05.850  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 12:41:05.850  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 12:41:05.851  5684  5730 I io.jxcore.node.ConnectionHelper: start: OK
08-29 12:41:05.851  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.851  5684  5730 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 12:41:05.851  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.851  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 12:41:05.851  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.851  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 12:41:05.851  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 12:41:05.851  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 12:41:05.851  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 12:41:05.851  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 12:41:05.851  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 12:41:05.851  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 12:41:05.852  5684  5730 D BluetoothAdapter: STATE_ON
08-29 12:41:05.852  4501  4756 D BtGatt.GattService: stopScan() - queue size =0
08-29 12:41:05.852  4501  4771 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 12:41:05.852  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 12:41:05.852  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 12:41:05.852  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 12:41:05.852  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 12:41:05.852  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 12:41:05.853  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 12:41:05.853  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 12:41:05.853  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 12:41:05.853  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 12:41:05.853  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 12:41:05.854  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.854  5684  5730 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 12:41:05.854  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.854  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.854  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 12:41:05.854  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.854  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.854  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 12:41:05.854  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 12:41:05.854  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
,08-29 12:41:05.854  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.854  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 12:41:05.854  4501  4577 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 12:41:05.854  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.854  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.854  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.854  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.854  4501  4585 D BtGatt.ScanManager: stopping BLe Batch
08-29 12:41:05.854  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.854  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.855  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.855  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.855  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.855  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
,08-29 12:41:05.855  5684  5730 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 12:41:05.855  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.856  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.856  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.856  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.856  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.856  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.856  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.856  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.856  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.856  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.856  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.856  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 12:41:05.856  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.856  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.858  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.858  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.858  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.858  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.858  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 12:41:05.858  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.858  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.858  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.858  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.858  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 12:41:05.858  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.858  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.858  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.858  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.858  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.858  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.859  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.859  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.859  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.859  4501  4577 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 12:41:05.859  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.859  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.859  4501  4585 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 12:41:05.859  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.859  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 12:41:05.859  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.859  5684  5730 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 12:41:05.859  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.859  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.859  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.860  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.860  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.860  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.860  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.860  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.860  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.860  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 12:41:05.860  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.860  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.860  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.860  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.860  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.860  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.860  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.860  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.861  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 12:41:05.861  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.861  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.861  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.861  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.861  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.861  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.861  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.861  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.861  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.861  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 12:41:05.861  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.861  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.861  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.861  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.861  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.861  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.861  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.862  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.862  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 12:41:05.862  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 12:41:05.862  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 12:41:05.862  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 12:41:05.862  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 12:41:05.862  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 12:41:05.862  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.862  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.862  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.862  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.862  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.862  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.862  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
,08-29 12:41:05.862  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.862  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.862  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.862  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.862  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.862  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.862  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.863  4501  4577 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 12:41:05.863  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.865  4501  4585 D BtGatt.ScanManager: handling starting scan
,08-29 12:41:05.865  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.865  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.866  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 12:41:05.866  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.866  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 12:41:05.867  5684  5730 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 12:41:05.867  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 12:41:05.869  4501  4577 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 12:41:05.869  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.869  4501  4585 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 12:41:05.869  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 12:41:05.869  5684  5730 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 12:41:05.869  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 12:41:05.869  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 12:41:05.869  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 12:41:05.869  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 12:41:05.869  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 12:41:05.870  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 12:41:05.871  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 12:41:05.871  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 12:41:05.871  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 12:41:05.871  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 12:41:05.871  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 12:41:05.871  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 12:41:05.871  5684  5730 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 12:41:05.871  5684  5730 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-29 12:41:05.871  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 12:41:05.871  5684  5730 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 12:41:05.871  5684  5730 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 12:41:05.872  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 12:41:05.872  5684  5730 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 12:41:05.872  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 12:41:05.873  4501  4577 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 12:41:05.873  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.873  4501  4585 D BtGatt.ScanManager: Starting BLE batch scan
08-29 12:41:05.873  4501  4585 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 12:41:05.874  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 12:41:05.874  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 12:41:05.874  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 12:41:05.874  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 12:41:05.874  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 12:41:05.874  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 12:41:05.874  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 12:41:05.875  5684  5730 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 12:41:05.875  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.875  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.875  5684  5731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
08-29 12:41:05.875  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.875  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.875  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.875  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.875  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 12:41:05.875  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.875  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.875  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.876  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.876  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.876  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.876  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.876  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.876  5684  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
,08-29 12:41:05.876  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.876  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.877  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.877  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.877  5684  5730 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 12:41:05.877  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.878  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.878  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.878  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.878  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.878  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.878  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.878  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.878  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.878  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.878  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.878  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.878  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.878  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.878  5684  5731 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 12:41:05.880  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.880  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.880  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.880  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.880  5684  5730 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 12:41:05.881  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.881  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.881  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.881  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.881  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.881  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.881  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.881  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.881  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.881  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.881  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.881  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.881  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.881  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.882  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.882  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.882  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.882  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.882  5684  5730 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 12:41:05.883  5684  5730 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 12:41:05.883  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 12:41:05.883  5684  5730 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 12:41:05.883  5684  5730 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 12:41:05.883  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 12:41:05.883  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 12:41:05.883  5684  5730 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 12:41:05.883  5684  5730 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 12:41:05.883  5684  5730 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 12:41:05.883  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 12:41:05.883  5684  5730 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 12:41:05.883  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.883  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.883  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.883  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.883  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.883  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.883  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.883  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.884  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.884  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.884  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.884  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.884  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.884  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.884  4501  4577 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 12:41:05.884  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.884  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.884  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.884  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.884  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.885  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.885  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.885  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.885  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.885  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.885  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.885  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.885  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.885  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.885  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.885  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.885  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.885  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.885  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.885  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.885  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.885  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.885  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.885  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.885  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.885  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.885  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.886  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.886  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.886  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.886  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.886  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.886  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.886  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.888  4501  4577 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 12:41:05.888  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.890  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.890  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.890  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.890  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.891  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 12:41:05.891  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 12:41:05.891  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 12:41:05.892  4501  4577 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 12:41:05.892  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.892  4501  4585 D BtGatt.ScanManager: stopping BLe Batch
08-29 12:41:05.892  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 12:41:05.892  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 12:41:05.892  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 12:41:05.892  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 12:41:05.892  5684  5684 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 12:41:05.893  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.893  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 12:41:05.893  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 12:41:05.893  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 12:41:05.893  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.893  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 12:41:05.893  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.893  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.893  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 12:41:05.893  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 12:41:05.893  5684  5684 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 12:41:05.893  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 12:41:05.893  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.893  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.893  5684  5733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 12:41:05.895  5684  5733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 12:41:05.895  5684  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 12:41:05.895  5684  5733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 12:41:05.895  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 12:41:05.895  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.895  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.895  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.895  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.895  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.895  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.895  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.895  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.895  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 12:41:05.895  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.895  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.896  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.895  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 12:41:05.896  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.896  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.896  5684  5684 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 12:41:05.896  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.896  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.896  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 12:41:05.896  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.896  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.896  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.896  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.897  4501  4577 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 12:41:05.897  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.897  5684  5730 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 12:41:05.897  5684  5730 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 12:41:05.897  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 12:41:05.897  4501  4585 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 12:41:05.897  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 12:41:05.897  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.897  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.897  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.897  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.897  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.897  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.897  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.897  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.897  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.897  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.897  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.897  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.897  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.897  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.898  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.898  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.898  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.898  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.899  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.899  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.899  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.899  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.899  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.899  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.899  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.899  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.899  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.900  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.900  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.900  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.900  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.900  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.900  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.900  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.900  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.900  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.900  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:05.900  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:05.900  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:05.901  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:05.901  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.901  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.901  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbfb33d not in the list
08-29 12:41:05.901  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.901  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.901  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:05.901  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.901  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.901  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:05.901  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:05.901  4501  4577 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 12:41:05.901  4501  4577 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:05.902  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:05.902  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:05.902  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:05.902  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.bt,connectorlib.DiscoveryManager@46a1732 not in the list
08-29 12:41:05.902  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 12:41:05.902  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 12:41:05.902  5684  5730 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 12:41:05.902  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 12:41:05.902  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 12:41:05.902  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 12:41:05.903  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 12:41:05.903  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 12:41:05.903  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 12:41:05.903  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 12:41:05.903  5684  5730 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 12:41:05.903  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 12:41:05.903  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 12:41:05.904  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 12:41:05.904  5684  5730 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 12:41:05.904  5684  5730 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 12:41:05.904  5684  5730 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 12:41:05.904  5684  5730 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 12:41:05.904  5684  5730 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 12:41:05.904  5684  5730 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 12:41:05.904  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:05.904  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9b512c4 added. We now have 2 listener(s)
08-29 12:41:05.905  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:05.905  5684  5730 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 12:41:05.905   928   939 D WifiService: setWifiEnabled: true pid=5684, uid=10077
08-29 12:41:05.905   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 12:41:05.906  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:05.906  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@568e5ad added. We now have 3 listener(s)
08-29 12:41:05.906  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:05.908  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:05.908  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@472b0e2 added. We now have 4 listener(s)
08-29 12:41:05.908  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:05.909  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:05.909  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7865c73 added. We now have 5 listener(s)
08-29 12:41:05.909  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:05.909   928  3686 D WifiService: setWifiEnabled: false pid=5684, uid=10077
08-29 12:41:05.909   928  3686 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 12:41:05.912   928  3049 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 12:41:05.912   928  3049 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 12:41:05.912   928  3049 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 12:41:05.912   928  3049 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 12:41:05.913  4501  4573 D BluetoothAdapterState: Current state: ON, message: 23
08-29 12:41:05.913  4501  4573 D BluetoothAdapterProperties: Setting state to 13
08-29 12:41:05.913  4501  4573 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 12:41:05.914  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 12:41:05.914  4501  4573 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 12:41:05.916  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:05.916  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 12:41:05.916  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:05.916  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:05.916  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:05.916  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 12:41:05.916  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 12:41:05.916  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 12:41:05.916  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 12:41:05.916  4501  4573 I BluetoothAdapterState: Entering PendingCommandState
08-29 12:41:05.917  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:05.917  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 12:41:05.917  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 12:41:05.918  4501  4501 D BluetoothMapService: onReceive
08-29 12:41:05.918  4501  4501 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 12:41:05.918  4501  4501 D BluetoothMapService: STATE_TURNING_OFF
08-29 12:41:05.918  4501  4501 D BluetoothMapService: MAP Service closeService in
08-29 12:41:05.918  4501  4501 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 12:41:05.919  4501  4501 D ObexServerSockets0: shutdown(block = true)
08-29 12:41:05.919  4501  4501 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 12:41:05.919  4501  4501 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 12:41:05.919  4501  4776 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
08-29 12:41:05.919  4501  4777 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 12:41:05.920  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:05.920  4501  4747 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 12:41:05.921  4501  4501 I BtOppRfcommListener: stopping Accept Thread
08-29 12:41:05.922   928  3049 E native  : do suspend true
08-29 12:41:05.922  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:05.925  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:05.925  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:05.925  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:05.925  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:05.925  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:05.925  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 12:41:05.925  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 12:41:05.925  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 12:41:05.925  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 12:41:05.925  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:05.925  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 12:41:05.927  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:05.928  4501  5306 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 12:41:05.928  4501  5306 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 12:41:05.931   928   941 I ActivityManager: Start proc 5736:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-29 12:41:05.931  4501  4577 D BluetoothAdapterProperties: Scan Mode:20
08-29 12:41:05.931  4501  4573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 12:41:05.934  4501  4501 D HeadsetService: Received stop request...Stopping profile...
08-29 12:41:05.935  4501  4501 V BluetoothAdapterState: isTurningOff()=true
08-29 12:41:05.935  4501  4501 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:05.935  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:05.935  4501  4501 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:05.935  3231  3873 D BluetoothHeadset: Proxy object disconnected
08-29 12:41:05.935  4501  4501 D A2dpService: Received stop request...Stopping profile...
08-29 12:41:05.935   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 12:41:05.935   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 12:41:05.935   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 12:41:05.935  4501  4763 D A2dpStateMachine: Exit Disconnected: -1
08-29 12:41:05.936  3622  3640 D BluetoothHeadset: Proxy object disconnected
08-29 12:41:05.938  3231  3231 D HeadsetProfile: Bluetooth service disconnected
08-29 12:41:05.939  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:05.940   928   928 D BluetoothA2dp: Proxy object disconnected
08-29 12:41:05.940  3231  3231 D BluetoothA2dp: Proxy object disconnected
08-29 12:41:05.942  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:05.942   928  5357 D DhcpClient: Clearing IP address
08-29 12:41:05.942   506   920 D CommandListener: Clearing all IP addresses on wlan0
08-29 12:41:05.943  4501  4501 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 12:41:05.943  4501  4501 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 12:41:05.943  4501  4731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 12:41:05.943  4501  4731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 12:41:05.943  4501  4501 D HidService: Received stop request...Stopping profile...
08-29 12:41:05.943  4501  4731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 12:41:05.943  4501  4501 D HidService: Stopping Bluetooth HidService
08-29 12:41:05.944  4501  4501 D HealthService: Received stop request...Stopping profile...
08-29 12:41:05.944  3231  3231 D BluetoothInputDevice: Proxy object disconnected
08-29 12:41:05.944  3231  3231 D HidProfile: Bluetooth service disconnected
08-29 12:41:05.945  4501  4501 D PanService: Received stop request...Stopping profile...
08-29 12:41:05.945  4501  4577 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 12:41:05.946  4501  4577 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 12:41:05.946  4501  4501 D BluetoothMapService: Received stop request...Stopping profile...
08-29 12:41:05.946  3231  3231 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 12:41:05.946  4501  4501 D BluetoothMapService: stop()
08-29 12:41:05.946  3231  3231 D PanProfile: Bluetooth service disconnected
08-29 12:41:05.947  4501  4501 D BluetoothMapAppObserver: deinitObservers()
,08-29 12:41:05.947  4501  4501 D BluetoothMapAppObserver: removeReceiver()
,08-29 12:41:05.947  4501  4501 V BluetoothAdapterState: isTurningOff()=true
08-29 12:41:05.947  4501  4501 V BluetoothAdapterState: isTurningOn()=false
,08-29 12:41:05.947  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:05.947  4501  4501 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:05.948   506   920 D CommandListener: Setting iface cfg
08-29 12:41:05.948  4501  4501 D SapService: Received stop request...Stopping profile...
08-29 12:41:05.948  4501  4501 V SapService: stop()
08-29 12:41:05.949  3231  3231 D BluetoothMap: Proxy object disconnected
08-29 12:41:05.949  3231  3231 D MapProfile: Bluetooth service disconnected
08-29 12:41:05.949  4501  4501 V BluetoothAdapterState: isTurningOff()=true
08-29 12:41:05.949  4501  4501 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:05.949  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 12:41:05.949   928  5358 D DhcpClient: Receive thread stopped
08-29 12:41:05.949  4501  4501 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:05.950  4501  4501 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 12:41:05.950  4501  4501 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 12:41:05.950  4501  4501 V BluetoothAdapterState: isTurningOff()=true
08-29 12:41:05.950  4501  4501 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:05.950  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:05.950  4501  4501 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:05.950  4501  4501 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 12:41:05.950  4501  4501 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 12:41:05.950  4501  4501 V BluetoothAdapterState: isTurningOff()=true
08-29 12:41:05.950  4501  4501 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:05.950  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:05.950  4501  4501 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:05.951  4501  4501 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 12:41:05.951  4501  4501 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 12:41:05.951  4501  4501 D BluetoothMapService: MAP Service closeService in
08-29 12:41:05.951  4501  4501 V BluetoothAdapterState: isTurningOff()=true
08-29 12:41:05.951  4501  4501 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:05.951  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:05.951  4501  4501 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:05.951  4501  4501 D BluetoothMapService: cleanup()
,08-29 12:41:05.951  4501  4501 D BluetoothMapService: MAP Service closeService in
08-29 12:41:05.951  4501  4501 V BluetoothAdapterState: isTurningOff()=true
08-29 12:41:05.951  4501  4501 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:05.951  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:05.952  4501  4501 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:05.952  4501  4573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 12:41:05.952  4501  4573 D BluetoothAdapterProperties: Setting state to 15
08-29 12:41:05.952  4501  4573 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 12:41:05.952  3231  3873 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 12:41:05.953  3702  5411 V NativeCrypto: Read error: ssl=0x7fadd90b00: I/O error during system call, Connection timed out
08-29 12:41:05.954  4501  4573 I BluetoothAdapterState: Entering BleOnState
08-29 12:41:05.955  3231  3243 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 12:41:05.955  3231  3242 D BluetoothMap: onBluetoothStateChange: up=false
08-29 12:41:05.956  3231  3873 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 12:41:05.956   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 12:41:05.956   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 12:41:05.956   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 12:41:05.957  3231  3243 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 12:41:05.957  3702  5411 V NativeCrypto: SSL shutdown failed: ssl=0x7fadd90b00: I/O error during system call, Broken pipe
08-29 12:41:05.958   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 12:41:05.958  3231  3242 D BluetoothPan: onBluetoothStateChange on: false
08-29 12:41:05.958  3622  3641 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 12:41:05.959  4501  4573 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 12:41:05.959  4501  4573 D BluetoothAdapterProperties: Setting state to 16
08-29 12:41:05.959  4501  4573 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 12:41:05.959   928  3646 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
08-29 12:41:05.959  4501  4577 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 12:41:05.959  4501  4731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 12:41:05.959  4501  4573 D BluetoothAdapterProperties: onBleDisable
08-29 12:41:05.959  4501  4577 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 12:41:05.960  4501  4731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 12:41:05.960  4501  4573 I BluetoothAdapterState: Entering PendingCommandState
,08-29 12:41:05.960  4501  4731 W bt_l2cap: btif_in_execute_service_request: Unknown service
08-29 12:41:05.960  4501  4577 E bt_btif : L2CAP - PSM: 0x0017 not found for deregistration
08-29 12:41:05.960  4501  4574 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 12:41:05.960  4501  4731 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 12:41:05.960  4501  4731 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 12:41:05.960  4501  4731 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 12:41:05.960   928  5353 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
08-29 12:41:05.960  4501  4577 D BluetoothAdapterProperties: Scan Mode:20
08-29 12:41:05.961  4501  4731 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 12:41:05.961  4501  4731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 12:41:05.961  5684  5731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
08-29 12:41:05.962   928  3059 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 12:41:05.962   928  3059 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 12:41:05.962   928  5353 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 12:41:05.964   618   618 E Parcel  : Reading a NULL string not supported here.
08-29 12:41:05.965  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:05.965  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:05.965  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:05.965  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:05.965  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:05.965  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 12:41:05.965  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:05.965  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 12:41:05.965  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 12:41:05.966   928   928 D RttService: SCAN_AVAILABLE : 1
08-29 12:41:05.966   928  3161 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 12:41:05.966  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:05.966  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 12:41:05.970  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:05.970  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:05.970  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:05.970  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:05.970  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi en,abled: true
08-29 12:41:05.970  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 12:41:05.970  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:05.970  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:05.970  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 12:41:05.971  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:05.971  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 12:41:05.972   928  3059 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 12:41:05.974  3592  3819 W QCNEJ   : |CORE| network lost: 100
08-29 12:41:05.974  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:05.974  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:05.974  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:05.974  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:05.974  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:05.974  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 12:41:05.974  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:05.974  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:05.974  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 12:41:05.975  3592  3819 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
08-29 12:41:05.976  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:05.976  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:05.976  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:05.976  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:05.976  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:05.976  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 12:41:05.976  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:05.976  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:05.976  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 12:41:05.987  5736  5736 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,08-29 12:41:05.990   928  3049 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 12:41:05.994   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 12:41:05.997   928  3049 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 12:41:05.997   928  3049 E native  : do suspend true
08-29 12:41:05.998  5736  5736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 12:41:06.003   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@46e67fe:true
,08-29 12:41:06.006  3702  3702 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 12:41:06.018   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 12:41:06.018   506   920 D CommandListener: Clearing all IP addresses on wlan0
08-29 12:41:06.018   928  3059 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 12:41:06.019   928  3059 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 12:41:06.019   506   920 D TetherController: Setting IP forward enable = 0
,08-29 12:41:06.021   928  3257 I ActivityManager: Start proc 5757:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 12:41:06.023   928  3049 D DhcpClient: doQuit
,08-29 12:41:06.023   928  3049 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 12:41:06.023   928  5357 D DhcpClient: onQuitting
,08-29 12:41:06.024  3741  3741 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
08-29 12:41:06.025   928   945 D Tethering: MasterInitialState.processMessage what=3
08-29 12:41:06.026  5248  5248 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@41d2918 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 12:41:06.027  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:06.027  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:06.027  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:06.027  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:06.027  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 12:41:06.027  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 12:41:06.027  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:06.027  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:06.027  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 12:41:06.028  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:06.028  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 12:41:06.030  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:06.031  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:06.031  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:06.031  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:06.031  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 12:41:06.031  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 12:41:06.031  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:06.031  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:06.031  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 12:41:06.032  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:06.032  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 12:41:06.033  4977  5008 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 12:41:06.033  4977  5008 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 12:41:06.033  4977  5008 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 12:41:06.033  4977  5008 E SarControlService: no key has been found,reset the power
08-29 12:41:06.034  4977  5026 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,08-29 12:41:06.034  4977  5026 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 12:41:06.034  4977  5026 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 12:41:06.035  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:06.035  5017  5017 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,08-29 12:41:06.035  5017  5017 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 12:41:06.036  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:06.037  4977  5026 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 12:41:06.037  4977  5026 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 12:41:06.037  4977  5026 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 12:41:06.037  5017  5017 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 12:41:06.037  5017  5017 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 12:41:06.040  5017  5032 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d6025be HexData = [00000000ea03000000000000ffffffff]
08-29 12:41:06.040  5017  5032 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,08-29 12:41:06.040  5017  5032 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
08-29 12:41:06.040  5017  5017 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 12:41:06.040  4977  4987 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,08-29 12:41:06.046  5017  5032 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d6025be HexData = [00000000eb03000000000000ffffffff]
,08-29 12:41:06.047  5017  5032 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 12:41:06.047  5017  5032 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
08-29 12:41:06.047  5017  5017 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 12:41:06.048  4977  4988 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-29 12:41:06.057  5736  5736 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 12:41:06.059  5736  5736 D BluetoothMap: Create BluetoothMap proxy object
,08-29 12:41:06.069   506   920 E Netd    : netlink response contains error (No such file or directory)
,08-29 12:41:06.069   506   920 D TetherController: Setting IP forward enable = 0
08-29 12:41:06.070   928  3059 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 12:41:06.070   928  3059 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 12:41:06.072  5757  5757 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,08-29 12:41:06.075  5736  5736 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 12:41:06.087  5736  5736 D DockEventReceiver: finishStartingService: stopping service
,08-29 12:41:06.100  3741  3741 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 12:41:06.100   928  3646 I ActivityManager: Killing 5108:com.google.android.gm/u0a68 (adj 15): empty #17
,08-29 12:41:06.104  3741  3741 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 12:41:06.169  4501  4577 I bt_hci  : shut_down
,08-29 12:41:06.173  4501  4589 D bt_hwcfg: hw_epilog_process
,08-29 12:41:06.173  4501  4589 I bt_vendor: low_power_mode_cb
,08-29 12:41:06.176  4501  4589 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 12:41:06.176  4501  4589 I bt_vendor: epilog_cb
08-29 12:41:06.176  4501  4589 I bt_hci  : epilog_finished_callback
08-29 12:41:06.176  3741  3741 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 12:41:06.178  4501  4577 I bt_hci_h4: hal_close
,08-29 12:41:06.178  4501  4577 I bt_userial_vendor: device fd = 51 close
,08-29 12:41:06.203  3741  3741 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 12:41:06.278  5757  5757 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 12:41:06.278  5757  5757 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 12:41:06.278  5757  5757 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 12:41:06.278  5757  5757 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 12:41:06.278  5757  5757 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 12:41:06.278  5757  5757 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 12:41:06.278  5757  5757 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 12:41:06.278  5757  5757 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 12:41:06.278  5757  5757 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 12:41:06.286  4501  4574 D bt_stack_manager: event_shut_down_stack finished.
08-29 12:41:06.286  4501  4573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-29 12:41:06.288  4501  4501 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 12:41:06.288  4501  4573 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 12:41:06.288  4501  4501 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 12:41:06.288  4501  4501 D BtGatt.GattService: stop()
08-29 12:41:06.288  4501  4501 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 12:41:06.289  5736  5736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 12:41:06.289  4501  4501 V BluetoothAdapterState: isTurningOff()=false
08-29 12:41:06.289  4501  4501 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:06.289  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:06.289  4501  4501 V BluetoothAdapterState: isBleTurningOff()=true
08-29 12:41:06.290  4501  4573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 12:41:06.290  4501  4573 D BluetoothAdapterProperties: Setting state to 10
08-29 12:41:06.290  4501  4573 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 12:41:06.290  4501  4573 I BluetoothAdapterState: Entering OffState
08-29 12:41:06.291   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-29 12:41:06.294  3702  3702 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 12:41:06.298  4501  4501 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 12:41:06.298  4501  4501 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 12:41:06.298  4501  4501 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 12:41:06.299  4501  4574 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 12:41:06.301  4501  4574 D bt_stack_manager: event_clean_up_stack finished.
08-29 12:41:06.304  4501  4501 I art     : System.exit called, status: 0
08-29 12:41:06.304  4501  4501 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 12:41:06.307   928  3049 D wifi    : In wifi stop Hal
08-29 12:41:06.307   928  3049 D wifi    : halHandle = 0x7f97bf9a00, mVM = 0x7fb408d140, mCls = 0x100b9a
08-29 12:41:06.307   928  3735 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 12:41:06.307   928  3735 D WifiHAL : Got a signal to exit!!!
08-29 12:41:06.307   928  3735 I WifiHAL : Exit wifi_event_loop
08-29 12:41:06.307  4320  4320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 12:41:06.307   928  3049 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 12:41:06.307   928  3049 E WifiHAL : Event processing terminated
08-29 12:41:06.308   928  3049 D wifi    : In wifi cleaned up handler
08-29 12:41:06.308   928  3049 I WifiHAL : Internal cleanup completed
08-29 12:41:06.309  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:06.309  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:06.310  3568  4062 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 12:41:06.316  5736  5736 D DockEventReceiver: finishStartingService: stopping service
08-29 12:41:06.317   928  3686 I ActivityManager: Killing 5384:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
08-29 12:41:06.325   928  3735 D wifi    : set interface wlan0 flags (DOWN)
08-29 12:41:06.325   928  3049 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 12:41:06.366   928  4049 I ActivityManager: Process com.android.bluetooth (pid 4501) has died
,08-29 12:41:06.388  3940  3940 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 12:41:06.391  3940  3940 D SystemUpdateService: onCreate
,08-29 12:41:06.395  3940  3940 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 12:41:06.397  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 12:41:06.398  3940  5800 I SystemUpdateService: active receiver: enabled
,08-29 12:41:06.403  3940  3940 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 12:41:06.408  3940  5381 I iu.UploadsManager: num queued entries: 0
,08-29 12:41:06.408  3940  5381 I iu.UploadsManager: num updated entries: 0
08-29 12:41:06.409  3940  5381 I iu.SyncManager: NEXT; no task
,08-29 12:41:06.410  3940  3940 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 12:41:06.412  3940  3940 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 12:41:06.425   928  3257 I ActivityManager: Start proc 5802:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 12:41:06.456  5802  5802 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,08-29 12:41:06.460  5802  5802 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 12:41:06.461  3940  5800 I SystemUpdateService: showing system update notification
,08-29 12:41:06.467  5802  5802 D SprintDMHelper: simOperator: 
08-29 12:41:06.467  5802  5802 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 12:41:06.493  4320  5814 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 12:41:06.504   928  3686 I ActivityManager: Start proc 5815:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 12:41:06.514  3940  5800 V SystemUpdateService: retry (wakeup: false) in 3599885 ms
,08-29 12:41:06.519  3940  3940 D SystemUpdateService: onDestroy
,08-29 12:41:06.520   928  3646 I ActivityManager: Killing 5248:com.google.android.music:main/u0a59 (adj 15): empty #17
,08-29 12:41:06.528   928   945 D Tethering: InitialState.processMessage what=4
,08-29 12:41:06.578   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 12:41:06.592  5815  5815 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,08-29 12:41:06.637  5815  5815 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 12:41:06.648   928  4053 I ActivityManager: Killing 4597:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-29 12:41:06.679  5757  5787 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 12:41:06.698   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@79ad3e0:true
,08-29 12:41:08.918   928  3644 D WifiService: setWifiEnabled: true pid=5684, uid=10077
,08-29 12:41:08.919   928  3644 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 12:41:08.927   506   920 D SoftapController: Softap fwReload - Ok
,08-29 12:41:08.931   506   920 D CommandListener: Setting iface cfg
,08-29 12:41:08.931   506   920 D CommandListener: Trying to bring down wlan0
,08-29 12:41:08.933   506   920 D CommandListener: Clearing all IP addresses on wlan0
,08-29 12:41:08.938   928  3049 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 12:41:09.534   928  3049 D wifi    : set interface wlan0 flags (UP)
,08-29 12:41:09.540   928  3049 I WifiHAL : Initializing wifi
,08-29 12:41:09.540   928  3049 I WifiHAL : Creating socket
,08-29 12:41:09.544   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 12:41:09.548   928  3049 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-29 12:41:09.548   928  3049 D wifi    : Did set static halHandle = 0x7f97bf9a00
08-29 12:41:09.548   928  3049 D wifi    : halHandle = 0x7f97bf9a00, mVM = 0x7fb408d140, mCls = 0x20184e
08-29 12:41:09.549   928  3049 D wifi    : array field set
08-29 12:41:09.549   928  3049 I WifiNative-HAL: interface[0] = wlan0
08-29 12:41:09.551   928  5842 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=548006763008
,08-29 12:41:09.551   928  5842 D wifi    : waitForHalEvents called, vm = 0x7fb408d140, obj = 0x20184e, env = 0x7f9a0fdf00
,08-29 12:41:09.596  5843  5843 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 12:41:09.616  5843  5843 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 12:41:09.625  5843  5843 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 12:41:09.625  5843  5843 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 12:41:09.652   928  3049 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 12:41:09.658  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 12:41:09.659  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:09.659  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:09.659  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:09.659  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:09.659  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 12:41:09.659  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:09.659  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:09.659  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 12:41:09.659  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:09.659  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 12:41:09.663   928  3049 D WifiConfigStore: Loading config and enabling all networks 
,08-29 12:41:09.665  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:09.665  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:09.665  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:09.665  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:09.665  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:09.665  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 12:41:09.665  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:09.665  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:09.665  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 12:41:09.665  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:09.665  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 12:41:09.666  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:09.667  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:09.669   928  3049 D WifiConfigStore: loaded 0 passpoint configs
,08-29 12:41:09.670   928  3049 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 12:41:09.670   928  3049 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 12:41:09.671   928  3049 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 12:41:09.671   928  3049 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 12:41:09.671   928  3049 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 12:41:09.675   928  3049 D WifiNative-HAL: Setting external_sim to 1
,08-29 12:41:09.676   928  3049 D wifi    : setting dfs flag to true, 0x7f98550060
08-29 12:41:09.676  4320  4320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 12:41:09.677   928  3049 D WifiStateMachine: Setting OUI to DA-A1-19
,08-29 12:41:09.677   928  3049 D wifi    : setting scan oui 0x7f98550060
08-29 12:41:09.677   928  3049 D WifiHAL : Sending mac address OUI
,08-29 12:41:09.692   928  3049 E native  : do suspend true
,08-29 12:41:09.697   928   928 D RttService: SCAN_AVAILABLE : 3
08-29 12:41:09.697   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 12:41:09.697   928  3049 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 12:41:09.697   928  3161 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 12:41:09.698   506   920 D CommandListener: Setting iface cfg
,08-29 12:41:09.702   928  3048 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,08-29 12:41:09.702   928  3048 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 12:41:09.704   928  3048 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 12:41:09.709   928  3048 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 12:41:09.727   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=177204 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,08-29 12:41:11.924   928  3255 D WifiService: setWifiEnabled: false pid=5684, uid=10077
08-29 12:41:11.924   928  3255 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 12:41:11.946   928   928 D RttService: SCAN_AVAILABLE : 1
,08-29 12:41:11.946   928  3161 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 12:41:11.960   928  3049 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 12:41:11.960   506   920 D CommandListener: Clearing all IP addresses on wlan0
,08-29 12:41:11.964   928  3049 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 12:41:11.966  5843  5843 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
08-29 12:41:11.970  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 12:41:11.970  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:11.970  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:11.970  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:11.970  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 12:41:11.970  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 12:41:11.970  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:11.970  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:11.970  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 12:41:11.971  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:11.971  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 12:41:11.974  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 12:41:11.974  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:11.974  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:11.974  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:11.974  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 12:41:11.974  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 12:41:11.974  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:11.974  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:11.974  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 12:41:11.974  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:11.975  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 12:41:11.992  5843  5843 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 12:41:12.004  5843  5843 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 12:41:12.006  5843  5843 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 12:41:12.110  4320  4320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 12:41:12.111   928  3049 D wifi    : In wifi stop Hal
,08-29 12:41:12.113   928  3049 D wifi    : halHandle = 0x7f97bf9a00, mVM = 0x7fb408d140, mCls = 0x20184e
08-29 12:41:12.114   928  5842 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 12:41:12.114   928  5842 D WifiHAL : Got a signal to exit!!!
08-29 12:41:12.114   928  5842 I WifiHAL : Exit wifi_event_loop
,08-29 12:41:12.116   928  3049 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,08-29 12:41:12.116   928  3049 E WifiHAL : Event processing terminated
,08-29 12:41:12.117   928  3049 D wifi    : In wifi cleaned up handler
08-29 12:41:12.117   928  3049 I WifiHAL : Internal cleanup completed
08-29 12:41:12.117  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:12.120  3568  4062 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 12:41:12.122  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:12.151   928  5842 D wifi    : set interface wlan0 flags (DOWN)
,08-29 12:41:12.152   928  3049 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 12:41:12.361   928   945 D Tethering: InitialState.processMessage what=4
,08-29 12:41:12.366   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 12:41:14.965   928   945 I ActivityManager: Start proc 5850:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 12:41:15.052  5850  5850 D AdapterServiceConfig: Adding HeadsetService
,08-29 12:41:15.052  5850  5850 D AdapterServiceConfig: Adding A2dpService
08-29 12:41:15.052  5850  5850 D AdapterServiceConfig: Adding HidService
08-29 12:41:15.052  5850  5850 D AdapterServiceConfig: Adding HealthService
08-29 12:41:15.052  5850  5850 D AdapterServiceConfig: Adding PanService
08-29 12:41:15.052  5850  5850 D AdapterServiceConfig: Adding GattService
,08-29 12:41:15.053  5850  5850 D AdapterServiceConfig: Adding BluetoothMapService
08-29 12:41:15.053  5850  5850 D AdapterServiceConfig: Adding SapService
,08-29 12:41:15.066   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5d63a0e:true
,08-29 12:41:15.066  5850  5850 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 12:41:15.070  5850  5850 I bt_bluedroid: init
,08-29 12:41:15.070  5850  5862 I BluetoothAdapterState: Entering OffState
,08-29 12:41:15.073  5850  5863 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 12:41:15.073  5850  5863 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 12:41:15.073  5850  5863 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 12:41:15.073  5850  5863 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 12:41:15.074  5850  5850 I bt_bluedroid: get_profile_interface socket
,08-29 12:41:15.076  5850  5850 I bt_bluedroid: get_profile_interface sdp
08-29 12:41:15.076  5850  5866 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 12:41:15.079  5850  5866 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 12:41:15.081  5850  5861 I bt_bluedroid: config_hci_snoop_log
,08-29 12:41:15.082   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 12:41:15.086  5850  5862 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 12:41:15.086  5850  5862 D BluetoothAdapterProperties: Setting state to 14
08-29 12:41:15.086  5850  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 12:41:15.088  5850  5862 D BluetoothBondStateMachine: make
,08-29 12:41:15.090  5850  5867 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 12:41:15.093  5850  5862 I BluetoothAdapterState: Entering PendingCommandState
,08-29 12:41:15.094  5850  5850 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 12:41:15.096  5850  5850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
08-29 12:41:15.096  5850  5850 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 12:41:15.097  5850  5850 D BtGatt.GattService: Received start request. Starting profile...
,08-29 12:41:15.097  5850  5850 D BtGatt.GattService: start()
08-29 12:41:15.097  5850  5850 I bt_bluedroid: get_profile_interface gatt
08-29 12:41:15.098  5850  5850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
08-29 12:41:15.098  5850  5850 D BtGatt.AdvertiseManager: advertise manager created
,08-29 12:41:15.103  5850  5850 V BluetoothAdapterState: isTurningOff()=false
,08-29 12:41:15.103  5850  5850 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:15.103  5850  5850 V BluetoothAdapterState: isBleTurningOn()=true
08-29 12:41:15.103  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:15.103  5850  5862 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 12:41:15.104  5850  5862 I bt_bluedroid: enable
08-29 12:41:15.104  5850  5863 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 12:41:15.104  5850  5863 I bt_hci  : start_up
,08-29 12:41:15.109  5850  5863 I bt_vendor: alloc value 0xf3b2904d
,08-29 12:41:15.109  5850  5863 I bt_vendor: init
08-29 12:41:15.109  5850  5863 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 12:41:15.109  5850  5863 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 12:41:15.227  5850  5863 D bt_hci  : start_up starting async portion
,08-29 12:41:15.228  5850  5870 I bt_hci  : event_finish_startup
08-29 12:41:15.228  5850  5870 I bt_hci_h4: hal_open
08-29 12:41:15.228  5850  5870 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 12:41:15.222  5871  5871 W irq/448-msm_hs_: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 12:41:15.232  5850  5870 I bt_userial_vendor: device fd = 51 open
,08-29 12:41:15.246  5850  5870 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 12:41:15.248  5850  5870 D bt_hwcfg: Chipset BCM4358A3
,08-29 12:41:15.249  5850  5870 D bt_hwcfg: Target name = [BCM4358A3]
,08-29 12:41:15.249  5850  5870 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 12:41:15.643  5850  5870 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 12:41:15.644  5850  5870 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 12:41:15.644  5850  5870 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 12:41:15.777  5850  5870 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 12:41:15.778  5850  5870 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 12:41:15.779  5850  5870 I bt_hwcfg: vendor lib fwcfg completed
,08-29 12:41:15.779  5850  5870 I bt_vendor: firmware callback
,08-29 12:41:15.779  5850  5870 I bt_hci  : firmware_config_callback
,08-29 12:41:15.788  5850  5873 I bt_btu  : btu_task pending for preload complete event
,08-29 12:41:15.788  5850  5873 I bt_btu_task: Bluetooth chip preload is complete
08-29 12:41:15.788  5850  5873 I bt_btu  : btu_task received preload complete event
,08-29 12:41:15.794  5850  5873 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 12:41:15.795  5850  5873 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 12:41:15.795  5850  5873 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 12:41:15.795  5850  5873 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 12:41:15.795  5850  5873 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 12:41:15.795  5850  5873 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 12:41:15.795  5850  5873 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 12:41:15.795  5850  5873 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 12:41:15.795  5850  5873 I         : BTE_InitTraceLevels -- TRC_GAP
,08-29 12:41:15.796  5850  5873 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 12:41:15.796  5850  5873 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 12:41:15.796  5850  5873 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 12:41:15.796  5850  5873 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 12:41:15.796  5850  5873 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 12:41:15.796  5850  5873 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 12:41:15.878  5850  5873 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3aa6c99
,08-29 12:41:15.878  5850  5873 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3aa6c99 
,08-29 12:41:15.891  5850  5866 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 12:41:15.892  5850  5866 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 12:41:15.894  5850  5866 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 12:41:15.897  5850  5866 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 12:41:15.900  5850  5866 D BluetoothAdapterProperties: Scan Mode:20
,08-29 12:41:15.900  5850  5866 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 12:41:15.901  5850  5866 D bt_hci  : do_postload posting postload work item
08-29 12:41:15.901  5850  5870 I bt_hci  : event_postload
08-29 12:41:15.901  5850  5870 I bt_vendor: sco_config_cb
08-29 12:41:15.901  5850  5870 I bt_hci  : sco_config_callback postload finished.
,08-29 12:41:15.906  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:15.908  5850  5870 I bt_vendor: low_power_mode_cb
08-29 12:41:15.909  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:15.910  5850  5866 D bt_bte_conf: Device ID record 1 : primary
08-29 12:41:15.910  5850  5866 D bt_bte_conf:   vendorId            = 000f
08-29 12:41:15.910  5850  5866 D bt_bte_conf:   vendorIdSource      = 0001
08-29 12:41:15.911  5850  5866 D bt_bte_conf:   product             = 1200
08-29 12:41:15.911  5850  5866 D bt_bte_conf:   version             = 1436
08-29 12:41:15.911  5850  5866 D bt_bte_conf:   clientExecutableURL = 
08-29 12:41:15.911  5850  5866 D bt_bte_conf:   serviceDescription  = 
08-29 12:41:15.911  5850  5866 D bt_bte_conf:   documentationURL    = 
08-29 12:41:15.911  5850  5866 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 12:41:15.911  5850  5863 D bt_stack_manager: event_start_up_stack finished
08-29 12:41:15.912  5850  5862 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 12:41:15.913  5850  5862 D BluetoothAdapterProperties: Setting state to 15
08-29 12:41:15.913  5850  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 12:41:15.914  5850  5862 I BluetoothAdapterState: Entering BleOnState
,08-29 12:41:15.917  5850  5862 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 12:41:15.917  5850  5862 D BluetoothAdapterProperties: Setting state to 11
08-29 12:41:15.917  5850  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 12:41:15.922  5850  5850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
,08-29 12:41:15.923  5850  5850 D HeadsetService: Received start request. Starting profile...
,08-29 12:41:15.925  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:15.926  5850  5850 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 12:41:15.926  5850  5850 D HeadsetStateMachine: make
08-29 12:41:15.927  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:15.935  5850  5862 I BluetoothAdapterState: Entering PendingCommandState
,08-29 12:41:15.936  5850  5850 D HeadsetStateMachine: max_hf_connections = 1
08-29 12:41:15.936  5850  5850 I bt_bluedroid: get_profile_interface handsfree
08-29 12:41:15.937  5850  5866 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 12:41:15.937  5850  5866 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,08-29 12:41:15.939  5850  5850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
,08-29 12:41:15.940  5850  5850 D A2dpService: Received start request. Starting profile...
08-29 12:41:15.940  5850  5850 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 12:41:15.941  5850  5850 I bt_bluedroid: get_profile_interface avrcp
,08-29 12:41:15.946  5850  5850 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 12:41:15.946  5850  5850 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 12:41:15.946  5850  5850 D A2dpStateMachine: make
08-29 12:41:15.947  5850  5850 I bt_bluedroid: get_profile_interface a2dp
,08-29 12:41:15.948  5850  5866 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 12:41:15.949  5850  5882 D A2dpStateMachine: Enter Disconnected: -2
,08-29 12:41:15.950  5850  5850 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 12:41:15.951  5850  5850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
08-29 12:41:15.952  3702  3702 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 12:41:15.953  5850  5850 D HidService: Received start request. Starting profile...
,08-29 12:41:15.953  5736  5736 D BluetoothInputDevice: Proxy object connected
08-29 12:41:15.954  5850  5850 I bt_bluedroid: get_profile_interface hidhost
08-29 12:41:15.954  5850  5866 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a882d9
08-29 12:41:15.954  5850  5850 D HidService: setHidService(): set to: null
08-29 12:41:15.954  5850  5866 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-29 12:41:15.954  5736  5736 D HidProfile: Bluetooth service connected
08-29 12:41:15.954  5850  5850 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 12:41:15.955  5850  5850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
08-29 12:41:15.956  5850  5850 D HealthService: Received start request. Starting profile...
,08-29 12:41:15.957  5850  5850 I bt_bluedroid: get_profile_interface health
,08-29 12:41:15.958  5850  5850 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 12:41:15.958  5850  5850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
08-29 12:41:15.959  5736  5736 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 12:41:15.960  5850  5850 D PanService: Received start request. Starting profile...
08-29 12:41:15.960  5850  5850 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 12:41:15.960  5850  5850 I bt_bluedroid: get_profile_interface pan
08-29 12:41:15.960  5736  5736 D PanProfile: Bluetooth service connected
08-29 12:41:15.960  5850  5866 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 12:41:15.964  5850  5850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
,08-29 12:41:15.965  5736  5736 D BluetoothMap: Proxy object connected
08-29 12:41:15.965  5850  5850 D BluetoothMapService: Received start request. Starting profile...
08-29 12:41:15.965  5850  5850 D BluetoothMapService: start()
08-29 12:41:15.965  5736  5736 D MapProfile: Bluetooth service connected
08-29 12:41:15.965  5736  5736 D BluetoothMap: getConnectedDevices()
08-29 12:41:15.966  5736  5736 D BluetoothMap: Bluetooth is Not enabled
,08-29 12:41:15.967  5850  5850 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 12:41:15.968  5850  5850 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 12:41:15.968  5850  5850 D BluetoothMapAppObserver: createReceiver()
08-29 12:41:15.969  5850  5850 D BluetoothMapAppObserver: initObservers()
08-29 12:41:15.969  5850  5850 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 12:41:15.975  5850  5850 V SapService: SapBinder()
,08-29 12:41:15.976  5850  5850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
08-29 12:41:15.976  5850  5850 D SapService: Received start request. Starting profile...
08-29 12:41:15.976  5850  5850 V SapService: start()
,08-29 12:41:15.978  5850  5850 V BluetoothAdapterState: isTurningOff()=false
,08-29 12:41:15.978  5850  5850 V BluetoothAdapterState: isTurningOn()=true
08-29 12:41:15.978  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:15.978  5850  5880 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 12:41:15.978  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:15.978  5850  5850 V BluetoothAdapterState: isTurningOff()=false
08-29 12:41:15.978  5850  5850 V BluetoothAdapterState: isTurningOn()=true
08-29 12:41:15.978  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:15.978  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 12:41:15.979  5850  5850 V BluetoothAdapterState: isTurningOff()=false
08-29 12:41:15.979  5850  5850 V BluetoothAdapterState: isTurningOn()=true
08-29 12:41:15.979  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:15.979  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:15.979  5850  5850 V BluetoothAdapterState: isTurningOff()=false
08-29 12:41:15.979  5850  5850 V BluetoothAdapterState: isTurningOn()=true
08-29 12:41:15.979  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:15.979  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:15.979  5850  5850 V BluetoothAdapterState: isTurningOff()=false
08-29 12:41:15.979  5850  5850 V BluetoothAdapterState: isTurningOn()=true
08-29 12:41:15.979  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:15.979  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:15.980  5850  5850 V BluetoothAdapterState: isTurningOff()=false
08-29 12:41:15.980  5850  5850 V BluetoothAdapterState: isTurningOn()=true
,08-29 12:41:15.980  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:15.980  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:15.980  5850  5850 V BluetoothAdapterState: isTurningOff()=false
08-29 12:41:15.980  5850  5850 V BluetoothAdapterState: isTurningOn()=true
08-29 12:41:15.980  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:15.981  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:15.981  5850  5862 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-29 12:41:15.981  5850  5862 D BluetoothAdapterProperties: ScanMode =  20
08-29 12:41:15.981  5850  5862 D BluetoothAdapterProperties: State =  11
08-29 12:41:15.981  5850  5862 D BluetoothAdapterProperties: Setting state to 12
08-29 12:41:15.981  5850  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 12:41:15.982  5850  5862 I BluetoothAdapterState: Entering OnState
08-29 12:41:15.982  5736  5746 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 12:41:15.984  5850  5866 D BluetoothAdapterProperties: Scan Mode:21
08-29 12:41:15.984  5850  5866 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 12:41:15.986  3231  3242 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 12:41:15.988  3231  3231 D BluetoothInputDevice: Proxy object connected
08-29 12:41:15.988  3231  3243 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 12:41:15.988  3231  3231 D HidProfile: Bluetooth service connected
08-29 12:41:15.989  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:15.989  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:15.989  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:15.989  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 12:41:15.989  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:15.989  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:15.989  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:15.989  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 12:41:15.990  5736  5747 D BluetoothPan: onBluetoothStateChange on: true
08-29 12:41:15.990  3231  3243 D BluetoothMap: onBluetoothStateChange: up=true
08-29 12:41:15.991  3231  3231 D BluetoothA2dp: Proxy object connected
08-29 12:41:15.991  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 12:41:15.992  3231  3243 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 12:41:15.993   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 12:41:15.993  5736  5746 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 12:41:15.994   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 12:41:15.994  3231  3231 D BluetoothMap: Proxy object connected
08-29 12:41:15.994  3231  3231 D MapProfile: Bluetooth service connected
08-29 12:41:15.994  3231  3231 D BluetoothMap: getConnectedDevices()
08-29 12:41:15.994   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 12:41:15.994   928   928 D BluetoothA2dp: Proxy object connected
08-29 12:41:15.994  5736  5747 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 12:41:15.994  5850  5850 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 12:41:15.995  3231  3873 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 12:41:15.995  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:15.995  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:15.995  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:15.995  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 12:41:15.995  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:15.995  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:15.995  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:15.995  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 12:41:15.995  5850  5850 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 12:41:15.995   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 12:41:15.995  3231  3243 D BluetoothPan: onBluetoothStateChange on: true
08-29 12:41:15.996  5850  5850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 12:41:15.997  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 12:41:15.998  3622  3641 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 12:41:15.998  3231  3231 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 12:41:15.998  3231  3231 D PanProfile: Bluetooth service connected
08-29 12:41:15.999  5850  5850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 12:41:15.999   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 12:41:16.001  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:16.002  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:16.003  5736  5736 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 12:41:16.003  5850  5850 D ObexServerSockets: Succeed to create listening sockets 
08-29 12:41:16.003  5850  5850 D ObexServerSockets0: startAccept()
08-29 12:41:16.003  5850  5850 D ObexServerSockets0: prepareForNewConnect()
08-29 12:41:16.005  5850  5850 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 12:41:16.005  5850  5850 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 12:41:16.005  5850  5888 D ObexServerSockets0: Accepting socket connection...
08-29 12:41:16.006  5850  5850 D BluetoothMapService: onReceive
,08-29 12:41:16.006  5850  5850 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 12:41:16.006  5850  5850 D BluetoothMapService: STATE_ON
08-29 12:41:16.006  5850  5889 D ObexServerSockets0: Accepting socket connection...
,08-29 12:41:16.008  5850  5890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 12:41:16.008  5736  5736 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 12:41:16.009  5850  5890 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,08-29 12:41:16.009  5850  5890 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 12:41:16.015  5736  5736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 12:41:16.017  5736  5736 D BluetoothA2dp: Proxy object connected
,08-29 12:41:16.020  3702  3702 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 12:41:16.025  5736  5736 D DockEventReceiver: finishStartingService: stopping service
,08-29 12:41:16.031  5736  5736 D BluetoothPbap: Proxy object connected
,08-29 12:41:16.032  5736  5736 D PbapServerProfile: Bluetooth service connected
08-29 12:41:16.032  3231  3231 D BluetoothPbap: Proxy object connected
08-29 12:41:16.032  3231  3231 D PbapServerProfile: Bluetooth service connected
,08-29 12:41:16.035  5850  5850 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 12:41:16.035  5850  5850 D ObexServerSockets0: prepareForNewConnect()
08-29 12:41:16.037  5850  5894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 12:41:16.049  5850  5898 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 12:41:16.050  5850  5898 I BtOppRfcommListener: Accept thread started.
,08-29 12:41:16.095  3231  3243 D BluetoothHeadset: Proxy object connected
,08-29 12:41:16.095  3231  3873 D BluetoothHeadset: Proxy object connected
08-29 12:41:16.095  3231  3231 D HeadsetProfile: Bluetooth service connected
08-29 12:41:16.095   928   928 D BluetoothHeadset: Proxy object connected
08-29 12:41:16.095   928   945 D BluetoothHeadset: Proxy object connected
08-29 12:41:16.095   928   928 D BluetoothHeadset: Proxy object connected
08-29 12:41:16.095   928   928 D BluetoothHeadset: Proxy object connected
08-29 12:41:16.096  3622  3908 D BluetoothHeadset: Proxy object connected
,08-29 12:41:16.098  3231  3231 D HeadsetProfile: Bluetooth service connected
,08-29 12:41:16.099  3622  3640 D BluetoothHeadset: Proxy object connected
,08-29 12:41:16.111  5736  5747 D BluetoothHeadset: Proxy object connected
,08-29 12:41:16.112  5736  5736 D HeadsetProfile: Bluetooth service connected
,08-29 12:41:17.940  5850  5862 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 12:41:17.941  5850  5862 D BluetoothAdapterProperties: Setting state to 13
08-29 12:41:17.941  5850  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 12:41:17.942  5850  5862 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 12:41:17.944  5850  5862 I BluetoothAdapterState: Entering PendingCommandState
,08-29 12:41:17.947  5850  5866 D BluetoothAdapterProperties: Scan Mode:20
,08-29 12:41:17.948  5850  5862 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 12:41:17.949  5850  5850 D BluetoothMapService: onReceive
,08-29 12:41:17.949  5850  5850 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 12:41:17.950  5850  5850 D BluetoothMapService: STATE_TURNING_OFF
,08-29 12:41:17.951  5850  5850 D BluetoothMapService: MAP Service closeService in
08-29 12:41:17.951  5850  5850 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 12:41:17.951  5850  5850 D ObexServerSockets0: shutdown(block = true)
08-29 12:41:17.952  5850  5888 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-29 12:41:17.956  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:17.956  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:17.956  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:17.956  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:17.956  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 12:41:17.956  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 12:41:17.956  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:17.956  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:17.956  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 12:41:17.957  5850  5850 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 12:41:17.958  5850  5850 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 12:41:17.958  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 12:41:17.958  5850  5889 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 12:41:17.959  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 12:41:17.960  5736  5736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 12:41:17.960  5850  5875 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-29 12:41:17.975  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:17.975  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:17.975  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:17.975  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:17.975  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 12:41:17.975  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 12:41:17.975  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:17.975  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:17.975  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 12:41:17.976  5850  5850 I BtOppRfcommListener: stopping Accept Thread
08-29 12:41:17.976  5850  5898 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 12:41:17.976  5850  5898 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 12:41:17.977  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 12:41:17.977  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 12:41:17.978  5850  5850 D HeadsetService: Received stop request...Stopping profile...
08-29 12:41:17.979  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:17.979  5736  5736 D DockEventReceiver: finishStartingService: stopping service
08-29 12:41:17.981  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:17.981  3231  3873 D BluetoothHeadset: Proxy object disconnected
08-29 12:41:17.981   928   928 D BluetoothHeadset: Proxy object disconnected
,08-29 12:41:17.981   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 12:41:17.981   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 12:41:17.981  3622  3641 D BluetoothHeadset: Proxy object disconnected
08-29 12:41:17.982  5736  5747 D BluetoothHeadset: Proxy object disconnected
08-29 12:41:17.982  5736  5736 D HeadsetProfile: Bluetooth service disconnected
08-29 12:41:17.983  5850  5850 D A2dpService: Received stop request...Stopping profile...
08-29 12:41:17.983  5850  5882 D A2dpStateMachine: Exit Disconnected: -1
,08-29 12:41:17.984   928   928 D BluetoothA2dp: Proxy object disconnected
08-29 12:41:17.984  5736  5736 D BluetoothA2dp: Proxy object disconnected
08-29 12:41:17.987  3702  3702 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 12:41:17.989  5850  5850 D HidService: Received stop request...Stopping profile...
08-29 12:41:17.989  5850  5850 D HidService: Stopping Bluetooth HidService
08-29 12:41:17.990  5850  5850 V BluetoothAdapterState: isTurningOff()=true
08-29 12:41:17.991  5850  5850 V BluetoothAdapterState: isTurningOn()=false
,08-29 12:41:17.991  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:17.991  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:17.992  5850  5850 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 12:41:17.992  5850  5850 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 12:41:17.992  5850  5873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 12:41:17.992  5850  5873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 12:41:17.992  5850  5873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 12:41:17.993  5850  5850 D HealthService: Received stop request...Stopping profile...
08-29 12:41:17.993  5850  5866 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 12:41:17.993  5850  5866 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 12:41:17.994  5736  5736 D BluetoothInputDevice: Proxy object disconnected
08-29 12:41:17.994  5736  5736 D HidProfile: Bluetooth service disconnected
08-29 12:41:17.999  3231  3231 D HeadsetProfile: Bluetooth service disconnected
,08-29 12:41:17.999  3231  3231 D BluetoothA2dp: Proxy object disconnected
08-29 12:41:17.999  3231  3231 D BluetoothInputDevice: Proxy object disconnected
08-29 12:41:17.999  3231  3231 D HidProfile: Bluetooth service disconnected
,08-29 12:41:18.000  5850  5850 V BluetoothAdapterState: isTurningOff()=true
,08-29 12:41:18.001  5850  5850 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:18.001  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:18.001  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:18.001  5850  5866 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 12:41:18.002  5850  5873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 12:41:18.002  5850  5873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 12:41:18.002  5850  5873 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 12:41:18.002  5850  5873 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 12:41:18.002  5850  5873 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 12:41:18.002  5850  5850 D PanService: Received stop request...Stopping profile...
,08-29 12:41:18.002  5850  5873 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 12:41:18.003  3231  3231 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 12:41:18.003  5736  5736 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 12:41:18.003  3231  3231 D PanProfile: Bluetooth service disconnected
08-29 12:41:18.003  5736  5736 D PanProfile: Bluetooth service disconnected
08-29 12:41:18.004  5736  5736 D BluetoothPbap: Proxy object disconnected
08-29 12:41:18.004  3231  3231 D BluetoothPbap: Proxy object disconnected
08-29 12:41:18.004  5736  5736 D PbapServerProfile: Bluetooth service disconnected
,08-29 12:41:18.004  3231  3231 D PbapServerProfile: Bluetooth service disconnected
,08-29 12:41:18.006  5850  5850 D BluetoothMapService: Received stop request...Stopping profile...
08-29 12:41:18.006  5850  5850 D BluetoothMapService: stop()
,08-29 12:41:18.006  5850  5850 D BluetoothMapAppObserver: deinitObservers()
,08-29 12:41:18.007  5850  5850 D BluetoothMapAppObserver: removeReceiver()
08-29 12:41:18.008  3231  3231 D BluetoothMap: Proxy object disconnected
08-29 12:41:18.008  3231  3231 D MapProfile: Bluetooth service disconnected
08-29 12:41:18.008  5850  5850 V BluetoothAdapterState: isTurningOff()=true
08-29 12:41:18.008  5850  5850 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:18.008  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:18.008  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:18.008  5850  5850 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-29 12:41:18.008  5850  5850 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 12:41:18.008  5850  5866 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 12:41:18.009  5850  5850 D SapService: Received stop request...Stopping profile...
08-29 12:41:18.009  5850  5850 V SapService: stop()
,08-29 12:41:18.011  5736  5736 D BluetoothMap: Proxy object disconnected
,08-29 12:41:18.011  5736  5736 D MapProfile: Bluetooth service disconnected
08-29 12:41:18.011  5850  5850 V BluetoothAdapterState: isTurningOff()=true
08-29 12:41:18.011  5850  5850 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:18.011  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:18.011  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:18.011  5850  5850 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 12:41:18.012  5850  5866 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 12:41:18.012  5850  5850 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 12:41:18.012  5850  5850 V BluetoothAdapterState: isTurningOff()=true
08-29 12:41:18.012  5850  5850 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:18.012  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:18.012  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:18.012  5850  5850 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 12:41:18.013  5850  5850 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 12:41:18.014  5850  5850 D BluetoothMapService: MAP Service closeService in
,08-29 12:41:18.014  5850  5850 V BluetoothAdapterState: isTurningOff()=true
08-29 12:41:18.014  5850  5850 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:18.014  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 12:41:18.014  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:18.014  5850  5850 D BluetoothMapService: cleanup()
08-29 12:41:18.014  5850  5850 D BluetoothMapService: MAP Service closeService in
,08-29 12:41:18.014  5850  5850 V BluetoothAdapterState: isTurningOff()=true
08-29 12:41:18.014  5850  5850 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:18.015  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:18.015  5850  5850 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:18.015  5850  5862 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 12:41:18.015  5850  5862 D BluetoothAdapterProperties: Setting state to 15
08-29 12:41:18.015  5850  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 12:41:18.016  5850  5862 I BluetoothAdapterState: Entering BleOnState
08-29 12:41:18.016  5736  5747 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 12:41:18.016  3231  3242 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 12:41:18.017  5736  5746 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 12:41:18.017  3231  3873 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 12:41:18.018  5736  5747 D BluetoothPan: onBluetoothStateChange on: false
08-29 12:41:18.018  3231  3243 D BluetoothMap: onBluetoothStateChange: up=false
08-29 12:41:18.019  3231  3242 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 12:41:18.019   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 12:41:18.019  5736  5746 D BluetoothMap: onBluetoothStateChange: up=false
08-29 12:41:18.020   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 12:41:18.020   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 12:41:18.020  5736  5747 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 12:41:18.020  5736  5746 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 12:41:18.021  3231  3873 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 12:41:18.021   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 12:41:18.021  3231  3243 D BluetoothPan: onBluetoothStateChange on: false
08-29 12:41:18.021  3622  3908 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 12:41:18.022  5850  5862 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 12:41:18.022  5850  5862 D BluetoothAdapterProperties: Setting state to 16
08-29 12:41:18.022  5850  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 12:41:18.022  5850  5862 D BluetoothAdapterProperties: onBleDisable
08-29 12:41:18.023  5850  5862 I BluetoothAdapterState: Entering PendingCommandState
08-29 12:41:18.023  5850  5863 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 12:41:18.024  5850  5873 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 12:41:18.024  5850  5866 D BluetoothAdapterProperties: Scan Mode:20
08-29 12:41:18.024  5850  5873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 12:41:18.025  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:18.025  5736  5736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 12:41:18.027  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:18.028  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:18.030  3702  3702 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 12:41:18.030  5736  5736 D DockEventReceiver: finishStartingService: stopping service
,08-29 12:41:18.041  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:18.231  5850  5866 I bt_hci  : shut_down
,08-29 12:41:18.236  5850  5870 D bt_hwcfg: hw_epilog_process
,08-29 12:41:18.236  5850  5870 I bt_vendor: low_power_mode_cb
,08-29 12:41:18.239  5850  5870 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 12:41:18.239  5850  5870 I bt_vendor: epilog_cb
08-29 12:41:18.239  5850  5870 I bt_hci  : epilog_finished_callback
08-29 12:41:18.241  5850  5866 I bt_hci_h4: hal_close
08-29 12:41:18.242  5850  5866 I bt_userial_vendor: device fd = 51 close
,08-29 12:41:18.361  5850  5863 D bt_stack_manager: event_shut_down_stack finished.
,08-29 12:41:18.362  5850  5862 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 12:41:18.366  5850  5862 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 12:41:18.366  5850  5850 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 12:41:18.367  5850  5850 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 12:41:18.367  5850  5850 D BtGatt.GattService: stop()
08-29 12:41:18.368  5850  5850 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 12:41:18.371  5850  5850 V BluetoothAdapterState: isTurningOff()=false
,08-29 12:41:18.371  5850  5850 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:18.372  5850  5850 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:18.372  5850  5850 V BluetoothAdapterState: isBleTurningOff()=true
08-29 12:41:18.372  5850  5862 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 12:41:18.373  5850  5862 D BluetoothAdapterProperties: Setting state to 10
,08-29 12:41:18.373  5850  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 12:41:18.374  5850  5862 I BluetoothAdapterState: Entering OffState
08-29 12:41:18.375   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 12:41:18.387  5850  5850 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 12:41:18.387  5850  5850 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 12:41:18.387  5850  5850 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 12:41:18.389  5850  5863 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 12:41:18.392  5850  5863 D bt_stack_manager: event_clean_up_stack finished.
,08-29 12:41:18.395  5850  5850 I art     : System.exit called, status: 0
,08-29 12:41:18.395  5850  5850 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 12:41:18.440   928  4049 I ActivityManager: Process com.android.bluetooth (pid 5850) has died
,08-29 12:41:20.940  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 12:41:20.941  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 12:41:21.719   620   620 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 12:41:22.720   620   620 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 12:41:23.721   620   620 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 12:41:23.947  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:23.947  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@45b2fa9 added. We now have 6 listener(s)
,08-29 12:41:23.948  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:23.951  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:23.952  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@90ef92e added. We now have 7 listener(s)
08-29 12:41:23.952  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:23.954  5684  5730 I System.out: IsBluetoothEnabled
,08-29 12:41:23.959  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:23.981   928   945 I ActivityManager: Start proc 5906:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 12:41:24.039  5906  5906 D AdapterServiceConfig: Adding HeadsetService
,08-29 12:41:24.039  5906  5906 D AdapterServiceConfig: Adding A2dpService
08-29 12:41:24.039  5906  5906 D AdapterServiceConfig: Adding HidService
08-29 12:41:24.040  5906  5906 D AdapterServiceConfig: Adding HealthService
,08-29 12:41:24.040  5906  5906 D AdapterServiceConfig: Adding PanService
08-29 12:41:24.040  5906  5906 D AdapterServiceConfig: Adding GattService
08-29 12:41:24.040  5906  5906 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 12:41:24.040  5906  5906 D AdapterServiceConfig: Adding SapService
,08-29 12:41:24.050   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f101fef:true
,08-29 12:41:24.050  5906  5906 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 12:41:24.052  5906  5906 I bt_bluedroid: init
08-29 12:41:24.053  5906  5918 I BluetoothAdapterState: Entering OffState
,08-29 12:41:24.055  5906  5919 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 12:41:24.055  5906  5919 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 12:41:24.055  5906  5919 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 12:41:24.055  5906  5919 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 12:41:24.055  5906  5906 I bt_bluedroid: get_profile_interface socket
,08-29 12:41:24.057  5906  5906 I bt_bluedroid: get_profile_interface sdp
08-29 12:41:24.057  5906  5922 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 12:41:24.059  5906  5922 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 12:41:24.060  5906  5917 I bt_bluedroid: config_hci_snoop_log
08-29 12:41:24.061   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 12:41:24.065  5906  5918 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 12:41:24.065  5906  5918 D BluetoothAdapterProperties: Setting state to 14
08-29 12:41:24.065  5906  5918 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-29 12:41:24.067  5906  5918 D BluetoothBondStateMachine: make
,08-29 12:41:24.068  5906  5923 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 12:41:24.070  5906  5918 I BluetoothAdapterState: Entering PendingCommandState
,08-29 12:41:24.072  5906  5906 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 12:41:24.074  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
08-29 12:41:24.074  5906  5906 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 12:41:24.075  5906  5906 D BtGatt.GattService: Received start request. Starting profile...
08-29 12:41:24.075  5906  5906 D BtGatt.GattService: start()
08-29 12:41:24.075  5906  5906 I bt_bluedroid: get_profile_interface gatt
,08-29 12:41:24.076  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
,08-29 12:41:24.076  5906  5906 D BtGatt.AdvertiseManager: advertise manager created
,08-29 12:41:24.081  5906  5906 V BluetoothAdapterState: isTurningOff()=false
,08-29 12:41:24.081  5906  5906 V BluetoothAdapterState: isTurningOn()=false
08-29 12:41:24.081  5906  5906 V BluetoothAdapterState: isBleTurningOn()=true
08-29 12:41:24.082  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:24.082  5906  5918 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 12:41:24.082  5906  5918 I bt_bluedroid: enable
08-29 12:41:24.082  5906  5919 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 12:41:24.082  5906  5919 I bt_hci  : start_up
,08-29 12:41:24.088  5906  5919 I bt_vendor: alloc value 0xf3b2904d
,08-29 12:41:24.088  5906  5919 I bt_vendor: init
08-29 12:41:24.088  5906  5919 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 12:41:24.088  5906  5919 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 12:41:24.208  5906  5919 D bt_hci  : start_up starting async portion
,08-29 12:41:24.208  5906  5926 I bt_hci  : event_finish_startup
08-29 12:41:24.208  5906  5926 I bt_hci_h4: hal_open
,08-29 12:41:24.209  5906  5926 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 12:41:24.202  5927  5927 W irq/448-msm_hs_: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
08-29 12:41:24.212  5906  5926 I bt_userial_vendor: device fd = 51 open
,08-29 12:41:24.226  5906  5926 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 12:41:24.229  5906  5926 D bt_hwcfg: Chipset BCM4358A3
08-29 12:41:24.229  5906  5926 D bt_hwcfg: Target name = [BCM4358A3]
,08-29 12:41:24.229  5906  5926 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 12:41:24.630  5906  5926 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 12:41:24.631  5906  5926 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 12:41:24.631  5906  5926 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 12:41:24.721   620   620 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 12:41:24.765  5906  5926 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 12:41:24.765  5906  5926 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 12:41:24.766  5906  5926 I bt_hwcfg: vendor lib fwcfg completed
,08-29 12:41:24.767  5906  5926 I bt_vendor: firmware callback
,08-29 12:41:24.767  5906  5926 I bt_hci  : firmware_config_callback
,08-29 12:41:24.774  5906  5929 I bt_btu  : btu_task pending for preload complete event
,08-29 12:41:24.774  5906  5929 I bt_btu_task: Bluetooth chip preload is complete
08-29 12:41:24.775  5906  5929 I bt_btu  : btu_task received preload complete event
,08-29 12:41:24.781  5906  5929 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 12:41:24.781  5906  5929 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 12:41:24.782  5906  5929 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 12:41:24.782  5906  5929 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 12:41:24.782  5906  5929 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 12:41:24.782  5906  5929 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 12:41:24.782  5906  5929 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 12:41:24.782  5906  5929 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 12:41:24.782  5906  5929 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 12:41:24.782  5906  5929 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 12:41:24.783  5906  5929 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 12:41:24.783  5906  5929 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 12:41:24.783  5906  5929 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 12:41:24.783  5906  5929 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 12:41:24.783  5906  5929 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 12:41:24.865  5906  5929 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3aa6c99
08-29 12:41:24.865  5906  5929 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3aa6c99 
,08-29 12:41:24.877  5906  5922 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 12:41:24.878  5906  5922 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 12:41:24.879  5906  5922 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 12:41:24.882  5906  5922 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 12:41:24.884  5906  5922 D BluetoothAdapterProperties: Scan Mode:20
,08-29 12:41:24.885  5906  5922 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 12:41:24.885  5906  5922 D bt_hci  : do_postload posting postload work item
08-29 12:41:24.885  5906  5926 I bt_hci  : event_postload
08-29 12:41:24.886  5906  5926 I bt_vendor: sco_config_cb
08-29 12:41:24.886  5906  5926 I bt_hci  : sco_config_callback postload finished.
08-29 12:41:24.889  5906  5922 D bt_bte_conf: Device ID record 1 : primary
08-29 12:41:24.890  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:24.890  5906  5922 D bt_bte_conf:   vendorId            = 000f
08-29 12:41:24.890  5906  5922 D bt_bte_conf:   vendorIdSource      = 0001
08-29 12:41:24.890  5906  5922 D bt_bte_conf:   product             = 1200
08-29 12:41:24.890  5906  5922 D bt_bte_conf:   version             = 1436
08-29 12:41:24.890  5906  5922 D bt_bte_conf:   clientExecutableURL = 
08-29 12:41:24.890  5906  5922 D bt_bte_conf:   serviceDescription  = 
08-29 12:41:24.891  5906  5922 D bt_bte_conf:   documentationURL    = 
08-29 12:41:24.891  5906  5922 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 12:41:24.891  5906  5919 D bt_stack_manager: event_start_up_stack finished
08-29 12:41:24.892  5906  5918 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 12:41:24.893  5906  5918 D BluetoothAdapterProperties: Setting state to 15
08-29 12:41:24.893  5906  5918 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 12:41:24.896  5906  5918 I BluetoothAdapterState: Entering BleOnState
,08-29 12:41:24.898  5906  5926 I bt_vendor: low_power_mode_cb
,08-29 12:41:24.900  5906  5918 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 12:41:24.900  5906  5918 D BluetoothAdapterProperties: Setting state to 11
08-29 12:41:24.900  5906  5918 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 12:41:24.907  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
08-29 12:41:24.911  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:24.913  5906  5906 D HeadsetService: Received start request. Starting profile...
,08-29 12:41:24.917  5906  5906 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 12:41:24.918  5906  5906 D HeadsetStateMachine: make
,08-29 12:41:24.929  5906  5918 I BluetoothAdapterState: Entering PendingCommandState
,08-29 12:41:24.929  5906  5906 D HeadsetStateMachine: max_hf_connections = 1
08-29 12:41:24.929  5906  5906 I bt_bluedroid: get_profile_interface handsfree
08-29 12:41:24.930  5906  5922 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 12:41:24.930  5906  5922 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-29 12:41:24.933  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
,08-29 12:41:24.934  5906  5906 D A2dpService: Received start request. Starting profile...
,08-29 12:41:24.935  5906  5906 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 12:41:24.935  5906  5906 I bt_bluedroid: get_profile_interface avrcp
,08-29 12:41:24.941  5906  5906 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 12:41:24.942  5906  5906 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 12:41:24.942  5906  5906 D A2dpStateMachine: make
08-29 12:41:24.943  5906  5906 I bt_bluedroid: get_profile_interface a2dp
,08-29 12:41:24.943  5906  5922 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 12:41:24.945  5906  5937 D A2dpStateMachine: Enter Disconnected: -2
,08-29 12:41:24.947  5906  5906 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 12:41:24.948  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
08-29 12:41:24.948  5906  5906 D HidService: Received start request. Starting profile...
08-29 12:41:24.949  5906  5906 I bt_bluedroid: get_profile_interface hidhost
08-29 12:41:24.949  5906  5906 D HidService: setHidService(): set to: null
08-29 12:41:24.949  5906  5922 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a882d9
08-29 12:41:24.949  5906  5922 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-29 12:41:24.949  5906  5906 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 12:41:24.950  3702  3702 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 12:41:24.950  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
08-29 12:41:24.951  5906  5906 D HealthService: Received start request. Starting profile...
,08-29 12:41:24.953  5906  5906 I bt_bluedroid: get_profile_interface health
,08-29 12:41:24.955  5906  5906 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 12:41:24.956  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
08-29 12:41:24.956  5906  5906 D PanService: Received start request. Starting profile...
08-29 12:41:24.956  5906  5906 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 12:41:24.956  5906  5906 I bt_bluedroid: get_profile_interface pan
08-29 12:41:24.957  5906  5922 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 12:41:24.959  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
,08-29 12:41:24.959  5906  5906 D BluetoothMapService: Received start request. Starting profile...
,08-29 12:41:24.960  5906  5906 D BluetoothMapService: start()
,08-29 12:41:24.963  5906  5906 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 12:41:24.964  5906  5906 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 12:41:24.964  5906  5906 D BluetoothMapAppObserver: createReceiver()
08-29 12:41:24.966  5906  5906 D BluetoothMapAppObserver: initObservers()
08-29 12:41:24.966  5906  5906 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 12:41:24.972  5906  5906 V SapService: SapBinder()
,08-29 12:41:24.973  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
08-29 12:41:24.973  5906  5906 D SapService: Received start request. Starting profile...
08-29 12:41:24.973  5906  5906 V SapService: start()
,08-29 12:41:24.975  5906  5906 V BluetoothAdapterState: isTurningOff()=false
08-29 12:41:24.975  5906  5906 V BluetoothAdapterState: isTurningOn()=true
08-29 12:41:24.975  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:24.975  5906  5935 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 12:41:24.975  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:24.975  5906  5906 V BluetoothAdapterState: isTurningOff()=false
08-29 12:41:24.975  5906  5906 V BluetoothAdapterState: isTurningOn()=true
,08-29 12:41:24.975  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:24.975  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:24.975  5906  5906 V BluetoothAdapterState: isTurningOff()=false
08-29 12:41:24.975  5906  5906 V BluetoothAdapterState: isTurningOn()=true
08-29 12:41:24.975  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 12:41:24.975  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:24.976  5906  5906 V BluetoothAdapterState: isTurningOff()=false
08-29 12:41:24.976  5906  5906 V BluetoothAdapterState: isTurningOn()=true
08-29 12:41:24.976  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:24.976  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:24.976  5906  5906 V BluetoothAdapterState: isTurningOff()=false
08-29 12:41:24.976  5906  5906 V BluetoothAdapterState: isTurningOn()=true
08-29 12:41:24.976  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:24.976  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:24.976  5906  5906 V BluetoothAdapterState: isTurningOff()=false
08-29 12:41:24.976  5906  5906 V BluetoothAdapterState: isTurningOn()=true
08-29 12:41:24.976  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:24.976  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:24.977  5906  5906 V BluetoothAdapterState: isTurningOff()=false
08-29 12:41:24.977  5906  5906 V BluetoothAdapterState: isTurningOn()=true
,08-29 12:41:24.977  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
08-29 12:41:24.977  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
08-29 12:41:24.978  5906  5918 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 12:41:24.978  5906  5918 D BluetoothAdapterProperties: ScanMode =  20
08-29 12:41:24.978  5906  5918 D BluetoothAdapterProperties: State =  11
08-29 12:41:24.980  5906  5922 D BluetoothAdapterProperties: Scan Mode:21
08-29 12:41:24.980  5906  5922 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 12:41:24.980  5906  5918 D BluetoothAdapterProperties: Setting state to 12
,08-29 12:41:24.980  5906  5918 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 12:41:24.981  5906  5918 I BluetoothAdapterState: Entering OnState
08-29 12:41:24.981  5736  5747 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 12:41:24.984  3231  3243 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 12:41:24.984  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:24.984  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:24.984  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:24.984  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 12:41:24.984  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:24.984  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:24.984  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:24.984  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 12:41:24.986  5736  5746 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 12:41:24.987  3231  3231 D BluetoothInputDevice: Proxy object connected
08-29 12:41:24.987  3231  3231 D HidProfile: Bluetooth service connected
08-29 12:41:24.987  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 12:41:24.988  3231  3873 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 12:41:24.989  3231  3231 D BluetoothA2dp: Proxy object connected
08-29 12:41:24.989  5736  5746 D BluetoothPan: onBluetoothStateChange on: true
08-29 12:41:24.991  3231  3242 D BluetoothMap: onBluetoothStateChange: up=true
08-29 12:41:24.992  5906  5906 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 12:41:24.992  5906  5906 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 12:41:24.993  3231  3873 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 12:41:24.993  5906  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 12:41:24.994  5736  5736 D BluetoothA2dp: Proxy object connected
08-29 12:41:24.995   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 12:41:24.995  5736  5747 D BluetoothMap: onBluetoothStateChange: up=true
08-29 12:41:24.995  5906  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 12:41:24.996   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 12:41:24.996  5906  5906 D ObexServerSockets: Succeed to create listening sockets 
08-29 12:41:24.996  5906  5906 D ObexServerSockets0: startAccept()
08-29 12:41:24.997  5906  5906 D ObexServerSockets0: prepareForNewConnect()
08-29 12:41:24.997   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 12:41:24.997   928   928 D BluetoothA2dp: Proxy object connected
08-29 12:41:24.997  5736  5746 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 12:41:24.997  5736  5747 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 12:41:24.999  5906  5906 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 12:41:24.999  5906  5906 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 12:41:24.999  5906  5943 D ObexServerSockets0: Accepting socket connection...
08-29 12:41:24.999  5906  5944 D ObexServerSockets0: Accepting socket connection...
08-29 12:41:25.000  3231  3243 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 12:41:25.001   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 12:41:25.001  3231  3231 D BluetoothMap: Proxy object connected
08-29 12:41:25.001  3231  3231 D MapProfile: Bluetooth service connected
08-29 12:41:25.001  3231  3243 D BluetoothPan: onBluetoothStateChange on: true
08-29 12:41:25.001  3231  3231 D BluetoothMap: getConnectedDevices()
08-29 12:41:25.002  5736  5736 D BluetoothInputDevice: Proxy object connected
,08-29 12:41:25.002  5736  5736 D HidProfile: Bluetooth service connected
08-29 12:41:25.003  3622  3641 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 12:41:25.003  3231  3231 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 12:41:25.003  3231  3231 D PanProfile: Bluetooth service connected
08-29 12:41:25.005  5736  5736 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 12:41:25.005  5736  5736 D PanProfile: Bluetooth service connected
08-29 12:41:25.005  5736  5736 D BluetoothMap: Proxy object connected
08-29 12:41:25.005  5736  5736 D MapProfile: Bluetooth service connected
08-29 12:41:25.005  5736  5736 D BluetoothMap: getConnectedDevices()
08-29 12:41:25.005   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 12:41:25.006  5906  5906 D BluetoothMapService: onReceive
08-29 12:41:25.006  5906  5906 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 12:41:25.006  5906  5906 D BluetoothMapService: STATE_ON
08-29 12:41:25.007  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:25.008  5906  5946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 12:41:25.009  5906  5946 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 12:41:25.009  5906  5946 D BluetoothSdpJni: SDP Create record success - handle: 1
08-29 12:41:25.010  5736  5736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 12:41:25.016  5736  5736 D DockEventReceiver: finishStartingService: stopping service
08-29 12:41:25.016  3702  3702 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 12:41:25.023  5736  5736 D BluetoothPbap: Proxy object connected
,08-29 12:41:25.023  5736  5736 D PbapServerProfile: Bluetooth service connected
,08-29 12:41:25.031  3231  3231 D BluetoothPbap: Proxy object connected
,08-29 12:41:25.031  3231  3231 D PbapServerProfile: Bluetooth service connected
,08-29 12:41:25.032  5906  5950 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 12:41:25.041  5906  5906 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 12:41:25.041  5906  5906 D ObexServerSockets0: prepareForNewConnect()
,08-29 12:41:25.044  5906  5954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 12:41:25.046  5906  5954 I BtOppRfcommListener: Accept thread started.
,08-29 12:41:25.096  3231  3873 D BluetoothHeadset: Proxy object connected
,08-29 12:41:25.096  3231  3231 D HeadsetProfile: Bluetooth service connected
08-29 12:41:25.096   928   928 D BluetoothHeadset: Proxy object connected
08-29 12:41:25.096   928   928 D BluetoothHeadset: Proxy object connected
08-29 12:41:25.096   928   928 D BluetoothHeadset: Proxy object connected
08-29 12:41:25.097  3622  3908 D BluetoothHeadset: Proxy object connected
08-29 12:41:25.097   928   945 D BluetoothHeadset: Proxy object connected
08-29 12:41:25.097  5736  5746 D BluetoothHeadset: Proxy object connected
,08-29 12:41:25.098  5736  5747 D BluetoothHeadset: Proxy object connected
,08-29 12:41:25.099  5736  5736 D HeadsetProfile: Bluetooth service connected
08-29 12:41:25.100  5736  5736 D HeadsetProfile: Bluetooth service connected
08-29 12:41:25.100  3231  3243 D BluetoothHeadset: Proxy object connected
08-29 12:41:25.100  3231  3231 D HeadsetProfile: Bluetooth service connected
,08-29 12:41:25.101   928   945 D BluetoothHeadset: Proxy object connected
,08-29 12:41:25.104  3622  3640 D BluetoothHeadset: Proxy object connected
,08-29 12:41:25.722   620   620 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 12:41:25.974  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:25.974  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:25.974  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:25.974  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 12:41:25.974  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:25.974  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:25.974  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:25.974  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 12:41:25.978  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 12:41:25.980  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:25.981  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e04ccf added. We now have 8 listener(s)
08-29 12:41:25.981  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:25.986   928   938 D WifiService: setWifiEnabled: false pid=5684, uid=10077
08-29 12:41:25.986   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 12:41:25.991  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:25.992   928  4049 D WifiService: setWifiEnabled: true pid=5684, uid=10077
08-29 12:41:25.992   928  4049 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 12:41:25.998   506   920 D SoftapController: Softap fwReload - Ok
,08-29 12:41:26.001   506   920 D CommandListener: Setting iface cfg
,08-29 12:41:26.001   506   920 D CommandListener: Trying to bring down wlan0
08-29 12:41:26.002   506   920 D CommandListener: Clearing all IP addresses on wlan0
,08-29 12:41:26.004   928  3049 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 12:41:26.620   928  3049 D wifi    : set interface wlan0 flags (UP)
,08-29 12:41:26.626   928  3049 I WifiHAL : Initializing wifi
,08-29 12:41:26.626   928  3049 I WifiHAL : Creating socket
08-29 12:41:26.627   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 12:41:26.631   928  3049 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-29 12:41:26.632   928  3049 D wifi    : Did set static halHandle = 0x7f97bf9a00
,08-29 12:41:26.632   928  3049 D wifi    : halHandle = 0x7f97bf9a00, mVM = 0x7fb408d140, mCls = 0x201852
08-29 12:41:26.632   928  3049 D wifi    : array field set
,08-29 12:41:26.633   928  3049 I WifiNative-HAL: interface[0] = wlan0
08-29 12:41:26.637   928  5959 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=548006763008
08-29 12:41:26.638   928  5959 D wifi    : waitForHalEvents called, vm = 0x7fb408d140, obj = 0x201852, env = 0x7f95988380
,08-29 12:41:26.696  5960  5960 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 12:41:26.717  5960  5960 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 12:41:26.723   620   620 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 12:41:26.726  5960  5960 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 12:41:26.726  5960  5960 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 12:41:26.739   928  3049 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 12:41:26.745  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:26.752   928  3049 D WifiConfigStore: Loading config and enabling all networks 
,08-29 12:41:26.755  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:26.755  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:26.755  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:26.755  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:26.755  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:26.755  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:26.755  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:26.755  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 12:41:26.757  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 12:41:26.760   928  3049 D WifiConfigStore: loaded 0 passpoint configs
,08-29 12:41:26.760   928  3049 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 12:41:26.760   928  3049 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 12:41:26.761   928  3049 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 12:41:26.761   928  3049 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 12:41:26.762   928  3049 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 12:41:26.765   928  3049 D WifiNative-HAL: Setting external_sim to 1
08-29 12:41:26.765  4320  4320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 12:41:26.766   928  3049 D wifi    : setting dfs flag to true, 0x7f97bf1320
,08-29 12:41:26.766   928  3049 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 12:41:26.767   928  3049 D wifi    : setting scan oui 0x7f97bf1320
08-29 12:41:26.767   928  3049 D WifiHAL : Sending mac address OUI
,08-29 12:41:26.781   928  3049 E native  : do suspend true
,08-29 12:41:26.787   928  3049 D wifi    : android_net_wifi_setLinkLayerStats: 1
,08-29 12:41:26.787   928   928 D RttService: SCAN_AVAILABLE : 3
08-29 12:41:26.787   928  3161 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 12:41:26.791   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 12:41:26.793   506   920 D CommandListener: Setting iface cfg
,08-29 12:41:26.793   928  3048 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '75 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 75 Failed to set address (No such device)'
08-29 12:41:26.794   928  3048 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 12:41:26.800   928  3048 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 12:41:26.800   928  3048 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 12:41:26.804   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=194281 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,08-29 12:41:27.004  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 12:41:27.004  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:27.004  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:27.004  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:27.004  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:27.004  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:27.004  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:27.004  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 12:41:27.009  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 12:41:27.016  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 12:41:27.017  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 12:41:27.019  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4d63fed Bundle[{}]
08-29 12:41:27.020  5684  5730 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 12:41:27.020  5684  5730 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 12:41:27.021  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 12:41:27.021  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 12:41:27.021  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 12:41:27.022  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 12:41:27.027  5684  5730 I System.out: Running OutgoingSocketThread
,08-29 12:41:27.029  5684  5962 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 151)
,08-29 12:41:27.031  5684  5962 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48879
,08-29 12:41:27.031  5684  5962 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 12:41:28.030  5684  5730 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 152)
,08-29 12:41:28.031  5684  5730 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 152)
,08-29 12:41:28.037  5684  5730 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 157)
,08-29 12:41:28.038  5684  5730 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 12:41:28.039  5684  5730 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,08-29 12:41:28.044  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 12:41:28.045  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@801f65c added. We now have 2 listener(s)
08-29 12:41:28.047  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 12:41:28.047  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 12:41:28.047  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 12:41:28.048  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:28.048  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90e1d65 added. We now have 9 listener(s)
08-29 12:41:28.048  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:28.049  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 12:41:28.052  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 12:41:28.056  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 12:41:28.056  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:28.056  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:28.056  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:28.056  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:28.056  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:28.056  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:28.056  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 12:41:28.059  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 12:41:28.059  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 12:41:28.059  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 12:41:28.059  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3ee6eb added. We now have 3 listener(s)
,08-29 12:41:28.061  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:28.061  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 12:41:28.061  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 12:41:28.061  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 12:41:28.062  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:28.062  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e61c48 added. We now have 10 listener(s)
08-29 12:41:28.062  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:28.062  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:28.062  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 12:41:28.062  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:28.062  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:28.062  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.062  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:28.063  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 12:41:28.063  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 12:41:28.063  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@801f65c removed from the list
08-29 12:41:28.064  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:28.064  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90e1d65 removed from the list
08-29 12:41:28.064  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 12:41:28.064  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 12:41:28.065  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 12:41:28.066  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:28.068  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:28.068  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:28.068  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:28.068  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90e1d65 not in the list
08-29 12:41:28.068  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.068  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 12:41:28.070  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:28.070  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:28.070  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:28.070  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e61c48 removed from the list
08-29 12:41:28.070  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:28.070  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 12:41:28.070  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:28.071  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 12:41:28.071  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3ee6eb removed from the list
08-29 12:41:28.072  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 12:41:28.072  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7482ae1 added. We now have 2 listener(s)
,08-29 12:41:28.074  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 12:41:28.074  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 12:41:28.074  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 12:41:28.075  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:28.075  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d10006 added. We now have 9 listener(s)
08-29 12:41:28.075  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:28.076  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 12:41:28.079  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 12:41:28.084  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 12:41:28.084  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:28.084  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:28.084  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:28.084  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:28.084  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:28.084  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:28.084  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 12:41:28.086  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 12:41:28.087  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 12:41:28.087  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 12:41:28.087  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c64b4f4 added. We now have 3 listener(s)
08-29 12:41:28.088  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 12:41:28.088  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 12:41:28.089  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 12:41:28.089  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:28.089  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:28.089  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ebb941d added. We now have 10 listener(s)
08-29 12:41:28.089  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:28.089  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 12:41:28.089  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 12:41:28.089  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 12:41:28.089  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 12:41:28.089  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 12:41:28.090  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:28.092  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 12:41:28.092  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 12:41:28.095  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 12:41:28.096  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 12:41:28.096  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 12:41:28.099  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 12:41:28.099  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 12:41:28.099  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 12:41:28.100  5684  5730 D BluetoothAdapter: STATE_ON
,08-29 12:41:28.102  5906  5916 D BtGatt.GattService: registerClient() - UUID=74e1d276-9768-4833-9c4f-74d2e3cc9155
,08-29 12:41:28.103  5906  5922 D BtGatt.GattService: onClientRegistered() - UUID=74e1d276-9768-4833-9c4f-74d2e3cc9155, clientIf=5
,08-29 12:41:28.104  5684  5695 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 12:41:28.105  5906  5917 D BtGatt.GattService: start scan with filters
,08-29 12:41:28.108  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 12:41:28.109  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 12:41:28.109  5906  5925 D BtGatt.ScanManager: handling starting scan
08-29 12:41:28.109  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 12:41:28.109  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 12:41:28.111  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 12:41:28.111  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 12:41:28.112  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 12:41:28.112  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 12:41:28.113  5906  5925 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@820b9b1
08-29 12:41:28.115  5684  5730 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 12:41:28.115  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:28.115  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 12:41:28.115  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.115  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 12:41:28.115  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 12:41:28.115  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 12:41:28.115  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 12:41:28.115  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 12:41:28.115  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 12:41:28.115  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 12:41:28.116  5684  5730 D BluetoothAdapter: STATE_ON
,08-29 12:41:28.117  5906  5917 D BtGatt.GattService: stopScan() - queue size =1
,08-29 12:41:28.118  5906  5942 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 12:41:28.118  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 12:41:28.118  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 12:41:28.118  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 12:41:28.118  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 12:41:28.118  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 12:41:28.119  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 12:41:28.119  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 12:41:28.119  5906  5922 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 12:41:28.119  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 12:41:28.119  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.119  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 12:41:28.120  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 12:41:28.120  5906  5925 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 12:41:28.122  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 12:41:28.122  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 12:41:28.122  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 12:41:28.124  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 12:41:28.124  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:28.124  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:28.124  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:28.124  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.124  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 12:41:28.124  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 12:41:28.124  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7482ae1 removed from the list
08-29 12:41:28.124  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:28.124  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d10006 removed from the list
,08-29 12:41:28.124  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:28.124  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 12:41:28.125  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.125  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:28.126  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:28.126  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 12:41:28.126  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:28.126  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d10006 not in the list
08-29 12:41:28.127  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.127  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:28.127  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 12:41:28.127  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:28.127  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.127  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:28.127  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:28.128  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ebb941d removed from the list
,08-29 12:41:28.128  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:28.128  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.128  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:28.128  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 12:41:28.128  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c64b4f4 removed from the list
08-29 12:41:28.128  5906  5925 D BtGatt.ScanManager: Starting BLE batch scan
08-29 12:41:28.128  5906  5925 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 12:41:28.128  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 12:41:28.128  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e025519 added. We now have 2 listener(s)
08-29 12:41:28.130  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 12:41:28.130  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 12:41:28.130  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 12:41:28.130  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:28.130  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74209de added. We now have 9 listener(s)
08-29 12:41:28.130  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:28.131  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 12:41:28.133  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 12:41:28.136  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 12:41:28.136  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:28.136  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:28.136  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:28.136  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:28.136  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:28.136  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:28.136  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 12:41:28.137  5906  5922 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 12:41:28.138  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.138  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 12:41:28.138  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 12:41:28.138  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 12:41:28.138  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25dae8c added. We now have 3 listener(s)
08-29 12:41:28.139  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 12:41:28.139  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 12:41:28.139  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 12:41:28.140  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:28.140  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95a29d5 added. We now have 10 listener(s)
08-29 12:41:28.140  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:28.140  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 12:41:28.141  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 12:41:28.141  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 12:41:28.141  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 12:41:28.141  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 12:41:28.141  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 12:41:28.143  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 12:41:28.143  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 12:41:28.144  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:28.154  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 12:41:28.155  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 12:41:28.145  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:28.158  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 12:41:28.159  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 12:41:28.159  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 12:41:28.160  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,08-29 12:41:28.160  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.160  5906  5925 D BtGatt.ScanManager: stopping BLe Batch
,08-29 12:41:28.161  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 12:41:28.162  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 12:41:28.162  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 12:41:28.162  5684  5730 D BluetoothAdapter: STATE_ON
08-29 12:41:28.164  5906  5916 D BtGatt.GattService: registerClient() - UUID=c88bfda6-36b5-4db6-86ed-3e73d4256915
08-29 12:41:28.164  5906  5922 D BtGatt.GattService: onClientRegistered() - UUID=c88bfda6-36b5-4db6-86ed-3e73d4256915, clientIf=5
,08-29 12:41:28.164  5684  5694 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 12:41:28.165  5906  5942 D BtGatt.GattService: start scan with filters
08-29 12:41:28.166  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 12:41:28.166  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.166  5906  5925 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 12:41:28.169  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 12:41:28.170  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 12:41:28.170  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 12:41:28.170  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 12:41:28.170  5906  5922 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 12:41:28.170  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 12:41:28.172  5906  5925 D BtGatt.ScanManager: handling starting scan
,08-29 12:41:28.172  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 12:41:28.173  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 12:41:28.173  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 12:41:28.174  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 12:41:28.176  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 12:41:28.177  5684  5730 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 12:41:28.177  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:28.177  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:28.177  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:28.177  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:28.177  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.177  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 12:41:28.177  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 12:41:28.177  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e025519 removed from the list
08-29 12:41:28.177  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:28.177  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74209de removed from the list
08-29 12:41:28.177  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:28.177  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 12:41:28.178  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.178  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 12:41:28.178  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.178  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 12:41:28.179  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:28.179  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:28.179  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 12:41:28.179  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74209de not in the list
08-29 12:41:28.179  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 12:41:28.179  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 12:41:28.179  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 12:41:28.179  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 12:41:28.179  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 12:41:28.180  5684  5730 D BluetoothAdapter: STATE_ON
08-29 12:41:28.180  5906  5922 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 12:41:28.180  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.180  5906  5925 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 12:41:28.180  5906  5934 D BtGatt.GattService: stopScan() - queue size =1
08-29 12:41:28.181  5906  5917 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 12:41:28.181  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 12:41:28.181  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 12:41:28.181  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 12:41:28.181  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 12:41:28.181  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 12:41:28.183  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 12:41:28.183  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 12:41:28.183  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 12:41:28.183  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 12:41:28.183  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 12:41:28.184  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:28.184  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 12:41:28.184  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:28.184  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.184  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:28.184  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 12:41:28.184  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95a29d5 removed from the list
08-29 12:41:28.184  5906  5925 D BtGatt.ScanManager: Starting BLE batch scan
08-29 12:41:28.185  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:28.185  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 12:41:28.185  5906  5925 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 12:41:28.185  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.185  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 12:41:28.185  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:28.185  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 12:41:28.185  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25dae8c removed from the list
08-29 12:41:28.185  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 12:41:28.185  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1208e51 added. We now have 2 listener(s)
08-29 12:41:28.186  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 12:41:28.186  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 12:41:28.187  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 12:41:28.187  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:28.187  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9df76b6 added. We now have 9 listener(s)
08-29 12:41:28.187  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:28.187  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 12:41:28.189  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 12:41:28.191  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 12:41:28.191  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-,29 12:41:28.191  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:28.191  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:28.191  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:28.191  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:28.191  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:28.191  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 12:41:28.193  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 12:41:28.193  5906  5922 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 12:41:28.193  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 12:41:28.193  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.193  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 12:41:28.193  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9194324 added. We now have 3 listener(s)
,08-29 12:41:28.194  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 12:41:28.194  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 12:41:28.194  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 12:41:28.195  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:28.195  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:28.195  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40ebe8d added. We now have 10 listener(s)
08-29 12:41:28.195  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:28.195  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 12:41:28.195  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 12:41:28.195  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 12:41:28.195  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 12:41:28.195  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 12:41:28.196  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:28.197  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 12:41:28.197  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 12:41:28.198  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 12:41:28.198  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 12:41:28.199  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 12:41:28.200  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 12:41:28.200  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 12:41:28.202  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 12:41:28.203  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 12:41:28.203  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 12:41:28.203  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 12:41:28.203  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.203  5906  5925 D BtGatt.ScanManager: stopping BLe Batch
08-29 12:41:28.204  5684  5730 D BluetoothAdapter: STATE_ON
,08-29 12:41:28.206  5906  5934 D BtGatt.GattService: registerClient() - UUID=c0b39ead-b242-433d-af76-e31b21601b89
08-29 12:41:28.206  5906  5922 D BtGatt.GattService: onClientRegistered() - UUID=c0b39ead-b242-433d-af76-e31b21601b89, clientIf=5
,08-29 12:41:28.207  5684  5695 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 12:41:28.207  5906  5916 D BtGatt.GattService: start scan with filters
,08-29 12:41:28.208  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 12:41:28.208  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.208  5906  5925 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 12:41:28.210  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 12:41:28.210  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 12:41:28.210  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 12:41:28.210  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 12:41:28.212  5906  5922 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 12:41:28.212  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.212  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 12:41:28.213  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 12:41:28.213  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 12:41:28.214  5906  5925 D BtGatt.ScanManager: handling starting scan
08-29 12:41:28.214  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 12:41:28.218  5906  5922 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 12:41:28.218  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.218  5906  5925 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 12:41:28.219  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 12:41:28.219  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:28.219  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:28.219  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:28.219  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.219  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 12:41:28.219  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 12:41:28.219  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1208e51 removed from the list
,08-29 12:41:28.219  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:28.219  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9df76b6 removed from the list
08-29 12:41:28.220  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:28.220  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 12:41:28.220  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.221  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-29 12:41:28.221  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.221  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 12:41:28.222  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:28.222  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:28.222  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:28.222  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9df76b6 not in the list
08-29 12:41:28.222  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 12:41:28.222  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 12:41:28.222  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 12:41:28.222  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 12:41:28.222  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 12:41:28.223  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 12:41:28.223  5684  5730 D BluetoothAdapter: STATE_ON
08-29 12:41:28.223  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.223  5906  5925 D BtGatt.ScanManager: Starting BLE batch scan
08-29 12:41:28.223  5906  5925 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 12:41:28.223  5906  5917 D BtGatt.GattService: stopScan() - queue size =1
,08-29 12:41:28.224  5906  5934 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 12:41:28.224  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 12:41:28.224  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 12:41:28.224  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 12:41:28.224  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 12:41:28.225  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 12:41:28.225  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 12:41:28.225  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 12:41:28.225  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 12:41:28.226  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 12:41:28.226  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:28.227  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:28.227  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:28.227  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:28.227  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 12:41:28.227  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40ebe8d removed from the list
08-29 12:41:28.227  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 12:41:28.227  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 12:41:28.227  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.227  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 12:41:28.227  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:28.227  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 12:41:28.227  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9194324 removed from the list
08-29 12:41:28.228  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 12:41:28.228  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@935b689 added. We now have 2 listener(s)
,08-29 12:41:28.229  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 12:41:28.229  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 12:41:28.229  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 12:41:28.229  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:28.229  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a68e added. We now have 9 listener(s)
08-29 12:41:28.229  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:28.230  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 12:41:28.232  5906  5922 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 12:41:28.232  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 12:41:28.233  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 12:41:28.235  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 12:41:28.235  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 12:41:28.235  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 12:41:28.235  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 12:41:28.235  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 12:41:28.235  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 12:41:28.235  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 12:41:28.235  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 12:41:28.236  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 12:41:28.236  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 12:41:28.237  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 12:41:28.237  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 12:41:28.238  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 12:41:28.238  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cefd2bc added. We now have 3 listener(s)
08-29 12:41:28.239  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 12:41:28.239  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 12:41:28.239  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 12:41:28.239  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 12:41:28.239  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 12:41:28.239  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dba3245 added. We now have 10 listener(s)
08-29 12:41:28.239  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 12:41:28.239  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 12:41:28.239  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:28.239  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 12:41:28.239  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:28.239  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.239  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 12:41:28.239  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 12:41:28.239  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@935b689 removed from the list
08-29 12:41:28.240  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:28.240  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a68e removed from the list
,08-29 12:41:28.240  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 12:41:28.240  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
08-29 12:41:28.240  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:28.241  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.241  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:28.242  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:28.242  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 12:41:28.242  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 12:41:28.242  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a68e not in the list
08-29 12:41:28.242  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 12:41:28.242  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.242  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.242  5906  5925 D BtGatt.ScanManager: stopping BLe Batch
08-29 12:41:28.242  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:28.243  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 12:41:28.244  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 12:41:28.244  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 12:41:28.244  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dba3245 removed from the list
08-29 12:41:28.244  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 12:41:28.244  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 12:41:28.244  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 12:41:28.244  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 12:41:28.244  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cefd2bc removed from the list
08-29 12:41:28.244  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 12:41:28.245  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 12:41:28.245  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 12:41:28.245  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 12:41:28.245  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 12:41:28.245  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 12:41:28.247  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 12:41:28.247  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 12:41:28.247  5906  5925 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 12:41:28.249  5684  5963 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: My test thread name)
08-29 12:41:28.250  5684  5963 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: My test thread name)
08-29 12:41:28.250  5684  5963 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 12:41:28.251  5684  5964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name)
08-29 12:41:28.251  5684  5964 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: My test thread name)
08-29 12:41:28.251  5684  5964 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 12:41:28.252  5906  5922 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 12:41:28.252  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 12:41:28.253  5684  5730 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-29 12:41:28.253  5684  5730 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 12:41:28.253  5684  5730 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 12:41:28.253  5684  5730 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 12:41:28.253  5684  5730 D com.test.thalitest.ThaliTestRunner: Total duration: 22542 ms
08-29 12:41:28.255  5684  5730 I jxcore-log: *Native tests were executed*
08-29 12:41:28.255  5684  5730 I jxcore-log: 
08-29 12:41:28.255  5684  5730 I jxcore-log: Total number of executed tests:  80
08-29 12:41:28.255  5684  5730 I jxcore-log: 
08-29 12:41:28.255  5684  5730 I jxcore-log: Number of passed tests:  80
08-29 12:41:28.255  5684  5730 I jxcore-log: 
08-29 12:41:28.255  5684  5730 I jxcore-log: Number of failed tests:  0
08-29 12:41:28.255  5684  5730 I jxcore-log: 
08-29 12:41:28.255  5684  5730 I jxcore-log: Number of ignored tests:  0
08-29 12:41:28.255  5684  5730 I jxcore-log: 
,08-29 12:41:28.256  5684  5730 I jxcore-log: Total duration:  22542
08-29 12:41:28.256  5684  5730 I jxcore-log: 
08-29 12:41:28.256  5684  5730 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 12:41:28.256  5684  5730 I jxcore-log: 
08-29 12:41:28.258  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 12:41:28.258  5684  5730 I jxcore-log: 
08-29 12:41:28.261  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 12:41:28.261  5684  5730 I jxcore-log: 
08-29 12:41:28.262  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 12:41:28.262  5684  5730 I jxcore-log: 
08-29 12:41:28.263  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 12:41:28.263  5684  5730 I jxcore-log: 
08-29 12:41:28.264  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 12:41:28.264  5684  5730 I jxcore-log: 
,08-29 12:41:28.265  5684  5684 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 12:41:28.265  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 12:41:28.265  5684  5730 I jxcore-log: 
08-29 12:41:28.268  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 12:41:28.268  5684  5730 I jxcore-log: 
08-29 12:41:28.270  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 12:41:28.270  5684  5730 I jxcore-log: 
08-29 12:41:28.270  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 12:41:28.270  5684  5730 I jxcore-log: 
08-29 12:41:28.271  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 12:41:28.271  5684  5730 I jxcore-log: 
08-29 12:41:28.272  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 12:41:28.272  5684  5730 I jxcore-log: 
08-29 12:41:28.273  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 12:41:28.273  5684  5730 I jxcore-log: 
08-29 12:41:28.274  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 12:41:28.274  5684  5730 I jxcore-log: 
08-29 12:41:28.275  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 12:41:28.275  5684  5730 I jxcore-log: 
08-29 12:41:28.275  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 12:41:28.275  5684  5730 I jxcore-log: 
08-29 12:41:28.276  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 12:41:28.276  5684  5730 I jxcore-log: 
08-29 12:41:28.277  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 12:41:28.277  5684  5730 I jxcore-log: 
08-29 12:41:28.277  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 12:41:28.277  5684  5730 I jxcore-log: 
08-29 12:41:28.278  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 12:41:28.278  5684  5730 I jxcore-log: 
08-29 12:41:28.279  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 12:41:28.279  5684  5730 I jxcore-log: 
08-29 12:41:28.279  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 12:41:28.279  5684  5730 I jxcore-log: 
,08-29 12:41:28.280  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 12:41:28.280  5684  5730 I jxcore-log: 
,08-29 12:41:28.280  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 12:41:28.280  5684  5730 I jxcore-log: 
,08-29 12:41:28.281  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 12:41:28.281  5684  5730 I jxcore-log: 
08-29 12:41:28.282  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 12:41:28.282  5684  5730 I jxcore-log: 
08-29 12:41:28.282  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 12:41:28.282  5684  5730 I jxcore-log: 
08-29 12:41:28.283  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 12:41:28.283  5684  5730 I jxcore-log: 
08-29 12:41:28.284  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 12:41:28.284  5684  5730 I jxcore-log: 
08-29 12:41:28.284  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 12:41:28.284  5684  5730 I jxcore-log: 
,08-29 12:41:28.623  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 12:41:28.627  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 12:41:28.627  5684  5730 I jxcore-log: 
,08-29 12:41:28.676  5965  5965 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 12:41:28.680  5965  5965 D AndroidRuntime: CheckJNI is OFF
,08-29 12:41:28.684  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 12:41:28.687  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 12:41:28.687  5684  5730 I jxcore-log: 
,08-29 12:41:28.709  5965  5965 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 12:41:28.727  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 12:41:28.730  5684  5730 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 12:41:28.730  5684  5730 I jxcore-log: 
,08-29 12:41:28.741  5965  5965 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 12:41:28.757  5965  5965 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 12:41:28.764   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,08-29 12:41:28.765   928   941 I ActivityManager: Killing 5684:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,08-29 12:41:28.838   928  4049 I WindowState: WIN DEATH: Window{c6f63b4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 12:41:28.838   928  3685 D GraphicsStats: Buffer count: 2
,08-29 12:41:28.840   928  3054 D WifiService: Client connection lost with reason: 4
,08-29 12:41:28.895   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-29 12:41:28.896   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-29 12:41:28.896   928   951 I art     : Starting a blocking GC Explicit
08-29 12:41:28.896   928   941 E ActivityManager: Failure starting process com.test.thalitest
08-29 12:41:28.896   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 12:41:28.896   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 12:41:28.896   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 12:41:28.896   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 12:41:28.896   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 12:41:28.897   928   941 I ActivityManager:   Force finishing activity ActivityRecord{ebe09f9 u0 com.test.thalitest/.MainActivity t4}
,08-29 12:41:28.901   928  3257 W ActivityManager: Spurious death for ProcessRecord{f9e34f0 0:com.test.thalitest/u0a77}, curProc for 5684: null
,08-29 12:41:28.972   928   951 I art     : Explicit concurrent mark sweep GC freed 23641(1456KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 1.564ms total 75.864ms
,08-29 12:41:28.992   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 12:41:28.995  5965  5965 I art     : System.exit called, status: 0
,08-29 12:41:28.995  5965  5965 I AndroidRuntime: VM exiting with result code 0.
,08-29 12:41:28.999   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,08-29 12:41:29.005   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 12:41:29.011  3501  3501 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 12:41:29.011  3568  4004 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 12:41:29.013  5906  5906 D BluetoothMapAppObserver: onReceive
08-29 12:41:29.013  5906  5906 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-29 12:41:29.017   928  3040 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 12:41:29.046  3501  5976 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 12:41:29.055  3622  3622 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 12:41:29.055  5491  5977 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-29 12:41:29.061  3702  3702 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-29 12:41:29.061  3702  3702 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-29 12:41:29.080  3940  5982 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-29 12:41:29.080  3940  5982 D AccountUtils: Clearing selected account for com.test.thalitest
,08-29 12:41:29.085  3501  5976 I Decoder : createOrResetDecoder
,08-29 12:41:29.085   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 12:41:29.104  3702  3702 I ConfigService: onCreate
,08-29 12:41:29.115  3940  5982 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-29 12:41:29.112  5848  5848 W kworker/3:4: type=1400 audit(0.0:73): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 12:41:29.122  5848  5848 W kworker/3:4: type=1400 audit(0.0:74): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 12:41:29.132  5848  5848 W kworker/3:4: type=1400 audit(0.0:75): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 12:41:29.137  3501  5976 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 12:41:29.146  5491  5977 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
08-29 12:41:29.147  5491  5977 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 12:41:29.147  5491  5977 E AndroidRuntime: Process: android.process.acore, PID: 5491
08-29 12:41:29.147  5491  5977 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 12:41:29.147  5491  5977 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 12:41:29.150   928  5988 E DropBoxManagerService: Can't write: system_app_crash
08-29 12:41:29.150   928  5988 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-29 12:41:29.150   928  5988 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 12:41:29.150   928  5988 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 12:41:29.150   928  5988 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 12:41:29.150   928  5988 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 12:41:29.150   928  5988 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 12:41:29.150   928  5988 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 12:41:29.150   928  5988 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 12:41:29.150   928  5988 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 12:41:29.150   928  5988 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 12:41:29.150   928  5988 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 12:41:29.150   928  5988 E DropBoxManagerService: 	... 5 more
,08-29 12:41:29.154  3940  5982 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/phenotype.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-29 12:41:29.160  5491  5977 I Process : Sending signal. PID: 5491 SIG: 9
,08-29 12:41:29.209  3940  3940 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-29 12:41:29.209  3940  3940 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded

```
