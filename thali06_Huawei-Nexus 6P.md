#### Test 83084099a4f621d_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-29 08:43:01.743   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:43:02.219  5550  5550 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 08:43:02.225  5550  5550 D AndroidRuntime: CheckJNI is OFF
08-29 08:43:02.248  5550  5550 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 08:43:02.278  5550  5550 I Radio-JNI: register_android_hardware_Radio DONE
08-29 08:43:02.293  5550  5550 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 08:43:02.298   928  3604 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 08:43:02.350   928  3604 I ActivityManager: Start proc 5559:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-29 08:43:02.355  5550  5550 D AndroidRuntime: Shutting down VM
08-29 08:43:02.461  5559  5559 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-29 08:43:02.494  5559  5559 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 08:43:02.519  5559  5559 I LibraryLoader: Time to load native libraries: 22 ms (timestamps 5927-5949)
08-29 08:43:02.519  5559  5559 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 08:43:02.541  5559  5559 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1fd6e92}
08-29 08:43:02.542  5559  5559 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 08:43:02.542  5559  5559 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 08:43:02.547  5559  5559 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 08:43:02.548  5559  5559 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 08:43:02.584  5559  5559 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 08:43:02.597  5559  5559 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 08:43:02.597  5559  5559 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 08:43:02.597  5559  5559 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 08:43:02.597  5559  5559 I Adreno  : Build Date                       : 10/21/15
08-29 08:43:02.597  5559  5559 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 08:43:02.597  5559  5559 I Adreno  : Local Branch                     : 
08-29 08:43:02.597  5559  5559 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 08:43:02.597  5559  5559 I Adreno  : Remote Branch                    : NONE
08-29 08:43:02.597  5559  5559 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 08:43:02.653   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@429e937:true
,08-29 08:43:02.701  5559  5559 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 08:43:02.710  5559  5559 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-29 08:43:02.735  5559  5596 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 08:43:02.742  5559  5583 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 08:43:02.744   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:43:02.781  5559  5596 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 08:43:02.866   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +455ms (total +545ms)
,08-29 08:43:02.890  5559  5559 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5559
,08-29 08:43:02.974  5559  5559 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 08:43:03.098  5559  5599 D jxcore_app_log: JniHelper::setJavaVM(0xf537c000), pthread_self() = -583792336
,08-29 08:43:03.101  5559  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 08:43:03.101  5559  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 08:43:03.101  5559  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 08:43:03.101  5559  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 08:43:03.101  5559  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 08:43:03.101  5559  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54a2438 added. We now have 1 listener(s)
,08-29 08:43:03.103  5559  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,08-29 08:43:03.104  5559  5599 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 08:43:03.104  5559  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:43:03.104  5559  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 08:43:03.106  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@660e377 added. We now have 1 listener(s)
08-29 08:43:03.106  5559  5599 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:43:03.109   928  3005 D WifiService: New client listening to asynchronous messages
,08-29 08:43:03.109  5559  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 08:43:03.109  5559  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 08:43:03.109  5559  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 08:43:03.110  5559  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 08:43:03.110  5559  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 08:43:03.111  5559  5599 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:43:03.111  5559  5599 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-29 08:43:03.114  5559  5599 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-29 08:43:03.115  5559  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:43:03.115  5559  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:03.115  5559  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:03.115  5559  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:03.115  5559  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:43:03.115  5559  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:03.115  5559  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:43:03.115  5559  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:43:03.115  5559  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-29 08:43:03.115  5559  5599 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:43:03.115  5559  5599 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 08:43:03.118  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:03.122  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:03.130  5559  5559 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 08:43:03.427  5559  5568 I art     : Background sticky concurrent mark sweep GC freed 87920(8MB) AllocSpace objects, 18(1604KB) LOS objects, 21% free, 25MB/32MB, paused 1.949ms total 110.897ms
,08-29 08:43:03.501  5559  5606 W jxcore-log: Initializing JXcore engine
,08-29 08:43:03.501  5559  5606 W jxcore-log: JXcore engine is ready
,08-29 08:43:03.518  5606  5606 W Thread-58: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=13585 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-29 08:43:03.518  5606  5606 W Thread-58: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[6397]" dev="sockfs" ino=6397 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 08:43:03.518  5606  5606 W Thread-58: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5901 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 08:43:03.518  5606  5606 W Thread-58: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[32888]" dev="sockfs" ino=32888 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 08:43:03.533  5559  5606 W jxcore-log: Starting JXcore engine
,08-29 08:43:03.584  5559  5606 W jxcore-log: Platform android
08-29 08:43:03.584  5559  5606 W jxcore-log: 
,08-29 08:43:03.584  5559  5606 W jxcore-log: Process ARCH arm
08-29 08:43:03.584  5559  5606 W jxcore-log: 
,08-29 08:43:03.708  5559  5606 I jxcore-log: JXcore Cordova bridge is ready!
08-29 08:43:03.708  5559  5606 I jxcore-log: 
,08-29 08:43:03.708  5559  5606 W jxcore-log: JXcore engine is started
,08-29 08:43:03.717  5559  5599 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 08:43:03.722  5559  5559 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 08:43:03.744   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 08:43:14.740  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 08:43:14.740  5559  5606 I jxcore-log: 
,08-29 08:43:14.741  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 08:43:14.741  5559  5606 I jxcore-log: 
,08-29 08:43:14.745  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:43:14.745  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:14.745  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:14.745  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:14.745  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:43:14.745  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:14.745  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:43:14.745  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:43:14.746  5559  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:14.748  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 08:43:14.748  5559  5606 I jxcore-log: 
,08-29 08:43:14.750  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 08:43:14.750  5559  5606 I jxcore-log: 
,08-29 08:43:14.993  5559  5606 I jxcore-log: Running unit tests
08-29 08:43:14.993  5559  5606 I jxcore-log: 
,08-29 08:43:14.993  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:43:14.993  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23266a7 added. We now have 2 listener(s)
,08-29 08:43:14.994  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:43:14.994  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:43:14.994  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:43:14.994  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:43:14.994  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6c754 added. We now have 2 listener(s)
08-29 08:43:14.994  5559  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:43:14.995  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:43:14.997  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:43:15.000  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:43:15.000  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:15.000  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:15.000  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:15.000  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:43:15.000  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:15.000  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:43:15.000  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:43:15.001  5559  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:15.001  5559  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:43:15.001  5559  5606 D ExecuteNativeTests: Running unit tests
08-29 08:43:15.008  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:15.013  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:15.036  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 08:43:15.036  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 added. We now have 3 listener(s)
08-29 08:43:15.037  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:43:15.037  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:43:15.037  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:43:15.037  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:43:15.037  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 added. We now have 3 listener(s)
08-29 08:43:15.037  5559  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:43:15.037  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 08:43:15.039  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:43:15.042  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:43:15.042  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:15.042  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:15.042  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:15.042  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:43:15.042  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:15.042  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:43:15.042  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:43:15.043  5559  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:43:15.043  5559  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:43:15.044  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 08:43:15.044  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 08:43:15.044  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 08:43:15.044  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 08:43:15.045  5559  5606 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 08:43:15.045  5559  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 08:43:15.045  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 08:43:15.045  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:43:15.045  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 08:43:15.045  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:43:15.045  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:15.046  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:15.046  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:15.046  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:15.046  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:15.046  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:43:15.046  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:43:15.046  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 removed from the list
,08-29 08:43:15.047  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:15.047  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 removed from the list
08-29 08:43:15.048  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:15.048  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:15.048  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:15.049  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:15.049  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:15.049  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:43:15.049  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:15.049  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:15.049  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
,08-29 08:43:15.050  5559  5606 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 08:43:15.051  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:15.051  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:15.051  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:15.051  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:15.051  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:43:15.051  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:15.051  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:15.051  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:15.051  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:15.053  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:15.054  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:43:15.054  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:15.054  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:15.054  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:15.054  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:15.055  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:43:15.055  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:15.055  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:15.055  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 08:43:15.057  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 08:43:15.058  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 08:43:15.058  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 08:43:15.058  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 08:43:15.058  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 08:43:15.058  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 08:43:15.058  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 08:43:15.058  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 08:43:15.058  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 08:43:15.058  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 08:43:15.058  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 08:43:15.058  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 08:43:15.058  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 08:43:15.058  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 08:43:15.058  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:15.058  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:43:15.058  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:15.058  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:15.058  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:15.058  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:15.058  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:15.058  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:15.058  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:15.058  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:15.058  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:15.058  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:15.058  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:15.058  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:15.059  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:43:15.059  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:15.059  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:15.059  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:15.059  5559  5606 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 08:43:15.060  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:43:15.062  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:43:15.062  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:15.062  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:15.062  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:15.062  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:43:15.062  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:15.062  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:43:15.062  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:43:15.063  5559  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:15.063  5559  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:43:15.063  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:43:15.063  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:43:15.063  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:43:15.063  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:43:15.063  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:43:15.065  5559  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 08:43:15.065  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 08:43:15.067  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:15.069  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 08:43:15.069  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:15.070  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 08:43:15.070  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 08:43:15.071  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 08:43:15.072  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 08:43:15.072  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 08:43:15.072  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 08:43:15.073  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 08:43:15.073  5559  5606 D BluetoothAdapter: STATE_ON
08-29 08:43:15.075  4380  4394 D BtGatt.GattService: registerClient() - UUID=f2757a99-3f2a-444d-93b9-fc5939413495
08-29 08:43:15.076  4380  4442 D BtGatt.GattService: onClientRegistered() - UUID=f2757a99-3f2a-444d-93b9-fc5939413495, clientIf=5
08-29 08:43:15.076  5559  5570 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 08:43:15.077  4380  4580 D BtGatt.GattService: start scan with filters
08-29 08:43:15.082  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 08:43:15.082  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 08:43:15.082  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:43:15.082  4380  4445 D BtGatt.ScanManager: handling starting scan
08-29 08:43:15.082  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 08:43:15.084  4380  4445 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
08-29 08:43:15.084  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:43:15.085  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 08:43:15.085  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:43:15.086  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 08:43:15.087  5559  5606 I io.jxcore.node.ConnectionHelper: start: OK
08-29 08:43:15.093  4380  4442 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 08:43:15.093  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:15.093  4380  4445 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 08:43:15.100  4380  4442 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 08:43:15.100  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:15.101  4380  4445 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:43:15.101  4380  4445 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 08:43:15.111  4380  4442 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 08:43:15.112  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:15.118  4380  4442 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 08:43:15.118  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:43:15.586  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 08:43:15.587  5559  5559 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:43:15.587  5559  5559 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 08:43:16.250   928  5260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=319680, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 08:43:20.091  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:43:20.092  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:20.092  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 08:43:20.092  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:20.092  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 08:43:20.092  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 08:43:20.092  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:43:20.092  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:43:20.092  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 08:43:20.093  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:43:20.093  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 08:43:20.094  5559  5606 D BluetoothAdapter: STATE_ON
08-29 08:43:20.095  4380  4394 D BtGatt.GattService: stopScan() - queue size =1
08-29 08:43:20.096  4380  4580 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:43:20.097  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:43:20.097  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:43:20.098  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 08:43:20.098  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 08:43:20.098  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 08:43:20.102  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:43:20.102  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:43:20.103  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:43:20.103  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:43:20.104  4380  4380 D BtGatt.ScanManager: awakened up at time 323534
08-29 08:43:20.105  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 08:43:20.108  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:20.109  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 08:43:20.109  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:20.109  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:43:20.109  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:43:20.109  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:43:20.111  4380  4442 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 08:43:20.111  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:20.111  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:20.111  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:20.111  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
,08-29 08:43:20.111  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:20.111  4380  4445 D BtGatt.ScanManager: stopping BLe Batch
08-29 08:43:20.111  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:43:20.118  4380  4442 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 08:43:20.119  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:20.119  4380  4445 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 08:43:20.136  4380  4442 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-29 08:43:20.137  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:20.137  4380  4442 D BtGatt.GattService: current time is 323567581489
,08-29 08:43:20.137  4380  4442 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -72, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -78, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -78, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -77, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -85, 84, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -82, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 08:43:20.138  4380  4442 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 08:43:20.139  4380  4442 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 08:43:20.139  4380  4442 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-29 08:43:20.140  4380  4442 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 08:43:20.140  4380  4442 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 08:43:20.140  4380  4442 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-29 08:43:20.610  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 08:43:25.113  5559  5606 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 08:43:25.118  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:43:25.128  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:43:25.128  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:25.128  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:25.128  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:25.128  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:43:25.128  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:25.128  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:43:25.128  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:43:25.131  5559  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:43:25.131  5559  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:43:25.132  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:43:25.132  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:43:25.132  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:43:25.132  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:43:25.132  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 08:43:25.135  5559  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 08:43:25.135  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 08:43:25.136  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:25.140  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:25.140  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 08:43:25.141  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 08:43:25.141  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:43:25.144  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 08:43:25.145  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 08:43:25.145  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 08:43:25.145  5559  5606 D BluetoothAdapter: STATE_ON
,08-29 08:43:25.148  4380  4394 D BtGatt.GattService: registerClient() - UUID=e866eff7-b331-4662-879a-c4389a6bec27
,08-29 08:43:25.148  4380  4442 D BtGatt.GattService: onClientRegistered() - UUID=e866eff7-b331-4662-879a-c4389a6bec27, clientIf=5
08-29 08:43:25.149  5559  5569 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 08:43:25.149  4380  4395 D BtGatt.GattService: start scan with filters
08-29 08:43:25.152  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 08:43:25.152  4380  4445 D BtGatt.ScanManager: handling starting scan
08-29 08:43:25.152  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 08:43:25.152  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 08:43:25.152  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:43:25.155  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 08:43:25.155  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 08:43:25.155  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:43:25.156  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 08:43:25.159  4380  4442 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 08:43:25.159  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:25.159  4380  4445 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 08:43:25.160  5559  5606 I io.jxcore.node.ConnectionHelper: start: OK
08-29 08:43:25.165  4380  4442 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 08:43:25.165  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:43:25.165  4380  4445 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:43:25.165  4380  4445 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 08:43:25.165  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:25.165  5559  5606 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 08:43:25.165  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:25.165  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 08:43:25.166  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:25.166  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 08:43:25.166  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:43:25.166  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:43:25.166  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:43:25.166  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:43:25.166  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:43:25.166  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 08:43:25.167  5559  5606 D BluetoothAdapter: STATE_ON
08-29 08:43:25.167  4380  4394 D BtGatt.GattService: stopScan() - queue size =1
08-29 08:43:25.168  4380  4581 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:43:25.169  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:43:25.169  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:43:25.169  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 08:43:25.169  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 08:43:25.169  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 08:43:25.170  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:43:25.170  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 08:43:25.170  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:43:25.170  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:43:25.171  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:43:25.172  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:25.172  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:25.172  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:43:25.172  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:25.172  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:43:25.172  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:25.172  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:25.172  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:43:25.172  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:25.172  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:43:25.172  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:25.173  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:25.173  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:25.174  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:43:25.175  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:25.175  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:25.175  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:25.175  5559  5606 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 08:43:25.176  4380  4442 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 08:43:25.176  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:25.177  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:43:25.182  4380  4442 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 08:43:25.182  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:43:25.184  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:43:25.184  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:25.184  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:25.184  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:25.184  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:43:25.184  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:25.184  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:43:25.184  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:43:25.186  5559  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:43:25.186  5559  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:43:25.186  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:43:25.186  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:43:25.186  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:43:25.186  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:43:25.186  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:43:25.190  5559  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 08:43:25.190  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 08:43:25.190  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:25.191  4380  4442 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 08:43:25.191  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:25.191  4380  4445 D BtGatt.ScanManager: stopping BLe Batch
08-29 08:43:25.194  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:25.195  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 08:43:25.196  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 08:43:25.196  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:43:25.196  4380  4442 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 08:43:25.196  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:25.196  4380  4445 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 08:43:25.202  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 08:43:25.202  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 08:43:25.202  4380  4442 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 08:43:25.202  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:25.202  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 08:43:25.202  5559  5606 D BluetoothAdapter: STATE_ON
,08-29 08:43:25.204  4380  4580 D BtGatt.GattService: registerClient() - UUID=6a221bf7-80f9-46bc-bae6-e636d000285f
08-29 08:43:25.205  4380  4442 D BtGatt.GattService: onClientRegistered() - UUID=6a221bf7-80f9-46bc-bae6-e636d000285f, clientIf=5
,08-29 08:43:25.205  5559  5569 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 08:43:25.206  4380  4395 D BtGatt.GattService: start scan with filters
08-29 08:43:25.208  4380  4445 D BtGatt.ScanManager: handling starting scan
,08-29 08:43:25.208  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 08:43:25.208  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 08:43:25.208  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:43:25.208  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:43:25.210  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:43:25.210  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 08:43:25.210  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:43:25.211  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 08:43:25.213  4380  4442 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 08:43:25.213  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:25.213  4380  4445 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 08:43:25.214  5559  5606 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 08:43:25.218  4380  4442 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-29 08:43:25.218  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:25.218  4380  4445 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:43:25.218  4380  4445 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 08:43:25.227  4380  4442 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 08:43:25.227  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:43:25.232  4380  4442 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 08:43:25.233  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:43:25.712  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-29 08:43:25.712  5559  5559 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 08:43:25.712  5559  5559 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 08:43:28.744   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 08:43:28.745   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 08:43:30.215  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:43:30.215  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:43:30.215  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 08:43:30.215  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:30.215  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 08:43:30.216  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:43:30.216  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:43:30.216  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:43:30.216  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:43:30.216  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:43:30.216  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 08:43:30.218  5559  5606 D BluetoothAdapter: STATE_ON
,08-29 08:43:30.221  4380  4581 D BtGatt.GattService: stopScan() - queue size =1
,08-29 08:43:30.223  4380  4394 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:43:30.224  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:43:30.224  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:43:30.224  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 08:43:30.224  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 08:43:30.225  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 08:43:30.228  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:43:30.229  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:43:30.229  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:43:30.229  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:43:30.231  4380  4380 D BtGatt.ScanManager: awakened up at time 333662
08-29 08:43:30.231  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:43:30.233  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 08:43:30.233  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:43:30.233  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 08:43:30.237  4380  4442 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 08:43:30.237  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:30.237  4380  4445 D BtGatt.ScanManager: stopping BLe Batch
,08-29 08:43:30.245  4380  4442 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 08:43:30.246  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:30.246  4380  4445 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 08:43:30.262  4380  4442 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-29 08:43:30.262  4380  4442 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:43:30.262  4380  4442 D BtGatt.GattService: current time is 333692960287
,08-29 08:43:30.262  4380  4442 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -78, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -78, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -72, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -78, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -77, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-29 08:43:30.263  4380  4442 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 08:43:30.263  4380  4442 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 08:43:30.263  4380  4442 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-29 08:43:30.263  4380  4442 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 08:43:30.264  4380  4442 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 08:43:30.264  4380  4442 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-29 08:43:30.734  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 08:43:30.735  5559  5559 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:30.735  5559  5559 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 08:43:35.234  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:43:35.235  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:43:35.235  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:43:35.235  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:43:35.235  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:43:35.235  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 08:43:35.235  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:35.236  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.236  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
,08-29 08:43:35.236  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:35.236  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:43:35.237  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.238  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:43:35.242  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:43:35.242  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:35.242  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.242  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
,08-29 08:43:35.244  5559  5606 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 08:43:35.245  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:35.246  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:35.246  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:35.246  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:35.246  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.246  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.246  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:35.247  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.247  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
,08-29 08:43:35.247  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:35.247  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.247  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.247  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.247  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:43:35.251  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:43:35.251  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:35.251  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:43:35.251  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.253  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 08:43:35.253  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:35.253  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:35.253  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:35.253  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:35.254  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.254  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:43:35.254  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:35.254  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.254  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.254  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:35.254  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.254  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.254  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.254  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:43:35.256  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:43:35.256  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:35.256  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.256  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.257  5559  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 08:43:35.258  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:35.258  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:35.258  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:35.258  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:35.258  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:43:35.258  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.258  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:35.258  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.258  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.259  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:35.259  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.259  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.259  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.259  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:43:35.260  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:43:35.260  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:35.260  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.261  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.262  5559  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 08:43:35.262  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:35.262  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:35.262  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:43:35.262  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:35.262  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.262  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.262  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:35.263  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.263  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.263  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:35.263  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.263  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.263  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.263  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.264  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:43:35.264  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:35.265  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.265  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.266  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 08:43:35.266  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 08:43:35.266  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 08:43:35.266  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 08:43:35.266  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:43:35.266  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:43:35.266  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 08:43:35.266  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 08:43:35.266  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 08:43:35.267  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:35.267  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:35.267  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:35.267  5559  5606 I org,.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:35.267  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.267  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.267  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:35.267  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.267  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.267  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:35.267  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.269  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.269  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.269  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.270  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:43:35.270  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:35.270  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.270  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
,08-29 08:43:35.271  5559  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:43:35.271  5559  5606 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 08:43:35.272  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 08:43:35.274  5559  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:43:35.274  5559  5606 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 08:43:35.275  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 08:43:35.276  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-29 08:43:35.276  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 08:43:35.276  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 08:43:35.276  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 08:43:35.276  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-29 08:43:35.276  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 08:43:35.276  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-29 08:43:35.276  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 08:43:35.276  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 08:43:35.276  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 08:43:35.276  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 08:43:35.276  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 08:43:35.276  5559  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 08:43:35.277  5559  5606 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 08:43:35.277  5559  5606 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 08:43:35.277  5559  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:43:35.277  5559  5606 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 08:43:35.277  5559  5606 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 08:43:35.277  5559  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:43:35.277  5559  5606 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 08:43:35.277  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 08:43:35.281  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 08:43:35.282  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 08:43:35.282  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 08:43:35.282  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 08:43:35.282  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 08:43:35.283  5559  5606 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 08:43:35.283  5559  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:43:35.283  5559  5606 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 08:43:35.283  5559  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 122)
08-29 08:43:35.284  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:35.284  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:35.284  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:35.284  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:35.284  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist ,in the list - probably already removed
08-29 08:43:35.284  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.284  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 08:43:35.285  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:35.285  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.286  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.286  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:35.286  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.286  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.286  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.286  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.286  5559  5609 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:43:35.287  5559  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 122
08-29 08:43:35.287  5559  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 122)
08-29 08:43:35.287  5559  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 122)
08-29 08:43:35.289  5559  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 122)
08-29 08:43:35.290  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:43:35.290  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:35.290  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.290  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.291  5559  5606 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 08:43:35.291  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:35.292  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:35.292  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:35.292  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:35.292  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.292  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.292  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08,-29 08:43:35.292  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.296  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.296  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:35.296  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.296  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.296  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.296  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.298  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:43:35.298  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:35.298  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.298  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.299  5559  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 08:43:35.306  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:35.306  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:35.306  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:35.306  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:35.306  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.306  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.306  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:35.306  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.306  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.306  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:35.306  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.306  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.306  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.306  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.307  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:43:35.307  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:35.307  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.308  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.308  5559  5606 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 08:43:35.308  5559  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 08:43:35.308  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 08:43:35.308  5559  5606 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 08:43:35.308  5559  5606 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 08:43:35.308  5559  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 08:43:35.308  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 08:43:35.308  5559  5606 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 08:43:35.309  5559  5606 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 08:43:35.309  5559  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 08:43:35.309  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 08:43:35.309  5559  5606 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 08:43:35.309  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:35.309  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:35.309  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:35.309  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:35.309  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.309  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.309  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:35.309  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.309  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.309  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:35.309  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.309  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.309  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.309  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.310  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:43:35.310  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:35.310  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.310  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.311  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:35.311  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.311  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:35.311  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:35.311  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:35.311  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:35.311  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:35.311  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:35.311  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:43:40.312  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:43:40.312  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:40.313  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:40.313  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.313  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:40.313  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:40.313  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:40.314  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:40.314  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:43:40.314  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:40.314  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.314  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:40.314  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:40.315  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:40.315  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
,08-29 08:43:40.315  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:40.315  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.315  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:40.315  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.315  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:40.319  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:43:40.319  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:40.320  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:40.320  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
,08-29 08:43:40.324  5559  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-29 08:43:40.325  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:43:40.327  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 08:43:40.329  5559  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 08:43:40.330  5559  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 08:43:40.330  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 08:43:40.330  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:43:40.330  5559  5559 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-29 08:43:40.331  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:40.331  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 08:43:40.331  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 08:43:40.331  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 08:43:40.331  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:40.331  5559  5611 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:43:40.331  5559  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 08:43:40.332  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:40.332  5559  5559 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 08:43:40.332  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:40.332  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:43:40.332  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:43:40.332  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:43:40.332  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.332  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:43:40.333  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:43:40.333  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:40.334  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:43:40.334  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:43:40.334  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:40.334  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:43:40.334  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:40.334  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:40.334  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:43:40.334  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.334  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:43:40.334  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:40.334  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:40.334  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:40.334  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:40.334  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.334  5559  5611 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 08:43:40.334  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:40.334  5559  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 08:43:40.334  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.335  5559  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 08:43:40.335  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:40.335  5559  5559 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-29 08:43:40.336  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:43:40.336  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:40.336  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:40.336  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:40.338  5559  5606 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 08:43:40.338  5559  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 08:43:40.338  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 08:43:40.338  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:43:40.339  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 08:43:40.339  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:40.339  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:40.339  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:40.339  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:40.339  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.339  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:40.339  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:40.339  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:40.339  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:40.339  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:40.339  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.340  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:43:40.340  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.340  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:40.341  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:43:40.341  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:40.341  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:40.342  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
,08-29 08:43:40.347  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:43:40.347  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:40.347  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:40.347  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:40.347  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.347  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:40.347  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:40.347  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:40.347  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:40.348  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:43:40.348  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.348  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:40.348  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.348  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:43:40.351  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:43:40.351  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:40.351  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:40.351  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:40.352  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:43:40.352  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:43:40.352  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:43:40.352  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:43:40.352  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.352  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:40.352  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a9a2 not in the list
08-29 08:43:40.353  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:40.353  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:40.353  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:43:40.353  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.353  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:40.353  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:40.353  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:40.355  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:43:40.355  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:43:40.355  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:40.355  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3c633 not in the list
08-29 08:43:40.356  5559  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 08:43:40.356  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 08:43:40.356  5559  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 08:43:40.356  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 08:43:40.356  5559  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-29 08:43:40.356  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 08:43:40.358  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 08:43:40.358  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 08:43:40.359  5559  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-29 08:43:40.359  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 08:43:40.359  5559  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 08:43:40.359  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 08:43:40.359  5559  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 08:43:40.359  5559  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 08:43:40.360  5559  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 08:43:40.360  5559  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-29 08:43:40.361  5559  5606 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 08:43:40.361  5559  5606 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 08:43:40.361  5559  5606 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 08:43:40.361  5559  5606 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 08:43:40.362  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:43:40.362  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f767dd added. We now have 3 listener(s)
08-29 08:43:40.362  5559  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:43:40.364  5559  5606 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 08:43:40.364   928  3569 D WifiService: setWifiEnabled: true pid=5559, uid=10077
08-29 08:43:40.364   928  3569 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:43:40.416  4380  4572 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-29 08:43:40.416  4380  4577 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,08-29 08:43:40.834  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 08:43:43.746   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:43:44.748   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:43:45.369  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:43:45.370  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eabf52 added. We now have 4 listener(s)
08-29 08:43:45.370  5559  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:43:45.384  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:43:45.384  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eabf52 removed from the list
,08-29 08:43:45.385  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:43:45.385  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:43:45.385  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:43:45.387  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:43:45.387  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5aaa223 added. We now have 4 listener(s)
08-29 08:43:45.387  5559  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:43:45.393  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:43:45.393  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5aaa223 removed from the list
08-29 08:43:45.394  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:43:45.394  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:43:45.394  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:43:45.396  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:43:45.396  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11fe320 added. We now have 4 listener(s)
08-29 08:43:45.396  5559  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:43:45.402   928  4956 D WifiService: setWifiEnabled: false pid=5559, uid=10077
08-29 08:43:45.403   928  4956 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:43:45.408   928  2993 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 08:43:45.409   928  2993 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 08:43:45.409   928  2993 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 08:43:45.412  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:43:45.414  4380  4438 D BluetoothAdapterState: Current state: ON, message: 23
08-29 08:43:45.414  4380  4438 D BluetoothAdapterProperties: Setting state to 13
08-29 08:43:45.414  4380  4438 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 08:43:45.415   928  2993 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 08:43:45.416  4380  4438 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 08:43:45.416  4380  4438 I BluetoothAdapterState: Entering PendingCommandState
,08-29 08:43:45.417  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:45.417  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:43:45.417  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:45.417  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:45.417  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:45.417  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:45.417  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:45.417  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:43:45.417  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:43:45.418  4380  4442 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:43:45.419  4380  4438 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 08:43:45.419  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:45.420  5559  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:45.420  5559  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:43:45.421  4380  4380 D HeadsetService: Received stop request...Stopping profile...
,08-29 08:43:45.424  3160  3171 D BluetoothHeadset: Proxy object disconnected
,08-29 08:43:45.424  3160  3160 D HeadsetProfile: Bluetooth service disconnected
08-29 08:43:45.424   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 08:43:45.424  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:45.424   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 08:43:45.424   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 08:43:45.425  3544  3560 D BluetoothHeadset: Proxy object disconnected
08-29 08:43:45.425  4380  4380 D A2dpService: Received stop request...Stopping profile...
,08-29 08:43:45.425  4380  4583 D A2dpStateMachine: Exit Disconnected: -1
08-29 08:43:45.427  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:45.430   928   928 D BluetoothA2dp: Proxy object disconnected
08-29 08:43:45.432  3160  3160 D BluetoothA2dp: Proxy object disconnected
,08-29 08:43:45.432  4380  4380 V BluetoothAdapterState: isTurningOff()=true
,08-29 08:43:45.432  4380  4380 V BluetoothAdapterState: isTurningOn()=false
08-29 08:43:45.432  4380  4380 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:43:45.432  4380  4380 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:43:45.433  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:45.433  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:45.433  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:45.433  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:45.433  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:45.433  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:45.433  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:45.433  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:43:45.433  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:43:45.434  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:45.434  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:45.435  4380  4380 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 08:43:45.435  4380  4380 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 08:43:45.435  4380  4572 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:43:45.435  4380  4380 V BluetoothAdapterState: isTurningOff()=true
08-29 08:43:45.436  4380  4572 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:43:45.436  4380  4380 V BluetoothAdapterState: isTurningOn()=false
08-29 08:43:45.436  4380  4572 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:43:45.436  4380  4380 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:43:45.436  4380  4442 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 08:43:45.436  4380  4380 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:43:45.436  4380  4442 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
08-29 08:43:45.437  4380  4572 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:43:45.438  4380  4572 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:43:45.438  4380  4442 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 08:43:45.438  4380  4572 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:43:45.438  4380  4572 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:43:45.438  4380  4572 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:43:45.438  4380  4572 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:43:45.439  4380  4380 D HidService: Received stop request...Stopping profile...
08-29 08:43:45.440  4380  4380 D HidService: Stopping Bluetooth HidService
,08-29 08:43:45.440  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:45.441  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:45.441  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:45.441  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:45.441  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:45.441  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:45.441  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:45.441  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:43:45.441  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:43:45.441  4380  4380 D HealthService: Received stop request...Stopping profile...
08-29 08:43:45.441  3160  3160 D BluetoothInputDevice: Proxy object disconnected
08-29 08:43:45.441  3160  3160 D HidProfile: Bluetooth service disconnected
08-29 08:43:45.441  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:45.441  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:43:45.443  4380  4380 D PanService: Received stop request...Stopping profile...
,08-29 08:43:45.443  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:45.443  3160  3160 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 08:43:45.444  3160  3160 D PanProfile: Bluetooth service disconnected
08-29 08:43:45.444  4380  4380 D BluetoothMapService: Received stop request...Stopping profile...
08-29 08:43:45.444  4380  4380 D BluetoothMapService: stop()
08-29 08:43:45.444  4380  4380 D BluetoothMapAppObserver: deinitObservers()
08-29 08:43:45.444  4380  4380 D BluetoothMapAppObserver: removeReceiver()
08-29 08:43:45.446   928  2993 E native  : do suspend true
,08-29 08:43:45.446  3160  3160 D BluetoothMap: Proxy object disconnected
08-29 08:43:45.446  4380  4380 D SapService: Received stop request...Stopping profile...
08-29 08:43:45.446  3160  3160 D MapProfile: Bluetooth service disconnected
08-29 08:43:45.446  4380  4380 V SapService: stop()
08-29 08:43:45.448  4380  4380 V BluetoothAdapterState: isTurningOff()=true
08-29 08:43:45.448  4380  4380 V BluetoothAdapterState: isTurningOn()=false
08-29 08:43:45.448  4380  4380 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 08:43:45.448  4380  4380 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:43:45.448  4380  4380 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 08:43:45.449  4380  4380 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 08:43:45.449  4380  4380 V BluetoothAdapterState: isTurningOff()=true
08-29 08:43:45.449  4380  4380 V BluetoothAdapterState: isTurningOn()=false
08-29 08:43:45.449  4380  4380 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:43:45.449  4380  4380 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:43:45.450  4380  4442 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 08:43:45.450  4380  4380 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 08:43:45.450  4380  4442 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 08:43:45.450  4380  4380 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 08:43:45.450  4380  4380 V BluetoothAdapterState: isTurningOff()=true
08-29 08:43:45.450  4380  4380 V BluetoothAdapterState: isTurningOn()=false
08-29 08:43:45.451  4380  4380 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:43:45.451  4380  4380 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:43:45.451  4380  4380 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 08:43:45.451  4380  4380 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 08:43:45.452  4380  4380 D BluetoothMapService: MAP Service closeService in
08-29 08:43:45.452  4380  4380 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 08:43:45.452  4380  4380 D ObexServerSockets0: shutdown(block = true)
08-29 08:43:45.453  4380  4380 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 08:43:45.453  4380  4601 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 08:43:45.453  4380  4380 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 08:43:45.453  4380  4577 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 08:43:45.453  4380  4600 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-29 08:43:45.454  4380  4380 V BluetoothAdapterState: isTurningOff()=true
08-29 08:43:45.454  4380  4380 V BluetoothAdapterState: isTurningOn()=false
08-29 08:43:45.454  4380  4380 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:43:45.454  4380  4380 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:43:45.454  4380  4380 D BluetoothMapService: cleanup()
08-29 08:43:45.454  4380  4380 D BluetoothMapService: MAP Service closeService in
,08-29 08:43:45.455  4380  4380 V BluetoothAdapterState: isTurningOff()=true
08-29 08:43:45.455  4380  4380 V BluetoothAdapterState: isTurningOn()=false
08-29 08:43:45.455  4380  4380 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:43:45.455  4380  4380 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:43:45.456  4380  4438 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-29 08:43:45.456  4380  4438 D BluetoothAdapterProperties: Setting state to 15
08-29 08:43:45.456  4380  4438 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 08:43:45.456  4380  4438 I BluetoothAdapterState: Entering BleOnState
,08-29 08:43:45.467  4380  4380 I BtOppRfcommListener: stopping Accept Thread
08-29 08:43:45.468  4380  5177 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 08:43:45.468  4380  5177 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 08:43:45.469   506   926 D CommandListener: Clearing all IP addresses on wlan0
08-29 08:43:45.470   928  5261 D DhcpClient: Clearing IP address
08-29 08:43:45.470  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:45.472   506   926 D CommandListener: Setting iface cfg
08-29 08:43:45.472  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:45.474  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:45.476   928  5262 D DhcpClient: Receive thread stopped
08-29 08:43:45.479  3625  5315 V NativeCrypto: Read error: ssl=0x7f94597200: I/O error during system call, Connection timed out
,08-29 08:43:45.481  3625  5315 V NativeCrypto: SSL shutdown failed: ssl=0x7f94597200: I/O error during system call, Broken pipe
08-29 08:43:45.483   928  3428 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
08-29 08:43:45.484   928  5259 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,08-29 08:43:45.490   928  5259 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 08:43:45.490   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-29 08:43:45.490   928  3006 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 08:43:45.490   928   941 I ActivityManager: Start proc 5615:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-29 08:43:45.491  3160  3168 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 08:43:45.492   928  3006 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 08:43:45.492   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 08:43:45.492   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-29 08:43:45.495   534   534 E Parcel  : Reading a NULL string not supported here.
,08-29 08:43:45.500  3544  3563 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 08:43:45.500   928  3006 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 08:43:45.500   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:43:45.500   928   928 D RttService: SCAN_AVAILABLE : 1
08-29 08:43:45.500   928  3082 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:43:45.500  3160  3171 D BluetoothPan: onBluetoothStateChange on: false
08-29 08:43:45.501  3160  3716 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:43:45.501   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:43:45.501  3160  3168 D BluetoothMap: onBluetoothStateChange: up=false
08-29 08:43:45.501  3510  3669 W QCNEJ   : |CORE| network lost: 100
08-29 08:43:45.502   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 08:43:45.502   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:43:45.502  3510  3669 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
08-29 08:43:45.502  3160  3716 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 08:43:45.503  3160  3171 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 08:43:45.503  4380  4438 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 08:43:45.503  4380  4438 D BluetoothAdapterProperties: Setting state to 16
08-29 08:43:45.503  4380  4438 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 08:43:45.504  4380  4438 D BluetoothAdapterProperties: onBleDisable
08-29 08:43:45.504  4380  4438 I BluetoothAdapterState: Entering PendingCommandState
08-29 08:43:45.505  4380  4439 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 08:43:45.505  4380  4442 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:43:45.507  4380  4572 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 08:43:45.507   928  2993 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 08:43:45.508  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:45.508  4380  4572 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:43:45.508  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:45.508  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:45.508  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:45.508  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:45.508  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:45.508  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:45.508  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:45.508  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:43:45.510  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:45.510  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:43:45.513  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:43:45.513  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:45.513  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:45.513  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:45.513  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:45.513  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:45.513  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:45.513  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:45.513  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:43:45.514  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:45.514  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:43:45.516  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:45.516  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:45.516  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:45.516  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:45.516  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:45.516  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:45.516  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:45.516  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:45.516  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:43:45.517   928  2993 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 08:43:45.517   928  2993 E native  : do suspend true
08-29 08:43:45.517  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:45.517  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:43:45.520  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:45.525  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:45.527  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:45.537   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:43:45.539  5615  5615 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,08-29 08:43:45.549  5615  5615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 08:43:45.554   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@90c841e:true
,08-29 08:43:45.555   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 08:43:45.555   506   926 D CommandListener: Clearing all IP addresses on wlan0
,08-29 08:43:45.555  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 08:43:45.555   506   926 D TetherController: Setting IP forward enable = 0
08-29 08:43:45.556   928  3006 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 08:43:45.557   928  3006 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:43:45.559   928  2993 D DhcpClient: doQuit
,08-29 08:43:45.559   928  2993 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 08:43:45.560   928   945 D Tethering: MasterInitialState.processMessage what=3
08-29 08:43:45.560  3645  3645 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
08-29 08:43:45.562   928  5261 D DhcpClient: onQuitting
08-29 08:43:45.562  5151  5151 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@214037f and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-29 08:43:45.564  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:45.564  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:45.564  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:45.564  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:45.564  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:43:45.564  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:45.564  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:45.564  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:45.564  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:43:45.564  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:43:45.565  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:43:45.565  4819  4855 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 08:43:45.565  4819  4855 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 08:43:45.565  4819  4855 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 08:43:45.565  4819  4855 E SarControlService: no key has been found,reset the power
08-29 08:43:45.566  4819  4869 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 08:43:45.566  4819  4869 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 08:43:45.566  4819  4869 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 08:43:45.566  4858  4858 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 08:43:45.566  4858  4858 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,08-29 08:43:45.568  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:43:45.568  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:45.568  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:45.568  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:45.568  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:43:45.568  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:45.568  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:45.568  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:45.568  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:43:45.569  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:45.569  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:43:45.570  4819  4869 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,08-29 08:43:45.570  4819  4869 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,08-29 08:43:45.571  4819  4869 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 08:43:45.571  4858  4858 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 08:43:45.571  4858  4858 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 08:43:45.572  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:45.572  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:45.572  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:45.572  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:45.572  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:43:45.572  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:45.572  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:45.572  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:45.572  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:43:45.573  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:43:45.573  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:43:45.574  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:45.576  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:45.577  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:45.578  4858  4875 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d764c1d HexData = [00000000ea03000000000000ffffffff]
08-29 08:43:45.578  4858  4875 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 08:43:45.578  4858  4875 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
08-29 08:43:45.579  4858  4858 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 08:43:45.579   928  3574 I ActivityManager: Start proc 5640:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 08:43:45.581  4819  4829 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 08:43:45.588  4858  4875 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d764c1d HexData = [00000000eb03000000000000ffffffff]
08-29 08:43:45.590  4858  4875 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 08:43:45.590  4858  4875 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
08-29 08:43:45.590  4858  4858 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 08:43:45.591  4819  4830 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-29 08:43:45.597  5615  5615 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 08:43:45.600  5615  5615 D BluetoothMap: Create BluetoothMap proxy object
08-29 08:43:45.608  3645  3645 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 08:43:45.614  3645  3645 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 08:43:45.618  5615  5615 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 08:43:45.618   506   926 E Netd    : netlink response contains error (No such file or directory)
,08-29 08:43:45.619   928  3006 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 08:43:45.619   506   926 D TetherController: Setting IP forward enable = 0
,08-29 08:43:45.626  5640  5640 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,08-29 08:43:45.636  5615  5615 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:43:45.639   928  3173 I ActivityManager: Killing 4971:com.google.android.gm/u0a68 (adj 15): empty #17
,08-29 08:43:45.650  3645  3645 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 08:43:45.680  3645  3645 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 08:43:45.712  4380  4442 I bt_hci  : shut_down
,08-29 08:43:45.716  4380  4446 D bt_hwcfg: hw_epilog_process
,08-29 08:43:45.716  4380  4446 I bt_vendor: low_power_mode_cb
,08-29 08:43:45.718  4380  4446 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 08:43:45.718  4380  4446 I bt_vendor: epilog_cb
08-29 08:43:45.718  4380  4446 I bt_hci  : epilog_finished_callback
,08-29 08:43:45.721  4380  4442 I bt_hci_h4: hal_close
,08-29 08:43:45.722  4380  4442 I bt_userial_vendor: device fd = 51 close
,08-29 08:43:45.748   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:43:45.782  4227  4227 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:43:45.782   928  2993 D wifi    : In wifi stop Hal
,08-29 08:43:45.783   928  2993 D wifi    : halHandle = 0x7f785a18a0, mVM = 0x7f9450d140, mCls = 0x100b3a
08-29 08:43:45.783   928  3641 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 08:43:45.783   928  3641 D WifiHAL : Got a signal to exit!!!
08-29 08:43:45.783   928  3641 I WifiHAL : Exit wifi_event_loop
08-29 08:43:45.784   928  2993 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 08:43:45.784   928  2993 E WifiHAL : Event processing terminated
08-29 08:43:45.784   928  2993 D wifi    : In wifi cleaned up handler
08-29 08:43:45.784   928  2993 I WifiHAL : Internal cleanup completed
08-29 08:43:45.785  3483  3979 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 08:43:45.785  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:45.787  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:45.789  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:45.802   928  3641 D wifi    : set interface wlan0 flags (DOWN)
,08-29 08:43:45.803   928  2993 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 08:43:45.826  5640  5640 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:43:45.826  5640  5640 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:43:45.826  5640  5640 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:43:45.826  5640  5640 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:43:45.826  5640  5640 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:43:45.826  5640  5640 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:43:45.826  5640  5640 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:43:45.826  5640  5640 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:43:45.826  5640  5640 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:43:45.831  5615  5615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 08:43:45.836  4380  4439 D bt_stack_manager: event_shut_down_stack finished.
08-29 08:43:45.836  4380  4438 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-29 08:43:45.837  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 08:43:45.837  4380  4438 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 08:43:45.838  4380  4380 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 08:43:45.839  4380  4380 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 08:43:45.839  4380  4380 D BtGatt.GattService: stop()
08-29 08:43:45.839  4380  4380 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 08:43:45.840  4380  4380 V BluetoothAdapterState: isTurningOff()=false
08-29 08:43:45.841  4380  4380 V BluetoothAdapterState: isTurningOn()=false
08-29 08:43:45.841  4380  4380 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:43:45.841  4380  4380 V BluetoothAdapterState: isBleTurningOff()=true
08-29 08:43:45.841  4380  4438 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 08:43:45.841  4380  4438 D BluetoothAdapterProperties: Setting state to 10
08-29 08:43:45.841  4380  4438 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 08:43:45.842   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-29 08:43:45.842  4380  4438 I BluetoothAdapterState: Entering OffState
08-29 08:43:45.847  4380  4380 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 08:43:45.847  4380  4380 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 08:43:45.847  4380  4380 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 08:43:45.848  4380  4439 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 08:43:45.850  4380  4439 D bt_stack_manager: event_clean_up_stack finished.
08-29 08:43:45.843  5615  5615 D DockEventReceiver: finishStartingService: stopping service
08-29 08:43:45.852  4380  4380 I art     : System.exit called, status: 0
08-29 08:43:45.853  4380  4380 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 08:43:45.861   928   939 I ActivityManager: Killing 5289:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,08-29 08:43:45.896  3891  3891 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 08:43:45.899  3891  3891 D SystemUpdateService: onCreate
,08-29 08:43:45.912  3891  3891 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 08:43:45.919  3891  3891 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 08:43:45.924  3891  5286 I iu.UploadsManager: num queued entries: 0
,08-29 08:43:45.924  3891  5286 I iu.UploadsManager: num updated entries: 0
08-29 08:43:45.925  3891  5286 I iu.SyncManager: NEXT; no task
,08-29 08:43:45.926  3891  3891 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 08:43:45.928  3891  3891 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 08:43:45.930  3891  5679 I SystemUpdateService: active receiver: enabled
,08-29 08:43:45.942   928   939 I ActivityManager: Start proc 5681:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 08:43:45.943   928  3432 I ActivityManager: Process com.android.bluetooth (pid 4380) has died
,08-29 08:43:45.953  3891  5679 I SystemUpdateService: showing system update notification
,08-29 08:43:45.993  5681  5681 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,08-29 08:43:46.001  5681  5681 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:43:46.005   928   945 D Tethering: InitialState.processMessage what=4
,08-29 08:43:46.008   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 08:43:46.014  5681  5681 D SprintDMHelper: simOperator: 
,08-29 08:43:46.014  5681  5681 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 08:43:46.026  3891  5679 V SystemUpdateService: retry (wakeup: false) in 3599907 ms
,08-29 08:43:46.028  3891  3891 D SystemUpdateService: onDestroy
,08-29 08:43:46.031  4227  5694 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 08:43:46.041   928  3428 I ActivityManager: Start proc 5695:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 08:43:46.044   928  3604 I ActivityManager: Killing 5151:com.google.android.music:main/u0a59 (adj 15): empty #17
,08-29 08:43:46.106  5695  5695 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,08-29 08:43:46.148  5695  5695 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 08:43:46.154   928   939 I ActivityManager: Killing 4452:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-29 08:43:46.240  5640  5668 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 08:43:46.248   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d718d83:true
,08-29 08:43:46.749   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:43:47.750   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:43:48.751   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 08:43:50.423   928  3428 D WifiService: setWifiEnabled: true pid=5559, uid=10077
,08-29 08:43:50.423   928  3428 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:43:50.432   506   926 D SoftapController: Softap fwReload - Ok
,08-29 08:43:50.439   506   926 D CommandListener: Setting iface cfg
,08-29 08:43:50.439   506   926 D CommandListener: Trying to bring down wlan0
08-29 08:43:50.441   506   926 D CommandListener: Clearing all IP addresses on wlan0
,08-29 08:43:50.444   928  2993 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 08:43:51.025   928  2993 D wifi    : set interface wlan0 flags (UP)
,08-29 08:43:51.028   928  2993 I WifiHAL : Initializing wifi
,08-29 08:43:51.028   928  2993 I WifiHAL : Creating socket
,08-29 08:43:51.029   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 08:43:51.031   928  2993 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-29 08:43:51.032   928  2993 D wifi    : Did set static halHandle = 0x7f785a18a0
08-29 08:43:51.032   928  2993 D wifi    : halHandle = 0x7f785a18a0, mVM = 0x7f9450d140, mCls = 0x201812
08-29 08:43:51.032   928  2993 D wifi    : array field set
08-29 08:43:51.032   928  2993 I WifiNative-HAL: interface[0] = wlan0
08-29 08:43:51.034   928  5725 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547480017056
08-29 08:43:51.034   928  5725 D wifi    : waitForHalEvents called, vm = 0x7f9450d140, obj = 0x201812, env = 0x7f780a0b80
,08-29 08:43:51.076  5726  5726 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 08:43:51.089  5726  5726 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 08:43:51.134  5726  5726 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 08:43:51.134  5726  5726 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 08:43:51.135   928  2993 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 08:43:51.137  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:51.138  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:51.139  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:51.154   928  2993 D WifiConfigStore: Loading config and enabling all networks 
,08-29 08:43:51.154  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:51.154  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:51.154  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:51.154  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:51.154  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:51.154  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:51.154  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:51.154  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:51.154  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:43:51.154  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:51.155  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:43:51.156  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:51.156  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:51.156  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:51.156  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:51.156  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:51.156  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:51.156  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:51.156  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:51.156  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:43:51.156  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:51.156  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:43:51.158  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:43:51.158  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:51.158  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:51.158  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:51.158  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:51.158  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:51.158  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:51.158  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:51.158  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:43:51.158  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:51.158  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:43:51.163   928  2993 D WifiConfigStore: loaded 0 passpoint configs
,08-29 08:43:51.164   928  2993 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 08:43:51.164   928  2993 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 08:43:51.165   928  2993 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 08:43:51.165   928  2993 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 08:43:51.165   928  2993 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 08:43:51.168   928  2993 D WifiNative-HAL: Setting external_sim to 1
,08-29 08:43:51.168   928  2993 D wifi    : setting dfs flag to true, 0x7f780ac460
,08-29 08:43:51.168  4227  4227 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:43:51.169   928  2993 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 08:43:51.169   928  2993 D wifi    : setting scan oui 0x7f780ac460
08-29 08:43:51.169   928  2993 D WifiHAL : Sending mac address OUI
,08-29 08:43:51.183   928  2993 E native  : do suspend true
,08-29 08:43:51.189   928   928 D RttService: SCAN_AVAILABLE : 3
,08-29 08:43:51.189   928  2993 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 08:43:51.189   506   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 08:43:51.189   928  3082 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 08:43:51.190   506   926 D CommandListener: Setting iface cfg
,08-29 08:43:51.195   928  2992 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,08-29 08:43:51.195   928  2992 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 08:43:51.197   928  2992 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 08:43:51.198   928  2992 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 08:43:51.227   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=354658 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=7 mControllerEnergyUsed=26 }
,08-29 08:43:53.752   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:43:54.431  5726  5726 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 08:43:54.459   928  2993 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-29 08:43:54.467   928  2993 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,08-29 08:43:54.467   928  2993 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 08:43:54.480   928  2993 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-29 08:43:54.518   928  2993 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-29 08:43:54.753   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:43:55.092  5726  5726 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 08:43:55.124  5726  5726 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 08:43:55.125  5726  5726 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 08:43:55.135   928  2993 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 08:43:55.136   928  2993 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 08:43:55.136   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 08:43:55.149   928  2993 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 08:43:55.160   506   926 D CommandListener: Setting iface cfg
,08-29 08:43:55.165   928  2993 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 08:43:55.172   928  2993 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 08:43:55.181   928  5732 D DhcpClient: Receive thread started
,08-29 08:43:55.264   928  2993 E native  : do suspend false
,08-29 08:43:55.276   928  5731 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 08:43:55.302   928  5732 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172485, domain null
,08-29 08:43:55.303   928  5731 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172485 seconds
,08-29 08:43:55.305   928  5731 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,08-29 08:43:55.325   928  5732 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 08:43:55.325   928  5731 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 08:43:55.328   506   926 D CommandListener: Setting iface cfg
,08-29 08:43:55.336   928  2993 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 08:43:55.338   928  5731 D DhcpClient: Scheduling renewal in 86399s
08-29 08:43:55.338   928  2993 E native  : do suspend true
,08-29 08:43:55.352   928  2993 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 08:43:55.354   928  2993 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 08:43:55.354   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 08:43:55.356   928  3006 D ConnectivityService: Adding iface wlan0 to network 101
08-29 08:43:55.359   928  2993 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 08:43:55.400   928  3006 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 08:43:55.400   928  3006 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 08:43:55.402   928  3006 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 08:43:55.405   928  3006 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 08:43:55.407   928  3006 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 08:43:55.412   928  3006 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 08:43:55.416   928  3006 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 08:43:55.416   928  3006 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-29 08:43:55.416   928  3006 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-29 08:43:55.416   928  2993 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 08:43:55.416   928  3006 D ConnectivityService:    accepting network in place of null
08-29 08:43:55.417   928  2993 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 08:43:55.417   928  3006 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 08:43:55.428   928  3569 D WifiService: setWifiEnabled: false pid=5559, uid=10077
08-29 08:43:55.428   928  3569 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 08:43:55.429   928  5730 D NetlinkSocketObserver: NeighborEvent{elapsedMs=358859, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:43:55.431   928  2993 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 08:43:55.431   928  2993 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 08:43:55.432   928  2993 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 08:43:55.432   928  2993 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 08:43:55.440   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:43:55.440   928  2993 E native  : do suspend true
,08-29 08:43:55.445   928  5731 D DhcpClient: Clearing IP address
,08-29 08:43:55.460   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:43:55.461   506   926 D CommandListener: Clearing all IP addresses on wlan0
,08-29 08:43:55.464   506   926 D CommandListener: Setting iface cfg
,08-29 08:43:55.473   928  3006 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 08:43:55.473   928  3006 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 08:43:55.474   928  3006 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 08:43:55.475   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 08:43:55.475   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-29 08:43:55.477  3510  3669 W QCNEJ   : |CORE| network available: 101
08-29 08:43:55.478   928   945 D Tethering: MasterInitialState.processMessage what=3
,08-29 08:43:55.478  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:43:55.479  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:55.479  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:55.479  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:55.479  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:55.479  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:55.479  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:55.479  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:55.479  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:43:55.480  3510  3669 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
08-29 08:43:55.480  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:55.480  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:55.480  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:55.480  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:55.480  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:55.480  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:55.480  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:55.480  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:55.480  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:43:55.481  3510  3669 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
08-29 08:43:55.481   928  3006 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-29 08:43:55.481  3510  3669 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
08-29 08:43:55.481  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:55.481  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:55.481  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:55.481  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:55.481  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:55.481  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:55.481  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:55.481  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:55.481  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:43:55.483  3510  3669 W QCNEJ   : |CORE| network lost: 101
,08-29 08:43:55.483  3510  3669 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
08-29 08:43:55.484   534   534 E Parcel  : Reading a NULL string not supported here.
08-29 08:43:55.489   928   928 D RttService: SCAN_AVAILABLE : 1
08-29 08:43:55.489   928  3082 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 08:43:55.489  3891  3891 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 08:43:55.493  3891  3891 D SystemUpdateService: onCreate
08-29 08:43:55.494   928  2993 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 08:43:55.497  3891  3891 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-29 08:43:55.499   928  2993 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 08:43:55.499   928  2993 E native  : do suspend true
,08-29 08:43:55.504  3891  5744 I SystemUpdateService: active receiver: enabled
,08-29 08:43:55.507   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:43:55.510   928  5732 D DhcpClient: Receive thread stopped
,08-29 08:43:55.513  3891  3891 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 08:43:55.514  3891  3891 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 08:43:55.516  5681  5681 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:43:55.520  5681  5681 D SprintDMHelper: simOperator: 
08-29 08:43:55.520  5681  5681 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 08:43:55.526   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:43:55.526   506   926 D CommandListener: Clearing all IP addresses on wlan0
,08-29 08:43:55.527   928  3006 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 08:43:55.527   928  3006 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:43:55.530   928   945 D Tethering: MasterInitialState.processMessage what=3
08-29 08:43:55.531  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:55.531  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:55.531  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:55.531  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:55.531  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:43:55.531  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:55.531  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:55.531  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:55.531  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:43:55.531   928  2993 D DhcpClient: doQuit
08-29 08:43:55.531   928  2993 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 08:43:55.531   928  5731 D DhcpClient: onQuitting
,08-29 08:43:55.532  5726  5726 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
08-29 08:43:55.532  3891  5744 I SystemUpdateService: showing system update notification
,08-29 08:43:55.534  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:55.534  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:55.534  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:55.534  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:55.534  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:43:55.534  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:55.534  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:55.534  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:55.534  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:43:55.534  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:55.534  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:43:55.535  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:55.535  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:55.535  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:55.535  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:55.535  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:43:55.535  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:55.535  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:55.535  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:55.535  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:43:55.535  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:55.535  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:43:55.536  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:55.536  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:43:55.536  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:43:55.536  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:43:55.536  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:43:55.536  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:43:55.536  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:43:55.536  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:43:55.536  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:43:55.536  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:43:55.536  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:43:55.537  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:55.537  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:55.545  3891  3891 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 08:43:55.547  3891  3891 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 08:43:55.561  5726  5726 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 08:43:55.561  3891  3891 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 08:43:55.563  3891  3891 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 08:43:55.565  5681  5681 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-29 08:43:55.566  5726  5726 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 08:43:55.569  5681  5681 D SprintDMHelper: simOperator: 
08-29 08:43:55.570  5681  5681 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 08:43:55.578  3891  5744 V SystemUpdateService: retry (wakeup: false) in 3599932 ms
,08-29 08:43:55.583   506   926 E Netd    : netlink response contains error (No such file or directory)
,08-29 08:43:55.584   928  3006 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 08:43:55.597  3891  5755 I SystemUpdateService: active receiver: enabled
,08-29 08:43:55.603  3891  5755 I SystemUpdateService: showing system update notification
,08-29 08:43:55.610  3891  5755 V SystemUpdateService: retry (wakeup: false) in 3599988 ms
,08-29 08:43:55.612  3891  3891 D SystemUpdateService: onDestroy
,08-29 08:43:55.619  5726  5726 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 08:43:55.632  5726  5726 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 08:43:55.736   928  2993 D wifi    : In wifi stop Hal
,08-29 08:43:55.736   928  2993 D wifi    : halHandle = 0x7f785a18a0, mVM = 0x7f9450d140, mCls = 0x201812
08-29 08:43:55.737   928  5725 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 08:43:55.738   928  5725 D WifiHAL : Got a signal to exit!!!
08-29 08:43:55.738   928  5725 I WifiHAL : Exit wifi_event_loop
08-29 08:43:55.741   928  2993 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 08:43:55.741   928  2993 E WifiHAL : Event processing terminated
08-29 08:43:55.742  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:55.742   928  2993 D wifi    : In wifi cleaned up handler
08-29 08:43:55.742   928  2993 I WifiHAL : Internal cleanup completed
08-29 08:43:55.743  4227  4227 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 08:43:55.745  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:43:55.749  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:43:55.750  3483  3979 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 08:43:55.753   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:43:55.762   928  5725 D wifi    : set interface wlan0 flags (DOWN)
08-29 08:43:55.762   928  2993 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 08:43:55.965   928   945 D Tethering: InitialState.processMessage what=4
,08-29 08:43:55.968   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 08:43:56.474   928  3006 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 08:43:56.754   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:43:57.755   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:43:58.756   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 08:44:00.430   928  5729 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-29 08:44:00.432   928  3006 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 08:44:00.463   928   945 I ActivityManager: Start proc 5760:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 08:44:00.542  5760  5760 D AdapterServiceConfig: Adding HeadsetService
,08-29 08:44:00.543  5760  5760 D AdapterServiceConfig: Adding A2dpService
08-29 08:44:00.543  5760  5760 D AdapterServiceConfig: Adding HidService
08-29 08:44:00.543  5760  5760 D AdapterServiceConfig: Adding HealthService
08-29 08:44:00.543  5760  5760 D AdapterServiceConfig: Adding PanService
08-29 08:44:00.543  5760  5760 D AdapterServiceConfig: Adding GattService
08-29 08:44:00.544  5760  5760 D AdapterServiceConfig: Adding BluetoothMapService
08-29 08:44:00.544  5760  5760 D AdapterServiceConfig: Adding SapService
,08-29 08:44:00.554   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f74a29f:true
,08-29 08:44:00.554  5760  5760 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 08:44:00.556  5760  5760 I bt_bluedroid: init
08-29 08:44:00.557  5760  5772 I BluetoothAdapterState: Entering OffState
,08-29 08:44:00.558  5760  5773 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 08:44:00.558  5760  5773 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 08:44:00.559  5760  5773 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 08:44:00.559  5760  5773 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 08:44:00.559  5760  5760 I bt_bluedroid: get_profile_interface socket
,08-29 08:44:00.561  5760  5776 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-29 08:44:00.561  5760  5760 I bt_bluedroid: get_profile_interface sdp
08-29 08:44:00.563  5760  5776 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 08:44:00.565  5760  5771 I bt_bluedroid: config_hci_snoop_log
,08-29 08:44:00.566   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-29 08:44:00.569  5760  5772 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 08:44:00.569  5760  5772 D BluetoothAdapterProperties: Setting state to 14
08-29 08:44:00.569  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 08:44:00.570  5760  5772 D BluetoothBondStateMachine: make
,08-29 08:44:00.572  5760  5777 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 08:44:00.574  5760  5772 I BluetoothAdapterState: Entering PendingCommandState
,08-29 08:44:00.575  5760  5760 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 08:44:00.577  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
08-29 08:44:00.578  5760  5760 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 08:44:00.578  5760  5760 D BtGatt.GattService: Received start request. Starting profile...
08-29 08:44:00.578  5760  5760 D BtGatt.GattService: start()
08-29 08:44:00.578  5760  5760 I bt_bluedroid: get_profile_interface gatt
,08-29 08:44:00.579  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
08-29 08:44:00.579  5760  5760 D BtGatt.AdvertiseManager: advertise manager created
,08-29 08:44:00.583  5760  5760 V BluetoothAdapterState: isTurningOff()=false
,08-29 08:44:00.583  5760  5760 V BluetoothAdapterState: isTurningOn()=false
08-29 08:44:00.584  5760  5760 V BluetoothAdapterState: isBleTurningOn()=true
08-29 08:44:00.584  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:00.584  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 08:44:00.584  5760  5772 I bt_bluedroid: enable
08-29 08:44:00.584  5760  5773 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 08:44:00.585  5760  5773 I bt_hci  : start_up
,08-29 08:44:00.590  5760  5773 I bt_vendor: alloc value 0xf405104d
,08-29 08:44:00.590  5760  5773 I bt_vendor: init
08-29 08:44:00.590  5760  5773 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 08:44:00.590  5760  5773 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 08:44:00.714  5760  5773 D bt_hci  : start_up starting async portion
,08-29 08:44:00.715  5760  5780 I bt_hci  : event_finish_startup
08-29 08:44:00.715  5760  5780 I bt_hci_h4: hal_open
08-29 08:44:00.715  5760  5780 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 08:44:00.718  5760  5780 I bt_userial_vendor: device fd = 51 open
,08-29 08:44:00.708  5781  5781 W irq/448-msm_hs_: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 08:44:00.732  5760  5780 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 08:44:00.734  5760  5780 D bt_hwcfg: Chipset BCM4358A3
,08-29 08:44:00.735  5760  5780 D bt_hwcfg: Target name = [BCM4358A3]
08-29 08:44:00.735  5760  5780 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 08:44:01.125  5760  5780 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 08:44:01.125  5760  5780 D bt_hwcfg: Settlement delay -- 100 ms
08-29 08:44:01.125  5760  5780 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 08:44:01.259  5760  5780 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 08:44:01.260  5760  5780 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
08-29 08:44:01.261  5760  5780 I bt_hwcfg: vendor lib fwcfg completed
08-29 08:44:01.261  5760  5780 I bt_vendor: firmware callback
08-29 08:44:01.261  5760  5780 I bt_hci  : firmware_config_callback
08-29 08:44:01.269  5760  5783 I bt_btu  : btu_task pending for preload complete event
08-29 08:44:01.269  5760  5783 I bt_btu_task: Bluetooth chip preload is complete
,08-29 08:44:01.269  5760  5783 I bt_btu  : btu_task received preload complete event
,08-29 08:44:01.275  5760  5783 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 08:44:01.276  5760  5783 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 08:44:01.276  5760  5783 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 08:44:01.276  5760  5783 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 08:44:01.276  5760  5783 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 08:44:01.276  5760  5783 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 08:44:01.276  5760  5783 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 08:44:01.276  5760  5783 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 08:44:01.277  5760  5783 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 08:44:01.277  5760  5783 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 08:44:01.277  5760  5783 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 08:44:01.277  5760  5783 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 08:44:01.277  5760  5783 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 08:44:01.277  5760  5783 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 08:44:01.277  5760  5783 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 08:44:01.358  5760  5783 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fcec99
,08-29 08:44:01.359  5760  5783 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fcec99 
,08-29 08:44:01.373  5760  5776 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 08:44:01.375  5760  5776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 08:44:01.375  5760  5776 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 08:44:01.378  5760  5776 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 08:44:01.381  5760  5776 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:44:01.382  5760  5776 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 08:44:01.382  5760  5776 D bt_hci  : do_postload posting postload work item
08-29 08:44:01.383  5760  5780 I bt_hci  : event_postload
08-29 08:44:01.383  5760  5780 I bt_vendor: sco_config_cb
08-29 08:44:01.383  5760  5780 I bt_hci  : sco_config_callback postload finished.
08-29 08:44:01.386  5760  5776 D bt_bte_conf: Device ID record 1 : primary
,08-29 08:44:01.386  5760  5776 D bt_bte_conf:   vendorId            = 000f
08-29 08:44:01.386  5760  5776 D bt_bte_conf:   vendorIdSource      = 0001
08-29 08:44:01.386  5760  5776 D bt_bte_conf:   product             = 1200
08-29 08:44:01.387  5760  5776 D bt_bte_conf:   version             = 1436
08-29 08:44:01.387  5760  5776 D bt_bte_conf:   clientExecutableURL = 
08-29 08:44:01.387  5760  5776 D bt_bte_conf:   serviceDescription  = 
08-29 08:44:01.387  5760  5776 D bt_bte_conf:   documentationURL    = 
,08-29 08:44:01.387  5760  5776 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 08:44:01.387  5760  5773 D bt_stack_manager: event_start_up_stack finished
08-29 08:44:01.387  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:01.388  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 08:44:01.388  5760  5772 D BluetoothAdapterProperties: Setting state to 15
08-29 08:44:01.388  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 08:44:01.389  5760  5772 I BluetoothAdapterState: Entering BleOnState
08-29 08:44:01.391  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:01.391  5760  5780 I bt_vendor: low_power_mode_cb
08-29 08:44:01.393  5760  5772 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 08:44:01.393  5760  5772 D BluetoothAdapterProperties: Setting state to 11
08-29 08:44:01.394  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 08:44:01.394  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:01.401  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
,08-29 08:44:01.404  5760  5760 D HeadsetService: Received start request. Starting profile...
08-29 08:44:01.406  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:01.408  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:01.408  5760  5760 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 08:44:01.408  5760  5760 D HeadsetStateMachine: make
08-29 08:44:01.412  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:01.418  5760  5772 I BluetoothAdapterState: Entering PendingCommandState
,08-29 08:44:01.420  5760  5760 D HeadsetStateMachine: max_hf_connections = 1
08-29 08:44:01.420  5760  5760 I bt_bluedroid: get_profile_interface handsfree
08-29 08:44:01.420  5760  5776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 08:44:01.420  5760  5776 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 08:44:01.423  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
,08-29 08:44:01.423  5760  5760 D A2dpService: Received start request. Starting profile...
08-29 08:44:01.424  5760  5760 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 08:44:01.424  5760  5760 I bt_bluedroid: get_profile_interface avrcp
,08-29 08:44:01.429  5760  5760 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 08:44:01.429  5760  5760 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 08:44:01.429  5760  5760 D A2dpStateMachine: make
,08-29 08:44:01.430  5760  5760 I bt_bluedroid: get_profile_interface a2dp
,08-29 08:44:01.431  5760  5776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 08:44:01.432  5760  5791 D A2dpStateMachine: Enter Disconnected: -2
08-29 08:44:01.433  5760  5760 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 08:44:01.433  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
08-29 08:44:01.435  5760  5760 D HidService: Received start request. Starting profile...
,08-29 08:44:01.435  5615  5615 D BluetoothInputDevice: Proxy object connected
,08-29 08:44:01.435  5760  5760 I bt_bluedroid: get_profile_interface hidhost
08-29 08:44:01.435  5760  5776 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fb02d9
08-29 08:44:01.435  5760  5760 D HidService: setHidService(): set to: null
08-29 08:44:01.435  5760  5776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 08:44:01.436  5760  5760 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 08:44:01.436  5615  5615 D HidProfile: Bluetooth service connected
08-29 08:44:01.436  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
08-29 08:44:01.437  5760  5760 D HealthService: Received start request. Starting profile...
,08-29 08:44:01.438  5760  5760 I bt_bluedroid: get_profile_interface health
,08-29 08:44:01.441  5760  5760 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 08:44:01.442  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
08-29 08:44:01.442  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 08:44:01.443  5615  5615 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 08:44:01.444  5615  5615 D PanProfile: Bluetooth service connected
,08-29 08:44:01.444  5760  5760 D PanService: Received start request. Starting profile...
08-29 08:44:01.444  5760  5760 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 08:44:01.444  5760  5760 I bt_bluedroid: get_profile_interface pan
08-29 08:44:01.445  5760  5776 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 08:44:01.447  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
08-29 08:44:01.448  5615  5615 D BluetoothMap: Proxy object connected
08-29 08:44:01.448  5760  5760 D BluetoothMapService: Received start request. Starting profile...
08-29 08:44:01.448  5760  5760 D BluetoothMapService: start()
08-29 08:44:01.448  5615  5615 D MapProfile: Bluetooth service connected
,08-29 08:44:01.448  5615  5615 D BluetoothMap: getConnectedDevices()
08-29 08:44:01.449  5615  5615 D BluetoothMap: Bluetooth is Not enabled
08-29 08:44:01.450  5760  5760 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 08:44:01.451  5760  5760 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 08:44:01.451  5760  5760 D BluetoothMapAppObserver: createReceiver()
08-29 08:44:01.453  5760  5760 D BluetoothMapAppObserver: initObservers()
08-29 08:44:01.453  5760  5760 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 08:44:01.460  5760  5760 V SapService: SapBinder()
,08-29 08:44:01.460  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
,08-29 08:44:01.461  5760  5760 D SapService: Received start request. Starting profile...
,08-29 08:44:01.461  5760  5760 V SapService: start()
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isTurningOff()=false
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isTurningOn()=true
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:01.463  5760  5789 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isTurningOff()=false
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isTurningOn()=true
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isTurningOff()=false
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isTurningOn()=true
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isTurningOff()=false
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isTurningOn()=true
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:01.463  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:44:01.464  5760  5760 V BluetoothAdapterState: isTurningOff()=false
08-29 08:44:01.464  5760  5760 V BluetoothAdapterState: isTurningOn()=true
08-29 08:44:01.464  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:01.464  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:01.464  5760  5760 V BluetoothAdapterState: isTurningOff()=false
08-29 08:44:01.464  5760  5760 V BluetoothAdapterState: isTurningOn()=true
08-29 08:44:01.464  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:01.464  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:01.465  5760  5760 V BluetoothAdapterState: isTurningOff()=false
08-29 08:44:01.465  5760  5760 V BluetoothAdapterState: isTurningOn()=true
08-29 08:44:01.465  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:01.465  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:44:01.466  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-29 08:44:01.466  5760  5772 D BluetoothAdapterProperties: ScanMode =  20
08-29 08:44:01.466  5760  5772 D BluetoothAdapterProperties: State =  11
08-29 08:44:01.468  5760  5776 D BluetoothAdapterProperties: Scan Mode:21
08-29 08:44:01.468  5760  5772 D BluetoothAdapterProperties: Setting state to 12
08-29 08:44:01.468  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 08:44:01.469  5760  5776 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 08:44:01.469  5760  5772 I BluetoothAdapterState: Entering OnState
08-29 08:44:01.470  3160  3171 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 08:44:01.471  5615  5627 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 08:44:01.472  3544  3560 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:44:01.472  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:44:01.472  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:01.472  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:01.472  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:44:01.472  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:01.472  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:44:01.472  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:44:01.472  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:44:01.472   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:44:01.472  3160  3716 D BluetoothPan: onBluetoothStateChange on: true
08-29 08:44:01.474  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:44:01.474  3160  3160 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 08:44:01.474  3160  3171 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:44:01.474  3160  3160 D PanProfile: Bluetooth service connected
08-29 08:44:01.474  5615  5628 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 08:44:01.475   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:44:01.476  3160  3716 D BluetoothMap: onBluetoothStateChange: up=true
08-29 08:44:01.476  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:44:01.476  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:01.476  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:01.476  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:44:01.476  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:01.476  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:44:01.476  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:44:01.476  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:44:01.477  3160  3160 D BluetoothMap: Proxy object connected
08-29 08:44:01.477   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:44:01.477  3160  3160 D MapProfile: Bluetooth service connected
08-29 08:44:01.477  3160  3160 D BluetoothMap: getConnectedDevices()
08-29 08:44:01.478   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:44:01.478  5760  5760 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 08:44:01.478  5615  5627 D BluetoothMap: onBluetoothStateChange: up=true
08-29 08:44:01.478  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:44:01.478  3160  3171 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 08:44:01.479  5760  5760 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-29 08:44:01.481  5615  5628 D BluetoothPan: onBluetoothStateChange on: true
,08-29 08:44:01.481  3160  3160 D BluetoothInputDevice: Proxy object connected
08-29 08:44:01.481  3160  3160 D HidProfile: Bluetooth service connected
08-29 08:44:01.483  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:44:01.483  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:01.483  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:01.483  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:44:01.483  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:01.483  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:44:01.483  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:44:01.483  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:44:01.484  3160  3168 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:44:01.484  5760  5760 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:44:01.486  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:44:01.488   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 08:44:01.489  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:01.490  5760  5760 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:44:01.490  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:01.491  5760  5760 D ObexServerSockets: Succeed to create listening sockets 
08-29 08:44:01.491  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:01.491  5760  5760 D ObexServerSockets0: startAccept()
08-29 08:44:01.491  5615  5615 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 08:44:01.491  5760  5760 D ObexServerSockets0: prepareForNewConnect()
,08-29 08:44:01.493  5760  5760 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-29 08:44:01.493  5760  5760 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 08:44:01.494  5760  5798 D ObexServerSockets0: Accepting socket connection...
08-29 08:44:01.494  5760  5799 D ObexServerSockets0: Accepting socket connection...
08-29 08:44:01.495   928   928 D BluetoothA2dp: Proxy object connected
08-29 08:44:01.495  3160  3160 D BluetoothA2dp: Proxy object connected
,08-29 08:44:01.495  5760  5760 D BluetoothMapService: onReceive
,08-29 08:44:01.495  5760  5760 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:44:01.495  5760  5760 D BluetoothMapService: STATE_ON
,08-29 08:44:01.497  5615  5615 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 08:44:01.500  5760  5800 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:44:01.502  5760  5800 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 08:44:01.502  5760  5800 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 08:44:01.506  5615  5615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 08:44:01.508  5615  5615 D BluetoothA2dp: Proxy object connected
,08-29 08:44:01.511  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:44:01.513  5615  5615 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:44:01.518  5615  5615 D BluetoothPbap: Proxy object connected
,08-29 08:44:01.518  5615  5615 D PbapServerProfile: Bluetooth service connected
08-29 08:44:01.520  3160  3160 D BluetoothPbap: Proxy object connected
08-29 08:44:01.520  3160  3160 D PbapServerProfile: Bluetooth service connected
,08-29 08:44:01.523  5760  5760 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 08:44:01.523  5760  5760 D ObexServerSockets0: prepareForNewConnect()
08-29 08:44:01.525  5760  5804 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:44:01.538  5760  5808 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:44:01.540  5760  5808 I BtOppRfcommListener: Accept thread started.
,08-29 08:44:01.573  3160  3171 D BluetoothHeadset: Proxy object connected
,08-29 08:44:01.573  3160  3160 D HeadsetProfile: Bluetooth service connected
08-29 08:44:01.573   928   928 D BluetoothHeadset: Proxy object connected
08-29 08:44:01.573   928   928 D BluetoothHeadset: Proxy object connected
08-29 08:44:01.573   928   928 D BluetoothHeadset: Proxy object connected
08-29 08:44:01.574  3160  3716 D BluetoothHeadset: Proxy object connected
08-29 08:44:01.574  3544  3563 D BluetoothHeadset: Proxy object connected
,08-29 08:44:01.575  3160  3160 D HeadsetProfile: Bluetooth service connected
,08-29 08:44:01.576   928   945 D BluetoothHeadset: Proxy object connected
,08-29 08:44:01.578   928   945 D BluetoothHeadset: Proxy object connected
,08-29 08:44:01.603  5615  5628 D BluetoothHeadset: Proxy object connected
,08-29 08:44:01.604  5615  5615 D HeadsetProfile: Bluetooth service connected
,08-29 08:44:03.419   928  3006 D ConnectivityService: handlePromptUnvalidated 101
,08-29 08:44:05.444  5760  5772 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 08:44:05.444  5760  5772 D BluetoothAdapterProperties: Setting state to 13
08-29 08:44:05.445  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 08:44:05.446  5760  5772 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 08:44:05.448  5760  5772 I BluetoothAdapterState: Entering PendingCommandState
,08-29 08:44:05.455  5760  5760 D BluetoothMapService: onReceive
,08-29 08:44:05.455  5760  5760 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:44:05.456  5760  5760 D BluetoothMapService: STATE_TURNING_OFF
08-29 08:44:05.456  5760  5760 D BluetoothMapService: MAP Service closeService in
08-29 08:44:05.456  5760  5760 D BluetoothMapMasInstance0: MAP Service shutdown
,08-29 08:44:05.457  5760  5760 D ObexServerSockets0: shutdown(block = true)
08-29 08:44:05.458  5760  5798 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 08:44:05.458  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:44:05.459  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:44:05.459  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:05.459  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:05.459  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:44:05.459  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:44:05.459  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:44:05.459  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:44:05.459  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:44:05.461  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:44:05.461  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:44:05.461  5760  5760 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 08:44:05.462  5760  5760 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 08:44:05.462  5760  5785 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 08:44:05.462  5760  5799 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-29 08:44:05.463  5760  5760 I BtOppRfcommListener: stopping Accept Thread
08-29 08:44:05.463  5760  5808 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 08:44:05.464  5760  5808 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 08:44:05.464  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:44:05.464  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:44:05.464  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:05.464  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:05.464  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:44:05.464  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:44:05.464  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:44:05.464  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:44:05.464  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:44:05.465  5760  5776 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:44:05.465  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 08:44:05.466  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:44:05.466  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:44:05.468  5760  5760 D HeadsetService: Received stop request...Stopping profile...
08-29 08:44:05.470  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:44:05.470  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:44:05.470  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:05.470  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:05.470  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:44:05.470  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:44:05.470  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:44:05.470  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:44:05.470  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:44:05.470  3160  3171 D BluetoothHeadset: Proxy object disconnected
08-29 08:44:05.470   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 08:44:05.470   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 08:44:05.470   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 08:44:05.471  3544  3770 D BluetoothHeadset: Proxy object disconnected
,08-29 08:44:05.471  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:44:05.471  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:44:05.472  5615  5627 D BluetoothHeadset: Proxy object disconnected
08-29 08:44:05.473  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:05.473  5760  5760 D A2dpService: Received stop request...Stopping profile...
08-29 08:44:05.475  5615  5615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 08:44:05.475  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:05.476   928   928 D BluetoothA2dp: Proxy object disconnected
08-29 08:44:05.477  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:05.477  3160  3160 D HeadsetProfile: Bluetooth service disconnected
08-29 08:44:05.477  5615  5615 D HeadsetProfile: Bluetooth service disconnected
08-29 08:44:05.478  3160  3160 D BluetoothA2dp: Proxy object disconnected
08-29 08:44:05.478  5760  5760 V BluetoothAdapterState: isTurningOff()=true
08-29 08:44:05.478  5760  5760 V BluetoothAdapterState: isTurningOn()=false
08-29 08:44:05.478  5760  5791 D A2dpStateMachine: Exit Disconnected: -1
08-29 08:44:05.478  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 08:44:05.478  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:05.478  5615  5615 D BluetoothA2dp: Proxy object disconnected
08-29 08:44:05.478  5760  5760 D HidService: Received stop request...Stopping profile...
08-29 08:44:05.478  5760  5760 D HidService: Stopping Bluetooth HidService
08-29 08:44:05.479  3160  3160 D BluetoothInputDevice: Proxy object disconnected
08-29 08:44:05.479  3160  3160 D HidProfile: Bluetooth service disconnected
08-29 08:44:05.481  5760  5760 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 08:44:05.481  5760  5760 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 08:44:05.482  5760  5783 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:44:05.482  5760  5783 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:44:05.482  5760  5783 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 08:44:05.482  5760  5776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 08:44:05.482  5760  5776 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 08:44:05.482  5760  5760 D HealthService: Received stop request...Stopping profile...
,08-29 08:44:05.484  5760  5760 D PanService: Received stop request...Stopping profile...
08-29 08:44:05.485  3160  3160 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 08:44:05.485  3160  3160 D PanProfile: Bluetooth service disconnected
,08-29 08:44:05.486  5760  5760 D BluetoothMapService: Received stop request...Stopping profile...
08-29 08:44:05.486  5760  5760 D BluetoothMapService: stop()
08-29 08:44:05.486  5760  5760 D BluetoothMapAppObserver: deinitObservers()
08-29 08:44:05.487  5760  5760 D BluetoothMapAppObserver: removeReceiver()
08-29 08:44:05.488  3160  3160 D BluetoothMap: Proxy object disconnected
08-29 08:44:05.488  3160  3160 D MapProfile: Bluetooth service disconnected
08-29 08:44:05.489  5760  5760 D SapService: Received stop request...Stopping profile...
08-29 08:44:05.489  5760  5760 V SapService: stop()
08-29 08:44:05.490  5760  5760 V BluetoothAdapterState: isTurningOff()=true
08-29 08:44:05.491  5760  5760 V BluetoothAdapterState: isTurningOn()=false
08-29 08:44:05.491  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:05.491  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:05.491  5760  5783 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:44:05.491  5760  5783 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:44:05.491  5760  5760 V BluetoothAdapterState: isTurningOff()=true
08-29 08:44:05.492  5760  5760 V BluetoothAdapterState: isTurningOn()=false
08-29 08:44:05.492  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:05.492  5760  5776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 08:44:05.492  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:44:05.492  5760  5783 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:44:05.492  5760  5783 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:44:05.492  5760  5783 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:44:05.492  5760  5783 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:44:05.493  5760  5760 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 08:44:05.493  5760  5760 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 08:44:05.493  5615  5615 D DockEventReceiver: finishStartingService: stopping service
08-29 08:44:05.493  5760  5760 V BluetoothAdapterState: isTurningOff()=true
08-29 08:44:05.493  5760  5760 V BluetoothAdapterState: isTurningOn()=false
08-29 08:44:05.493  5760  5776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 08:44:05.493  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:05.493  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:05.493  5760  5760 V BluetoothAdapterState: isTurningOff()=true
08-29 08:44:05.493  5760  5760 V BluetoothAdapterState: isTurningOn()=false
08-29 08:44:05.494  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:05.494  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:05.494  5760  5760 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-29 08:44:05.494  5760  5776 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 08:44:05.494  5760  5760 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 08:44:05.494  5615  5615 D BluetoothInputDevice: Proxy object disconnected
08-29 08:44:05.494  5615  5615 D HidProfile: Bluetooth service disconnected
08-29 08:44:05.494  5615  5615 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 08:44:05.494  5760  5760 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 08:44:05.494  5615  5615 D PanProfile: Bluetooth service disconnected
08-29 08:44:05.494  5760  5760 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 08:44:05.494  5615  5615 D BluetoothMap: Proxy object disconnected
08-29 08:44:05.494  5615  5615 D MapProfile: Bluetooth service disconnected
08-29 08:44:05.496  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:44:05.497  5760  5760 D BluetoothMapService: MAP Service closeService in
08-29 08:44:05.497  5760  5760 V BluetoothAdapterState: isTurningOff()=true
08-29 08:44:05.497  5760  5760 V BluetoothAdapterState: isTurningOn()=false
08-29 08:44:05.497  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:05.497  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:05.497  5760  5760 D BluetoothMapService: cleanup()
08-29 08:44:05.497  5760  5760 D BluetoothMapService: MAP Service closeService in
08-29 08:44:05.498  5760  5760 V BluetoothAdapterState: isTurningOff()=true
08-29 08:44:05.498  5760  5760 V BluetoothAdapterState: isTurningOn()=false
08-29 08:44:05.498  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:05.498  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:05.498  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 08:44:05.498  5760  5772 D BluetoothAdapterProperties: Setting state to 15
08-29 08:44:05.498  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-29 08:44:05.498  5760  5772 I BluetoothAdapterState: Entering BleOnState
,08-29 08:44:05.501  3160  3160 D BluetoothPbap: Proxy object disconnected
08-29 08:44:05.501  3160  3160 D PbapServerProfile: Bluetooth service disconnected
,08-29 08:44:05.501  5615  5627 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 08:44:05.503  3160  3168 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 08:44:05.503  5615  5628 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 08:44:05.505  3544  3560 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:44:05.505   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:44:05.505  3160  3171 D BluetoothPan: onBluetoothStateChange on: false
08-29 08:44:05.506  3160  3716 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:44:05.506  5615  5627 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 08:44:05.506   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:44:05.506  3160  3168 D BluetoothMap: onBluetoothStateChange: up=false
08-29 08:44:05.507   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 08:44:05.507  5615  5628 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 08:44:05.507   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 08:44:05.507  5615  5627 D BluetoothMap: onBluetoothStateChange: up=false
08-29 08:44:05.508  3160  3171 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 08:44:05.509  5615  5628 D BluetoothPan: onBluetoothStateChange on: false
08-29 08:44:05.510  3160  3716 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 08:44:05.510  5760  5772 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 08:44:05.510  5760  5772 D BluetoothAdapterProperties: Setting state to 16
08-29 08:44:05.510  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 08:44:05.511  5760  5772 D BluetoothAdapterProperties: onBleDisable
08-29 08:44:05.511  5760  5772 I BluetoothAdapterState: Entering PendingCommandState
08-29 08:44:05.511  5760  5773 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-29 08:44:05.504  5615  5615 D BluetoothPbap: Proxy object disconnected
08-29 08:44:05.512  5615  5615 D PbapServerProfile: Bluetooth service disconnected
08-29 08:44:05.513  5760  5783 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 08:44:05.513  5760  5783 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:44:05.513  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:05.515  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:05.516  5615  5615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 08:44:05.516  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:05.516  5760  5776 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:44:05.519  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:05.520  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:05.521  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:44:05.523  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:05.523  5615  5615 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:44:05.724  5760  5776 I bt_hci  : shut_down
,08-29 08:44:05.730  5760  5780 D bt_hwcfg: hw_epilog_process
08-29 08:44:05.730  5760  5780 I bt_vendor: low_power_mode_cb
,08-29 08:44:05.732  5760  5780 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 08:44:05.733  5760  5780 I bt_vendor: epilog_cb
08-29 08:44:05.733  5760  5780 I bt_hci  : epilog_finished_callback
,08-29 08:44:05.734  5760  5776 I bt_hci_h4: hal_close
08-29 08:44:05.735  5760  5776 I bt_userial_vendor: device fd = 51 close
,08-29 08:44:05.846  5760  5773 D bt_stack_manager: event_shut_down_stack finished.
,08-29 08:44:05.846  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 08:44:05.849  5760  5772 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 08:44:05.849  5760  5760 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 08:44:05.850  5760  5760 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 08:44:05.850  5760  5760 D BtGatt.GattService: stop()
08-29 08:44:05.850  5760  5760 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 08:44:05.853  5760  5760 V BluetoothAdapterState: isTurningOff()=false
,08-29 08:44:05.853  5760  5760 V BluetoothAdapterState: isTurningOn()=false
08-29 08:44:05.853  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:05.853  5760  5760 V BluetoothAdapterState: isBleTurningOff()=true
08-29 08:44:05.854  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 08:44:05.854  5760  5772 D BluetoothAdapterProperties: Setting state to 10
08-29 08:44:05.854  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 08:44:05.855  5760  5772 I BluetoothAdapterState: Entering OffState
08-29 08:44:05.856   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 08:44:05.874  5760  5760 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 08:44:05.874  5760  5760 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 08:44:05.875  5760  5773 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 08:44:05.877  5760  5773 D bt_stack_manager: event_clean_up_stack finished.
08-29 08:44:05.877  5760  5760 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 08:44:05.880  5760  5760 I art     : System.exit called, status: 0
08-29 08:44:05.880  5760  5760 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 08:44:05.917   928  3604 I ActivityManager: Process com.android.bluetooth (pid 5760) has died
,08-29 08:44:08.757   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:09.758   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:10.443  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:44:10.444  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:44:10.447  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:44:10.448  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11fe320 removed from the list
,08-29 08:44:10.448  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:44:10.448  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:44:10.448  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:10.452  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:44:10.452  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d17e9e added. We now have 4 listener(s)
,08-29 08:44:10.452  5559  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:44:10.454  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:44:10.455  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d17e9e removed from the list
08-29 08:44:10.455  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:44:10.455  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:44:10.455  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:10.456  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:44:10.457  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fb3d7f added. We now have 4 listener(s)
08-29 08:44:10.457  5559  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:44:10.759   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:11.760   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:12.762   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:13.762   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 08:44:15.465  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:15.493   928   945 I ActivityManager: Start proc 5817:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 08:44:15.561  5817  5817 D AdapterServiceConfig: Adding HeadsetService
,08-29 08:44:15.561  5817  5817 D AdapterServiceConfig: Adding A2dpService
08-29 08:44:15.561  5817  5817 D AdapterServiceConfig: Adding HidService
08-29 08:44:15.561  5817  5817 D AdapterServiceConfig: Adding HealthService
08-29 08:44:15.561  5817  5817 D AdapterServiceConfig: Adding PanService
08-29 08:44:15.562  5817  5817 D AdapterServiceConfig: Adding GattService
08-29 08:44:15.562  5817  5817 D AdapterServiceConfig: Adding BluetoothMapService
08-29 08:44:15.562  5817  5817 D AdapterServiceConfig: Adding SapService
08-29 08:44:15.571   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@83d58ac:true
,08-29 08:44:15.571  5817  5817 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 08:44:15.574  5817  5817 I bt_bluedroid: init
,08-29 08:44:15.575  5817  5829 I BluetoothAdapterState: Entering OffState
,08-29 08:44:15.577  5817  5830 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 08:44:15.577  5817  5830 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 08:44:15.578  5817  5830 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 08:44:15.578  5817  5830 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 08:44:15.578  5817  5817 I bt_bluedroid: get_profile_interface socket
,08-29 08:44:15.581  5817  5833 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-29 08:44:15.581  5817  5817 I bt_bluedroid: get_profile_interface sdp
08-29 08:44:15.582  5817  5833 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 08:44:15.584  5817  5828 I bt_bluedroid: config_hci_snoop_log
08-29 08:44:15.585   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 08:44:15.589  5817  5829 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 08:44:15.589  5817  5829 D BluetoothAdapterProperties: Setting state to 14
08-29 08:44:15.590  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 08:44:15.591  5817  5829 D BluetoothBondStateMachine: make
,08-29 08:44:15.593  5817  5834 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 08:44:15.595  5817  5829 I BluetoothAdapterState: Entering PendingCommandState
,08-29 08:44:15.596  5817  5817 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 08:44:15.599  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
08-29 08:44:15.599  5817  5817 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 08:44:15.600  5817  5817 D BtGatt.GattService: Received start request. Starting profile...
08-29 08:44:15.600  5817  5817 D BtGatt.GattService: start()
08-29 08:44:15.600  5817  5817 I bt_bluedroid: get_profile_interface gatt
,08-29 08:44:15.601  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
08-29 08:44:15.601  5817  5817 D BtGatt.AdvertiseManager: advertise manager created
,08-29 08:44:15.607  5817  5817 V BluetoothAdapterState: isTurningOff()=false
,08-29 08:44:15.607  5817  5817 V BluetoothAdapterState: isTurningOn()=false
08-29 08:44:15.607  5817  5817 V BluetoothAdapterState: isBleTurningOn()=true
08-29 08:44:15.607  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:15.607  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 08:44:15.607  5817  5829 I bt_bluedroid: enable
08-29 08:44:15.608  5817  5830 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 08:44:15.608  5817  5830 I bt_hci  : start_up
,08-29 08:44:15.612  5817  5830 I bt_vendor: alloc value 0xf405104d
08-29 08:44:15.613  5817  5830 I bt_vendor: init
08-29 08:44:15.613  5817  5830 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 08:44:15.613  5817  5830 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 08:44:15.734  5817  5830 D bt_hci  : start_up starting async portion
,08-29 08:44:15.735  5817  5837 I bt_hci  : event_finish_startup
08-29 08:44:15.735  5817  5837 I bt_hci_h4: hal_open
08-29 08:44:15.735  5817  5837 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 08:44:15.728  5838  5838 W irq/448-msm_hs_: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 08:44:15.739  5817  5837 I bt_userial_vendor: device fd = 51 open
,08-29 08:44:15.755  5817  5837 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 08:44:15.758  5817  5837 D bt_hwcfg: Chipset BCM4358A3
,08-29 08:44:15.758  5817  5837 D bt_hwcfg: Target name = [BCM4358A3]
08-29 08:44:15.759  5817  5837 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 08:44:16.258  5817  5837 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 08:44:16.258  5817  5837 D bt_hwcfg: Settlement delay -- 100 ms
08-29 08:44:16.258  5817  5837 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 08:44:16.392  5817  5837 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 08:44:16.393  5817  5837 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 08:44:16.395  5817  5837 I bt_hwcfg: vendor lib fwcfg completed
,08-29 08:44:16.395  5817  5837 I bt_vendor: firmware callback
,08-29 08:44:16.395  5817  5837 I bt_hci  : firmware_config_callback
,08-29 08:44:16.404  5817  5840 I bt_btu  : btu_task pending for preload complete event
,08-29 08:44:16.404  5817  5840 I bt_btu_task: Bluetooth chip preload is complete
,08-29 08:44:16.404  5817  5840 I bt_btu  : btu_task received preload complete event
,08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_GAP
,08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 08:44:16.411  5817  5840 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 08:44:16.502  5817  5840 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fcec99
,08-29 08:44:16.503  5817  5840 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fcec99 
,08-29 08:44:16.522  5817  5833 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 08:44:16.524  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 08:44:16.525  5817  5833 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 08:44:16.527  5817  5833 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 08:44:16.530  5817  5833 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:44:16.530  5817  5833 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 08:44:16.530  5817  5833 D bt_hci  : do_postload posting postload work item
,08-29 08:44:16.530  5817  5837 I bt_hci  : event_postload
,08-29 08:44:16.531  5817  5837 I bt_vendor: sco_config_cb
,08-29 08:44:16.531  5817  5837 I bt_hci  : sco_config_callback postload finished.
08-29 08:44:16.533  5817  5833 D bt_bte_conf: Device ID record 1 : primary
08-29 08:44:16.533  5817  5833 D bt_bte_conf:   vendorId            = 000f
,08-29 08:44:16.533  5817  5833 D bt_bte_conf:   vendorIdSource      = 0001
08-29 08:44:16.533  5817  5833 D bt_bte_conf:   product             = 1200
08-29 08:44:16.533  5817  5833 D bt_bte_conf:   version             = 1436
08-29 08:44:16.533  5817  5833 D bt_bte_conf:   clientExecutableURL = 
08-29 08:44:16.533  5817  5833 D bt_bte_conf:   serviceDescription  = 
08-29 08:44:16.534  5817  5833 D bt_bte_conf:   documentationURL    = 
08-29 08:44:16.534  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:16.534  5817  5833 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 08:44:16.534  5817  5830 D bt_stack_manager: event_start_up_stack finished
08-29 08:44:16.536  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 08:44:16.536  5817  5829 D BluetoothAdapterProperties: Setting state to 15
08-29 08:44:16.536  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 08:44:16.536  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:16.540  5817  5829 I BluetoothAdapterState: Entering BleOnState
,08-29 08:44:16.544  5817  5837 I bt_vendor: low_power_mode_cb
08-29 08:44:16.545  5817  5829 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 08:44:16.545  5817  5829 D BluetoothAdapterProperties: Setting state to 11
08-29 08:44:16.545  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 08:44:16.554  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:16.555  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
08-29 08:44:16.555  5817  5817 D HeadsetService: Received start request. Starting profile...
08-29 08:44:16.558  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:16.558  5817  5817 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 08:44:16.559  5817  5817 D HeadsetStateMachine: make
,08-29 08:44:16.571  5817  5829 I BluetoothAdapterState: Entering PendingCommandState
,08-29 08:44:16.571  5817  5817 D HeadsetStateMachine: max_hf_connections = 1
08-29 08:44:16.572  5817  5817 I bt_bluedroid: get_profile_interface handsfree
08-29 08:44:16.572  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 08:44:16.573  5817  5833 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 08:44:16.576  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
,08-29 08:44:16.577  5817  5817 D A2dpService: Received start request. Starting profile...
08-29 08:44:16.578  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 08:44:16.578  5817  5817 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 08:44:16.578  5817  5817 I bt_bluedroid: get_profile_interface avrcp
,08-29 08:44:16.584  5817  5817 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 08:44:16.584  5817  5817 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-29 08:44:16.584  5817  5817 D A2dpStateMachine: make
,08-29 08:44:16.586  5817  5817 I bt_bluedroid: get_profile_interface a2dp
08-29 08:44:16.586  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 08:44:16.588  5817  5848 D A2dpStateMachine: Enter Disconnected: -2
,08-29 08:44:16.589  5817  5817 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 08:44:16.590  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
,08-29 08:44:16.590  5817  5817 D HidService: Received start request. Starting profile...
08-29 08:44:16.591  5817  5817 I bt_bluedroid: get_profile_interface hidhost
08-29 08:44:16.591  5817  5817 D HidService: setHidService(): set to: null
08-29 08:44:16.591  5817  5833 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fb02d9
08-29 08:44:16.591  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 08:44:16.591  5817  5817 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 08:44:16.592  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
08-29 08:44:16.592  5817  5817 D HealthService: Received start request. Starting profile...
,08-29 08:44:16.594  5817  5817 I bt_bluedroid: get_profile_interface health
,08-29 08:44:16.595  5817  5817 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 08:44:16.596  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
,08-29 08:44:16.596  5817  5817 D PanService: Received start request. Starting profile...
08-29 08:44:16.597  5817  5817 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 08:44:16.597  5817  5817 I bt_bluedroid: get_profile_interface pan
,08-29 08:44:16.598  5817  5833 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 08:44:16.600  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
,08-29 08:44:16.600  5817  5817 D BluetoothMapService: Received start request. Starting profile...
08-29 08:44:16.600  5817  5817 D BluetoothMapService: start()
,08-29 08:44:16.603  5817  5817 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 08:44:16.604  5817  5817 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 08:44:16.604  5817  5817 D BluetoothMapAppObserver: createReceiver()
,08-29 08:44:16.605  5817  5817 D BluetoothMapAppObserver: initObservers()
,08-29 08:44:16.605  5817  5817 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 08:44:16.613  5817  5817 V SapService: SapBinder()
08-29 08:44:16.613  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
08-29 08:44:16.613  5817  5817 D SapService: Received start request. Starting profile...
08-29 08:44:16.613  5817  5817 V SapService: start()
,08-29 08:44:16.615  5817  5817 V BluetoothAdapterState: isTurningOff()=false
08-29 08:44:16.615  5817  5817 V BluetoothAdapterState: isTurningOn()=true
08-29 08:44:16.615  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:16.615  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:16.615  5817  5846 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 08:44:16.615  5817  5817 V BluetoothAdapterState: isTurningOff()=false
08-29 08:44:16.615  5817  5817 V BluetoothAdapterState: isTurningOn()=true
08-29 08:44:16.615  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:16.615  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:16.615  5817  5817 V BluetoothAdapterState: isTurningOff()=false
08-29 08:44:16.615  5817  5817 V BluetoothAdapterState: isTurningOn()=true
08-29 08:44:16.615  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:16.615  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:16.616  5817  5817 V BluetoothAdapterState: isTurningOff()=false
08-29 08:44:16.616  5817  5817 V BluetoothAdapterState: isTurningOn()=true
08-29 08:44:16.616  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:16.616  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:16.616  5817  5817 V BluetoothAdapterState: isTurningOff()=false
08-29 08:44:16.616  5817  5817 V BluetoothAdapterState: isTurningOn()=true
08-29 08:44:16.616  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:16.616  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:16.616  5817  5817 V BluetoothAdapterState: isTurningOff()=false
08-29 08:44:16.616  5817  5817 V BluetoothAdapterState: isTurningOn()=true
08-29 08:44:16.616  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:16.616  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:44:16.617  5817  5817 V BluetoothAdapterState: isTurningOff()=false
08-29 08:44:16.617  5817  5817 V BluetoothAdapterState: isTurningOn()=true
08-29 08:44:16.617  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:44:16.617  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:44:16.617  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 08:44:16.617  5817  5829 D BluetoothAdapterProperties: ScanMode =  20
08-29 08:44:16.617  5817  5829 D BluetoothAdapterProperties: State =  11
08-29 08:44:16.618  5817  5833 D BluetoothAdapterProperties: Scan Mode:21
08-29 08:44:16.619  5817  5833 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 08:44:16.619  5817  5829 D BluetoothAdapterProperties: Setting state to 12
08-29 08:44:16.619  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 08:44:16.619  5817  5829 I BluetoothAdapterState: Entering OnState
08-29 08:44:16.620  5615  5627 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 08:44:16.622  3160  3716 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 08:44:16.623  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:44:16.623  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:16.623  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:16.623  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:44:16.623  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:16.623  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:44:16.623  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:44:16.623  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:44:16.623  5615  5628 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 08:44:16.625  3544  3563 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:44:16.625  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:44:16.625   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 08:44:16.626  3160  3168 D BluetoothPan: onBluetoothStateChange on: true
08-29 08:44:16.628  3160  3171 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:44:16.628  3160  3160 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 08:44:16.628  3160  3160 D PanProfile: Bluetooth service connected
08-29 08:44:16.628  5615  5812 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 08:44:16.628  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:44:16.628  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:16.628  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:16.628  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:44:16.628  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:16.628  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:44:16.628  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:44:16.628  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:44:16.630   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:44:16.630  3160  3171 D BluetoothMap: onBluetoothStateChange: up=true
08-29 08:44:16.630  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:44:16.632   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:44:16.632   928   928 D BluetoothA2dp: Proxy object connected
08-29 08:44:16.632  5615  5628 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:44:16.632  5817  5817 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 08:44:16.633  5615  5615 D BluetoothA2dp: Proxy object connected
08-29 08:44:16.633  5817  5817 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 08:44:16.633   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 08:44:16.633  5615  5627 D BluetoothMap: onBluetoothStateChange: up=true
08-29 08:44:16.634  5817  5817 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:44:16.635  3160  3716 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 08:44:16.636  5817  5817 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:44:16.636  5615  5615 D BluetoothInputDevice: Proxy object connected
08-29 08:44:16.636  5615  5615 D HidProfile: Bluetooth service connected
08-29 08:44:16.637  3160  3160 D BluetoothInputDevice: Proxy object connected
08-29 08:44:16.637  3160  3160 D HidProfile: Bluetooth service connected
08-29 08:44:16.637  5817  5817 D ObexServerSockets: Succeed to create listening sockets 
,08-29 08:44:16.637  5817  5817 D ObexServerSockets0: startAccept()
08-29 08:44:16.638  5817  5817 D ObexServerSockets0: prepareForNewConnect()
08-29 08:44:16.638  5615  5812 D BluetoothPan: onBluetoothStateChange on: true
08-29 08:44:16.640  5817  5817 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 08:44:16.640  5817  5817 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-29 08:44:16.641  3160  3171 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 08:44:16.642  5817  5854 D ObexServerSockets0: Accepting socket connection...
08-29 08:44:16.643  5817  5855 D ObexServerSockets0: Accepting socket connection...
08-29 08:44:16.643  3160  3160 D BluetoothA2dp: Proxy object connected
08-29 08:44:16.644  5615  5615 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 08:44:16.644  5615  5615 D PanProfile: Bluetooth service connected
08-29 08:44:16.644   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 08:44:16.647  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:16.648  5817  5817 D BluetoothMapService: onReceive
08-29 08:44:16.648  3160  3160 D BluetoothMap: Proxy object connected
08-29 08:44:16.648  5817  5817 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:44:16.648  3160  3160 D MapProfile: Bluetooth service connected
08-29 08:44:16.648  3160  3160 D BluetoothMap: getConnectedDevices()
08-29 08:44:16.648  5817  5817 D BluetoothMapService: STATE_ON
08-29 08:44:16.650  5817  5856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:44:16.649  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:16.651  5817  5856 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 08:44:16.658  5817  5856 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 08:44:16.660  5615  5615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 08:44:16.662  5615  5615 D BluetoothMap: Proxy object connected
08-29 08:44:16.662  5615  5615 D MapProfile: Bluetooth service connected
08-29 08:44:16.662  5615  5615 D BluetoothMap: getConnectedDevices()
,08-29 08:44:16.666  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 08:44:16.667  5615  5615 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:44:16.672  5817  5817 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 08:44:16.672  5817  5817 D ObexServerSockets0: prepareForNewConnect()
,08-29 08:44:16.675  5615  5615 D BluetoothPbap: Proxy object connected
08-29 08:44:16.675  5615  5615 D PbapServerProfile: Bluetooth service connected
,08-29 08:44:16.678  3160  3160 D BluetoothPbap: Proxy object connected
08-29 08:44:16.678  3160  3160 D PbapServerProfile: Bluetooth service connected
,08-29 08:44:16.679  5817  5860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:44:16.696  5817  5864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:44:16.697  5817  5864 I BtOppRfcommListener: Accept thread started.
,08-29 08:44:16.727  3160  3171 D BluetoothHeadset: Proxy object connected
,08-29 08:44:16.727   928   928 D BluetoothHeadset: Proxy object connected
,08-29 08:44:16.727   928   928 D BluetoothHeadset: Proxy object connected
08-29 08:44:16.727   928   928 D BluetoothHeadset: Proxy object connected
,08-29 08:44:16.727  3160  3160 D HeadsetProfile: Bluetooth service connected
,08-29 08:44:16.727  3544  3770 D BluetoothHeadset: Proxy object connected
08-29 08:44:16.728  5615  5628 D BluetoothHeadset: Proxy object connected
08-29 08:44:16.728  3160  3716 D BluetoothHeadset: Proxy object connected
08-29 08:44:16.729  5615  5615 D HeadsetProfile: Bluetooth service connected
08-29 08:44:16.729  3160  3160 D HeadsetProfile: Bluetooth service connected
08-29 08:44:16.730   928   945 D BluetoothHeadset: Proxy object connected
,08-29 08:44:16.733  5615  5812 D BluetoothHeadset: Proxy object connected
,08-29 08:44:16.733   928   945 D BluetoothHeadset: Proxy object connected
08-29 08:44:16.734  5615  5615 D HeadsetProfile: Bluetooth service connected
,08-29 08:44:20.479  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:44:20.479  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:20.479  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:20.479  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:44:20.479  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:20.479  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:44:20.479  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:44:20.479  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:44:20.484  5559  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:44:20.485  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:44:20.485  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fb3d7f removed from the list
08-29 08:44:20.485  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:44:20.485  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:44:20.485  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:44:20.486  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:44:20.487  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@df0114c added. We now have 4 listener(s)
08-29 08:44:20.487  5559  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:44:20.490   928  3428 D WifiService: setWifiEnabled: false pid=5559, uid=10077
,08-29 08:44:20.490   928  3428 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:44:25.500  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:25.501   928  3569 D WifiService: setWifiEnabled: true pid=5559, uid=10077
,08-29 08:44:25.502   928  3569 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:44:25.512   506   926 D SoftapController: Softap fwReload - Ok
,08-29 08:44:25.517   506   926 D CommandListener: Setting iface cfg
,08-29 08:44:25.517   506   926 D CommandListener: Trying to bring down wlan0
08-29 08:44:25.519   506   926 D CommandListener: Clearing all IP addresses on wlan0
,08-29 08:44:25.524   928  2993 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 08:44:26.190   928  2993 D wifi    : set interface wlan0 flags (UP)
,08-29 08:44:26.191   928  2993 I WifiHAL : Initializing wifi
08-29 08:44:26.191   928  2993 I WifiHAL : Creating socket
08-29 08:44:26.197   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 08:44:26.198   928  2993 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-29 08:44:26.199   928  2993 D wifi    : Did set static halHandle = 0x7f785a18a0
08-29 08:44:26.199   928  2993 D wifi    : halHandle = 0x7f785a18a0, mVM = 0x7f9450d140, mCls = 0x1017d2
08-29 08:44:26.199   928  2993 D wifi    : array field set
08-29 08:44:26.200   928  2993 I WifiNative-HAL: interface[0] = wlan0
08-29 08:44:26.203   928  5869 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547480017056
08-29 08:44:26.203   928  5869 D wifi    : waitForHalEvents called, vm = 0x7f9450d140, obj = 0x1017d2, env = 0x7f78f45b40
,08-29 08:44:26.254  5870  5870 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 08:44:26.274  5870  5870 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 08:44:26.296  5870  5870 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 08:44:26.296  5870  5870 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 08:44:26.304   928  2993 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 08:44:26.312  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:26.317  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:26.321   928  2993 D WifiConfigStore: Loading config and enabling all networks 
,08-29 08:44:26.326  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:44:26.326  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:26.326  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:26.326  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:44:26.326  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:26.326  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:44:26.326  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:44:26.326  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:44:26.327   928  2993 D WifiConfigStore: loaded 0 passpoint configs
08-29 08:44:26.327   928  2993 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 08:44:26.328   928  2993 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 08:44:26.328  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:44:26.328   928  2993 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 08:44:26.329   928  2993 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 08:44:26.329   928  2993 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 08:44:26.331  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:44:26.331  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:26.331  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:26.331  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:44:26.331  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:26.331  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:44:26.331  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:44:26.331  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:44:26.333   928  2993 D WifiNative-HAL: Setting external_sim to 1
08-29 08:44:26.333  4227  4227 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 08:44:26.333  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:44:26.333   928  2993 D wifi    : setting dfs flag to true, 0x7f780ac3e0
08-29 08:44:26.334   928  2993 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 08:44:26.334   928  2993 D wifi    : setting scan oui 0x7f780ac3e0
08-29 08:44:26.334   928  2993 D WifiHAL : Sending mac address OUI
,08-29 08:44:26.352   928  2993 E native  : do suspend true
,08-29 08:44:26.359   928  2993 D wifi    : android_net_wifi_setLinkLayerStats: 1
,08-29 08:44:26.359   928   928 D RttService: SCAN_AVAILABLE : 3
08-29 08:44:26.359   928  3082 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 08:44:26.365   506   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 08:44:26.366   506   926 D CommandListener: Setting iface cfg
,08-29 08:44:26.367   928  2992 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '96 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 96 Failed to set address (No such device)'
08-29 08:44:26.367   928  2992 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 08:44:26.373   928  2992 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 08:44:26.373   928  2992 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
08-29 08:44:26.379   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=389809 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=7 mControllerEnergyUsed=26 }
,08-29 08:44:28.763   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:29.594  5870  5870 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 08:44:29.625   928  2993 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-29 08:44:29.640   928  2993 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,08-29 08:44:29.640   928  2993 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 08:44:29.653   928  2993 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-29 08:44:29.701   928  2993 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-29 08:44:29.764   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:30.038  5870  5870 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 08:44:30.087  5870  5870 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 08:44:30.088  5870  5870 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 08:44:30.107   928  2993 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 08:44:30.109   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 08:44:30.108   928  2993 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 08:44:30.128   928  2993 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 08:44:30.140   506   926 D CommandListener: Setting iface cfg
,08-29 08:44:30.145   928  2993 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 08:44:30.152   928  2993 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 08:44:30.161   928  5875 D DhcpClient: Receive thread started
,08-29 08:44:30.244   928  2993 E native  : do suspend false
,08-29 08:44:30.259   928  5874 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 08:44:30.280   928  5875 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-29 08:44:30.281   928  5874 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-29 08:44:30.283   928  5874 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,08-29 08:44:30.296   928  5875 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 08:44:30.296   928  5874 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 08:44:30.299   506   926 D CommandListener: Setting iface cfg
,08-29 08:44:30.308   928  5874 D DhcpClient: Scheduling renewal in 86399s
,08-29 08:44:30.309   928  2993 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[],
,08-29 08:44:30.313   928  2993 E native  : do suspend true
,08-29 08:44:30.329   928  2993 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 08:44:30.331   928  2993 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 08:44:30.333   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 08:44:30.337   928  3006 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 08:44:30.338   928  2993 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 08:44:30.376   928  3006 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 08:44:30.376   928  3006 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-29 08:44:30.378   928  3006 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 08:44:30.380   928  3006 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 08:44:30.382   928  3006 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 08:44:30.390   928  3006 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 08:44:30.394   928  3006 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 08:44:30.394   928  3006 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-29 08:44:30.394   928  3006 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 08:44:30.394   928  3006 D ConnectivityService:    accepting network in place of null
,08-29 08:44:30.394   928  2993 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 08:44:30.395   928  2993 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 08:44:30.395   928  3006 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 08:44:30.402   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=393832, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:44:30.418   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:44:30.442   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:44:30.445   928  3006 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 08:44:30.445   928  3006 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:44:30.445  3510  3669 W QCNEJ   : |CORE| network available: 102
,08-29 08:44:30.446   928  3006 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-29 08:44:30.449   928   945 D Tethering: MasterInitialState.processMessage what=3
08-29 08:44:30.451  3510  3669 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,08-29 08:44:30.452  3510  3669 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
08-29 08:44:30.453  3510  3669 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
08-29 08:44:30.454  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:44:30.454  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:30.454  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:30.454  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:44:30.454  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:30.454  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:44:30.454  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:44:30.454  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:44:30.456  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:44:30.461  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:44:30.461  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:30.461  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:30.461  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:44:30.461  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:30.461  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:44:30.461  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:44:30.461  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:44:30.463  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:44:30.465  4819  4855 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 08:44:30.466  4819  4855 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 08:44:30.466  4819  4855 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
08-29 08:44:30.466  4819  4855 E SarControlService: no key has been found,reset the power
08-29 08:44:30.466  4819  4869 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,08-29 08:44:30.466  4819  4869 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 08:44:30.466  4819  4869 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 08:44:30.466  4858  4858 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 08:44:30.467  4858  4858 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 08:44:30.468  4819  4869 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 08:44:30.468  4819  4869 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 08:44:30.468  4819  4869 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 08:44:30.468  4858  4858 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 08:44:30.468  4858  4858 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 08:44:30.469  4858  4875 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d764c1d HexData = [00000000ec03000000000000ffffffff]
08-29 08:44:30.470  4858  4875 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 08:44:30.470  4858  4875 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
08-29 08:44:30.470  3891  3891 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 08:44:30.474  4858  4858 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 08:44:30.475  4819  4830 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 08:44:30.475  3891  3891 D SystemUpdateService: onCreate
08-29 08:44:30.478   928  5872 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:810::200e
08-29 08:44:30.478  3891  3891 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-29 08:44:30.480  4858  4875 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d764c1d HexData = [00000000ed03000000000000ffffffff]
08-29 08:44:30.480  4858  4875 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,08-29 08:44:30.480  4858  4875 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
08-29 08:44:30.481  4858  4858 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 08:44:30.481  4819  4829 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-29 08:44:30.491  3891  3891 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 08:44:30.496  3891  5286 I iu.UploadsManager: num queued entries: 0
,08-29 08:44:30.497  3891  5286 I iu.UploadsManager: num updated entries: 0
08-29 08:44:30.497  3891  5286 I iu.SyncManager: NEXT; no task
,08-29 08:44:30.500  3891  5890 I SystemUpdateService: active receiver: enabled
,08-29 08:44:30.501  3891  3891 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 08:44:30.503  3891  3891 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 08:44:30.504  5681  5681 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-29 08:44:30.508  5681  5681 D SprintDMHelper: simOperator: 
08-29 08:44:30.508  5681  5681 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 08:44:30.514  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:44:30.514  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:30.514  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:30.514  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:44:30.514  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:30.514  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:44:30.514  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:44:30.514  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:44:30.516  5559  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:44:30.516  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:44:30.516  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@df0114c removed from the list
08-29 08:44:30.516  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:44:30.517  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:44:30.517  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:30.519  5559  5898 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-29 08:44:30.519  5559  5898 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 08:44:30.548  3891  5890 I SystemUpdateService: showing system update notification
,08-29 08:44:30.558  3891  5890 V SystemUpdateService: retry (wakeup: false) in 3599945 ms
,08-29 08:44:30.561  3891  3891 D SystemUpdateService: onDestroy
,08-29 08:44:30.569   928  5872 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 12:44:30 GMT], X-Android-Received-Millis=[1472474670568], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472474670530]}
,08-29 08:44:30.569   928  3006 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 08:44:30.569   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-29 08:44:30.569   928  3006 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 08:44:30.570   928  3006 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 08:44:30.647   506   926 D TetherController: Setting IP forward enable = 1
,08-29 08:44:30.686  4227  5899 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 08:44:30.765   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:31.766   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:32.767   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:33.530  5559  5898 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-29 08:44:33.530  5559  5934 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-29 08:44:33.531  5559  5934 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-29 08:44:33.531  5559  5898 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-29 08:44:33.532  5559  5934 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 08:44:33.533  5559  5898 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 08:44:33.534  5559  5934 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 08:44:33.534  5559  5898 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 08:44:33.538  5559  5937 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: IncomingSocketThread/Sender)
,08-29 08:44:33.538  5559  5898 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-29 08:44:33.538  5559  5934 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-29 08:44:33.540  5559  5936 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: OutgoingSocketThread/Sender)
,08-29 08:44:33.544  5559  5938 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: OutgoingSocketThread/Receiver)
,08-29 08:44:33.544  5559  5939 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: IncomingSocketThread/Receiver)
08-29 08:44:33.545  5559  5938 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: OutgoingSocketThread/Receiver)
08-29 08:44:33.545  5559  5938 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-29 08:44:33.545  5559  5938 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-29 08:44:33.545  5559  5939 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: IncomingSocketThread/Receiver)
08-29 08:44:33.545  5559  5939 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-29 08:44:33.546  5559  5939 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-29 08:44:33.767   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 08:44:36.526  5559  5606 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 08:44:36.528  5559  5606 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 08:44:36.533  5559  5606 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@60c3f78 Bundle[{}]
08-29 08:44:36.535  5559  5606 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 08:44:36.535  5559  5606 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 08:44:36.536  5559  5606 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 08:44:36.537  5559  5606 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 08:44:36.538  5559  5606 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 08:44:36.540  5559  5606 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 08:44:36.546  5559  5606 I System.out: Running OutgoingSocketThread
,08-29 08:44:36.548  5559  5940 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-29 08:44:36.548  5559  5940 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 08:44:38.402   928  3006 D ConnectivityService: handlePromptUnvalidated 102
,08-29 08:44:39.558  5559  5940 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-29 08:44:39.559  5559  5940 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-29 08:44:39.559  5559  5940 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 08:44:39.560  5559  5941 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-29 08:44:39.560  5559  5941 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-29 08:44:39.560  5559  5940 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 08:44:39.560  5559  5941 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 08:44:39.562  5559  5941 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 08:44:39.566  5559  5943 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Sender)
,08-29 08:44:39.567  5559  5940 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-29 08:44:39.567  5559  5945 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: OutgoingSocketThread/Receiver)
,08-29 08:44:39.568  5559  5944 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Sender)
08-29 08:44:39.569  5559  5945 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: OutgoingSocketThread/Receiver)
,08-29 08:44:39.569  5559  5945 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-29 08:44:39.570  5559  5945 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-29 08:44:39.571  5559  5941 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-29 08:44:39.575  5559  5946 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: IncomingSocketThread/Receiver)
,08-29 08:44:39.578  5559  5946 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: IncomingSocketThread/Receiver)
,08-29 08:44:39.578  5559  5946 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-29 08:44:39.578  5559  5946 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-29 08:44:42.557  5559  5606 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,08-29 08:44:42.558  5559  5606 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 08:44:42.558  5559  5606 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 178)
,08-29 08:44:42.563  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:44:42.563  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@144b595 added. We now have 3 listener(s)
,08-29 08:44:42.566  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 08:44:42.566  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:44:42.566  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:44:42.566  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:44:42.566  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd2e6aa added. We now have 4 listener(s)
08-29 08:44:42.566  5559  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:44:42.567  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:44:42.571  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:44:42.576  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:44:42.576  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:42.576  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:42.576  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:44:42.576  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:42.576  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:44:42.576  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:44:42.576  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:44:42.578  5559  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:44:42.578  5559  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:44:42.579  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:44:42.579  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:44:42.579  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:44:42.580  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:44:42.580  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:42.580  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:44:42.580  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:44:42.580  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@144b595 removed from the list
08-29 08:44:42.580  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:44:42.580  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd2e6aa removed from the list
,08-29 08:44:42.582  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:42.582  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:44:42.583  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:44:42.583  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:42.583  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:42.584  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:44:42.584  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:44:42.585  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:44:42.585  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd2e6aa not in the list
08-29 08:44:42.585  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:44:42.585  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:42.586  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:44:42.586  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:44:42.586  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:44:42.586  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd2e6aa not in the list
,08-29 08:44:42.586  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:44:42.586  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:42.586  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:42.586  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@144b595 not in the list
08-29 08:44:42.586  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:42.587  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:44:42.587  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb2f638 added. We now have 3 listener(s)
,08-29 08:44:42.589  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 08:44:42.589  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:44:42.589  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:44:42.589  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:44:42.589  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9881611 added. We now have 4 listener(s)
08-29 08:44:42.589  5559  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:44:42.590  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:44:42.592  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:44:42.597  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:44:42.597  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:42.597  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:42.597  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:44:42.597  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:42.597  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:44:42.597  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:44:42.597  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:44:42.598  5559  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:44:42.598  5559  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:44:42.598  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:44:42.599  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:44:42.599  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:44:42.599  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:44:42.599  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:44:42.602  5559  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 08:44:42.602  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 08:44:42.603  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:42.605  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 08:44:42.605  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:42.606  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 08:44:42.606  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 08:44:42.608  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 08:44:42.608  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 08:44:42.609  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 08:44:42.609  5559  5606 D BluetoothAdapter: STATE_ON
,08-29 08:44:42.612  5817  5827 D BtGatt.GattService: registerClient() - UUID=51a626be-89a9-48cd-a992-2a74cd50afdd
,08-29 08:44:42.613  5817  5833 D BtGatt.GattService: onClientRegistered() - UUID=51a626be-89a9-48cd-a992-2a74cd50afdd, clientIf=5
,08-29 08:44:42.613  5559  5569 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 08:44:42.614  5817  5845 D BtGatt.GattService: start scan with filters
08-29 08:44:42.617  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 08:44:42.617  5817  5836 D BtGatt.ScanManager: handling starting scan
08-29 08:44:42.617  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 08:44:42.618  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:44:42.618  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:44:42.620  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:44:42.620  5817  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dab468c
08-29 08:44:42.620  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 08:44:42.620  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:44:42.621  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 08:44:42.624  5559  5606 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 08:44:42.624  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 08:44:42.624  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 08:44:42.624  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:42.624  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 08:44:42.624  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:44:42.624  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:44:42.624  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:44:42.624  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:44:42.624  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:44:42.624  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 08:44:42.625  5559  5606 D BluetoothAdapter: STATE_ON
08-29 08:44:42.626  5817  5845 D BtGatt.GattService: stopScan() - queue size =1
08-29 08:44:42.627  5817  5853 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:44:42.627  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:44:42.627  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:44:42.627  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 08:44:42.627  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 08:44:42.627  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 08:44:42.627  5817  5833 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 08:44:42.627  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:44:42.628  5817  5836 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 08:44:42.628  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:44:42.628  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:44:42.628  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:44:42.628  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:44:42.629  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 08:44:42.630  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 08:44:42.631  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:44:42.631  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 08:44:42.634  5817  5833 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 08:44:42.634  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:44:42.635  5817  5836 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:44:42.635  5817  5836 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 08:44:42.645  5817  5833 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 08:44:42.645  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:44:42.650  5817  5833 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 08:44:42.650  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:44:42.657  5817  5833 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 08:44:42.657  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:44:42.657  5817  5836 D BtGatt.ScanManager: stopping BLe Batch
,08-29 08:44:42.662  5817  5833 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 08:44:42.662  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:44:42.663  5817  5836 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 08:44:42.668  5817  5833 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 08:44:42.668  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:44:43.132  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 08:44:43.132  5559  5559 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:44:43.133  5559  5559 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 08:44:45.631  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:44:45.631  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:44:45.631  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:44:45.632  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:44:45.632  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:45.632  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 08:44:45.632  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 08:44:45.633  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb2f638 removed from the list
08-29 08:44:45.633  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:44:45.633  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9881611 removed from the list
08-29 08:44:45.633  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:44:45.633  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:45.635  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:45.635  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:44:45.638  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:44:45.638  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:44:45.638  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:44:45.638  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9881611 not in the list
08-29 08:44:45.639  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:45.639  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:44:45.642  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:44:45.642  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:44:45.642  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:44:45.642  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9881611 not in the list,
08-29 08:44:45.642  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:44:45.643  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:45.643  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:45.643  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb2f638 not in the list
08-29 08:44:45.644  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:44:45.645  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fda102 added. We now have 3 listener(s)
08-29 08:44:45.649  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:44:45.649  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:44:45.649  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:44:45.650  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:44:45.650  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@985a13 added. We now have 4 listener(s)
08-29 08:44:45.650  5559  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:44:45.651  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:44:45.654  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:44:45.659  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:44:45.659  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:45.659  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:45.659  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:44:45.659  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:45.659  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:44:45.659  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:44:45.659  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:44:45.661  5559  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:44:45.661  5559  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:44:45.662  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 08:44:45.662  5559  5606 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-29 08:44:45.663  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-29 08:44:45.663  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 08:44:45.663  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 08:44:45.663  5559  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 08:44:45.663  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:44:45.664  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 08:44:45.665  5559  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 08:44:45.665  5559  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 08:44:45.665  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 08:44:45.665  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-29 08:44:45.665  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:44:45.665  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 08:44:45.667  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:45.669  5559  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 08:44:45.669  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 08:44:45.672  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:45.672  5559  5947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:44:45.672  5559  5559 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-29 08:44:45.674  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 08:44:45.674  5559  5947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-29 08:44:45.675  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 08:44:45.676  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 08:44:45.677  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-29 08:44:45.678  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:44:45.678  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
08-29 08:44:45.679  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 08:44:45.679  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 08:44:45.679  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-29 08:44:45.680  5559  5606 D BluetoothAdapter: STATE_ON
,08-29 08:44:45.685  5817  5827 D BtGatt.GattService: registerClient() - UUID=049239d8-7045-420c-9890-fc5fe525aaf7
08-29 08:44:45.685  5817  5833 D BtGatt.GattService: onClientRegistered() - UUID=049239d8-7045-420c-9890-fc5fe525aaf7, clientIf=5
,08-29 08:44:45.685  5559  5569 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-29 08:44:45.687  5817  5835 D BtGatt.AdvertiseManager: message : 0
,08-29 08:44:45.690  5817  5835 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 08:44:45.700  5817  5833 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-29 08:44:45.706  5817  5833 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-29 08:44:45.707  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-29 08:44:45.708  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 08:44:45.709  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 08:44:45.711  5559  5559 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 08:44:45.711  5559  5559 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-29 08:44:45.711  5559  5559 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-29 08:44:45.711  5559  5559 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-29 08:44:45.711  5559  5559 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-29 08:44:45.711  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-29 08:44:45.713  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 08:44:45.714  5559  5559 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-29 08:44:45.714  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 08:44:46.215  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-29 08:44:46.216  5559  5559 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 08:44:46.216  5559  5559 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 08:44:48.715  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:44:48.715  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-29 08:44:48.715  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 08:44:48.715  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 08:44:48.716  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 08:44:48.716  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 08:44:48.716  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-29 08:44:48.716  5559  5947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 08:44:48.717  5559  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 08:44:48.717  5559  5947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 08:44:48.717  5559  5947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 08:44:48.717  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:44:48.717  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:44:48.717  5559  5559 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 08:44:48.717  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:44:48.717  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 08:44:48.717  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:44:48.720  5559  5606 D BluetoothAdapter: STATE_ON
08-29 08:44:48.720  5559  5606 D BluetoothLeScanner: could not find callback wrapper
08-29 08:44:48.720  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:44:48.720  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-29 08:44:48.722  5817  5835 D BtGatt.AdvertiseManager: message : 1
08-29 08:44:48.723  5817  5835 D BtGatt.AdvertiseManager: stop advertise for client 5
08-29 08:44:48.737  5817  5833 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-29 08:44:48.737  5817  5833 D BtGatt.GattService: Client app is not null!
08-29 08:44:48.738  5817  5845 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:44:48.739  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:44:48.739  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 08:44:48.740  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-29 08:44:48.740  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 08:44:48.740  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-29 08:44:48.742  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:44:48.742  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:44:48.742  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:44:48.744  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 08:44:48.746  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:44:48.746  5559  5559 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 08:44:48.746  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:48.746  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:44:48.746  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 08:44:48.746  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:44:48.746  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fda102 removed from the list
08-29 08:44:48.746  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:44:48.746  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:44:48.747  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@985a13 removed from the list
08-29 08:44:48.747  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:44:48.747  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:44:48.747  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:48.748  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:48.748  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:44:48.751  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:44:48.751  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:44:48.751  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:44:48.752  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@985a13 not in the list
08-29 08:44:48.752  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:48.752  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:48.753  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:44:48.753  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:44:48.753  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:44:48.754  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@985a13 not in the list
08-29 08:44:48.754  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:44:48.754  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:48.754  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:48.754  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fda102 not in the list
08-29 08:44:48.755  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:44:48.755  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@240657c added. We now have 3 listener(s)
,08-29 08:44:48.757  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:44:48.757  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:44:48.757  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:44:48.757  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:44:48.757  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3f2e05 added. We now have 4 listener(s)
08-29 08:44:48.757  5559  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:44:48.758  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:44:48.762  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:44:48.766  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:44:48.766  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:48.766  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:48.766  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:44:48.766  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:48.766  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:44:48.766  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:44:48.766  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:44:48.768  5559  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:44:48.768  5559  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:44:48.769  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:44:48.769  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:44:48.769  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:44:48.769  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:44:48.769  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 08:44:48.771  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:48.773  5559  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 08:44:48.773  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 08:44:48.775  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:44:48.777  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 08:44:48.778  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 08:44:48.778  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:44:48.782  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 08:44:48.782  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 08:44:48.782  5559  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 08:44:48.783  5559  5606 D BluetoothAdapter: STATE_ON
08-29 08:44:48.785  5817  5827 D BtGatt.GattService: registerClient() - UUID=5a1464c4-4a49-4b7f-8ca8-df3e112e514c
08-29 08:44:48.785  5817  5833 D BtGatt.GattService: onClientRegistered() - UUID=5a1464c4-4a49-4b7f-8ca8-df3e112e514c, clientIf=5
08-29 08:44:48.786  5559  5569 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 08:44:48.786  5817  5845 D BtGatt.GattService: start scan with filters
,08-29 08:44:48.789  5817  5836 D BtGatt.ScanManager: handling starting scan
08-29 08:44:48.789  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 08:44:48.789  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 08:44:48.789  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:44:48.789  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:44:48.793  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:44:48.793  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 08:44:48.793  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:44:48.794  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 08:44:48.796  5817  5833 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 08:44:48.797  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:44:48.797  5817  5836 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 08:44:48.802  5817  5833 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-29 08:44:48.802  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:44:48.802  5817  5836 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:44:48.803  5817  5836 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 08:44:48.812  5817  5833 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 08:44:48.812  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:44:48.817  5817  5833 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 08:44:48.817  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:44:49.248  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 08:44:49.293  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 08:44:49.293  5559  5559 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:44:49.293  5559  5559 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 08:44:51.805  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:44:51.805  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 08:44:51.805  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 08:44:51.805  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:51.806  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-29 08:44:51.806  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:44:51.806  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:44:51.806  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:44:51.806  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:44:51.806  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:44:51.807  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 08:44:51.811  5559  5606 D BluetoothAdapter: STATE_ON
,08-29 08:44:51.813  5817  5827 D BtGatt.GattService: stopScan() - queue size =1
08-29 08:44:51.815  5817  5845 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:44:51.815  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:44:51.816  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:44:51.816  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 08:44:51.816  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 08:44:51.816  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 08:44:51.818  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:44:51.818  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:44:51.818  5559  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:44:51.818  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:44:51.819  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:44:51.822  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:44:51.822  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:44:51.822  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:51.822  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:44:51.822  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:44:51.822  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:44:51.822  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:44:51.822  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@240657c removed from the list
08-29 08:44:51.822  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:44:51.822  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3f2e05 removed from the list
08-29 08:44:51.822  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:44:51.823  5817  5817 D BtGatt.ScanManager: awakened up at time 415253
08-29 08:44:51.823  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:44:51.827  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:51.828  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:51.830  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:44:51.831  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:44:51.831  5817  5833 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 08:44:51.831  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:44:51.831  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:44:51.831  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3f2e05 not in the list
08-29 08:44:51.831  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:51.831  5817  5836 D BtGatt.ScanManager: stopping BLe Batch
08-29 08:44:51.831  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:51.834  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:44:51.834  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:44:51.834  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:44:51.834  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3f2e05 not in the list
,08-29 08:44:51.834  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:44:51.834  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:51.834  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:51.834  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@240657c not in the list
08-29 08:44:51.835  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:44:51.835  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcef626 added. We now have 3 listener(s)
,08-29 08:44:51.836  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 08:44:51.837  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:44:51.837  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:44:51.837  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:44:51.837  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1829267 added. We now have 4 listener(s)
08-29 08:44:51.837  5559  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:44:51.837  5817  5833 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 08:44:51.837  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 08:44:51.837  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:44:51.838  5817  5836 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 08:44:51.840  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:44:51.845  5559  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:44:51.845  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:44:51.845  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:44:51.845  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:44:51.845  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:44:51.845  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:44:51.845  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:44:51.845  5559  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:44:51.847  5559  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:44:51.848  5559  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:44:51.848  5559  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:44:51.848  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:44:51.848  5559  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:44:51.848  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:44:51.848  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:51.848  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:44:51.848  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:44:51.848  5559  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcef626 removed from the list
,08-29 08:44:51.848  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:44:51.849  5559  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1829267 removed from the list
,08-29 08:44:51.850  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:51.854  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:44:51.854  5559  5606 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:44:51.854  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:44:51.854  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:44:51.854  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:51.855  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:44:51.855  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:44:51.855  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:44:51.855  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1829267 not in the list
08-29 08:44:51.855  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:51.855  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:51.856  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:44:51.856  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:44:51.856  5559  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:44:51.856  5559  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1829267 not in the list
08-29 08:44:51.856  5559  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:44:51.857  5559  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:44:51.857  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:44:51.857  5559  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcef626 not in the list
08-29 08:44:51.857  5817  5833 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-29 08:44:51.857  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:44:51.857  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 08:44:51.857  5817  5833 D BtGatt.GattService: current time is 415288220725
08-29 08:44:51.857  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 08:44:51.857  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 08:44:51.858  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 08:44:51.858  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 08:44:51.858  5559  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 08:44:51.858  5817  5833 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -78, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -77, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -83, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -86, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -78, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -77, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 08:44:51.859  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-29 08:44:51.859  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 08:44:51.859  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 08:44:51.860  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 08:44:51.860  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 08:44:51.860  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10,, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-29 08:44:52.323  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 08:44:53.768   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:53.869  5559  5948 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
,08-29 08:44:54.770   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:55.771   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:55.868  5559  5606 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 187
,08-29 08:44:55.868  5559  5606 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 187, name: My test thread name)
,08-29 08:44:55.874  5559  5949 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name)
08-29 08:44:55.875  5559  5949 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 188, thread name: My test thread name)
,08-29 08:44:55.875  5559  5949 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-29 08:44:55.879  5559  5606 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 08:44:55.884  5559  5950 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name)
,08-29 08:44:55.885  5559  5950 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 192, thread name: My test thread name): Test exception.
08-29 08:44:55.885  5559  5950 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-29 08:44:55.892  5559  5606 I jxcore-log: Total number of executed tests:  82
08-29 08:44:55.892  5559  5606 I jxcore-log: 
08-29 08:44:55.893  5559  5606 I jxcore-log: Number of passed tests:  82
08-29 08:44:55.893  5559  5606 I jxcore-log: 
,08-29 08:44:55.893  5559  5606 I jxcore-log: Number of failed tests:  0
08-29 08:44:55.893  5559  5606 I jxcore-log: 
08-29 08:44:55.893  5559  5606 I jxcore-log: Number of ignored tests:  0
08-29 08:44:55.893  5559  5606 I jxcore-log: 
08-29 08:44:55.894  5559  5606 I jxcore-log: Total duration:  100853
08-29 08:44:55.894  5559  5606 I jxcore-log: 
08-29 08:44:55.898  5559  5606 I jxcore-log: Unit Test app is loaded
08-29 08:44:55.898  5559  5606 I jxcore-log: 
,08-29 08:44:55.910  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.910  5559  5606 I jxcore-log: 
,08-29 08:44:55.917  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.917  5559  5606 I jxcore-log: 
,08-29 08:44:55.919  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.919  5559  5606 I jxcore-log: 
,08-29 08:44:55.920  5559  5559 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-29 08:44:55.921  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.921  5559  5606 I jxcore-log: 
,08-29 08:44:55.923  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 08:44:55.923  5559  5606 I jxcore-log: 
08-29 08:44:55.925  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:44:55.925  5559  5606 I jxcore-log: 
08-29 08:44:55.928  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.928  5559  5606 I jxcore-log: 
08-29 08:44:55.930  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.930  5559  5606 I jxcore-log: 
08-29 08:44:55.931  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 08:44:55.931  5559  5606 I jxcore-log: 
08-29 08:44:55.932  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:44:55.932  5559  5606 I jxcore-log: 
08-29 08:44:55.933  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:44:55.933  5559  5606 I jxcore-log: 
08-29 08:44:55.933  5559  5948 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
08-29 08:44:55.934  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.934  5559  5606 I jxcore-log: 
08-29 08:44:55.935  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.935  5559  5606 I jxcore-log: 
08-29 08:44:55.936  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.936  5559  5606 I jxcore-log: 
08-29 08:44:55.937  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:44:55.937  5559  5606 I jxcore-log: 
08-29 08:44:55.938  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:44:55.938  5559  5606 I jxcore-log: 
08-29 08:44:55.939  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:44:55.939  5559  5606 I jxcore-log: 
,08-29 08:44:55.941  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.941  5559  5606 I jxcore-log: 
08-29 08:44:55.942  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.942  5559  5606 I jxcore-log: 
,08-29 08:44:55.943  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.943  5559  5606 I jxcore-log: 
,08-29 08:44:55.945  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:44:55.945  5559  5606 I jxcore-log: 
,08-29 08:44:55.946  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:44:55.946  5559  5606 I jxcore-log: 
,08-29 08:44:55.947  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:44:55.947  5559  5606 I jxcore-log: 
08-29 08:44:55.948  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.948  5559  5606 I jxcore-log: 
,08-29 08:44:55.949  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.949  5559  5606 I jxcore-log: 
08-29 08:44:55.950  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.950  5559  5606 I jxcore-log: 
,08-29 08:44:55.951  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.951  5559  5606 I jxcore-log: 
08-29 08:44:55.952  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.952  5559  5606 I jxcore-log: 
,08-29 08:44:55.953  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.953  5559  5606 I jxcore-log: 
08-29 08:44:55.954  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.954  5559  5606 I jxcore-log: 
08-29 08:44:55.954  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.954  5559  5606 I jxcore-log: 
08-29 08:44:55.955  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.955  5559  5606 I jxcore-log: 
08-29 08:44:55.955  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.955  5559  5606 I jxcore-log: 
08-29 08:44:55.956  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.956  5559  5606 I jxcore-log: 
08-29 08:44:55.956  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:44:55.956  5559  5606 I jxcore-log: 
08-29 08:44:55.957  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 08:44:55.957  5559  5606 I jxcore-log: 
08-29 08:44:55.957  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 08:44:55.957  5559  5606 I jxcore-log: 
08-29 08:44:55.958  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.958  5559  5606 I jxcore-log: 
08-29 08:44:55.958  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.958  5559  5606 I jxcore-log: 
08-29 08:44:55.959  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.959  5559  5606 I jxcore-log: 
,08-29 08:44:55.961  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.961  5559  5606 I jxcore-log: 
08-29 08:44:55.962  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.962  5559  5606 I jxcore-log: 
,08-29 08:44:55.963  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:44:55.963  5559  5606 I jxcore-log: 
08-29 08:44:55.964  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.964  5559  5606 I jxcore-log: 
,08-29 08:44:55.965  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 08:44:55.965  5559  5606 I jxcore-log: 
,08-29 08:44:55.966  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.966  5559  5606 I jxcore-log: 
08-29 08:44:55.967  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:44:55.967  5559  5606 I jxcore-log: 
,08-29 08:44:55.968  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 08:44:55.968  5559  5606 I jxcore-log: 
08-29 08:44:55.969  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:44:55.969  5559  5606 I jxcore-log: 
,08-29 08:44:55.970  5559  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:44:55.970  5559  5606 I jxcore-log: 
,08-29 08:44:55.973  5559  5606 I jxcore-log: My device name is: Huawei-Nexus 6P
08-29 08:44:55.973  5559  5606 I jxcore-log: 
08-29 08:44:55.974  5559  5606 I jxcore-log: WARN testUtils: myNameCallback not set!
08-29 08:44:55.974  5559  5606 I jxcore-log: 
,08-29 08:44:56.772   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:57.758  5559  5606 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-29 08:44:57.758  5559  5606 I jxcore-log: 
,08-29 08:44:57.766  5559  5606 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-29 08:44:57.767  5559  5606 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-29 08:44:57.767  5559  5606 I jxcore-log: 
,08-29 08:44:57.773   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:44:58.774   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 08:45:23.774   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 08:45:23.775   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 08:45:43.776   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:45:44.777   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:45:45.779   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:45:46.780   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:45:47.781   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:45:48.782   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 08:45:53.783   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:45:54.785   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:45:55.786   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:45:56.787   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:45:57.788   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:45:58.789   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 08:46:08.790   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:09.791   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:10.793   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:11.794   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:12.795   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:13.795   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 08:46:28.797   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:29.798   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:30.800   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:31.801   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:32.803   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:33.803   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 08:46:53.805   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:54.806   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:55.807   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:56.808   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:57.810   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:46:58.811   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 08:47:23.812   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 08:47:23.812   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 08:47:48.822   536  1309 E QC-QMI  : qmi_client [536] 9: failed to locate client data
,08-29 08:47:48.824   518   518 E QC-QMI  : qmuxd: RX on fd=17 returned error=0 errno[2:No such file or directory]
08-29 08:47:48.826   518   518 E QC-QMI  : QMUX qmux_client_id=9 not found in qmux client list, unable to remove
,08-29 08:47:48.831   536   536 I Atfwd_Daemon: Stop the daemon....
,08-29 08:47:48.876  5961  5961 I libmdmdetect: ESOC framework not supported
,08-29 08:47:48.876  5961  5961 I libmdmdetect: Found internal modem: modem
08-29 08:47:48.868  5961  5961 W ATFWD-daemon: type=1400 audit(0.0:73): avc: denied { read write } for name="diag" dev="tmpfs" ino=13524 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,08-29 08:47:48.885  5961  5961 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,08-29 08:47:48.885  5961  5961 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,08-29 08:47:48.886  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:47:49.889  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:47:50.891  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:47:51.892  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:47:52.894  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:47:53.895  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 08:47:58.896  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:47:59.897  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:00.899  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:01.900  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:02.902  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:03.902  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 08:48:13.904  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:14.905  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:15.907  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:16.908  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:17.910  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:18.911  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 08:48:33.913  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:34.914  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:35.915  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:36.917  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:37.918  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:38.919  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 08:48:58.920  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:48:59.922  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:00.923  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:01.924  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:02.925  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:03.926  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 08:49:28.927  5961  5961 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 08:49:28.927  5961  5961 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 08:49:33.928  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:34.929  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:35.931  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:36.932  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:37.933  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:38.934  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 08:49:43.935  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:44.937  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:45.938  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:46.941  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:47.942  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:48.943  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 08:49:58.944  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:49:59.945  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:50:00.946  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:50:01.948  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:50:02.949  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:50:03.949  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 08:50:18.951  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:50:19.953  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:50:20.954  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:50:21.956  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:50:22.957  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:50:23.958  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 08:50:43.959  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:50:44.961  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:50:45.962  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:50:46.963  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:50:47.964  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:50:48.965  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 08:51:13.966  5961  5961 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 08:51:13.966  5961  5961 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 08:51:23.967  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:24.969  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:25.970  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:26.971  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:27.972  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:28.973  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 08:51:33.974  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:34.975  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:35.976  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:36.977  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:37.978  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:38.979  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 08:51:48.981  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:49.982  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:50.983  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:51.984  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:52.985  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:51:53.986  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 08:52:08.987  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:52:09.988  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:52:10.989  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:52:11.990  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:52:12.991  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:52:13.992  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 08:52:33.993  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:52:34.994  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:52:35.995  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:52:36.997  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:52:37.998  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:52:38.998  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 08:53:03.999  5961  5961 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 08:53:03.999  5961  5961 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 08:53:19.000  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:20.002  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:21.003  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:22.004  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:23.006  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:24.006  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 08:53:29.008  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:30.009  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:31.011  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:32.012  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:33.014  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:34.015  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 08:53:44.016  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:45.017  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:46.019  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:47.020  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:48.021  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:53:49.022  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 08:54:04.023  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:54:05.024  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:54:06.026  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:54:07.027  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:54:08.028  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:54:09.029  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 08:54:29.030  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:54:30.031  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:54:31.032  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:54:32.033  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:54:33.034  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:54:34.010   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=997440, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 08:54:34.035  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 08:54:43.780   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1007210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:54:59.035  5961  5961 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 08:54:59.035  5961  5961 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 08:54:59.051   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1022480, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 08:55:08.831   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1032260, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:55:19.036  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:20.038  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:21.039  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:22.041  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:23.042  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:24.043  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 08:55:24.131   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1047560, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 08:55:29.044  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:30.045  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:31.047  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:32.048  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:33.049  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:33.881   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1057310, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:55:34.050  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 08:55:44.051  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:45.052  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:46.053  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:47.054  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:48.055  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:55:49.055  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 08:55:49.171   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1072600, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 08:55:58.931   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1082361, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:56:04.057  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:56:05.058  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:56:06.059  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:56:07.061  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:56:08.062  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:56:09.063  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 08:56:14.211   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1097640, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 08:56:23.991   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1107420, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:56:29.064  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:56:30.065  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:56:31.066  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:56:32.067  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:56:33.068  5961  5961 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:56:34.069  5961  5961 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 08:56:39.291   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1122721, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 08:56:49.040   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1132470, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:56:59.070  5961  5961 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 08:56:59.071  5961  5961 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 08:57:04.331   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1147761, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 08:57:14.091   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1157520, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:57:24.081  5961  5963 E QC-QMI  : qmi_client [5961] 1d: failed to locate client data
,08-29 08:57:24.084   518   518 E QC-QMI  : qmuxd: RX on fd=17 returned error=0 errno[2:No such file or directory]
,08-29 08:57:24.084   518   518 E QC-QMI  : QMUX qmux_client_id=1d not found in qmux client list, unable to remove
,08-29 08:57:24.089  5961  5961 I Atfwd_Daemon: Stop the daemon....
,08-29 08:57:24.135  5978  5978 I libmdmdetect: ESOC framework not supported
,08-29 08:57:24.136  5978  5978 I libmdmdetect: Found internal modem: modem
08-29 08:57:24.137  5978  5978 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 08:57:24.128  5978  5978 W ATFWD-daemon: type=1400 audit(0.0:74): avc: denied { read write } for name="diag" dev="tmpfs" ino=13524 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,08-29 08:57:24.145  5978  5978 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,08-29 08:57:24.146  5978  5978 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,08-29 08:57:24.147  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:25.150  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:26.151  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:27.153  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:28.154  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:29.155  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 08:57:29.371   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1172801, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 08:57:34.156  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:35.157  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:36.159  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:37.160  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:38.161  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:39.141   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1182570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:57:39.162  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 08:57:49.163  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:50.164  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:51.166  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:52.167  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:53.168  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:57:54.169  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 08:57:54.411   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1197841, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 08:58:04.192   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1207621, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:58:09.171  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:58:10.172  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:58:11.174  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:58:12.175  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:58:13.176  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:58:14.177  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 08:58:18.664   928   940 I UsageStatsService: User[0] Flushing usage stats to disk
,08-29 08:58:19.491   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1222921, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 08:58:29.240   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1232670, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:58:34.178  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:58:35.180  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:58:36.181  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:58:37.183  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:58:38.184  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:58:39.185  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 08:58:44.531   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1247960, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 08:58:54.300   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1257730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:59:04.186  5978  5978 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 08:59:04.186  5978  5978 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 08:59:09.187  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:10.188  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:11.140   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1274570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 08:59:11.190  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:12.191  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:13.193  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:14.193  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 08:59:19.195  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:19.350   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1282780, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:59:20.196  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:21.197  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:22.199  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:23.200  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:24.201  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 08:59:30.933  3891  5983 I EventLogService: Aggregate from 1472473137479 (log), 1472473137479 (data)
,08-29 08:59:31.014   928  3432 I ActivityManager: Start proc 5985:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-29 08:59:31.050  5985  5985 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,08-29 08:59:31.067  3625  5997 I VacuumService: Vacuum at: now=1472475571067 tag=VacuumService
,08-29 08:59:31.117  5985  5998 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,08-29 08:59:31.176  5985  5998 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-29 08:59:31.223  5985  5998 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-29 08:59:31.260  6011  6011 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1233839963.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1233839963.dex
,08-29 08:59:31.263  5985  5985 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-29 08:59:31.298  6011  6011 I dex2oat : dex2oat took 39.013ms (threads: 2) arena alloc=187KB java alloc=37KB native alloc=1258KB free=1045KB
,08-29 08:59:31.393  5985  5985 W InstanceID/Rpc: Found 10012
,08-29 08:59:31.444   928  3145 I ActivityManager: Killing 5444:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-29 08:59:31.508  3625  6069 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,08-29 08:59:31.542  3625  6066 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-29 08:59:31.545  3625  6066 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 08:59:31.567  3625  6069 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 08:59:32.038  3625  6066 W Uploader:  no longer exists, so no auth token.
,08-29 08:59:32.050  3625  6071 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 08:59:32.138  3625  6069 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 08:59:32.250  3625  6071 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 08:59:32.333  3625  6066 W Uploader:  no longer exists, so no auth token.
,08-29 08:59:32.343  3625  6069 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 08:59:32.429  3625  6071 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 08:59:34.202  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:35.203  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:36.204  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:37.205  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:38.206  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:39.207  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 08:59:54.209  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:55.210  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:56.211  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:57.212  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:58.213  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 08:59:59.214  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:00:01.730   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1325160, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:00:10.411   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1333840, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:00:19.215  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:00:20.216  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:00:21.218  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:00:22.220  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:00:23.222  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:00:24.223  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:00:26.811   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1350241, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:00:35.450   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1358880, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:00:49.224  5978  5978 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:00:49.224  5978  5978 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:00:51.850   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1375280, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:00:59.225  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:00.226  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:00.531   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1383960, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:01:01.227  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:02.229  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:03.230  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:04.231  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:01:09.233  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:10.234  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:11.235  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:12.237  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:13.238  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:14.238  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:01:16.931   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1400361, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:01:24.240  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:25.241  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:25.590   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1409020, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:01:26.243  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:27.244  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:28.245  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:29.245  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:01:42.011   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1425441, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:01:44.247  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:45.248  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:46.249  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:47.250  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:48.251  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:01:49.252  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:01:50.681   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1434111, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:02:07.050   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1450480, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:02:09.253  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:02:10.254  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:02:11.255  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:02:12.256  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:02:13.257  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:02:14.258  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:02:15.720   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1459150, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:02:32.090   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1475520, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:02:39.258  5978  5978 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:02:39.258  5978  5978 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:02:40.770   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1484200, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:02:54.260  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:02:55.261  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:02:56.262  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:02:57.131   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1500561, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:02:57.263  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:02:58.264  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:02:59.265  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:03:04.266  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:05.267  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:05.821   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1509250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:03:06.269  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:07.270  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:08.272  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:09.272  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:03:19.274  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:20.275  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:21.277  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:22.251   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1525680, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:03:22.278  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:23.279  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:24.280  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:03:30.891   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1534320, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:03:39.282  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:40.283  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:41.285  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:42.286  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:43.287  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:03:44.288  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:03:47.291   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1550720, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:03:56.011   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1559441, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:04:04.290  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:04:05.292  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:04:06.293  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:04:07.294  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:04:08.296  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:04:09.296  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:04:12.410   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1575840, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:04:21.061   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1584491, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:04:30.051   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1593480, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:04:34.297  5978  5978 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:04:34.297  5978  5978 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:04:36.561   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1599990, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:04:54.299  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:04:55.091   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1618520, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:04:55.300  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:04:56.301  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:04:57.303  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:04:58.304  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:04:59.304  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:05:04.306  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:05.307  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:06.309  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:07.310  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:08.311  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:09.312  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:05:11.150   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1634580, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:05:19.313  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:20.131   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1643561, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:05:20.314  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:21.316  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:22.317  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:23.318  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:24.319  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:05:36.191   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1659621, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:05:39.320  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:40.321  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:41.322  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:42.323  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:43.324  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:05:44.325  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:05:45.170   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1668600, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:06:01.240   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1684670, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:06:04.327  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:06:05.328  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:06:06.329  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:06:07.330  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:06:08.331  5978  5978 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:06:09.331  5978  5978 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:06:10.211   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1693641, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:06:26.281   928  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1709710, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms)
```
