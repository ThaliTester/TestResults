#### Test 861743790af7a74_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-22 06:41:58.427   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 06:41:59.428   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
09-22 06:41:59.725  5344  5344 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-22 06:41:59.731  5344  5344 D AndroidRuntime: CheckJNI is OFF
09-22 06:41:59.757  5344  5344 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-22 06:41:59.788  5344  5344 I Radio-JNI: register_android_hardware_Radio DONE
09-22 06:41:59.803  5344  5344 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-22 06:41:59.813   929   939 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-22 06:41:59.856   929   939 I ActivityManager: Start proc 5353:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-22 06:41:59.861  5344  5344 D AndroidRuntime: Shutting down VM
,09-22 06:42:00.200   929   940 I WindowManager: Screenshot max retries 4 of Token{2f2d501 ActivityRecord{b869ae8 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{cafdf00 u0 Starting com.test.thalitest} drawState=2
,09-22 06:42:00.271  5353  5353 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-22 06:42:00.304  5353  5353 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-22 06:42:00.330  5353  5353 I LibraryLoader: Time to load native libraries: 22 ms (timestamps 45-67)
,09-22 06:42:00.330  5353  5353 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-22 06:42:00.350  5353  5353 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b930bf7}
,09-22 06:42:00.351  5353  5353 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-22 06:42:00.351  5353  5353 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-22 06:42:00.354  5353  5353 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-22 06:42:00.355  5353  5353 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-22 06:42:00.394  5353  5353 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-22 06:42:00.402  5353  5353 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-22 06:42:00.403  5353  5353 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-22 06:42:00.403  5353  5353 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-22 06:42:00.403  5353  5353 I Adreno  : Build Date                       : 12/06/15
09-22 06:42:00.403  5353  5353 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-22 06:42:00.403  5353  5353 I Adreno  : Local Branch                     : mybranch17112971
09-22 06:42:00.403  5353  5353 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-22 06:42:00.403  5353  5353 I Adreno  : Remote Branch                    : NONE
09-22 06:42:00.403  5353  5353 I Adreno  : Reconstruct Branch               : NOTHING
,09-22 06:42:00.445   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@60a8e18:true
,09-22 06:42:00.483   400   400 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22464]" dev="sockfs" ino=22464 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 06:42:00.483   400   400 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[22464]" dev="sockfs" ino=22464 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-22 06:42:00.495  5353  5353 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-22 06:42:00.502  5353  5353 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-22 06:42:00.527   400   400 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31189]" dev="sockfs" ino=31189 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 06:42:00.527   400   400 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31189]" dev="sockfs" ino=31189 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-22 06:42:00.530  5353  5390 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-22 06:42:00.530  3497  3497 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14227]" dev="sockfs" ino=14227 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-22 06:42:00.530  3497  3497 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14227]" dev="sockfs" ino=14227 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-22 06:42:00.536  5353  5377 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-22 06:42:00.571  5353  5390 I OpenGLRenderer: Initialized EGL, version 1.4
,09-22 06:42:00.645   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +443ms (total +817ms)
,09-22 06:42:00.675  5353  5353 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5353
,09-22 06:42:00.778  5353  5353 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-22 06:42:01.065  5353  5393 D jxcore_app_log: JniHelper::setJavaVM(0xf4e3c000), pthread_self() = -568063696
,09-22 06:42:01.077  5353  5393 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-22 06:42:01.077  5353  5393 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-22 06:42:01.077  5353  5393 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-22 06:42:01.077  5353  5393 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-22 06:42:01.077  5353  5393 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-22 06:42:01.077  5353  5393 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f81cabc added. We now have 1 listener(s)
,09-22 06:42:01.080  5353  5393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-22 06:42:01.081  5353  5393 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 06:42:01.081  5353  5393 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
,09-22 06:42:01.081  5353  5393 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-22 06:42:01.084  5353  5393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c768ecb added. We now have 1 listener(s)
09-22 06:42:01.084  5353  5393 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 06:42:01.092   929  2898 D WifiService: New client listening to asynchronous messages
,09-22 06:42:01.092  5353  5393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 06:42:01.092  5353  5393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-22 06:42:01.092  5353  5393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-22 06:42:01.092  5353  5393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-22 06:42:01.092  5353  5393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-22 06:42:01.095  5353  5393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 06:42:01.095  5353  5393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-22 06:42:01.101  5353  5393 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-22 06:42:01.102  5353  5393 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:42:01.102  5353  5393 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:01.102  5353  5393 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:01.102  5353  5393 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:01.102  5353  5393 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:01.102  5353  5393 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:42:01.102  5353  5393 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:42:01.102  5353  5393 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 06:42:01.102  5353  5393 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-22 06:42:01.102  5353  5393 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:42:01.102  5353  5393 I io.jxcore.node.LifeCycleMonitor: start: OK
09-22 06:42:01.106  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:01.112  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:01.131  5353  5353 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-22 06:42:01.531  5353  5399 W jxcore-log: Initializing JXcore engine
09-22 06:42:01.531  5353  5399 W jxcore-log: JXcore engine is ready
,09-22 06:42:01.553  5399  5399 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10644 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-22 06:42:01.553  5399  5399 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[11221]" dev="sockfs" ino=11221 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-22 06:42:01.553  5399  5399 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-22 06:42:01.553  5399  5399 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31847]" dev="sockfs" ino=31847 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-22 06:42:01.562  5353  5399 W jxcore-log: Starting JXcore engine
,09-22 06:42:01.580  5353  5362 I art     : Background sticky concurrent mark sweep GC freed 81612(8MB) AllocSpace objects, 19(2MB) LOS objects, 24% free, 24MB/32MB, paused 1.257ms total 102.105ms
,09-22 06:42:01.613  5353  5399 W jxcore-log: Platform android
09-22 06:42:01.613  5353  5399 W jxcore-log: 
,09-22 06:42:01.613  5353  5399 W jxcore-log: Process ARCH arm
09-22 06:42:01.613  5353  5399 W jxcore-log: 
,09-22 06:42:01.713  5353  5399 I jxcore-log: JXcore Cordova bridge is ready!
09-22 06:42:01.713  5353  5399 I jxcore-log: 
,09-22 06:42:01.713  5353  5399 W jxcore-log: JXcore engine is started
,09-22 06:42:01.719  5353  5393 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-22 06:42:01.722  5353  5353 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-22 06:42:08.387  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-22 06:42:08.387  5353  5399 I jxcore-log: 
,09-22 06:42:08.389  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-22 06:42:08.389  5353  5399 I jxcore-log: 
,09-22 06:42:08.392  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:42:08.392  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:08.392  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:08.392  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:08.392  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:08.392  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:42:08.392  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:42:08.392  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 06:42:08.394  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 06:42:08.395  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-22 06:42:08.395  5353  5399 I jxcore-log: 
,09-22 06:42:08.397  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-22 06:42:08.397  5353  5399 I jxcore-log: 
,09-22 06:42:08.755  5353  5399 D executeNativeTests: Running unit tests
,09-22 06:42:08.796  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 06:42:08.797  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 added. We now have 2 listener(s)
,09-22 06:42:08.797  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 06:42:08.797  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 06:42:08.797  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 06:42:08.798  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 06:42:08.798  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 added. We now have 2 listener(s)
09-22 06:42:08.798  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:08.798  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 06:42:08.800  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 06:42:08.804  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:42:08.804  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:08.804  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:08.804  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:08.804  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:08.804  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:42:08.804  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:42:08.804  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 06:42:08.804  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 06:42:08.805  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:42:08.806  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 06:42:08.806  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-22 06:42:08.806  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-22 06:42:08.807  5353  5399 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-22 06:42:08.807  5353  5399 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-22 06:42:08.807  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-22 06:42:08.807  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 06:42:08.807  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 06:42:08.807  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 06:42:08.807  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.807  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.807  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.807  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.807  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:42:08.807  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 06:42:08.808  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 removed from the list
09-22 06:42:08.808  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.808  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 removed from the list
09-22 06:42:08.813  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:08.818  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:08.819  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.819  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.819  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.819  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.820  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 06:42:08.820  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.820  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.820  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.821  5353  5399 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-22 06:42:08.821  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 06:42:08.821  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.821  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.821  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.821  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.821  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.821  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
,09-22 06:42:08.821  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.821  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.821  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.821  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.821  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 06:42:08.821  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.822  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.822  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.822  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.822  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 06:42:08.822  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.824  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-22 06:42:08.824  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-22 06:42:08.824  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-22 06:42:08.824  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-22 06:42:08.824  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-22 06:42:08.824  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-22 06:42:08.824  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-22 06:42:08.825  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-22 06:42:08.825  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.825  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.825  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.825  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.825  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.825  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.825  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.825  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.826  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.826  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.826  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.826  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.826  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.826  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.826  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.826  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.826  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.826  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.827  5353  5399 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 06:42:08.828  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:42:08.830  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:42:08.830  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:08.830  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:08.830  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:08.830  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:08.830  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:42:08.830  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:42:08.830  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 06:42:08.831  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 06:42:08.831  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:42:08.831  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 06:42:08.831  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 06:42:08.831  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 06:42:08.831  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:42:08.831  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 06:42:08.833  5353  5399 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 06:42:08.833  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 06:42:08.836  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:08.836  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 06:42:08.837  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:08.837  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 06:42:08.838  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 06:42:08.839  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-22 06:42:08.840  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-22 06:42:08.840  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 06:42:08.841  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 06:42:08.841  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 06:42:08.841  5353  5399 D BluetoothAdapter: STATE_ON
09-22 06:42:08.843  4323  4337 D BtGatt.GattService: registerClient() - UUID=9e818811-8724-4334-a7cf-070a57a6f9c8
09-22 06:42:08.844  4323  4410 D BtGatt.GattService: onClientRegistered() - UUID=9e818811-8724-4334-a7cf-070a57a6f9c8, clientIf=5
09-22 06:42:08.845  5353  5363 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 06:42:08.846  4323  4566 D BtGatt.GattService: start scan with filters
09-22 06:42:08.851  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 06:42:08.851  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 06:42:08.851  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 06:42:08.851  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 06:42:08.851  4323  4413 D BtGatt.ScanManager: handling starting scan
09-22 06:42:08.852  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:42:08.852  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 06:42:08.852  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:42:08.853  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 06:42:08.854  5353  5399 I io.jxcore.node.ConnectionHelper: start: OK
09-22 06:42:08.854  4323  4413 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
09-22 06:42:08.855  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.855  5353  5399 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 06:42:08.855  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.855  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 06:42:08.855  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.855  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 06:42:08.855  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 06:42:08.855  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 06:42:08.855  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 06:42:08.855  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 06:42:08.856  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 06:42:08.856  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 06:42:08.856  5353  5399 D BluetoothAdapter: STATE_ON
09-22 06:42:08.857  4323  4337 D BtGatt.GattService: stopScan() - queue size =1
09-22 06:42:08.858  4323  4566 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 06:42:08.858  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 06:42:08.858  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 06:42:08.858  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 06:42:08.858  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 06:42:08.858  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 06:42:08.860  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 06:42:08.860  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 06:42:08.860  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 06:42:08.860  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 06:42:08.861  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:42:08.862  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.862  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.862  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:42:08.862  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:42:08.862  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.862  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.862  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.862  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:42:08.862  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.862  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.862  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 06:42:08.862  5353  5399 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 06:42:08.862  4323  4410 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 06:42:08.862  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.863  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:42:08.863  4323  4413 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 06:42:08.865  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:42:08.865  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:08.865  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:08.865  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:08.865  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:08.865  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:42:08.865  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:42:08.865  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 06:42:08.866  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 06:42:08.866  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:42:08.866  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 06:42:08.866  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 06:42:08.867  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 06:42:08.867  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:42:08.867  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 06:42:08.869  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:08.869  5353  5399 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 06:42:08.869  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 06:42:08.870  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:08.872  4323  4410 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 06:42:08.872  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.872  4323  4413 D BtGatt.ScanManager: Starting BLE batch scan
09-22 06:42:08.872  4323  4413 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 06:42:08.873  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 06:42:08.874  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 06:42:08.874  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 06:42:08.880  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 06:42:08.880  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 06:42:08.880  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 06:42:08.881  5353  5399 D BluetoothAdapter: STATE_ON
09-22 06:42:08.882  4323  4410 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 06:42:08.882  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.884  4323  4337 D BtGatt.GattService: registerClient() - UUID=29d5d95f-12dd-4988-bb8f-24f821d288eb
09-22 06:42:08.885  4323  4410 D BtGatt.GattService: onClientRegistered() - UUID=29d5d95f-12dd-4988-bb8f-24f821d288eb, clientIf=5
09-22 06:42:08.885  5353  5364 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 06:42:08.886  4323  4566 D BtGatt.GattService: start scan with filters
09-22 06:42:08.887  4323  4410 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 06:42:08.887  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.888  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 06:42:08.889  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 06:42:08.889  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 06:42:08.889  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 06:42:08.890  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:42:08.890  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 06:42:08.890  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:42:08.890  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 06:42:08.891  5353  5399 I io.jxcore.node.ConnectionHelper: start: OK
09-22 06:42:08.892  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.892  5353  5399 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 06:42:08.893  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.893  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 06:42:08.893  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.893  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 06:42:08.893  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 06:42:08.893  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 06:42:08.893  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 06:42:08.893  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 06:42:08.893  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 06:42:08.893  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 06:42:08.893  5353  5399 D BluetoothAdapter: STATE_ON
09-22 06:42:08.893  4323  4336 D BtGatt.GattService: stopScan() - queue size =0
09-22 06:42:08.893  4323  4410 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 06:42:08.893  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.894  4323  4337 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 06:42:08.894  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 06:42:08.894  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 06:42:08.894  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 06:42:08.894  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 06:42:08.894  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 06:42:08.894  4323  4413 D BtGatt.ScanManager: stopping BLe Batch
09-22 06:42:08.894  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 06:42:08.894  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 06:42:08.894  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 06:42:08.894  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 06:42:08.895  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:42:08.895  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.895  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.895  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:42:08.895  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:42:08.895  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.895  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.895  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:42:08.895  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.895  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.895  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 06:42:08.895  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.895  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.895  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.896  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.896  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.896  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.896  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.896  5353  5399 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 06:42:08.897  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:42:08.900  4323  4410 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 06:42:08.900  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.900  4323  4413 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 06:42:08.900  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:42:08.900  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:08.900  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:08.900  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:08.900  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:08.900  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:42:08.900  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:42:08.900  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 06:42:08.905  4323  4410 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-22 06:42:08.905  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 06:42:08.905  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.905  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:42:08.905  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 06:42:08.905  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 06:42:08.905  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 06:42:08.905  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:42:08.905  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 06:42:08.907  4323  4413 D BtGatt.ScanManager: handling starting scan
09-22 06:42:08.907  5353  5399 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 06:42:08.907  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 06:42:08.908  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:08.909  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 06:42:08.910  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 06:42:08.910  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 06:42:08.911  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:08.912  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 06:42:08.912  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-22 06:42:08.912  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 06:42:08.912  5353  5399 D BluetoothAdapter: STATE_ON
09-22 06:42:08.913  4323  4336 D BtGatt.GattService: registerClient() - UUID=9787f21d-6b16-425f-8e5b-558a75b6979c
09-22 06:42:08.914  4323  4410 D BtGatt.GattService: onClientRegistered() - UUID=9787f21d-6b16-425f-8e5b-558a75b6979c, clientIf=5
,09-22 06:42:08.914  5353  5363 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 06:42:08.914  4323  4337 D BtGatt.GattService: start scan with filters
09-22 06:42:08.915  4323  4410 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 06:42:08.915  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.915  4323  4413 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-22 06:42:08.917  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 06:42:08.917  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 06:42:08.917  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 06:42:08.917  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 06:42:08.918  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:42:08.918  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 06:42:08.918  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 06:42:08.918  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-22 06:42:08.920  5353  5399 I io.jxcore.node.ConnectionHelper: start: OK
09-22 06:42:08.920  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.920  5353  5399 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 06:42:08.920  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.920  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 06:42:08.920  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.920  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 06:42:08.920  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 06:42:08.920  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 06:42:08.920  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 06:42:08.920  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 06:42:08.920  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 06:42:08.920  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 06:42:08.920  4323  4410 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 06:42:08.920  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.920  5353  5399 D BluetoothAdapter: STATE_ON
09-22 06:42:08.920  4323  4413 D BtGatt.ScanManager: Starting BLE batch scan
09-22 06:42:08.920  4323  4413 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 06:42:08.920  4323  4542 D BtGatt.GattService: stopScan() - queue size =1
09-22 06:42:08.921  4323  4337 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 06:42:08.921  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 06:42:08.921  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 06:42:08.921  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 06:42:08.921  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 06:42:08.921  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 06:42:08.921  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 06:42:08.922  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 06:42:08.922  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 06:42:08.922  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 06:42:08.922  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 06:42:08.922  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:42:08.922  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.922  5353  5399 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 06:42:08.922  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.922  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:42:08.923  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.923  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 06:42:08.923  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.923  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.923  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:42:08.923  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.923  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.923  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
,09-22 06:42:08.923  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.923  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.923  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.923  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.923  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.923  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.924  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.924  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.924  5353  5399 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-22 06:42:08.924  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.924  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.924  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.924  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.924  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.924  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.924  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.924  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.924  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.924  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.924  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 06:42:08.924  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.924  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.924  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.925  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.925  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.925  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.925  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.925  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-22 06:42:08.925  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.925  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.926  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.926  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.926  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.926  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.926  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.926  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 06:42:08.926  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.926  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.926  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.926  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.926  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.926  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.927  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.927  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.927  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.927  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.927  5353  5399 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-22 06:42:08.927  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.927  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-22 06:42:08.927  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.927  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.927  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.927  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.927  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.927  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.927  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.927  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.927  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.927  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.927  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.927  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.928  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 06:42:08.928  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.928  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.928  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.928  5353  5399 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-22 06:42:08.928  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.928  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.928  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.928  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.928  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.929  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 06:42:08.929  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.929  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.929  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.929  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.929  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.929  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.929  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.929  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.929  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.929  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.929  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.930  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.930  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 06:42:08.930  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 06:42:08.930  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 06:42:08.930  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-22 06:42:08.930  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 06:42:08.930  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 06:42:08.930  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.930  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.930  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.930  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.930  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.930  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.930  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.930  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.930  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
,09-22 06:42:08.930  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.930  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.930  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.931  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.931  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.931  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.931  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.931  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.931  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.931  5353  5399 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 06:42:08.931  5353  5399 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-22 06:42:08.932  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-22 06:42:08.933  5353  5399 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 06:42:08.933  5353  5399 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-22 06:42:08.933  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-22 06:42:08.934  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-22 06:42:08.934  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-22 06:42:08.934  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-22 06:42:08.934  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-22 06:42:08.934  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-22 06:42:08.934  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-22 06:42:08.934  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-22 06:42:08.934  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-22 06:42:08.934  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-22 06:42:08.934  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-22 06:42:08.934  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-22 06:42:08.934  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-22 06:42:08.934  5353  5399 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-22 06:42:08.934  5353  5399 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 06:42:08.934  5353  5399 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-22 06:42:08.934  5353  5399 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 06:42:08.934  5353  5399 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 06:42:08.934  5353  5399 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,09-22 06:42:08.934  4323  4410 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 06:42:08.934  5353  5399 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 06:42:08.934  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.934  5353  5399 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 06:42:08.934  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-22 06:42:08.938  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-22 06:42:08.939  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-22 06:42:08.939  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-22 06:42:08.940  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-22 06:42:08.940  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-22 06:42:08.940  5353  5399 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-22 06:42:08.940  5353  5399 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 06:42:08.940  5353  5399 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-22 06:42:08.940  4323  4410 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 06:42:08.940  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.940  5353  5400 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-22 06:42:08.940  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.940  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.940  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.940  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.941  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.941  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.941  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-22 06:42:08.941  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.941  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.941  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.941  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.941  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.941  5353  5399 D org.thali,project.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.941  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.941  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.942  5353  5400 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 06:42:08.942  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.942  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.942  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.940  4336  4336 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[27619]" dev="sockfs" ino=27619 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 06:42:08.942  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.942  5353  5399 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-22 06:42:08.942  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.942  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.943  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.943  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.943  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.943  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.943  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.943  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.943  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
,09-22 06:42:08.943  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.943  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.943  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.943  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.943  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.943  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.943  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.943  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.944  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.944  5353  5399 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-22 06:42:08.944  5353  5401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-22 06:42:08.944  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 06:42:08.944  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-22 06:42:08.944  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.944  5353  5401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-22 06:42:08.944  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.944  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.944  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.944  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.944  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 06:42:08.944  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.944  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.944  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.944  4323  4537 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
09-22 06:42:08.944  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.944  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.944  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.945  5353  5400 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-22 06:42:08.945  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.945  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.945  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.945  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.946  5353  5399 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-22 06:42:08.946  5353  5399 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-22 06:42:08.946  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 06:42:08.946  5353  5399 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-22 06:42:08.946  5353  5399 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-22 06:42:08.946  5353  5399 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-22 06:42:08.940  4336  4336 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[27619]" dev="sockfs" ino=27619 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 06:42:08.946  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 06:42:08.946  5353  5399 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-22 06:42:08.946  5353  5401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-22 06:42:08.946  5353  5399 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-22 06:42:08.946  5353  5399 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-22 06:42:08.946  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 06:42:08.946  5353  5399 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-22 06:42:08.946  5353  5399 I io.jxcor,e.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.946  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.946  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.946  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.946  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.946  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.946  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.946  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.946  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.946  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.947  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.947  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.947  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.947  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.947  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.947  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.947  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.947  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.947  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.947  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.947  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.947  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.947  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.947  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.948  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.948  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.948  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.948  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.948  5353  5399 E org.thaliproject.p2p.b,tconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.948  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.948  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.948  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.948  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.948  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.948  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.948  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.948  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.948  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.948  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.948  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.948  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.948  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.948  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.948  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.948  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.948  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.948  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.948  4323  4410 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 06:42:08.949  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.949  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.949  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.949  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.949  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.949  5353  5399 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-22 06:42:08.949  4323  4413 D BtGatt.ScanManager: stopping BLe Batch
09-22 06:42:08.949  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:42:08.950  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-22 06:42:08.950  5353  5399 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-22 06:42:08.950  5353  5399 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-22 06:42:08.950  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-22 06:42:08.950  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 06:42:08.951  5353  5353 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-22 06:42:08.951  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.951  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-22 06:42:08.951  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-22 06:42:08.951  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-22 06:42:08.951  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.951  5353  5399 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-22 06:42:08.951  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.951  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.951  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 06:42:08.952  5353  5402 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 06:42:08.951  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 06:42:08.952  5353  5353 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-22 06:42:08.953  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 06:42:08.954  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.954  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.950  4566  4566 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[27622]" dev="sockfs" ino=27622 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 06:42:08.954  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 06:42:08.954  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.954  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.954  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.954  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.954  5353  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-22 06:42:08.954  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.955  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.955  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.955  5353  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-22 06:42:08.955  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.955  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.955  5353  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-22 06:42:08.955  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.955  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.955  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.955  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.955  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.955  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.956  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.956  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.956  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.957  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.957  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:42:08.957  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:42:08.957  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 06:42:08.957  5353  5353 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-22 06:42:08.957  5353  5399 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-22 06:42:08.957  5353  5399 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-22 06:42:08.957  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 06:42:08.957  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 06:42:08.957  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.957  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.957  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.958  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.958  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.950  4566  4566 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[27622]" dev="sockfs" ino=27622 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 06:42:08.958  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.958  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.958  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.958  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.958  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.958  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.958  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.958  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.958  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.958  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.959  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.959  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.959  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.961  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.961  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.961  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.961  4323  4410 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 06:42:08.961  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.961  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.961  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.961  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.961  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.961  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.961  4323  4413 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 06:42:08.961  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.961  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.961  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.962  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.962  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.962  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.963  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.963  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.963  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.963  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.963  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:08.963  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:08.963  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:08.963  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:08.963  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.963  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.963  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2b378 not in the list
09-22 06:42:08.963  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.963  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.963  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:08.963  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.963  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.964  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:08.964  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:08.964  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:08.964  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:08.964  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:08.964  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5652a51 not in the list
09-22 06:42:08.965  5353  5399 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-22 06:42:08.965  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 06:42:08.965  5353  5399 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-22 06:42:08.965  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 06:42:08.965  5353  5399 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-22 06:42:08.965  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 06:42:08.965  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-22 06:42:08.965  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-22 06:42:08.966  5353  5399 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-22 06:42:08.966  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-22 06:42:08.966  5353  5399 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-22 06:42:08.966  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-22 06:42:08.966  5353  5399 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-22 06:42:08.966  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-22 06:42:08.966  5353  5399 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-22 06:42:08.966  5353  5399 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-22 06:42:08.966  5353  5399 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-22 06:42:08.966  5353  5399 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-22 06:42:08.967  5353  5399 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-22 06:42:08.967  5353  5399 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-22 06:42:08.967  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:42:08.967  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19d72cb added. We now have 2 listener(s)
09-22 06:42:08.967  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:08.967  4323  4410 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 06:42:08.967  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.968  4323  4413 D BtGatt.ScanManager: handling starting scan
09-22 06:42:08.970  5353  5399 D BluetoothAdapter: enable(): BT is already enabled..!
09-22 06:42:08.970   929  3909 D WifiService: setWifiEnabled: true pid=5353, uid=10077
09-22 06:42:08.970   929  3909 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-22 06:42:08.970  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:42:08.970  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d05eaa8 added. We now have 3 listener(s)
09-22 06:42:08.970  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:08.972  4323  4410 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 06:42:08.973  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.973  4323  4413 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 06:42:08.975  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:42:08.975  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef449c1 added. We now have 4 listener(s)
09-22 06:42:08.975  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:08.976  4323  4410 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 06:42:08.976  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.976  4323  4413 D BtGatt.ScanManager: Starting BLE batch scan
09-22 06:42:08.976  4323  4413 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 06:42:08.977  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:42:08.977  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c26566 added. We now have 5 listener(s)
09-22 06:42:08.977  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:08.979   929  3347 D WifiService: setWifiEnabled: false pid=5353, uid=10077
09-22 06:42:08.979   929  3347 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-22 06:42:08.980   929  2897 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-22 06:42:08.980   929  2897 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-22 06:42:08.981   929  2897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-22 06:42:08.981   929  2897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-22 06:42:08.983  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:42:08.984  4323  4406 D BluetoothAdapterState: Current state: ON, message: 23
09-22 06:42:08.984  4323  4406 D BluetoothAdapterProperties: Setting state to 13
09-22 06:42:08.984  4323  4406 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-22 06:42:08.985  4323  4410 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 06:42:08.985  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:08.985  4323  4406 D BluetoothAdapterProperties: onBluetoothDisable()
09-22 06:42:08.985  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:08.985  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:42:08.985  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:08.985  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:08.985  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:08.985  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 06:42:08.985  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:42:08.985  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:42:08.985  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 06:42:08.985  4323  4406 I BluetoothAdapterState: Entering PendingCommandState
09-22 06:42:08.986  4323  4323 D BluetoothMapService: onReceive
09-22 06:42:08.986  4323  4323 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 06:42:08.986  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:08.986  4323  4323 D BluetoothMapService: STATE_TURNING_OFF
09-22 06:42:08.986  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 06:42:08.986  4323  4323 D BluetoothMapService: MAP Service closeService in
09-22 06:42:08.986  4323  4323 D BluetoothMapMasInstance0: MAP Service shutdown
09-22 06:42:08.986  4323  4323 D ObexServerSockets0: shutdown(block = true)
09-22 06:42:08.986  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:42:08.987  4323  4323 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 06:42:08.987  4323  4323 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 06:42:08.987  4323  4573 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-22 06:42:08.987  4323  4572 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-22 06:42:08.988  4323  4537 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-22 06:42:08.990   929  5110 D DhcpClient: Clearing IP address
09-22 06:42:08.990   507   923 D CommandListener: Clearing all IP addresses on wlan0
09-22 06:42:08.990  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:08.994  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:08.991  4323  4323 I BtOppRfcommListener: stopping Accept Thread
09-22 06:42:08.996  4323  5004 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-22 06:42:08.996  4323  5004 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-22 06:42:08.996   507   923 D CommandListener: Setting iface cfg
09-22 06:42:08.997  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:08.997  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:08.997  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:08.997  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:08.997  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:08.997  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 06:42:08.997  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:42:08.997  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:42:08.997  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 06:42:08.998   929  5111 D DhcpClient: Receive thread stopped
09-22 06:42:08.998  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:08.998  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 06:42:09.001  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:09.002  3553  5164 V NativeCrypto: Read error: ssl=0x7f9d9e6000: I/O error during system call, Connection timed out
09-22 06:42:09.004  3553  5164 V NativeCrypto: SSL shutdown failed: ssl=0x7f9d9e6000: I/O error during system call, Broken pipe
09-22 06:42:09.010   929   940 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-22 06:42:09.010   929  5108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-22 06:42:09.012   929  5108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-22 06:42:09.012   929   942 I ActivityManager: Start proc 5405:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-22 06:42:09.012   929  2899 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-22 06:42:09.013  4323  4410 D BluetoothAdapterProperties: Scan Mode:20
09-22 06:42:09.013   929  2899 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-22 06:42:09.013  4323  4406 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-22 06:42:09.013   929  2899 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-22 06:42:09.014   929  2899 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-22 06:42:09.014   929  2899 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-22 06:42:09.016  4323  4323 D HeadsetService: Received stop request...Stopping profile...
09-22 06:42:09.018   929   929 D RttService: SCAN_AVAILABLE : 1
09-22 06:42:09.018   533   533 E Parcel  : Reading a NULL string not supported here.
09-22 06:42:09.018   929  3004 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-22 06:42:09.018   929  2899 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-22 06:42:09.019  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:09.020  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:09.020  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:09.020  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:09.020  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:09.020  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 06:42:09.020  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:09.020  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:42:09.020  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 06:42:09.020  3441  3603 W QCNEJ   : |CORE| network lost: 100
,09-22 06:42:09.021  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:09.021  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 06:42:09.021  4323  4410 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 06:42:09.021  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:09.021   929   929 D BluetoothHeadset: Proxy object disconnected
09-22 06:42:09.021   929   929 D BluetoothHeadset: Proxy object disconnected
09-22 06:42:09.021  3441  3603 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-22 06:42:09.022  3476  3686 D BluetoothHeadset: Proxy object disconnected
09-22 06:42:09.022  3052  3065 D BluetoothHeadset: Proxy object disconnected
09-22 06:42:09.023  4323  4323 D A2dpService: Received stop request...Stopping profile...
09-22 06:42:09.023  4323  4554 D A2dpStateMachine: Exit Disconnected: -1
09-22 06:42:09.023  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:09.023  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:09.023  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:09.023  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:09.023  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:09.023  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 06:42:09.023  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:09.023  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:09.023  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 06:42:09.025  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:09.025  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 06:42:09.028  4323  4323 D HidService: Received stop request...Stopping profile...
09-22 06:42:09.028  4323  4323 D HidService: Stopping Bluetooth HidService
09-22 06:42:09.029   929   929 D BluetoothHeadset: Proxy object disconnected
09-22 06:42:09.029   929   929 D BluetoothA2dp: Proxy object disconnected
09-22 06:42:09.030  4323  4323 V BluetoothAdapterState: isTurningOff()=true
09-22 06:42:09.030  4323  4323 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:09.030  4323  4323 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:09.030  4323  4323 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:09.033  3052  3052 D HeadsetProfile: Bluetooth service disconnected
09-22 06:42:09.034  3052  3052 D BluetoothA2dp: Proxy object disconnected
09-22 06:42:09.034  3052  3052 D BluetoothInputDevice: Proxy object disconnected
09-22 06:42:09.034  3052  3052 D HidProfile: Bluetooth service disconnected
09-22 06:42:09.035  4323  4323 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-22 06:42:09.035  4323  4323 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-22 06:42:09.036  4323  4323 D HealthService: Received stop request...Stopping profile...
09-22 06:42:09.037  4323  4323 D PanService: Received stop request...Stopping profile...
09-22 06:42:09.038  4323  4410 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-22 06:42:09.038  4323  4523 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 06:42:09.038  4323  4523 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 06:42:09.038  4323  4523 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 06:42:09.039  4323  4410 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-22 06:42:09.041  4323  4323 V BluetoothAdapterState: isTurningOff()=true
09-22 06:42:09.041  4323  4323 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:09.041  4323  4323 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:09.041  4323  4323 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 06:42:09.042   929  2897 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-22 06:42:09.043  4323  4323 D BluetoothMapService: Received stop request...Stopping profile...
,09-22 06:42:09.043  4323  4323 D BluetoothMapService: stop()
09-22 06:42:09.044  4323  4323 D BluetoothMapAppObserver: deinitObservers()
09-22 06:42:09.044  4323  4323 D BluetoothMapAppObserver: removeReceiver()
09-22 06:42:09.044  4323  4410 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-22 06:42:09.044  4323  4523 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 06:42:09.044  4323  4523 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 06:42:09.044  4323  4523 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 06:42:09.044  4323  4523 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 06:42:09.044  4323  4523 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 06:42:09.044  4323  4523 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 06:42:09.044   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-22 06:42:09.045  4323  4323 V BluetoothAdapterState: isTurningOff()=true
09-22 06:42:09.045  4323  4323 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:09.045  4323  4323 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:09.045  4323  4323 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:09.046  4323  4323 D SapService: Received stop request...Stopping profile...
09-22 06:42:09.046  4323  4323 V SapService: stop()
09-22 06:42:09.047  4323  4323 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-22 06:42:09.047  4323  4323 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-22 06:42:09.047  4323  4410 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 06:42:09.047  4323  4323 V BluetoothAdapterState: isTurningOff()=true
09-22 06:42:09.047  4323  4323 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:09.047  4323  4323 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:09.047  4323  4323 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:09.047  4323  4323 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-22 06:42:09.047  4323  4410 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-22 06:42:09.048  4323  4323 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-22 06:42:09.048  4323  4323 V BluetoothAdapterState: isTurningOff()=true
09-22 06:42:09.048  4323  4323 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:09.048  4323  4323 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:09.048  4323  4323 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:09.048  4323  4323 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-22 06:42:09.048  4323  4323 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-22 06:42:09.048  4323  4410 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 06:42:09.049  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:09.049  4323  4413 D BtGatt.ScanManager: stopping BLe Batch
09-22 06:42:09.049  4323  4323 D BluetoothMapService: MAP Service closeService in
09-22 06:42:09.049  4323  4323 V BluetoothAdapterState: isTurningOff()=true
09-22 06:42:09.049  4323  4323 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:09.049  4323  4323 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:09.049  4323  4323 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:09.051  3052  3052 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 06:42:09.051  3052  3052 D PanProfile: Bluetooth service disconnected
09-22 06:42:09.051  3052  3052 D BluetoothMap: Proxy object disconnected
09-22 06:42:09.051  3052  3052 D MapProfile: Bluetooth service disconnected
09-22 06:42:09.053  4323  4323 D BluetoothMapService: cleanup()
09-22 06:42:09.053  4323  4323 D BluetoothMapService: MAP Service closeService in
09-22 06:42:09.053  4323  4323 V BluetoothAdapterState: isTurningOff()=true
09-22 06:42:09.053  4323  4323 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:09.053  4323  4323 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:09.053  4323  4323 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:09.054  4323  4406 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-22 06:42:09.054  4323  4406 D BluetoothAdapterProperties: Setting state to 15
09-22 06:42:09.054  4323  4406 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-22 06:42:09.055  3476  3507 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 06:42:09.055   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 06:42:09.055   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 06:42:09.055   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 06:42:09.055  3052  3065 D BluetoothPbap: onBluetoothStateChange: up=false
09-22 06:42:09.056  4323  4406 I BluetoothAdapterState: Entering BleOnState
09-22 06:42:09.056   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 06:42:09.056  3052  3278 D BluetoothPan: onBluetoothStateChange on: false
09-22 06:42:09.057  3052  3063 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 06:42:09.058  3052  3065 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-22 06:42:09.058  3052  3278 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 06:42:09.059  3052  3063 D BluetoothMap: onBluetoothStateChange: up=false
09-22 06:42:09.059  4323  4406 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-22 06:42:09.059  4323  4406 D BluetoothAdapterProperties: Setting state to 16
09-22 06:42:09.059  4323  4406 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-22 06:42:09.060  4323  4406 D BluetoothAdapterProperties: onBleDisable
09-22 06:42:09.060  4323  4406 I BluetoothAdapterState: Entering PendingCommandState
09-22 06:42:09.060  4323  4407 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-22 06:42:09.060  4323  4410 D BluetoothAdapterProperties: Scan Mode:20
09-22 06:42:09.061   929  2897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-22 06:42:09.062  4323  4523 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-22 06:42:09.063  4323  4523 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-22 06:42:09.063  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:09.063  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:09.063  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:09.063  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:09.063  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:09.063  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 06:42:09.063  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:09.063  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:09.063  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 06:42:09.063  5405  5405 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-22 06:42:09.065  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:09.068  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:09.070  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:09.075   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-22 06:42:09.075   507   923 D CommandListener: Clearing all IP addresses on wlan0
09-22 06:42:09.076   507   923 D TetherController: Setting IP forward enable = 0
09-22 06:42:09.077   929  2899 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-22 06:42:09.077   929  2899 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-22 06:42:09.078   929   946 D Tethering: MasterInitialState.processMessage what=3
09-22 06:42:09.082  4323  4410 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-22 06:42:09.082  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:09.082  4323  4413 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 06:42:09.084  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:09.086   929  2897 D DhcpClient: doQuit
09-22 06:42:09.087   929  5110 D DhcpClient: onQuitting
,09-22 06:42:09.086   929  2897 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-22 06:42:09.087  4323  4410 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 06:42:09.087  4170  4170 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@398c0a4 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-22 06:42:09.087  4323  4410 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:09.088  3596  3596 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-22 06:42:09.090  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:09.090  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:09.090  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:09.090  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:09.090  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 06:42:09.090  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 06:42:09.090  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:09.090  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:09.090  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 06:42:09.090  4714  4732 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-22 06:42:09.090  4714  4732 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,09-22 06:42:09.090  4714  4732 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-22 06:42:09.091  4714  4732 E SarControlService: no key has been found,reset the power
09-22 06:42:09.091  4714  4753 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-22 06:42:09.091  4714  4753 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-22 06:42:09.091  4714  4753 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-22 06:42:09.091  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:09.091  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 06:42:09.091  4741  4741 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 06:42:09.091  4741  4741 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-22 06:42:09.093  4714  4753 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-22 06:42:09.093  4714  4753 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-22 06:42:09.093  4714  4753 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-22 06:42:09.093  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:09.093  4741  4741 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 06:42:09.093  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:09.093  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:09.093  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:09.093  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 06:42:09.093  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 06:42:09.093  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:09.093  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:09.093  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 06:42:09.093  4741  4741 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-22 06:42:09.094  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:09.094  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 06:42:09.095  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:09.097  4741  4756 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@16748aa HexData = [00000000ea03000000000000ffffffff]
09-22 06:42:09.097  4741  4756 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 06:42:09.097  4741  4756 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-22 06:42:09.097  4741  4741 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-22 06:42:09.097  4714  4724 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-22 06:42:09.103  5405  5405 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 06:42:09.105  4741  4756 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@16748aa HexData = [00000000eb03000000000000ffffffff]
,09-22 06:42:09.105  4741  4756 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 06:42:09.105  4741  4756 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-22 06:42:09.106  4741  4741 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-22 06:42:09.106  4714  4725 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-22 06:42:09.110   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@85c8bc0:true
,09-22 06:42:09.111  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 06:42:09.116  3596  3596 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-22 06:42:09.121  3596  3596 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-22 06:42:09.125   929  3497 I ActivityManager: Start proc 5433:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-22 06:42:09.139  5405  5405 D LocalBluetoothProfileManager: Adding local MAP profile
,09-22 06:42:09.141  5405  5405 D BluetoothMap: Create BluetoothMap proxy object
,09-22 06:42:09.148  5405  5405 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-22 06:42:09.161  3596  3596 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-22 06:42:09.161  5433  5433 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-22 06:42:09.165  5405  5405 D DockEventReceiver: finishStartingService: stopping service
,09-22 06:42:09.172   929  3497 I ActivityManager: Killing 4667:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-22 06:42:09.176  3596  3596 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-22 06:42:09.268  4323  4410 I bt_hci  : shut_down
,09-22 06:42:09.271  4323  4414 D bt_hwcfg: hw_epilog_process
,09-22 06:42:09.272  4323  4414 I bt_vendor: low_power_mode_cb
,09-22 06:42:09.275  4323  4414 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-22 06:42:09.275  4323  4414 I bt_vendor: epilog_cb
,09-22 06:42:09.275  4323  4414 I bt_hci  : epilog_finished_callback
,09-22 06:42:09.278  4323  4410 I bt_hci_h4: hal_close
,09-22 06:42:09.278  4323  4410 I bt_userial_vendor: device fd = 54 close
,09-22 06:42:09.281  4216  4216 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 06:42:09.281   929  2897 D wifi    : In wifi stop Hal
09-22 06:42:09.281   929  2897 D wifi    : halHandle = 0x7f8bf3a000, mVM = 0x7fa854d140, mCls = 0x100b7e
09-22 06:42:09.282   929  3587 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-22 06:42:09.282   929  3587 D WifiHAL : Got a signal to exit!!!
09-22 06:42:09.282   929  3587 I WifiHAL : Exit wifi_event_loop
09-22 06:42:09.282   929  2897 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-22 06:42:09.282   929  2897 E WifiHAL : Event processing terminated
09-22 06:42:09.283   929  2897 D wifi    : In wifi cleaned up handler
09-22 06:42:09.283   929  2897 I WifiHAL : Internal cleanup completed
09-22 06:42:09.283  3412  3967 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 06:42:09.284  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:09.285  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:09.304   929  3587 D wifi    : set interface wlan0 flags (DOWN)
,09-22 06:42:09.304   929  2897 D WifiNative-HAL: HAL event thread stopped successfully
,09-22 06:42:09.372  5433  5433 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 06:42:09.372  5433  5433 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 06:42:09.372  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-22 06:42:09.378  5433  5433 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-22 06:42:09.378  5433  5433 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 06:42:09.378  5433  5433 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-22 06:42:09.378  5,433  5433 D StrictMode: 	at com.google.r.e.b(PG:170)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 06:42:09.378  5433  5433 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.r.k.d(PG:583)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.r.e.b(PG:170)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 0,6:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 06:42:09.378  5433  5433 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 06:42:09.378  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 06:42:09.379  5433  5433 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 06:42:09.379  5433  5433 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 06:42:09.379  5433  5433 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 06:42:09.385  5405  5405 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 06:42:09.392  5405  5405 D DockEventReceiver: finishStartingService: stopping service
09-22 06:42:09.392  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 06:42:09.392  4323  4407 D bt_stack_manager: event_shut_down_stack finished.
09-22 06:42:09.392  4323  4406 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-22 06:42:09.394   929  3347 I ActivityManager: Killing 4170:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-22 06:42:09.426  4323  4406 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-22 06:42:09.428  4323  4323 D BtGatt.DebugUtils: handleDebugAction() action=null
09-22 06:42:09.428  4323  4323 D BtGatt.GattService: Received stop request...Stopping profile...
09-22 06:42:09.428  4323  4323 D BtGatt.GattService: stop()
09-22 06:42:09.428  4323  4323 D BtGatt.AdvertiseManager: advertise clients cleared
09-22 06:42:09.429  4323  4323 V BluetoothAdapterState: isTurningOff()=false
09-22 06:42:09.430  4323  4323 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:09.430  4323  4323 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:09.430  4323  4323 V BluetoothAdapterState: isBleTurningOff()=true
09-22 06:42:09.430  4323  4406 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-22 06:42:09.430  4323  4406 D BluetoothAdapterProperties: Setting state to 10
09-22 06:42:09.430  4323  4406 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-22 06:42:09.430  4323  4406 I BluetoothAdapterState: Entering OffState
09-22 06:42:09.431   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-22 06:42:09.436  4323  4323 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-22 06:42:09.436  4323  4323 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-22 06:42:09.436  4323  4323 I BluetoothServiceJni: cleanupNative: return from cleanup
09-22 06:42:09.438  4323  4407 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-22 06:42:09.441  4323  4323 I art     : System.exit called, status: 0
09-22 06:42:09.441  4323  4323 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-22 06:42:09.457  5353  5353 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 06:42:09.474  3848  3848 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-22 06:42:09.478  3848  3848 D SystemUpdateService: onCreate
,09-22 06:42:09.479   929  3078 I ActivityManager: Process com.android.bluetooth (pid 4323) has died
,09-22 06:42:09.482  3848  3848 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-22 06:42:09.490  3848  3848 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-22 06:42:09.495  3848  5136 I iu.UploadsManager: num queued entries: 0
,09-22 06:42:09.495  3848  5136 I iu.UploadsManager: num updated entries: 0
09-22 06:42:09.495  3848  5136 I iu.SyncManager: NEXT; no task
,09-22 06:42:09.504  3848  3848 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-22 06:42:09.505  3848  3848 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-22 06:42:09.506   929   946 D Tethering: InitialState.processMessage what=4
,09-22 06:42:09.507  5138  5138 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-22 06:42:09.508   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-22 06:42:09.511  5138  5138 D SprintDMHelper: simOperator: 
09-22 06:42:09.512  5138  5138 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-22 06:42:09.523  3848  5466 I SystemUpdateService: active receiver: enabled
,09-22 06:42:09.526  4216  5468 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-22 06:42:09.535   929  3480 I ActivityManager: Start proc 5469:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-22 06:42:09.538  3848  5466 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-22 06:42:09.549  3848  5466 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,09-22 06:42:09.550  3848  5466 I SystemUpdateService: now status is 0 (complete)
09-22 06:42:09.550  3848  5466 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-22 06:42:09.550  3848  5466 I SystemUpdateService: file has been verified
09-22 06:42:09.551  3848  5466 I SystemUpdateService: OTA package size = 21989297
,09-22 06:42:09.573  5469  5469 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-22 06:42:09.578  3848  5466 I SystemUpdateService: showing system update notification
,09-22 06:42:09.612  3848  3848 D SystemUpdateService: onDestroy
,09-22 06:42:09.614   929  3044 I ActivityManager: Killing 4420:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-22 06:42:09.713  5433  5451 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-22 06:42:09.725   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@687b2dd:true
,09-22 06:42:10.167   507   923 E Netd    : netlink response contains error (No such file or directory)
,09-22 06:42:10.169   929  2899 E NetdConnector: NDC Command {53 network destroy 100} took too long (1091ms)
,09-22 06:42:10.170   929  2899 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-22 06:42:10.170   929  2899 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-22 06:42:10.171   929  2895 E NetdConnector: NDC Command {54 bandwidth setglobalalert 2097152} took too long (1075ms)
09-22 06:42:10.172   929  2894 E NetdConnector: NDC Command {55 bandwidth gettetherstats} took too long (663ms)
09-22 06:42:10.172   507   923 D TetherController: Setting IP forward enable = 0
,09-22 06:42:11.988   929   940 D WifiService: setWifiEnabled: true pid=5353, uid=10077
09-22 06:42:11.988   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 06:42:11.997   507   923 D SoftapController: Softap fwReload - Ok
,09-22 06:42:12.002   507   923 D CommandListener: Setting iface cfg
,09-22 06:42:12.002   507   923 D CommandListener: Trying to bring down wlan0
09-22 06:42:12.004   507   923 D CommandListener: Clearing all IP addresses on wlan0
,09-22 06:42:12.010   929  2897 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 06:42:12.616   929  2897 D wifi    : set interface wlan0 flags (UP)
,09-22 06:42:12.618   929  2897 I WifiHAL : Initializing wifi
09-22 06:42:12.618   929  2897 I WifiHAL : Creating socket
,09-22 06:42:12.626   929  2897 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-22 06:42:12.626   929  2897 D wifi    : Did set static halHandle = 0x7f8bf3a000
,09-22 06:42:12.627   929  2897 D wifi    : halHandle = 0x7f8bf3a000, mVM = 0x7fa854d140, mCls = 0x1862
09-22 06:42:12.627   929  2897 D wifi    : array field set
09-22 06:42:12.627   929  2897 I WifiNative-HAL: interface[0] = wlan0
,09-22 06:42:12.627   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-22 06:42:12.637   929  5493 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547808845824
,09-22 06:42:12.637   929  5493 D wifi    : waitForHalEvents called, vm = 0x7fa854d140, obj = 0x1862, env = 0x7f8d15e380
,09-22 06:42:12.714  5494  5494 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-22 06:42:12.732   929  2897 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-22 06:42:12.737  5494  5494 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 06:42:12.743  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:12.746  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:12.769  5494  5494 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 06:42:12.769  5494  5494 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-22 06:42:12.785   929  2897 D WifiConfigStore: Loading config and enabling all networks 
,09-22 06:42:12.786  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:12.786  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:12.786  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:12.786  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:12.786  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:12.786  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 06:42:12.786  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:12.786  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:12.786  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 06:42:12.786  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:12.786  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 06:42:12.787  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:12.787  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:12.787  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:12.787  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:12.787  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:12.787  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 06:42:12.787  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:12.787  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:12.787  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 06:42:12.787  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 06:42:12.787  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 06:42:12.798   929  2897 D WifiConfigStore: loaded 0 passpoint configs
,09-22 06:42:12.799   929  2897 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-22 06:42:12.799   929  2897 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-22 06:42:12.800   929  2897 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-22 06:42:12.801   929  2897 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-22 06:42:12.802   929  2897 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-22 06:42:12.802   929  2897 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-22 06:42:12.802   929  2897 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-22 06:42:12.806   929  2897 D WifiNative-HAL: Setting external_sim to 1
,09-22 06:42:12.806   929  2897 D wifi    : setting dfs flag to true, 0x7f8e2d9620
,09-22 06:42:12.807  4216  4216 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 06:42:12.807   929  2897 D WifiStateMachine: Setting OUI to DA-A1-19
,09-22 06:42:12.807   929  2897 D wifi    : setting scan oui 0x7f8e2d9620
09-22 06:42:12.807   929  2897 D WifiHAL : Sending mac address OUI
,09-22 06:42:12.811   929  2897 E native  : do suspend false
,09-22 06:42:12.818   929  2897 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-22 06:42:12.818   929   929 D RttService: SCAN_AVAILABLE : 3
09-22 06:42:12.818   929  3004 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-22 06:42:12.818   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-22 06:42:12.819   507   923 D CommandListener: Setting iface cfg
,09-22 06:42:12.822   929  2896 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
,09-22 06:42:12.822   929  2896 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-22 06:42:12.831   929  2896 D WifiNative-HAL: p2pGetDeviceAddress
,09-22 06:42:12.831   929  2896 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-22 06:42:12.850   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=182587 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=27 mControllerEnergyUsed=102 }
,09-22 06:42:14.996   929  3908 D WifiService: setWifiEnabled: false pid=5353, uid=10077
09-22 06:42:14.997   929  3908 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 06:42:15.003   929   929 D RttService: SCAN_AVAILABLE : 1
,09-22 06:42:15.003   929  3004 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-22 06:42:15.016   929  2897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-22 06:42:15.017   507   923 D CommandListener: Clearing all IP addresses on wlan0
,09-22 06:42:15.023   929  2897 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-22 06:42:15.025  5494  5494 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-22 06:42:15.034  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 06:42:15.034  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:15.034  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:15.034  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:15.034  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 06:42:15.034  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 06:42:15.034  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:15.034  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:15.034  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 06:42:15.035  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:15.035  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 06:42:15.036  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:15.037  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:15.037  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:15.037  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:15.037  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 06:42:15.037  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 06:42:15.037  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:15.037  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:15.037  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 06:42:15.037  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:15.037  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 06:42:15.037  5494  5494 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-22 06:42:15.043  5494  5494 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-22 06:42:15.045  5494  5494 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-22 06:42:15.149   929  2897 D wifi    : In wifi stop Hal
09-22 06:42:15.149   929  2897 D wifi    : halHandle = 0x7f8bf3a000, mVM = 0x7fa854d140, mCls = 0x1862
09-22 06:42:15.149   929  5493 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-22 06:42:15.149   929  5493 D WifiHAL : Got a signal to exit!!!
09-22 06:42:15.149   929  5493 I WifiHAL : Exit wifi_event_loop
09-22 06:42:15.149  4216  4216 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 06:42:15.151   929  2897 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-22 06:42:15.152   929  2897 E WifiHAL : Event processing terminated
09-22 06:42:15.154   929  2897 D wifi    : In wifi cleaned up handler
09-22 06:42:15.155   929  2897 I WifiHAL : Internal cleanup completed
09-22 06:42:15.156  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:15.158  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:15.160  3412  3967 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 06:42:15.193   929  5493 D wifi    : set interface wlan0 flags (DOWN)
,09-22 06:42:15.194   929  2897 D WifiNative-HAL: HAL event thread stopped successfully
,09-22 06:42:15.397   929   946 D Tethering: InitialState.processMessage what=4
,09-22 06:42:15.400   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-22 06:42:18.037   929   946 I ActivityManager: Start proc 5498:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-22 06:42:18.127  5498  5498 D AdapterServiceConfig: Adding HeadsetService
,09-22 06:42:18.128  5498  5498 D AdapterServiceConfig: Adding A2dpService
09-22 06:42:18.128  5498  5498 D AdapterServiceConfig: Adding HidService
09-22 06:42:18.128  5498  5498 D AdapterServiceConfig: Adding HealthService
09-22 06:42:18.128  5498  5498 D AdapterServiceConfig: Adding PanService
09-22 06:42:18.128  5498  5498 D AdapterServiceConfig: Adding GattService
09-22 06:42:18.128  5498  5498 D AdapterServiceConfig: Adding BluetoothMapService
,09-22 06:42:18.128  5498  5498 D AdapterServiceConfig: Adding SapService
,09-22 06:42:18.141   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2215002:true
,09-22 06:42:18.141  5498  5498 D BluetoothAdapterState: make() - Creating AdapterState
,09-22 06:42:18.145  5498  5498 I bt_bluedroid: init
,09-22 06:42:18.145  5498  5510 I BluetoothAdapterState: Entering OffState
,09-22 06:42:18.147  5498  5511 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-22 06:42:18.148  5498  5511 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-22 06:42:18.148  5498  5511 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-22 06:42:18.149  5498  5511 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-22 06:42:18.150  5498  5498 I bt_bluedroid: get_profile_interface socket
,09-22 06:42:18.151  5498  5514 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 06:42:18.152  5498  5498 I bt_bluedroid: get_profile_interface sdp
09-22 06:42:18.153  5498  5514 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 06:42:18.156  5498  5509 I bt_bluedroid: config_hci_snoop_log
09-22 06:42:18.157   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-22 06:42:18.161  5498  5510 D BluetoothAdapterState: Current state: OFF, message: 0
,09-22 06:42:18.161  5498  5510 D BluetoothAdapterProperties: Setting state to 14
09-22 06:42:18.161  5498  5510 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-22 06:42:18.163  5498  5510 D BluetoothBondStateMachine: make
,09-22 06:42:18.164  5498  5515 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-22 06:42:18.167  5498  5510 I BluetoothAdapterState: Entering PendingCommandState
,09-22 06:42:18.168  5498  5498 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-22 06:42:18.170  5498  5498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
09-22 06:42:18.170  5498  5498 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-22 06:42:18.171  5498  5498 D BtGatt.GattService: Received start request. Starting profile...
09-22 06:42:18.171  5498  5498 D BtGatt.GattService: start()
09-22 06:42:18.171  5498  5498 I bt_bluedroid: get_profile_interface gatt
,09-22 06:42:18.172  5498  5498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
09-22 06:42:18.172  5498  5498 D BtGatt.AdvertiseManager: advertise manager created
,09-22 06:42:18.177  5498  5498 V BluetoothAdapterState: isTurningOff()=false
,09-22 06:42:18.177  5498  5498 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:18.177  5498  5498 V BluetoothAdapterState: isBleTurningOn()=true
09-22 06:42:18.177  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:18.177  5498  5510 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-22 06:42:18.179  5498  5510 I bt_bluedroid: bt_bluedroid
09-22 06:42:18.179  5498  5511 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-22 06:42:18.179  5498  5511 I bt_hci  : start_up
,09-22 06:42:18.184  5498  5511 I bt_vendor: alloc value 0xf3aeb871
09-22 06:42:18.184  5498  5511 I bt_vendor: init
09-22 06:42:18.184  5498  5511 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-22 06:42:18.184  5498  5511 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-22 06:42:18.296  5498  5511 D bt_hci  : start_up starting async portion
09-22 06:42:18.296  5498  5518 I bt_hci  : event_finish_startup
09-22 06:42:18.297  5498  5518 I bt_hci_h4: hal_open
,09-22 06:42:18.297  5498  5518 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-22 06:42:18.301  5498  5518 I bt_userial_vendor: device fd = 54 open
,09-22 06:42:18.297  5519  5519 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 06:42:18.315  5498  5518 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 06:42:18.317  5498  5518 D bt_hwcfg: Chipset BCM4358A3
,09-22 06:42:18.317  5498  5518 D bt_hwcfg: Target name = [BCM4358A3]
09-22 06:42:18.318  5498  5518 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-22 06:42:18.727  5498  5518 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-22 06:42:18.728  5498  5518 D bt_hwcfg: Settlement delay -- 100 ms
,09-22 06:42:18.728  5498  5518 I bt_hwcfg: Setting fw settlement delay to 100 
,09-22 06:42:18.862  5498  5518 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-22 06:42:18.862  5498  5518 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-22 06:42:18.864  5498  5518 I bt_hwcfg: vendor lib fwcfg completed
09-22 06:42:18.864  5498  5518 I bt_vendor: firmware callback
09-22 06:42:18.864  5498  5518 I bt_hci  : firmware_config_callback
09-22 06:42:18.873  5498  5521 I bt_btu  : btu_task pending for preload complete event
09-22 06:42:18.873  5498  5521 I bt_btu_task: Bluetooth chip preload is complete
09-22 06:42:18.873  5498  5521 I bt_btu  : btu_task received preload complete event
09-22 06:42:18.880  5498  5521 I         : BTE_InitTraceLevels -- TRC_HCI
09-22 06:42:18.880  5498  5521 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-22 06:42:18.880  5498  5521 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-22 06:42:18.880  5498  5521 I         : BTE_InitTraceLevels -- TRC_AVDT
09-22 06:42:18.880  5498  5521 I         : BTE_InitTraceLevels -- TRC_AVRC
09-22 06:42:18.880  5498  5521 I         : BTE_InitTraceLevels -- TRC_A2D
09-22 06:42:18.881  5498  5521 I         : BTE_InitTraceLevels -- TRC_BNEP
09-22 06:42:18.881  5498  5521 I         : BTE_InitTraceLevels -- TRC_BTM
09-22 06:42:18.881  5498  5521 I         : BTE_InitTraceLevels -- TRC_GAP
09-22 06:42:18.881  5498  5521 I         : BTE_InitTraceLevels -- TRC_PAN
09-22 06:42:18.881  5498  5521 I         : BTE_InitTraceLevels -- TRC_SDP
09-22 06:42:18.881  5498  5521 I         : BTE_InitTraceLevels -- TRC_GATT
09-22 06:42:18.881  5498  5521 I         : BTE_InitTraceLevels -- TRC_SMP
09-22 06:42:18.881  5498  5521 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-22 06:42:18.881  5498  5521 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-22 06:42:18.964  5498  5521 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3a69549
09-22 06:42:18.965  5498  5521 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3a69549 
,09-22 06:42:18.985  5498  5514 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-22 06:42:18.987  5498  5514 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-22 06:42:18.987  5498  5514 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 06:42:18.990  5498  5514 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 06:42:18.993  5498  5514 D BluetoothAdapterProperties: Scan Mode:20
,09-22 06:42:18.994  5498  5514 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 06:42:18.994  5498  5514 D bt_hci  : do_postload posting postload work item
09-22 06:42:18.994  5498  5518 I bt_hci  : event_postload
,09-22 06:42:18.994  5498  5518 I bt_vendor: sco_config_cb
09-22 06:42:18.994  5498  5518 I bt_hci  : sco_config_callback postload finished.
09-22 06:42:18.998  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:18.999  5498  5514 D bt_bte_conf: Device ID record 1 : primary
09-22 06:42:18.999  5498  5514 D bt_bte_conf:   vendorId            = 000f
09-22 06:42:18.999  5498  5514 D bt_bte_conf:   vendorIdSource      = 0001
09-22 06:42:18.999  5498  5514 D bt_bte_conf:   product             = 1200
,09-22 06:42:18.999  5498  5514 D bt_bte_conf:   version             = 1436
09-22 06:42:19.000  5498  5514 D bt_bte_conf:   clientExecutableURL = 
09-22 06:42:19.000  5498  5514 D bt_bte_conf:   serviceDescription  = 
09-22 06:42:19.000  5498  5514 D bt_bte_conf:   documentationURL    = 
09-22 06:42:19.000  5498  5514 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-22 06:42:19.000  5498  5511 D bt_stack_manager: event_start_up_stack finished
,09-22 06:42:19.003  5498  5518 I bt_vendor: low_power_mode_cb
,09-22 06:42:19.005  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:19.006  5498  5510 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-22 06:42:19.006  5498  5510 D BluetoothAdapterProperties: Setting state to 15
09-22 06:42:19.006  5498  5510 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-22 06:42:19.007  5498  5510 I BluetoothAdapterState: Entering BleOnState
,09-22 06:42:19.010  5498  5510 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-22 06:42:19.010  5498  5510 D BluetoothAdapterProperties: Setting state to 11
09-22 06:42:19.010  5498  5510 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-22 06:42:19.014  5498  5498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
,09-22 06:42:19.015  5498  5498 D HeadsetService: Received start request. Starting profile...
,09-22 06:42:19.018  5498  5498 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-22 06:42:19.018  5498  5498 D HeadsetStateMachine: make
,09-22 06:42:19.021  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:19.025  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:19.029  5498  5498 D HeadsetStateMachine: max_hf_connections = 1
,09-22 06:42:19.029  5498  5498 I bt_bluedroid: get_profile_interface handsfree
09-22 06:42:19.029  5498  5514 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-22 06:42:19.031  5498  5514 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-22 06:42:19.033  5498  5498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
09-22 06:42:19.033  5498  5498 D A2dpService: Received start request. Starting profile...
,09-22 06:42:19.034  5498  5498 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-22 06:42:19.034  5498  5498 I bt_bluedroid: get_profile_interface avrcp
,09-22 06:42:19.036  5498  5510 I BluetoothAdapterState: Entering PendingCommandState
,09-22 06:42:19.041  5498  5498 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-22 06:42:19.041  5498  5498 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-22 06:42:19.041  5498  5498 D A2dpStateMachine: make
09-22 06:42:19.042  5498  5498 I bt_bluedroid: get_profile_interface a2dp
,09-22 06:42:19.043  5498  5514 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-22 06:42:19.046  5498  5530 D A2dpStateMachine: Enter Disconnected: -2
09-22 06:42:19.046  5498  5498 I BluetoothHidServiceJni: classInitNative: succeeds
,09-22 06:42:19.047  5498  5498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
,09-22 06:42:19.048  5405  5405 D BluetoothInputDevice: Proxy object connected
,09-22 06:42:19.049  5405  5405 D HidProfile: Bluetooth service connected
,09-22 06:42:19.050  5498  5498 D HidService: Received start request. Starting profile...
09-22 06:42:19.050  5498  5498 I bt_bluedroid: get_profile_interface hidhost
09-22 06:42:19.050  5498  5498 D HidService: setHidService(): set to: null
09-22 06:42:19.050  5498  5514 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a4a56d
09-22 06:42:19.050  5498  5514 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-22 06:42:19.051  5498  5498 I BluetoothHealthServiceJni: classInitNative: succeeds
09-22 06:42:19.051  5498  5498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
,09-22 06:42:19.053  5498  5498 D HealthService: Received start request. Starting profile...
,09-22 06:42:19.054  5498  5498 I bt_bluedroid: get_profile_interface health
,09-22 06:42:19.057  5498  5498 V BluetoothAdapterState: isTurningOff()=false
09-22 06:42:19.057  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 06:42:19.057  5498  5498 V BluetoothAdapterState: isTurningOn()=true
09-22 06:42:19.057  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:19.057  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:19.058  5498  5526 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-22 06:42:19.058  5498  5498 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-22 06:42:19.059  5498  5498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
,09-22 06:42:19.060  5405  5405 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 06:42:19.060  5498  5498 D PanService: Received start request. Starting profile...
09-22 06:42:19.060  5498  5498 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-22 06:42:19.060  5498  5498 I bt_bluedroid: get_profile_interface pan
09-22 06:42:19.060  5405  5405 D PanProfile: Bluetooth service connected
09-22 06:42:19.061  5498  5514 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-22 06:42:19.062  5498  5498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
,09-22 06:42:19.064  5498  5498 D BluetoothMapService: Received start request. Starting profile...
09-22 06:42:19.064  5498  5498 D BluetoothMapService: start()
09-22 06:42:19.066  5498  5498 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-22 06:42:19.067  5498  5498 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-22 06:42:19.067  5498  5498 D BluetoothMapAppObserver: createReceiver()
09-22 06:42:19.068  5498  5498 D BluetoothMapAppObserver: initObservers()
09-22 06:42:19.069  5498  5498 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-22 06:42:19.074  5498  5498 V SapService: SapBinder()
09-22 06:42:19.074  5498  5498 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
09-22 06:42:19.074  5405  5405 D BluetoothMap: Proxy object connected
09-22 06:42:19.075  5405  5405 D MapProfile: Bluetooth service connected
09-22 06:42:19.075  5405  5405 D BluetoothMap: getConnectedDevices()
09-22 06:42:19.075  5498  5498 D SapService: Received start request. Starting profile...
09-22 06:42:19.075  5498  5498 V SapService: start()
09-22 06:42:19.075  5405  5405 D BluetoothMap: Bluetooth is Not enabled
,09-22 06:42:19.077  5498  5498 V BluetoothAdapterState: isTurningOff()=false
09-22 06:42:19.077  5498  5498 V BluetoothAdapterState: isTurningOn()=true
09-22 06:42:19.077  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:19.077  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:19.077  5498  5498 V BluetoothAdapterState: isTurningOff()=false
09-22 06:42:19.077  5498  5498 V BluetoothAdapterState: isTurningOn()=true
09-22 06:42:19.077  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:19.077  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:19.077  5498  5498 V BluetoothAdapterState: isTurningOff()=false
,09-22 06:42:19.077  5498  5498 V BluetoothAdapterState: isTurningOn()=true
09-22 06:42:19.077  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:19.077  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 06:42:19.078  5498  5498 V BluetoothAdapterState: isTurningOff()=false
09-22 06:42:19.078  5498  5498 V BluetoothAdapterState: isTurningOn()=true
09-22 06:42:19.078  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:19.078  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:19.078  5498  5498 V BluetoothAdapterState: isTurningOff()=false
09-22 06:42:19.078  5498  5498 V BluetoothAdapterState: isTurningOn()=true
09-22 06:42:19.078  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:19.078  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:19.079  5498  5498 V BluetoothAdapterState: isTurningOff()=false
,09-22 06:42:19.079  5498  5498 V BluetoothAdapterState: isTurningOn()=true
09-22 06:42:19.079  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:19.079  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:19.080  5498  5510 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-22 06:42:19.080  5498  5510 D BluetoothAdapterProperties: ScanMode =  20
09-22 06:42:19.080  5498  5510 D BluetoothAdapterProperties: State =  11
,09-22 06:42:19.083  5498  5514 D BluetoothAdapterProperties: Scan Mode:21
,09-22 06:42:19.083  5498  5510 D BluetoothAdapterProperties: Setting state to 12
09-22 06:42:19.083  5498  5510 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-22 06:42:19.083  5498  5514 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 06:42:19.083  5498  5510 I BluetoothAdapterState: Entering OnState
09-22 06:42:19.083  3476  3504 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-22 06:42:19.085  5405  5417 D BluetoothPan: onBluetoothStateChange on: true
,09-22 06:42:19.085  5405  5418 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 06:42:19.085   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 06:42:19.085   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-22 06:42:19.086  5405  5417 D BluetoothMap: onBluetoothStateChange: up=true
09-22 06:42:19.086   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 06:42:19.086  3052  3278 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 06:42:19.086  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:19.086  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:19.086  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:19.086  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 06:42:19.086  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:19.086  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:19.086  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:19.086  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 06:42:19.087  5405  5418 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 06:42:19.088  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 06:42:19.088   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-22 06:42:19.089  3052  3063 D BluetoothPan: onBluetoothStateChange on: true
09-22 06:42:19.090   929   929 D BluetoothA2dp: Proxy object connected
09-22 06:42:19.091  3052  3065 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 06:42:19.091  3052  3052 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 06:42:19.091  3052  3052 D PanProfile: Bluetooth service connected
09-22 06:42:19.092  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:19.092  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:19.092  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:19.092  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 06:42:19.092  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:19.092  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:19.092  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:19.092  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 06:42:19.093  3052  3278 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 06:42:19.093  3052  3052 D BluetoothInputDevice: Proxy object connected
09-22 06:42:19.093  3052  3052 D HidProfile: Bluetooth service connected
09-22 06:42:19.093  3052  3065 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-22 06:42:19.094  5498  5498 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 06:42:19.094  5498  5498 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-22 06:42:19.094  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 06:42:19.095  3052  3278 D BluetoothMap: onBluetoothStateChange: up=true
09-22 06:42:19.095  3052  3052 D BluetoothA2dp: Proxy object connected
,09-22 06:42:19.095  5498  5498 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 06:42:19.098  3052  3052 D BluetoothMap: Proxy object connected
09-22 06:42:19.098  3052  3052 D MapProfile: Bluetooth service connected
09-22 06:42:19.098  3052  3052 D BluetoothMap: getConnectedDevices()
09-22 06:42:19.098   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-22 06:42:19.101  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:19.102  5498  5498 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 06:42:19.102  5405  5405 D LocalBluetoothProfileManager: Adding local A2DP profile
09-22 06:42:19.102  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:19.103  5498  5498 D ObexServerSockets: Succeed to create listening sockets 
09-22 06:42:19.103  5498  5498 D ObexServerSockets0: startAccept()
09-22 06:42:19.103  5498  5498 D ObexServerSockets0: prepareForNewConnect()
09-22 06:42:19.105  5405  5405 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-22 06:42:19.106  5498  5498 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-22 06:42:19.106  5498  5498 D BluetoothSdpJni: SDP Create record success - handle: 0
09-22 06:42:19.107  5498  5536 D ObexServerSockets0: Accepting socket connection...
09-22 06:42:19.107  5498  5498 D BluetoothMapService: onReceive
09-22 06:42:19.107  5498  5537 D ObexServerSockets0: Accepting socket connection...
09-22 06:42:19.107  5498  5498 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 06:42:19.107  5498  5498 D BluetoothMapService: STATE_ON
09-22 06:42:19.109  5498  5538 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 06:42:19.110  5498  5538 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-22 06:42:19.110  5498  5538 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-22 06:42:19.115  5405  5405 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 06:42:19.117  5405  5405 D BluetoothA2dp: Proxy object connected
,09-22 06:42:19.120  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 06:42:19.121  5405  5405 D DockEventReceiver: finishStartingService: stopping service
,09-22 06:42:19.128  5405  5405 D BluetoothPbap: Proxy object connected
,09-22 06:42:19.128  5405  5405 D PbapServerProfile: Bluetooth service connected
,09-22 06:42:19.133  5498  5498 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 06:42:19.133  5498  5498 D ObexServerSockets0: prepareForNewConnect()
09-22 06:42:19.133  3052  3052 D BluetoothPbap: Proxy object connected
09-22 06:42:19.133  3052  3052 D PbapServerProfile: Bluetooth service connected
,09-22 06:42:19.136  5498  5542 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 06:42:19.150  5498  5546 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 06:42:19.150  5498  5546 I BtOppRfcommListener: Accept thread started.
,09-22 06:42:19.185   929   929 D BluetoothHeadset: Proxy object connected
,09-22 06:42:19.185   929   929 D BluetoothHeadset: Proxy object connected
09-22 06:42:19.185  3476  3507 D BluetoothHeadset: Proxy object connected
09-22 06:42:19.186  3052  3065 D BluetoothHeadset: Proxy object connected
09-22 06:42:19.186  3052  3052 D HeadsetProfile: Bluetooth service connected
09-22 06:42:19.186   929   929 D BluetoothHeadset: Proxy object connected
09-22 06:42:19.186   929   946 D BluetoothHeadset: Proxy object connected
09-22 06:42:19.186   929   946 D BluetoothHeadset: Proxy object connected
,09-22 06:42:19.186   929   946 D BluetoothHeadset: Proxy object connected
,09-22 06:42:19.193  3052  3278 D BluetoothHeadset: Proxy object connected
09-22 06:42:19.193  3052  3052 D HeadsetProfile: Bluetooth service connected
,09-22 06:42:19.208  5405  5418 D BluetoothHeadset: Proxy object connected
,09-22 06:42:19.209  5405  5405 D HeadsetProfile: Bluetooth service connected
,09-22 06:42:19.429   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 06:42:20.430   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 06:42:21.015  5498  5510 D BluetoothAdapterState: Current state: ON, message: 23
,09-22 06:42:21.015  5498  5510 D BluetoothAdapterProperties: Setting state to 13
09-22 06:42:21.016  5498  5510 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-22 06:42:21.017  5498  5510 D BluetoothAdapterProperties: onBluetoothDisable()
,09-22 06:42:21.018  5498  5510 I BluetoothAdapterState: Entering PendingCommandState
,09-22 06:42:21.026  5405  5405 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 06:42:21.026  5498  5498 D BluetoothMapService: onReceive
09-22 06:42:21.027  5498  5498 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-22 06:42:21.027  5498  5498 D BluetoothMapService: STATE_TURNING_OFF
09-22 06:42:21.027  5498  5498 D BluetoothMapService: MAP Service closeService in
09-22 06:42:21.027  5498  5498 D BluetoothMapMasInstance0: MAP Service shutdown
09-22 06:42:21.027  5498  5498 D ObexServerSockets0: shutdown(block = true)
,09-22 06:42:21.028  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 06:42:21.028  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:21.028  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:21.028  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:21.028  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 06:42:21.028  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 06:42:21.028  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:21.028  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:21.028  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 06:42:21.028  5498  5498 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-22 06:42:21.028  5498  5536 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-22 06:42:21.029  5498  5498 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-22 06:42:21.029  5498  5523 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-22 06:42:21.030  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 06:42:21.030  5498  5537 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-22 06:42:21.030  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 06:42:21.031  5498  5514 D BluetoothAdapterProperties: Scan Mode:20
,09-22 06:42:21.034  5498  5510 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-22 06:42:21.035  5498  5498 I BtOppRfcommListener: stopping Accept Thread
09-22 06:42:21.036  5498  5546 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-22 06:42:21.036  5498  5546 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-22 06:42:21.037  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 06:42:21.037  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:21.037  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:21.037  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:21.037  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 06:42:21.037  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 06:42:21.037  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:21.037  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:21.037  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 06:42:21.039  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 06:42:21.039  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 06:42:21.042  5498  5498 D HeadsetService: Received stop request...Stopping profile...
09-22 06:42:21.043  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:21.043  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 06:42:21.046  5405  5405 D DockEventReceiver: finishStartingService: stopping service
,09-22 06:42:21.048  5405  5417 D BluetoothHeadset: Proxy object disconnected
09-22 06:42:21.048   929   929 D BluetoothHeadset: Proxy object disconnected
09-22 06:42:21.048   929   929 D BluetoothHeadset: Proxy object disconnected
,09-22 06:42:21.049  3476  5429 D BluetoothHeadset: Proxy object disconnected
09-22 06:42:21.049  5498  5498 D A2dpService: Received stop request...Stopping profile...
09-22 06:42:21.049  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:21.049  3052  3065 D BluetoothHeadset: Proxy object disconnected
09-22 06:42:21.050   929   929 D BluetoothHeadset: Proxy object disconnected
09-22 06:42:21.050  5405  5405 D HeadsetProfile: Bluetooth service disconnected
09-22 06:42:21.050  5498  5530 D A2dpStateMachine: Exit Disconnected: -1
09-22 06:42:21.055   929   929 D BluetoothA2dp: Proxy object disconnected
09-22 06:42:21.055  5405  5405 D BluetoothA2dp: Proxy object disconnected
09-22 06:42:21.057  3052  3052 D HeadsetProfile: Bluetooth service disconnected
09-22 06:42:21.057  5498  5498 D HidService: Received stop request...Stopping profile...
09-22 06:42:21.057  5498  5498 D HidService: Stopping Bluetooth HidService
09-22 06:42:21.057  3052  3052 D BluetoothA2dp: Proxy object disconnected
09-22 06:42:21.060  3052  3052 D BluetoothInputDevice: Proxy object disconnected
09-22 06:42:21.060  3052  3052 D HidProfile: Bluetooth service disconnected
09-22 06:42:21.061  3052  3052 D BluetoothPbap: Proxy object disconnected
09-22 06:42:21.061  3052  3052 D PbapServerProfile: Bluetooth service disconnected
09-22 06:42:21.061  5498  5498 D HealthService: Received stop request...Stopping profile...
09-22 06:42:21.063  5498  5498 V BluetoothAdapterState: isTurningOff()=true
09-22 06:42:21.063  5498  5498 V BluetoothAdapterState: isTurningOn()=false
,09-22 06:42:21.063  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:21.063  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:21.065  5498  5498 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-22 06:42:21.065  5498  5498 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-22 06:42:21.065  5498  5521 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 06:42:21.065  5498  5521 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 06:42:21.065  5498  5521 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-22 06:42:21.066  5405  5405 D BluetoothInputDevice: Proxy object disconnected
09-22 06:42:21.066  5405  5405 D HidProfile: Bluetooth service disconnected
09-22 06:42:21.066  5498  5514 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-22 06:42:21.066  5498  5498 D PanService: Received stop request...Stopping profile...
09-22 06:42:21.066  5405  5405 D BluetoothPbap: Proxy object disconnected
09-22 06:42:21.066  5405  5405 D PbapServerProfile: Bluetooth service disconnected
09-22 06:42:21.066  5498  5514 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-22 06:42:21.070  5405  5405 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 06:42:21.070  3052  3052 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 06:42:21.070  3052  3052 D PanProfile: Bluetooth service disconnected
09-22 06:42:21.070  5405  5405 D PanProfile: Bluetooth service disconnected
09-22 06:42:21.071  5498  5498 D BluetoothMapService: Received stop request...Stopping profile...
09-22 06:42:21.071  5498  5498 D BluetoothMapService: stop()
09-22 06:42:21.072  5498  5498 D BluetoothMapAppObserver: deinitObservers()
09-22 06:42:21.072  5498  5498 D BluetoothMapAppObserver: removeReceiver()
09-22 06:42:21.074  5405  5405 D BluetoothMap: Proxy object disconnected
09-22 06:42:21.074  5405  5405 D MapProfile: Bluetooth service disconnected
,09-22 06:42:21.074  5498  5498 V BluetoothAdapterState: isTurningOff()=true
09-22 06:42:21.075  5498  5498 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:21.075  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:21.075  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:21.075  5498  5498 D SapService: Received stop request...Stopping profile...
09-22 06:42:21.075  5498  5498 V SapService: stop()
09-22 06:42:21.076  3052  3052 D BluetoothMap: Proxy object disconnected
09-22 06:42:21.076  3052  3052 D MapProfile: Bluetooth service disconnected
09-22 06:42:21.078  5498  5521 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 06:42:21.078  5498  5498 V BluetoothAdapterState: isTurningOff()=true
09-22 06:42:21.078  5498  5521 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 06:42:21.078  5498  5498 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:21.078  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:21.078  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:21.078  5498  5498 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-22 06:42:21.078  5498  5498 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-22 06:42:21.079  5498  5498 V BluetoothAdapterState: isTurningOff()=true
09-22 06:42:21.079  5498  5498 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:21.079  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:21.079  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:21.079  5498  5514 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 06:42:21.079  5498  5498 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-22 06:42:21.079  5498  5521 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 06:42:21.079  5498  5514 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 06:42:21.079  5498  5521 W bt_l2cap: btif_in_execute_service_request: Unknown service
09-22 06:42:21.079  5498  5514 E bt_btif : L2CAP - PSM: 0x0019 not found for deregistration
09-22 06:42:21.079  5498  5521 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-22 06:42:21.079  5498  5521 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-22 06:42:21.080  5498  5498 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-22 06:42:21.080  5498  5498 V BluetoothAdapterState: isTurningOff()=true
09-22 06:42:21.080  5498  5498 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:21.080  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:21.080  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 06:42:21.080  5498  5498 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-22 06:42:21.080  5498  5498 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-22 06:42:21.081  5498  5498 D BluetoothMapService: MAP Service closeService in
09-22 06:42:21.081  5498  5498 V BluetoothAdapterState: isTurningOff()=true
09-22 06:42:21.081  5498  5498 V BluetoothAdapterState: isTurningOn()=false
,09-22 06:42:21.081  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:21.081  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:21.082  5498  5498 D BluetoothMapService: cleanup()
09-22 06:42:21.082  5498  5498 D BluetoothMapService: MAP Service closeService in
09-22 06:42:21.082  5498  5498 V BluetoothAdapterState: isTurningOff()=true
,09-22 06:42:21.082  5498  5498 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:21.082  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:21.082  5498  5498 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:21.082  5498  5510 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-22 06:42:21.082  5498  5510 D BluetoothAdapterProperties: Setting state to 15
09-22 06:42:21.082  5498  5510 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-22 06:42:21.083  5498  5510 I BluetoothAdapterState: Entering BleOnState
09-22 06:42:21.083  3476  3686 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-22 06:42:21.084  5405  5417 D BluetoothPan: onBluetoothStateChange on: false
09-22 06:42:21.084  5405  5418 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 06:42:21.085  5405  5417 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 06:42:21.085   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 06:42:21.085   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 06:42:21.085  5405  5418 D BluetoothMap: onBluetoothStateChange: up=false
,09-22 06:42:21.096   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 06:42:21.096  3052  3065 D BluetoothPbap: onBluetoothStateChange: up=false
,09-22 06:42:21.097  5405  5417 D BluetoothPbap: onBluetoothStateChange: up=false
,09-22 06:42:21.097   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 06:42:21.097  5405  5418 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 06:42:21.098  3052  3278 D BluetoothPan: onBluetoothStateChange on: false
09-22 06:42:21.098  3052  3063 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 06:42:21.099  3052  3065 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 06:42:21.099  3052  3278 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 06:42:21.100  3052  3063 D BluetoothMap: onBluetoothStateChange: up=false
09-22 06:42:21.100  5498  5510 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-22 06:42:21.100  5498  5510 D BluetoothAdapterProperties: Setting state to 16
09-22 06:42:21.100  5498  5510 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-22 06:42:21.101  5498  5510 D BluetoothAdapterProperties: onBleDisable
09-22 06:42:21.101  5498  5510 I BluetoothAdapterState: Entering PendingCommandState
,09-22 06:42:21.101  5498  5511 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-22 06:42:21.103  5498  5514 D BluetoothAdapterProperties: Scan Mode:20
,09-22 06:42:21.103  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:21.103  5498  5521 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-22 06:42:21.104  5498  5521 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 06:42:21.106  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:21.106  5405  5405 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 06:42:21.109  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:21.111  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:21.115  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 06:42:21.115  5405  5405 D DockEventReceiver: finishStartingService: stopping service
,09-22 06:42:21.318  5498  5514 I bt_hci  : shut_down
,09-22 06:42:21.323  5498  5518 D bt_hwcfg: hw_epilog_process
,09-22 06:42:21.323  5498  5518 I bt_vendor: low_power_mode_cb
,09-22 06:42:21.326  5498  5518 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-22 06:42:21.326  5498  5518 I bt_vendor: epilog_cb
09-22 06:42:21.326  5498  5518 I bt_hci  : epilog_finished_callback
,09-22 06:42:21.328  5498  5514 I bt_hci_h4: hal_close
,09-22 06:42:21.328  5498  5514 I bt_userial_vendor: device fd = 54 close
,09-22 06:42:21.431   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 06:42:21.442  5498  5511 D bt_stack_manager: event_shut_down_stack finished.
,09-22 06:42:21.442  5498  5510 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-22 06:42:21.446  5498  5510 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-22 06:42:21.446  5498  5498 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-22 06:42:21.447  5498  5498 D BtGatt.GattService: Received stop request...Stopping profile...
,09-22 06:42:21.447  5498  5498 D BtGatt.GattService: stop()
,09-22 06:42:21.447  5498  5498 D BtGatt.AdvertiseManager: advertise clients cleared
09-22 06:42:21.450  5498  5498 V BluetoothAdapterState: isTurningOff()=false
,09-22 06:42:21.450  5498  5498 V BluetoothAdapterState: isTurningOn()=false
,09-22 06:42:21.450  5498  5498 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:21.450  5498  5498 V BluetoothAdapterState: isBleTurningOff()=true
,09-22 06:42:21.451  5498  5510 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-22 06:42:21.451  5498  5510 D BluetoothAdapterProperties: Setting state to 10
09-22 06:42:21.451  5498  5510 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-22 06:42:21.452  5498  5510 I BluetoothAdapterState: Entering OffState
09-22 06:42:21.454   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-22 06:42:21.468  5498  5498 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-22 06:42:21.468  5498  5498 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-22 06:42:21.468  5498  5498 I BluetoothServiceJni: cleanupNative: return from cleanup
09-22 06:42:21.470  5498  5511 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-22 06:42:21.476  5498  5498 I art     : System.exit called, status: 0
,09-22 06:42:21.476  5498  5498 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-22 06:42:21.507   929  3044 I ActivityManager: Process com.android.bluetooth (pid 5498) has died
,09-22 06:42:22.432   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 06:42:23.433   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 06:42:24.013  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:24.013  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 06:42:24.434   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-22 06:42:27.021  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 06:42:27.021  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3230954 added. We now have 6 listener(s)
09-22 06:42:27.021  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 06:42:27.027  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:42:27.028  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dbac0fd added. We now have 7 listener(s)
,09-22 06:42:27.028  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 06:42:27.030  5353  5399 I System.out: IsBluetoothEnabled
,09-22 06:42:27.038  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:27.065   929   946 I ActivityManager: Start proc 5554:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-22 06:42:27.140  5554  5554 D AdapterServiceConfig: Adding HeadsetService
,09-22 06:42:27.140  5554  5554 D AdapterServiceConfig: Adding A2dpService
09-22 06:42:27.141  5554  5554 D AdapterServiceConfig: Adding HidService
,09-22 06:42:27.141  5554  5554 D AdapterServiceConfig: Adding HealthService
09-22 06:42:27.141  5554  5554 D AdapterServiceConfig: Adding PanService
09-22 06:42:27.141  5554  5554 D AdapterServiceConfig: Adding GattService
09-22 06:42:27.141  5554  5554 D AdapterServiceConfig: Adding BluetoothMapService
09-22 06:42:27.141  5554  5554 D AdapterServiceConfig: Adding SapService
,09-22 06:42:27.152   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@afe54d3:true
,09-22 06:42:27.152  5554  5554 D BluetoothAdapterState: make() - Creating AdapterState
,09-22 06:42:27.155  5554  5554 I bt_bluedroid: init
,09-22 06:42:27.155  5554  5566 I BluetoothAdapterState: Entering OffState
,09-22 06:42:27.157  5554  5567 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-22 06:42:27.157  5554  5567 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-22 06:42:27.157  5554  5567 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-22 06:42:27.157  5554  5567 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-22 06:42:27.158  5554  5554 I bt_bluedroid: get_profile_interface socket
,09-22 06:42:27.160  5554  5570 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 06:42:27.160  5554  5554 I bt_bluedroid: get_profile_interface sdp
09-22 06:42:27.161  5554  5570 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 06:42:27.164  5554  5565 I bt_bluedroid: config_hci_snoop_log
09-22 06:42:27.165   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-22 06:42:27.169  5554  5566 D BluetoothAdapterState: Current state: OFF, message: 0
,09-22 06:42:27.169  5554  5566 D BluetoothAdapterProperties: Setting state to 14
09-22 06:42:27.169  5554  5566 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-22 06:42:27.171  5554  5566 D BluetoothBondStateMachine: make
09-22 06:42:27.172  5554  5571 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-22 06:42:27.175  5554  5566 I BluetoothAdapterState: Entering PendingCommandState
,09-22 06:42:27.176  5554  5554 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-22 06:42:27.178  5554  5554 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
09-22 06:42:27.178  5554  5554 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-22 06:42:27.179  5554  5554 D BtGatt.GattService: Received start request. Starting profile...
09-22 06:42:27.179  5554  5554 D BtGatt.GattService: start()
09-22 06:42:27.179  5554  5554 I bt_bluedroid: get_profile_interface gatt
,09-22 06:42:27.180  5554  5554 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
,09-22 06:42:27.180  5554  5554 D BtGatt.AdvertiseManager: advertise manager created
,09-22 06:42:27.185  5554  5554 V BluetoothAdapterState: isTurningOff()=false
,09-22 06:42:27.185  5554  5554 V BluetoothAdapterState: isTurningOn()=false
09-22 06:42:27.185  5554  5554 V BluetoothAdapterState: isBleTurningOn()=true
09-22 06:42:27.185  5554  5554 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:27.185  5554  5566 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-22 06:42:27.187  5554  5566 I bt_bluedroid: bt_bluedroid
09-22 06:42:27.187  5554  5567 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-22 06:42:27.187  5554  5567 I bt_hci  : start_up
,09-22 06:42:27.192  5554  5567 I bt_vendor: alloc value 0xf3aeb871
,09-22 06:42:27.192  5554  5567 I bt_vendor: init
09-22 06:42:27.192  5554  5567 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-22 06:42:27.192  5554  5567 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-22 06:42:27.303  5554  5567 D bt_hci  : start_up starting async portion
,09-22 06:42:27.303  5554  5574 I bt_hci  : event_finish_startup
09-22 06:42:27.303  5554  5574 I bt_hci_h4: hal_open
09-22 06:42:27.304  5554  5574 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-22 06:42:27.300  5575  5575 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-22 06:42:27.306  5554  5574 I bt_userial_vendor: device fd = 54 open
,09-22 06:42:27.321  5554  5574 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 06:42:27.324  5554  5574 D bt_hwcfg: Chipset BCM4358A3
,09-22 06:42:27.324  5554  5574 D bt_hwcfg: Target name = [BCM4358A3]
09-22 06:42:27.325  5554  5574 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-22 06:42:27.727  5554  5574 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-22 06:42:27.727  5554  5574 D bt_hwcfg: Settlement delay -- 100 ms
09-22 06:42:27.727  5554  5574 I bt_hwcfg: Setting fw settlement delay to 100 
,09-22 06:42:27.861  5554  5574 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 06:42:27.862  5554  5574 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-22 06:42:27.863  5554  5574 I bt_hwcfg: vendor lib fwcfg completed
09-22 06:42:27.863  5554  5574 I bt_vendor: firmware callback
09-22 06:42:27.863  5554  5574 I bt_hci  : firmware_config_callback
,09-22 06:42:27.871  5554  5577 I bt_btu  : btu_task pending for preload complete event
,09-22 06:42:27.871  5554  5577 I bt_btu_task: Bluetooth chip preload is complete
09-22 06:42:27.871  5554  5577 I bt_btu  : btu_task received preload complete event
,09-22 06:42:27.878  5554  5577 I         : BTE_InitTraceLevels -- TRC_HCI
,09-22 06:42:27.879  5554  5577 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-22 06:42:27.879  5554  5577 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-22 06:42:27.879  5554  5577 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-22 06:42:27.879  5554  5577 I         : BTE_InitTraceLevels -- TRC_AVRC
09-22 06:42:27.879  5554  5577 I         : BTE_InitTraceLevels -- TRC_A2D
,09-22 06:42:27.879  5554  5577 I         : BTE_InitTraceLevels -- TRC_BNEP
09-22 06:42:27.879  5554  5577 I         : BTE_InitTraceLevels -- TRC_BTM
,09-22 06:42:27.880  5554  5577 I         : BTE_InitTraceLevels -- TRC_GAP
09-22 06:42:27.880  5554  5577 I         : BTE_InitTraceLevels -- TRC_PAN
,09-22 06:42:27.880  5554  5577 I         : BTE_InitTraceLevels -- TRC_SDP
,09-22 06:42:27.880  5554  5577 I         : BTE_InitTraceLevels -- TRC_GATT
09-22 06:42:27.880  5554  5577 I         : BTE_InitTraceLevels -- TRC_SMP
09-22 06:42:27.880  5554  5577 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-22 06:42:27.880  5554  5577 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-22 06:42:27.962  5554  5577 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3a69549
09-22 06:42:27.962  5554  5577 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3a69549 
,09-22 06:42:27.972  5554  5570 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-22 06:42:27.973  5554  5570 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-22 06:42:27.974  5554  5570 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-22 06:42:27.976  5554  5570 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 06:42:27.979  5554  5570 D BluetoothAdapterProperties: Scan Mode:20
09-22 06:42:27.979  5554  5570 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 06:42:27.979  5554  5570 D bt_hci  : do_postload posting postload work item
09-22 06:42:27.980  5554  5574 I bt_hci  : event_postload
09-22 06:42:27.980  5554  5574 I bt_vendor: sco_config_cb
,09-22 06:42:27.980  5554  5574 I bt_hci  : sco_config_callback postload finished.
,09-22 06:42:27.984  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:27.986  5554  5570 D bt_bte_conf: Device ID record 1 : primary
,09-22 06:42:27.986  5554  5570 D bt_bte_conf:   vendorId            = 000f
09-22 06:42:27.987  5554  5570 D bt_bte_conf:   vendorIdSource      = 0001
09-22 06:42:27.987  5554  5570 D bt_bte_conf:   product             = 1200
,09-22 06:42:27.987  5554  5570 D bt_bte_conf:   version             = 1436
09-22 06:42:27.987  5554  5570 D bt_bte_conf:   clientExecutableURL = 
,09-22 06:42:27.987  5554  5570 D bt_bte_conf:   serviceDescription  = 
09-22 06:42:27.987  5554  5570 D bt_bte_conf:   documentationURL    = 
09-22 06:42:27.987  5554  5570 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-22 06:42:27.987  5554  5574 I bt_vendor: low_power_mode_cb
09-22 06:42:27.987  5554  5567 D bt_stack_manager: event_start_up_stack finished
09-22 06:42:27.988  5554  5566 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-22 06:42:27.989  5554  5566 D BluetoothAdapterProperties: Setting state to 15
09-22 06:42:27.989  5554  5566 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-22 06:42:27.992  5554  5566 I BluetoothAdapterState: Entering BleOnState
,09-22 06:42:27.995  5554  5566 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-22 06:42:27.995  5554  5566 D BluetoothAdapterProperties: Setting state to 11
09-22 06:42:27.995  5554  5566 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-22 06:42:28.000  5554  5554 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
,09-22 06:42:28.001  5554  5554 D HeadsetService: Received start request. Starting profile...
,09-22 06:42:28.004  5554  5554 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-22 06:42:28.005  5554  5554 D HeadsetStateMachine: make
09-22 06:42:28.006  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:28.015  5554  5566 I BluetoothAdapterState: Entering PendingCommandState
,09-22 06:42:28.019  5554  5554 D HeadsetStateMachine: max_hf_connections = 1
09-22 06:42:28.019  5554  5554 I bt_bluedroid: get_profile_interface handsfree
,09-22 06:42:28.019  5554  5570 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-22 06:42:28.020  5554  5570 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-22 06:42:28.023  5554  5554 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
,09-22 06:42:28.024  5554  5554 D A2dpService: Received start request. Starting profile...
,09-22 06:42:28.025  5554  5554 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-22 06:42:28.025  5554  5554 I bt_bluedroid: get_profile_interface avrcp
,09-22 06:42:28.031  5554  5554 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-22 06:42:28.031  5554  5554 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-22 06:42:28.031  5554  5554 D A2dpStateMachine: make
09-22 06:42:28.032  5554  5554 I bt_bluedroid: get_profile_interface a2dp
,09-22 06:42:28.033  5554  5570 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-22 06:42:28.034  5554  5585 D A2dpStateMachine: Enter Disconnected: -2
,09-22 06:42:28.034  5554  5554 I BluetoothHidServiceJni: classInitNative: succeeds
09-22 06:42:28.035  5554  5554 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
,09-22 06:42:28.036  5554  5554 D HidService: Received start request. Starting profile...
09-22 06:42:28.036  5554  5554 I bt_bluedroid: get_profile_interface hidhost
09-22 06:42:28.036  5554  5554 D HidService: setHidService(): set to: null
09-22 06:42:28.036  5554  5570 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a4a56d
09-22 06:42:28.036  5554  5570 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-22 06:42:28.038  5554  5554 I BluetoothHealthServiceJni: classInitNative: succeeds
09-22 06:42:28.039  5554  5554 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
09-22 06:42:28.040  5554  5554 D HealthService: Received start request. Starting profile...
09-22 06:42:28.040  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 06:42:28.042  5554  5554 I bt_bluedroid: get_profile_interface health
,09-22 06:42:28.044  5554  5554 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-22 06:42:28.045  5554  5554 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
09-22 06:42:28.045  5554  5554 D PanService: Received start request. Starting profile...
09-22 06:42:28.046  5554  5554 D BluetoothPanServiceJni: initializeNative(L110): pan
09-22 06:42:28.046  5554  5554 I bt_bluedroid: get_profile_interface pan
09-22 06:42:28.046  5554  5570 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-22 06:42:28.048  5554  5554 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
09-22 06:42:28.048  5554  5554 D BluetoothMapService: Received start request. Starting profile...
09-22 06:42:28.048  5554  5554 D BluetoothMapService: start()
,09-22 06:42:28.051  5554  5554 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-22 06:42:28.052  5554  5554 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-22 06:42:28.052  5554  5554 D BluetoothMapAppObserver: createReceiver()
09-22 06:42:28.054  5554  5554 D BluetoothMapAppObserver: initObservers()
09-22 06:42:28.054  5554  5554 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-22 06:42:28.060  5554  5554 V SapService: SapBinder()
,09-22 06:42:28.060  5554  5554 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
,09-22 06:42:28.061  5554  5554 D SapService: Received start request. Starting profile...
,09-22 06:42:28.061  5554  5554 V SapService: start()
,09-22 06:42:28.064  5554  5554 V BluetoothAdapterState: isTurningOff()=false
,09-22 06:42:28.065  5554  5554 V BluetoothAdapterState: isTurningOn()=true
09-22 06:42:28.065  5554  5582 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-22 06:42:28.065  5554  5554 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:28.065  5554  5554 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:28.065  5554  5554 V BluetoothAdapterState: isTurningOff()=false
09-22 06:42:28.065  5554  5554 V BluetoothAdapterState: isTurningOn()=true
09-22 06:42:28.065  5554  5554 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:28.065  5554  5554 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:28.065  5554  5554 V BluetoothAdapterState: isTurningOff()=false
09-22 06:42:28.065  5554  5554 V BluetoothAdapterState: isTurningOn()=true
,09-22 06:42:28.065  5554  5554 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:28.066  5554  5554 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:28.066  5554  5554 V BluetoothAdapterState: isTurningOff()=false
09-22 06:42:28.066  5554  5554 V BluetoothAdapterState: isTurningOn()=true
09-22 06:42:28.066  5554  5554 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:28.066  5554  5554 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:28.067  5554  5554 V BluetoothAdapterState: isTurningOff()=false
09-22 06:42:28.067  5554  5554 V BluetoothAdapterState: isTurningOn()=true
,09-22 06:42:28.067  5554  5554 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:28.067  5554  5554 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:28.067  5554  5554 V BluetoothAdapterState: isTurningOff()=false
09-22 06:42:28.067  5554  5554 V BluetoothAdapterState: isTurningOn()=true
09-22 06:42:28.067  5554  5554 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:28.067  5554  5554 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 06:42:28.068  5554  5554 V BluetoothAdapterState: isTurningOff()=false
09-22 06:42:28.068  5554  5554 V BluetoothAdapterState: isTurningOn()=true
09-22 06:42:28.068  5554  5554 V BluetoothAdapterState: isBleTurningOn()=false
09-22 06:42:28.068  5554  5554 V BluetoothAdapterState: isBleTurningOff()=false
09-22 06:42:28.069  5554  5566 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-22 06:42:28.069  5554  5566 D BluetoothAdapterProperties: ScanMode =  20
09-22 06:42:28.069  5554  5566 D BluetoothAdapterProperties: State =  11
09-22 06:42:28.071  5554  5570 D BluetoothAdapterProperties: Scan Mode:21
,09-22 06:42:28.071  5554  5570 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-22 06:42:28.071  5554  5566 D BluetoothAdapterProperties: Setting state to 12
,09-22 06:42:28.071  5554  5566 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-22 06:42:28.072  3476  3686 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 06:42:28.072  5554  5566 I BluetoothAdapterState: Entering OnState
09-22 06:42:28.072  5405  5417 D BluetoothPan: onBluetoothStateChange on: true
09-22 06:42:28.074  5405  5418 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 06:42:28.075  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:28.075  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:28.075  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:28.075  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 06:42:28.075  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:28.075  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:28.075  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:28.075  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 06:42:28.076  5405  5405 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 06:42:28.076  5405  5405 D PanProfile: Bluetooth service connected
09-22 06:42:28.077  5405  5417 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-22 06:42:28.077   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-22 06:42:28.078   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 06:42:28.078  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 06:42:28.078  5405  5418 D BluetoothMap: onBluetoothStateChange: up=true
09-22 06:42:28.079   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 06:42:28.080  3052  3278 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 06:42:28.080  5554  5554 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 06:42:28.080  5554  5554 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-22 06:42:28.081  5405  5417 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 06:42:28.081  5554  5554 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 06:42:28.083   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 06:42:28.083  5554  5554 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 06:42:28.084  5405  5418 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-22 06:42:28.085  5554  5554 D ObexServerSockets: Succeed to create listening sockets 
,09-22 06:42:28.085  5554  5554 D ObexServerSockets0: startAccept()
09-22 06:42:28.085  5554  5554 D ObexServerSockets0: prepareForNewConnect()
09-22 06:42:28.086  3052  3063 D BluetoothPan: onBluetoothStateChange on: true
,09-22 06:42:28.087  5554  5554 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-22 06:42:28.088  5554  5554 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-22 06:42:28.088  3052  3052 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 06:42:28.088  5554  5591 D ObexServerSockets0: Accepting socket connection...
09-22 06:42:28.088  3052  3278 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 06:42:28.088  3052  3052 D PanProfile: Bluetooth service connected
09-22 06:42:28.088  5554  5592 D ObexServerSockets0: Accepting socket connection...
,09-22 06:42:28.089  5405  5405 D BluetoothInputDevice: Proxy object connected
,09-22 06:42:28.090  5405  5405 D HidProfile: Bluetooth service connected
09-22 06:42:28.091  3052  3052 D BluetoothInputDevice: Proxy object connected
09-22 06:42:28.091  3052  3052 D HidProfile: Bluetooth service connected
09-22 06:42:28.091  3052  3065 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-22 06:42:28.091   929   929 D BluetoothA2dp: Proxy object connected
09-22 06:42:28.092  3052  3278 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-22 06:42:28.093  5405  5405 D BluetoothMap: Proxy object connected
,09-22 06:42:28.093  5405  5405 D MapProfile: Bluetooth service connected
09-22 06:42:28.093  5405  5405 D BluetoothMap: getConnectedDevices()
09-22 06:42:28.095  3052  3065 D BluetoothMap: onBluetoothStateChange: up=true
09-22 06:42:28.095  3052  3052 D BluetoothA2dp: Proxy object connected
09-22 06:42:28.095  5405  5405 D BluetoothA2dp: Proxy object connected
,09-22 06:42:28.101  3052  3052 D BluetoothMap: Proxy object connected
,09-22 06:42:28.101  3052  3052 D MapProfile: Bluetooth service connected
09-22 06:42:28.101  3052  3052 D BluetoothMap: getConnectedDevices()
09-22 06:42:28.102   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-22 06:42:28.103  5554  5554 D BluetoothMapService: onReceive
09-22 06:42:28.103  5554  5554 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 06:42:28.103  5554  5554 D BluetoothMapService: STATE_ON
,09-22 06:42:28.104  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:28.106  5554  5595 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 06:42:28.108  5554  5595 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-22 06:42:28.108  5554  5595 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-22 06:42:28.110  5405  5405 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 06:42:28.116  3553  3553 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 06:42:28.116  5405  5405 D DockEventReceiver: finishStartingService: stopping service
,09-22 06:42:28.122  5405  5405 D BluetoothPbap: Proxy object connected
,09-22 06:42:28.122  5405  5405 D PbapServerProfile: Bluetooth service connected
,09-22 06:42:28.128  5554  5554 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 06:42:28.129  5554  5554 D ObexServerSockets0: prepareForNewConnect()
09-22 06:42:28.129  5554  5599 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 06:42:28.131  3052  3052 D BluetoothPbap: Proxy object connected
,09-22 06:42:28.131  3052  3052 D PbapServerProfile: Bluetooth service connected
,09-22 06:42:28.150  5554  5603 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 06:42:28.151  5554  5603 I BtOppRfcommListener: Accept thread started.
,09-22 06:42:28.174  5405  5417 D BluetoothHeadset: Proxy object connected
,09-22 06:42:28.174   929   929 D BluetoothHeadset: Proxy object connected
09-22 06:42:28.174   929   929 D BluetoothHeadset: Proxy object connected
09-22 06:42:28.174  3476  3504 D BluetoothHeadset: Proxy object connected
09-22 06:42:28.175  3052  3063 D BluetoothHeadset: Proxy object connected
09-22 06:42:28.175  3052  3052 D HeadsetProfile: Bluetooth service connected
09-22 06:42:28.175   929   929 D BluetoothHeadset: Proxy object connected
,09-22 06:42:28.176  5405  5405 D HeadsetProfile: Bluetooth service connected
,09-22 06:42:28.177  5405  5590 D BluetoothHeadset: Proxy object connected
,09-22 06:42:28.177   929   946 D BluetoothHeadset: Proxy object connected
09-22 06:42:28.177   929   946 D BluetoothHeadset: Proxy object connected
09-22 06:42:28.178  5405  5405 D HeadsetProfile: Bluetooth service connected
09-22 06:42:28.180   929   946 D BluetoothHeadset: Proxy object connected
,09-22 06:42:28.192  3052  3065 D BluetoothHeadset: Proxy object connected
09-22 06:42:28.192  3052  3052 D HeadsetProfile: Bluetooth service connected
,09-22 06:42:29.054  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:29.054  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:29.054  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:29.054  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 06:42:29.054  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:29.054  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:29.054  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:29.054  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 06:42:29.059  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 06:42:29.063  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 06:42:29.064  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fff71f2 added. We now have 8 listener(s)
09-22 06:42:29.064  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 06:42:29.069   929   940 D WifiService: setWifiEnabled: false pid=5353, uid=10077
,09-22 06:42:29.069   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 06:42:29.076  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:29.077   929  3347 D WifiService: setWifiEnabled: true pid=5353, uid=10077
09-22 06:42:29.077   929  3347 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 06:42:29.084   507   923 D SoftapController: Softap fwReload - Ok
,09-22 06:42:29.087   507   923 D CommandListener: Setting iface cfg
09-22 06:42:29.087   507   923 D CommandListener: Trying to bring down wlan0
,09-22 06:42:29.088   507   923 D CommandListener: Clearing all IP addresses on wlan0
,09-22 06:42:29.091   929  2897 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 06:42:29.709   929  2897 D wifi    : set interface wlan0 flags (UP)
,09-22 06:42:29.713   929  2897 I WifiHAL : Initializing wifi
09-22 06:42:29.714   929  2897 I WifiHAL : Creating socket
09-22 06:42:29.716   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-22 06:42:29.722   929  2897 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-22 06:42:29.723   929  2897 D wifi    : Did set static halHandle = 0x7f8bf3a000
09-22 06:42:29.723   929  2897 D wifi    : halHandle = 0x7f8bf3a000, mVM = 0x7fa854d140, mCls = 0x1017ce
09-22 06:42:29.723   929  2897 D wifi    : array field set
09-22 06:42:29.723   929  2897 I WifiNative-HAL: interface[0] = wlan0
,09-22 06:42:29.725   929  5608 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547808845824
09-22 06:42:29.725   929  5608 D wifi    : waitForHalEvents called, vm = 0x7fa854d140, obj = 0x1017ce, env = 0x7f8d15e800
,09-22 06:42:29.779  5609  5609 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-22 06:42:29.799  5609  5609 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 06:42:29.808  5609  5609 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 06:42:29.808  5609  5609 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-22 06:42:29.829   929  2897 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-22 06:42:29.831  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:42:29.839   929  2897 D WifiConfigStore: Loading config and enabling all networks 
,09-22 06:42:29.843  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:29.843  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:29.843  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:29.843  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:29.843  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:29.843  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:29.843  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:29.843  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 06:42:29.845  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 06:42:29.850   929  2897 D WifiConfigStore: loaded 0 passpoint configs
,09-22 06:42:29.850   929  2897 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-22 06:42:29.850   929  2897 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-22 06:42:29.851   929  2897 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-22 06:42:29.852   929  2897 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-22 06:42:29.852   929  2897 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-22 06:42:29.852   929  2897 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-22 06:42:29.852   929  2897 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-22 06:42:29.856  4216  4216 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 06:42:29.856   929  2897 D WifiNative-HAL: Setting external_sim to 1
09-22 06:42:29.857   929  2897 D wifi    : setting dfs flag to true, 0x7f8debfee0
09-22 06:42:29.857   929  2897 D WifiStateMachine: Setting OUI to DA-A1-19
09-22 06:42:29.857   929  2897 D wifi    : setting scan oui 0x7f8debfee0
09-22 06:42:29.857   929  2897 D WifiHAL : Sending mac address OUI
,09-22 06:42:29.862   929  2897 E native  : do suspend false
,09-22 06:42:29.868   929  2897 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-22 06:42:29.868   929   929 D RttService: SCAN_AVAILABLE : 3
09-22 06:42:29.869   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-22 06:42:29.869   929  3004 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-22 06:42:29.870   507   923 D CommandListener: Setting iface cfg
,09-22 06:42:29.873   929  2896 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
09-22 06:42:29.873   929  2896 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-22 06:42:29.883   929  2896 D WifiNative-HAL: p2pGetDeviceAddress
,09-22 06:42:29.887   929  2896 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-22 06:42:29.887   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=199625 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-22 06:42:30.094  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 06:42:30.094  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:30.094  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:30.094  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:30.094  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:30.094  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:30.094  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:30.094  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 06:42:30.100  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 06:42:30.111  5353  5399 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-22 06:42:30.111  5353  5399 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-22 06:42:30.114  5353  5399 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8f49085 Bundle[{}]
09-22 06:42:30.114  5353  5399 I io.jxcore.node.LifeCycleMonitor: start: OK
09-22 06:42:30.114  5353  5399 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-22 06:42:30.115  5353  5399 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-22 06:42:30.116  5353  5399 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-22 06:42:30.116  5353  5399 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-22 06:42:30.117  5353  5399 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-22 06:42:30.123  5353  5399 I System.out: Running OutgoingSocketThread
,09-22 06:42:30.125  5353  5611 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 152)
,09-22 06:42:30.126  5353  5611 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46781
09-22 06:42:30.127  5353  5611 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-22 06:42:31.127  5353  5399 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 153)
,09-22 06:42:31.127  5353  5399 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 153)
09-22 06:42:31.132  5353  5399 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,09-22 06:42:31.136  5353  5399 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-22 06:42:31.137  5353  5399 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 159)
,09-22 06:42:31.143  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 06:42:31.144  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a77043 added. We now have 2 listener(s)
,09-22 06:42:31.146  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 06:42:31.147  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-22 06:42:31.147  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 06:42:31.147  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:42:31.147  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5166c0 added. We now have 9 listener(s)
09-22 06:42:31.147  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:31.149  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 06:42:31.153  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 06:42:31.158  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:42:31.158  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:31.158  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:31.158  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:31.158  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:31.158  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:31.158  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:31.158  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 06:42:31.163  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 06:42:31.163  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:42:31.163  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 06:42:31.164  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78ebb3e added. We now have 3 listener(s)
09-22 06:42:31.165  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:31.165  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 06:42:31.165  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 06:42:31.165  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 06:42:31.165  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:42:31.165  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c6cd9f added. We now have 10 listener(s)
09-22 06:42:31.165  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:31.165  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:31.166  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:31.166  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:31.166  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-22 06:42:31.166  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.166  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:42:31.166  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 06:42:31.166  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a77043 removed from the list
09-22 06:42:31.166  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:31.166  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:31.166  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5166c0 removed from the list
09-22 06:42:31.166  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:31.166  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:31.167  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.167  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 06:42:31.168  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:31.168  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:31.168  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:31.168  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5166c0 not in the list
09-22 06:42:31.168  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.168  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 06:42:31.170  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 06:42:31.170  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:31.170  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:31.170  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c6cd9f removed from the list
09-22 06:42:31.170  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:31.170  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.170  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:31.170  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 06:42:31.170  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78ebb3e removed from the list
09-22 06:42:31.171  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 06:42:31.171  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3462eec added. We now have 2 listener(s)
,09-22 06:42:31.172  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 06:42:31.173  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 06:42:31.173  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 06:42:31.173  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:42:31.173  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db612b5 added. We now have 9 listener(s)
09-22 06:42:31.173  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:31.173  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 06:42:31.176  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 06:42:31.179  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:42:31.179  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:31.179  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:31.179  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:31.179  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:31.179  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:31.179  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:31.179  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 06:42:31.181  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 06:42:31.181  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-22 06:42:31.182  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 06:42:31.182  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b54a4bb added. We now have 3 listener(s)
09-22 06:42:31.183  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:31.183  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 06:42:31.183  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 06:42:31.183  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 06:42:31.183  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 06:42:31.183  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd4dd8 added. We now have 10 listener(s)
09-22 06:42:31.184  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:31.184  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 06:42:31.184  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 06:42:31.184  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 06:42:31.184  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:42:31.184  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 06:42:31.184  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:31.188  5353  5399 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 06:42:31.188  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 06:42:31.191  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 06:42:31.192  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 06:42:31.192  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 06:42:31.195  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 06:42:31.195  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 06:42:31.195  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 06:42:31.195  5353  5399 D BluetoothAdapter: STATE_ON
09-22 06:42:31.198  5554  5583 D BtGatt.GattService: registerClient() - UUID=b4002927-ed65-46e3-abe0-bb7335924148
09-22 06:42:31.198  5554  5570 D BtGatt.GattService: onClientRegistered() - UUID=b4002927-ed65-46e3-abe0-bb7335924148, clientIf=5
09-22 06:42:31.199  5353  5364 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 06:42:31.200  5554  5565 D BtGatt.GattService: start scan with filters
,09-22 06:42:31.203  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 06:42:31.203  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 06:42:31.203  5554  5573 D BtGatt.ScanManager: handling starting scan
,09-22 06:42:31.203  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 06:42:31.203  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 06:42:31.204  5554  5573 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c90b3ce
09-22 06:42:31.205  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:42:31.206  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 06:42:31.206  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:42:31.207  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 06:42:31.209  5353  5399 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 06:42:31.209  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:31.209  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 06:42:31.209  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 06:42:31.209  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 06:42:31.209  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 06:42:31.210  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 06:42:31.210  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 06:42:31.210  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 06:42:31.210  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 06:42:31.210  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 06:42:31.210  5554  5570 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-22 06:42:31.210  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.211  5554  5573 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 06:42:31.212  5353  5399 D BluetoothAdapter: STATE_ON
,09-22 06:42:31.213  5554  5583 D BtGatt.GattService: stopScan() - queue size =1
09-22 06:42:31.213  5554  5565 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-22 06:42:31.216  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 06:42:31.216  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 06:42:31.216  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 06:42:31.216  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 06:42:31.216  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 06:42:31.217  5554  5570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 06:42:31.217  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.217  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 06:42:31.217  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 06:42:31.217  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 06:42:31.217  5554  5573 D BtGatt.ScanManager: Starting BLE batch scan
09-22 06:42:31.217  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 06:42:31.217  5554  5573 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 06:42:31.218  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 06:42:31.220  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:42:31.220  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:42:31.220  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 06:42:31.222  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:31.222  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:31.222  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:31.222  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:31.222  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 06:42:31.222  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:42:31.223  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 06:42:31.223  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3462eec removed from the list
09-22 06:42:31.223  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:31.223  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db612b5 removed from the list
09-22 06:42:31.223  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:31.223  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:31.223  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.223  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:31.224  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:31.224  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:31.224  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 06:42:31.224  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db612b5 not in the list
09-22 06:42:31.225  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.225  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:31.227  5554  5570 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 06:42:31.227  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:31.227  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:31.227  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.227  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:31.227  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd4dd8 removed from the list
09-22 06:42:31.227  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:31.227  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.227  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:31.228  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 06:42:31.228  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b54a4bb removed from the list
,09-22 06:42:31.228  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 06:42:31.228  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c56f84 added. We now have 2 listener(s)
09-22 06:42:31.230  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 06:42:31.230  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 06:42:31.230  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 06:42:31.230  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:42:31.230  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d22e36d added. We now have 9 listener(s)
09-22 06:42:31.230  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:31.231  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 06:42:31.235  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 06:42:31.235  5554  5570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 06:42:31.235  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 06:42:31.238  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:42:31.238  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:31.238  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:31.238  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:31.238  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:31.238  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:31.238  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:31.238  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 06:42:31.239  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 06:42:31.239  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:42:31.240  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 06:42:31.240  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f4f033 added. We now have 3 listener(s)
09-22 06:42:31.241  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 06:42:31.241  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:31.241  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 06:42:31.241  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 06:42:31.241  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:42:31.241  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bebfff0 added. We now have 10 listener(s)
09-22 06:42:31.241  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:31.241  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 06:42:31.242  5554  5570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 06:42:31.242  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.242  5554  5573 D BtGatt.ScanManager: stopping BLe Batch
09-22 06:42:31.242  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 06:42:31.242  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 06:42:31.242  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-22 06:42:31.242  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:42:31.242  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 06:42:31.242  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:31.246  5353  5399 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 06:42:31.246  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 06:42:31.248  5554  5570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 06:42:31.248  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.248  5554  5573 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-22 06:42:31.249  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 06:42:31.250  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-22 06:42:31.250  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 06:42:31.253  5554  5570 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 06:42:31.253  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 06:42:31.255  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 06:42:31.255  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 06:42:31.255  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 06:42:31.256  5353  5399 D BluetoothAdapter: STATE_ON
,09-22 06:42:31.258  5554  5583 D BtGatt.GattService: registerClient() - UUID=18673674-ad66-482e-b5d3-336926bbe6f8
,09-22 06:42:31.259  5554  5570 D BtGatt.GattService: onClientRegistered() - UUID=18673674-ad66-482e-b5d3-336926bbe6f8, clientIf=5
09-22 06:42:31.259  5353  5364 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 06:42:31.259  5554  5565 D BtGatt.GattService: start scan with filters
,09-22 06:42:31.261  5554  5573 D BtGatt.ScanManager: handling starting scan
09-22 06:42:31.261  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 06:42:31.261  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 06:42:31.261  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-22 06:42:31.261  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 06:42:31.264  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 06:42:31.264  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 06:42:31.264  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:42:31.265  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-22 06:42:31.267  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-22 06:42:31.268  5353  5399 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-22 06:42:31.268  5554  5570 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 06:42:31.268  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.268  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:31.268  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:31.268  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:31.268  5554  5573 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-22 06:42:31.268  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:31.268  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.268  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 06:42:31.268  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 06:42:31.268  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c56f84 removed from the list
09-22 06:42:31.268  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:31.268  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d22e36d removed from the list
,09-22 06:42:31.268  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
,09-22 06:42:31.268  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:42:31.269  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.269  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-22 06:42:31.269  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.269  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:42:31.270  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:31.270  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:31.270  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:31.270  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d22e36d not in the list
09-22 06:42:31.270  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 06:42:31.270  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 06:42:31.270  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 06:42:31.270  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-22 06:42:31.270  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 06:42:31.271  5353  5399 D BluetoothAdapter: STATE_ON
09-22 06:42:31.272  5554  5594 D BtGatt.GattService: stopScan() - queue size =1
09-22 06:42:31.272  5554  5593 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 06:42:31.272  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 06:42:31.272  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 06:42:31.272  5554  5570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 06:42:31.273  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 06:42:31.273  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.273  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 06:42:31.273  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 06:42:31.273  5554  5573 D BtGatt.ScanManager: Starting BLE batch scan
09-22 06:42:31.273  5554  5573 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 06:42:31.274  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 06:42:31.274  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 06:42:31.274  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 06:42:31.274  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 06:42:31.274  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:31.276  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:31.276  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:31.276  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:31.276  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:42:31.277  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bebfff0 removed from the list
09-22 06:42:31.277  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:31.277  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:42:31.277  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.277  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 06:42:31.277  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:31.277  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 06:42:31.277  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f4f033 removed from the list
09-22 06:42:31.278  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 06:42:31.278  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a92b1c added. We now have 2 listener(s)
09-22 06:42:31.279  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 06:42:31.279  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 06:42:31.279  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 06:42:31.279  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:42:31.279  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad21325 added. We now have 9 listener(s)
09-22 06:42:31.279  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:31.280  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 06:42:31.283  5554  5570 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 06:42:31.283  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.284  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:42:31.288  5554  5570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 06:42:31.288  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.288  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:42:31.288  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:31.288  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:31.288  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:31.288  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:31.288  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:31.288  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:31.288  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 06:42:31.289  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 06:42:31.289  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:42:31.289  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 06:42:31.290  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af432ab added. We now have 3 listener(s)
09-22 06:42:31.291  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:31.291  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 06:42:31.291  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 06:42:31.291  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 06:42:31.291  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:42:31.291  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cabdd08 added. We now have 10 listener(s)
09-22 06:42:31.291  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:31.291  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 06:42:31.291  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 06:42:31.291  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 06:42:31.291  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:42:31.291  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 06:42:31.292  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:31.294  5554  5570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 06:42:31.294  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 06:42:31.294  5554  5573 D BtGatt.ScanManager: stopping BLe Batch
09-22 06:42:31.295  5353  5399 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 06:42:31.295  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 06:42:31.299  5554  5570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 06:42:31.299  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.299  5554  5573 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-22 06:42:31.303  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 06:42:31.303  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-22 06:42:31.303  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 06:42:31.304  5554  5570 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 06:42:31.304  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 06:42:31.307  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 06:42:31.307  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 06:42:31.307  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-22 06:42:31.307  5353  5399 D BluetoothAdapter: STATE_ON
09-22 06:42:31.309  5554  5593 D BtGatt.GattService: registerClient() - UUID=b2a62d71-e87a-4a9f-9e5d-651c2a0102f5
09-22 06:42:31.310  5554  5570 D BtGatt.GattService: onClientRegistered() - UUID=b2a62d71-e87a-4a9f-9e5d-651c2a0102f5, clientIf=5
,09-22 06:42:31.310  5353  5445 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 06:42:31.310  5554  5564 D BtGatt.GattService: start scan with filters
09-22 06:42:31.312  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 06:42:31.312  5554  5573 D BtGatt.ScanManager: handling starting scan
,09-22 06:42:31.312  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-22 06:42:31.312  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 06:42:31.312  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 06:42:31.314  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:42:31.314  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 06:42:31.314  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:42:31.315  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 06:42:31.316  5554  5570 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 06:42:31.317  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.317  5554  5573 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 06:42:31.318  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:31.318  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:31.319  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:42:31.319  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:31.319  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 06:42:31.319  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 06:42:31.319  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 06:42:31.319  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a92b1c removed from the list
09-22 06:42:31.319  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:31.319  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad21325 removed from the list
09-22 06:42:31.319  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:31.319  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 06:42:31.320  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.320  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-22 06:42:31.320  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.320  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:42:31.320  5554  5570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 06:42:31.320  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.320  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:31.321  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:31.321  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:31.321  5554  5573 D BtGatt.ScanManager: Starting BLE batch scan
09-22 06:42:31.321  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad21325 not in the list
09-22 06:42:31.321  5554  5573 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 06:42:31.321  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 06:42:31.321  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 06:42:31.321  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 06:42:31.321  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 06:42:31.321  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 06:42:31.321  5353  5399 D BluetoothAdapter: STATE_ON
,09-22 06:42:31.322  5554  5583 D BtGatt.GattService: stopScan() - queue size =1
09-22 06:42:31.322  5554  5593 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 06:42:31.323  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 06:42:31.323  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 06:42:31.323  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 06:42:31.323  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 06:42:31.323  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-22 06:42:31.324  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 06:42:31.325  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 06:42:31.325  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 06:42:31.325  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 06:42:31.325  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:31.326  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:31.326  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:31.326  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:31.326  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cabdd08 removed from the list
09-22 06:42:31.326  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:31.326  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.326  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:42:31.326  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:31.326  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 06:42:31.326  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:42:31.326  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af432ab removed from the list
,09-22 06:42:31.326  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 06:42:31.327  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 06:42:31.327  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea5c1b4 added. We now have 2 listener(s)
09-22 06:42:31.328  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 06:42:31.328  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 06:42:31.328  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 06:42:31.328  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:42:31.328  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d081dd added. We now have 9 listener(s)
09-22 06:42:31.328  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:31.329  5554  5570 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 06:42:31.329  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 06:42:31.329  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 06:42:31.331  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 06:42:31.334  5554  5570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-22 06:42:31.334  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.334  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:42:31.334  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:42:31.334  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:42:31.334  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:42:31.334  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:42:31.334  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 06:42:31.334  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 06:42:31.334  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 06:42:31.336  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 06:42:31.336  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:42:31.336  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 06:42:31.337  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a4c23 added. We now have 3 listener(s)
09-22 06:42:31.337  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:31.338  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 06:42:31.338  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 06:42:31.338  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 06:42:31.338  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:42:31.338  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb74520 added. We now have 10 listener(s)
09-22 06:42:31.338  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:42:31.338  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:42:31.338  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:31.338  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-22 06:42:31.338  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:31.338  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.338  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:42:31.338  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 06:42:31.338  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:42:31.339  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea5c1b4 removed from the list
09-22 06:42:31.339  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:31.339  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d081dd removed from the list
09-22 06:42:31.339  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:42:31.339  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:31.339  5554  5570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-22 06:42:31.339  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.339  5554  5573 D BtGatt.ScanManager: stopping BLe Batch
,09-22 06:42:31.340  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.340  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:31.340  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:31.340  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 06:42:31.340  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:31.341  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d081dd not in the list
09-22 06:42:31.341  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.341  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 06:42:31.341  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:42:31.341  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:42:31.341  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:42:31.342  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb74520 removed from the list
09-22 06:42:31.342  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:42:31.342  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:42:31.342  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 06:42:31.342  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 06:42:31.342  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a4c23 removed from the list
09-22 06:42:31.343  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-22 06:42:31.343  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-22 06:42:31.343  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-22 06:42:31.343  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 06:42:31.343  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-22 06:42:31.343  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 06:42:31.344  5554  5570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 06:42:31.344  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:42:31.344  5554  5573 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 06:42:31.347  5353  5612 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: My test thread name)
09-22 06:42:31.347  5353  5612 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: My test thread name)
09-22 06:42:31.347  5353  5612 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-22 06:42:31.348  5554  5570 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 06:42:31.348  5554  5570 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 06:42:31.349  5353  5613 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name)
09-22 06:42:31.349  5353  5613 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: My test thread name)
09-22 06:42:31.349  5353  5613 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-22 06:42:31.351  5353  5399 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-22 06:42:31.351  5353  5399 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-22 06:42:31.351  5353  5399 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-22 06:42:31.351  5353  5399 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-22 06:42:31.351  5353  5399 D com.test.thalitest.ThaliTestRunner: Total duration: 22556 ms
,09-22 06:42:31.353  5353  5399 I jxcore-log: *Native tests were executed*
09-22 06:42:31.353  5353  5399 I jxcore-log: 
09-22 06:42:31.353  5353  5399 I jxcore-log: Total number of executed tests:  80
09-22 06:42:31.353  5353  5399 I jxcore-log: 
09-22 06:42:31.353  5353  5399 I jxcore-log: Number of passed tests:  80
09-22 06:42:31.353  5353  5399 I jxcore-log: 
09-22 06:42:31.354  5353  5399 I jxcore-log: Number of failed tests:  0
09-22 06:42:31.354  5353  5399 I jxcore-log: 
,09-22 06:42:31.354  5353  5399 I jxcore-log: Number of ignored tests:  0
09-22 06:42:31.354  5353  5399 I jxcore-log: 
,09-22 06:42:31.355  5353  5399 I jxcore-log: Total duration:  22556
09-22 06:42:31.355  5353  5399 I jxcore-log: 
,09-22 06:42:31.355  5353  5399 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-22 06:42:31.355  5353  5399 I jxcore-log: 
,09-22 06:42:31.358  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 06:42:31.358  5353  5399 I jxcore-log: 
09-22 06:42:31.361  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 06:42:31.361  5353  5399 I jxcore-log: 
09-22 06:42:31.362  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 06:42:31.362  5353  5399 I jxcore-log: 
09-22 06:42:31.364  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 06:42:31.364  5353  5399 I jxcore-log: 
09-22 06:42:31.364  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 06:42:31.364  5353  5399 I jxcore-log: 
09-22 06:42:31.365  5353  5353 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-22 06:42:31.366  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 06:42:31.366  5353  5399 I jxcore-log: 
09-22 06:42:31.368  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 06:42:31.368  5353  5399 I jxcore-log: 
09-22 06:42:31.370  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 06:42:31.370  5353  5399 I jxcore-log: 
09-22 06:42:31.371  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 06:42:31.371  5353  5399 I jxcore-log: 
09-22 06:42:31.372  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 06:42:31.372  5353  5399 I jxcore-log: 
09-22 06:42:31.373  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 06:42:31.373  5353  5399 I jxcore-log: 
09-22 06:42:31.374  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 06:42:31.374  5353  5399 I jxcore-log: 
09-22 06:42:31.375  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 06:42:31.375  5353  5399 I jxcore-log: 
09-22 06:42:31.375  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 06:42:31.375  5353  5399 I jxcore-log: 
09-22 06:42:31.376  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 06:42:31.376  5353  5399 I jxcore-log: 
09-22 06:42:31.377  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 06:42:31.377  5353  5399 I jxcore-log: 
,09-22 06:42:31.377  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 06:42:31.377  5353  5399 I jxcore-log: 
,09-22 06:42:31.378  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 06:42:31.378  5353  5399 I jxcore-log: 
09-22 06:42:31.379  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 06:42:31.379  5353  5399 I jxcore-log: 
,09-22 06:42:31.379  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 06:42:31.379  5353  5399 I jxcore-log: 
09-22 06:42:31.380  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 06:42:31.380  5353  5399 I jxcore-log: 
09-22 06:42:31.381  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 06:42:31.381  5353  5399 I jxcore-log: 
09-22 06:42:31.381  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 06:42:31.381  5353  5399 I jxcore-log: 
09-22 06:42:31.382  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 06:42:31.382  5353  5399 I jxcore-log: 
09-22 06:42:31.383  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 06:42:31.383  5353  5399 I jxcore-log: 
09-22 06:42:31.383  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 06:42:31.383  5353  5399 I jxcore-log: 
09-22 06:42:31.384  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 06:42:31.384  5353  5399 I jxcore-log: 
,09-22 06:42:31.385  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 06:42:31.385  5353  5399 I jxcore-log: 
,09-22 06:42:31.385  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 06:42:31.385  5353  5399 I jxcore-log: 
,09-22 06:42:31.720  5353  5353 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 06:42:31.724  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 06:42:31.724  5353  5399 I jxcore-log: 
,09-22 06:42:31.777  5353  5353 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 06:42:31.781  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 06:42:31.781  5353  5399 I jxcore-log: 
,09-22 06:42:31.794  5614  5614 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-22 06:42:31.800  5614  5614 D AndroidRuntime: CheckJNI is OFF
,09-22 06:42:31.827  5353  5353 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 06:42:31.830  5614  5614 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-22 06:42:31.830  5353  5399 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 06:42:31.830  5353  5399 I jxcore-log: 
,09-22 06:42:31.863  5614  5614 I Radio-JNI: register_android_hardware_Radio DONE
,09-22 06:42:31.879  5614  5614 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-22 06:42:31.888   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-22 06:42:31.888   929   942 I ActivityManager: Killing 5353:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-22 06:42:31.960   929   940 D GraphicsStats: Buffer count: 2
09-22 06:42:31.960   929   939 I WindowState: WIN DEATH: Window{1048bc7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-22 06:42:31.961   929  2898 D WifiService: Client connection lost with reason: 4
,09-22 06:42:32.016   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-22 06:42:32.017   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-22 06:42:32.017   929   952 I art     : Starting a blocking GC Explicit
,09-22 06:42:32.018   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-22 06:42:32.018   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-22 06:42:32.018   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:42:32.018   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:42:32.018   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 06:42:32.018   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-22 06:42:32.018   929   942 I ActivityManager:   Force finishing activity ActivityRecord{b869ae8 u0 com.test.thalitest/.MainActivity t2}
,09-22 06:42:32.026   929  3044 W ActivityManager: Spurious death for ProcessRecord{b2336c4 0:com.test.thalitest/u0a77}, curProc for 5353: null
,09-22 06:42:32.030   929   947 W WindowManager: Attempted to add application window with unknown token Token{2f2d501 ActivityRecord{b869ae8 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-22 06:42:32.031   929   947 W WindowManager: Token{2f2d501 ActivityRecord{b869ae8 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{2f2d501 ActivityRecord{b869ae8 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-22 06:42:32.031   929   947 W WindowManager: view not successfully added to wm, removing view
09-22 06:42:32.031   929   947 W WindowManager: Exception when adding starting window
09-22 06:42:32.031   929   947 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{3b300cf V.E...... R.....ID 0,0-0,0} not attached to window manager
09-22 06:42:32.031   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-22 06:42:32.031   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-22 06:42:32.031   929   947 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-22 06:42:32.031   929   947 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-22 06:42:32.031   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-22 06:42:32.031   929   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:42:32.031   929   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:42:32.031   929   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 06:42:32.031   929   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-22 06:42:32.095   929   952 I art     : Explicit concurrent mark sweep GC freed 24534(1556KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.516ms total 77.583ms
,09-22 06:42:32.115   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-22 06:42:32.117  5614  5614 I art     : System.exit called, status: 0
,09-22 06:42:32.117  5614  5614 I AndroidRuntime: VM exiting with result code 0.
,09-22 06:42:32.121   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-22 06:42:32.128   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-22 06:42:32.131  5554  5554 D BluetoothMapAppObserver: onReceive
09-22 06:42:32.132  5554  5554 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-22 06:42:32.140  3412  3890 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-22 06:42:32.143   929  2889 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-22 06:42:32.145  3348  3348 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-22 06:42:32.163  3313  5626 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-22 06:42:32.167  3348  5625 I Keyboard.Facilitator.DecoderInitializer: run()
,09-22 06:42:32.177  3348  5625 I Decoder : createOrResetDecoder
,09-22 06:42:32.186  3476  3476 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-22 06:42:32.207  3553  3553 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-22 06:42:32.207  3553  3553 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-22 06:42:32.207   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-22 06:42:32.210    28    28 W kworker/2:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 06:42:32.213    28    28 W kworker/2:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 06:42:32.223  3512  3620 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-22 06:42:32.224  3848  5631 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-22 06:42:32.226  3848  5631 D AccountUtils: Clearing selected account for com.test.thalitest
,09-22 06:42:32.230    28    28 W kworker/2:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 06:42:32.237   929  3480 I ActivityManager: Start proc 5633:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-22 06:42:32.238  3512  3620 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-22 06:42:32.238  3512  3620 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3512
09-22 06:42:32.238  3512  3620 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-22 06:42:32.238  3512  3620 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-22 06:42:32.238  3512  3620 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-22 06:42:32.238  3512  3620 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-22 06:42:32.238  3512  3620 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-22 06:42:32.238  3512  3620 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-22 06:42:32.238  3512  3620 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-22 06:42:32.238  3512  3620 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-22 06:42:32.238  3512  3620 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-22 06:42:32.238  3512  3620 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-22 06:42:32.238  3512  3620 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:42:32.238  3512  3620 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-22 06:42:32.241  3553  3553 I ConfigService: onCreate
,09-22 06:42:32.244   929  3347 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-22 06:42:32.247   929  5642 E DropBoxManagerService: Can't write: system_app_crash
09-22 06:42:32.247   929  5642 E DropBoxManagerService: java.io.IOException: write failed: EROFS (Read-only file system)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:498)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: 	at java.io.FilterOutputStream.close(FilterOutputStream.java:61)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: 	at java.io.BufferedOutputStream.close(BufferedOutputStream.java:152)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:230)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: 	at libcore.io.Posix.writeBytes(Native Method)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: 	at libcore.io.Posix.write(Posix.java:271)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:493)
09-22 06:42:32.247   929  5642 E DropBoxManagerService: 	... 8 more
,09-22 06:42:32.249  3512  3620 I Process : Sending signal. PID: 3512 SIG: 9
,09-22 06:42:32.275  3348  5625 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-22 06:42:32.291  3848  5631 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-22 06:42:32.310  3848  5631 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:42:32.310  3848  5631 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:42:32.310  3848  5631 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 06:42:32.311  3848  5631 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-22 06:42:32.370   929  3080 I WindowState: WIN DEATH: Window{f0e95d0 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-22 06:42:32.370   929  3908 D GraphicsStats: Buffer count: 1
,09-22 06:42:32.376   929  3488 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3512) has died
,09-22 06:42:32.376   929  3488 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-22 06:42:32.391  3848  5652 I GMPM-SVC: App measurement is starting up
,09-22 06:42:32.395  3848  5652 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-22 06:42:32.396  3848  5652 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-22 06:42:32.600   384   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
