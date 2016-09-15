#### Test 83276082e94149a_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-15 09:35:12.865   542   542 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 09:35:12.866   542   542 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-15 09:35:13.338  5312  5312 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-15 09:35:13.344  5312  5312 D AndroidRuntime: CheckJNI is OFF
09-15 09:35:13.374  5312  5312 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-15 09:35:13.411  5312  5312 I Radio-JNI: register_android_hardware_Radio DONE
09-15 09:35:13.428  5312  5312 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-15 09:35:13.434   928   939 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-15 09:35:13.477   928   939 I ActivityManager: Start proc 5322:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-15 09:35:13.481  5312  5312 D AndroidRuntime: Shutting down VM
09-15 09:35:13.571  5322  5322 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-15 09:35:13.603  5322  5322 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-15 09:35:13.627  5322  5322 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 620-638)
09-15 09:35:13.627  5322  5322 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 09:35:13.647  5322  5322 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1baf020}
09-15 09:35:13.647  5322  5322 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 09:35:13.647  5322  5322 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-15 09:35:13.653  5322  5322 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-15 09:35:13.654  5322  5322 E SysUtils: ApplicationContext is null in ApplicationStatus
09-15 09:35:13.688  5322  5322 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-15 09:35:13.701  5322  5322 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 09:35:13.702  5322  5322 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 09:35:13.702  5322  5322 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-15 09:35:13.702  5322  5322 I Adreno  : Build Date                       : 12/06/15
09-15 09:35:13.702  5322  5322 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-15 09:35:13.702  5322  5322 I Adreno  : Local Branch                     : mybranch17112971
09-15 09:35:13.702  5322  5322 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-15 09:35:13.702  5322  5322 I Adreno  : Remote Branch                    : NONE
09-15 09:35:13.702  5322  5322 I Adreno  : Reconstruct Branch               : NOTHING
,09-15 09:35:13.752   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9ae5fe6:true
,09-15 09:35:13.783   409   409 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[21315]" dev="sockfs" ino=21315 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 09:35:13.783   409   409 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[21315]" dev="sockfs" ino=21315 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 09:35:13.799  5322  5322 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-15 09:35:13.808  5322  5322 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-15 09:35:13.830   705   705 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[31084]" dev="sockfs" ino=31084 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 09:35:13.830   705   705 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31084]" dev="sockfs" ino=31084 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 09:35:13.833  5322  5359 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-15 09:35:13.833  3438  3438 W Binder_8: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[12980]" dev="sockfs" ino=12980 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 09:35:13.833  3438  3438 W Binder_8: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[12980]" dev="sockfs" ino=12980 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 09:35:13.838  5322  5346 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-15 09:35:13.872  5322  5359 I OpenGLRenderer: Initialized EGL, version 1.4
,09-15 09:35:13.951   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +435ms (total +499ms),
,09-15 09:35:13.961  5322  5322 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5322
,09-15 09:35:14.046  5322  5322 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-15 09:35:14.145  5322  5360 D jxcore_app_log: JniHelper::setJavaVM(0xf507c000), pthread_self() = -563349200
,09-15 09:35:14.148  5322  5360 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-15 09:35:14.148  5322  5360 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-15 09:35:14.148  5322  5360 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-15 09:35:14.148  5322  5360 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-15 09:35:14.148  5322  5360 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-15 09:35:14.148  5322  5360 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be64d1 added. We now have 1 listener(s)
,09-15 09:35:14.150  5322  5360 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-15 09:35:14.151  5322  5360 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 09:35:14.151  5322  5360 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 09:35:14.151  5322  5360 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-15 09:35:14.153  5322  5360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b7eba4 added. We now have 1 listener(s)
09-15 09:35:14.154  5322  5360 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 09:35:14.157   928  2865 D WifiService: New client listening to asynchronous messages
,09-15 09:35:14.157  5322  5360 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 09:35:14.158  5322  5360 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-15 09:35:14.158  5322  5360 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-15 09:35:14.158  5322  5360 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-15 09:35:14.158  5322  5360 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-15 09:35:14.159  5322  5360 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 09:35:14.160  5322  5360 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-15 09:35:14.163  5322  5360 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-15 09:35:14.163  5322  5360 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 09:35:14.163  5322  5360 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:14.163  5322  5360 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:14.163  5322  5360 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:14.163  5322  5360 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:14.163  5322  5360 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 09:35:14.163  5322  5360 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 09:35:14.163  5322  5360 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 09:35:14.163  5322  5360 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-15 09:35:14.163  5322  5360 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 09:35:14.164  5322  5360 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-15 09:35:14.168  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:14.171  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:14.191  5322  5322 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-15 09:35:14.442  5322  5368 W jxcore-log: Initializing JXcore engine
,09-15 09:35:14.442  5322  5368 W jxcore-log: JXcore engine is ready
,09-15 09:35:14.463  5368  5368 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11832 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-15 09:35:14.463  5368  5368 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[16416]" dev="sockfs" ino=16416 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-15 09:35:14.463  5368  5368 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-15 09:35:14.463  5368  5368 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31956]" dev="sockfs" ino=31956 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-15 09:35:14.474  5322  5368 W jxcore-log: Starting JXcore engine
,09-15 09:35:14.490  5322  5331 I art     : Background sticky concurrent mark sweep GC freed 81414(8MB) AllocSpace objects, 18(1604KB) LOS objects, 22% free, 25MB/32MB, paused 1.112ms total 113.490ms
,09-15 09:35:14.524  5322  5368 W jxcore-log: Platform android
09-15 09:35:14.524  5322  5368 W jxcore-log: 
09-15 09:35:14.524  5322  5368 W jxcore-log: Process ARCH arm
09-15 09:35:14.524  5322  5368 W jxcore-log: 
,09-15 09:35:14.620  5322  5368 I jxcore-log: JXcore Cordova bridge is ready!
09-15 09:35:14.620  5322  5368 I jxcore-log: 
,09-15 09:35:14.620  5322  5368 W jxcore-log: JXcore engine is started
,09-15 09:35:14.625  5322  5360 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-15 09:35:14.628  5322  5322 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-15 09:35:21.337  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-15 09:35:21.337  5322  5368 I jxcore-log: 
,09-15 09:35:21.339  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-15 09:35:21.339  5322  5368 I jxcore-log: 
,09-15 09:35:21.343  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 09:35:21.343  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:21.343  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:21.343  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:21.343  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:21.343  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 09:35:21.343  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 09:35:21.343  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 09:35:21.344  5322  5368 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 09:35:21.346  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-15 09:35:21.346  5322  5368 I jxcore-log: 
,09-15 09:35:21.347  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-15 09:35:21.347  5322  5368 I jxcore-log: 
,09-15 09:35:21.694  5322  5368 I jxcore-log: Unit Test app is loaded
09-15 09:35:21.694  5322  5368 I jxcore-log: 
,09-15 09:35:21.698  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 09:35:21.698  5322  5368 I jxcore-log: 
,09-15 09:35:21.703  5322  5368 D executeNativeTests: Running unit tests
,09-15 09:35:21.723  5322  5322 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-15 09:35:21.739  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 09:35:21.739  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 added. We now have 2 listener(s)
09-15 09:35:21.739  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 09:35:21.739  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 09:35:21.739  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 09:35:21.739  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:21.739  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d added. We now have 2 listener(s)
09-15 09:35:21.739  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 09:35:21.740  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 09:35:21.741  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 09:35:21.744  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 09:35:21.744  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:21.744  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:21.744  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:21.744  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:21.744  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 09:35:21.744  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 09:35:21.744  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 09:35:21.744  5322  5368 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 09:35:21.744  5322  5368 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 09:35:21.746  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 09:35:21.746  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 09:35:21.746  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 09:35:21.746  5322  5368 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-15 09:35:21.747  5322  5368 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 09:35:21.747  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 09:35:21.747  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 09:35:21.747  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 09:35:21.747  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.747  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.747  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.747  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.747  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.747  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 09:35:21.747  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 09:35:21.748  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 removed from the list
09-15 09:35:21.748  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.748  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d removed from the list
09-15 09:35:21.753  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateCo,nnectivityInfo: No relevant state changes
,09-15 09:35:21.759  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:21.760  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.760  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.760  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.760  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 09:35:21.760  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.761  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.761  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.761  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
,09-15 09:35:21.761  5322  5368 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-15 09:35:21.762  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.762  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.762  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.762  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 09:35:21.762  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.762  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.762  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.762  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.762  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.762  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.762  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.762  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.762  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 09:35:21.762  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.763  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.763  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.763  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.763  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
,09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 09:35:21.765  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 09:35:21.766  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.766  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.766  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.766  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.766  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.766  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.766  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.766  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.766  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.766  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.766  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.766  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.766  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 09:35:21.766  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.768  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.769  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.769  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.769  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.770  5322  5368 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 09:35:21.771  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 09:35:21.774  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 09:35:21.774  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:21.774  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:21.774  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:21.774  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:21.774  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 09:35:21.774  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 09:35:21.774  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 09:35:21.775  5322  5368 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 09:35:21.775  5322  5368 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 09:35:21.775  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 09:35:21.775  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 09:35:21.775  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 09:35:21.775  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 09:35:21.775  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 09:35:21.777  5322  5368 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 09:35:21.777  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 09:35:21.779  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 09:35:21.780  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:21.781  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 09:35:21.781  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 09:35:21.782  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-15 09:35:21.783  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:21.784  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-15 09:35:21.784  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 09:35:21.784  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 09:35:21.784  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 09:35:21.785  5322  5368 D BluetoothAdapter: STATE_ON
09-15 09:35:21.787  4356  4369 D BtGatt.GattService: registerClient() - UUID=a48596e4-f663-4670-9bc4-891fea58eec0
,09-15 09:35:21.788  4356  4418 D BtGatt.GattService: onClientRegistered() - UUID=a48596e4-f663-4670-9bc4-891fea58eec0, clientIf=5
,09-15 09:35:21.789  5322  5332 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 09:35:21.790  4356  4579 D BtGatt.GattService: start scan with filters
,09-15 09:35:21.794  4356  4423 D BtGatt.ScanManager: handling starting scan
,09-15 09:35:21.794  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 09:35:21.794  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 09:35:21.794  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-15 09:35:21.794  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 09:35:21.795  4356  4423 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
09-15 09:35:21.796  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 09:35:21.796  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-15 09:35:21.797  5322  5322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 09:35:21.797  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 09:35:21.798  5322  5368 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 09:35:21.799  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.799  5322  5368 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 09:35:21.799  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.800  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 09:35:21.800  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.800  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 09:35:21.800  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 09:35:21.800  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-15 09:35:21.800  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 09:35:21.800  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 09:35:21.800  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 09:35:21.800  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 09:35:21.800  5322  5368 D BluetoothAdapter: STATE_ON
09-15 09:35:21.801  4356  4369 D BtGatt.GattService: stopScan() - queue size =1
09-15 09:35:21.801  4356  4579 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 09:35:21.801  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 09:35:21.801  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 09:35:21.801  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-15 09:35:21.801  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 09:35:21.801  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 09:35:21.802  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 09:35:21.802  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 09:35:21.802  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 09:35:21.802  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 09:35:21.802  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 09:35:21.802  4356  4418 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 09:35:21.803  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.803  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.803  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.803  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 09:35:21.803  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.803  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.803  5322  5322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 09:35:21.803  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.803  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.803  4356  4423 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 09:35:21.803  5322  5322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 09:35:21.803  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 09:35:21.803  5322  5322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 09:35:21.803  5322  5368 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 09:35:21.804  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 09:35:21.807  4356  4418 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-15 09:35:21.807  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.807  4356  4423 D BtGatt.ScanManager: Starting BLE batch scan
09-15 09:35:21.808  4356  4423 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 09:35:21.808  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 09:35:21.808  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:21.808  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:21.808  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:21.808  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:21.808  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 09:35:21.808  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 09:35:21.808  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 09:35:21.810  5322  5368 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 09:35:21.810  5322  5368 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 09:35:21.810  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 09:35:21.810  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-15 09:35:21.810  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-15 09:35:21.810  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 09:35:21.811  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 09:35:21.813  4356  4418 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 09:35:21.813  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 09:35:21.815  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:21.815  5322  5368 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 09:35:21.816  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 09:35:21.818  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 09:35:21.818  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:21.819  4356  4418 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 09:35:21.819  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.819  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 09:35:21.819  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 09:35:21.822  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 09:35:21.822  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 09:35:21.822  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 09:35:21.822  5322  5368 D BluetoothAdapter: STATE_ON
,09-15 09:35:21.824  4356  4418 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-15 09:35:21.824  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.824  4356  4588 D BtGatt.GattService: registerClient() - UUID=7232a142-0d74-4e27-9057-41d2843c2aad
09-15 09:35:21.824  4356  4423 D BtGatt.ScanManager: stopping BLe Batch
09-15 09:35:21.825  4356  4418 D BtGatt.GattService: onClientRegistered() - UUID=7232a142-0d74-4e27-9057-41d2843c2aad, clientIf=5
09-15 09:35:21.825  5322  5332 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 09:35:21.825  4356  4579 D BtGatt.GattService: start scan with filters
09-15 09:35:21.828  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 09:35:21.828  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 09:35:21.828  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 09:35:21.828  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 09:35:21.829  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 09:35:21.829  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 09:35:21.829  5322  5322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 09:35:21.830  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 09:35:21.830  4356  4418 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 09:35:21.830  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.830  4356  4423 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 09:35:21.831  5322  5368 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 09:35:21.832  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 09:35:21.832  5322  5368 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 09:35:21.832  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.832  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 09:35:21.832  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.832  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 09:35:21.832  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 09:35:21.832  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 09:35:21.832  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 09:35:21.832  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 09:35:21.832  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-15 09:35:21.832  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 09:35:21.832  5322  5368 D BluetoothAdapter: STATE_ON
09-15 09:35:21.833  4356  4588 D BtGatt.GattService: stopScan() - queue size =0
09-15 09:35:21.833  4356  4579 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 09:35:21.833  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 09:35:21.833  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 09:35:21.833  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 09:35:21.833  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 09:35:21.833  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 09:35:21.834  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 09:35:21.834  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 09:35:21.834  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 09:35:21.834  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 09:35:21.834  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 09:35:21.834  4356  4418 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 09:35:21.834  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 09:35:21.836  4356  4423 D BtGatt.ScanManager: handling starting scan
,09-15 09:35:21.837  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 09:35:21.837  5322  5322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 09:35:21.837  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 09:35:21.837  5322  5322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-15 09:35:21.837  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 09:35:21.837  5322  5322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 09:35:21.837  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.837  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.837  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.837  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.837  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.838  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.838  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.839  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.839  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.839  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 09:35:21.840  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.840  5322  5368 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 09:35:21.841  4356  4418 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 09:35:21.841  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.841  4356  4423 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 09:35:21.842  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 09:35:21.846  4356  4418 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 09:35:21.846  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 09:35:21.846  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 09:35:21.846  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:21.846  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:21.846  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:21.846  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:21.846  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 09:35:21.846  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 09:35:21.846  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 09:35:21.846  4356  4423 D BtGatt.ScanManager: Starting BLE batch scan
09-15 09:35:21.846  4356  4423 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 09:35:21.847  5322  5368 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 09:35:21.847  5322  5368 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 09:35:21.848  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 09:35:21.848  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 09:35:21.848  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 09:35:21.848  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 09:35:21.848  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-15 09:35:21.850  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:21.851  5322  5368 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 09:35:21.851  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 09:35:21.852  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:21.854  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 09:35:21.854  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 09:35:21.854  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 09:35:21.856  4356  4418 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 09:35:21.856  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 09:35:21.856  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 09:35:21.856  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 09:35:21.856  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 09:35:21.857  5322  5368 D BluetoothAdapter: STATE_ON
,09-15 09:35:21.859  4356  4418 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 09:35:21.859  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.859  4356  4588 D BtGatt.GattService: registerClient() - UUID=1e249844-edd1-4410-ab5e-ef4a71044056
,09-15 09:35:21.860  4356  4418 D BtGatt.GattService: onClientRegistered() - UUID=1e249844-edd1-4410-ab5e-ef4a71044056, clientIf=5
,09-15 09:35:21.860  5322  5333 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 09:35:21.861  4356  4369 D BtGatt.GattService: start scan with filters
,09-15 09:35:21.863  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 09:35:21.863  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 09:35:21.863  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 09:35:21.863  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 09:35:21.864  4356  4418 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 09:35:21.864  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.864  4356  4423 D BtGatt.ScanManager: stopping BLe Batch
,09-15 09:35:21.864  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 09:35:21.864  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 09:35:21.865  5322  5322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 09:35:21.865  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 09:35:21.866  5322  5368 I io.jxcore.node.ConnectionHelper: start: OK
09-15 09:35:21.866  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.867  5322  5368 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 09:35:21.867  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.867  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-15 09:35:21.867  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.867  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 09:35:21.867  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 09:35:21.867  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 09:35:21.867  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 09:35:21.867  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 09:35:21.867  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 09:35:21.867  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 09:35:21.867  5322  5368 D BluetoothAdapter: STATE_ON
,09-15 09:35:21.867  4356  4579 D BtGatt.GattService: stopScan() - queue size =0
09-15 09:35:21.868  4356  4371 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 09:35:21.868  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 09:35:21.868  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 09:35:21.868  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 09:35:21.868  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 09:35:21.868  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 09:35:21.869  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 09:35:21.869  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 09:35:21.869  4356  4418 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 09:35:21.869  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-15 09:35:21.869  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.869  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 09:35:21.869  4356  4423 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 09:35:21.869  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 09:35:21.870  5322  5322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 09:35:21.870  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.870  5322  5368 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 09:35:21.870  5322  5322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 09:35:21.870  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.870  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 09:35:21.870  5322  5322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 09:35:21.870  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.870  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.870  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 09:35:21.870  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.870  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.870  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.870  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.870  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.870  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.870  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.871  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.871  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.871  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.871  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
,09-15 09:35:21.871  5322  5368 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-15 09:35:21.871  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.871  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.871  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.871  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.872  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.872  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.872  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.872  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.872  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.872  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.872  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.872  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.872  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.872  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 09:35:21.872  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.872  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.872  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.872  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.873  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 09:35:21.873  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.873  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.873  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.873  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.873  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.873  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.873  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.873  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 09:35:21.873  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.873  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.873  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.873  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.873  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.873  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.874  4356  4418 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-15 09:35:21.874  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.874  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.874  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.874  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.874  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.874  5322  5368 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-15 09:35:21.874  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.874  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.874  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 09:35:21.874  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.874  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.874  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.874  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.875  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.875  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.875  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.875  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.875  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.875  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.875  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.875  4356  4423 D BtGatt.ScanManager: handling starting scan
09-15 09:35:21.876  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.876  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.876  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.876  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.876  5322  5368 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-15 09:35:21.876  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.876  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.876  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.877  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.877  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.877  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.877  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.877  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.877  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.877  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.877  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 09:35:21.877  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.877  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.877  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.877  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.877  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.877  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.877  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.878  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 09:35:21.878  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 09:35:21.878  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 09:35:21.878  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-15 09:35:21.878  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 09:35:21.878  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 09:35:21.878  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.878  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.878  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.878  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.878  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.878  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.878  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.878  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 09:35:21.878  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.878  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.878  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.878  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.879  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.879  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.880  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.880  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.880  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.880  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.880  5322  5368 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 09:35:21.880  5322  5368 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 09:35:21.880  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 09:35:21.881  5322  5368 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 09:35:21.881  5322  5368 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-15 09:35:21.881  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-15 09:35:21.881  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-15 09:35:21.882  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 09:35:21.883  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-15 09:35:21.883  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 09:35:21.883  5322  5368 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-15 09:35:21.883  5322  5368 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 09:35:21.883  5322  5368 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-15 09:35:21.883  5322  5368 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 09:35:21.883  5322  5368 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 09:35:21.883  5322  5368 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-15 09:35:21.883  5322  5368 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 09:35:21.883  5322  5368 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-15 09:35:21.883  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-15 09:35:21.884  4356  4418 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 09:35:21.884  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.884  4356  4423 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 09:35:21.885  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-15 09:35:21.885  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-15 09:35:21.885  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-15 09:35:21.886  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-15 09:35:21.886  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-15 09:35:21.886  5322  5368 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-15 09:35:21.886  5322  5368 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 09:35:21.886  5322  5368 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-15 09:35:21.886  5322  5369 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-15 09:35:21.887  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.887  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.887  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.887  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.887  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.887  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 09:35:21.887  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-15 09:35:21.887  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.887  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.887  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.888  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.888  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.888  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.888  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.888  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.888  5322  5370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-15 09:35:21.888  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.889  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.889  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.889  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.889  5322  5368 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-15 09:35:21.889  4356  4418 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 09:35:21.889  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.889  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.889  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.889  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.889  4356  4423 D BtGatt.ScanManager: Starting BLE batch scan
09-15 09:35:21.890  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.890  4356  4423 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 09:35:21.890  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.890  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.890  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.890  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.890  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.890  5322  5368 D io.jxcore.node.ConnectivityMonitor: s,top
09-15 09:35:21.890  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.890  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.890  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.890  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.890  5322  5369 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 09:35:21.891  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.891  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.891  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.891  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.891  5322  5368 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-15 09:35:21.892  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.892  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.892  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.892  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.892  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.892  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.892  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.892  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.892  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.892  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.892  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.892  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.892  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.892  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.893  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.893  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.893  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.893  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.893  5322  5368 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-15 09:35:21.893  5322  5368 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-15 09:35:21.893  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 09:35:21.893  5322  5368 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-15 09:35:21.893  5322  5368 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 09:35:21.894  5322  5368 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-15 09:35:21.894  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 09:35:21.894  5322  5368 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-15 09:35:21.894  5322  5368 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 09:35:21.894  5322  5368 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 09:35:21.894  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 09:35:21.894  5322  5368 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-15 09:35:21.894  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.894  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.894  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.894  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.894  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.894  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.894  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.894  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.894  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.894  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.894  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.894  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.894  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.894  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.895  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.895  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.895  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.895  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.895  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.895  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.895  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.895  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.896  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.896  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.896  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.896  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.896  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.896  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.896  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.896  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.896  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.896  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.896  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.896  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.896  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.896  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.896  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.896  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.896  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.896  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.896  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.896  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.896  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.897  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.897  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.897  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.897  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.897  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.897  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.897  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.897  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.898  5322  5368 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 09:35:21.898  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 09:35:21.899  4356  4418 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 09:35:21.899  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.896  4579  4579 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[28662]" dev="sockfs" ino=28662 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 09:35:21.896  4579  4579 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[28662]" dev="sockfs" ino=28662 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 09:35:21.900  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-15 09:35:21.901  5322  5368 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 09:35:21.901  5322  5368 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 09:35:21.901  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 09:35:21.901  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 09:35:21.901  5322  5322 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 09:35:21.902  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.902  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 09:35:21.902  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 09:35:21.902  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 09:35:21.902  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.902  5322  5368 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-15 09:35:21.903  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.903  5322  5322 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 09:35:21.903  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.903  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 09:35:21.903  5322  5371 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 09:35:21.903  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 09:35:21.905  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 09:35:21.905  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.905  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.906  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 09:35:21.906  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.906  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.906  5322  5322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 09:35:21.906  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.906  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.906  5322  5322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 09:35:21.906  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.906  5322  5322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 09:35:21.903  4588  4588 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32397]" dev="sockfs" ino=32397 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 09:35:21.903  4588  4588 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32397]" dev="sockfs" ino=32397 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 09:35:21.906  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.906  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.906  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.906  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.906  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.906  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.906  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.906  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.906  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.906  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.907  5322  5371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 09:35:21.907  5322  5371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 09:35:21.907  5322  5371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 09:35:21.907  5322  5322 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 09:35:21.909  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.909  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.909  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.909  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.910  5322  5368 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-15 09:35:21.910  5322  5368 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 09:35:21.910  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 09:35:21.910  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 09:35:21.910  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.910  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.910  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.911  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.911  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.911  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.911  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.911  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.911  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.911  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.911  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.911  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.911  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.911  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.913  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.913  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.913  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.913  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.914  4356  4418 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 09:35:21.914  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.915  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.915  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.915  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.915  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.915  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.915  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.915  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.915  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.916  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.916  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.916  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.916  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.916  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.916  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.916  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.916  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.916  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.916  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.917  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:21.917  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:21.917  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:21.917  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:21.917  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.917  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.917  5322  5368 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1729174 not in the list
09-15 09:35:21.917  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.917  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.917  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:21.917  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.917  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.918  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:21.918  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:21.922  4356  4418 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 09:35:21.922  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.923  4356  4423 D BtGatt.ScanManager: stopping BLe Batch
09-15 09:35:21.923  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:21.923  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:21.923  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:21.923  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d1769d not in the list
09-15 09:35:21.923  5322  5368 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-15 09:35:21.923  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 09:35:21.923  5322  5368 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-15 09:35:21.923  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 09:35:21.923  5322  5368 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-15 09:35:21.923  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 09:35:21.924  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 09:35:21.924  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-15 09:35:21.925  5322  5368 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-15 09:35:21.925  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 09:35:21.925  5322  5368 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-15 09:35:21.925  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 09:35:21.925  5322  5368 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-15 09:35:21.925  5322  5368 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-15 09:35:21.925  5322  5368 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-15 09:35:21.925  5322  5368 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-15 09:35:21.926  5322  5368 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-15 09:35:21.926  5322  5368 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-15 09:35:21.926  5322  5368 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-15 09:35:21.926  5322  5368 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-15 09:35:21.926  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:21.926  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e134e37 added. We now have 2 listener(s)
09-15 09:35:21.926  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 09:35:21.927  4356  4418 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 09:35:21.927  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.927  4356  4423 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 09:35:21.927  5322  5368 D BluetoothAdapter: enable(): BT is already enabled..!
09-15 09:35:21.928   928  3402 D WifiService: setWifiEnabled: true pid=5322, uid=10077
09-15 09:35:21.928   928  3402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 09:35:21.928  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:21.928  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5973fa4 added. We now have 3 listener(s)
09-15 09:35:21.928  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 09:35:21.931  4356  4418 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 09:35:21.931  4356  4418 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:21.933  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:21.933  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a2410d added. We now have 4 listener(s)
09-15 09:35:21.933  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 09:35:21.934  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:21.934  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f5d8c2 added. We now have 5 listener(s)
09-15 09:35:21.934  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 09:35:21.935   928  3402 D WifiService: setWifiEnabled: false pid=5322, uid=10077
09-15 09:35:21.935   928  3402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 09:35:21.937   928  2858 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-15 09:35:21.937   928  2858 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-15 09:35:21.937   928  2858 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 09:35:21.938   928  2858 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-15 09:35:21.940  4356  4414 D BluetoothAdapterState: Current state: ON, message: 23
09-15 09:35:21.940  4356  4414 D BluetoothAdapterProperties: Setting state to 13
09-15 09:35:21.940  4356  4414 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-15 09:35:21.940  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 09:35:21.940  4356  4414 D BluetoothAdapterProperties: onBluetoothDisable()
09-15 09:35:21.941  4356  4414 I BluetoothAdapterState: Entering PendingCommandState
09-15 09:35:21.942  4356  4418 D BluetoothAdapterProperties: Scan Mode:20
09-15 09:35:21.943  4356  4414 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-15 09:35:21.944  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:21.944  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 09:35:21.944  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:21.944  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:21.944  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:21.944  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 09:35:21.944  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 09:35:21.944  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 09:35:21.944  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 09:35:21.944  4356  4356 D HeadsetService: Received stop request...Stopping profile...
09-15 09:35:21.944  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:21.944  5322  5368 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 09:35:21.945  5322  5368 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 09:35:21.946   928  2858 E native  : do suspend true
09-15 09:35:21.947   928   928 D BluetoothHeadset: Proxy object disconnected
09-15 09:35:21.947  3037  5321 D BluetoothHeadset: Proxy object disconnected
09-15 09:35:21.947   928   928 D BluetoothHeadset: Proxy object disconnected
09-15 09:35:21.947   928   928 D BluetoothHeadset: Proxy object disconnected
09-15 09:35:21.948  3037  3037 D HeadsetProfile: Bluetooth service disconnected
09-15 09:35:21.948  3415  3434 D BluetoothHeadset: Proxy object disconnected
09-15 09:35:21.949  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:21.949  4356  4356 D A2dpService: Received stop request...Stopping profile...
09-15 09:35:21.950  4356  4582 D A2dpStateMachine: Exit Disconnected: -1
09-15 09:35:21.951  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:21.953  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:21.954  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:21.954  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:21.954  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:21.954  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:21.954  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 09:35:21.954  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 09:35:21.954  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 09:35:21.954  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 09:35:21.954  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:21.954  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 09:35:21.957  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:21.959  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:21.960   928   941 I ActivityManager: Start proc 5374:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-15 09:35:21.961  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:21.962  4356  4356 V BluetoothAdapterState: isTurningOff()=true
09-15 09:35:21.962  4356  4356 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:21.962   928   928 D BluetoothA2dp: Proxy object disconnected
09-15 09:35:21.962  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:21.962  4356  4356 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:21.963  4356  4356 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-15 09:35:21.964  4356  4356 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 09:35:21.964  4356  4563 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 09:35:21.964  4356  4563 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 09:35:21.964  4356  4563 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 09:35:21.964  4356  4356 D HidService: Received stop request...Stopping profile...
09-15 09:35:21.964  4356  4356 D HidService: Stopping Bluetooth HidService
09-15 09:35:21.965  4356  4418 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 09:35:21.965  4356  4418 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-15 09:35:21.965  4356  4356 D BluetoothMapService: onReceive
09-15 09:35:21.965  4356  4356 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 09:35:21.965  4356  4356 D BluetoothMapService: STATE_TURNING_OFF
09-15 09:35:21.966  4356  4356 V BluetoothAdapterState: isTurningOff()=true
09-15 09:35:21.966  4356  4356 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:21.966  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:21.966  4356  4356 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:21.968  4356  4356 D HealthService: Received stop request...Stopping profile...
09-15 09:35:21.970  4356  4418 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-15 09:35:21.970  4356  4563 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 09:35:21.970  4356  4563 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 09:35:21.970  4356  4563 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 09:35:21.970  4356  4563 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 09:35:21.970  4356  4563 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 09:35:21.970  4356  4563 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 09:35:21.970  4356  4356 D PanService: Received stop request...Stopping profile...
,09-15 09:35:21.973   928  5071 D DhcpClient: Clearing IP address
,09-15 09:35:21.974   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-15 09:35:21.975  3037  3037 D BluetoothA2dp: Proxy object disconnected
09-15 09:35:21.975  3037  3037 D BluetoothInputDevice: Proxy object disconnected
09-15 09:35:21.975  3037  3037 D HidProfile: Bluetooth service disconnected
09-15 09:35:21.976  3037  3037 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 09:35:21.976  3037  3037 D PanProfile: Bluetooth service disconnected
09-15 09:35:21.976  4356  4356 D BluetoothMapService: Received stop request...Stopping profile...
09-15 09:35:21.976  4356  4356 D BluetoothMapService: stop()
09-15 09:35:21.976  4356  4356 D BluetoothMapAppObserver: deinitObservers()
09-15 09:35:21.976  4356  4356 D BluetoothMapAppObserver: removeReceiver()
09-15 09:35:21.977  4356  4356 V BluetoothAdapterState: isTurningOff()=true
09-15 09:35:21.977  3037  3037 D BluetoothMap: Proxy object disconnected
09-15 09:35:21.977  3037  3037 D MapProfile: Bluetooth service disconnected
09-15 09:35:21.977  4356  4356 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:21.977  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:21.977  4356  4356 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:21.978  4356  4356 D SapService: Received stop request...Stopping profile...
09-15 09:35:21.979  4356  4356 V SapService: stop()
09-15 09:35:21.980   507   922 D CommandListener: Setting iface cfg
09-15 09:35:21.980  4356  4356 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 09:35:21.980  4356  4418 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 09:35:21.980  4356  4356 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 09:35:21.981  4356  4356 I BtOppRfcommListener: stopping Accept Thread
09-15 09:35:21.982  4356  5024 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 09:35:21.982   928  5072 D DhcpClient: Receive thread stopped
09-15 09:35:21.983  3499  5124 V NativeCrypto: Read error: ssl=0x7f7ae63a80: I/O error during system call, Connection timed out
,09-15 09:35:21.984  3499  5124 V NativeCrypto: SSL shutdown failed: ssl=0x7f7ae63a80: I/O error during system call, Broken pipe
,09-15 09:35:21.986  4356  5024 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 09:35:21.986   928  3061 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-15 09:35:21.986   928  5069 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-15 09:35:21.987  4356  4356 V BluetoothAdapterState: isTurningOff()=true
09-15 09:35:21.987  4356  4356 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:21.987  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:21.987  4356  4356 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 09:35:21.988  4356  4356 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-15 09:35:21.988  4356  4418 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-15 09:35:21.988  4356  4356 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-15 09:35:21.988   928  5069 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-15 09:35:21.989  4356  4356 V BluetoothAdapterState: isTurningOff()=true
09-15 09:35:21.989  4356  4356 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:21.989  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:21.989   928  2870 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-15 09:35:21.989   928  2870 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-15 09:35:21.990   928  2870 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-15 09:35:21.990  4356  4356 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:21.991  4356  4356 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 09:35:21.991  4356  4356 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-15 09:35:21.992  4356  4356 D BluetoothMapService: MAP Service closeService in
09-15 09:35:21.992  4356  4356 D BluetoothMapMasInstance0: MAP Service shutdown
09-15 09:35:21.992  4356  4356 D ObexServerSockets0: shutdown(block = true)
09-15 09:35:21.992  4356  4356 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 09:35:21.993  4356  4356 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 09:35:21.993  4356  4590 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-15 09:35:21.993  4356  4589 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-15 09:35:21.993  4356  4356 V BluetoothAdapterState: isTurningOff()=true
09-15 09:35:21.993  4356  4356 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:21.993  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:21.993  4356  4356 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:21.994  4356  4577 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-15 09:35:21.994  4356  4356 D BluetoothMapService: cleanup()
09-15 09:35:21.994  4356  4356 D BluetoothMapService: MAP Service closeService in
09-15 09:35:21.994  4356  4356 V BluetoothAdapterState: isTurningOff()=true
09-15 09:35:21.994  4356  4356 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:21.994  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:21.995  4356  4356 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:21.995  4356  4414 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 09:35:21.995  4356  4414 D BluetoothAdapterProperties: Setting state to 15
09-15 09:35:21.995  4356  4414 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 09:35:21.995  4356  4414 I BluetoothAdapterState: Entering BleOnState
09-15 09:35:21.995  3037  3051 D BluetoothMap: onBluetoothStateChange: up=false
09-15 09:35:21.996  3037  5321 D BluetoothPan: onBluetoothStateChange on: false
09-15 09:35:21.997   928  2870 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-15 09:35:21.997   928  2870 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-15 09:35:22.000   540   540 E Parcel  : Reading a NULL string not supported here.
,09-15 09:35:22.001   928   928 D RttService: SCAN_AVAILABLE : 1
09-15 09:35:22.001   928  2870 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-15 09:35:22.002   928  2973 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-15 09:35:22.006  3383  3506 W QCNEJ   : |CORE| network lost: 100
09-15 09:35:22.006  3383  3506 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-15 09:35:22.007  3037  3051 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 09:35:22.007   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 09:35:22.007   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 09:35:22.007  3037  3256 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 09:35:22.008  3037  3049 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 09:35:22.008   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 09:35:22.009  3037  5321 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 09:35:22.009  3415  3434 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 09:35:22.009   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 09:35:22.010  4356  4414 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 09:35:22.010  4356  4414 D BluetoothAdapterProperties: Setting state to 16
09-15 09:35:22.010  4356  4414 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 09:35:22.011  4356  4414 D BluetoothAdapterProperties: onBleDisable
09-15 09:35:22.011  4356  4414 I BluetoothAdapterState: Entering PendingCommandState
09-15 09:35:22.011  4356  4415 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-15 09:35:22.012  4356  4418 D BluetoothAdapterProperties: Scan Mode:20
09-15 09:35:22.014  4356  4563 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-15 09:35:22.014  4356  4563 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 09:35:22.015  5322  5369 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-15 09:35:22.015  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:22.015  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:22.015  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:22.015  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:22.015  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:22.015  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 09:35:22.015  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:22.015  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:22.015  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 09:35:22.016  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:22.016  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 09:35:22.022  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 09:35:22.022   928  2858 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-15 09:35:22.022  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:22.022  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:22.022  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:22.022  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:22.022  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 09:35:22.022  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:22.022  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:22.022  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 09:35:22.025  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:22.025  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 09:35:22.026   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-15 09:35:22.027  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:22.028  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:22.031   928  2858 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 09:35:22.031   928  2858 E native  : do suspend true
,09-15 09:35:22.036  5374  5374 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-15 09:35:22.047  5374  5374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 09:35:22.049   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 09:35:22.049   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-15 09:35:22.050   928  2870 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-15 09:35:22.050   507   922 D TetherController: Setting IP forward enable = 0
09-15 09:35:22.050   928  2870 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-15 09:35:22.054   928  2858 D DhcpClient: doQuit
09-15 09:35:22.054   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d43582:true
09-15 09:35:22.054   928  2858 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-15 09:35:22.054   928  5071 D DhcpClient: onQuitting
09-15 09:35:22.055  3525  3525 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-15 09:35:22.055   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-15 09:35:22.056  4144  4144 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@2a1c70c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-15 09:35:22.057  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 09:35:22.058  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:22.060  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:22.060  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:22.060  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:22.060  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 09:35:22.060  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 09:35:22.060  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:22.060  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:22.060  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 09:35:22.061  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:22.061  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 09:35:22.064  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 09:35:22.064  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:22.064  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:22.064  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:22.064  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 09:35:22.064  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 09:35:22.064  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:22.064  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:22.064  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 09:35:22.065  4776  4791 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-15 09:35:22.065  4776  4791 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 09:35:22.065  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:22.065  4776  4791 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-15 09:35:22.065  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 09:35:22.066  4776  4791 E SarControlService: no key has been found,reset the power
09-15 09:35:22.066  4776  4817 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-15 09:35:22.066  4776  4817 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 09:35:22.066  4776  4817 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 09:35:22.066  4805  4805 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 09:35:22.067  4805  4805 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-15 09:35:22.067  4776  4817 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 09:35:22.068  4776  4817 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-15 09:35:22.068  4776  4817 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-15 09:35:22.068  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:22.068  4805  4805 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 09:35:22.068  4805  4805 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-15 09:35:22.070  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:22.071  4805  4819 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ee9c452 HexData = [00000000ea03000000000000ffffffff]
09-15 09:35:22.071  4805  4819 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 09:35:22.071  4805  4819 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-15 09:35:22.071  4805  4805 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 09:35:22.072  4776  4786 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-15 09:35:22.074  4805  4819 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ee9c452 HexData = [00000000eb03000000000000ffffffff]
,09-15 09:35:22.074  4805  4819 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 09:35:22.074  4805  4819 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-15 09:35:22.074  4805  4805 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-15 09:35:22.075  4776  4788 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-15 09:35:22.078   928   938 I ActivityManager: Start proc 5399:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-15 09:35:22.092  5374  5374 D LocalBluetoothProfileManager: Adding local MAP profile
,09-15 09:35:22.094  5374  5374 D BluetoothMap: Create BluetoothMap proxy object
,09-15 09:35:22.095  3525  3525 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-15 09:35:22.101  3525  3525 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-15 09:35:22.120  5374  5374 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-15 09:35:22.128  5399  5399 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-15 09:35:22.134   507   922 E Netd    : netlink response contains error (No such file or directory)
,09-15 09:35:22.134   507   922 D TetherController: Setting IP forward enable = 0
09-15 09:35:22.135   928  2870 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-15 09:35:22.141  5374  5374 D DockEventReceiver: finishStartingService: stopping service
,09-15 09:35:22.146   928  3700 I ActivityManager: Killing 4757:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-15 09:35:22.146  3525  3525 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 09:35:22.159  3525  3525 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 09:35:22.221  4356  4418 I bt_hci  : shut_down
,09-15 09:35:22.224  4356  4424 D bt_hwcfg: hw_epilog_process
,09-15 09:35:22.225  4356  4424 I bt_vendor: low_power_mode_cb
,09-15 09:35:22.228  4356  4424 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-15 09:35:22.228  4356  4424 I bt_vendor: epilog_cb
09-15 09:35:22.228  4356  4424 I bt_hci  : epilog_finished_callback
,09-15 09:35:22.231  4356  4418 I bt_hci_h4: hal_close
,09-15 09:35:22.231  4356  4418 I bt_userial_vendor: device fd = 54 close
,09-15 09:35:22.264   928  2858 D wifi    : In wifi stop Hal
,09-15 09:35:22.264   928  2858 D wifi    : halHandle = 0x7f79d70900, mVM = 0x7f963cd140, mCls = 0x100b2e
09-15 09:35:22.265   928  3517 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-15 09:35:22.265   928  3517 D WifiHAL : Got a signal to exit!!!
09-15 09:35:22.265   928  3517 I WifiHAL : Exit wifi_event_loop
09-15 09:35:22.265  4208  4208 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 09:35:22.265   928  2858 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 09:35:22.265   928  2858 E WifiHAL : Event processing terminated
09-15 09:35:22.266   928  2858 D wifi    : In wifi cleaned up handler
09-15 09:35:22.266   928  2858 I WifiHAL : Internal cleanup completed
09-15 09:35:22.267  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:22.268  3519  3923 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 09:35:22.269  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:22.285   928  3517 D wifi    : set interface wlan0 flags (DOWN)
,09-15 09:35:22.286   928  2858 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 09:35:22.343  4356  4415 D bt_stack_manager: event_shut_down_stack finished.
,09-15 09:35:22.343  4356  4414 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-15 09:35:22.345  4356  4414 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-15 09:35:22.345  4356  4356 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 09:35:22.345  4356  4356 D BtGatt.GattService: Received stop request...Stopping profile...
09-15 09:35:22.345  4356  4356 D BtGatt.GattService: stop()
09-15 09:35:22.346  4356  4356 D BtGatt.AdvertiseManager: advertise clients cleared
,09-15 09:35:22.347  4356  4356 V BluetoothAdapterState: isTurningOff()=false
,09-15 09:35:22.347  4356  4356 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:22.347  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:22.347  4356  4356 V BluetoothAdapterState: isBleTurningOff()=true
09-15 09:35:22.348  4356  4414 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 09:35:22.348  4356  4414 D BluetoothAdapterProperties: Setting state to 10
09-15 09:35:22.348  4356  4414 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 09:35:22.349  4356  4414 I BluetoothAdapterState: Entering OffState
,09-15 09:35:22.349   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-15 09:35:22.355  4356  4356 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-15 09:35:22.355  4356  4356 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 09:35:22.355  4356  4415 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-15 09:35:22.357  4356  4356 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-15 09:35:22.367  4356  4415 D bt_stack_manager: event_clean_up_stack finished.
09-15 09:35:22.370  5399  5399 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 09:35:22.370  5399  5399 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693),
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 09:35:22.370  5399  5399 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Looper.loop(Looper.java:148),
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 09:35:22.370  5399  5399 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 09:35:22.370  5399  5399 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.r.k.d(PG:583)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 09:35:22.370  5399  5399 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 09:35:22.370  5399  5399 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 09:35:22.370  5399  5399 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 09:35:22.370  5399  5399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 09:35:22.376  5374  5374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 09:35:22.387  4356  4356 I art     : System.exit called, status: 0
09-15 09:35:22.387  4356  4356 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-15 09:35:22.398  5374  5374 D DockEventReceiver: finishStartingService: stopping service
09-15 09:35:22.400   928   938 I ActivityManager: Killing 4144:com.google.android.music:main/u0a59 (adj 15): empty #17
09-15 09:35:22.406  5322  5322 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 09:35:22.444   928  3061 I ActivityManager: Process com.android.bluetooth (pid 4356) has died
09-15 09:35:22.446  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 09:35:22.458   928  3593 I ActivityManager: Start proc 5438:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-15 09:35:22.488   928   945 D Tethering: InitialState.processMessage what=4
,09-15 09:35:22.490   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-15 09:35:22.523  5438  5438 D AdapterServiceConfig: Adding HeadsetService
09-15 09:35:22.524  5438  5438 D AdapterServiceConfig: Adding A2dpService
09-15 09:35:22.524  5438  5438 D AdapterServiceConfig: Adding HidService
09-15 09:35:22.524  5438  5438 D AdapterServiceConfig: Adding HealthService
09-15 09:35:22.524  5438  5438 D AdapterServiceConfig: Adding PanService
09-15 09:35:22.524  5438  5438 D AdapterServiceConfig: Adding GattService
09-15 09:35:22.524  5438  5438 D AdapterServiceConfig: Adding BluetoothMapService
09-15 09:35:22.524  5438  5438 D AdapterServiceConfig: Adding SapService
,09-15 09:35:22.527   928  3402 I ActivityManager: Killing 5097:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-15 09:35:22.568  3825  3825 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-15 09:35:22.573  3825  5094 I iu.UploadsManager: num queued entries: 0
,09-15 09:35:22.574  3825  5094 I iu.UploadsManager: num updated entries: 0
09-15 09:35:22.574  3825  5094 I iu.SyncManager: NEXT; no task
,09-15 09:35:22.586  3825  3825 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-15 09:35:22.588  3825  3825 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-15 09:35:22.599   928  3700 I ActivityManager: Start proc 5451:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-15 09:35:22.633  5451  5451 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-15 09:35:22.640  5451  5451 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-15 09:35:22.649  5451  5451 D SprintDMHelper: simOperator: 
,09-15 09:35:22.649  5451  5451 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-15 09:35:22.661  4208  5463 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-15 09:35:22.674   928  3593 I ActivityManager: Start proc 5464:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-15 09:35:22.675   928  3593 I ActivityManager: Killing 4428:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-15 09:35:22.718  5464  5464 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-15 09:35:22.728   928   938 I ActivityManager: Killing 5184:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-15 09:35:22.771  5399  5424 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-15 09:35:22.781   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10cdf71:true
,09-15 09:35:22.866   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 09:35:23.867   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 09:35:24.868   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 09:35:24.946   928  3438 D WifiService: setWifiEnabled: true pid=5322, uid=10077
,09-15 09:35:24.946   928  3438 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 09:35:24.954   507   922 D SoftapController: Softap fwReload - Ok
09-15 09:35:24.958   507   922 D CommandListener: Setting iface cfg
,09-15 09:35:24.959   507   922 D CommandListener: Trying to bring down wlan0
09-15 09:35:24.960   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-15 09:35:24.966   928  2858 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 09:35:25.576   928  2858 D wifi    : set interface wlan0 flags (UP)
,09-15 09:35:25.580   928  2858 I WifiHAL : Initializing wifi
09-15 09:35:25.580   928  2858 I WifiHAL : Creating socket
09-15 09:35:25.584   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 09:35:25.587   928  2858 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-15 09:35:25.588   928  2858 D wifi    : Did set static halHandle = 0x7f79d70900
,09-15 09:35:25.588   928  2858 D wifi    : halHandle = 0x7f79d70900, mVM = 0x7f963cd140, mCls = 0x201886
09-15 09:35:25.588   928  2858 D wifi    : array field set
,09-15 09:35:25.589   928  2858 I WifiNative-HAL: interface[0] = wlan0
09-15 09:35:25.591   928  5481 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547504982272
09-15 09:35:25.591   928  5481 D wifi    : waitForHalEvents called, vm = 0x7f963cd140, obj = 0x201886, env = 0x7f7a849e80
,09-15 09:35:25.673  5482  5482 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 09:35:25.693   928  2858 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-15 09:35:25.693  5482  5482 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 09:35:25.703  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:25.706  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:25.722  5482  5482 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 09:35:25.722  5482  5482 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 09:35:25.737   928  2858 D WifiConfigStore: Loading config and enabling all networks 
09-15 09:35:25.738  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:25.738  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:25.738  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:25.738  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:25.738  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:25.738  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 09:35:25.738  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:25.738  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:25.738  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 09:35:25.738  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:25.738  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 09:35:25.740  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:25.740  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:25.740  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:25.740  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:25.740  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:25.740  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 09:35:25.740  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:25.740  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:25.740  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 09:35:25.740  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 09:35:25.740  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 09:35:25.747   928  2858 D WifiConfigStore: loaded 0 passpoint configs
09-15 09:35:25.747   928  2858 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 09:35:25.747   928  2858 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-15 09:35:25.748   928  2858 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-15 09:35:25.749   928  2858 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-15 09:35:25.749   928  2858 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 09:35:25.749   928  2858 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-15 09:35:25.750   928  2858 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 09:35:25.753   928  2858 D WifiNative-HAL: Setting external_sim to 1
,09-15 09:35:25.753   928  2858 D wifi    : setting dfs flag to true, 0x7f7d1a6e00
,09-15 09:35:25.754  4208  4208 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 09:35:25.754   928  2858 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 09:35:25.754   928  2858 D wifi    : setting scan oui 0x7f7d1a6e00
09-15 09:35:25.754   928  2858 D WifiHAL : Sending mac address OUI
,09-15 09:35:25.768   928  2858 E native  : do suspend true
,09-15 09:35:25.774   928  2858 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-15 09:35:25.774   928   928 D RttService: SCAN_AVAILABLE : 3
09-15 09:35:25.774   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-15 09:35:25.774   928  2973 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 09:35:25.775   507   922 D CommandListener: Setting iface cfg
,09-15 09:35:25.780   928  2857 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
09-15 09:35:25.780   928  2857 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 09:35:25.786   928  2857 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 09:35:25.791   928  2857 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 09:35:25.791   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=232802 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,09-15 09:35:25.869   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 09:35:26.869   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 09:35:27.870   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 09:35:27.954   928  3592 D WifiService: setWifiEnabled: false pid=5322, uid=10077
,09-15 09:35:27.954   928  3592 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 09:35:27.961   928   928 D RttService: SCAN_AVAILABLE : 1
,09-15 09:35:27.961   928  2973 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 09:35:27.977   928  2858 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-15 09:35:27.978   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-15 09:35:27.984   928  2858 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 09:35:27.986  5482  5482 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-15 09:35:27.995  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 09:35:27.995  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:27.995  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:27.995  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:27.995  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 09:35:27.995  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 09:35:27.995  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:27.995  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:27.995  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 09:35:27.995  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 09:35:27.995  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 09:35:27.998  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 09:35:27.998  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:27.998  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:27.998  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:27.998  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 09:35:27.998  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 09:35:27.998  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:27.998  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:27.998  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 09:35:27.998  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 09:35:27.998  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 09:35:27.999  5482  5482 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-15 09:35:28.015  5482  5482 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 09:35:28.017  5482  5482 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 09:35:28.121   928  2858 D wifi    : In wifi stop Hal
,09-15 09:35:28.122   928  2858 D wifi    : halHandle = 0x7f79d70900, mVM = 0x7f963cd140, mCls = 0x201886
,09-15 09:35:28.122   928  5481 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-15 09:35:28.122   928  5481 D WifiHAL : Got a signal to exit!!!
09-15 09:35:28.122   928  5481 I WifiHAL : Exit wifi_event_loop
09-15 09:35:28.124   928  2858 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 09:35:28.124   928  2858 E WifiHAL : Event processing terminated
,09-15 09:35:28.125   928  2858 D wifi    : In wifi cleaned up handler
,09-15 09:35:28.125   928  2858 I WifiHAL : Internal cleanup completed
09-15 09:35:28.126  4208  4208 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 09:35:28.127  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:28.129  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:28.137  3519  3923 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 09:35:28.159   928  5481 D wifi    : set interface wlan0 flags (DOWN)
,09-15 09:35:28.160   928  2858 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 09:35:28.365   928   945 D Tethering: InitialState.processMessage what=4
,09-15 09:35:28.373   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-15 09:35:30.994   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@49f2c06:true
,09-15 09:35:30.995  5438  5438 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 09:35:31.002  5438  5438 I bt_bluedroid: init
,09-15 09:35:31.002  5438  5488 I BluetoothAdapterState: Entering OffState
,09-15 09:35:31.006  5438  5489 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-15 09:35:31.007  5438  5489 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-15 09:35:31.007  5438  5489 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 09:35:31.007  5438  5489 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-15 09:35:31.009  5438  5438 I bt_bluedroid: get_profile_interface socket
,09-15 09:35:31.013  5438  5438 I bt_bluedroid: get_profile_interface sdp
,09-15 09:35:31.014  5438  5492 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 09:35:31.017  5438  5492 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 09:35:31.026  5438  5448 I bt_bluedroid: config_hci_snoop_log
09-15 09:35:31.029   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 09:35:31.037  5438  5488 D BluetoothAdapterState: Current state: OFF, message: 0
09-15 09:35:31.037  5438  5488 D BluetoothAdapterProperties: Setting state to 14
,09-15 09:35:31.038  5438  5488 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-15 09:35:31.041  5438  5488 D BluetoothBondStateMachine: make
,09-15 09:35:31.044  5438  5493 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 09:35:31.049  5438  5488 I BluetoothAdapterState: Entering PendingCommandState
,09-15 09:35:31.052  5438  5438 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 09:35:31.057  5438  5438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
,09-15 09:35:31.058  5438  5438 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 09:35:31.060  5438  5438 D BtGatt.GattService: Received start request. Starting profile...
,09-15 09:35:31.060  5438  5438 D BtGatt.GattService: start()
09-15 09:35:31.060  5438  5438 I bt_bluedroid: get_profile_interface gatt
,09-15 09:35:31.062  5438  5438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
,09-15 09:35:31.063  5438  5438 D BtGatt.AdvertiseManager: advertise manager created
,09-15 09:35:31.071  5438  5438 V BluetoothAdapterState: isTurningOff()=false
,09-15 09:35:31.071  5438  5438 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:31.071  5438  5438 V BluetoothAdapterState: isBleTurningOn()=true
09-15 09:35:31.072  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:31.072  5438  5488 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 09:35:31.074  5438  5488 I bt_bluedroid: bt_bluedroid
,09-15 09:35:31.074  5438  5489 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 09:35:31.075  5438  5489 I bt_hci  : start_up
,09-15 09:35:31.083  5438  5489 I bt_vendor: alloc value 0xf3cec871
,09-15 09:35:31.083  5438  5489 I bt_vendor: init
09-15 09:35:31.083  5438  5489 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 09:35:31.083  5438  5489 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 09:35:31.196  5438  5489 D bt_hci  : start_up starting async portion
,09-15 09:35:31.196  5438  5496 I bt_hci  : event_finish_startup
09-15 09:35:31.197  5438  5496 I bt_hci_h4: hal_open
09-15 09:35:31.197  5438  5496 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-15 09:35:31.193  5497  5497 W irq/448-msm_hs_: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 09:35:31.200  5438  5496 I bt_userial_vendor: device fd = 54 open
,09-15 09:35:31.214  5438  5496 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 09:35:31.217  5438  5496 D bt_hwcfg: Chipset BCM4358A3
,09-15 09:35:31.217  5438  5496 D bt_hwcfg: Target name = [BCM4358A3]
09-15 09:35:31.218  5438  5496 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 09:35:31.612  5438  5496 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-15 09:35:31.613  5438  5496 D bt_hwcfg: Settlement delay -- 100 ms
,09-15 09:35:31.613  5438  5496 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 09:35:31.747  5438  5496 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-15 09:35:31.747  5438  5496 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-15 09:35:31.749  5438  5496 I bt_hwcfg: vendor lib fwcfg completed
09-15 09:35:31.749  5438  5496 I bt_vendor: firmware callback
09-15 09:35:31.749  5438  5496 I bt_hci  : firmware_config_callback
,09-15 09:35:31.758  5438  5499 I bt_btu  : btu_task pending for preload complete event
09-15 09:35:31.758  5438  5499 I bt_btu_task: Bluetooth chip preload is complete
09-15 09:35:31.758  5438  5499 I bt_btu  : btu_task received preload complete event
,09-15 09:35:31.758   928   928 E WifiNative-wlan0: set PNO failure
,09-15 09:35:31.766  5438  5499 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 09:35:31.766  5438  5499 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 09:35:31.767  5438  5499 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 09:35:31.767  5438  5499 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 09:35:31.767  5438  5499 I         : BTE_InitTraceLevels -- TRC_AVRC
09-15 09:35:31.767  5438  5499 I         : BTE_InitTraceLevels -- TRC_A2D
09-15 09:35:31.767  5438  5499 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-15 09:35:31.767  5438  5499 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 09:35:31.767  5438  5499 I         : BTE_InitTraceLevels -- TRC_GAP
09-15 09:35:31.767  5438  5499 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 09:35:31.767  5438  5499 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 09:35:31.768  5438  5499 I         : BTE_InitTraceLevels -- TRC_GATT
,09-15 09:35:31.768  5438  5499 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 09:35:31.768  5438  5499 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-15 09:35:31.768  5438  5499 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 09:35:31.850  5438  5499 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c6a549
,09-15 09:35:31.850  5438  5499 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c6a549 
,09-15 09:35:31.872  5438  5492 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 09:35:31.873  5438  5492 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 09:35:31.874  5438  5492 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 09:35:31.876  5438  5492 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 09:35:31.879  5438  5492 D BluetoothAdapterProperties: Scan Mode:20
09-15 09:35:31.880  5438  5492 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 09:35:31.880  5438  5492 D bt_hci  : do_postload posting postload work item
09-15 09:35:31.880  5438  5496 I bt_hci  : event_postload
,09-15 09:35:31.881  5438  5496 I bt_vendor: sco_config_cb
09-15 09:35:31.881  5438  5496 I bt_hci  : sco_config_callback postload finished.
09-15 09:35:31.885  5438  5492 D bt_bte_conf: Device ID record 1 : primary
09-15 09:35:31.886  5438  5492 D bt_bte_conf:   vendorId            = 000f
09-15 09:35:31.886  5438  5492 D bt_bte_conf:   vendorIdSource      = 0001
09-15 09:35:31.886  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:31.886  5438  5492 D bt_bte_conf:   product             = 1200
09-15 09:35:31.886  5438  5492 D bt_bte_conf:   version             = 1436
09-15 09:35:31.886  5438  5492 D bt_bte_conf:   clientExecutableURL = 
09-15 09:35:31.886  5438  5492 D bt_bte_conf:   serviceDescription  = 
,09-15 09:35:31.886  5438  5492 D bt_bte_conf:   documentationURL    = 
,09-15 09:35:31.886  5438  5492 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-15 09:35:31.887  5438  5489 D bt_stack_manager: event_start_up_stack finished
09-15 09:35:31.888  5438  5488 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-15 09:35:31.889  5438  5488 D BluetoothAdapterProperties: Setting state to 15
09-15 09:35:31.889  5438  5488 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-15 09:35:31.889  5438  5496 I bt_vendor: low_power_mode_cb
09-15 09:35:31.891  5438  5488 I BluetoothAdapterState: Entering BleOnState
09-15 09:35:31.894  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:31.897  5438  5488 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-15 09:35:31.897  5438  5488 D BluetoothAdapterProperties: Setting state to 11
09-15 09:35:31.897  5438  5488 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-15 09:35:31.902  5438  5438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
09-15 09:35:31.903  5438  5438 D HeadsetService: Received start request. Starting profile...
09-15 09:35:31.904  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:31.906  5438  5438 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 09:35:31.906  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:31.906  5438  5438 D HeadsetStateMachine: make
,09-15 09:35:31.915  5438  5488 I BluetoothAdapterState: Entering PendingCommandState
,09-15 09:35:31.916  5438  5438 D HeadsetStateMachine: max_hf_connections = 1
09-15 09:35:31.916  5438  5438 I bt_bluedroid: get_profile_interface handsfree
09-15 09:35:31.917  5438  5492 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 09:35:31.917  5438  5492 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-15 09:35:31.920  5438  5438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
,09-15 09:35:31.921  5438  5438 D A2dpService: Received start request. Starting profile...
,09-15 09:35:31.921  5438  5438 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-15 09:35:31.922  5438  5438 I bt_bluedroid: get_profile_interface avrcp
,09-15 09:35:31.927  5438  5438 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-15 09:35:31.928  5438  5438 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 09:35:31.928  5438  5438 D A2dpStateMachine: make
09-15 09:35:31.928  5438  5438 I bt_bluedroid: get_profile_interface a2dp
,09-15 09:35:31.929  5438  5492 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 09:35:31.931  5438  5508 D A2dpStateMachine: Enter Disconnected: -2
,09-15 09:35:31.933  5438  5438 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 09:35:31.934  5438  5438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
09-15 09:35:31.934  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 09:35:31.935  5374  5374 D BluetoothInputDevice: Proxy object connected
09-15 09:35:31.935  5438  5438 D HidService: Received start request. Starting profile...
09-15 09:35:31.935  5438  5438 I bt_bluedroid: get_profile_interface hidhost
09-15 09:35:31.936  5438  5438 D HidService: setHidService(): set to: null
09-15 09:35:31.936  5438  5492 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c4b56d
09-15 09:35:31.936  5438  5492 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-15 09:35:31.936  5438  5438 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 09:35:31.936  5374  5374 D HidProfile: Bluetooth service connected
09-15 09:35:31.937  5438  5438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
09-15 09:35:31.937  5438  5438 D HealthService: Received start request. Starting profile...
,09-15 09:35:31.939  5438  5438 I bt_bluedroid: get_profile_interface health
09-15 09:35:31.940  5438  5438 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-15 09:35:31.940  5438  5438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
,09-15 09:35:31.941  5438  5438 D PanService: Received start request. Starting profile...
,09-15 09:35:31.942  5374  5374 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 09:35:31.942  5438  5438 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 09:35:31.942  5438  5438 I bt_bluedroid: get_profile_interface pan
09-15 09:35:31.942  5438  5492 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-15 09:35:31.943  5374  5374 D PanProfile: Bluetooth service connected
,09-15 09:35:31.946  5438  5438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
,09-15 09:35:31.947  5438  5438 D BluetoothMapService: Received start request. Starting profile...
,09-15 09:35:31.947  5438  5438 D BluetoothMapService: start()
09-15 09:35:31.950  5438  5438 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-15 09:35:31.951  5438  5438 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-15 09:35:31.951  5438  5438 D BluetoothMapAppObserver: createReceiver()
09-15 09:35:31.952  5438  5438 D BluetoothMapAppObserver: initObservers()
09-15 09:35:31.952  5438  5438 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 09:35:31.956  5374  5374 D BluetoothMap: Proxy object connected
,09-15 09:35:31.957  5374  5374 D MapProfile: Bluetooth service connected
09-15 09:35:31.957  5374  5374 D BluetoothMap: getConnectedDevices()
,09-15 09:35:31.957  5374  5374 D BluetoothMap: Bluetooth is Not enabled
,09-15 09:35:31.960  5438  5438 V SapService: SapBinder()
,09-15 09:35:31.960  5438  5438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
09-15 09:35:31.961  5438  5438 D SapService: Received start request. Starting profile...
09-15 09:35:31.961  5438  5438 V SapService: start()
,09-15 09:35:31.962  5438  5438 V BluetoothAdapterState: isTurningOff()=false
,09-15 09:35:31.962  5438  5438 V BluetoothAdapterState: isTurningOn()=true
09-15 09:35:31.962  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:31.962  5438  5506 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 09:35:31.962  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:31.963  5438  5438 V BluetoothAdapterState: isTurningOff()=false
09-15 09:35:31.963  5438  5438 V BluetoothAdapterState: isTurningOn()=true
09-15 09:35:31.963  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:31.963  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:31.963  5438  5438 V BluetoothAdapterState: isTurningOff()=false
09-15 09:35:31.963  5438  5438 V BluetoothAdapterState: isTurningOn()=true
09-15 09:35:31.963  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:31.963  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:31.963  5438  5438 V BluetoothAdapterState: isTurningOff()=false
09-15 09:35:31.963  5438  5438 V BluetoothAdapterState: isTurningOn()=true
,09-15 09:35:31.963  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:31.963  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:31.963  5438  5438 V BluetoothAdapterState: isTurningOff()=false
09-15 09:35:31.964  5438  5438 V BluetoothAdapterState: isTurningOn()=true
09-15 09:35:31.964  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:31.964  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:31.964  5438  5438 V BluetoothAdapterState: isTurningOff()=false
09-15 09:35:31.964  5438  5438 V BluetoothAdapterState: isTurningOn()=true
09-15 09:35:31.964  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:31.964  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:31.965  5438  5438 V BluetoothAdapterState: isTurningOff()=false
09-15 09:35:31.965  5438  5438 V BluetoothAdapterState: isTurningOn()=true
09-15 09:35:31.965  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:31.965  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:31.965  5438  5488 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 09:35:31.965  5438  5488 D BluetoothAdapterProperties: ScanMode =  20
,09-15 09:35:31.965  5438  5488 D BluetoothAdapterProperties: State =  11
09-15 09:35:31.966  5438  5488 D BluetoothAdapterProperties: Setting state to 12
09-15 09:35:31.966  5438  5488 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 09:35:31.967  5438  5488 I BluetoothAdapterState: Entering OnState
09-15 09:35:31.968  3037  3051 D BluetoothMap: onBluetoothStateChange: up=true
,09-15 09:35:31.969  5438  5492 D BluetoothAdapterProperties: Scan Mode:21
09-15 09:35:31.970  5438  5492 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-15 09:35:31.970  3037  5321 D BluetoothPan: onBluetoothStateChange on: true
09-15 09:35:31.970  3037  3037 D BluetoothMap: Proxy object connected
09-15 09:35:31.970  3037  3037 D MapProfile: Bluetooth service connected
09-15 09:35:31.970  3037  3037 D BluetoothMap: getConnectedDevices()
09-15 09:35:31.972  3037  3051 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 09:35:31.973  5374  5385 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 09:35:31.973  3037  3037 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 09:35:31.973  3037  3037 D PanProfile: Bluetooth service connected
,09-15 09:35:31.974  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:31.974  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:31.974  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:31.974  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 09:35:31.974  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:31.974  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:31.974  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:31.974  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 09:35:31.974   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 09:35:31.974   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-15 09:35:31.975  3037  3049 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-15 09:35:31.976  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 09:35:31.976   928   928 D BluetoothA2dp: Proxy object connected
09-15 09:35:31.978  3037  3037 D BluetoothInputDevice: Proxy object connected
09-15 09:35:31.978  3037  3037 D HidProfile: Bluetooth service connected
09-15 09:35:31.978  5374  5384 D BluetoothPan: onBluetoothStateChange on: true
09-15 09:35:31.978  3037  5321 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 09:35:31.979   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 09:35:31.979  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:31.979  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:31.979  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:31.979  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 09:35:31.979  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:31.979  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:31.979  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:31.979  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 09:35:31.979  3037  3051 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 09:35:31.979  5438  5438 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 09:35:31.980  5438  5438 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-15 09:35:31.981  3037  3037 D BluetoothA2dp: Proxy object connected
,09-15 09:35:31.981  5374  5385 D BluetoothMap: onBluetoothStateChange: up=true
09-15 09:35:31.982  5438  5438 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 09:35:31.982  3415  3643 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 09:35:31.983  5374  5384 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 09:35:31.983  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 09:35:31.983   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 09:35:31.984   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,09-15 09:35:31.985  5438  5438 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 09:35:31.986  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:31.986  5438  5438 D ObexServerSockets: Succeed to create listening sockets 
09-15 09:35:31.986  5438  5438 D ObexServerSockets0: startAccept()
09-15 09:35:31.987  5438  5438 D ObexServerSockets0: prepareForNewConnect()
09-15 09:35:31.988  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:31.988  5374  5374 D LocalBluetoothProfileManager: Adding local A2DP profile
09-15 09:35:31.989  5438  5438 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-15 09:35:31.989  5438  5438 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 09:35:31.989  5438  5513 D ObexServerSockets0: Accepting socket connection...
09-15 09:35:31.989  5438  5438 D BluetoothMapService: onReceive
,09-15 09:35:31.989  5438  5438 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 09:35:31.989  5438  5438 D BluetoothMapService: STATE_ON
09-15 09:35:31.990  5438  5514 D ObexServerSockets0: Accepting socket connection...
,09-15 09:35:31.992  5438  5515 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 09:35:31.994  5438  5515 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-15 09:35:31.994  5438  5515 D BluetoothSdpJni: SDP Create record success - handle: 1
09-15 09:35:31.995  5374  5374 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-15 09:35:32.000  5374  5374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 09:35:32.003  5374  5374 D BluetoothA2dp: Proxy object connected
,09-15 09:35:32.008  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 09:35:32.008  5374  5374 D DockEventReceiver: finishStartingService: stopping service
,09-15 09:35:32.014  3037  3037 D BluetoothPbap: Proxy object connected
,09-15 09:35:32.014  5374  5374 D BluetoothPbap: Proxy object connected
09-15 09:35:32.014  5438  5438 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 09:35:32.014  3037  3037 D PbapServerProfile: Bluetooth service connected
09-15 09:35:32.014  5438  5438 D ObexServerSockets0: prepareForNewConnect()
09-15 09:35:32.015  5374  5374 D PbapServerProfile: Bluetooth service connected
,09-15 09:35:32.022  5438  5519 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 09:35:32.034  5438  5523 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 09:35:32.035  5438  5523 I BtOppRfcommListener: Accept thread started.
,09-15 09:35:32.074   928   928 D BluetoothHeadset: Proxy object connected
,09-15 09:35:32.074   928   945 D BluetoothHeadset: Proxy object connected
09-15 09:35:32.074  3037  3049 D BluetoothHeadset: Proxy object connected
09-15 09:35:32.074  3037  3037 D HeadsetProfile: Bluetooth service connected
09-15 09:35:32.074   928   928 D BluetoothHeadset: Proxy object connected
09-15 09:35:32.074   928   928 D BluetoothHeadset: Proxy object connected
09-15 09:35:32.075  3415  3434 D BluetoothHeadset: Proxy object connected
,09-15 09:35:32.079   928   945 D BluetoothHeadset: Proxy object connected
,09-15 09:35:32.083  3415  3455 D BluetoothHeadset: Proxy object connected
,09-15 09:35:32.083   928   945 D BluetoothHeadset: Proxy object connected
,09-15 09:35:32.097  5374  5384 D BluetoothHeadset: Proxy object connected
,09-15 09:35:32.101  5374  5374 D HeadsetProfile: Bluetooth service connected
,09-15 09:35:32.871   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 09:35:33.872   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 09:35:33.976  5438  5488 D BluetoothAdapterState: Current state: ON, message: 23
09-15 09:35:33.977  5438  5488 D BluetoothAdapterProperties: Setting state to 13
,09-15 09:35:33.977  5438  5488 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-15 09:35:33.978  5438  5488 D BluetoothAdapterProperties: onBluetoothDisable()
09-15 09:35:33.979  5438  5488 I BluetoothAdapterState: Entering PendingCommandState
,09-15 09:35:33.983  5438  5492 D BluetoothAdapterProperties: Scan Mode:20
09-15 09:35:33.984  5438  5488 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-15 09:35:33.985  5438  5438 D BluetoothMapService: onReceive
,09-15 09:35:33.986  5438  5438 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 09:35:33.986  5438  5438 D BluetoothMapService: STATE_TURNING_OFF
,09-15 09:35:33.986  5438  5438 D BluetoothMapService: MAP Service closeService in
09-15 09:35:33.987  5438  5438 D BluetoothMapMasInstance0: MAP Service shutdown
09-15 09:35:33.987  5438  5438 D ObexServerSockets0: shutdown(block = true)
09-15 09:35:33.988  5438  5438 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 09:35:33.989  5438  5501 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-15 09:35:33.989  5438  5513 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-15 09:35:33.990  5438  5514 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-15 09:35:33.989  5438  5438 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 09:35:33.996  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 09:35:33.996  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:33.996  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:33.996  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:33.996  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 09:35:33.996  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 09:35:33.996  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:33.996  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:33.996  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 09:35:33.998  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 09:35:33.999  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 09:35:34.000  5438  5438 D HeadsetService: Received stop request...Stopping profile...
,09-15 09:35:34.001  5374  5374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 09:35:34.002   928   928 D BluetoothHeadset: Proxy object disconnected
09-15 09:35:34.003  3037  3051 D BluetoothHeadset: Proxy object disconnected
,09-15 09:35:34.004   928   928 D BluetoothHeadset: Proxy object disconnected
09-15 09:35:34.004   928   928 D BluetoothHeadset: Proxy object disconnected
09-15 09:35:34.004  5438  5438 D A2dpService: Received stop request...Stopping profile...
,09-15 09:35:34.004  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:34.005  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:34.005  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:34.005  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:34.005  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 09:35:34.005  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 09:35:34.005  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:34.005  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:34.005  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 09:35:34.005  5374  5384 D BluetoothHeadset: Proxy object disconnected
09-15 09:35:34.005  5438  5508 D A2dpStateMachine: Exit Disconnected: -1
09-15 09:35:34.006  5322  5322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 09:35:34.006  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 09:35:34.006  3415  3643 D BluetoothHeadset: Proxy object disconnected
,09-15 09:35:34.007   928   928 D BluetoothA2dp: Proxy object disconnected
09-15 09:35:34.008  5374  5374 D HeadsetProfile: Bluetooth service disconnected
,09-15 09:35:34.008  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:34.010  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:34.011  5438  5438 D HidService: Received stop request...Stopping profile...
,09-15 09:35:34.011  5438  5438 D HidService: Stopping Bluetooth HidService
,09-15 09:35:34.013  5438  5438 D HealthService: Received stop request...Stopping profile...
,09-15 09:35:34.015  5374  5374 D DockEventReceiver: finishStartingService: stopping service
09-15 09:35:34.017  5438  5438 D PanService: Received stop request...Stopping profile...
09-15 09:35:34.018  5374  5374 D BluetoothA2dp: Proxy object disconnected
09-15 09:35:34.019  5438  5438 D BluetoothMapService: Received stop request...Stopping profile...
09-15 09:35:34.019  5374  5374 D BluetoothInputDevice: Proxy object disconnected
,09-15 09:35:34.019  5438  5438 D BluetoothMapService: stop()
09-15 09:35:34.019  5374  5374 D HidProfile: Bluetooth service disconnected
09-15 09:35:34.020  5374  5374 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 09:35:34.020  5374  5374 D PanProfile: Bluetooth service disconnected
09-15 09:35:34.020  3037  3037 D HeadsetProfile: Bluetooth service disconnected
09-15 09:35:34.020  5438  5438 D BluetoothMapAppObserver: deinitObservers()
09-15 09:35:34.020  5438  5438 D BluetoothMapAppObserver: removeReceiver()
09-15 09:35:34.020  3037  3037 D BluetoothA2dp: Proxy object disconnected
09-15 09:35:34.021  3037  3037 D BluetoothInputDevice: Proxy object disconnected
09-15 09:35:34.021  3037  3037 D HidProfile: Bluetooth service disconnected
09-15 09:35:34.022  3037  3037 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-15 09:35:34.022  3037  3037 D PanProfile: Bluetooth service disconnected
09-15 09:35:34.022  3037  3037 D BluetoothMap: Proxy object disconnected
09-15 09:35:34.022  3037  3037 D MapProfile: Bluetooth service disconnected
09-15 09:35:34.022  5438  5438 I BtOppRfcommListener: stopping Accept Thread
09-15 09:35:34.022  5374  5374 D BluetoothMap: Proxy object disconnected
09-15 09:35:34.023  5438  5523 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-15 09:35:34.023  5438  5523 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 09:35:34.022  5374  5374 D MapProfile: Bluetooth service disconnected
09-15 09:35:34.024  5438  5438 V BluetoothAdapterState: isTurningOff()=true
09-15 09:35:34.024  5438  5438 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:34.024  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 09:35:34.024  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:34.025  5438  5438 D SapService: Received stop request...Stopping profile...
09-15 09:35:34.025  5438  5438 V SapService: stop()
,09-15 09:35:34.028  5438  5438 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-15 09:35:34.028  5438  5438 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 09:35:34.028  5438  5499 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 09:35:34.028  5438  5499 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 09:35:34.028  5438  5438 V BluetoothAdapterState: isTurningOff()=true
09-15 09:35:34.028  5438  5499 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 09:35:34.028  5438  5438 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:34.028  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:34.029  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:34.029  5438  5492 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 09:35:34.029  5438  5492 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-15 09:35:34.030  5438  5499 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 09:35:34.030  5438  5499 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 09:35:34.030  5438  5499 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 09:35:34.030  5438  5499 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 09:35:34.030  5438  5499 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-15 09:35:34.030  5438  5499 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 09:35:34.031  5438  5492 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-15 09:35:34.031  5438  5438 V BluetoothAdapterState: isTurningOff()=true
09-15 09:35:34.031  5438  5438 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:34.031  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 09:35:34.032  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:34.032  5438  5438 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 09:35:34.032  5438  5438 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 09:35:34.032  5438  5492 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 09:35:34.032  5438  5438 V BluetoothAdapterState: isTurningOff()=true
09-15 09:35:34.032  5438  5438 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:34.032  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 09:35:34.032  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:34.033  5438  5438 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-15 09:35:34.033  5438  5492 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 09:35:34.033  5438  5438 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-15 09:35:34.033  5438  5438 V BluetoothAdapterState: isTurningOff()=true
09-15 09:35:34.033  5438  5438 V BluetoothAdapterState: isTurningOn()=false
,09-15 09:35:34.033  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 09:35:34.033  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 09:35:34.033  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:34.034  5438  5438 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 09:35:34.034  5438  5438 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-15 09:35:34.035  5438  5438 D BluetoothMapService: MAP Service closeService in
09-15 09:35:34.035  5438  5438 V BluetoothAdapterState: isTurningOff()=true
09-15 09:35:34.035  5438  5438 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:34.035  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:34.035  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:34.035  5438  5438 D BluetoothMapService: cleanup()
,09-15 09:35:34.035  5438  5438 D BluetoothMapService: MAP Service closeService in
09-15 09:35:34.037  5438  5438 V BluetoothAdapterState: isTurningOff()=true
09-15 09:35:34.037  5438  5438 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:34.037  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:34.037  5438  5438 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:34.038  5438  5488 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 09:35:34.038  5438  5488 D BluetoothAdapterProperties: Setting state to 15
09-15 09:35:34.038  5438  5488 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 09:35:34.038  3037  3037 D BluetoothPbap: Proxy object disconnected
09-15 09:35:34.039  3037  3037 D PbapServerProfile: Bluetooth service disconnected
09-15 09:35:34.039  5438  5488 I BluetoothAdapterState: Entering BleOnState
09-15 09:35:34.039  3037  3256 D BluetoothMap: onBluetoothStateChange: up=false
09-15 09:35:34.040  3037  3049 D BluetoothPan: onBluetoothStateChange on: false
09-15 09:35:34.040  5374  5374 D BluetoothPbap: Proxy object disconnected
,09-15 09:35:34.043  3037  5321 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 09:35:34.044  5374  5526 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 09:35:34.044   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 09:35:34.044   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 09:35:34.044  5374  5385 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 09:35:34.045  3037  3051 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 09:35:34.045  5374  5384 D BluetoothPan: onBluetoothStateChange on: false
09-15 09:35:34.046  3037  3256 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 09:35:34.046   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 09:35:34.047  3037  3049 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 09:35:34.047  5374  5526 D BluetoothMap: onBluetoothStateChange: up=false
09-15 09:35:34.048  3415  3434 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 09:35:34.048  5374  5385 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 09:35:34.048  5374  5384 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 09:35:34.049   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 09:35:34.049  5438  5488 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 09:35:34.050  5438  5488 D BluetoothAdapterProperties: Setting state to 16
09-15 09:35:34.050  5438  5488 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 09:35:34.050  5438  5488 D BluetoothAdapterProperties: onBleDisable
09-15 09:35:34.040  5374  5374 D PbapServerProfile: Bluetooth service disconnected
09-15 09:35:34.050  5438  5488 I BluetoothAdapterState: Entering PendingCommandState
09-15 09:35:34.052  5438  5492 D BluetoothAdapterProperties: Scan Mode:20
09-15 09:35:34.053  5438  5489 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-15 09:35:34.053  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:34.053  5438  5499 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-15 09:35:34.054  5438  5499 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-15 09:35:34.056  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:34.059  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:34.063  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:34.065  5374  5374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 09:35:34.071  5374  5374 D DockEventReceiver: finishStartingService: stopping service
,09-15 09:35:34.072  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 09:35:34.262  5438  5492 I bt_hci  : shut_down
,09-15 09:35:34.266  5438  5496 D bt_hwcfg: hw_epilog_process
,09-15 09:35:34.267  5438  5496 I bt_vendor: low_power_mode_cb
,09-15 09:35:34.270  5438  5496 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-15 09:35:34.270  5438  5496 I bt_vendor: epilog_cb
,09-15 09:35:34.271  5438  5496 I bt_hci  : epilog_finished_callback
09-15 09:35:34.274  5438  5492 I bt_hci_h4: hal_close
,09-15 09:35:34.275  5438  5492 I bt_userial_vendor: device fd = 54 close
,09-15 09:35:34.387  5438  5489 D bt_stack_manager: event_shut_down_stack finished.
,09-15 09:35:34.388  5438  5488 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-15 09:35:34.392  5438  5488 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-15 09:35:34.393  5438  5438 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 09:35:34.394  5438  5438 D BtGatt.GattService: Received stop request...Stopping profile...
,09-15 09:35:34.394  5438  5438 D BtGatt.GattService: stop()
09-15 09:35:34.394  5438  5438 D BtGatt.AdvertiseManager: advertise clients cleared
,09-15 09:35:34.397  5438  5438 V BluetoothAdapterState: isTurningOff()=false
09-15 09:35:34.397  5438  5438 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:34.398  5438  5438 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:34.398  5438  5438 V BluetoothAdapterState: isBleTurningOff()=true
,09-15 09:35:34.398  5438  5488 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 09:35:34.398  5438  5488 D BluetoothAdapterProperties: Setting state to 10
09-15 09:35:34.399  5438  5488 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 09:35:34.400  5438  5488 I BluetoothAdapterState: Entering OffState
09-15 09:35:34.401   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-15 09:35:34.413  5438  5438 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-15 09:35:34.414  5438  5438 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 09:35:34.414  5438  5438 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-15 09:35:34.416  5438  5489 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 09:35:34.424  5438  5438 I art     : System.exit called, status: 0
,09-15 09:35:34.425  5438  5438 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-15 09:35:34.462   928  3402 I ActivityManager: Process com.android.bluetooth (pid 5438) has died
,09-15 09:35:34.873   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 09:35:35.874   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 09:35:36.875   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 09:35:36.972  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:36.973  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 09:35:37.875   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 09:35:39.979  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:39.979  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3dab210 added. We now have 6 listener(s)
09-15 09:35:39.979  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 09:35:39.984  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 09:35:39.984  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ebee109 added. We now have 7 listener(s)
,09-15 09:35:39.985  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 09:35:39.986  5322  5368 I System.out: IsBluetoothEnabled
,09-15 09:35:39.993  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:40.019   928   945 I ActivityManager: Start proc 5532:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-15 09:35:40.101  5532  5532 D AdapterServiceConfig: Adding HeadsetService
09-15 09:35:40.102  5532  5532 D AdapterServiceConfig: Adding A2dpService
09-15 09:35:40.102  5532  5532 D AdapterServiceConfig: Adding HidService
09-15 09:35:40.102  5532  5532 D AdapterServiceConfig: Adding HealthService
,09-15 09:35:40.102  5532  5532 D AdapterServiceConfig: Adding PanService
09-15 09:35:40.103  5532  5532 D AdapterServiceConfig: Adding GattService
09-15 09:35:40.103  5532  5532 D AdapterServiceConfig: Adding BluetoothMapService
09-15 09:35:40.103  5532  5532 D AdapterServiceConfig: Adding SapService
,09-15 09:35:40.114   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7ed0e87:true
,09-15 09:35:40.115  5532  5532 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 09:35:40.117  5532  5532 I bt_bluedroid: init
,09-15 09:35:40.117  5532  5544 I BluetoothAdapterState: Entering OffState
,09-15 09:35:40.120  5532  5545 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-15 09:35:40.120  5532  5545 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 09:35:40.120  5532  5545 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 09:35:40.120  5532  5545 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-15 09:35:40.121  5532  5532 I bt_bluedroid: get_profile_interface socket
,09-15 09:35:40.122  5532  5548 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 09:35:40.123  5532  5532 I bt_bluedroid: get_profile_interface sdp
09-15 09:35:40.124  5532  5548 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 09:35:40.127  5532  5543 I bt_bluedroid: config_hci_snoop_log
09-15 09:35:40.128   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 09:35:40.132  5532  5544 D BluetoothAdapterState: Current state: OFF, message: 0
,09-15 09:35:40.133  5532  5544 D BluetoothAdapterProperties: Setting state to 14
09-15 09:35:40.133  5532  5544 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-15 09:35:40.134  5532  5544 D BluetoothBondStateMachine: make
,09-15 09:35:40.136  5532  5549 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 09:35:40.139  5532  5544 I BluetoothAdapterState: Entering PendingCommandState
,09-15 09:35:40.140  5532  5532 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 09:35:40.142  5532  5532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
09-15 09:35:40.143  5532  5532 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 09:35:40.143  5532  5532 D BtGatt.GattService: Received start request. Starting profile...
,09-15 09:35:40.143  5532  5532 D BtGatt.GattService: start()
09-15 09:35:40.143  5532  5532 I bt_bluedroid: get_profile_interface gatt
,09-15 09:35:40.144  5532  5532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
09-15 09:35:40.145  5532  5532 D BtGatt.AdvertiseManager: advertise manager created
,09-15 09:35:40.150  5532  5532 V BluetoothAdapterState: isTurningOff()=false
,09-15 09:35:40.150  5532  5532 V BluetoothAdapterState: isTurningOn()=false
09-15 09:35:40.150  5532  5532 V BluetoothAdapterState: isBleTurningOn()=true
09-15 09:35:40.150  5532  5532 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:40.150  5532  5544 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 09:35:40.151  5532  5544 I bt_bluedroid: bt_bluedroid
09-15 09:35:40.152  5532  5545 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 09:35:40.152  5532  5545 I bt_hci  : start_up
,09-15 09:35:40.157  5532  5545 I bt_vendor: alloc value 0xf3d3f871
,09-15 09:35:40.158  5532  5545 I bt_vendor: init
09-15 09:35:40.158  5532  5545 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 09:35:40.158  5532  5545 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 09:35:40.269  5532  5545 D bt_hci  : start_up starting async portion
,09-15 09:35:40.270  5532  5552 I bt_hci  : event_finish_startup
,09-15 09:35:40.270  5532  5552 I bt_hci_h4: hal_open
,09-15 09:35:40.270  5532  5552 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-15 09:35:40.272  5532  5552 I bt_userial_vendor: device fd = 54 open
09-15 09:35:40.266  5553  5553 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 09:35:40.287  5532  5552 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 09:35:40.289  5532  5552 D bt_hwcfg: Chipset BCM4358A3
,09-15 09:35:40.290  5532  5552 D bt_hwcfg: Target name = [BCM4358A3]
09-15 09:35:40.290  5532  5552 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 09:35:40.688  5532  5552 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-15 09:35:40.688  5532  5552 D bt_hwcfg: Settlement delay -- 100 ms
09-15 09:35:40.688  5532  5552 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 09:35:40.822  5532  5552 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 09:35:40.823  5532  5552 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-15 09:35:40.824  5532  5552 I bt_hwcfg: vendor lib fwcfg completed
09-15 09:35:40.824  5532  5552 I bt_vendor: firmware callback
09-15 09:35:40.824  5532  5552 I bt_hci  : firmware_config_callback
,09-15 09:35:40.832  5532  5555 I bt_btu  : btu_task pending for preload complete event
,09-15 09:35:40.833  5532  5555 I bt_btu_task: Bluetooth chip preload is complete
09-15 09:35:40.833  5532  5555 I bt_btu  : btu_task received preload complete event
,09-15 09:35:40.839  5532  5555 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 09:35:40.840  5532  5555 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 09:35:40.840  5532  5555 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 09:35:40.840  5532  5555 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-15 09:35:40.840  5532  5555 I         : BTE_InitTraceLevels -- TRC_AVRC
09-15 09:35:40.840  5532  5555 I         : BTE_InitTraceLevels -- TRC_A2D
09-15 09:35:40.840  5532  5555 I         : BTE_InitTraceLevels -- TRC_BNEP
09-15 09:35:40.840  5532  5555 I         : BTE_InitTraceLevels -- TRC_BTM
,09-15 09:35:40.840  5532  5555 I         : BTE_InitTraceLevels -- TRC_GAP
09-15 09:35:40.841  5532  5555 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 09:35:40.841  5532  5555 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 09:35:40.841  5532  5555 I         : BTE_InitTraceLevels -- TRC_GATT
,09-15 09:35:40.841  5532  5555 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 09:35:40.841  5532  5555 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-15 09:35:40.841  5532  5555 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 09:35:40.923  5532  5555 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cbd549
,09-15 09:35:40.923  5532  5555 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cbd549 
,09-15 09:35:40.940  5532  5548 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 09:35:40.941  5532  5548 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 09:35:40.942  5532  5548 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-15 09:35:40.944  5532  5548 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 09:35:40.947  5532  5548 D BluetoothAdapterProperties: Scan Mode:20
,09-15 09:35:40.947  5532  5548 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 09:35:40.947  5532  5548 D bt_hci  : do_postload posting postload work item
09-15 09:35:40.947  5532  5552 I bt_hci  : event_postload
09-15 09:35:40.948  5532  5552 I bt_vendor: sco_config_cb
09-15 09:35:40.948  5532  5552 I bt_hci  : sco_config_callback postload finished.
,09-15 09:35:40.952  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:40.952  5532  5548 D bt_bte_conf: Device ID record 1 : primary
,09-15 09:35:40.953  5532  5548 D bt_bte_conf:   vendorId            = 000f
,09-15 09:35:40.953  5532  5548 D bt_bte_conf:   vendorIdSource      = 0001
,09-15 09:35:40.953  5532  5548 D bt_bte_conf:   product             = 1200
09-15 09:35:40.953  5532  5548 D bt_bte_conf:   version             = 1436
09-15 09:35:40.953  5532  5548 D bt_bte_conf:   clientExecutableURL = 
09-15 09:35:40.953  5532  5548 D bt_bte_conf:   serviceDescription  = 
09-15 09:35:40.953  5532  5548 D bt_bte_conf:   documentationURL    = 
,09-15 09:35:40.953  5532  5548 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 09:35:40.954  5532  5545 D bt_stack_manager: event_start_up_stack finished
09-15 09:35:40.955  5532  5544 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-15 09:35:40.955  5532  5544 D BluetoothAdapterProperties: Setting state to 15
09-15 09:35:40.955  5532  5544 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-15 09:35:40.956  5532  5544 I BluetoothAdapterState: Entering BleOnState
,09-15 09:35:40.956  5532  5552 I bt_vendor: low_power_mode_cb
,09-15 09:35:40.960  5532  5544 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-15 09:35:40.960  5532  5544 D BluetoothAdapterProperties: Setting state to 11
09-15 09:35:40.960  5532  5544 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-15 09:35:40.965  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:40.969  5532  5532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
,09-15 09:35:40.969  5532  5532 D HeadsetService: Received start request. Starting profile...
09-15 09:35:40.972  5532  5532 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 09:35:40.972  5532  5532 D HeadsetStateMachine: make
,09-15 09:35:40.981  5532  5544 I BluetoothAdapterState: Entering PendingCommandState
,09-15 09:35:40.983  5532  5532 D HeadsetStateMachine: max_hf_connections = 1
,09-15 09:35:40.983  5532  5532 I bt_bluedroid: get_profile_interface handsfree
,09-15 09:35:40.984  5532  5548 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 09:35:40.984  5532  5548 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-15 09:35:40.988  5532  5532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
,09-15 09:35:40.988  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 09:35:40.988  5532  5532 D A2dpService: Received start request. Starting profile...
,09-15 09:35:40.989  5532  5532 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-15 09:35:40.990  5532  5532 I bt_bluedroid: get_profile_interface avrcp
,09-15 09:35:40.995  5532  5532 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-15 09:35:40.995  5532  5532 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 09:35:40.995  5532  5532 D A2dpStateMachine: make
09-15 09:35:40.996  5532  5532 I bt_bluedroid: get_profile_interface a2dp
,09-15 09:35:40.996  5532  5548 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 09:35:40.998  5532  5563 D A2dpStateMachine: Enter Disconnected: -2
,09-15 09:35:40.999  5532  5532 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 09:35:41.000  5532  5532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
,09-15 09:35:41.000  5532  5532 D HidService: Received start request. Starting profile...
09-15 09:35:41.001  5532  5532 I bt_bluedroid: get_profile_interface hidhost
09-15 09:35:41.001  5532  5548 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c9e56d
09-15 09:35:41.001  5532  5532 D HidService: setHidService(): set to: null
09-15 09:35:41.001  5532  5548 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 09:35:41.002  5532  5532 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-15 09:35:41.002  5532  5532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
,09-15 09:35:41.003  5532  5532 D HealthService: Received start request. Starting profile...
,09-15 09:35:41.004  5532  5532 I bt_bluedroid: get_profile_interface health
09-15 09:35:41.005  5532  5532 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-15 09:35:41.005  5532  5532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
,09-15 09:35:41.006  5532  5532 D PanService: Received start request. Starting profile...
,09-15 09:35:41.006  5532  5532 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 09:35:41.006  5532  5532 I bt_bluedroid: get_profile_interface pan
09-15 09:35:41.006  5532  5548 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-15 09:35:41.009  5532  5532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
,09-15 09:35:41.010  5532  5532 D BluetoothMapService: Received start request. Starting profile...
09-15 09:35:41.010  5532  5532 D BluetoothMapService: start()
,09-15 09:35:41.012  5532  5532 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-15 09:35:41.013  5532  5532 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-15 09:35:41.013  5532  5532 D BluetoothMapAppObserver: createReceiver()
,09-15 09:35:41.014  5532  5532 D BluetoothMapAppObserver: initObservers()
,09-15 09:35:41.014  5532  5532 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 09:35:41.020  5532  5532 V SapService: SapBinder()
09-15 09:35:41.020  5532  5532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
,09-15 09:35:41.021  5532  5532 D SapService: Received start request. Starting profile...
09-15 09:35:41.021  5532  5532 V SapService: start()
,09-15 09:35:41.022  5532  5532 V BluetoothAdapterState: isTurningOff()=false
,09-15 09:35:41.022  5532  5532 V BluetoothAdapterState: isTurningOn()=true
09-15 09:35:41.022  5532  5532 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:41.022  5532  5532 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:41.022  5532  5561 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 09:35:41.023  5532  5532 V BluetoothAdapterState: isTurningOff()=false
09-15 09:35:41.023  5532  5532 V BluetoothAdapterState: isTurningOn()=true
09-15 09:35:41.023  5532  5532 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:41.023  5532  5532 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:41.023  5532  5532 V BluetoothAdapterState: isTurningOff()=false
09-15 09:35:41.023  5532  5532 V BluetoothAdapterState: isTurningOn()=true
09-15 09:35:41.023  5532  5532 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:41.023  5532  5532 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:41.023  5532  5532 V BluetoothAdapterState: isTurningOff()=false
09-15 09:35:41.023  5532  5532 V BluetoothAdapterState: isTurningOn()=true
09-15 09:35:41.023  5532  5532 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:41.023  5532  5532 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:41.024  5532  5532 V BluetoothAdapterState: isTurningOff()=false
09-15 09:35:41.024  5532  5532 V BluetoothAdapterState: isTurningOn()=true
09-15 09:35:41.024  5532  5532 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 09:35:41.024  5532  5532 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:41.024  5532  5532 V BluetoothAdapterState: isTurningOff()=false
09-15 09:35:41.024  5532  5532 V BluetoothAdapterState: isTurningOn()=true
,09-15 09:35:41.024  5532  5532 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:41.024  5532  5532 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:41.025  5532  5532 V BluetoothAdapterState: isTurningOff()=false
09-15 09:35:41.025  5532  5532 V BluetoothAdapterState: isTurningOn()=true
09-15 09:35:41.025  5532  5532 V BluetoothAdapterState: isBleTurningOn()=false
09-15 09:35:41.025  5532  5532 V BluetoothAdapterState: isBleTurningOff()=false
09-15 09:35:41.026  5532  5544 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 09:35:41.026  5532  5544 D BluetoothAdapterProperties: ScanMode =  20
09-15 09:35:41.026  5532  5544 D BluetoothAdapterProperties: State =  11
09-15 09:35:41.026  5532  5548 D BluetoothAdapterProperties: Scan Mode:21
09-15 09:35:41.026  5532  5548 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-15 09:35:41.027  5532  5544 D BluetoothAdapterProperties: Setting state to 12
09-15 09:35:41.027  5532  5544 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 09:35:41.028  5532  5544 I BluetoothAdapterState: Entering OnState
09-15 09:35:41.028  3037  3256 D BluetoothMap: onBluetoothStateChange: up=true
,09-15 09:35:41.030  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:41.030  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:41.030  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:41.030  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 09:35:41.030  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:41.030  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:41.030  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:41.030  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 09:35:41.030  3037  5321 D BluetoothPan: onBluetoothStateChange on: true
09-15 09:35:41.031  3037  3037 D BluetoothMap: Proxy object connected
09-15 09:35:41.031  3037  3037 D MapProfile: Bluetooth service connected
09-15 09:35:41.031  3037  3037 D BluetoothMap: getConnectedDevices()
09-15 09:35:41.032  3037  3256 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 09:35:41.033  3037  3037 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 09:35:41.033  5374  5384 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 09:35:41.033  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 09:35:41.033  3037  3037 D PanProfile: Bluetooth service connected
,09-15 09:35:41.034   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 09:35:41.034   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 09:35:41.035  5374  5526 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 09:35:41.036   928   928 D BluetoothA2dp: Proxy object connected
09-15 09:35:41.037  3037  5321 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 09:35:41.038  5374  5384 D BluetoothPan: onBluetoothStateChange on: true
,09-15 09:35:41.039  5532  5532 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 09:35:41.040  5532  5532 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-15 09:35:41.040  3037  3256 D BluetoothPbap: onBluetoothStateChange: up=true
,09-15 09:35:41.041  5532  5532 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 09:35:41.042   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 09:35:41.042  3037  3051 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-15 09:35:41.043  5532  5532 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 09:35:41.043  3037  3037 D BluetoothA2dp: Proxy object connected
09-15 09:35:41.043  5374  5526 D BluetoothMap: onBluetoothStateChange: up=true
09-15 09:35:41.044  5374  5374 D BluetoothA2dp: Proxy object connected
09-15 09:35:41.044  5532  5532 D ObexServerSockets: Succeed to create listening sockets 
09-15 09:35:41.044  5532  5532 D ObexServerSockets0: startAccept()
09-15 09:35:41.044  5532  5532 D ObexServerSockets0: prepareForNewConnect()
09-15 09:35:41.046  3415  3434 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 09:35:41.046  5532  5532 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-15 09:35:41.046  5532  5532 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 09:35:41.047  5374  5384 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 09:35:41.047  5532  5569 D ObexServerSockets0: Accepting socket connection...
09-15 09:35:41.047  5532  5570 D ObexServerSockets0: Accepting socket connection...
09-15 09:35:41.047  5374  5385 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 09:35:41.048  3037  3037 D BluetoothInputDevice: Proxy object connected
09-15 09:35:41.048  3037  3037 D HidProfile: Bluetooth service connected
,09-15 09:35:41.049  5374  5374 D BluetoothPan: BluetoothPAN Proxy object connected
,09-15 09:35:41.049  5374  5374 D PanProfile: Bluetooth service connected
09-15 09:35:41.049  5374  5374 D BluetoothMap: Proxy object connected
09-15 09:35:41.049  5374  5374 D MapProfile: Bluetooth service connected
09-15 09:35:41.049  5374  5374 D BluetoothMap: getConnectedDevices()
09-15 09:35:41.050   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 09:35:41.051  5532  5532 D BluetoothMapService: onReceive
,09-15 09:35:41.051  5532  5532 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 09:35:41.051  5532  5532 D BluetoothMapService: STATE_ON
09-15 09:35:41.052   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-15 09:35:41.052  5374  5374 D BluetoothInputDevice: Proxy object connected
09-15 09:35:41.052  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:41.052  5374  5374 D HidProfile: Bluetooth service connected
09-15 09:35:41.053  5532  5571 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 09:35:41.055  5532  5571 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-15 09:35:41.055  5532  5571 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-15 09:35:41.058  5374  5374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 09:35:41.064  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 09:35:41.065  5374  5374 D DockEventReceiver: finishStartingService: stopping service
,09-15 09:35:41.070  5374  5374 D BluetoothPbap: Proxy object connected
,09-15 09:35:41.070  5374  5374 D PbapServerProfile: Bluetooth service connected
,09-15 09:35:41.075  5532  5532 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 09:35:41.075  5532  5532 D ObexServerSockets0: prepareForNewConnect()
,09-15 09:35:41.076  5532  5575 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 09:35:41.083  3037  3037 D BluetoothPbap: Proxy object connected
,09-15 09:35:41.083  3037  3037 D PbapServerProfile: Bluetooth service connected
,09-15 09:35:41.090  5532  5579 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 09:35:41.091  5532  5579 I BtOppRfcommListener: Accept thread started.
,09-15 09:35:41.134   928   928 D BluetoothHeadset: Proxy object connected
,09-15 09:35:41.135  3037  5321 D BluetoothHeadset: Proxy object connected
09-15 09:35:41.135  3037  3037 D HeadsetProfile: Bluetooth service connected
09-15 09:35:41.135   928   928 D BluetoothHeadset: Proxy object connected
09-15 09:35:41.135   928   928 D BluetoothHeadset: Proxy object connected
09-15 09:35:41.135  5374  5526 D BluetoothHeadset: Proxy object connected
09-15 09:35:41.136  3415  3455 D BluetoothHeadset: Proxy object connected
09-15 09:35:41.137  5374  5374 D HeadsetProfile: Bluetooth service connected
,09-15 09:35:41.142   928   945 D BluetoothHeadset: Proxy object connected
,09-15 09:35:41.147  3415  3643 D BluetoothHeadset: Proxy object connected
,09-15 09:35:41.147  5374  5385 D BluetoothHeadset: Proxy object connected
09-15 09:35:41.148  5374  5374 D HeadsetProfile: Bluetooth service connected
,09-15 09:35:41.151   928   945 D BluetoothHeadset: Proxy object connected
,09-15 09:35:42.010  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:42.010  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:42.010  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:42.010  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 09:35:42.010  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:42.010  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:42.010  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:42.010  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 09:35:42.015  5322  5368 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 09:35:42.018  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 09:35:42.019  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ccbf0e added. We now have 8 listener(s)
09-15 09:35:42.019  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 09:35:42.026   928   938 D WifiService: setWifiEnabled: false pid=5322, uid=10077
,09-15 09:35:42.026   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 09:35:42.034  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:42.035   928  3402 D WifiService: setWifiEnabled: true pid=5322, uid=10077
,09-15 09:35:42.035   928  3402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 09:35:42.041   507   922 D SoftapController: Softap fwReload - Ok
,09-15 09:35:42.046   507   922 D CommandListener: Setting iface cfg
,09-15 09:35:42.046   507   922 D CommandListener: Trying to bring down wlan0
,09-15 09:35:42.048   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-15 09:35:42.052   928  2858 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 09:35:42.655   928  2858 D wifi    : set interface wlan0 flags (UP)
,09-15 09:35:42.660   928  2858 I WifiHAL : Initializing wifi
09-15 09:35:42.660   928  2858 I WifiHAL : Creating socket
09-15 09:35:42.663   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
09-15 09:35:42.665   928  2858 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-15 09:35:42.666   928  2858 D wifi    : Did set static halHandle = 0x7f79d70900
09-15 09:35:42.666   928  2858 D wifi    : halHandle = 0x7f79d70900, mVM = 0x7f963cd140, mCls = 0x101932
09-15 09:35:42.666   928  2858 D wifi    : array field set
,09-15 09:35:42.667   928  2858 I WifiNative-HAL: interface[0] = wlan0
09-15 09:35:42.669   928  5584 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547504982272
09-15 09:35:42.670   928  5584 D wifi    : waitForHalEvents called, vm = 0x7f963cd140, obj = 0x101932, env = 0x7f77bd3080
,09-15 09:35:42.715  5585  5585 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 09:35:42.733  5585  5585 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 09:35:42.740  5585  5585 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 09:35:42.740  5585  5585 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 09:35:42.771   928  2858 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-15 09:35:42.789   928  2858 D WifiConfigStore: Loading config and enabling all networks 
,09-15 09:35:42.790  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:42.790  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:42.790  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:42.790  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:42.790  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:42.790  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:42.790  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:42.790  5322  5322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 09:35:42.793  5322  5322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 09:35:42.794  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:42.800   928  2858 D WifiConfigStore: loaded 0 passpoint configs
09-15 09:35:42.800   928  2858 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-15 09:35:42.801   928  2858 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-15 09:35:42.802   928  2858 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-15 09:35:42.803   928  2858 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-15 09:35:42.803   928  2858 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 09:35:42.804   928  2858 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-15 09:35:42.804   928  2858 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 09:35:42.807   928  2858 D WifiNative-HAL: Setting external_sim to 1
,09-15 09:35:42.807  4208  4208 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 09:35:42.808   928  2858 D wifi    : setting dfs flag to true, 0x7f7bdf9ea0
,09-15 09:35:42.808   928  2858 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 09:35:42.809   928  2858 D wifi    : setting scan oui 0x7f7bdf9ea0
09-15 09:35:42.809   928  2858 D WifiHAL : Sending mac address OUI
,09-15 09:35:42.823   928  2858 E native  : do suspend true
,09-15 09:35:42.828   928   928 D RttService: SCAN_AVAILABLE : 3
,09-15 09:35:42.828   928  2858 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-15 09:35:42.828   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-15 09:35:42.828   928  2973 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-15 09:35:42.829   507   922 D CommandListener: Setting iface cfg
,09-15 09:35:42.833   928  2857 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '75 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 75 Failed to set address (No such device)'
09-15 09:35:42.833   928  2857 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 09:35:42.839   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=249850 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,09-15 09:35:42.840   928  2857 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 09:35:42.840   928  2857 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 09:35:43.058  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 09:35:43.058  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:43.058  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:43.058  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:43.058  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:43.058  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:43.058  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:43.058  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 09:35:43.064  5322  5368 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 09:35:43.073  5322  5368 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-15 09:35:43.074  5322  5368 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-15 09:35:43.077  5322  5368 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@590b876 Bundle[{}]
09-15 09:35:43.078  5322  5368 I io.jxcore.node.LifeCycleMonitor: start: OK
09-15 09:35:43.078  5322  5368 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-15 09:35:43.078  5322  5368 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-15 09:35:43.079  5322  5368 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-15 09:35:43.080  5322  5368 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-15 09:35:43.081  5322  5368 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-15 09:35:43.087  5322  5368 I System.out: Running OutgoingSocketThread
,09-15 09:35:43.088  5322  5587 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 151)
,09-15 09:35:43.090  5322  5587 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44057
,09-15 09:35:43.090  5322  5587 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-15 09:35:44.090  5322  5368 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 152)
,09-15 09:35:44.090  5322  5368 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 152)
,09-15 09:35:44.096  5322  5368 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 157)
,09-15 09:35:44.098  5322  5368 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-15 09:35:44.098  5322  5368 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,09-15 09:35:44.103  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 09:35:44.104  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d37cd2f added. We now have 2 listener(s)
09-15 09:35:44.107  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 09:35:44.107  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 09:35:44.108  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 09:35:44.108  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:44.108  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0df3c added. We now have 9 listener(s)
09-15 09:35:44.108  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 09:35:44.109  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 09:35:44.113  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 09:35:44.117  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 09:35:44.117  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:44.117  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:44.117  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:44.117  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:44.117  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:44.117  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:44.117  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 09:35:44.120  5322  5368 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 09:35:44.120  5322  5368 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 09:35:44.120  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 09:35:44.120  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a19be1a added. We now have 3 listener(s)
09-15 09:35:44.122  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 09:35:44.122  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:44.122  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 09:35:44.123  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 09:35:44.123  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:44.123  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fe0d4b added. We now have 10 listener(s)
09-15 09:35:44.123  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 09:35:44.123  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:44.123  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:44.123  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 09:35:44.123  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:44.124  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.124  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 09:35:44.124  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 09:35:44.124  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d37cd2f removed from the list
09-15 09:35:44.124  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 09:35:44.124  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0df3c removed from the list
09-15 09:35:44.124  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:44.125  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:44.125  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:44.126  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.126  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 09:35:44.128  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:44.128  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:44.128  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:44.129  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0df3c not in the list
09-15 09:35:44.129  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 09:35:44.129  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 09:35:44.131  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 09:35:44.131  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:44.131  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:44.131  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fe0d4b removed from the list
09-15 09:35:44.131  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:44.131  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.131  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:44.131  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 09:35:44.131  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a19be1a removed from the list
09-15 09:35:44.132  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 09:35:44.132  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53ab328 added. We now have 2 listener(s)
,09-15 09:35:44.134  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 09:35:44.134  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 09:35:44.134  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 09:35:44.134  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:44.134  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@584a841 added. We now have 9 listener(s)
09-15 09:35:44.134  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 09:35:44.135  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 09:35:44.138  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 09:35:44.140  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 09:35:44.140  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:44.140  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:44.140  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:44.140  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:44.140  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:44.140  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:44.140  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 09:35:44.142  5322  5368 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 09:35:44.142  5322  5368 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 09:35:44.142  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 09:35:44.142  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9e3327 added. We now have 3 listener(s)
09-15 09:35:44.144  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:44.144  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 09:35:44.144  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 09:35:44.144  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 09:35:44.144  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:44.144  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11bd9d4 added. We now have 10 listener(s)
,09-15 09:35:44.144  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 09:35:44.144  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 09:35:44.144  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 09:35:44.145  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 09:35:44.145  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 09:35:44.145  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 09:35:44.145  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 09:35:44.148  5322  5368 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 09:35:44.148  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 09:35:44.152  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 09:35:44.152  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 09:35:44.153  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 09:35:44.155  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 09:35:44.155  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 09:35:44.155  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 09:35:44.156  5322  5368 D BluetoothAdapter: STATE_ON
09-15 09:35:44.159  5532  5542 D BtGatt.GattService: registerClient() - UUID=4c4d71ee-6bc7-4afe-a086-c5b732f7c92b
,09-15 09:35:44.160  5532  5548 D BtGatt.GattService: onClientRegistered() - UUID=4c4d71ee-6bc7-4afe-a086-c5b732f7c92b, clientIf=5
,09-15 09:35:44.161  5322  5332 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 09:35:44.162  5532  5568 D BtGatt.GattService: start scan with filters
,09-15 09:35:44.165  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 09:35:44.165  5532  5551 D BtGatt.ScanManager: handling starting scan
09-15 09:35:44.165  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 09:35:44.165  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 09:35:44.165  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 09:35:44.167  5532  5551 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9ce739b
,09-15 09:35:44.168  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 09:35:44.168  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 09:35:44.168  5322  5322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 09:35:44.169  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 09:35:44.172  5322  5368 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-15 09:35:44.172  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:44.172  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 09:35:44.172  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.172  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 09:35:44.172  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 09:35:44.172  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 09:35:44.172  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 09:35:44.172  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 09:35:44.172  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 09:35:44.172  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 09:35:44.173  5322  5368 D BluetoothAdapter: STATE_ON
09-15 09:35:44.174  5532  5548 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 09:35:44.174  5532  5542 D BtGatt.GattService: stopScan() - queue size =1
09-15 09:35:44.174  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 09:35:44.175  5532  5551 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 09:35:44.175  5532  5560 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 09:35:44.175  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 09:35:44.175  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 09:35:44.175  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-15 09:35:44.175  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 09:35:44.175  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-15 09:35:44.177  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 09:35:44.177  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-15 09:35:44.177  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 09:35:44.177  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 09:35:44.177  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 09:35:44.179  5322  5322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 09:35:44.179  5322  5322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 09:35:44.179  5322  5322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 09:35:44.181  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 09:35:44.181  5532  5548 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 09:35:44.181  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.181  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:44.181  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:44.181  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:44.181  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.181  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 09:35:44.181  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 09:35:44.181  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53ab328 removed from the list
09-15 09:35:44.181  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:44.181  5532  5551 D BtGatt.ScanManager: Starting BLE batch scan
09-15 09:35:44.181  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@584a841 removed from the list
09-15 09:35:44.181  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:44.181  5532  5551 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 09:35:44.181  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:44.182  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 09:35:44.182  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:44.183  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:44.183  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:44.183  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 09:35:44.183  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@584a841 not in the list
09-15 09:35:44.183  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.183  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:44.184  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:44.184  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:44.184  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:44.184  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11bd9d4 removed from the list
09-15 09:35:44.185  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:44.185  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.185  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 09:35:44.185  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 09:35:44.185  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9e3327 removed from the list
09-15 09:35:44.185  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 09:35:44.186  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d46bf40 added. We now have 2 listener(s)
09-15 09:35:44.187  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 09:35:44.187  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 09:35:44.187  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 09:35:44.187  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 09:35:44.187  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e51e79 added. We now have 9 listener(s)
09-15 09:35:44.187  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 09:35:44.188  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 09:35:44.191  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 09:35:44.192  5532  5548 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 09:35:44.192  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 09:35:44.198  5532  5548 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 09:35:44.198  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 09:35:44.199  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 09:35:44.199  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:44.199  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:44.199  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:44.199  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:44.199  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:44.199  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:44.199  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 09:35:44.201  5322  5368 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 09:35:44.201  5322  5368 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 09:35:44.202  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 09:35:44.202  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc601f added. We now have 3 listener(s)
09-15 09:35:44.203  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 09:35:44.203  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:44.203  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 09:35:44.203  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 09:35:44.203  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:44.203  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c788f6c added. We now have 10 listener(s)
09-15 09:35:44.203  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 09:35:44.203  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 09:35:44.204  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 09:35:44.204  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 09:35:44.204  5532  5548 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 09:35:44.204  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 09:35:44.204  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.204  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 09:35:44.204  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 09:35:44.204  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:44.204  5532  5551 D BtGatt.ScanManager: stopping BLe Batch
,09-15 09:35:44.207  5322  5368 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 09:35:44.207  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 09:35:44.209  5532  5548 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 09:35:44.209  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.209  5532  5551 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 09:35:44.210  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 09:35:44.211  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 09:35:44.211  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 09:35:44.214  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 09:35:44.214  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 09:35:44.214  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 09:35:44.214  5532  5548 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 09:35:44.214  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.214  5322  5368 D BluetoothAdapter: STATE_ON
09-15 09:35:44.216  5532  5568 D BtGatt.GattService: registerClient() - UUID=1fe0ec05-1005-41c6-9e80-02591b609947
09-15 09:35:44.216  5532  5548 D BtGatt.GattService: onClientRegistered() - UUID=1fe0ec05-1005-41c6-9e80-02591b609947, clientIf=5
,09-15 09:35:44.217  5322  5332 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 09:35:44.217  5532  5543 D BtGatt.GattService: start scan with filters
09-15 09:35:44.219  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 09:35:44.219  5532  5551 D BtGatt.ScanManager: handling starting scan
09-15 09:35:44.219  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 09:35:44.219  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 09:35:44.219  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 09:35:44.221  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 09:35:44.222  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 09:35:44.222  5322  5322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 09:35:44.223  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 09:35:44.224  5532  5548 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 09:35:44.224  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.224  5532  5551 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 09:35:44.225  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 09:35:44.226  5322  5368 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-15 09:35:44.226  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:44.226  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:44.226  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:44.226  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:44.226  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.226  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 09:35:44.226  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 09:35:44.226  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d46bf40 removed from the list
09-15 09:35:44.226  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:44.226  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e51e79 removed from the list
,09-15 09:35:44.226  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:44.226  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 09:35:44.227  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.227  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-15 09:35:44.227  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.227  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 09:35:44.228  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 09:35:44.228  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:44.229  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:44.229  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e51e79 not in the list
09-15 09:35:44.229  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 09:35:44.229  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 09:35:44.229  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 09:35:44.229  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 09:35:44.229  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 09:35:44.229  5532  5548 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 09:35:44.229  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.229  5532  5551 D BtGatt.ScanManager: Starting BLE batch scan
09-15 09:35:44.229  5532  5551 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 09:35:44.230  5322  5368 D BluetoothAdapter: STATE_ON
09-15 09:35:44.230  5532  5543 D BtGatt.GattService: stopScan() - queue size =1
,09-15 09:35:44.231  5532  5568 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 09:35:44.231  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-15 09:35:44.232  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 09:35:44.232  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 09:35:44.232  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 09:35:44.232  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-15 09:35:44.233  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 09:35:44.233  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 09:35:44.233  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 09:35:44.233  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 09:35:44.234  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:44.235  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:44.235  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:44.235  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:44.235  5322  5322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-15 09:35:44.235  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c788f6c removed from the list
09-15 09:35:44.235  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:44.235  5322  5322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 09:35:44.235  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.235  5322  5322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 09:35:44.235  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:44.235  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 09:35:44.235  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc601f removed from the list
09-15 09:35:44.236  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 09:35:44.236  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e153658 added. We now have 2 listener(s)
09-15 09:35:44.237  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 09:35:44.237  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 09:35:44.237  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 09:35:44.237  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:44.237  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a723b1 added. We now have 9 listener(s)
09-15 09:35:44.237  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 09:35:44.238  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 09:35:44.238  5532  5548 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 09:35:44.238  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 09:35:44.240  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 09:35:44.243  5532  5548 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 09:35:44.243  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.244  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 09:35:44.244  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:44.244  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:44.244  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:44.244  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:44.244  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:44.244  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:44.244  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 09:35:44.246  5322  5368 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 09:35:44.246  5322  5368 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 09:35:44.246  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 09:35:44.246  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e43417 added. We now have 3 listener(s)
09-15 09:35:44.247  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 09:35:44.247  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 09:35:44.247  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 09:35:44.247  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:44.247  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d36004 added. We now have 10 listener(s)
09-15 09:35:44.247  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 09:35:44.248  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 09:35:44.248  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 09:35:44.248  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-15 09:35:44.248  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 09:35:44.248  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 09:35:44.248  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:44.249  5532  5548 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 09:35:44.250  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.250  5532  5551 D BtGatt.ScanManager: stopping BLe Batch
09-15 09:35:44.250  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:44.251  5322  5368 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 09:35:44.251  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 09:35:44.254  5532  5548 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 09:35:44.255  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.255  5532  5551 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 09:35:44.255  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 09:35:44.256  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 09:35:44.256  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 09:35:44.259  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 09:35:44.259  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 09:35:44.259  5322  5368 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 09:35:44.259  5532  5548 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 09:35:44.259  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.259  5322  5368 D BluetoothAdapter: STATE_ON
09-15 09:35:44.261  5532  5560 D BtGatt.GattService: registerClient() - UUID=12c96e7c-2490-4f4e-b81f-81b3e5a26dba
09-15 09:35:44.261  5532  5548 D BtGatt.GattService: onClientRegistered() - UUID=12c96e7c-2490-4f4e-b81f-81b3e5a26dba, clientIf=5
09-15 09:35:44.261  5322  5333 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 09:35:44.262  5532  5568 D BtGatt.GattService: start scan with filters
09-15 09:35:44.264  5532  5551 D BtGatt.ScanManager: handling starting scan
09-15 09:35:44.264  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 09:35:44.264  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 09:35:44.264  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 09:35:44.264  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 09:35:44.266  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 09:35:44.266  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 09:35:44.266  5322  5322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 09:35:44.267  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 09:35:44.268  5532  5548 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 09:35:44.268  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.269  5532  5551 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 09:35:44.270  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:44.271  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:44.271  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:44.271  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:44.271  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.271  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-15 09:35:44.271  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 09:35:44.271  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e153658 removed from the list
09-15 09:35:44.271  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:44.271  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a723b1 removed from the list
09-15 09:35:44.271  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:44.271  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 09:35:44.271  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.271  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-15 09:35:44.271  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.272  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 09:35:44.273  5532  5548 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 09:35:44.273  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:44.273  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.273  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:44.273  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:44.273  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a723b1 not in the list
09-15 09:35:44.273  5532  5551 D BtGatt.ScanManager: Starting BLE batch scan
09-15 09:35:44.273  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 09:35:44.273  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 09:35:44.273  5532  5551 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 09:35:44.273  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-15 09:35:44.273  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 09:35:44.273  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-15 09:35:44.274  5322  5368 D BluetoothAdapter: STATE_ON
09-15 09:35:44.274  5532  5560 D BtGatt.GattService: stopScan() - queue size =1
09-15 09:35:44.275  5532  5568 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 09:35:44.275  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 09:35:44.275  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 09:35:44.275  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 09:35:44.275  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 09:35:44.275  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 09:35:44.276  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 09:35:44.276  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 09:35:44.276  5322  5368 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 09:35:44.276  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 09:35:44.276  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:44.277  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:44.277  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:44.277  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:44.277  5322  5322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-15 09:35:44.277  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d36004 removed from the list
09-15 09:35:44.277  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:44.277  5322  5322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 09:35:44.277  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.277  5322  5322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 09:35:44.277  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:44.278  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 09:35:44.278  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e43417 removed from the list
09-15 09:35:44.278  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 09:35:44.278  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a287870 added. We now have 2 listener(s)
09-15 09:35:44.280  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 09:35:44.280  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 09:35:44.280  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 09:35:44.280  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:44.280  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8d97e9 added. We now have 9 listener(s)
09-15 09:35:44.280  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 09:35:44.281  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 09:35:44.281  5532  5548 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 09:35:44.281  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.283  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 09:35:44.287  5532  5548 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-15 09:35:44.287  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 09:35:44.290  5322  5368 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 09:35:44.290  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 09:35:44.290  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 09:35:44.290  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 09:35:44.290  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 09:35:44.290  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 09:35:44.290  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 09:35:44.290  5322  5368 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 09:35:44.292  5322  5368 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 09:35:44.293  5322  5368 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 09:35:44.293  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 09:35:44.293  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc38f0f added. We now have 3 listener(s)
09-15 09:35:44.293  5532  5548 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-15 09:35:44.293  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.293  5532  5551 D BtGatt.ScanManager: stopping BLe Batch
09-15 09:35:44.294  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:44.294  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 09:35:44.294  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 09:35:44.294  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 09:35:44.294  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 09:35:44.294  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@974ab9c added. We now have 10 listener(s)
09-15 09:35:44.294  5322  5368 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 09:35:44.294  5322  5368 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 09:35:44.294  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:44.294  5322  5368 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 09:35:44.295  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:44.295  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.295  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 09:35:44.295  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 09:35:44.295  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a287870 removed from the list
09-15 09:35:44.295  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:44.295  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8d97e9 removed from the list
09-15 09:35:44.295  5322  5322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 09:35:44.296  5322  5368 D io.jxcore.node.ConnectivityMonitor: stop
09-15 09:35:44.296  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:44.296  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.296  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:44.297  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:44.297  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 09:35:44.297  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:44.297  5322  5368 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Discove,ryManager@e8d97e9 not in the list
09-15 09:35:44.297  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.297  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 09:35:44.298  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 09:35:44.298  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 09:35:44.298  5322  5368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 09:35:44.298  5322  5368 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@974ab9c removed from the list
09-15 09:35:44.298  5322  5368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 09:35:44.298  5322  5368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 09:35:44.298  5532  5548 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 09:35:44.298  5322  5368 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 09:35:44.298  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.298  5322  5368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 09:35:44.298  5322  5368 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc38f0f removed from the list
09-15 09:35:44.298  5532  5551 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 09:35:44.299  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-15 09:35:44.299  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 09:35:44.299  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-15 09:35:44.299  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 09:35:44.300  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 09:35:44.300  5322  5368 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 09:35:44.303  5532  5548 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 09:35:44.303  5532  5548 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 09:35:44.304  5322  5588 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: My test thread name)
,09-15 09:35:44.304  5322  5588 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: My test thread name)
09-15 09:35:44.304  5322  5588 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-15 09:35:44.306  5322  5589 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name)
,09-15 09:35:44.306  5322  5589 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: My test thread name)
09-15 09:35:44.306  5322  5589 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-15 09:35:44.307  5322  5368 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-15 09:35:44.307  5322  5368 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-15 09:35:44.308  5322  5368 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-15 09:35:44.308  5322  5368 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-15 09:35:44.308  5322  5368 D com.test.thalitest.ThaliTestRunner: Total duration: 22570 ms
09-15 09:35:44.309  5322  5368 I jxcore-log: Total number of executed tests:  80
09-15 09:35:44.309  5322  5368 I jxcore-log: 
09-15 09:35:44.309  5322  5368 I jxcore-log: Number of passed tests:  80
09-15 09:35:44.309  5322  5368 I jxcore-log: 
09-15 09:35:44.310  5322  5368 I jxcore-log: Number of failed tests:  0
09-15 09:35:44.310  5322  5368 I jxcore-log: 
09-15 09:35:44.310  5322  5368 I jxcore-log: Number of ignored tests:  0
09-15 09:35:44.310  5322  5368 I jxcore-log: 
09-15 09:35:44.310  5322  5368 I jxcore-log: Total duration:  22570
09-15 09:35:44.310  5322  5368 I jxcore-log: 
09-15 09:35:44.311  5322  5368 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-15 09:35:44.311  5322  5368 I jxcore-log: 
09-15 09:35:44.312  5322  5368 I jxcore-log: My device name is: Huawei-Nexus 6P
09-15 09:35:44.312  5322  5368 I jxcore-log: 
,09-15 09:35:44.314  5322  5368 I jxcore-log: WARN testUtils: myNameCallback not set!
09-15 09:35:44.314  5322  5368 I jxcore-log: 
09-15 09:35:44.316  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 09:35:44.316  5322  5368 I jxcore-log: 
09-15 09:35:44.317  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 09:35:44.317  5322  5368 I jxcore-log: 
09-15 09:35:44.318  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 09:35:44.318  5322  5368 I jxcore-log: 
09-15 09:35:44.320  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 09:35:44.320  5322  5368 I jxcore-log: 
09-15 09:35:44.323  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 09:35:44.323  5322  5368 I jxcore-log: 
09-15 09:35:44.324  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 09:35:44.324  5322  5368 I jxcore-log: 
09-15 09:35:44.325  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 09:35:44.325  5322  5368 I jxcore-log: 
09-15 09:35:44.326  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 09:35:44.326  5322  5368 I jxcore-log: 
09-15 09:35:44.327  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 09:35:44.327  5322  5368 I jxcore-log: 
09-15 09:35:44.327  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 09:35:44.327  5322  5368 I jxcore-log: 
09-15 09:35:44.329  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 09:35:44.329  5322  5368 I jxcore-log: 
09-15 09:35:44.330  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 09:35:44.330  5322  5368 I jxcore-log: 
09-15 09:35:44.330  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 09:35:44.330  5322  5368 I jxcore-log: 
,09-15 09:35:44.331  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 09:35:44.331  5322  5368 I jxcore-log: 
,09-15 09:35:44.332  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 09:35:44.332  5322  5368 I jxcore-log: 
,09-15 09:35:44.332  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 09:35:44.332  5322  5368 I jxcore-log: 
09-15 09:35:44.333  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 09:35:44.333  5322  5368 I jxcore-log: 
,09-15 09:35:44.334  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 09:35:44.334  5322  5368 I jxcore-log: 
09-15 09:35:44.334  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 09:35:44.334  5322  5368 I jxcore-log: 
,09-15 09:35:44.335  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 09:35:44.335  5322  5368 I jxcore-log: 
09-15 09:35:44.336  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 09:35:44.336  5322  5368 I jxcore-log: 
09-15 09:35:44.336  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 09:35:44.336  5322  5368 I jxcore-log: 
09-15 09:35:44.337  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 09:35:44.337  5322  5368 I jxcore-log: 
09-15 09:35:44.338  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 09:35:44.338  5322  5368 I jxcore-log: 
09-15 09:35:44.338  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 09:35:44.338  5322  5368 I jxcore-log: 
09-15 09:35:44.339  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 09:35:44.339  5322  5368 I jxcore-log: 
09-15 09:35:44.340  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 09:35:44.340  5322  5368 I jxcore-log: 
,09-15 09:35:44.340  5322  5368 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 09:35:44.340  5322  5368 I jxcore-log: 
,09-15 09:35:44.680  5322  5322 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 09:35:44.735  5322  5322 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 09:35:44.778  5322  5322 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 09:35:44.780  5590  5590 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-15 09:35:44.784  5590  5590 D AndroidRuntime: CheckJNI is OFF
,09-15 09:35:44.813  5590  5590 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-15 09:35:44.845  5590  5590 I Radio-JNI: register_android_hardware_Radio DONE
,09-15 09:35:44.863  5590  5590 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-15 09:35:44.872   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-15 09:35:44.873   928   941 I ActivityManager: Killing 5322:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-15 09:35:44.950   928  5292 I WindowState: WIN DEATH: Window{5448e96 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-15 09:35:44.950   928  2865 D WifiService: Client connection lost with reason: 4
09-15 09:35:44.950   928  3312 D GraphicsStats: Buffer count: 2
,09-15 09:35:45.008   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-15 09:35:45.008   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-15 09:35:45.009   928   951 I art     : Starting a blocking GC Explicit
,09-15 09:35:45.009   928   941 E ActivityManager: Failure starting process com.test.thalitest
09-15 09:35:45.009   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-15 09:35:45.009   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 09:35:45.009   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-15 09:35:45.009   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 09:35:45.009   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-15 09:35:45.010   928   941 I ActivityManager:   Force finishing activity ActivityRecord{4ec5cd3 u0 com.test.thalitest/.MainActivity t2}
,09-15 09:35:45.022   928  3438 W ActivityManager: Spurious death for ProcessRecord{1a69428 0:com.test.thalitest/u0a77}, curProc for 5322: null
,09-15 09:35:45.084   928   951 I art     : Explicit concurrent mark sweep GC freed 23918(1506KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.512ms total 75.343ms
,09-15 09:35:45.103   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-15 09:35:45.105  5590  5590 I art     : System.exit called, status: 0
,09-15 09:35:45.106  5590  5590 I AndroidRuntime: VM exiting with result code 0.
,09-15 09:35:45.121   928   951 I ActivityManager: Start proc 5600:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-15 09:35:45.121   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-15 09:35:45.125   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-15 09:35:45.134  3314  3314 I Keyboard.Facilitator: resetDictionaries() : en_US
09-15 09:35:45.134  5532  5532 D BluetoothMapAppObserver: onReceive
,09-15 09:35:45.134  5532  5532 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-15 09:35:45.134  3519  3861 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-15 09:35:45.138   928  2850 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-15 09:35:45.166  3314  5611 I Keyboard.Facilitator.DecoderInitializer: run()
09-15 09:35:45.164  3326  5613 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-15 09:35:45.183  3415  3415 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-15 09:35:45.188  3499  3499 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-15 09:35:45.188  3499  3499 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-15 09:35:45.193    27    27 W kworker/2:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 09:35:45.195  3314  5611 I Decoder : createOrResetDecoder
09-15 09:35:45.201  4565  4574 W art     : Suspending all threads took: 16.912ms
,09-15 09:35:45.196    27    27 W kworker/2:1: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 09:35:45.206   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-15 09:35:45.213    27    27 W kworker/2:1: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 09:35:45.208  3825  5619 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-15 09:35:45.214  3446  3595 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-15 09:35:45.223  3825  5619 D AccountUtils: Clearing selected account for com.test.thalitest
,09-15 09:35:45.227   928  3402 I ActivityManager: Start proc 5622:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-15 09:35:45.227  3446  3595 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-15 09:35:45.227  3446  3595 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3446
09-15 09:35:45.227  3446  3595 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 09:35:45.227  3446  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-15 09:35:45.227  3446  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-15 09:35:45.227  3446  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-15 09:35:45.227  3446  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-15 09:35:45.227  3446  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-15 09:35:45.227  3446  3595 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-15 09:35:45.227  3446  3595 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-15 09:35:45.227  3446  3595 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-15 09:35:45.227  3446  3595 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-15 09:35:45.227  3446  3595 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-15 09:35:45.227  3446  3595 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-15 09:35:45.231   928  5627 E DropBoxManagerService: Can't write: system_app_crash
09-15 09:35:45.231   928  5627 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
09-15 09:35:45.231   928  5627 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-15 09:35:45.231   928  5627 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-15 09:35:45.231   928  5627 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-15 09:35:45.231   928  5627 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-15 09:35:45.231   928  5627 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 09:35:45.231   928  5627 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 09:35:45.231   928  5627 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 09:35:45.231   928  5627 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-15 09:35:45.231   928  5627 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 09:35:45.231   928  5627 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 09:35:45.231   928  5627 E DropBoxManagerService: 	... 5 more
,09-15 09:35:45.233   928   938 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-15 09:35:45.238  3446  3595 I Process : Sending signal. PID: 3446 SIG: 9
,09-15 09:35:45.219  3326  3343 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-15 09:35:45.260  3326  3343 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-15 09:35:45.260  3326  3343 E AndroidRuntime: Process: android.process.acore, PID: 3326
09-15 09:35:45.260  3326  3343 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 09:35:45.260  3326  3343 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-15 09:35:45.260  3326  3343 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-15 09:35:45.260  3326  3343 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-15 09:35:45.260  3326  3343 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-15 09:35:45.260  3326  3343 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-15 09:35:45.260  3326  3343 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-15 09:35:45.260  3326  3343 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
09-15 09:35:45.260  3326  3343 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-15 09:35:45.260  3326  3343 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-15 09:35:45.260  3326  3343 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-15 09:35:45.260  3326  3343 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 09:35:45.260  3326  3343 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-15 09:35:45.260  3326  3343 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 09:35:45.263   928  5635 E DropBoxManagerService: Can't write: system_app_crash
09-15 09:35:45.263   928  5635 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
09-15 09:35:45.263   928  5635 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-15 09:35:45.263   928  5635 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-15 09:35:45.263   928  5635 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-15 09:35:45.263   928  5635 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-15 09:35:45.263   928  5635 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 09:35:45.263   928  5635 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 09:35:45.263   928  5635 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 09:35:45.263   928  5635 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-15 09:35:45.263   928  5635 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 09:35:45.263   928  5635 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 09:35:45.263   928  5635 E DropBoxManagerService: 	... 5 more
,09-15 09:35:45.291  3326  5613 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,09-15 09:35:45.291  3326  5613 I Process : Sending signal. PID: 3326 SIG: 9
,09-15 09:35:45.296  3499  3499 I ConfigService: onCreate
,09-15 09:35:45.296   928  3402 I WindowState: WIN DEATH: Window{a0b0f1e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-15 09:35:45.296   928  5292 D GraphicsStats: Buffer count: 1

```
