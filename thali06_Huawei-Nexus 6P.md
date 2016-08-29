#### Test 79763830f89c62d_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-29 08:21:57.975   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:21:58.459  5685  5685 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 08:21:58.465  5685  5685 D AndroidRuntime: CheckJNI is OFF
08-29 08:21:58.493  5685  5685 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 08:21:58.529  5685  5685 I Radio-JNI: register_android_hardware_Radio DONE
08-29 08:21:58.545  5685  5685 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 08:21:58.549   927  3668 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 08:21:58.593   927  3668 I ActivityManager: Start proc 5694:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-29 08:21:58.597  5685  5685 D AndroidRuntime: Shutting down VM
08-29 08:21:58.680  5694  5694 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-29 08:21:58.713  5694  5694 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 08:21:58.735  5694  5694 I LibraryLoader: Time to load native libraries: 17 ms (timestamps 6223-6240)
08-29 08:21:58.735  5694  5694 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 08:21:58.753  5694  5694 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9e128ac}
08-29 08:21:58.754  5694  5694 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 08:21:58.754  5694  5694 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 08:21:58.759  5694  5694 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 08:21:58.760  5694  5694 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 08:21:58.793  5694  5694 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 08:21:58.809  5694  5694 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 08:21:58.809  5694  5694 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 08:21:58.809  5694  5694 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 08:21:58.809  5694  5694 I Adreno  : Build Date                       : 10/21/15
08-29 08:21:58.809  5694  5694 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 08:21:58.809  5694  5694 I Adreno  : Local Branch                     : 
08-29 08:21:58.809  5694  5694 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 08:21:58.809  5694  5694 I Adreno  : Remote Branch                    : NONE
08-29 08:21:58.809  5694  5694 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 08:21:58.857   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8013e60:true
,08-29 08:21:58.895  5694  5694 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 08:21:58.905  5694  5694 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-29 08:21:58.931  5694  5731 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 08:21:58.937  5694  5718 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 08:21:58.963  5694  5731 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 08:21:58.976   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:21:59.041   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +410ms (total +472ms)
,08-29 08:21:59.063  5694  5694 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5694
,08-29 08:21:59.146  5694  5694 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 08:21:59.251  5694  5734 D jxcore_app_log: JniHelper::setJavaVM(0xf53fc000), pthread_self() = -582219472
,08-29 08:21:59.254  5694  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 08:21:59.254  5694  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 08:21:59.254  5694  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 08:21:59.254  5694  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 08:21:59.254  5694  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 08:21:59.255  5694  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4114222 added. We now have 1 listener(s)
,08-29 08:21:59.257  5694  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,08-29 08:21:59.257  5694  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 08:21:59.257  5694  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:21:59.258  5694  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 08:21:59.259  5694  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e62e1e9 added. We now have 1 listener(s)
,08-29 08:21:59.260  5694  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:21:59.262   927  3074 D WifiService: New client listening to asynchronous messages
08-29 08:21:59.262  5694  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:21:59.262  5694  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 08:21:59.262  5694  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-29 08:21:59.262  5694  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 08:21:59.262  5694  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 08:21:59.264  5694  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:21:59.264  5694  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-29 08:21:59.267  5694  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-29 08:21:59.267  5694  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:21:59.267  5694  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:21:59.267  5694  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:21:59.267  5694  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:21:59.267  5694  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:21:59.267  5694  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:21:59.267  5694  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:21:59.267  5694  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:21:59.267  5694  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 08:21:59.267  5694  5734 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:21:59.268  5694  5734 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 08:21:59.270  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:21:59.272  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:21:59.280  5694  5694 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 08:21:59.516  5694  5740 W jxcore-log: Initializing JXcore engine
08-29 08:21:59.516  5694  5740 W jxcore-log: JXcore engine is ready
,08-29 08:21:59.524  5740  5740 W Thread-61: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1296 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-29 08:21:59.524  5740  5740 W Thread-61: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[15450]" dev="sockfs" ino=15450 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-29 08:21:59.524  5740  5740 W Thread-61: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5901 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 08:21:59.524  5740  5740 W Thread-61: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[32579]" dev="sockfs" ino=32579 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 08:21:59.548  5694  5740 W jxcore-log: Starting JXcore engine
,08-29 08:21:59.601  5694  5740 W jxcore-log: Platform android
08-29 08:21:59.601  5694  5740 W jxcore-log: 
,08-29 08:21:59.601  5694  5740 W jxcore-log: Process ARCH arm
08-29 08:21:59.601  5694  5740 W jxcore-log: 
,08-29 08:21:59.695  5694  5740 I jxcore-log: JXcore Cordova bridge is ready!
08-29 08:21:59.695  5694  5740 I jxcore-log: 
,08-29 08:21:59.696  5694  5740 W jxcore-log: JXcore engine is started
,08-29 08:21:59.700  5694  5734 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 08:21:59.703  5694  5694 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 08:21:59.976   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:22:00.365   927  5357 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167870, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 08:22:00.977   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:22:01.978   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:22:02.978   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 08:22:06.254  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 08:22:06.254  5694  5740 I jxcore-log: 
,08-29 08:22:06.256  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 08:22:06.256  5694  5740 I jxcore-log: 
,08-29 08:22:06.259  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:22:06.259  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:06.259  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:06.259  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:06.259  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:06.259  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:22:06.259  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:22:06.259  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:22:06.260  5694  5740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:22:06.261  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 08:22:06.261  5694  5740 I jxcore-log: 
,08-29 08:22:06.262  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 08:22:06.262  5694  5740 I jxcore-log: 
,08-29 08:22:06.616  5694  5740 D executeNativeTests: Running unit tests
,08-29 08:22:06.656  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 08:22:06.656  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 added. We now have 2 listener(s)
08-29 08:22:06.657  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 08:22:06.657  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:22:06.657  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:22:06.657  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:06.657  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 added. We now have 2 listener(s)
,08-29 08:22:06.657  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:22:06.657  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:22:06.659  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:22:06.662  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:22:06.662  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:06.662  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:06.662  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:06.662  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:06.662  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:22:06.662  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:22:06.662  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:22:06.665  5694  5740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:22:06.665  5694  5740 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 08:22:06.667  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 08:22:06.668  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 08:22:06.668  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 08:22:06.669  5694  5740 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 08:22:06.669  5694  5740 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 08:22:06.669  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 08:22:06.669  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:22:06.669  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:22:06.669  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.670  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.670  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:22:06.670  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.670  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.670  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:22:06.670  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:22:06.671  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 removed from the list
,08-29 08:22:06.671  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.671  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 removed from the list
08-29 08:22:06.672  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:06.672  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.672  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:22:06.673  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.673  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.674  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.674  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.674  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.674  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.675  5694  5740 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 08:22:06.676  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.676  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.676  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.676  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:22:06.676  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.676  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.676  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.676  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.676  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.678  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:06.678  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.678  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.678  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:22:06.678  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.678  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.679  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.679  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.679  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.679  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.682  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 08:22:06.682  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-29 08:22:06.682  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 08:22:06.682  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 08:22:06.682  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 08:22:06.682  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 08:22:06.682  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 08:22:06.682  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-29 08:22:06.682  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 08:22:06.682  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 08:22:06.682  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 08:22:06.682  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 08:22:06.682  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 08:22:06.682  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 08:22:06.683  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.683  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.683  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.683  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.683  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.683  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.683  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.683  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.683  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.683  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.683  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.683  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.683  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.683  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.684  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:22:06.684  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.684  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.684  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.684  5694  5740 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 08:22:06.685  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:22:06.687  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:22:06.687  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:06.687  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:06.687  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:06.687  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:06.687  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:22:06.687  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:22:06.687  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:22:06.688  5694  5740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:22:06.688  5694  5740 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 08:22:06.688  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:22:06.688  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:22:06.688  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:22:06.688  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:22:06.688  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:22:06.690  5694  5740 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 08:22:06.690  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 08:22:06.691  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:06.693  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 08:22:06.694  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:06.695  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 08:22:06.695  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:22:06.696  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 08:22:06.697  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 08:22:06.697  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 08:22:06.697  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 08:22:06.698  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 08:22:06.698  5694  5740 D BluetoothAdapter: STATE_ON
,08-29 08:22:06.700  4494  4511 D BtGatt.GattService: registerClient() - UUID=812779cc-cd51-4178-9889-e3e5b6a77285
,08-29 08:22:06.701  4494  4570 D BtGatt.GattService: onClientRegistered() - UUID=812779cc-cd51-4178-9889-e3e5b6a77285, clientIf=5
,08-29 08:22:06.701  5694  5704 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 08:22:06.703  4494  4767 D BtGatt.GattService: start scan with filters
,08-29 08:22:06.706  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 08:22:06.706  4494  4579 D BtGatt.ScanManager: handling starting scan
08-29 08:22:06.706  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 08:22:06.706  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:22:06.706  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:22:06.708  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:22:06.708  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 08:22:06.708  5694  5694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 08:22:06.708  4494  4579 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
,08-29 08:22:06.708  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 08:22:06.710  5694  5740 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 08:22:06.711  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.711  5694  5740 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 08:22:06.711  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.711  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 08:22:06.711  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.711  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:22:06.711  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:22:06.711  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 08:22:06.711  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:22:06.711  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:22:06.712  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:22:06.712  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 08:22:06.712  5694  5740 D BluetoothAdapter: STATE_ON
08-29 08:22:06.712  4494  4767 D BtGatt.GattService: stopScan() - queue size =1
08-29 08:22:06.713  4494  4734 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:22:06.713  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 08:22:06.713  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:22:06.713  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 08:22:06.713  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 08:22:06.713  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 08:22:06.714  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:22:06.715  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:22:06.715  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:22:06.715  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:22:06.715  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:22:06.715  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.715  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.715  5694  5694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 08:22:06.716  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:22:06.716  4494  4570 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 08:22:06.716  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
,08-29 08:22:06.716  5694  5694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:22:06.716  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.716  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.716  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.716  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.716  5694  5694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:22:06.716  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.716  5694  5740 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 08:22:06.717  4494  4579 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 08:22:06.717  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:22:06.721  4494  4570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-29 08:22:06.721  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.721  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:22:06.721  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:06.721  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:06.721  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:06.721  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:06.721  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:22:06.721  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:22:06.721  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:22:06.721  4494  4579 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:22:06.721  4494  4579 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 08:22:06.722  5694  5740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:22:06.722  5694  5740 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 08:22:06.722  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:22:06.722  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:22:06.722  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:22:06.723  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:22:06.723  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:22:06.725  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:06.726  5694  5740 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 08:22:06.726  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 08:22:06.727  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 08:22:06.727  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:06.728  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 08:22:06.728  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:22:06.729  4494  4570 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 08:22:06.729  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:22:06.730  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 08:22:06.730  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 08:22:06.730  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 08:22:06.730  5694  5740 D BluetoothAdapter: STATE_ON
,08-29 08:22:06.733  4494  4570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 08:22:06.733  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:22:06.735  4494  4734 D BtGatt.GattService: registerClient() - UUID=c8d3f366-6d1a-4960-b3ee-16cd79f02d66
,08-29 08:22:06.735  4494  4570 D BtGatt.GattService: onClientRegistered() - UUID=c8d3f366-6d1a-4960-b3ee-16cd79f02d66, clientIf=5
08-29 08:22:06.736  5694  5704 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 08:22:06.736  4494  4508 D BtGatt.GattService: start scan with filters
,08-29 08:22:06.738  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 08:22:06.738  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 08:22:06.738  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:22:06.738  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:22:06.739  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:22:06.739  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 08:22:06.739  5694  5694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:22:06.739  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 08:22:06.740  4494  4570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 08:22:06.740  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:22:06.740  4494  4579 D BtGatt.ScanManager: stopping BLe Batch
08-29 08:22:06.740  5694  5740 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 08:22:06.741  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.741  5694  5740 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 08:22:06.741  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.741  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 08:22:06.741  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:22:06.741  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:22:06.741  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:22:06.741  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:22:06.741  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:22:06.741  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:22:06.741  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:22:06.741  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 08:22:06.742  5694  5740 D BluetoothAdapter: STATE_ON
08-29 08:22:06.742  4494  4734 D BtGatt.GattService: stopScan() - queue size =0
,08-29 08:22:06.742  4494  4508 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:22:06.742  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:22:06.742  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:22:06.742  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 08:22:06.742  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 08:22:06.742  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 08:22:06.743  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:22:06.743  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:22:06.743  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:22:06.743  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 08:22:06.743  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:22:06.744  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.744  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.744  5694  5694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:22:06.744  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:22:06.744  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.744  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.744  5694  5694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:22:06.744  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.744  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:22:06.744  5694  5694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:22:06.744  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.744  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.744  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.744  4494  4570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 08:22:06.744  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.744  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.744  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 08:22:06.744  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.744  4494  4579 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 08:22:06.745  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.745  5694  5740 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 08:22:06.746  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:22:06.748  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:22:06.748  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:06.748  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:06.748  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:06.748  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:06.748  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:22:06.748  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:22:06.748  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:22:06.748  4494  4570 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 08:22:06.748  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:22:06.749  4494  4579 D BtGatt.ScanManager: handling starting scan
08-29 08:22:06.749  5694  5740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:22:06.750  5694  5740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:22:06.750  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:22:06.750  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:22:06.750  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:22:06.750  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:22:06.750  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:22:06.751  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:06.752  5694  5740 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 08:22:06.752  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 08:22:06.753  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:06.753  4494  4570 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 08:22:06.753  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.753  4494  4579 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 08:22:06.754  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 08:22:06.754  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 08:22:06.754  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:22:06.757  4494  4570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-29 08:22:06.757  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.757  4494  4579 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:22:06.757  4494  4579 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 08:22:06.758  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 08:22:06.758  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 08:22:06.758  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 08:22:06.758  5694  5740 D BluetoothAdapter: STATE_ON
,08-29 08:22:06.759  4494  4508 D BtGatt.GattService: registerClient() - UUID=d68b204d-00e1-4b22-a6b8-cfdfd3e075b2
,08-29 08:22:06.760  4494  4570 D BtGatt.GattService: onClientRegistered() - UUID=d68b204d-00e1-4b22-a6b8-cfdfd3e075b2, clientIf=5
08-29 08:22:06.760  5694  5704 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 08:22:06.760  4494  4511 D BtGatt.GattService: start scan with filters
,08-29 08:22:06.762  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 08:22:06.762  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 08:22:06.762  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:22:06.762  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:22:06.763  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:22:06.763  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 08:22:06.763  5694  5694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:22:06.763  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 08:22:06.764  4494  4570 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 08:22:06.765  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.765  5694  5740 I io.jxcore.node.ConnectionHelper: start: OK
08-29 08:22:06.765  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.765  5694  5740 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 08:22:06.765  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.765  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 08:22:06.765  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.765  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:22:06.765  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:22:06.765  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:22:06.765  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:22:06.765  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:22:06.765  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:22:06.765  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 08:22:06.765  5694  5740 D BluetoothAdapter: STATE_ON
08-29 08:22:06.766  4494  4511 D BtGatt.GattService: stopScan() - queue size =1
08-29 08:22:06.766  4494  4734 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:22:06.766  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 08:22:06.766  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:22:06.766  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 08:22:06.766  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 08:22:06.766  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 08:22:06.768  4494  4570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 08:22:06.768  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:22:06.768  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.768  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:22:06.768  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:22:06.768  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:22:06.768  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:22:06.769  5694  5694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:22:06.769  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.769  5694  5740 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 08:22:06.769  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.769  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.769  5694  5694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:22:06.769  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.769  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:22:06.769  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:22:06.769  5694  5694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:22:06.769  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.769  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.769  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.769  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.769  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.769  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.769  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:22:06.770  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.770  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.770  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.770  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.770  5694  5740 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 08:22:06.770  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.770  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.770  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.770  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.770  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:22:06.770  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.770  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.771  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.771  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.771  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.771  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.771  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.771  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.771  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:22:06.771  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.771  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.771  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.771  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.772  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 08:22:06.772  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.772  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.772  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.772  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:22:06.772  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.772  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.772  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.772  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.772  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.772  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.772  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.772  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.772  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.772  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:22:06.772  4494  4570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 08:22:06.772  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.772  4494  4579 D BtGatt.ScanManager: stopping BLe Batch
08-29 08:22:06.773  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.773  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.773  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.773  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.773  5694  5740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-29 08:22:06.773  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.773  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.773  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.773  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.773  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.773  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.773  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.773  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.773  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.773  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.773  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.773  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.773  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.773  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.774  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.774  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.774  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.774  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.774  5694  5740 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 08:22:06.774  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.774  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.774  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.774  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:22:06.774  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.774  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.774  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.774  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.774  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.774  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.774  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.774  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.774  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.774  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.775  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.775  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.775  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.775  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.775  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 08:22:06.775  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 08:22:06.775  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 08:22:06.775  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:22:06.775  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 08:22:06.775  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 08:22:06.776  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.776  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.776  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.776  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.776  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.776  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.776  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconn,ectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.776  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.776  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.776  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.776  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.776  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.776  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.776  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.776  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.777  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.777  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.777  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.777  5694  5740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:22:06.777  5694  5740 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 08:22:06.777  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 08:22:06.777  4494  4570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 08:22:06.777  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.777  4494  4579 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 08:22:06.778  5694  5740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:22:06.778  5694  5740 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 08:22:06.778  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 08:22:06.778  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 08:22:06.778  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 08:22:06.778  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 08:22:06.778  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 08:22:06.778  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 08:22:06.778  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 08:22:06.778  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 08:22:06.778  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 08:22:06.778  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 08:22:06.778  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 08:22:06.778  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 08:22:06.779  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 08:22:06.779  5694  5740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 08:22:06.779  5694  5740 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 08:22:06.779  5694  5740 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 08:22:06.779  5694  5740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:22:06.779  5694  5740 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 08:22:06.779  5694  5740 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 08:22:06.779  5694  5740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:22:06.780  5694  5740 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 08:22:06.780  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 08:22:06.782  4494  4570 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 08:22:06.782  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.782  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 08:22:06.782  4494  4579 D BtGatt.ScanManager: handling starting scan
08-29 08:22:06.783  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 08:22:06.783  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 08:22:06.783  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 08:22:06.783  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 08:22:06.783  5694  5740 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 08:22:06.783  5694  5740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:22:06.783  5694  5740 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 08:22:06.784  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.784  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.784  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.784  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.784  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.784  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.784  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 08:22:06.784  5694  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
08-29 08:22:06.784  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.784  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.784  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.784  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.784  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.784  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.785  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.785  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.785  5694  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
08-29 08:22:06.786  5694  5741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:22:06.787  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.787  4494  4570 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 08:22:06.787  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.787  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.787  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.787  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.787  4494  4579 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 08:22:06.788  5694  5740 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 08:22:06.788  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.788  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.788  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.788  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.788  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.788  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.788  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.788  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.788  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.788  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.788  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.788  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.788  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.788  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.789  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.789  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.789  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.789  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.789  5694  5740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 08:22:06.789  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.789  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.789  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.789  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.789  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.789  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.789  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.789  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.789  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.790  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.790  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.790  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.790  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.790  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.793  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.793  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.793  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.793  4494  4570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 08:22:06.793  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.793  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.793  4494  4579 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:22:06.793  4494  4579 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 08:22:06.793  5694  5740 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 08:22:06.793  5694  5740 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 08:22:06.793  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 08:22:06.793  5694  5740 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 08:22:06.793  5694  5740 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 08:22:06.793  5694  5740 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 08:22:06.793  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 08:22:06.793  5694  5740 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 08:22:06.793  5694  5740 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 08:22:06.793  5694  5740 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 08:22:06.793  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 08:22:06.793  5694  5740 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 08:22:06.793  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.793  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.793  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.794  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.794  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.794  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.794  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.794  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.794  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.794  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.794  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.794  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.794  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.794  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.794  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.794  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.794  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.794  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.795  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.795  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.795  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.795  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.795  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.795  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.795  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.795  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.795  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.795  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.795  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.795  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.795  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.795  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.795  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.795  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.795  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.795  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.795  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.795  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.795  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.795  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.795  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.795  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.795  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.796  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.796  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.796  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.796  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.796  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.796  5694  5740 I org.thaliproject.p2p.b,tconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.796  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.796  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.797  5694  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 08:22:06.797  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:22:06.797  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 08:22:06.798  5694  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 08:22:06.798  5694  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 08:22:06.798  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 08:22:06.798  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:22:06.798  5694  5694 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 08:22:06.798  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.798  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 08:22:06.798  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 08:22:06.798  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 08:22:06.798  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.798  5694  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 08:22:06.798  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.798  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.798  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:22:06.798  5694  5694 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 08:22:06.799  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:22:06.799  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:22:06.799  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.799  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.799  5694  5743 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:22:06.799  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:22:06.799  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.799  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.799  5694  5694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:22:06.799  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.799  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.799  5694  5694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:22:06.799  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.800  5694  5694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:22:06.800  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.800  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.800  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.800  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.800  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.800  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.800  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.800  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.800  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.800  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.800  4494  4570 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 08:22:06.800  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.800  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.800  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.800  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.800  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.801  5694  5740 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 08:22:06.801  5694  5740 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 08:22:06.801  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 08:22:06.801  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:22:06.801  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.801  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.801  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.801  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.801  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.801  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.801  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.801  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.801  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.801  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.801  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.801  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.802  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.802  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.801  5694  5743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 08:22:06.802  5694  5743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 08:22:06.802  5694  5743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 08:22:06.803  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.803  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.803  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.803  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.803  5694  5694 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 08:22:06.804  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.804  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.804  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.804  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.804  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.804  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.804  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.804  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.804  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.804  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.804  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.804  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.804  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.804  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.805  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.805  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.805  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.806  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.806  4494  4570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 08:22:06.806  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.806  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:06.806  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:06.806  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:06.806  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:06.806  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.806  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.806  5694  5740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc4c72 not in the list
08-29 08:22:06.806  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.806  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.806  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:06.806  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.806  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.806  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:06.806  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:06.807  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:06.807  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:06.807  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:06.807  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee378c3 not in the list
08-29 08:22:06.807  5694  5740 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 08:22:06.807  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 08:22:06.807  5694  5740 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 08:22:06.807  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 08:22:06.807  5694  5740 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 08:22:06.807  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 08:22:06.808  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 08:22:06.808  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 08:22:06.808  5694  5740 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 08:22:06.808  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 08:22:06.808  5694  5740 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 08:22:06.808  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 08:22:06.808  5694  5740 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 08:22:06.808  5694  5740 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 08:22:06.809  5694  5740 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 08:22:06.809  5694  5740 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 08:22:06.809  5694  5740 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 08:22:06.809  5694  5740 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 08:22:06.809  5694  5740 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 08:22:06.809  5694  5740 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 08:22:06.809  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:06.809  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b0eb7ed added. We now have 2 listener(s)
08-29 08:22:06.809  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:22:06.810  5694  5740 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 08:22:06.810   927  3669 D WifiService: setWifiEnabled: true pid=5694, uid=10077
08-29 08:22:06.810   927  3669 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 08:22:06.811  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:06.811  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f9cb622 added. We now have 3 listener(s)
08-29 08:22:06.811  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:22:06.812  4494  4570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 08:22:06.813  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.813  4494  4579 D BtGatt.ScanManager: stopping BLe Batch
08-29 08:22:06.814  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:06.814  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@58418b3 added. We now have 4 listener(s)
08-29 08:22:06.814  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:22:06.815  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:06.815  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6373e70 added. We now have 5 listener(s)
08-29 08:22:06.815  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:22:06.817  4494  4570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 08:22:06.817  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.817   927  3253 D WifiService: setWifiEnabled: false pid=5694, uid=10077
08-29 08:22:06.817  4494  4579 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 08:22:06.817   927  3253 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:22:06.820   927  3073 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 08:22:06.820   927  3073 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 08:22:06.820   927  3073 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 08:22:06.820   927  3073 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 08:22:06.821  4494  4570 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 08:22:06.821  4494  4570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:06.822  4494  4566 D BluetoothAdapterState: Current state: ON, message: 23
08-29 08:22:06.822  4494  4566 D BluetoothAdapterProperties: Setting state to 13
08-29 08:22:06.822  4494  4566 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 08:22:06.822  4494  4566 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 08:22:06.823  4494  4566 I BluetoothAdapterState: Entering PendingCommandState
08-29 08:22:06.824  4494  4494 D BluetoothMapService: onReceive
08-29 08:22:06.824  4494  4494 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:22:06.824  4494  4494 D BluetoothMapService: STATE_TURNING_OFF
08-29 08:22:06.824  4494  4494 D BluetoothMapService: MAP Service closeService in
08-29 08:22:06.825  4494  4494 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 08:22:06.825  4494  4494 D ObexServerSockets0: shutdown(block = true)
08-29 08:22:06.825  4494  4494 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 08:22:06.825  4494  4774 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
08-29 08:22:06.825  4494  4494 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 08:22:06.826  4494  4727 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 08:22:06.826  4494  4775 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 08:22:06.826  4494  4494 I BtOppRfcommListener: stopping Accept Thread
08-29 08:22:06.826  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:06.826  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:06.826  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:06.826  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:06.826  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:06.826  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:22:06.826  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:22:06.826  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:22:06.826  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:22:06.827  4494  5321 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 08:22:06.827  4494  5321 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 08:22:06.827  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:06.827  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:22:06.830   927  3073 E native  : do suspend true
08-29 08:22:06.835   927   940 I ActivityManager: Start proc 5746:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-29 08:22:06.836  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:22:06.837  4494  4570 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:22:06.837  4494  4566 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 08:22:06.839  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:06.839  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:22:06.839  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:06.839  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:06.839  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:06.839  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:22:06.839  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:22:06.839  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:22:06.839  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:22:06.839  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:06.839  5694  5740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:22:06.839  5694  5740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:22:06.840  4494  4494 D HeadsetService: Received stop request...Stopping profile...
08-29 08:22:06.841  3648  3670 D BluetoothHeadset: Proxy object disconnected
08-29 08:22:06.842  4494  4494 D A2dpService: Received stop request...Stopping profile...
08-29 08:22:06.842  4494  4756 D A2dpStateMachine: Exit Disconnected: -1
08-29 08:22:06.842  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:06.843   927   927 D BluetoothHeadset: Proxy object disconnected
08-29 08:22:06.843  3242  3255 D BluetoothHeadset: Proxy object disconnected
08-29 08:22:06.843   927   927 D BluetoothHeadset: Proxy object disconnected
08-29 08:22:06.843   927   927 D BluetoothHeadset: Proxy object disconnected
08-29 08:22:06.845  4494  4494 D HidService: Received stop request...Stopping profile...
08-29 08:22:06.845   927   927 D BluetoothA2dp: Proxy object disconnected
08-29 08:22:06.846  4494  4494 D HidService: Stopping Bluetooth HidService
08-29 08:22:06.846  4494  4494 D HealthService: Received stop request...Stopping profile...
08-29 08:22:06.847  4494  4494 D PanService: Received stop request...Stopping profile...
08-29 08:22:06.848  4494  4494 V BluetoothAdapterState: isTurningOff()=true
08-29 08:22:06.848  4494  4494 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:06.848  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:06.848  4494  4494 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:06.848  3242  3242 D HeadsetProfile: Bluetooth service disconnected
08-29 08:22:06.849  3242  3242 D BluetoothA2dp: Proxy object disconnected
08-29 08:22:06.849  3242  3242 D BluetoothInputDevice: Proxy object disconnected
08-29 08:22:06.849  3242  3242 D HidProfile: Bluetooth service disconnected
08-29 08:22:06.849  3242  3242 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 08:22:06.849  3242  3242 D PanProfile: Bluetooth service disconnected
08-29 08:22:06.849  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:06.849  4494  4494 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 08:22:06.850  4494  4494 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 08:22:06.850  4494  4570 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 08:22:06.850  4494  4723 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:22:06.850  4494  4723 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:22:06.850  4494  4723 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:22:06.850  4494  4570 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 08:22:06.850  4494  4494 D BluetoothMapService: Received stop request...Stopping profile...
08-29 08:22:06.850  4494  4494 D BluetoothMapService: stop()
08-29 08:22:06.851  4494  4494 D BluetoothMapAppObserver: deinitObservers()
08-29 08:22:06.851  4494  4494 D BluetoothMapAppObserver: removeReceiver()
08-29 08:22:06.852  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:06.854  4494  4494 D SapService: Received stop request...Stopping profile...
08-29 08:22:06.854  4494  4494 V SapService: stop()
08-29 08:22:06.855  3242  3242 D BluetoothMap: Proxy object disconnected
08-29 08:22:06.855  3242  3242 D MapProfile: Bluetooth service disconnected
08-29 08:22:06.855  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:06.855  4494  4494 V BluetoothAdapterState: isTurningOff()=true
08-29 08:22:06.855  4494  4494 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:06.855  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:06.855  4494  4494 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:06.856  4494  4570 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 08:22:06.856  4494  4723 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:22:06.856  4494  4494 V BluetoothAdapterState: isTurningOff()=true
,08-29 08:22:06.857  4494  4494 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:06.857  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:06.857  4494  4723 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:22:06.857  4494  4723 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:22:06.857  4494  4494 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:06.857  4494  4723 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:22:06.857  4494  4723 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:22:06.857  4494  4723 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:22:06.857  4494  4494 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 08:22:06.857  4494  4494 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 08:22:06.857  4494  4570 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 08:22:06.857  4494  4494 V BluetoothAdapterState: isTurningOff()=true
08-29 08:22:06.857  4494  4494 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:06.857  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:06.857  4494  4494 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:06.858  4494  4494 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 08:22:06.858   927  5358 D DhcpClient: Clearing IP address
08-29 08:22:06.858  4494  4494 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 08:22:06.858   505   921 D CommandListener: Clearing all IP addresses on wlan0
,08-29 08:22:06.859  4494  4494 V BluetoothAdapterState: isTurningOff()=true
08-29 08:22:06.859  4494  4494 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:06.859  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:06.859  4494  4494 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:22:06.859  4494  4494 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 08:22:06.859  4494  4494 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 08:22:06.860  4494  4570 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 08:22:06.860  4494  4494 D BluetoothMapService: MAP Service closeService in
08-29 08:22:06.860  4494  4494 V BluetoothAdapterState: isTurningOff()=true
08-29 08:22:06.860  4494  4494 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:06.860  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:06.860  4494  4494 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:06.860  4494  4494 D BluetoothMapService: cleanup()
08-29 08:22:06.860  4494  4494 D BluetoothMapService: MAP Service closeService in
,08-29 08:22:06.861  4494  4494 V BluetoothAdapterState: isTurningOff()=true
08-29 08:22:06.861  4494  4494 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:06.861  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:06.861  4494  4494 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:06.861  4494  4566 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 08:22:06.861  4494  4566 D BluetoothAdapterProperties: Setting state to 15
08-29 08:22:06.861  4494  4566 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 08:22:06.861  4494  4566 I BluetoothAdapterState: Entering BleOnState
,08-29 08:22:06.864   505   921 D CommandListener: Setting iface cfg
,08-29 08:22:06.865  3242  3255 D BluetoothPan: onBluetoothStateChange on: false
08-29 08:22:06.866  3242  3256 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 08:22:06.866   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:22:06.866  3242  3848 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 08:22:06.867   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:22:06.867   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 08:22:06.867  3242  3255 D BluetoothMap: onBluetoothStateChange: up=false
08-29 08:22:06.867  3242  3256 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:22:06.868   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:22:06.868  3242  3848 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 08:22:06.868  3648  3855 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:22:06.869  4494  4566 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 08:22:06.869  4494  4566 D BluetoothAdapterProperties: Setting state to 16
08-29 08:22:06.869  4494  4566 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 08:22:06.870  3710  5412 V NativeCrypto: Read error: ssl=0x7f99689600: I/O error during system call, Connection timed out
08-29 08:22:06.871  4494  4566 D BluetoothAdapterProperties: onBleDisable
08-29 08:22:06.871   927  5359 D DhcpClient: Receive thread stopped
,08-29 08:22:06.872  4494  4566 I BluetoothAdapterState: Entering PendingCommandState
,08-29 08:22:06.872  3710  5412 V NativeCrypto: SSL shutdown failed: ssl=0x7f99689600: I/O error during system call, Broken pipe
08-29 08:22:06.872  4494  4567 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-29 08:22:06.873  4494  4570 D BluetoothAdapterProperties: Scan Mode:20
,08-29 08:22:06.877  4494  4723 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 08:22:06.878  4494  4723 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:22:06.878  5694  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
08-29 08:22:06.878   927  3075 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 08:22:06.878   927  3075 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 08:22:06.882   927   927 D RttService: SCAN_AVAILABLE : 1
08-29 08:22:06.882   927  3183 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:22:06.882  5746  5746 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
08-29 08:22:06.883   538   538 E Parcel  : Reading a NULL string not supported here.
08-29 08:22:06.884  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:06.884  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:06.884  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:06.884  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:06.884  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:06.884  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:22:06.884  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:06.884  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:06.884  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:22:06.886  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:06.886  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:06.887   927  3075 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 08:22:06.888  3597  3824 W QCNEJ   : |CORE| network lost: 100
,08-29 08:22:06.888  3597  3824 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
08-29 08:22:06.889  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:06.889  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:06.889  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:06.889  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:06.889  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:06.889  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:22:06.889  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:06.889  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:06.889  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:22:06.890  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:06.890  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:22:06.891   927  3073 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 08:22:06.892  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:06.892  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:06.892  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:06.892  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:06.892  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:06.892  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:22:06.892  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:06.892  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:06.892  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:22:06.894  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:22:06.894  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:06.894  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:06.894  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:06.894  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:06.894  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:22:06.894  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:06.894  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:06.894  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:22:06.896   927  3073 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 08:22:06.896   927  3073 E native  : do suspend true
,08-29 08:22:06.897  5746  5746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 08:22:06.903   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9c3111c:true
,08-29 08:22:06.904  3710  3710 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:22:06.911   505   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:22:06.917   927  3704 I ActivityManager: Start proc 5765:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 08:22:06.930  5746  5746 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 08:22:06.931   505   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:22:06.931   505   921 D CommandListener: Clearing all IP addresses on wlan0
08-29 08:22:06.932   505   921 D TetherController: Setting IP forward enable = 0
,08-29 08:22:06.932  5746  5746 D BluetoothMap: Create BluetoothMap proxy object
,08-29 08:22:06.933   927  3075 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 08:22:06.933   927  3075 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 08:22:06.934   927   944 D Tethering: MasterInitialState.processMessage what=3
08-29 08:22:06.936   927  3073 D DhcpClient: doQuit
08-29 08:22:06.936   927  3073 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 08:22:06.936   927  5358 D DhcpClient: onQuitting
08-29 08:22:06.937  3751  3751 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
08-29 08:22:06.937  5255  5255 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d052db1 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 08:22:06.938  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:06.940  4990  5006 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,08-29 08:22:06.942  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:22:06.942  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:06.942  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:06.942  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:06.942  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:22:06.942  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:22:06.942  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:06.942  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:06.942  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:22:06.943  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:06.943  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:06.940  4990  5006 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 08:22:06.944  4990  5006 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 08:22:06.944  4990  5006 E SarControlService: no key has been found,reset the power
08-29 08:22:06.944  4990  5029 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 08:22:06.944  4990  5029 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,08-29 08:22:06.945  4990  5029 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 08:22:06.945  5019  5019 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 08:22:06.945  5019  5019 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 08:22:06.945  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:06.946  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:06.946  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:06.946  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:06.946  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:22:06.946  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:22:06.946  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:06.946  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:06.946  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:22:06.947  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:06.947  4990  5029 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 08:22:06.947  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:06.947  4990  5029 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,08-29 08:22:06.947  4990  5029 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,08-29 08:22:06.948  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:06.948  5019  5019 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 08:22:06.949  5019  5019 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 08:22:06.952  5019  5033 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@eee965f HexData = [00000000ea03000000000000ffffffff]
08-29 08:22:06.952  5019  5033 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 08:22:06.952  5019  5033 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
08-29 08:22:06.953  5019  5019 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 08:22:06.953  4990  5002 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,08-29 08:22:06.962  5019  5033 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@eee965f HexData = [00000000eb03000000000000ffffffff]
,08-29 08:22:06.962  5019  5033 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 08:22:06.962  5019  5033 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,08-29 08:22:06.963  5019  5019 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,08-29 08:22:06.963  4990  5003 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-29 08:22:06.971  5765  5765 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,08-29 08:22:06.974  5746  5746 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 08:22:06.975   505   921 E Netd    : netlink response contains error (No such file or directory)
,08-29 08:22:06.985  5746  5746 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:22:06.992  3751  3751 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 08:22:06.997  3751  3751 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 08:22:07.004   927  3677 I ActivityManager: Killing 4919:com.google.android.calendar/u0a36 (adj 15): empty #17
,08-29 08:22:07.067  3751  3751 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 08:22:07.083  4494  4570 I bt_hci  : shut_down
,08-29 08:22:07.085  4494  4582 D bt_hwcfg: hw_epilog_process
08-29 08:22:07.086  4494  4582 I bt_vendor: low_power_mode_cb
,08-29 08:22:07.088  4494  4582 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 08:22:07.088  4494  4582 I bt_vendor: epilog_cb
08-29 08:22:07.088  4494  4582 I bt_hci  : epilog_finished_callback
,08-29 08:22:07.091  4494  4570 I bt_hci_h4: hal_close
,08-29 08:22:07.091  4494  4570 I bt_userial_vendor: device fd = 51 close
,08-29 08:22:07.105  3751  3751 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 08:22:07.198  4494  4567 D bt_stack_manager: event_shut_down_stack finished.
,08-29 08:22:07.198  4494  4566 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 08:22:07.200  4494  4494 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 08:22:07.200  4494  4566 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 08:22:07.200  4494  4494 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 08:22:07.201  4494  4494 D BtGatt.GattService: stop()
08-29 08:22:07.201  4494  4494 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 08:22:07.202  4494  4494 V BluetoothAdapterState: isTurningOff()=false
,08-29 08:22:07.203  4494  4494 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:07.203  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:07.203  4494  4494 V BluetoothAdapterState: isBleTurningOff()=true
08-29 08:22:07.203  4494  4566 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 08:22:07.203  4494  4566 D BluetoothAdapterProperties: Setting state to 10
08-29 08:22:07.203  4494  4566 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 08:22:07.204  4494  4566 I BluetoothAdapterState: Entering OffState
,08-29 08:22:07.204   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 08:22:07.207   927  3073 D wifi    : In wifi stop Hal
,08-29 08:22:07.207   927  3073 D wifi    : halHandle = 0x7f870b4be0, mVM = 0x7fa354d140, mCls = 0x100b4e
08-29 08:22:07.208   927  3740 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 08:22:07.208   927  3740 D WifiHAL : Got a signal to exit!!!
08-29 08:22:07.208   927  3740 I WifiHAL : Exit wifi_event_loop
08-29 08:22:07.208   927  3073 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 08:22:07.208   927  3073 E WifiHAL : Event processing terminated
08-29 08:22:07.209   927  3073 D wifi    : In wifi cleaned up handler
08-29 08:22:07.209   927  3073 I WifiHAL : Internal cleanup completed
08-29 08:22:07.209  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:07.209  4960  4960 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:22:07.210  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:07.210  3571  4087 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 08:22:07.212  4494  4494 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 08:22:07.212  4494  4494 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-29 08:22:07.212  4494  4494 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 08:22:07.214  4494  4567 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 08:22:07.215  4494  4567 D bt_stack_manager: event_clean_up_stack finished.
08-29 08:22:07.221  5765  5765 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:22:07.221  5765  5765 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 ,08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:22:07.221  5765  5765 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08,-29 08:22:07.221  5765  5765 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:22:07.221  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:22:07.222  5765  5765 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:22:07.222  5765  5765 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:22:07.222  5765  5765 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:22:07.222  5765  5765 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:22:07.222  5765  5765 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:22:07.222  5765  5765 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:22:07.226  5746  5746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 08:22:07.227   927  3740 D wifi    : set interface wlan0 flags (DOWN)
08-29 08:22:07.227   927  3073 D WifiNative-HAL: HAL event thread stopped successfully
08-29 08:22:07.239  4494  4494 I art     : System.exit called, status: 0
08-29 08:22:07.239  4494  4494 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 08:22:07.246  5746  5746 D DockEventReceiver: finishStartingService: stopping service
08-29 08:22:07.247   927  3663 I ActivityManager: Killing 5069:com.google.android.deskclock/u0a66 (adj 15): empty #17
,08-29 08:22:07.300  5694  5694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 08:22:07.317   927  3704 I ActivityManager: Process com.android.bluetooth (pid 4494) has died
,08-29 08:22:07.320  3710  3710 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:22:07.332   927   937 I ActivityManager: Start proc 5804:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,08-29 08:22:07.392  5804  5804 D AdapterServiceConfig: Adding HeadsetService
,08-29 08:22:07.392  5804  5804 D AdapterServiceConfig: Adding A2dpService
08-29 08:22:07.392  5804  5804 D AdapterServiceConfig: Adding HidService
08-29 08:22:07.392  5804  5804 D AdapterServiceConfig: Adding HealthService
08-29 08:22:07.392  5804  5804 D AdapterServiceConfig: Adding PanService
08-29 08:22:07.392  5804  5804 D AdapterServiceConfig: Adding GattService
08-29 08:22:07.392  5804  5804 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 08:22:07.393  5804  5804 D AdapterServiceConfig: Adding SapService
,08-29 08:22:07.400   927  3668 I ActivityManager: Killing 5435:com.qualcomm.timeservice/1000 (adj 15): empty #17
,08-29 08:22:07.420  3914  3914 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 08:22:07.423  3914  3914 D SystemUpdateService: onCreate
,08-29 08:22:07.430   927   944 D Tethering: InitialState.processMessage what=4
,08-29 08:22:07.430  3914  3914 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 08:22:07.433   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 08:22:07.438  3914  3914 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 08:22:07.444  3914  5383 I iu.UploadsManager: num queued entries: 0
,08-29 08:22:07.444  3914  5383 I iu.UploadsManager: num updated entries: 0
,08-29 08:22:07.445  3914  5816 I SystemUpdateService: active receiver: enabled
,08-29 08:22:07.455  3914  5383 I iu.SyncManager: NEXT; no task
,08-29 08:22:07.457  3914  3914 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 08:22:07.459  3914  3914 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 08:22:07.466  3914  5816 I SystemUpdateService: showing system update notification
,08-29 08:22:07.471   927   937 I ActivityManager: Start proc 5818:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 08:22:07.509  5818  5818 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,08-29 08:22:07.515  3914  5816 V SystemUpdateService: retry (wakeup: false) in 3599954 ms
,08-29 08:22:07.518  3914  3914 D SystemUpdateService: onDestroy
,08-29 08:22:07.520  5818  5818 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:22:07.527  5818  5818 D SprintDMHelper: simOperator: 
08-29 08:22:07.527  5818  5818 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 08:22:07.541  5765  5796 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 08:22:07.541   927  3669 I ActivityManager: Start proc 5830:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 08:22:07.542   927  3669 I ActivityManager: Killing 5416:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,08-29 08:22:07.571   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@448be49:true
,08-29 08:22:07.679  4960  5847 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 08:22:07.690   927  3677 I ActivityManager: Start proc 5848:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 08:22:07.692   927   937 I ActivityManager: Killing 5255:com.google.android.music:main/u0a59 (adj 15): empty #17
,08-29 08:22:07.739  5848  5848 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 08:22:07.898   927  3529 I ActivityManager: Killing 4593:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-29 08:22:07.939   927  3663 I ActivityManager: Start proc 5860:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 08:22:07.971  5860  5860 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,08-29 08:22:07.979   505   921 D TetherController: Setting IP forward enable = 0
,08-29 08:22:08.014  5860  5860 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 08:22:08.018   927  3306 I ActivityManager: Killing 5581:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-29 08:22:09.841   927  3677 D WifiService: setWifiEnabled: true pid=5694, uid=10077
,08-29 08:22:09.841   927  3677 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:22:09.850   505   921 D SoftapController: Softap fwReload - Ok
,08-29 08:22:09.854   505   921 D CommandListener: Setting iface cfg
08-29 08:22:09.855   505   921 D CommandListener: Trying to bring down wlan0
,08-29 08:22:09.857   505   921 D CommandListener: Clearing all IP addresses on wlan0
,08-29 08:22:09.862   927  3073 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 08:22:10.466   927  3073 D wifi    : set interface wlan0 flags (UP)
,08-29 08:22:10.471   927  3073 I WifiHAL : Initializing wifi
,08-29 08:22:10.471   927  3073 I WifiHAL : Creating socket
,08-29 08:22:10.476   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 08:22:10.477   927  3073 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-29 08:22:10.478   927  3073 D wifi    : Did set static halHandle = 0x7f870b4be0
,08-29 08:22:10.478   927  3073 D wifi    : halHandle = 0x7f870b4be0, mVM = 0x7fa354d140, mCls = 0x1016d6
08-29 08:22:10.479   927  3073 D wifi    : array field set
08-29 08:22:10.479   927  3073 I WifiNative-HAL: interface[0] = wlan0
,08-29 08:22:10.481   927  5893 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547726511072
08-29 08:22:10.481   927  5893 D wifi    : waitForHalEvents called, vm = 0x7fa354d140, obj = 0x1016d6, env = 0x7f896ad380
,08-29 08:22:10.529  5894  5894 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 08:22:10.549  5894  5894 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 08:22:10.558  5894  5894 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 08:22:10.558  5894  5894 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 08:22:10.582   927  3073 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 08:22:10.586  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:10.588  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:10.596   927  3073 D WifiConfigStore: Loading config and enabling all networks 
,08-29 08:22:10.597  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:10.597  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:10.597  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:10.597  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:10.597  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:10.597  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:22:10.597  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:10.597  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:10.597  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:22:10.597  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:10.597  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:10.598  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:10.598  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:10.598  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:10.598  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:10.598  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:10.598  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:22:10.598  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:10.598  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:10.598  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:22:10.598  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:22:10.598  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:22:10.603   927  3073 D WifiConfigStore: loaded 0 passpoint configs
,08-29 08:22:10.603   927  3073 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 08:22:10.603   927  3073 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 08:22:10.604   927  3073 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 08:22:10.604   927  3073 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 08:22:10.604   927  3073 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 08:22:10.608   927  3073 D WifiNative-HAL: Setting external_sim to 1
,08-29 08:22:10.609   927  3073 D wifi    : setting dfs flag to true, 0x7f885f1f40
08-29 08:22:10.609   927  3073 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 08:22:10.609  4960  4960 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:22:10.609   927  3073 D wifi    : setting scan oui 0x7f885f1f40
08-29 08:22:10.609   927  3073 D WifiHAL : Sending mac address OUI
,08-29 08:22:10.624   927  3073 E native  : do suspend true
,08-29 08:22:10.629   927  3073 D wifi    : android_net_wifi_setLinkLayerStats: 1
,08-29 08:22:10.629   927   927 D RttService: SCAN_AVAILABLE : 3
08-29 08:22:10.629   927  3183 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 08:22:10.633   505   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 08:22:10.635   505   921 D CommandListener: Setting iface cfg
,08-29 08:22:10.635   927  3072 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
08-29 08:22:10.635   927  3072 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 08:22:10.641   927  3072 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 08:22:10.642   927  3072 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 08:22:10.647   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=178152 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=8 mControllerEnergyUsed=30 }
,08-29 08:22:12.847   927  3663 D WifiService: setWifiEnabled: false pid=5694, uid=10077
08-29 08:22:12.847   927  3663 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:22:12.856   927   927 D RttService: SCAN_AVAILABLE : 1
,08-29 08:22:12.856   927  3183 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 08:22:12.867   927  3073 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 08:22:12.867   505   921 D CommandListener: Clearing all IP addresses on wlan0
,08-29 08:22:12.869   927  3073 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 08:22:12.870  5894  5894 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-29 08:22:12.873  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:12.873  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:12.873  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:12.873  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:12.873  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:22:12.873  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:22:12.873  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:12.873  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:12.873  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:22:12.873  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:12.873  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:12.874  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:12.874  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:12.874  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:12.874  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:12.874  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:22:12.874  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:22:12.874  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:12.874  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:12.874  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:22:12.874  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:12.874  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:22:12.887  5894  5894 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 08:22:12.975  5894  5894 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 08:22:12.996  5894  5894 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 08:22:13.101   927  3073 D wifi    : In wifi stop Hal
,08-29 08:22:13.102   927  3073 D wifi    : halHandle = 0x7f870b4be0, mVM = 0x7fa354d140, mCls = 0x1016d6
08-29 08:22:13.102  4960  4960 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:22:13.102   927  5893 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,08-29 08:22:13.102   927  5893 D WifiHAL : Got a signal to exit!!!
08-29 08:22:13.102   927  5893 I WifiHAL : Exit wifi_event_loop
08-29 08:22:13.103   927  3073 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 08:22:13.103   927  3073 E WifiHAL : Event processing terminated
08-29 08:22:13.104   927  3073 D wifi    : In wifi cleaned up handler
08-29 08:22:13.104   927  3073 I WifiHAL : Internal cleanup completed
08-29 08:22:13.105  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:13.109  3571  4087 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 08:22:13.111  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:13.135   927  5893 D wifi    : set interface wlan0 flags (DOWN)
,08-29 08:22:13.136   927  3073 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 08:22:13.340   927   944 D Tethering: InitialState.processMessage what=4
08-29 08:22:13.344   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 08:22:15.883   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5d227b:true
,08-29 08:22:15.884  5804  5804 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 08:22:15.888  5804  5804 I bt_bluedroid: init
,08-29 08:22:15.888  5804  5898 I BluetoothAdapterState: Entering OffState
,08-29 08:22:15.891  5804  5899 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 08:22:15.891  5804  5899 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 08:22:15.891  5804  5899 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 08:22:15.892  5804  5899 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 08:22:15.892  5804  5804 I bt_bluedroid: get_profile_interface socket
,08-29 08:22:15.895  5804  5902 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 08:22:15.896  5804  5804 I bt_bluedroid: get_profile_interface sdp
08-29 08:22:15.897  5804  5902 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 08:22:15.900  5804  5814 I bt_bluedroid: config_hci_snoop_log
,08-29 08:22:15.901   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 08:22:15.906  5804  5898 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 08:22:15.906  5804  5898 D BluetoothAdapterProperties: Setting state to 14
08-29 08:22:15.906  5804  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-29 08:22:15.907  5804  5898 D BluetoothBondStateMachine: make
,08-29 08:22:15.909  5804  5903 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 08:22:15.912  5804  5898 I BluetoothAdapterState: Entering PendingCommandState
,08-29 08:22:15.913  5804  5804 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 08:22:15.916  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
08-29 08:22:15.916  5804  5804 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 08:22:15.917  5804  5804 D BtGatt.GattService: Received start request. Starting profile...
08-29 08:22:15.917  5804  5804 D BtGatt.GattService: start()
08-29 08:22:15.917  5804  5804 I bt_bluedroid: get_profile_interface gatt
08-29 08:22:15.918  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
,08-29 08:22:15.918  5804  5804 D BtGatt.AdvertiseManager: advertise manager created
,08-29 08:22:15.924  5804  5804 V BluetoothAdapterState: isTurningOff()=false
08-29 08:22:15.924  5804  5804 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:15.924  5804  5804 V BluetoothAdapterState: isBleTurningOn()=true
08-29 08:22:15.924  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:15.924  5804  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-29 08:22:15.924  5804  5898 I bt_bluedroid: enable
08-29 08:22:15.924  5804  5899 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 08:22:15.925  5804  5899 I bt_hci  : start_up
,08-29 08:22:15.930  5804  5899 I bt_vendor: alloc value 0xf407904d
08-29 08:22:15.930  5804  5899 I bt_vendor: init
08-29 08:22:15.930  5804  5899 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 08:22:15.930  5804  5899 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 08:22:16.046  5804  5899 D bt_hci  : start_up starting async portion
,08-29 08:22:16.046  5804  5906 I bt_hci  : event_finish_startup
08-29 08:22:16.046  5804  5906 I bt_hci_h4: hal_open
08-29 08:22:16.047  5804  5906 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 08:22:16.034  5909  5909 W irq/448-msm_hs_: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 08:22:16.050  5804  5906 I bt_userial_vendor: device fd = 51 open
,08-29 08:22:16.064  5804  5906 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 08:22:16.068  5804  5906 D bt_hwcfg: Chipset BCM4358A3
,08-29 08:22:16.068  5804  5906 D bt_hwcfg: Target name = [BCM4358A3]
08-29 08:22:16.069  5804  5906 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 08:22:16.470  5804  5906 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 08:22:16.471  5804  5906 D bt_hwcfg: Settlement delay -- 100 ms
08-29 08:22:16.471  5804  5906 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 08:22:16.604  5804  5906 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 08:22:16.604  5804  5906 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 08:22:16.606  5804  5906 I bt_hwcfg: vendor lib fwcfg completed
,08-29 08:22:16.606  5804  5906 I bt_vendor: firmware callback
,08-29 08:22:16.606  5804  5906 I bt_hci  : firmware_config_callback
,08-29 08:22:16.615  5804  5911 I bt_btu  : btu_task pending for preload complete event
,08-29 08:22:16.615  5804  5911 I bt_btu_task: Bluetooth chip preload is complete
08-29 08:22:16.615  5804  5911 I bt_btu  : btu_task received preload complete event
,08-29 08:22:16.621  5804  5911 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 08:22:16.622  5804  5911 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 08:22:16.622  5804  5911 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 08:22:16.622  5804  5911 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 08:22:16.622  5804  5911 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 08:22:16.622  5804  5911 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 08:22:16.622  5804  5911 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 08:22:16.622  5804  5911 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 08:22:16.622  5804  5911 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 08:22:16.623  5804  5911 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 08:22:16.623  5804  5911 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 08:22:16.623  5804  5911 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 08:22:16.623  5804  5911 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 08:22:16.623  5804  5911 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 08:22:16.623  5804  5911 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 08:22:16.704  5804  5911 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ff6c99
,08-29 08:22:16.704  5804  5911 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ff6c99 
,08-29 08:22:16.734  5804  5902 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 08:22:16.735  5804  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 08:22:16.736  5804  5902 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 08:22:16.738  5804  5902 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 08:22:16.740  5804  5902 D BluetoothAdapterProperties: Scan Mode:20
,08-29 08:22:16.741  5804  5902 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 08:22:16.741  5804  5902 D bt_hci  : do_postload posting postload work item
,08-29 08:22:16.741  5804  5906 I bt_hci  : event_postload
08-29 08:22:16.741  5804  5906 I bt_vendor: sco_config_cb
08-29 08:22:16.741  5804  5906 I bt_hci  : sco_config_callback postload finished.
08-29 08:22:16.744  5804  5902 D bt_bte_conf: Device ID record 1 : primary
08-29 08:22:16.745  5804  5902 D bt_bte_conf:   vendorId            = 000f
08-29 08:22:16.745  5804  5902 D bt_bte_conf:   vendorIdSource      = 0001
08-29 08:22:16.745  5804  5902 D bt_bte_conf:   product             = 1200
,08-29 08:22:16.745  5804  5902 D bt_bte_conf:   version             = 1436
08-29 08:22:16.745  5804  5902 D bt_bte_conf:   clientExecutableURL = 
08-29 08:22:16.745  5804  5902 D bt_bte_conf:   serviceDescription  = 
08-29 08:22:16.745  5804  5902 D bt_bte_conf:   documentationURL    = 
08-29 08:22:16.745  5804  5902 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 08:22:16.745  5804  5899 D bt_stack_manager: event_start_up_stack finished
08-29 08:22:16.747  5804  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 08:22:16.747  5804  5898 D BluetoothAdapterProperties: Setting state to 15
08-29 08:22:16.747  5804  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 08:22:16.747  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:16.748  5804  5898 I BluetoothAdapterState: Entering BleOnState
08-29 08:22:16.750  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:16.756  5804  5898 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 08:22:16.756  5804  5898 D BluetoothAdapterProperties: Setting state to 11
08-29 08:22:16.756  5804  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 08:22:16.757  5804  5906 I bt_vendor: low_power_mode_cb
08-29 08:22:16.760  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
08-29 08:22:16.761  5804  5804 D HeadsetService: Received start request. Starting profile...
,08-29 08:22:16.765  5804  5804 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 08:22:16.766  5804  5804 D HeadsetStateMachine: make
,08-29 08:22:16.770  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:16.772  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:16.776  5804  5898 I BluetoothAdapterState: Entering PendingCommandState
,08-29 08:22:16.778  5804  5804 D HeadsetStateMachine: max_hf_connections = 1
,08-29 08:22:16.778  5804  5804 I bt_bluedroid: get_profile_interface handsfree
08-29 08:22:16.779  5804  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 08:22:16.779  5804  5902 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-29 08:22:16.782  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
,08-29 08:22:16.783  5804  5804 D A2dpService: Received start request. Starting profile...
,08-29 08:22:16.784  5804  5804 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 08:22:16.784  5804  5804 I bt_bluedroid: get_profile_interface avrcp
,08-29 08:22:16.789  5804  5804 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 08:22:16.789  5804  5804 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 08:22:16.790  5804  5804 D A2dpStateMachine: make
08-29 08:22:16.791  5804  5804 I bt_bluedroid: get_profile_interface a2dp
,08-29 08:22:16.791  5804  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 08:22:16.792  5804  5919 D A2dpStateMachine: Enter Disconnected: -2
08-29 08:22:16.793  5804  5804 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 08:22:16.794  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
,08-29 08:22:16.796  5804  5804 D HidService: Received start request. Starting profile...
,08-29 08:22:16.796  5804  5804 I bt_bluedroid: get_profile_interface hidhost
08-29 08:22:16.796  5746  5746 D BluetoothInputDevice: Proxy object connected
08-29 08:22:16.796  5804  5804 D HidService: setHidService(): set to: null
08-29 08:22:16.796  5804  5902 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fd82d9
08-29 08:22:16.796  5804  5804 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 08:22:16.796  5804  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 08:22:16.797  5746  5746 D HidProfile: Bluetooth service connected
08-29 08:22:16.797  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
08-29 08:22:16.798  5804  5804 D HealthService: Received start request. Starting profile...
,08-29 08:22:16.799  5804  5804 I bt_bluedroid: get_profile_interface health
08-29 08:22:16.800  5804  5804 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 08:22:16.800  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
,08-29 08:22:16.801  5746  5746 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 08:22:16.801  5804  5804 D PanService: Received start request. Starting profile...
08-29 08:22:16.801  5804  5804 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 08:22:16.802  5804  5804 I bt_bluedroid: get_profile_interface pan
08-29 08:22:16.802  5746  5746 D PanProfile: Bluetooth service connected
08-29 08:22:16.802  5804  5902 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 08:22:16.804  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
,08-29 08:22:16.805  5746  5746 D BluetoothMap: Proxy object connected
08-29 08:22:16.805  5804  5804 D BluetoothMapService: Received start request. Starting profile...
08-29 08:22:16.805  5804  5804 D BluetoothMapService: start()
08-29 08:22:16.805  5746  5746 D MapProfile: Bluetooth service connected
08-29 08:22:16.805  5746  5746 D BluetoothMap: getConnectedDevices()
08-29 08:22:16.806  5746  5746 D BluetoothMap: Bluetooth is Not enabled
,08-29 08:22:16.807  5804  5804 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 08:22:16.808  5804  5804 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 08:22:16.808  5804  5804 D BluetoothMapAppObserver: createReceiver()
,08-29 08:22:16.809  5804  5804 D BluetoothMapAppObserver: initObservers()
,08-29 08:22:16.810  5804  5804 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 08:22:16.816  3710  3710 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:22:16.816  5804  5804 V SapService: SapBinder()
08-29 08:22:16.816  5804  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
08-29 08:22:16.817  5804  5804 D SapService: Received start request. Starting profile...
08-29 08:22:16.817  5804  5804 V SapService: start()
,08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isTurningOff()=false
,08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isTurningOn()=true
08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:16.820  5804  5917 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isTurningOff()=false
08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isTurningOn()=true
08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isTurningOff()=false
08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isTurningOn()=true
,08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isTurningOff()=false
08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isTurningOn()=true
08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:16.820  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:16.821  5804  5804 V BluetoothAdapterState: isTurningOff()=false
08-29 08:22:16.821  5804  5804 V BluetoothAdapterState: isTurningOn()=true
,08-29 08:22:16.821  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:16.821  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:16.821  5804  5804 V BluetoothAdapterState: isTurningOff()=false
08-29 08:22:16.821  5804  5804 V BluetoothAdapterState: isTurningOn()=true
08-29 08:22:16.821  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:16.821  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:16.822  5804  5804 V BluetoothAdapterState: isTurningOff()=false
08-29 08:22:16.822  5804  5804 V BluetoothAdapterState: isTurningOn()=true
08-29 08:22:16.822  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:16.822  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:22:16.824  5804  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-29 08:22:16.824  5804  5898 D BluetoothAdapterProperties: ScanMode =  20
08-29 08:22:16.824  5804  5898 D BluetoothAdapterProperties: State =  11
08-29 08:22:16.825  5804  5902 D BluetoothAdapterProperties: Scan Mode:21
08-29 08:22:16.826  5804  5902 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 08:22:16.826  5804  5898 D BluetoothAdapterProperties: Setting state to 12
08-29 08:22:16.826  5804  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 08:22:16.826  5804  5898 I BluetoothAdapterState: Entering OnState
08-29 08:22:16.827  5746  5756 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 08:22:16.827  3242  3848 D BluetoothPan: onBluetoothStateChange on: true
08-29 08:22:16.829  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:16.829  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:16.829  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:16.829  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:22:16.829  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:16.829  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:16.829  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:16.829  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:22:16.830  3242  3242 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 08:22:16.830  3242  3242 D PanProfile: Bluetooth service connected
08-29 08:22:16.830  3242  3255 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 08:22:16.831  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:16.832  5746  5757 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 08:22:16.833   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:22:16.833  5746  5756 D BluetoothPan: onBluetoothStateChange on: true
08-29 08:22:16.833  3242  3256 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 08:22:16.834  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:16.834  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:16.834  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:16.834  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:22:16.834  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:16.834  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:16.834  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:16.834  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:22:16.835  5804  5804 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 08:22:16.835   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 08:22:16.835   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:22:16.835  3242  3242 D BluetoothInputDevice: Proxy object connected
08-29 08:22:16.835  3242  3242 D HidProfile: Bluetooth service connected
08-29 08:22:16.835  5804  5804 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 08:22:16.836  3242  3255 D BluetoothMap: onBluetoothStateChange: up=true
08-29 08:22:16.836  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:16.837  5804  5804 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:22:16.837  3242  3242 D BluetoothMap: Proxy object connected
08-29 08:22:16.837  3242  3848 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:22:16.837  3242  3242 D MapProfile: Bluetooth service connected
08-29 08:22:16.837  3242  3242 D BluetoothMap: getConnectedDevices()
08-29 08:22:16.838   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 08:22:16.838  3242  3255 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:22:16.839  5804  5804 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:22:16.840  5804  5804 D ObexServerSockets: Succeed to create listening sockets 
08-29 08:22:16.840  5804  5804 D ObexServerSockets0: startAccept()
08-29 08:22:16.840  3648  3667 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 08:22:16.840  5804  5804 D ObexServerSockets0: prepareForNewConnect()
08-29 08:22:16.841  5746  5757 D BluetoothMap: onBluetoothStateChange: up=true
08-29 08:22:16.842  5804  5804 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 08:22:16.842  5804  5804 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 08:22:16.843   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 08:22:16.845  5804  5925 D ObexServerSockets0: Accepting socket connection...
,08-29 08:22:16.845  5804  5926 D ObexServerSockets0: Accepting socket connection...
,08-29 08:22:16.846   927   927 D BluetoothA2dp: Proxy object connected
,08-29 08:22:16.846  5804  5804 D BluetoothMapService: onReceive
08-29 08:22:16.846  5804  5804 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:22:16.846  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:16.846  5804  5804 D BluetoothMapService: STATE_ON
08-29 08:22:16.846  3242  3242 D BluetoothA2dp: Proxy object connected
08-29 08:22:16.847  5746  5746 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 08:22:16.847  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:16.850  5804  5929 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:22:16.852  5804  5929 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 08:22:16.852  5804  5929 D BluetoothSdpJni: SDP Create record success - handle: 1
08-29 08:22:16.852  5746  5746 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 08:22:16.858  5746  5746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 08:22:16.860  5746  5746 D BluetoothA2dp: Proxy object connected
,08-29 08:22:16.865  3710  3710 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:22:16.867  5746  5746 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:22:16.872  5804  5804 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 08:22:16.872  5804  5804 D ObexServerSockets0: prepareForNewConnect()
08-29 08:22:16.872  3242  3242 D BluetoothPbap: Proxy object connected
08-29 08:22:16.872  3242  3242 D PbapServerProfile: Bluetooth service connected
08-29 08:22:16.873  5746  5746 D BluetoothPbap: Proxy object connected
08-29 08:22:16.874  5746  5746 D PbapServerProfile: Bluetooth service connected
,08-29 08:22:16.879  5804  5933 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:22:16.890  5804  5937 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:22:16.891  5804  5937 I BtOppRfcommListener: Accept thread started.
,08-29 08:22:16.934  3648  3670 D BluetoothHeadset: Proxy object connected
,08-29 08:22:16.934   927   927 D BluetoothHeadset: Proxy object connected
08-29 08:22:16.935  3242  3848 D BluetoothHeadset: Proxy object connected
08-29 08:22:16.935  3242  3242 D HeadsetProfile: Bluetooth service connected
08-29 08:22:16.935   927   927 D BluetoothHeadset: Proxy object connected
08-29 08:22:16.935   927   927 D BluetoothHeadset: Proxy object connected
08-29 08:22:16.935   927   944 D BluetoothHeadset: Proxy object connected
,08-29 08:22:16.938  3242  3255 D BluetoothHeadset: Proxy object connected
,08-29 08:22:16.939  3242  3242 D HeadsetProfile: Bluetooth service connected
08-29 08:22:16.939   927   944 D BluetoothHeadset: Proxy object connected
,08-29 08:22:16.941  3648  3855 D BluetoothHeadset: Proxy object connected
,08-29 08:22:16.955  5746  5756 D BluetoothHeadset: Proxy object connected
,08-29 08:22:16.956  5746  5746 D HeadsetProfile: Bluetooth service connected
,08-29 08:22:18.864  5804  5898 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 08:22:18.864  5804  5898 D BluetoothAdapterProperties: Setting state to 13
,08-29 08:22:18.865  5804  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 08:22:18.866  5804  5898 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 08:22:18.868  5804  5898 I BluetoothAdapterState: Entering PendingCommandState
08-29 08:22:18.871  5804  5804 D BluetoothMapService: onReceive
08-29 08:22:18.871  5804  5902 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:22:18.871  5804  5804 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:22:18.872  5804  5804 D BluetoothMapService: STATE_TURNING_OFF
08-29 08:22:18.872  5804  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 08:22:18.872  5804  5804 D BluetoothMapService: MAP Service closeService in
08-29 08:22:18.872  5804  5804 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 08:22:18.873  5804  5804 D ObexServerSockets0: shutdown(block = true)
08-29 08:22:18.874  5804  5804 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 08:22:18.875  5804  5913 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-29 08:22:18.875  5804  5804 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 08:22:18.877  5804  5925 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-29 08:22:18.879  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:18.879  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:18.879  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:18.879  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:18.879  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:22:18.879  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:22:18.879  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:18.879  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:18.879  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:22:18.881  5804  5926 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 08:22:18.882  5804  5804 I BtOppRfcommListener: stopping Accept Thread
08-29 08:22:18.882  5804  5937 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 08:22:18.883  5804  5937 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 08:22:18.883  5746  5746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 08:22:18.885  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:22:18.885  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:18.886  5804  5804 D HeadsetService: Received stop request...Stopping profile...
08-29 08:22:18.888  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:18.888  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:18.888  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:18.888  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:18.888  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:22:18.888  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:22:18.888  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:18.888  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:18.888  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:22:18.889  5694  5694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:22:18.889  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:18.891  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:18.892  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:18.893  3648  3667 D BluetoothHeadset: Proxy object disconnected
,08-29 08:22:18.894  5746  5756 D BluetoothHeadset: Proxy object disconnected
,08-29 08:22:18.894   927   927 D BluetoothHeadset: Proxy object disconnected
08-29 08:22:18.895  3242  3256 D BluetoothHeadset: Proxy object disconnected
08-29 08:22:18.895  5804  5804 D A2dpService: Received stop request...Stopping profile...
08-29 08:22:18.895   927   927 D BluetoothHeadset: Proxy object disconnected
08-29 08:22:18.895   927   927 D BluetoothHeadset: Proxy object disconnected
08-29 08:22:18.895  5804  5919 D A2dpStateMachine: Exit Disconnected: -1
08-29 08:22:18.896   927   927 D BluetoothA2dp: Proxy object disconnected
08-29 08:22:18.897  5746  5746 D DockEventReceiver: finishStartingService: stopping service
08-29 08:22:18.898  5804  5804 D HidService: Received stop request...Stopping profile...
,08-29 08:22:18.898  5804  5804 D HidService: Stopping Bluetooth HidService
08-29 08:22:18.898  5746  5746 D HeadsetProfile: Bluetooth service disconnected
08-29 08:22:18.899  5746  5746 D BluetoothA2dp: Proxy object disconnected
08-29 08:22:18.899  5746  5746 D BluetoothInputDevice: Proxy object disconnected
08-29 08:22:18.899  5804  5804 D HealthService: Received stop request...Stopping profile...
08-29 08:22:18.899  5746  5746 D HidProfile: Bluetooth service disconnected
08-29 08:22:18.899  3242  3242 D HeadsetProfile: Bluetooth service disconnected
08-29 08:22:18.901  5804  5804 D PanService: Received stop request...Stopping profile...
,08-29 08:22:18.902  5746  5746 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 08:22:18.902  5746  5746 D PanProfile: Bluetooth service disconnected
08-29 08:22:18.903  3242  3242 D BluetoothA2dp: Proxy object disconnected
08-29 08:22:18.903  3242  3242 D BluetoothInputDevice: Proxy object disconnected
08-29 08:22:18.903  3242  3242 D HidProfile: Bluetooth service disconnected
08-29 08:22:18.903  3242  3242 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 08:22:18.903  3242  3242 D PanProfile: Bluetooth service disconnected
08-29 08:22:18.904  5804  5804 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 08:22:18.904  5804  5804 D BluetoothMapService: stop()
08-29 08:22:18.904  5804  5804 D BluetoothMapAppObserver: deinitObservers()
08-29 08:22:18.904  5804  5804 D BluetoothMapAppObserver: removeReceiver()
08-29 08:22:18.905  3242  3242 D BluetoothMap: Proxy object disconnected
08-29 08:22:18.905  5746  5746 D BluetoothMap: Proxy object disconnected
08-29 08:22:18.905  3242  3242 D MapProfile: Bluetooth service disconnected
08-29 08:22:18.906  5746  5746 D MapProfile: Bluetooth service disconnected
08-29 08:22:18.906  5804  5804 D SapService: Received stop request...Stopping profile...
08-29 08:22:18.906  5804  5804 V SapService: stop()
,08-29 08:22:18.907  5804  5804 V BluetoothAdapterState: isTurningOff()=true
,08-29 08:22:18.907  5804  5804 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:18.907  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:18.907  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:18.908  5804  5804 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 08:22:18.908  5804  5804 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 08:22:18.909  5804  5911 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:22:18.909  5804  5911 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:22:18.909  5804  5911 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:22:18.909  5804  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 08:22:18.910  5804  5804 V BluetoothAdapterState: isTurningOff()=true
08-29 08:22:18.910  5804  5902 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 08:22:18.910  5804  5804 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:18.910  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:18.910  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:22:18.911  5804  5804 V BluetoothAdapterState: isTurningOff()=true
,08-29 08:22:18.912  5804  5804 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:18.912  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:18.912  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:18.912  5804  5804 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 08:22:18.912  5804  5804 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 08:22:18.912  5804  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 08:22:18.912  5804  5804 V BluetoothAdapterState: isTurningOff()=true
08-29 08:22:18.912  5804  5911 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 08:22:18.912  5804  5804 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:18.912  5804  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 08:22:18.912  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:18.912  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:18.912  5804  5911 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:22:18.912  5804  5804 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 08:22:18.912  5804  5911 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:22:18.912  5804  5911 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:22:18.912  5804  5911 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:22:18.912  5804  5911 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:22:18.913  5804  5804 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 08:22:18.913  5804  5902 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 08:22:18.913  5804  5804 V BluetoothAdapterState: isTurningOff()=true
08-29 08:22:18.913  5804  5804 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:18.913  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:18.913  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:18.913  3710  3710 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 08:22:18.913  5804  5804 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 08:22:18.913  5804  5804 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 08:22:18.914  5804  5804 D BluetoothMapService: MAP Service closeService in
08-29 08:22:18.914  5804  5804 V BluetoothAdapterState: isTurningOff()=true
08-29 08:22:18.914  5804  5804 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:18.914  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:18.914  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:18.915  5804  5804 D BluetoothMapService: cleanup()
08-29 08:22:18.915  5804  5804 D BluetoothMapService: MAP Service closeService in
08-29 08:22:18.915  5804  5804 V BluetoothAdapterState: isTurningOff()=true
08-29 08:22:18.915  5804  5804 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:18.915  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:18.915  5804  5804 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:22:18.915  5804  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 08:22:18.915  5804  5898 D BluetoothAdapterProperties: Setting state to 15
08-29 08:22:18.915  5804  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 08:22:18.916  5804  5898 I BluetoothAdapterState: Entering BleOnState
,08-29 08:22:18.916  5746  5757 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 08:22:18.916  3242  3242 D BluetoothPbap: Proxy object disconnected
08-29 08:22:18.916  3242  3242 D PbapServerProfile: Bluetooth service disconnected
08-29 08:22:18.918  3242  3255 D BluetoothPan: onBluetoothStateChange on: false
08-29 08:22:18.919  5746  5756 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 08:22:18.920  3242  3256 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 08:22:18.920  5746  5757 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 08:22:18.921   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:22:18.921  5746  5756 D BluetoothPan: onBluetoothStateChange on: false
08-29 08:22:18.922  3242  3848 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 08:22:18.922   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:22:18.922   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 08:22:18.923  3242  3255 D BluetoothMap: onBluetoothStateChange: up=false
08-29 08:22:18.924  3242  3256 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:22:18.924   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:22:18.924  3242  3848 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 08:22:18.925  5746  5757 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:22:18.925  3648  3670 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:22:18.926  5746  5756 D BluetoothMap: onBluetoothStateChange: up=false
08-29 08:22:18.926  5804  5898 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 08:22:18.926  5804  5898 D BluetoothAdapterProperties: Setting state to 16
08-29 08:22:18.926  5804  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 08:22:18.927  5804  5898 D BluetoothAdapterProperties: onBleDisable
08-29 08:22:18.927  5804  5898 I BluetoothAdapterState: Entering PendingCommandState
08-29 08:22:18.928  5804  5899 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 08:22:18.928  5804  5902 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:22:18.930  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:18.930  5804  5911 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 08:22:18.930  5804  5911 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 08:22:18.930  5746  5746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 08:22:18.932  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:18.934  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:18.935  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:18.945  5746  5746 D DockEventReceiver: finishStartingService: stopping service
08-29 08:22:18.946  3710  3710 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:22:19.140  5804  5902 I bt_hci  : shut_down
,08-29 08:22:19.145  5804  5906 D bt_hwcfg: hw_epilog_process
,08-29 08:22:19.145  5804  5906 I bt_vendor: low_power_mode_cb
,08-29 08:22:19.148  5804  5906 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 08:22:19.148  5804  5906 I bt_vendor: epilog_cb
08-29 08:22:19.148  5804  5906 I bt_hci  : epilog_finished_callback
,08-29 08:22:19.150  5804  5902 I bt_hci_h4: hal_close
,08-29 08:22:19.150  5804  5902 I bt_userial_vendor: device fd = 51 close
,08-29 08:22:19.262  5804  5899 D bt_stack_manager: event_shut_down_stack finished.
,08-29 08:22:19.263  5804  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 08:22:19.266  5804  5898 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 08:22:19.266  5804  5804 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 08:22:19.268  5804  5804 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 08:22:19.268  5804  5804 D BtGatt.GattService: stop()
,08-29 08:22:19.268  5804  5804 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 08:22:19.271  5804  5804 V BluetoothAdapterState: isTurningOff()=false
08-29 08:22:19.271  5804  5804 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:19.272  5804  5804 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:19.272  5804  5804 V BluetoothAdapterState: isBleTurningOff()=true
08-29 08:22:19.272  5804  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 08:22:19.272  5804  5898 D BluetoothAdapterProperties: Setting state to 10
08-29 08:22:19.273  5804  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 08:22:19.275  5804  5898 I BluetoothAdapterState: Entering OffState
08-29 08:22:19.275   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 08:22:19.287  5804  5804 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 08:22:19.287  5804  5804 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 08:22:19.287  5804  5804 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 08:22:19.289  5804  5899 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 08:22:19.290  5804  5899 D bt_stack_manager: event_clean_up_stack finished.
,08-29 08:22:19.292  5804  5804 I art     : System.exit called, status: 0
08-29 08:22:19.292  5804  5804 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 08:22:19.320   927  3677 I ActivityManager: Process com.android.bluetooth (pid 5804) has died
,08-29 08:22:21.863  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:22:21.864  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:22:22.979   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:22:23.980   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:22:24.870  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:22:24.870  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef4126e added. We now have 6 listener(s)
,08-29 08:22:24.871  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:22:24.875  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:22:24.875  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a9d8d0f added. We now have 7 listener(s)
08-29 08:22:24.875  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:22:24.877  5694  5740 I System.out: IsBluetoothEnabled
,08-29 08:22:24.886  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:24.914   927   944 I ActivityManager: Start proc 5946:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 08:22:24.981   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:22:24.992  5946  5946 D AdapterServiceConfig: Adding HeadsetService
,08-29 08:22:24.992  5946  5946 D AdapterServiceConfig: Adding A2dpService
08-29 08:22:24.992  5946  5946 D AdapterServiceConfig: Adding HidService
08-29 08:22:24.992  5946  5946 D AdapterServiceConfig: Adding HealthService
08-29 08:22:24.993  5946  5946 D AdapterServiceConfig: Adding PanService
08-29 08:22:24.993  5946  5946 D AdapterServiceConfig: Adding GattService
08-29 08:22:24.993  5946  5946 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 08:22:24.993  5946  5946 D AdapterServiceConfig: Adding SapService
,08-29 08:22:25.003   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a084f96:true
,08-29 08:22:25.003  5946  5946 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 08:22:25.006  5946  5946 I bt_bluedroid: init
,08-29 08:22:25.006  5946  5958 I BluetoothAdapterState: Entering OffState
,08-29 08:22:25.008  5946  5959 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 08:22:25.009  5946  5959 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 08:22:25.009  5946  5959 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 08:22:25.009  5946  5959 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 08:22:25.009  5946  5946 I bt_bluedroid: get_profile_interface socket
,08-29 08:22:25.011  5946  5962 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 08:22:25.012  5946  5946 I bt_bluedroid: get_profile_interface sdp
08-29 08:22:25.012  5946  5962 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 08:22:25.015  5946  5956 I bt_bluedroid: config_hci_snoop_log
,08-29 08:22:25.016   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 08:22:25.020  5946  5958 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 08:22:25.021  5946  5958 D BluetoothAdapterProperties: Setting state to 14
08-29 08:22:25.021  5946  5958 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-29 08:22:25.022  5946  5958 D BluetoothBondStateMachine: make
,08-29 08:22:25.024  5946  5963 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 08:22:25.026  5946  5958 I BluetoothAdapterState: Entering PendingCommandState
,08-29 08:22:25.027  5946  5946 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 08:22:25.030  5946  5946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
08-29 08:22:25.030  5946  5946 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 08:22:25.031  5946  5946 D BtGatt.GattService: Received start request. Starting profile...
08-29 08:22:25.031  5946  5946 D BtGatt.GattService: start()
08-29 08:22:25.031  5946  5946 I bt_bluedroid: get_profile_interface gatt
,08-29 08:22:25.032  5946  5946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
,08-29 08:22:25.033  5946  5946 D BtGatt.AdvertiseManager: advertise manager created
,08-29 08:22:25.038  5946  5946 V BluetoothAdapterState: isTurningOff()=false
,08-29 08:22:25.038  5946  5946 V BluetoothAdapterState: isTurningOn()=false
08-29 08:22:25.038  5946  5946 V BluetoothAdapterState: isBleTurningOn()=true
08-29 08:22:25.038  5946  5946 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:25.038  5946  5958 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 08:22:25.038  5946  5958 I bt_bluedroid: enable
08-29 08:22:25.039  5946  5959 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 08:22:25.039  5946  5959 I bt_hci  : start_up
,08-29 08:22:25.045  5946  5959 I bt_vendor: alloc value 0xf40c704d
08-29 08:22:25.045  5946  5959 I bt_vendor: init
,08-29 08:22:25.045  5946  5959 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 08:22:25.045  5946  5959 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 08:22:25.168  5946  5959 D bt_hci  : start_up starting async portion
,08-29 08:22:25.169  5946  5966 I bt_hci  : event_finish_startup
08-29 08:22:25.169  5946  5966 I bt_hci_h4: hal_open
,08-29 08:22:25.169  5946  5966 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
08-29 08:22:25.154  5967  5967 W irq/448-msm_hs_: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 08:22:25.173  5946  5966 I bt_userial_vendor: device fd = 51 open
,08-29 08:22:25.188  5946  5966 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 08:22:25.190  5946  5966 D bt_hwcfg: Chipset BCM4358A3
,08-29 08:22:25.191  5946  5966 D bt_hwcfg: Target name = [BCM4358A3]
08-29 08:22:25.191  5946  5966 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 08:22:25.591  5946  5966 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 08:22:25.591  5946  5966 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 08:22:25.591  5946  5966 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 08:22:25.725  5946  5966 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-29 08:22:25.725  5946  5966 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 08:22:25.728  5946  5966 I bt_hwcfg: vendor lib fwcfg completed
,08-29 08:22:25.728  5946  5966 I bt_vendor: firmware callback
08-29 08:22:25.728  5946  5966 I bt_hci  : firmware_config_callback
,08-29 08:22:25.737  5946  5969 I bt_btu  : btu_task pending for preload complete event
,08-29 08:22:25.737  5946  5969 I bt_btu_task: Bluetooth chip preload is complete
08-29 08:22:25.737  5946  5969 I bt_btu  : btu_task received preload complete event
,08-29 08:22:25.743  5946  5969 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 08:22:25.743  5946  5969 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 08:22:25.743  5946  5969 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 08:22:25.743  5946  5969 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 08:22:25.743  5946  5969 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 08:22:25.743  5946  5969 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 08:22:25.743  5946  5969 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 08:22:25.744  5946  5969 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 08:22:25.744  5946  5969 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 08:22:25.744  5946  5969 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 08:22:25.744  5946  5969 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 08:22:25.744  5946  5969 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 08:22:25.744  5946  5969 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 08:22:25.744  5946  5969 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 08:22:25.744  5946  5969 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 08:22:25.826  5946  5969 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4044c99
08-29 08:22:25.826  5946  5969 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4044c99 
,08-29 08:22:25.842  5946  5962 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 08:22:25.843  5946  5962 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 08:22:25.844  5946  5962 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 08:22:25.846  5946  5962 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 08:22:25.849  5946  5962 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:22:25.849  5946  5962 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 08:22:25.849  5946  5962 D bt_hci  : do_postload posting postload work item
,08-29 08:22:25.849  5946  5966 I bt_hci  : event_postload
08-29 08:22:25.850  5946  5966 I bt_vendor: sco_config_cb
08-29 08:22:25.850  5946  5966 I bt_hci  : sco_config_callback postload finished.
08-29 08:22:25.854  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:25.857  5946  5962 D bt_bte_conf: Device ID record 1 : primary
08-29 08:22:25.857  5946  5962 D bt_bte_conf:   vendorId            = 000f
08-29 08:22:25.857  5946  5962 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 08:22:25.857  5946  5962 D bt_bte_conf:   product             = 1200
08-29 08:22:25.857  5946  5962 D bt_bte_conf:   version             = 1436
08-29 08:22:25.857  5946  5962 D bt_bte_conf:   clientExecutableURL = 
08-29 08:22:25.858  5946  5962 D bt_bte_conf:   serviceDescription  = 
,08-29 08:22:25.858  5946  5962 D bt_bte_conf:   documentationURL    = 
08-29 08:22:25.858  5946  5962 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 08:22:25.858  5946  5959 D bt_stack_manager: event_start_up_stack finished
08-29 08:22:25.858  5946  5966 I bt_vendor: low_power_mode_cb
08-29 08:22:25.859  5946  5958 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 08:22:25.859  5946  5958 D BluetoothAdapterProperties: Setting state to 15
08-29 08:22:25.859  5946  5958 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 08:22:25.860  5946  5958 I BluetoothAdapterState: Entering BleOnState
,08-29 08:22:25.864  5946  5958 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 08:22:25.864  5946  5958 D BluetoothAdapterProperties: Setting state to 11
,08-29 08:22:25.864  5946  5958 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 08:22:25.869  5946  5946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
08-29 08:22:25.870  5946  5946 D HeadsetService: Received start request. Starting profile...
,08-29 08:22:25.873  5946  5946 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 08:22:25.873  5946  5946 D HeadsetStateMachine: make
,08-29 08:22:25.876  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:25.887  5946  5946 D HeadsetStateMachine: max_hf_connections = 1
,08-29 08:22:25.888  5946  5946 I bt_bluedroid: get_profile_interface handsfree
,08-29 08:22:25.888  5946  5962 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-29 08:22:25.888  5946  5962 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,08-29 08:22:25.889  5946  5958 I BluetoothAdapterState: Entering PendingCommandState
08-29 08:22:25.892  5946  5946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
08-29 08:22:25.892  5946  5946 D A2dpService: Received start request. Starting profile...
08-29 08:22:25.893  5946  5946 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 08:22:25.893  5946  5946 I bt_bluedroid: get_profile_interface avrcp
,08-29 08:22:25.899  5946  5946 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 08:22:25.900  5946  5946 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 08:22:25.900  5946  5946 D A2dpStateMachine: make
08-29 08:22:25.901  5946  5946 I bt_bluedroid: get_profile_interface a2dp
,08-29 08:22:25.901  5946  5962 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 08:22:25.903  5946  5977 D A2dpStateMachine: Enter Disconnected: -2
,08-29 08:22:25.903  5946  5946 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 08:22:25.904  5946  5946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
,08-29 08:22:25.905  5946  5946 D HidService: Received start request. Starting profile...
,08-29 08:22:25.905  5946  5946 I bt_bluedroid: get_profile_interface hidhost
08-29 08:22:25.905  5946  5946 D HidService: setHidService(): set to: null
08-29 08:22:25.905  5946  5962 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40262d9
08-29 08:22:25.905  5946  5962 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 08:22:25.907  5946  5946 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 08:22:25.908  5946  5946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
08-29 08:22:25.908  5946  5946 D HealthService: Received start request. Starting profile...
08-29 08:22:25.908  3710  3710 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:22:25.910  5946  5946 I bt_bluedroid: get_profile_interface health
,08-29 08:22:25.911  5946  5946 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 08:22:25.912  5946  5946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
08-29 08:22:25.912  5946  5946 D PanService: Received start request. Starting profile...
08-29 08:22:25.913  5946  5946 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 08:22:25.913  5946  5946 I bt_bluedroid: get_profile_interface pan
08-29 08:22:25.913  5946  5962 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 08:22:25.916  5946  5946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
,08-29 08:22:25.917  5946  5946 D BluetoothMapService: Received start request. Starting profile...
,08-29 08:22:25.917  5946  5946 D BluetoothMapService: start()
08-29 08:22:25.920  5946  5946 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 08:22:25.920  5946  5946 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 08:22:25.920  5946  5946 D BluetoothMapAppObserver: createReceiver()
08-29 08:22:25.922  5946  5946 D BluetoothMapAppObserver: initObservers()
08-29 08:22:25.922  5946  5946 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 08:22:25.928  5946  5946 V SapService: SapBinder()
,08-29 08:22:25.928  5946  5946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
08-29 08:22:25.929  5946  5946 D SapService: Received start request. Starting profile...
08-29 08:22:25.929  5946  5946 V SapService: start()
,08-29 08:22:25.930  5946  5946 V BluetoothAdapterState: isTurningOff()=false
08-29 08:22:25.930  5946  5946 V BluetoothAdapterState: isTurningOn()=true
08-29 08:22:25.930  5946  5946 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:25.930  5946  5946 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:25.930  5946  5975 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 08:22:25.930  5946  5946 V BluetoothAdapterState: isTurningOff()=false
,08-29 08:22:25.930  5946  5946 V BluetoothAdapterState: isTurningOn()=true
08-29 08:22:25.930  5946  5946 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:25.930  5946  5946 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:25.930  5946  5946 V BluetoothAdapterState: isTurningOff()=false
08-29 08:22:25.930  5946  5946 V BluetoothAdapterState: isTurningOn()=true
08-29 08:22:25.931  5946  5946 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:25.931  5946  5946 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:22:25.931  5946  5946 V BluetoothAdapterState: isTurningOff()=false
08-29 08:22:25.931  5946  5946 V BluetoothAdapterState: isTurningOn()=true
08-29 08:22:25.931  5946  5946 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:25.931  5946  5946 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:25.931  5946  5946 V BluetoothAdapterState: isTurningOff()=false
08-29 08:22:25.931  5946  5946 V BluetoothAdapterState: isTurningOn()=true
08-29 08:22:25.932  5946  5946 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:25.932  5946  5946 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:25.932  5946  5946 V BluetoothAdapterState: isTurningOff()=false
08-29 08:22:25.932  5946  5946 V BluetoothAdapterState: isTurningOn()=true
08-29 08:22:25.932  5946  5946 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:25.932  5946  5946 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:25.932  5946  5946 V BluetoothAdapterState: isTurningOff()=false
08-29 08:22:25.932  5946  5946 V BluetoothAdapterState: isTurningOn()=true
08-29 08:22:25.932  5946  5946 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:22:25.933  5946  5946 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:22:25.933  5946  5958 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-29 08:22:25.933  5946  5958 D BluetoothAdapterProperties: ScanMode =  20
08-29 08:22:25.933  5946  5958 D BluetoothAdapterProperties: State =  11
,08-29 08:22:25.933  5946  5958 D BluetoothAdapterProperties: Setting state to 12
08-29 08:22:25.933  5946  5958 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 08:22:25.934  5946  5958 I BluetoothAdapterState: Entering OnState
08-29 08:22:25.935  5746  5757 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 08:22:25.935  5946  5962 D BluetoothAdapterProperties: Scan Mode:21
08-29 08:22:25.936  5946  5962 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 08:22:25.938  3242  3848 D BluetoothPan: onBluetoothStateChange on: true
,08-29 08:22:25.939  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:25.939  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:25.939  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:25.939  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:22:25.939  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:25.939  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:25.939  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:25.939  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:22:25.940  5746  5941 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:22:25.941  5746  5746 D BluetoothInputDevice: Proxy object connected
08-29 08:22:25.941  3242  3242 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 08:22:25.941  3242  3242 D PanProfile: Bluetooth service connected
08-29 08:22:25.942  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:25.942  3242  3256 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 08:22:25.944  5746  5756 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 08:22:25.945   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:22:25.946  5746  5941 D BluetoothPan: onBluetoothStateChange on: true
08-29 08:22:25.947  3242  3848 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 08:22:25.947  5946  5946 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 08:22:25.948  5946  5946 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 08:22:25.949  3242  3242 D BluetoothInputDevice: Proxy object connected
08-29 08:22:25.949  3242  3242 D HidProfile: Bluetooth service connected
08-29 08:22:25.949   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:22:25.949   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:22:25.949  5946  5946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:22:25.950   927   927 D BluetoothA2dp: Proxy object connected
08-29 08:22:25.950  3242  3256 D BluetoothMap: onBluetoothStateChange: up=true
08-29 08:22:25.951  5946  5946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:22:25.952  3242  3848 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:22:25.952   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:22:25.952  3242  3255 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:22:25.952  5946  5946 D ObexServerSockets: Succeed to create listening sockets 
08-29 08:22:25.952  5946  5946 D ObexServerSockets0: startAccept()
08-29 08:22:25.952  5946  5946 D ObexServerSockets0: prepareForNewConnect()
08-29 08:22:25.954  3242  3242 D BluetoothA2dp: Proxy object connected
08-29 08:22:25.954  5746  5756 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:22:25.954  3648  3667 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 08:22:25.955  5746  5757 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 08:22:25.955  5946  5946 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 08:22:25.955  5946  5946 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 08:22:25.956  5946  5982 D ObexServerSockets0: Accepting socket connection...
08-29 08:22:25.956  5946  5983 D ObexServerSockets0: Accepting socket connection...
08-29 08:22:25.958  3242  3242 D BluetoothMap: Proxy object connected
08-29 08:22:25.958  3242  3242 D MapProfile: Bluetooth service connected
08-29 08:22:25.958  3242  3242 D BluetoothMap: getConnectedDevices()
08-29 08:22:25.941  5746  5746 D HidProfile: Bluetooth service connected
08-29 08:22:25.959   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 08:22:25.961  5946  5946 D BluetoothMapService: onReceive
08-29 08:22:25.961  5946  5946 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 08:22:25.961  5946  5946 D BluetoothMapService: STATE_ON
08-29 08:22:25.961  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:25.962  5746  5746 D BluetoothA2dp: Proxy object connected
,08-29 08:22:25.964  5746  5746 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 08:22:25.964  5746  5746 D PanProfile: Bluetooth service connected
08-29 08:22:25.964  5746  5746 D BluetoothMap: Proxy object connected
08-29 08:22:25.964  5746  5746 D MapProfile: Bluetooth service connected
08-29 08:22:25.964  5746  5746 D BluetoothMap: getConnectedDevices()
08-29 08:22:25.964  5946  5986 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:22:25.965  5946  5986 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 08:22:25.965  5946  5986 D BluetoothSdpJni: SDP Create record success - handle: 1
08-29 08:22:25.970  5746  5746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 08:22:25.977  3710  3710 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:22:25.977  5746  5746 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:22:25.981   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:22:25.985  5746  5746 D BluetoothPbap: Proxy object connected
,08-29 08:22:25.985  5746  5746 D PbapServerProfile: Bluetooth service connected
,08-29 08:22:25.987  3242  3242 D BluetoothPbap: Proxy object connected
08-29 08:22:25.987  3242  3242 D PbapServerProfile: Bluetooth service connected
,08-29 08:22:25.990  5946  5946 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 08:22:25.990  5946  5946 D ObexServerSockets0: prepareForNewConnect()
,08-29 08:22:25.993  5946  5990 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:22:26.007  5946  5994 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:22:26.008  5946  5994 I BtOppRfcommListener: Accept thread started.
,08-29 08:22:26.048  3648  3670 D BluetoothHeadset: Proxy object connected
,08-29 08:22:26.049  5746  5756 D BluetoothHeadset: Proxy object connected
08-29 08:22:26.049   927   927 D BluetoothHeadset: Proxy object connected
08-29 08:22:26.049   927   944 D BluetoothHeadset: Proxy object connected
08-29 08:22:26.049  3242  3255 D BluetoothHeadset: Proxy object connected
08-29 08:22:26.049  3242  3242 D HeadsetProfile: Bluetooth service connected
08-29 08:22:26.049   927   927 D BluetoothHeadset: Proxy object connected
08-29 08:22:26.049   927   927 D BluetoothHeadset: Proxy object connected
,08-29 08:22:26.051  5746  5746 D HeadsetProfile: Bluetooth service connected
08-29 08:22:26.052  3242  3256 D BluetoothHeadset: Proxy object connected
08-29 08:22:26.053  3242  3242 D HeadsetProfile: Bluetooth service connected
08-29 08:22:26.053   927   944 D BluetoothHeadset: Proxy object connected
,08-29 08:22:26.054  5746  5757 D BluetoothHeadset: Proxy object connected
,08-29 08:22:26.055  3648  3855 D BluetoothHeadset: Proxy object connected
08-29 08:22:26.055  5746  5746 D HeadsetProfile: Bluetooth service connected
,08-29 08:22:26.903  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:26.903  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:26.903  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:26.903  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:22:26.903  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:26.903  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:26.903  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:26.903  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:22:26.910  5694  5740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:22:26.912  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:26.913  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ea9d19c added. We now have 8 listener(s)
08-29 08:22:26.913  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:22:26.919   927   937 D WifiService: setWifiEnabled: false pid=5694, uid=10077
,08-29 08:22:26.919   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:22:26.928  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:26.929   927  3306 D WifiService: setWifiEnabled: true pid=5694, uid=10077
,08-29 08:22:26.929   927  3306 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:22:26.939   505   921 D SoftapController: Softap fwReload - Ok
,08-29 08:22:26.943   505   921 D CommandListener: Setting iface cfg
08-29 08:22:26.944   505   921 D CommandListener: Trying to bring down wlan0
,08-29 08:22:26.946   505   921 D CommandListener: Clearing all IP addresses on wlan0
,08-29 08:22:26.951   927  3073 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 08:22:26.982   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:22:27.562   927  3073 D wifi    : set interface wlan0 flags (UP)
,08-29 08:22:27.567   927  3073 I WifiHAL : Initializing wifi
08-29 08:22:27.567   927  3073 I WifiHAL : Creating socket
,08-29 08:22:27.572   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 08:22:27.576   927  3073 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-29 08:22:27.576   927  3073 D wifi    : Did set static halHandle = 0x7f870b4be0
08-29 08:22:27.576   927  3073 D wifi    : halHandle = 0x7f870b4be0, mVM = 0x7fa354d140, mCls = 0x20183e
08-29 08:22:27.576   927  3073 D wifi    : array field set
08-29 08:22:27.576   927  3073 I WifiNative-HAL: interface[0] = wlan0
08-29 08:22:27.578   927  5999 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547726511072
,08-29 08:22:27.578   927  5999 D wifi    : waitForHalEvents called, vm = 0x7fa354d140, obj = 0x20183e, env = 0x7f885abc00
,08-29 08:22:27.581   927  3073 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 08:22:27.582   927  3073 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-29 08:22:27.586  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:27.639  6000  6000 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 08:22:27.661  6000  6000 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 08:22:27.677  6000  6000 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 08:22:27.677  6000  6000 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 08:22:27.982   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 08:22:28.599   927  3073 D WifiConfigStore: Loading config and enabling all networks 
,08-29 08:22:28.606  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:28.606  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:28.606  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:28.606  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:28.606  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:28.606  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:28.606  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:28.606  5694  5694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:22:28.610  5694  5694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:28.611   927  3073 D WifiConfigStore: loaded 0 passpoint configs
,08-29 08:22:28.612   927  3073 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 08:22:28.612   927  3073 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 08:22:28.614   927  3073 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 08:22:28.614   927  3073 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 08:22:28.614   927  3073 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 08:22:28.617  4960  4960 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 08:22:28.617   927  3073 D WifiNative-HAL: Setting external_sim to 1
08-29 08:22:28.618   927  3073 D wifi    : setting dfs flag to true, 0x7f85176d60
08-29 08:22:28.618   927  3073 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 08:22:28.619   927  3073 D wifi    : setting scan oui 0x7f85176d60
08-29 08:22:28.619   927  3073 D WifiHAL : Sending mac address OUI
,08-29 08:22:28.634   927  3073 E native  : do suspend true
,08-29 08:22:28.640   927   927 D RttService: SCAN_AVAILABLE : 3
08-29 08:22:28.640   927  3073 D wifi    : android_net_wifi_setLinkLayerStats: 1
,08-29 08:22:28.640   505   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 08:22:28.640   927  3183 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:22:28.641   505   921 D CommandListener: Setting iface cfg
,08-29 08:22:28.646   927  3072 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '75 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 75 Failed to set address (No such device)'
,08-29 08:22:28.646   927  3072 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 08:22:28.654   927  3072 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 08:22:28.655   927  3072 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 08:22:28.664   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=196169 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=10 mControllerEnergyUsed=38 }
,08-29 08:22:28.949  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:22:28.949  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:28.949  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:28.949  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:28.949  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:28.949  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:28.949  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:28.949  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:22:28.953  5694  5740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:28.960  5694  5740 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 08:22:28.961  5694  5740 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 08:22:28.963  5694  5740 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e186362 Bundle[{}]
08-29 08:22:28.964  5694  5740 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 08:22:28.964  5694  5740 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 08:22:28.965  5694  5740 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 08:22:28.966  5694  5740 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 08:22:28.967  5694  5740 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 08:22:28.969  5694  5740 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 08:22:28.973  5694  5740 I System.out: Running OutgoingSocketThread
08-29 08:22:28.976  5694  6002 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 156)
,08-29 08:22:28.978  5694  6002 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48889
,08-29 08:22:28.978  5694  6002 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 08:22:29.976  5694  5740 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 157)
,08-29 08:22:29.977  5694  5740 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 157)
08-29 08:22:29.982  5694  5740 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 162)
08-29 08:22:29.983  5694  5740 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 08:22:29.983  5694  5740 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 163)
,08-29 08:22:29.990  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 08:22:29.991  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d3f7a5 added. We now have 2 listener(s)
,08-29 08:22:29.995  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 08:22:29.996  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:22:29.996  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:22:29.996  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:29.996  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c52e77a added. We now have 9 listener(s)
08-29 08:22:29.996  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:22:29.997  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:22:30.001  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:22:30.006  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:22:30.006  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:30.006  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:30.006  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:30.006  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:30.006  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:30.006  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:30.006  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:22:30.008  5694  5740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:30.008  5694  5740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:22:30.008  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:22:30.008  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@506b88 added. We now have 3 listener(s)
08-29 08:22:30.010  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:30.010  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:22:30.010  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:22:30.010  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:22:30.011  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:30.011  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6316921 added. We now have 10 listener(s)
,08-29 08:22:30.011  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:22:30.011  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:30.011  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:30.011  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:30.011  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:30.011  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.011  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:22:30.011  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:22:30.012  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d3f7a5 removed from the list
08-29 08:22:30.012  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:30.012  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:30.012  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c52e77a removed from the list
08-29 08:22:30.012  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:30.012  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:30.012  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.013  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:22:30.014  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:30.015  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:30.015  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:30.015  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c52e77a not in the list
,08-29 08:22:30.015  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.015  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:22:30.017  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 08:22:30.017  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:30.017  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:30.017  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6316921 removed from the list
,08-29 08:22:30.017  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:30.017  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.017  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:30.017  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 08:22:30.017  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@506b88 removed from the list
08-29 08:22:30.018  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:22:30.018  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1980146 added. We now have 2 listener(s)
08-29 08:22:30.020  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:22:30.020  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:22:30.020  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 08:22:30.020  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:30.020  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@400f07 added. We now have 9 listener(s)
08-29 08:22:30.020  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:22:30.021  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:22:30.025  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:22:30.029  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:22:30.029  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:30.029  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:30.029  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:30.029  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:30.029  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:30.029  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:30.029  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:22:30.030  5694  5740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:30.030  5694  5740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:22:30.031  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:22:30.031  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a765d added. We now have 3 listener(s)
08-29 08:22:30.032  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:30.032  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:22:30.032  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:22:30.032  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:22:30.032  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:30.032  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c2ebd2 added. We now have 10 listener(s)
08-29 08:22:30.033  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:22:30.033  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:22:30.033  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:22:30.033  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:22:30.033  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:22:30.033  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:22:30.033  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:30.036  5694  5740 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 08:22:30.036  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 08:22:30.040  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 08:22:30.041  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 08:22:30.041  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:22:30.044  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 08:22:30.044  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 08:22:30.044  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 08:22:30.045  5694  5740 D BluetoothAdapter: STATE_ON
,08-29 08:22:30.047  5946  5956 D BtGatt.GattService: registerClient() - UUID=8db9442b-e982-440e-a79b-f03ce2126e6e
,08-29 08:22:30.048  5946  5962 D BtGatt.GattService: onClientRegistered() - UUID=8db9442b-e982-440e-a79b-f03ce2126e6e, clientIf=5
,08-29 08:22:30.049  5694  5842 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 08:22:30.050  5946  5985 D BtGatt.GattService: start scan with filters
08-29 08:22:30.053  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 08:22:30.053  5946  5965 D BtGatt.ScanManager: handling starting scan
08-29 08:22:30.053  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 08:22:30.053  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:22:30.053  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:22:30.055  5946  5965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ac21fd6
,08-29 08:22:30.055  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:22:30.055  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 08:22:30.056  5694  5694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:22:30.057  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 08:22:30.059  5694  5740 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 08:22:30.059  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:30.059  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 08:22:30.059  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.059  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:22:30.059  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:22:30.059  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:22:30.059  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:22:30.059  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:22:30.059  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 08:22:30.059  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 08:22:30.062  5946  5962 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 08:22:30.062  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:22:30.063  5946  5965 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 08:22:30.060  5694  5740 D BluetoothAdapter: STATE_ON
,08-29 08:22:30.068  5946  5962 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 08:22:30.070  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.071  5946  5965 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:22:30.071  5946  5965 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 08:22:30.071  5946  5956 D BtGatt.GattService: stopScan() - queue size =1
,08-29 08:22:30.072  5946  5985 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 08:22:30.072  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:22:30.072  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:22:30.072  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 08:22:30.072  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 08:22:30.073  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 08:22:30.073  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:22:30.074  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:22:30.074  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:22:30.074  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 08:22:30.074  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:22:30.076  5694  5694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:22:30.076  5694  5694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:22:30.076  5694  5694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 08:22:30.077  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:30.078  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:22:30.078  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:30.078  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:30.078  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.078  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:22:30.078  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:22:30.078  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1980146 removed from the list
08-29 08:22:30.078  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:30.078  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@400f07 removed from the list
08-29 08:22:30.078  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:30.078  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:30.079  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.079  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:30.079  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:22:30.080  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:30.080  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:30.080  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@400f07 not in the list
08-29 08:22:30.080  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.080  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:30.080  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:30.081  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:30.081  5946  5962 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 08:22:30.081  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:30.081  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.081  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c2ebd2 removed from the list
08-29 08:22:30.081  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:22:30.081  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.081  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:30.081  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:22:30.081  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a765d removed from the list
08-29 08:22:30.081  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:22:30.082  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3ff31e added. We now have 2 listener(s)
08-29 08:22:30.083  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:22:30.083  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:22:30.083  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:22:30.083  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:30.083  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@481d7ff added. We now have 9 listener(s)
08-29 08:22:30.083  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:22:30.084  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:22:30.086  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:22:30.090  5946  5962 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 08:22:30.090  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:22:30.092  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:22:30.092  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:30.092  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:30.092  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:30.092  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:30.092  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:30.092  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:30.092  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:22:30.095  5694  5740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:22:30.095  5694  5740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:22:30.095  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:22:30.095  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66b1415 added. We now have 3 listener(s)
08-29 08:22:30.096  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:30.096  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:22:30.096  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:22:30.097  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:22:30.097  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:30.097  5946  5962 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 08:22:30.097  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.097  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f4232a added. We now have 10 listener(s)
08-29 08:22:30.097  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:22:30.097  5946  5965 D BtGatt.ScanManager: stopping BLe Batch
08-29 08:22:30.097  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:22:30.097  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:30.097  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:22:30.097  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:22:30.098  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:22:30.098  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:22:30.098  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 08:22:30.100  5694  5740 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 08:22:30.100  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 08:22:30.102  5946  5962 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 08:22:30.102  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.103  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 08:22:30.103  5946  5965 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 08:22:30.103  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 08:22:30.103  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:22:30.107  5946  5962 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 08:22:30.107  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 08:22:30.107  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.107  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 08:22:30.107  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 08:22:30.107  5694  5740 D BluetoothAdapter: STATE_ON
,08-29 08:22:30.109  5946  5957 D BtGatt.GattService: registerClient() - UUID=0619889a-657c-4834-8a95-1a641e06191c
08-29 08:22:30.110  5946  5962 D BtGatt.GattService: onClientRegistered() - UUID=0619889a-657c-4834-8a95-1a641e06191c, clientIf=5
08-29 08:22:30.110  5694  5842 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 08:22:30.110  5946  5985 D BtGatt.GattService: start scan with filters
,08-29 08:22:30.112  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 08:22:30.112  5946  5965 D BtGatt.ScanManager: handling starting scan
08-29 08:22:30.112  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 08:22:30.112  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:22:30.112  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:22:30.114  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 08:22:30.114  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 08:22:30.114  5694  5694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 08:22:30.115  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 08:22:30.117  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:22:30.117  5694  5740 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 08:22:30.117  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:30.117  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:30.117  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:30.117  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:30.117  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.117  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:22:30.117  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:22:30.117  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3ff31e removed from the list
08-29 08:22:30.117  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:30.117  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@481d7ff removed from the list
08-29 08:22:30.117  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:30.117  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:22:30.118  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.118  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 08:22:30.118  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.118  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:22:30.119  5946  5962 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 08:22:30.119  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:30.119  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.119  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:30.119  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:30.119  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@481d7ff not in the list
08-29 08:22:30.119  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:22:30.119  5946  5965 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 08:22:30.119  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:22:30.119  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:22:30.119  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth,.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:22:30.119  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 08:22:30.120  5694  5740 D BluetoothAdapter: STATE_ON
,08-29 08:22:30.120  5946  5985 D BtGatt.GattService: stopScan() - queue size =1
08-29 08:22:30.120  5946  5956 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:22:30.121  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:22:30.121  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:22:30.121  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 08:22:30.121  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 08:22:30.121  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 08:22:30.123  5946  5962 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-29 08:22:30.123  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.123  5946  5965 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:22:30.123  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:22:30.123  5946  5965 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 08:22:30.123  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:22:30.123  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:22:30.124  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:22:30.124  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:22:30.125  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:30.125  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:30.125  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:22:30.125  5694  5694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:22:30.125  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f4232a removed from the list
08-29 08:22:30.125  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:30.125  5694  5694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:22:30.125  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.125  5694  5694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:22:30.125  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:30.125  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:22:30.126  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66b1415 removed from the list
08-29 08:22:30.126  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:22:30.126  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0947f6 added. We now have 2 listener(s)
08-29 08:22:30.127  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:22:30.128  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:22:30.128  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:22:30.128  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:30.128  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@524c7f7 added. We now have 9 listener(s)
,08-29 08:22:30.128  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:22:30.128  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:22:30.130  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:22:30.132  5946  5962 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 08:22:30.132  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:22:30.132  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:22:30.132  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:30.132  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:30.132  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:30.132  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:30.132  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:30.132  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:30.132  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:22:30.134  5694  5740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:22:30.134  5694  5740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:22:30.134  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:22:30.134  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88ab0cd added. We now have 3 listener(s)
08-29 08:22:30.135  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:22:30.135  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 08:22:30.136  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:22:30.136  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:30.136  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79ed82 added. We now have 10 listener(s)
08-29 08:22:30.136  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:30.136  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:22:30.136  5946  5962 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 08:22:30.136  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.136  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 08:22:30.136  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:22:30.136  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:22:30.136  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:22:30.136  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:22:30.137  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:22:30.138  5694  5740 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 08:22:30.138  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 08:22:30.141  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 08:22:30.141  5946  5962 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 08:22:30.141  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.141  5946  5965 D BtGatt.ScanManager: stopping BLe Batch
08-29 08:22:30.142  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 08:22:30.142  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:22:30.146  5946  5962 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 08:22:30.146  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.146  5946  5965 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 08:22:30.151  5946  5962 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 08:22:30.151  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:22:30.152  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 08:22:30.152  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 08:22:30.152  5694  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 08:22:30.153  5694  5740 D BluetoothAdapter: STATE_ON
,08-29 08:22:30.155  5946  5957 D BtGatt.GattService: registerClient() - UUID=355dea72-14a8-4fb5-9520-2f95068167ec
,08-29 08:22:30.156  5946  5962 D BtGatt.GattService: onClientRegistered() - UUID=355dea72-14a8-4fb5-9520-2f95068167ec, clientIf=5
08-29 08:22:30.156  5694  5705 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 08:22:30.156  5946  5974 D BtGatt.GattService: start scan with filters
,08-29 08:22:30.158  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 08:22:30.158  5946  5965 D BtGatt.ScanManager: handling starting scan
08-29 08:22:30.158  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 08:22:30.158  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:22:30.158  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:22:30.160  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 08:22:30.160  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 08:22:30.160  5694  5694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:22:30.161  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 08:22:30.162  5946  5962 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 08:22:30.163  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.163  5946  5965 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 08:22:30.167  5946  5962 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-29 08:22:30.167  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.167  5946  5965 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:22:30.167  5946  5965 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 08:22:30.167  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:30.167  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:30.167  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:22:30.167  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:30.167  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.167  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:22:30.167  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:22:30.167  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0947f6 removed from the list
08-29 08:22:30.167  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:30.167  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@524c7f7 removed from the list
08-29 08:22:30.167  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:22:30.167  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:22:30.168  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.168  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 08:22:30.168  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.168  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:22:30.174  5946  5962 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 08:22:30.175  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.175  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:22:30.175  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:30.175  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:30.175  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@524c7f7 not in the list
,08-29 08:22:30.175  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:22:30.175  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:22:30.175  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:22:30.175  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:22:30.175  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 08:22:30.176  5694  5740 D BluetoothAdapter: STATE_ON
08-29 08:22:30.177  5946  5957 D BtGatt.GattService: stopScan() - queue size =1
,08-29 08:22:30.177  5946  5974 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 08:22:30.178  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:22:30.178  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:22:30.178  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 08:22:30.178  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 08:22:30.178  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 08:22:30.179  5946  5962 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 08:22:30.179  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.179  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:22:30.179  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:22:30.179  5694  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:22:30.179  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 08:22:30.180  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:22:30.181  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:30.181  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:30.181  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:30.181  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79ed82 removed from the list
08-29 08:22:30.181  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:30.181  5694  5694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 08:22:30.181  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.181  5694  5694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:22:30.181  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:30.181  5694  5694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:22:30.181  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:22:30.182  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88ab0cd removed from the list
08-29 08:22:30.182  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:22:30.182  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85d5fce added. We now have 2 listener(s)
08-29 08:22:30.183  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:22:30.183  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:22:30.183  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:22:30.184  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:22:30.184  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a46beef added. We now have 9 listener(s)
,08-29 08:22:30.184  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:22:30.184  5946  5962 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 08:22:30.184  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.184  5946  5965 D BtGatt.ScanManager: stopping BLe Batch
08-29 08:22:30.184  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 08:22:30.186  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:22:30.188  5694  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:22:30.188  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:22:30.188  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:22:30.188  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:22:30.188  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:22:30.188  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:22:30.188  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:22:30.188  5694  5740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:22:30.189  5946  5962 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 08:22:30.189  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.189  5946  5965 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 08:22:30.190  5694  5740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:22:30.190  5694  5740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:22:30.190  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:22:30.190  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2c85 added. We now have 3 listener(s)
08-29 08:22:30.191  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:22:30.191  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:22:30.191  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:22:30.191  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:22:30.192  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f3aada added. We now have 10 listener(s)
08-29 08:22:30.192  5694  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:22:30.192  5694  5740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:22:30.192  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:30.192  5694  5740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:22:30.192  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:30.192  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.192  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:22:30.192  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:22:30.192  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85d5fce removed from the list
08-29 08:22:30.192  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:30.192  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a46beef removed from the list
08-29 08:22:30.192  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:30.193  5946  5962 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 08:22:30.193  5946  5962 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:22:30.194  5694  5694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:22:30.194  5694  5740 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:22:30.194  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:30.194  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.194  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:22:30.196  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:22:30.196  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:30.196  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:30.196  5694  5740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a46beef not in the list
08-29 08:22:30.196  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:22:30.196  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:30.197  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:22:30.197  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:22:30.197  5694  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:22:30.197  5694  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f3aada removed from the list
08-29 08:22:30.197  5694  5740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:22:30.197  5694  5740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:22:30.197  5694  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:22:30.197  5694  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:22:30.197  5694  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2c85 removed from the list
08-29 08:22:30.198  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 08:22:30.198  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 08:22:30.198  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 08:22:30.198  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:22:30.198  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 08:22:30.198  5694  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 08:22:30.201  5694  6003 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: My test thread name)
08-29 08:22:30.201  5694  6003 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 170, thread name: My test thread name)
08-29 08:22:30.201  5694  6003 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 08:22:30.203  5694  6004 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: My test thread name)
08-29 08:22:30.203  5694  6004 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: My test thread name)
,08-29 08:22:30.203  5694  6004 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 08:22:30.205  5694  5740 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-29 08:22:30.205  5694  5740 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 08:22:30.205  5694  5740 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 08:22:30.206  5694  5740 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 08:22:30.206  5694  5740 D com.test.thalitest.ThaliTestRunner: Total duration: 23551 ms
08-29 08:22:30.207  5694  5740 I jxcore-log: *Native tests were executed*
08-29 08:22:30.207  5694  5740 I jxcore-log: 
08-29 08:22:30.207  5694  5740 I jxcore-log: Total number of executed tests:  80
08-29 08:22:30.207  5694  5740 I jxcore-log: 
08-29 08:22:30.207  5694  5740 I jxcore-log: Number of passed tests:  80
08-29 08:22:30.207  5694  5740 I jxcore-log: 
08-29 08:22:30.208  5694  5740 I jxcore-log: Number of failed tests:  0
08-29 08:22:30.208  5694  5740 I jxcore-log: 
08-29 08:22:30.208  5694  5740 I jxcore-log: Number of ignored tests:  0
08-29 08:22:30.208  5694  5740 I jxcore-log: 
08-29 08:22:30.208  5694  5740 I jxcore-log: Total duration:  23551
08-29 08:22:30.208  5694  5740 I jxcore-log: 
08-29 08:22:30.208  5694  5740 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 08:22:30.208  5694  5740 I jxcore-log: 
,08-29 08:22:30.211  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:22:30.211  5694  5740 I jxcore-log: 
08-29 08:22:30.213  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:22:30.213  5694  5740 I jxcore-log: 
08-29 08:22:30.214  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:22:30.214  5694  5740 I jxcore-log: 
08-29 08:22:30.215  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:22:30.215  5694  5740 I jxcore-log: 
08-29 08:22:30.216  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:22:30.216  5694  5740 I jxcore-log: 
08-29 08:22:30.217  5694  5694 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 08:22:30.217  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:22:30.217  5694  5740 I jxcore-log: 
08-29 08:22:30.219  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:22:30.219  5694  5740 I jxcore-log: 
08-29 08:22:30.221  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:22:30.221  5694  5740 I jxcore-log: 
08-29 08:22:30.221  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:22:30.221  5694  5740 I jxcore-log: 
08-29 08:22:30.222  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:22:30.222  5694  5740 I jxcore-log: 
08-29 08:22:30.222  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:22:30.222  5694  5740 I jxcore-log: 
08-29 08:22:30.223  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:22:30.223  5694  5740 I jxcore-log: 
08-29 08:22:30.224  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:22:30.224  5694  5740 I jxcore-log: 
08-29 08:22:30.225  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:22:30.225  5694  5740 I jxcore-log: 
08-29 08:22:30.226  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:22:30.226  5694  5740 I jxcore-log: 
08-29 08:22:30.227  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:22:30.227  5694  5740 I jxcore-log: 
08-29 08:22:30.227  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:22:30.227  5694  5740 I jxcore-log: 
08-29 08:22:30.228  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:22:30.228  5694  5740 I jxcore-log: 
08-29 08:22:30.229  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:22:30.229  5694  5740 I jxcore-log: 
08-29 08:22:30.229  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:22:30.229  5694  5740 I jxcore-log: 
08-29 08:22:30.230  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:22:30.230  5694  5740 I jxcore-log: 
08-29 08:22:30.231  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:22:30.231  5694  5740 I jxcore-log: 
08-29 08:22:30.231  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 08:22:30.231  5694  5740 I jxcore-log: 
08-29 08:22:30.232  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 08:22:30.232  5694  5740 I jxcore-log: 
08-29 08:22:30.233  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 08:22:30.233  5694  5740 I jxcore-log: 
08-29 08:22:30.233  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 08:22:30.233  5694  5740 I jxcore-log: 
08-29 08:22:30.234  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 08:22:30.234  5694  5740 I jxcore-log: 
08-29 08:22:30.235  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 08:22:30.235  5694  5740 I jxcore-log: 
08-29 08:22:30.235  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 08:22:30.235  5694  5740 I jxcore-log: 
,08-29 08:22:30.576  5694  5694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 08:22:30.581  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:22:30.581  5694  5740 I jxcore-log: 
,08-29 08:22:30.626  5694  5694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 08:22:30.631  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:22:30.631  5694  5740 I jxcore-log: 
,08-29 08:22:30.660  6005  6005 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 08:22:30.667  6005  6005 D AndroidRuntime: CheckJNI is OFF
,08-29 08:22:30.682  5694  5694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 08:22:30.685  5694  5740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:22:30.685  5694  5740 I jxcore-log: 
,08-29 08:22:30.696  6005  6005 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 08:22:30.727  6005  6005 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 08:22:30.742  6005  6005 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 08:22:30.749   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
08-29 08:22:30.750   927   940 I ActivityManager: Killing 5694:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,08-29 08:22:30.856   927  3668 D GraphicsStats: Buffer count: 2
08-29 08:22:30.857   927  3074 D WifiService: Client connection lost with reason: 4
,08-29 08:22:30.857   927  3306 I WindowState: WIN DEATH: Window{290ff90 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 08:22:30.894   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-29 08:22:30.895   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-29 08:22:30.895   927   951 I art     : Starting a blocking GC Explicit
,08-29 08:22:30.896   927   940 E ActivityManager: Failure starting process com.test.thalitest
08-29 08:22:30.896   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 08:22:30.896   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:22:30.896   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:22:30.896   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 08:22:30.896   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-29 08:22:30.897   927   940 I ActivityManager:   Force finishing activity ActivityRecord{acee765 u0 com.test.thalitest/.MainActivity t4}
,08-29 08:22:30.908   927   938 W ActivityManager: Spurious death for ProcessRecord{69539db 0:com.test.thalitest/u0a77}, curProc for 5694: null
,08-29 08:22:30.969   927   951 I art     : Explicit concurrent mark sweep GC freed 25367(1550KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 1.325ms total 73.585ms
,08-29 08:22:30.993   927   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 08:22:30.995  6005  6005 I art     : System.exit called, status: 0
,08-29 08:22:30.996  6005  6005 I AndroidRuntime: VM exiting with result code 0.
,08-29 08:22:31.011   927   951 I ActivityManager: Start proc 6015:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-29 08:22:31.011   927   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,08-29 08:22:31.016   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 08:22:31.020  5946  5946 D BluetoothMapAppObserver: onReceive
,08-29 08:22:31.020  5946  5946 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-29 08:22:31.028   927  3039 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 08:22:31.028  3571  4009 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 08:22:31.031  3519  3519 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 08:22:31.055  3519  6028 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 08:22:31.058  3519  6028 I Decoder : createOrResetDecoder
,08-29 08:22:31.072  3648  3648 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 08:22:31.079  5504  6030 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 08:22:31.080  3710  3710 I ConfigService: onCreate
,08-29 08:22:31.081   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 08:22:31.101  3519  6028 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 08:22:31.106  3710  3710 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-29 08:22:31.106  3710  3710 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-29 08:22:31.114    28    28 W kworker/2:1: type=1400 audit(0.0:73): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 08:22:31.121  3914  6035 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-29 08:22:31.122  3914  6035 D AccountUtils: Clearing selected account for com.test.thalitest
,08-29 08:22:31.114    28    28 W kworker/2:1: type=1400 audit(0.0:74): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 08:22:31.134    28    28 W kworker/2:1: type=1400 audit(0.0:75): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 08:22:31.169  3914  6035 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-29 08:22:31.176  3519  6028 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /system/app/LatinImeGoogle/LatinImeGoogle.apk (offset=3195532, length=4014912) with up to date LoudsLmContentVersion = 20150512
08-29 08:22:31.179  3519  6028 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-29 08:22:31.179  3519  6028 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-29 08:22:31.181  5504  6030 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
08-29 08:22:31.182  5504  6030 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 08:22:31.182  5504  6030 E AndroidRuntime: Process: android.process.acore, PID: 5504
08-29 08:22:31.182  5504  6030 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:22:31.182  5504  6030 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 08:22:31.187   927  6040 E DropBoxManagerService: Can't write: system_app_crash
08-29 08:22:31.187   927  6040 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-29 08:22:31.187   927  6040 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 08:22:31.187   927  6040 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 08:22:31.187   927  6040 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 08:22:31.187   927  6040 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 08:22:31.187   927  6040 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 08:22:31.187   927  6040 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 08:22:31.187   927  6040 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 08:22:31.187   927  6040 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 08:22:31.187   927  6040 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 08:22:31.187   927  6040 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 08:22:31.187   927  6040 E DropBoxManagerService: 	... 5 more
,08-29 08:22:31.194  3914  6035 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:22:31.194  3914  6035 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:22:31.194  3914  6035 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 08:22:31.196  3914  6035 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,08-29 08:22:31.204  5504  6030 I Process : Sending signal. PID: 5504 SIG: 9

```
