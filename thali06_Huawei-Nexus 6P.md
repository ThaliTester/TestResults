#### Test 81444731606602a_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-29 07:29:45.354   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:29:45.782  5606  5606 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 07:29:45.787  5606  5606 D AndroidRuntime: CheckJNI is OFF
08-29 07:29:45.810  5606  5606 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 07:29:45.838  5606  5606 I Radio-JNI: register_android_hardware_Radio DONE
08-29 07:29:45.853  5606  5606 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 07:29:45.858   933  3629 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 07:29:45.883   933  3629 I ActivityManager: Start proc 5616:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-29 07:29:45.886  5606  5606 D AndroidRuntime: Shutting down VM
08-29 07:29:45.953  5616  5616 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-29 07:29:45.975  5616  5616 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 07:29:46.000  5616  5616 I LibraryLoader: Time to load native libraries: 22 ms (timestamps 5983-6005)
08-29 07:29:46.000  5616  5616 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 07:29:46.020  5616  5616 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {477d70}
08-29 07:29:46.020  5616  5616 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 07:29:46.021  5616  5616 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 07:29:46.024  5616  5616 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 07:29:46.025  5616  5616 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 07:29:46.058  5616  5616 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 07:29:46.070  5616  5616 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 07:29:46.070  5616  5616 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 07:29:46.070  5616  5616 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 07:29:46.070  5616  5616 I Adreno  : Build Date                       : 10/21/15
08-29 07:29:46.070  5616  5616 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 07:29:46.070  5616  5616 I Adreno  : Local Branch                     : 
08-29 07:29:46.070  5616  5616 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 07:29:46.070  5616  5616 I Adreno  : Remote Branch                    : NONE
08-29 07:29:46.070  5616  5616 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 07:29:46.127   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fc141a1:true
,08-29 07:29:46.175  5616  5616 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 07:29:46.185  5616  5616 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-29 07:29:46.213  5616  5653 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 07:29:46.221  5616  5640 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 07:29:46.256  5616  5653 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 07:29:46.355   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:29:46.356   933   951 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +442ms (total +486ms)
,08-29 07:29:46.388  5616  5616 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5616
,08-29 07:29:46.483  5616  5616 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 07:29:46.649  5616  5655 D jxcore_app_log: JniHelper::setJavaVM(0xf557c000), pthread_self() = -576718544
,08-29 07:29:46.653  5616  5655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 07:29:46.653  5616  5655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 07:29:46.653  5616  5655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 07:29:46.653  5616  5655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 07:29:46.653  5616  5655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 07:29:46.654  5616  5655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee985c7 added. We now have 1 listener(s)
,08-29 07:29:46.656  5616  5655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,08-29 07:29:46.657  5616  5655 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 07:29:46.657  5616  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:29:46.658  5616  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 07:29:46.660  5616  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@288e192 added. We now have 1 listener(s)
08-29 07:29:46.660  5616  5655 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:29:46.663   933  3036 D WifiService: New client listening to asynchronous messages
,08-29 07:29:46.663  5616  5655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 07:29:46.663  5616  5655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 07:29:46.663  5616  5655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 07:29:46.663  5616  5655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 07:29:46.664  5616  5655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 07:29:46.666  5616  5655 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:29:46.666  5616  5655 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-29 07:29:46.670  5616  5655 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 07:29:46.670  5616  5655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:29:46.670  5616  5655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:46.670  5616  5655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:46.670  5616  5655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:29:46.670  5616  5655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:29:46.670  5616  5655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:29:46.670  5616  5655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:29:46.670  5616  5655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 07:29:46.671  5616  5655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 07:29:46.671  5616  5655 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:29:46.671  5616  5655 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 07:29:46.673  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:46.676  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:29:46.693  5616  5616 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 07:29:47.216  5616  5662 W jxcore-log: Initializing JXcore engine
08-29 07:29:47.216  5616  5662 W jxcore-log: JXcore engine is ready
08-29 07:29:47.217  5616  5625 I art     : Background sticky concurrent mark sweep GC freed 79708(8MB) AllocSpace objects, 18(1604KB) LOS objects, 23% free, 25MB/32MB, paused 1.519ms total 294.429ms
,08-29 07:29:47.263  5662  5662 W Thread-57: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12763 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 07:29:47.263  5662  5662 W Thread-57: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[14703]" dev="sockfs" ino=14703 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-29 07:29:47.263  5662  5662 W Thread-57: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=7220 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 07:29:47.263  5662  5662 W Thread-57: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[31264]" dev="sockfs" ino=31264 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 07:29:47.286  5616  5662 W jxcore-log: Starting JXcore engine
,08-29 07:29:47.356   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:29:47.360  5616  5662 W jxcore-log: Platform android
08-29 07:29:47.360  5616  5662 W jxcore-log: 
,08-29 07:29:47.360  5616  5662 W jxcore-log: Process ARCH arm
08-29 07:29:47.360  5616  5662 W jxcore-log: 
,08-29 07:29:47.453  5616  5662 I jxcore-log: JXcore Cordova bridge is ready!
08-29 07:29:47.453  5616  5662 I jxcore-log: 
,08-29 07:29:47.454  5616  5662 W jxcore-log: JXcore engine is started
,08-29 07:29:47.465  5616  5655 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 07:29:47.471  5616  5616 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 07:29:48.356   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:29:49.357   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:29:50.358   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 07:29:50.546   933  5290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=170550, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 07:29:54.095  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 07:29:54.095  5616  5662 I jxcore-log: 
,08-29 07:29:54.097  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 07:29:54.097  5616  5662 I jxcore-log: 
,08-29 07:29:54.101  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:29:54.101  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:54.101  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:54.101  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:29:54.101  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:29:54.101  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:29:54.101  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:29:54.101  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 07:29:54.102  5616  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 07:29:54.104  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 07:29:54.104  5616  5662 I jxcore-log: 
,08-29 07:29:54.105  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 07:29:54.105  5616  5662 I jxcore-log: 
,08-29 07:29:54.461  5616  5662 D executeNativeTests: Running unit tests
,08-29 07:29:54.500  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 07:29:54.500  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 added. We now have 2 listener(s)
,08-29 07:29:54.501  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 07:29:54.501  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 07:29:54.501  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:29:54.501  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:29:54.501  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 added. We now have 2 listener(s)
08-29 07:29:54.501  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:29:54.502  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 07:29:54.504  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:29:54.507  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:29:54.507  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:54.507  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:54.507  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:29:54.507  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:29:54.507  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:29:54.507  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:29:54.507  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 07:29:54.508  5616  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 07:29:54.508  5616  5662 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:29:54.510  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 07:29:54.510  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 07:29:54.510  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 07:29:54.511  5616  5662 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 07:29:54.511  5616  5662 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 07:29:54.511  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 07:29:54.511  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 07:29:54.511  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 07:29:54.511  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.512  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 07:29:54.512  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.512  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.512  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.512  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:29:54.512  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:29:54.512  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 removed from the list
08-29 07:29:54.512  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.512  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 removed from the list
,08-29 07:29:54.514  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:54.521  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:29:54.521  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.521  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.522  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:29:54.522  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:29:54.522  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.522  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.522  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.522  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.523  5616  5662 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-29 07:29:54.523  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.523  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.523  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.523  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.523  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:29:54.524  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.524  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.524  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.524  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.524  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 07:29:54.524  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.524  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.524  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.524  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.524  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.524  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.524  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.524  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-29 07:29:54.527  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 07:29:54.528  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 07:29:54.528  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 07:29:54.528  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-29 07:29:54.528  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 07:29:54.528  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 07:29:54.528  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 07:29:54.528  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 07:29:54.528  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 07:29:54.528  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.528  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 07:29:54.528  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.528  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.528  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.528  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.528  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.528  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.528  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
,08-29 07:29:54.528  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.528  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.528  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.528  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.528  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.529  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.529  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 07:29:54.529  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.529  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.529  5616  5662 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 07:29:54.530  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:29:54.532  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:29:54.532  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:54.532  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:54.532  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:29:54.532  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:29:54.532  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:29:54.532  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:29:54.532  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 07:29:54.533  5616  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 07:29:54.533  5616  5662 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:29:54.533  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:29:54.533  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:29:54.533  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:29:54.533  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:29:54.533  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 07:29:54.535  5616  5662 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 07:29:54.535  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 07:29:54.536  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:54.539  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 07:29:54.540  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:29:54.542  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 07:29:54.542  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 07:29:54.546  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 07:29:54.549  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 07:29:54.549  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 07:29:54.549  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:29:54.550  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 07:29:54.551  5616  5662 D BluetoothAdapter: STATE_ON
,08-29 07:29:54.556  4463  4479 D BtGatt.GattService: registerClient() - UUID=cb5e0481-67a8-4fcc-b9cf-0828d2089c23
,08-29 07:29:54.557  4463  4546 D BtGatt.GattService: onClientRegistered() - UUID=cb5e0481-67a8-4fcc-b9cf-0828d2089c23, clientIf=5
,08-29 07:29:54.558  5616  5627 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 07:29:54.560  4463  4724 D BtGatt.GattService: start scan with filters
08-29 07:29:54.563  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 07:29:54.563  4463  4551 D BtGatt.ScanManager: handling starting scan
08-29 07:29:54.563  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:29:54.563  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:29:54.563  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 07:29:54.566  4463  4551 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
,08-29 07:29:54.569  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 07:29:54.570  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:29:54.570  5616  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:29:54.572  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 07:29:54.574  4463  4546 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:29:54.574  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:29:54.576  5616  5662 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 07:29:54.576  4463  4551 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 07:29:54.577  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.577  5616  5662 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 07:29:54.577  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 07:29:54.578  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 07:29:54.578  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.578  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:29:54.578  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 07:29:54.578  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:29:54.578  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:29:54.578  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:29:54.578  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:29:54.578  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 07:29:54.579  5616  5662 D BluetoothAdapter: STATE_ON
,08-29 07:29:54.579  4463  4724 D BtGatt.GattService: stopScan() - queue size =1
08-29 07:29:54.579  4463  4482 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 07:29:54.579  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:29:54.580  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:29:54.580  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:29:54.580  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:29:54.580  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:29:54.580  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:29:54.580  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:29:54.581  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 07:29:54.581  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 07:29:54.582  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 07:29:54.582  4463  4546 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:29:54.582  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.583  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.583  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.583  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:29:54.583  4463  4551 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 07:29:54.583  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.583  5616  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:29:54.583  4463  4551 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:29:54.583  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.583  5616  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:29:54.583  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.583  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.583  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.583  5616  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:29:54.583  5616  5662 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 07:29:54.584  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:29:54.590  4463  4546 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:29:54.590  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:29:54.591  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:29:54.591  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:54.591  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:54.591  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:29:54.591  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:29:54.591  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:29:54.591  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:29:54.591  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 07:29:54.593  5616  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 07:29:54.593  5616  5662 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:29:54.593  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:29:54.593  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:29:54.593  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:29:54.593  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:29:54.594  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 07:29:54.596  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:54.596  4463  4546 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:29:54.596  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:29:54.597  5616  5662 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 07:29:54.598  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 07:29:54.598  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:54.602  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 07:29:54.602  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 07:29:54.602  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 07:29:54.603  4463  4546 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:29:54.603  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.603  4463  4551 D BtGatt.ScanManager: stopping BLe Batch
,08-29 07:29:54.607  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 07:29:54.607  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 07:29:54.607  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:29:54.608  5616  5662 D BluetoothAdapter: STATE_ON
,08-29 07:29:54.610  4463  4479 D BtGatt.GattService: registerClient() - UUID=cfed671e-de31-4094-9404-c0830c37c0de
08-29 07:29:54.610  4463  4546 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 07:29:54.610  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.610  4463  4546 D BtGatt.GattService: onClientRegistered() - UUID=cfed671e-de31-4094-9404-c0830c37c0de, clientIf=5
08-29 07:29:54.610  4463  4551 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 07:29:54.610  5616  5627 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 07:29:54.611  4463  4482 D BtGatt.GattService: start scan with filters
08-29 07:29:54.613  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 07:29:54.613  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:29:54.613  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 07:29:54.613  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 07:29:54.615  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:29:54.615  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:29:54.615  4463  4546 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:29:54.615  5616  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:29:54.615  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.616  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 07:29:54.617  4463  4551 D BtGatt.ScanManager: handling starting scan
08-29 07:29:54.617  5616  5662 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 07:29:54.619  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.619  5616  5662 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 07:29:54.619  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.619  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 07:29:54.619  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.619  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:29:54.620  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 07:29:54.620  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:29:54.620  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:29:54.620  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:29:54.620  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:29:54.620  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 07:29:54.620  5616  5662 D BluetoothAdapter: STATE_ON
08-29 07:29:54.621  4463  4479 D BtGatt.GattService: stopScan() - queue size =1
08-29 07:29:54.622  4463  4546 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:29:54.622  4463  4482 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 07:29:54.622  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:29:54.623  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 07:29:54.623  4463  4551 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 07:29:54.623  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:29:54.623  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:29:54.623  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:29:54.623  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:29:54.624  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:29:54.624  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:29:54.624  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:29:54.625  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 07:29:54.625  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 07:29:54.626  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.626  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.626  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 07:29:54.626  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.626  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.626  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.626  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.626  5616  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:29:54.626  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.626  5616  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:29:54.627  5616  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:29:54.627  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.627  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.627  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.627  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.627  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.627  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.627  4463  4546 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:29:54.628  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.628  4463  4551 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 07:29:54.628  4463  4551 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:29:54.628  5616  5662 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 07:29:54.629  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:29:54.636  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:29:54.636  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:54.636  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:54.636  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:29:54.636  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:29:54.636  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:29:54.636  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:29:54.636  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 07:29:54.637  4463  4546 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:29:54.637  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.638  5616  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 07:29:54.638  5616  5662 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:29:54.638  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:29:54.638  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:29:54.638  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:29:54.638  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:29:54.638  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:29:54.641  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:54.642  4463  4546 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:29:54.642  5616  5662 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 07:29:54.642  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 07:29:54.642  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.643  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:54.645  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 07:29:54.645  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 07:29:54.645  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 07:29:54.647  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 07:29:54.647  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:29:54.647  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:29:54.648  5616  5662 D BluetoothAdapter: STATE_ON
08-29 07:29:54.648  4463  4546 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:29:54.648  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.648  4463  4551 D BtGatt.ScanManager: stopping BLe Batch
08-29 07:29:54.649  4463  4724 D BtGatt.GattService: registerClient() - UUID=268332b5-2a85-4858-879b-8d1f6fc8411b
08-29 07:29:54.649  4463  4546 D BtGatt.GattService: onClientRegistered() - UUID=268332b5-2a85-4858-879b-8d1f6fc8411b, clientIf=5
08-29 07:29:54.650  5616  5626 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 07:29:54.650  4463  4482 D BtGatt.GattService: start scan with filters
08-29 07:29:54.652  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 07:29:54.653  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:29:54.653  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:29:54.653  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 07:29:54.654  4463  4546 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:29:54.654  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.654  4463  4551 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 07:29:54.656  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:29:54.656  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:29:54.656  5616  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:29:54.656  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 07:29:54.658  5616  5662 I io.jxcore.node.ConnectionHelper: start: OK
08-29 07:29:54.658  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.658  5616  5662 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 07:29:54.658  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.658  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 07:29:54.658  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.658  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:29:54.658  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 07:29:54.658  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:29:54.658  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:29:54.658  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:29:54.658  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:29:54.658  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 07:29:54.659  5616  5662 D BluetoothAdapter: STATE_ON
08-29 07:29:54.659  4463  4546 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:29:54.659  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.659  4463  4482 D BtGatt.GattService: stopScan() - queue size =0
08-29 07:29:54.659  4463  4723 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 07:29:54.660  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:29:54.660  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:29:54.660  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:29:54.660  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:29:54.660  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:29:54.661  4463  4551 D BtGatt.ScanManager: handling starting scan
08-29 07:29:54.662  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:29:54.662  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:29:54.662  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:29:54.662  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 07:29:54.662  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:29:54.663  5616  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:29:54.663  5616  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:29:54.663  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.663  5616  5662 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 07:29:54.663  5616  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:29:54.663  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.663  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.663  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.664  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.664  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:29:54.664  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.664  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.664  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.664  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.664  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.664  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.664  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.665  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.665  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.665  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.665  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.666  5616  5662 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-29 07:29:54.666  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.667  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.667  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.667  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.667  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.667  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.667  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.667  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.667  4463  4546 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:29:54.667  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.667  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.667  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.667  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.667  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.667  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.667  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.667  4463  4551 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 07:29:54.668  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.669  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.669  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.669  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.669  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 07:29:54.670  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.670  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.670  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.670  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.670  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.670  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.670  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.670  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.670  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.670  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.670  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.670  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.670  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.670  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.671  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.671  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.671  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.671  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.672  5616  5662 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 07:29:54.672  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.672  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.672  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.672  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.672  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.672  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.672  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.672  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.672  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.672  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.672  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.672  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.672  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.672  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.673  4463  4546 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:29:54.673  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.673  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.673  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.673  4463  4551 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:29:54.673  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.673  4463  4551 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:29:54.673  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.674  5616  5662 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 07:29:54.674  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.674  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.674  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.674  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.674  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.674  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.674  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.674  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.674  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.674  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.674  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.674  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.675  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.675  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.683  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.683  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.683  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.683  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.683  4463  4546 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:29:54.683  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.684  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 07:29:54.684  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 07:29:54.684  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 07:29:54.684  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 07:29:54.684  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 07:29:54.684  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 07:29:54.684  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.684  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.684  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.684  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.684  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.684  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.685  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.685  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.685  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.685  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.685  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.685  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.685  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.685  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.686  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.686  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.686  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.686  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.686  5616  5662 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 07:29:54.687  5616  5662 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 07:29:54.687  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 07:29:54.688  4463  4546 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:29:54.688  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.688  5616  5662 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 07:29:54.688  5616  5662 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 07:29:54.688  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 07:29:54.688  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 07:29:54.688  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 07:29:54.688  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 07:29:54.688  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 07:29:54.688  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 07:29:54.689  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 07:29:54.690  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 07:29:54.690  5616  5662 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 07:29:54.690  5616  5662 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 07:29:54.690  5616  5662 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 07:29:54.690  5616  5662 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 07:29:54.690  5616  5662 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 07:29:54.690  5616  5662 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 07:29:54.690  5616  5662 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 07:29:54.690  5616  5662 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 07:29:54.690  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 07:29:54.692  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 07:29:54.693  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 07:29:54.693  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 07:29:54.694  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 07:29:54.694  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 07:29:54.694  5616  5662 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 07:29:54.694  4463  4546 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:29:54.694  5616  5662 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 07:29:54.694  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.694  5616  5662 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 07:29:54.694  5616  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
08-29 07:29:54.694  4463  4551 D BtGatt.ScanManager: stopping BLe Batch
08-29 07:29:54.694  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.694  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.695  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.695  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.695  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.695  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.695  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 07:29:54.696  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.696  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.696  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.696  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.696  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.696  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.696  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.696  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.696  5616  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
08-29 07:29:54.697  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.697  5616  5663 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:29:54.697  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.697  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.697  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.698  5616  5662 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 07:29:54.698  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.698  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.698  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.698  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.698  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.698  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.698  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.698  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.698  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.698  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.698  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.698  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.699  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.699  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.699  4463  4546 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:29:54.699  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.699  4463  4551 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 07:29:54.699  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.699  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.699  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.699  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.700  5616  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 07:29:54.700  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.700  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.700  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.700  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.700  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.700  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.700  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.700  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.700  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.700  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.700  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.700  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.700  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.700  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.705  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.705  5616  5662 I org.thaliproject.p2p.btconnectorlib.Di,scoveryManager: stopDiscovery
08-29 07:29:54.705  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.705  4463  4546 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:29:54.705  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.705  4463  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:29:54.705  5616  5662 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 07:29:54.706  5616  5662 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 07:29:54.706  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 07:29:54.706  5616  5662 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 07:29:54.706  5616  5662 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 07:29:54.706  5616  5662 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 07:29:54.706  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 07:29:54.706  5616  5662 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 07:29:54.706  5616  5662 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 07:29:54.706  5616  5662 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 07:29:54.706  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 07:29:54.706  5616  5662 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 07:29:54.706  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.706  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.706  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.706  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.706  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.706  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.706  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.706  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.706  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.707  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.707  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.707  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.707  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.707  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.707  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 07:29:54.707  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.707  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.707  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.708  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.708  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.708  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.708  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.708  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.708  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.708  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.708  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.708  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.708  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.708  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.708  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.708  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.708  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.708  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.708  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.708  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.708  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.708  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.708  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.709  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.709  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.709  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.709  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.709  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.709  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.709  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.709  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.709  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.709  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.709  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.709  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.710  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.710  5616  5662 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 07:29:54.710  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:29:54.711  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 07:29:54.711  5616  5662 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 07:29:54.711  5616  5662 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 07:29:54.711  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 07:29:54.711  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 07:29:54.712  5616  5616 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 07:29:54.712  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.712  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 07:29:54.712  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 07:29:54.712  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 07:29:54.712  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.712  5616  5662 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 07:29:54.712  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.712  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.712  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:29:54.712  5616  5616 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 07:29:54.712  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:29:54.712  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:29:54.712  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.712  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.712  5616  5665 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:29:54.714  5616  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 07:29:54.714  5616  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 07:29:54.714  5616  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 07:29:54.715  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:29:54.715  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.715  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.715  5616  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:29:54.715  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.715  5616  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:29:54.715  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.715  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.715  5616  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 07:29:54.715  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.715  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.715  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.715  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.715  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.715  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.715  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.715  5616  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:29:54.715  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.715  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.715  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.716  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.716  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.716  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.716  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.717  5616  5662 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 07:29:54.717  5616  5662 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 07:29:54.717  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 07:29:54.717  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 07:29:54.717  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.717  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.717  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.717  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.717  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.717  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.717  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.717  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.717  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.717  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.717  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.717  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.717  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.717  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.718  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.718  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.718  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.718  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.720  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.720  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.720  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.720  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.720  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.720  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.720  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.720  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.720  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.720  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.721  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.721  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.721  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.721  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.721  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.721  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.721  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.721  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.722  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:29:54.722  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:29:54.722  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:29:54.722  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:29:54.722  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.722  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.722  5616  5662 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecdcd7 not in the list
08-29 07:29:54.722  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.722  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.722  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:29:54.722  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.722  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.722  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:29:54.722  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:29:54.723  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:29:54.723  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:29:54.723  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:29:54.723  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db9c4 not in the list
08-29 07:29:54.723  5616  5662 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 07:29:54.723  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 07:29:54.723  5616  5662 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 07:29:54.724  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 07:29:54.724  5616  5662 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 07:29:54.724  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 07:29:54.724  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 07:29:54.725  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 07:29:54.725  5616  5662 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 07:29:54.725  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 07:29:54.725  5616  5662 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 07:29:54.725  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 07:29:54.725  5616  5662 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 07:29:54.725  5616  5662 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 07:29:54.726  5616  5662 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 07:29:54.726  5616  5662 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 07:29:54.726  5616  5662 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 07:29:54.726  5616  5662 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 07:29:54.726  5616  5662 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 07:29:54.726  5616  5662 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 07:29:54.726  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:29:54.726  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@44b4f06 added. We now have 2 listener(s)
08-29 07:29:54.726  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:29:54.727  5616  5662 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 07:29:54.727   933  3494 D WifiService: setWifiEnabled: true pid=5616, uid=10077
08-29 07:29:54.727   933  3494 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 07:29:54.728  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:29:54.728  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ac8a9c7 added. We now have 3 listener(s)
08-29 07:29:54.728  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:29:54.730  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:29:54.730  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2151bf4 added. We now have 4 listener(s)
08-29 07:29:54.730  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:29:54.731  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:29:54.731  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4396f1d added. We now have 5 listener(s)
08-29 07:29:54.731  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:29:54.732   933   943 D WifiService: setWifiEnabled: false pid=5616, uid=10077
08-29 07:29:54.732   933   943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 07:29:54.735   933  3035 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 07:29:54.735   933  3035 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 07:29:54.735   933  3035 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 07:29:54.735   933  3035 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 07:29:54.738  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:29:54.738  4463  4542 D BluetoothAdapterState: Current state: ON, message: 23
08-29 07:29:54.738  4463  4542 D BluetoothAdapterProperties: Setting state to 13
08-29 07:29:54.739  4463  4542 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 07:29:54.739  4463  4542 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 07:29:54.739  4463  4542 I BluetoothAdapterState: Entering PendingCommandState
08-29 07:29:54.740  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:29:54.740  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:29:54.740  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:54.740  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:54.740  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:29:54.740  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:29:54.740  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:29:54.740  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:29:54.740  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 07:29:54.740  4463  4546 D BluetoothAdapterProperties: Scan Mode:20
08-29 07:29:54.741  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the c,heck when the Bluetooth is disabled - will return stored value
08-29 07:29:54.741  5616  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 07:29:54.741  4463  4542 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 07:29:54.741  5616  5662 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:29:54.742  4463  4463 D HeadsetService: Received stop request...Stopping profile...
08-29 07:29:54.744  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:54.745   933   933 D BluetoothHeadset: Proxy object disconnected
08-29 07:29:54.745  3616  3633 D BluetoothHeadset: Proxy object disconnected
08-29 07:29:54.746   933   933 D BluetoothHeadset: Proxy object disconnected
08-29 07:29:54.746   933   933 D BluetoothHeadset: Proxy object disconnected
08-29 07:29:54.746  4463  4463 D A2dpService: Received stop request...Stopping profile...
08-29 07:29:54.746  3192  3801 D BluetoothHeadset: Proxy object disconnected
08-29 07:29:54.746  4463  4706 D A2dpStateMachine: Exit Disconnected: -1
08-29 07:29:54.746  3192  3192 D HeadsetProfile: Bluetooth service disconnected
08-29 07:29:54.747   933  3035 E native  : do suspend true
,08-29 07:29:54.749  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:54.751   933   933 D BluetoothA2dp: Proxy object disconnected
,08-29 07:29:54.752  3192  3192 D BluetoothA2dp: Proxy object disconnected
,08-29 07:29:54.753  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:29:54.753  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:29:54.753  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:54.753  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:54.753  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:29:54.753  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:29:54.753  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:29:54.753  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:29:54.753  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 07:29:54.754  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 07:29:54.754  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 07:29:54.755  4463  4463 V BluetoothAdapterState: isTurningOff()=true
08-29 07:29:54.755  4463  4463 V BluetoothAdapterState: isTurningOn()=false
08-29 07:29:54.755  4463  4463 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:29:54.755  4463  4463 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 07:29:54.756  4463  4463 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 07:29:54.756  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:29:54.757  4463  4463 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 07:29:54.757  4463  4546 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 07:29:54.757  4463  4463 D HidService: Received stop request...Stopping profile...
08-29 07:29:54.757  4463  4463 D HidService: Stopping Bluetooth HidService
08-29 07:29:54.757  4463  4670 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:29:54.757  4463  4670 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:29:54.757  4463  4670 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:29:54.758  4463  4546 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 07:29:54.758  3192  3192 D BluetoothInputDevice: Proxy object disconnected
08-29 07:29:54.758  3192  3192 D HidProfile: Bluetooth service disconnected
08-29 07:29:54.759  4463  4463 D HealthService: Received stop request...Stopping profile...
,08-29 07:29:54.759  4463  4463 V BluetoothAdapterState: isTurningOff()=true
08-29 07:29:54.760  4463  4463 V BluetoothAdapterState: isTurningOn()=false
08-29 07:29:54.760  4463  4463 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:29:54.760  4463  4463 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:29:54.760  4463  4463 D PanService: Received stop request...Stopping profile...
08-29 07:29:54.761  3192  3192 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 07:29:54.761  3192  3192 D PanProfile: Bluetooth service disconnected
,08-29 07:29:54.766  4463  4463 D BluetoothMapService: Received stop request...Stopping profile...
08-29 07:29:54.766  4463  4463 D BluetoothMapService: stop()
08-29 07:29:54.766  4463  4463 D BluetoothMapAppObserver: deinitObservers()
08-29 07:29:54.766  4463  4463 D BluetoothMapAppObserver: removeReceiver()
08-29 07:29:54.767  4463  4463 D SapService: Received stop request...Stopping profile...
,08-29 07:29:54.767  4463  4463 V SapService: stop()
08-29 07:29:54.767  3192  3192 D BluetoothMap: Proxy object disconnected
08-29 07:29:54.767  3192  3192 D MapProfile: Bluetooth service disconnected
08-29 07:29:54.770  4463  4670 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:29:54.770  4463  4463 V BluetoothAdapterState: isTurningOff()=true
08-29 07:29:54.770  4463  4463 V BluetoothAdapterState: isTurningOn()=false
08-29 07:29:54.770  4463  4463 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:29:54.770  4463  4463 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:29:54.770  4463  4670 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:29:54.770  4463  4546 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 07:29:54.770  4463  4670 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 07:29:54.770  4463  4463 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-29 07:29:54.770  4463  4463 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 07:29:54.770  4463  4546 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 07:29:54.770  4463  4670 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 07:29:54.771  4463  4670 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 07:29:54.771  4463  4670 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 07:29:54.771  4463  4463 V BluetoothAdapterState: isTurningOff()=true
08-29 07:29:54.771  4463  4463 V BluetoothAdapterState: isTurningOn()=false
08-29 07:29:54.771  4463  4463 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:29:54.771  4463  4463 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:29:54.771  4463  4463 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 07:29:54.771  4463  4546 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 07:29:54.771  4463  4463 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 07:29:54.771  4463  4463 V BluetoothAdapterState: isTurningOff()=true
08-29 07:29:54.771  4463  4463 V BluetoothAdapterState: isTurningOn()=false
08-29 07:29:54.771  4463  4463 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:29:54.771  4463  4463 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:29:54.772  4463  4463 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 07:29:54.772  4463  4463 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 07:29:54.772  4463  4463 D BluetoothMapService: MAP Service closeService in
08-29 07:29:54.773  4463  4463 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 07:29:54.773  4463  4463 D ObexServerSockets0: shutdown(block = true)
08-29 07:29:54.773  4463  4463 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 07:29:54.773  4463  4689 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 07:29:54.773  4463  4463 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 07:29:54.774   508   926 D CommandListener: Clearing all IP addresses on wlan0
08-29 07:29:54.774  4463  4728 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-29 07:29:54.775  4463  4727 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 07:29:54.776   933  5291 D DhcpClient: Clearing IP address
08-29 07:29:54.776  4463  4463 V BluetoothAdapterState: isTurningOff()=true
08-29 07:29:54.776  4463  4463 V BluetoothAdapterState: isTurningOn()=false
08-29 07:29:54.776  4463  4463 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:29:54.776  4463  4463 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:29:54.776  4463  4463 D BluetoothMapService: cleanup()
08-29 07:29:54.776  4463  4463 D BluetoothMapService: MAP Service closeService in
08-29 07:29:54.777  4463  4463 V BluetoothAdapterState: isTurningOff()=true
,08-29 07:29:54.777  4463  4463 V BluetoothAdapterState: isTurningOn()=false
08-29 07:29:54.777  4463  4463 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:29:54.777  4463  4463 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:29:54.778  4463  4542 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 07:29:54.778  4463  4542 D BluetoothAdapterProperties: Setting state to 15
08-29 07:29:54.778  4463  4542 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 07:29:54.778  4463  4542 I BluetoothAdapterState: Entering BleOnState
,08-29 07:29:54.781   508   926 D CommandListener: Setting iface cfg
08-29 07:29:54.784  3692  5349 V NativeCrypto: Read error: ssl=0x7f8ef0af80: I/O error during system call, Connection timed out
08-29 07:29:54.786   933  5292 D DhcpClient: Receive thread stopped
08-29 07:29:54.786  3692  5349 V NativeCrypto: SSL shutdown failed: ssl=0x7f8ef0af80: I/O error during system call, Broken pipe
,08-29 07:29:54.789   933  3642 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
08-29 07:29:54.789   933  5289 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
08-29 07:29:54.791  3192  5615 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 07:29:54.791   933  5289 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 07:29:54.792   933  3037 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-29 07:29:54.792   933  3037 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 07:29:54.793  4463  4463 I BtOppRfcommListener: stopping Accept Thread
,08-29 07:29:54.793  4463  5231 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 07:29:54.793  4463  5231 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 07:29:54.794   933  3037 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 07:29:54.796  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:29:54.797  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:29:54.797  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:54.797  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:54.797  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:29:54.797  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:29:54.797  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:29:54.797  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:29:54.797  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 07:29:54.797  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 07:29:54.797  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:29:54.800  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:29:54.800  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:29:54.800  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:54.800  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:54.800  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:29:54.800  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:29:54.800  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:29:54.800  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:29:54.800  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 07:29:54.801  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:29:54.801  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:29:54.804   933   946 I ActivityManager: Start proc 5669:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-29 07:29:54.805   933  3037 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 07:29:54.806   933  3037 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-29 07:29:54.806  3192  3801 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 07:29:54.806  3192  3204 D BluetoothPan: onBluetoothStateChange on: false
08-29 07:29:54.809  3192  3801 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 07:29:54.810   534   534 E Parcel  : Reading a NULL string not supported here.
,08-29 07:29:54.811   933   950 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 07:29:54.812  3192  3203 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 07:29:54.815   933  3037 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-29 07:29:54.816  3616  3816 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 07:29:54.817   933   933 D RttService: SCAN_AVAILABLE : 1
08-29 07:29:54.817   933  3143 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 07:29:54.817  3569  3773 W QCNEJ   : |CORE| network lost: 100
08-29 07:29:54.818   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 07:29:54.818  3192  5615 D BluetoothMap: onBluetoothStateChange: up=false
08-29 07:29:54.818  3569  3773 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
08-29 07:29:54.819   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:29:54.819   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:29:54.819  4463  4542 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 07:29:54.819  4463  4542 D BluetoothAdapterProperties: Setting state to 16
08-29 07:29:54.819  4463  4542 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 07:29:54.821  4463  4542 D BluetoothAdapterProperties: onBleDisable
08-29 07:29:54.821  4463  4542 I BluetoothAdapterState: Entering PendingCommandState
08-29 07:29:54.821  4463  4543 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 07:29:54.822  4463  4546 D BluetoothAdapterProperties: Scan Mode:20
08-29 07:29:54.823  4463  4670 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 07:29:54.823  5616  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,08-29 07:29:54.823  4463  4670 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:29:54.825   933  3035 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 07:29:54.826  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:29:54.827  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:29:54.827  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:54.827  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:54.827  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:29:54.827  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:29:54.827  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:29:54.827  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:29:54.827  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:29:54.829  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 07:29:54.829  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:29:54.829  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:54.829  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:54.829  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:29:54.829  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:29:54.829  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:29:54.829  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:29:54.829  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:29:54.832  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:29:54.835  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:54.839   933  3035 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 07:29:54.839   933  3035 E native  : do suspend true
,08-29 07:29:54.856   508   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 07:29:54.862  5669  5669 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,08-29 07:29:54.872  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 07:29:54.874   508   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 07:29:54.874   508   926 D CommandListener: Clearing all IP addresses on wlan0
,08-29 07:29:54.875   933  3037 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 07:29:54.875   508   926 D TetherController: Setting IP forward enable = 0
,08-29 07:29:54.875   933  3037 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 07:29:54.877   933   950 D Tethering: MasterInitialState.processMessage what=3
,08-29 07:29:54.879   933  3035 D DhcpClient: doQuit
,08-29 07:29:54.879   933  3035 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 07:29:54.880  5214  5214 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@8cee53a and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-29 07:29:54.880   933  5291 D DhcpClient: onQuitting
08-29 07:29:54.880  3718  3718 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
08-29 07:29:54.883   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aac75b0:true
08-29 07:29:54.884  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:29:54.884  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:29:54.884  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:54.884  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:54.884  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:29:54.884  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:29:54.884  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:29:54.884  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:29:54.884  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:29:54.886  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:29:54.886  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:29:54.886  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 07:29:54.888  4919  4953 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 07:29:54.888  4919  4953 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 07:29:54.888  4919  4953 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 07:29:54.888  4919  4953 E SarControlService: no key has been found,reset the power
08-29 07:29:54.888  4919  4972 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,08-29 07:29:54.888  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 07:29:54.888  4919  4972 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 07:29:54.888  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:29:54.888  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:54.888  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:54.888  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:29:54.888  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:29:54.888  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:29:54.888  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:29:54.888  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:29:54.889  4919  4972 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 07:29:54.889  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 07:29:54.889  4959  4959 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 07:29:54.889  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:29:54.890  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:29:54.890  4919  4972 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 07:29:54.891  4919  4972 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 07:29:54.891  4919  4972 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 07:29:54.891  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 07:29:54.891  4959  4959 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 07:29:54.892  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:54.893  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:54.895  4959  4974 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@477d70 HexData = [00000000ea03000000000000ffffffff]
08-29 07:29:54.895  4959  4974 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 07:29:54.896  4959  4974 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
08-29 07:29:54.896  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 07:29:54.896  4919  4929 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,08-29 07:29:54.904   933   944 I ActivityManager: Start proc 5694:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-29 07:29:54.905  4959  4974 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@477d70 HexData = [00000000eb03000000000000ffffffff]
08-29 07:29:54.905  4959  4974 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 07:29:54.905  4959  4974 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
08-29 07:29:54.906  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 07:29:54.906  4919  4930 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-29 07:29:54.921  5669  5669 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 07:29:54.924  5669  5669 D BluetoothMap: Create BluetoothMap proxy object
,08-29 07:29:54.932   508   926 E Netd    : netlink response contains error (No such file or directory)
,08-29 07:29:54.933   508   926 D TetherController: Setting IP forward enable = 0
08-29 07:29:54.934  5669  5669 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 07:29:54.934   933  3037 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 07:29:54.934   933  3037 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 07:29:54.944  5694  5694 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,08-29 07:29:54.949  5669  5669 D DockEventReceiver: finishStartingService: stopping service
,08-29 07:29:54.958   933  3494 I ActivityManager: Killing 5042:com.google.android.gm/u0a68 (adj 15): empty #17
,08-29 07:29:54.964  3718  3718 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 07:29:54.969  3718  3718 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 07:29:55.029  3718  3718 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 07:29:55.031  4463  4546 I bt_hci  : shut_down
,08-29 07:29:55.033  4463  4552 D bt_hwcfg: hw_epilog_process
,08-29 07:29:55.034  4463  4552 I bt_vendor: low_power_mode_cb
,08-29 07:29:55.037  4463  4552 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 07:29:55.037  4463  4552 I bt_vendor: epilog_cb
08-29 07:29:55.037  4463  4552 I bt_hci  : epilog_finished_callback
,08-29 07:29:55.040  4463  4546 I bt_hci_h4: hal_close
,08-29 07:29:55.041  4463  4546 I bt_userial_vendor: device fd = 51 close
,08-29 07:29:55.045  3718  3718 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 07:29:55.148   933  3035 D wifi    : In wifi stop Hal
,08-29 07:29:55.148   933  3035 D wifi    : halHandle = 0x7f7b3e37e0, mVM = 0x7f9078d140, mCls = 0x100b12
08-29 07:29:55.148  4304  4304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 07:29:55.148   933  3706 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,08-29 07:29:55.148   933  3706 D WifiHAL : Got a signal to exit!!!
,08-29 07:29:55.148   933  3706 I WifiHAL : Exit wifi_event_loop
08-29 07:29:55.149   933  3035 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
08-29 07:29:55.149   933  3035 E WifiHAL : Event processing terminated
08-29 07:29:55.149   933  3035 D wifi    : In wifi cleaned up handler
08-29 07:29:55.150   933  3035 I WifiHAL : Internal cleanup completed
08-29 07:29:55.152  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:55.153  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:55.153  3541  4049 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 07:29:55.154  4463  4543 D bt_stack_manager: event_shut_down_stack finished.
,08-29 07:29:55.154  4463  4542 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 07:29:55.156  4463  4542 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 07:29:55.156  4463  4463 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 07:29:55.157  4463  4463 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 07:29:55.157  4463  4463 D BtGatt.GattService: stop()
08-29 07:29:55.157  4463  4463 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 07:29:55.158  4463  4463 V BluetoothAdapterState: isTurningOff()=false
08-29 07:29:55.158  4463  4463 V BluetoothAdapterState: isTurningOn()=false
08-29 07:29:55.158  4463  4463 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:29:55.158  4463  4463 V BluetoothAdapterState: isBleTurningOff()=true
08-29 07:29:55.158  4463  4542 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 07:29:55.159  4463  4542 D BluetoothAdapterProperties: Setting state to 10
08-29 07:29:55.159  4463  4542 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 07:29:55.159  4463  4542 I BluetoothAdapterState: Entering OffState
08-29 07:29:55.160   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 07:29:55.166  4463  4463 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 07:29:55.166  4463  4463 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 07:29:55.166  4463  4463 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 07:29:55.167  4463  4543 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 07:29:55.168  4463  4543 D bt_stack_manager: event_clean_up_stack finished.
08-29 07:29:55.172  4463  4463 I art     : System.exit called, status: 0
,08-29 07:29:55.172  4463  4463 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 07:29:55.174   933  3706 D wifi    : set interface wlan0 flags (DOWN)
,08-29 07:29:55.174   933  3035 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 07:29:55.184  5694  5694 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:29:55.184  5694  5694 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:29:55.184  5694  5694 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:29:55.184  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:29:55.195  5694  5694 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:29:55.195  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:29:55.195  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:29:55.200  5694  5694 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:29:55.200  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:29:55.200  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:29:55.204  5694  5694 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:29:55.204  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:29:55.204  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:29:55.210  5694  5694 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:29:55.210  5694  5694 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:29:55.210  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:29:55.216  5616  5616 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 07:29:55.227   933  3631 I ActivityManager: Process com.android.bluetooth (pid 4463) has died
08-29 07:29:55.231  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 07:29:55.245   933  3643 I ActivityManager: Start proc 5733:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
08-29 07:29:55.246  5669  5669 D DockEventReceiver: finishStartingService: stopping service
08-29 07:29:55.249   933  3187 I ActivityManager: Killing 5318:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,08-29 07:29:55.340  5733  5733 D AdapterServiceConfig: Adding HeadsetService
08-29 07:29:55.341  5733  5733 D AdapterServiceConfig: Adding A2dpService
08-29 07:29:55.341  5733  5733 D AdapterServiceConfig: Adding HidService
,08-29 07:29:55.341  5733  5733 D AdapterServiceConfig: Adding HealthService
08-29 07:29:55.341  5733  5733 D AdapterServiceConfig: Adding PanService
08-29 07:29:55.341  5733  5733 D AdapterServiceConfig: Adding GattService
08-29 07:29:55.341  5733  5733 D AdapterServiceConfig: Adding BluetoothMapService
08-29 07:29:55.341  5733  5733 D AdapterServiceConfig: Adding SapService
08-29 07:29:55.343   933  3185 I ActivityManager: Killing 5330:com.android.chrome/u0a39 (adj 15): empty #17
,08-29 07:29:55.409  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 07:29:55.412   933   950 D Tethering: InitialState.processMessage what=4
,08-29 07:29:55.414   933   950 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 07:29:55.418  3928  3928 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 07:29:55.421  3928  3928 D SystemUpdateService: onCreate
,08-29 07:29:55.427  3928  3928 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 07:29:55.434  3928  5745 I SystemUpdateService: active receiver: enabled
,08-29 07:29:55.436  3928  3928 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*,
,08-29 07:29:55.442  3928  3928 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 07:29:55.444  3928  3928 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 07:29:55.446  3928  5316 I iu.UploadsManager: num queued entries: 0
,08-29 07:29:55.447  3928  5316 I iu.UploadsManager: num updated entries: 0
,08-29 07:29:55.448  3928  5316 I iu.SyncManager: NEXT; no task
,08-29 07:29:55.458   933   943 I ActivityManager: Start proc 5747:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 07:29:55.465  3928  5745 I SystemUpdateService: showing system update notification
,08-29 07:29:55.492  5747  5747 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,08-29 07:29:55.496  5747  5747 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 07:29:55.502  5747  5747 D SprintDMHelper: simOperator: 
,08-29 07:29:55.503  5747  5747 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 07:29:55.511  5694  5725 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 07:29:55.516   933   944 I ActivityManager: Start proc 5759:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 07:29:55.517  3928  5745 V SystemUpdateService: retry (wakeup: false) in 3599930 ms
,08-29 07:29:55.519  3928  3928 D SystemUpdateService: onDestroy
08-29 07:29:55.521   933  3494 I ActivityManager: Killing 5353:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,08-29 07:29:55.550   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5a83037:true
,08-29 07:29:55.634  4304  5775 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 07:29:55.644   933  3572 I ActivityManager: Start proc 5776:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 07:29:55.647   933  3572 I ActivityManager: Killing 5214:com.google.android.music:main/u0a59 (adj 15): empty #17
,08-29 07:29:55.686  5776  5776 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 07:29:55.848   933  3643 I ActivityManager: Killing 4556:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-29 07:29:55.893   933  3185 I ActivityManager: Start proc 5788:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 07:29:55.934  5788  5788 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,08-29 07:29:55.974  5788  5788 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 07:29:55.978   933  3494 I ActivityManager: Killing 5502:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-29 07:29:57.742   933  3643 D WifiService: setWifiEnabled: true pid=5616, uid=10077
,08-29 07:29:57.743   933  3643 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 07:29:57.750   508   926 D SoftapController: Softap fwReload - Ok
,08-29 07:29:57.754   508   926 D CommandListener: Setting iface cfg
,08-29 07:29:57.755   508   926 D CommandListener: Trying to bring down wlan0
,08-29 07:29:57.756   508   926 D CommandListener: Clearing all IP addresses on wlan0
,08-29 07:29:57.760   933  3035 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 07:29:58.369   933  3035 D wifi    : set interface wlan0 flags (UP)
08-29 07:29:58.374   933  3035 I WifiHAL : Initializing wifi
,08-29 07:29:58.374   933  3035 I WifiHAL : Creating socket
,08-29 07:29:58.378   933   950 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 07:29:58.381   933  3035 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-29 07:29:58.382   933  3035 D wifi    : Did set static halHandle = 0x7f7b3e37e0
08-29 07:29:58.382   933  3035 D wifi    : halHandle = 0x7f7b3e37e0, mVM = 0x7f9078d140, mCls = 0x2016c6
08-29 07:29:58.382   933  3035 D wifi    : array field set
,08-29 07:29:58.382   933  3035 I WifiNative-HAL: interface[0] = wlan0
08-29 07:29:58.384   933  5816 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547528521696
08-29 07:29:58.384   933  5816 D wifi    : waitForHalEvents called, vm = 0x7f9078d140, obj = 0x2016c6, env = 0x7f71f61d40
,08-29 07:29:58.441  5817  5817 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 07:29:58.461  5817  5817 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 07:29:58.471  5817  5817 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 07:29:58.471  5817  5817 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 07:29:58.485   933  3035 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 07:29:58.490  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:58.491  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:29:58.498  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:29:58.498  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:29:58.498  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:58.498  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:58.498  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:29:58.498  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:29:58.498  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:29:58.498  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:29:58.498  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:29:58.499  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 07:29:58.499  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:29:58.499   933  3035 D WifiConfigStore: Loading config and enabling all networks 
08-29 07:29:58.500  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:29:58.500  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:29:58.500  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:29:58.500  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:29:58.500  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:29:58.500  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:29:58.500  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:29:58.500  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:29:58.500  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:29:58.500  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:29:58.500  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:29:58.504   933  3035 D WifiConfigStore: loaded 0 passpoint configs
,08-29 07:29:58.504   933  3035 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 07:29:58.505   933  3035 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 07:29:58.506   933  3035 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 07:29:58.507   933  3035 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 07:29:58.507   933  3035 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-29 07:29:58.510  4304  4304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 07:29:58.511   933  3035 D WifiNative-HAL: Setting external_sim to 1
08-29 07:29:58.511   933  3035 D wifi    : setting dfs flag to true, 0x7f77fb8c60
08-29 07:29:58.512   933  3035 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 07:29:58.512   933  3035 D wifi    : setting scan oui 0x7f77fb8c60
08-29 07:29:58.512   933  3035 D WifiHAL : Sending mac address OUI
,08-29 07:29:58.527   933  3035 E native  : do suspend true
,08-29 07:29:58.532   933   933 D RttService: SCAN_AVAILABLE : 3
,08-29 07:29:58.533   933  3035 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 07:29:58.533   508   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 07:29:58.533   933  3143 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 07:29:58.534   508   926 D CommandListener: Setting iface cfg
,08-29 07:29:58.539   933  3034 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,08-29 07:29:58.539   933  3034 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 07:29:58.546   933  3034 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 07:29:58.546   933  3034 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 07:29:58.552   933   948 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=178557 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=7 mControllerEnergyUsed=26 }
,08-29 07:30:00.746   933  3629 D WifiService: setWifiEnabled: false pid=5616, uid=10077
,08-29 07:30:00.747   933  3629 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 07:30:00.755   933   933 D RttService: SCAN_AVAILABLE : 1
,08-29 07:30:00.756   933  3143 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 07:30:00.766   933  3035 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 07:30:00.767   508   926 D CommandListener: Clearing all IP addresses on wlan0
,08-29 07:30:00.769   933  3035 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 07:30:00.770  5817  5817 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-29 07:30:00.776  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 07:30:00.776  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:30:00.776  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:00.776  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:00.776  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:30:00.776  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:30:00.776  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:00.776  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:00.776  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:30:00.777  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:30:00.777  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:30:00.780  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:30:00.781  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:30:00.781  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:00.781  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:00.781  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:30:00.781  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:30:00.781  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:00.781  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:00.781  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:30:00.781  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:30:00.781  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:30:00.789  5817  5817 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 07:30:00.805  5817  5817 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 07:30:00.815  5817  5817 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 07:30:00.822   933  3035 D wifi    : In wifi stop Hal
,08-29 07:30:00.822  4304  4304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 07:30:00.822   933  3035 D wifi    : halHandle = 0x7f7b3e37e0, mVM = 0x7f9078d140, mCls = 0x2016c6
08-29 07:30:00.822   933  5816 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 07:30:00.822   933  5816 D WifiHAL : Got a signal to exit!!!
08-29 07:30:00.822   933  5816 I WifiHAL : Exit wifi_event_loop
,08-29 07:30:00.822   933  3035 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
08-29 07:30:00.822   933  3035 E WifiHAL : Event processing terminated
08-29 07:30:00.823   933  3035 D wifi    : In wifi cleaned up handler
08-29 07:30:00.823   933  3035 I WifiHAL : Internal cleanup completed
08-29 07:30:00.823  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:00.825  3541  4049 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 07:30:00.825  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:30:00.851   933  5816 D wifi    : set interface wlan0 flags (DOWN)
,08-29 07:30:00.851   933  3035 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 07:30:01.060   933   950 D Tethering: InitialState.processMessage what=4
,08-29 07:30:01.068   933   950 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 07:30:03.774   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@59b7079:true
,08-29 07:30:03.775  5733  5733 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 07:30:03.778  5733  5733 I bt_bluedroid: init
08-29 07:30:03.778  5733  5823 I BluetoothAdapterState: Entering OffState
,08-29 07:30:03.780  5733  5824 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 07:30:03.781  5733  5824 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 07:30:03.781  5733  5824 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 07:30:03.781  5733  5824 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 07:30:03.781  5733  5733 I bt_bluedroid: get_profile_interface socket
,08-29 07:30:03.783  5733  5827 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 07:30:03.783  5733  5733 I bt_bluedroid: get_profile_interface sdp
,08-29 07:30:03.786  5733  5827 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 07:30:03.787  5733  5743 I bt_bluedroid: config_hci_snoop_log
,08-29 07:30:03.788   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 07:30:03.794  5733  5823 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 07:30:03.795  5733  5823 D BluetoothAdapterProperties: Setting state to 14
08-29 07:30:03.795  5733  5823 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-29 07:30:03.796  5733  5823 D BluetoothBondStateMachine: make
,08-29 07:30:03.798  5733  5828 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 07:30:03.801  5733  5823 I BluetoothAdapterState: Entering PendingCommandState
,08-29 07:30:03.802  5733  5733 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 07:30:03.805  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
08-29 07:30:03.806  5733  5733 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 07:30:03.807  5733  5733 D BtGatt.GattService: Received start request. Starting profile...
08-29 07:30:03.807  5733  5733 D BtGatt.GattService: start()
08-29 07:30:03.807  5733  5733 I bt_bluedroid: get_profile_interface gatt
,08-29 07:30:03.808  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
08-29 07:30:03.808  5733  5733 D BtGatt.AdvertiseManager: advertise manager created
,08-29 07:30:03.814  5733  5733 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:03.814  5733  5733 V BluetoothAdapterState: isTurningOn()=false
08-29 07:30:03.814  5733  5733 V BluetoothAdapterState: isBleTurningOn()=true
08-29 07:30:03.815  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:03.815  5733  5823 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 07:30:03.815  5733  5823 I bt_bluedroid: enable
08-29 07:30:03.815  5733  5824 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 07:30:03.816  5733  5824 I bt_hci  : start_up
,08-29 07:30:03.821  5733  5824 I bt_vendor: alloc value 0xf41ed04d
08-29 07:30:03.821  5733  5824 I bt_vendor: init
08-29 07:30:03.821  5733  5824 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-29 07:30:03.821  5733  5824 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 07:30:03.939  5733  5824 D bt_hci  : start_up starting async portion
,08-29 07:30:03.940  5733  5831 I bt_hci  : event_finish_startup
08-29 07:30:03.940  5733  5831 I bt_hci_h4: hal_open
08-29 07:30:03.940  5733  5831 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 07:30:03.933  5832  5832 W irq/448-msm_hs_: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 07:30:03.943  5733  5831 I bt_userial_vendor: device fd = 51 open
,08-29 07:30:03.958  5733  5831 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 07:30:03.962  5733  5831 D bt_hwcfg: Chipset BCM4358A3
08-29 07:30:03.962  5733  5831 D bt_hwcfg: Target name = [BCM4358A3]
08-29 07:30:03.963  5733  5831 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 07:30:04.363  5733  5831 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-29 07:30:04.364  5733  5831 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 07:30:04.364  5733  5831 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 07:30:04.499  5733  5831 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-29 07:30:04.499  5733  5831 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 07:30:04.500  5733  5831 I bt_hwcfg: vendor lib fwcfg completed
08-29 07:30:04.501  5733  5831 I bt_vendor: firmware callback
08-29 07:30:04.501  5733  5831 I bt_hci  : firmware_config_callback
,08-29 07:30:04.510  5733  5835 I bt_btu  : btu_task pending for preload complete event
,08-29 07:30:04.511  5733  5835 I bt_btu_task: Bluetooth chip preload is complete
,08-29 07:30:04.511  5733  5835 I bt_btu  : btu_task received preload complete event
,08-29 07:30:04.517  5733  5835 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 07:30:04.518  5733  5835 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 07:30:04.518  5733  5835 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 07:30:04.518  5733  5835 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 07:30:04.518  5733  5835 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 07:30:04.518  5733  5835 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 07:30:04.518  5733  5835 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 07:30:04.518  5733  5835 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 07:30:04.518  5733  5835 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 07:30:04.519  5733  5835 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 07:30:04.519  5733  5835 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 07:30:04.519  5733  5835 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 07:30:04.519  5733  5835 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 07:30:04.519  5733  5835 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 07:30:04.519  5733  5835 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 07:30:04.601  5733  5835 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf416ac99
,08-29 07:30:04.601  5733  5835 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf416ac99 
,08-29 07:30:04.621  5733  5827 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 07:30:04.622  5733  5827 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 07:30:04.623  5733  5827 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 07:30:04.625  5733  5827 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 07:30:04.628  5733  5827 D BluetoothAdapterProperties: Scan Mode:20
,08-29 07:30:04.628  5733  5827 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 07:30:04.629  5733  5827 D bt_hci  : do_postload posting postload work item
,08-29 07:30:04.629  5733  5831 I bt_hci  : event_postload
08-29 07:30:04.629  5733  5831 I bt_vendor: sco_config_cb
08-29 07:30:04.629  5733  5831 I bt_hci  : sco_config_callback postload finished.
08-29 07:30:04.632  5733  5827 D bt_bte_conf: Device ID record 1 : primary
08-29 07:30:04.632  5733  5827 D bt_bte_conf:   vendorId            = 000f
08-29 07:30:04.632  5733  5827 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 07:30:04.632  5733  5827 D bt_bte_conf:   product             = 1200
08-29 07:30:04.632  5733  5827 D bt_bte_conf:   version             = 1436
08-29 07:30:04.632  5733  5827 D bt_bte_conf:   clientExecutableURL = 
08-29 07:30:04.632  5733  5827 D bt_bte_conf:   serviceDescription  = 
08-29 07:30:04.633  5733  5827 D bt_bte_conf:   documentationURL    = 
08-29 07:30:04.633  5733  5827 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 07:30:04.633  5733  5824 D bt_stack_manager: event_start_up_stack finished
08-29 07:30:04.634  5733  5823 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 07:30:04.635  5733  5823 D BluetoothAdapterProperties: Setting state to 15
08-29 07:30:04.635  5733  5823 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 07:30:04.636  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:04.638  5733  5823 I BluetoothAdapterState: Entering BleOnState
,08-29 07:30:04.638  5733  5831 I bt_vendor: low_power_mode_cb
08-29 07:30:04.640  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:04.641  5733  5823 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 07:30:04.641  5733  5823 D BluetoothAdapterProperties: Setting state to 11
08-29 07:30:04.641  5733  5823 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 07:30:04.647  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
,08-29 07:30:04.648  5733  5733 D HeadsetService: Received start request. Starting profile...
,08-29 07:30:04.651  5733  5733 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 07:30:04.651  5733  5733 D HeadsetStateMachine: make
08-29 07:30:04.653  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:04.657  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:30:04.662  5733  5823 I BluetoothAdapterState: Entering PendingCommandState
,08-29 07:30:04.664  5733  5733 D HeadsetStateMachine: max_hf_connections = 1
,08-29 07:30:04.665  5733  5733 I bt_bluedroid: get_profile_interface handsfree
08-29 07:30:04.665  5733  5827 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 07:30:04.665  5733  5827 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 07:30:04.669  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
,08-29 07:30:04.670  5733  5733 D A2dpService: Received start request. Starting profile...
,08-29 07:30:04.670  5733  5733 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 07:30:04.671  5733  5733 I bt_bluedroid: get_profile_interface avrcp
,08-29 07:30:04.677  5733  5733 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 07:30:04.677  5733  5733 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 07:30:04.677  5733  5733 D A2dpStateMachine: make
08-29 07:30:04.678  5733  5733 I bt_bluedroid: get_profile_interface a2dp
,08-29 07:30:04.679  5733  5827 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 07:30:04.681  5733  5844 D A2dpStateMachine: Enter Disconnected: -2
,08-29 07:30:04.681  5733  5733 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 07:30:04.682  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
,08-29 07:30:04.684  5733  5733 D HidService: Received start request. Starting profile...
,08-29 07:30:04.684  5733  5733 I bt_bluedroid: get_profile_interface hidhost
08-29 07:30:04.684  5733  5827 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf414c2d9
08-29 07:30:04.684  5733  5733 D HidService: setHidService(): set to: null
08-29 07:30:04.684  5733  5827 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 07:30:04.685  5733  5733 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 07:30:04.686  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
08-29 07:30:04.686  5733  5733 D HealthService: Received start request. Starting profile...
08-29 07:30:04.687  5669  5669 D BluetoothInputDevice: Proxy object connected
08-29 07:30:04.687  5669  5669 D HidProfile: Bluetooth service connected
08-29 07:30:04.687  5733  5733 I bt_bluedroid: get_profile_interface health
08-29 07:30:04.688  5733  5733 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 07:30:04.689  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
,08-29 07:30:04.691  5733  5733 D PanService: Received start request. Starting profile...
08-29 07:30:04.691  5733  5733 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 07:30:04.691  5733  5733 I bt_bluedroid: get_profile_interface pan
08-29 07:30:04.691  5733  5827 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 07:30:04.693  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
08-29 07:30:04.694  5669  5669 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 07:30:04.694  5733  5733 D BluetoothMapService: Received start request. Starting profile...
08-29 07:30:04.694  5733  5733 D BluetoothMapService: start()
08-29 07:30:04.694  5669  5669 D PanProfile: Bluetooth service connected
08-29 07:30:04.695  5669  5669 D BluetoothMap: Proxy object connected
08-29 07:30:04.696  5669  5669 D MapProfile: Bluetooth service connected
08-29 07:30:04.696  5669  5669 D BluetoothMap: getConnectedDevices()
08-29 07:30:04.696  5669  5669 D BluetoothMap: Bluetooth is Not enabled
,08-29 07:30:04.697  5733  5733 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 07:30:04.698  5733  5733 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 07:30:04.698  5733  5733 D BluetoothMapAppObserver: createReceiver()
08-29 07:30:04.700  5733  5733 D BluetoothMapAppObserver: initObservers()
08-29 07:30:04.700  5733  5733 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 07:30:04.706  5733  5733 V SapService: SapBinder()
,08-29 07:30:04.707  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
08-29 07:30:04.707  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 07:30:04.708  5733  5733 D SapService: Received start request. Starting profile...
08-29 07:30:04.708  5733  5733 V SapService: start()
,08-29 07:30:04.711  5733  5733 V BluetoothAdapterState: isTurningOff()=false
,08-29 07:30:04.711  5733  5733 V BluetoothAdapterState: isTurningOn()=true
08-29 07:30:04.711  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:04.711  5733  5840 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 07:30:04.711  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isTurningOn()=true
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isTurningOn()=true
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isTurningOn()=true
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isTurningOn()=true
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:04.712  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:04.713  5733  5733 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:04.713  5733  5733 V BluetoothAdapterState: isTurningOn()=true
08-29 07:30:04.713  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:04.713  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 07:30:04.714  5733  5733 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:04.714  5733  5733 V BluetoothAdapterState: isTurningOn()=true
08-29 07:30:04.714  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:04.714  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 07:30:04.714  5733  5823 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 07:30:04.714  5733  5823 D BluetoothAdapterProperties: ScanMode =  20
08-29 07:30:04.714  5733  5823 D BluetoothAdapterProperties: State =  11
,08-29 07:30:04.716  5733  5827 D BluetoothAdapterProperties: Scan Mode:21
08-29 07:30:04.716  5733  5823 D BluetoothAdapterProperties: Setting state to 12
08-29 07:30:04.716  5733  5823 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 07:30:04.716  5733  5827 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 07:30:04.717  5669  5680 D BluetoothPan: onBluetoothStateChange on: true
08-29 07:30:04.717  5733  5823 I BluetoothAdapterState: Entering OnState
08-29 07:30:04.717  3192  3204 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 07:30:04.719  3192  3203 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:30:04.720  3192  3204 D BluetoothPan: onBluetoothStateChange on: true
08-29 07:30:04.720  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:30:04.720  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:04.720  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:04.720  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:30:04.720  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:30:04.720  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:04.720  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:04.720  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:30:04.720  3192  3192 D BluetoothA2dp: Proxy object connected
08-29 07:30:04.722  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:30:04.725  5733  5733 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 07:30:04.725  5733  5733 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 07:30:04.725  3192  3192 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 07:30:04.725  3192  5615 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 07:30:04.725  3192  3192 D PanProfile: Bluetooth service connected
08-29 07:30:04.726  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:30:04.726  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:04.726  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:04.726  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:30:04.726  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:30:04.726  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:04.726  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:04.726  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:30:04.727   933   950 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 07:30:04.727  3192  3192 D BluetoothInputDevice: Proxy object connected
08-29 07:30:04.727  3192  3192 D HidProfile: Bluetooth service connected
08-29 07:30:04.728  5733  5733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:30:04.728   933   933 D BluetoothA2dp: Proxy object connected
08-29 07:30:04.728  3192  3204 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 07:30:04.729  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:30:04.730  3616  5691 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:30:04.730  5733  5733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:30:04.731  5669  5685 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 07:30:04.731  5733  5733 D ObexServerSockets: Succeed to create listening sockets 
08-29 07:30:04.732  5733  5733 D ObexServerSockets0: startAccept()
08-29 07:30:04.732  5733  5733 D ObexServerSockets0: prepareForNewConnect()
,08-29 07:30:04.733   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:30:04.734  5733  5733 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 07:30:04.734  3192  3203 D BluetoothMap: onBluetoothStateChange: up=true
08-29 07:30:04.734  5733  5733 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 07:30:04.734  5733  5849 D ObexServerSockets0: Accepting socket connection...
08-29 07:30:04.735  5733  5850 D ObexServerSockets0: Accepting socket connection...
08-29 07:30:04.735  3192  3192 D BluetoothMap: Proxy object connected
08-29 07:30:04.736  5669  5680 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 07:30:04.736  3192  3192 D MapProfile: Bluetooth service connected
08-29 07:30:04.736  3192  3192 D BluetoothMap: getConnectedDevices()
08-29 07:30:04.736   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:30:04.736  5669  5685 D BluetoothMap: onBluetoothStateChange: up=true
08-29 07:30:04.737   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 07:30:04.738   933   933 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 07:30:04.738  5733  5733 D BluetoothMapService: onReceive
08-29 07:30:04.738  5733  5733 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 07:30:04.738  5733  5733 D BluetoothMapService: STATE_ON
,08-29 07:30:04.741  5669  5669 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 07:30:04.741  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:04.741  5733  5851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:30:04.742  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:30:04.743  5733  5851 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 07:30:04.743  5733  5851 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 07:30:04.745  5669  5669 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 07:30:04.752  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 07:30:04.755  5669  5669 D BluetoothA2dp: Proxy object connected
,08-29 07:30:04.759  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 07:30:04.760  5669  5669 D DockEventReceiver: finishStartingService: stopping service
,08-29 07:30:04.765  5669  5669 D BluetoothPbap: Proxy object connected
,08-29 07:30:04.765  5733  5733 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 07:30:04.766  5733  5733 D ObexServerSockets0: prepareForNewConnect()
08-29 07:30:04.766  5669  5669 D PbapServerProfile: Bluetooth service connected
08-29 07:30:04.767  3192  3192 D BluetoothPbap: Proxy object connected
,08-29 07:30:04.767  3192  3192 D PbapServerProfile: Bluetooth service connected
,08-29 07:30:04.773  5733  5855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:30:04.784  5733  5859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:30:04.786  5733  5859 I BtOppRfcommListener: Accept thread started.
,08-29 07:30:04.821   933   933 D BluetoothHeadset: Proxy object connected
08-29 07:30:04.821  3616  3816 D BluetoothHeadset: Proxy object connected
08-29 07:30:04.822   933   933 D BluetoothHeadset: Proxy object connected
,08-29 07:30:04.822   933   933 D BluetoothHeadset: Proxy object connected
08-29 07:30:04.822  3192  5615 D BluetoothHeadset: Proxy object connected
08-29 07:30:04.822  3192  3192 D HeadsetProfile: Bluetooth service connected
,08-29 07:30:04.831  3616  3635 D BluetoothHeadset: Proxy object connected
,08-29 07:30:04.833   933   950 D BluetoothHeadset: Proxy object connected
,08-29 07:30:04.836   933   950 D BluetoothHeadset: Proxy object connected
,08-29 07:30:04.838   933   950 D BluetoothHeadset: Proxy object connected
,08-29 07:30:04.847  5669  5680 D BluetoothHeadset: Proxy object connected
,08-29 07:30:04.848  5669  5669 D HeadsetProfile: Bluetooth service connected
,08-29 07:30:06.761  5733  5823 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 07:30:06.761  5733  5823 D BluetoothAdapterProperties: Setting state to 13
,08-29 07:30:06.762  5733  5823 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 07:30:06.763  5733  5823 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 07:30:06.765  5733  5823 I BluetoothAdapterState: Entering PendingCommandState
08-29 07:30:06.767  5733  5733 D BluetoothMapService: onReceive
,08-29 07:30:06.767  5733  5733 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 07:30:06.767  5733  5733 D BluetoothMapService: STATE_TURNING_OFF
,08-29 07:30:06.767  5733  5733 D BluetoothMapService: MAP Service closeService in
,08-29 07:30:06.767  5733  5733 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 07:30:06.767  5733  5733 D ObexServerSockets0: shutdown(block = true)
,08-29 07:30:06.768  5733  5733 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 07:30:06.768  5733  5733 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 07:30:06.768  5733  5849 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 07:30:06.768  5733  5850 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 07:30:06.770  5733  5827 D BluetoothAdapterProperties: Scan Mode:20
08-29 07:30:06.771  5733  5823 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 07:30:06.772  5733  5837 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-29 07:30:06.772  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 07:30:06.774  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:30:06.774  5733  5733 I BtOppRfcommListener: stopping Accept Thread
08-29 07:30:06.774  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:30:06.774  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:06.774  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:06.774  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:30:06.774  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:30:06.774  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:06.774  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:06.774  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:30:06.775  5733  5859 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 07:30:06.776  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 07:30:06.777  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:30:06.780  5733  5859 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 07:30:06.782  5733  5733 D HeadsetService: Received stop request...Stopping profile...
08-29 07:30:06.785  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:30:06.785  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:30:06.785  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:06.785  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:06.785  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:30:06.785  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:30:06.785  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:06.785  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:06.785  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:30:06.786  5669  5680 D BluetoothHeadset: Proxy object disconnected
08-29 07:30:06.787  5616  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 07:30:06.787   933   933 D BluetoothHeadset: Proxy object disconnected
08-29 07:30:06.787  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:30:06.787  5733  5733 D A2dpService: Received stop request...Stopping profile...
08-29 07:30:06.787  3616  3633 D BluetoothHeadset: Proxy object disconnected
08-29 07:30:06.787  5733  5844 D A2dpStateMachine: Exit Disconnected: -1
08-29 07:30:06.788   933   933 D BluetoothHeadset: Proxy object disconnected
08-29 07:30:06.788   933   933 D BluetoothHeadset: Proxy object disconnected
,08-29 07:30:06.788  3192  3204 D BluetoothHeadset: Proxy object disconnected
08-29 07:30:06.789  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:06.790  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:06.791  5669  5669 D DockEventReceiver: finishStartingService: stopping service
08-29 07:30:06.792  5669  5669 D HeadsetProfile: Bluetooth service disconnected
08-29 07:30:06.792   933   933 D BluetoothA2dp: Proxy object disconnected
08-29 07:30:06.792  5669  5669 D BluetoothA2dp: Proxy object disconnected
08-29 07:30:06.793  3192  3192 D HeadsetProfile: Bluetooth service disconnected
08-29 07:30:06.793  5733  5733 D HidService: Received stop request...Stopping profile...
08-29 07:30:06.793  5733  5733 D HidService: Stopping Bluetooth HidService
08-29 07:30:06.794  3192  3192 D BluetoothA2dp: Proxy object disconnected
,08-29 07:30:06.795  3192  3192 D BluetoothInputDevice: Proxy object disconnected
08-29 07:30:06.795  3192  3192 D HidProfile: Bluetooth service disconnected
,08-29 07:30:06.799  5733  5733 D HealthService: Received stop request...Stopping profile...
,08-29 07:30:06.800  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 07:30:06.803  5669  5669 D BluetoothInputDevice: Proxy object disconnected
08-29 07:30:06.804  5669  5669 D HidProfile: Bluetooth service disconnected
08-29 07:30:06.804  5733  5733 D PanService: Received stop request...Stopping profile...
,08-29 07:30:06.805  5733  5733 V BluetoothAdapterState: isTurningOff()=true
,08-29 07:30:06.805  5733  5733 V BluetoothAdapterState: isTurningOn()=false
08-29 07:30:06.805  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:06.805  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:06.806  5669  5669 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 07:30:06.806  5669  5669 D PanProfile: Bluetooth service disconnected
08-29 07:30:06.806  3192  3192 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 07:30:06.806  3192  3192 D PanProfile: Bluetooth service disconnected
08-29 07:30:06.807  5733  5733 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 07:30:06.807  5733  5733 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 07:30:06.807  5733  5835 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:30:06.807  5733  5835 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:30:06.807  5733  5835 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 07:30:06.808  5733  5733 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 07:30:06.808  5733  5733 D BluetoothMapService: stop()
08-29 07:30:06.808  5733  5733 D BluetoothMapAppObserver: deinitObservers()
08-29 07:30:06.809  5733  5733 D BluetoothMapAppObserver: removeReceiver()
08-29 07:30:06.809  5733  5827 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-29 07:30:06.809  5733  5827 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 07:30:06.810  3192  3192 D BluetoothMap: Proxy object disconnected
08-29 07:30:06.810  3192  3192 D MapProfile: Bluetooth service disconnected
,08-29 07:30:06.810  5669  5669 D BluetoothMap: Proxy object disconnected
08-29 07:30:06.810  5669  5669 D MapProfile: Bluetooth service disconnected
08-29 07:30:06.813  5733  5733 D SapService: Received stop request...Stopping profile...
08-29 07:30:06.813  5733  5733 V SapService: stop()
08-29 07:30:06.814  5733  5733 V BluetoothAdapterState: isTurningOff()=true
08-29 07:30:06.814  5733  5733 V BluetoothAdapterState: isTurningOn()=false
08-29 07:30:06.814  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:06.814  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:06.815  5733  5733 V BluetoothAdapterState: isTurningOff()=true
08-29 07:30:06.815  5733  5733 V BluetoothAdapterState: isTurningOn()=false
08-29 07:30:06.815  5733  5827 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-29 07:30:06.815  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:06.816  5733  5835 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:30:06.816  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:06.816  5733  5835 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:30:06.816  5733  5835 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 07:30:06.816  5733  5835 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 07:30:06.816  5733  5733 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-29 07:30:06.816  5733  5835 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 07:30:06.816  5733  5733 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 07:30:06.816  5733  5835 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 07:30:06.816  5733  5827 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 07:30:06.819  5733  5733 V BluetoothAdapterState: isTurningOff()=true
08-29 07:30:06.819  5733  5733 V BluetoothAdapterState: isTurningOn()=false
08-29 07:30:06.819  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:06.819  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:06.819  5733  5733 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-29 07:30:06.819  5733  5827 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-29 07:30:06.819  5733  5733 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 07:30:06.820  5733  5733 V BluetoothAdapterState: isTurningOff()=true
08-29 07:30:06.820  3192  3192 D BluetoothPbap: Proxy object disconnected
08-29 07:30:06.820  5733  5733 V BluetoothAdapterState: isTurningOn()=false
08-29 07:30:06.820  3192  3192 D PbapServerProfile: Bluetooth service disconnected
08-29 07:30:06.820  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:06.820  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:06.820  5733  5733 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 07:30:06.821  5733  5733 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 07:30:06.822  5733  5733 D BluetoothMapService: MAP Service closeService in
08-29 07:30:06.822  5733  5733 V BluetoothAdapterState: isTurningOff()=true
08-29 07:30:06.822  5733  5733 V BluetoothAdapterState: isTurningOn()=false
08-29 07:30:06.822  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:06.823  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:06.823  5733  5733 D BluetoothMapService: cleanup()
08-29 07:30:06.823  5733  5733 D BluetoothMapService: MAP Service closeService in
08-29 07:30:06.823  5733  5733 V BluetoothAdapterState: isTurningOff()=true
08-29 07:30:06.823  5733  5733 V BluetoothAdapterState: isTurningOn()=false
08-29 07:30:06.823  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:06.823  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:06.824  5733  5823 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 07:30:06.824  5733  5823 D BluetoothAdapterProperties: Setting state to 15
08-29 07:30:06.824  5733  5823 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 07:30:06.824  5733  5823 I BluetoothAdapterState: Entering BleOnState
,08-29 07:30:06.825  5669  5680 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 07:30:06.826  5669  5685 D BluetoothPan: onBluetoothStateChange on: false
08-29 07:30:06.827  3192  5615 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 07:30:06.827  3192  3204 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:30:06.828  3192  3801 D BluetoothPan: onBluetoothStateChange on: false
08-29 07:30:06.828  3192  3203 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 07:30:06.829   933   950 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 07:30:06.829  3192  5615 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 07:30:06.829  3616  5691 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:30:06.830  5669  5680 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 07:30:06.831   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:30:06.831  3192  3204 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 07:30:06.832  5669  5685 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 07:30:06.832   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:30:06.832  5669  5680 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:30:06.832  5669  5685 D BluetoothMap: onBluetoothStateChange: up=false
08-29 07:30:06.833   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:30:06.833  5733  5823 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 07:30:06.833  5733  5823 D BluetoothAdapterProperties: Setting state to 16
08-29 07:30:06.833  5733  5823 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 07:30:06.834  5669  5669 D BluetoothPbap: Proxy object disconnected
,08-29 07:30:06.834  5669  5669 D PbapServerProfile: Bluetooth service disconnected
08-29 07:30:06.834  5733  5823 D BluetoothAdapterProperties: onBleDisable
08-29 07:30:06.834  5733  5823 I BluetoothAdapterState: Entering PendingCommandState
08-29 07:30:06.834  5733  5824 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 07:30:06.835  5733  5835 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 07:30:06.835  5733  5835 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:30:06.836  5733  5827 D BluetoothAdapterProperties: Scan Mode:20
08-29 07:30:06.837  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:06.838  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 07:30:06.838  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:06.839  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:06.840  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:06.843  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 07:30:06.846  5669  5669 D DockEventReceiver: finishStartingService: stopping service
,08-29 07:30:07.040  5733  5827 I bt_hci  : shut_down
,08-29 07:30:07.044  5733  5831 D bt_hwcfg: hw_epilog_process
,08-29 07:30:07.045  5733  5831 I bt_vendor: low_power_mode_cb
,08-29 07:30:07.047  5733  5831 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 07:30:07.047  5733  5831 I bt_vendor: epilog_cb
08-29 07:30:07.047  5733  5831 I bt_hci  : epilog_finished_callback
08-29 07:30:07.049  5733  5827 I bt_hci_h4: hal_close
08-29 07:30:07.049  5733  5827 I bt_userial_vendor: device fd = 51 close
,08-29 07:30:07.166  5733  5824 D bt_stack_manager: event_shut_down_stack finished.
,08-29 07:30:07.166  5733  5823 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 07:30:07.171  5733  5733 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 07:30:07.172  5733  5823 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 07:30:07.173  5733  5733 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 07:30:07.173  5733  5733 D BtGatt.GattService: stop()
,08-29 07:30:07.173  5733  5733 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 07:30:07.177  5733  5733 V BluetoothAdapterState: isTurningOff()=false
,08-29 07:30:07.177  5733  5733 V BluetoothAdapterState: isTurningOn()=false
08-29 07:30:07.177  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:07.177  5733  5733 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 07:30:07.178  5733  5823 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 07:30:07.178  5733  5823 D BluetoothAdapterProperties: Setting state to 10
08-29 07:30:07.178  5733  5823 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 07:30:07.179  5733  5823 I BluetoothAdapterState: Entering OffState
,08-29 07:30:07.181   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 07:30:07.196  5733  5733 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 07:30:07.196  5733  5733 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 07:30:07.196  5733  5733 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 07:30:07.198  5733  5824 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 07:30:07.200  5733  5824 D bt_stack_manager: event_clean_up_stack finished.
,08-29 07:30:07.203  5733  5733 I art     : System.exit called, status: 0
,08-29 07:30:07.203  5733  5733 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 07:30:07.233   933  3643 I ActivityManager: Process com.android.bluetooth (pid 5733) has died
,08-29 07:30:09.759  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:30:09.759  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:30:10.359   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:30:11.360   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:30:12.361   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:30:12.766  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 07:30:12.766  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@69c1b63 added. We now have 6 listener(s)
,08-29 07:30:12.767  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:30:12.769  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 07:30:12.770  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2620360 added. We now have 7 listener(s)
,08-29 07:30:12.770  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:30:12.772  5616  5662 I System.out: IsBluetoothEnabled
,08-29 07:30:12.778  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:30:12.800   933   950 I ActivityManager: Start proc 5867:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 07:30:12.860  5867  5867 D AdapterServiceConfig: Adding HeadsetService
,08-29 07:30:12.860  5867  5867 D AdapterServiceConfig: Adding A2dpService
08-29 07:30:12.860  5867  5867 D AdapterServiceConfig: Adding HidService
08-29 07:30:12.861  5867  5867 D AdapterServiceConfig: Adding HealthService
08-29 07:30:12.861  5867  5867 D AdapterServiceConfig: Adding PanService
08-29 07:30:12.861  5867  5867 D AdapterServiceConfig: Adding GattService
08-29 07:30:12.861  5867  5867 D AdapterServiceConfig: Adding BluetoothMapService
08-29 07:30:12.861  5867  5867 D AdapterServiceConfig: Adding SapService
,08-29 07:30:12.870   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cec65df:true
,08-29 07:30:12.870  5867  5867 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 07:30:12.873  5867  5867 I bt_bluedroid: init
08-29 07:30:12.873  5867  5879 I BluetoothAdapterState: Entering OffState
,08-29 07:30:12.875  5867  5880 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 07:30:12.875  5867  5880 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 07:30:12.875  5867  5880 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 07:30:12.875  5867  5880 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 07:30:12.876  5867  5867 I bt_bluedroid: get_profile_interface socket
,08-29 07:30:12.878  5867  5883 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 07:30:12.878  5867  5867 I bt_bluedroid: get_profile_interface sdp
08-29 07:30:12.879  5867  5883 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 07:30:12.881  5867  5878 I bt_bluedroid: config_hci_snoop_log
,08-29 07:30:12.882   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-29 07:30:12.886  5867  5879 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 07:30:12.886  5867  5879 D BluetoothAdapterProperties: Setting state to 14
08-29 07:30:12.886  5867  5879 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 07:30:12.887  5867  5879 D BluetoothBondStateMachine: make
,08-29 07:30:12.889  5867  5884 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 07:30:12.892  5867  5879 I BluetoothAdapterState: Entering PendingCommandState
,08-29 07:30:12.893  5867  5867 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 07:30:12.895  5867  5867 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
,08-29 07:30:12.896  5867  5867 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 07:30:12.897  5867  5867 D BtGatt.GattService: Received start request. Starting profile...
08-29 07:30:12.897  5867  5867 D BtGatt.GattService: start()
08-29 07:30:12.897  5867  5867 I bt_bluedroid: get_profile_interface gatt
,08-29 07:30:12.898  5867  5867 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
08-29 07:30:12.898  5867  5867 D BtGatt.AdvertiseManager: advertise manager created
,08-29 07:30:12.903  5867  5867 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:12.903  5867  5867 V BluetoothAdapterState: isTurningOn()=false
08-29 07:30:12.903  5867  5867 V BluetoothAdapterState: isBleTurningOn()=true
08-29 07:30:12.903  5867  5867 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:12.903  5867  5879 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 07:30:12.904  5867  5879 I bt_bluedroid: enable
08-29 07:30:12.904  5867  5880 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 07:30:12.904  5867  5880 I bt_hci  : start_up
,08-29 07:30:12.909  5867  5880 I bt_vendor: alloc value 0xf423904d
,08-29 07:30:12.910  5867  5880 I bt_vendor: init
08-29 07:30:12.910  5867  5880 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 07:30:12.910  5867  5880 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 07:30:13.027  5867  5880 D bt_hci  : start_up starting async portion
,08-29 07:30:13.027  5867  5887 I bt_hci  : event_finish_startup
,08-29 07:30:13.027  5867  5887 I bt_hci_h4: hal_open
08-29 07:30:13.027  5867  5887 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
08-29 07:30:13.023  5888  5888 W irq/448-msm_hs_: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
08-29 07:30:13.029  5867  5887 I bt_userial_vendor: device fd = 51 open
,08-29 07:30:13.041  5867  5887 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 07:30:13.043  5867  5887 D bt_hwcfg: Chipset BCM4358A3
,08-29 07:30:13.043  5867  5887 D bt_hwcfg: Target name = [BCM4358A3]
08-29 07:30:13.043  5867  5887 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 07:30:13.362   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:30:13.438  5867  5887 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-29 07:30:13.438  5867  5887 D bt_hwcfg: Settlement delay -- 100 ms
08-29 07:30:13.439  5867  5887 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 07:30:13.574  5867  5887 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 07:30:13.574  5867  5887 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 07:30:13.576  5867  5887 I bt_hwcfg: vendor lib fwcfg completed
,08-29 07:30:13.597  5867  5887 I bt_vendor: firmware callback
08-29 07:30:13.597  5867  5887 I bt_hci  : firmware_config_callback
,08-29 07:30:13.603  5867  5890 I bt_btu  : btu_task pending for preload complete event
08-29 07:30:13.603  5867  5890 I bt_btu_task: Bluetooth chip preload is complete
08-29 07:30:13.603  5867  5890 I bt_btu  : btu_task received preload complete event
,08-29 07:30:13.607  5867  5890 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 07:30:13.607  5867  5890 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 07:30:13.608  5867  5890 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 07:30:13.608  5867  5890 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 07:30:13.608  5867  5890 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 07:30:13.608  5867  5890 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 07:30:13.608  5867  5890 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 07:30:13.608  5867  5890 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 07:30:13.608  5867  5890 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 07:30:13.608  5867  5890 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 07:30:13.608  5867  5890 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 07:30:13.608  5867  5890 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 07:30:13.608  5867  5890 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 07:30:13.608  5867  5890 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 07:30:13.608  5867  5890 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 07:30:13.687  5867  5890 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41b6c99
,08-29 07:30:13.687  5867  5890 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41b6c99 
,08-29 07:30:13.702  5867  5883 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 07:30:13.703  5867  5883 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 07:30:13.704  5867  5883 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 07:30:13.706  5867  5883 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 07:30:13.709  5867  5883 D BluetoothAdapterProperties: Scan Mode:20
,08-29 07:30:13.709  5867  5883 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 07:30:13.710  5867  5883 D bt_hci  : do_postload posting postload work item
,08-29 07:30:13.710  5867  5887 I bt_hci  : event_postload
08-29 07:30:13.710  5867  5887 I bt_vendor: sco_config_cb
,08-29 07:30:13.710  5867  5887 I bt_hci  : sco_config_callback postload finished.
,08-29 07:30:13.715  5867  5883 D bt_bte_conf: Device ID record 1 : primary
08-29 07:30:13.716  5867  5883 D bt_bte_conf:   vendorId            = 000f
08-29 07:30:13.716  5867  5883 D bt_bte_conf:   vendorIdSource      = 0001
08-29 07:30:13.716  5867  5883 D bt_bte_conf:   product             = 1200
08-29 07:30:13.716  5867  5883 D bt_bte_conf:   version             = 1436
08-29 07:30:13.716  5867  5883 D bt_bte_conf:   clientExecutableURL = 
08-29 07:30:13.716  5867  5883 D bt_bte_conf:   serviceDescription  = 
08-29 07:30:13.716  5867  5883 D bt_bte_conf:   documentationURL    = 
08-29 07:30:13.716  5867  5883 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 07:30:13.716  5867  5880 D bt_stack_manager: event_start_up_stack finished
08-29 07:30:13.717  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:13.718  5867  5887 I bt_vendor: low_power_mode_cb
08-29 07:30:13.718  5867  5879 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 07:30:13.719  5867  5879 D BluetoothAdapterProperties: Setting state to 15
08-29 07:30:13.719  5867  5879 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 07:30:13.719  5867  5879 I BluetoothAdapterState: Entering BleOnState
,08-29 07:30:13.723  5867  5879 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 07:30:13.723  5867  5879 D BluetoothAdapterProperties: Setting state to 11
,08-29 07:30:13.723  5867  5879 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 07:30:13.732  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:30:13.738  5867  5867 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
,08-29 07:30:13.738  5867  5867 D HeadsetService: Received start request. Starting profile...
08-29 07:30:13.741  5867  5867 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 07:30:13.741  5867  5867 D HeadsetStateMachine: make
,08-29 07:30:13.746  5867  5879 I BluetoothAdapterState: Entering PendingCommandState
,08-29 07:30:13.749  5867  5867 D HeadsetStateMachine: max_hf_connections = 1
,08-29 07:30:13.749  5867  5867 I bt_bluedroid: get_profile_interface handsfree
08-29 07:30:13.749  5867  5883 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 07:30:13.749  5867  5883 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 07:30:13.754  5867  5867 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
,08-29 07:30:13.755  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 07:30:13.755  5867  5867 D A2dpService: Received start request. Starting profile...
,08-29 07:30:13.756  5867  5867 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 07:30:13.757  5867  5867 I bt_bluedroid: get_profile_interface avrcp
,08-29 07:30:13.763  5867  5867 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 07:30:13.763  5867  5867 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 07:30:13.763  5867  5867 D A2dpStateMachine: make
08-29 07:30:13.764  5867  5867 I bt_bluedroid: get_profile_interface a2dp
,08-29 07:30:13.765  5867  5883 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 07:30:13.766  5867  5898 D A2dpStateMachine: Enter Disconnected: -2
,08-29 07:30:13.767  5867  5867 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 07:30:13.768  5867  5867 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
,08-29 07:30:13.768  5867  5867 D HidService: Received start request. Starting profile...
,08-29 07:30:13.769  5867  5867 I bt_bluedroid: get_profile_interface hidhost
08-29 07:30:13.769  5867  5883 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41982d9
08-29 07:30:13.769  5867  5867 D HidService: setHidService(): set to: null
08-29 07:30:13.769  5867  5883 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 07:30:13.769  5867  5867 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 07:30:13.770  5867  5867 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
08-29 07:30:13.771  5867  5867 D HealthService: Received start request. Starting profile...
,08-29 07:30:13.773  5867  5867 I bt_bluedroid: get_profile_interface health
,08-29 07:30:13.774  5867  5867 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 07:30:13.775  5867  5867 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
08-29 07:30:13.775  5867  5867 D PanService: Received start request. Starting profile...
08-29 07:30:13.775  5867  5867 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 07:30:13.775  5867  5867 I bt_bluedroid: get_profile_interface pan
08-29 07:30:13.776  5867  5883 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 07:30:13.778  5867  5867 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
08-29 07:30:13.778  5867  5867 D BluetoothMapService: Received start request. Starting profile...
08-29 07:30:13.778  5867  5867 D BluetoothMapService: start()
,08-29 07:30:13.781  5867  5867 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 07:30:13.782  5867  5867 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 07:30:13.782  5867  5867 D BluetoothMapAppObserver: createReceiver()
,08-29 07:30:13.783  5867  5867 D BluetoothMapAppObserver: initObservers()
08-29 07:30:13.783  5867  5867 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 07:30:13.789  5867  5867 V SapService: SapBinder()
08-29 07:30:13.789  5867  5867 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
08-29 07:30:13.790  5867  5867 D SapService: Received start request. Starting profile...
08-29 07:30:13.790  5867  5867 V SapService: start()
08-29 07:30:13.792  5867  5867 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:13.792  5867  5867 V BluetoothAdapterState: isTurningOn()=true
08-29 07:30:13.792  5867  5867 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:13.792  5867  5867 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:13.793  5867  5896 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 07:30:13.793  5867  5867 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:13.793  5867  5867 V BluetoothAdapterState: isTurningOn()=true
,08-29 07:30:13.793  5867  5867 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:13.793  5867  5867 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:13.793  5867  5867 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:13.793  5867  5867 V BluetoothAdapterState: isTurningOn()=true
08-29 07:30:13.793  5867  5867 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:13.793  5867  5867 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:13.794  5867  5867 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:13.794  5867  5867 V BluetoothAdapterState: isTurningOn()=true
08-29 07:30:13.794  5867  5867 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:13.794  5867  5867 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:13.794  5867  5867 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:13.794  5867  5867 V BluetoothAdapterState: isTurningOn()=true
08-29 07:30:13.794  5867  5867 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:13.794  5867  5867 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:13.794  5867  5867 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:13.794  5867  5867 V BluetoothAdapterState: isTurningOn()=true
08-29 07:30:13.794  5867  5867 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:13.794  5867  5867 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:30:13.795  5867  5867 V BluetoothAdapterState: isTurningOff()=false
08-29 07:30:13.795  5867  5867 V BluetoothAdapterState: isTurningOn()=true
08-29 07:30:13.795  5867  5867 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:30:13.795  5867  5867 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 07:30:13.796  5867  5879 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 07:30:13.797  5867  5879 D BluetoothAdapterProperties: ScanMode =  20
08-29 07:30:13.797  5867  5879 D BluetoothAdapterProperties: State =  11
,08-29 07:30:13.797  5867  5879 D BluetoothAdapterProperties: Setting state to 12
08-29 07:30:13.797  5867  5879 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 07:30:13.797  5867  5879 I BluetoothAdapterState: Entering OnState
08-29 07:30:13.797  5669  5680 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 07:30:13.800  5669  5685 D BluetoothPan: onBluetoothStateChange on: true
08-29 07:30:13.800  5867  5883 D BluetoothAdapterProperties: Scan Mode:21
,08-29 07:30:13.800  5867  5883 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 07:30:13.802  3192  3801 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 07:30:13.803  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:30:13.803  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:13.803  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:13.803  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:30:13.803  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:30:13.803  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:13.803  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:13.803  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:30:13.804  3192  3192 D BluetoothA2dp: Proxy object connected
08-29 07:30:13.804  3192  3204 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:30:13.804  3192  5615 D BluetoothPan: onBluetoothStateChange on: true
,08-29 07:30:13.805  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:30:13.806  3192  3192 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 07:30:13.806  3192  3204 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 07:30:13.806  3192  3192 D PanProfile: Bluetooth service connected
08-29 07:30:13.807   933   950 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 07:30:13.808   933   933 D BluetoothA2dp: Proxy object connected
08-29 07:30:13.808  3192  3203 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 07:30:13.808  3192  3192 D BluetoothInputDevice: Proxy object connected
08-29 07:30:13.808  3192  3192 D HidProfile: Bluetooth service connected
08-29 07:30:13.808  5867  5867 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 07:30:13.809  5867  5867 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 07:30:13.809  5669  5669 D BluetoothA2dp: Proxy object connected
08-29 07:30:13.810  3616  3816 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:30:13.810  5867  5867 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:30:13.810  5669  5685 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 07:30:13.811   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:30:13.812  3192  3204 D BluetoothMap: onBluetoothStateChange: up=true
08-29 07:30:13.812  5867  5867 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:30:13.813  5867  5867 D ObexServerSockets: Succeed to create listening sockets 
08-29 07:30:13.813  5867  5867 D ObexServerSockets0: startAccept()
08-29 07:30:13.813  5867  5867 D ObexServerSockets0: prepareForNewConnect()
08-29 07:30:13.813  5669  5680 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 07:30:13.815  5867  5867 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 07:30:13.815  5867  5867 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 07:30:13.815   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 07:30:13.816  5669  5685 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 07:30:13.816  5867  5906 D ObexServerSockets0: Accepting socket connection...
,08-29 07:30:13.816  5867  5905 D ObexServerSockets0: Accepting socket connection...
08-29 07:30:13.817  3192  3192 D BluetoothMap: Proxy object connected
08-29 07:30:13.817  3192  3192 D MapProfile: Bluetooth service connected
08-29 07:30:13.817  3192  3192 D BluetoothMap: getConnectedDevices()
08-29 07:30:13.818  5669  5680 D BluetoothMap: onBluetoothStateChange: up=true
08-29 07:30:13.820   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 07:30:13.821  5669  5669 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 07:30:13.821  5669  5669 D PanProfile: Bluetooth service connected
08-29 07:30:13.821  5669  5669 D BluetoothInputDevice: Proxy object connected
08-29 07:30:13.821  5669  5669 D HidProfile: Bluetooth service connected
08-29 07:30:13.822  5867  5867 D BluetoothMapService: onReceive
08-29 07:30:13.822  5867  5867 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 07:30:13.822  5867  5867 D BluetoothMapService: STATE_ON
08-29 07:30:13.822   933   933 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 07:30:13.823  5669  5669 D BluetoothMap: Proxy object connected
08-29 07:30:13.823  5669  5669 D MapProfile: Bluetooth service connected
08-29 07:30:13.823  5669  5669 D BluetoothMap: getConnectedDevices()
08-29 07:30:13.823  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:13.826  5867  5908 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:30:13.827  5867  5908 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 07:30:13.827  5867  5908 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 07:30:13.829  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 07:30:13.836  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 07:30:13.836  5669  5669 D DockEventReceiver: finishStartingService: stopping service
,08-29 07:30:13.844  5669  5669 D BluetoothPbap: Proxy object connected
,08-29 07:30:13.844  5669  5669 D PbapServerProfile: Bluetooth service connected
,08-29 07:30:13.848  3192  3192 D BluetoothPbap: Proxy object connected
08-29 07:30:13.848  3192  3192 D PbapServerProfile: Bluetooth service connected
,08-29 07:30:13.848  5867  5867 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 07:30:13.849  5867  5867 D ObexServerSockets0: prepareForNewConnect()
08-29 07:30:13.849  5867  5912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:30:13.863  5867  5916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:30:13.864  5867  5916 I BtOppRfcommListener: Accept thread started.
,08-29 07:30:13.906  5669  5903 D BluetoothHeadset: Proxy object connected
,08-29 07:30:13.906   933   933 D BluetoothHeadset: Proxy object connected
,08-29 07:30:13.907  3616  3635 D BluetoothHeadset: Proxy object connected
08-29 07:30:13.907   933   933 D BluetoothHeadset: Proxy object connected
08-29 07:30:13.907   933   933 D BluetoothHeadset: Proxy object connected
08-29 07:30:13.908  3192  5615 D BluetoothHeadset: Proxy object connected
08-29 07:30:13.908  3192  3192 D HeadsetProfile: Bluetooth service connected
08-29 07:30:13.909  5669  5669 D HeadsetProfile: Bluetooth service connected
,08-29 07:30:13.911  3616  3633 D BluetoothHeadset: Proxy object connected
,08-29 07:30:13.911   933   950 D BluetoothHeadset: Proxy object connected
,08-29 07:30:13.917   933   950 D BluetoothHeadset: Proxy object connected
,08-29 07:30:13.917  5669  5680 D BluetoothHeadset: Proxy object connected
08-29 07:30:13.917  5669  5669 D HeadsetProfile: Bluetooth service connected
,08-29 07:30:13.921   933   950 D BluetoothHeadset: Proxy object connected
,08-29 07:30:14.363   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:30:14.794  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:30:14.794  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:14.794  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:14.794  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:30:14.794  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:30:14.794  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:14.794  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:14.794  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:30:14.800  5616  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:30:14.803  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:30:14.803  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d02e019 added. We now have 8 listener(s)
,08-29 07:30:14.804  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:30:14.810   933  3642 D WifiService: setWifiEnabled: false pid=5616, uid=10077
,08-29 07:30:14.811   933  3642 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 07:30:14.822  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:30:14.822   933  3643 D WifiService: setWifiEnabled: true pid=5616, uid=10077
08-29 07:30:14.823   933  3643 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 07:30:14.831   508   926 D SoftapController: Softap fwReload - Ok
,08-29 07:30:14.835   508   926 D CommandListener: Setting iface cfg
08-29 07:30:14.836   508   926 D CommandListener: Trying to bring down wlan0
,08-29 07:30:14.837   508   926 D CommandListener: Clearing all IP addresses on wlan0
,08-29 07:30:14.842   933  3035 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 07:30:15.363   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 07:30:15.444   933  3035 D wifi    : set interface wlan0 flags (UP)
,08-29 07:30:15.444   933  3035 I WifiHAL : Initializing wifi
08-29 07:30:15.444   933  3035 I WifiHAL : Creating socket
,08-29 07:30:15.450   933   950 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 07:30:15.453   933  3035 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-29 07:30:15.453   933  3035 D wifi    : Did set static halHandle = 0x7f7b3e37e0
08-29 07:30:15.453   933  3035 D wifi    : halHandle = 0x7f7b3e37e0, mVM = 0x7f9078d140, mCls = 0x201826
08-29 07:30:15.454   933  3035 D wifi    : array field set
08-29 07:30:15.454   933  3035 I WifiNative-HAL: interface[0] = wlan0
,08-29 07:30:15.458   933  5921 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547528521696
08-29 07:30:15.458   933  5921 D wifi    : waitForHalEvents called, vm = 0x7f9078d140, obj = 0x201826, env = 0x7f71f60480
,08-29 07:30:15.460   933  3035 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 07:30:15.462   933  3035 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-29 07:30:15.464  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:30:15.504  5922  5922 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 07:30:15.523  5922  5922 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 07:30:15.532  5922  5922 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 07:30:15.532  5922  5922 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 07:30:16.477   933  3035 D WifiConfigStore: Loading config and enabling all networks 
,08-29 07:30:16.488   933  3035 D WifiConfigStore: loaded 0 passpoint configs
08-29 07:30:16.488   933  3035 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 07:30:16.489   933  3035 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 07:30:16.491  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:30:16.491  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:16.491  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:16.491  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:30:16.491  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:30:16.491  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:16.491  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:16.491  5616  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:30:16.491   933  3035 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 07:30:16.491   933  3035 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
,08-29 07:30:16.492   933  3035 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-29 07:30:16.496  5616  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:30:16.498   933  3035 D WifiNative-HAL: Setting external_sim to 1
,08-29 07:30:16.498  4304  4304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 07:30:16.499   933  3035 D wifi    : setting dfs flag to true, 0x7f76d58a60
08-29 07:30:16.499   933  3035 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 07:30:16.499   933  3035 D wifi    : setting scan oui 0x7f76d58a60
,08-29 07:30:16.499   933  3035 D WifiHAL : Sending mac address OUI
,08-29 07:30:16.515   933  3035 E native  : do suspend true
,08-29 07:30:16.520   933   933 D RttService: SCAN_AVAILABLE : 3
,08-29 07:30:16.520   933  3035 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 07:30:16.520   508   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 07:30:16.521   933  3143 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 07:30:16.522   508   926 D CommandListener: Setting iface cfg
,08-29 07:30:16.526   933  3034 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '75 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 75 Failed to set address (No such device)'
,08-29 07:30:16.527   933  3034 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 07:30:16.529   933  3034 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 07:30:16.535   933  3034 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 07:30:16.542   933   948 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=196547 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=8 mControllerEnergyUsed=30 }
,08-29 07:30:16.842  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:30:16.842  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:16.842  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:16.842  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:30:16.842  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:30:16.842  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:16.842  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:16.842  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:30:16.847  5616  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:30:16.852  5616  5662 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 07:30:16.852  5616  5662 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 07:30:16.855  5616  5662 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f26fa07 Bundle[{}]
,08-29 07:30:16.856  5616  5662 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 07:30:16.857  5616  5662 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 07:30:16.858  5616  5662 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 07:30:16.858  5616  5662 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 07:30:16.859  5616  5662 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 07:30:16.860  5616  5662 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 07:30:16.864  5616  5662 I System.out: Running OutgoingSocketThread
,08-29 07:30:16.868  5616  5924 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 151)
,08-29 07:30:16.869  5616  5924 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45898
,08-29 07:30:16.869  5616  5924 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 07:30:17.869  5616  5662 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 152)
08-29 07:30:17.869  5616  5662 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 152)
,08-29 07:30:17.874  5616  5662 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 157)
08-29 07:30:17.876  5616  5662 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 07:30:17.877  5616  5662 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,08-29 07:30:17.884  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 07:30:17.884  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d738de added. We now have 2 listener(s)
,08-29 07:30:17.887  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:30:17.887  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:30:17.887  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 07:30:17.887  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:30:17.887  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ab0abf added. We now have 9 listener(s)
08-29 07:30:17.887  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:30:17.888  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 07:30:17.891  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:30:17.895  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:30:17.895  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:17.895  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:17.895  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:30:17.895  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:30:17.895  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:17.895  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:17.895  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:30:17.898  5616  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:30:17.898  5616  5662 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:30:17.898  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:30:17.898  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5864d5 added. We now have 3 listener(s)
08-29 07:30:17.900  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:17.900  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:30:17.900  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 07:30:17.900  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:30:17.901  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:30:17.901  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a04ea added. We now have 10 listener(s)
08-29 07:30:17.901  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:30:17.901  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:30:17.901  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 07:30:17.901  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:30:17.901  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:30:17.901  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:17.901  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:17.901  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:30:17.901  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 07:30:17.901  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d738de removed from the list
08-29 07:30:17.902  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:17.902  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ab0abf removed from the list
08-29 07:30:17.902  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 07:30:17.902  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:30:17.903  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:17.903  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:30:17.905  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 07:30:17.905  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:30:17.906  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:17.906  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ab0abf not in the list
08-29 07:30:17.906  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:17.906  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:30:17.907  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:30:17.907  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:30:17.907  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:17.908  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a04ea removed from the list
08-29 07:30:17.908  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 07:30:17.908  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:17.908  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:30:17.908  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:30:17.908  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5864d5 removed from the list
08-29 07:30:17.909  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:30:17.909  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48f93db added. We now have 2 listener(s)
08-29 07:30:17.911  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:30:17.911  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:30:17.911  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:30:17.911  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 07:30:17.911  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@690de78 added. We now have 9 listener(s)
08-29 07:30:17.911  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:30:17.912  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 07:30:17.917  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:30:17.920  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:30:17.920  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:17.920  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:17.920  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:30:17.920  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:30:17.920  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:17.920  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:17.920  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:30:17.922  5616  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:30:17.922  5616  5662 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 07:30:17.922  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:30:17.922  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b85b6 added. We now have 3 listener(s)
08-29 07:30:17.923  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:17.923  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:30:17.924  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:30:17.924  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:30:17.924  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:30:17.924  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6992b7 added. We now have 10 listener(s)
08-29 07:30:17.924  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:30:17.924  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:30:17.924  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:30:17.924  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:30:17.924  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:17.924  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:30:17.924  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:30:17.928  5616  5662 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 07:30:17.928  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 07:30:17.931  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 07:30:17.932  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 07:30:17.932  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 07:30:17.934  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 07:30:17.934  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:30:17.934  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 07:30:17.936  5616  5662 D BluetoothAdapter: STATE_ON
08-29 07:30:17.938  5867  5877 D BtGatt.GattService: registerClient() - UUID=96112405-cfda-4f8a-97cf-3617cb5e5a12
08-29 07:30:17.939  5867  5883 D BtGatt.GattService: onClientRegistered() - UUID=96112405-cfda-4f8a-97cf-3617cb5e5a12, clientIf=5
,08-29 07:30:17.940  5616  5626 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 07:30:17.941  5867  5895 D BtGatt.GattService: start scan with filters
,08-29 07:30:17.944  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 07:30:17.944  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 07:30:17.944  5867  5886 D BtGatt.ScanManager: handling starting scan
08-29 07:30:17.945  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:30:17.945  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 07:30:17.946  5867  5886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f892e7a
08-29 07:30:17.947  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 07:30:17.947  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 07:30:17.947  5616  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:30:17.948  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 07:30:17.952  5867  5883 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:30:17.952  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:30:17.953  5616  5662 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 07:30:17.953  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 07:30:17.953  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 07:30:17.953  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:17.953  5867  5886 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 07:30:17.953  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:30:17.953  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 07:30:17.953  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:30:17.953  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:30:17.953  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 07:30:17.953  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:30:17.953  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 07:30:17.954  5616  5662 D BluetoothAdapter: STATE_ON
,08-29 07:30:17.955  5867  5877 D BtGatt.GattService: stopScan() - queue size =1
,08-29 07:30:17.957  5867  5895 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 07:30:17.957  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:30:17.958  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:30:17.958  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:30:17.958  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:30:17.958  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 07:30:17.960  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 07:30:17.960  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 07:30:17.960  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:30:17.960  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 07:30:17.960  5867  5883 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:30:17.960  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:30:17.961  5867  5886 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:30:17.961  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 07:30:17.961  5867  5886 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:30:17.962  5616  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:30:17.962  5616  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:30:17.962  5616  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:30:17.963  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:30:17.963  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:30:17.963  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:30:17.964  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:30:17.964  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:30:17.964  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:30:17.964  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:30:17.964  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48f93db removed from the list
08-29 07:30:17.964  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:17.964  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@690de78 removed from the list
08-29 07:30:17.964  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:30:17.964  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:30:17.964  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:17.964  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:30:17.966  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:30:17.966  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:30:17.966  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:17.966  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@690de78 not in the list
08-29 07:30:17.966  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:17.966  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:30:17.967  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:30:17.967  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 07:30:17.967  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:17.967  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6992b7 removed from the list
08-29 07:30:17.967  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:30:17.967  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:17.967  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:30:17.968  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:30:17.968  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b85b6 removed from the list
08-29 07:30:17.968  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:30:17.968  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7aa353 added. We now have 2 listener(s)
08-29 07:30:17.970  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:30:17.970  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:30:17.970  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:30:17.970  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:30:17.970  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2d0490 added. We now have 9 listener(s)
,08-29 07:30:17.970  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:30:17.970  5867  5883 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:30:17.970  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:30:17.971  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 07:30:17.974  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:30:17.976  5867  5883 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:30:17.976  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:30:17.978  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:30:17.978  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:17.978  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:17.978  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:30:17.978  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:30:17.978  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:17.978  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:17.978  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:30:17.980  5616  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:30:17.980  5616  5662 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:30:17.980  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:30:17.980  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@331958e added. We now have 3 listener(s)
08-29 07:30:17.981  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:30:17.981  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:17.981  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:30:17.981  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:30:17.982  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:30:17.982  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18221af added. We now have 10 listener(s)
08-29 07:30:17.982  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:30:17.982  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:30:17.982  5867  5883 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:30:17.982  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:30:17.982  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:17.983  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:30:17.983  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:30:17.983  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:30:17.983  5867  5886 D BtGatt.ScanManager: stopping BLe Batch
08-29 07:30:17.983  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:30:17.983  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 07:30:17.988  5867  5883 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:30:17.988  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:30:17.988  5867  5886 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 07:30:17.989  5616  5662 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 07:30:17.989  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 07:30:17.992  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 07:30:17.993  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 07:30:17.993  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 07:30:17.994  5867  5883 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:30:17.994  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:30:17.996  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 07:30:17.996  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:30:17.996  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:30:17.997  5616  5662 D BluetoothAdapter: STATE_ON
08-29 07:30:17.998  5867  5904 D BtGatt.GattService: registerClient() - UUID=9ad49756-6d67-41c5-9eb0-29e1cf95cb1f
08-29 07:30:17.999  5867  5883 D BtGatt.GattService: onClientRegistered() - UUID=9ad49756-6d67-41c5-9eb0-29e1cf95cb1f, clientIf=5
,08-29 07:30:17.999  5616  5627 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 07:30:17.999  5867  5877 D BtGatt.GattService: start scan with filters
08-29 07:30:18.001  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 07:30:18.001  5867  5886 D BtGatt.ScanManager: handling starting scan
08-29 07:30:18.001  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:30:18.001  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:30:18.001  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 07:30:18.003  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:30:18.003  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 07:30:18.004  5616  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:30:18.004  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 07:30:18.006  5867  5883 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:30:18.006  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:30:18.007  5867  5886 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 07:30:18.007  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 07:30:18.007  5616  5662 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 07:30:18.007  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:30:18.007  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:30:18.007  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:30:18.007  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:30:18.007  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:18.007  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:30:18.007  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:30:18.007  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7aa353 removed from the list
08-29 07:30:18.007  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:18.007  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2d0490 removed from the list
08-29 07:30:18.007  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:30:18.008  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:30:18.008  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:18.008  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 07:30:18.008  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:30:18.008  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:30:18.009  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:30:18.009  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:30:18.009  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:18.009  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2d0490 not in the list
08-29 07:30:18.009  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:30:18.009  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:30:18.009  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:30:18.009  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:30:18.009  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 07:30:18.010  5616  5662 D BluetoothAdapter: STATE_ON
08-29 07:30:18.010  5867  5877 D BtGatt.GattService: stopScan() - queue size =1
08-29 07:30:18.011  5867  5895 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 07:30:18.011  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:30:18.011  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:30:18.011  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 07:30:18.011  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:30:18.011  5867  5883 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:30:18.011  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:30:18.011  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:30:18.011  5867  5886 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:30:18.011  5867  5886 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:30:18.012  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:30:18.012  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:30:18.012  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:30:18.012  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 07:30:18.013  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:30:18.014  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:30:18.014  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:30:18.014  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:18.014  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18221af removed from the list
,08-29 07:30:18.014  5616  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:30:18.014  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:30:18.014  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:18.014  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:30:18.014  5616  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:30:18.014  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:30:18.014  5616  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:30:18.014  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@331958e removed from the list
08-29 07:30:18.015  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:30:18.015  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad929cb added. We now have 2 listener(s)
,08-29 07:30:18.016  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:30:18.016  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:30:18.016  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:30:18.016  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:30:18.016  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@734d5a8 added. We now have 9 listener(s)
,08-29 07:30:18.016  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:30:18.020  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 07:30:18.020  5867  5883 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:30:18.020  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:30:18.022  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:30:18.025  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:30:18.025  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:18.025  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:18.025  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:30:18.025  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:30:18.025  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:18.025  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:18.025  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:30:18.025  5867  5883 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:30:18.025  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:30:18.027  5616  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:30:18.027  5616  5662 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:30:18.027  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:30:18.027  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55ec866 added. We now have 3 listener(s)
08-29 07:30:18.028  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:18.028  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:30:18.028  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:30:18.028  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 07:30:18.029  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:30:18.029  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4e97a7 added. We now have 10 listener(s)
08-29 07:30:18.029  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:30:18.029  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:30:18.029  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:30:18.029  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:30:18.029  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:30:18.029  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:30:18.029  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:30:18.031  5867  5883 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:30:18.031  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:30:18.031  5867  5886 D BtGatt.ScanManager: stopping BLe Batch
08-29 07:30:18.031  5616  5662 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 07:30:18.031  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 07:30:18.034  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 07:30:18.035  5867  5883 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:30:18.035  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:30:18.035  5867  5886 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 07:30:18.035  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 07:30:18.035  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 07:30:18.039  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 07:30:18.039  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:30:18.039  5616  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:30:18.039  5867  5883 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:30:18.039  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:30:18.040  5616  5662 D BluetoothAdapter: STATE_ON
,08-29 07:30:18.042  5867  5878 D BtGatt.GattService: registerClient() - UUID=69f1a12d-910a-4ce2-a93d-4e71c5fdaf4b
,08-29 07:30:18.042  5867  5883 D BtGatt.GattService: onClientRegistered() - UUID=69f1a12d-910a-4ce2-a93d-4e71c5fdaf4b, clientIf=5
,08-29 07:30:18.042  5616  5626 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 07:30:18.043  5867  5877 D BtGatt.GattService: start scan with filters
,08-29 07:30:18.044  5867  5886 D BtGatt.ScanManager: handling starting scan
08-29 07:30:18.044  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 07:30:18.045  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 07:30:18.045  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:30:18.045  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 07:30:18.047  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:30:18.047  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:30:18.047  5616  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:30:18.048  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 07:30:18.049  5867  5883 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:30:18.049  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:30:18.050  5867  5886 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 07:30:18.053  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 07:30:18.053  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:30:18.053  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:30:18.053  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:30:18.053  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:18.053  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:30:18.053  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:30:18.054  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad929cb removed from the list
08-29 07:30:18.054  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:18.054  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@734d5a8 removed from the list
08-29 07:30:18.054  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:30:18.054  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:30:18.054  5867  5883 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:30:18.054  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:30:18.054  5867  5886 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:30:18.054  5867  5886 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:30:18.054  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:18.055  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 07:30:18.055  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:30:18.055  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:30:18.055  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:30:18.055  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:30:18.056  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:18.056  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@734d5a8 not in the list
08-29 07:30:18.056  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:30:18.056  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:30:18.056  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:30:18.056  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:30:18.056  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 07:30:18.056  5616  5662 D BluetoothAdapter: STATE_ON
08-29 07:30:18.057  5867  5895 D BtGatt.GattService: stopScan() - queue size =1
08-29 07:30:18.057  5867  5878 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 07:30:18.058  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:30:18.058  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 07:30:18.058  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:30:18.058  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:30:18.058  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:30:18.059  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:30:18.059  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:30:18.059  5616  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:30:18.059  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 07:30:18.061  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:30:18.062  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:30:18.062  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:30:18.062  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:18.062  5616  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:30:18.062  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4e97a7 removed from the list
08-29 07:30:18.062  5616  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:30:18.062  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:30:18.062  5616  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:30:18.062  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:30:18.062  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:30:18.062  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:30:18.062  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55ec866 removed from the list
08-29 07:30:18.063  5867  5883 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:30:18.063  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:30:18.063  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:30:18.063  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c30743 added. We now have 2 listener(s)
08-29 07:30:18.064  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:30:18.064  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:30:18.064  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:30:18.064  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:30:18.064  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b12b1c0 added. We now have 9 listener(s)
08-29 07:30:18.064  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:30:18.065  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 07:30:18.067  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:30:18.068  5867  5883 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:30:18.068  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:30:18.070  5616  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:30:18.070  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:30:18.070  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:30:18.070  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:30:18.070  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:30:18.070  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:30:18.070  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:30:18.070  5616  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:30:18.072  5616  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:30:18.072  5616  5662 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 07:30:18.072  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:30:18.072  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f47e3e added. We now have 3 listener(s)
08-29 07:30:18.073  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:30:18.073  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:30:18.073  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:30:18.074  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:30:18.074  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84d49f added. We now have 10 listener(s)
08-29 07:30:18.074  5616  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:30:18.074  5867  5883 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:30:18.074  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:30:18.074  5616  5662 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:30:18.074  5867  5886 D BtGatt.ScanManager: stopping BLe Batch
08-29 07:30:18.074  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 07:30:18.074  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:18.074  5616  5662 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:30:18.074  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:30:18.074  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:18.074  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:30:18.074  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:30:18.074  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c30743 removed from the list
08-29 07:30:18.074  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:18.074  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b12b1c0 removed from the list
08-29 07:30:18.075  5616  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:30:18.075  5616  5662 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:30:18.076  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:30:18.076  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:18.076  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:30:18.077  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 07:30:18.077  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:30:18.077  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:18.077  5616  5662 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b12b1c0 not in the list
08-29 07:30:18.077  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:30:18.077  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:30:18.078  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:30:18.078  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:30:18.078  5616  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:30:18.078  5616  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84d49f removed from the list
08-29 07:30:18.078  5616  5662 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:30:18.078  5616  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:30:18.079  5616  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:30:18.079  5616  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:30:18.079  5867  5883 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:30:18.079  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:30:18.079  5616  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f47e3e removed from the list
08-29 07:30:18.079  5867  5886 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 07:30:18.079  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-29 07:30:18.079  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 07:30:18.080  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 07:30:18.080  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:30:18.080  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 07:30:18.080  5616  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 07:30:18.084  5867  5883 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:30:18.084  5867  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:30:18.084  5616  5925 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: My test thread name)
08-29 07:30:18.084  5616  5925 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: My test thread name)
,08-29 07:30:18.084  5616  5925 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 07:30:18.086  5616  5926 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name)
,08-29 07:30:18.086  5616  5926 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: My test thread name)
08-29 07:30:18.086  5616  5926 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 07:30:18.088  5616  5662 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-29 07:30:18.088  5616  5662 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 07:30:18.088  5616  5662 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 07:30:18.088  5616  5662 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 07:30:18.088  5616  5662 D com.test.thalitest.ThaliTestRunner: Total duration: 23589 ms
08-29 07:30:18.090  5616  5662 I jxcore-log: *Native tests were executed*
08-29 07:30:18.090  5616  5662 I jxcore-log: 
08-29 07:30:18.090  5616  5662 I jxcore-log: Total number of executed tests:  80
08-29 07:30:18.090  5616  5662 I jxcore-log: 
,08-29 07:30:18.090  5616  5662 I jxcore-log: Number of passed tests:  80
08-29 07:30:18.090  5616  5662 I jxcore-log: 
08-29 07:30:18.090  5616  5662 I jxcore-log: Number of failed tests:  0
08-29 07:30:18.090  5616  5662 I jxcore-log: 
08-29 07:30:18.090  5616  5662 I jxcore-log: Number of ignored tests:  0
08-29 07:30:18.090  5616  5662 I jxcore-log: 
08-29 07:30:18.091  5616  5662 I jxcore-log: Total duration:  23589
08-29 07:30:18.091  5616  5662 I jxcore-log: 
08-29 07:30:18.091  5616  5662 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 07:30:18.091  5616  5662 I jxcore-log: 
08-29 07:30:18.093  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 07:30:18.093  5616  5662 I jxcore-log: 
08-29 07:30:18.096  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 07:30:18.096  5616  5662 I jxcore-log: 
08-29 07:30:18.097  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 07:30:18.097  5616  5662 I jxcore-log: 
08-29 07:30:18.098  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 07:30:18.098  5616  5662 I jxcore-log: 
08-29 07:30:18.098  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 07:30:18.098  5616  5662 I jxcore-log: 
,08-29 07:30:18.100  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 07:30:18.100  5616  5662 I jxcore-log: 
08-29 07:30:18.100  5616  5616 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 07:30:18.102  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 07:30:18.102  5616  5662 I jxcore-log: 
08-29 07:30:18.103  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 07:30:18.103  5616  5662 I jxcore-log: 
08-29 07:30:18.104  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 07:30:18.104  5616  5662 I jxcore-log: 
08-29 07:30:18.104  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:30:18.104  5616  5662 I jxcore-log: 
08-29 07:30:18.106  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:30:18.106  5616  5662 I jxcore-log: 
08-29 07:30:18.107  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 07:30:18.107  5616  5662 I jxcore-log: 
08-29 07:30:18.108  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 07:30:18.108  5616  5662 I jxcore-log: 
08-29 07:30:18.109  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 07:30:18.109  5616  5662 I jxcore-log: 
08-29 07:30:18.109  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:30:18.109  5616  5662 I jxcore-log: 
08-29 07:30:18.110  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:30:18.110  5616  5662 I jxcore-log: 
08-29 07:30:18.111  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 07:30:18.111  5616  5662 I jxcore-log: 
08-29 07:30:18.111  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 07:30:18.111  5616  5662 I jxcore-log: 
08-29 07:30:18.112  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:30:18.112  5616  5662 I jxcore-log: 
08-29 07:30:18.113  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:30:18.113  5616  5662 I jxcore-log: 
08-29 07:30:18.113  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 07:30:18.113  5616  5662 I jxcore-log: 
08-29 07:30:18.114  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 07:30:18.114  5616  5662 I jxcore-log: 
08-29 07:30:18.114  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:30:18.114  5616  5662 I jxcore-log: 
08-29 07:30:18.115  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:30:18.115  5616  5662 I jxcore-log: 
08-29 07:30:18.116  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:30:18.116  5616  5662 I jxcore-log: 
08-29 07:30:18.117  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:30:18.117  5616  5662 I jxcore-log: 
08-29 07:30:18.117  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:30:18.117  5616  5662 I jxcore-log: 
08-29 07:30:18.118  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:30:18.118  5616  5662 I jxcore-log: 
08-29 07:30:18.119  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:30:18.119  5616  5662 I jxcore-log: 
,08-29 07:30:18.463  5616  5616 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 07:30:18.466  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 07:30:18.466  5616  5662 I jxcore-log: 
,08-29 07:30:18.514  5616  5616 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 07:30:18.518  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 07:30:18.518  5616  5662 I jxcore-log: 
,08-29 07:30:18.541  5927  5927 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 07:30:18.547  5927  5927 D AndroidRuntime: CheckJNI is OFF
,08-29 07:30:18.562  5616  5616 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 07:30:18.565  5616  5662 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 07:30:18.565  5616  5662 I jxcore-log: 
,08-29 07:30:18.573  5927  5927 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 07:30:18.603  5927  5927 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 07:30:18.619  5927  5927 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 07:30:18.626   933   946 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,08-29 07:30:18.627   933   946 I ActivityManager: Killing 5616:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,08-29 07:30:18.707   933   944 D GraphicsStats: Buffer count: 2
,08-29 07:30:18.707   933  3185 I WindowState: WIN DEATH: Window{dbc48e4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 07:30:18.708   933  3036 D WifiService: Client connection lost with reason: 4
,08-29 07:30:18.760   933   946 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-29 07:30:18.761   933   946 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-29 07:30:18.761   933   956 I art     : Starting a blocking GC Explicit
08-29 07:30:18.762   933   946 E ActivityManager: Failure starting process com.test.thalitest
08-29 07:30:18.762   933   946 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 07:30:18.762   933   946 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:30:18.762   933   946 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:30:18.762   933   946 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 07:30:18.762   933   946 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 07:30:18.762   933   946 I ActivityManager:   Force finishing activity ActivityRecord{82b2e69 u0 com.test.thalitest/.MainActivity t4}
,08-29 07:30:18.770   933   944 W ActivityManager: Spurious death for ProcessRecord{f339120 0:com.test.thalitest/u0a77}, curProc for 5616: null
,08-29 07:30:18.837   933   956 I art     : Explicit concurrent mark sweep GC freed 25375(1559KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 1.569ms total 76.041ms
,08-29 07:30:18.859   933   956 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 07:30:18.862  5927  5927 I art     : System.exit called, status: 0
,08-29 07:30:18.862  5927  5927 I AndroidRuntime: VM exiting with result code 0.
,08-29 07:30:18.877   933   956 I ActivityManager: Start proc 5937:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-29 07:30:18.877   933   956 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,08-29 07:30:18.888   933   946 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 07:30:18.892  5867  5867 D BluetoothMapAppObserver: onReceive
,08-29 07:30:18.892  5867  5867 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-29 07:30:18.900  3541  3967 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 07:30:18.904   933  3003 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 07:30:18.908  3464  3464 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 07:30:18.922  3464  5950 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 07:30:18.925  3464  5950 I Decoder : createOrResetDecoder
,08-29 07:30:18.936  5426  5952 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 07:30:18.962  3616  3616 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 07:30:18.953    27    27 W kworker/2:1: type=1400 audit(0.0:73): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 07:30:18.963    27    27 W kworker/2:1: type=1400 audit(0.0:74): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 07:30:18.983  3692  3692 I ConfigService: onCreate
,08-29 07:30:18.983    27    27 W kworker/2:1: type=1400 audit(0.0:75): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 07:30:18.991  3692  5955 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-29 07:30:18.993  5426  5952 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-29 07:30:18.994  3645  3778 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-29 07:30:18.996   933   945 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-29 07:30:18.996   933   933 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 07:30:18.997   933   945 E PackageManager: Failed to write settings, restoring backup
08-29 07:30:18.997   933   945 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 07:30:18.997   933   945 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 07:30:18.997   933   945 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 07:30:18.997   933   945 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 07:30:18.997   933   945 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 07:30:18.997   933   945 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:30:18.997   933   945 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:30:18.997   933   945 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 07:30:18.999   933   946 E DropBoxManagerService: Can't write: system_server_wtf
08-29 07:30:18.999   933   946 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 07:30:18.999   933   946 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 07:30:18.999   933   946 E DropBoxManagerService: 	... 13 more
08-29 07:30:19.002  3464  5950 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 07:30:19.008   933  3469 I ActivityManager: Start proc 5956:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-29 07:30:19.009  3645  3778 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 07:30:19.009  3645  3778 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3645
08-29 07:30:19.009  3645  3778 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 07:30:19.009  3645  3778 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 07:30:19.009  3645  3778 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 07:30:19.009  3645  3778 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 07:30:19.009  3645  3778 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 07:30:19.009  3645  3778 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 07:30:19.009  3645  3778 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 07:30:19.009  3645  3778 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 07:30:19.009  3645  3778 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 07:30:19.009  3645  3778 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 07:30:19.009  3645  3778 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:30:19.009  3645  3778 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 07:30:18.994  5426  5952 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 07:30:18.994  5426  5952 E AndroidRuntime: Process: android.process.acore, PID: 5426
08-29 07:30:18.994  5426  5952 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:30:18.994  5426  5952 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 07:30:19.018   933   943 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 07:30:19.020  3692  3692 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-29 07:30:19.021  3692  3692 D AndroidRuntime: Shutting down VM
,08-29 07:30:19.022  3692  3692 E AndroidRuntime: FATAL EXCEPTION: main
08-29 07:30:19.022  3692  3692 E AndroidRuntime: Process: com.google.process.gapps, PID: 3692
08-29 07:30:19.022  3692  3692 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 07:30:19.022  3692  3692 E AndroidRuntime: 	... 8 more
,08-29 07:30:19.024   933  5966 E DropBoxManagerService: Can't write: system_app_crash
08-29 07:30:19.024   933  5966 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-29 07:30:19.024   933  5966 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 07:30:19.024   933  5966 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 07:30:19.024   933  5966 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 07:30:19.024   933  5966 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 07:30:19.024   933  5966 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 07:30:19.024   933  5966 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 07:30:19.024   933  5966 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 07:30:19.024   933  5966 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 07:30:19.024   933  5966 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 07:30:19.024   933  5966 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 07:30:19.024   933  5966 E DropBoxManagerService: 	... 5 more
,08-29 07:30:19.029  3645  3778 I Process : Sending signal. PID: 3645 SIG: 9
,08-29 07:30:19.029   933  5970 E DropBoxManagerService: Can't write: system_app_crash
08-29 07:30:19.029   933  5970 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-29 07:30:19.029   933  5970 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 07:30:19.029   933  5970 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 07:30:19.029   933  5970 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 07:30:19.029   933  5970 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 07:30:19.029   933  5970 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 07:30:19.029   933  5970 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 07:30:19.029   933  5970 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 07:30:19.029   933  5970 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 07:30:19.029   933  5970 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 07:30:19.029   933  5970 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 07:30:19.029   933  5970 E DropBoxManagerService: 	... 5 more
,08-29 07:30:19.033   933  5971 E DropBoxManagerService: Can't write: system_app_crash
08-29 07:30:19.033   933  5971 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
08-29 07:30:19.033   933  5971 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 07:30:19.033   933  5971 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 07:30:19.033   933  5971 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 07:30:19.033   933  5971 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 07:30:19.033   933  5971 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 07:30:19.033   933  5971 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 07:30:19.033   933  5971 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 07:30:19.033   933  5971 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 07:30:19.033   933  5971 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 07:30:19.033   933  5971 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 07:30:19.033   933  5971 E DropBoxManagerService: 	... 5 more
08-29 07:30:19.033  3692  3692 I Process : Sending signal. PID: 3692 SIG: 9
,08-29 07:30:19.055  5426  5952 I Process : Sending signal. PID: 5426 SIG: 9

```
