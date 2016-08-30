#### Test 8288334193c2946_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-30 06:30:52.145   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:30:52.617  5577  5577 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 06:30:52.623  5577  5577 D AndroidRuntime: CheckJNI is OFF
08-30 06:30:52.652  5577  5577 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 06:30:52.688  5577  5577 I Radio-JNI: register_android_hardware_Radio DONE
08-30 06:30:52.705  5577  5577 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 06:30:52.710   928  3556 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 06:30:52.750   928  3556 I ActivityManager: Start proc 5587:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-30 06:30:52.755  5577  5577 D AndroidRuntime: Shutting down VM
08-30 06:30:52.837  5587  5587 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-30 06:30:52.869  5587  5587 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 06:30:52.928  5587  5587 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 6898-6953)
08-30 06:30:52.928  5587  5587 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 06:30:52.966  5587  5587 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5f10961}
08-30 06:30:52.966  5587  5587 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 06:30:52.966  5587  5587 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 06:30:52.972  5587  5587 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 06:30:52.973  5587  5587 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 06:30:53.017  5587  5587 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 06:30:53.030  5587  5587 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 06:30:53.030  5587  5587 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 06:30:53.030  5587  5587 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-30 06:30:53.030  5587  5587 I Adreno  : Build Date                       : 10/21/15
08-30 06:30:53.030  5587  5587 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 06:30:53.030  5587  5587 I Adreno  : Local Branch                     : 
08-30 06:30:53.030  5587  5587 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-30 06:30:53.030  5587  5587 I Adreno  : Remote Branch                    : NONE
08-30 06:30:53.030  5587  5587 I Adreno  : Reconstruct Branch               : NOTHING
,08-30 06:30:53.085   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a7464fa:true
,08-30 06:30:53.134  5587  5587 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 06:30:53.145   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:30:53.147  5587  5587 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-30 06:30:53.187  5587  5624 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 06:30:53.199  5587  5611 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 06:30:53.233  5587  5624 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 06:30:53.321   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +532ms (total +596ms)
,08-30 06:30:53.342  5587  5587 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5587
,08-30 06:30:53.426  5587  5587 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 06:30:53.539  5587  5627 D jxcore_app_log: JniHelper::setJavaVM(0xf53bc000), pthread_self() = -561772240
,08-30 06:30:53.543  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 06:30:53.543  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 06:30:53.543  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 06:30:53.543  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 06:30:53.543  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 06:30:53.543  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9df9dff added. We now have 1 listener(s)
,08-30 06:30:53.545  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,08-30 06:30:53.546  5587  5627 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-30 06:30:53.546  5587  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 06:30:53.547  5587  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 06:30:53.549  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa9212a added. We now have 1 listener(s)
08-30 06:30:53.549  5587  5627 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 06:30:53.552   928  2886 D WifiService: New client listening to asynchronous messages
,08-30 06:30:53.552  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 06:30:53.552  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 06:30:53.552  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-30 06:30:53.552  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 06:30:53.552  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 06:30:53.554  5587  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:30:53.554  5587  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-30 06:30:53.558  5587  5627 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 06:30:53.558  5587  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:30:53.558  5587  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:30:53.558  5587  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:30:53.558  5587  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:30:53.558  5587  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:30:53.558  5587  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:30:53.558  5587  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:30:53.558  5587  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 06:30:53.558  5587  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 06:30:53.558  5587  5627 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 06:30:53.558  5587  5627 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 06:30:53.560  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:30:53.563  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:30:53.582  5587  5587 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 06:30:53.823  5587  5633 W jxcore-log: Initializing JXcore engine
08-30 06:30:53.823  5587  5633 W jxcore-log: JXcore engine is ready
,08-30 06:30:53.840  5633  5633 W Thread-57: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11646 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 06:30:53.840  5633  5633 W Thread-57: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[14365]" dev="sockfs" ino=14365 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 06:30:53.840  5633  5633 W Thread-57: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 06:30:53.840  5633  5633 W Thread-57: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[33077]" dev="sockfs" ino=33077 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 06:30:53.858  5587  5633 W jxcore-log: Starting JXcore engine
,08-30 06:30:53.908  5587  5633 W jxcore-log: Platform android
08-30 06:30:53.908  5587  5633 W jxcore-log: 
,08-30 06:30:53.908  5587  5633 W jxcore-log: Process ARCH arm
08-30 06:30:53.908  5587  5633 W jxcore-log: 
,08-30 06:30:54.002  5587  5633 I jxcore-log: JXcore Cordova bridge is ready!
08-30 06:30:54.002  5587  5633 I jxcore-log: 
,08-30 06:30:54.002  5587  5633 W jxcore-log: JXcore engine is started
,08-30 06:30:54.008  5587  5627 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 06:30:54.013  5587  5587 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 06:30:54.146   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:30:54.515   928  5166 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168540, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 06:30:55.147   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:30:56.148   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:30:57.148   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-30 06:31:00.533  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 06:31:00.533  5587  5633 I jxcore-log: 
,08-30 06:31:00.535  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 06:31:00.535  5587  5633 I jxcore-log: 
,08-30 06:31:00.539  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:31:00.539  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:00.539  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:00.539  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:00.539  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:31:00.539  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:00.539  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:31:00.539  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 06:31:00.540  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 06:31:00.541  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 06:31:00.541  5587  5633 I jxcore-log: 
,08-30 06:31:00.542  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 06:31:00.542  5587  5633 I jxcore-log: 
,08-30 06:31:00.896  5587  5633 I jxcore-log: Unit Test app is loaded
08-30 06:31:00.896  5587  5633 I jxcore-log: 
,08-30 06:31:00.900  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:31:00.900  5587  5633 I jxcore-log: 
,08-30 06:31:00.904  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 06:31:00.904  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d576c added. We now have 2 listener(s)
08-30 06:31:00.905  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 06:31:00.905  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 06:31:00.905  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 06:31:00.906  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 06:31:00.906  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd95135 added. We now have 2 listener(s)
,08-30 06:31:00.906  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 06:31:00.906  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 06:31:00.908  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 06:31:00.911  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:31:00.911  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:00.911  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:00.911  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:00.911  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:31:00.911  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:00.911  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:31:00.911  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 06:31:00.913  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 06:31:00.913  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 06:31:00.913  5587  5633 D ExecuteNativeTests: Running unit tests
,08-30 06:31:00.920  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:31:00.926  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:31:00.927  5587  5587 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 06:31:00.949  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 06:31:00.949  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b added. We now have 3 listener(s)
08-30 06:31:00.949  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 06:31:00.949  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 06:31:00.949  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 06:31:00.949  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 06:31:00.949  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 added. We now have 3 listener(s)
08-30 06:31:00.949  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 06:31:00.950  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 06:31:00.951  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:31:00.953  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:31:00.953  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:00.953  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:00.953  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:00.953  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:31:00.953  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:00.953  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:31:00.953  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 06:31:00.954  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:00.955  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 06:31:00.956  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 06:31:00.956  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 06:31:00.956  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 06:31:00.956  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 06:31:00.957  5587  5633 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 06:31:00.957  5587  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 06:31:00.957  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 06:31:00.957  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 06:31:00.957  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 06:31:00.957  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 06:31:00.957  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:00.958  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:00.958  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 06:31:00.958  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 06:31:00.958  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b removed from the list
08-30 06:31:00.958  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:00.958  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 removed from the list
08-30 06:31:00.961  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:00.961  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:00.961  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:00.962  5587  5633 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 06:31:00.963  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:00.963  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:00.963  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:00.963  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:00.963  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:00.963  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:00.963  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:00.963  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:00.963  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 06:31:00.966  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 06:31:00.967  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:00.967  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:00.967  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:00.967  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:00.967  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:00.967  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:00.967  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:00.967  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:00.967  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:00.968  5587  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
08-30 06:31:00.969  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:31:00.971  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:31:00.971  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:00.971  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:00.971  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:00.971  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:31:00.971  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:00.971  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:31:00.971  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 06:31:00.972  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:00.972  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 06:31:00.972  5587  5633 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-30 06:31:00.972  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-30 06:31:00.972  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 06:31:00.972  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 06:31:00.972  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 06:31:00.973  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 06:31:00.973  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 06:31:00.973  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 06:31:00.973  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 06:31:00.974  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 06:31:00.974  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 06:31:00.974  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:31:00.974  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 06:31:00.976  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 06:31:00.976  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 06:31:00.977  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:00.979  5587  5636 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 06:31:00.979  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:00.980  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 06:31:00.980  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 06:31:00.981  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 06:31:00.981  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 06:31:00.982  5587  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-30 06:31:00.982  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-30 06:31:00.982  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 06:31:00.982  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
08-30 06:31:00.983  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 06:31:00.983  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 06:31:00.983  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-30 06:31:00.983  5587  5633 D BluetoothAdapter: STATE_ON
08-30 06:31:00.986  4332  4595 D BtGatt.GattService: registerClient() - UUID=935925aa-8516-4be6-8605-634891b33a02
08-30 06:31:00.987  4332  4394 D BtGatt.GattService: onClientRegistered() - UUID=935925aa-8516-4be6-8605-634891b33a02, clientIf=5
08-30 06:31:00.988  5587  5597 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-30 06:31:00.990  4332  4398 D BtGatt.AdvertiseManager: message : 0
08-30 06:31:00.993  4332  4398 D BtGatt.AdvertiseManager: starting multi advertising
08-30 06:31:01.006  4332  4394 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
08-30 06:31:01.012  4332  4394 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
08-30 06:31:01.013  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-30 06:31:01.013  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 06:31:01.014  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 06:31:01.015  5587  5633 I io.jxcore.node.ConnectionHelper: start: OK
08-30 06:31:01.015  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 06:31:01.015  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-30 06:31:01.015  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 06:31:01.016  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-30 06:31:01.016  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-30 06:31:01.016  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-30 06:31:01.019  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-30 06:31:01.019  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 06:31:01.520  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 06:31:01.521  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 06:31:01.521  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 06:31:06.021  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-30 06:31:06.021  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
08-30 06:31:06.021  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 06:31:11.028  5587  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
08-30 06:31:11.028  5587  5633 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-30 06:31:11.028  5587  5633 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,08-30 06:31:11.028  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
08-30 06:31:11.029  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 06:31:11.029  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 06:31:11.030  5587  5633 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 06:31:11.725   928  5166 D NetlinkSocketObserver: NeighborEvent{elapsedMs=185751, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 06:31:16.037  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 06:31:16.037  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 06:31:16.037  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-30 06:31:16.037  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 06:31:16.038  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 06:31:16.038  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 06:31:16.038  5587  5636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 06:31:16.038  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:16.039  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 06:31:16.039  5587  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 06:31:16.039  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 06:31:16.039  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 06:31:16.039  5587  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-30 06:31:16.040  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 06:31:16.039  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 06:31:16.040  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 06:31:16.042  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 06:31:16.044  5587  5633 D BluetoothAdapter: STATE_ON
08-30 06:31:16.045  5587  5633 D BluetoothLeScanner: could not find callback wrapper
08-30 06:31:16.045  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 06:31:16.045  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-30 06:31:16.046  4332  4398 D BtGatt.AdvertiseManager: message : 1
08-30 06:31:16.048  4332  4398 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 06:31:16.059  4332  4394 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-30 06:31:16.059  4332  4394 D BtGatt.GattService: Client app is not null!
,08-30 06:31:16.060  4332  4595 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 06:31:16.061  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 06:31:16.062  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-30 06:31:16.062  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-30 06:31:16.062  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-30 06:31:16.062  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-30 06:31:16.064  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 06:31:16.064  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 06:31:16.065  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 06:31:16.065  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 06:31:16.067  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:16.067  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 06:31:16.067  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 06:31:16.067  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:16.067  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 06:31:16.067  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 06:31:16.069  5587  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 06:31:16.072  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 06:31:16.077  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:31:16.077  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:16.077  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:16.077  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:16.077  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:31:16.077  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:16.077  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:31:16.077  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 06:31:16.079  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:16.079  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 06:31:16.079  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 06:31:16.079  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 06:31:16.080  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 06:31:16.080  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:31:16.080  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 06:31:16.082  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:31:16.088  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 06:31:16.088  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 06:31:16.088  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:16.092  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 06:31:16.092  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 06:31:16.093  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 06:31:16.095  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 06:31:16.097  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-30 06:31:16.098  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 06:31:16.098  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 06:31:16.098  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 06:31:16.099  5587  5633 D BluetoothAdapter: STATE_ON
,08-30 06:31:16.102  4332  4346 D BtGatt.GattService: registerClient() - UUID=744a7e7c-90fc-43ce-994e-d839304d13f2
,08-30 06:31:16.103  4332  4394 D BtGatt.GattService: onClientRegistered() - UUID=744a7e7c-90fc-43ce-994e-d839304d13f2, clientIf=5
,08-30 06:31:16.104  5587  5597 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 06:31:16.105  4332  4577 D BtGatt.GattService: start scan with filters
08-30 06:31:16.109  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 06:31:16.109  4332  4399 D BtGatt.ScanManager: handling starting scan
08-30 06:31:16.109  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 06:31:16.109  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 06:31:16.109  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 06:31:16.112  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 06:31:16.113  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 06:31:16.113  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 06:31:16.114  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 06:31:16.114  4332  4399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
08-30 06:31:16.116  5587  5633 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 06:31:16.120  4332  4394 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 06:31:16.120  4332  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 06:31:16.121  4332  4399 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 06:31:16.126  4332  4394 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-30 06:31:16.126  4332  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 06:31:16.126  4332  4399 D BtGatt.ScanManager: Starting BLE batch scan
08-30 06:31:16.127  4332  4399 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 06:31:16.135  4332  4394 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 06:31:16.136  4332  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 06:31:16.141  4332  4394 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 06:31:16.141  4332  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 06:31:16.614  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-30 06:31:16.614  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 06:31:16.615  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 06:31:17.149   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:31:18.150   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:31:19.151   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:31:20.152   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:31:21.117  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 06:31:21.117  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 06:31:21.117  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 06:31:21.118  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:21.118  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 06:31:21.118  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 06:31:21.118  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 06:31:21.118  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 06:31:21.118  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 06:31:21.119  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 06:31:21.119  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 06:31:21.123  5587  5633 D BluetoothAdapter: STATE_ON
,08-30 06:31:21.125  4332  4577 D BtGatt.GattService: stopScan() - queue size =1
,08-30 06:31:21.127  4332  4595 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 06:31:21.128  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 06:31:21.129  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 06:31:21.129  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 06:31:21.129  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 06:31:21.129  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 06:31:21.132  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 06:31:21.133  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 06:31:21.133  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 06:31:21.133  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 06:31:21.135  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 06:31:21.136  4332  4332 D BtGatt.ScanManager: awakened up at time 195161
,08-30 06:31:21.138  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 06:31:21.138  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 06:31:21.138  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 06:31:21.144  4332  4394 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,08-30 06:31:21.144  4332  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 06:31:21.145  4332  4399 D BtGatt.ScanManager: stopping BLe Batch
,08-30 06:31:21.153  4332  4394 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 06:31:21.153  4332  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 06:31:21.153   537   537 I ServiceManager: Waiting for service AtCmdFwd...
08-30 06:31:21.153  4332  4399 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 06:31:21.174  4332  4394 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-30 06:31:21.174  4332  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 06:31:21.175  4332  4394 D BtGatt.GattService: current time is 195200997528
08-30 06:31:21.175  4332  4394 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -78, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -77, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -77, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -77, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -90, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -83, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-30 06:31:21.177  4332  4394 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 06:31:21.177  4332  4394 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 06:31:21.177  4332  4394 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 06:31:21.178  4332  4394 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 06:31:21.178  4332  4394 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 06:31:21.178  4332  4394 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 06:31:21.640  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 06:31:21.640  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 06:31:21.640  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 06:31:22.154   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-30 06:31:26.139  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 06:31:26.139  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 06:31:26.139  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
08-30 06:31:26.140  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:26.140  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:26.140  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:26.140  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:26.140  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.144  5587  5633 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 06:31:26.146  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:26.146  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.147  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.147  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
,08-30 06:31:26.147  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:26.147  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:26.147  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:26.148  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.148  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.151  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 06:31:26.151  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:26.151  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.151  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.152  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:26.152  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 06:31:26.152  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:26.152  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:26.152  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.152  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:31:26.156  5587  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 06:31:26.156  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:26.157  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 06:31:26.157  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.157  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:26.157  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:26.157  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:26.157  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:26.157  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.157  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.158  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 06:31:26.158  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:26.159  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.159  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.159  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
,08-30 06:31:26.159  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:26.159  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:26.159  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:26.159  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.159  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.160  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 06:31:26.160  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 06:31:26.160  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 06:31:26.160  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 06:31:26.160  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 06:31:26.160  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 06:31:26.161  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 06:31:26.161  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 06:31:26.161  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 06:31:26.161  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:26.161  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.161  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.161  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:26.161  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:26.161  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:26.161  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:26.161  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.162  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.163  5587  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 06:31:26.163  5587  5633 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 06:31:26.163  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 06:31:26.167  5587  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 06:31:26.168  5587  5633 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 06:31:26.168  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-30 06:31:26.168  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 06:31:26.168  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 06:31:26.168  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 06:31:26.168  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 06:31:26.168  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 06:31:26.168  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 06:31:26.168  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 06:31:26.168  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 06:31:26.169  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 06:31:26.169  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 06:31:26.169  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 06:31:26.169  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 06:31:26.169  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 06:31:26.169  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 06:31:26.169  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 06:31:26.169  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 06:31:26.169  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 06:31:26.169  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 06:31:26.169  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 06:31:26.169  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 06:31:26.170  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 06:31:26.170  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 06:31:26.170  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 06:31:26.170  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-30 06:31:26.170  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 06:31:26.170  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 06:31:26.170  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 06:31:26.170  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 06:31:26.170  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 06:31:26.170  5587  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 06:31:26.171  5587  5633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 06:31:26.171  5587  5633 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 06:31:26.171  5587  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 06:31:26.171  5587  5633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 06:31:26.172  5587  5633 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 06:31:26.172  5587  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 06:31:26.172  5587  5633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 06:31:26.172  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-30 06:31:26.179  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-30 06:31:26.181  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 06:31:26.181  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-30 06:31:26.182  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 06:31:26.183  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 06:31:26.183  5587  5633 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 06:31:26.183  5587  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 06:31:26.183  5587  5633 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 06:31:26.184  5587  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 122)
08-30 06:31:26.185  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:26.185  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.185  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.185  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-30 06:31:26.186  5587  5640 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 06:31:26.186  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:26.186  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:26.186  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:26.186  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:26.186  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.187  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.187  5587  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 122
08-30 06:31:26.187  5587  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 122)
08-30 06:31:26.187  5587  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 122)
08-30 06:31:26.187  5587  5633 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 06:31:26.188  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:26.188  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.188  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.188  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:26.188  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:26.188  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:26.189  5587  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 122)
08-30 06:31:26.189  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:26.189  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.189  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.190  5587  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 06:31:26.190  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:26.190  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.190  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.190  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:26.190  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:26.190  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thalip,roject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:26.190  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:26.190  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.190  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.191  5587  5633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 06:31:26.191  5587  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 06:31:26.191  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 06:31:26.191  5587  5633 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 06:31:26.191  5587  5633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 06:31:26.191  5587  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 06:31:26.192  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 06:31:26.192  5587  5633 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 06:31:26.192  5587  5633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 06:31:26.192  5587  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 06:31:26.192  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 06:31:26.193  5587  5633 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 06:31:26.193  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:26.193  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.193  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:26.193  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:26.194  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:26.194  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:26.195  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:26.195  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:26.195  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:31:26.198  5587  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
08-30 06:31:26.200  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:31:26.204  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:31:26.204  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:26.204  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:26.204  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:26.204  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:31:26.204  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:26.204  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:31:26.204  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 06:31:26.206  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:26.206  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 06:31:26.206  5587  5633 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
08-30 06:31:26.206  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
08-30 06:31:26.207  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 06:31:26.207  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 06:31:26.207  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 06:31:26.207  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 06:31:26.208  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 06:31:26.208  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 06:31:26.208  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 06:31:26.208  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 06:31:26.209  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 06:31:26.209  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:31:26.209  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 06:31:26.210  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:26.210  5587  5642 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 06:31:26.212  5587  5642 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-30 06:31:26.214  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 06:31:26.214  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 06:31:26.214  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:26.214  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-30 06:31:26.218  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 06:31:26.218  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 06:31:26.218  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 06:31:26.220  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-30 06:31:26.220  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 06:31:26.220  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
08-30 06:31:26.220  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 06:31:26.220  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 06:31:26.220  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-30 06:31:26.221  5587  5633 D BluetoothAdapter: STATE_ON
08-30 06:31:26.222  4332  4577 D BtGatt.GattService: registerClient() - UUID=f5999c35-b6e3-4438-87db-8a17d1a2bca9
08-30 06:31:26.223  4332  4394 D BtGatt.GattService: onClientRegistered() - UUID=f5999c35-b6e3-4438-87db-8a17d1a2bca9, clientIf=5
,08-30 06:31:26.223  5587  5597 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-30 06:31:26.224  4332  4398 D BtGatt.AdvertiseManager: message : 0
,08-30 06:31:26.226  4332  4398 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 06:31:26.237  4332  4394 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 06:31:26.243  4332  4394 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 06:31:26.244  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-30 06:31:26.244  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 06:31:26.245  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 06:31:26.246  5587  5633 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 06:31:26.247  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 06:31:26.247  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-30 06:31:26.247  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 06:31:26.247  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-30 06:31:26.247  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-30 06:31:26.247  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-30 06:31:26.249  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-30 06:31:26.250  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 06:31:26.751  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
08-30 06:31:26.752  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 06:31:26.752  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 06:31:31.247  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 06:31:31.247  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 06:31:31.247  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-30 06:31:31.248  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 06:31:31.248  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 06:31:31.248  5587  5642 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 06:31:31.248  5587  5642 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 06:31:31.248  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-30 06:31:31.249  5587  5642 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 06:31:31.249  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:31.249  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 06:31:31.249  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:31.249  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 06:31:31.249  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 06:31:31.249  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 06:31:31.249  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 06:31:31.250  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 06:31:31.252  5587  5633 D BluetoothAdapter: STATE_ON
,08-30 06:31:31.253  5587  5633 D BluetoothLeScanner: could not find callback wrapper
08-30 06:31:31.253  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 06:31:31.253  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-30 06:31:31.255  4332  4398 D BtGatt.AdvertiseManager: message : 1
,08-30 06:31:31.257  4332  4398 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 06:31:31.269  4332  4394 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-30 06:31:31.270  4332  4394 D BtGatt.GattService: Client app is not null!
,08-30 06:31:31.271  4332  4595 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 06:31:31.272  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 06:31:31.272  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-30 06:31:31.272  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-30 06:31:31.272  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-30 06:31:31.272  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-30 06:31:31.274  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 06:31:31.274  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 06:31:31.274  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 06:31:31.275  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 06:31:31.276  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
,08-30 06:31:31.276  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 06:31:31.276  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:31.276  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 06:31:31.276  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:31.276  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 06:31:31.315  4332  4560 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-30 06:31:31.316  4332  4569 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 6
,08-30 06:31:31.777  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 06:31:36.279  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 06:31:36.279  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:36.279  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:36.279  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:36.279  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:36.280  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:36.280  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:36.280  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:36.280  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:31:36.280  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:36.281  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:36.281  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:36.281  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:36.281  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:36.281  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:36.288  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 06:31:36.288  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:31:36.291  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 06:31:36.292  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 06:31:36.292  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 06:31:36.293  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 06:31:36.293  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 06:31:36.293  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 06:31:36.294  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:36.294  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 06:31:36.295  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 06:31:36.295  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 06:31:36.295  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:36.295  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 06:31:36.296  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:36.296  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:36.296  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 06:31:36.296  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 06:31:36.297  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 06:31:36.297  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 06:31:36.297  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:36.297  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:36.297  5587  5643 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 06:31:36.301  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 06:31:36.301  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:36.302  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:31:36.302  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 06:31:36.302  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:36.302  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:36.302  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 06:31:36.302  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:36.302  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 06:31:36.302  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:36.302  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:36.302  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 06:31:36.302  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:36.302  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:36.303  5587  5643 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 06:31:36.303  5587  5643 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 06:31:36.303  5587  5643 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 06:31:36.303  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 06:31:36.304  5587  5633 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 06:31:36.304  5587  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 06:31:36.304  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 06:31:36.304  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 06:31:36.304  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 06:31:36.305  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 06:31:36.305  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:36.305  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:36.305  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:36.305  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:36.305  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:36.305  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:36.305  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:36.306  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:31:36.311  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 06:31:36.311  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:36.311  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:36.311  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
08-30 06:31:36.311  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:36.311  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:36.311  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:36.311  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:36.311  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:31:36.312  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 06:31:36.312  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:36.312  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:36.312  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def752b not in the list
,08-30 06:31:36.312  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:31:36.312  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eea2d88 not in the list
08-30 06:31:36.313  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:36.313  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:36.313  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:36.315  5587  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 06:31:36.315  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-30 06:31:36.315  5587  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 06:31:36.315  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 06:31:36.315  5587  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 06:31:36.315  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 06:31:36.317  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 06:31:36.317  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 06:31:36.318  5587  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 06:31:36.318  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 06:31:36.318  5587  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 06:31:36.318  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 06:31:36.318  5587  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 06:31:36.318  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 06:31:36.319  5587  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 06:31:36.319  5587  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-30 06:31:36.319  5587  5633 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 06:31:36.319  5587  5633 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 06:31:36.319  5587  5633 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 06:31:36.319  5587  5633 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 06:31:36.320  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 06:31:36.320  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef4152a added. We now have 3 listener(s)
08-30 06:31:36.320  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 06:31:36.323  5587  5633 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 06:31:36.324   928  3342 D WifiService: setWifiEnabled: true pid=5587, uid=10077
08-30 06:31:36.324   928  3342 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 06:31:36.803  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 06:31:41.330  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 06:31:41.330  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4dbff1b added. We now have 4 listener(s)
08-30 06:31:41.330  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 06:31:41.346  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 06:31:41.346  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4dbff1b removed from the list
08-30 06:31:41.347  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:41.347  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:41.347  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:31:41.347  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 06:31:41.347  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34808b8 added. We now have 4 listener(s)
,08-30 06:31:41.348  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 06:31:41.349  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 06:31:41.349  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34808b8 removed from the list
08-30 06:31:41.350  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:31:41.350  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:31:41.350  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:31:41.350  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 06:31:41.351  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ea3f691 added. We now have 4 listener(s)
08-30 06:31:41.351  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 06:31:41.353   928  3342 D WifiService: setWifiEnabled: false pid=5587, uid=10077
,08-30 06:31:41.353   928  3342 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 06:31:41.358   928  2885 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 06:31:41.359   928  2885 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 06:31:41.359   928  2885 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 06:31:41.359   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 06:31:41.361  4332  4390 D BluetoothAdapterState: Current state: ON, message: 23
08-30 06:31:41.361  4332  4390 D BluetoothAdapterProperties: Setting state to 13
08-30 06:31:41.362  4332  4390 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 06:31:41.362  4332  4390 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 06:31:41.364  4332  4390 I BluetoothAdapterState: Entering PendingCommandState
,08-30 06:31:41.366  4332  4332 D BluetoothMapService: onReceive
08-30 06:31:41.366  4332  4332 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 06:31:41.366  4332  4332 D BluetoothMapService: STATE_TURNING_OFF
08-30 06:31:41.367  4332  4332 D BluetoothMapService: MAP Service closeService in
08-30 06:31:41.367  4332  4332 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 06:31:41.367  4332  4332 D ObexServerSockets0: shutdown(block = true)
08-30 06:31:41.368  4332  4332 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 06:31:41.368  4332  4332 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 06:31:41.368  4332  4601 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 06:31:41.368  4332  4600 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
08-30 06:31:41.368  4332  4569 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-30 06:31:41.371  4332  4332 I BtOppRfcommListener: stopping Accept Thread
08-30 06:31:41.372  4332  5116 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 06:31:41.372  4332  5116 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 06:31:41.374  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.374  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:41.374  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:41.374  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:41.374  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:41.374  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:41.374  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:41.374  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:31:41.374  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 06:31:41.378   928  2885 E native  : do suspend true
08-30 06:31:41.383  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.383  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:41.386  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.387  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:41.387  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:41.387  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:41.387  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:41.387  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:41.387  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:41.387  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:31:41.387  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 06:31:41.387  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.387  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 06:31:41.390   928   941 I ActivityManager: Start proc 5647:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-30 06:31:41.391  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:31:41.391  4332  4394 D BluetoothAdapterProperties: Scan Mode:20
08-30 06:31:41.392  4332  4390 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 06:31:41.395  4332  4332 D HeadsetService: Received stop request...Stopping profile...
,08-30 06:31:41.397  3065  3076 D BluetoothHeadset: Proxy object disconnected
,08-30 06:31:41.397   928   928 D BluetoothHeadset: Proxy object disconnected
08-30 06:31:41.397  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.397   928   928 D BluetoothHeadset: Proxy object disconnected
08-30 06:31:41.397  3065  3065 D HeadsetProfile: Bluetooth service disconnected
08-30 06:31:41.397  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:31:41.397  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:41.397  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:41.397  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:41.397  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:41.397  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:41.397  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:31:41.397  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 06:31:41.397  3449  3475 D BluetoothHeadset: Proxy object disconnected
08-30 06:31:41.398   928   928 D BluetoothHeadset: Proxy object disconnected
08-30 06:31:41.398  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.398  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:41.398  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 06:31:41.400  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:41.401  4332  4332 D A2dpService: Received stop request...Stopping profile...
08-30 06:31:41.402  4332  4580 D A2dpStateMachine: Exit Disconnected: -1
08-30 06:31:41.405   928   928 D BluetoothA2dp: Proxy object disconnected
08-30 06:31:41.405  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:41.405  4332  4332 V BluetoothAdapterState: isTurningOff()=true
08-30 06:31:41.406  4332  4332 V BluetoothAdapterState: isTurningOn()=false
08-30 06:31:41.406  4332  4332 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:31:41.406  4332  4332 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:31:41.406  3065  3065 D BluetoothA2dp: Proxy object disconnected
,08-30 06:31:41.407  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:41.409  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:41.411  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:41.411   928  5167 D DhcpClient: Clearing IP address
08-30 06:31:41.411  4332  4332 D HidService: Received stop request...Stopping profile...
08-30 06:31:41.411  4332  4332 D HidService: Stopping Bluetooth HidService
08-30 06:31:41.411   507   923 D CommandListener: Clearing all IP addresses on wlan0
08-30 06:31:41.413  3065  3065 D BluetoothInputDevice: Proxy object disconnected
08-30 06:31:41.413  3065  3065 D HidProfile: Bluetooth service disconnected
08-30 06:31:41.414  4332  4332 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 06:31:41.414  4332  4332 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 06:31:41.414  4332  4560 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 06:31:41.414  4332  4560 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 06:31:41.414  4332  4560 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 06:31:41.415  4332  4332 D HealthService: Received stop request...Stopping profile...
08-30 06:31:41.415  4332  4394 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 06:31:41.415  4332  4394 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 06:31:41.418  4332  4332 D PanService: Received stop request...Stopping profile...
08-30 06:31:41.419  3065  3065 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 06:31:41.419  3065  3065 D PanProfile: Bluetooth service disconnected
08-30 06:31:41.419   507   923 D CommandListener: Setting iface cfg
,08-30 06:31:41.423  4332  4332 D BluetoothMapService: Received stop request...Stopping profile...
08-30 06:31:41.423  4332  4332 D BluetoothMapService: stop()
,08-30 06:31:41.424  4332  4332 D BluetoothMapAppObserver: deinitObservers()
08-30 06:31:41.424  4332  4332 D BluetoothMapAppObserver: removeReceiver()
,08-30 06:31:41.426  3526  5221 V NativeCrypto: Read error: ssl=0x7f77fc9c80: I/O error during system call, Connection timed out
08-30 06:31:41.426   928  5168 D DhcpClient: Receive thread stopped
08-30 06:31:41.427  4332  4332 D SapService: Received stop request...Stopping profile...
08-30 06:31:41.427  4332  4332 V SapService: stop()
,08-30 06:31:41.427  3065  3065 D BluetoothMap: Proxy object disconnected
,08-30 06:31:41.427  3065  3065 D MapProfile: Bluetooth service disconnected
08-30 06:31:41.428  3526  5221 V NativeCrypto: SSL shutdown failed: ssl=0x7f77fc9c80: I/O error during system call, Broken pipe
08-30 06:31:41.428  4332  4332 V BluetoothAdapterState: isTurningOff()=true
08-30 06:31:41.428  4332  4332 V BluetoothAdapterState: isTurningOn()=false
08-30 06:31:41.428  4332  4332 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:31:41.428  4332  4332 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:31:41.430   928  3087 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,08-30 06:31:41.430   928  5165 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
08-30 06:31:41.430  4332  4394 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 06:31:41.430  4332  4560 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 06:31:41.431  4332  4560 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 06:31:41.431  4332  4560 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 06:31:41.431  4332  4560 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 06:31:41.431  4332  4560 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 06:31:41.431  4332  4560 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 06:31:41.432   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 06:31:41.432  5647  5647 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
08-30 06:31:41.432   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-30 06:31:41.432   928  5165 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-30 06:31:41.434  4332  4332 V BluetoothAdapterState: isTurningOff()=true
08-30 06:31:41.434  4332  4332 V BluetoothAdapterState: isTurningOn()=false
,08-30 06:31:41.434  4332  4332 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 06:31:41.434  4332  4332 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 06:31:41.434   535   535 E Parcel  : Reading a NULL string not supported here.
08-30 06:31:41.435  4332  4332 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 06:31:41.435  4332  4332 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 06:31:41.435  4332  4394 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 06:31:41.436  4332  4332 V BluetoothAdapterState: isTurningOff()=true
08-30 06:31:41.437  4332  4332 V BluetoothAdapterState: isTurningOn()=false
08-30 06:31:41.437  4332  4332 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:31:41.437  4332  4332 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 06:31:41.437   928   928 D RttService: SCAN_AVAILABLE : 1
,08-30 06:31:41.437   928  2992 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 06:31:41.438  4332  4332 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 06:31:41.438  4332  4394 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 06:31:41.439  4332  4332 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 06:31:41.439  4332  4332 V BluetoothAdapterState: isTurningOff()=true
08-30 06:31:41.439  4332  4332 V BluetoothAdapterState: isTurningOn()=false
08-30 06:31:41.439  4332  4332 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:31:41.439  4332  4332 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:31:41.439  4332  4332 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 06:31:41.439   928  2887 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 06:31:41.440  4332  4332 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 06:31:41.441  4332  4332 D BluetoothMapService: MAP Service closeService in
,08-30 06:31:41.441  4332  4332 V BluetoothAdapterState: isTurningOff()=true
,08-30 06:31:41.441  4332  4332 V BluetoothAdapterState: isTurningOn()=false
08-30 06:31:41.441  4332  4332 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:31:41.441  4332  4332 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:31:41.442  4332  4332 D BluetoothMapService: cleanup()
08-30 06:31:41.442  3417  3567 W QCNEJ   : |CORE| network lost: 100
08-30 06:31:41.442  4332  4332 D BluetoothMapService: MAP Service closeService in
,08-30 06:31:41.442  4332  4332 V BluetoothAdapterState: isTurningOff()=true
08-30 06:31:41.442  4332  4332 V BluetoothAdapterState: isTurningOn()=false
08-30 06:31:41.442  4332  4332 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:31:41.442  4332  4332 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:31:41.442  3417  3567 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
08-30 06:31:41.443  4332  4390 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 06:31:41.443  4332  4390 D BluetoothAdapterProperties: Setting state to 15
08-30 06:31:41.443  4332  4390 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 06:31:41.444  4332  4390 I BluetoothAdapterState: Entering BleOnState
08-30 06:31:41.447   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 06:31:41.447  3065  3646 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 06:31:41.448  3065  3077 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 06:31:41.448  3065  3076 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 06:31:41.449  3449  3666 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 06:31:41.449   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 06:31:41.449  3065  5586 D BluetoothPan: onBluetoothStateChange on: false
08-30 06:31:41.450  3065  3643 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 06:31:41.450   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 06:31:41.450   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 06:31:41.451  3065  3646 D BluetoothMap: onBluetoothStateChange: up=false
08-30 06:31:41.451  4332  4390 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 06:31:41.451  4332  4390 D BluetoothAdapterProperties: Setting state to 16
08-30 06:31:41.452  4332  4390 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 06:31:41.454  4332  4390 D BluetoothAdapterProperties: onBleDisable
08-30 06:31:41.454  4332  4390 I BluetoothAdapterState: Entering PendingCommandState
08-30 06:31:41.455  4332  4391 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 06:31:41.455   928  2885 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 06:31:41.456  4332  4394 D BluetoothAdapterProperties: Scan Mode:20
08-30 06:31:41.457  4332  4560 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 06:31:41.457  4332  4560 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 06:31:41.457  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.457  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:41.457  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:41.457  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:41.457  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:41.457  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:41.457  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:41.457  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:41.457  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 06:31:41.458  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.458  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 06:31:41.459  5647  5647 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 06:31:41.462  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.462  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:41.462  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:41.462  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:41.462  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:41.462  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:41.462  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:41.462  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:41.462  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:41.463  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.463  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:31:41.465  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.465  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:41.465  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:41.465  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:41.465  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:41.465  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:41.465  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:41.465  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:41.465  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:41.465  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.465  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 06:31:41.466  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:41.467  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:41.468  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:41.470  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 06:31:41.471   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c52262:true
08-30 06:31:41.475   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 06:31:41.475   928  2885 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 06:31:41.476   928  2885 E native  : do suspend true
,08-30 06:31:41.485   928  3561 I ActivityManager: Start proc 5667:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-30 06:31:41.497   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 06:31:41.497   507   923 D TetherController: Setting IP forward enable = 0
08-30 06:31:41.504   507   923 D CommandListener: Clearing all IP addresses on wlan0
08-30 06:31:41.504   928  2887 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 06:31:41.504   928  2887 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 06:31:41.505   928   945 D Tethering: MasterInitialState.processMessage what=3
,08-30 06:31:41.508  5060  5060 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@20e29d2 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-30 06:31:41.508   928  2885 D DhcpClient: doQuit
08-30 06:31:41.509   928  2885 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-30 06:31:41.509  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:41.509   928  5167 D DhcpClient: onQuitting
08-30 06:31:41.510  3541  3541 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
08-30 06:31:41.512  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.512  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:41.512  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:41.512  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:41.512  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:31:41.512  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:41.512  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:41.512  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:41.512  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:41.513  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.513  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:31:41.516  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.516  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:41.516  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:41.516  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:41.516  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:31:41.516  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:41.516  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:41.516  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:41.516  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:41.517  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 06:31:41.517  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:31:41.518  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.518  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:41.518  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:41.518  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:41.518  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:31:41.518  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:41.518  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:41.518  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:41.518  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:41.519  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:41.519  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:31:41.520  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:31:41.521  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:41.524  4791  4820 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-30 06:31:41.525  4791  4820 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-30 06:31:41.525  4791  4820 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,08-30 06:31:41.525  4791  4820 E SarControlService: no key has been found,reset the power
08-30 06:31:41.525  4791  4838 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-30 06:31:41.525  4791  4838 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-30 06:31:41.525  4791  4838 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-30 06:31:41.526  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 06:31:41.526  4830  4830 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-30 06:31:41.527  4791  4838 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,08-30 06:31:41.527  4791  4838 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-30 06:31:41.527  4791  4838 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-30 06:31:41.529  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 06:31:41.529  4830  4830 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-30 06:31:41.529  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d4564c8 HexData = [00000000ea03000000000000ffffffff]
08-30 06:31:41.529  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-30 06:31:41.529  4830  4844 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
08-30 06:31:41.530  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-30 06:31:41.531  4791  4801 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-30 06:31:41.538  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d4564c8 HexData = [00000000eb03000000000000ffffffff]
08-30 06:31:41.538  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,08-30 06:31:41.538  4830  4844 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
08-30 06:31:41.539  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-30 06:31:41.539  4791  4802 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-30 06:31:41.543  5647  5647 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 06:31:41.546   507   923 E Netd    : netlink response contains error (No such file or directory)
,08-30 06:31:41.546  3541  3541 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
08-30 06:31:41.547   507   923 D TetherController: Setting IP forward enable = 0
08-30 06:31:41.548   928  2887 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 06:31:41.548   928  2887 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 06:31:41.550  5667  5667 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
08-30 06:31:41.551  3541  3541 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 06:31:41.553  5647  5647 D BluetoothMap: Create BluetoothMap proxy object
,08-30 06:31:41.566  5647  5647 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 06:31:41.577  5647  5647 D DockEventReceiver: finishStartingService: stopping service
,08-30 06:31:41.585   928  3087 I ActivityManager: Killing 5195:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,08-30 06:31:41.646  3541  3541 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-30 06:31:41.690  3541  3541 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 06:31:41.693  4332  4394 I bt_hci  : shut_down
,08-30 06:31:41.696  4332  4401 D bt_hwcfg: hw_epilog_process
,08-30 06:31:41.696  4156  4156 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 06:31:41.697  4332  4401 I bt_vendor: low_power_mode_cb
08-30 06:31:41.698   928  2885 D wifi    : In wifi stop Hal
08-30 06:31:41.698   928  2885 D wifi    : halHandle = 0x7f665494e0, mVM = 0x7f829cd140, mCls = 0x200ac6
08-30 06:31:41.698   928  3537 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-30 06:31:41.698   928  3537 D WifiHAL : Got a signal to exit!!!
08-30 06:31:41.698   928  3537 I WifiHAL : Exit wifi_event_loop
08-30 06:31:41.699   928  2885 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-30 06:31:41.699   928  2885 E WifiHAL : Event processing terminated
,08-30 06:31:41.699   928  2885 D wifi    : In wifi cleaned up handler
08-30 06:31:41.699   928  2885 I WifiHAL : Internal cleanup completed
,08-30 06:31:41.699  3570  3895 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 06:31:41.700  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:41.700  4332  4401 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-30 06:31:41.700  4332  4401 I bt_vendor: epilog_cb
08-30 06:31:41.700  4332  4401 I bt_hci  : epilog_finished_callback
08-30 06:31:41.702  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:41.703  4332  4394 I bt_hci_h4: hal_close
,08-30 06:31:41.703  4332  4394 I bt_userial_vendor: device fd = 51 close
08-30 06:31:41.703  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:31:41.717   928  3537 D wifi    : set interface wlan0 flags (DOWN)
,08-30 06:31:41.717   928  2885 D WifiNative-HAL: HAL event thread stopped successfully
,08-30 06:31:41.802  5667  5667 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 06:31:41.802  5667  5667 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 06:31:41.802  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 06:31:41.803  5667  5667 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 06:31:41.803  5667  5667 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 06:31:41.803  5667  5667 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 06:31:41.803  5667  5667 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 06:31:41.803  5667  5667 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 06:31:41.803  5667  5667 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 06:31:41.803  5667  5667 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 06:31:41.809  5647  5647 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 06:31:41.815  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 06:31:41.816  4332  4391 D bt_stack_manager: event_shut_down_stack finished.
08-30 06:31:41.816  4332  4390 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-30 06:31:41.818  4332  4332 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 06:31:41.818  4332  4390 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-30 06:31:41.818  4332  4332 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 06:31:41.818  4332  4332 D BtGatt.GattService: stop()
08-30 06:31:41.819  4332  4332 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 06:31:41.822  4332  4332 V BluetoothAdapterState: isTurningOff()=false
08-30 06:31:41.822  4332  4332 V BluetoothAdapterState: isTurningOn()=false
08-30 06:31:41.822  4332  4332 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:31:41.822  4332  4332 V BluetoothAdapterState: isBleTurningOff()=true
08-30 06:31:41.822  4332  4390 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 06:31:41.822  4332  4390 D BluetoothAdapterProperties: Setting state to 10
08-30 06:31:41.822  4332  4390 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 06:31:41.823  4332  4390 I BluetoothAdapterState: Entering OffState
08-30 06:31:41.824   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-30 06:31:41.830  3809  3809 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 06:31:41.832  4332  4332 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-30 06:31:41.832  4332  4332 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 06:31:41.832  4332  4332 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 06:31:41.833  4332  4391 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-30 06:31:41.835  4332  4391 D bt_stack_manager: event_clean_up_stack finished.
08-30 06:31:41.837  3809  3809 D SystemUpdateService: onCreate
08-30 06:31:41.840  3809  3809 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-30 06:31:41.847  5647  5647 D DockEventReceiver: finishStartingService: stopping service
08-30 06:31:41.848  3809  3809 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-30 06:31:41.853  3809  5192 I iu.UploadsManager: num queued entries: 0
08-30 06:31:41.853  3809  5192 I iu.UploadsManager: num updated entries: 0
08-30 06:31:41.854  3809  5192 I iu.SyncManager: NEXT; no task
08-30 06:31:41.855  4332  4332 I art     : System.exit called, status: 0
,08-30 06:31:41.855  4332  4332 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 06:31:41.875  3809  3809 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 06:31:41.877  3809  3809 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
08-30 06:31:41.878  3809  5710 I SystemUpdateService: active receiver: enabled
08-30 06:31:41.889   928  3087 I ActivityManager: Start proc 5712:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 06:31:41.905   928  3342 I ActivityManager: Process com.android.bluetooth (pid 4332) has died
,08-30 06:31:41.911  3809  5710 I SystemUpdateService: showing system update notification
,08-30 06:31:41.919   928   945 D Tethering: InitialState.processMessage what=4
08-30 06:31:41.922   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 06:31:41.938  5712  5712 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,08-30 06:31:41.950  5712  5712 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 06:31:41.957  5712  5712 D SprintDMHelper: simOperator: 
,08-30 06:31:41.957  5712  5712 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 06:31:41.968  4156  5725 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 06:31:41.973   928  3443 I ActivityManager: Killing 5060:com.google.android.music:main/u0a59 (adj 15): empty #17
,08-30 06:31:42.050   928  3443 I ActivityManager: Start proc 5726:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-30 06:31:42.059  3809  5710 V SystemUpdateService: retry (wakeup: false) in 3599883 ms
,08-30 06:31:42.061  3809  3809 D SystemUpdateService: onDestroy
08-30 06:31:42.062   928   939 I ActivityManager: Killing 4404:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-30 06:31:42.120  5667  5704 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 06:31:42.132  5726  5726 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,08-30 06:31:42.175  5726  5726 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 06:31:42.183   928  3443 I ActivityManager: Killing 5379:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-30 06:31:42.197   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6909036:true
,08-30 06:31:46.401   928  3087 D WifiService: setWifiEnabled: true pid=5587, uid=10077
,08-30 06:31:46.401   928  3087 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 06:31:46.412   507   923 D SoftapController: Softap fwReload - Ok
,08-30 06:31:46.418   507   923 D CommandListener: Setting iface cfg
,08-30 06:31:46.419   507   923 D CommandListener: Trying to bring down wlan0
,08-30 06:31:46.421   507   923 D CommandListener: Clearing all IP addresses on wlan0
,08-30 06:31:46.429   928  2885 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-30 06:31:47.021   928  2885 D wifi    : set interface wlan0 flags (UP)
,08-30 06:31:47.025   928  2885 I WifiHAL : Initializing wifi
08-30 06:31:47.025   928  2885 I WifiHAL : Creating socket
08-30 06:31:47.029   928  2885 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-30 06:31:47.029   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 06:31:47.029   928  2885 D wifi    : Did set static halHandle = 0x7f665494e0
08-30 06:31:47.029   928  2885 D wifi    : halHandle = 0x7f665494e0, mVM = 0x7f829cd140, mCls = 0x1832
08-30 06:31:47.029   928  2885 D wifi    : array field set
,08-30 06:31:47.030   928  2885 I WifiNative-HAL: interface[0] = wlan0
08-30 06:31:47.032   928  5755 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547177665760
08-30 06:31:47.032   928  5755 D wifi    : waitForHalEvents called, vm = 0x7f829cd140, obj = 0x1832, env = 0x7f6760da80
,08-30 06:31:47.082  5756  5756 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 06:31:47.103  5756  5756 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 06:31:47.113  5756  5756 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 06:31:47.113  5756  5756 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-30 06:31:47.133   928  2885 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 06:31:47.139  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:47.141  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:31:47.146  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 06:31:47.146  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:47.146  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:47.146  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:47.146  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:47.146  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:47.146  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:47.146  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:47.146  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 06:31:47.146  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:47.146  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:31:47.150  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:47.150  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:47.150  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:47.150  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:47.150  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:47.150  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:47.150  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:47.150  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:47.150  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:47.150  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:47.150  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 06:31:47.150   928  2885 D WifiConfigStore: Loading config and enabling all networks 
08-30 06:31:47.151  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:47.151  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:47.151  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:47.151  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:47.151  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:47.151  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:47.151  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:47.151  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:47.151  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:47.151  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:47.151  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:31:47.152  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:31:47.154   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-30 06:31:47.155   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-30 06:31:47.155   928  2885 D WifiConfigStore: loaded 0 passpoint configs
,08-30 06:31:47.156   928  2885 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 06:31:47.156   928  2885 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 06:31:47.157   928  2885 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 06:31:47.158   928  2885 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-30 06:31:47.158   928  2885 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 06:31:47.161  4156  4156 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 06:31:47.161   928  2885 D WifiNative-HAL: Setting external_sim to 1
08-30 06:31:47.161   928  2885 D wifi    : setting dfs flag to true, 0x7f68e3e160
,08-30 06:31:47.161   928  2885 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 06:31:47.162   928  2885 D wifi    : setting scan oui 0x7f68e3e160
08-30 06:31:47.162   928  2885 D WifiHAL : Sending mac address OUI
,08-30 06:31:47.177   928  2885 E native  : do suspend true
,08-30 06:31:47.183   928   928 D RttService: SCAN_AVAILABLE : 3
08-30 06:31:47.183   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-30 06:31:47.183   928  2885 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-30 06:31:47.183   928  2992 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 06:31:47.184   507   923 D CommandListener: Setting iface cfg
,08-30 06:31:47.188   928  2884 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
08-30 06:31:47.188   928  2884 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 06:31:47.191   928  2884 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 06:31:47.196   928  2884 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-30 06:31:47.213   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=221239 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,08-30 06:31:50.399  5756  5756 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 06:31:50.432   928  2885 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-30 06:31:50.441   928  2885 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,08-30 06:31:50.442   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 06:31:50.458   928  2885 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-30 06:31:50.508   928  2885 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-30 06:31:50.839  5756  5756 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 06:31:50.869  5756  5756 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 06:31:50.869  5756  5756 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-30 06:31:50.878   928  2885 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 06:31:50.878   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 06:31:50.878   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 06:31:50.894   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 06:31:50.906   507   923 D CommandListener: Setting iface cfg
,08-30 06:31:50.912   928  2885 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 06:31:50.920   928  2885 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 06:31:50.948   928  5762 D DhcpClient: Receive thread started
,08-30 06:31:51.031   928  2885 E native  : do suspend false
,08-30 06:31:51.047   928  5761 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 06:31:51.064   928  5762 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172618, domain null
,08-30 06:31:51.065   928  5761 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172618 seconds
,08-30 06:31:51.068   928  5761 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,08-30 06:31:51.082   928  5762 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 06:31:51.083   928  5761 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-30 06:31:51.086   507   923 D CommandListener: Setting iface cfg
,08-30 06:31:51.096   928  2885 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 06:31:51.097   928  5761 D DhcpClient: Scheduling renewal in 86399s
08-30 06:31:51.098   928  2885 E native  : do suspend true
,08-30 06:31:51.116   928  2885 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 06:31:51.119   928  2885 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 06:31:51.121   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 06:31:51.123   928  2887 D ConnectivityService: Adding iface wlan0 to network 101
08-30 06:31:51.128   928  2885 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 06:31:51.165   928  2887 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 06:31:51.165   928  2887 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-30 06:31:51.166   928  2887 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 06:31:51.168   928  2887 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 06:31:51.170   928  2887 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 06:31:51.177   928  2887 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 06:31:51.181   928  2887 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 06:31:51.182   928  2887 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-30 06:31:51.182   928  2887 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-30 06:31:51.182   928  2885 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 06:31:51.182   928  2887 D ConnectivityService:    accepting network in place of null
08-30 06:31:51.182   928  2885 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 06:31:51.183   928  2887 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 06:31:51.210   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 06:31:51.223   928  5760 D NetlinkSocketObserver: NeighborEvent{elapsedMs=225249, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 06:31:51.234   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 06:31:51.237   928  2887 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 06:31:51.237  3417  3567 W QCNEJ   : |CORE| network available: 101
08-30 06:31:51.237   928  2887 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 06:31:51.238   928  2887 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 06:31:51.242   928   945 D Tethering: MasterInitialState.processMessage what=3
08-30 06:31:51.242  3417  3567 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,08-30 06:31:51.243  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.243  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:51.243  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:51.243  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:51.243  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:51.243  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:51.243  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:51.243  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:31:51.243  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 06:31:51.243  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.243  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:51.243  3417  3567 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
08-30 06:31:51.246  3417  3567 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,08-30 06:31:51.247  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.247  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:51.247  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:51.247  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:51.247  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:51.247  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:51.247  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:51.247  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:31:51.247  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 06:31:51.247  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.247  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:51.249  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.249  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:51.249  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:51.249  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:51.249  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:51.249  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:51.249  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:31:51.249  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:31:51.249  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 06:31:51.249  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.249  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 06:31:51.256  4791  4820 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,08-30 06:31:51.256  4791  4820 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-30 06:31:51.256  4791  4820 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
08-30 06:31:51.257  4791  4820 E SarControlService: no key has been found,reset the power
08-30 06:31:51.257  4791  4838 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,08-30 06:31:51.257  4791  4838 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,08-30 06:31:51.257  4791  4838 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-30 06:31:51.257  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 06:31:51.257  4830  4830 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-30 06:31:51.259  4791  4838 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-30 06:31:51.259  4791  4838 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-30 06:31:51.259  4791  4838 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-30 06:31:51.259  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 06:31:51.259  4830  4830 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-30 06:31:51.262  3809  3809 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 06:31:51.265  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d4564c8 HexData = [00000000ec03000000000000ffffffff]
08-30 06:31:51.265  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-30 06:31:51.265  4830  4844 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
08-30 06:31:51.265  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d4564c8 HexData = [00000000ed03000000000000ffffffff]
08-30 06:31:51.265  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-30 06:31:51.265  4830  4844 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
08-30 06:31:51.266  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-30 06:31:51.266  4791  4801 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-30 06:31:51.267  3809  3809 D SystemUpdateService: onCreate
08-30 06:31:51.267  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-30 06:31:51.268  4791  4802 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-30 06:31:51.270  3809  3809 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 06:31:51.282  3809  3809 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 06:31:51.287  3809  5192 I iu.UploadsManager: num queued entries: 0
,08-30 06:31:51.287  3809  5192 I iu.UploadsManager: num updated entries: 0
08-30 06:31:51.288  3809  5192 I iu.SyncManager: NEXT; no task
,08-30 06:31:51.290  3809  5772 I SystemUpdateService: active receiver: enabled
,08-30 06:31:51.292  3809  3809 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 06:31:51.293  3809  3809 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-30 06:31:51.295  5712  5712 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 06:31:51.298  5712  5712 D SprintDMHelper: simOperator: 
08-30 06:31:51.298  5712  5712 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 06:31:51.332   928  5759 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-30 06:31:51.332  3809  5772 I SystemUpdateService: showing system update notification
,08-30 06:31:51.340  3809  5772 V SystemUpdateService: retry (wakeup: false) in 3599950 ms
,08-30 06:31:51.342  3809  3809 D SystemUpdateService: onDestroy
,08-30 06:31:51.404   928  5759 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:31:51 GMT], X-Android-Received-Millis=[1472553111403], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472553111373]}
,08-30 06:31:51.404   928  2887 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 06:31:51.405   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-30 06:31:51.405   928  2887 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 06:31:51.406   928  2887 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 06:31:51.409   928  3443 D WifiService: setWifiEnabled: false pid=5587, uid=10077
08-30 06:31:51.409   928  3443 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 06:31:51.411   928  2885 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 06:31:51.412   928  2885 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 06:31:51.412   928  2885 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 06:31:51.412   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 06:31:51.418   928  2885 E native  : do suspend true
,08-30 06:31:51.420  4156  5776 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 06:31:51.427   928  5761 D DhcpClient: Clearing IP address
,08-30 06:31:51.427   507   923 D CommandListener: Clearing all IP addresses on wlan0
08-30 06:31:51.429   507   923 D CommandListener: Setting iface cfg
,08-30 06:31:51.430   928  5762 D DhcpClient: Receive thread stopped
,08-30 06:31:51.437  3526  5784 V NativeCrypto: Read error: ssl=0x7f67bf4000: I/O error during system call, Connection timed out
08-30 06:31:51.438  3526  5784 V NativeCrypto: SSL shutdown failed: ssl=0x7f67bf4000: I/O error during system call, Broken pipe
08-30 06:31:51.439   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 06:31:51.440   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-30 06:31:51.443   928   928 D RttService: SCAN_AVAILABLE : 1
,08-30 06:31:51.445   928  2992 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 06:31:51.445   535   535 E Parcel  : Reading a NULL string not supported here.
,08-30 06:31:51.451   928  2887 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-30 06:31:51.451   928  2885 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 06:31:51.452  3417  3567 W QCNEJ   : |CORE| network lost: 101
08-30 06:31:51.453  3417  3567 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
08-30 06:31:51.455   928  2885 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 06:31:51.455   928  2885 E native  : do suspend true
,08-30 06:31:51.471   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 06:31:51.491   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 06:31:51.491   507   923 D CommandListener: Clearing all IP addresses on wlan0
08-30 06:31:51.491   928  2887 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 06:31:51.491   928  2887 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 06:31:51.493   928   945 D Tethering: MasterInitialState.processMessage what=3
08-30 06:31:51.496  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.496  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:51.496  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:51.496  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:51.496  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:51.496  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:51.496  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:51.496  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:51.496  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:51.496  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.496  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:31:51.497   928  2885 D DhcpClient: doQuit
08-30 06:31:51.497   928  2885 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-30 06:31:51.497   928  5761 D DhcpClient: onQuitting
,08-30 06:31:51.498  5756  5756 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-30 06:31:51.499  3809  3809 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 06:31:51.500  4791  4820 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-30 06:31:51.501  4791  4820 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-30 06:31:51.501  4791  4820 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-30 06:31:51.501  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.501  4791  4820 E SarControlService: no key has been found,reset the power
08-30 06:31:51.501  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:51.501  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:51.501  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:51.501  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:31:51.501  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:51.501  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:51.501  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:51.501  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:51.501  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 06:31:51.501  4791  4838 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-30 06:31:51.501  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:31:51.501  4791  4838 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-30 06:31:51.501  4791  4838 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-30 06:31:51.502  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 06:31:51.502  4830  4830 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-30 06:31:51.503  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.503  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:51.503  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:51.503  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:51.503  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:31:51.503  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:51.503  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:51.503  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:51.503  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:51.503  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.503  4791  4838 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-30 06:31:51.503  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:31:51.504  4791  4838 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,08-30 06:31:51.504  4791  4838 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,08-30 06:31:51.504  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,08-30 06:31:51.504  4830  4830 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-30 06:31:51.505  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.505  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:51.505  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:51.505  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:51.505  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:31:51.505  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:51.505  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:51.505  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:51.505  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:51.505  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.505  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:31:51.506  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.507  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:51.507  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:51.507  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:51.507  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:31:51.507  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:31:51.507  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:51.507  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:51.507  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:51.507  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:31:51.507  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 06:31:51.507  3809  3809 D SystemUpdateService: onCreate
08-30 06:31:51.508  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:51.508  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d4564c8 HexData = [00000000ee03000000000000ffffffff]
08-30 06:31:51.509  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-30 06:31:51.509  4830  4844 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
08-30 06:31:51.509  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-30 06:31:51.509  4791  4802 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-30 06:31:51.509  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d4564c8 HexData = [00000000ef03000000000000ffffffff]
08-30 06:31:51.509  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-30 06:31:51.510  4830  4844 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
08-30 06:31:51.510  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,08-30 06:31:51.510  4791  4801 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-30 06:31:51.513  3809  3809 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 06:31:51.520  3809  5792 I SystemUpdateService: active receiver: enabled
,08-30 06:31:51.522  3809  3809 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 06:31:51.526  5756  5756 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-30 06:31:51.528  3809  5192 I iu.UploadsManager: num queued entries: 0
08-30 06:31:51.529  3809  5192 I iu.UploadsManager: num updated entries: 0
,08-30 06:31:51.529  3809  5192 I iu.SyncManager: NEXT; no task
,08-30 06:31:51.530  5756  5756 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 06:31:51.531  3809  3809 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 06:31:51.533  3809  3809 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-30 06:31:51.535  5712  5712 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 06:31:51.538  5712  5712 D SprintDMHelper: simOperator: 
08-30 06:31:51.538  5712  5712 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 06:31:51.549  4156  5796 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 06:31:51.551   507   923 E Netd    : netlink response contains error (No such file or directory)
08-30 06:31:51.553   928  2887 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 06:31:51.554  3809  5792 I SystemUpdateService: showing system update notification
,08-30 06:31:51.568  3809  5792 V SystemUpdateService: retry (wakeup: false) in 3599953 ms
,08-30 06:31:51.569  3809  3809 D SystemUpdateService: onDestroy
,08-30 06:31:51.581  5756  5756 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-30 06:31:51.584  5756  5756 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 06:31:51.688   928  2885 D wifi    : In wifi stop Hal
,08-30 06:31:51.688  4156  4156 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 06:31:51.688   928  2885 D wifi    : halHandle = 0x7f665494e0, mVM = 0x7f829cd140, mCls = 0x1832
08-30 06:31:51.688   928  5755 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-30 06:31:51.688   928  5755 D WifiHAL : Got a signal to exit!!!
08-30 06:31:51.688   928  5755 I WifiHAL : Exit wifi_event_loop
08-30 06:31:51.689   928  2885 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,08-30 06:31:51.689   928  2885 E WifiHAL : Event processing terminated
08-30 06:31:51.689   928  2885 D wifi    : In wifi cleaned up handler
08-30 06:31:51.689   928  2885 I WifiHAL : Internal cleanup completed
08-30 06:31:51.689  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:51.691  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:31:51.691  3570  3895 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 06:31:51.692  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:31:51.707   928  5755 D wifi    : set interface wlan0 flags (DOWN)
,08-30 06:31:51.707   928  2885 D WifiNative-HAL: HAL event thread stopped successfully
,08-30 06:31:51.914   928   945 D Tethering: InitialState.processMessage what=4
,08-30 06:31:51.921   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 06:31:52.238   928  2887 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 06:31:56.449   928   945 I ActivityManager: Start proc 5798:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 06:31:56.510  5798  5798 D AdapterServiceConfig: Adding HeadsetService
,08-30 06:31:56.510  5798  5798 D AdapterServiceConfig: Adding A2dpService
08-30 06:31:56.510  5798  5798 D AdapterServiceConfig: Adding HidService
08-30 06:31:56.511  5798  5798 D AdapterServiceConfig: Adding HealthService
08-30 06:31:56.511  5798  5798 D AdapterServiceConfig: Adding PanService
08-30 06:31:56.511  5798  5798 D AdapterServiceConfig: Adding GattService
08-30 06:31:56.511  5798  5798 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 06:31:56.512  5798  5798 D AdapterServiceConfig: Adding SapService
,08-30 06:31:56.521   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e7bd5da:true
,08-30 06:31:56.521  5798  5798 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 06:31:56.523  5798  5798 I bt_bluedroid: init
08-30 06:31:56.523  5798  5810 I BluetoothAdapterState: Entering OffState
,08-30 06:31:56.525  5798  5811 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 06:31:56.525  5798  5811 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 06:31:56.525  5798  5811 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 06:31:56.525  5798  5811 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 06:31:56.526  5798  5798 I bt_bluedroid: get_profile_interface socket
,08-30 06:31:56.527  5798  5814 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-30 06:31:56.527  5798  5798 I bt_bluedroid: get_profile_interface sdp
,08-30 06:31:56.529  5798  5814 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-30 06:31:56.530  5798  5809 I bt_bluedroid: config_hci_snoop_log
08-30 06:31:56.531   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 06:31:56.535  5798  5810 D BluetoothAdapterState: Current state: OFF, message: 0
08-30 06:31:56.535  5798  5810 D BluetoothAdapterProperties: Setting state to 14
08-30 06:31:56.535  5798  5810 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 06:31:56.536  5798  5810 D BluetoothBondStateMachine: make
,08-30 06:31:56.537  5798  5815 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 06:31:56.540  5798  5810 I BluetoothAdapterState: Entering PendingCommandState
,08-30 06:31:56.541  5798  5798 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 06:31:56.542  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
08-30 06:31:56.543  5798  5798 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 06:31:56.543  5798  5798 D BtGatt.GattService: Received start request. Starting profile...
08-30 06:31:56.543  5798  5798 D BtGatt.GattService: start()
08-30 06:31:56.543  5798  5798 I bt_bluedroid: get_profile_interface gatt
08-30 06:31:56.545  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
08-30 06:31:56.545  5798  5798 D BtGatt.AdvertiseManager: advertise manager created
,08-30 06:31:56.549  5798  5798 V BluetoothAdapterState: isTurningOff()=false
08-30 06:31:56.549  5798  5798 V BluetoothAdapterState: isTurningOn()=false
08-30 06:31:56.549  5798  5798 V BluetoothAdapterState: isBleTurningOn()=true
08-30 06:31:56.549  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:31:56.549  5798  5810 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 06:31:56.549  5798  5810 I bt_bluedroid: enable
08-30 06:31:56.549  5798  5811 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 06:31:56.549  5798  5811 I bt_hci  : start_up
,08-30 06:31:56.554  5798  5811 I bt_vendor: alloc value 0xf406904d
,08-30 06:31:56.554  5798  5811 I bt_vendor: init
08-30 06:31:56.554  5798  5811 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 06:31:56.554  5798  5811 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 06:31:56.680  5798  5811 D bt_hci  : start_up starting async portion
,08-30 06:31:56.681  5798  5818 I bt_hci  : event_finish_startup
08-30 06:31:56.681  5798  5818 I bt_hci_h4: hal_open
08-30 06:31:56.681  5798  5818 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 06:31:56.670  5819  5819 W irq/448-msm_hs_: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-30 06:31:56.685  5798  5818 I bt_userial_vendor: device fd = 51 open
,08-30 06:31:56.702  5798  5818 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 06:31:56.706  5798  5818 D bt_hwcfg: Chipset BCM4358A3
,08-30 06:31:56.706  5798  5818 D bt_hwcfg: Target name = [BCM4358A3]
08-30 06:31:56.706  5798  5818 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-30 06:31:57.156   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:31:57.201  5798  5818 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 06:31:57.202  5798  5818 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 06:31:57.202  5798  5818 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 06:31:57.336  5798  5818 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 06:31:57.336  5798  5818 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-30 06:31:57.338  5798  5818 I bt_hwcfg: vendor lib fwcfg completed
,08-30 06:31:57.338  5798  5818 I bt_vendor: firmware callback
,08-30 06:31:57.338  5798  5818 I bt_hci  : firmware_config_callback
,08-30 06:31:57.347  5798  5821 I bt_btu  : btu_task pending for preload complete event
08-30 06:31:57.348  5798  5821 I bt_btu_task: Bluetooth chip preload is complete
,08-30 06:31:57.348  5798  5821 I bt_btu  : btu_task received preload complete event
08-30 06:31:57.353  5798  5821 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 06:31:57.353  5798  5821 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 06:31:57.353  5798  5821 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 06:31:57.354  5798  5821 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 06:31:57.354  5798  5821 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 06:31:57.354  5798  5821 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 06:31:57.354  5798  5821 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 06:31:57.354  5798  5821 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 06:31:57.354  5798  5821 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 06:31:57.355  5798  5821 I         : BTE_InitTraceLevels -- TRC_PAN
,08-30 06:31:57.355  5798  5821 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 06:31:57.355  5798  5821 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 06:31:57.355  5798  5821 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 06:31:57.355  5798  5821 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-30 06:31:57.355  5798  5821 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 06:31:57.453  5798  5821 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fe6c99
08-30 06:31:57.453  5798  5821 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fe6c99 
,08-30 06:31:57.494  5798  5814 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-30 06:31:57.496  5798  5814 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 06:31:57.496  5798  5814 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-30 06:31:57.498  5798  5814 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-30 06:31:57.501  5798  5814 D BluetoothAdapterProperties: Scan Mode:20
08-30 06:31:57.501  5798  5814 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 06:31:57.501  5798  5814 D bt_hci  : do_postload posting postload work item
08-30 06:31:57.502  5798  5818 I bt_hci  : event_postload
08-30 06:31:57.502  5798  5818 I bt_vendor: sco_config_cb
08-30 06:31:57.502  5798  5818 I bt_hci  : sco_config_callback postload finished.
08-30 06:31:57.504  5798  5814 D bt_bte_conf: Device ID record 1 : primary
08-30 06:31:57.505  5798  5814 D bt_bte_conf:   vendorId            = 000f
08-30 06:31:57.505  5798  5814 D bt_bte_conf:   vendorIdSource      = 0001
08-30 06:31:57.505  5798  5814 D bt_bte_conf:   product             = 1200
,08-30 06:31:57.505  5798  5814 D bt_bte_conf:   version             = 1436
08-30 06:31:57.505  5798  5814 D bt_bte_conf:   clientExecutableURL = 
08-30 06:31:57.505  5798  5814 D bt_bte_conf:   serviceDescription  = 
08-30 06:31:57.505  5798  5814 D bt_bte_conf:   documentationURL    = 
08-30 06:31:57.505  5798  5814 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 06:31:57.505  5798  5811 D bt_stack_manager: event_start_up_stack finished
,08-30 06:31:57.506  5798  5810 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 06:31:57.506  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:57.506  5798  5810 D BluetoothAdapterProperties: Setting state to 15
08-30 06:31:57.506  5798  5810 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 06:31:57.507  5798  5810 I BluetoothAdapterState: Entering BleOnState
,08-30 06:31:57.512  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:57.516  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:57.516  5798  5810 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 06:31:57.516  5798  5810 D BluetoothAdapterProperties: Setting state to 11
,08-30 06:31:57.516  5798  5810 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 06:31:57.519  5798  5818 I bt_vendor: low_power_mode_cb
,08-30 06:31:57.524  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:57.526  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:31:57.528  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:57.528  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
,08-30 06:31:57.529  5798  5798 D HeadsetService: Received start request. Starting profile...
,08-30 06:31:57.532  5798  5798 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 06:31:57.532  5798  5798 D HeadsetStateMachine: make
,08-30 06:31:57.538  5798  5810 I BluetoothAdapterState: Entering PendingCommandState
,08-30 06:31:57.540  5798  5798 D HeadsetStateMachine: max_hf_connections = 1
,08-30 06:31:57.541  5798  5798 I bt_bluedroid: get_profile_interface handsfree
08-30 06:31:57.541  5798  5814 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 06:31:57.541  5798  5814 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-30 06:31:57.546  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
,08-30 06:31:57.546  5798  5798 D A2dpService: Received start request. Starting profile...
08-30 06:31:57.547  5798  5798 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 06:31:57.547  5798  5798 I bt_bluedroid: get_profile_interface avrcp
08-30 06:31:57.547  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 06:31:57.553  5798  5798 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 06:31:57.554  5798  5798 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 06:31:57.554  5798  5798 D A2dpStateMachine: make
,08-30 06:31:57.555  5798  5798 I bt_bluedroid: get_profile_interface a2dp
,08-30 06:31:57.556  5798  5814 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-30 06:31:57.557  5798  5830 D A2dpStateMachine: Enter Disconnected: -2
08-30 06:31:57.558  5798  5798 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 06:31:57.558  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
,08-30 06:31:57.560  5647  5647 D BluetoothInputDevice: Proxy object connected
,08-30 06:31:57.560  5798  5798 D HidService: Received start request. Starting profile...
08-30 06:31:57.560  5798  5798 I bt_bluedroid: get_profile_interface hidhost
08-30 06:31:57.560  5798  5798 D HidService: setHidService(): set to: null
08-30 06:31:57.560  5798  5814 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fc82d9
,08-30 06:31:57.560  5798  5814 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 06:31:57.561  5647  5647 D HidProfile: Bluetooth service connected
08-30 06:31:57.561  5798  5798 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 06:31:57.561  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
08-30 06:31:57.562  5798  5798 D HealthService: Received start request. Starting profile...
,08-30 06:31:57.563  5798  5798 I bt_bluedroid: get_profile_interface health
08-30 06:31:57.564  5798  5798 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 06:31:57.564  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
,08-30 06:31:57.566  5647  5647 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 06:31:57.566  5647  5647 D PanProfile: Bluetooth service connected
08-30 06:31:57.566  5798  5798 D PanService: Received start request. Starting profile...
08-30 06:31:57.566  5798  5798 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 06:31:57.566  5798  5798 I bt_bluedroid: get_profile_interface pan
,08-30 06:31:57.567  5798  5814 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 06:31:57.568  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
,08-30 06:31:57.570  5798  5798 D BluetoothMapService: Received start request. Starting profile...
,08-30 06:31:57.570  5798  5798 D BluetoothMapService: start()
08-30 06:31:57.572  5798  5798 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-30 06:31:57.573  5798  5798 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 06:31:57.573  5798  5798 D BluetoothMapAppObserver: createReceiver()
08-30 06:31:57.574  5798  5798 D BluetoothMapAppObserver: initObservers()
08-30 06:31:57.574  5798  5798 D BluetoothMapAppObserver: getEnabledAccountItems()
08-30 06:31:57.580  5798  5798 V SapService: SapBinder()
08-30 06:31:57.580  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
08-30 06:31:57.581  5798  5798 D SapService: Received start request. Starting profile...
08-30 06:31:57.581  5798  5798 V SapService: start()
,08-30 06:31:57.583  5798  5798 V BluetoothAdapterState: isTurningOff()=false
08-30 06:31:57.583  5798  5798 V BluetoothAdapterState: isTurningOn()=true
08-30 06:31:57.583  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:31:57.583  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:31:57.583  5798  5828 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 06:31:57.583  5798  5798 V BluetoothAdapterState: isTurningOff()=false
08-30 06:31:57.583  5798  5798 V BluetoothAdapterState: isTurningOn()=true
08-30 06:31:57.583  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:31:57.583  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isTurningOff()=false
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isTurningOn()=true
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isTurningOff()=false
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isTurningOn()=true
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isTurningOff()=false
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isTurningOn()=true
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isTurningOff()=false
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isTurningOn()=true
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:31:57.584  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:31:57.585  5798  5798 V BluetoothAdapterState: isTurningOff()=false
08-30 06:31:57.585  5798  5798 V BluetoothAdapterState: isTurningOn()=true
08-30 06:31:57.585  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:31:57.585  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:31:57.585  5798  5810 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 06:31:57.585  5798  5810 D BluetoothAdapterProperties: ScanMode =  20
08-30 06:31:57.586  5798  5810 D BluetoothAdapterProperties: State =  11
,08-30 06:31:57.583  5647  5647 D BluetoothMap: Proxy object connected
,08-30 06:31:57.588  5647  5647 D MapProfile: Bluetooth service connected
08-30 06:31:57.588  5647  5647 D BluetoothMap: getConnectedDevices()
08-30 06:31:57.588  5798  5814 D BluetoothAdapterProperties: Scan Mode:21
08-30 06:31:57.588  5798  5814 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 06:31:57.588  5798  5810 D BluetoothAdapterProperties: Setting state to 12
08-30 06:31:57.588  5798  5810 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 06:31:57.589   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 06:31:57.589  5798  5810 I BluetoothAdapterState: Entering OnState
08-30 06:31:57.589  5647  5657 D BluetoothMap: onBluetoothStateChange: up=true
08-30 06:31:57.589  3065  3077 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 06:31:57.591  3065  3076 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 06:31:57.592  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:57.592  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:57.592  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:57.592  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:31:57.592  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:31:57.592  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:57.592  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:57.592  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:57.592  3065  3065 D BluetoothA2dp: Proxy object connected
,08-30 06:31:57.593  3065  3077 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 06:31:57.595  3065  3065 D BluetoothInputDevice: Proxy object connected
08-30 06:31:57.595  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 06:31:57.595  3065  3065 D HidProfile: Bluetooth service connected
08-30 06:31:57.595  3449  3666 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 06:31:57.596  5647  5658 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 06:31:57.596   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 06:31:57.596  3065  3076 D BluetoothPan: onBluetoothStateChange on: true
08-30 06:31:57.598  3065  3065 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 06:31:57.598  3065  3065 D PanProfile: Bluetooth service connected
08-30 06:31:57.598  3065  3077 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 06:31:57.599  5647  5657 D BluetoothPan: onBluetoothStateChange on: true
08-30 06:31:57.599   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 06:31:57.599  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:57.599  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:57.599  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:57.599  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:31:57.599  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:31:57.599  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:57.599  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:57.599  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:57.599  5798  5798 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 06:31:57.599   928   928 D BluetoothA2dp: Proxy object connected
08-30 06:31:57.599  5647  5658 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 06:31:57.600  5798  5798 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-30 06:31:57.600   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 06:31:57.601  3065  3646 D BluetoothMap: onBluetoothStateChange: up=true
08-30 06:31:57.601  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:31:57.602  3065  3065 D BluetoothMap: Proxy object connected
08-30 06:31:57.602  3065  3065 D MapProfile: Bluetooth service connected
08-30 06:31:57.602  3065  3065 D BluetoothMap: getConnectedDevices()
08-30 06:31:57.603  5798  5798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 06:31:57.604   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 06:31:57.606  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:31:57.606  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:31:57.606  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:31:57.606  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:31:57.606  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:31:57.606  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:31:57.606  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:31:57.606  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:31:57.607  5798  5798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 06:31:57.607  5647  5647 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-30 06:31:57.609  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:31:57.611  5647  5647 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 06:31:57.611  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:57.612  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:57.612  5798  5798 D ObexServerSockets: Succeed to create listening sockets 
08-30 06:31:57.612  5798  5798 D ObexServerSockets0: startAccept()
08-30 06:31:57.612  5798  5798 D ObexServerSockets0: prepareForNewConnect()
08-30 06:31:57.614  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:31:57.614  5798  5798 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 06:31:57.614  5798  5798 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 06:31:57.615  5798  5798 D BluetoothMapService: onReceive
08-30 06:31:57.615  5798  5798 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 06:31:57.616  5798  5798 D BluetoothMapService: STATE_ON
08-30 06:31:57.616  5798  5838 D ObexServerSockets0: Accepting socket connection...
08-30 06:31:57.616  5798  5839 D ObexServerSockets0: Accepting socket connection...
08-30 06:31:57.618  5798  5840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 06:31:57.619  5647  5647 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 06:31:57.620  5798  5840 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-30 06:31:57.620  5798  5840 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-30 06:31:57.621  5647  5647 D BluetoothA2dp: Proxy object connected
,08-30 06:31:57.626  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 06:31:57.627  5647  5647 D DockEventReceiver: finishStartingService: stopping service
,08-30 06:31:57.635  5647  5647 D BluetoothPbap: Proxy object connected
08-30 06:31:57.636  5647  5647 D PbapServerProfile: Bluetooth service connected
,08-30 06:31:57.636  3065  3065 D BluetoothPbap: Proxy object connected
08-30 06:31:57.636  3065  3065 D PbapServerProfile: Bluetooth service connected
,08-30 06:31:57.641  5798  5798 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 06:31:57.641  5798  5798 D ObexServerSockets0: prepareForNewConnect()
08-30 06:31:57.643  5798  5844 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 06:31:57.656  5798  5848 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 06:31:57.657  5798  5848 I BtOppRfcommListener: Accept thread started.
,08-30 06:31:57.690  3065  3646 D BluetoothHeadset: Proxy object connected
,08-30 06:31:57.691   928   928 D BluetoothHeadset: Proxy object connected
08-30 06:31:57.691   928   928 D BluetoothHeadset: Proxy object connected
08-30 06:31:57.691  3065  3065 D HeadsetProfile: Bluetooth service connected
08-30 06:31:57.691  3449  3475 D BluetoothHeadset: Proxy object connected
08-30 06:31:57.691   928   928 D BluetoothHeadset: Proxy object connected
,08-30 06:31:57.695  3449  3468 D BluetoothHeadset: Proxy object connected
,08-30 06:31:57.697   928   945 D BluetoothHeadset: Proxy object connected
,08-30 06:31:57.698  3065  3643 D BluetoothHeadset: Proxy object connected
,08-30 06:31:57.699  3065  3065 D HeadsetProfile: Bluetooth service connected
,08-30 06:31:57.701   928   945 D BluetoothHeadset: Proxy object connected
,08-30 06:31:57.714  5647  5658 D BluetoothHeadset: Proxy object connected
,08-30 06:31:57.715  5647  5647 D HeadsetProfile: Bluetooth service connected
,08-30 06:31:58.157   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:31:59.159   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:31:59.189   928  2887 D ConnectivityService: handlePromptUnvalidated 101
,08-30 06:32:00.000   928   937 I art     : Background partial concurrent mark sweep GC freed 60153(3MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.063ms total 125.327ms
,08-30 06:32:00.160   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:01.161   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:01.423  5798  5810 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 06:32:01.423  5798  5810 D BluetoothAdapterProperties: Setting state to 13
,08-30 06:32:01.423  5798  5810 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 06:32:01.425  5798  5810 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 06:32:01.427  5798  5810 I BluetoothAdapterState: Entering PendingCommandState
08-30 06:32:01.431  5798  5798 D BluetoothMapService: onReceive
08-30 06:32:01.431  5798  5798 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 06:32:01.432  5798  5798 D BluetoothMapService: STATE_TURNING_OFF
,08-30 06:32:01.432  5798  5798 D BluetoothMapService: MAP Service closeService in
08-30 06:32:01.432  5798  5798 D BluetoothMapMasInstance0: MAP Service shutdown
,08-30 06:32:01.433  5798  5798 D ObexServerSockets0: shutdown(block = true)
08-30 06:32:01.435  5798  5798 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 06:32:01.436  5798  5798 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 06:32:01.436  5798  5839 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 06:32:01.436  5798  5838 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-30 06:32:01.438  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:32:01.438  5798  5814 D BluetoothAdapterProperties: Scan Mode:20
,08-30 06:32:01.438  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:32:01.438  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:01.438  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:01.438  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:32:01.438  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:32:01.438  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:32:01.438  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:32:01.438  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:32:01.438  5798  5810 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 06:32:01.439  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:32:01.440  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:32:01.440  5798  5823 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 06:32:01.441  5798  5798 I BtOppRfcommListener: stopping Accept Thread
08-30 06:32:01.442  5798  5848 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 06:32:01.443  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:32:01.443  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:32:01.443  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:01.443  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:01.443  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:32:01.443  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 06:32:01.443  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:32:01.443  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:32:01.443  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:32:01.443  5798  5848 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 06:32:01.444  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:32:01.445  5798  5798 D HeadsetService: Received stop request...Stopping profile...
08-30 06:32:01.445  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:32:01.447  3065  3646 D BluetoothHeadset: Proxy object disconnected
08-30 06:32:01.447  5647  5647 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 06:32:01.447   928   928 D BluetoothHeadset: Proxy object disconnected
08-30 06:32:01.447   928   928 D BluetoothHeadset: Proxy object disconnected
08-30 06:32:01.447  3449  3666 D BluetoothHeadset: Proxy object disconnected
08-30 06:32:01.447  5798  5798 D A2dpService: Received stop request...Stopping profile...
08-30 06:32:01.448   928   928 D BluetoothHeadset: Proxy object disconnected
08-30 06:32:01.448  5798  5830 D A2dpStateMachine: Exit Disconnected: -1
08-30 06:32:01.449  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:32:01.449  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:32:01.449  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:01.449  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:01.449  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:32:01.449  5587  5587 V io.jxcore.node.Connecti,vityMonitor:     - is Bluetooth enabled: false
08-30 06:32:01.449  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:32:01.449  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:32:01.449  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:32:01.449  5647  5657 D BluetoothHeadset: Proxy object disconnected
08-30 06:32:01.450   928   928 D BluetoothA2dp: Proxy object disconnected
08-30 06:32:01.451  5798  5798 D HidService: Received stop request...Stopping profile...
08-30 06:32:01.451  5798  5798 D HidService: Stopping Bluetooth HidService
08-30 06:32:01.451  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 06:32:01.451  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:32:01.455  5647  5647 D DockEventReceiver: finishStartingService: stopping service
08-30 06:32:01.455  5798  5798 V BluetoothAdapterState: isTurningOff()=true
08-30 06:32:01.455  5798  5798 V BluetoothAdapterState: isTurningOn()=false
08-30 06:32:01.455  5647  5647 D HeadsetProfile: Bluetooth service disconnected
08-30 06:32:01.455  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:01.456  5647  5647 D BluetoothA2dp: Proxy object disconnected
08-30 06:32:01.456  5647  5647 D BluetoothInputDevice: Proxy object disconnected
08-30 06:32:01.456  5647  5647 D HidProfile: Bluetooth service disconnected
08-30 06:32:01.457  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:32:01.457  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:32:01.457  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:01.458  5798  5798 D HealthService: Received stop request...Stopping profile...
08-30 06:32:01.459  3065  3065 D HeadsetProfile: Bluetooth service disconnected
08-30 06:32:01.459  3065  3065 D BluetoothA2dp: Proxy object disconnected
08-30 06:32:01.459  3065  3065 D BluetoothInputDevice: Proxy object disconnected
08-30 06:32:01.459  3065  3065 D HidProfile: Bluetooth service disconnected
08-30 06:32:01.460  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:01.460  5798  5798 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 06:32:01.460  5798  5798 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 06:32:01.460  5798  5821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 06:32:01.460  5798  5821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 06:32:01.460  5798  5821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 06:32:01.460  5798  5814 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 06:32:01.461  5798  5798 D PanService: Received stop request...Stopping profile...
08-30 06:32:01.461  5798  5814 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 06:32:01.462  3065  3065 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 06:32:01.462  5647  5647 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 06:32:01.462  5798  5798 V BluetoothAdapterState: isTurningOff()=true
08-30 06:32:01.462  3065  3065 D PanProfile: Bluetooth service disconnected
08-30 06:32:01.462  5647  5647 D PanProfile: Bluetooth service disconnected
08-30 06:32:01.462  5798  5798 V BluetoothAdapterState: isTurningOn()=false
08-30 06:32:01.462  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:32:01.462  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:32:01.462  5798  5798 D BluetoothMapService: Received stop request...Stopping profile...
08-30 06:32:01.462  5798  5798 D BluetoothMapService: stop()
,08-30 06:32:01.463  5798  5798 D BluetoothMapAppObserver: deinitObservers()
08-30 06:32:01.463  5798  5798 D BluetoothMapAppObserver: removeReceiver()
,08-30 06:32:01.465  3065  3065 D BluetoothMap: Proxy object disconnected
,08-30 06:32:01.465  3065  3065 D MapProfile: Bluetooth service disconnected
08-30 06:32:01.465  5647  5647 D BluetoothMap: Proxy object disconnected
08-30 06:32:01.465  5647  5647 D MapProfile: Bluetooth service disconnected
,08-30 06:32:01.466  5798  5821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 06:32:01.467  5798  5798 V BluetoothAdapterState: isTurningOff()=true
08-30 06:32:01.467  5798  5821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 06:32:01.467  5798  5798 V BluetoothAdapterState: isTurningOn()=false
08-30 06:32:01.467  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:32:01.467  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:32:01.467  5798  5814 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 06:32:01.467  5798  5821 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 06:32:01.467  5798  5821 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 06:32:01.467  5798  5821 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 06:32:01.467  5798  5821 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 06:32:01.468  5798  5798 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 06:32:01.468  5798  5798 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 06:32:01.468  5798  5798 D SapService: Received stop request...Stopping profile...
08-30 06:32:01.468  5798  5814 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 06:32:01.468  5798  5798 V SapService: stop()
08-30 06:32:01.469  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 06:32:01.469  5798  5798 V BluetoothAdapterState: isTurningOff()=true
08-30 06:32:01.469  5798  5798 V BluetoothAdapterState: isTurningOn()=false
08-30 06:32:01.469  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:32:01.469  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:32:01.469  5798  5798 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 06:32:01.470  5798  5814 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-30 06:32:01.470  5798  5798 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 06:32:01.470  5798  5798 V BluetoothAdapterState: isTurningOff()=true
08-30 06:32:01.470  5798  5798 V BluetoothAdapterState: isTurningOn()=false
08-30 06:32:01.470  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:32:01.470  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:32:01.470  5798  5798 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 06:32:01.470  5798  5798 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 06:32:01.471  5798  5798 D BluetoothMapService: MAP Service closeService in
08-30 06:32:01.471  5798  5798 V BluetoothAdapterState: isTurningOff()=true
08-30 06:32:01.471  5798  5798 V BluetoothAdapterState: isTurningOn()=false
08-30 06:32:01.471  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 06:32:01.471  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 06:32:01.471  5798  5798 D BluetoothMapService: cleanup()
08-30 06:32:01.471  5798  5798 D BluetoothMapService: MAP Service closeService in
08-30 06:32:01.472  3065  3065 D BluetoothPbap: Proxy object disconnected
08-30 06:32:01.473  3065  3065 D PbapServerProfile: Bluetooth service disconnected
08-30 06:32:01.473  5647  5647 D BluetoothPbap: Proxy object disconnected
08-30 06:32:01.473  5647  5647 D PbapServerProfile: Bluetooth service disconnected
08-30 06:32:01.473  5798  5798 V BluetoothAdapterState: isTurningOff()=true
,08-30 06:32:01.473  5798  5798 V BluetoothAdapterState: isTurningOn()=false
08-30 06:32:01.473  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:32:01.473  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:32:01.473  5798  5810 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 06:32:01.473  5798  5810 D BluetoothAdapterProperties: Setting state to 15
08-30 06:32:01.473  5798  5810 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 06:32:01.474  5798  5810 I BluetoothAdapterState: Entering BleOnState
,08-30 06:32:01.474   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 06:32:01.474  5647  5658 D BluetoothMap: onBluetoothStateChange: up=false
08-30 06:32:01.475  3065  3643 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 06:32:01.476  3065  5586 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 06:32:01.476  3065  3076 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 06:32:01.477  5647  5657 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 06:32:01.477  3449  3475 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 06:32:01.477  5647  5658 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 06:32:01.477   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 06:32:01.478  3065  3077 D BluetoothPan: onBluetoothStateChange on: false
,08-30 06:32:01.478  3065  3646 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 06:32:01.478  5647  5657 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 06:32:01.479  5647  5658 D BluetoothPan: onBluetoothStateChange on: false
08-30 06:32:01.479   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 06:32:01.480  5647  5657 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 06:32:01.480   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 06:32:01.480  3065  3643 D BluetoothMap: onBluetoothStateChange: up=false
08-30 06:32:01.481  5798  5810 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 06:32:01.481  5798  5810 D BluetoothAdapterProperties: Setting state to 16
08-30 06:32:01.481  5798  5810 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 06:32:01.482  5798  5810 D BluetoothAdapterProperties: onBleDisable
08-30 06:32:01.482  5798  5810 I BluetoothAdapterState: Entering PendingCommandState
08-30 06:32:01.482  5798  5811 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 06:32:01.483  5798  5821 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 06:32:01.483  5798  5821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 06:32:01.483  5798  5814 D BluetoothAdapterProperties: Scan Mode:20
,08-30 06:32:01.484  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:32:01.485  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:01.486  5647  5647 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 06:32:01.486  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:32:01.488  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:01.489  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:01.491  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:01.492  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 06:32:01.492  5647  5647 D DockEventReceiver: finishStartingService: stopping service
,08-30 06:32:01.690  5798  5814 I bt_hci  : shut_down
,08-30 06:32:01.694  5798  5818 D bt_hwcfg: hw_epilog_process
,08-30 06:32:01.694  5798  5818 I bt_vendor: low_power_mode_cb
,08-30 06:32:01.696  5798  5818 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-30 06:32:01.696  5798  5818 I bt_vendor: epilog_cb
08-30 06:32:01.696  5798  5818 I bt_hci  : epilog_finished_callback
,08-30 06:32:01.699  5798  5814 I bt_hci_h4: hal_close
,08-30 06:32:01.700  5798  5814 I bt_userial_vendor: device fd = 51 close
,08-30 06:32:01.806  5798  5811 D bt_stack_manager: event_shut_down_stack finished.
,08-30 06:32:01.807  5798  5810 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 06:32:01.809  5798  5810 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-30 06:32:01.810  5798  5798 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 06:32:01.810  5798  5798 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 06:32:01.810  5798  5798 D BtGatt.GattService: stop()
08-30 06:32:01.811  5798  5798 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 06:32:01.813  5798  5798 V BluetoothAdapterState: isTurningOff()=false
08-30 06:32:01.813  5798  5798 V BluetoothAdapterState: isTurningOn()=false
08-30 06:32:01.813  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:32:01.813  5798  5798 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 06:32:01.813  5798  5810 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 06:32:01.813  5798  5810 D BluetoothAdapterProperties: Setting state to 10
08-30 06:32:01.814  5798  5810 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 06:32:01.815  5798  5810 I BluetoothAdapterState: Entering OffState
,08-30 06:32:01.816   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 06:32:01.824  5798  5798 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 06:32:01.825  5798  5798 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 06:32:01.825  5798  5798 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 06:32:01.826  5798  5811 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-30 06:32:01.827  5798  5811 D bt_stack_manager: event_clean_up_stack finished.
,08-30 06:32:01.829  5798  5798 I art     : System.exit called, status: 0
08-30 06:32:01.829  5798  5798 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 06:32:01.854   928  3477 I ActivityManager: Process com.android.bluetooth (pid 5798) has died
,08-30 06:32:02.161   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-30 06:32:06.420  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 06:32:06.421  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:32:06.426  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 06:32:06.427  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ea3f691 removed from the list
08-30 06:32:06.427  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:32:06.427  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 06:32:06.427  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:32:06.429  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 06:32:06.429  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13171f7 added. We now have 4 listener(s)
08-30 06:32:06.430  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 06:32:06.432  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:06.432  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13171f7 removed from the list
08-30 06:32:06.432  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:32:06.433  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:06.433  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:06.436  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 06:32:06.436  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ed0f864 added. We now have 4 listener(s)
08-30 06:32:06.436  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 06:32:07.162   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:08.163   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:09.164   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:10.165   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:11.167   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:11.445  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:32:11.484   928   945 I ActivityManager: Start proc 5856:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 06:32:11.572  5856  5856 D AdapterServiceConfig: Adding HeadsetService
,08-30 06:32:11.572  5856  5856 D AdapterServiceConfig: Adding A2dpService
08-30 06:32:11.572  5856  5856 D AdapterServiceConfig: Adding HidService
08-30 06:32:11.572  5856  5856 D AdapterServiceConfig: Adding HealthService
08-30 06:32:11.572  5856  5856 D AdapterServiceConfig: Adding PanService
08-30 06:32:11.572  5856  5856 D AdapterServiceConfig: Adding GattService
08-30 06:32:11.573  5856  5856 D AdapterServiceConfig: Adding BluetoothMapService
08-30 06:32:11.573  5856  5856 D AdapterServiceConfig: Adding SapService
,08-30 06:32:11.583   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1483866:true
,08-30 06:32:11.583  5856  5856 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 06:32:11.586  5856  5856 I bt_bluedroid: init
08-30 06:32:11.586  5856  5868 I BluetoothAdapterState: Entering OffState
,08-30 06:32:11.588  5856  5869 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 06:32:11.589  5856  5869 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 06:32:11.589  5856  5869 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 06:32:11.589  5856  5869 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 06:32:11.590  5856  5856 I bt_bluedroid: get_profile_interface socket
,08-30 06:32:11.592  5856  5872 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-30 06:32:11.592  5856  5856 I bt_bluedroid: get_profile_interface sdp
08-30 06:32:11.593  5856  5872 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-30 06:32:11.596  5856  5867 I bt_bluedroid: config_hci_snoop_log
08-30 06:32:11.597   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 06:32:11.601  5856  5868 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 06:32:11.601  5856  5868 D BluetoothAdapterProperties: Setting state to 14
08-30 06:32:11.601  5856  5868 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-30 06:32:11.602  5856  5868 D BluetoothBondStateMachine: make
08-30 06:32:11.604  5856  5873 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 06:32:11.607  5856  5868 I BluetoothAdapterState: Entering PendingCommandState
,08-30 06:32:11.608  5856  5856 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 06:32:11.610  5856  5856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
08-30 06:32:11.611  5856  5856 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 06:32:11.611  5856  5856 D BtGatt.GattService: Received start request. Starting profile...
08-30 06:32:11.611  5856  5856 D BtGatt.GattService: start()
08-30 06:32:11.611  5856  5856 I bt_bluedroid: get_profile_interface gatt
,08-30 06:32:11.612  5856  5856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
08-30 06:32:11.612  5856  5856 D BtGatt.AdvertiseManager: advertise manager created
,08-30 06:32:11.619  5856  5856 V BluetoothAdapterState: isTurningOff()=false
08-30 06:32:11.619  5856  5856 V BluetoothAdapterState: isTurningOn()=false
08-30 06:32:11.619  5856  5856 V BluetoothAdapterState: isBleTurningOn()=true
,08-30 06:32:11.619  5856  5856 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:32:11.620  5856  5868 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 06:32:11.620  5856  5868 I bt_bluedroid: enable
08-30 06:32:11.620  5856  5869 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 06:32:11.621  5856  5869 I bt_hci  : start_up
,08-30 06:32:11.626  5856  5869 I bt_vendor: alloc value 0xf406904d
,08-30 06:32:11.626  5856  5869 I bt_vendor: init
08-30 06:32:11.626  5856  5869 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 06:32:11.626  5856  5869 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 06:32:11.749  5856  5869 D bt_hci  : start_up starting async portion
08-30 06:32:11.750  5856  5876 I bt_hci  : event_finish_startup
,08-30 06:32:11.750  5856  5876 I bt_hci_h4: hal_open
08-30 06:32:11.750  5856  5876 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 06:32:11.740  5877  5877 W irq/448-msm_hs_: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
08-30 06:32:11.754  5856  5876 I bt_userial_vendor: device fd = 51 open
,08-30 06:32:11.769  5856  5876 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 06:32:11.773  5856  5876 D bt_hwcfg: Chipset BCM4358A3
,08-30 06:32:11.774  5856  5876 D bt_hwcfg: Target name = [BCM4358A3]
08-30 06:32:11.774  5856  5876 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-30 06:32:12.168   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-30 06:32:12.271  5856  5876 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-30 06:32:12.271  5856  5876 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 06:32:12.272  5856  5876 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 06:32:12.406  5856  5876 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 06:32:12.407  5856  5876 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-30 06:32:12.409  5856  5876 I bt_hwcfg: vendor lib fwcfg completed
08-30 06:32:12.409  5856  5876 I bt_vendor: firmware callback
,08-30 06:32:12.409  5856  5876 I bt_hci  : firmware_config_callback
,08-30 06:32:12.418  5856  5879 I bt_btu  : btu_task pending for preload complete event
08-30 06:32:12.418  5856  5879 I bt_btu_task: Bluetooth chip preload is complete
,08-30 06:32:12.418  5856  5879 I bt_btu  : btu_task received preload complete event
,08-30 06:32:12.424  5856  5879 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 06:32:12.425  5856  5879 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 06:32:12.425  5856  5879 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 06:32:12.425  5856  5879 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 06:32:12.425  5856  5879 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 06:32:12.425  5856  5879 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 06:32:12.425  5856  5879 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 06:32:12.425  5856  5879 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 06:32:12.426  5856  5879 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 06:32:12.426  5856  5879 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 06:32:12.426  5856  5879 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 06:32:12.426  5856  5879 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 06:32:12.426  5856  5879 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 06:32:12.426  5856  5879 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 06:32:12.426  5856  5879 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 06:32:12.526  5856  5879 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fe6c99
08-30 06:32:12.526  5856  5879 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fe6c99 
,08-30 06:32:12.616  5856  5872 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 06:32:12.618  5856  5872 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 06:32:12.619  5856  5872 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-30 06:32:12.621  5856  5872 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-30 06:32:12.623  5856  5872 D BluetoothAdapterProperties: Scan Mode:20
08-30 06:32:12.624  5856  5872 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 06:32:12.624  5856  5872 D bt_hci  : do_postload posting postload work item
08-30 06:32:12.625  5856  5876 I bt_hci  : event_postload
08-30 06:32:12.625  5856  5876 I bt_vendor: sco_config_cb
08-30 06:32:12.625  5856  5876 I bt_hci  : sco_config_callback postload finished.
,08-30 06:32:12.627  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:32:12.629  5856  5872 D bt_bte_conf: Device ID record 1 : primary
08-30 06:32:12.629  5856  5872 D bt_bte_conf:   vendorId            = 000f
,08-30 06:32:12.629  5856  5872 D bt_bte_conf:   vendorIdSource      = 0001
08-30 06:32:12.629  5856  5872 D bt_bte_conf:   product             = 1200
08-30 06:32:12.629  5856  5872 D bt_bte_conf:   version             = 1436
08-30 06:32:12.629  5856  5872 D bt_bte_conf:   clientExecutableURL = 
08-30 06:32:12.629  5856  5872 D bt_bte_conf:   serviceDescription  = 
,08-30 06:32:12.629  5856  5872 D bt_bte_conf:   documentationURL    = 
08-30 06:32:12.629  5856  5872 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 06:32:12.629  5856  5869 D bt_stack_manager: event_start_up_stack finished
08-30 06:32:12.630  5856  5868 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 06:32:12.630  5856  5868 D BluetoothAdapterProperties: Setting state to 15
08-30 06:32:12.630  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:12.630  5856  5868 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 06:32:12.632  5856  5868 I BluetoothAdapterState: Entering BleOnState
,08-30 06:32:12.635  5856  5868 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 06:32:12.635  5856  5868 D BluetoothAdapterProperties: Setting state to 11
08-30 06:32:12.635  5856  5868 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 06:32:12.636  5856  5876 I bt_vendor: low_power_mode_cb
,08-30 06:32:12.639  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:32:12.643  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:12.644  5856  5856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
,08-30 06:32:12.645  5856  5856 D HeadsetService: Received start request. Starting profile...
08-30 06:32:12.647  5856  5856 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 06:32:12.647  5856  5856 D HeadsetStateMachine: make
,08-30 06:32:12.655  5856  5868 I BluetoothAdapterState: Entering PendingCommandState
,08-30 06:32:12.655  5856  5856 D HeadsetStateMachine: max_hf_connections = 1
,08-30 06:32:12.655  5856  5856 I bt_bluedroid: get_profile_interface handsfree
08-30 06:32:12.656  5856  5872 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 06:32:12.656  5856  5872 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-30 06:32:12.659  5856  5856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
,08-30 06:32:12.660  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 06:32:12.661  5856  5856 D A2dpService: Received start request. Starting profile...
08-30 06:32:12.661  5856  5856 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 06:32:12.661  5856  5856 I bt_bluedroid: get_profile_interface avrcp
,08-30 06:32:12.666  5856  5856 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 06:32:12.667  5856  5856 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 06:32:12.667  5856  5856 D A2dpStateMachine: make
08-30 06:32:12.667  5856  5856 I bt_bluedroid: get_profile_interface a2dp
,08-30 06:32:12.668  5856  5872 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-30 06:32:12.669  5856  5887 D A2dpStateMachine: Enter Disconnected: -2
08-30 06:32:12.669  5856  5856 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 06:32:12.670  5856  5856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
08-30 06:32:12.670  5856  5856 D HidService: Received start request. Starting profile...
08-30 06:32:12.671  5856  5856 I bt_bluedroid: get_profile_interface hidhost
08-30 06:32:12.671  5856  5856 D HidService: setHidService(): set to: null
08-30 06:32:12.671  5856  5872 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fc82d9
08-30 06:32:12.671  5856  5872 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 06:32:12.671  5856  5856 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 06:32:12.672  5856  5856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
08-30 06:32:12.672  5856  5856 D HealthService: Received start request. Starting profile...
,08-30 06:32:12.674  5856  5856 I bt_bluedroid: get_profile_interface health
,08-30 06:32:12.674  5856  5856 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 06:32:12.675  5856  5856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
08-30 06:32:12.675  5856  5856 D PanService: Received start request. Starting profile...
08-30 06:32:12.675  5856  5856 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 06:32:12.676  5856  5856 I bt_bluedroid: get_profile_interface pan
08-30 06:32:12.676  5856  5872 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 06:32:12.677  5856  5856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
08-30 06:32:12.678  5856  5856 D BluetoothMapService: Received start request. Starting profile...
08-30 06:32:12.678  5856  5856 D BluetoothMapService: start()
08-30 06:32:12.680  5856  5856 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 06:32:12.681  5856  5856 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 06:32:12.681  5856  5856 D BluetoothMapAppObserver: createReceiver()
,08-30 06:32:12.682  5856  5856 D BluetoothMapAppObserver: initObservers()
,08-30 06:32:12.682  5856  5856 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 06:32:12.689  5856  5856 V SapService: SapBinder()
,08-30 06:32:12.689  5856  5856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
08-30 06:32:12.690  5856  5856 D SapService: Received start request. Starting profile...
08-30 06:32:12.690  5856  5856 V SapService: start()
,08-30 06:32:12.692  5856  5856 V BluetoothAdapterState: isTurningOff()=false
,08-30 06:32:12.692  5856  5856 V BluetoothAdapterState: isTurningOn()=true
08-30 06:32:12.692  5856  5856 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:32:12.692  5856  5885 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 06:32:12.692  5856  5856 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:32:12.692  5856  5856 V BluetoothAdapterState: isTurningOff()=false
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isTurningOn()=true
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isTurningOff()=false
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isTurningOn()=true
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isTurningOff()=false
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isTurningOn()=true
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isTurningOff()=false
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isTurningOn()=true
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isTurningOff()=false
,08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isTurningOn()=true
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:32:12.693  5856  5856 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:32:12.695  5856  5856 V BluetoothAdapterState: isTurningOff()=false
08-30 06:32:12.695  5856  5856 V BluetoothAdapterState: isTurningOn()=true
08-30 06:32:12.695  5856  5856 V BluetoothAdapterState: isBleTurningOn()=false
08-30 06:32:12.695  5856  5856 V BluetoothAdapterState: isBleTurningOff()=false
08-30 06:32:12.696  5856  5868 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 06:32:12.696  5856  5868 D BluetoothAdapterProperties: ScanMode =  20
08-30 06:32:12.696  5856  5868 D BluetoothAdapterProperties: State =  11
08-30 06:32:12.697  5856  5868 D BluetoothAdapterProperties: Setting state to 12
08-30 06:32:12.697  5856  5868 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 06:32:12.697  5856  5868 I BluetoothAdapterState: Entering OnState
08-30 06:32:12.697   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 06:32:12.698  5647  5658 D BluetoothMap: onBluetoothStateChange: up=true
08-30 06:32:12.698  5856  5872 D BluetoothAdapterProperties: Scan Mode:21
08-30 06:32:12.698  5856  5872 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 06:32:12.700  3065  3646 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 06:32:12.701  3065  3643 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 06:32:12.702  3065  3065 D BluetoothA2dp: Proxy object connected
08-30 06:32:12.703  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:32:12.703  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:12.703  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:12.703  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:32:12.703  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:32:12.703  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:32:12.703  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:32:12.703  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:32:12.703  3065  3077 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 06:32:12.705  3065  3065 D BluetoothInputDevice: Proxy object connected
08-30 06:32:12.705  5647  5658 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 06:32:12.705  3065  3065 D HidProfile: Bluetooth service connected
08-30 06:32:12.705  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:32:12.705  3449  3468 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 06:32:12.706  5647  5657 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 06:32:12.707   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 06:32:12.708  3065  5586 D BluetoothPan: onBluetoothStateChange on: true
08-30 06:32:12.708  5856  5856 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 06:32:12.708  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:32:12.708  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:12.708  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:12.708  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:32:12.708  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:32:12.708  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:32:12.708  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:32:12.708  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 06:32:12.708  5856  5856 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 06:32:12.709  5647  5647 D BluetoothMap: Proxy object connected
08-30 06:32:12.709  5647  5647 D MapProfile: Bluetooth service connected
08-30 06:32:12.709  5647  5647 D BluetoothMap: getConnectedDevices()
08-30 06:32:12.710  5856  5856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 06:32:12.710  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:32:12.710  3065  3076 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 06:32:12.710  5647  5658 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 06:32:12.711  5856  5856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 06:32:12.712  5647  5657 D BluetoothPan: onBluetoothStateChange on: true
08-30 06:32:12.712  5856  5856 D ObexServerSockets: Succeed to create listening sockets 
08-30 06:32:12.712  5856  5856 D ObexServerSockets0: startAccept()
,08-30 06:32:12.712  5856  5856 D ObexServerSockets0: prepareForNewConnect()
08-30 06:32:12.713   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 06:32:12.714   928   928 D BluetoothA2dp: Proxy object connected
08-30 06:32:12.714  5647  5658 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 06:32:12.714  5856  5856 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 06:32:12.715  5856  5856 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 06:32:12.715  5856  5895 D ObexServerSockets0: Accepting socket connection...
08-30 06:32:12.715  5856  5896 D ObexServerSockets0: Accepting socket connection...
08-30 06:32:12.715   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 06:32:12.716  3065  3643 D BluetoothMap: onBluetoothStateChange: up=true
08-30 06:32:12.716  3065  3065 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 06:32:12.716  3065  3065 D PanProfile: Bluetooth service connected
08-30 06:32:12.717  3065  3065 D BluetoothMap: Proxy object connected
,08-30 06:32:12.717  3065  3065 D MapProfile: Bluetooth service connected
08-30 06:32:12.717  3065  3065 D BluetoothMap: getConnectedDevices()
08-30 06:32:12.719  5856  5856 D BluetoothMapService: onReceive
08-30 06:32:12.719  5856  5856 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 06:32:12.720  5856  5856 D BluetoothMapService: STATE_ON
08-30 06:32:12.720   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 06:32:12.721  5647  5647 D BluetoothInputDevice: Proxy object connected
08-30 06:32:12.722  5647  5647 D HidProfile: Bluetooth service connected
08-30 06:32:12.722  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:12.723  5856  5897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 06:32:12.723  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:12.724  5647  5647 D BluetoothA2dp: Proxy object connected
08-30 06:32:12.725  5856  5897 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-30 06:32:12.725  5856  5897 D BluetoothSdpJni: SDP Create record success - handle: 1
08-30 06:32:12.725  5647  5647 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 06:32:12.726  5647  5647 D PanProfile: Bluetooth service connected
,08-30 06:32:12.730  5647  5647 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 06:32:12.736  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 06:32:12.739  5647  5647 D DockEventReceiver: finishStartingService: stopping service
,08-30 06:32:12.744  5647  5647 D BluetoothPbap: Proxy object connected
,08-30 06:32:12.744  5647  5647 D PbapServerProfile: Bluetooth service connected
,08-30 06:32:12.747  3065  3065 D BluetoothPbap: Proxy object connected
08-30 06:32:12.747  5856  5856 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 06:32:12.747  3065  3065 D PbapServerProfile: Bluetooth service connected
08-30 06:32:12.747  5856  5856 D ObexServerSockets0: prepareForNewConnect()
,08-30 06:32:12.749  5856  5901 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 06:32:12.763  5856  5905 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 06:32:12.764  5856  5905 I BtOppRfcommListener: Accept thread started.
,08-30 06:32:12.799  3065  3643 D BluetoothHeadset: Proxy object connected
,08-30 06:32:12.799  3065  3065 D HeadsetProfile: Bluetooth service connected
08-30 06:32:12.799   928   928 D BluetoothHeadset: Proxy object connected
08-30 06:32:12.799   928   928 D BluetoothHeadset: Proxy object connected
08-30 06:32:12.799  3449  3666 D BluetoothHeadset: Proxy object connected
08-30 06:32:12.800   928   928 D BluetoothHeadset: Proxy object connected
08-30 06:32:12.800  5647  5658 D BluetoothHeadset: Proxy object connected
,08-30 06:32:12.801  5647  5647 D HeadsetProfile: Bluetooth service connected
,08-30 06:32:12.805  5647  5657 D BluetoothHeadset: Proxy object connected
,08-30 06:32:12.806  3449  3475 D BluetoothHeadset: Proxy object connected
,08-30 06:32:12.806  5647  5647 D HeadsetProfile: Bluetooth service connected
08-30 06:32:12.807   928   945 D BluetoothHeadset: Proxy object connected
,08-30 06:32:12.811  3065  3077 D BluetoothHeadset: Proxy object connected
,08-30 06:32:12.811  3065  3065 D HeadsetProfile: Bluetooth service connected
,08-30 06:32:12.815   928   945 D BluetoothHeadset: Proxy object connected
,08-30 06:32:16.460  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:32:16.460  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:16.460  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:16.460  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 06:32:16.460  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:32:16.460  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:32:16.460  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:32:16.460  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 06:32:16.465  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 06:32:16.466  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:16.466  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ed0f864 removed from the list
08-30 06:32:16.466  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:32:16.466  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:16.466  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:16.467  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 06:32:16.468  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c006acd added. We now have 4 listener(s)
08-30 06:32:16.468  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 06:32:16.471   928  3342 D WifiService: setWifiEnabled: false pid=5587, uid=10077
,08-30 06:32:16.472   928  3342 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 06:32:21.481  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:32:21.482   928  3474 D WifiService: setWifiEnabled: true pid=5587, uid=10077
08-30 06:32:21.482   928  3474 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 06:32:21.495   507   923 D SoftapController: Softap fwReload - Ok
,08-30 06:32:21.500   507   923 D CommandListener: Setting iface cfg
08-30 06:32:21.500   507   923 D CommandListener: Trying to bring down wlan0
08-30 06:32:21.501   507   923 D CommandListener: Clearing all IP addresses on wlan0
08-30 06:32:21.506   928  2885 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-30 06:32:22.105   928  2885 D wifi    : set interface wlan0 flags (UP)
,08-30 06:32:22.110   928  2885 I WifiHAL : Initializing wifi
08-30 06:32:22.110   928  2885 I WifiHAL : Creating socket
,08-30 06:32:22.113   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 06:32:22.116   928  2885 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-30 06:32:22.117   928  2885 D wifi    : Did set static halHandle = 0x7f665494e0
,08-30 06:32:22.117   928  2885 D wifi    : halHandle = 0x7f665494e0, mVM = 0x7f829cd140, mCls = 0x12c6
08-30 06:32:22.132   928  2885 D wifi    : array field set
08-30 06:32:22.132   928  2885 I WifiNative-HAL: interface[0] = wlan0
,08-30 06:32:22.133   928  5910 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547177665760
08-30 06:32:22.133   928  5910 D wifi    : waitForHalEvents called, vm = 0x7f829cd140, obj = 0x12c6, env = 0x7f6448aa40
,08-30 06:32:22.168   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:22.177  5911  5911 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 06:32:22.197  5911  5911 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 06:32:22.204  5911  5911 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 06:32:22.204  5911  5911 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-30 06:32:22.234   928  2885 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 06:32:22.240  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:22.243   928  2885 D WifiConfigStore: Loading config and enabling all networks 
,08-30 06:32:22.248  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:32:22.248  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:22.248  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:22.248  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:32:22.248  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:32:22.248  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:32:22.248  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:32:22.248  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 06:32:22.250  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 06:32:22.253  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:32:22.253  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:22.253  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:22.253  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:32:22.253  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:32:22.253  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 06:32:22.253  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 06:32:22.253  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 06:32:22.256  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 06:32:22.257  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:22.259   928  2885 D WifiConfigStore: loaded 0 passpoint configs
,08-30 06:32:22.259   928  2885 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 06:32:22.260   928  2885 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 06:32:22.261   928  2885 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 06:32:22.261   928  2885 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-30 06:32:22.261   928  2885 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 06:32:22.266  4156  4156 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 06:32:22.266   928  2885 D WifiNative-HAL: Setting external_sim to 1
08-30 06:32:22.266   928  2885 D wifi    : setting dfs flag to true, 0x7f674e8d40
08-30 06:32:22.267   928  2885 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 06:32:22.267   928  2885 D wifi    : setting scan oui 0x7f674e8d40
08-30 06:32:22.267   928  2885 D WifiHAL : Sending mac address OUI
,08-30 06:32:22.281   928  2885 E native  : do suspend true
,08-30 06:32:22.287   928  2885 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-30 06:32:22.287   928   928 D RttService: SCAN_AVAILABLE : 3
08-30 06:32:22.287   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-30 06:32:22.287   928  2992 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 06:32:22.288   507   923 D CommandListener: Setting iface cfg
,08-30 06:32:22.292   928  2884 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '96 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 96 Failed to set address (No such device)'
,08-30 06:32:22.292   928  2884 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 06:32:22.295   928  2884 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 06:32:22.299   928  2884 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-30 06:32:22.317   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=256343 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,08-30 06:32:23.169   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:24.170   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:25.171   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:25.507  5911  5911 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 06:32:25.538   928  2885 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-30 06:32:25.545   928  2885 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
08-30 06:32:25.546   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 06:32:25.561   928  2885 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-30 06:32:25.612   928  2885 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-30 06:32:25.943  5911  5911 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 06:32:25.981  5911  5911 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 06:32:25.982  5911  5911 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-30 06:32:25.996   928  2885 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 06:32:25.997   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 06:32:25.997   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 06:32:26.014   928  2885 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 06:32:26.028   507   923 D CommandListener: Setting iface cfg
,08-30 06:32:26.034   928  2885 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 06:32:26.042   928  2885 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 06:32:26.068   928  5916 D DhcpClient: Receive thread started
,08-30 06:32:26.152   928  2885 E native  : do suspend false
,08-30 06:32:26.167   928  5915 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 06:32:26.171   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:26.181   928  5916 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-30 06:32:26.182   928  5915 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-30 06:32:26.184   928  5915 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,08-30 06:32:26.215   928  5916 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
08-30 06:32:26.215   928  5915 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-30 06:32:26.218   507   923 D CommandListener: Setting iface cfg
,08-30 06:32:26.228   928  5915 D DhcpClient: Scheduling renewal in 86399s
,08-30 06:32:26.230   928  2885 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 06:32:26.232   928  2885 E native  : do suspend true
,08-30 06:32:26.248   928  2885 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 06:32:26.251   928  2885 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 06:32:26.252   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 06:32:26.254   928  2885 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 06:32:26.261   928  2887 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 06:32:26.297   928  2887 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 06:32:26.298   928  2887 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 06:32:26.299   928  2887 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 06:32:26.301   928  2887 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 06:32:26.303   928  2887 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 06:32:26.310   928  2887 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 06:32:26.315   928  2887 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 06:32:26.315   928  2887 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-30 06:32:26.315   928  2887 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-30 06:32:26.315   928  2885 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 06:32:26.315   928  2887 D ConnectivityService:    accepting network in place of null
08-30 06:32:26.316   928  2885 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 06:32:26.316   928  2887 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 06:32:26.335   928  5914 D NetlinkSocketObserver: NeighborEvent{elapsedMs=260360, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 06:32:26.346   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 06:32:26.373   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 06:32:26.377   928  2887 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 06:32:26.377   928  2887 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 06:32:26.377  3417  3567 W QCNEJ   : |CORE| network available: 102
08-30 06:32:26.378   928  2887 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 06:32:26.379  3417  3567 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,08-30 06:32:26.382  3417  3567 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
08-30 06:32:26.382   928   945 D Tethering: MasterInitialState.processMessage what=3
08-30 06:32:26.382  3417  3567 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,08-30 06:32:26.389  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:32:26.389  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:26.389  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:26.389  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:32:26.389  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:32:26.389  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:32:26.389  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:32:26.389  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 06:32:26.391  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 06:32:26.396  4791  4820 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,08-30 06:32:26.396  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:32:26.396  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:26.396  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:26.396  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:32:26.396  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:32:26.396  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:32:26.396  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:32:26.396  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 06:32:26.396  4791  4820 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,08-30 06:32:26.396  4791  4820 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
08-30 06:32:26.397  4791  4820 E SarControlService: no key has been found,reset the power
08-30 06:32:26.397  4791  4838 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-30 06:32:26.397  4791  4838 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-30 06:32:26.397  4791  4838 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-30 06:32:26.398  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 06:32:26.398  4830  4830 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-30 06:32:26.399  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 06:32:26.399  4791  4838 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-30 06:32:26.399  4791  4838 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-30 06:32:26.399  4791  4838 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-30 06:32:26.401  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 06:32:26.402  4830  4830 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-30 06:32:26.405  3809  3809 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 06:32:26.408  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d4564c8 HexData = [00000000f003000000000000ffffffff]
,08-30 06:32:26.408  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-30 06:32:26.408  4830  4844 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
08-30 06:32:26.410  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-30 06:32:26.410  4791  4802 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-30 06:32:26.410   928  5913 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.206,2a00:1450:400d:802::200e
08-30 06:32:26.409  3809  3809 D SystemUpdateService: onCreate
08-30 06:32:26.412  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d4564c8 HexData = [00000000f103000000000000ffffffff]
08-30 06:32:26.412  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-30 06:32:26.412  4830  4844 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
08-30 06:32:26.413  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-30 06:32:26.413  4791  4801 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-30 06:32:26.416  3809  3809 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 06:32:26.427  3809  5926 I SystemUpdateService: active receiver: enabled
,08-30 06:32:26.433  3809  3809 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 06:32:26.441  3809  5192 I iu.UploadsManager: num queued entries: 0
,08-30 06:32:26.441  3809  5192 I iu.UploadsManager: num updated entries: 0
,08-30 06:32:26.442  3809  5192 I iu.SyncManager: NEXT; no task
,08-30 06:32:26.445  3809  3809 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 06:32:26.446  3809  3809 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-30 06:32:26.448  5712  5712 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 06:32:26.453  5712  5712 D SprintDMHelper: simOperator: 
,08-30 06:32:26.453  5712  5712 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 06:32:26.454  3809  5926 I SystemUpdateService: showing system update notification
,08-30 06:32:26.456   928  5913 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:32:26 GMT], X-Android-Received-Millis=[1472553146456], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472553146434]}
,08-30 06:32:26.457   928  2887 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 06:32:26.457   928  2887 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-30 06:32:26.457   928  2887 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 06:32:26.458   928  2887 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 06:32:26.485  3809  5926 V SystemUpdateService: retry (wakeup: false) in 3599943 ms
,08-30 06:32:26.487  3809  3809 D SystemUpdateService: onDestroy
,08-30 06:32:26.496  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 06:32:26.496  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:26.496  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:26.496  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:32:26.496  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:32:26.496  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:32:26.496  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:32:26.496  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 06:32:26.497  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 06:32:26.497  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:26.498  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c006acd removed from the list
08-30 06:32:26.498  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:32:26.498  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:26.498  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:32:26.500  5587  5937 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-30 06:32:26.500  5587  5937 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 06:32:26.560  4156  5933 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 06:32:27.172   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-30 06:32:29.510  5587  5937 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-30 06:32:29.511  5587  5937 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-30 06:32:29.512  5587  5937 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 06:32:29.512  5587  5942 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-30 06:32:29.512  5587  5942 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-30 06:32:29.513  5587  5942 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 06:32:29.513  5587  5937 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 06:32:29.514  5587  5942 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 06:32:29.515  5587  5944 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: OutgoingSocketThread/Sender)
08-30 06:32:29.516  5587  5937 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 06:32:29.518  5587  5945 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: IncomingSocketThread/Sender)
,08-30 06:32:29.519  5587  5942 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-30 06:32:29.520  5587  5946 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: OutgoingSocketThread/Receiver)
08-30 06:32:29.521  5587  5947 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: IncomingSocketThread/Receiver)
,08-30 06:32:29.522  5587  5946 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: OutgoingSocketThread/Receiver)
,08-30 06:32:29.522  5587  5946 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 06:32:29.522  5587  5947 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 157, thread name: IncomingSocketThread/Receiver)
08-30 06:32:29.522  5587  5946 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-30 06:32:29.522  5587  5947 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 06:32:29.523  5587  5947 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-30 06:32:32.508  5587  5633 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-30 06:32:32.510  5587  5633 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 06:32:32.516  5587  5633 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5e61a3f Bundle[{}]
,08-30 06:32:32.517  5587  5633 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 06:32:32.517  5587  5633 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 06:32:32.518  5587  5633 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 06:32:32.518  5587  5633 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 06:32:32.519  5587  5633 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 06:32:32.520  5587  5633 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 06:32:32.526  5587  5633 I System.out: Running OutgoingSocketThread
,08-30 06:32:32.528  5587  5948 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-30 06:32:32.528  5587  5948 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 06:32:34.324   928  2887 D ConnectivityService: handlePromptUnvalidated 102
,08-30 06:32:35.539  5587  5948 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-30 06:32:35.539  5587  5948 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 06:32:35.539  5587  5948 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 06:32:35.540  5587  5948 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 06:32:35.543  5587  5948 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-30 06:32:35.543  5587  5949 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-30 06:32:35.543  5587  5949 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 06:32:35.545  5587  5951 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: OutgoingSocketThread/Sender)
08-30 06:32:35.545  5587  5949 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 06:32:35.546  5587  5952 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: OutgoingSocketThread/Receiver)
08-30 06:32:35.547  5587  5949 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 06:32:35.549  5587  5949 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-30 06:32:35.550  5587  5952 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: OutgoingSocketThread/Receiver)
08-30 06:32:35.550  5587  5952 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 06:32:35.550  5587  5952 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-30 06:32:35.552  5587  5953 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: IncomingSocketThread/Sender)
,08-30 06:32:35.553  5587  5954 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: IncomingSocketThread/Receiver)
,08-30 06:32:35.555  5587  5954 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 169, thread name: IncomingSocketThread/Receiver)
,08-30 06:32:35.555  5587  5954 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 06:32:35.555  5587  5954 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 06:32:38.537  5587  5633 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 178)
,08-30 06:32:38.539  5587  5633 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 06:32:38.539  5587  5633 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 179)
08-30 06:32:38.543  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 06:32:38.544  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4461f82 added. We now have 3 listener(s)
08-30 06:32:38.547  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 06:32:38.547  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 06:32:38.547  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 06:32:38.548  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 06:32:38.548  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13693 added. We now have 4 listener(s)
08-30 06:32:38.548  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 06:32:38.549  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 06:32:38.554  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 06:32:38.561  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:32:38.561  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:38.561  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:38.561  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:32:38.561  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:32:38.561  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:32:38.561  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:32:38.561  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 06:32:38.564  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 06:32:38.565  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 06:32:38.565  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 06:32:38.565  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 06:32:38.565  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 06:32:38.565  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:32:38.565  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:38.566  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 06:32:38.566  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 06:32:38.566  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4461f82 removed from the list
,08-30 06:32:38.566  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:38.566  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13693 removed from the list
08-30 06:32:38.568  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:38.568  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 06:32:38.568  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:38.569  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:38.569  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:38.571  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 06:32:38.571  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 06:32:38.571  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:38.571  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13693 not in the list
08-30 06:32:38.571  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:38.571  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:38.573  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 06:32:38.573  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 06:32:38.573  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 06:32:38.573  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13693 not in the list
08-30 06:32:38.573  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:32:38.573  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:38.573  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:38.573  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:38.573  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4461f82 not in the list
,08-30 06:32:38.574  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 06:32:38.575  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e35e6c9 added. We now have 3 listener(s)
,08-30 06:32:38.577  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 06:32:38.577  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 06:32:38.577  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 06:32:38.577  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 06:32:38.578  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bab1ce added. We now have 4 listener(s)
08-30 06:32:38.578  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 06:32:38.578  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 06:32:38.582  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 06:32:38.587  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:32:38.587  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:38.587  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:38.587  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:32:38.587  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:32:38.587  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:32:38.587  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:32:38.587  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 06:32:38.588  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 06:32:38.589  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 06:32:38.589  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 06:32:38.589  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 06:32:38.589  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 06:32:38.589  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:32:38.589  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 06:32:38.592  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:38.592  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 06:32:38.592  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 06:32:38.596  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:38.596  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 06:32:38.597  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 06:32:38.597  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 06:32:38.601  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 06:32:38.601  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 06:32:38.601  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 06:32:38.601  5587  5633 D BluetoothAdapter: STATE_ON
08-30 06:32:38.604  5856  5867 D BtGatt.GattService: registerClient() - UUID=1cf9a47c-9e54-4a4d-a459-81acebb2acf7
08-30 06:32:38.605  5856  5872 D BtGatt.GattService: onClientRegistered() - UUID=1cf9a47c-9e54-4a4d-a459-81acebb2acf7, clientIf=5
,08-30 06:32:38.605  5587  5598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 06:32:38.606  5856  5866 D BtGatt.GattService: start scan with filters
08-30 06:32:38.610  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 06:32:38.610  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 06:32:38.610  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 06:32:38.610  5856  5875 D BtGatt.ScanManager: handling starting scan
08-30 06:32:38.610  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 06:32:38.612  5856  5875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@61d32e3
,08-30 06:32:38.612  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 06:32:38.613  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 06:32:38.613  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 06:32:38.614  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 06:32:38.617  5587  5633 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 06:32:38.617  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 06:32:38.617  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 06:32:38.617  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:38.617  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 06:32:38.617  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 06:32:38.617  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 06:32:38.618  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 06:32:38.618  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 06:32:38.618  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 06:32:38.618  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 06:32:38.618  5587  5633 D BluetoothAdapter: STATE_ON
08-30 06:32:38.619  5856  5872 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 06:32:38.619  5856  5872 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 06:32:38.619  5856  5867 D BtGatt.GattService: stopScan() - queue size =1
08-30 06:32:38.620  5856  5875 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 06:32:38.620  5856  5866 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 06:32:38.621  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 06:32:38.621  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 06:32:38.621  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 06:32:38.621  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 06:32:38.621  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 06:32:38.625  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 06:32:38.625  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 06:32:38.625  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 06:32:38.625  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 06:32:38.626  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 06:32:38.626  5856  5872 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-30 06:32:38.626  5856  5872 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 06:32:38.627  5856  5875 D BtGatt.ScanManager: Starting BLE batch scan
08-30 06:32:38.627  5856  5875 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 06:32:38.627  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 06:32:38.627  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 06:32:38.628  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 06:32:38.637  5856  5872 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 06:32:38.637  5856  5872 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 06:32:38.643  5856  5872 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 06:32:38.643  5856  5872 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 06:32:38.650  5856  5872 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-30 06:32:38.650  5856  5872 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 06:32:38.651  5856  5875 D BtGatt.ScanManager: stopping BLe Batch
,08-30 06:32:38.658  5856  5872 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 06:32:38.658  5856  5872 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 06:32:38.658  5856  5875 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 06:32:38.664  5856  5872 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 06:32:38.664  5856  5872 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 06:32:39.128  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 06:32:39.129  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 06:32:39.129  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 06:32:41.628  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 06:32:41.628  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 06:32:41.629  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 06:32:41.629  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:32:41.629  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 06:32:41.629  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 06:32:41.629  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 06:32:41.630  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e35e6c9 removed from the list
,08-30 06:32:41.630  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:41.630  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bab1ce removed from the list
08-30 06:32:41.630  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:32:41.630  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:41.632  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 06:32:41.633  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:41.637  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 06:32:41.637  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 06:32:41.637  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:41.637  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bab1ce not in the list
08-30 06:32:41.637  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 06:32:41.638  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:41.640  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 06:32:41.641  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 06:32:41.641  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:41.641  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bab1ce not in the list
08-30 06:32:41.641  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:32:41.641  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 06:32:41.641  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:32:41.642  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e35e6c9 not in the list
08-30 06:32:41.643  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 06:32:41.643  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6e50b added. We now have 3 listener(s)
08-30 06:32:41.647  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 06:32:41.648  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 06:32:41.648  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 06:32:41.648  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 06:32:41.648  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b0fe8 added. We now have 4 listener(s)
08-30 06:32:41.648  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 06:32:41.650  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 06:32:41.656  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:32:41.664  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:32:41.664  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:41.664  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:41.664  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:32:41.664  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:32:41.664  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:32:41.664  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:32:41.664  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 06:32:41.667  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 06:32:41.668  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 06:32:41.668  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 06:32:41.669  5587  5633 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
08-30 06:32:41.669  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,08-30 06:32:41.670  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 06:32:41.670  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 06:32:41.670  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 06:32:41.670  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:32:41.671  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 06:32:41.672  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 06:32:41.672  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 06:32:41.673  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 06:32:41.673  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 06:32:41.673  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:32:41.673  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 06:32:41.673  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:41.674  5587  5955 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 06:32:41.679  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 06:32:41.679  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 06:32:41.681  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:41.681  5587  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-30 06:32:41.681  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-30 06:32:41.684  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 06:32:41.685  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 06:32:41.685  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 06:32:41.688  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-30 06:32:41.688  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 06:32:41.688  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
08-30 06:32:41.688  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 06:32:41.688  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 06:32:41.688  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-30 06:32:41.689  5587  5633 D BluetoothAdapter: STATE_ON
,08-30 06:32:41.692  5856  5867 D BtGatt.GattService: registerClient() - UUID=9f21d808-163c-4add-a1c1-2f72a7efeabf
,08-30 06:32:41.692  5856  5872 D BtGatt.GattService: onClientRegistered() - UUID=9f21d808-163c-4add-a1c1-2f72a7efeabf, clientIf=5
,08-30 06:32:41.693  5587  5598 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-30 06:32:41.695  5856  5874 D BtGatt.AdvertiseManager: message : 0
,08-30 06:32:41.697  5856  5874 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 06:32:41.708  5856  5872 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 06:32:41.714  5856  5872 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 06:32:41.715  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-30 06:32:41.715  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 06:32:41.716  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 06:32:41.717  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 06:32:41.718  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-30 06:32:41.718  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 06:32:41.718  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-30 06:32:41.718  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-30 06:32:41.718  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-30 06:32:41.719  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 06:32:41.721  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-30 06:32:41.721  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 06:32:42.173   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:42.222  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 06:32:42.222  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 06:32:42.222  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 06:32:43.174   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:44.175   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:44.720  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 06:32:44.721  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-30 06:32:44.721  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 06:32:44.721  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 06:32:44.721  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 06:32:44.721  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 06:32:44.722  5587  5955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 06:32:44.722  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 06:32:44.722  5587  5955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 06:32:44.722  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 06:32:44.722  5587  5955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 06:32:44.723  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 06:32:44.723  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 06:32:44.723  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 06:32:44.723  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 06:32:44.723  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 06:32:44.723  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 06:32:44.725  5587  5633 D BluetoothAdapter: STATE_ON
08-30 06:32:44.726  5587  5633 D BluetoothLeScanner: could not find callback wrapper
08-30 06:32:44.726  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 06:32:44.726  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-30 06:32:44.728  5856  5874 D BtGatt.AdvertiseManager: message : 1
,08-30 06:32:44.729  5856  5874 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 06:32:44.744  5856  5872 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-30 06:32:44.745  5856  5872 D BtGatt.GattService: Client app is not null!
,08-30 06:32:44.746  5856  5866 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 06:32:44.747  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 06:32:44.748  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-30 06:32:44.748  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-30 06:32:44.749  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-30 06:32:44.749  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-30 06:32:44.752  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 06:32:44.752  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 06:32:44.752  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 06:32:44.754  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 06:32:44.756  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 06:32:44.756  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 06:32:44.756  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:44.756  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 06:32:44.757  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 06:32:44.757  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 06:32:44.757  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6e50b removed from the list
08-30 06:32:44.757  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 06:32:44.757  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:44.757  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b0fe8 removed from the list
08-30 06:32:44.757  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 06:32:44.757  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:32:44.757  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:44.758  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 06:32:44.758  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:44.760  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 06:32:44.760  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 06:32:44.760  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:44.760  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b0fe8 not in the list
08-30 06:32:44.760  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:44.760  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:32:44.763  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 06:32:44.763  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 06:32:44.763  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:44.763  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b0fe8 not in the list
08-30 06:32:44.763  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:32:44.763  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:44.763  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:32:44.764  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6e50b not in the list
08-30 06:32:44.765  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 06:32:44.765  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4ea13d added. We now have 3 listener(s)
,08-30 06:32:44.769  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-30 06:32:44.769  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 06:32:44.770  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 06:32:44.770  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 06:32:44.770  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc96d32 added. We now have 4 listener(s)
08-30 06:32:44.770  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 06:32:44.772  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 06:32:44.777  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 06:32:44.783  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:32:44.783  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:44.783  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:44.783  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:32:44.783  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:32:44.783  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:32:44.783  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:32:44.783  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 06:32:44.786  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 06:32:44.787  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 06:32:44.787  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 06:32:44.787  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 06:32:44.787  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 06:32:44.787  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:32:44.787  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 06:32:44.790  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:32:44.793  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 06:32:44.793  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 06:32:44.795  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:32:44.799  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 06:32:44.800  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 06:32:44.800  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 06:32:44.803  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 06:32:44.803  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 06:32:44.803  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 06:32:44.804  5587  5633 D BluetoothAdapter: STATE_ON
08-30 06:32:44.806  5856  5892 D BtGatt.GattService: registerClient() - UUID=09fcc784-ad11-42c1-99a5-24f9768f87d0
08-30 06:32:44.807  5856  5872 D BtGatt.GattService: onClientRegistered() - UUID=09fcc784-ad11-42c1-99a5-24f9768f87d0, clientIf=5
08-30 06:32:44.807  5587  5598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 06:32:44.807  5856  5866 D BtGatt.GattService: start scan with filters
,08-30 06:32:44.811  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 06:32:44.811  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 06:32:44.811  5856  5875 D BtGatt.ScanManager: handling starting scan
08-30 06:32:44.811  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 06:32:44.811  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 06:32:44.815  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 06:32:44.815  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 06:32:44.815  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 06:32:44.816  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 06:32:44.818  5856  5872 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 06:32:44.818  5856  5872 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 06:32:44.819  5856  5875 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 06:32:44.824  5856  5872 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-30 06:32:44.825  5856  5872 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 06:32:44.825  5856  5875 D BtGatt.ScanManager: Starting BLE batch scan
08-30 06:32:44.825  5856  5875 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 06:32:44.835  5856  5872 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 06:32:44.836  5856  5872 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 06:32:44.841  5856  5872 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 06:32:44.841  5856  5872 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 06:32:45.065   928  5914 D NetlinkSocketObserver: NeighborEvent{elapsedMs=279090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 06:32:45.176   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:45.258  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 06:32:45.316  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 06:32:45.316  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 06:32:45.317  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 06:32:46.177   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:32:47.178   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-30 06:32:47.826  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 06:32:47.826  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 06:32:47.827  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 06:32:47.827  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 06:32:47.827  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 06:32:47.827  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 06:32:47.827  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 06:32:47.827  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 06:32:47.828  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 06:32:47.828  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 06:32:47.828  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 06:32:47.830  5587  5633 D BluetoothAdapter: STATE_ON
08-30 06:32:47.832  5856  5893 D BtGatt.GattService: stopScan() - queue size =1
,08-30 06:32:47.834  5856  5884 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 06:32:47.835  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 06:32:47.835  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 06:32:47.836  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 06:32:47.836  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 06:32:47.836  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 06:32:47.838  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 06:32:47.838  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 06:32:47.838  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 06:32:47.839  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 06:32:47.840  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 06:32:47.842  5856  5856 D BtGatt.ScanManager: awakened up at time 281867
08-30 06:32:47.843  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 06:32:47.843  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:32:47.843  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:47.843  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 06:32:47.843  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 06:32:47.843  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 06:32:47.843  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 06:32:47.844  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4ea13d removed from the list
08-30 06:32:47.844  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:47.844  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc96d32 removed from the list
08-30 06:32:47.844  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:32:47.844  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:47.845  5856  5872 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-30 06:32:47.845  5856  5872 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 06:32:47.845  5856  5875 D BtGatt.ScanManager: stopping BLe Batch
08-30 06:32:47.845  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:47.845  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:32:47.848  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 06:32:47.849  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 06:32:47.849  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:47.849  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc96d32 not in the list
08-30 06:32:47.849  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:47.849  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:47.850  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 06:32:47.851  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 06:32:47.851  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:47.851  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc96d32 not in the list
08-30 06:32:47.851  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:32:47.851  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:47.851  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:47.851  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4ea13d not in the list
08-30 06:32:47.852  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 06:32:47.852  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d1abdf added. We now have 3 listener(s)
,08-30 06:32:47.854  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 06:32:47.854  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 06:32:47.854  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 06:32:47.854  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 06:32:47.854  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1e502c added. We now have 4 listener(s)
08-30 06:32:47.855  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 06:32:47.855  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 06:32:47.855  5856  5872 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 06:32:47.856  5856  5872 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 06:32:47.856  5856  5875 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 06:32:47.858  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 06:32:47.863  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:32:47.863  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:32:47.863  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:32:47.863  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:32:47.863  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:32:47.863  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:32:47.863  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:32:47.863  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 06:32:47.865  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 06:32:47.866  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 06:32:47.866  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 06:32:47.866  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 06:32:47.866  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 06:32:47.866  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:32:47.866  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 06:32:47.866  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 06:32:47.866  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 06:32:47.866  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d1abdf removed from the list
08-30 06:32:47.866  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:47.866  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1e502c removed from the list
08-30 06:32:47.868  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:47.868  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
08-30 06:32:47.869  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:32:47.869  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:47.869  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 06:32:47.871  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 06:32:47.871  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 06:32:47.871  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:47.871  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1e502c not in the list
08-30 06:32:47.871  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:47.871  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:47.872  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 06:32:47.873  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 06:32:47.873  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 06:32:47.873  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 06:32:47.873  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1e502c not in the list
08-30 06:32:47.873  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 06:32:47.873  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 06:32:47.873  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 06:32:47.873  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d1abdf not in the list
,08-30 06:32:47.873  5856  5872 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-30 06:32:47.873  5856  5872 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 06:32:47.874  5856  5872 D BtGatt.GattService: current time is 281899764422
08-30 06:32:47.874  5856  5872 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -72, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -77, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -83, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -77, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -84, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-30 06:32:47.874  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 06:32:47.875  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 06:32:47.875  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 06:32:47.875  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 06:32:47.875  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 06:32:47.875  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 06:32:47.875  5856  5872 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 06:32:47.876  5856  5872 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24,, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 06:32:47.876  5856  5872 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 06:32:47.876  5856  5872 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 06:32:47.876  5856  5872 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 06:32:47.876  5856  5872 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 06:32:48.344  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 06:32:49.885  5587  5956 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name)
,08-30 06:32:51.884  5587  5633 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 188
,08-30 06:32:51.884  5587  5633 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 188, name: My test thread name)
,08-30 06:32:51.889  5587  5957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name)
08-30 06:32:51.889  5587  5957 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 189, thread name: My test thread name)
08-30 06:32:51.890  5587  5957 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-30 06:32:51.892  5587  5633 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 06:32:51.897  5587  5958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: My test thread name)
,08-30 06:32:51.898  5587  5958 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 193, thread name: My test thread name): Test exception.
08-30 06:32:51.898  5587  5958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-30 06:32:51.902  5587  5633 I jxcore-log: Total number of executed tests:  82
08-30 06:32:51.902  5587  5633 I jxcore-log: 
,08-30 06:32:51.903  5587  5633 I jxcore-log: Number of passed tests:  82
08-30 06:32:51.903  5587  5633 I jxcore-log: 
08-30 06:32:51.903  5587  5633 I jxcore-log: Number of failed tests:  0
08-30 06:32:51.903  5587  5633 I jxcore-log: 
,08-30 06:32:51.905  5587  5633 I jxcore-log: Number of ignored tests:  0
08-30 06:32:51.905  5587  5633 I jxcore-log: 
08-30 06:32:51.905  5587  5633 I jxcore-log: Total duration:  110952
08-30 06:32:51.905  5587  5633 I jxcore-log: 
08-30 06:32:51.907  5587  5633 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 06:32:51.907  5587  5633 I jxcore-log: 
08-30 06:32:51.909  5587  5633 I jxcore-log: My device name is: Huawei-Nexus 6P
08-30 06:32:51.909  5587  5633 I jxcore-log: 
08-30 06:32:51.913  5587  5633 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 06:32:51.913  5587  5633 I jxcore-log: 
,08-30 06:32:51.918  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.918  5587  5633 I jxcore-log: 
08-30 06:32:51.920  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.920  5587  5633 I jxcore-log: 
08-30 06:32:51.922  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.922  5587  5633 I jxcore-log: 
,08-30 06:32:51.925  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 06:32:51.925  5587  5633 I jxcore-log: 
08-30 06:32:51.929  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.929  5587  5633 I jxcore-log: 
,08-30 06:32:51.931  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 06:32:51.931  5587  5633 I jxcore-log: 
08-30 06:32:51.932  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 06:32:51.932  5587  5633 I jxcore-log: 
08-30 06:32:51.933  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.933  5587  5633 I jxcore-log: 
08-30 06:32:51.933  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 06:32:51.933  5587  5633 I jxcore-log: 
08-30 06:32:51.935  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 06:32:51.935  5587  5633 I jxcore-log: 
,08-30 06:32:51.936  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 06:32:51.936  5587  5633 I jxcore-log: 
,08-30 06:32:51.937  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.937  5587  5633 I jxcore-log: 
08-30 06:32:51.938  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.938  5587  5633 I jxcore-log: 
08-30 06:32:51.939  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.939  5587  5633 I jxcore-log: 
08-30 06:32:51.940  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 06:32:51.940  5587  5633 I jxcore-log: 
08-30 06:32:51.942  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 06:32:51.942  5587  5633 I jxcore-log: 
,08-30 06:32:51.944  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 06:32:51.944  5587  5633 I jxcore-log: 
,08-30 06:32:51.945  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.945  5587  5633 I jxcore-log: 
08-30 06:32:51.946  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.946  5587  5633 I jxcore-log: 
08-30 06:32:51.947  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.947  5587  5633 I jxcore-log: 
08-30 06:32:51.948  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 06:32:51.948  5587  5633 I jxcore-log: 
08-30 06:32:51.949  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 06:32:51.949  5587  5633 I jxcore-log: 
08-30 06:32:51.950  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 06:32:51.950  5587  5633 I jxcore-log: 
08-30 06:32:51.950  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.950  5587  5633 I jxcore-log: 
,08-30 06:32:51.951  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.951  5587  5633 I jxcore-log: 
08-30 06:32:51.951  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.951  5587  5633 I jxcore-log: 
08-30 06:32:51.952  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 06:32:51.952  5587  5633 I jxcore-log: 
08-30 06:32:51.952  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 06:32:51.952  5587  5633 I jxcore-log: 
08-30 06:32:51.953  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.953  5587  5633 I jxcore-log: 
08-30 06:32:51.953  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.953  5587  5633 I jxcore-log: 
08-30 06:32:51.954  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.954  5587  5633 I jxcore-log: 
,08-30 06:32:51.955  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.955  5587  5633 I jxcore-log: 
08-30 06:32:51.956  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.956  5587  5633 I jxcore-log: 
08-30 06:32:51.957  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.957  5587  5633 I jxcore-log: 
,08-30 06:32:51.958  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.958  5587  5633 I jxcore-log: 
08-30 06:32:51.959  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.959  5587  5633 I jxcore-log: 
08-30 06:32:51.959  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.959  5587  5633 I jxcore-log: 
08-30 06:32:51.960  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.960  5587  5633 I jxcore-log: 
08-30 06:32:51.960  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.960  5587  5633 I jxcore-log: 
08-30 06:32:51.961  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 06:32:51.961  5587  5633 I jxcore-log: 
08-30 06:32:51.961  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 06:32:51.961  5587  5633 I jxcore-log: 
08-30 06:32:51.962  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 06:32:51.962  5587  5633 I jxcore-log: 
08-30 06:32:51.962  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.962  5587  5633 I jxcore-log: 
08-30 06:32:51.963  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.963  5587  5633 I jxcore-log: 
,08-30 06:32:51.963  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.963  5587  5633 I jxcore-log: 
,08-30 06:32:51.964  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.964  5587  5633 I jxcore-log: 
,08-30 06:32:51.966  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.966  5587  5633 I jxcore-log: 
08-30 06:32:51.966  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 06:32:51.966  5587  5633 I jxcore-log: 
08-30 06:32:51.967  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.967  5587  5633 I jxcore-log: 
08-30 06:32:51.968  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 06:32:51.968  5587  5633 I jxcore-log: 
08-30 06:32:51.968  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.968  5587  5633 I jxcore-log: 
08-30 06:32:51.969  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 06:32:51.969  5587  5633 I jxcore-log: 
08-30 06:32:51.969  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 06:32:51.969  5587  5633 I jxcore-log: 
08-30 06:32:51.970  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:32:51.970  5587  5633 I jxcore-log: 
08-30 06:32:51.970  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 06:32:51.970  5587  5633 I jxcore-log: 
08-30 06:32:51.975  5587  5956 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-30 06:32:52.351  5959  5959 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 06:32:52.356  5959  5959 D AndroidRuntime: CheckJNI is OFF
,08-30 06:32:52.386  5959  5959 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 06:32:52.419  5959  5959 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 06:32:52.438  5959  5959 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 06:32:52.447   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,08-30 06:32:52.447   928   941 I ActivityManager: Killing 5587:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,08-30 06:32:52.525   928  3322 I WindowState: WIN DEATH: Window{f3000aa u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 06:32:52.525   928  2886 D WifiService: Client connection lost with reason: 4
,08-30 06:32:52.526   928  3561 D GraphicsStats: Buffer count: 2
,08-30 06:32:52.585   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-30 06:32:52.586   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-30 06:32:52.586   928   951 I art     : Starting a blocking GC Explicit
08-30 06:32:52.586   928   941 E ActivityManager: Failure starting process com.test.thalitest
08-30 06:32:52.586   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 06:32:52.586   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:32:52.586   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:32:52.586   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 06:32:52.586   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 06:32:52.588   928   941 I ActivityManager:   Force finishing activity ActivityRecord{42a7997 u0 com.test.thalitest/.MainActivity t4}
,08-30 06:32:52.598   928  3556 W ActivityManager: Spurious death for ProcessRecord{3e06017 0:com.test.thalitest/u0a77}, curProc for 5587: null
,08-30 06:32:52.668   928   951 I art     : Explicit concurrent mark sweep GC freed 54236(3MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/43MB, paused 1.645ms total 81.677ms
,08-30 06:32:52.690   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 06:32:52.692  5959  5959 I art     : System.exit called, status: 0
,08-30 06:32:52.692  5959  5959 I AndroidRuntime: VM exiting with result code 0.
,08-30 06:32:52.715   928   951 I ActivityManager: Start proc 5969:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-30 06:32:52.715   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,08-30 06:32:52.734   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 06:32:52.741  3355  3355 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 06:32:52.744  5856  5856 D BluetoothMapAppObserver: onReceive
,08-30 06:32:52.744  3570  3846 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 06:32:52.744  5856  5856 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-30 06:32:52.756   928  2877 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 06:32:52.756  3355  5982 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 06:32:52.784  3355  5982 I Decoder : createOrResetDecoder
,08-30 06:32:52.786  5304  5983 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 06:32:52.790    27    27 W kworker/1:1: type=1400 audit(0.0:73): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-30 06:32:52.800    27    27 W kworker/1:1: type=1400 audit(0.0:74): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-30 06:32:52.825  3449  3449 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 06:32:52.832  3526  3526 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-30 06:32:52.833  3526  3526 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
08-30 06:32:52.834  3526  3526 E AndroidRuntime: FATAL EXCEPTION: main
08-30 06:32:52.834  3526  3526 E AndroidRuntime: Process: com.google.process.gapps, PID: 3526
08-30 06:32:52.834  3526  3526 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 06:32:52.834  3526  3526 E AndroidRuntime: 	... 8 more
,08-30 06:32:52.830    27    27 W kworker/1:1: type=1400 audit(0.0:75): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-30 06:32:52.839  5304  5983 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-30 06:32:52.840  5304  5983 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 06:32:52.840  5304  5983 E AndroidRuntime: Process: android.process.acore, PID: 5304
08-30 06:32:52.840  5304  5983 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:32:52.840  5304  5983 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 06:32:52.843   928  5988 E DropBoxManagerService: Can't write: system_app_crash
08-30 06:32:52.843   928  5988 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-30 06:32:52.843   928  5988 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 06:32:52.843   928  5988 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 06:32:52.843   928  5988 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 06:32:52.843   928  5988 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 06:32:52.843   928  5988 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 06:32:52.843   928  5988 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 06:32:52.843   928  5988 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 06:32:52.843   928  5988 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 06:32:52.843   928  5988 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 06:32:52.843   928  5988 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 06:32:52.843   928  5988 E DropBoxManagerService: 	... 5 more
,08-30 06:32:52.844  3526  3526 I Process : Sending signal. PID: 3526 SIG: 9
,08-30 06:32:52.846  5304  5983 I Process : Sending signal. PID: 5304 SIG: 9
,08-30 06:32:52.847   928  5989 E DropBoxManagerService: Can't write: system_app_crash
08-30 06:32:52.847   928  5989 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-30 06:32:52.847   928  5989 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 06:32:52.847   928  5989 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 06:32:52.847   928  5989 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 06:32:52.847   928  5989 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 06:32:52.847   928  5989 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 06:32:52.847   928  5989 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 06:32:52.847   928  5989 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 06:32:52.847   928  5989 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 06:32:52.847   928  5989 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 06:32:52.847   928  5989 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 06:32:52.847   928  5989 E DropBoxManagerService: 	... 5 more
,08-30 06:32:52.863   928   940 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-30 06:32:52.864   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 06:32:52.864   928   940 E PackageManager: Failed to write settings, restoring backup
08-30 06:32:52.864   928   940 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 06:32:52.864   928   940 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 06:32:52.864   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 06:32:52.864   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 06:32:52.864   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 06:32:52.864   928   940 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:32:52.864   928   940 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:32:52.864   928   940 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 06:32:52.868   928   941 E DropBoxManagerService: Can't write: system_server_wtf
08-30 06:32:52.868   928   941 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 06:32:52.868   928   941 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 06:32:52.868   928   941 E DropBoxManagerService: 	... 13 more
,08-30 06:32:52.876  3484  3592 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-30 06:32:52.889   928  3561 I ActivityManager: Start proc 5990:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-30 06:32:52.890  3484  3592 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 06:32:52.890  3484  3592 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3484
08-30 06:32:52.890  3484  3592 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 06:32:52.890  3484  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 06:32:52.890  3484  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 06:32:52.890  3484  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 06:32:52.890  3484  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 06:32:52.890  3484  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 06:32:52.890  3484  3592 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 06:32:52.890  3484  3592 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 06:32:52.890  3484  3592 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 06:32:52.890  3484  3592 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 06:32:52.890  3484  3592 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:32:52.890  3484  3592 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 06:32:52.894   928  3087 I ActivityManager: Process android.process.acore (pid 5304) has died

```
