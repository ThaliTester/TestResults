#### Test 852025183f6a479_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-14 06:51:33.103   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-14 06:51:33.104   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 06:51:33.609  5495  5495 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-14 06:51:33.615  5495  5495 D AndroidRuntime: CheckJNI is OFF
09-14 06:51:33.643  5495  5495 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-14 06:51:33.690  5495  5495 I Radio-JNI: register_android_hardware_Radio DONE
09-14 06:51:33.706  5495  5495 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-14 06:51:33.722   926  3806 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-14 06:51:33.768   926  3806 I ActivityManager: Start proc 5505:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-14 06:51:33.773  5495  5495 D AndroidRuntime: Shutting down VM
09-14 06:51:33.870  5505  5505 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-14 06:51:33.903  5505  5505 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-14 06:51:33.927  5505  5505 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 9603-9622)
09-14 06:51:33.927  5505  5505 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-14 06:51:33.950  5505  5505 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {de33115}
09-14 06:51:33.951  5505  5505 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-14 06:51:33.951  5505  5505 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-14 06:51:33.956  5505  5505 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-14 06:51:33.958  5505  5505 E SysUtils: ApplicationContext is null in ApplicationStatus
09-14 06:51:33.994  5505  5505 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-14 06:51:34.007  5505  5505 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-14 06:51:34.008  5505  5505 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-14 06:51:34.008  5505  5505 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-14 06:51:34.008  5505  5505 I Adreno  : Build Date                       : 12/06/15
09-14 06:51:34.008  5505  5505 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-14 06:51:34.008  5505  5505 I Adreno  : Local Branch                     : mybranch17112971
09-14 06:51:34.008  5505  5505 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-14 06:51:34.008  5505  5505 I Adreno  : Remote Branch                    : NONE
09-14 06:51:34.008  5505  5505 I Adreno  : Reconstruct Branch               : NOTHING
,09-14 06:51:34.072   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6420ae4:true
,09-14 06:51:34.107   406   406 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30965]" dev="sockfs" ino=30965 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-14 06:51:34.107   406   406 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30965]" dev="sockfs" ino=30965 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-14 06:51:34.121  5505  5505 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-14 06:51:34.131  5505  5505 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-14 06:51:34.203   406   406 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[34059]" dev="sockfs" ino=34059 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-14 06:51:34.203   406   406 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[34059]" dev="sockfs" ino=34059 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-14 06:51:34.207  5505  5542 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-14 06:51:34.213  3806  3806 W Binder_A: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[30970]" dev="sockfs" ino=30970 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:51:34.213  3806  3806 W Binder_A: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[30970]" dev="sockfs" ino=30970 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:51:34.222  5505  5529 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-14 06:51:34.256  5505  5542 I OpenGLRenderer: Initialized EGL, version 1.4
,09-14 06:51:34.343   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +527ms (total +607ms)
,09-14 06:51:34.356  5505  5505 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5505
,09-14 06:51:34.451  5505  5505 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-14 06:51:34.617  5505  5543 D jxcore_app_log: JniHelper::setJavaVM(0xf54fc000), pthread_self() = -559941328
,09-14 06:51:34.623  5505  5543 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-14 06:51:34.623  5505  5543 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-14 06:51:34.623  5505  5543 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-14 06:51:34.623  5505  5543 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-14 06:51:34.623  5505  5543 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-14 06:51:34.623  5505  5543 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78c6953 added. We now have 1 listener(s)
,09-14 06:51:34.627  5505  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-14 06:51:34.628  5505  5543 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:51:34.628  5505  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:51:34.629  5505  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-14 06:51:34.635  5505  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82a938e added. We now have 1 listener(s)
09-14 06:51:34.636  5505  5543 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:51:34.640   926  2991 D WifiService: New client listening to asynchronous messages
,09-14 06:51:34.641  5505  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 06:51:34.641  5505  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-14 06:51:34.642  5505  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-14 06:51:34.642  5505  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-14 06:51:34.642  5505  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-14 06:51:34.645  5505  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:51:34.645  5505  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-14 06:51:34.653  5505  5543 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-14 06:51:34.655  5505  5543 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:51:34.655  5505  5543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:51:34.655  5505  5543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:51:34.655  5505  5543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:51:34.655  5505  5543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:51:34.655  5505  5543 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:51:34.655  5505  5543 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:51:34.655  5505  5543 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 06:51:34.655  5505  5543 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-14 06:51:34.655  5505  5543 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:51:34.656  5505  5543 I io.jxcore.node.LifeCycleMonitor: start: OK
09-14 06:51:34.657  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:51:34.661  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:51:34.682  5505  5505 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-14 06:51:34.945  5505  5551 W jxcore-log: Initializing JXcore engine
09-14 06:51:34.945  5505  5551 W jxcore-log: JXcore engine is ready
,09-14 06:51:34.970  5551  5551 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12051 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-14 06:51:34.970  5551  5551 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[17448]" dev="sockfs" ino=17448 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-14 06:51:34.970  5551  5551 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-14 06:51:34.970  5551  5551 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[34027]" dev="sockfs" ino=34027 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-14 06:51:34.978  5505  5551 W jxcore-log: Starting JXcore engine
,09-14 06:51:35.028  5505  5551 W jxcore-log: Platform android
09-14 06:51:35.028  5505  5551 W jxcore-log: 
09-14 06:51:35.028  5505  5551 W jxcore-log: Process ARCH arm
09-14 06:51:35.028  5505  5551 W jxcore-log: 
,09-14 06:51:35.126  5505  5551 I jxcore-log: JXcore Cordova bridge is ready!
09-14 06:51:35.126  5505  5551 I jxcore-log: 
,09-14 06:51:35.126  5505  5551 W jxcore-log: JXcore engine is started
,09-14 06:51:35.134  5505  5543 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-14 06:51:35.137  5505  5505 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-14 06:51:44.905  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-14 06:51:44.905  5505  5551 I jxcore-log: 
,09-14 06:51:44.907  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-14 06:51:44.907  5505  5551 I jxcore-log: 
,09-14 06:51:44.912  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:51:44.912  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:51:44.912  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:51:44.912  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:51:44.912  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:51:44.912  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:51:44.912  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:51:44.912  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 06:51:44.914  5505  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 06:51:44.916  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-14 06:51:44.916  5505  5551 I jxcore-log: 
09-14 06:51:44.917  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-14 06:51:44.917  5505  5551 I jxcore-log: 
,09-14 06:51:45.165  5505  5551 I jxcore-log: Running unit tests
09-14 06:51:45.165  5505  5551 I jxcore-log: 
,09-14 06:51:45.166  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 06:51:45.166  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc55bd3 added. We now have 2 listener(s)
09-14 06:51:45.167  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:51:45.167  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-14 06:51:45.167  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:51:45.167  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:51:45.167  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1349310 added. We now have 2 listener(s)
09-14 06:51:45.167  5505  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:51:45.168  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 06:51:45.170  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:51:45.180  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:51:45.180  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:51:45.180  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:51:45.180  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:51:45.180  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:51:45.180  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:51:45.180  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:51:45.180  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 06:51:45.186  5505  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 06:51:45.187  5505  5551 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:51:45.188  5505  5551 D executeNativeTests: Running unit tests
,09-14 06:51:45.192  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:51:45.197  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:51:45.224  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 06:51:45.224  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be added. We now have 3 listener(s)
,09-14 06:51:45.225  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-14 06:51:45.225  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:51:45.225  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:51:45.225  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:51:45.225  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f added. We now have 3 listener(s)
09-14 06:51:45.225  5505  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:51:45.226  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 06:51:45.227  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:51:45.235  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:51:45.235  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:51:45.235  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:51:45.235  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:51:45.235  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:51:45.235  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:51:45.235  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:51:45.235  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 06:51:45.239  5505  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 06:51:45.239  5505  5551 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:51:45.242  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 06:51:45.242  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 06:51:45.242  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 06:51:45.242  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-14 06:51:45.243  5505  5551 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-14 06:51:45.243  5505  5551 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-14 06:51:45.243  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 06:51:45.243  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 06:51:45.243  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 06:51:45.243  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 06:51:45.243  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 06:51:45.243  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:51:45.243  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:51:45.244  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:51:45.244  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:51:45.244  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:51:45.244  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:51:45.244  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be removed from the list
,09-14 06:51:45.245  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:51:45.245  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f removed from the list
,09-14 06:51:45.245  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:51:45.256  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:51:45.257  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:51:45.257  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:51:45.257  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:51:45.257  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:51:45.258  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:51:45.258  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:51:45.258  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:51:45.258  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:51:45.259  5505  5551 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-14 06:51:45.259  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:51:45.259  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:51:45.259  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 06:51:45.259  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:51:45.259  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:51:45.259  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:51:45.259  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:51:45.259  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:51:45.259  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
,09-14 06:51:45.259  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:51:45.259  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:51:45.259  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:51:45.259  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:51:45.259  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:51:45.260  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:51:45.260  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:51:45.260  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:51:45.260  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-14 06:51:45.263  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-14 06:51:45.264  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-14 06:51:45.264  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-14 06:51:45.264  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-14 06:51:45.264  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-14 06:51:45.264  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-14 06:51:45.264  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:51:45.264  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:51:45.264  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:51:45.264  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:51:45.264  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:51:45.264  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:51:45.264  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
,09-14 06:51:45.264  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:51:45.264  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:51:45.264  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:51:45.264  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:51:45.264  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:51:45.264  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:51:45.264  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:51:45.265  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:51:45.265  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:51:45.265  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:51:45.265  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:51:45.265  5505  5551 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-14 06:51:45.266  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:51:45.268  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:51:45.268  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:51:45.268  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:51:45.268  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:51:45.268  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:51:45.268  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:51:45.268  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:51:45.268  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 06:51:45.269  5505  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 06:51:45.269  5505  5551 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:51:45.269  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 06:51:45.269  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 06:51:45.269  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 06:51:45.269  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:51:45.269  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:51:45.274  5505  5551 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:51:45.274  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 06:51:45.274  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:51:45.277  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 06:51:45.277  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:51:45.278  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 06:51:45.278  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 06:51:45.279  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-14 06:51:45.281  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-14 06:51:45.281  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 06:51:45.281  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 06:51:45.281  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 06:51:45.281  5505  5551 D BluetoothAdapter: STATE_ON
09-14 06:51:45.283  4458  4668 D BtGatt.GattService: registerClient() - UUID=98aaa396-9198-473b-98b5-6ae51e5c15a8
09-14 06:51:45.284  4458  4535 D BtGatt.GattService: onClientRegistered() - UUID=98aaa396-9198-473b-98b5-6ae51e5c15a8, clientIf=5
09-14 06:51:45.285  5505  5515 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 06:51:45.286  4458  4699 D BtGatt.GattService: start scan with filters
09-14 06:51:45.290  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 06:51:45.290  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 06:51:45.290  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 06:51:45.290  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-14 06:51:45.292  4458  4550 D BtGatt.ScanManager: handling starting scan
09-14 06:51:45.294  4458  4550 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
09-14 06:51:45.295  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 06:51:45.295  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 06:51:45.296  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-14 06:51:45.296  5505  5505 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 06:51:45.297  5505  5551 I io.jxcore.node.ConnectionHelper: start: OK
09-14 06:51:45.302  4458  4535 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 06:51:45.302  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:51:45.302  4458  4550 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-14 06:51:45.309  4458  4535 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 06:51:45.309  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:51:45.310  4458  4550 D BtGatt.ScanManager: Starting BLE batch scan
09-14 06:51:45.310  4458  4550 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-14 06:51:45.325  4458  4535 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 06:51:45.325  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:51:45.331  4458  4535 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 06:51:45.331  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:51:45.797  5505  5505 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-14 06:51:45.798  5505  5505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 06:51:45.798  5505  5505 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 06:51:46.341   926  5212 D NetlinkSocketObserver: NeighborEvent{elapsedMs=342037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-14 06:51:48.104   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:51:49.106   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:51:50.106   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:51:50.301  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 06:51:50.301  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 06:51:50.301  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 06:51:50.302  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:51:50.302  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-14 06:51:50.302  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-14 06:51:50.302  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-14 06:51:50.302  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-14 06:51:50.302  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 06:51:50.303  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 06:51:50.303  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 06:51:50.306  5505  5551 D BluetoothAdapter: STATE_ON
09-14 06:51:50.308  4458  4668 D BtGatt.GattService: stopScan() - queue size =1
,09-14 06:51:50.312  4458  4699 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 06:51:50.312  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:51:50.313  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 06:51:50.313  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 06:51:50.313  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 06:51:50.313  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-14 06:51:50.316  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:51:50.316  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:51:50.317  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-14 06:51:50.318  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:51:50.318  4458  4458 D BtGatt.ScanManager: awakened up at time 346014
09-14 06:51:50.322  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 06:51:50.325  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 06:51:50.325  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:51:50.325  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:51:50.325  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:51:50.325  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:51:50.325  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:51:50.325  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:51:50.325  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:51:50.325  5505  5505 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:51:50.325  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:51:50.325  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:51:50.327  4458  4535 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-14 06:51:50.327  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:51:50.327  4458  4550 D BtGatt.ScanManager: stopping BLe Batch
,09-14 06:51:50.337  4458  4535 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-14 06:51:50.338  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:51:50.338  4458  4550 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 06:51:50.358  4458  4535 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-14 06:51:50.359  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:51:50.359  4458  4535 D BtGatt.GattService: current time is 346054987550
09-14 06:51:50.359  4458  4535 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -83, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -85, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -80, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -79, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -73, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -77, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-14 06:51:50.361  4458  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-14 06:51:50.362  4458  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 06:51:50.362  4458  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-14 06:51:50.362  4458  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-14 06:51:50.362  4458  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-14 06:51:50.363  4458  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-14 06:51:50.827  5505  5505 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 06:51:51.108   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:51:52.109   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:51:53.110   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 06:51:55.327  5505  5551 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-14 06:51:55.333  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:51:55.343  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:51:55.343  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:51:55.343  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:51:55.343  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:51:55.343  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:51:55.343  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:51:55.343  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:51:55.343  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 06:51:55.348  5505  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 06:51:55.349  5505  5551 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:51:55.349  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 06:51:55.349  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-14 06:51:55.349  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 06:51:55.350  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:51:55.350  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:51:55.355  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:51:55.359  5505  5551 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:51:55.359  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 06:51:55.362  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:51:55.366  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 06:51:55.368  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 06:51:55.368  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 06:51:55.374  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 06:51:55.375  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-14 06:51:55.375  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 06:51:55.376  5505  5551 D BluetoothAdapter: STATE_ON
09-14 06:51:55.379  4458  4668 D BtGatt.GattService: registerClient() - UUID=e7d07576-ba21-4f3d-8aa6-c1a1685fa024
09-14 06:51:55.380  4458  4535 D BtGatt.GattService: onClientRegistered() - UUID=e7d07576-ba21-4f3d-8aa6-c1a1685fa024, clientIf=5
09-14 06:51:55.380  5505  5515 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 06:51:55.380  4458  4699 D BtGatt.GattService: start scan with filters
,09-14 06:51:55.386  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-14 06:51:55.386  4458  4550 D BtGatt.ScanManager: handling starting scan
09-14 06:51:55.386  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 06:51:55.386  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 06:51:55.386  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-14 06:51:55.390  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 06:51:55.390  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 06:51:55.390  5505  5505 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 06:51:55.393  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-14 06:51:55.395  4458  4535 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-14 06:51:55.395  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:51:55.395  4458  4550 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 06:51:55.397  5505  5551 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 06:51:55.401  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:51:55.401  5505  5551 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-14 06:51:55.401  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 06:51:55.401  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 06:51:55.401  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:51:55.401  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-14 06:51:55.401  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 06:51:55.401  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-14 06:51:55.401  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 06:51:55.401  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 06:51:55.402  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 06:51:55.402  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 06:51:55.403  5505  5551 D BluetoothAdapter: STATE_ON
09-14 06:51:55.403  4458  4535 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 06:51:55.404  4458  4699 D BtGatt.GattService: stopScan() - queue size =1
09-14 06:51:55.404  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:51:55.404  4458  4550 D BtGatt.ScanManager: Starting BLE batch scan
09-14 06:51:55.404  4458  4550 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-14 06:51:55.404  4458  4472 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 06:51:55.405  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:51:55.405  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 06:51:55.405  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 06:51:55.405  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 06:51:55.405  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-14 06:51:55.407  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:51:55.407  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:51:55.407  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 06:51:55.407  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:51:55.408  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 06:51:55.409  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:51:55.410  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:51:55.410  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:51:55.410  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:51:55.410  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:51:55.410  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:51:55.410  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:51:55.410  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:51:55.410  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:51:55.410  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:51:55.410  5505  5505 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:51:55.412  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:51:55.412  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:51:55.413  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:51:55.414  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:51:55.414  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:51:55.415  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:51:55.416  5505  5551 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-14 06:51:55.419  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:51:55.421  4458  4535 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 06:51:55.421  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:51:55.424  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:51:55.424  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:51:55.424  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:51:55.424  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:51:55.424  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:51:55.424  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:51:55.424  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:51:55.424  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 06:51:55.427  4458  4535 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 06:51:55.427  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:51:55.428  5505  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 06:51:55.428  5505  5551 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 06:51:55.429  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 06:51:55.429  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 06:51:55.429  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 06:51:55.429  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:51:55.429  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:51:55.432  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:51:55.433  5505  5551 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:51:55.433  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 06:51:55.434  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:51:55.436  4458  4535 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-14 06:51:55.436  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:51:55.436  4458  4550 D BtGatt.ScanManager: stopping BLe Batch
,09-14 06:51:55.437  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 06:51:55.438  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 06:51:55.438  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 06:51:55.441  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 06:51:55.441  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 06:51:55.441  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 06:51:55.441  4458  4535 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 06:51:55.441  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:51:55.442  5505  5551 D BluetoothAdapter: STATE_ON
,09-14 06:51:55.442  4458  4550 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 06:51:55.445  4458  4472 D BtGatt.GattService: registerClient() - UUID=be056f89-286a-4b6a-a615-0c3f88df86bf
09-14 06:51:55.445  4458  4535 D BtGatt.GattService: onClientRegistered() - UUID=be056f89-286a-4b6a-a615-0c3f88df86bf, clientIf=5
09-14 06:51:55.446  5505  5516 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 06:51:55.446  4458  4699 D BtGatt.GattService: start scan with filters
09-14 06:51:55.447  4458  4535 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 06:51:55.447  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:51:55.448  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 06:51:55.448  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-14 06:51:55.448  4458  4550 D BtGatt.ScanManager: handling starting scan
09-14 06:51:55.449  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 06:51:55.449  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-14 06:51:55.451  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 06:51:55.452  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 06:51:55.452  5505  5505 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 06:51:55.453  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 06:51:55.455  5505  5551 I io.jxcore.node.ConnectionHelper: start: OK
09-14 06:51:55.456  4458  4535 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 06:51:55.456  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:51:55.456  4458  4550 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 06:51:55.460  4458  4535 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 06:51:55.460  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:51:55.460  4458  4550 D BtGatt.ScanManager: Starting BLE batch scan
09-14 06:51:55.461  4458  4550 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 06:51:55.469  4458  4535 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 06:51:55.469  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:51:55.474  4458  4535 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 06:51:55.474  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:51:55.953  5505  5505 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-14 06:51:55.953  5505  5505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 06:51:55.954  5505  5505 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 06:51:58.111   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:51:59.112   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:00.113   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:00.456  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 06:52:00.456  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:00.456  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 06:52:00.457  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:00.457  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-14 06:52:00.457  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 06:52:00.457  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 06:52:00.457  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 06:52:00.457  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 06:52:00.458  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 06:52:00.458  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 06:52:00.460  5505  5551 D BluetoothAdapter: STATE_ON
,09-14 06:52:00.462  4458  4699 D BtGatt.GattService: stopScan() - queue size =1
,09-14 06:52:00.464  4458  4471 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 06:52:00.465  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:52:00.465  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 06:52:00.465  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 06:52:00.465  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 06:52:00.465  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-14 06:52:00.468  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:52:00.468  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:52:00.468  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-14 06:52:00.468  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:52:00.470  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:52:00.471  4458  4458 D BtGatt.ScanManager: awakened up at time 356167
09-14 06:52:00.474  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:52:00.474  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:52:00.475  5505  5505 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 06:52:00.481  4458  4535 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-14 06:52:00.482  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:52:00.482  4458  4550 D BtGatt.ScanManager: stopping BLe Batch
,09-14 06:52:00.491  4458  4535 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-14 06:52:00.491  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:52:00.492  4458  4550 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 06:52:00.513  4458  4535 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-14 06:52:00.513  4458  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:52:00.513  4458  4535 D BtGatt.GattService: current time is 356209376076
09-14 06:52:00.514  4458  4535 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -76, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -82, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -77, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -71, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -93, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-14 06:52:00.514  4458  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 06:52:00.514  4458  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 06:52:00.515  4458  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-14 06:52:00.515  4458  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 06:52:00.515  4458  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-14 06:52:00.515  4458  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-14 06:52:00.976  5505  5505 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 06:52:00.976  5505  5505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:00.976  5505  5505 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 06:52:01.114   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:02.115   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:03.116   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 06:52:04.462   926  5212 D NetlinkSocketObserver: NeighborEvent{elapsedMs=360157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 06:52:05.475  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 06:52:05.475  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:05.475  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:52:05.476  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 06:52:05.476  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.476  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 06:52:05.476  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:05.476  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.477  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.477  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:05.477  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.478  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:52:05.479  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:05.484  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 06:52:05.484  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:52:05.484  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.484  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.486  5505  5551 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-14 06:52:05.487  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:52:05.488  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 06:52:05.488  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:52:05.488  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:05.488  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.488  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.489  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:05.489  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.489  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
,09-14 06:52:05.489  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:05.489  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.489  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.489  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.490  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.492  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:52:05.492  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:52:05.492  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.492  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.494  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-14 06:52:05.495  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:52:05.495  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:05.495  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:52:05.495  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 06:52:05.495  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.496  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.496  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:05.496  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.496  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.496  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 06:52:05.496  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.496  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.496  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.497  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:05.499  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:52:05.499  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:52:05.499  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.499  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.500  5505  5551 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-14 06:52:05.501  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:52:05.501  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 06:52:05.501  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:52:05.501  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:05.501  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.502  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.502  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:05.502  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.502  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.502  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 06:52:05.502  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.502  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.502  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.503  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:05.505  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:52:05.505  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:52:05.505  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.505  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.507  5505  5551 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-14 06:52:05.507  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:52:05.507  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:05.507  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:52:05.508  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:05.508  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.508  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.508  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:05.508  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.508  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.508  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:05.508  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.509  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.509  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.509  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.511  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 06:52:05.511  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:52:05.511  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.511  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.513  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 06:52:05.513  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 06:52:05.513  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 06:52:05.513  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 06:52:05.513  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 06:52:05.513  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 06:52:05.514  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 06:52:05.514  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-14 06:52:05.514  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 06:52:05.514  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:52:05.514  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:05.515  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:52:05.515  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:05.515  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.515  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.515  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
,09-14 06:52:05.515  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.515  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.515  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:05.516  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.516  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.516  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.516  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:05.518  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:52:05.518  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:52:05.518  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.518  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
,09-14 06:52:05.519  5505  5551 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-14 06:52:05.520  5505  5551 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-14 06:52:05.520  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-14 06:52:05.523  5505  5551 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 06:52:05.523  5505  5551 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-14 06:52:05.524  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-14 06:52:05.524  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-14 06:52:05.524  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-14 06:52:05.524  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-14 06:52:05.524  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-14 06:52:05.524  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-14 06:52:05.524  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-14 06:52:05.524  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-14 06:52:05.524  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-14 06:52:05.524  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-14 06:52:05.524  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-14 06:52:05.524  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-14 06:52:05.524  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-14 06:52:05.524  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-14 06:52:05.525  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-14 06:52:05.526  5505  5551 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-14 06:52:05.526  5505  5551 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 06:52:05.526  5505  5551 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-14 06:52:05.526  5505  5551 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 06:52:05.526  5505  5551 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 06:52:05.526  5505  5551 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-14 06:52:05.526  5505  5551 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 06:52:05.526  5505  5551 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 06:52:05.527  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-14 06:52:05.532  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-14 06:52:05.533  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-14 06:52:05.533  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-14 06:52:05.534  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-14 06:52:05.534  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-14 06:52:05.534  5505  5551 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-14 06:52:05.534  5505  5551 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 06:52:05.534  5505  5551 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-14 06:52:05.534  5505  5552 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-14 06:52:05.536  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:52:05.536  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:05.536  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:52:05.536  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:05.536  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.536  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.536  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-14 06:52:05.537  5505  5552 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:52:05.537  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:05.537  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.537  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.537  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:05.537  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.537  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:05.538  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.538  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.538  5505  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-14 06:52:05.538  5505  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-14 06:52:05.538  5505  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-14 06:52:05.538  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:52:05.538  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:52:05.539  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.539  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.539  5505  5551 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-14 06:52:05.540  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:52:05.540  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:05.540  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:52:05.540  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:05.540  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.541  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.541  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:05.541  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.541  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.541  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:05.541  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.541  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.541  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:52:05.541  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.542  5505  5552 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-14 06:52:05.543  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 06:52:05.543  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:52:05.543  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.543  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
,09-14 06:52:05.540  4472  4472 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33262]" dev="sockfs" ino=33262 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 06:52:05.540  4472  4472 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33262]" dev="sockfs" ino=33262 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 06:52:05.544  5505  5551 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-14 06:52:05.544  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:52:05.544  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:05.544  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 06:52:05.544  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:05.544  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.544  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.544  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:05.544  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:52:05.545  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.545  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:05.545  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.545  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.545  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.545  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.547  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:52:05.547  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:52:05.547  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:52:05.548  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.549  5505  5551 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-14 06:52:05.549  5505  5551 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-14 06:52:05.549  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 06:52:05.549  5505  5551 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-14 06:52:05.549  5505  5551 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-14 06:52:05.549  5505  5551 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-14 06:52:05.549  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 06:52:05.549  5505  5551 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-14 06:52:05.550  5505  5551 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-14 06:52:05.550  5505  5551 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-14 06:52:05.550  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 06:52:05.550  5505  5551 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-14 06:52:05.550  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:52:05.551  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:05.551  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 06:52:05.551  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 06:52:05.551  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.551  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.552  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:05.552  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.552  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.552  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 06:52:05.552  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.552  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.552  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.552  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.553  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:52:05.553  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:52:05.553  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.553  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.553  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:05.554  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.554  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:05.554  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
,09-14 06:52:05.554  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:05.554  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:05.554  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:05.554  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:05.554  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:10.555  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:52:10.555  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:10.555  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:10.555  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.556  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:10.556  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:10.556  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 06:52:10.556  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:10.556  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:52:10.557  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:10.557  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.557  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:10.557  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:10.557  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:10.558  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:10.558  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:10.558  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:52:10.558  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:10.558  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.558  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:10.562  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 06:52:10.562  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:52:10.562  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:10.563  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:10.566  5505  5551 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-14 06:52:10.569  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:52:10.571  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-14 06:52:10.574  5505  5551 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-14 06:52:10.575  5505  5551 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-14 06:52:10.575  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 06:52:10.575  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 06:52:10.575  5505  5505 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-14 06:52:10.576  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:10.576  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-14 06:52:10.576  5505  5555 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:52:10.576  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-14 06:52:10.577  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-14 06:52:10.577  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:10.577  5505  5551 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 06:52:10.577  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:10.577  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:52:10.577  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 06:52:10.577  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 06:52:10.577  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 06:52:10.577  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.578  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:10.577  5505  5505 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-14 06:52:10.579  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:52:10.580  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:10.580  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:52:10.580  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:52:10.580  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:52:10.580  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:10.580  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:52:10.580  5505  5505 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:52:10.580  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:10.580  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.580  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:10.581  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:10.581  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:10.581  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:10.581  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:10.581  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.581  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:10.581  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.581  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:10.580  4699  4699 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32298]" dev="sockfs" ino=32298 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-14 06:52:10.580  4699  4699 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32298]" dev="sockfs" ino=32298 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-14 06:52:10.583  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 06:52:10.583  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:52:10.583  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:10.583  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:10.583  5505  5555 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-14 06:52:10.583  5505  5555 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-14 06:52:10.584  5505  5555 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-14 06:52:10.585  5505  5505 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-14 06:52:10.585  5505  5551 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-14 06:52:10.585  5505  5551 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-14 06:52:10.585  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 06:52:10.586  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 06:52:10.586  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 06:52:10.586  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:52:10.586  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:10.586  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 06:52:10.586  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:10.586  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.586  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:10.586  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:10.587  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:10.587  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
,09-14 06:52:10.587  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:10.587  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.588  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:10.589  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.589  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:10.593  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 06:52:10.593  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:52:10.593  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:10.593  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
,09-14 06:52:10.599  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 06:52:10.599  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:10.599  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:52:10.599  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:10.599  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.599  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:10.599  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:10.599  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:10.599  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
,09-14 06:52:10.599  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:10.599  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.599  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:10.599  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.600  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:10.601  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:52:10.601  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:52:10.601  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:10.601  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
,09-14 06:52:10.602  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 06:52:10.602  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:52:10.602  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:52:10.602  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:52:10.602  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.602  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:10.602  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8890be not in the list
09-14 06:52:10.602  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:10.602  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:10.602  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:10.602  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.602  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:10.603  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:10.603  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:10.604  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 06:52:10.604  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:52:10.604  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:10.604  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b51f not in the list
09-14 06:52:10.605  5505  5551 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-14 06:52:10.605  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-14 06:52:10.606  5505  5551 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-14 06:52:10.606  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 06:52:10.606  5505  5551 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-14 06:52:10.606  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 06:52:10.608  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-14 06:52:10.608  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-14 06:52:10.608  5505  5551 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-14 06:52:10.609  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-14 06:52:10.609  5505  5551 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-14 06:52:10.609  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-14 06:52:10.609  5505  5551 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-14 06:52:10.609  5505  5551 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-14 06:52:10.610  5505  5551 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-14 06:52:10.610  5505  5551 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-14 06:52:10.610  5505  5551 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-14 06:52:10.610  5505  5551 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-14 06:52:10.611  5505  5551 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-14 06:52:10.611  5505  5551 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-14 06:52:10.612  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:52:10.612  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dcae4e9 added. We now have 3 listener(s)
09-14 06:52:10.613  5505  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:52:10.614  5505  5551 D BluetoothAdapter: enable(): BT is already enabled..!
,09-14 06:52:10.615   926  3417 D WifiService: setWifiEnabled: true pid=5505, uid=10077
09-14 06:52:10.615   926  3417 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 06:52:10.666  4458  4661 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-14 06:52:10.667  4458  4666 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-14 06:52:11.081  5505  5505 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 06:52:13.117   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:14.118   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:15.119   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:15.620  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 06:52:15.621  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@658a56e added. We now have 4 listener(s)
09-14 06:52:15.621  5505  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:52:15.633  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:52:15.634  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@658a56e removed from the list
,09-14 06:52:15.634  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:15.634  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:52:15.634  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:15.636  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:52:15.636  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@73a240f added. We now have 4 listener(s)
09-14 06:52:15.637  5505  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:52:15.640  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:52:15.640  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@73a240f removed from the list
09-14 06:52:15.640  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:15.640  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:15.640  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:15.644  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:52:15.644  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d581c9c added. We now have 4 listener(s)
,09-14 06:52:15.644  5505  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:52:15.652   926  3417 D WifiService: setWifiEnabled: false pid=5505, uid=10077
,09-14 06:52:15.652   926  3417 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 06:52:15.656   926  2990 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-14 06:52:15.656   926  2990 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-14 06:52:15.657   926  2990 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 06:52:15.657   926  2990 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 06:52:15.664  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:52:15.665  4458  4529 D BluetoothAdapterState: Current state: ON, message: 23
,09-14 06:52:15.666  4458  4529 D BluetoothAdapterProperties: Setting state to 13
09-14 06:52:15.667  4458  4529 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-14 06:52:15.670  4458  4529 D BluetoothAdapterProperties: onBluetoothDisable()
,09-14 06:52:15.672  4458  4529 I BluetoothAdapterState: Entering PendingCommandState
,09-14 06:52:15.675  4458  4535 D BluetoothAdapterProperties: Scan Mode:20
,09-14 06:52:15.676  4458  4529 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-14 06:52:15.677   926  2990 E native  : do suspend true
,09-14 06:52:15.679  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:15.679  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:52:15.679  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:15.679  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:15.679  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:15.679  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:15.679  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:52:15.679  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:52:15.679  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 06:52:15.680  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:15.680  5505  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 06:52:15.681  5505  5551 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 06:52:15.683  4458  4458 D HeadsetService: Received stop request...Stopping profile...
,09-14 06:52:15.684  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:15.685   926   926 D BluetoothHeadset: Proxy object disconnected
09-14 06:52:15.685  3523  3546 D BluetoothHeadset: Proxy object disconnected
,09-14 06:52:15.685   926   926 D BluetoothHeadset: Proxy object disconnected
,09-14 06:52:15.685  4458  4458 V BluetoothAdapterState: isTurningOff()=true
09-14 06:52:15.685  4458  4458 V BluetoothAdapterState: isTurningOn()=false
09-14 06:52:15.685  4458  4458 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 06:52:15.686  4458  4458 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:15.686  3129  3143 D BluetoothHeadset: Proxy object disconnected
09-14 06:52:15.686  3129  3129 D HeadsetProfile: Bluetooth service disconnected
09-14 06:52:15.686   926   926 D BluetoothHeadset: Proxy object disconnected
09-14 06:52:15.688  4458  4458 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-14 06:52:15.688  4458  4458 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-14 06:52:15.688  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:15.688  4458  4535 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-14 06:52:15.688  4458  4661 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-14 06:52:15.688  4458  4661 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:52:15.689  4458  4661 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:52:15.689  4458  4458 D A2dpService: Received stop request...Stopping profile...
09-14 06:52:15.689  4458  4535 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-14 06:52:15.690  4458  4671 D A2dpStateMachine: Exit Disconnected: -1
09-14 06:52:15.691   926   926 D BluetoothA2dp: Proxy object disconnected
09-14 06:52:15.691  3129  3129 D BluetoothA2dp: Proxy object disconnected
09-14 06:52:15.693   926  5213 D DhcpClient: Clearing IP address
09-14 06:52:15.693   506   919 D CommandListener: Clearing all IP addresses on wlan0
,09-14 06:52:15.695  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:52:15.695  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:15.695  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:15.695  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:15.695  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:15.695  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:15.695  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:52:15.695  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:52:15.695  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 06:52:15.696   506   919 D CommandListener: Setting iface cfg
09-14 06:52:15.697  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:15.699  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 06:52:15.703  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:52:15.703  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:15.703  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:15.703  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:15.703  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:15.703  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:15.703  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:52:15.703  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:52:15.703  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 06:52:15.703  4458  4458 D HidService: Received stop request...Stopping profile...
09-14 06:52:15.703  4458  4458 D HidService: Stopping Bluetooth HidService
09-14 06:52:15.704  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:15.704  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 06:52:15.704  3129  3129 D BluetoothInputDevice: Proxy object disconnected
09-14 06:52:15.704  3129  3129 D HidProfile: Bluetooth service disconnected
09-14 06:52:15.705  4458  4458 D HealthService: Received stop request...Stopping profile...
09-14 06:52:15.707  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:15.709  4458  4458 D PanService: Received stop request...Stopping profile...
,09-14 06:52:15.710  3604  5283 V NativeCrypto: Read error: ssl=0x7f8d6b5000: I/O error during system call, Connection timed out
09-14 06:52:15.710  3129  3129 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-14 06:52:15.710  3129  3129 D PanProfile: Bluetooth service disconnected
09-14 06:52:15.711  4458  4458 V BluetoothAdapterState: isTurningOff()=true
09-14 06:52:15.711  4458  4458 V BluetoothAdapterState: isTurningOn()=false
,09-14 06:52:15.711  4458  4458 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:15.711  4458  4458 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 06:52:15.712  3604  5283 V NativeCrypto: SSL shutdown failed: ssl=0x7f8d6b5000: I/O error during system call, Broken pipe
09-14 06:52:15.713  4458  4535 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-14 06:52:15.713  4458  4661 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:52:15.713  4458  4661 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:52:15.713  4458  4458 D BluetoothMapService: Received stop request...Stopping profile...
09-14 06:52:15.713  4458  4661 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 06:52:15.713  4458  4458 D BluetoothMapService: stop()
09-14 06:52:15.713  4458  4661 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 06:52:15.713  4458  4661 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 06:52:15.713   926  5214 D DhcpClient: Receive thread stopped
09-14 06:52:15.713  4458  4661 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 06:52:15.714  4458  4458 D BluetoothMapAppObserver: deinitObservers()
09-14 06:52:15.714  4458  4458 D BluetoothMapAppObserver: removeReceiver()
09-14 06:52:15.714   926  3206 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-14 06:52:15.714   926  5211 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-14 06:52:15.715  3129  3129 D BluetoothMap: Proxy object disconnected
09-14 06:52:15.716  3129  3129 D MapProfile: Bluetooth service disconnected
09-14 06:52:15.717   926  2992 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-14 06:52:15.717  4458  4458 D SapService: Received stop request...Stopping profile...
09-14 06:52:15.717  4458  4458 V SapService: stop()
09-14 06:52:15.717   926  2992 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-14 06:52:15.718   926  5211 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-14 06:52:15.722   926  2992 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-14 06:52:15.723   532   532 E Parcel  : Reading a NULL string not supported here.
09-14 06:52:15.724  3499  3646 W QCNEJ   : |CORE| network lost: 100
09-14 06:52:15.725  3499  3646 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-14 06:52:15.728   926   926 D RttService: SCAN_AVAILABLE : 1
09-14 06:52:15.728   926  3095 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-14 06:52:15.730  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:52:15.730  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:15.730  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:15.730  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:15.730  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:15.730  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:15.730  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:15.730  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:15.730  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:52:15.731  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:52:15.731  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:15.733  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:15.733  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:15.733  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:15.733  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:15.733  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:15.733  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:15.733  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:15.733  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:15.733  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:15.734  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:15.734  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:15.737  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:15.737  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:15.737  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:15.737  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:15.737  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:15.737  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:15.737  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:15.737  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:15.737  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:15.738  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:15.738  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:52:15.741   926   939 I ActivityManager: Start proc 5562:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-14 06:52:15.743  4458  4458 V BluetoothAdapterState: isTurningOff()=true
09-14 06:52:15.743  4458  4458 V BluetoothAdapterState: isTurningOn()=false
,09-14 06:52:15.743  4458  4458 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:15.743  4458  4458 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:15.743   926  2990 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-14 06:52:15.743  4458  4458 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-14 06:52:15.743  4458  4458 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-14 06:52:15.744  4458  4458 V BluetoothAdapterState: isTurningOff()=true
09-14 06:52:15.744  4458  4458 V BluetoothAdapterState: isTurningOn()=false
09-14 06:52:15.744  4458  4458 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:15.744  4458  4458 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:15.744  4458  4458 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-14 06:52:15.744  4458  4535 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-14 06:52:15.744  4458  4535 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-14 06:52:15.745  4458  4458 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-14 06:52:15.745  4458  4458 V BluetoothAdapterState: isTurningOff()=true
09-14 06:52:15.745  4458  4458 V BluetoothAdapterState: isTurningOn()=false
09-14 06:52:15.745  4458  4458 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 06:52:15.745  4458  4458 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:15.745  4458  4458 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-14 06:52:15.745  4458  4458 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-14 06:52:15.746  4458  4458 D BluetoothMapService: MAP Service closeService in
09-14 06:52:15.746  4458  4458 D BluetoothMapMasInstance0: MAP Service shutdown
09-14 06:52:15.746  4458  4458 D ObexServerSockets0: shutdown(block = true)
09-14 06:52:15.747  4458  4458 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 06:52:15.747  4458  4458 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 06:52:15.747  4458  4704 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-14 06:52:15.747  4458  4666 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-14 06:52:15.748  4458  4703 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-14 06:52:15.749  4458  4458 V BluetoothAdapterState: isTurningOff()=true
09-14 06:52:15.749  4458  4458 V BluetoothAdapterState: isTurningOn()=false
09-14 06:52:15.750  4458  4458 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:15.750  4458  4458 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:15.750  4458  4458 D BluetoothMapService: cleanup()
09-14 06:52:15.750  4458  4458 D BluetoothMapService: MAP Service closeService in
09-14 06:52:15.750  4458  4458 V BluetoothAdapterState: isTurningOff()=true
09-14 06:52:15.751  4458  4458 V BluetoothAdapterState: isTurningOn()=false
,09-14 06:52:15.751  4458  4458 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:15.751  4458  4458 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:15.751  4458  4529 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-14 06:52:15.751  4458  4529 D BluetoothAdapterProperties: Setting state to 15
09-14 06:52:15.751  4458  4529 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-14 06:52:15.751  4458  4529 I BluetoothAdapterState: Entering BleOnState
,09-14 06:52:15.752  3129  5504 D BluetoothPan: onBluetoothStateChange on: false
09-14 06:52:15.753   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:52:15.753   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 06:52:15.753   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:52:15.753  3129  3143 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-14 06:52:15.753   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-14 06:52:15.754   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:52:15.754  3129  3141 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-14 06:52:15.755  3129  3491 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 06:52:15.758  3129  5504 D BluetoothMap: onBluetoothStateChange: up=false
09-14 06:52:15.758  3129  3143 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 06:52:15.759  3523  3802 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:52:15.759  4458  4529 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-14 06:52:15.760  4458  4529 D BluetoothAdapterProperties: Setting state to 16
,09-14 06:52:15.760  4458  4529 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-14 06:52:15.751  4458  4458 I BtOppRfcommListener: stopping Accept Thread
09-14 06:52:15.761  4458  4529 D BluetoothAdapterProperties: onBleDisable
09-14 06:52:15.761  4458  4529 I BluetoothAdapterState: Entering PendingCommandState
09-14 06:52:15.761  4458  4532 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-14 06:52:15.762  4458  5165 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 06:52:15.762  4458  4661 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-14 06:52:15.762  4458  4661 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:52:15.763  4458  4535 D BluetoothAdapterProperties: Scan Mode:20
09-14 06:52:15.763  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:15.764  4458  5165 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-14 06:52:15.765  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:15.768  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:15.769   926  2990 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 06:52:15.769   926  2990 E native  : do suspend true
,09-14 06:52:15.769  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:15.772  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:15.773  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:15.799   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-14 06:52:15.799   506   919 D CommandListener: Clearing all IP addresses on wlan0
,09-14 06:52:15.800   926  2992 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-14 06:52:15.800  5562  5562 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-14 06:52:15.801   926  2992 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-14 06:52:15.803   926   943 D Tethering: MasterInitialState.processMessage what=3
09-14 06:52:15.804  5100  5100 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@834ef51 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-14 06:52:15.804   926  2990 D DhcpClient: doQuit
09-14 06:52:15.805   926  2990 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-14 06:52:15.805   926  5213 D DhcpClient: onQuitting
09-14 06:52:15.805  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:15.806  3615  3615 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-14 06:52:15.808  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:15.809  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:15.809  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:15.809  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:15.809  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:15.809  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:15.809  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:15.809  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:15.809  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:52:15.809  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:52:15.809  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:15.811  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:15.811  4879  4894 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-14 06:52:15.811  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:15.811  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:15.811  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:15.811  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:15.811  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:15.811  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:15.811  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:15.811  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:15.811  4879  4894 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-14 06:52:15.812  4879  4894 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-14 06:52:15.812  4879  4894 E SarControlService: no key has been found,reset the power
09-14 06:52:15.812  4879  4920 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-14 06:52:15.812  4879  4920 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-14 06:52:15.812  4879  4920 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-14 06:52:15.812  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:15.812  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:52:15.812  4908  4908 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-14 06:52:15.813  4908  4908 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-14 06:52:15.814  4879  4920 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-14 06:52:15.814  4879  4920 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-14 06:52:15.814  4879  4920 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-14 06:52:15.815  4908  4908 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 06:52:15.815  4908  4908 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-14 06:52:15.815  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:15.815  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:15.815  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:15.815  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:15.815  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:15.815  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:15.815  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:15.815  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:15.815  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:15.816  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:15.816  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:15.817  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:15.818  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:15.820  4908  4922 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e336cff HexData = [00000000ea03000000000000ffffffff]
09-14 06:52:15.820  4908  4922 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 06:52:15.820  4908  4922 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-14 06:52:15.822  4908  4908 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 06:52:15.822  4879  4890 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-14 06:52:15.828  4908  4922 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e336cff HexData = [00000000eb03000000000000ffffffff]
,09-14 06:52:15.829  4908  4922 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 06:52:15.829  4908  4922 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-14 06:52:15.829  4908  4908 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-14 06:52:15.830  3615  3615 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-14 06:52:15.830  4879  4891 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-14 06:52:15.833  3615  3615 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-14 06:52:15.853  5562  5562 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-14 06:52:15.854   506   919 E Netd    : netlink response contains error (No such file or directory)
,09-14 06:52:15.856   926  2992 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-14 06:52:15.856   926  2992 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-14 06:52:15.867   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a8435b:true
,09-14 06:52:15.867  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:52:15.867  3615  3615 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-14 06:52:15.880   926  3417 I ActivityManager: Start proc 5585:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-14 06:52:15.880  3615  3615 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-14 06:52:15.886   926  2990 D wifi    : In wifi stop Hal
,09-14 06:52:15.886   926  2990 D wifi    : halHandle = 0x7f8c88b300, mVM = 0x7fa864d140, mCls = 0x100ace
09-14 06:52:15.886  4304  4304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 06:52:15.886   926  3614 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-14 06:52:15.886   926  3614 D WifiHAL : Got a signal to exit!!!
09-14 06:52:15.886   926  3614 I WifiHAL : Exit wifi_event_loop
,09-14 06:52:15.887   926  2990 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-14 06:52:15.887   926  2990 E WifiHAL : Event processing terminated
09-14 06:52:15.888   926  2990 D wifi    : In wifi cleaned up handler
09-14 06:52:15.888   926  2990 I WifiHAL : Internal cleanup completed
,09-14 06:52:15.888  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:15.890  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:15.891  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:15.893  3648  4041 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 06:52:15.906   926  3614 D wifi    : set interface wlan0 flags (DOWN)
09-14 06:52:15.908   926  2990 D WifiNative-HAL: HAL event thread stopped successfully
,09-14 06:52:15.931  5562  5562 D LocalBluetoothProfileManager: Adding local MAP profile
,09-14 06:52:15.933  5562  5562 D BluetoothMap: Create BluetoothMap proxy object
,09-14 06:52:15.940  5585  5585 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-14 06:52:15.945  5562  5562 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-14 06:52:15.965  5562  5562 D DockEventReceiver: finishStartingService: stopping service
,09-14 06:52:15.968   926  3806 I ActivityManager: Killing 4860:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-14 06:52:15.968  4458  4535 I bt_hci  : shut_down
,09-14 06:52:15.974   506   919 E Netd    : netlink response contains error (No such file or directory)
,09-14 06:52:15.998  4458  4551 D bt_hwcfg: hw_epilog_process
,09-14 06:52:15.999  4458  4551 I bt_vendor: low_power_mode_cb
,09-14 06:52:16.001  4458  4551 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-14 06:52:16.001  4458  4551 I bt_vendor: epilog_cb
09-14 06:52:16.001  4458  4551 I bt_hci  : epilog_finished_callback
09-14 06:52:16.003  4458  4535 I bt_hci_h4: hal_close
09-14 06:52:16.003  4458  4535 I bt_userial_vendor: device fd = 54 close
,09-14 06:52:16.111   926   943 D Tethering: InitialState.processMessage what=4
,09-14 06:52:16.112  4458  4532 D bt_stack_manager: event_shut_down_stack finished.
09-14 06:52:16.112  4458  4529 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-14 06:52:16.114  4458  4529 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-14 06:52:16.114  4458  4458 D BtGatt.DebugUtils: handleDebugAction() action=null
09-14 06:52:16.114   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-14 06:52:16.114  4458  4458 D BtGatt.GattService: Received stop request...Stopping profile...
,09-14 06:52:16.114  4458  4458 D BtGatt.GattService: stop()
09-14 06:52:16.114  4458  4458 D BtGatt.AdvertiseManager: advertise clients cleared
,09-14 06:52:16.117  4458  4458 V BluetoothAdapterState: isTurningOff()=false
,09-14 06:52:16.117  4458  4458 V BluetoothAdapterState: isTurningOn()=false
09-14 06:52:16.117  4458  4458 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 06:52:16.117  4458  4458 V BluetoothAdapterState: isBleTurningOff()=true
09-14 06:52:16.117  4458  4529 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-14 06:52:16.117  4458  4529 D BluetoothAdapterProperties: Setting state to 10
,09-14 06:52:16.117  4458  4529 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-14 06:52:16.118   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-14 06:52:16.119  4458  4529 I BluetoothAdapterState: Entering OffState
09-14 06:52:16.120   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:16.133  4458  4458 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-14 06:52:16.134  4458  4458 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-14 06:52:16.134  4458  4532 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-14 06:52:16.135  4458  4458 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-14 06:52:16.144  4458  4532 D bt_stack_manager: event_clean_up_stack finished.
,09-14 06:52:16.165  4458  4458 I art     : System.exit called, status: 0
,09-14 06:52:16.165  4458  4458 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-14 06:52:16.180  5585  5585 D StrictMode: StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at java.io.File.exists(File.java:361)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-14 06:52:16.180  5585  5585 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 06:52:16.180  5585  5585 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:52:16.180  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 06:52:16.181  5585  5585 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.r.e.b(PG:170)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 06:52:16.181  5585  5585 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.r.k.d(PG:583)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.r.e.b(PG:170)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 06:52:16.181  5585  5585 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.io.File.exists(File.java:361)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 06:52:16.181  5585  5585 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.io.File.exists(File.java:361)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 06:52:16.181  5585  5585 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:52:16.181  5585  5585 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 06:52:16.186  5562  5562 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-14 06:52:16.200  5562  5562 D DockEventReceiver: finishStartingService: stopping service
09-14 06:52:16.201   926  3168 I ActivityManager: Killing 5239:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
09-14 06:52:16.218   926  3397 I ActivityManager: Process com.android.bluetooth (pid 4458) has died
09-14 06:52:16.221  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:52:16.233   926  3423 I ActivityManager: Start proc 5622:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-14 06:52:16.302  5622  5622 D AdapterServiceConfig: Adding HeadsetService
,09-14 06:52:16.303  5622  5622 D AdapterServiceConfig: Adding A2dpService
09-14 06:52:16.303  5622  5622 D AdapterServiceConfig: Adding HidService
09-14 06:52:16.303  5622  5622 D AdapterServiceConfig: Adding HealthService
,09-14 06:52:16.303  5622  5622 D AdapterServiceConfig: Adding PanService
09-14 06:52:16.303  5622  5622 D AdapterServiceConfig: Adding GattService
09-14 06:52:16.303  5622  5622 D AdapterServiceConfig: Adding BluetoothMapService
09-14 06:52:16.304  5622  5622 D AdapterServiceConfig: Adding SapService
,09-14 06:52:16.309   926  3806 I ActivityManager: Killing 5251:com.android.chrome/u0a39 (adj 15): empty #17
,09-14 06:52:16.347  3927  3927 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-14 06:52:16.352  3927  5237 I iu.UploadsManager: num queued entries: 0
,09-14 06:52:16.352  3927  5237 I iu.UploadsManager: num updated entries: 0
09-14 06:52:16.353  3927  5237 I iu.SyncManager: NEXT; no task
,09-14 06:52:16.358  3927  3927 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-14 06:52:16.360  3927  3927 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-14 06:52:16.373   926  3567 I ActivityManager: Start proc 5636:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-14 06:52:16.406  5636  5636 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-14 06:52:16.409  5636  5636 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-14 06:52:16.419  5636  5636 D SprintDMHelper: simOperator: 
09-14 06:52:16.419  5636  5636 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-14 06:52:16.431   926  3423 I ActivityManager: Start proc 5648:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-14 06:52:16.431   926  3423 I ActivityManager: Killing 5269:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-14 06:52:16.539  4304  5662 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-14 06:52:16.545   926  3806 I ActivityManager: Start proc 5663:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-14 06:52:16.547   926  3423 I ActivityManager: Killing 5100:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-14 06:52:16.568  5585  5611 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-14 06:52:16.596  5663  5663 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-14 06:52:16.747   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c2b0b6c:true
,09-14 06:52:16.752   926  3206 I ActivityManager: Killing 4555:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-14 06:52:16.794   926   936 I ActivityManager: Start proc 5677:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-14 06:52:16.825  5677  5677 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-14 06:52:16.835   926  3397 I ActivityManager: Killing 5367:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-14 06:52:17.121   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:18.121   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 06:52:20.684   926  3206 D WifiService: setWifiEnabled: true pid=5505, uid=10077
,09-14 06:52:20.684   926  3206 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 06:52:20.696   506   919 D SoftapController: Softap fwReload - Ok
,09-14 06:52:20.700   506   919 D CommandListener: Setting iface cfg
,09-14 06:52:20.700   506   919 D CommandListener: Trying to bring down wlan0
,09-14 06:52:20.701   506   919 D CommandListener: Clearing all IP addresses on wlan0
,09-14 06:52:20.705   926  2990 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-14 06:52:21.281   926  2990 D wifi    : set interface wlan0 flags (UP)
,09-14 06:52:21.286   926  2990 I WifiHAL : Initializing wifi
09-14 06:52:21.286   926  2990 I WifiHAL : Creating socket
09-14 06:52:21.292   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-14 06:52:21.296   926  2990 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-14 06:52:21.296   926  2990 D wifi    : Did set static halHandle = 0x7f8c88b300
09-14 06:52:21.297   926  2990 D wifi    : halHandle = 0x7f8c88b300, mVM = 0x7fa864d140, mCls = 0x1932
09-14 06:52:21.297   926  2990 D wifi    : array field set
09-14 06:52:21.297   926  2990 I WifiNative-HAL: interface[0] = wlan0
,09-14 06:52:21.300   926  5695 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547818615552
,09-14 06:52:21.300   926  5695 D wifi    : waitForHalEvents called, vm = 0x7fa864d140, obj = 0x1932, env = 0x7f8e0251c0
,09-14 06:52:21.366  5697  5697 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-14 06:52:21.389  5697  5697 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-14 06:52:21.391   506   919 E FrameworkListener: read() failed (Connection reset by peer)
,09-14 06:52:21.402   926  2990 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-14 06:52:21.406  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:21.407  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:21.408  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:21.423  5697  5697 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-14 06:52:21.423  5697  5697 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-14 06:52:21.439  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:52:21.439  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:21.439  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:21.439  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:21.439  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:21.439  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:21.439  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:21.439  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:21.439  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:21.439  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:21.439  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:52:21.440  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:21.440  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:21.440  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:21.440  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:21.440  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:21.440  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:21.440  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:21.440  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:21.440  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:21.440  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:21.440  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:21.440   926  2990 D WifiConfigStore: Loading config and enabling all networks 
09-14 06:52:21.441  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:21.441  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:21.441  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:21.441  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:21.441  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:21.441  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:21.441  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:21.441  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:21.441  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:52:21.441  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:21.441  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:52:21.445   926  2990 D WifiConfigStore: loaded 0 passpoint configs
,09-14 06:52:21.445   926  2990 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-14 06:52:21.446   926  2990 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-14 06:52:21.446   926  2990 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-14 06:52:21.446   926  2990 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
09-14 06:52:21.447   926  2990 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-14 06:52:21.450  4304  4304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 06:52:21.450   926  2990 D WifiNative-HAL: Setting external_sim to 1
09-14 06:52:21.451   926  2990 D wifi    : setting dfs flag to true, 0x7f8da7f680
09-14 06:52:21.451   926  2990 D WifiStateMachine: Setting OUI to DA-A1-19
09-14 06:52:21.452   926  2990 D wifi    : setting scan oui 0x7f8da7f680
09-14 06:52:21.452   926  2990 D WifiHAL : Sending mac address OUI
,09-14 06:52:21.466   926  2990 E native  : do suspend true
,09-14 06:52:21.471   926  2990 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-14 06:52:21.471   506   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-14 06:52:21.472   926   926 D RttService: SCAN_AVAILABLE : 3
09-14 06:52:21.472   926  3095 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-14 06:52:21.472   506   919 D CommandListener: Setting iface cfg
,09-14 06:52:21.476   926  2963 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,09-14 06:52:21.476   926  2963 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-14 06:52:21.482   926  2963 D WifiNative-HAL: p2pGetDeviceAddress
,09-14 06:52:21.487   926  2963 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-14 06:52:21.487   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=377182 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=7 mControllerEnergyUsed=26 }
,09-14 06:52:24.718  5697  5697 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-14 06:52:24.749   926  2990 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-14 06:52:24.754   926  2990 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,09-14 06:52:24.755   926  2990 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 06:52:24.772   926  2990 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-14 06:52:24.820   926  2990 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-14 06:52:25.157  5697  5697 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-14 06:52:25.193  5697  5697 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-14 06:52:25.193  5697  5697 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-14 06:52:25.203   926  2990 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-14 06:52:25.204   926  2990 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 06:52:25.204   926  2992 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-14 06:52:25.219   926  2990 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 06:52:25.233   506   919 D CommandListener: Setting iface cfg
,09-14 06:52:25.238   926  2990 D WifiStateMachine: Start Dhcp Watchdog 2
,09-14 06:52:25.242   926  2990 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-14 06:52:25.246   926  5715 D DhcpClient: Receive thread started
,09-14 06:52:25.328   926  2990 E native  : do suspend false
,09-14 06:52:25.342   926  5714 D DhcpClient: Broadcasting DHCPDISCOVER
,09-14 06:52:25.355   926  5715 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172461, domain null
,09-14 06:52:25.356   926  5714 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172461 seconds
,09-14 06:52:25.358   926  5714 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-14 06:52:25.377   926  5715 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-14 06:52:25.378   926  5714 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-14 06:52:25.380   506   919 D CommandListener: Setting iface cfg
,09-14 06:52:25.385   926  2990 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-14 06:52:25.390   926  2990 E native  : do suspend true
,09-14 06:52:25.390   926  5714 D DhcpClient: Scheduling renewal in 86399s
,09-14 06:52:25.415   926  2990 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-14 06:52:25.415   926  2990 D WifiConfigStore: No blacklist allowed without epno enabled
,09-14 06:52:25.417   926  2992 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-14 06:52:25.419   926  2992 D ConnectivityService: Adding iface wlan0 to network 101
09-14 06:52:25.427   926  2990 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-14 06:52:25.471   926  2992 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-14 06:52:25.472   926  2992 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-14 06:52:25.475   926  2992 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-14 06:52:25.477   926  2992 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-14 06:52:25.479   926  2992 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-14 06:52:25.487   926  2992 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:52:25.492   926  2992 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-14 06:52:25.492   926  2992 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-14 06:52:25.492   926  2992 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-14 06:52:25.492   926  2992 D ConnectivityService:    accepting network in place of null
,09-14 06:52:25.492   926  2990 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-14 06:52:25.492   926  2990 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 06:52:25.493   926  2992 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-14 06:52:25.523   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 06:52:25.549   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 06:52:25.552   926  2992 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-14 06:52:25.552   926  2992 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-14 06:52:25.552  3499  3646 W QCNEJ   : |CORE| network available: 101
09-14 06:52:25.554   926  2992 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-14 06:52:25.554  3499  3646 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-14 06:52:25.555  3499  3646 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-14 06:52:25.556  3499  3646 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-14 06:52:25.556   926   943 D Tethering: MasterInitialState.processMessage what=3
,09-14 06:52:25.567  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:52:25.567  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:25.567  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:25.567  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:25.567  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:25.567  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:25.567  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:52:25.567  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:52:25.567  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 06:52:25.567  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.567  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 06:52:25.569  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.569  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:25.569  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:25.569  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:25.569  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:25.569  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:25.569  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:52:25.569  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:52:25.569  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 06:52:25.569  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.569  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 06:52:25.571  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:52:25.571  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:25.571  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:25.571  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:25.571  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:25.571  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:25.571  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:52:25.571  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:52:25.571  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 06:52:25.571  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.571  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 06:52:25.572  4879  4894 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-14 06:52:25.572  4879  4894 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-14 06:52:25.572  4879  4894 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-14 06:52:25.572  4879  4894 E SarControlService: no key has been found,reset the power
09-14 06:52:25.573  4879  4920 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-14 06:52:25.573  4879  4920 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-14 06:52:25.573  4879  4920 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-14 06:52:25.573  4908  4908 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 06:52:25.573  4908  4908 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-14 06:52:25.574   926  5713 D NetlinkSocketObserver: NeighborEvent{elapsedMs=381270, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 06:52:25.575  4879  4920 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-14 06:52:25.576  4879  4920 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-14 06:52:25.576  4879  4920 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-14 06:52:25.576  4908  4908 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 06:52:25.576  4908  4908 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-14 06:52:25.580  4908  4922 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e336cff HexData = [00000000ec03000000000000ffffffff]
09-14 06:52:25.580  4908  4922 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-14 06:52:25.580  4908  4922 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,09-14 06:52:25.582  4908  4908 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 06:52:25.583  4879  4890 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-14 06:52:25.583  4908  4922 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e336cff HexData = [00000000ed03000000000000ffffffff]
09-14 06:52:25.584  4908  4922 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 06:52:25.584  4908  4922 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,09-14 06:52:25.585  4908  4908 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 06:52:25.585  4879  4891 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-14 06:52:25.590  3927  3927 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-14 06:52:25.599  3927  5237 I iu.UploadsManager: num queued entries: 0
,09-14 06:52:25.600  3927  5237 I iu.UploadsManager: num updated entries: 0
09-14 06:52:25.600  3927  5237 I iu.SyncManager: NEXT; no task
,09-14 06:52:25.601  3927  3927 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-14 06:52:25.603  3927  3927 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-14 06:52:25.605  5636  5636 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-14 06:52:25.608  5636  5636 D SprintDMHelper: simOperator: 
,09-14 06:52:25.608  5636  5636 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-14 06:52:25.647   926  5712 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-14 06:52:25.694   926  3206 D WifiService: setWifiEnabled: false pid=5505, uid=10077
,09-14 06:52:25.694   926  3206 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 06:52:25.695   926  2990 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-14 06:52:25.695   926  2990 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-14 06:52:25.695   926  2990 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 06:52:25.695   926  2990 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 06:52:25.704   926  2990 E native  : do suspend true
,09-14 06:52:25.708   926  5712 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 14 Sep 2016 10:52:25 GMT], X-Android-Received-Millis=[1473850345708], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473850345674]}
,09-14 06:52:25.709   926  2992 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-14 06:52:25.709   926  2992 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-14 06:52:25.709   926  2992 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:52:25.710   926  2992 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-14 06:52:25.712   926  5714 D DhcpClient: Clearing IP address
09-14 06:52:25.712   506   919 D CommandListener: Clearing all IP addresses on wlan0
09-14 06:52:25.714   506   919 D CommandListener: Setting iface cfg
,09-14 06:52:25.720  3604  5725 V NativeCrypto: SSL handshake aborted: ssl=0x7f8da2a680: I/O error during system call, Connection timed out
09-14 06:52:25.722  4304  5729 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-14 06:52:25.723   926  2992 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-14 06:52:25.723   926  2992 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-14 06:52:25.726   532   532 E Parcel  : Reading a NULL string not supported here.
09-14 06:52:25.731   926  5715 D DhcpClient: Receive thread stopped
09-14 06:52:25.732   926  2990 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-14 06:52:25.733   926   926 D RttService: SCAN_AVAILABLE : 1
09-14 06:52:25.733   926  3095 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-14 06:52:25.735   926  2992 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
09-14 06:52:25.735  ,4304  5729 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
09-14 06:52:25.735  4304  5729 W Babel_NetworkConnectionCheckingService: 	... 21 more
09-14 06:52:25.735   926  2990 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 06:52:25.736   926  2990 E native  : do suspend true
09-14 06:52:25.736  3499  3646 W QCNEJ   : |CORE| network lost: 101
,09-14 06:52:25.737  3499  3646 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-14 06:52:25.738  4304  5729 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-14 06:52:25.755   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 06:52:25.774   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 06:52:25.774   926  2992 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-14 06:52:25.774   506   919 D CommandListener: Clearing all IP addresses on wlan0
09-14 06:52:25.774   926  2992 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-14 06:52:25.776   926   943 D Tethering: MasterInitialState.processMessage what=3
,09-14 06:52:25.779  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.779  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:25.779  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:25.779  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:25.779  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:25.779  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:25.779  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:25.779  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:25.779  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:25.779  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.779  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:25.781   926  2990 D DhcpClient: doQuit
09-14 06:52:25.781   926  2990 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-14 06:52:25.781   926  5714 D DhcpClient: onQuitting
09-14 06:52:25.781  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:52:25.781  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:25.781  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:25.781  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:25.781  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:25.781  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:25.781  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:25.781  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:25.781  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:25.781  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.781  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:25.781  5697  5697 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-14 06:52:25.782  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.782  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:25.782  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:25.782  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:25.782  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:25.782  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:25.782  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:25.782  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:25.782  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:25.782  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.782  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:25.784  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.784  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:25.784  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:25.784  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:25.784  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:25.784  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:25.784  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:25.784  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:25.784  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:25.784  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.b,luetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.784  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:25.784  4879  4894 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-14 06:52:25.784  4879  4894 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-14 06:52:25.784  4879  4894 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-14 06:52:25.785  4879  4894 E SarControlService: no key has been found,reset the power
09-14 06:52:25.785  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.785  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:25.785  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:25.785  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:25.785  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:25.785  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:25.785  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:25.785  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:25.785  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:25.785  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.785  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:25.786  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.786  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:25.786  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:25.786  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:25.786  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:25.786  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:25.786  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:25.786  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:25.786  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:25.786  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:25.786  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:25.786  4879  4920 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-14 06:52:25.787  4879  4920 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-14 06:52:25.787  4879  4920 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-14 06:52:,25.788  4908  4908 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 06:52:25.788  4908  4908 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-14 06:52:25.789  4879  4920 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-14 06:52:25.790  4879  4920 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-14 06:52:25.790  4879  4920 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-14 06:52:25.790  4908  4908 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 06:52:25.791  4908  4908 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-14 06:52:25.795  4908  4922 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e336cff HexData = [00000000ee03000000000000ffffffff]
09-14 06:52:25.795  4908  4922 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 06:52:25.795  4908  4922 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-14 06:52:25.795  4908  4908 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 06:52:25.795  4879  4891 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-14 06:52:25.796  4908  4922 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e336cff HexData = [00000000ef03000000000000ffffffff]
09-14 06:52:25.796  4908  4922 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 06:52:25.796  4908  4922 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-14 06:52:25.797  4908  4908 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 06:52:25.797  4879  4890 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-14 06:52:25.797  3927  3927 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-14 06:52:25.802  3927  5237 I iu.UploadsManager: num queued entries: 0
09-14 06:52:25.802  3927  5237 I iu.UploadsManager: num updated entries: 0
09-14 06:52:25.803  3927  5237 I iu.SyncManager: NEXT; no task
09-14 06:52:25.804  3927  3927 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-14 06:52:25.806  5697  5697 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-14 06:52:25.806  3927  3927 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-14 06:52:25.808  5636  5636 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-14 06:52:25.808  5697  5697 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-14 06:52:25.815  5636  5636 D SprintDMHelper: simOperator: 
09-14 06:52:25.815  5636  5636 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-14 06:52:25.831  4304  5745 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-14 06:52:25.835   506   919 E Netd    : netlink response contains error (No such file or directory)
,09-14 06:52:25.837   926  2992 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-14 06:52:25.837  5697  5697 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-14 06:52:25.844  5697  5697 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-14 06:52:25.946   926  2990 D wifi    : In wifi stop Hal
09-14 06:52:25.946   926  2990 D wifi    : halHandle = 0x7f8c88b300, mVM = 0x7fa864d140, mCls = 0x1932
09-14 06:52:25.946   926  5695 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-14 06:52:25.946   926  5695 D WifiHAL : Got a signal to exit!!!
09-14 06:52:25.946   926  5695 I WifiHAL : Exit wifi_event_loop
09-14 06:52:25.946   926  2990 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-14 06:52:25.946   926  2990 E WifiHAL : Event processing terminated
09-14 06:52:25.947   926  2990 D wifi    : In wifi cleaned up handler
09-14 06:52:25.947   926  2990 I WifiHAL : Internal cleanup completed
,09-14 06:52:25.947  4304  4304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 06:52:25.950  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:25.952  3648  4041 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 06:52:25.952  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:25.954  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:25.968   926  5695 D wifi    : set interface wlan0 flags (DOWN)
,09-14 06:52:25.968   926  2990 D WifiNative-HAL: HAL event thread stopped successfully
,09-14 06:52:26.026   506   919 E Netd    : netlink response contains error (No such file or directory)
,09-14 06:52:26.177   926   943 D Tethering: InitialState.processMessage what=4
,09-14 06:52:26.184   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-14 06:52:26.553   926  2992 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-14 06:52:28.918   926   926 E WifiNative-wlan0: set PNO failure
,09-14 06:52:30.732   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f8f3718:true
,09-14 06:52:30.733  5622  5622 D BluetoothAdapterState: make() - Creating AdapterState
,09-14 06:52:30.737  5622  5622 I bt_bluedroid: init
09-14 06:52:30.737  5622  5755 I BluetoothAdapterState: Entering OffState
,09-14 06:52:30.740  5622  5756 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-14 06:52:30.741  5622  5756 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-14 06:52:30.741  5622  5756 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-14 06:52:30.741  5622  5756 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-14 06:52:30.742  5622  5622 I bt_bluedroid: get_profile_interface socket
,09-14 06:52:30.745  5622  5622 I bt_bluedroid: get_profile_interface sdp
09-14 06:52:30.745  5622  5759 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-14 06:52:30.747  5622  5759 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-14 06:52:30.753  5622  5633 I bt_bluedroid: config_hci_snoop_log
09-14 06:52:30.755   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-14 06:52:30.761  5622  5755 D BluetoothAdapterState: Current state: OFF, message: 0
,09-14 06:52:30.761  5622  5755 D BluetoothAdapterProperties: Setting state to 14
09-14 06:52:30.761  5622  5755 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-14 06:52:30.764  5622  5755 D BluetoothBondStateMachine: make
,09-14 06:52:30.767  5622  5760 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-14 06:52:30.771  5622  5755 I BluetoothAdapterState: Entering PendingCommandState
,09-14 06:52:30.773  5622  5622 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-14 06:52:30.777  5622  5622 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
,09-14 06:52:30.778  5622  5622 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-14 06:52:30.779  5622  5622 D BtGatt.GattService: Received start request. Starting profile...
09-14 06:52:30.779  5622  5622 D BtGatt.GattService: start()
09-14 06:52:30.780  5622  5622 I bt_bluedroid: get_profile_interface gatt
,09-14 06:52:30.782  5622  5622 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
,09-14 06:52:30.782  5622  5622 D BtGatt.AdvertiseManager: advertise manager created
,09-14 06:52:30.789  5622  5622 V BluetoothAdapterState: isTurningOff()=false
,09-14 06:52:30.789  5622  5622 V BluetoothAdapterState: isTurningOn()=false
09-14 06:52:30.789  5622  5622 V BluetoothAdapterState: isBleTurningOn()=true
09-14 06:52:30.789  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:30.789  5622  5755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-14 06:52:30.791  5622  5755 I bt_bluedroid: bt_bluedroid
09-14 06:52:30.792  5622  5756 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-14 06:52:30.792  5622  5756 I bt_hci  : start_up
,09-14 06:52:30.798  5622  5756 I bt_vendor: alloc value 0xf4138871
,09-14 06:52:30.798  5622  5756 I bt_vendor: init
09-14 06:52:30.798  5622  5756 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-14 06:52:30.798  5622  5756 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-14 06:52:30.910  5622  5756 D bt_hci  : start_up starting async portion
09-14 06:52:30.910  5622  5763 I bt_hci  : event_finish_startup
,09-14 06:52:30.910  5622  5763 I bt_hci_h4: hal_open
09-14 06:52:30.910  5622  5763 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-14 06:52:30.913  5622  5763 I bt_userial_vendor: device fd = 54 open
,09-14 06:52:30.910  5764  5764 W irq/448-msm_hs_: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-14 06:52:30.928  5622  5763 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 06:52:30.930  5622  5763 D bt_hwcfg: Chipset BCM4358A3
,09-14 06:52:30.931  5622  5763 D bt_hwcfg: Target name = [BCM4358A3]
09-14 06:52:30.931  5622  5763 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-14 06:52:31.323  5622  5763 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-14 06:52:31.324  5622  5763 D bt_hwcfg: Settlement delay -- 100 ms
09-14 06:52:31.324  5622  5763 I bt_hwcfg: Setting fw settlement delay to 100 
,09-14 06:52:31.459  5622  5763 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-14 06:52:31.459  5622  5763 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-14 06:52:31.461  5622  5763 I bt_hwcfg: vendor lib fwcfg completed
09-14 06:52:31.461  5622  5763 I bt_vendor: firmware callback
09-14 06:52:31.461  5622  5763 I bt_hci  : firmware_config_callback
,09-14 06:52:31.470  5622  5766 I bt_btu  : btu_task pending for preload complete event
,09-14 06:52:31.471  5622  5766 I bt_btu_task: Bluetooth chip preload is complete
09-14 06:52:31.471  5622  5766 I bt_btu  : btu_task received preload complete event
,09-14 06:52:31.478  5622  5766 I         : BTE_InitTraceLevels -- TRC_HCI
09-14 06:52:31.479  5622  5766 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-14 06:52:31.479  5622  5766 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-14 06:52:31.479  5622  5766 I         : BTE_InitTraceLevels -- TRC_AVDT
09-14 06:52:31.479  5622  5766 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-14 06:52:31.479  5622  5766 I         : BTE_InitTraceLevels -- TRC_A2D
09-14 06:52:31.479  5622  5766 I         : BTE_InitTraceLevels -- TRC_BNEP
09-14 06:52:31.479  5622  5766 I         : BTE_InitTraceLevels -- TRC_BTM
,09-14 06:52:31.480  5622  5766 I         : BTE_InitTraceLevels -- TRC_GAP
09-14 06:52:31.480  5622  5766 I         : BTE_InitTraceLevels -- TRC_PAN
09-14 06:52:31.480  5622  5766 I         : BTE_InitTraceLevels -- TRC_SDP
09-14 06:52:31.480  5622  5766 I         : BTE_InitTraceLevels -- TRC_GATT
09-14 06:52:31.480  5622  5766 I         : BTE_InitTraceLevels -- TRC_SMP
09-14 06:52:31.480  5622  5766 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-14 06:52:31.480  5622  5766 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-14 06:52:31.560  5622  5766 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40b6549
,09-14 06:52:31.560  5622  5766 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40b6549 
,09-14 06:52:31.569  5622  5759 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-14 06:52:31.571  5622  5759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-14 06:52:31.572  5622  5759 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-14 06:52:31.573  5622  5759 D BluetoothAdapterProperties: Name is: Nexus 6P
09-14 06:52:31.576  5622  5759 D BluetoothAdapterProperties: Scan Mode:20
09-14 06:52:31.576  5622  5759 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-14 06:52:31.576  5622  5759 D bt_hci  : do_postload posting postload work item
09-14 06:52:31.576  5622  5763 I bt_hci  : event_postload
,09-14 06:52:31.576  5622  5763 I bt_vendor: sco_config_cb
,09-14 06:52:31.576  5622  5763 I bt_hci  : sco_config_callback postload finished.
,09-14 06:52:31.579  5622  5759 D bt_bte_conf: Device ID record 1 : primary
09-14 06:52:31.579  5622  5759 D bt_bte_conf:   vendorId            = 000f
09-14 06:52:31.579  5622  5759 D bt_bte_conf:   vendorIdSource      = 0001
09-14 06:52:31.579  5622  5759 D bt_bte_conf:   product             = 1200
09-14 06:52:31.579  5622  5759 D bt_bte_conf:   version             = 1436
09-14 06:52:31.579  5622  5759 D bt_bte_conf:   clientExecutableURL = 
09-14 06:52:31.579  5622  5759 D bt_bte_conf:   serviceDescription  = 
09-14 06:52:31.579  5622  5759 D bt_bte_conf:   documentationURL    = 
09-14 06:52:31.580  5622  5759 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-14 06:52:31.580  5622  5756 D bt_stack_manager: event_start_up_stack finished
09-14 06:52:31.581  5622  5755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-14 06:52:31.581  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:31.581  5622  5755 D BluetoothAdapterProperties: Setting state to 15
09-14 06:52:31.582  5622  5755 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-14 06:52:31.583  5622  5755 I BluetoothAdapterState: Entering BleOnState
09-14 06:52:31.585  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:31.590  5622  5755 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-14 06:52:31.590  5622  5755 D BluetoothAdapterProperties: Setting state to 11
09-14 06:52:31.590  5622  5755 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-14 06:52:31.592  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:31.594  5622  5622 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
,09-14 06:52:31.595  5622  5622 D HeadsetService: Received start request. Starting profile...
09-14 06:52:31.597  5622  5763 I bt_vendor: low_power_mode_cb
09-14 06:52:31.597  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:31.597  5622  5622 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-14 06:52:31.598  5622  5622 D HeadsetStateMachine: make
,09-14 06:52:31.600  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:31.603  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:31.611  5622  5622 D HeadsetStateMachine: max_hf_connections = 1
09-14 06:52:31.611  5622  5622 I bt_bluedroid: get_profile_interface handsfree
,09-14 06:52:31.611  5622  5759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-14 06:52:31.612  5622  5759 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-14 06:52:31.612  5622  5755 I BluetoothAdapterState: Entering PendingCommandState
,09-14 06:52:31.614  5622  5622 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
,09-14 06:52:31.615  5622  5622 D A2dpService: Received start request. Starting profile...
,09-14 06:52:31.616  5622  5622 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-14 06:52:31.616  5622  5622 I bt_bluedroid: get_profile_interface avrcp
,09-14 06:52:31.620  5622  5622 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-14 06:52:31.620  5622  5622 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-14 06:52:31.621  5622  5622 D A2dpStateMachine: make
09-14 06:52:31.621  5622  5622 I bt_bluedroid: get_profile_interface a2dp
,09-14 06:52:31.623  5622  5775 D A2dpStateMachine: Enter Disconnected: -2
,09-14 06:52:31.624  5622  5759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-14 06:52:31.624  5622  5622 I BluetoothHidServiceJni: classInitNative: succeeds
09-14 06:52:31.625  5622  5622 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
09-14 06:52:31.626  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:52:31.628  5562  5562 D BluetoothInputDevice: Proxy object connected
,09-14 06:52:31.628  5562  5562 D HidProfile: Bluetooth service connected
09-14 06:52:31.629  5622  5622 D HidService: Received start request. Starting profile...
09-14 06:52:31.629  5622  5622 I bt_bluedroid: get_profile_interface hidhost
09-14 06:52:31.629  5622  5622 D HidService: setHidService(): set to: null
09-14 06:52:31.629  5622  5759 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf409756d
09-14 06:52:31.630  5622  5759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-14 06:52:31.630  5622  5622 I BluetoothHealthServiceJni: classInitNative: succeeds
09-14 06:52:31.630  5622  5622 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
09-14 06:52:31.631  5622  5622 D HealthService: Received start request. Starting profile...
,09-14 06:52:31.632  5622  5622 I bt_bluedroid: get_profile_interface health
,09-14 06:52:31.634  5622  5622 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-14 06:52:31.634  5622  5622 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
,09-14 06:52:31.635  5562  5562 D BluetoothPan: BluetoothPAN Proxy object connected
09-14 06:52:31.636  5622  5622 D PanService: Received start request. Starting profile...
09-14 06:52:31.636  5562  5562 D PanProfile: Bluetooth service connected
09-14 06:52:31.636  5622  5622 D BluetoothPanServiceJni: initializeNative(L110): pan
09-14 06:52:31.636  5622  5622 I bt_bluedroid: get_profile_interface pan
,09-14 06:52:31.636  5622  5759 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-14 06:52:31.638  5622  5622 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
,09-14 06:52:31.640  5622  5622 D BluetoothMapService: Received start request. Starting profile...
,09-14 06:52:31.640  5622  5622 D BluetoothMapService: start()
09-14 06:52:31.642  5622  5622 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-14 06:52:31.643  5622  5622 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-14 06:52:31.643  5622  5622 D BluetoothMapAppObserver: createReceiver()
09-14 06:52:31.644  5622  5622 D BluetoothMapAppObserver: initObservers()
09-14 06:52:31.644  5622  5622 D BluetoothMapAppObserver: getEnabledAccountItems()
09-14 06:52:31.647  5562  5562 D BluetoothMap: Proxy object connected
09-14 06:52:31.648  5562  5562 D MapProfile: Bluetooth service connected
09-14 06:52:31.648  5562  5562 D BluetoothMap: getConnectedDevices()
09-14 06:52:31.651  5622  5622 V SapService: SapBinder()
09-14 06:52:31.652  5622  5622 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
09-14 06:52:31.652  5622  5622 D SapService: Received start request. Starting profile...
,09-14 06:52:31.652  5622  5622 V SapService: start()
09-14 06:52:31.653  5622  5622 V BluetoothAdapterState: isTurningOff()=false
09-14 06:52:31.653  5622  5622 V BluetoothAdapterState: isTurningOn()=true
09-14 06:52:31.653  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:31.653  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:31.653  5622  5622 V BluetoothAdapterState: isTurningOff()=false
09-14 06:52:31.654  5622  5622 V BluetoothAdapterState: isTurningOn()=true
09-14 06:52:31.654  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:31.654  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 06:52:31.654  5622  5622 V BluetoothAdapterState: isTurningOff()=false
09-14 06:52:31.654  5622  5622 V BluetoothAdapterState: isTurningOn()=true
09-14 06:52:31.654  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:31.654  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:31.654  5622  5622 V BluetoothAdapterState: isTurningOff()=false
,09-14 06:52:31.654  5622  5622 V BluetoothAdapterState: isTurningOn()=true
09-14 06:52:31.654  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:31.655  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:31.655  5622  5622 V BluetoothAdapterState: isTurningOff()=false
,09-14 06:52:31.655  5622  5622 V BluetoothAdapterState: isTurningOn()=true
09-14 06:52:31.655  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:31.655  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:31.656  5622  5622 V BluetoothAdapterState: isTurningOff()=false
09-14 06:52:31.656  5622  5622 V BluetoothAdapterState: isTurningOn()=true
09-14 06:52:31.656  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:31.656  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:31.656  5622  5622 V BluetoothAdapterState: isTurningOff()=false
09-14 06:52:31.656  5622  5622 V BluetoothAdapterState: isTurningOn()=true
09-14 06:52:31.656  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 06:52:31.656  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:31.656  5622  5755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-14 06:52:31.657  5622  5755 D BluetoothAdapterProperties: ScanMode =  20
09-14 06:52:31.657  5622  5755 D BluetoothAdapterProperties: State =  11
09-14 06:52:31.657  5562  5562 D BluetoothMap: Bluetooth is Not enabled
09-14 06:52:31.658  5622  5759 D BluetoothAdapterProperties: Scan Mode:21
09-14 06:52:31.659  5622  5759 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 06:52:31.659  5622  5755 D BluetoothAdapterProperties: Setting state to 12
09-14 06:52:31.659  5622  5755 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-14 06:52:31.659  5622  5755 I BluetoothAdapterState: Entering OnState
09-14 06:52:31.660  5562  5575 D BluetoothPan: onBluetoothStateChange on: true
09-14 06:52:31.661  3129  3143 D BluetoothPan: onBluetoothStateChange on: true
,09-14 06:52:31.662  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:31.662  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:31.662  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:31.662  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:31.662  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:52:31.662  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:31.662  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:31.662  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:52:31.663   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-14 06:52:31.663  3129  3129 D BluetoothPan: BluetoothPAN Proxy object connected
09-14 06:52:31.663  3129  3129 D PanProfile: Bluetooth service connected
09-14 06:52:31.663  5562  5574 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 06:52:31.664  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:31.664   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 06:52:31.664   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:52:31.665  3129  5504 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:52:31.665   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:52:31.665   926   926 D BluetoothA2dp: Proxy object connected
09-14 06:52:31.665  3129  3491 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-14 06:52:31.667  5562  5575 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-14 06:52:31.667  3129  3129 D BluetoothInputDevice: Proxy object connected
09-14 06:52:31.667  3129  3129 D HidProfile: Bluetooth service connected
09-14 06:52:31.667  5562  5574 D BluetoothMap: onBluetoothStateChange: up=true
09-14 06:52:31.667  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:31.667  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:31.667  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:31.667  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:31.667  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:52:31.667  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:31.667  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:31.667  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:31.668  3129  3141 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 06:52:31.669  3129  5504 D BluetoothMap: onBluetoothStateChange: up=true
,09-14 06:52:31.669  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:52:31.670  3129  3129 D BluetoothMap: Proxy object connected
09-14 06:52:31.671  3129  3129 D MapProfile: Bluetooth service connected
09-14 06:52:31.671  3129  3129 D BluetoothMap: getConnectedDevices()
09-14 06:52:31.671  3129  3141 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 06:52:31.672  3129  3129 D BluetoothA2dp: Proxy object connected
09-14 06:52:31.672  3523  3802 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:52:31.673  5622  5622 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-14 06:52:31.673  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:31.673  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:31.673  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:31.673  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:31.673  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:52:31.673  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:31.673  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:31.673  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:31.673  5622  5622 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-14 06:52:31.674   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
09-14 06:52:31.676  5622  5622 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:52:31.676  5562  5562 D LocalBluetoothProfileManager: Adding local A2DP profile
09-14 06:52:31.676  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:31.678  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:31.678  5622  5622 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:52:31.680  5562  5562 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-14 06:52:31.680  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:31.681  5622  5622 D ObexServerSockets: Succeed to create listening sockets 
09-14 06:52:31.681  5622  5622 D ObexServerSockets0: startAccept()
,09-14 06:52:31.681  5622  5622 D ObexServerSockets0: prepareForNewConnect()
09-14 06:52:31.681  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:31.683  5622  5622 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-14 06:52:31.683  5622  5622 D BluetoothSdpJni: SDP Create record success - handle: 0
09-14 06:52:31.684  5622  5622 D BluetoothMapService: onReceive
09-14 06:52:31.684  5622  5781 D ObexServerSockets0: Accepting socket connection...
09-14 06:52:31.684  5622  5622 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 06:52:31.684  5622  5622 D BluetoothMapService: STATE_ON
09-14 06:52:31.684  5622  5782 D ObexServerSockets0: Accepting socket connection...
09-14 06:52:31.686  5622  5783 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:52:31.687  5622  5783 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-14 06:52:31.687  5622  5783 D BluetoothSdpJni: SDP Create record success - handle: 1
09-14 06:52:31.687  5562  5562 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-14 06:52:31.690  5562  5562 D BluetoothA2dp: Proxy object connected
,09-14 06:52:31.695  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:52:31.696  5562  5562 D DockEventReceiver: finishStartingService: stopping service
,09-14 06:52:31.702  5562  5562 D BluetoothPbap: Proxy object connected
,09-14 06:52:31.703  5562  5562 D PbapServerProfile: Bluetooth service connected
,09-14 06:52:31.706  3129  3129 D BluetoothPbap: Proxy object connected
09-14 06:52:31.706  3129  3129 D PbapServerProfile: Bluetooth service connected
,09-14 06:52:31.708  5622  5622 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-14 06:52:31.708  5622  5622 D ObexServerSockets0: prepareForNewConnect()
09-14 06:52:31.711  5622  5787 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 06:52:31.722  5622  5791 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 06:52:31.723  5622  5791 I BtOppRfcommListener: Accept thread started.
,09-14 06:52:31.764   926   926 D BluetoothHeadset: Proxy object connected
,09-14 06:52:31.764  3523  3539 D BluetoothHeadset: Proxy object connected
,09-14 06:52:31.765   926   926 D BluetoothHeadset: Proxy object connected
,09-14 06:52:31.765   926   943 D BluetoothHeadset: Proxy object connected
,09-14 06:52:31.765  3129  5504 D BluetoothHeadset: Proxy object connected
,09-14 06:52:31.765  3129  3143 D BluetoothHeadset: Proxy object connected
09-14 06:52:31.766  3129  3129 D HeadsetProfile: Bluetooth service connected
,09-14 06:52:31.766   926   926 D BluetoothHeadset: Proxy object connected
09-14 06:52:31.766   926   943 D BluetoothHeadset: Proxy object connected
,09-14 06:52:31.769  3129  3129 D HeadsetProfile: Bluetooth service connected
,09-14 06:52:31.773  3523  3546 D BluetoothHeadset: Proxy object connected
,09-14 06:52:31.783  5562  5575 D BluetoothHeadset: Proxy object connected
,09-14 06:52:31.784  5562  5562 D HeadsetProfile: Bluetooth service connected
,09-14 06:52:33.122   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:33.499   926  2992 D ConnectivityService: handlePromptUnvalidated 101
,09-14 06:52:34.123   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:35.124   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:35.710  5622  5755 D BluetoothAdapterState: Current state: ON, message: 23
,09-14 06:52:35.710  5622  5755 D BluetoothAdapterProperties: Setting state to 13
09-14 06:52:35.710  5622  5755 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-14 06:52:35.711  5622  5755 D BluetoothAdapterProperties: onBluetoothDisable()
,09-14 06:52:35.714  5622  5755 I BluetoothAdapterState: Entering PendingCommandState
,09-14 06:52:35.716  5622  5759 D BluetoothAdapterProperties: Scan Mode:20
,09-14 06:52:35.716  5622  5755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-14 06:52:35.719  5622  5622 D BluetoothMapService: onReceive
09-14 06:52:35.719  5622  5622 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 06:52:35.719  5622  5622 D BluetoothMapService: STATE_TURNING_OFF
,09-14 06:52:35.720  5622  5622 D BluetoothMapService: MAP Service closeService in
09-14 06:52:35.720  5622  5622 D BluetoothMapMasInstance0: MAP Service shutdown
,09-14 06:52:35.720  5622  5622 D ObexServerSockets0: shutdown(block = true)
09-14 06:52:35.721  5622  5622 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 06:52:35.721  5622  5622 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-14 06:52:35.721  5622  5781 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-14 06:52:35.721  5622  5782 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-14 06:52:35.723  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:52:35.723  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:35.723  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:35.723  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:35.723  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:35.723  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:35.723  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:35.723  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:35.723  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:35.723  5622  5768 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-14 06:52:35.726  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:35.726  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:52:35.727  5562  5562 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-14 06:52:35.733  5622  5622 I BtOppRfcommListener: stopping Accept Thread
09-14 06:52:35.734  5622  5791 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 06:52:35.735  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:35.735  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:35.735  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:35.735  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:35.735  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:35.735  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:35.735  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:35.735  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:35.735  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:35.736  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:35.736  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:52:35.740  5622  5791 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-14 06:52:35.741  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:35.741  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:35.741  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:35.741  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:35.741  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:35.741  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:52:35.741  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:35.741  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:35.741  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:35.742  5505  5505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:52:35.742  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:52:35.743  5622  5622 D HeadsetService: Received stop request...Stopping profile...
09-14 06:52:35.744  5562  5562 D DockEventReceiver: finishStartingService: stopping service
09-14 06:52:35.745  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:35.746  5562  5575 D BluetoothHeadset: Proxy object disconnected
09-14 06:52:35.746   926   926 D BluetoothHeadset: Proxy object disconnected
09-14 06:52:35.746  3523  3539 D BluetoothHeadset: Proxy object disconnected
09-14 06:52:35.747  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:35.747   926   926 D BluetoothHeadset: Proxy object disconnected
09-14 06:52:35.747  5622  5622 D A2dpService: Received stop request...Stopping profile...
09-14 06:52:35.747  3129  3141 D BluetoothHeadset: Proxy object disconnected
09-14 06:52:35.747  5622  5775 D A2dpStateMachine: Exit Disconnected: -1
09-14 06:52:35.747   926   926 D BluetoothHeadset: Proxy object disconnected
09-14 06:52:35.748  5562  5562 D HeadsetProfile: Bluetooth service disconnected
09-14 06:52:35.748  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:35.748   926   926 D BluetoothA2dp: Proxy object disconnected
,09-14 06:52:35.749  5562  5562 D BluetoothA2dp: Proxy object disconnected
09-14 06:52:35.749  5622  5622 D HidService: Received stop request...Stopping profile...
09-14 06:52:35.750  5622  5622 D HidService: Stopping Bluetooth HidService
09-14 06:52:35.751  5562  5562 D BluetoothInputDevice: Proxy object disconnected
09-14 06:52:35.751  5562  5562 D HidProfile: Bluetooth service disconnected
09-14 06:52:35.752  3129  3129 D HeadsetProfile: Bluetooth service disconnected
09-14 06:52:35.752  3129  3129 D BluetoothA2dp: Proxy object disconnected
,09-14 06:52:35.753  5622  5622 D HealthService: Received stop request...Stopping profile...
09-14 06:52:35.753  3129  3129 D BluetoothInputDevice: Proxy object disconnected
09-14 06:52:35.753  3129  3129 D HidProfile: Bluetooth service disconnected
,09-14 06:52:35.756  5622  5622 D PanService: Received stop request...Stopping profile...
,09-14 06:52:35.758  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:52:35.759  3129  3129 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-14 06:52:35.759  5562  5562 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-14 06:52:35.759  3129  3129 D PanProfile: Bluetooth service disconnected
09-14 06:52:35.759  5562  5562 D PanProfile: Bluetooth service disconnected
09-14 06:52:35.759  5622  5622 D BluetoothMapService: Received stop request...Stopping profile...
09-14 06:52:35.759  5622  5622 D BluetoothMapService: stop()
09-14 06:52:35.760  5622  5622 D BluetoothMapAppObserver: deinitObservers()
09-14 06:52:35.760  5622  5622 D BluetoothMapAppObserver: removeReceiver()
09-14 06:52:35.761  3129  3129 D BluetoothMap: Proxy object disconnected
09-14 06:52:35.761  3129  3129 D MapProfile: Bluetooth service disconnected
09-14 06:52:35.761  5562  5562 D BluetoothMap: Proxy object disconnected
,09-14 06:52:35.761  5562  5562 D MapProfile: Bluetooth service disconnected
09-14 06:52:35.763  5622  5622 D SapService: Received stop request...Stopping profile...
09-14 06:52:35.763  5622  5622 V SapService: stop()
,09-14 06:52:35.765  5622  5622 V BluetoothAdapterState: isTurningOff()=true
,09-14 06:52:35.765  5622  5622 V BluetoothAdapterState: isTurningOn()=false
09-14 06:52:35.765  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:35.765  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:35.766  5622  5622 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-14 06:52:35.766  5622  5622 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-14 06:52:35.766  5622  5766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:52:35.766  5622  5622 V BluetoothAdapterState: isTurningOff()=true
09-14 06:52:35.766  5622  5766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:52:35.766  5622  5622 V BluetoothAdapterState: isTurningOn()=false
09-14 06:52:35.766  5622  5766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:52:35.766  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 06:52:35.767  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:35.767  5622  5759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-14 06:52:35.767  5622  5759 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-14 06:52:35.768  5622  5766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:52:35.768  5622  5622 V BluetoothAdapterState: isTurningOff()=true
09-14 06:52:35.768  5622  5622 V BluetoothAdapterState: isTurningOn()=false
09-14 06:52:35.768  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:35.768  5622  5766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:52:35.768  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:35.768  5622  5766 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 06:52:35.768  5622  5766 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-14 06:52:35.768  5622  5622 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-14 06:52:35.768  5622  5766 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 06:52:35.768  5622  5622 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-14 06:52:35.768  5622  5766 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 06:52:35.768  5622  5759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-14 06:52:35.769  5622  5622 V BluetoothAdapterState: isTurningOff()=true
09-14 06:52:35.769  5622  5622 V BluetoothAdapterState: isTurningOn()=false
09-14 06:52:35.769  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:35.769  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:35.769  5622  5759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-14 06:52:35.769  5622  5622 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-14 06:52:35.769  5622  5759 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-14 06:52:35.770  5622  5622 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-14 06:52:35.772  3129  3129 D BluetoothPbap: Proxy object disconnected
09-14 06:52:35.772  3129  3129 D PbapServerProfile: Bluetooth service disconnected
09-14 06:52:35.772  5562  5562 D BluetoothPbap: Proxy object disconnected
09-14 06:52:35.772  5562  5562 D PbapServerProfile: Bluetooth service disconnected
09-14 06:52:35.772  5622  5622 V BluetoothAdapterState: isTurningOff()=true
09-14 06:52:35.772  5622  5622 V BluetoothAdapterState: isTurningOn()=false
09-14 06:52:35.772  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 06:52:35.772  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 06:52:35.773  5622  5622 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-14 06:52:35.773  5622  5622 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-14 06:52:35.774  5622  5622 D BluetoothMapService: MAP Service closeService in
09-14 06:52:35.774  5622  5622 V BluetoothAdapterState: isTurningOff()=true
09-14 06:52:35.774  5622  5622 V BluetoothAdapterState: isTurningOn()=false
09-14 06:52:35.774  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:35.774  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:35.774  5622  5622 D BluetoothMapService: cleanup()
09-14 06:52:35.774  5622  5622 D BluetoothMapService: MAP Service closeService in
09-14 06:52:35.775  5622  5622 V BluetoothAdapterState: isTurningOff()=true
09-14 06:52:35.775  5622  5622 V BluetoothAdapterState: isTurningOn()=false
09-14 06:52:35.775  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:35.775  5622  5622 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 06:52:35.775  5622  5755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-14 06:52:35.776  5622  5755 D BluetoothAdapterProperties: Setting state to 15
09-14 06:52:35.776  5622  5755 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-14 06:52:35.776  5622  5755 I BluetoothAdapterState: Entering BleOnState
,09-14 06:52:35.776  5562  5574 D BluetoothPan: onBluetoothStateChange on: false
09-14 06:52:35.778  3129  5504 D BluetoothPan: onBluetoothStateChange on: false
09-14 06:52:35.778   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:52:35.778  5562  5575 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 06:52:35.779  5562  5574 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 06:52:35.779   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 06:52:35.779   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:52:35.780  3129  3141 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-14 06:52:35.780   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:52:35.780  3129  3491 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-14 06:52:35.781  5562  5575 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-14 06:52:35.782  5562  5574 D BluetoothMap: onBluetoothStateChange: up=false
,09-14 06:52:35.783  5562  5575 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:52:35.783  3129  3143 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 06:52:35.783  3129  5504 D BluetoothMap: onBluetoothStateChange: up=false
09-14 06:52:35.784  3129  3141 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-14 06:52:35.784  3523  3546 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:52:35.785  5622  5755 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-14 06:52:35.785  5622  5755 D BluetoothAdapterProperties: Setting state to 16
09-14 06:52:35.785  5622  5755 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-14 06:52:35.786  5622  5755 D BluetoothAdapterProperties: onBleDisable
,09-14 06:52:35.786  5622  5755 I BluetoothAdapterState: Entering PendingCommandState
09-14 06:52:35.786  5622  5756 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-14 06:52:35.788  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:35.788  5622  5766 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-14 06:52:35.788  5622  5766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-14 06:52:35.789  5622  5759 D BluetoothAdapterProperties: Scan Mode:20
09-14 06:52:35.789  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:35.790  5562  5562 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-14 06:52:35.792  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:35.795  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:35.796  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:35.797  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:35.799  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:52:35.805  5562  5562 D DockEventReceiver: finishStartingService: stopping service
,09-14 06:52:36.002  5622  5759 I bt_hci  : shut_down
,09-14 06:52:36.006  5622  5763 D bt_hwcfg: hw_epilog_process
,09-14 06:52:36.007  5622  5763 I bt_vendor: low_power_mode_cb
,09-14 06:52:36.010  5622  5763 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-14 06:52:36.010  5622  5763 I bt_vendor: epilog_cb
09-14 06:52:36.010  5622  5763 I bt_hci  : epilog_finished_callback
,09-14 06:52:36.015  5622  5759 I bt_hci_h4: hal_close
,09-14 06:52:36.016  5622  5759 I bt_userial_vendor: device fd = 54 close
,09-14 06:52:36.125   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:36.132  5622  5756 D bt_stack_manager: event_shut_down_stack finished.
,09-14 06:52:36.133  5622  5755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-14 06:52:36.138  5622  5755 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-14 06:52:36.138  5622  5622 D BtGatt.DebugUtils: handleDebugAction() action=null
09-14 06:52:36.139  5622  5622 D BtGatt.GattService: Received stop request...Stopping profile...
09-14 06:52:36.140  5622  5622 D BtGatt.GattService: stop()
09-14 06:52:36.140  5622  5622 D BtGatt.AdvertiseManager: advertise clients cleared
,09-14 06:52:36.145  5622  5622 V BluetoothAdapterState: isTurningOff()=false
09-14 06:52:36.145  5622  5622 V BluetoothAdapterState: isTurningOn()=false
,09-14 06:52:36.145  5622  5622 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:36.146  5622  5622 V BluetoothAdapterState: isBleTurningOff()=true
09-14 06:52:36.146  5622  5755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-14 06:52:36.147  5622  5755 D BluetoothAdapterProperties: Setting state to 10
09-14 06:52:36.147  5622  5755 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-14 06:52:36.148  5622  5755 I BluetoothAdapterState: Entering OffState
09-14 06:52:36.149   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-14 06:52:36.165  5622  5622 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-14 06:52:36.165  5622  5622 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-14 06:52:36.165  5622  5622 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-14 06:52:36.168  5622  5756 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-14 06:52:36.176  5622  5622 I art     : System.exit called, status: 0
,09-14 06:52:36.176  5622  5622 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-14 06:52:36.211   926   937 I ActivityManager: Process com.android.bluetooth (pid 5622) has died
,09-14 06:52:37.126   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:38.127   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 06:52:40.707  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 06:52:40.707  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:40.713  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:52:40.713  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d581c9c removed from the list
09-14 06:52:40.713  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:40.713  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:40.714  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:40.716  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:52:40.716  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@edaa7a added. We now have 4 listener(s)
09-14 06:52:40.716  5505  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:52:40.719  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:40.719  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@edaa7a removed from the list
,09-14 06:52:40.719  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:40.719  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:40.719  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:52:40.721  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:52:40.721  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37ef22b added. We now have 4 listener(s)
,09-14 06:52:40.722  5505  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:52:45.733  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:45.766   926   943 I ActivityManager: Start proc 5801:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-14 06:52:45.855  5801  5801 D AdapterServiceConfig: Adding HeadsetService
,09-14 06:52:45.855  5801  5801 D AdapterServiceConfig: Adding A2dpService
09-14 06:52:45.856  5801  5801 D AdapterServiceConfig: Adding HidService
09-14 06:52:45.856  5801  5801 D AdapterServiceConfig: Adding HealthService
09-14 06:52:45.856  5801  5801 D AdapterServiceConfig: Adding PanService
09-14 06:52:45.856  5801  5801 D AdapterServiceConfig: Adding GattService
09-14 06:52:45.856  5801  5801 D AdapterServiceConfig: Adding BluetoothMapService
09-14 06:52:45.857  5801  5801 D AdapterServiceConfig: Adding SapService
,09-14 06:52:45.870   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fe1216:true
,09-14 06:52:45.871  5801  5801 D BluetoothAdapterState: make() - Creating AdapterState
,09-14 06:52:45.874  5801  5801 I bt_bluedroid: init
,09-14 06:52:45.876  5801  5813 I BluetoothAdapterState: Entering OffState
,09-14 06:52:45.878  5801  5814 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-14 06:52:45.879  5801  5814 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-14 06:52:45.879  5801  5814 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-14 06:52:45.879  5801  5814 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-14 06:52:45.880  5801  5801 I bt_bluedroid: get_profile_interface socket
,09-14 06:52:45.882  5801  5817 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-14 06:52:45.882  5801  5801 I bt_bluedroid: get_profile_interface sdp
,09-14 06:52:45.883  5801  5817 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-14 06:52:45.888  5801  5812 I bt_bluedroid: config_hci_snoop_log
09-14 06:52:45.889   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-14 06:52:45.894  5801  5813 D BluetoothAdapterState: Current state: OFF, message: 0
,09-14 06:52:45.894  5801  5813 D BluetoothAdapterProperties: Setting state to 14
09-14 06:52:45.894  5801  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-14 06:52:45.896  5801  5813 D BluetoothBondStateMachine: make
,09-14 06:52:45.898  5801  5818 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-14 06:52:45.901  5801  5813 I BluetoothAdapterState: Entering PendingCommandState
,09-14 06:52:45.902  5801  5801 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-14 06:52:45.904  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
,09-14 06:52:45.905  5801  5801 D BtGatt.DebugUtils: handleDebugAction() action=null
09-14 06:52:45.906  5801  5801 D BtGatt.GattService: Received start request. Starting profile...
09-14 06:52:45.906  5801  5801 D BtGatt.GattService: start()
,09-14 06:52:45.906  5801  5801 I bt_bluedroid: get_profile_interface gatt
09-14 06:52:45.907  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
09-14 06:52:45.907  5801  5801 D BtGatt.AdvertiseManager: advertise manager created
,09-14 06:52:45.914  5801  5801 V BluetoothAdapterState: isTurningOff()=false
,09-14 06:52:45.915  5801  5801 V BluetoothAdapterState: isTurningOn()=false
09-14 06:52:45.915  5801  5801 V BluetoothAdapterState: isBleTurningOn()=true
09-14 06:52:45.915  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:45.916  5801  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-14 06:52:45.917  5801  5813 I bt_bluedroid: bt_bluedroid
09-14 06:52:45.917  5801  5814 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-14 06:52:45.917  5801  5814 I bt_hci  : start_up
,09-14 06:52:45.923  5801  5814 I bt_vendor: alloc value 0xf41a5871
,09-14 06:52:45.923  5801  5814 I bt_vendor: init
09-14 06:52:45.923  5801  5814 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-14 06:52:45.923  5801  5814 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-14 06:52:46.031  5801  5814 D bt_hci  : start_up starting async portion
,09-14 06:52:46.032  5801  5821 I bt_hci  : event_finish_startup
,09-14 06:52:46.032  5801  5821 I bt_hci_h4: hal_open
09-14 06:52:46.032  5801  5821 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-14 06:52:46.030  5822  5822 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-14 06:52:46.035  5801  5821 I bt_userial_vendor: device fd = 54 open
,09-14 06:52:46.051  5801  5821 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 06:52:46.055  5801  5821 D bt_hwcfg: Chipset BCM4358A3
,09-14 06:52:46.055  5801  5821 D bt_hwcfg: Target name = [BCM4358A3]
09-14 06:52:46.055  5801  5821 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-14 06:52:46.586  5801  5821 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-14 06:52:46.587  5801  5821 D bt_hwcfg: Settlement delay -- 100 ms
09-14 06:52:46.587  5801  5821 I bt_hwcfg: Setting fw settlement delay to 100 
,09-14 06:52:46.721  5801  5821 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 06:52:46.722  5801  5821 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-14 06:52:46.724  5801  5821 I bt_hwcfg: vendor lib fwcfg completed
,09-14 06:52:46.724  5801  5821 I bt_vendor: firmware callback
,09-14 06:52:46.724  5801  5821 I bt_hci  : firmware_config_callback
,09-14 06:52:46.735  5801  5824 I bt_btu  : btu_task pending for preload complete event
,09-14 06:52:46.735  5801  5824 I bt_btu_task: Bluetooth chip preload is complete
09-14 06:52:46.735  5801  5824 I bt_btu  : btu_task received preload complete event
,09-14 06:52:46.741  5801  5824 I         : BTE_InitTraceLevels -- TRC_HCI
,09-14 06:52:46.742  5801  5824 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-14 06:52:46.742  5801  5824 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-14 06:52:46.742  5801  5824 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-14 06:52:46.742  5801  5824 I         : BTE_InitTraceLevels -- TRC_AVRC
09-14 06:52:46.742  5801  5824 I         : BTE_InitTraceLevels -- TRC_A2D
09-14 06:52:46.742  5801  5824 I         : BTE_InitTraceLevels -- TRC_BNEP
09-14 06:52:46.742  5801  5824 I         : BTE_InitTraceLevels -- TRC_BTM
09-14 06:52:46.743  5801  5824 I         : BTE_InitTraceLevels -- TRC_GAP
,09-14 06:52:46.743  5801  5824 I         : BTE_InitTraceLevels -- TRC_PAN
09-14 06:52:46.743  5801  5824 I         : BTE_InitTraceLevels -- TRC_SDP
09-14 06:52:46.743  5801  5824 I         : BTE_InitTraceLevels -- TRC_GATT
,09-14 06:52:46.743  5801  5824 I         : BTE_InitTraceLevels -- TRC_SMP
09-14 06:52:46.743  5801  5824 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-14 06:52:46.743  5801  5824 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-14 06:52:46.844  5801  5824 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4123549
09-14 06:52:46.844  5801  5824 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4123549 
,09-14 06:52:46.868  5801  5817 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-14 06:52:46.870  5801  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-14 06:52:46.871  5801  5817 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-14 06:52:46.873  5801  5817 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-14 06:52:46.877  5801  5817 D BluetoothAdapterProperties: Scan Mode:20
,09-14 06:52:46.877  5801  5817 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 06:52:46.878  5801  5817 D bt_hci  : do_postload posting postload work item
,09-14 06:52:46.878  5801  5821 I bt_hci  : event_postload
09-14 06:52:46.878  5801  5821 I bt_vendor: sco_config_cb
09-14 06:52:46.878  5801  5821 I bt_hci  : sco_config_callback postload finished.
09-14 06:52:46.882  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:46.886  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:46.887  5801  5821 I bt_vendor: low_power_mode_cb
,09-14 06:52:46.888  5801  5817 D bt_bte_conf: Device ID record 1 : primary
09-14 06:52:46.888  5801  5817 D bt_bte_conf:   vendorId            = 000f
09-14 06:52:46.888  5801  5817 D bt_bte_conf:   vendorIdSource      = 0001
09-14 06:52:46.888  5801  5817 D bt_bte_conf:   product             = 1200
09-14 06:52:46.888  5801  5817 D bt_bte_conf:   version             = 1436
09-14 06:52:46.888  5801  5817 D bt_bte_conf:   clientExecutableURL = 
09-14 06:52:46.888  5801  5817 D bt_bte_conf:   serviceDescription  = 
09-14 06:52:46.888  5801  5817 D bt_bte_conf:   documentationURL    = 
09-14 06:52:46.889  5801  5817 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-14 06:52:46.889  5801  5814 D bt_stack_manager: event_start_up_stack finished
,09-14 06:52:46.889  5801  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-14 06:52:46.890  5801  5813 D BluetoothAdapterProperties: Setting state to 15
09-14 06:52:46.890  5801  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-14 06:52:46.893  5801  5813 I BluetoothAdapterState: Entering BleOnState
,09-14 06:52:46.896  5801  5813 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-14 06:52:46.896  5801  5813 D BluetoothAdapterProperties: Setting state to 11
,09-14 06:52:46.896  5801  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-14 06:52:46.902  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
,09-14 06:52:46.906  5801  5801 D HeadsetService: Received start request. Starting profile...
09-14 06:52:46.909  5801  5801 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-14 06:52:46.910  5801  5801 D HeadsetStateMachine: make
09-14 06:52:46.913  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:46.916  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:46.921  5801  5801 D HeadsetStateMachine: max_hf_connections = 1
09-14 06:52:46.921  5801  5801 I bt_bluedroid: get_profile_interface handsfree
09-14 06:52:46.922  5801  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-14 06:52:46.922  5801  5817 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-14 06:52:46.926  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
,09-14 06:52:46.929  5801  5813 I BluetoothAdapterState: Entering PendingCommandState
,09-14 06:52:46.930  5801  5801 D A2dpService: Received start request. Starting profile...
09-14 06:52:46.931  5801  5801 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-14 06:52:46.931  5801  5801 I bt_bluedroid: get_profile_interface avrcp
,09-14 06:52:46.938  5801  5801 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-14 06:52:46.938  5801  5801 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-14 06:52:46.939  5801  5801 D A2dpStateMachine: make
,09-14 06:52:46.940  5801  5801 I bt_bluedroid: get_profile_interface a2dp
,09-14 06:52:46.941  5801  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-14 06:52:46.942  5801  5831 D A2dpStateMachine: Enter Disconnected: -2
09-14 06:52:46.942  5801  5801 I BluetoothHidServiceJni: classInitNative: succeeds
,09-14 06:52:46.943  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
09-14 06:52:46.944  5801  5801 D HidService: Received start request. Starting profile...
09-14 06:52:46.944  5801  5801 I bt_bluedroid: get_profile_interface hidhost
09-14 06:52:46.944  5801  5801 D HidService: setHidService(): set to: null
09-14 06:52:46.946  5801  5817 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf410456d
09-14 06:52:46.946  5801  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-14 06:52:46.948  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:52:46.948  5801  5801 I BluetoothHealthServiceJni: classInitNative: succeeds
09-14 06:52:46.949  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
09-14 06:52:46.950  5801  5801 D HealthService: Received start request. Starting profile...
,09-14 06:52:46.951  5801  5801 I bt_bluedroid: get_profile_interface health
,09-14 06:52:46.952  5801  5801 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-14 06:52:46.953  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
09-14 06:52:46.954  5801  5801 D PanService: Received start request. Starting profile...
09-14 06:52:46.954  5801  5801 D BluetoothPanServiceJni: initializeNative(L110): pan
09-14 06:52:46.954  5801  5801 I bt_bluedroid: get_profile_interface pan
09-14 06:52:46.954  5801  5817 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-14 06:52:46.955  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-14 06:52:46.955  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-14 06:52:46.955  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:46.955  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:46.957  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
09-14 06:52:46.958  5801  5801 D BluetoothMapService: Received start request. Starting profile...
09-14 06:52:46.958  5801  5801 D BluetoothMapService: start()
09-14 06:52:46.960  5801  5801 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-14 06:52:46.961  5801  5801 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-14 06:52:46.961  5801  5801 D BluetoothMapAppObserver: createReceiver()
,09-14 06:52:46.962  5801  5801 D BluetoothMapAppObserver: initObservers()
09-14 06:52:46.962  5801  5801 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-14 06:52:46.968  5801  5801 V SapService: SapBinder()
09-14 06:52:46.968  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
09-14 06:52:46.969  5801  5801 D SapService: Received start request. Starting profile...
09-14 06:52:46.969  5801  5801 V SapService: start()
09-14 06:52:46.970  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-14 06:52:46.970  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-14 06:52:46.970  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:46.970  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:46.970  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-14 06:52:46.970  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-14 06:52:46.970  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:46.970  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:46.971  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-14 06:52:46.971  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-14 06:52:46.971  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:46.971  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 06:52:46.971  5801  5801 V BluetoothAdapterState: isTurningOff()=false
,09-14 06:52:46.971  5801  5801 V BluetoothAdapterState: isTurningOn()=true
,09-14 06:52:46.972  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:46.972  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:46.972  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-14 06:52:46.972  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-14 06:52:46.972  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:46.972  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:46.973  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-14 06:52:46.974  5801  5801 V BluetoothAdapterState: isTurningOn()=true
,09-14 06:52:46.974  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:52:46.974  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:52:46.975  5801  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-14 06:52:46.975  5801  5813 D BluetoothAdapterProperties: ScanMode =  20
09-14 06:52:46.975  5801  5813 D BluetoothAdapterProperties: State =  11
09-14 06:52:46.975  5801  5813 D BluetoothAdapterProperties: Setting state to 12
09-14 06:52:46.975  5801  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-14 06:52:46.976  5801  5813 I BluetoothAdapterState: Entering OnState
,09-14 06:52:46.976  5562  5575 D BluetoothPan: onBluetoothStateChange on: true
09-14 06:52:46.976  5801  5817 D BluetoothAdapterProperties: Scan Mode:21
09-14 06:52:46.977  5801  5817 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 06:52:46.978  3129  3143 D BluetoothPan: onBluetoothStateChange on: true
,09-14 06:52:46.980   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-14 06:52:46.980  3129  3129 D BluetoothPan: BluetoothPAN Proxy object connected
09-14 06:52:46.980  3129  3129 D PanProfile: Bluetooth service connected
,09-14 06:52:46.980  5562  5575 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 06:52:46.982  5562  5574 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 06:52:46.983  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:46.983  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:46.983  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:46.983  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:46.983  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:52:46.983  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:46.983  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:46.983  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:46.984   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 06:52:46.984   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:52:46.985  5562  5562 D BluetoothPan: BluetoothPAN Proxy object connected
09-14 06:52:46.985  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:46.985  5562  5562 D PanProfile: Bluetooth service connected
09-14 06:52:46.985  5562  5562 D BluetoothA2dp: Proxy object connected
,09-14 06:52:46.985   926   926 D BluetoothA2dp: Proxy object connected
09-14 06:52:46.985  3129  5504 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:52:46.986   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:52:46.986  3129  3491 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-14 06:52:46.988  5562  5574 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-14 06:52:46.988  5801  5801 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-14 06:52:46.989  5801  5801 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-14 06:52:46.989  5562  5575 D BluetoothMap: onBluetoothStateChange: up=true
09-14 06:52:46.990  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:46.990  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:46.990  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:46.990  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:46.990  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:52:46.990  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:46.990  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:46.990  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:46.991  5801  5801 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:52:46.991  5562  5574 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:52:46.992  3129  3143 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 06:52:46.993  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:46.993  3129  3141 D BluetoothMap: onBluetoothStateChange: up=true
09-14 06:52:46.995  3129  5504 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 06:52:46.995  5801  5801 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:52:46.996  3129  3129 D BluetoothA2dp: Proxy object connected
09-14 06:52:46.996  3523  3539 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:52:46.997  5801  5801 D ObexServerSockets: Succeed to create listening sockets 
09-14 06:52:46.997  5801  5801 D ObexServerSockets0: startAccept()
09-14 06:52:46.997  5801  5801 D ObexServerSockets0: prepareForNewConnect()
,09-14 06:52:46.999   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
,09-14 06:52:47.000  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:52:47.001  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:47.002  5801  5801 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-14 06:52:47.002  5801  5801 D BluetoothSdpJni: SDP Create record success - handle: 0
09-14 06:52:47.003  5801  5839 D ObexServerSockets0: Accepting socket connection...
09-14 06:52:47.004  5801  5840 D ObexServerSockets0: Accepting socket connection...
09-14 06:52:47.004  3129  3129 D BluetoothInputDevice: Proxy object connected
09-14 06:52:47.004  3129  3129 D HidProfile: Bluetooth service connected
09-14 06:52:47.004  5562  5562 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-14 06:52:47.006  5801  5801 D BluetoothMapService: onReceive
09-14 06:52:47.007  5801  5801 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-14 06:52:47.007  5801  5801 D BluetoothMapService: STATE_ON
09-14 06:52:47.007  5562  5562 D BluetoothInputDevice: Proxy object connected
09-14 06:52:47.007  5562  5562 D HidProfile: Bluetooth service connected
09-14 06:52:47.007  3129  3129 D BluetoothMap: Proxy object connected
09-14 06:52:47.007  3129  3129 D MapProfile: Bluetooth service connected
09-14 06:52:47.007  3129  3129 D BluetoothMap: getConnectedDevices()
,09-14 06:52:47.009  5562  5562 D BluetoothMap: Proxy object connected
09-14 06:52:47.009  5562  5562 D MapProfile: Bluetooth service connected
09-14 06:52:47.009  5562  5562 D BluetoothMap: getConnectedDevices()
,09-14 06:52:47.012  5801  5841 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 06:52:47.014  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:52:47.016  5562  5562 D DockEventReceiver: finishStartingService: stopping service
,09-14 06:52:47.017  5801  5841 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-14 06:52:47.017  5801  5841 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-14 06:52:47.022  5562  5562 D BluetoothPbap: Proxy object connected
,09-14 06:52:47.022  5562  5562 D PbapServerProfile: Bluetooth service connected
,09-14 06:52:47.029  5801  5846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 06:52:47.038  3129  3129 D BluetoothPbap: Proxy object connected
,09-14 06:52:47.038  3129  3129 D PbapServerProfile: Bluetooth service connected
,09-14 06:52:47.040  5801  5801 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-14 06:52:47.040  5801  5801 D ObexServerSockets0: prepareForNewConnect()
,09-14 06:52:47.044  5801  5850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 06:52:47.046  5801  5850 I BtOppRfcommListener: Accept thread started.
,09-14 06:52:47.082  5562  5574 D BluetoothHeadset: Proxy object connected
09-14 06:52:47.082   926   926 D BluetoothHeadset: Proxy object connected
09-14 06:52:47.083  3523  3546 D BluetoothHeadset: Proxy object connected
,09-14 06:52:47.083   926   926 D BluetoothHeadset: Proxy object connected
,09-14 06:52:47.083  3129  5504 D BluetoothHeadset: Proxy object connected
09-14 06:52:47.083   926   926 D BluetoothHeadset: Proxy object connected
09-14 06:52:47.083  3129  3129 D HeadsetProfile: Bluetooth service connected
,09-14 06:52:47.084   926   943 D BluetoothHeadset: Proxy object connected
,09-14 06:52:47.084  5562  5562 D HeadsetProfile: Bluetooth service connected
09-14 06:52:47.086  3129  3141 D BluetoothHeadset: Proxy object connected
,09-14 06:52:47.086   926   943 D BluetoothHeadset: Proxy object connected
09-14 06:52:47.087  3129  3129 D HeadsetProfile: Bluetooth service connected
,09-14 06:52:47.092  5562  5575 D BluetoothHeadset: Proxy object connected
,09-14 06:52:47.092  5562  5562 D HeadsetProfile: Bluetooth service connected
,09-14 06:52:47.096  3523  3802 D BluetoothHeadset: Proxy object connected
,09-14 06:52:50.750  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:50.750  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:50.750  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:50.750  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:52:50.750  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:52:50.750  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:50.750  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:50.750  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:52:50.757  5505  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:52:50.758  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:52:50.758  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37ef22b removed from the list
,09-14 06:52:50.758  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:52:50.759  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:52:50.759  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:52:50.763  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 06:52:50.764  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3186688 added. We now have 4 listener(s)
09-14 06:52:50.764  5505  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:52:50.768   926  3206 D WifiService: setWifiEnabled: false pid=5505, uid=10077
,09-14 06:52:50.768   926  3206 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 06:52:55.780  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:55.781   926  3423 D WifiService: setWifiEnabled: true pid=5505, uid=10077
09-14 06:52:55.781   926  3423 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 06:52:55.791   506   919 D SoftapController: Softap fwReload - Ok
,09-14 06:52:55.797   506   919 D CommandListener: Setting iface cfg
,09-14 06:52:55.797   506   919 D CommandListener: Trying to bring down wlan0
,09-14 06:52:55.799   506   919 D CommandListener: Clearing all IP addresses on wlan0
,09-14 06:52:55.805   926  2990 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-14 06:52:56.467   926  2990 D wifi    : set interface wlan0 flags (UP)
,09-14 06:52:56.474   926  2990 I WifiHAL : Initializing wifi
,09-14 06:52:56.474   926  2990 I WifiHAL : Creating socket
,09-14 06:52:56.476   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-14 06:52:56.480   926  2990 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-14 06:52:56.481   926  2990 D wifi    : Did set static halHandle = 0x7f8c88b300
09-14 06:52:56.481   926  2990 D wifi    : halHandle = 0x7f8c88b300, mVM = 0x7fa864d140, mCls = 0x1642
,09-14 06:52:56.482   926  2990 D wifi    : array field set
09-14 06:52:56.482   926  2990 I WifiNative-HAL: interface[0] = wlan0
09-14 06:52:56.485   926  5856 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547818615552
09-14 06:52:56.485   926  5856 D wifi    : waitForHalEvents called, vm = 0x7fa864d140, obj = 0x1642, env = 0x7f8cd5ca40
,09-14 06:52:56.532  5857  5857 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-14 06:52:56.551  5857  5857 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-14 06:52:56.585   926  2990 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-14 06:52:56.590  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:56.592  5857  5857 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-14 06:52:56.592  5857  5857 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-14 06:52:56.592  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:52:56.609   926  2990 D WifiConfigStore: Loading config and enabling all networks 
,09-14 06:52:56.613  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:56.613  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:56.613  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:56.613  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:56.613  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:52:56.613  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:56.613  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:56.613  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:56.615  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:52:56.619  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:52:56.619  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:52:56.619  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:52:56.619  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:52:56.619  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:52:56.619  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:52:56.619  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:52:56.619  5505  5505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:52:56.620   926  2990 D WifiConfigStore: loaded 0 passpoint configs
,09-14 06:52:56.620   926  2990 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-14 06:52:56.620  5505  5505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:52:56.621   926  2990 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-14 06:52:56.622   926  2990 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-14 06:52:56.622   926  2990 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
09-14 06:52:56.622   926  2990 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-14 06:52:56.625   926  2990 D WifiNative-HAL: Setting external_sim to 1
,09-14 06:52:56.626  4304  4304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 06:52:56.626   926  2990 D wifi    : setting dfs flag to true, 0x7f8d160b00
09-14 06:52:56.626   926  2990 D WifiStateMachine: Setting OUI to DA-A1-19
09-14 06:52:56.627   926  2990 D wifi    : setting scan oui 0x7f8d160b00
09-14 06:52:56.627   926  2990 D WifiHAL : Sending mac address OUI
,09-14 06:52:56.644   926  2990 E native  : do suspend true
,09-14 06:52:56.651   926  2990 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-14 06:52:56.651   506   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-14 06:52:56.651   926   926 D RttService: SCAN_AVAILABLE : 3
09-14 06:52:56.652   926  3095 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-14 06:52:56.652   506   919 D CommandListener: Setting iface cfg
,09-14 06:52:56.657   926  2963 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '96 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 96 Failed to set address (No such device)'
,09-14 06:52:56.657   926  2963 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-14 06:52:56.664   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=412360 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=7 mControllerEnergyUsed=26 }
,09-14 06:52:56.665   926  2963 D WifiNative-HAL: p2pGetDeviceAddress
09-14 06:52:56.665   926  2963 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-14 06:52:58.128   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:52:59.129   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:53:00.129   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:53:00.806  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:53:00.806  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:53:00.806  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:53:00.806  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:53:00.806  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:53:00.806  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:53:00.806  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:53:00.806  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:53:00.812  5505  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:53:00.813  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:53:00.813  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3186688 removed from the list
09-14 06:53:00.813  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 06:53:00.813  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:53:00.813  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:53:00.823  5505  5868 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-14 06:53:00.823  5505  5868 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-14 06:53:01.131   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:53:02.132   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:53:03.133   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 06:53:03.854  5505  5869 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-14 06:53:03.854  5505  5868 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-14 06:53:03.855  5505  5868 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-14 06:53:03.855  5505  5869 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-14 06:53:03.856  5505  5868 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 06:53:03.856  5505  5869 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 06:53:03.858  5505  5868 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 06:53:03.858  5505  5869 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 06:53:03.860  5505  5868 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-14 06:53:03.860  5505  5869 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-14 06:53:03.865  5505  5871 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: OutgoingSocketThread/Sender)
09-14 06:53:03.865  5505  5872 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: IncomingSocketThread/Sender)
,09-14 06:53:03.866  5505  5873 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: OutgoingSocketThread/Receiver)
,09-14 06:53:03.867  5505  5874 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: IncomingSocketThread/Receiver)
09-14 06:53:03.867  5505  5873 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 154, thread name: OutgoingSocketThread/Receiver)
09-14 06:53:03.867  5505  5873 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-14 06:53:03.868  5505  5873 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-14 06:53:03.869  5505  5874 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: IncomingSocketThread/Receiver)
09-14 06:53:03.869  5505  5874 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-14 06:53:03.869  5505  5874 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-14 06:53:06.831  5505  5551 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-14 06:53:06.832  5505  5551 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-14 06:53:06.838  5505  5551 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1aa55d0 Bundle[{}]
,09-14 06:53:06.841  5505  5551 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-14 06:53:06.842  5505  5551 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-14 06:53:06.843  5505  5551 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-14 06:53:06.845  5505  5551 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-14 06:53:06.846  5505  5551 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-14 06:53:06.848  5505  5551 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-14 06:53:06.855  5505  5551 I System.out: Running OutgoingSocketThread
,09-14 06:53:06.858  5505  5875 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-14 06:53:06.858  5505  5875 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-14 06:53:09.869  5505  5875 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-14 06:53:09.869  5505  5875 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-14 06:53:09.869  5505  5875 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 06:53:09.870  5505  5875 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 06:53:09.872  5505  5878 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: OutgoingSocketThread/Sender)
,09-14 06:53:09.873  5505  5876 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-14 06:53:09.873  5505  5875 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-14 06:53:09.873  5505  5876 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-14 06:53:09.876  5505  5876 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 06:53:09.880  5505  5879 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Receiver)
,09-14 06:53:09.880  5505  5876 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 06:53:09.882  5505  5876 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-14 06:53:09.882  5505  5879 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: OutgoingSocketThread/Receiver)
09-14 06:53:09.883  5505  5879 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-14 06:53:09.883  5505  5879 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-14 06:53:09.883  5505  5880 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Sender)
,09-14 06:53:09.886  5505  5881 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Receiver)
,09-14 06:53:09.888  5505  5881 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: IncomingSocketThread/Receiver)
,09-14 06:53:09.888  5505  5881 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-14 06:53:09.888  5505  5881 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-14 06:53:12.868  5505  5551 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,09-14 06:53:12.869  5505  5551 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-14 06:53:12.869  5505  5551 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-14 06:53:12.877  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 06:53:12.877  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d14821 added. We now have 3 listener(s)
,09-14 06:53:12.880  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-14 06:53:12.880  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:53:12.880  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:53:12.881  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 06:53:12.881  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89bf446 added. We now have 4 listener(s)
09-14 06:53:12.881  5505  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:53:12.882  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 06:53:12.886  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:53:12.891  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:53:12.891  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:53:12.891  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:53:12.891  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:53:12.891  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:53:12.891  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:53:12.891  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:53:12.891  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:53:12.910  5505  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:53:12.910  5505  5551 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:53:12.911  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:53:12.911  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:53:12.911  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:53:12.911  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:53:12.911  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:12.911  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:53:12.911  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:53:12.912  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d14821 removed from the list
09-14 06:53:12.912  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:53:12.912  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89bf446 removed from the list
09-14 06:53:12.912  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:53:12.914  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:53:12.914  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:53:12.914  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:53:12.915  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:53:12.915  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:53:12.917  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:53:12.917  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:53:12.917  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:53:12.917  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89bf446 not in the list
09-14 06:53:12.917  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:12.917  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:53:12.918  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:53:12.918  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:53:12.918  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:53:12.918  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89bf446 not in the list
09-14 06:53:12.918  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 06:53:12.918  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:12.919  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:53:12.919  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d14821 not in the list
09-14 06:53:12.919  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 06:53:12.919  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d116334 added. We now have 3 listener(s)
09-14 06:53:12.921  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:53:12.921  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:53:12.921  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:53:12.921  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:53:12.921  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad9455d added. We now have 4 listener(s)
09-14 06:53:12.921  5505  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:53:12.922  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 06:53:12.925  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:53:12.929  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:53:12.929  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:53:12.929  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:53:12.929  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:53:12.929  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:53:12.929  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:53:12.929  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:53:12.929  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:53:12.930  5505  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:53:12.930  5505  5551 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:53:12.931  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 06:53:12.931  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 06:53:12.931  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 06:53:12.931  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:53:12.931  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 06:53:12.932  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:53:12.934  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:53:12.935  5505  5551 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:53:12.935  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 06:53:12.938  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 06:53:12.939  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 06:53:12.939  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 06:53:12.942  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 06:53:12.942  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 06:53:12.943  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-14 06:53:12.943  5505  5551 D BluetoothAdapter: STATE_ON
,09-14 06:53:12.946  5801  5842 D BtGatt.GattService: registerClient() - UUID=b0831735-d0e5-49e5-9733-4650245141bd
,09-14 06:53:12.947  5801  5817 D BtGatt.GattService: onClientRegistered() - UUID=b0831735-d0e5-49e5-9733-4650245141bd, clientIf=5
,09-14 06:53:12.948  5505  5516 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-14 06:53:12.949  5801  5811 D BtGatt.GattService: start scan with filters
09-14 06:53:12.952  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 06:53:12.952  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 06:53:12.952  5801  5820 D BtGatt.ScanManager: handling starting scan
09-14 06:53:12.952  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 06:53:12.952  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-14 06:53:12.955  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 06:53:12.955  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 06:53:12.955  5801  5820 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d602764
09-14 06:53:12.955  5505  5505 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 06:53:12.956  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 06:53:12.959  5505  5551 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-14 06:53:12.959  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 06:53:12.959  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 06:53:12.959  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:12.959  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-14 06:53:12.960  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 06:53:12.960  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 06:53:12.960  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 06:53:12.960  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 06:53:12.960  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 06:53:12.960  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 06:53:12.961  5505  5551 D BluetoothAdapter: STATE_ON
09-14 06:53:12.962  5801  5812 D BtGatt.GattService: stopScan() - queue size =1
,09-14 06:53:12.962  5801  5817 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 06:53:12.963  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:53:12.963  5801  5842 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 06:53:12.963  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:53:12.963  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 06:53:12.963  5801  5820 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-14 06:53:12.963  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 06:53:12.963  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 06:53:12.963  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-14 06:53:12.965  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:53:12.965  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:53:12.965  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-14 06:53:12.965  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:53:12.966  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:53:12.967  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:53:12.967  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:53:12.967  5505  5505 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 06:53:12.969  5801  5817 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-14 06:53:12.969  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:53:12.970  5801  5820 D BtGatt.ScanManager: Starting BLE batch scan
09-14 06:53:12.970  5801  5820 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 06:53:12.981  5801  5817 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 06:53:12.981  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:53:12.987  5801  5817 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 06:53:12.987  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:53:12.995  5801  5817 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-14 06:53:12.995  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:53:12.995  5801  5820 D BtGatt.ScanManager: stopping BLe Batch
,09-14 06:53:13.001  5801  5817 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 06:53:13.001  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:53:13.001  5801  5820 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 06:53:13.007  5801  5817 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 06:53:13.008  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:53:13.469  5505  5505 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 06:53:13.469  5505  5505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:53:13.469  5505  5505 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 06:53:15.968  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 06:53:15.968  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 06:53:15.968  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:53:15.969  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 06:53:15.969  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:15.969  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 06:53:15.969  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-14 06:53:15.969  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d116334 removed from the list
09-14 06:53:15.969  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:53:15.970  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad9455d removed from the list
09-14 06:53:15.970  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 06:53:15.970  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:53:15.972  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:15.972  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:53:15.977  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 06:53:15.977  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:53:15.978  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:53:15.978  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad9455d not in the list
09-14 06:53:15.979  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:53:15.979  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:53:15.983  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:53:15.983  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:53:15.984  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:53:15.984  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad9455d not in the list
,09-14 06:53:15.985  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:53:15.985  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:15.985  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:53:15.985  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d116334 not in the list
,09-14 06:53:15.988  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 06:53:15.988  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d6f461e added. We now have 3 listener(s)
09-14 06:53:15.991  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:53:15.991  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-14 06:53:15.991  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:53:15.991  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:53:15.992  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f22eff added. We now have 4 listener(s)
,09-14 06:53:15.992  5505  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:53:15.993  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 06:53:15.999  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:53:16.005  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:53:16.005  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:53:16.005  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:53:16.005  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:53:16.005  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:53:16.005  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:53:16.005  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:53:16.005  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:53:16.008  5505  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:53:16.009  5505  5551 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 06:53:16.010  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-14 06:53:16.011  5505  5551 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-14 06:53:16.012  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-14 06:53:16.012  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:53:16.012  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 06:53:16.012  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-14 06:53:16.012  5505  5551 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 06:53:16.013  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:53:16.017  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-14 06:53:16.018  5505  5551 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-14 06:53:16.018  5505  5551 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-14 06:53:16.018  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 06:53:16.018  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-14 06:53:16.018  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:53:16.019  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 06:53:16.021  5505  5882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 06:53:16.023  5837  5837 W Binder_4: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[36045]" dev="sockfs" ino=36045 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 06:53:16.023  5837  5837 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[36045]" dev="sockfs" ino=36045 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-14 06:53:16.024  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:53:16.024  5505  5505 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-14 06:53:16.026  5505  5551 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:53:16.026  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 06:53:16.026  5505  5882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-14 06:53:16.032  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 06:53:16.032  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 06:53:16.032  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 06:53:16.034  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-14 06:53:16.035  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:53:16.035  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-14 06:53:16.036  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 06:53:16.036  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-14 06:53:16.036  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-14 06:53:16.037  5505  5551 D BluetoothAdapter: STATE_ON
,09-14 06:53:16.043  5801  5812 D BtGatt.GattService: registerClient() - UUID=455bf102-04c6-4438-a726-16d47d6cccdc
,09-14 06:53:16.044  5801  5817 D BtGatt.GattService: onClientRegistered() - UUID=455bf102-04c6-4438-a726-16d47d6cccdc, clientIf=5
,09-14 06:53:16.044  5505  5515 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-14 06:53:16.046  5801  5819 D BtGatt.AdvertiseManager: message : 0
,09-14 06:53:16.049  5801  5819 D BtGatt.AdvertiseManager: starting multi advertising
,09-14 06:53:16.062  5801  5817 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-14 06:53:16.070  5801  5817 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-14 06:53:16.072  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-14 06:53:16.072  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-14 06:53:16.074  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 06:53:16.076  5505  5505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 06:53:16.076  5505  5505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-14 06:53:16.076  5505  5505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-14 06:53:16.076  5505  5505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-14 06:53:16.076  5505  5505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-14 06:53:16.076  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-14 06:53:16.078  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-14 06:53:16.080  5505  5505 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 06:53:16.081  5505  5505 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 06:53:16.581  5505  5505 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-14 06:53:16.581  5505  5505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-14 06:53:16.581  5505  5505 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 06:53:19.080  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 06:53:19.080  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-14 06:53:19.080  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 06:53:19.081  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-14 06:53:19.081  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-14 06:53:19.081  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-14 06:53:19.081  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-14 06:53:19.081  5505  5882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-14 06:53:19.082  5505  5551 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 06:53:19.082  5505  5882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-14 06:53:19.082  5505  5882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-14 06:53:19.082  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 06:53:19.082  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 06:53:19.082  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 06:53:19.082  5505  5505 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-14 06:53:19.082  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-14 06:53:19.082  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-14 06:53:19.087  5505  5551 D BluetoothAdapter: STATE_ON
09-14 06:53:19.087  5505  5551 D BluetoothLeScanner: could not find callback wrapper
09-14 06:53:19.087  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:53:19.087  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-14 06:53:19.089  5801  5819 D BtGatt.AdvertiseManager: message : 1
09-14 06:53:19.091  5801  5819 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-14 06:53:19.108  5801  5817 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-14 06:53:19.109  5801  5817 D BtGatt.GattService: Client app is not null!
09-14 06:53:19.110  5801  5838 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 06:53:19.111  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:53:19.111  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-14 06:53:19.111  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-14 06:53:19.112  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-14 06:53:19.112  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-14 06:53:19.114  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 06:53:19.115  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-14 06:53:19.115  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 06:53:19.116  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 06:53:19.119  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:53:19.119  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-14 06:53:19.119  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:19.119  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:53:19.119  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-14 06:53:19.119  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:53:19.119  5505  5505 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-14 06:53:19.119  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d6f461e removed from the list
09-14 06:53:19.119  5505  5505 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:53:19.120  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:53:19.120  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f22eff removed from the list
09-14 06:53:19.120  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:53:19.120  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:53:19.122  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:19.122  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:53:19.125  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:53:19.125  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:53:19.125  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:53:19.126  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f22eff not in the list
09-14 06:53:19.126  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:19.126  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:53:19.129  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:53:19.129  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:53:19.129  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:53:19.129  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f22eff not in the list
09-14 06:53:19.129  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:53:19.129  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:19.129  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:53:19.130  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d6f461e not in the list
,09-14 06:53:19.131  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 06:53:19.131  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff681b8 added. We now have 3 listener(s)
,09-14 06:53:19.133  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:53:19.134  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-14 06:53:19.134  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:53:19.134  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 06:53:19.134  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb7b91 added. We now have 4 listener(s)
09-14 06:53:19.134  5505  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:53:19.135  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 06:53:19.140  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:53:19.144  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:53:19.144  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:53:19.144  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:53:19.144  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:53:19.144  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:53:19.144  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:53:19.144  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:53:19.144  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:53:19.146  5505  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:53:19.147  5505  5551 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:53:19.147  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 06:53:19.147  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 06:53:19.147  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 06:53:19.147  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:53:19.147  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 06:53:19.148  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:53:19.151  5505  5551 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:53:19.151  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 06:53:19.152  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:53:19.155  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 06:53:19.156  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 06:53:19.156  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 06:53:19.159  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-14 06:53:19.160  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 06:53:19.160  5505  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 06:53:19.160  5505  5551 D BluetoothAdapter: STATE_ON
,09-14 06:53:19.163  5801  5811 D BtGatt.GattService: registerClient() - UUID=0448114d-aa20-42a4-9c9a-73e3f4953cec
,09-14 06:53:19.163  5801  5817 D BtGatt.GattService: onClientRegistered() - UUID=0448114d-aa20-42a4-9c9a-73e3f4953cec, clientIf=5
09-14 06:53:19.163  5505  5516 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 06:53:19.164  5801  5838 D BtGatt.GattService: start scan with filters
,09-14 06:53:19.166  5801  5820 D BtGatt.ScanManager: handling starting scan
09-14 06:53:19.167  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 06:53:19.167  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 06:53:19.167  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 06:53:19.167  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-14 06:53:19.169  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 06:53:19.170  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 06:53:19.170  5505  5505 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 06:53:19.171  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-14 06:53:19.173  5801  5817 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 06:53:19.173  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:53:19.173  5801  5820 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 06:53:19.179  5801  5817 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-14 06:53:19.179  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:53:19.179  5801  5820 D BtGatt.ScanManager: Starting BLE batch scan
09-14 06:53:19.179  5801  5820 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 06:53:19.189  5801  5817 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-14 06:53:19.189  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:53:19.195  5801  5817 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 06:53:19.195  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:53:19.621  5505  5505 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 06:53:19.670  5505  5505 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-14 06:53:19.670  5505  5505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 06:53:19.670  5505  5505 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 06:53:22.181  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 06:53:22.182  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 06:53:22.182  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-14 06:53:22.182  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:53:22.182  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-14 06:53:22.182  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 06:53:22.182  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 06:53:22.183  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 06:53:22.183  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 06:53:22.183  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 06:53:22.183  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 06:53:22.185  5505  5551 D BluetoothAdapter: STATE_ON
09-14 06:53:22.188  5801  5836 D BtGatt.GattService: stopScan() - queue size =1
,09-14 06:53:22.192  5801  5812 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 06:53:22.193  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:53:22.193  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-14 06:53:22.193  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 06:53:22.194  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 06:53:22.194  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-14 06:53:22.198  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:53:22.199  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:53:22.199  5505  5551 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 06:53:22.199  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 06:53:22.200  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:53:22.202  5801  5801 D BtGatt.ScanManager: awakened up at time 437898
09-14 06:53:22.202  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:53:22.202  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-14 06:53:22.203  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:22.203  5505  5505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:53:22.203  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:53:22.203  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:53:22.203  5505  5505 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:53:22.203  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff681b8 removed from the list
09-14 06:53:22.203  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:53:22.203  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb7b91 removed from the list
09-14 06:53:22.203  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:53:22.203  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:53:22.207  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:53:22.207  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:53:22.208  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:53:22.208  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:53:22.208  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:53:22.209  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb7b91 not in the list
09-14 06:53:22.209  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:22.209  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:53:22.210  5801  5817 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-14 06:53:22.210  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:53:22.210  5801  5820 D BtGatt.ScanManager: stopping BLe Batch
09-14 06:53:22.210  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:53:22.210  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:53:22.210  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:53:22.210  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb7b91 not in the list
09-14 06:53:22.210  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:53:22.210  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:22.210  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:53:22.211  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff681b8 not in the list
09-14 06:53:22.212  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 06:53:22.212  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@118d082 added. We now have 3 listener(s)
09-14 06:53:22.213  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:53:22.214  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:53:22.214  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:53:22.214  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:53:22.214  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da49393 added. We now have 4 listener(s)
09-14 06:53:22.214  5505  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:53:22.214  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 06:53:22.217  5801  5817 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 06:53:22.217  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:53:22.217  5801  5820 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 06:53:22.218  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:53:22.222  5505  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:53:22.222  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:53:22.222  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:53:22.222  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:53:22.222  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:53:22.222  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:53:22.222  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:53:22.222  5505  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:53:22.227  5505  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:53:22.227  5505  5551 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:53:22.228  5505  5551 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:53:22.228  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:53:22.228  5505  5551 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:53:22.228  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:53:22.228  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:22.228  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:53:22.228  5505  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:53:22.228  5505  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@118d082 removed from the list
09-14 06:53:22.228  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:53:22.228  5505  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da49393 removed from the list
,09-14 06:53:22.229  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:53:22.230  5505  5505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:53:22.230  5505  5551 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:53:22.230  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:53:22.231  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:22.231  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:53:22.232  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:53:22.232  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:53:22.232  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:53:22.232  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da49393 not in the list
09-14 06:53:22.232  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:22.232  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:53:22.233  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:53:22.233  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:53:22.233  5505  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:53:22.233  5505  5551 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da49393 not in the list
09-14 06:53:22.233  5505  5551 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:53:22.233  5505  5551 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:53:22.233  5505  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:53:22.233  5505  5551 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@118d082 not in the list
09-14 06:53:22.234  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-14 06:53:22.234  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-14 06:53:22.234  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-14 06:53:22.234  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 06:53:22.234  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 06:53:22.234  5505  5551 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-14 06:53:22.239  5801  5817 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-14 06:53:22.239  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:53:22.239  5801  5817 D BtGatt.GattService: current time is 437934971415
09-14 06:53:22.239  5801  5817 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -76, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -81, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -85, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -77, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -74, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
09-14 06:53:22.240  5801  5817 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-14 06:53:22.241  5801  5817 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-14 06:53:22.241  5801  5817 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 06:53:22.241  5801  5817 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-14 06:53:22.242  5801  5817 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 06:53:22.242  5801  5817 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,09-14 06:53:22.704  5505  5505 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 06:53:24.246  5505  5883 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name)
,09-14 06:53:26.245  5505  5551 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 186
,09-14 06:53:26.245  5505  5551 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 186, name: My test thread name)
,09-14 06:53:26.249  5505  5884 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
,09-14 06:53:26.250  5505  5884 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 187, thread name: My test thread name)
09-14 06:53:26.250  5505  5884 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-14 06:53:26.257  5505  5551 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 06:53:26.265  5505  5885 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,09-14 06:53:26.266  5505  5885 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 191, thread name: My test thread name): Test exception.
09-14 06:53:26.266  5505  5885 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-14 06:53:26.273  5505  5551 I jxcore-log: Total number of executed tests:  82
09-14 06:53:26.273  5505  5551 I jxcore-log: 
,09-14 06:53:26.274  5505  5551 I jxcore-log: Number of passed tests:  82
09-14 06:53:26.274  5505  5551 I jxcore-log: 
,09-14 06:53:26.274  5505  5551 I jxcore-log: Number of failed tests:  0
09-14 06:53:26.274  5505  5551 I jxcore-log: 
09-14 06:53:26.275  5505  5551 I jxcore-log: Number of ignored tests:  0
09-14 06:53:26.275  5505  5551 I jxcore-log: 
,09-14 06:53:26.275  5505  5551 I jxcore-log: Total duration:  101045
09-14 06:53:26.275  5505  5551 I jxcore-log: 
,09-14 06:53:26.283  5505  5551 I jxcore-log: Unit Test app is loaded
09-14 06:53:26.283  5505  5551 I jxcore-log: 
,09-14 06:53:26.297  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:53:26.297  5505  5551 I jxcore-log: 
,09-14 06:53:26.302  5505  5505 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-14 06:53:26.304  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:53:26.304  5505  5551 I jxcore-log: 
,09-14 06:53:26.306  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:53:26.306  5505  5551 I jxcore-log: 
,09-14 06:53:26.307  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:53:26.307  5505  5551 I jxcore-log: 
09-14 06:53:26.308  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-14 06:53:26.308  5505  5551 I jxcore-log: 
,09-14 06:53:26.311  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 06:53:26.311  5505  5551 I jxcore-log: 
,09-14 06:53:26.313  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:53:26.313  5505  5551 I jxcore-log: 
,09-14 06:53:26.317  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:53:26.317  5505  5551 I jxcore-log: 
,09-14 06:53:26.318  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-14 06:53:26.318  5505  5551 I jxcore-log: 
,09-14 06:53:26.319  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 06:53:26.319  5505  5551 I jxcore-log: 
,09-14 06:53:26.320  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 06:53:26.320  5505  5551 I jxcore-log: 
,09-14 06:53:26.321  5505  5883 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
09-14 06:53:26.322  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:53:26.322  5505  5551 I jxcore-log: 
,09-14 06:53:26.323  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:53:26.323  5505  5551 I jxcore-log: 
,09-14 06:53:26.325  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:53:26.325  5505  5551 I jxcore-log: 
,09-14 06:53:26.326  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.326  5505  5551 I jxcore-log: 
,09-14 06:53:26.328  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.328  5505  5551 I jxcore-log: 
,09-14 06:53:26.329  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.329  5505  5551 I jxcore-log: 
,09-14 06:53:26.330  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.330  5505  5551 I jxcore-log: 
09-14 06:53:26.331  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.331  5505  5551 I jxcore-log: 
,09-14 06:53:26.332  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.332  5505  5551 I jxcore-log: 
,09-14 06:53:26.333  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.333  5505  5551 I jxcore-log: 
09-14 06:53:26.334  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.334  5505  5551 I jxcore-log: 
,09-14 06:53:26.335  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.335  5505  5551 I jxcore-log: 
,09-14 06:53:26.336  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:53:26.336  5505  5551 I jxcore-log: 
,09-14 06:53:26.338  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:53:26.338  5505  5551 I jxcore-log: 
,09-14 06:53:26.338  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:53:26.338  5505  5551 I jxcore-log: 
09-14 06:53:26.339  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.339  5505  5551 I jxcore-log: 
09-14 06:53:26.340  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.340  5505  5551 I jxcore-log: 
09-14 06:53:26.340  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.340  5505  5551 I jxcore-log: 
09-14 06:53:26.341  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.341  5505  5551 I jxcore-log: 
,09-14 06:53:26.342  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.342  5505  5551 I jxcore-log: 
,09-14 06:53:26.343  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.343  5505  5551 I jxcore-log: 
,09-14 06:53:26.345  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.345  5505  5551 I jxcore-log: 
,09-14 06:53:26.345  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.345  5505  5551 I jxcore-log: 
,09-14 06:53:26.346  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.346  5505  5551 I jxcore-log: 
,09-14 06:53:26.347  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.347  5505  5551 I jxcore-log: 
,09-14 06:53:26.348  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.348  5505  5551 I jxcore-log: 
,09-14 06:53:26.348  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.348  5505  5551 I jxcore-log: 
,09-14 06:53:26.349  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.349  5505  5551 I jxcore-log: 
,09-14 06:53:26.350  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.350  5505  5551 I jxcore-log: 
,09-14 06:53:26.350  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 06:53:26.350  5505  5551 I jxcore-log: 
09-14 06:53:26.351  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.351  5505  5551 I jxcore-log: 
,09-14 06:53:26.352  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.352  5505  5551 I jxcore-log: 
,09-14 06:53:26.352  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.352  5505  5551 I jxcore-log: 
,09-14 06:53:26.353  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.353  5505  5551 I jxcore-log: 
,09-14 06:53:26.354  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.354  5505  5551 I jxcore-log: 
,09-14 06:53:26.355  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 06:53:26.355  5505  5551 I jxcore-log: 
,09-14 06:53:26.355  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.355  5505  5551 I jxcore-log: 
,09-14 06:53:26.356  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-14 06:53:26.356  5505  5551 I jxcore-log: 
,09-14 06:53:26.357  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.357  5505  5551 I jxcore-log: 
,09-14 06:53:26.357  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 06:53:26.357  5505  5551 I jxcore-log: 
,09-14 06:53:26.358  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-14 06:53:26.358  5505  5551 I jxcore-log: 
,09-14 06:53:26.359  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:53:26.359  5505  5551 I jxcore-log: 
09-14 06:53:26.359  5505  5551 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 06:53:26.359  5505  5551 I jxcore-log: 
,09-14 06:53:26.365  5505  5551 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-14 06:53:26.365  5505  5551 I jxcore-log:   bluetooth: 'on',
09-14 06:53:26.365  5505  5551 I jxcore-log:   wifi: 'on',
09-14 06:53:26.365  5505  5551 I jxcore-log:   cellular: 'doNotCare',
09-14 06:53:26.365  5505  5551 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-14 06:53:26.365  5505  5551 I jxcore-log: 
,09-14 06:53:26.369  5505  5551 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-14 06:53:26.369  5505  5551 I jxcore-log:   bluetooth: 'on',
09-14 06:53:26.369  5505  5551 I jxcore-log:   wifi: 'on',
09-14 06:53:26.369  5505  5551 I jxcore-log:   cellular: 'doNotCare' }
09-14 06:53:26.369  5505  5551 I jxcore-log: 
,09-14 06:53:26.370  5505  5551 I jxcore-log: My device name is: Huawei-Nexus 6P
09-14 06:53:26.370  5505  5551 I jxcore-log: 
,09-14 06:53:26.370  5505  5551 I jxcore-log: WARN testUtils: myNameCallback not set!
09-14 06:53:26.370  5505  5551 I jxcore-log: 
09-14 06:53:26.370  5505  5551 I jxcore-log: Running for WIFI network type
09-14 06:53:26.370  5505  5551 I jxcore-log: 
,09-14 06:53:28.106  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-14 06:53:28.106  5505  5551 I jxcore-log: 
,09-14 06:53:28.133   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-14 06:53:28.134   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 06:53:28.407  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-14 06:53:28.407  5505  5551 I jxcore-log: 
,09-14 06:53:28.433  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-14 06:53:28.433  5505  5551 I jxcore-log: 
,09-14 06:53:29.574  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-14 06:53:29.574  5505  5551 I jxcore-log: 
,09-14 06:53:29.578  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-14 06:53:29.578  5505  5551 I jxcore-log: 
,09-14 06:53:29.582  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-14 06:53:29.582  5505  5551 I jxcore-log: 
,09-14 06:53:29.626  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-14 06:53:29.626  5505  5551 I jxcore-log: 
,09-14 06:53:29.638  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-14 06:53:29.638  5505  5551 I jxcore-log: 
,09-14 06:53:29.641  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-14 06:53:29.641  5505  5551 I jxcore-log: 
,09-14 06:53:30.284  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-14 06:53:30.284  5505  5551 I jxcore-log: 
,09-14 06:53:30.396  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-14 06:53:30.396  5505  5551 I jxcore-log: 
,09-14 06:53:30.624  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-14 06:53:30.624  5505  5551 I jxcore-log: 
,09-14 06:53:30.631  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-14 06:53:30.631  5505  5551 I jxcore-log: 
,09-14 06:53:30.637  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-14 06:53:30.637  5505  5551 I jxcore-log: 
,09-14 06:53:30.648  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-14 06:53:30.648  5505  5551 I jxcore-log: 
,09-14 06:53:30.673  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-14 06:53:30.673  5505  5551 I jxcore-log: 
,09-14 06:53:30.706  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-14 06:53:30.706  5505  5551 I jxcore-log: 
,09-14 06:53:30.711  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-14 06:53:30.711  5505  5551 I jxcore-log: 
,09-14 06:53:30.717  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-14 06:53:30.717  5505  5551 I jxcore-log: 
,09-14 06:53:30.730  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-14 06:53:30.730  5505  5551 I jxcore-log: 
,09-14 06:53:30.733  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-14 06:53:30.733  5505  5551 I jxcore-log: 
,09-14 06:53:30.737  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-14 06:53:30.737  5505  5551 I jxcore-log: 
,09-14 06:53:30.748  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-14 06:53:30.748  5505  5551 I jxcore-log: 
,09-14 06:53:30.766  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-14 06:53:30.766  5505  5551 I jxcore-log: 
,09-14 06:53:30.774  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-14 06:53:30.774  5505  5551 I jxcore-log: 
,09-14 06:53:30.783  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-14 06:53:30.783  5505  5551 I jxcore-log: 
,09-14 06:53:30.791  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-14 06:53:30.791  5505  5551 I jxcore-log: 
,09-14 06:53:30.802  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-14 06:53:30.802  5505  5551 I jxcore-log: 
,09-14 06:53:30.809  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-14 06:53:30.809  5505  5551 I jxcore-log: 
,09-14 06:53:30.813  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-14 06:53:30.813  5505  5551 I jxcore-log: 
,09-14 06:53:30.834  5505  5551 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-14 06:53:30.834  5505  5551 I jxcore-log: 
,09-14 06:53:30.842  5505  5551 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-14 06:53:30.843  5505  5551 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-14 06:53:30.843  5505  5551 I jxcore-log: 
,09-14 06:53:30.845  5505  5551 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-14 06:53:30.845  5505  5551 I jxcore-log: 
,09-14 06:53:30.845  5505  5551 I jxcore-log: ThaliTape :: Started ThaliTape
09-14 06:53:30.845  5505  5551 I jxcore-log: 
,09-14 06:53:30.849  5505  5551 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-14 06:53:30.849  5505  5551 I jxcore-log: 
,09-14 06:53:30.879  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:53:30.879  5505  5551 I jxcore-log: 
,09-14 06:53:30.880  5505  5551 I jxcore-log: websocket error
09-14 06:53:30.880  5505  5551 I jxcore-log: 
,09-14 06:53:30.880  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:53:30.880  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:53:30.880  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:53:30.880  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:30.880  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:53:30.880  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:30.880  5505  5551 I jxcore-log: 
,09-14 06:53:30.880  5505  5551 I jxcore-log: WARN testUtils: logCallback not set!
09-14 06:53:30.880  5505  5551 I jxcore-log: 
,09-14 06:53:31.966  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:53:31.966  5505  5551 I jxcore-log: 
,09-14 06:53:31.966  5505  5551 I jxcore-log: websocket error
09-14 06:53:31.966  5505  5551 I jxcore-log: 
09-14 06:53:31.967  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:53:31.967  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:53:31.967  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:53:31.967  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:31.967  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:53:31.967  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:31.967  5505  5551 I jxcore-log: 
,09-14 06:53:33.391  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:53:33.391  5505  5551 I jxcore-log: 
09-14 06:53:33.391  5505  5551 I jxcore-log: websocket error
09-14 06:53:33.391  5505  5551 I jxcore-log: 
09-14 06:53:33.391  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:53:33.391  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:53:33.391  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:53:33.391  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:33.391  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:53:33.391  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:33.391  5505  5551 I jxcore-log: 
,09-14 06:53:38.424  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:53:38.424  5505  5551 I jxcore-log: 
,09-14 06:53:38.424  5505  5551 I jxcore-log: websocket error
09-14 06:53:38.424  5505  5551 I jxcore-log: 
09-14 06:53:38.424  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:53:38.424  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:53:38.424  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:53:38.424  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:38.424  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:53:38.424  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:38.424  5505  5551 I jxcore-log: 
,09-14 06:53:43.454  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:53:43.454  5505  5551 I jxcore-log: 
,09-14 06:53:43.455  5505  5551 I jxcore-log: websocket error
09-14 06:53:43.455  5505  5551 I jxcore-log: 
09-14 06:53:43.455  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:53:43.455  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:53:43.455  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:53:43.455  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:43.455  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:53:43.455  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:43.455  5505  5551 I jxcore-log: 
,09-14 06:53:48.135   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:53:48.489  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:53:48.489  5505  5551 I jxcore-log: 
,09-14 06:53:48.489  5505  5551 I jxcore-log: websocket error
09-14 06:53:48.489  5505  5551 I jxcore-log: 
09-14 06:53:48.490  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:53:48.490  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:53:48.490  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:53:48.490  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:48.490  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:53:48.490  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:48.490  5505  5551 I jxcore-log: 
,09-14 06:53:49.136   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:53:50.138   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:53:51.139   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:53:52.141   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:53:53.141   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 06:53:53.514  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:53:53.514  5505  5551 I jxcore-log: 
,09-14 06:53:53.514  5505  5551 I jxcore-log: websocket error
09-14 06:53:53.514  5505  5551 I jxcore-log: 
09-14 06:53:53.515  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:53:53.515  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:53:53.515  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:53:53.515  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:53.515  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:53:53.515  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:53.515  5505  5551 I jxcore-log: 
,09-14 06:53:58.143   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:53:58.546  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:53:58.546  5505  5551 I jxcore-log: 
,09-14 06:53:58.547  5505  5551 I jxcore-log: websocket error
09-14 06:53:58.547  5505  5551 I jxcore-log: 
09-14 06:53:58.547  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:53:58.547  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:53:58.547  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:53:58.547  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:58.547  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:53:58.547  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:53:58.547  5505  5551 I jxcore-log: 
,09-14 06:53:59.144   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:00.146   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:01.148   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:02.149   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:03.150   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 06:54:03.576  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:54:03.576  5505  5551 I jxcore-log: 
,09-14 06:54:03.577  5505  5551 I jxcore-log: websocket error
09-14 06:54:03.577  5505  5551 I jxcore-log: 
09-14 06:54:03.577  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:54:03.577  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:54:03.577  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:54:03.577  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:03.577  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:54:03.577  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:03.577  5505  5551 I jxcore-log: 
,09-14 06:54:08.603  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:54:08.603  5505  5551 I jxcore-log: 
,09-14 06:54:08.604  5505  5551 I jxcore-log: websocket error
09-14 06:54:08.604  5505  5551 I jxcore-log: 
09-14 06:54:08.604  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:54:08.604  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:54:08.604  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:54:08.604  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:08.604  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:54:08.604  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:08.604  5505  5551 I jxcore-log: 
,09-14 06:54:13.151   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:13.666  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:54:13.666  5505  5551 I jxcore-log: 
09-14 06:54:13.666  5505  5551 I jxcore-log: websocket error
09-14 06:54:13.666  5505  5551 I jxcore-log: 
,09-14 06:54:13.666  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:54:13.666  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:54:13.666  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:54:13.666  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:13.666  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:54:13.666  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:13.666  5505  5551 I jxcore-log: 
,09-14 06:54:14.153   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:15.154   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:16.155   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:17.157   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:18.157   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 06:54:18.695  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:54:18.695  5505  5551 I jxcore-log: 
,09-14 06:54:18.695  5505  5551 I jxcore-log: websocket error
09-14 06:54:18.695  5505  5551 I jxcore-log: 
09-14 06:54:18.696  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:54:18.696  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:54:18.696  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:54:18.696  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:18.696  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:54:18.696  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:18.696  5505  5551 I jxcore-log: 
,09-14 06:54:23.722  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:54:23.722  5505  5551 I jxcore-log: 
09-14 06:54:23.722  5505  5551 I jxcore-log: websocket error
09-14 06:54:23.722  5505  5551 I jxcore-log: 
09-14 06:54:23.723  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:54:23.723  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:54:23.723  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:54:23.723  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:23.723  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:54:23.723  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:23.723  5505  5551 I jxcore-log: 
,09-14 06:54:28.750  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:54:28.750  5505  5551 I jxcore-log: 
09-14 06:54:28.750  5505  5551 I jxcore-log: websocket error
09-14 06:54:28.750  5505  5551 I jxcore-log: 
09-14 06:54:28.750  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:54:28.750  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:54:28.750  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:54:28.750  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:28.750  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:54:28.750  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:28.750  5505  5551 I jxcore-log: 
,09-14 06:54:33.159   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:33.774  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:54:33.774  5505  5551 I jxcore-log: 
,09-14 06:54:33.775  5505  5551 I jxcore-log: websocket error
09-14 06:54:33.775  5505  5551 I jxcore-log: 
09-14 06:54:33.775  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:54:33.775  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:54:33.775  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:54:33.775  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:33.775  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:54:33.775  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:33.775  5505  5551 I jxcore-log: 
,09-14 06:54:34.160   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:35.161   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:36.162   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:37.164   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:38.165   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 06:54:38.800  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:54:38.800  5505  5551 I jxcore-log: 
,09-14 06:54:38.800  5505  5551 I jxcore-log: websocket error
09-14 06:54:38.800  5505  5551 I jxcore-log: 
09-14 06:54:38.801  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:54:38.801  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:54:38.801  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:54:38.801  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:38.801  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:54:38.801  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:38.801  5505  5551 I jxcore-log: 
,09-14 06:54:43.829  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:54:43.829  5505  5551 I jxcore-log: 
,09-14 06:54:43.829  5505  5551 I jxcore-log: websocket error
09-14 06:54:43.829  5505  5551 I jxcore-log: 
,09-14 06:54:43.830  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:54:43.830  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:54:43.830  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:54:43.830  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:43.830  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:54:43.830  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:43.830  5505  5551 I jxcore-log: 
,09-14 06:54:48.854  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:54:48.854  5505  5551 I jxcore-log: 
,09-14 06:54:48.855  5505  5551 I jxcore-log: websocket error
09-14 06:54:48.855  5505  5551 I jxcore-log: 
09-14 06:54:48.856  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:54:48.856  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:54:48.856  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:54:48.856  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:48.856  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:54:48.856  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:48.856  5505  5551 I jxcore-log: 
,09-14 06:54:53.879  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:54:53.879  5505  5551 I jxcore-log: 
09-14 06:54:53.879  5505  5551 I jxcore-log: websocket error
09-14 06:54:53.879  5505  5551 I jxcore-log: 
,09-14 06:54:53.880  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:54:53.880  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:54:53.880  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:54:53.880  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:53.880  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:54:53.880  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:53.880  5505  5551 I jxcore-log: 
,09-14 06:54:58.166   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:54:58.906  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:54:58.906  5505  5551 I jxcore-log: 
,09-14 06:54:58.906  5505  5551 I jxcore-log: websocket error
09-14 06:54:58.906  5505  5551 I jxcore-log: 
09-14 06:54:58.907  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:54:58.907  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:54:58.907  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:54:58.907  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:58.907  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:54:58.907  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:54:58.907  5505  5551 I jxcore-log: 
,09-14 06:54:59.168   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:55:00.169   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:55:01.170   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:55:02.172   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:55:03.172   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 06:55:03.931  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:55:03.931  5505  5551 I jxcore-log: 
,09-14 06:55:03.932  5505  5551 I jxcore-log: websocket error
09-14 06:55:03.932  5505  5551 I jxcore-log: 
,09-14 06:55:03.932  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:55:03.932  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:55:03.932  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:55:03.932  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:03.932  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:55:03.932  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:03.932  5505  5551 I jxcore-log: 
,09-14 06:55:08.958  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:55:08.958  5505  5551 I jxcore-log: 
,09-14 06:55:08.958  5505  5551 I jxcore-log: websocket error
09-14 06:55:08.958  5505  5551 I jxcore-log: 
09-14 06:55:08.959  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:55:08.959  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:55:08.959  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:55:08.959  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:08.959  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:55:08.959  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:08.959  5505  5551 I jxcore-log: 
,09-14 06:55:13.984  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:55:13.984  5505  5551 I jxcore-log: 
,09-14 06:55:13.985  5505  5551 I jxcore-log: websocket error
09-14 06:55:13.985  5505  5551 I jxcore-log: 
09-14 06:55:13.985  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:55:13.985  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:55:13.985  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:55:13.985  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:13.985  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:55:13.985  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:13.985  5505  5551 I jxcore-log: 
,09-14 06:55:19.018  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:55:19.018  5505  5551 I jxcore-log: 
09-14 06:55:19.019  5505  5551 I jxcore-log: websocket error
09-14 06:55:19.019  5505  5551 I jxcore-log: 
,09-14 06:55:19.019  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:55:19.019  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:55:19.019  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:55:19.019  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:19.019  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:55:19.019  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:19.019  5505  5551 I jxcore-log: 
,09-14 06:55:24.042  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:55:24.042  5505  5551 I jxcore-log: 
09-14 06:55:24.043  5505  5551 I jxcore-log: websocket error
09-14 06:55:24.043  5505  5551 I jxcore-log: 
09-14 06:55:24.043  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:55:24.043  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:55:24.043  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:55:24.043  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:24.043  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:55:24.043  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:24.043  5505  5551 I jxcore-log: 
,09-14 06:55:28.173   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-14 06:55:28.173   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 06:55:29.067  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:55:29.067  5505  5551 I jxcore-log: 
09-14 06:55:29.068  5505  5551 I jxcore-log: websocket error
09-14 06:55:29.068  5505  5551 I jxcore-log: 
09-14 06:55:29.068  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:55:29.068  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:55:29.068  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:55:29.068  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:29.068  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:55:29.068  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:29.068  5505  5551 I jxcore-log: 
,09-14 06:55:34.092  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:55:34.092  5505  5551 I jxcore-log: 
,09-14 06:55:34.092  5505  5551 I jxcore-log: websocket error
09-14 06:55:34.092  5505  5551 I jxcore-log: 
09-14 06:55:34.092  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:55:34.092  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:55:34.092  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:55:34.092  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:34.092  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:55:34.092  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:34.092  5505  5551 I jxcore-log: 
,09-14 06:55:39.115  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:55:39.115  5505  5551 I jxcore-log: 
,09-14 06:55:39.116  5505  5551 I jxcore-log: websocket error
09-14 06:55:39.116  5505  5551 I jxcore-log: 
09-14 06:55:39.116  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:55:39.116  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:55:39.116  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:55:39.116  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:39.116  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:55:39.116  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:39.116  5505  5551 I jxcore-log: 
,09-14 06:55:44.143  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:55:44.143  5505  5551 I jxcore-log: 
,09-14 06:55:44.143  5505  5551 I jxcore-log: websocket error
09-14 06:55:44.143  5505  5551 I jxcore-log: 
09-14 06:55:44.144  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:55:44.144  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:55:44.144  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:55:44.144  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:44.144  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:55:44.144  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:44.144  5505  5551 I jxcore-log: 
,09-14 06:55:49.168  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:55:49.168  5505  5551 I jxcore-log: 
09-14 06:55:49.169  5505  5551 I jxcore-log: websocket error
09-14 06:55:49.169  5505  5551 I jxcore-log: 
09-14 06:55:49.169  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:55:49.169  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:55:49.169  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:55:49.169  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:49.169  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:55:49.169  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:49.169  5505  5551 I jxcore-log: 
,09-14 06:55:53.184   534  1475 E QC-QMI  : qmi_client [534] 8: failed to locate client data
,09-14 06:55:53.189   518   518 E QC-QMI  : qmuxd: RX on fd=16 returned error=0 errno[2:No such file or directory]
,09-14 06:55:53.190   518   518 E QC-QMI  : QMUX qmux_client_id=8 not found in qmux client list, unable to remove
,09-14 06:55:53.192   534   534 I Atfwd_Daemon: Stop the daemon....
,09-14 06:55:53.304  5888  5888 I libmdmdetect: ESOC framework not supported
,09-14 06:55:53.306  5888  5888 I libmdmdetect: Found internal modem: modem
,09-14 06:55:53.303  5888  5888 W ATFWD-daemon: type=1400 audit(0.0:120): avc: denied { read write } for name="diag" dev="tmpfs" ino=11991 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-14 06:55:53.307  5888  5888 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-14 06:55:53.318  5888  5888 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
09-14 06:55:53.318  5888  5888 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-14 06:55:53.319  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:55:54.196  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:55:54.196  5505  5551 I jxcore-log: 
,09-14 06:55:54.197  5505  5551 I jxcore-log: websocket error
09-14 06:55:54.197  5505  5551 I jxcore-log: 
,09-14 06:55:54.198  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:55:54.198  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:55:54.198  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:55:54.198  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:54.198  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:55:54.198  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:54.198  5505  5551 I jxcore-log: 
,09-14 06:55:54.322  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:55:55.323  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:55:56.324  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:55:57.326  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:55:58.326  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 06:55:59.252  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:55:59.252  5505  5551 I jxcore-log: 
09-14 06:55:59.253  5505  5551 I jxcore-log: websocket error
09-14 06:55:59.253  5505  5551 I jxcore-log: 
09-14 06:55:59.253  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:55:59.253  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:55:59.253  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:55:59.253  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:59.253  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:55:59.253  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:55:59.253  5505  5551 I jxcore-log: 
,09-14 06:56:03.327  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:04.278  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:56:04.278  5505  5551 I jxcore-log: 
09-14 06:56:04.278  5505  5551 I jxcore-log: websocket error
09-14 06:56:04.278  5505  5551 I jxcore-log: 
,09-14 06:56:04.279  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:56:04.279  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:56:04.279  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:56:04.279  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:04.279  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:56:04.279  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:04.279  5505  5551 I jxcore-log: 
,09-14 06:56:04.328  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:05.329  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:06.331  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:07.332  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:08.333  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 06:56:09.306  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:56:09.306  5505  5551 I jxcore-log: 
,09-14 06:56:09.307  5505  5551 I jxcore-log: websocket error
09-14 06:56:09.307  5505  5551 I jxcore-log: 
09-14 06:56:09.307  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:56:09.307  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:56:09.307  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:56:09.307  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:09.307  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:56:09.307  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:09.307  5505  5551 I jxcore-log: 
,09-14 06:56:14.335  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:56:14.335  5505  5551 I jxcore-log: 
09-14 06:56:14.335  5505  5551 I jxcore-log: websocket error
09-14 06:56:14.335  5505  5551 I jxcore-log: 
09-14 06:56:14.336  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:56:14.336  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:56:14.336  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:56:14.336  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:14.336  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:56:14.336  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:14.336  5505  5551 I jxcore-log: 
,09-14 06:56:18.334  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:19.336  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:19.364  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:56:19.364  5505  5551 I jxcore-log: 
,09-14 06:56:19.364  5505  5551 I jxcore-log: websocket error
09-14 06:56:19.364  5505  5551 I jxcore-log: 
09-14 06:56:19.364  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:56:19.364  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:56:19.364  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:56:19.364  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:19.364  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:56:19.364  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:19.364  5505  5551 I jxcore-log: 
,09-14 06:56:20.337  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:21.338  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:22.339  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:23.340  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 06:56:24.391  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:56:24.391  5505  5551 I jxcore-log: 
,09-14 06:56:24.392  5505  5551 I jxcore-log: websocket error
09-14 06:56:24.392  5505  5551 I jxcore-log: 
,09-14 06:56:24.392  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:56:24.392  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:56:24.392  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:56:24.392  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:24.392  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:56:24.392  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:24.392  5505  5551 I jxcore-log: 
,09-14 06:56:29.422  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:56:29.422  5505  5551 I jxcore-log: 
,09-14 06:56:29.422  5505  5551 I jxcore-log: websocket error
09-14 06:56:29.422  5505  5551 I jxcore-log: 
,09-14 06:56:29.423  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:56:29.423  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:56:29.423  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:56:29.423  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:29.423  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:56:29.423  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:29.423  5505  5551 I jxcore-log: 
,09-14 06:56:34.452  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:56:34.452  5505  5551 I jxcore-log: 
09-14 06:56:34.453  5505  5551 I jxcore-log: websocket error
09-14 06:56:34.453  5505  5551 I jxcore-log: 
09-14 06:56:34.453  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:56:34.453  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:56:34.453  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:56:34.453  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:34.453  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:56:34.453  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:34.453  5505  5551 I jxcore-log: 
,09-14 06:56:38.341  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:39.342  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:39.482  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:56:39.482  5505  5551 I jxcore-log: 
,09-14 06:56:39.482  5505  5551 I jxcore-log: websocket error
09-14 06:56:39.482  5505  5551 I jxcore-log: 
09-14 06:56:39.483  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:56:39.483  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:56:39.483  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:56:39.483  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:39.483  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:56:39.483  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:39.483  5505  5551 I jxcore-log: 
,09-14 06:56:40.343  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:41.344  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:42.345  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:56:43.345  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 06:56:44.509  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:56:44.509  5505  5551 I jxcore-log: 
,09-14 06:56:44.509  5505  5551 I jxcore-log: websocket error
09-14 06:56:44.509  5505  5551 I jxcore-log: 
09-14 06:56:44.509  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:56:44.509  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:56:44.509  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:56:44.509  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:44.509  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:56:44.509  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:44.509  5505  5551 I jxcore-log: 
,09-14 06:56:49.535  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:56:49.535  5505  5551 I jxcore-log: 
09-14 06:56:49.535  5505  5551 I jxcore-log: websocket error
09-14 06:56:49.535  5505  5551 I jxcore-log: 
,09-14 06:56:49.536  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:56:49.536  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:56:49.536  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:56:49.536  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:49.536  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:56:49.536  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:49.536  5505  5551 I jxcore-log: 
,09-14 06:56:54.564  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:56:54.564  5505  5551 I jxcore-log: 
09-14 06:56:54.565  5505  5551 I jxcore-log: websocket error
09-14 06:56:54.565  5505  5551 I jxcore-log: 
09-14 06:56:54.565  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:56:54.565  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:56:54.565  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:56:54.565  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:54.565  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:56:54.565  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:54.565  5505  5551 I jxcore-log: 
,09-14 06:56:59.589  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:56:59.589  5505  5551 I jxcore-log: 
,09-14 06:56:59.589  5505  5551 I jxcore-log: websocket error
09-14 06:56:59.589  5505  5551 I jxcore-log: 
09-14 06:56:59.590  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:56:59.590  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:56:59.590  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:56:59.590  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:59.590  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:56:59.590  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:56:59.590  5505  5551 I jxcore-log: 
,09-14 06:57:03.346  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:04.348  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:04.617  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:57:04.617  5505  5551 I jxcore-log: 
,09-14 06:57:04.617  5505  5551 I jxcore-log: websocket error
09-14 06:57:04.617  5505  5551 I jxcore-log: 
,09-14 06:57:04.617  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:57:04.617  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:57:04.617  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:57:04.617  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:04.617  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:57:04.617  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:04.617  5505  5551 I jxcore-log: 
,09-14 06:57:05.349  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:06.350  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:07.352  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:08.352  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 06:57:09.645  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:57:09.645  5505  5551 I jxcore-log: 
,09-14 06:57:09.645  5505  5551 I jxcore-log: websocket error
09-14 06:57:09.645  5505  5551 I jxcore-log: 
09-14 06:57:09.646  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:57:09.646  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:57:09.646  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:57:09.646  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:09.646  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:57:09.646  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:09.646  5505  5551 I jxcore-log: 
,09-14 06:57:14.672  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:57:14.672  5505  5551 I jxcore-log: 
09-14 06:57:14.672  5505  5551 I jxcore-log: websocket error
09-14 06:57:14.672  5505  5551 I jxcore-log: 
,09-14 06:57:14.672  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:57:14.672  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:57:14.672  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:57:14.672  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:14.672  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:57:14.672  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:14.672  5505  5551 I jxcore-log: 
,09-14 06:57:19.700  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:57:19.700  5505  5551 I jxcore-log: 
,09-14 06:57:19.700  5505  5551 I jxcore-log: websocket error
09-14 06:57:19.700  5505  5551 I jxcore-log: 
09-14 06:57:19.701  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:57:19.701  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:57:19.701  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:57:19.701  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:19.701  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:57:19.701  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:19.701  5505  5551 I jxcore-log: 
,09-14 06:57:24.728  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:57:24.728  5505  5551 I jxcore-log: 
,09-14 06:57:24.729  5505  5551 I jxcore-log: websocket error
09-14 06:57:24.729  5505  5551 I jxcore-log: 
09-14 06:57:24.729  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:57:24.729  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:57:24.729  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:57:24.729  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:24.729  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:57:24.729  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:24.729  5505  5551 I jxcore-log: 
,09-14 06:57:29.758  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:57:29.758  5505  5551 I jxcore-log: 
09-14 06:57:29.759  5505  5551 I jxcore-log: websocket error
09-14 06:57:29.759  5505  5551 I jxcore-log: 
09-14 06:57:29.759  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:57:29.759  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:57:29.759  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:57:29.759  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:29.759  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:57:29.759  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:29.759  5505  5551 I jxcore-log: 
,09-14 06:57:33.353  5888  5888 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-14 06:57:33.353  5888  5888 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 06:57:34.784  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:57:34.784  5505  5551 I jxcore-log: 
,09-14 06:57:34.785  5505  5551 I jxcore-log: websocket error
09-14 06:57:34.785  5505  5551 I jxcore-log: 
,09-14 06:57:34.785  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:57:34.785  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:57:34.785  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:57:34.785  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:34.785  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:57:34.785  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:34.785  5505  5551 I jxcore-log: 
,09-14 06:57:38.354  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:39.356  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:39.810  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:57:39.810  5505  5551 I jxcore-log: 
09-14 06:57:39.810  5505  5551 I jxcore-log: websocket error
09-14 06:57:39.810  5505  5551 I jxcore-log: 
09-14 06:57:39.811  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:57:39.811  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:57:39.811  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:57:39.811  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:39.811  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:57:39.811  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:39.811  5505  5551 I jxcore-log: 
,09-14 06:57:40.357  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:41.358  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:42.359  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:43.360  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 06:57:44.838  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:57:44.838  5505  5551 I jxcore-log: 
,09-14 06:57:44.839  5505  5551 I jxcore-log: websocket error
09-14 06:57:44.839  5505  5551 I jxcore-log: 
09-14 06:57:44.839  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:57:44.839  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:57:44.839  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:57:44.839  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:44.839  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:57:44.839  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:44.839  5505  5551 I jxcore-log: 
,09-14 06:57:48.361  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:49.362  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:49.871  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:57:49.871  5505  5551 I jxcore-log: 
,09-14 06:57:49.871  5505  5551 I jxcore-log: websocket error
09-14 06:57:49.871  5505  5551 I jxcore-log: 
,09-14 06:57:49.872  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:57:49.872  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:57:49.872  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:57:49.872  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:49.872  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:57:49.872  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:49.872  5505  5551 I jxcore-log: 
,09-14 06:57:50.364  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:51.365  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:52.366  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:57:53.367  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 06:57:54.911  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:57:54.911  5505  5551 I jxcore-log: 
,09-14 06:57:54.912  5505  5551 I jxcore-log: websocket error
09-14 06:57:54.912  5505  5551 I jxcore-log: 
,09-14 06:57:54.912  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:57:54.912  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:57:54.912  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:57:54.912  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:54.912  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:57:54.912  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:54.912  5505  5551 I jxcore-log: 
,09-14 06:57:59.944  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:57:59.944  5505  5551 I jxcore-log: 
,09-14 06:57:59.944  5505  5551 I jxcore-log: websocket error
09-14 06:57:59.944  5505  5551 I jxcore-log: 
09-14 06:57:59.945  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:57:59.945  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:57:59.945  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:57:59.945  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:59.945  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:57:59.945  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:57:59.945  5505  5551 I jxcore-log: 
,09-14 06:58:03.368  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:04.370  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:04.972  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:58:04.972  5505  5551 I jxcore-log: 
09-14 06:58:04.972  5505  5551 I jxcore-log: websocket error
09-14 06:58:04.972  5505  5551 I jxcore-log: 
,09-14 06:58:04.973  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:58:04.973  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:58:04.973  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:58:04.973  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:04.973  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:58:04.973  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:04.973  5505  5551 I jxcore-log: 
,09-14 06:58:05.371  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:06.372  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:07.374  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:08.374  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 06:58:09.999  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:58:09.999  5505  5551 I jxcore-log: 
,09-14 06:58:09.999  5505  5551 I jxcore-log: websocket error
09-14 06:58:09.999  5505  5551 I jxcore-log: 
09-14 06:58:09.999  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:58:09.999  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:58:09.999  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:58:09.999  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:09.999  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:58:09.999  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:09.999  5505  5551 I jxcore-log: 
,09-14 06:58:15.026  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:58:15.026  5505  5551 I jxcore-log: 
09-14 06:58:15.027  5505  5551 I jxcore-log: websocket error
09-14 06:58:15.027  5505  5551 I jxcore-log: 
09-14 06:58:15.027  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:58:15.027  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:58:15.027  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:58:15.027  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:15.027  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:58:15.027  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:15.027  5505  5551 I jxcore-log: 
,09-14 06:58:20.051  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:58:20.051  5505  5551 I jxcore-log: 
,09-14 06:58:20.052  5505  5551 I jxcore-log: websocket error
09-14 06:58:20.052  5505  5551 I jxcore-log: 
09-14 06:58:20.052  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:58:20.052  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:58:20.052  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:58:20.052  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:20.052  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:58:20.052  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:20.052  5505  5551 I jxcore-log: 
,09-14 06:58:23.375  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:24.376  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:25.075  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:58:25.075  5505  5551 I jxcore-log: 
,09-14 06:58:25.076  5505  5551 I jxcore-log: websocket error
09-14 06:58:25.076  5505  5551 I jxcore-log: 
,09-14 06:58:25.076  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:58:25.076  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:58:25.076  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:58:25.076  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:25.076  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:58:25.076  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:25.076  5505  5551 I jxcore-log: 
,09-14 06:58:25.377  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:26.378  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:27.379  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:28.380  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 06:58:30.101  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:58:30.101  5505  5551 I jxcore-log: 
,09-14 06:58:30.102  5505  5551 I jxcore-log: websocket error
09-14 06:58:30.102  5505  5551 I jxcore-log: 
09-14 06:58:30.102  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:58:30.102  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:58:30.102  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:58:30.102  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:30.102  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:58:30.102  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:30.102  5505  5551 I jxcore-log: 
,09-14 06:58:35.127  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:58:35.127  5505  5551 I jxcore-log: 
09-14 06:58:35.127  5505  5551 I jxcore-log: websocket error
09-14 06:58:35.127  5505  5551 I jxcore-log: 
09-14 06:58:35.128  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:58:35.128  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:58:35.128  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:58:35.128  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:35.128  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:58:35.128  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:35.128  5505  5551 I jxcore-log: 
,09-14 06:58:40.170  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:58:40.170  5505  5551 I jxcore-log: 
,09-14 06:58:40.170  5505  5551 I jxcore-log: websocket error
09-14 06:58:40.170  5505  5551 I jxcore-log: 
,09-14 06:58:40.170  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:58:40.170  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:58:40.170  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:58:40.170  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:40.170  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:58:40.170  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:40.170  5505  5551 I jxcore-log: 
,09-14 06:58:45.195  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:58:45.195  5505  5551 I jxcore-log: 
,09-14 06:58:45.196  5505  5551 I jxcore-log: websocket error
09-14 06:58:45.196  5505  5551 I jxcore-log: 
09-14 06:58:45.196  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:58:45.196  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:58:45.196  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:58:45.196  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:45.196  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:58:45.196  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:45.196  5505  5551 I jxcore-log: 
,09-14 06:58:48.381  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:49.382  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:50.221  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:58:50.221  5505  5551 I jxcore-log: 
09-14 06:58:50.221  5505  5551 I jxcore-log: websocket error
09-14 06:58:50.221  5505  5551 I jxcore-log: 
09-14 06:58:50.222  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:58:50.222  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:58:50.222  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:58:50.222  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:50.222  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:58:50.222  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:50.222  5505  5551 I jxcore-log: 
,09-14 06:58:50.383  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:51.384  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:52.386  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:58:53.386  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 06:58:55.246  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:58:55.246  5505  5551 I jxcore-log: 
,09-14 06:58:55.246  5505  5551 I jxcore-log: websocket error
09-14 06:58:55.246  5505  5551 I jxcore-log: 
09-14 06:58:55.247  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:58:55.247  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:58:55.247  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:58:55.247  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:55.247  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:58:55.247  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:58:55.247  5505  5551 I jxcore-log: 
,09-14 06:59:00.294  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:59:00.294  5505  5551 I jxcore-log: 
09-14 06:59:00.294  5505  5551 I jxcore-log: websocket error
09-14 06:59:00.294  5505  5551 I jxcore-log: 
09-14 06:59:00.294  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:59:00.294  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:59:00.294  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:59:00.294  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:00.294  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:59:00.294  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:00.294  5505  5551 I jxcore-log: 
,09-14 06:59:05.320  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:59:05.320  5505  5551 I jxcore-log: 
,09-14 06:59:05.320  5505  5551 I jxcore-log: websocket error
09-14 06:59:05.320  5505  5551 I jxcore-log: 
09-14 06:59:05.320  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:59:05.320  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:59:05.320  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:59:05.320  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:05.320  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:59:05.320  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:05.320  5505  5551 I jxcore-log: 
,09-14 06:59:10.348  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:59:10.348  5505  5551 I jxcore-log: 
,09-14 06:59:10.348  5505  5551 I jxcore-log: websocket error
09-14 06:59:10.348  5505  5551 I jxcore-log: 
09-14 06:59:10.349  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:59:10.349  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:59:10.349  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:59:10.349  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:10.349  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:59:10.349  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:10.349  5505  5551 I jxcore-log: 
,09-14 06:59:15.373  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:59:15.373  5505  5551 I jxcore-log: 
,09-14 06:59:15.374  5505  5551 I jxcore-log: websocket error
09-14 06:59:15.374  5505  5551 I jxcore-log: 
09-14 06:59:15.374  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:59:15.374  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:59:15.374  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:59:15.374  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:15.374  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:59:15.374  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:15.374  5505  5551 I jxcore-log: 
,09-14 06:59:18.387  5888  5888 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-14 06:59:18.388  5888  5888 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 06:59:20.409  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:59:20.409  5505  5551 I jxcore-log: 
09-14 06:59:20.409  5505  5551 I jxcore-log: websocket error
09-14 06:59:20.409  5505  5551 I jxcore-log: 
09-14 06:59:20.409  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:59:20.409  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:59:20.409  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:59:20.409  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:20.409  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:59:20.409  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:20.409  5505  5551 I jxcore-log: 
,09-14 06:59:25.437  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:59:25.437  5505  5551 I jxcore-log: 
,09-14 06:59:25.437  5505  5551 I jxcore-log: websocket error
09-14 06:59:25.437  5505  5551 I jxcore-log: 
,09-14 06:59:25.437  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:59:25.437  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:59:25.437  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:59:25.437  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:25.437  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:59:25.437  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:25.437  5505  5551 I jxcore-log: 
,09-14 06:59:28.389  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:29.390  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:30.392  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:30.462  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:59:30.462  5505  5551 I jxcore-log: 
,09-14 06:59:30.463  5505  5551 I jxcore-log: websocket error
09-14 06:59:30.463  5505  5551 I jxcore-log: 
09-14 06:59:30.463  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:59:30.463  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:59:30.463  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:59:30.463  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:30.463  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:59:30.463  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:30.463  5505  5551 I jxcore-log: 
,09-14 06:59:31.393  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:32.394  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:33.395  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 06:59:35.488  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:59:35.488  5505  5551 I jxcore-log: 
09-14 06:59:35.489  5505  5551 I jxcore-log: websocket error
09-14 06:59:35.489  5505  5551 I jxcore-log: 
09-14 06:59:35.489  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:59:35.489  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:59:35.489  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:59:35.489  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:35.489  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:59:35.489  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:35.489  5505  5551 I jxcore-log: 
,09-14 06:59:38.396  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:39.398  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:40.399  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:40.515  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:59:40.515  5505  5551 I jxcore-log: 
,09-14 06:59:40.516  5505  5551 I jxcore-log: websocket error
09-14 06:59:40.516  5505  5551 I jxcore-log: 
09-14 06:59:40.516  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:59:40.516  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:59:40.516  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:59:40.516  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:40.516  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:59:40.516  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:40.516  5505  5551 I jxcore-log: 
,09-14 06:59:41.400  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:42.401  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:43.401  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 06:59:45.543  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:59:45.543  5505  5551 I jxcore-log: 
,09-14 06:59:45.543  5505  5551 I jxcore-log: websocket error
09-14 06:59:45.543  5505  5551 I jxcore-log: 
09-14 06:59:45.543  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:59:45.543  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:59:45.543  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:59:45.543  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:45.543  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:59:45.543  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:45.543  5505  5551 I jxcore-log: 
,09-14 06:59:50.568  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:59:50.568  5505  5551 I jxcore-log: 
09-14 06:59:50.568  5505  5551 I jxcore-log: websocket error
09-14 06:59:50.568  5505  5551 I jxcore-log: 
09-14 06:59:50.569  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:59:50.569  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:59:50.569  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:59:50.569  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:50.569  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:59:50.569  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:50.569  5505  5551 I jxcore-log: 
,09-14 06:59:53.403  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:54.404  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:55.405  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:55.596  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 06:59:55.596  5505  5551 I jxcore-log: 
,09-14 06:59:55.596  5505  5551 I jxcore-log: websocket error
09-14 06:59:55.596  5505  5551 I jxcore-log: 
,09-14 06:59:55.596  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 06:59:55.596  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 06:59:55.596  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 06:59:55.596  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:55.596  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 06:59:55.596  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 06:59:55.596  5505  5551 I jxcore-log: 
,09-14 06:59:56.407  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:57.408  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:59:58.409  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 07:00:00.625  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:00:00.625  5505  5551 I jxcore-log: 
,09-14 07:00:00.625  5505  5551 I jxcore-log: websocket error
09-14 07:00:00.625  5505  5551 I jxcore-log: 
,09-14 07:00:00.626  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:00:00.626  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:00:00.626  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:00:00.626  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:00.626  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:00:00.626  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:00.626  5505  5551 I jxcore-log: 
,09-14 07:00:05.652  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:00:05.652  5505  5551 I jxcore-log: 
,09-14 07:00:05.652  5505  5551 I jxcore-log: websocket error
09-14 07:00:05.652  5505  5551 I jxcore-log: 
,09-14 07:00:05.653  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:00:05.653  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:00:05.653  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:00:05.653  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:05.653  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:00:05.653  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:05.653  5505  5551 I jxcore-log: 
,09-14 07:00:10.678  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:00:10.678  5505  5551 I jxcore-log: 
,09-14 07:00:10.679  5505  5551 I jxcore-log: websocket error
09-14 07:00:10.679  5505  5551 I jxcore-log: 
09-14 07:00:10.679  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:00:10.679  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:00:10.679  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:00:10.679  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:10.679  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:00:10.679  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:10.679  5505  5551 I jxcore-log: 
,09-14 07:00:13.410  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:00:14.411  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:00:15.412  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:00:15.703  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:00:15.703  5505  5551 I jxcore-log: 
09-14 07:00:15.704  5505  5551 I jxcore-log: websocket error
09-14 07:00:15.704  5505  5551 I jxcore-log: 
09-14 07:00:15.704  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:00:15.704  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:00:15.704  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:00:15.704  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:15.704  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:00:15.704  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:15.704  5505  5551 I jxcore-log: 
,09-14 07:00:16.413  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:00:17.413  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:00:18.414  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 07:00:20.729  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:00:20.729  5505  5551 I jxcore-log: 
,09-14 07:00:20.730  5505  5551 I jxcore-log: websocket error
09-14 07:00:20.730  5505  5551 I jxcore-log: 
,09-14 07:00:20.730  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:00:20.730  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:00:20.730  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:00:20.730  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:20.730  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:00:20.730  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:20.730  5505  5551 I jxcore-log: 
,09-14 07:00:25.759  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:00:25.759  5505  5551 I jxcore-log: 
09-14 07:00:25.760  5505  5551 I jxcore-log: websocket error
09-14 07:00:25.760  5505  5551 I jxcore-log: 
09-14 07:00:25.760  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:00:25.760  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:00:25.760  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:00:25.760  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:25.760  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:00:25.760  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:25.760  5505  5551 I jxcore-log: 
,09-14 07:00:30.784  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:00:30.784  5505  5551 I jxcore-log: 
,09-14 07:00:30.785  5505  5551 I jxcore-log: websocket error
09-14 07:00:30.785  5505  5551 I jxcore-log: 
09-14 07:00:30.785  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:00:30.785  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:00:30.785  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:00:30.785  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:30.785  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:00:30.785  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:30.785  5505  5551 I jxcore-log: 
,09-14 07:00:35.812  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:00:35.812  5505  5551 I jxcore-log: 
09-14 07:00:35.813  5505  5551 I jxcore-log: websocket error
09-14 07:00:35.813  5505  5551 I jxcore-log: 
09-14 07:00:35.813  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:00:35.813  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:00:35.813  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:00:35.813  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:35.813  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:00:35.813  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:35.813  5505  5551 I jxcore-log: 
,09-14 07:00:38.415  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:00:39.417  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:00:40.418  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:00:40.840  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:00:40.840  5505  5551 I jxcore-log: 
,09-14 07:00:40.840  5505  5551 I jxcore-log: websocket error
09-14 07:00:40.840  5505  5551 I jxcore-log: 
09-14 07:00:40.841  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:00:40.841  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:00:40.841  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:00:40.841  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:40.841  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:00:40.841  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:40.841  5505  5551 I jxcore-log: 
,09-14 07:00:41.419  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:00:42.420  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:00:43.421  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 07:00:45.865  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:00:45.865  5505  5551 I jxcore-log: 
09-14 07:00:45.865  5505  5551 I jxcore-log: websocket error
09-14 07:00:45.865  5505  5551 I jxcore-log: 
09-14 07:00:45.866  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:00:45.866  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:00:45.866  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:00:45.866  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:45.866  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:00:45.866  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:45.866  5505  5551 I jxcore-log: 
,09-14 07:00:50.891  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:00:50.891  5505  5551 I jxcore-log: 
,09-14 07:00:50.892  5505  5551 I jxcore-log: websocket error
09-14 07:00:50.892  5505  5551 I jxcore-log: 
09-14 07:00:50.892  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:00:50.892  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:00:50.892  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:00:50.892  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:50.892  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:00:50.892  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:50.892  5505  5551 I jxcore-log: 
,09-14 07:00:55.918  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:00:55.918  5505  5551 I jxcore-log: 
09-14 07:00:55.918  5505  5551 I jxcore-log: websocket error
09-14 07:00:55.918  5505  5551 I jxcore-log: 
,09-14 07:00:55.919  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:00:55.919  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:00:55.919  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:00:55.919  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:55.919  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:00:55.919  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:00:55.919  5505  5551 I jxcore-log: 
,09-14 07:01:00.946  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:01:00.946  5505  5551 I jxcore-log: 
,09-14 07:01:00.947  5505  5551 I jxcore-log: websocket error
09-14 07:01:00.947  5505  5551 I jxcore-log: 
,09-14 07:01:00.948  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:01:00.948  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:01:00.948  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:01:00.948  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:00.948  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:01:00.948  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:00.948  5505  5551 I jxcore-log: 
,09-14 07:01:05.973  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:01:05.973  5505  5551 I jxcore-log: 
,09-14 07:01:05.973  5505  5551 I jxcore-log: websocket error
09-14 07:01:05.973  5505  5551 I jxcore-log: 
09-14 07:01:05.973  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:01:05.973  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:01:05.973  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:01:05.973  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:05.973  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:01:05.973  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:05.973  5505  5551 I jxcore-log: 
,09-14 07:01:08.422  5888  5888 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-14 07:01:08.422  5888  5888 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 07:01:11.001  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:01:11.001  5505  5551 I jxcore-log: 
,09-14 07:01:11.003  5505  5551 I jxcore-log: websocket error
09-14 07:01:11.003  5505  5551 I jxcore-log: 
,09-14 07:01:11.005  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:01:11.005  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:01:11.005  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:01:11.005  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:11.005  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:01:11.005  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:11.005  5505  5551 I jxcore-log: 
,09-14 07:01:16.031  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:01:16.031  5505  5551 I jxcore-log: 
,09-14 07:01:16.031  5505  5551 I jxcore-log: websocket error
09-14 07:01:16.031  5505  5551 I jxcore-log: 
09-14 07:01:16.031  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:01:16.031  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:01:16.031  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:01:16.031  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:16.031  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:01:16.031  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:16.031  5505  5551 I jxcore-log: 
,09-14 07:01:21.056  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:01:21.056  5505  5551 I jxcore-log: 
,09-14 07:01:21.056  5505  5551 I jxcore-log: websocket error
09-14 07:01:21.056  5505  5551 I jxcore-log: 
,09-14 07:01:21.057  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:01:21.057  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:01:21.057  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:01:21.057  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:21.057  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:01:21.057  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:21.057  5505  5551 I jxcore-log: 
,09-14 07:01:23.423  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:24.424  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:25.425  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:26.084  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:01:26.084  5505  5551 I jxcore-log: 
09-14 07:01:26.085  5505  5551 I jxcore-log: websocket error
09-14 07:01:26.085  5505  5551 I jxcore-log: 
,09-14 07:01:26.085  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:01:26.085  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:01:26.085  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:01:26.085  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:26.085  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:01:26.085  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:26.085  5505  5551 I jxcore-log: 
,09-14 07:01:26.426  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:27.427  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:28.428  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 07:01:31.111  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:01:31.111  5505  5551 I jxcore-log: 
09-14 07:01:31.112  5505  5551 I jxcore-log: websocket error
09-14 07:01:31.112  5505  5551 I jxcore-log: 
09-14 07:01:31.112  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:01:31.112  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:01:31.112  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:01:31.112  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:31.112  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:01:31.112  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:31.112  5505  5551 I jxcore-log: 
,09-14 07:01:33.430  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:34.431  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:35.432  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:36.136  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:01:36.136  5505  5551 I jxcore-log: 
,09-14 07:01:36.137  5505  5551 I jxcore-log: websocket error
09-14 07:01:36.137  5505  5551 I jxcore-log: 
,09-14 07:01:36.137  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:01:36.137  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:01:36.137  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:01:36.137  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:36.137  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:01:36.137  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:36.137  5505  5551 I jxcore-log: 
,09-14 07:01:36.433  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:37.434  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:38.435  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 07:01:41.171  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:01:41.171  5505  5551 I jxcore-log: 
09-14 07:01:41.171  5505  5551 I jxcore-log: websocket error
09-14 07:01:41.171  5505  5551 I jxcore-log: 
,09-14 07:01:41.172  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:01:41.172  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:01:41.172  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:01:41.172  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:41.172  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:01:41.172  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:41.172  5505  5551 I jxcore-log: 
,09-14 07:01:46.196  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:01:46.196  5505  5551 I jxcore-log: 
,09-14 07:01:46.197  5505  5551 I jxcore-log: websocket error
09-14 07:01:46.197  5505  5551 I jxcore-log: 
,09-14 07:01:46.198  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:01:46.198  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:01:46.198  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:01:46.198  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:46.198  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:01:46.198  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:46.198  5505  5551 I jxcore-log: 
,09-14 07:01:48.436  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:49.438  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:50.439  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:51.225  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:01:51.225  5505  5551 I jxcore-log: 
,09-14 07:01:51.225  5505  5551 I jxcore-log: websocket error
09-14 07:01:51.225  5505  5551 I jxcore-log: 
09-14 07:01:51.225  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:01:51.225  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:01:51.225  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:01:51.225  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:51.225  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:01:51.225  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:51.225  5505  5551 I jxcore-log: 
,09-14 07:01:51.440  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:52.442  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:01:53.442  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 07:01:56.252  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:01:56.252  5505  5551 I jxcore-log: 
,09-14 07:01:56.253  5505  5551 I jxcore-log: websocket error
09-14 07:01:56.253  5505  5551 I jxcore-log: 
09-14 07:01:56.253  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:01:56.253  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:01:56.253  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:01:56.253  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:56.253  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:01:56.253  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:01:56.253  5505  5551 I jxcore-log: 
,09-14 07:02:01.279  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:02:01.279  5505  5551 I jxcore-log: 
09-14 07:02:01.280  5505  5551 I jxcore-log: websocket error
09-14 07:02:01.280  5505  5551 I jxcore-log: 
09-14 07:02:01.280  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:02:01.280  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:02:01.280  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:02:01.280  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:01.280  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:02:01.280  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:01.280  5505  5551 I jxcore-log: 
,09-14 07:02:06.306  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:02:06.306  5505  5551 I jxcore-log: 
09-14 07:02:06.307  5505  5551 I jxcore-log: websocket error
09-14 07:02:06.307  5505  5551 I jxcore-log: 
09-14 07:02:06.308  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:02:06.308  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:02:06.308  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:02:06.308  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:06.308  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:02:06.308  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:06.308  5505  5551 I jxcore-log: 
,09-14 07:02:08.444  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:02:09.445  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:02:10.447  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:02:11.331  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:02:11.331  5505  5551 I jxcore-log: 
,09-14 07:02:11.331  5505  5551 I jxcore-log: websocket error
09-14 07:02:11.331  5505  5551 I jxcore-log: 
09-14 07:02:11.331  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:02:11.331  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:02:11.331  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:02:11.331  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:11.331  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:02:11.331  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:11.331  5505  5551 I jxcore-log: 
,09-14 07:02:11.448  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:02:12.450  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:02:13.451  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 07:02:16.356  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:02:16.356  5505  5551 I jxcore-log: 
,09-14 07:02:16.357  5505  5551 I jxcore-log: websocket error
09-14 07:02:16.357  5505  5551 I jxcore-log: 
09-14 07:02:16.357  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:02:16.357  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:02:16.357  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:02:16.357  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:16.357  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:02:16.357  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:16.357  5505  5551 I jxcore-log: 
,09-14 07:02:21.384  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:02:21.384  5505  5551 I jxcore-log: 
09-14 07:02:21.384  5505  5551 I jxcore-log: websocket error
09-14 07:02:21.384  5505  5551 I jxcore-log: 
09-14 07:02:21.385  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:02:21.385  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:02:21.385  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:02:21.385  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:21.385  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:02:21.385  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:21.385  5505  5551 I jxcore-log: 
,09-14 07:02:26.411  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:02:26.411  5505  5551 I jxcore-log: 
,09-14 07:02:26.412  5505  5551 I jxcore-log: websocket error
09-14 07:02:26.412  5505  5551 I jxcore-log: 
,09-14 07:02:26.412  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:02:26.412  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:02:26.412  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:02:26.412  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:26.412  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:02:26.412  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:26.412  5505  5551 I jxcore-log: 
,09-14 07:02:31.436  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:02:31.436  5505  5551 I jxcore-log: 
09-14 07:02:31.436  5505  5551 I jxcore-log: websocket error
09-14 07:02:31.436  5505  5551 I jxcore-log: 
09-14 07:02:31.437  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:02:31.437  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:02:31.437  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:02:31.437  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:31.437  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:02:31.437  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:31.437  5505  5551 I jxcore-log: 
,09-14 07:02:33.452  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:02:34.453  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:02:35.454  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:02:36.456  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:02:36.469  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:02:36.469  5505  5551 I jxcore-log: 
09-14 07:02:36.469  5505  5551 I jxcore-log: websocket error
09-14 07:02:36.469  5505  5551 I jxcore-log: 
,09-14 07:02:36.469  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:02:36.469  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:02:36.469  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:02:36.469  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:36.469  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:02:36.469  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:36.469  5505  5551 I jxcore-log: 
,09-14 07:02:37.457  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:02:38.457  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 07:02:41.492  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:02:41.492  5505  5551 I jxcore-log: 
09-14 07:02:41.492  5505  5551 I jxcore-log: websocket error
09-14 07:02:41.492  5505  5551 I jxcore-log: 
,09-14 07:02:41.493  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:02:41.493  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:02:41.493  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:02:41.493  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:41.493  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:02:41.493  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:41.493  5505  5551 I jxcore-log: 
,09-14 07:02:46.518  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:02:46.518  5505  5551 I jxcore-log: 
,09-14 07:02:46.518  5505  5551 I jxcore-log: websocket error
09-14 07:02:46.518  5505  5551 I jxcore-log: 
09-14 07:02:46.519  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:02:46.519  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:02:46.519  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:02:46.519  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:46.519  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:02:46.519  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:46.519  5505  5551 I jxcore-log: 
,09-14 07:02:51.550  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:02:51.550  5505  5551 I jxcore-log: 
,09-14 07:02:51.550  5505  5551 I jxcore-log: websocket error
09-14 07:02:51.550  5505  5551 I jxcore-log: 
,09-14 07:02:51.551  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:02:51.551  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:02:51.551  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:02:51.551  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:51.551  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:02:51.551  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:51.551  5505  5551 I jxcore-log: 
,09-14 07:02:56.574  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:02:56.574  5505  5551 I jxcore-log: 
,09-14 07:02:56.574  5505  5551 I jxcore-log: websocket error
09-14 07:02:56.574  5505  5551 I jxcore-log: 
09-14 07:02:56.575  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:02:56.575  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:02:56.575  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:02:56.575  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:56.575  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:02:56.575  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:02:56.575  5505  5551 I jxcore-log: 
,09-14 07:03:01.599  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:03:01.599  5505  5551 I jxcore-log: 
09-14 07:03:01.599  5505  5551 I jxcore-log: websocket error
09-14 07:03:01.599  5505  5551 I jxcore-log: 
09-14 07:03:01.600  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:03:01.600  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:03:01.600  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:03:01.600  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:01.600  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:03:01.600  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:01.600  5505  5551 I jxcore-log: 
,09-14 07:03:03.458  5888  5888 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-14 07:03:03.458  5888  5888 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 07:03:06.626  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:03:06.626  5505  5551 I jxcore-log: 
,09-14 07:03:06.627  5505  5551 I jxcore-log: websocket error
09-14 07:03:06.627  5505  5551 I jxcore-log: 
,09-14 07:03:06.627  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:03:06.627  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:03:06.627  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:03:06.627  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:06.627  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:03:06.627  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:06.627  5505  5551 I jxcore-log: 
,09-14 07:03:11.654  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:03:11.654  5505  5551 I jxcore-log: 
,09-14 07:03:11.654  5505  5551 I jxcore-log: websocket error
09-14 07:03:11.654  5505  5551 I jxcore-log: 
,09-14 07:03:11.655  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:03:11.655  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:03:11.655  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:03:11.655  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:11.655  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:03:11.655  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:11.655  5505  5551 I jxcore-log: 
,09-14 07:03:16.684  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:03:16.684  5505  5551 I jxcore-log: 
,09-14 07:03:16.684  5505  5551 I jxcore-log: websocket error
09-14 07:03:16.684  5505  5551 I jxcore-log: 
09-14 07:03:16.684  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:03:16.684  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:03:16.684  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:03:16.684  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:16.684  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:03:16.684  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:16.684  5505  5551 I jxcore-log: 
,09-14 07:03:21.710  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:03:21.710  5505  5551 I jxcore-log: 
,09-14 07:03:21.711  5505  5551 I jxcore-log: websocket error
09-14 07:03:21.711  5505  5551 I jxcore-log: 
,09-14 07:03:21.713  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:03:21.713  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:03:21.713  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:03:21.713  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:21.713  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:03:21.713  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:21.713  5505  5551 I jxcore-log: 
,09-14 07:03:23.459  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:24.460  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:25.462  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:26.463  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:26.739  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:03:26.739  5505  5551 I jxcore-log: 
,09-14 07:03:26.740  5505  5551 I jxcore-log: websocket error
09-14 07:03:26.740  5505  5551 I jxcore-log: 
09-14 07:03:26.740  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:03:26.740  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:03:26.740  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:03:26.740  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:26.740  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:03:26.740  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:26.740  5505  5551 I jxcore-log: 
,09-14 07:03:27.464  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:28.465  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 07:03:31.765  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:03:31.765  5505  5551 I jxcore-log: 
09-14 07:03:31.766  5505  5551 I jxcore-log: websocket error
09-14 07:03:31.766  5505  5551 I jxcore-log: 
09-14 07:03:31.766  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:03:31.766  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:03:31.766  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:03:31.766  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:31.766  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:03:31.766  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:31.766  5505  5551 I jxcore-log: 
,09-14 07:03:33.466  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:34.467  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:35.468  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:36.469  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:36.793  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:03:36.793  5505  5551 I jxcore-log: 
09-14 07:03:36.793  5505  5551 I jxcore-log: websocket error
09-14 07:03:36.793  5505  5551 I jxcore-log: 
,09-14 07:03:36.794  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:03:36.794  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:03:36.794  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:03:36.794  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:36.794  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:03:36.794  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:36.794  5505  5551 I jxcore-log: 
,09-14 07:03:37.470  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:38.471  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 07:03:41.820  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:03:41.820  5505  5551 I jxcore-log: 
,09-14 07:03:41.820  5505  5551 I jxcore-log: websocket error
09-14 07:03:41.820  5505  5551 I jxcore-log: 
,09-14 07:03:41.820  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:03:41.820  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:03:41.820  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:03:41.820  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:41.820  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:03:41.820  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:41.820  5505  5551 I jxcore-log: 
,09-14 07:03:46.849  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:03:46.849  5505  5551 I jxcore-log: 
09-14 07:03:46.850  5505  5551 I jxcore-log: websocket error
09-14 07:03:46.850  5505  5551 I jxcore-log: 
09-14 07:03:46.850  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:03:46.850  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:03:46.850  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:03:46.850  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:46.850  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:03:46.850  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:46.850  5505  5551 I jxcore-log: 
,09-14 07:03:48.472  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:49.474  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:50.475  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:51.476  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:51.925  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:03:51.925  5505  5551 I jxcore-log: 
,09-14 07:03:51.926  5505  5551 I jxcore-log: websocket error
09-14 07:03:51.926  5505  5551 I jxcore-log: 
09-14 07:03:51.927  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:03:51.927  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:03:51.927  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:03:51.927  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:51.927  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:03:51.927  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:51.927  5505  5551 I jxcore-log: 
,09-14 07:03:52.478  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:03:53.479  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 07:03:56.955  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:03:56.955  5505  5551 I jxcore-log: 
,09-14 07:03:56.956  5505  5551 I jxcore-log: websocket error
09-14 07:03:56.956  5505  5551 I jxcore-log: 
09-14 07:03:56.956  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:03:56.956  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:03:56.956  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:03:56.956  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:56.956  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:03:56.956  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:03:56.956  5505  5551 I jxcore-log: 
,09-14 07:04:01.984  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:04:01.984  5505  5551 I jxcore-log: 
,09-14 07:04:01.985  5505  5551 I jxcore-log: websocket error
09-14 07:04:01.985  5505  5551 I jxcore-log: 
,09-14 07:04:01.986  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:04:01.986  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:04:01.986  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:04:01.986  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:01.986  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:04:01.986  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:01.986  5505  5551 I jxcore-log: 
,09-14 07:04:07.010  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:04:07.010  5505  5551 I jxcore-log: 
,09-14 07:04:07.011  5505  5551 I jxcore-log: websocket error
09-14 07:04:07.011  5505  5551 I jxcore-log: 
,09-14 07:04:07.013  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:04:07.013  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:04:07.013  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:04:07.013  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:07.013  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:04:07.013  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:07.013  5505  5551 I jxcore-log: 
,09-14 07:04:08.480  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:04:09.481  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:04:10.482  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:04:11.483  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:04:12.038  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:04:12.038  5505  5551 I jxcore-log: 
,09-14 07:04:12.039  5505  5551 I jxcore-log: websocket error
09-14 07:04:12.039  5505  5551 I jxcore-log: 
09-14 07:04:12.039  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:04:12.039  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:04:12.039  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:04:12.039  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:12.039  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:04:12.039  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:12.039  5505  5551 I jxcore-log: 
,09-14 07:04:12.485  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:04:13.485  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 07:04:17.066  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:04:17.066  5505  5551 I jxcore-log: 
09-14 07:04:17.067  5505  5551 I jxcore-log: websocket error
09-14 07:04:17.067  5505  5551 I jxcore-log: 
,09-14 07:04:17.067  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:04:17.067  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:04:17.067  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:04:17.067  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:17.067  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:04:17.067  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:17.067  5505  5551 I jxcore-log: 
,09-14 07:04:22.094  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:04:22.094  5505  5551 I jxcore-log: 
09-14 07:04:22.094  5505  5551 I jxcore-log: websocket error
09-14 07:04:22.094  5505  5551 I jxcore-log: 
,09-14 07:04:22.095  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:04:22.095  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:04:22.095  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:04:22.095  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:22.095  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:04:22.095  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:22.095  5505  5551 I jxcore-log: 
,09-14 07:04:27.123  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:04:27.123  5505  5551 I jxcore-log: 
,09-14 07:04:27.124  5505  5551 I jxcore-log: websocket error
09-14 07:04:27.124  5505  5551 I jxcore-log: 
09-14 07:04:27.124  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:04:27.124  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:04:27.124  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:04:27.124  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:27.124  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:04:27.124  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:27.124  5505  5551 I jxcore-log: 
,09-14 07:04:32.155  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:04:32.155  5505  5551 I jxcore-log: 
,09-14 07:04:32.155  5505  5551 I jxcore-log: websocket error
09-14 07:04:32.155  5505  5551 I jxcore-log: 
09-14 07:04:32.156  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:04:32.156  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:04:32.156  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:04:32.156  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:32.156  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:04:32.156  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:32.156  5505  5551 I jxcore-log: 
,09-14 07:04:33.486  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:04:34.488  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:04:35.489  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:04:36.490  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:04:37.182  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:04:37.182  5505  5551 I jxcore-log: 
09-14 07:04:37.183  5505  5551 I jxcore-log: websocket error
09-14 07:04:37.183  5505  5551 I jxcore-log: 
,09-14 07:04:37.183  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:04:37.183  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:04:37.183  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:04:37.183  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:37.183  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:04:37.183  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:37.183  5505  5551 I jxcore-log: 
,09-14 07:04:37.491  5888  5888 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:04:38.492  5888  5888 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 07:04:42.208  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:04:42.208  5505  5551 I jxcore-log: 
,09-14 07:04:42.208  5505  5551 I jxcore-log: websocket error
09-14 07:04:42.208  5505  5551 I jxcore-log: 
,09-14 07:04:42.209  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:04:42.209  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:04:42.209  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:04:42.209  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:42.209  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:04:42.209  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:42.209  5505  5551 I jxcore-log: 
,09-14 07:04:47.237  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:04:47.237  5505  5551 I jxcore-log: 
09-14 07:04:47.237  5505  5551 I jxcore-log: websocket error
09-14 07:04:47.237  5505  5551 I jxcore-log: 
09-14 07:04:47.238  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:04:47.238  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:04:47.238  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:04:47.238  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:47.238  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:04:47.238  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:47.238  5505  5551 I jxcore-log: 
,09-14 07:04:52.263  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:04:52.263  5505  5551 I jxcore-log: 
,09-14 07:04:52.263  5505  5551 I jxcore-log: websocket error
09-14 07:04:52.263  5505  5551 I jxcore-log: 
09-14 07:04:52.263  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:04:52.263  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:04:52.263  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:04:52.263  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:52.263  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:04:52.263  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:52.263  5505  5551 I jxcore-log: 
,09-14 07:04:57.296  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:04:57.296  5505  5551 I jxcore-log: 
,09-14 07:04:57.296  5505  5551 I jxcore-log: websocket error
09-14 07:04:57.296  5505  5551 I jxcore-log: 
09-14 07:04:57.297  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:04:57.297  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:04:57.297  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:04:57.297  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:57.297  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:04:57.297  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:04:57.297  5505  5551 I jxcore-log: 
,09-14 07:05:02.323  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:05:02.323  5505  5551 I jxcore-log: 
,09-14 07:05:02.324  5505  5551 I jxcore-log: websocket error
09-14 07:05:02.324  5505  5551 I jxcore-log: 
,09-14 07:05:02.325  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:05:02.325  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:05:02.325  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:05:02.325  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:02.325  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:05:02.325  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:02.325  5505  5551 I jxcore-log: 
,09-14 07:05:03.493  5888  5888 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-14 07:05:03.493  5888  5888 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 07:05:07.351  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:05:07.351  5505  5551 I jxcore-log: 
,09-14 07:05:07.352  5505  5551 I jxcore-log: websocket error
09-14 07:05:07.352  5505  5551 I jxcore-log: 
09-14 07:05:07.352  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:05:07.352  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:05:07.352  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:05:07.352  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:07.352  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:05:07.352  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:07.352  5505  5551 I jxcore-log: 
,09-14 07:05:12.378  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:05:12.378  5505  5551 I jxcore-log: 
,09-14 07:05:12.378  5505  5551 I jxcore-log: websocket error
09-14 07:05:12.378  5505  5551 I jxcore-log: 
09-14 07:05:12.379  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:05:12.379  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:05:12.379  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:05:12.379  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:12.379  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:05:12.379  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:12.379  5505  5551 I jxcore-log: 
,09-14 07:05:17.407  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:05:17.407  5505  5551 I jxcore-log: 
09-14 07:05:17.408  5505  5551 I jxcore-log: websocket error
09-14 07:05:17.408  5505  5551 I jxcore-log: 
09-14 07:05:17.408  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:05:17.408  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:05:17.408  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:05:17.408  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:17.408  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:05:17.408  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:17.408  5505  5551 I jxcore-log: 
,09-14 07:05:22.434  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:05:22.434  5505  5551 I jxcore-log: 
,09-14 07:05:22.435  5505  5551 I jxcore-log: websocket error
09-14 07:05:22.435  5505  5551 I jxcore-log: 
09-14 07:05:22.435  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:05:22.435  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:05:22.435  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:05:22.435  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:22.435  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:05:22.435  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:22.435  5505  5551 I jxcore-log: 
,09-14 07:05:27.465  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:05:27.465  5505  5551 I jxcore-log: 
09-14 07:05:27.466  5505  5551 I jxcore-log: websocket error
09-14 07:05:27.466  5505  5551 I jxcore-log: 
09-14 07:05:27.466  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:05:27.466  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:05:27.466  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:05:27.466  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:27.466  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:05:27.466  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:27.466  5505  5551 I jxcore-log: 
,09-14 07:05:28.505  5888  5890 E QC-QMI  : qmi_client [5888] 1d: failed to locate client data
,09-14 07:05:28.508   518   518 E QC-QMI  : qmuxd: RX on fd=16 returned error=0 errno[2:No such file or directory]
,09-14 07:05:28.509   518   518 E QC-QMI  : QMUX qmux_client_id=1d not found in qmux client list, unable to remove
,09-14 07:05:28.514  5888  5888 I Atfwd_Daemon: Stop the daemon....
,09-14 07:05:28.560  5903  5903 W ATFWD-daemon: type=1400 audit(0.0:121): avc: denied { read write } for name="diag" dev="tmpfs" ino=11991 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-14 07:05:28.561  5903  5903 I libmdmdetect: ESOC framework not supported
09-14 07:05:28.562  5903  5903 I libmdmdetect: Found internal modem: modem
09-14 07:05:28.562  5903  5903 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-14 07:05:28.571  5903  5903 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-14 07:05:28.571  5903  5903 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-14 07:05:28.572  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:29.576  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:30.577  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:31.578  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:32.491  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:05:32.491  5505  5551 I jxcore-log: 
,09-14 07:05:32.492  5505  5551 I jxcore-log: websocket error
09-14 07:05:32.492  5505  5551 I jxcore-log: 
09-14 07:05:32.492  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:05:32.492  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:05:32.492  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:05:32.492  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:32.492  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:05:32.492  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:32.492  5505  5551 I jxcore-log: 
,09-14 07:05:32.580  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:33.581  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 07:05:37.519  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:05:37.519  5505  5551 I jxcore-log: 
,09-14 07:05:37.519  5505  5551 I jxcore-log: websocket error
09-14 07:05:37.519  5505  5551 I jxcore-log: 
,09-14 07:05:37.519  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:05:37.519  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:05:37.519  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:05:37.519  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:37.519  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:05:37.519  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:37.519  5505  5551 I jxcore-log: 
,09-14 07:05:38.582  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:39.583  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:40.584  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:41.585  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:42.549  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:05:42.549  5505  5551 I jxcore-log: 
,09-14 07:05:42.550  5505  5551 I jxcore-log: websocket error
09-14 07:05:42.550  5505  5551 I jxcore-log: 
09-14 07:05:42.550  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:05:42.550  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:05:42.550  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:05:42.550  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:42.550  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:05:42.550  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:42.550  5505  5551 I jxcore-log: 
,09-14 07:05:42.586  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:43.587  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 07:05:47.577  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:05:47.577  5505  5551 I jxcore-log: 
,09-14 07:05:47.577  5505  5551 I jxcore-log: websocket error
09-14 07:05:47.577  5505  5551 I jxcore-log: 
,09-14 07:05:47.577  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:05:47.577  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:05:47.577  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:05:47.577  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:47.577  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:05:47.577  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:47.577  5505  5551 I jxcore-log: 
,09-14 07:05:52.605  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:05:52.605  5505  5551 I jxcore-log: 
09-14 07:05:52.606  5505  5551 I jxcore-log: websocket error
09-14 07:05:52.606  5505  5551 I jxcore-log: 
,09-14 07:05:52.608  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:05:52.608  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:05:52.608  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:05:52.608  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:52.608  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:05:52.608  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:52.608  5505  5551 I jxcore-log: 
,09-14 07:05:53.588  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:54.589  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:55.591  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:56.592  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:57.593  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:05:57.637  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:05:57.637  5505  5551 I jxcore-log: 
,09-14 07:05:57.637  5505  5551 I jxcore-log: websocket error
09-14 07:05:57.637  5505  5551 I jxcore-log: 
,09-14 07:05:57.638  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:05:57.638  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:05:57.638  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:05:57.638  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:57.638  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:05:57.638  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:05:57.638  5505  5551 I jxcore-log: 
,09-14 07:05:58.594  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 07:06:02.662  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:06:02.662  5505  5551 I jxcore-log: 
,09-14 07:06:02.663  5505  5551 I jxcore-log: websocket error
09-14 07:06:02.663  5505  5551 I jxcore-log: 
09-14 07:06:02.663  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:06:02.663  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:06:02.663  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:06:02.663  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:02.663  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:06:02.663  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:02.663  5505  5551 I jxcore-log: 
,09-14 07:06:07.691  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:06:07.691  5505  5551 I jxcore-log: 
,09-14 07:06:07.691  5505  5551 I jxcore-log: websocket error
09-14 07:06:07.691  5505  5551 I jxcore-log: 
,09-14 07:06:07.692  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:06:07.692  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:06:07.692  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:06:07.692  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:07.692  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:06:07.692  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:07.692  5505  5551 I jxcore-log: 
,09-14 07:06:12.719  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:06:12.719  5505  5551 I jxcore-log: 
,09-14 07:06:12.719  5505  5551 I jxcore-log: websocket error
09-14 07:06:12.719  5505  5551 I jxcore-log: 
09-14 07:06:12.720  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:06:12.720  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:06:12.720  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:06:12.720  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:12.720  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:06:12.720  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:12.720  5505  5551 I jxcore-log: 
,09-14 07:06:13.595  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:06:14.597  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:06:15.598  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:06:16.599  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:06:17.600  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:06:17.746  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:06:17.746  5505  5551 I jxcore-log: 
,09-14 07:06:17.747  5505  5551 I jxcore-log: websocket error
09-14 07:06:17.747  5505  5551 I jxcore-log: 
,09-14 07:06:17.747  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:06:17.747  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:06:17.747  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:06:17.747  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:17.747  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:06:17.747  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:17.747  5505  5551 I jxcore-log: 
,09-14 07:06:18.601  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 07:06:22.776  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:06:22.776  5505  5551 I jxcore-log: 
,09-14 07:06:22.776  5505  5551 I jxcore-log: websocket error
09-14 07:06:22.776  5505  5551 I jxcore-log: 
09-14 07:06:22.777  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:06:22.777  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:06:22.777  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:06:22.777  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:22.777  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:06:22.777  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:22.777  5505  5551 I jxcore-log: 
,09-14 07:06:22.885   926   938 I UsageStatsService: User[0] Flushing usage stats to disk
,09-14 07:06:27.805  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:06:27.805  5505  5551 I jxcore-log: 
,09-14 07:06:27.805  5505  5551 I jxcore-log: websocket error
09-14 07:06:27.805  5505  5551 I jxcore-log: 
09-14 07:06:27.806  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:06:27.806  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:06:27.806  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:06:27.806  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:27.806  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:06:27.806  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:27.806  5505  5551 I jxcore-log: 
,09-14 07:06:32.830  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:06:32.830  5505  5551 I jxcore-log: 
09-14 07:06:32.831  5505  5551 I jxcore-log: websocket error
09-14 07:06:32.831  5505  5551 I jxcore-log: 
09-14 07:06:32.831  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:06:32.831  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:06:32.831  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:06:32.831  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:32.831  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:06:32.831  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:32.831  5505  5551 I jxcore-log: 
,09-14 07:06:37.856  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:06:37.856  5505  5551 I jxcore-log: 
,09-14 07:06:37.856  5505  5551 I jxcore-log: websocket error
09-14 07:06:37.856  5505  5551 I jxcore-log: 
09-14 07:06:37.857  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:06:37.857  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:06:37.857  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:06:37.857  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:37.857  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:06:37.857  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:37.857  5505  5551 I jxcore-log: 
,09-14 07:06:38.602  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:06:39.604  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:06:40.605  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:06:41.606  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:06:42.607  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:06:42.884  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:06:42.884  5505  5551 I jxcore-log: 
,09-14 07:06:42.885  5505  5551 I jxcore-log: websocket error
09-14 07:06:42.885  5505  5551 I jxcore-log: 
,09-14 07:06:42.885  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:06:42.885  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:06:42.885  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:06:42.885  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:42.885  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:06:42.885  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:42.885  5505  5551 I jxcore-log: 
,09-14 07:06:43.608  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 07:06:47.910  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:06:47.910  5505  5551 I jxcore-log: 
,09-14 07:06:47.912  5505  5551 I jxcore-log: websocket error
09-14 07:06:47.912  5505  5551 I jxcore-log: 
,09-14 07:06:47.914  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:06:47.914  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:06:47.914  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:06:47.914  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:47.914  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:06:47.914  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:47.914  5505  5551 I jxcore-log: 
,09-14 07:06:52.939  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:06:52.939  5505  5551 I jxcore-log: 
09-14 07:06:52.940  5505  5551 I jxcore-log: websocket error
09-14 07:06:52.940  5505  5551 I jxcore-log: 
,09-14 07:06:52.940  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:06:52.940  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:06:52.940  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:06:52.940  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:52.940  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:06:52.940  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:52.940  5505  5551 I jxcore-log: 
,09-14 07:06:57.968  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:06:57.968  5505  5551 I jxcore-log: 
,09-14 07:06:57.969  5505  5551 I jxcore-log: websocket error
09-14 07:06:57.969  5505  5551 I jxcore-log: 
,09-14 07:06:57.969  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:06:57.969  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:06:57.969  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:06:57.969  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:57.969  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:06:57.969  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:06:57.969  5505  5551 I jxcore-log: 
,09-14 07:07:02.999  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:07:02.999  5505  5551 I jxcore-log: 
09-14 07:07:03.000  5505  5551 I jxcore-log: websocket error
09-14 07:07:03.000  5505  5551 I jxcore-log: 
09-14 07:07:03.000  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:07:03.000  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:07:03.000  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:07:03.000  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:03.000  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:07:03.000  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:03.000  5505  5551 I jxcore-log: 
,09-14 07:07:08.029  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:07:08.029  5505  5551 I jxcore-log: 
,09-14 07:07:08.029  5505  5551 I jxcore-log: websocket error
09-14 07:07:08.029  5505  5551 I jxcore-log: 
09-14 07:07:08.030  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:07:08.030  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:07:08.030  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:07:08.030  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:08.030  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:07:08.030  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:08.030  5505  5551 I jxcore-log: 
,09-14 07:07:08.609  5903  5903 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-14 07:07:08.609  5903  5903 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 07:07:13.053  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:07:13.053  5505  5551 I jxcore-log: 
,09-14 07:07:13.053  5505  5551 I jxcore-log: websocket error
09-14 07:07:13.053  5505  5551 I jxcore-log: 
09-14 07:07:13.054  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:07:13.054  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:07:13.054  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:07:13.054  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:13.054  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:07:13.054  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:13.054  5505  5551 I jxcore-log: 
,09-14 07:07:13.610  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:14.611  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:15.612  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:16.614  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:17.615  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:18.086  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:07:18.086  5505  5551 I jxcore-log: 
09-14 07:07:18.086  5505  5551 I jxcore-log: websocket error
09-14 07:07:18.086  5505  5551 I jxcore-log: 
09-14 07:07:18.087  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:07:18.087  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:07:18.087  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:07:18.087  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:18.087  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:07:18.087  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:18.087  5505  5551 I jxcore-log: 
,09-14 07:07:18.616  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 07:07:23.127  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:07:23.127  5505  5551 I jxcore-log: 
09-14 07:07:23.128  5505  5551 I jxcore-log: websocket error
09-14 07:07:23.128  5505  5551 I jxcore-log: 
09-14 07:07:23.128  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:07:23.128  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:07:23.128  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:07:23.128  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:23.128  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:07:23.128  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:23.128  5505  5551 I jxcore-log: 
,09-14 07:07:23.618  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:24.619  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:25.620  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:26.621  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:27.622  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:28.153  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:07:28.153  5505  5551 I jxcore-log: 
,09-14 07:07:28.154  5505  5551 I jxcore-log: websocket error
09-14 07:07:28.154  5505  5551 I jxcore-log: 
09-14 07:07:28.154  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:07:28.154  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:07:28.154  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:07:28.154  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:28.154  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:07:28.154  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:28.154  5505  5551 I jxcore-log: 
,09-14 07:07:28.623  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 07:07:33.181  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:07:33.181  5505  5551 I jxcore-log: 
,09-14 07:07:33.181  5505  5551 I jxcore-log: websocket error
09-14 07:07:33.181  5505  5551 I jxcore-log: 
09-14 07:07:33.181  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:07:33.181  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:07:33.181  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:07:33.181  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:33.181  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:07:33.181  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:33.181  5505  5551 I jxcore-log: 
,09-14 07:07:38.209  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:07:38.209  5505  5551 I jxcore-log: 
09-14 07:07:38.210  5505  5551 I jxcore-log: websocket error
09-14 07:07:38.210  5505  5551 I jxcore-log: 
09-14 07:07:38.210  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:07:38.210  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:07:38.210  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:07:38.210  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:38.210  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:07:38.210  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:38.210  5505  5551 I jxcore-log: 
,09-14 07:07:38.624  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:39.625  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:40.627  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:41.628  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:42.630  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:43.236  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:07:43.236  5505  5551 I jxcore-log: 
,09-14 07:07:43.236  5505  5551 I jxcore-log: websocket error
09-14 07:07:43.236  5505  5551 I jxcore-log: 
,09-14 07:07:43.237  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:07:43.237  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:07:43.237  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:07:43.237  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:43.237  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:07:43.237  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:43.237  5505  5551 I jxcore-log: 
,09-14 07:07:43.630  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 07:07:48.262  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:07:48.262  5505  5551 I jxcore-log: 
,09-14 07:07:48.263  5505  5551 I jxcore-log: websocket error
09-14 07:07:48.263  5505  5551 I jxcore-log: 
09-14 07:07:48.263  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:07:48.263  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:07:48.263  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:07:48.263  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:48.263  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:07:48.263  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:48.263  5505  5551 I jxcore-log: 
,09-14 07:07:53.289  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:07:53.289  5505  5551 I jxcore-log: 
09-14 07:07:53.289  5505  5551 I jxcore-log: websocket error
09-14 07:07:53.289  5505  5551 I jxcore-log: 
,09-14 07:07:53.289  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:07:53.289  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:07:53.289  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:07:53.289  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:53.289  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:07:53.289  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:53.289  5505  5551 I jxcore-log: 
,09-14 07:07:58.317  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:07:58.317  5505  5551 I jxcore-log: 
,09-14 07:07:58.318  5505  5551 I jxcore-log: websocket error
09-14 07:07:58.318  5505  5551 I jxcore-log: 
09-14 07:07:58.319  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:07:58.319  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:07:58.319  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:07:58.319  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:58.319  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:07:58.319  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:07:58.319  5505  5551 I jxcore-log: 
,09-14 07:07:58.632  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:07:59.633  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:08:00.634  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:08:01.636  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:08:02.637  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:08:03.342  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:08:03.342  5505  5551 I jxcore-log: 
,09-14 07:08:03.343  5505  5551 I jxcore-log: websocket error
09-14 07:08:03.343  5505  5551 I jxcore-log: 
09-14 07:08:03.343  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:08:03.343  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:08:03.343  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:08:03.343  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:03.343  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:08:03.343  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:03.343  5505  5551 I jxcore-log: 
,09-14 07:08:03.638  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 07:08:08.371  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:08:08.371  5505  5551 I jxcore-log: 
,09-14 07:08:08.373  5505  5551 I jxcore-log: websocket error
09-14 07:08:08.373  5505  5551 I jxcore-log: 
,09-14 07:08:08.373  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:08:08.373  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:08:08.373  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:08:08.373  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:08.373  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:08:08.373  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:08.373  5505  5551 I jxcore-log: 
,09-14 07:08:13.396  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:08:13.396  5505  5551 I jxcore-log: 
,09-14 07:08:13.396  5505  5551 I jxcore-log: websocket error
09-14 07:08:13.396  5505  5551 I jxcore-log: 
09-14 07:08:13.397  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:08:13.397  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:08:13.397  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:08:13.397  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:13.397  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:08:13.397  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:13.397  5505  5551 I jxcore-log: 
,09-14 07:08:18.425  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:08:18.425  5505  5551 I jxcore-log: 
09-14 07:08:18.425  5505  5551 I jxcore-log: websocket error
09-14 07:08:18.425  5505  5551 I jxcore-log: 
09-14 07:08:18.426  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:08:18.426  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:08:18.426  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:08:18.426  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:18.426  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:08:18.426  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:18.426  5505  5551 I jxcore-log: 
,09-14 07:08:23.453  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:08:23.453  5505  5551 I jxcore-log: 
09-14 07:08:23.453  5505  5551 I jxcore-log: websocket error
09-14 07:08:23.453  5505  5551 I jxcore-log: 
09-14 07:08:23.453  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:08:23.453  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:08:23.453  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:08:23.453  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:23.453  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:08:23.453  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:23.453  5505  5551 I jxcore-log: 
,09-14 07:08:23.639  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:08:24.640  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:08:25.642  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:08:26.643  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:08:27.644  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:08:28.479  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:08:28.479  5505  5551 I jxcore-log: 
09-14 07:08:28.479  5505  5551 I jxcore-log: websocket error
09-14 07:08:28.479  5505  5551 I jxcore-log: 
09-14 07:08:28.480  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:08:28.480  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:08:28.480  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:08:28.480  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:28.480  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:08:28.480  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:28.480  5505  5551 I jxcore-log: 
,09-14 07:08:28.645  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 07:08:33.524  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:08:33.524  5505  5551 I jxcore-log: 
09-14 07:08:33.524  5505  5551 I jxcore-log: websocket error
09-14 07:08:33.524  5505  5551 I jxcore-log: 
09-14 07:08:33.524  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:08:33.524  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:08:33.524  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:08:33.524  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:33.524  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:08:33.524  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:33.524  5505  5551 I jxcore-log: 
,09-14 07:08:38.550  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:08:38.550  5505  5551 I jxcore-log: 
,09-14 07:08:38.551  5505  5551 I jxcore-log: websocket error
09-14 07:08:38.551  5505  5551 I jxcore-log: 
09-14 07:08:38.551  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:08:38.551  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:08:38.551  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:08:38.551  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:38.551  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:08:38.551  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:38.551  5505  5551 I jxcore-log: 
,09-14 07:08:43.577  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:08:43.577  5505  5551 I jxcore-log: 
09-14 07:08:43.577  5505  5551 I jxcore-log: websocket error
09-14 07:08:43.577  5505  5551 I jxcore-log: 
09-14 07:08:43.578  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:08:43.578  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:08:43.578  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:08:43.578  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:43.578  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:08:43.578  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:43.578  5505  5551 I jxcore-log: 
,09-14 07:08:48.607  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:08:48.607  5505  5551 I jxcore-log: 
,09-14 07:08:48.608  5505  5551 I jxcore-log: websocket error
09-14 07:08:48.608  5505  5551 I jxcore-log: 
,09-14 07:08:48.608  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:08:48.608  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:08:48.608  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:08:48.608  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:48.608  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:08:48.608  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:48.608  5505  5551 I jxcore-log: 
,09-14 07:08:53.634  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:08:53.634  5505  5551 I jxcore-log: 
09-14 07:08:53.634  5505  5551 I jxcore-log: websocket error
09-14 07:08:53.634  5505  5551 I jxcore-log: 
09-14 07:08:53.635  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:08:53.635  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:08:53.635  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:08:53.635  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:53.635  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:08:53.635  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:53.635  5505  5551 I jxcore-log: 
09-14 07:08:53.645  5903  5903 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-14 07:08:53.646  5903  5903 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 07:08:58.661  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:08:58.661  5505  5551 I jxcore-log: 
09-14 07:08:58.662  5505  5551 I jxcore-log: websocket error
09-14 07:08:58.662  5505  5551 I jxcore-log: 
,09-14 07:08:58.662  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:08:58.662  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:08:58.662  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:08:58.662  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:58.662  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:08:58.662  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:08:58.662  5505  5551 I jxcore-log: 
,09-14 07:09:03.647  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:03.689  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:09:03.689  5505  5551 I jxcore-log: 
09-14 07:09:03.690  5505  5551 I jxcore-log: websocket error
09-14 07:09:03.690  5505  5551 I jxcore-log: 
09-14 07:09:03.690  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:09:03.690  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:09:03.690  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:09:03.690  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:03.690  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:09:03.690  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:03.690  5505  5551 I jxcore-log: 
,09-14 07:09:04.648  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:05.649  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:06.650  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:07.651  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:08.652  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 07:09:08.718  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:09:08.718  5505  5551 I jxcore-log: 
09-14 07:09:08.718  5505  5551 I jxcore-log: websocket error
09-14 07:09:08.718  5505  5551 I jxcore-log: 
09-14 07:09:08.718  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:09:08.718  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:09:08.718  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:09:08.718  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:08.718  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:09:08.718  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:08.718  5505  5551 I jxcore-log: 
,09-14 07:09:13.653  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:13.746  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:09:13.746  5505  5551 I jxcore-log: 
,09-14 07:09:13.747  5505  5551 I jxcore-log: websocket error
09-14 07:09:13.747  5505  5551 I jxcore-log: 
09-14 07:09:13.747  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:09:13.747  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:09:13.747  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:09:13.747  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:13.747  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:09:13.747  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:13.747  5505  5551 I jxcore-log: 
,09-14 07:09:14.654  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:15.656  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:16.657  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:17.658  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:18.659  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 07:09:18.775  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:09:18.775  5505  5551 I jxcore-log: 
,09-14 07:09:18.776  5505  5551 I jxcore-log: websocket error
09-14 07:09:18.776  5505  5551 I jxcore-log: 
09-14 07:09:18.776  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:09:18.776  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:09:18.776  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:09:18.776  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:18.776  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:09:18.776  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:18.776  5505  5551 I jxcore-log: 
,09-14 07:09:23.804  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:09:23.804  5505  5551 I jxcore-log: 
09-14 07:09:23.805  5505  5551 I jxcore-log: websocket error
09-14 07:09:23.805  5505  5551 I jxcore-log: 
09-14 07:09:23.805  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:09:23.805  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:09:23.805  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:09:23.805  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:23.805  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:09:23.805  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:23.805  5505  5551 I jxcore-log: 
,09-14 07:09:28.660  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:28.834  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:09:28.834  5505  5551 I jxcore-log: 
09-14 07:09:28.834  5505  5551 I jxcore-log: websocket error
09-14 07:09:28.834  5505  5551 I jxcore-log: 
09-14 07:09:28.835  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:09:28.835  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:09:28.835  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:09:28.835  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:28.835  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:09:28.835  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:28.835  5505  5551 I jxcore-log: 
,09-14 07:09:29.661  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:30.662  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:31.664  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:32.665  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:33.665  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 07:09:33.862  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:09:33.862  5505  5551 I jxcore-log: 
,09-14 07:09:33.863  5505  5551 I jxcore-log: websocket error
09-14 07:09:33.863  5505  5551 I jxcore-log: 
,09-14 07:09:33.863  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:09:33.863  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:09:33.863  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:09:33.863  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:33.863  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:09:33.863  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:33.863  5505  5551 I jxcore-log: 
,09-14 07:09:38.892  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:09:38.892  5505  5551 I jxcore-log: 
09-14 07:09:38.892  5505  5551 I jxcore-log: websocket error
09-14 07:09:38.892  5505  5551 I jxcore-log: 
09-14 07:09:38.893  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:09:38.893  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:09:38.893  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:09:38.893  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:38.893  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:09:38.893  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:38.893  5505  5551 I jxcore-log: 
,09-14 07:09:43.918  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:09:43.918  5505  5551 I jxcore-log: 
,09-14 07:09:43.918  5505  5551 I jxcore-log: websocket error
09-14 07:09:43.918  5505  5551 I jxcore-log: 
09-14 07:09:43.919  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:09:43.919  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:09:43.919  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:09:43.919  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:43.919  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:09:43.919  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:43.919  5505  5551 I jxcore-log: 
,09-14 07:09:48.667  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:48.944  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:09:48.944  5505  5551 I jxcore-log: 
,09-14 07:09:48.944  5505  5551 I jxcore-log: websocket error
09-14 07:09:48.944  5505  5551 I jxcore-log: 
09-14 07:09:48.945  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:09:48.945  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:09:48.945  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:09:48.945  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:48.945  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:09:48.945  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:48.945  5505  5551 I jxcore-log: 
,09-14 07:09:49.668  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:50.669  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:51.671  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:52.672  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:09:53.672  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 07:09:53.973  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:09:53.973  5505  5551 I jxcore-log: 
,09-14 07:09:53.973  5505  5551 I jxcore-log: websocket error
09-14 07:09:53.973  5505  5551 I jxcore-log: 
,09-14 07:09:53.973  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:09:53.973  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:09:53.973  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:09:53.973  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:53.973  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:09:53.973  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:53.973  5505  5551 I jxcore-log: 
,09-14 07:09:58.998  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:09:58.998  5505  5551 I jxcore-log: 
09-14 07:09:58.998  5505  5551 I jxcore-log: websocket error
09-14 07:09:58.998  5505  5551 I jxcore-log: 
09-14 07:09:58.999  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:09:58.999  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:09:58.999  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:09:58.999  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:58.999  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:09:58.999  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:09:58.999  5505  5551 I jxcore-log: 
,09-14 07:10:04.031  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:10:04.031  5505  5551 I jxcore-log: 
,09-14 07:10:04.031  5505  5551 I jxcore-log: websocket error
09-14 07:10:04.031  5505  5551 I jxcore-log: 
09-14 07:10:04.031  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:10:04.031  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:10:04.031  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:10:04.031  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:04.031  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:10:04.031  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:04.031  5505  5551 I jxcore-log: 
,09-14 07:10:09.056  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:10:09.056  5505  5551 I jxcore-log: 
,09-14 07:10:09.057  5505  5551 I jxcore-log: websocket error
09-14 07:10:09.057  5505  5551 I jxcore-log: 
,09-14 07:10:09.057  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:10:09.057  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:10:09.057  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:10:09.057  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:09.057  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:10:09.057  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:09.057  5505  5551 I jxcore-log: 
,09-14 07:10:13.674  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:10:14.085  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:10:14.085  5505  5551 I jxcore-log: 
,09-14 07:10:14.086  5505  5551 I jxcore-log: websocket error
09-14 07:10:14.086  5505  5551 I jxcore-log: 
,09-14 07:10:14.086  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:10:14.086  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:10:14.086  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:10:14.086  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:14.086  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:10:14.086  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:14.086  5505  5551 I jxcore-log: 
,09-14 07:10:14.675  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:10:15.676  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:10:16.678  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:10:17.679  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:10:18.680  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 07:10:19.114  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:10:19.114  5505  5551 I jxcore-log: 
09-14 07:10:19.115  5505  5551 I jxcore-log: websocket error
09-14 07:10:19.115  5505  5551 I jxcore-log: 
09-14 07:10:19.115  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:10:19.115  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:10:19.115  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:10:19.115  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:19.115  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:10:19.115  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:19.115  5505  5551 I jxcore-log: 
,09-14 07:10:24.141  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:10:24.141  5505  5551 I jxcore-log: 
09-14 07:10:24.142  5505  5551 I jxcore-log: websocket error
09-14 07:10:24.142  5505  5551 I jxcore-log: 
09-14 07:10:24.142  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:10:24.142  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:10:24.142  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:10:24.142  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:24.142  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:10:24.142  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:24.142  5505  5551 I jxcore-log: 
,09-14 07:10:29.167  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:10:29.167  5505  5551 I jxcore-log: 
,09-14 07:10:29.168  5505  5551 I jxcore-log: websocket error
09-14 07:10:29.168  5505  5551 I jxcore-log: 
09-14 07:10:29.168  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:10:29.168  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:10:29.168  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:10:29.168  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:29.168  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:10:29.168  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:29.168  5505  5551 I jxcore-log: 
,09-14 07:10:34.196  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:10:34.196  5505  5551 I jxcore-log: 
,09-14 07:10:34.196  5505  5551 I jxcore-log: websocket error
09-14 07:10:34.196  5505  5551 I jxcore-log: 
09-14 07:10:34.197  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:10:34.197  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:10:34.197  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:10:34.197  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:34.197  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:10:34.197  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:34.197  5505  5551 I jxcore-log: 
,09-14 07:10:39.226  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:10:39.226  5505  5551 I jxcore-log: 
09-14 07:10:39.226  5505  5551 I jxcore-log: websocket error
09-14 07:10:39.226  5505  5551 I jxcore-log: 
09-14 07:10:39.226  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:10:39.226  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:10:39.226  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:10:39.226  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:39.226  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:10:39.226  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:39.226  5505  5551 I jxcore-log: 
,09-14 07:10:43.681  5903  5903 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-14 07:10:43.681  5903  5903 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 07:10:44.253  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:10:44.253  5505  5551 I jxcore-log: 
,09-14 07:10:44.253  5505  5551 I jxcore-log: websocket error
09-14 07:10:44.253  5505  5551 I jxcore-log: 
,09-14 07:10:44.253  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:10:44.253  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:10:44.253  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:10:44.253  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:44.253  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:10:44.253  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:44.253  5505  5551 I jxcore-log: 
,09-14 07:10:49.282  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:10:49.282  5505  5551 I jxcore-log: 
,09-14 07:10:49.282  5505  5551 I jxcore-log: websocket error
09-14 07:10:49.282  5505  5551 I jxcore-log: 
09-14 07:10:49.283  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:10:49.283  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:10:49.283  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:10:49.283  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:49.283  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:10:49.283  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:49.283  5505  5551 I jxcore-log: 
,09-14 07:10:54.307  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:10:54.307  5505  5551 I jxcore-log: 
09-14 07:10:54.308  5505  5551 I jxcore-log: websocket error
09-14 07:10:54.308  5505  5551 I jxcore-log: 
09-14 07:10:54.308  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:10:54.308  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:10:54.308  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:10:54.308  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:54.308  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:10:54.308  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:54.308  5505  5551 I jxcore-log: 
,09-14 07:10:58.683  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:10:59.334  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:10:59.334  5505  5551 I jxcore-log: 
,09-14 07:10:59.335  5505  5551 I jxcore-log: websocket error
09-14 07:10:59.335  5505  5551 I jxcore-log: 
09-14 07:10:59.335  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:10:59.335  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:10:59.335  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:10:59.335  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:59.335  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:10:59.335  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:10:59.335  5505  5551 I jxcore-log: 
,09-14 07:10:59.684  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:00.685  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:01.687  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:02.688  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:03.689  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 07:11:04.362  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:11:04.362  5505  5551 I jxcore-log: 
09-14 07:11:04.363  5505  5551 I jxcore-log: websocket error
09-14 07:11:04.363  5505  5551 I jxcore-log: 
,09-14 07:11:04.363  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:11:04.363  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:11:04.363  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:11:04.363  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:04.363  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:11:04.363  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:04.363  5505  5551 I jxcore-log: 
,09-14 07:11:08.690  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:09.387  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:11:09.387  5505  5551 I jxcore-log: 
,09-14 07:11:09.387  5505  5551 I jxcore-log: websocket error
09-14 07:11:09.387  5505  5551 I jxcore-log: 
09-14 07:11:09.388  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:11:09.388  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:11:09.388  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:11:09.388  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:09.388  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:11:09.388  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:09.388  5505  5551 I jxcore-log: 
,09-14 07:11:09.691  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:10.692  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:11.693  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:12.695  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:13.696  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 07:11:14.411  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:11:14.411  5505  5551 I jxcore-log: 
,09-14 07:11:14.412  5505  5551 I jxcore-log: websocket error
09-14 07:11:14.412  5505  5551 I jxcore-log: 
09-14 07:11:14.412  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:11:14.412  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:11:14.412  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:11:14.412  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:14.412  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:11:14.412  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:14.412  5505  5551 I jxcore-log: 
,09-14 07:11:19.437  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:11:19.437  5505  5551 I jxcore-log: 
,09-14 07:11:19.437  5505  5551 I jxcore-log: websocket error
09-14 07:11:19.437  5505  5551 I jxcore-log: 
09-14 07:11:19.438  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:11:19.438  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:11:19.438  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:11:19.438  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:19.438  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:11:19.438  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:19.438  5505  5551 I jxcore-log: 
,09-14 07:11:23.697  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:24.463  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:11:24.463  5505  5551 I jxcore-log: 
,09-14 07:11:24.464  5505  5551 I jxcore-log: websocket error
09-14 07:11:24.464  5505  5551 I jxcore-log: 
09-14 07:11:24.464  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:11:24.464  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:11:24.464  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:11:24.464  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:24.464  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:11:24.464  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:24.464  5505  5551 I jxcore-log: 
,09-14 07:11:24.698  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:25.699  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:26.700  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:27.701  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:28.702  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 07:11:29.494  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:11:29.494  5505  5551 I jxcore-log: 
,09-14 07:11:29.494  5505  5551 I jxcore-log: websocket error
09-14 07:11:29.494  5505  5551 I jxcore-log: 
09-14 07:11:29.495  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:11:29.495  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:11:29.495  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:11:29.495  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:29.495  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:11:29.495  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:29.495  5505  5551 I jxcore-log: 
,09-14 07:11:34.524  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:11:34.524  5505  5551 I jxcore-log: 
09-14 07:11:34.524  5505  5551 I jxcore-log: websocket error
09-14 07:11:34.524  5505  5551 I jxcore-log: 
,09-14 07:11:34.525  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:11:34.525  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:11:34.525  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:11:34.525  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:34.525  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:11:34.525  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:34.525  5505  5551 I jxcore-log: 
,09-14 07:11:39.551  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:11:39.551  5505  5551 I jxcore-log: 
09-14 07:11:39.552  5505  5551 I jxcore-log: websocket error
09-14 07:11:39.552  5505  5551 I jxcore-log: 
09-14 07:11:39.552  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:11:39.552  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:11:39.552  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:11:39.552  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:39.552  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:11:39.552  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:39.552  5505  5551 I jxcore-log: 
,09-14 07:11:43.703  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:44.577  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:11:44.577  5505  5551 I jxcore-log: 
,09-14 07:11:44.578  5505  5551 I jxcore-log: websocket error
09-14 07:11:44.578  5505  5551 I jxcore-log: 
09-14 07:11:44.578  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:11:44.578  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:11:44.578  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:11:44.578  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:44.578  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:11:44.578  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:44.578  5505  5551 I jxcore-log: 
,09-14 07:11:44.705  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:45.706  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:46.707  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:47.708  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:11:48.709  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 07:11:49.602  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:11:49.602  5505  5551 I jxcore-log: 
,09-14 07:11:49.603  5505  5551 I jxcore-log: websocket error
09-14 07:11:49.603  5505  5551 I jxcore-log: 
09-14 07:11:49.603  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:11:49.603  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:11:49.603  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:11:49.603  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:49.603  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:11:49.603  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:49.603  5505  5551 I jxcore-log: 
,09-14 07:11:54.630  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:11:54.630  5505  5551 I jxcore-log: 
09-14 07:11:54.631  5505  5551 I jxcore-log: websocket error
09-14 07:11:54.631  5505  5551 I jxcore-log: 
09-14 07:11:54.631  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:11:54.631  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:11:54.631  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:11:54.631  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:54.631  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:11:54.631  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:54.631  5505  5551 I jxcore-log: 
,09-14 07:11:59.656  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:11:59.656  5505  5551 I jxcore-log: 
09-14 07:11:59.656  5505  5551 I jxcore-log: websocket error
09-14 07:11:59.656  5505  5551 I jxcore-log: 
09-14 07:11:59.656  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:11:59.656  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:11:59.656  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:11:59.656  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:59.656  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:11:59.656  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:11:59.656  5505  5551 I jxcore-log: 
,09-14 07:12:04.682  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:12:04.682  5505  5551 I jxcore-log: 
,09-14 07:12:04.683  5505  5551 I jxcore-log: websocket error
09-14 07:12:04.683  5505  5551 I jxcore-log: 
09-14 07:12:04.683  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:12:04.683  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:12:04.683  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:12:04.683  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:04.683  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:12:04.683  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:04.683  5505  5551 I jxcore-log: 
,09-14 07:12:08.710  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:12:09.711  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:12:09.711  5505  5551 I jxcore-log: 
,09-14 07:12:09.712  5505  5551 I jxcore-log: websocket error
09-14 07:12:09.712  5505  5551 I jxcore-log: 
09-14 07:12:09.712  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
09-14 07:12:09.712  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:12:09.712  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:12:09.712  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:12:09.712  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:09.712  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:12:09.712  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:09.712  5505  5551 I jxcore-log: 
,09-14 07:12:10.713  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:12:11.714  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:12:12.715  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:12:13.716  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 07:12:14.739  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:12:14.739  5505  5551 I jxcore-log: 
,09-14 07:12:14.739  5505  5551 I jxcore-log: websocket error
09-14 07:12:14.739  5505  5551 I jxcore-log: 
09-14 07:12:14.739  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:12:14.739  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:12:14.739  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:12:14.739  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:14.739  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:12:14.739  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:14.739  5505  5551 I jxcore-log: 
,09-14 07:12:19.765  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:12:19.765  5505  5551 I jxcore-log: 
,09-14 07:12:19.766  5505  5551 I jxcore-log: websocket error
09-14 07:12:19.766  5505  5551 I jxcore-log: 
09-14 07:12:19.766  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:12:19.766  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:12:19.766  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:12:19.766  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:19.766  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:12:19.766  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:19.766  5505  5551 I jxcore-log: 
,09-14 07:12:24.793  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:12:24.793  5505  5551 I jxcore-log: 
,09-14 07:12:24.793  5505  5551 I jxcore-log: websocket error
09-14 07:12:24.793  5505  5551 I jxcore-log: 
09-14 07:12:24.794  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:12:24.794  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:12:24.794  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:12:24.794  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:24.794  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:12:24.794  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:24.794  5505  5551 I jxcore-log: 
,09-14 07:12:26.586  5801  5829 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=1
,09-14 07:12:29.820  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:12:29.820  5505  5551 I jxcore-log: 
09-14 07:12:29.824  5505  5551 I jxcore-log: websocket error
09-14 07:12:29.824  5505  5551 I jxcore-log: 
09-14 07:12:29.825  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:12:29.825  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:12:29.825  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:12:29.825  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:29.825  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:12:29.825  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:29.825  5505  5551 I jxcore-log: 
,09-14 07:12:34.851  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:12:34.851  5505  5551 I jxcore-log: 
09-14 07:12:34.852  5505  5551 I jxcore-log: websocket error
09-14 07:12:34.852  5505  5551 I jxcore-log: 
09-14 07:12:34.852  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:12:34.852  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:12:34.852  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:12:34.852  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:34.852  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:12:34.852  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:34.852  5505  5551 I jxcore-log: 
,09-14 07:12:38.716  5903  5903 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-14 07:12:38.717  5903  5903 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 07:12:39.875  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:12:39.875  5505  5551 I jxcore-log: 
,09-14 07:12:39.876  5505  5551 I jxcore-log: websocket error
09-14 07:12:39.876  5505  5551 I jxcore-log: 
,09-14 07:12:39.876  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:12:39.876  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:12:39.876  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:12:39.876  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:39.876  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:12:39.876  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:39.876  5505  5551 I jxcore-log: 
,09-14 07:12:44.905  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:12:44.905  5505  5551 I jxcore-log: 
,09-14 07:12:44.905  5505  5551 I jxcore-log: websocket error
09-14 07:12:44.905  5505  5551 I jxcore-log: 
09-14 07:12:44.906  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:12:44.906  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:12:44.906  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:12:44.906  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:44.906  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:12:44.906  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:44.906  5505  5551 I jxcore-log: 
,09-14 07:12:49.931  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:12:49.931  5505  5551 I jxcore-log: 
09-14 07:12:49.932  5505  5551 I jxcore-log: websocket error
09-14 07:12:49.932  5505  5551 I jxcore-log: 
,09-14 07:12:49.932  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:12:49.932  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:12:49.932  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:12:49.932  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:49.932  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:12:49.932  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:49.932  5505  5551 I jxcore-log: 
,09-14 07:12:54.956  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:12:54.956  5505  5551 I jxcore-log: 
,09-14 07:12:54.957  5505  5551 I jxcore-log: websocket error
09-14 07:12:54.957  5505  5551 I jxcore-log: 
,09-14 07:12:54.958  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:12:54.958  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:12:54.958  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:12:54.958  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:54.958  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:12:54.958  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:54.958  5505  5551 I jxcore-log: 
,09-14 07:12:58.718  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:12:59.719  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:12:59.984  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:12:59.984  5505  5551 I jxcore-log: 
09-14 07:12:59.984  5505  5551 I jxcore-log: websocket error
09-14 07:12:59.984  5505  5551 I jxcore-log: 
09-14 07:12:59.984  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:12:59.984  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:12:59.984  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:12:59.984  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:59.984  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:12:59.984  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:12:59.984  5505  5551 I jxcore-log: 
,09-14 07:13:00.720  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:01.721  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:02.723  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:03.723  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 07:13:05.011  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:13:05.011  5505  5551 I jxcore-log: 
09-14 07:13:05.011  5505  5551 I jxcore-log: websocket error
09-14 07:13:05.011  5505  5551 I jxcore-log: 
09-14 07:13:05.012  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:13:05.012  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:13:05.012  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:13:05.012  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:05.012  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:13:05.012  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:05.012  5505  5551 I jxcore-log: 
,09-14 07:13:08.725  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:09.726  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:10.038  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:13:10.038  5505  5551 I jxcore-log: 
,09-14 07:13:10.039  5505  5551 I jxcore-log: websocket error
09-14 07:13:10.039  5505  5551 I jxcore-log: 
09-14 07:13:10.039  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:13:10.039  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:13:10.039  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:13:10.039  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:10.039  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:13:10.039  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:10.039  5505  5551 I jxcore-log: 
,09-14 07:13:10.727  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:11.728  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:12.729  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:13.730  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 07:13:15.065  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:13:15.065  5505  5551 I jxcore-log: 
,09-14 07:13:15.065  5505  5551 I jxcore-log: websocket error
09-14 07:13:15.065  5505  5551 I jxcore-log: 
09-14 07:13:15.066  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:13:15.066  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:13:15.066  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:13:15.066  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:15.066  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:13:15.066  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:15.066  5505  5551 I jxcore-log: 
,09-14 07:13:20.099  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:13:20.099  5505  5551 I jxcore-log: 
09-14 07:13:20.100  5505  5551 I jxcore-log: websocket error
09-14 07:13:20.100  5505  5551 I jxcore-log: 
,09-14 07:13:20.101  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:13:20.101  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:13:20.101  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:13:20.101  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:20.101  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:13:20.101  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:20.101  5505  5551 I jxcore-log: 
,09-14 07:13:23.732  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:24.733  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:25.125  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:13:25.125  5505  5551 I jxcore-log: 
,09-14 07:13:25.126  5505  5551 I jxcore-log: websocket error
09-14 07:13:25.126  5505  5551 I jxcore-log: 
,09-14 07:13:25.126  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:13:25.126  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:13:25.126  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:13:25.126  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:25.126  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:13:25.126  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:25.126  5505  5551 I jxcore-log: 
,09-14 07:13:25.734  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:26.735  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:27.736  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:28.737  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 07:13:30.153  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:13:30.153  5505  5551 I jxcore-log: 
09-14 07:13:30.153  5505  5551 I jxcore-log: websocket error
09-14 07:13:30.153  5505  5551 I jxcore-log: 
09-14 07:13:30.153  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:13:30.153  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:13:30.153  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:13:30.153  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:30.153  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:13:30.153  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:30.153  5505  5551 I jxcore-log: 
,09-14 07:13:35.180  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:13:35.180  5505  5551 I jxcore-log: 
09-14 07:13:35.181  5505  5551 I jxcore-log: websocket error
09-14 07:13:35.181  5505  5551 I jxcore-log: 
09-14 07:13:35.181  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:13:35.181  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:13:35.181  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:13:35.181  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:35.181  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:13:35.181  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:35.181  5505  5551 I jxcore-log: 
,09-14 07:13:40.208  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:13:40.208  5505  5551 I jxcore-log: 
,09-14 07:13:40.208  5505  5551 I jxcore-log: websocket error
09-14 07:13:40.208  5505  5551 I jxcore-log: 
09-14 07:13:40.209  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:13:40.209  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:13:40.209  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:13:40.209  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:40.209  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:13:40.209  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:40.209  5505  5551 I jxcore-log: 
,09-14 07:13:43.739  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:44.740  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:45.233  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:13:45.233  5505  5551 I jxcore-log: 
,09-14 07:13:45.233  5505  5551 I jxcore-log: websocket error
09-14 07:13:45.233  5505  5551 I jxcore-log: 
,09-14 07:13:45.233  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:13:45.233  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:13:45.233  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:13:45.233  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:45.233  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:13:45.233  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:45.233  5505  5551 I jxcore-log: 
,09-14 07:13:45.741  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:46.742  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:47.744  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:13:48.745  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 07:13:50.259  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:13:50.259  5505  5551 I jxcore-log: 
09-14 07:13:50.259  5505  5551 I jxcore-log: websocket error
09-14 07:13:50.259  5505  5551 I jxcore-log: 
09-14 07:13:50.260  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:13:50.260  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:13:50.260  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:13:50.260  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:50.260  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:13:50.260  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:50.260  5505  5551 I jxcore-log: 
,09-14 07:13:55.290  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:13:55.290  5505  5551 I jxcore-log: 
,09-14 07:13:55.290  5505  5551 I jxcore-log: websocket error
09-14 07:13:55.290  5505  5551 I jxcore-log: 
09-14 07:13:55.290  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:13:55.290  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:13:55.290  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:13:55.290  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:55.290  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:13:55.290  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:13:55.290  5505  5551 I jxcore-log: 
,09-14 07:14:00.315  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:14:00.315  5505  5551 I jxcore-log: 
,09-14 07:14:00.316  5505  5551 I jxcore-log: websocket error
09-14 07:14:00.316  5505  5551 I jxcore-log: 
09-14 07:14:00.316  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:14:00.316  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:14:00.316  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:14:00.316  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:00.316  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:14:00.316  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:00.316  5505  5551 I jxcore-log: 
,09-14 07:14:05.341  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:14:05.341  5505  5551 I jxcore-log: 
,09-14 07:14:05.342  5505  5551 I jxcore-log: websocket error
09-14 07:14:05.342  5505  5551 I jxcore-log: 
09-14 07:14:05.342  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:14:05.342  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:14:05.342  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:14:05.342  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:05.342  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:14:05.342  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:05.342  5505  5551 I jxcore-log: 
,09-14 07:14:08.746  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:14:09.747  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:14:10.368  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:14:10.368  5505  5551 I jxcore-log: 
09-14 07:14:10.368  5505  5551 I jxcore-log: websocket error
09-14 07:14:10.368  5505  5551 I jxcore-log: 
09-14 07:14:10.369  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:14:10.369  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:14:10.369  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:14:10.369  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:10.369  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:14:10.369  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:10.369  5505  5551 I jxcore-log: 
,09-14 07:14:10.748  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:14:11.749  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:14:12.751  5903  5903 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 07:14:13.751  5903  5903 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 07:14:15.444  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:14:15.444  5505  5551 I jxcore-log: 
,09-14 07:14:15.444  5505  5551 I jxcore-log: websocket error
09-14 07:14:15.444  5505  5551 I jxcore-log: 
,09-14 07:14:15.444  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:14:15.444  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:14:15.444  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:14:15.444  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:15.444  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:14:15.444  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:15.444  5505  5551 I jxcore-log: 
,09-14 07:14:20.485  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:14:20.485  5505  5551 I jxcore-log: 
09-14 07:14:20.486  5505  5551 I jxcore-log: websocket error
09-14 07:14:20.486  5505  5551 I jxcore-log: 
09-14 07:14:20.486  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:14:20.486  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:14:20.486  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:14:20.486  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:20.486  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:14:20.486  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:20.486  5505  5551 I jxcore-log: 
,09-14 07:14:25.537  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:14:25.537  5505  5551 I jxcore-log: 
,09-14 07:14:25.537  5505  5551 I jxcore-log: websocket error
09-14 07:14:25.537  5505  5551 I jxcore-log: 
09-14 07:14:25.538  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:14:25.538  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:14:25.538  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:14:25.538  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:25.538  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:14:25.538  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:25.538  5505  5551 I jxcore-log: 
,09-14 07:14:30.589  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:14:30.589  5505  5551 I jxcore-log: 
09-14 07:14:30.589  5505  5551 I jxcore-log: websocket error
09-14 07:14:30.589  5505  5551 I jxcore-log: 
,09-14 07:14:30.589  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:14:30.589  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:14:30.589  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:14:30.589  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:30.589  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:14:30.589  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:30.589  5505  5551 I jxcore-log: 
,09-14 07:14:35.613  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:14:35.613  5505  5551 I jxcore-log: 
,09-14 07:14:35.613  5505  5551 I jxcore-log: websocket error
09-14 07:14:35.613  5505  5551 I jxcore-log: 
09-14 07:14:35.614  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:14:35.614  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:14:35.614  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:14:35.614  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:35.614  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:14:35.614  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:35.614  5505  5551 I jxcore-log: 
,09-14 07:14:38.752  5903  5903 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-14 07:14:38.752  5903  5903 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 07:14:40.641  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:14:40.641  5505  5551 I jxcore-log: 
,09-14 07:14:40.641  5505  5551 I jxcore-log: websocket error
09-14 07:14:40.641  5505  5551 I jxcore-log: 
09-14 07:14:40.641  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:14:40.641  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:14:40.641  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:14:40.641  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:40.641  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:14:40.641  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:40.641  5505  5551 I jxcore-log: 
,09-14 07:14:45.666  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:14:45.666  5505  5551 I jxcore-log: 
09-14 07:14:45.666  5505  5551 I jxcore-log: websocket error
09-14 07:14:45.666  5505  5551 I jxcore-log: 
09-14 07:14:45.666  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:14:45.666  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:14:45.666  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:14:45.666  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:45.666  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:14:45.666  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:45.666  5505  5551 I jxcore-log: 
,09-14 07:14:50.693  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:14:50.693  5505  5551 I jxcore-log: 
,09-14 07:14:50.693  5505  5551 I jxcore-log: websocket error
09-14 07:14:50.693  5505  5551 I jxcore-log: 
09-14 07:14:50.693  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:14:50.693  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:14:50.693  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:14:50.693  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:50.693  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:14:50.693  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:50.693  5505  5551 I jxcore-log: 
,09-14 07:14:55.719  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:14:55.719  5505  5551 I jxcore-log: 
,09-14 07:14:55.720  5505  5551 I jxcore-log: websocket error
09-14 07:14:55.720  5505  5551 I jxcore-log: 
09-14 07:14:55.720  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:14:55.720  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:14:55.720  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:14:55.720  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:55.720  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:14:55.720  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:14:55.720  5505  5551 I jxcore-log: 
,09-14 07:15:00.745  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:15:00.745  5505  5551 I jxcore-log: 
,09-14 07:15:00.746  5505  5551 I jxcore-log: websocket error
09-14 07:15:00.746  5505  5551 I jxcore-log: 
09-14 07:15:00.746  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:15:00.746  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:15:00.746  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:15:00.746  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:15:00.746  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:15:00.746  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:15:00.746  5505  5551 I jxcore-log: 
,09-14 07:15:03.766  5903  5905 E QC-QMI  : qmi_client [5903] 1e: failed to locate client data
,09-14 07:15:03.770   518   518 E QC-QMI  : qmuxd: RX on fd=16 returned error=0 errno[2:No such file or directory]
,09-14 07:15:03.770   518   518 E QC-QMI  : QMUX qmux_client_id=1e not found in qmux client list, unable to remove
,09-14 07:15:03.774  5903  5903 I Atfwd_Daemon: Stop the daemon....
,09-14 07:15:03.894  5918  5918 I libmdmdetect: ESOC framework not supported
,09-14 07:15:03.894  5918  5918 I libmdmdetect: Found internal modem: modem
,09-14 07:15:03.895  5918  5918 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-14 07:15:03.893  5918  5918 W ATFWD-daemon: type=1400 audit(0.0:122): avc: denied { read write } for name="diag" dev="tmpfs" ino=11991 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-14 07:15:03.904  5918  5918 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
09-14 07:15:03.904  5918  5918 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-14 07:15:03.905  5918  5918 I ServiceManager: Waiting for service AtCmdFwd...
,TIME-OUT KILL (timeout was 1400000ms),09-14 07:15:04.909  5918  5918 I ServiceManager: Waiting for service AtCmdFwd...
09-14 07:15:05.764  5925  5925 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-14 07:15:05.772  5505  5551 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 07:15:05.772  5505  5551 I jxcore-log: 
09-14 07:15:05.773  5505  5551 I jxcore-log: websocket error
09-14 07:15:05.773  5505  5551 I jxcore-log: 
09-14 07:15:05.773  5505  5551 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 07:15:05.773  5505  5551 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 07:15:05.773  5505  5551 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 07:15:05.773  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:15:05.773  5505  5551 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 07:15:05.773  5505  5551 I jxcore-log: emit@events.js:82:1
09-14 07:15:05.773  5505  5551 I jxcore-log: 
09-14 07:15:05.786  5925  5925 D AndroidRuntime: CheckJNI is OFF
09-14 07:15:05.810  5925  5925 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-14 07:15:05.838  5925  5925 I Radio-JNI: register_android_hardware_Radio DONE
09-14 07:15:05.854  5925  5925 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-14 07:15:05.861   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-14 07:15:05.862   926   939 I ActivityManager: Killing 5505:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
09-14 07:15:05.905   926  2950 W InputDispatcher: channel '62b1f03 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-14 07:15:05.905   926  2950 E InputDispatcher: channel '62b1f03 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
09-14 07:15:05.909   926  3206 I WindowState: WIN DEATH: Window{62b1f03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-14 07:15:05.909   926  2991 D WifiService: Client connection lost with reason: 4
09-14 07:15:05.909   926  3206 W InputDispatcher: Attempted to unregister already unregistered input channel '62b1f03 com.test.thalitest/com.test.thalitest.MainActivity (server)'
09-14 07:15:05.911   926  3168 D GraphicsStats: Buffer count: 2
09-14 07:15:05.910  5918  5918 I ServiceManager: Waiting for service AtCmdFwd...
09-14 07:15:05.989   926   939 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-14 07:15:05.989   926   939 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-14 07:15:05.990   926   939 E ActivityManager: Failure starting process com.test.thalitest
09-14 07:15:05.990   926   939 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-14 07:15:05.990   926   939 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 07:15:05.990   926   939 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-14 07:15:05.990   926   939 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 07:15:05.990   926   939 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-14 07:15:05.990   926   939 I ActivityManager:   Force finishing activity ActivityRecord{bbc3e4c u0 com.test.thalitest/.MainActivity t2}
09-14 07:15:05.992   926   949 I art     : Starting a blocking GC Explicit
09-14 07:15:06.001   926  3567 W ActivityManager: Spurious death for ProcessRecord{e62c25b 0:com.test.thalitest/u0a77}, curProc for 5505: null
09-14 07:15:06.085   926   949 I art     : Explicit concurrent mark sweep GC freed 41153(2MB) AllocSpace objects, 41(900KB) LOS objects, 33% free, 28MB/43MB, paused 2.031ms total 92.274ms
09-14 07:15:06.108   926   949 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-14 07:15:06.112  5925  5925 I art     : System.exit called, status: 0
09-14 07:15:06.112  5925  5925 I AndroidRuntime: VM exiting with result code 0.
09-14 07:15:06.126   926   949 I ActivityManager: Start proc 5935:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-14 07:15:06.127   926   949 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
09-14 07:15:06.135   926   939 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-14 07:15:06.140  5801  5801 D BluetoothMapAppObserver: onReceive
09-14 07:15:06.143  5801  5801 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-14 07:15:06.150  3432  3432 I Keyboard.Facilitator: resetDictionaries() : en_US
09-14 07:15:06.150  3648  3967 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-14 07:15:06.161   926  2951 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-14 07:15:06.187  3432  5948 I Keyboard.Facilitator.DecoderInitializer: run()
09-14 07:15:06.201  3432  5948 I Decoder : createOrResetDecoder
09-14 07:15:06.203  3418  5950 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-14 07:15:06.203   214   214 W kworker/1:2: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-14 07:15:06.215  3523  3523 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-14 07:15:06.213   214   214 W kworker/1:2: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-14 07:15:06.226   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-14 07:15:06.227   214   214 W kworker/1:2: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-14 07:15:06.247   926   938 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-14 07:15:06.248   926   938 E PackageManager: Failed to write settings, restoring backup
09-14 07:15:06.248   926   938 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-14 07:15:06.248   926   938 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-14 07:15:06.248   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-14 07:15:06.248   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-14 07:15:06.248   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-14 07:15:06.248   926   938 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 07:15:06.248   926   938 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-14 07:15:06.248   926   938 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 07:15:06.252  3604  3604 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-14 07:15:06.253   926   939 E DropBoxManagerService: Can't write: system_server_wtf
09-14 07:15:06.253   926   939 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-14 07:15:06.253   926   939 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 07:15:06.253   926   939 E DropBoxManagerService: 	... 13 more
09-14 07:15:06.253  3604  3604 D AndroidRuntime: Shutting down VM
--------- beginning of crash
09-14 07:15:06.254  3604  3604 E AndroidRuntime: FATAL EXCEPTION: main
09-14 07:15:06.254  3604  3604 E AndroidRuntime: Process: com.google.process.gapps, PID: 3604
09-14 07:15:06.254  3604  3604 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-14 07:15:06.254  3604  3604 E AndroidRuntime: 	... 8 more
09-14 07:15:06.261   926  5954 E DropBoxManagerService: Can't write: system_app_crash
09-14 07:15:06.261   926  5954 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
09-14 07:15:06.261   926  5954 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-14 07:15:06.261   926  5954 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-14 07:15:06.261   926  5954 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-14 07:15:06.261   926  5954 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-14 07:15:06.261   926  5954 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-14 07:15:06.261   926  5954 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-14 07:15:06.261   926  5954 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-14 07:15:06.261   926  5954 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-14 07:15:06.261   926  5954 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-14 07:15:06.261   926  5954 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 07:15:06.261   926  5954 E DropBoxManagerService: 	... 5 more
09-14 07:15:06.263  3604  3604 I Process : Sending signal. PID: 3604 SIG: 9
09-14 07:15:06.265  3566  3693 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-14 07:15:06.278   926   937 I ActivityManager: Start proc 5956:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-14 07:15:06.279  3566  3693 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-14 07:15:06.279  3566  3693 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3566
09-14 07:15:06.279  3566  3693 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-14 07:15:06.279  3566  3693 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-14 07:15:06.279  3566  3693 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-14 07:15:06.279  3566  3693 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-14 07:15:06.279  3566  3693 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-14 07:15:06.279  3566  3693 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-14 07:15:06.279  3566  3693 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-14 07:15:06.279  3566  3693 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-14 07:15:06.279  3566  3693 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-14 07:15:06.279  3566  3693 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-14 07:15:06.279  3566  3693 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-14 07:15:06.279  3566  3693 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 07:15:06.283  3418  3448 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjE280C79B3) - 
09-14 07:15:06.283   926  5965 E DropBoxManagerService: Can't write: system_app_crash
09-14 07:15:06.283   926  5965 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
09-14 07:15:06.283   926  5965 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-14 07:15:06.283   926  5965 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-14 07:15:06.283   926  5965 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-14 07:15:06.283   926  5965 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-14 07:15:06.283   926  5965 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-14 07:15:06.283   926  5965 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-14 07:15:06.283   926  5965 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-14 07:15:06.283   926  5965 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-14 07:15:06.283   926  5965 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-14 07:15:06.283   926  5965 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 07:15:06.283   926  5965 E DropBoxManagerService: 	... 5 more
09-14 07:15:06.285   926  3206 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-14 07:15:06.293  3566  3693 I Process : Sending signal. PID: 3566 SIG: 9
09-14 07:15:06.306   386   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
