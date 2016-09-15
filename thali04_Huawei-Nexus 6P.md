#### Test 83276082d331142_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
,09-15 07:31:50.946   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 07:31:50.946   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-15 07:31:51.414  5513  5513 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-15 07:31:51.420  5513  5513 D AndroidRuntime: CheckJNI is OFF
09-15 07:31:51.448  5513  5513 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-15 07:31:51.485  5513  5513 I Radio-JNI: register_android_hardware_Radio DONE
09-15 07:31:51.502  5513  5513 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-15 07:31:51.508   925  3499 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-15 07:31:51.550   925  3499 I ActivityManager: Start proc 5522:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-15 07:31:51.555  5513  5513 D AndroidRuntime: Shutting down VM
09-15 07:31:51.643  5522  5522 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-15 07:31:51.672  5522  5522 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-15 07:31:51.697  5522  5522 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 345-364)
09-15 07:31:51.697  5522  5522 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 07:31:51.715  5522  5522 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b2a00b6}
09-15 07:31:51.716  5522  5522 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 07:31:51.716  5522  5522 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-15 07:31:51.721  5522  5522 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-15 07:31:51.722  5522  5522 E SysUtils: ApplicationContext is null in ApplicationStatus
09-15 07:31:51.755  5522  5522 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-15 07:31:51.768  5522  5522 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 07:31:51.769  5522  5522 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-15 07:31:51.769  5522  5522 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-15 07:31:51.769  5522  5522 I Adreno  : Build Date                       : 12/06/15
09-15 07:31:51.769  5522  5522 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-15 07:31:51.769  5522  5522 I Adreno  : Local Branch                     : mybranch17112971
09-15 07:31:51.769  5522  5522 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-15 07:31:51.769  5522  5522 I Adreno  : Remote Branch                    : NONE
09-15 07:31:51.769  5522  5522 I Adreno  : Reconstruct Branch               : NOTHING
,09-15 07:31:51.819   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@69ee75d:true
,09-15 07:31:51.849  2487  2487 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30989]" dev="sockfs" ino=30989 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 07:31:51.849  2487  2487 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30989]" dev="sockfs" ino=30989 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 07:31:51.864  5522  5522 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-15 07:31:51.873  5522  5522 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-15 07:31:51.893  2487  2487 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33168]" dev="sockfs" ino=33168 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 07:31:51.898  5522  5559 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-15 07:31:51.893  2487  2487 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33168]" dev="sockfs" ino=33168 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 07:31:51.896  3500  3500 W Binder_7: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[19999]" dev="sockfs" ino=19999 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 07:31:51.896  3500  3500 W Binder_7: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[19999]" dev="sockfs" ino=19999 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-15 07:31:51.904  5522  5546 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-15 07:31:51.942  5522  5559 I OpenGLRenderer: Initialized EGL, version 1.4
,09-15 07:31:52.015   925   943 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +426ms (total +491ms)
,09-15 07:31:52.039  5522  5522 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5522
,09-15 07:31:52.127  5522  5522 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-15 07:31:52.267  5522  5562 D jxcore_app_log: JniHelper::setJavaVM(0xf533c000), pthread_self() = -567277264
,09-15 07:31:52.271  5522  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-15 07:31:52.271  5522  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-15 07:31:52.271  5522  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-15 07:31:52.271  5522  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-15 07:31:52.271  5522  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-15 07:31:52.271  5522  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@820d46f added. We now have 1 listener(s)
,09-15 07:31:52.274  5522  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-15 07:31:52.275  5522  5562 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 07:31:52.275  5522  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:31:52.275  5522  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-15 07:31:52.277  5522  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6ede5a added. We now have 1 listener(s)
,09-15 07:31:52.278  5522  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 07:31:52.284   925  3042 D WifiService: New client listening to asynchronous messages
09-15 07:31:52.284  5522  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 07:31:52.284  5522  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-15 07:31:52.284  5522  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-15 07:31:52.284  5522  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-15 07:31:52.284  5522  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2,
,09-15 07:31:52.286  5522  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:31:52.287  5522  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
09-15 07:31:52.294  5522  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-15 07:31:52.294  5522  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:31:52.294  5522  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:31:52.294  5522  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:31:52.294  5522  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:31:52.294  5522  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:31:52.294  5522  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:31:52.294  5522  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:31:52.294  5522  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 07:31:52.294  5522  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-15 07:31:52.294  5522  5562 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:31:52.294  5522  5562 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-15 07:31:52.298  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:31:52.300  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:31:52.310  5522  5522 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-15 07:31:52.598  5522  5568 W jxcore-log: Initializing JXcore engine
,09-15 07:31:52.598  5522  5568 W jxcore-log: JXcore engine is ready
,09-15 07:31:52.626  5568  5568 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12111 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-15 07:31:52.626  5568  5568 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[17441]" dev="sockfs" ino=17441 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-15 07:31:52.626  5568  5568 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-15 07:31:52.626  5568  5568 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[30537]" dev="sockfs" ino=30537 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-15 07:31:52.638  5522  5568 W jxcore-log: Starting JXcore engine
,09-15 07:31:52.690  5522  5568 W jxcore-log: Platform android
09-15 07:31:52.690  5522  5568 W jxcore-log: 
09-15 07:31:52.690  5522  5568 W jxcore-log: Process ARCH arm
09-15 07:31:52.690  5522  5568 W jxcore-log: 
,09-15 07:31:52.785  5522  5568 I jxcore-log: JXcore Cordova bridge is ready!
09-15 07:31:52.785  5522  5568 I jxcore-log: 
,09-15 07:31:52.785  5522  5568 W jxcore-log: JXcore engine is started
,09-15 07:31:52.792  5522  5562 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-15 07:31:52.795  5522  5522 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-15 07:31:59.414  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-15 07:31:59.414  5522  5568 I jxcore-log: 
,09-15 07:31:59.415  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-15 07:31:59.415  5522  5568 I jxcore-log: 
,09-15 07:31:59.419  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:31:59.419  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:31:59.419  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:31:59.419  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:31:59.419  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:31:59.419  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:31:59.419  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:31:59.419  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 07:31:59.421  5522  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 07:31:59.422  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-15 07:31:59.422  5522  5568 I jxcore-log: 
,09-15 07:31:59.424  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-15 07:31:59.424  5522  5568 I jxcore-log: 
,09-15 07:31:59.788  5522  5568 I jxcore-log: Unit Test app is loaded
09-15 07:31:59.788  5522  5568 I jxcore-log: 
,09-15 07:31:59.792  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 07:31:59.792  5522  5568 I jxcore-log: 
,09-15 07:31:59.797  5522  5568 D executeNativeTests: Running unit tests
,09-15 07:31:59.815  5522  5522 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-15 07:31:59.835  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 07:31:59.835  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa added. We now have 2 listener(s)
,09-15 07:31:59.836  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 07:31:59.836  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 07:31:59.836  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 07:31:59.836  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 07:31:59.836  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b added. We now have 2 listener(s)
,09-15 07:31:59.836  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 07:31:59.836  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 07:31:59.838  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:31:59.840  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:31:59.840  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:31:59.840  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:31:59.840  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:31:59.840  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:31:59.840  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:31:59.840  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:31:59.840  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 07:31:59.841  5522  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 07:31:59.841  5522  5568 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:31:59.842  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 07:31:59.842  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 07:31:59.842  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 07:31:59.843  5522  5568 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-15 07:31:59.843  5522  5568 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 07:31:59.843  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-15 07:31:59.843  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 07:31:59.843  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 07:31:59.844  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:31:59.844  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 07:31:59.844  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:31:59.844  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:31:59.844  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.844  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:31:59.844  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-15 07:31:59.844  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa removed from the list
09-15 07:31:59.844  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.844  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b removed from the list
09-15 07:31:59.850  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:31:59.850  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:31:59.850  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:31:59.851  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.851  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:31:59.851  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:31:59.851  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:31:59.851  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.851  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.852  5522  5568 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-15 07:31:59.853  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:31:59.853  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 07:31:59.853  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:31:59.853  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:31:59.853  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.853  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.853  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
,09-15 07:31:59.853  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.853  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.856  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:31:59.856  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 07:31:59.856  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.856  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.856  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.856  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.857  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 07:31:59.857  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:31:59.857  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.857  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 07:31:59.859  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 07:31:59.860  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-15 07:31:59.860  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 07:31:59.860  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 07:31:59.860  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 07:31:59.860  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-15 07:31:59.860  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 07:31:59.860  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 07:31:59.860  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 07:31:59.860  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-15 07:31:59.860  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 07:31:59.860  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-15 07:31:59.860  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 07:31:59.860  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:31:59.860  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 07:31:59.860  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:31:59.860  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:31:59.860  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.860  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.860  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:31:59.860  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 07:31:59.860  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.860  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:31:59.860  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.860  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.860  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.860  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:31:59.861  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:31:59.861  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:31:59.861  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.861  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.861  5522  5568 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 07:31:59.862  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 07:31:59.864  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:31:59.864  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:31:59.864  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:31:59.864  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:31:59.864  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:31:59.864  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:31:59.864  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:31:59.864  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 07:31:59.865  5522  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 07:31:59.865  5522  5568 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:31:59.865  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 07:31:59.865  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 07:31:59.866  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 07:31:59.866  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:31:59.866  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 07:31:59.867  5522  5568 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 07:31:59.868  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 07:31:59.870  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:31:59.873  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:31:59.874  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 07:31:59.876  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 07:31:59.876  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 07:31:59.877  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-15 07:31:59.878  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-15 07:31:59.878  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 07:31:59.878  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-15 07:31:59.879  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 07:31:59.879  5522  5568 D BluetoothAdapter: STATE_ON
09-15 07:31:59.881  4519  4532 D BtGatt.GattService: registerClient() - UUID=54b46fd7-019d-4590-ab45-306c315ab7d8
,09-15 07:31:59.883  4519  4582 D BtGatt.GattService: onClientRegistered() - UUID=54b46fd7-019d-4590-ab45-306c315ab7d8, clientIf=5
,09-15 07:31:59.884  5522  5533 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 07:31:59.885  4519  4534 D BtGatt.GattService: start scan with filters
09-15 07:31:59.889  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 07:31:59.889  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 07:31:59.889  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 07:31:59.889  4519  4595 D BtGatt.ScanManager: handling starting scan
09-15 07:31:59.889  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 07:31:59.890  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 07:31:59.891  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 07:31:59.891  5522  5522 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:31:59.891  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 07:31:59.893  5522  5568 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 07:31:59.894  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 07:31:59.894  5522  5568 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 07:31:59.894  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 07:31:59.894  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 07:31:59.894  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.894  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 07:31:59.894  4519  4595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
09-15 07:31:59.894  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-15 07:31:59.894  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 07:31:59.894  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 07:31:59.894  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-15 07:31:59.895  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 07:31:59.895  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-15 07:31:59.898  5522  5568 D BluetoothAdapter: STATE_ON
,09-15 07:31:59.899  4519  4532 D BtGatt.GattService: stopScan() - queue size =1
09-15 07:31:59.900  4519  4534 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 07:31:59.900  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 07:31:59.900  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 07:31:59.901  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 07:31:59.901  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 07:31:59.901  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 07:31:59.902  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:31:59.902  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 07:31:59.902  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 07:31:59.902  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 07:31:59.903  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 07:31:59.903  4519  4582 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 07:31:59.903  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:31:59.904  4519  4595 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 07:31:59.904  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:31:59.904  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 07:31:59.904  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:31:59.904  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:31:59.904  5522  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:31:59.904  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.905  5522  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:31:59.905  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.905  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:31:59.905  5522  5522 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:31:59.905  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.905  5522  5568 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 07:31:59.907  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 07:31:59.910  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:31:59.910  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:31:59.910  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:31:59.910  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:31:59.910  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:31:59.910  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:31:59.910  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:31:59.910  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 07:31:59.910  4519  4582 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 07:31:59.911  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:31:59.911  4519  4595 D BtGatt.ScanManager: Starting BLE batch scan
09-15 07:31:59.911  4519  4595 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 07:31:59.911  5522  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 07:31:59.911  5522  5568 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:31:59.911  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:31:59.911  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 07:31:59.911  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 07:31:59.911  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:31:59.911  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-15 07:31:59.914  5522  5568 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 07:31:59.914  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 07:31:59.915  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:31:59.918  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 07:31:59.918  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:31:59.918  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 07:31:59.919  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 07:31:59.922  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 07:31:59.922  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 07:31:59.922  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 07:31:59.922  4519  4582 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 07:31:59.922  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 07:31:59.923  5522  5568 D BluetoothAdapter: STATE_ON
,09-15 07:31:59.925  4519  4743 D BtGatt.GattService: registerClient() - UUID=733e8e52-e46b-4594-984e-9fe834986835
,09-15 07:31:59.926  4519  4582 D BtGatt.GattService: onClientRegistered() - UUID=733e8e52-e46b-4594-984e-9fe834986835, clientIf=5
09-15 07:31:59.926  5522  5533 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 07:31:59.926  4519  4534 D BtGatt.GattService: start scan with filters
,09-15 07:31:59.928  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 07:31:59.928  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 07:31:59.928  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 07:31:59.928  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 07:31:59.930  4519  4582 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-15 07:31:59.930  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:31:59.931  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:31:59.931  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 07:31:59.931  5522  5522 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 07:31:59.932  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 07:31:59.935  5522  5568 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 07:31:59.937  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 07:31:59.937  5522  5568 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 07:31:59.937  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 07:31:59.937  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 07:31:59.937  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.937  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 07:31:59.937  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 07:31:59.937  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 07:31:59.937  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 07:31:59.937  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-15 07:31:59.938  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 07:31:59.938  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 07:31:59.938  5522  5568 D BluetoothAdapter: STATE_ON
09-15 07:31:59.939  4519  4582 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 07:31:59.939  4519  4743 D BtGatt.GattService: stopScan() - queue size =0
09-15 07:31:59.939  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:31:59.939  4519  4595 D BtGatt.ScanManager: stopping BLe Batch
09-15 07:31:59.940  4519  4534 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 07:31:59.940  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 07:31:59.940  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-15 07:31:59.940  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 07:31:59.940  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 07:31:59.940  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-15 07:31:59.941  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 07:31:59.941  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 07:31:59.941  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 07:31:59.941  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-15 07:31:59.942  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:31:59.943  5522  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:31:59.943  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:31:59.943  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.943  5522  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:31:59.943  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:31:59.943  5522  5522 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:31:59.943  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:31:59.943  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.943  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.943  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:31:59.943  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.943  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.943  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.945  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 07:31:59.945  4519  4582 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 07:31:59.945  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:31:59.945  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:31:59.945  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.945  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.945  4519  4595 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 07:31:59.945  5522  5568 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 07:31:59.947  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:31:59.950  4519  4582 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 07:31:59.950  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:31:59.950  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:31:59.950  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:31:59.950  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:31:59.950  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:31:59.950  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:31:59.950  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:31:59.950  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:31:59.950  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 07:31:59.952  4519  4595 D BtGatt.ScanManager: handling starting scan
09-15 07:31:59.955  5522  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 07:31:59.956  5522  5568 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:31:59.956  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:31:59.956  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 07:31:59.956  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 07:31:59.956  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:31:59.956  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 07:31:59.957  4519  4582 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 07:31:59.957  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:31:59.957  4519  4595 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 07:31:59.959  5522  5568 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 07:31:59.959  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 07:31:59.960  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:31:59.962  4519  4582 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 07:31:59.962  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:31:59.962  4519  4595 D BtGatt.ScanManager: Starting BLE batch scan
09-15 07:31:59.962  4519  4595 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 07:31:59.963  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:31:59.963  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 07:31:59.964  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 07:31:59.964  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 07:31:59.967  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 07:31:59.967  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 07:31:59.967  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 07:31:59.968  5522  5568 D BluetoothAdapter: STATE_ON
09-15 07:31:59.970  4519  4743 D BtGatt.GattService: registerClient() - UUID=95b0e55d-3e54-4281-8a59-120a087c2f62
09-15 07:31:59.970  4519  4582 D BtGatt.GattService: onClientRegistered() - UUID=95b0e55d-3e54-4281-8a59-120a087c2f62, clientIf=5
09-15 07:31:59.970  4519  4582 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 07:31:59.970  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:31:59.970  5522  5532 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 07:31:59.970  4519  4751 D BtGatt.GattService: start scan with filters
09-15 07:31:59.973  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 07:31:59.973  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 07:31:59.973  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 07:31:59.973  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 07:31:59.975  4519  4582 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 07:31:59.975  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:31:59.975  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:31:59.975  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 07:31:59.975  5522  5522 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:31:59.976  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 07:31:59.980  5522  5568 I io.jxcore.node.ConnectionHelper: start: OK
09-15 07:31:59.980  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:31:59.980  5522  5568 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 07:31:59.980  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 07:31:59.980  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 07:31:59.980  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.980  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 07:31:59.980  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 07:31:59.980  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 07:31:59.980  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 07:31:59.980  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 07:31:59.980  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 07:31:59.981  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 07:31:59.981  4519  4582 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 07:31:59.981  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:31:59.981  4519  4595 D BtGatt.ScanManager: stopping BLe Batch
09-15 07:31:59.981  5522  5568 D BluetoothAdapter: STATE_ON
09-15 07:31:59.982  4519  4751 D BtGatt.GattService: stopScan() - queue size =0
09-15 07:31:59.982  4519  4534 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 07:31:59.983  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 07:31:59.983  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 07:31:59.983  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 07:31:59.983  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 07:31:59.983  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 07:31:59.984  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:31:59.984  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 07:31:59.984  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 07:31:59.984  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-15 07:31:59.985  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:31:59.986  5522  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:31:59.986  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:31:59.986  5522  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:31:59.986  5522  5568 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 07:31:59.986  5522  5522 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:31:59.986  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:31:59.986  4519  4582 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 07:31:59.986  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:31:59.986  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:31:59.986  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.986  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:31:59.986  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:31:59.986  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:31:59.986  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.986  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.986  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:31:59.986  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.986  4519  4595 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 07:31:59.987  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.987  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.988  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:31:59.988  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:31:59.988  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.988  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.989  5522  5568 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-15 07:31:59.989  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:31:59.989  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:31:59.989  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:31:59.990  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:31:59.990  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.990  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.990  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:31:59.990  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.990  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.990  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:31:59.990  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.990  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.990  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.990  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.991  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:31:59.991  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:31:59.991  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.991  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.991  4519  4582 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 07:31:59.991  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:31:59.992  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 07:31:59.992  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:31:59.992  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:31:59.992  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:31:59.992  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:31:59.992  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.992  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.992  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:31:59.992  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.992  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.993  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:31:59.993  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.993  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.993  4519  4595 D BtGatt.ScanManager: handling starting scan
09-15 07:31:59.993  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.993  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.994  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:31:59.994  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:31:59.994  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.994  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.994  5522  5568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-15 07:31:59.994  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:31:59.994  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:31:59.995  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:31:59.995  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:31:59.995  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.995  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.995  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:31:59.995  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.995  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.995  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:31:59.995  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.995  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.995  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.995  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.996  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:31:59.996  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:31:59.997  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.997  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.997  5522  5568 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-15 07:31:59.997  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:31:59.997  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:31:59.997  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:31:59.998  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:31:59.998  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.998  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.998  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:31:59.998  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.998  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:31:59.998  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:31:59.998  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.998  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.998  4519  4582 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 07:31:59.998  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:31:59.998  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:31:59.998  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:31:59.998  4519  4595 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 07:31:59.999  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:31:59.999  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:31:59.999  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:31:59.999  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.000  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 07:32:00.000  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 07:32:00.000  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 07:32:00.000  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 07:32:00.000  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 07:32:00.000  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 07:32:00.000  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:32:00.000  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:00.000  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:00.000  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:00.000  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.000  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.000  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:32:00.000  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.001  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.001  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:00.001  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.001  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.001  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.001  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.002  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:00.002  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:00.002  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.002  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.002  5522  5568 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 07:32:00.003  5522  5568 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 07:32:00.003  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 07:32:00.004  4519  4582 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 07:32:00.004  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:00.004  4519  4595 D BtGatt.ScanManager: Starting BLE batch scan
09-15 07:32:00.004  4519  4595 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 07:32:00.005  5522  5568 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 07:32:00.005  5522  5568 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-15 07:32:00.005  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-15 07:32:00.005  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 07:32:00.005  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 07:32:00.005  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 07:32:00.005  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 07:32:00.005  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 07:32:00.005  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 07:32:00.005  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 07:32:00.005  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38,:2810:2810:2810:2810:2810]
09-15 07:32:00.006  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 07:32:00.007  5522  5568 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-15 07:32:00.007  5522  5568 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 07:32:00.007  5522  5568 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-15 07:32:00.007  5522  5568 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 07:32:00.007  5522  5568 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 07:32:00.007  5522  5568 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-15 07:32:00.007  5522  5568 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 07:32:00.007  5522  5568 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 07:32:00.007  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-15 07:32:00.011  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-15 07:32:00.011  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-15 07:32:00.011  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-15 07:32:00.012  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-15 07:32:00.012  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-15 07:32:00.012  5522  5568 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-15 07:32:00.013  5522  5568 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 07:32:00.013  5522  5568 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-15 07:32:00.014  4519  4582 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 07:32:00.014  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:00.013  4534  4534 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[28310]" dev="sockfs" ino=28310 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 07:32:00.013  4534  4534 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[28310]" dev="sockfs" ino=28310 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 07:32:00.015  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:32:00.015  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:00.015  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:00.015  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:00.015  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.015  5522  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-15 07:32:00.015  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.015  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-15 07:32:00.016  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:32:00.016  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 07:32:00.016  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.016  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:00.016  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.016  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.016  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.016  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.017  5522  5569 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 07:32:00.019  4519  4582 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 07:32:00.019  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:00.019  5522  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-15 07:32:00.019  5522  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-15 07:32:00.020  5522  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-15 07:32:00.020  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:00.020  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:00.020  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.020  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.020  5522  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-15 07:32:00.020  4519  4741 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
09-15 07:32:00.021  5522  5568 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-15 07:32:00.021  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:32:00.021  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:00.021  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:00.021  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:00.022  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.022  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.022  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:32:00.022  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.022  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.022  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:00.022  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.022  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.022  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.022  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.024  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:00.024  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:00.024  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.024  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.025  5522  5568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-15 07:32:00.025  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:32:00.026  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:00.026  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:00.026  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:00.026  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.026  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.027  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:32:00.027  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.027  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.027  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:00.027  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.027  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.027  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.027  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.028  4519  4582 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 07:32:00.028  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:00.028  4519  4595 D BtGatt.ScanManager: stopping BLe Batch
09-15 07:32:00.033  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:00.033  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:00.033  4519  4582 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 07:32:00.033  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.033  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:00.033  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.033  4519  4595 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 07:32:00.033  5522  5568 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-15 07:32:00.034  5522  5568 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-15 07:32:00.034  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 07:32:00.034  5522  5568 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-15 07:32:00.034  5522  5568 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 07:32:00.034  5522  5568 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-15 07:32:00.034  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 07:32:00.034  5522  5568 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-15 07:32:00.034  5522  5568 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 07:32:00.034  5522  5568 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 07:32:00.034  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 07:32:00.034  5522  5568 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-15 07:32:00.034  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:32:00.034  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:00.034  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:00.034  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:00.034  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.034  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.035  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:32:00.035  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.035  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.035  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:00.035  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.035  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.035  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.035  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.036  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:00.036  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:00.036  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.036  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.036  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:00.036  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.036  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.036  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:32:00.036  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.037  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.037  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:00.037  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.037  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.037  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.037  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.037  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:00.037  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.037  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.037  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:32:00.037  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:32:00.037  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:00.037  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:00.037  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:00.037  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.037  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.037  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:32:00.037  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.037  4519  4582 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 07:32:00.037  4519  4582 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:00.037  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.038  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:00.038  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.038  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.038  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.038  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.040  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:00.040  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:00.040  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.040  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.042  5522  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 07:32:00.042  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:32:00.043  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-15 07:32:00.044  5522  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 07:32:00.044  5522  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 07:32:00.044  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 07:32:00.045  5522  5522 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 07:32:00.045  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 07:32:00.045  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:00.045  5522  5571 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 07:32:00.045  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 07:32:00.045  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 07:32:00.045  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 07:32:00.045  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.045  5522  5568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-15 07:32:00.045  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:32:00.045  5522  5522 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 07:32:00.045  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.045  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 07:32:00.045  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 07:32:00.045  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 07:32:00.045  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.045  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.043  4751  4751 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33901]" dev="sockfs" ino=33901 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 07:32:00.043  4751  4751 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33901]" dev="sockfs" ino=33901 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 07:32:00.046  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:32:00.046  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.046  5522  5571 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 07:32:00.047  5522  5571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 07:32:00.047  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:32:00.047  5522  5571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 07:32:00.047  5522  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:32:00.047  5522  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:32:00.047  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:00.047  5522  5522 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:32:00.047  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:00.047  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:00.047  5522  5522 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 07:32:00.047  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.047  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.047  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:32:00.047  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.047  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.047  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:00.048  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.048  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.048  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.048  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.049  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:00.049  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:00.049  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.049  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.050  5522  5568 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-15 07:32:00.050  5522  5568 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 07:32:00.051  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 07:32:00.051  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 07:32:00.051  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:32:00.051  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:00.051  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:00.051  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:00.051  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.051  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.052  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:32:00.052  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.052  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.052  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:00.052  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.052  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.052  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.052  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.053  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:00.053  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:00.053  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.053  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.056  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:32:00.056  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:00.056  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:00.056  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:00.056  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.057  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.057  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:32:00.057  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.057  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.057  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:00.057  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.057  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.057  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.057  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.058  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:00.058  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:00.058  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.058  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.058  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:32:00.058  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:00.058  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:00.058  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:00.059  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.059  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.059  5522  5568 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aaa not in the list
09-15 07:32:00.059  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.059  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.059  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:00.059  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.059  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.059  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:00.059  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:00.060  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:00.060  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:00.060  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:00.060  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e57669b not in the list
09-15 07:32:00.061  5522  5568 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-15 07:32:00.061  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 07:32:00.061  5522  5568 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-15 07:32:00.061  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 07:32:00.061  5522  5568 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-15 07:32:00.061  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 07:32:00.062  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 07:32:00.062  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-15 07:32:00.063  5522  5568 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-15 07:32:00.063  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 07:32:00.063  5522  5568 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-15 07:32:00.063  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 07:32:00.063  5522  5568 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-15 07:32:00.063  5522  5568 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-15 07:32:00.064  5522  5568 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-15 07:32:00.064  5522  5568 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-15 07:32:00.064  5522  5568 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-15 07:32:00.064  5522  5568 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-15 07:32:00.064  5522  5568 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-15 07:32:00.064  5522  5568 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-15 07:32:00.065  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:32:00.065  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d4b4205 added. We now have 2 listener(s)
09-15 07:32:00.065  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:00.066  5522  5568 D BluetoothAdapter: enable(): BT is already enabled..!
09-15 07:32:00.066   925  3261 D WifiService: setWifiEnabled: true pid=5522, uid=10077
09-15 07:32:00.067   925  3261 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 07:32:00.067  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:32:00.067  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c06d25a added. We now have 3 listener(s)
09-15 07:32:00.067  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:00.071  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:32:00.071  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e9b2c8b added. We now have 4 listener(s)
09-15 07:32:00.071  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:00.073  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:32:00.073  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e268168 added. We now have 5 listener(s)
09-15 07:32:00.073  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:00.076   925  3594 D WifiService: setWifiEnabled: false pid=5522, uid=10077
09-15 07:32:00.076   925  3594 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 07:32:00.079   925  3041 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-15 07:32:00.079   925  3041 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-15 07:32:00.079   925  3041 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 07:32:00.079   925  3041 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-15 07:32:00.082  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:32:00.083  4519  4578 D BluetoothAdapterState: Current state: ON, message: 23
09-15 07:32:00.083  4519  4578 D BluetoothAdapterProperties: Setting state to 13
09-15 07:32:00.083  4519  4578 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-15 07:32:00.084  4519  4578 D BluetoothAdapterProperties: onBluetoothDisable()
09-15 07:32:00.084  4519  4578 I BluetoothAdapterState: Entering PendingCommandState
09-15 07:32:00.086  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:00.086   925  3041 E native  : do suspend true
09-15 07:32:00.086  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:32:00.086  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:00.086  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:00.086  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:32:00.086  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:32:00.086  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:32:00.086  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:32:00.086  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 07:32:00.087  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:00.087  4519  4519 D BluetoothMapService: onReceive
09-15 07:32:00.087  5522  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 07:32:00.087  4519  4519 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 07:32:00.087  5522  5568 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:32:00.087  4519  4519 D BluetoothMapService: STATE_TURNING_OFF
09-15 07:32:00.088  4519  4519 D BluetoothMapService: MAP Service closeService in
09-15 07:32:00.088  4519  4519 D BluetoothMapMasInstance0: MAP Service shutdown
09-15 07:32:00.088  4519  4519 D ObexServerSockets0: shutdown(block = true)
09-15 07:32:00.089  4519  4519 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 07:32:00.089  4519  4753 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-15 07:32:00.089  4519  4519 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 07:32:00.089  4519  4754 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-15 07:32:00.090  4519  4741 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-15 07:32:00.090  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:00.093  4519  4519 I BtOppRfcommListener: stopping Accept Thread
09-15 07:32:00.093  4519  5188 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 07:32:00.093  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:00.093  4519  5188 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 07:32:00.096  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:00.096  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:00.096  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:00.096  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:00.096  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:32:00.096  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:32:00.096  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:32:00.096  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:32:00.096  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 07:32:00.097  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:00.097  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 07:32:00.098   925   938 I ActivityManager: Start proc 5574:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-15 07:32:00.099  4519  4582 D BluetoothAdapterProperties: Scan Mode:20
09-15 07:32:00.099  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:00.102  4519  4578 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-15 07:32:00.104  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:00.105  4519  4519 D HeadsetService: Received stop request...Stopping profile...
09-15 07:32:00.106   925   925 D BluetoothHeadset: Proxy object disconnected
09-15 07:32:00.107  3571  3845 D BluetoothHeadset: Proxy object disconnected
09-15 07:32:00.108  4519  4519 D A2dpService: Received stop request...Stopping profile...
09-15 07:32:00.108  3195  3207 D BluetoothHeadset: Proxy object disconnected
09-15 07:32:00.108   925   925 D BluetoothHeadset: Proxy object disconnected
09-15 07:32:00.108   925   925 D BluetoothHeadset: Proxy object disconnected
09-15 07:32:00.108  4519  4746 D A2dpStateMachine: Exit Disconnected: -1
09-15 07:32:00.108  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:00.109   925   925 D BluetoothA2dp: Proxy object disconnected
,09-15 07:32:00.110  4519  4519 D HidService: Received stop request...Stopping profile...
,09-15 07:32:00.110  4519  4519 D HidService: Stopping Bluetooth HidService
09-15 07:32:00.111   925  5236 D DhcpClient: Clearing IP address
09-15 07:32:00.111  4519  4519 D HealthService: Received stop request...Stopping profile...
09-15 07:32:00.111   508   919 D CommandListener: Clearing all IP addresses on wlan0
09-15 07:32:00.112  4519  4519 V BluetoothAdapterState: isTurningOff()=true
09-15 07:32:00.112  4519  4519 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:00.112  4519  4519 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:00.112  4519  4519 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:00.114   508   919 D CommandListener: Setting iface cfg
09-15 07:32:00.114  4519  4519 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-15 07:32:00.114  4519  4519 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 07:32:00.114  4519  4727 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:32:00.114  4519  4727 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:32:00.114  4519  4519 V BluetoothAdapterState: isTurningOff()=true
09-15 07:32:00.114  4519  4727 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:32:00.114  4519  4519 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:00.115  4519  4519 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:00.115  3195  3195 D HeadsetProfile: Bluetooth service disconnected
09-15 07:32:00.115  4519  4519 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:00.115  4519  4519 V BluetoothAdapterState: isTurningOff()=true
09-15 07:32:00.115  4519  4519 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:00.115  3195  3195 D BluetoothA2dp: Proxy object disconnected
09-15 07:32:00.115  4519  4519 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:00.115  4519  4519 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:00.115  3195  3195 D BluetoothInputDevice: Proxy object disconnected
09-15 07:32:00.115  3195  3195 D HidProfile: Bluetooth service disconnected
09-15 07:32:00.115  4519  4582 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 07:32:00.115  4519  4519 D PanService: Received stop request...Stopping profile...
09-15 07:32:00.116  4519  4582 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-15 07:32:00.117  3195  3195 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 07:32:00.117  3195  3195 D PanProfile: Bluetooth service disconnected
09-15 07:32:00.118   925  3043 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-15 07:32:00.118   925  3043 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-15 07:32:00.118  4519  4727 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:32:00.118  4519  4727 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:32:00.118  4519  4727 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 07:32:00.118  4519  4519 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 07:32:00.118  4519  4727 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 07:32:00.119   925  5237 D DhcpClient: Receive thread stopped
09-15 07:32:00.120  4519  4727 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 07:32:00.120  4519  4727 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 07:32:00.120  4519  4582 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 07:32:00.120  4519  4582 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 07:32:00.118  4519  4519 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 07:32:00.121  4519  4519 V BluetoothAdapterState: isTurningOff()=true
09-15 07:32:00.121  4519  4519 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:00.121  4519  4519 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:00.121  4519  4519 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:00.121  4519  4519 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-15 07:32:00.121  4519  4582 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 07:32:00.122  4519  4519 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-15 07:32:00.122  4519  4519 D BluetoothMapService: Received stop request...Stopping profile...
09-15 07:32:00.122  4519  4519 D BluetoothMapService: stop()
09-15 07:32:00.122  3660  5289 V NativeCrypto: Read error: ssl=0x7f96764000: I/O error during system call, Connection timed out
09-15 07:32:00.123   534   534 E Parcel  : Reading a NULL string not supported here.
09-15 07:32:00.123   925  3043 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-15 07:32:00.124  3660  5289 V NativeCrypto: SSL shutdown failed: ssl=0x7f96764000: I/O error during system call, Broken pipe
09-15 07:32:00.125  3534  3688 W QCNEJ   : |CORE| network lost: 100
09-15 07:32:00.127  3534  3688 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-15 07:32:00.127   925   925 D RttService: SCAN_AVAILABLE : 1
09-15 07:32:00.127  4519  4519 D BluetoothMapAppObserver: deinitObservers()
09-15 07:32:00.127  4519  4519 D BluetoothMapAppObserver: removeReceiver()
09-15 07:32:00.128   925  3148 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 07:32:00.130  4519  4519 D SapService: Received stop request...Stopping profile...
09-15 07:32:00.130  4519  4519 V SapService: stop()
,09-15 07:32:00.132  4519  4519 V BluetoothAdapterState: isTurningOff()=true
09-15 07:32:00.132  4519  4519 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:00.132  4519  4519 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:00.132  4519  4519 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:00.132  4519  4519 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 07:32:00.132  4519  4519 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-15 07:32:00.134  4519  4519 D BluetoothMapService: MAP Service closeService in
,09-15 07:32:00.134  4519  4519 V BluetoothAdapterState: isTurningOff()=true
09-15 07:32:00.134  4519  4519 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:00.134  4519  4519 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:00.134  4519  4519 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:00.134  4519  4519 D BluetoothMapService: cleanup()
09-15 07:32:00.134  4519  4519 D BluetoothMapService: MAP Service closeService in
09-15 07:32:00.134  4519  4519 V BluetoothAdapterState: isTurningOff()=true
09-15 07:32:00.134  4519  4519 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:00.134  4519  4519 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:00.135  4519  4519 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 07:32:00.135  4519  4578 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-15 07:32:00.135  4519  4578 D BluetoothAdapterProperties: Setting state to 15
09-15 07:32:00.135  4519  4578 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 07:32:00.135  4519  4578 I BluetoothAdapterState: Entering BleOnState
09-15 07:32:00.136  3195  3207 D BluetoothMap: onBluetoothStateChange: up=false
09-15 07:32:00.136  3195  3758 D BluetoothPan: onBluetoothStateChange on: false
09-15 07:32:00.137   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:32:00.137   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 07:32:00.137  3571  3845 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:32:00.137  3195  3213 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 07:32:00.138  3195  3207 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 07:32:00.138   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:32:00.138  3195  3758 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 07:32:00.139   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:32:00.139  3195  3213 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:32:00.140  4519  4578 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 07:32:00.140  4519  4578 D BluetoothAdapterProperties: Setting state to 16
09-15 07:32:00.140  4519  4578 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 07:32:00.143  4519  4578 D BluetoothAdapterProperties: onBleDisable
09-15 07:32:00.143  4519  4578 I BluetoothAdapterState: Entering PendingCommandState
09-15 07:32:00.143  4519  4579 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-15 07:32:00.143  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:00.143  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:00.143  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:00.143  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:00.143  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:32:00.143  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:32:00.143  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:00.143  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:00.143  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:32:00.143  4519  4582 D BluetoothAdapterProperties: Scan Mode:20
,09-15 07:32:00.144  4519  4727 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-15 07:32:00.144  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:00.144  4519  4727 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:32:00.144  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:32:00.148  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:00.149  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:00.149  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:00.149  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:00.149  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:32:00.149  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:32:00.149  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:00.149  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:00.149  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:32:00.149   925  3041 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-15 07:32:00.151  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 07:32:00.151  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:32:00.153  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:00.155  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:00.162   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 07:32:00.166   925  3041 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 07:32:00.166   925  3041 E native  : do suspend true
,09-15 07:32:00.174  5574  5574 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-15 07:32:00.184  5574  5574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 07:32:00.189   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a9f64a9:true
,09-15 07:32:00.191  3660  3660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 07:32:00.193   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 07:32:00.193   508   919 D CommandListener: Clearing all IP addresses on wlan0
09-15 07:32:00.194   925  3043 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-15 07:32:00.195   925  3043 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-15 07:32:00.205   925  3499 I ActivityManager: Start proc 5590:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-15 07:32:00.208   925   942 D Tethering: MasterInitialState.processMessage what=3
,09-15 07:32:00.210   925  3041 D DhcpClient: doQuit
09-15 07:32:00.210   925  3041 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-15 07:32:00.210   925  5236 D DhcpClient: onQuitting
09-15 07:32:00.211  4319  4319 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@b8bd8b1 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-15 07:32:00.211  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:00.212  3722  3722 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-15 07:32:00.213  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:00.216  4942  4958 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-15 07:32:00.218  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:00.217  4942  4958 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 07:32:00.219  4942  4958 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-15 07:32:00.219  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:00.219  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:00.219  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:00.219  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:32:00.219  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:32:00.219  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:00.219  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:00.219  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:32:00.219  4942  4958 E SarControlService: no key has been found,reset the power
09-15 07:32:00.220  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:00.220  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:32:00.221  4942  4983 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-15 07:32:00.221  4942  4983 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 07:32:00.221  4942  4983 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 07:32:00.222  4971  4971 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 07:32:00.222  4971  4971 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-15 07:32:00.222  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:00.223  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:00.223  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:00.223  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:00.223  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:32:00.223  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:32:00.223  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:00.223  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:00.223  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:32:00.223  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:00.223  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:32:00.224  4942  4983 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 07:32:00.224  4942  4983 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-15 07:32:00.224  4942  4983 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-15 07:32:00.224  4971  4971 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 07:32:00.224  4971  4971 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-15 07:32:00.228  4971  4985 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a98595f HexData = [00000000ea03000000000000ffffffff]
09-15 07:32:00.228  4971  4985 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 07:32:00.229  4971  4985 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-15 07:32:00.229  4971  4971 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 07:32:00.229  4942  4953 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-15 07:32:00.235  4971  4985 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a98595f HexData = [00000000eb03000000000000ffffffff]
,09-15 07:32:00.235  4971  4985 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 07:32:00.235  4971  4985 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-15 07:32:00.236  4971  4971 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-15 07:32:00.236  4942  4954 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-15 07:32:00.238  3722  3722 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-15 07:32:00.241  3722  3722 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-15 07:32:00.251  5574  5574 D LocalBluetoothProfileManager: Adding local MAP profile
,09-15 07:32:00.255  5574  5574 D BluetoothMap: Create BluetoothMap proxy object
,09-15 07:32:00.261  5590  5590 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-15 07:32:00.263   508   919 E Netd    : netlink response contains error (No such file or directory)
,09-15 07:32:00.264   925  3043 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-15 07:32:00.268  5574  5574 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-15 07:32:00.276  3722  3722 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 07:32:00.282  5574  5574 D DockEventReceiver: finishStartingService: stopping service
,09-15 07:32:00.290  3722  3722 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 07:32:00.296   925  3591 I ActivityManager: Killing 4923:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-15 07:32:00.347  4519  4582 I bt_hci  : shut_down
,09-15 07:32:00.351  4519  4598 D bt_hwcfg: hw_epilog_process
,09-15 07:32:00.351  4519  4598 I bt_vendor: low_power_mode_cb
,09-15 07:32:00.353  4519  4598 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-15 07:32:00.353  4519  4598 I bt_vendor: epilog_cb
09-15 07:32:00.353  4519  4598 I bt_hci  : epilog_finished_callback
,09-15 07:32:00.356  4519  4582 I bt_hci_h4: hal_close
,09-15 07:32:00.356  4519  4582 I bt_userial_vendor: device fd = 54 close
,09-15 07:32:00.392   925  3041 D wifi    : In wifi stop Hal
,09-15 07:32:00.392   925  3041 D wifi    : halHandle = 0x7f808a5380, mVM = 0x7f9c9cd140, mCls = 0x100bb6
09-15 07:32:00.393   925  3712 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-15 07:32:00.393   925  3712 D WifiHAL : Got a signal to exit!!!
09-15 07:32:00.393   925  3712 I WifiHAL : Exit wifi_event_loop
09-15 07:32:00.393  4366  4366 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 07:32:00.393   925  3041 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 07:32:00.393   925  3041 E WifiHAL : Event processing terminated
,09-15 07:32:00.393   925  3041 D wifi    : In wifi cleaned up handler
09-15 07:32:00.393   925  3041 I WifiHAL : Internal cleanup completed
09-15 07:32:00.395  3678  4109 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 07:32:00.395  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:00.397  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:00.417   925  3712 D wifi    : set interface wlan0 flags (DOWN)
,09-15 07:32:00.417   925  3041 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 07:32:00.466  4519  4579 D bt_stack_manager: event_shut_down_stack finished.
,09-15 07:32:00.466  4519  4578 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-15 07:32:00.467  4519  4578 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-15 07:32:00.468  4519  4519 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 07:32:00.468  4519  4519 D BtGatt.GattService: Received stop request...Stopping profile...
,09-15 07:32:00.468  4519  4519 D BtGatt.GattService: stop()
09-15 07:32:00.468  4519  4519 D BtGatt.AdvertiseManager: advertise clients cleared
09-15 07:32:00.470  4519  4519 V BluetoothAdapterState: isTurningOff()=false
09-15 07:32:00.470  4519  4519 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:00.470  4519  4519 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:00.470  4519  4519 V BluetoothAdapterState: isBleTurningOff()=true
,09-15 07:32:00.470  4519  4578 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-15 07:32:00.470  4519  4578 D BluetoothAdapterProperties: Setting state to 10
09-15 07:32:00.470  4519  4578 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 07:32:00.472  4519  4578 I BluetoothAdapterState: Entering OffState
09-15 07:32:00.472   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-15 07:32:00.478  4519  4519 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-15 07:32:00.478  4519  4519 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 07:32:00.478  4519  4519 I BluetoothServiceJni: cleanupNative: return from cleanup
09-15 07:32:00.479  4519  4579 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 07:32:00.483   508   919 E Netd    : netlink response contains error (No such file or directory)
,09-15 07:32:00.492  4519  4579 D bt_stack_manager: event_clean_up_stack finished.
09-15 07:32:00.494  5590  5590 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:32:00.494  5590  5590 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693),
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:32:00.494  5590  5590 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Looper.loop(Looper.java:148),
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:32:00.494  5590  5590 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:32:00.494  5590  5590 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.r.k.d(PG:583)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:32:00.494  5590  5590 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:32:00.494  5590  5590 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:54,22)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:32:00.494  5590  5590 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:32:00.494  5590  5590 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:32:00.499  5574  5574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 07:32:00.503  4519  4519 I art     : System.exit called, status: 0
09-15 07:32:00.503  4519  4519 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-15 07:32:00.534  5574  5574 D DockEventReceiver: finishStartingService: stopping service
09-15 07:32:00.535   925  3840 I ActivityManager: Killing 4319:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-15 07:32:00.547  5522  5522 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 07:32:00.619   925   942 D Tethering: InitialState.processMessage what=4
,09-15 07:32:00.625   925  3204 I ActivityManager: Process com.android.bluetooth (pid 4519) has died
,09-15 07:32:00.627   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-15 07:32:00.628  3660  3660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 07:32:00.640   925  3500 I ActivityManager: Start proc 5634:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-15 07:32:00.701  5634  5634 D AdapterServiceConfig: Adding HeadsetService
09-15 07:32:00.701  5634  5634 D AdapterServiceConfig: Adding A2dpService
09-15 07:32:00.701  5634  5634 D AdapterServiceConfig: Adding HidService
09-15 07:32:00.701  5634  5634 D AdapterServiceConfig: Adding HealthService
09-15 07:32:00.701  5634  5634 D AdapterServiceConfig: Adding PanService
09-15 07:32:00.701  5634  5634 D AdapterServiceConfig: Adding GattService
09-15 07:32:00.701  5634  5634 D AdapterServiceConfig: Adding BluetoothMapService
09-15 07:32:00.702  5634  5634 D AdapterServiceConfig: Adding SapService
,09-15 07:32:00.704   925  3261 I ActivityManager: Killing 5263:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-15 07:32:00.731  3980  3980 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-15 07:32:00.740  3980  5260 I iu.UploadsManager: num queued entries: 0
,09-15 07:32:00.740  3980  5260 I iu.UploadsManager: num updated entries: 0
09-15 07:32:00.741  3980  5260 I iu.SyncManager: NEXT; no task
,09-15 07:32:00.742  3980  3980 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-15 07:32:00.744  3980  3980 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-15 07:32:00.757   925  4032 I ActivityManager: Start proc 5647:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-15 07:32:00.791  5647  5647 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-15 07:32:00.794  5647  5647 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-15 07:32:00.800  5647  5647 D SprintDMHelper: simOperator: 
,09-15 07:32:00.800  5647  5647 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-15 07:32:00.812  4366  5659 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-15 07:32:00.814   925  3499 I ActivityManager: Killing 4605:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-15 07:32:00.842  5590  5619 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-15 07:32:00.852   925  3499 I ActivityManager: Start proc 5660:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-15 07:32:00.857   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fdcccb7:true
,09-15 07:32:00.883  5660  5660 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-15 07:32:00.894   925  3594 I ActivityManager: Killing 5385:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-15 07:32:00.947   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:32:01.947   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:32:02.948   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:32:03.090   925  3593 D WifiService: setWifiEnabled: true pid=5522, uid=10077
,09-15 07:32:03.090   925  3593 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 07:32:03.101   508   919 D SoftapController: Softap fwReload - Ok
,09-15 07:32:03.106   508   919 D CommandListener: Setting iface cfg
,09-15 07:32:03.107   508   919 D CommandListener: Trying to bring down wlan0
,09-15 07:32:03.108   508   919 D CommandListener: Clearing all IP addresses on wlan0
,09-15 07:32:03.115   925  3041 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 07:32:03.725   925  3041 D wifi    : set interface wlan0 flags (UP)
,09-15 07:32:03.731   925  3041 I WifiHAL : Initializing wifi
09-15 07:32:03.731   925  3041 I WifiHAL : Creating socket
09-15 07:32:03.733   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 07:32:03.737   925  3041 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-15 07:32:03.738   925  3041 D wifi    : Did set static halHandle = 0x7f808a5380
,09-15 07:32:03.738   925  3041 D wifi    : halHandle = 0x7f808a5380, mVM = 0x7f9c9cd140, mCls = 0x1018d6
,09-15 07:32:03.740   925  3041 D wifi    : array field set
09-15 07:32:03.740   925  3041 I WifiNative-HAL: interface[0] = wlan0
,09-15 07:32:03.745   925  5678 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547617395584
,09-15 07:32:03.745   925  5678 D wifi    : waitForHalEvents called, vm = 0x7f9c9cd140, obj = 0x1018d6, env = 0x7f816d38c0
,09-15 07:32:03.812  5679  5679 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 07:32:03.825  5679  5679 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 07:32:03.846   925  3041 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-15 07:32:03.849  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:03.850  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:03.854  5679  5679 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 07:32:03.855  5679  5679 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 07:32:03.869   925  3041 D WifiConfigStore: Loading config and enabling all networks 
,09-15 07:32:03.869  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:03.869  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:03.869  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:03.869  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:03.869  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:32:03.869  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:32:03.869  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:03.869  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:03.869  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:32:03.869  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:03.869  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:32:03.871  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:03.871  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:03.871  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:03.871  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:03.871  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:32:03.871  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:32:03.871  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:03.871  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:03.871  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:32:03.871  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:03.871  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:32:03.883   925  3041 D WifiConfigStore: loaded 0 passpoint configs
,09-15 07:32:03.883   925  3041 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 07:32:03.884   925  3041 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-15 07:32:03.885   925  3041 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-15 07:32:03.887   925  3041 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-15 07:32:03.887   925  3041 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 07:32:03.887   925  3041 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-15 07:32:03.887   925  3041 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 07:32:03.891   925  3041 D WifiNative-HAL: Setting external_sim to 1
,09-15 07:32:03.891  4366  4366 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 07:32:03.891   925  3041 D wifi    : setting dfs flag to true, 0x7f838bd1c0
09-15 07:32:03.892   925  3041 D WifiStateMachine: Setting OUI to DA-A1-19
,09-15 07:32:03.892   925  3041 D wifi    : setting scan oui 0x7f838bd1c0
09-15 07:32:03.892   925  3041 D WifiHAL : Sending mac address OUI
,09-15 07:32:03.906   925  3041 E native  : do suspend true
,09-15 07:32:03.912   925  3041 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-15 07:32:03.912   925   925 D RttService: SCAN_AVAILABLE : 3
09-15 07:32:03.912   508   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-15 07:32:03.913   925  3148 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-15 07:32:03.914   508   919 D CommandListener: Setting iface cfg
,09-15 07:32:03.923   925  3040 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,09-15 07:32:03.924   925  3040 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 07:32:03.933   925  3040 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 07:32:03.939   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=232606 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=10 mControllerEnergyUsed=38 }
,09-15 07:32:03.939   925  3040 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62,
,09-15 07:32:03.949   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:32:04.950   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:32:05.950   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 07:32:06.099   925  3261 D WifiService: setWifiEnabled: false pid=5522, uid=10077
,09-15 07:32:06.099   925  3261 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 07:32:06.107   925   925 D RttService: SCAN_AVAILABLE : 1
,09-15 07:32:06.107   925  3148 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 07:32:06.124   925  3041 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-15 07:32:06.125   508   919 D CommandListener: Clearing all IP addresses on wlan0
,09-15 07:32:06.131   925  3041 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 07:32:06.133  5679  5679 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-15 07:32:06.141  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 07:32:06.141  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:06.141  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:06.141  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:06.141  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:32:06.141  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:32:06.141  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:06.141  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:06.141  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:32:06.141  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 07:32:06.141  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:32:06.143  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:06.144  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:06.144  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:06.144  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:06.144  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:32:06.144  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:32:06.144  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:06.144  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:06.144  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:32:06.144  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:06.144  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:32:06.151  5679  5679 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-15 07:32:06.161  5679  5679 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 07:32:06.170  5679  5679 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 07:32:06.276   925  3041 D wifi    : In wifi stop Hal
,09-15 07:32:06.276  4366  4366 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 07:32:06.276   925  3041 D wifi    : halHandle = 0x7f808a5380, mVM = 0x7f9c9cd140, mCls = 0x1018d6
,09-15 07:32:06.277   925  5678 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-15 07:32:06.277   925  5678 D WifiHAL : Got a signal to exit!!!
09-15 07:32:06.277   925  5678 I WifiHAL : Exit wifi_event_loop
09-15 07:32:06.281   925  3041 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 07:32:06.281   925  3041 E WifiHAL : Event processing terminated
,09-15 07:32:06.282   925  3041 D wifi    : In wifi cleaned up handler
09-15 07:32:06.282   925  3041 I WifiHAL : Internal cleanup completed
,09-15 07:32:06.284  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:06.287  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:06.290  3678  4109 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 07:32:06.316   925  5678 D wifi    : set interface wlan0 flags (DOWN)
,09-15 07:32:06.317   925  3041 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 07:32:06.399   508   919 E Netd    : netlink response contains error (No such file or directory)
,09-15 07:32:06.520   925   942 D Tethering: InitialState.processMessage what=4
,09-15 07:32:06.527   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-15 07:32:09.141   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6e09fd:true
,09-15 07:32:09.142  5634  5634 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 07:32:09.148  5634  5634 I bt_bluedroid: init
,09-15 07:32:09.148  5634  5698 I BluetoothAdapterState: Entering OffState
,09-15 07:32:09.152  5634  5699 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-15 07:32:09.153  5634  5699 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-15 07:32:09.153  5634  5699 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-15 07:32:09.153  5634  5699 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-15 07:32:09.154  5634  5634 I bt_bluedroid: get_profile_interface socket
,09-15 07:32:09.157  5634  5702 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 07:32:09.157  5634  5634 I bt_bluedroid: get_profile_interface sdp
,09-15 07:32:09.160  5634  5702 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 07:32:09.167  5634  5644 I bt_bluedroid: config_hci_snoop_log
09-15 07:32:09.169   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 07:32:09.177  5634  5698 D BluetoothAdapterState: Current state: OFF, message: 0
,09-15 07:32:09.177  5634  5698 D BluetoothAdapterProperties: Setting state to 14
09-15 07:32:09.177  5634  5698 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-15 07:32:09.180  5634  5698 D BluetoothBondStateMachine: make
,09-15 07:32:09.183  5634  5703 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 07:32:09.189  5634  5698 I BluetoothAdapterState: Entering PendingCommandState
,09-15 07:32:09.190  5634  5634 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 07:32:09.194  5634  5634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
,09-15 07:32:09.195  5634  5634 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 07:32:09.196  5634  5634 D BtGatt.GattService: Received start request. Starting profile...
09-15 07:32:09.197  5634  5634 D BtGatt.GattService: start()
09-15 07:32:09.197  5634  5634 I bt_bluedroid: get_profile_interface gatt
,09-15 07:32:09.198  5634  5634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
,09-15 07:32:09.199  5634  5634 D BtGatt.AdvertiseManager: advertise manager created
,09-15 07:32:09.207  5634  5634 V BluetoothAdapterState: isTurningOff()=false
,09-15 07:32:09.207  5634  5634 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:09.207  5634  5634 V BluetoothAdapterState: isBleTurningOn()=true
09-15 07:32:09.207  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 07:32:09.207  5634  5698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 07:32:09.211  5634  5698 I bt_bluedroid: bt_bluedroid
,09-15 07:32:09.211  5634  5699 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 07:32:09.212  5634  5699 I bt_hci  : start_up
,09-15 07:32:09.221  5634  5699 I bt_vendor: alloc value 0xf3f78871
09-15 07:32:09.221  5634  5699 I bt_vendor: init
,09-15 07:32:09.221  5634  5699 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 07:32:09.221  5634  5699 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 07:32:09.333  5634  5699 D bt_hci  : start_up starting async portion
,09-15 07:32:09.333  5634  5706 I bt_hci  : event_finish_startup
,09-15 07:32:09.333  5634  5706 I bt_hci_h4: hal_open
,09-15 07:32:09.333  5634  5706 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-15 07:32:09.336  5634  5706 I bt_userial_vendor: device fd = 54 open
,09-15 07:32:09.329  5707  5707 W irq/448-msm_hs_: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 07:32:09.350  5634  5706 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 07:32:09.353  5634  5706 D bt_hwcfg: Chipset BCM4358A3
,09-15 07:32:09.353  5634  5706 D bt_hwcfg: Target name = [BCM4358A3]
,09-15 07:32:09.354  5634  5706 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 07:32:09.732  5634  5706 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-15 07:32:09.732  5634  5706 D bt_hwcfg: Settlement delay -- 100 ms
09-15 07:32:09.733  5634  5706 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 07:32:09.866  5634  5706 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 07:32:09.867  5634  5706 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-15 07:32:09.868  5634  5706 I bt_hwcfg: vendor lib fwcfg completed
09-15 07:32:09.868  5634  5706 I bt_vendor: firmware callback
09-15 07:32:09.868  5634  5706 I bt_hci  : firmware_config_callback
,09-15 07:32:09.887   925   925 E WifiNative-wlan0: set PNO failure
,09-15 07:32:09.889  5634  5709 I bt_btu  : btu_task pending for preload complete event
,09-15 07:32:09.889  5634  5709 I bt_btu_task: Bluetooth chip preload is complete
,09-15 07:32:09.890  5634  5709 I bt_btu  : btu_task received preload complete event
09-15 07:32:09.894  5634  5709 I         : BTE_InitTraceLevels -- TRC_HCI
09-15 07:32:09.894  5634  5709 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-15 07:32:09.894  5634  5709 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 07:32:09.894  5634  5709 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 07:32:09.894  5634  5709 I         : BTE_InitTraceLevels -- TRC_AVRC
09-15 07:32:09.894  5634  5709 I         : BTE_InitTraceLevels -- TRC_A2D
09-15 07:32:09.895  5634  5709 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-15 07:32:09.895  5634  5709 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 07:32:09.895  5634  5709 I         : BTE_InitTraceLevels -- TRC_GAP
,09-15 07:32:09.895  5634  5709 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 07:32:09.895  5634  5709 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 07:32:09.895  5634  5709 I         : BTE_InitTraceLevels -- TRC_GATT
09-15 07:32:09.895  5634  5709 I         : BTE_InitTraceLevels -- TRC_SMP
,09-15 07:32:09.895  5634  5709 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-15 07:32:09.895  5634  5709 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 07:32:09.973  5634  5709 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ef6549
,09-15 07:32:09.973  5634  5709 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ef6549 
,09-15 07:32:09.987  5634  5702 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 07:32:09.989  5634  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 07:32:09.989  5634  5702 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 07:32:09.992  5634  5702 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 07:32:09.995  5634  5702 D BluetoothAdapterProperties: Scan Mode:20
,09-15 07:32:09.996  5634  5702 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-15 07:32:09.996  5634  5702 D bt_hci  : do_postload posting postload work item
09-15 07:32:09.996  5634  5706 I bt_hci  : event_postload
09-15 07:32:09.997  5634  5706 I bt_vendor: sco_config_cb
09-15 07:32:09.997  5634  5706 I bt_hci  : sco_config_callback postload finished.
,09-15 07:32:10.000  5634  5702 D bt_bte_conf: Device ID record 1 : primary
09-15 07:32:10.000  5634  5702 D bt_bte_conf:   vendorId            = 000f
09-15 07:32:10.000  5634  5702 D bt_bte_conf:   vendorIdSource      = 0001
09-15 07:32:10.001  5634  5702 D bt_bte_conf:   product             = 1200
09-15 07:32:10.001  5634  5702 D bt_bte_conf:   version             = 1436
09-15 07:32:10.001  5634  5702 D bt_bte_conf:   clientExecutableURL = 
09-15 07:32:10.001  5634  5702 D bt_bte_conf:   serviceDescription  = 
09-15 07:32:10.001  5634  5702 D bt_bte_conf:   documentationURL    = 
09-15 07:32:10.001  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:10.001  5634  5702 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 07:32:10.001  5634  5699 D bt_stack_manager: event_start_up_stack finished
09-15 07:32:10.004  5634  5698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 07:32:10.005  5634  5698 D BluetoothAdapterProperties: Setting state to 15
09-15 07:32:10.005  5634  5698 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-15 07:32:10.005  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:10.005  5634  5706 I bt_vendor: low_power_mode_cb
09-15 07:32:10.006  5634  5698 I BluetoothAdapterState: Entering BleOnState
,09-15 07:32:10.010  5634  5698 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-15 07:32:10.010  5634  5698 D BluetoothAdapterProperties: Setting state to 11
09-15 07:32:10.010  5634  5698 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-15 07:32:10.015  5634  5634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
,09-15 07:32:10.016  5634  5634 D HeadsetService: Received start request. Starting profile...
,09-15 07:32:10.018  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:10.020  5634  5634 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 07:32:10.020  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:10.020  5634  5634 D HeadsetStateMachine: make
,09-15 07:32:10.031  5634  5698 I BluetoothAdapterState: Entering PendingCommandState
,09-15 07:32:10.032  5634  5634 D HeadsetStateMachine: max_hf_connections = 1
09-15 07:32:10.032  5634  5634 I bt_bluedroid: get_profile_interface handsfree
,09-15 07:32:10.033  5634  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 07:32:10.033  5634  5702 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-15 07:32:10.035  5634  5634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
,09-15 07:32:10.036  5634  5634 D A2dpService: Received start request. Starting profile...
,09-15 07:32:10.037  5634  5634 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-15 07:32:10.037  5634  5634 I bt_bluedroid: get_profile_interface avrcp
,09-15 07:32:10.042  5634  5634 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-15 07:32:10.043  5634  5634 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 07:32:10.043  5634  5634 D A2dpStateMachine: make
09-15 07:32:10.044  5634  5634 I bt_bluedroid: get_profile_interface a2dp
,09-15 07:32:10.046  5634  5718 D A2dpStateMachine: Enter Disconnected: -2
,09-15 07:32:10.047  5634  5634 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 07:32:10.047  5634  5634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
,09-15 07:32:10.048  5634  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 07:32:10.049  5574  5574 D BluetoothInputDevice: Proxy object connected
09-15 07:32:10.049  5634  5634 D HidService: Received start request. Starting profile...
09-15 07:32:10.049  5634  5634 I bt_bluedroid: get_profile_interface hidhost
09-15 07:32:10.049  5634  5634 D HidService: setHidService(): set to: null
09-15 07:32:10.049  5634  5702 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ed756d
09-15 07:32:10.049  5634  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 07:32:10.050  5574  5574 D HidProfile: Bluetooth service connected
09-15 07:32:10.050  5634  5634 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-15 07:32:10.050  5634  5634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
09-15 07:32:10.051  5634  5634 D HealthService: Received start request. Starting profile...
,09-15 07:32:10.052  5634  5634 I bt_bluedroid: get_profile_interface health
09-15 07:32:10.053  5634  5634 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-15 07:32:10.054  5634  5634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
,09-15 07:32:10.055  5574  5574 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 07:32:10.055  5634  5634 D PanService: Received start request. Starting profile...
09-15 07:32:10.055  5634  5634 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 07:32:10.055  5634  5634 I bt_bluedroid: get_profile_interface pan
09-15 07:32:10.056  5574  5574 D PanProfile: Bluetooth service connected
09-15 07:32:10.056  5634  5702 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-15 07:32:10.059  5634  5634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
09-15 07:32:10.059  3660  3660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 07:32:10.063  5574  5574 D BluetoothMap: Proxy object connected
,09-15 07:32:10.063  5574  5574 D MapProfile: Bluetooth service connected
09-15 07:32:10.063  5574  5574 D BluetoothMap: getConnectedDevices()
09-15 07:32:10.064  5634  5634 D BluetoothMapService: Received start request. Starting profile...
09-15 07:32:10.064  5634  5634 D BluetoothMapService: start()
09-15 07:32:10.064  5574  5574 D BluetoothMap: Bluetooth is Not enabled
,09-15 07:32:10.066  5634  5634 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-15 07:32:10.067  5634  5634 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-15 07:32:10.068  5634  5634 D BluetoothMapAppObserver: createReceiver()
,09-15 07:32:10.069  5634  5634 D BluetoothMapAppObserver: initObservers()
,09-15 07:32:10.069  5634  5634 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 07:32:10.076  5634  5634 V SapService: SapBinder()
,09-15 07:32:10.077  5634  5634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
,09-15 07:32:10.077  5634  5634 D SapService: Received start request. Starting profile...
09-15 07:32:10.077  5634  5634 V SapService: start()
09-15 07:32:10.079  5634  5634 V BluetoothAdapterState: isTurningOff()=false
09-15 07:32:10.079  5634  5634 V BluetoothAdapterState: isTurningOn()=true
09-15 07:32:10.079  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 07:32:10.079  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:10.079  5634  5634 V BluetoothAdapterState: isTurningOff()=false
09-15 07:32:10.079  5634  5634 V BluetoothAdapterState: isTurningOn()=true
09-15 07:32:10.079  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:10.079  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:10.079  5634  5634 V BluetoothAdapterState: isTurningOff()=false
09-15 07:32:10.079  5634  5634 V BluetoothAdapterState: isTurningOn()=true
09-15 07:32:10.079  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 07:32:10.079  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:10.080  5634  5716 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 07:32:10.080  5634  5634 V BluetoothAdapterState: isTurningOff()=false
09-15 07:32:10.080  5634  5634 V BluetoothAdapterState: isTurningOn()=true
09-15 07:32:10.080  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:10.080  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 07:32:10.080  5634  5634 V BluetoothAdapterState: isTurningOff()=false
,09-15 07:32:10.080  5634  5634 V BluetoothAdapterState: isTurningOn()=true
09-15 07:32:10.080  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:10.080  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 07:32:10.080  5634  5634 V BluetoothAdapterState: isTurningOff()=false
09-15 07:32:10.080  5634  5634 V BluetoothAdapterState: isTurningOn()=true
09-15 07:32:10.080  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:10.080  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:10.081  5634  5634 V BluetoothAdapterState: isTurningOff()=false
09-15 07:32:10.081  5634  5634 V BluetoothAdapterState: isTurningOn()=true
09-15 07:32:10.081  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:10.081  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:10.081  5634  5698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 07:32:10.081  5634  5698 D BluetoothAdapterProperties: ScanMode =  20
,09-15 07:32:10.081  5634  5698 D BluetoothAdapterProperties: State =  11
09-15 07:32:10.082  5634  5698 D BluetoothAdapterProperties: Setting state to 12
09-15 07:32:10.082  5634  5698 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 07:32:10.082  3195  3213 D BluetoothMap: onBluetoothStateChange: up=true
09-15 07:32:10.083  5634  5698 I BluetoothAdapterState: Entering OnState
09-15 07:32:10.085  3195  3195 D BluetoothMap: Proxy object connected
09-15 07:32:10.086  3195  3195 D MapProfile: Bluetooth service connected
09-15 07:32:10.086  3195  3195 D BluetoothMap: getConnectedDevices()
09-15 07:32:10.086  5634  5702 D BluetoothAdapterProperties: Scan Mode:21
09-15 07:32:10.086  3195  3207 D BluetoothPan: onBluetoothStateChange on: true
09-15 07:32:10.086  5634  5702 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-15 07:32:10.088   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 07:32:10.088  3195  3195 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 07:32:10.088  3195  3195 D PanProfile: Bluetooth service connected
09-15 07:32:10.089  5574  5584 D BluetoothMap: onBluetoothStateChange: up=true
09-15 07:32:10.089  5574  5586 D BluetoothPan: onBluetoothStateChange on: true
09-15 07:32:10.090  5574  5584 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 07:32:10.090  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:10.090  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:10.090  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:10.090  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:32:10.090  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:32:10.090  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:10.090  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:10.090  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:32:10.091   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 07:32:10.091  3571  3585 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:32:10.091  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:32:10.092  3195  3758 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-15 07:32:10.092   925   925 D BluetoothA2dp: Proxy object connected
09-15 07:32:10.094  3195  3213 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 07:32:10.094  3195  3195 D BluetoothA2dp: Proxy object connected
09-15 07:32:10.095  5634  5634 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 07:32:10.095   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:32:10.096  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:10.096  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:10.096  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:10.096  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:32:10.096  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:32:10.096  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:10.096  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:10.096  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:32:10.096  5574  5586 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 07:32:10.096  3195  3207 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 07:32:10.096  3195  3195 D BluetoothInputDevice: Proxy object connected
09-15 07:32:10.096  3195  3195 D HidProfile: Bluetooth service connected
09-15 07:32:10.098  5634  5634 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-15 07:32:10.098  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:32:10.098   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:32:10.099  3195  3758 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:32:10.099  5634  5634 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 07:32:10.100   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
,09-15 07:32:10.102  5574  5574 D LocalBluetoothProfileManager: Adding local A2DP profile
09-15 07:32:10.103  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:10.104  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:10.104  5634  5634 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 07:32:10.106  5634  5634 D ObexServerSockets: Succeed to create listening sockets 
09-15 07:32:10.106  5634  5634 D ObexServerSockets0: startAccept()
09-15 07:32:10.106  5634  5634 D ObexServerSockets0: prepareForNewConnect()
,09-15 07:32:10.107  5574  5574 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-15 07:32:10.108  5634  5634 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-15 07:32:10.108  5634  5634 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 07:32:10.108  5634  5724 D ObexServerSockets0: Accepting socket connection...
09-15 07:32:10.108  5634  5634 D BluetoothMapService: onReceive
,09-15 07:32:10.108  5634  5634 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 07:32:10.108  5634  5634 D BluetoothMapService: STATE_ON
09-15 07:32:10.109  5634  5725 D ObexServerSockets0: Accepting socket connection...
,09-15 07:32:10.111  5634  5726 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 07:32:10.112  5634  5726 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-15 07:32:10.112  5634  5726 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-15 07:32:10.115  5574  5574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 07:32:10.117  5574  5574 D BluetoothA2dp: Proxy object connected
09-15 07:32:10.121  3660  3660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 07:32:10.124  5574  5574 D DockEventReceiver: finishStartingService: stopping service
,09-15 07:32:10.128  5574  5574 D BluetoothPbap: Proxy object connected
,09-15 07:32:10.128  5574  5574 D PbapServerProfile: Bluetooth service connected
,09-15 07:32:10.130  3195  3195 D BluetoothPbap: Proxy object connected
09-15 07:32:10.130  3195  3195 D PbapServerProfile: Bluetooth service connected
,09-15 07:32:10.133  5634  5634 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 07:32:10.133  5634  5634 D ObexServerSockets0: prepareForNewConnect()
09-15 07:32:10.136  5634  5730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 07:32:10.148  5634  5734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 07:32:10.149  5634  5734 I BtOppRfcommListener: Accept thread started.
,09-15 07:32:10.190   925   925 D BluetoothHeadset: Proxy object connected
,09-15 07:32:10.190  3571  3586 D BluetoothHeadset: Proxy object connected
,09-15 07:32:10.191  3195  3213 D BluetoothHeadset: Proxy object connected
09-15 07:32:10.191  3195  3195 D HeadsetProfile: Bluetooth service connected
09-15 07:32:10.191   925   925 D BluetoothHeadset: Proxy object connected
09-15 07:32:10.191   925   925 D BluetoothHeadset: Proxy object connected
,09-15 07:32:10.192  3571  3845 D BluetoothHeadset: Proxy object connected
,09-15 07:32:10.196   925   942 D BluetoothHeadset: Proxy object connected
,09-15 07:32:10.199   925   942 D BluetoothHeadset: Proxy object connected
,09-15 07:32:10.200  3195  3207 D BluetoothHeadset: Proxy object connected
09-15 07:32:10.200  3195  3195 D HeadsetProfile: Bluetooth service connected
,09-15 07:32:10.210  5574  5584 D BluetoothHeadset: Proxy object connected
09-15 07:32:10.211  5574  5574 D HeadsetProfile: Bluetooth service connected
,09-15 07:32:10.951   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:32:11.952   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:32:12.115  5634  5698 D BluetoothAdapterState: Current state: ON, message: 23
09-15 07:32:12.116  5634  5698 D BluetoothAdapterProperties: Setting state to 13
09-15 07:32:12.116  5634  5698 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-15 07:32:12.117  5634  5698 D BluetoothAdapterProperties: onBluetoothDisable()
,09-15 07:32:12.125  5634  5634 D BluetoothMapService: onReceive
,09-15 07:32:12.126  5634  5634 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 07:32:12.126  5634  5634 D BluetoothMapService: STATE_TURNING_OFF
09-15 07:32:12.126  5634  5698 I BluetoothAdapterState: Entering PendingCommandState
,09-15 07:32:12.127  5634  5634 D BluetoothMapService: MAP Service closeService in
09-15 07:32:12.127  5634  5634 D BluetoothMapMasInstance0: MAP Service shutdown
09-15 07:32:12.127  5634  5634 D ObexServerSockets0: shutdown(block = true)
,09-15 07:32:12.128  5634  5634 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 07:32:12.128  5634  5634 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 07:32:12.128  5634  5724 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-15 07:32:12.128  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:12.128  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:12.128  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:12.128  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:12.128  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:32:12.128  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:32:12.128  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:12.128  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:12.128  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:32:12.128  5634  5725 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-15 07:32:12.130  5634  5702 D BluetoothAdapterProperties: Scan Mode:20
09-15 07:32:12.130  5634  5698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-15 07:32:12.130  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:12.131  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:32:12.131  5634  5711 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-15 07:32:12.134  5574  5574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 07:32:12.135  5634  5634 I BtOppRfcommListener: stopping Accept Thread
09-15 07:32:12.136  5634  5734 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 07:32:12.137  5634  5734 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 07:32:12.139  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:12.139  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:12.139  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:12.139  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:12.139  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:32:12.139  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:32:12.139  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:12.139  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:12.139  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:32:12.141  5522  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:32:12.141  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:32:12.145  5634  5634 D HeadsetService: Received stop request...Stopping profile...
09-15 07:32:12.145  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:12.148  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:12.152   925   925 D BluetoothHeadset: Proxy object disconnected
09-15 07:32:12.152  3571  3585 D BluetoothHeadset: Proxy object disconnected
09-15 07:32:12.153  3195  3207 D BluetoothHeadset: Proxy object disconnected
,09-15 07:32:12.153  5574  5586 D BluetoothHeadset: Proxy object disconnected
09-15 07:32:12.153  3195  3195 D HeadsetProfile: Bluetooth service disconnected
09-15 07:32:12.154   925   925 D BluetoothHeadset: Proxy object disconnected
09-15 07:32:12.154   925   925 D BluetoothHeadset: Proxy object disconnected
09-15 07:32:12.154  5634  5634 D A2dpService: Received stop request...Stopping profile...
09-15 07:32:12.154  5634  5718 D A2dpStateMachine: Exit Disconnected: -1
09-15 07:32:12.154  5574  5574 D DockEventReceiver: finishStartingService: stopping service
09-15 07:32:12.155  5574  5574 D HeadsetProfile: Bluetooth service disconnected
,09-15 07:32:12.157   925   925 D BluetoothA2dp: Proxy object disconnected
09-15 07:32:12.157  5574  5574 D BluetoothA2dp: Proxy object disconnected
09-15 07:32:12.157  3195  3195 D BluetoothA2dp: Proxy object disconnected
09-15 07:32:12.158  5634  5634 D HidService: Received stop request...Stopping profile...
09-15 07:32:12.158  5634  5634 D HidService: Stopping Bluetooth HidService
,09-15 07:32:12.159  5574  5574 D BluetoothInputDevice: Proxy object disconnected
09-15 07:32:12.159  5574  5574 D HidProfile: Bluetooth service disconnected
09-15 07:32:12.160  3195  3195 D BluetoothInputDevice: Proxy object disconnected
09-15 07:32:12.160  3195  3195 D HidProfile: Bluetooth service disconnected
09-15 07:32:12.162  5634  5634 D HealthService: Received stop request...Stopping profile...
,09-15 07:32:12.163  3660  3660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 07:32:12.164  5634  5634 D PanService: Received stop request...Stopping profile...
,09-15 07:32:12.166  5574  5574 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 07:32:12.166  3195  3195 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-15 07:32:12.166  3195  3195 D PanProfile: Bluetooth service disconnected
09-15 07:32:12.166  5574  5574 D PanProfile: Bluetooth service disconnected
09-15 07:32:12.166  5634  5634 D BluetoothMapService: Received stop request...Stopping profile...
09-15 07:32:12.167  5634  5634 D BluetoothMapService: stop()
09-15 07:32:12.167  5634  5634 D BluetoothMapAppObserver: deinitObservers()
09-15 07:32:12.167  5634  5634 D BluetoothMapAppObserver: removeReceiver()
09-15 07:32:12.168  3195  3195 D BluetoothMap: Proxy object disconnected
09-15 07:32:12.168  5574  5574 D BluetoothMap: Proxy object disconnected
09-15 07:32:12.168  3195  3195 D MapProfile: Bluetooth service disconnected
09-15 07:32:12.168  5574  5574 D MapProfile: Bluetooth service disconnected
09-15 07:32:12.169  5634  5634 D SapService: Received stop request...Stopping profile...
09-15 07:32:12.169  5634  5634 V SapService: stop()
,09-15 07:32:12.171  5634  5634 V BluetoothAdapterState: isTurningOff()=true
09-15 07:32:12.171  5634  5634 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:12.171  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:12.171  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 07:32:12.173  5634  5634 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-15 07:32:12.173  5634  5634 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 07:32:12.173  5634  5709 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:32:12.173  5634  5709 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:32:12.173  5634  5634 V BluetoothAdapterState: isTurningOff()=true
09-15 07:32:12.173  5634  5709 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:32:12.173  5634  5634 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:12.173  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:12.173  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:12.173  5634  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 07:32:12.173  5634  5702 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-15 07:32:12.174  5634  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-15 07:32:12.174  5634  5709 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:32:12.174  5634  5634 V BluetoothAdapterState: isTurningOff()=true
09-15 07:32:12.174  5634  5634 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:12.174  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:12.174  5634  5709 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:32:12.174  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 07:32:12.175  5634  5709 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 07:32:12.175  5634  5709 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 07:32:12.175  5634  5634 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 07:32:12.175  5634  5709 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 07:32:12.175  5634  5634 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 07:32:12.175  5634  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 07:32:12.175  5634  5709 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-15 07:32:12.180  5574  5574 D BluetoothPbap: Proxy object disconnected
09-15 07:32:12.180  5574  5574 D PbapServerProfile: Bluetooth service disconnected
09-15 07:32:12.180  3195  3195 D BluetoothPbap: Proxy object disconnected
09-15 07:32:12.181  3195  3195 D PbapServerProfile: Bluetooth service disconnected
09-15 07:32:12.181  5634  5634 V BluetoothAdapterState: isTurningOff()=true
09-15 07:32:12.181  5634  5634 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:12.181  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:12.181  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 07:32:12.181  5634  5634 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-15 07:32:12.181  5634  5702 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 07:32:12.181  5634  5634 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-15 07:32:12.181  5634  5634 V BluetoothAdapterState: isTurningOff()=true
09-15 07:32:12.182  5634  5634 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:12.182  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:12.182  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:12.182  5634  5634 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 07:32:12.182  5634  5634 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-15 07:32:12.183  5634  5634 D BluetoothMapService: MAP Service closeService in
09-15 07:32:12.183  5634  5634 V BluetoothAdapterState: isTurningOff()=true
09-15 07:32:12.183  5634  5634 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:12.183  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:12.183  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:12.184  5634  5634 D BluetoothMapService: cleanup()
09-15 07:32:12.184  5634  5634 D BluetoothMapService: MAP Service closeService in
09-15 07:32:12.184  5634  5634 V BluetoothAdapterState: isTurningOff()=true
09-15 07:32:12.184  5634  5634 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:12.184  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:12.184  5634  5634 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 07:32:12.186  5634  5698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 07:32:12.186  5634  5698 D BluetoothAdapterProperties: Setting state to 15
09-15 07:32:12.186  5634  5698 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 07:32:12.187  5634  5698 I BluetoothAdapterState: Entering BleOnState
09-15 07:32:12.187  3195  3213 D BluetoothMap: onBluetoothStateChange: up=false
09-15 07:32:12.190  3195  3207 D BluetoothPan: onBluetoothStateChange on: false
09-15 07:32:12.191   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 07:32:12.191  5574  5586 D BluetoothMap: onBluetoothStateChange: up=false
,09-15 07:32:12.192  5574  5584 D BluetoothPan: onBluetoothStateChange on: false
,09-15 07:32:12.193  5574  5586 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 07:32:12.194   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 07:32:12.194  5574  5584 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 07:32:12.194  3571  3586 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:32:12.195  3195  3758 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 07:32:12.195  3195  3213 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 07:32:12.196   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:32:12.196  5574  5586 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-15 07:32:12.197  3195  3207 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 07:32:12.197  5574  5584 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:32:12.197   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:32:12.197  3195  3758 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:32:12.198  5634  5698 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 07:32:12.198  5634  5698 D BluetoothAdapterProperties: Setting state to 16
,09-15 07:32:12.198  5634  5698 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-15 07:32:12.199  5634  5698 D BluetoothAdapterProperties: onBleDisable
09-15 07:32:12.199  5634  5698 I BluetoothAdapterState: Entering PendingCommandState
09-15 07:32:12.199  5634  5699 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-15 07:32:12.200  5634  5709 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-15 07:32:12.200  5634  5709 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:32:12.202  5634  5702 D BluetoothAdapterProperties: Scan Mode:20
09-15 07:32:12.202  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:12.203  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:12.204  5574  5574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 07:32:12.205  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:12.211  3660  3660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 07:32:12.214  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:12.218  5574  5574 D DockEventReceiver: finishStartingService: stopping service
,09-15 07:32:12.410  5634  5702 I bt_hci  : shut_down
,09-15 07:32:12.416  5634  5706 D bt_hwcfg: hw_epilog_process
,09-15 07:32:12.416  5634  5706 I bt_vendor: low_power_mode_cb
,09-15 07:32:12.419  5634  5706 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-15 07:32:12.419  5634  5706 I bt_vendor: epilog_cb
,09-15 07:32:12.419  5634  5706 I bt_hci  : epilog_finished_callback
09-15 07:32:12.422  5634  5702 I bt_hci_h4: hal_close
09-15 07:32:12.423  5634  5702 I bt_userial_vendor: device fd = 54 close
,09-15 07:32:12.540  5634  5699 D bt_stack_manager: event_shut_down_stack finished.
,09-15 07:32:12.541  5634  5698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-15 07:32:12.545  5634  5698 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-15 07:32:12.546  5634  5634 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 07:32:12.547  5634  5634 D BtGatt.GattService: Received stop request...Stopping profile...
,09-15 07:32:12.547  5634  5634 D BtGatt.GattService: stop()
09-15 07:32:12.547  5634  5634 D BtGatt.AdvertiseManager: advertise clients cleared
,09-15 07:32:12.551  5634  5634 V BluetoothAdapterState: isTurningOff()=false
,09-15 07:32:12.551  5634  5634 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:12.551  5634  5634 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:12.551  5634  5634 V BluetoothAdapterState: isBleTurningOff()=true
09-15 07:32:12.552  5634  5698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-15 07:32:12.552  5634  5698 D BluetoothAdapterProperties: Setting state to 10
,09-15 07:32:12.553  5634  5698 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 07:32:12.553  5634  5698 I BluetoothAdapterState: Entering OffState
09-15 07:32:12.555   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-15 07:32:12.567  5634  5634 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-15 07:32:12.568  5634  5634 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 07:32:12.568  5634  5634 I BluetoothServiceJni: cleanupNative: return from cleanup
09-15 07:32:12.569  5634  5699 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 07:32:12.577  5634  5634 I art     : System.exit called, status: 0
,09-15 07:32:12.577  5634  5634 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-15 07:32:12.603   925  3499 I ActivityManager: Process com.android.bluetooth (pid 5634) has died
,09-15 07:32:12.953   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:32:13.954   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:32:14.955   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:32:15.113  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 07:32:15.113  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:32:15.956   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 07:32:18.119  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:32:18.120  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f4fba26 added. We now have 6 listener(s)
09-15 07:32:18.120  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 07:32:18.123  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 07:32:18.123  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f0e0667 added. We now have 7 listener(s)
09-15 07:32:18.123  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:18.124  5522  5568 I System.out: IsBluetoothEnabled
,09-15 07:32:18.132  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:18.159   925   942 I ActivityManager: Start proc 5742:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-15 07:32:18.240  5742  5742 D AdapterServiceConfig: Adding HeadsetService
,09-15 07:32:18.241  5742  5742 D AdapterServiceConfig: Adding A2dpService
09-15 07:32:18.241  5742  5742 D AdapterServiceConfig: Adding HidService
09-15 07:32:18.241  5742  5742 D AdapterServiceConfig: Adding HealthService
09-15 07:32:18.241  5742  5742 D AdapterServiceConfig: Adding PanService
09-15 07:32:18.241  5742  5742 D AdapterServiceConfig: Adding GattService
09-15 07:32:18.242  5742  5742 D AdapterServiceConfig: Adding BluetoothMapService
09-15 07:32:18.242  5742  5742 D AdapterServiceConfig: Adding SapService
,09-15 07:32:18.253   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c348903:true
,09-15 07:32:18.253  5742  5742 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 07:32:18.256  5742  5742 I bt_bluedroid: init
,09-15 07:32:18.256  5742  5754 I BluetoothAdapterState: Entering OffState
,09-15 07:32:18.258  5742  5755 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-15 07:32:18.258  5742  5755 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 07:32:18.258  5742  5755 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 07:32:18.259  5742  5755 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-15 07:32:18.260  5742  5742 I bt_bluedroid: get_profile_interface socket
,09-15 07:32:18.261  5742  5758 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 07:32:18.261  5742  5742 I bt_bluedroid: get_profile_interface sdp
09-15 07:32:18.263  5742  5758 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 07:32:18.267  5742  5753 I bt_bluedroid: config_hci_snoop_log
,09-15 07:32:18.268   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 07:32:18.273  5742  5754 D BluetoothAdapterState: Current state: OFF, message: 0
,09-15 07:32:18.273  5742  5754 D BluetoothAdapterProperties: Setting state to 14
09-15 07:32:18.273  5742  5754 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-15 07:32:18.274  5742  5754 D BluetoothBondStateMachine: make
,09-15 07:32:18.276  5742  5759 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 07:32:18.279  5742  5754 I BluetoothAdapterState: Entering PendingCommandState
,09-15 07:32:18.280  5742  5742 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 07:32:18.282  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
09-15 07:32:18.282  5742  5742 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 07:32:18.283  5742  5742 D BtGatt.GattService: Received start request. Starting profile...
09-15 07:32:18.283  5742  5742 D BtGatt.GattService: start()
09-15 07:32:18.283  5742  5742 I bt_bluedroid: get_profile_interface gatt
09-15 07:32:18.284  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
09-15 07:32:18.284  5742  5742 D BtGatt.AdvertiseManager: advertise manager created
,09-15 07:32:18.289  5742  5742 V BluetoothAdapterState: isTurningOff()=false
,09-15 07:32:18.289  5742  5742 V BluetoothAdapterState: isTurningOn()=false
09-15 07:32:18.289  5742  5742 V BluetoothAdapterState: isBleTurningOn()=true
09-15 07:32:18.289  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:18.290  5742  5754 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 07:32:18.291  5742  5754 I bt_bluedroid: bt_bluedroid
09-15 07:32:18.291  5742  5755 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 07:32:18.292  5742  5755 I bt_hci  : start_up
,09-15 07:32:18.297  5742  5755 I bt_vendor: alloc value 0xf3ff3871
09-15 07:32:18.297  5742  5755 I bt_vendor: init
09-15 07:32:18.297  5742  5755 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 07:32:18.297  5742  5755 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 07:32:18.409  5742  5755 D bt_hci  : start_up starting async portion
09-15 07:32:18.409  5742  5762 I bt_hci  : event_finish_startup
,09-15 07:32:18.409  5742  5762 I bt_hci_h4: hal_open
09-15 07:32:18.410  5742  5762 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-15 07:32:18.406  5763  5763 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 07:32:18.412  5742  5762 I bt_userial_vendor: device fd = 54 open
,09-15 07:32:18.426  5742  5762 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 07:32:18.428  5742  5762 D bt_hwcfg: Chipset BCM4358A3
,09-15 07:32:18.428  5742  5762 D bt_hwcfg: Target name = [BCM4358A3]
,09-15 07:32:18.429  5742  5762 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 07:32:18.833  5742  5762 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-15 07:32:18.834  5742  5762 D bt_hwcfg: Settlement delay -- 100 ms
,09-15 07:32:18.834  5742  5762 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 07:32:18.969  5742  5762 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 07:32:18.969  5742  5762 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-15 07:32:18.971  5742  5762 I bt_hwcfg: vendor lib fwcfg completed
,09-15 07:32:18.972  5742  5762 I bt_vendor: firmware callback
09-15 07:32:18.972  5742  5762 I bt_hci  : firmware_config_callback
,09-15 07:32:18.980  5742  5765 I bt_btu  : btu_task pending for preload complete event
09-15 07:32:18.980  5742  5765 I bt_btu_task: Bluetooth chip preload is complete
,09-15 07:32:18.980  5742  5765 I bt_btu  : btu_task received preload complete event
,09-15 07:32:18.987  5742  5765 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 07:32:18.988  5742  5765 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 07:32:18.988  5742  5765 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 07:32:18.988  5742  5765 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 07:32:18.988  5742  5765 I         : BTE_InitTraceLevels -- TRC_AVRC
09-15 07:32:18.988  5742  5765 I         : BTE_InitTraceLevels -- TRC_A2D
,09-15 07:32:18.988  5742  5765 I         : BTE_InitTraceLevels -- TRC_BNEP
09-15 07:32:18.988  5742  5765 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 07:32:18.989  5742  5765 I         : BTE_InitTraceLevels -- TRC_GAP
09-15 07:32:18.989  5742  5765 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 07:32:18.989  5742  5765 I         : BTE_InitTraceLevels -- TRC_SDP
,09-15 07:32:18.989  5742  5765 I         : BTE_InitTraceLevels -- TRC_GATT
09-15 07:32:18.989  5742  5765 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 07:32:18.989  5742  5765 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-15 07:32:18.989  5742  5765 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 07:32:19.073  5742  5765 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f71549
,09-15 07:32:19.074  5742  5765 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f71549 
,09-15 07:32:19.090  5742  5758 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 07:32:19.091  5742  5758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 07:32:19.092  5742  5758 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 07:32:19.095  5742  5758 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 07:32:19.098  5742  5758 D BluetoothAdapterProperties: Scan Mode:20
,09-15 07:32:19.098  5742  5758 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 07:32:19.098  5742  5758 D bt_hci  : do_postload posting postload work item
,09-15 07:32:19.099  5742  5762 I bt_hci  : event_postload
09-15 07:32:19.099  5742  5762 I bt_vendor: sco_config_cb
09-15 07:32:19.099  5742  5762 I bt_hci  : sco_config_callback postload finished.
,09-15 07:32:19.101  5742  5758 D bt_bte_conf: Device ID record 1 : primary
09-15 07:32:19.102  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:19.101  5742  5758 D bt_bte_conf:   vendorId            = 000f
,09-15 07:32:19.107  5742  5762 I bt_vendor: low_power_mode_cb
09-15 07:32:19.118  5742  5758 D bt_bte_conf:   vendorIdSource      = 0001
09-15 07:32:19.118  5742  5758 D bt_bte_conf:   product             = 1200
09-15 07:32:19.118  5742  5758 D bt_bte_conf:   version             = 1436
09-15 07:32:19.118  5742  5758 D bt_bte_conf:   clientExecutableURL = 
09-15 07:32:19.118  5742  5758 D bt_bte_conf:   serviceDescription  = 
09-15 07:32:19.118  5742  5758 D bt_bte_conf:   documentationURL    = 
09-15 07:32:19.119  5742  5758 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 07:32:19.119  5742  5755 D bt_stack_manager: event_start_up_stack finished
,09-15 07:32:19.119  5742  5754 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 07:32:19.119  5742  5754 D BluetoothAdapterProperties: Setting state to 15
09-15 07:32:19.120  5742  5754 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-15 07:32:19.120  5742  5754 I BluetoothAdapterState: Entering BleOnState
,09-15 07:32:19.123  5742  5754 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-15 07:32:19.124  5742  5754 D BluetoothAdapterProperties: Setting state to 11
09-15 07:32:19.124  5742  5754 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-15 07:32:19.134  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:19.136  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
,09-15 07:32:19.137  5742  5742 D HeadsetService: Received start request. Starting profile...
09-15 07:32:19.139  5742  5742 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 07:32:19.139  5742  5742 D HeadsetStateMachine: make
,09-15 07:32:19.146  5742  5754 I BluetoothAdapterState: Entering PendingCommandState
,09-15 07:32:19.150  5742  5742 D HeadsetStateMachine: max_hf_connections = 1
,09-15 07:32:19.150  5742  5742 I bt_bluedroid: get_profile_interface handsfree
09-15 07:32:19.150  5742  5758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 07:32:19.151  5742  5758 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-15 07:32:19.154  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
09-15 07:32:19.154  5742  5742 D A2dpService: Received start request. Starting profile...
,09-15 07:32:19.155  5742  5742 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-15 07:32:19.155  5742  5742 I bt_bluedroid: get_profile_interface avrcp
,09-15 07:32:19.160  5742  5742 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-15 07:32:19.160  5742  5742 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 07:32:19.161  5742  5742 D A2dpStateMachine: make
09-15 07:32:19.161  5742  5742 I bt_bluedroid: get_profile_interface a2dp
,09-15 07:32:19.162  5742  5758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 07:32:19.163  5742  5773 D A2dpStateMachine: Enter Disconnected: -2
,09-15 07:32:19.164  5742  5742 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 07:32:19.164  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
,09-15 07:32:19.165  5742  5742 D HidService: Received start request. Starting profile...
09-15 07:32:19.165  5742  5742 I bt_bluedroid: get_profile_interface hidhost
09-15 07:32:19.165  5742  5742 D HidService: setHidService(): set to: null
09-15 07:32:19.165  5742  5758 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f5256d
09-15 07:32:19.165  5742  5758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 07:32:19.167  5742  5742 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 07:32:19.168  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
,09-15 07:32:19.168  5742  5742 D HealthService: Received start request. Starting profile...
09-15 07:32:19.168  3660  3660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 07:32:19.169  5742  5742 I bt_bluedroid: get_profile_interface health
,09-15 07:32:19.170  5742  5742 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-15 07:32:19.171  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
,09-15 07:32:19.171  5742  5742 D PanService: Received start request. Starting profile...
09-15 07:32:19.171  5742  5742 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 07:32:19.171  5742  5742 I bt_bluedroid: get_profile_interface pan
09-15 07:32:19.172  5742  5758 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-15 07:32:19.174  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
,09-15 07:32:19.174  5742  5742 D BluetoothMapService: Received start request. Starting profile...
,09-15 07:32:19.175  5742  5742 D BluetoothMapService: start()
,09-15 07:32:19.177  5742  5742 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-15 07:32:19.178  5742  5742 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-15 07:32:19.178  5742  5742 D BluetoothMapAppObserver: createReceiver()
,09-15 07:32:19.179  5742  5742 D BluetoothMapAppObserver: initObservers()
,09-15 07:32:19.179  5742  5742 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 07:32:19.186  5742  5742 V SapService: SapBinder()
09-15 07:32:19.186  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
,09-15 07:32:19.186  5742  5742 D SapService: Received start request. Starting profile...
09-15 07:32:19.186  5742  5742 V SapService: start()
,09-15 07:32:19.190  5742  5742 V BluetoothAdapterState: isTurningOff()=false
,09-15 07:32:19.190  5742  5742 V BluetoothAdapterState: isTurningOn()=true
09-15 07:32:19.190  5742  5742 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:19.190  5742  5771 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 07:32:19.190  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:19.190  5742  5742 V BluetoothAdapterState: isTurningOff()=false
09-15 07:32:19.190  5742  5742 V BluetoothAdapterState: isTurningOn()=true
09-15 07:32:19.190  5742  5742 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:19.190  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 07:32:19.191  5742  5742 V BluetoothAdapterState: isTurningOff()=false
09-15 07:32:19.191  5742  5742 V BluetoothAdapterState: isTurningOn()=true
09-15 07:32:19.191  5742  5742 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:19.191  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:19.191  5742  5742 V BluetoothAdapterState: isTurningOff()=false
09-15 07:32:19.191  5742  5742 V BluetoothAdapterState: isTurningOn()=true
09-15 07:32:19.191  5742  5742 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:19.191  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 07:32:19.192  5742  5742 V BluetoothAdapterState: isTurningOff()=false
09-15 07:32:19.192  5742  5742 V BluetoothAdapterState: isTurningOn()=true
09-15 07:32:19.192  5742  5742 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:19.192  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 07:32:19.192  5742  5742 V BluetoothAdapterState: isTurningOff()=false
,09-15 07:32:19.192  5742  5742 V BluetoothAdapterState: isTurningOn()=true
09-15 07:32:19.192  5742  5742 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:19.193  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:19.194  5742  5742 V BluetoothAdapterState: isTurningOff()=false
09-15 07:32:19.194  5742  5742 V BluetoothAdapterState: isTurningOn()=true
09-15 07:32:19.194  5742  5742 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:32:19.194  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:32:19.194  5742  5754 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-15 07:32:19.194  5742  5754 D BluetoothAdapterProperties: ScanMode =  20
09-15 07:32:19.194  5742  5754 D BluetoothAdapterProperties: State =  11
09-15 07:32:19.197  5742  5758 D BluetoothAdapterProperties: Scan Mode:21
09-15 07:32:19.197  5742  5758 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 07:32:19.198  5742  5754 D BluetoothAdapterProperties: Setting state to 12
09-15 07:32:19.198  5742  5754 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-15 07:32:19.198  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:19.198  3195  3758 D BluetoothMap: onBluetoothStateChange: up=true
09-15 07:32:19.198  5742  5754 I BluetoothAdapterState: Entering OnState
09-15 07:32:19.200  3195  3207 D BluetoothPan: onBluetoothStateChange on: true
09-15 07:32:19.201  3195  3195 D BluetoothMap: Proxy object connected
09-15 07:32:19.201  3195  3195 D MapProfile: Bluetooth service connected
09-15 07:32:19.201  3195  3195 D BluetoothMap: getConnectedDevices()
09-15 07:32:19.202   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:32:19.202  5574  5586 D BluetoothMap: onBluetoothStateChange: up=true
,09-15 07:32:19.204  3195  3195 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 07:32:19.204  3195  3195 D PanProfile: Bluetooth service connected
,09-15 07:32:19.204  5742  5742 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 07:32:19.205  5742  5742 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-15 07:32:19.205  5574  5584 D BluetoothPan: onBluetoothStateChange on: true
09-15 07:32:19.206  5742  5742 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 07:32:19.207  5574  5586 D BluetoothPbap: onBluetoothStateChange: up=true
,09-15 07:32:19.208  5742  5742 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 07:32:19.210  5742  5742 D ObexServerSockets: Succeed to create listening sockets 
,09-15 07:32:19.210   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 07:32:19.210  5742  5742 D ObexServerSockets0: startAccept()
09-15 07:32:19.210  5742  5742 D ObexServerSockets0: prepareForNewConnect()
09-15 07:32:19.211  5574  5584 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 07:32:19.212  5742  5742 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-15 07:32:19.212  5742  5742 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-15 07:32:19.212  5574  5574 D BluetoothMap: Proxy object connected
09-15 07:32:19.212  5574  5574 D MapProfile: Bluetooth service connected
09-15 07:32:19.212  5574  5574 D BluetoothMap: getConnectedDevices()
09-15 07:32:19.213  5742  5780 D ObexServerSockets0: Accepting socket connection...
09-15 07:32:19.213  5742  5779 D ObexServerSockets0: Accepting socket connection...
,09-15 07:32:19.214   925   925 D BluetoothA2dp: Proxy object connected
,09-15 07:32:19.214  3571  3585 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:32:19.215  3195  3758 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-15 07:32:19.217  3195  3195 D BluetoothA2dp: Proxy object connected
,09-15 07:32:19.217  3195  3213 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-15 07:32:19.219   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 07:32:19.220  5574  5584 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-15 07:32:19.220  3195  3195 D BluetoothInputDevice: Proxy object connected
09-15 07:32:19.220  3195  3195 D HidProfile: Bluetooth service connected
09-15 07:32:19.222  3195  3207 D BluetoothPbap: onBluetoothStateChange: up=true
,09-15 07:32:19.224  5574  5778 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:32:19.225   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:32:19.225  3195  3213 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 07:32:19.226  5574  5574 D BluetoothPan: BluetoothPAN Proxy object connected
,09-15 07:32:19.226  5574  5574 D PanProfile: Bluetooth service connected
09-15 07:32:19.226  5574  5574 D BluetoothA2dp: Proxy object connected
09-15 07:32:19.226   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
09-15 07:32:19.227  5742  5742 D BluetoothMapService: onReceive
09-15 07:32:19.227  5742  5742 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 07:32:19.227  5742  5742 D BluetoothMapService: STATE_ON
,09-15 07:32:19.229  5574  5574 D BluetoothInputDevice: Proxy object connected
09-15 07:32:19.229  5574  5574 D HidProfile: Bluetooth service connected
09-15 07:32:19.232  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:19.232  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:19.232  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:19.232  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:32:19.232  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:32:19.232  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:19.232  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:19.232  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:32:19.232  5742  5783 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 07:32:19.234  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:32:19.234  5742  5783 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-15 07:32:19.235  5742  5783 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-15 07:32:19.236  5574  5574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 07:32:19.242  3660  3660 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 07:32:19.242  5574  5574 D DockEventReceiver: finishStartingService: stopping service
,09-15 07:32:19.250  5574  5574 D BluetoothPbap: Proxy object connected
,09-15 07:32:19.250  5574  5574 D PbapServerProfile: Bluetooth service connected
,09-15 07:32:19.253  5742  5742 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 07:32:19.253  5742  5742 D ObexServerSockets0: prepareForNewConnect()
09-15 07:32:19.256  5742  5787 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 07:32:19.257  3195  3195 D BluetoothPbap: Proxy object connected
09-15 07:32:19.257  3195  3195 D PbapServerProfile: Bluetooth service connected
,09-15 07:32:19.268  5742  5791 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 07:32:19.270  5742  5791 I BtOppRfcommListener: Accept thread started.
,09-15 07:32:19.304   925   925 D BluetoothHeadset: Proxy object connected
,09-15 07:32:19.304  3571  3586 D BluetoothHeadset: Proxy object connected
,09-15 07:32:19.305  3195  3758 D BluetoothHeadset: Proxy object connected
,09-15 07:32:19.305  3195  3195 D HeadsetProfile: Bluetooth service connected
09-15 07:32:19.305  5574  5584 D BluetoothHeadset: Proxy object connected
09-15 07:32:19.306   925   925 D BluetoothHeadset: Proxy object connected
09-15 07:32:19.306   925   925 D BluetoothHeadset: Proxy object connected
09-15 07:32:19.307  5574  5574 D HeadsetProfile: Bluetooth service connected
,09-15 07:32:19.315  3571  3845 D BluetoothHeadset: Proxy object connected
,09-15 07:32:19.320   925   942 D BluetoothHeadset: Proxy object connected
,09-15 07:32:19.325  5574  5778 D BluetoothHeadset: Proxy object connected
,09-15 07:32:19.326   925   942 D BluetoothHeadset: Proxy object connected
09-15 07:32:19.326  3195  3207 D BluetoothHeadset: Proxy object connected
,09-15 07:32:19.326  3195  3195 D HeadsetProfile: Bluetooth service connected
09-15 07:32:19.326  5574  5574 D HeadsetProfile: Bluetooth service connected
,09-15 07:32:20.150  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:20.150  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:20.150  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:20.150  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:32:20.150  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:32:20.150  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:20.150  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:20.150  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:32:20.157  5522  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:32:20.160  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 07:32:20.161  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9964c14 added. We now have 8 listener(s)
09-15 07:32:20.161  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:20.165   925  3593 D WifiService: setWifiEnabled: false pid=5522, uid=10077
09-15 07:32:20.165   925  3593 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 07:32:20.177  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:20.178   925  3591 D WifiService: setWifiEnabled: true pid=5522, uid=10077
,09-15 07:32:20.178   925  3591 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 07:32:20.186   508   919 D SoftapController: Softap fwReload - Ok
,09-15 07:32:20.190   508   919 D CommandListener: Setting iface cfg
09-15 07:32:20.190   508   919 D CommandListener: Trying to bring down wlan0
,09-15 07:32:20.191   508   919 D CommandListener: Clearing all IP addresses on wlan0
,09-15 07:32:20.196   925  3041 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 07:32:20.812   925  3041 D wifi    : set interface wlan0 flags (UP)
,09-15 07:32:20.813   925  3041 I WifiHAL : Initializing wifi
09-15 07:32:20.813   925  3041 I WifiHAL : Creating socket
09-15 07:32:20.819   925  3041 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-15 07:32:20.819   925  3041 D wifi    : Did set static halHandle = 0x7f808a5380
,09-15 07:32:20.820   925  3041 D wifi    : halHandle = 0x7f808a5380, mVM = 0x7f9c9cd140, mCls = 0x20193e
09-15 07:32:20.820   925  3041 D wifi    : array field set
09-15 07:32:20.820   925  3041 I WifiNative-HAL: interface[0] = wlan0
09-15 07:32:20.822   925  5797 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547617395584
09-15 07:32:20.822   925  5797 D wifi    : waitForHalEvents called, vm = 0x7f9c9cd140, obj = 0x20193e, env = 0x7f7cf0ba80
,09-15 07:32:20.826   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 07:32:20.882  5798  5798 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 07:32:20.902  5798  5798 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 07:32:20.923   925  3041 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-15 07:32:20.927  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:20.945  5798  5798 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 07:32:20.945  5798  5798 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 07:32:20.959   925  3041 D WifiConfigStore: Loading config and enabling all networks 
,09-15 07:32:20.964  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:20.964  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:20.964  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:20.964  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:32:20.964  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:32:20.964  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:20.964  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:20.964  5522  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:32:20.966  5522  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:32:20.971   925  3041 D WifiConfigStore: loaded 0 passpoint configs
,09-15 07:32:20.971   925  3041 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 07:32:20.972   925  3041 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-15 07:32:20.972   925  3041 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-15 07:32:20.973   925  3041 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-15 07:32:20.974   925  3041 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 07:32:20.974   925  3041 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-15 07:32:20.974   925  3041 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 07:32:20.977   925  3041 D WifiNative-HAL: Setting external_sim to 1
,09-15 07:32:20.977  4366  4366 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 07:32:20.978   925  3041 D wifi    : setting dfs flag to true, 0x7f81f39020
,09-15 07:32:20.978   925  3041 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 07:32:20.978   925  3041 D wifi    : setting scan oui 0x7f81f39020
09-15 07:32:20.978   925  3041 D WifiHAL : Sending mac address OUI
,09-15 07:32:20.994   925  3041 E native  : do suspend true
,09-15 07:32:21.000   925  3041 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-15 07:32:21.000   925   925 D RttService: SCAN_AVAILABLE : 3
09-15 07:32:21.000   508   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-15 07:32:21.000   925  3148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-15 07:32:21.001   508   919 D CommandListener: Setting iface cfg
,09-15 07:32:21.005   925  3040 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '75 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 75 Failed to set address (No such device)'
,09-15 07:32:21.005   925  3040 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 07:32:21.011   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=249678 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,09-15 07:32:21.012   925  3040 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 07:32:21.012   925  3040 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 07:32:21.197  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:32:21.197  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:21.197  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:21.197  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:32:21.197  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:32:21.197  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:21.197  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:21.197  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:32:21.202  5522  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:32:21.211  5522  5568 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-15 07:32:21.212  5522  5568 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-15 07:32:21.216  5522  5568 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@47facbc Bundle[{}]
,09-15 07:32:21.217  5522  5568 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-15 07:32:21.218  5522  5568 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-15 07:32:21.220  5522  5568 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-15 07:32:21.221  5522  5568 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-15 07:32:21.223  5522  5568 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-15 07:32:21.225  5522  5568 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-15 07:32:21.232  5522  5568 I System.out: Running OutgoingSocketThread
,09-15 07:32:21.234  5522  5809 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 152)
09-15 07:32:21.235  5522  5809 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49118
,09-15 07:32:21.235  5522  5809 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-15 07:32:22.235  5522  5568 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 153)
,09-15 07:32:22.235  5522  5568 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 153)
,09-15 07:32:22.241  5522  5568 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,09-15 07:32:22.243  5522  5568 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-15 07:32:22.243  5522  5568 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 159)
,09-15 07:32:22.248  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 07:32:22.249  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba4acbd added. We now have 2 listener(s)
,09-15 07:32:22.253  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 07:32:22.253  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:32:22.253  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:32:22.254  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:32:22.254  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ed52b2 added. We now have 9 listener(s)
09-15 07:32:22.254  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:22.255  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 07:32:22.258  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 07:32:22.263  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:32:22.263  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:22.263  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:22.263  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:32:22.263  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:32:22.263  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:22.263  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:22.263  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:32:22.266  5522  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:32:22.266  5522  5568 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:32:22.266  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:32:22.266  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9961580 added. We now have 3 listener(s)
09-15 07:32:22.268  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:22.268  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:32:22.268  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:32:22.268  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:32:22.269  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:32:22.269  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7457b9 added. We now have 10 listener(s)
,09-15 07:32:22.269  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:22.269  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:32:22.269  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:22.269  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:22.270  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:22.270  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.270  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:32:22.270  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-15 07:32:22.270  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba4acbd removed from the list
09-15 07:32:22.270  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:22.270  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ed52b2 removed from the list
09-15 07:32:22.270  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:22.271  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 07:32:22.271  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:22.272  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.272  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:32:22.273  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:22.274  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:22.274  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 07:32:22.274  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ed52b2 not in the list
09-15 07:32:22.274  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.274  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:32:22.276  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 07:32:22.276  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:22.276  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:22.276  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7457b9 removed from the list
09-15 07:32:22.276  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:22.276  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.276  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:32:22.276  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:32:22.276  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9961580 removed from the list
09-15 07:32:22.277  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:32:22.277  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@659e7fe added. We now have 2 listener(s)
09-15 07:32:22.279  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:32:22.280  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:32:22.280  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:32:22.280  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:32:22.280  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56b5b5f added. We now have 9 listener(s)
09-15 07:32:22.280  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 07:32:22.281  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 07:32:22.284  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 07:32:22.288  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:32:22.288  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:22.288  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:22.288  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:32:22.288  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:32:22.288  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:22.288  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:22.288  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:32:22.290  5522  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:32:22.290  5522  5568 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:32:22.290  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:32:22.290  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f9b675 added. We now have 3 listener(s)
09-15 07:32:22.292  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:22.292  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:32:22.292  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:32:22.292  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:32:22.293  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 07:32:22.293  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68860a added. We now have 10 listener(s)
09-15 07:32:22.293  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:22.293  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:32:22.293  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 07:32:22.293  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 07:32:22.293  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:32:22.293  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 07:32:22.293  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:22.298  5522  5568 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 07:32:22.298  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 07:32:22.302  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 07:32:22.303  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 07:32:22.303  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 07:32:22.306  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 07:32:22.307  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 07:32:22.307  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 07:32:22.307  5522  5568 D BluetoothAdapter: STATE_ON
,09-15 07:32:22.311  5742  5753 D BtGatt.GattService: registerClient() - UUID=065e1d7d-4ab9-44ed-836d-a19caa370fa9
,09-15 07:32:22.312  5742  5758 D BtGatt.GattService: onClientRegistered() - UUID=065e1d7d-4ab9-44ed-836d-a19caa370fa9, clientIf=5
09-15 07:32:22.313  5522  5610 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 07:32:22.314  5742  5752 D BtGatt.GattService: start scan with filters
,09-15 07:32:22.317  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 07:32:22.317  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 07:32:22.317  5742  5761 D BtGatt.ScanManager: handling starting scan
,09-15 07:32:22.317  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 07:32:22.317  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 07:32:22.320  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 07:32:22.320  5742  5761 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c686889
09-15 07:32:22.320  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 07:32:22.320  5522  5522 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:32:22.321  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 07:32:22.323  5522  5568 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 07:32:22.324  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:22.324  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 07:32:22.324  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.324  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 07:32:22.324  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 07:32:22.324  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 07:32:22.324  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 07:32:22.324  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 07:32:22.324  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 07:32:22.324  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 07:32:22.326  5522  5568 D BluetoothAdapter: STATE_ON
,09-15 07:32:22.326  5742  5758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 07:32:22.326  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.326  5742  5752 D BtGatt.GattService: stopScan() - queue size =1
09-15 07:32:22.327  5742  5761 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 07:32:22.328  5742  5770 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 07:32:22.328  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-15 07:32:22.329  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-15 07:32:22.329  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 07:32:22.329  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 07:32:22.329  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 07:32:22.330  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:32:22.331  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 07:32:22.331  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 07:32:22.331  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 07:32:22.331  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 07:32:22.333  5742  5758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 07:32:22.333  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.333  5522  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:32:22.333  5522  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:32:22.334  5522  5522 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:32:22.334  5742  5761 D BtGatt.ScanManager: Starting BLE batch scan
09-15 07:32:22.334  5742  5761 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 07:32:22.337  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 07:32:22.337  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:22.337  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:22.337  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:22.337  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.337  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:32:22.337  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:32:22.337  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@659e7fe removed from the list
09-15 07:32:22.337  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:22.337  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56b5b5f removed from the list
09-15 07:32:22.337  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:22.337  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:22.338  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.338  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:22.339  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:22.339  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:22.339  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:22.339  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56b5b5f not in the list
09-15 07:32:22.339  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.339  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:22.340  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:22.340  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:22.340  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:22.340  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68860a removed from the list
09-15 07:32:22.340  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:22.340  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.340  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:22.340  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:32:22.340  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f9b675 removed from the ,list
09-15 07:32:22.341  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:32:22.341  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@810f8d6 added. We now have 2 listener(s)
09-15 07:32:22.342  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:32:22.343  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:32:22.343  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:32:22.343  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:32:22.343  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68f5757 added. We now have 9 listener(s)
09-15 07:32:22.343  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:22.344  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 07:32:22.344  5742  5758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 07:32:22.344  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 07:32:22.347  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 07:32:22.351  5742  5758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 07:32:22.351  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:32:22.351  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:22.351  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:22.351  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:32:22.351  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:32:22.351  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:22.351  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:22.351  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:32:22.351  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.352  5522  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:32:22.352  5522  5568 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:32:22.353  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:32:22.353  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f3f2d added. We now have 3 listener(s)
09-15 07:32:22.354  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:32:22.354  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 07:32:22.354  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:32:22.354  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:32:22.354  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fbcc62 added. We now have 10 listener(s)
09-15 07:32:22.354  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:22.354  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:22.354  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:32:22.355  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:32:22.355  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 07:32:22.355  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 07:32:22.355  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:32:22.355  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 07:32:22.356  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:22.357  5742  5758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 07:32:22.357  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.357  5742  5761 D BtGatt.ScanManager: stopping BLe Batch
09-15 07:32:22.358  5522  5568 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 07:32:22.358  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 07:32:22.361  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 07:32:22.361  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 07:32:22.361  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 07:32:22.361  5742  5758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 07:32:22.361  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.362  5742  5761 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 07:32:22.365  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 07:32:22.365  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 07:32:22.365  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 07:32:22.365  5522  5568 D BluetoothAdapter: STATE_ON
09-15 07:32:22.366  5742  5758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 07:32:22.366  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.367  5742  5770 D BtGatt.GattService: registerClient() - UUID=91981c75-a361-40a2-b218-5052e87bb455
09-15 07:32:22.368  5742  5758 D BtGatt.GattService: onClientRegistered() - UUID=91981c75-a361-40a2-b218-5052e87bb455, clientIf=5
09-15 07:32:22.368  5522  5610 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 07:32:22.368  5742  5752 D BtGatt.GattService: start scan with filters
09-15 07:32:22.370  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 07:32:22.370  5742  5761 D BtGatt.ScanManager: handling starting scan
09-15 07:32:22.370  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 07:32:22.371  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 07:32:22.371  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 07:32:22.373  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:32:22.373  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 07:32:22.373  5522  5522 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:32:22.374  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 07:32:22.375  5742  5758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 07:32:22.376  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.376  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:32:22.376  5742  5761 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 07:32:22.376  5522  5568 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-15 07:32:22.376  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:32:22.376  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:22.376  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:22.376  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:22.376  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.376  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 07:32:22.376  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:32:22.376  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@810f8d6 removed from the list
09-15 07:32:22.376  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:22.376  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68f5757 removed from the list
09-15 07:32:22.376  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:22.376  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:32:22.378  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.378  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-15 07:32:22.378  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.378  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:32:22.379  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:22.379  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:22.379  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:22.379  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68f5757 not in the list
09-15 07:32:22.380  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 07:32:22.380  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 07:32:22.380  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 07:32:22.380  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 07:32:22.380  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 07:32:22.380  5522  5568 D BluetoothAdapter: STATE_ON
09-15 07:32:22.380  5742  5758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 07:32:22.381  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.381  5742  5761 D BtGatt.ScanManager: Starting BLE batch scan
09-15 07:32:22.381  5742  5761 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 07:32:22.381  5742  5752 D BtGatt.GattService: stopScan() - queue size =1
,09-15 07:32:22.381  5742  5753 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 07:32:22.382  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 07:32:22.382  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-15 07:32:22.382  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 07:32:22.382  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 07:32:22.382  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 07:32:22.383  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:32:22.383  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 07:32:22.383  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 07:32:22.383  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 07:32:22.384  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:22.385  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:22.385  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:22.385  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:22.385  5522  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-15 07:32:22.385  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fbcc62 removed from the list
09-15 07:32:22.385  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:22.385  5522  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:32:22.385  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.385  5522  5522 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:32:22.385  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:22.385  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:32:22.385  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f3f2d removed from the list
09-15 07:32:22.386  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:32:22.386  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ace4cae added. We now have 2 listener(s)
09-15 07:32:22.387  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:32:22.387  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:32:22.387  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:32:22.387  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:32:22.387  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7da4f added. We now have 9 listener(s)
09-15 07:32:22.387  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:22.388  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 07:32:22.389  5742  5758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 07:32:22.389  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.390  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 07:32:22.393  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:32:22.393  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:22.393  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:22.393  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:32:22.393  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:32:22.393  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:22.393  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:22.393  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:32:22.394  5742  5758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 07:32:22.394  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 07:32:22.396  5522  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:32:22.396  5522  5568 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:32:22.396  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 07:32:22.396  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2626e5 added. We now have 3 listener(s)
09-15 07:32:22.397  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:22.397  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:32:22.397  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:32:22.397  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:32:22.397  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:32:22.397  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63685ba added. We now have 10 listener(s)
09-15 07:32:22.398  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:22.398  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:32:22.398  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 07:32:22.398  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 07:32:22.398  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:32:22.398  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 07:32:22.399  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:32:22.400  5742  5758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 07:32:22.400  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.400  5742  5761 D BtGatt.ScanManager: stopping BLe Batch
,09-15 07:32:22.401  5522  5568 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 07:32:22.401  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 07:32:22.404  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 07:32:22.405  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 07:32:22.405  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 07:32:22.405  5742  5758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 07:32:22.405  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.405  5742  5761 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 07:32:22.408  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 07:32:22.408  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 07:32:22.408  5522  5568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 07:32:22.409  5522  5568 D BluetoothAdapter: STATE_ON
09-15 07:32:22.410  5742  5758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 07:32:22.410  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 07:32:22.412  5742  5753 D BtGatt.GattService: registerClient() - UUID=bf772739-f3f7-46d6-9295-7ff67ffd6ba8
,09-15 07:32:22.412  5742  5758 D BtGatt.GattService: onClientRegistered() - UUID=bf772739-f3f7-46d6-9295-7ff67ffd6ba8, clientIf=5
09-15 07:32:22.412  5522  5610 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 07:32:22.413  5742  5781 D BtGatt.GattService: start scan with filters
,09-15 07:32:22.414  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 07:32:22.414  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 07:32:22.415  5742  5761 D BtGatt.ScanManager: handling starting scan
09-15 07:32:22.415  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 07:32:22.415  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 07:32:22.417  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 07:32:22.417  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 07:32:22.417  5522  5522 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:32:22.418  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 07:32:22.419  5742  5758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 07:32:22.419  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.420  5742  5761 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 07:32:22.422  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 07:32:22.422  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:22.422  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:22.422  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:22.422  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.422  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 07:32:22.422  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-15 07:32:22.422  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ace4cae removed from the list
09-15 07:32:22.422  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:22.422  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7da4f removed from the list
09-15 07:32:22.422  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:22.422  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:32:22.423  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-15 07:32:22.423  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-15 07:32:22.423  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.423  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 07:32:22.423  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 07:32:22.423  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:22.424  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:22.424  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7da4f not in the list
09-15 07:32:22.424  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 07:32:22.424  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 07:32:22.424  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 07:32:22.424  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 07:32:22.424  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 07:32:22.424  5742  5758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-15 07:32:22.424  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.424  5742  5761 D BtGatt.ScanManager: Starting BLE batch scan
09-15 07:32:22.424  5742  5761 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 07:32:22.424  5522  5568 D BluetoothAdapter: STATE_ON
09-15 07:32:22.425  5742  5753 D BtGatt.GattService: stopScan() - queue size =1
09-15 07:32:22.425  5742  5781 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 07:32:22.426  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 07:32:22.426  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 07:32:22.426  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 07:32:22.426  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 07:32:22.426  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-15 07:32:22.427  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 07:32:22.427  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 07:32:22.427  5522  5568 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 07:32:22.427  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 07:32:22.428  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:22.428  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:22.429  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:22.429  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:22.429  5522  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:32:22.429  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63685ba removed from the list
09-15 07:32:22.429  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:22.429  5522  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:32:22.429  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.429  5522  5522 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:32:22.429  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:22.429  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:32:22.429  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2626e5 removed from the list
09-15 07:32:22.430  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:32:22.430  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab74386 added. We now have 2 listener(s)
09-15 07:32:22.431  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:32:22.431  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:32:22.431  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:32:22.431  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 07:32:22.431  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63ec447 added. We now have 9 listener(s)
09-15 07:32:22.431  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:22.431  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 07:32:22.433  5742  5758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 07:32:22.433  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.434  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 07:32:22.436  5522  5568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:32:22.436  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:32:22.436  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:32:22.436  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:32:22.436  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:32:22.436  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:32:22.436  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:32:22.436  5522  5568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:32:22.437  5742  5758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 07:32:22.437  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.438  5522  5568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:32:22.439  5522  5568 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:32:22.439  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 07:32:22.439  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89b4d9d added. We now have 3 listener(s)
09-15 07:32:22.440  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:22.440  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:32:22.440  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:32:22.441  5522  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:32:22.441  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:32:22.441  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 07:32:22.441  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341212 added. We now have 10 listener(s)
09-15 07:32:22.441  5522  5568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:32:22.441  5522  5568 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:32:22.441  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 07:32:22.441  5522  5568 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:32:22.441  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:22.442  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.442  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:32:22.442  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:32:22.442  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab74386 removed from the list
09-15 07:32:22.442  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 07:32:22.442  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63ec447 removed from the list
09-15 07:32:22.442  5522  5568 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:32:22.442  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:22.443  5742  5758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 07:32:22.443  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:32:22.443  5742  5761 D BtGatt.ScanManager: stopping BLe Batch
09-15 07:32:22.443  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 07:32:22.443  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:22.444  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:22.445  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:22.445  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:22.445  5522  5568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63ec447 not in the list
09-15 07:32:22.445  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.445  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:32:22.446  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:32:22.446  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:32:22.446  5522  5568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:32:22.446  5522  5568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341212 removed from the list
09-15 07:32:22.446  5522  5568 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:32:22.447  5522  5568 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:32:22.447  5522  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:32:22.447  5522  5568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-15 07:32:22.447  5522  5568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89b4d9d removed from the list
09-15 07:32:22.448  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-15 07:32:22.448  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 07:32:22.448  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-15 07:32:22.448  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:32:22.448  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 07:32:22.448  5522  5568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 07:32:22.449  5742  5758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 07:32:22.449  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 07:32:22.449  5742  5761 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 07:32:22.453  5742  5758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-15 07:32:22.453  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 07:32:22.453  5522  5810 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: My test thread name)
09-15 07:32:22.453  5522  5810 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: My test thread name)
09-15 07:32:22.453  5522  5810 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-15 07:32:22.455  5522  5811 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name)
09-15 07:32:22.455  5522  5811 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: My test thread name)
09-15 07:32:22.455  5522  5811 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-15 07:32:22.457  5522  5568 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-15 07:32:22.457  5522  5568 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-15 07:32:22.457  5522  5568 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-15 07:32:22.457  5522  5568 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-15 07:32:22.457  5522  5568 D com.test.thalitest.ThaliTestRunner: Total duration: 22622 ms
09-15 07:32:22.458  5522  5568 I jxcore-log: Total number of executed tests:  80
09-15 07:32:22.458  5522  5568 I jxcore-log: 
09-15 07:32:22.458  5522  5568 I jxcore-log: Number of passed tests:  80
09-15 07:32:22.458  5522  5568 I jxcore-log: 
09-15 07:32:22.459  5522  5568 I jxcore-log: Number of failed tests:  0
09-15 07:32:22.459  5522  5568 I jxcore-log: 
09-15 07:32:22.459  5522  5568 I jxcore-log: Number of ignored tests:  0
09-15 07:32:22.459  5522  5568 I jxcore-log: 
09-15 07:32:22.459  5522  5568 I jxcore-log: Total duration:  22622
09-15 07:32:22.459  5522  5568 I jxcore-log: 
09-15 07:32:22.460  5522  5568 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-15 07:32:22.460  5522  5568 I jxcore-log: 
09-15 07:32:22.461  5522  5568 I jxcore-log: My device name is: Huawei-Nexus 6P
09-15 07:32:22.461  5522  5568 I jxcore-log: 
09-15 07:32:22.463  5522  5568 I jxcore-log: WARN testUtils: myNameCallback not set!
09-15 07:32:22.463  5522  5568 I jxcore-log: 
09-15 07:32:22.465  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 07:32:22.465  5522  5568 I jxcore-log: 
09-15 07:32:22.467  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 07:32:22.467  5522  5568 I jxcore-log: 
09-15 07:32:22.468  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 07:32:22.468  5522  5568 I jxcore-log: 
09-15 07:32:22.469  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 07:32:22.469  5522  5568 I jxcore-log: 
09-15 07:32:22.471  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 07:32:22.471  5522  5568 I jxcore-log: 
09-15 07:32:22.473  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 07:32:22.473  5522  5568 I jxcore-log: 
09-15 07:32:22.474  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 07:32:22.474  5522  5568 I jxcore-log: 
09-15 07:32:22.475  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 07:32:22.475  5522  5568 I jxcore-log: 
09-15 07:32:22.475  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 07:32:22.475  5522  5568 I jxcore-log: 
09-15 07:32:22.476  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 07:32:22.476  5522  5568 I jxcore-log: 
09-15 07:32:22.477  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 07:32:22.477  5522  5568 I jxcore-log: 
09-15 07:32:22.478  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 07:32:22.478  5522  5568 I jxcore-log: 
09-15 07:32:22.479  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 07:32:22.479  5522  5568 I jxcore-log: 
09-15 07:32:22.480  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 07:32:22.480  5522  5568 I jxcore-log: 
09-15 07:32:22.481  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 07:32:22.481  5522  5568 I jxcore-log: 
09-15 07:32:22.481  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 07:32:22.481  5522  5568 I jxcore-log: 
09-15 07:32:22.482  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 07:32:22.482  5522  5568 I jxcore-log: 
09-15 07:32:22.483  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 07:32:22.483  5522  5568 I jxcore-log: 
09-15 07:32:22.483  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 07:32:22.483  5522  5568 I jxcore-log: 
09-15 07:32:22.484  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 07:32:22.484  5522  5568 I jxcore-log: 
09-15 07:32:22.484  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 07:32:22.484  5522  5568 I jxcore-log: 
09-15 07:32:22.485  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 07:32:22.485  5522  5568 I jxcore-log: 
09-15 07:32:22.486  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 07:32:22.486  5522  5568 I jxcore-log: 
09-15 07:32:22.486  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 07:32:22.486  5522  5568 I jxcore-log: 
,09-15 07:32:22.487  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 07:32:22.487  5522  5568 I jxcore-log: 
09-15 07:32:22.488  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 07:32:22.488  5522  5568 I jxcore-log: 
09-15 07:32:22.488  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 07:32:22.488  5522  5568 I jxcore-log: 
09-15 07:32:22.489  5522  5568 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 07:32:22.489  5522  5568 I jxcore-log: 
,09-15 07:32:22.834  5522  5522 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 07:32:22.885  5522  5522 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 07:32:22.930  5522  5522 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 07:32:22.970  5812  5812 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-15 07:32:22.974  5812  5812 D AndroidRuntime: CheckJNI is OFF
,09-15 07:32:23.004  5812  5812 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-15 07:32:23.038  5812  5812 I Radio-JNI: register_android_hardware_Radio DONE
,09-15 07:32:23.057  5812  5812 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-15 07:32:23.065   925   938 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-15 07:32:23.065   925   938 I ActivityManager: Killing 5522:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-15 07:32:23.143   925  3042 D WifiService: Client connection lost with reason: 4
,09-15 07:32:23.143   925  3591 D GraphicsStats: Buffer count: 2
09-15 07:32:23.145   925  3446 I WindowState: WIN DEATH: Window{e0d61cd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-15 07:32:23.200   925   938 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-15 07:32:23.201   925   948 I art     : Starting a blocking GC Explicit
,09-15 07:32:23.206   925   938 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-15 07:32:23.207   925   938 E ActivityManager: Failure starting process com.test.thalitest
09-15 07:32:23.207   925   938 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-15 07:32:23.207   925   938 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:32:23.207   925   938 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:32:23.207   925   938 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 07:32:23.207   925   938 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-15 07:32:23.208   925   938 I ActivityManager:   Force finishing activity ActivityRecord{185bf6e u0 com.test.thalitest/.MainActivity t2}
,09-15 07:32:23.216   925  3594 W ActivityManager: Spurious death for ProcessRecord{818d034 0:com.test.thalitest/u0a77}, curProc for 5522: null
,09-15 07:32:23.278   925   948 I art     : Explicit concurrent mark sweep GC freed 23846(1501KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 1.454ms total 76.525ms
,09-15 07:32:23.299   925   948 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-15 07:32:23.302  5812  5812 I art     : System.exit called, status: 0
,09-15 07:32:23.302  5812  5812 I AndroidRuntime: VM exiting with result code 0.
,09-15 07:32:23.316   925   948 I ActivityManager: Start proc 5822:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-15 07:32:23.317   925   948 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-15 07:32:23.325   925   938 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-15 07:32:23.330  5742  5742 D BluetoothMapAppObserver: onReceive
09-15 07:32:23.330  5742  5742 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-15 07:32:23.336  3466  3466 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-15 07:32:23.337   925  3007 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-15 07:32:23.341  3678  4018 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-15 07:32:23.361  3466  5834 I Keyboard.Facilitator.DecoderInitializer: run()
09-15 07:32:23.362  3486  5835 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-15 07:32:23.369  3571  3571 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-15 07:32:23.383    28    28 W kworker/1:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 07:32:23.389    28    28 W kworker/1:1: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 07:32:23.403  3466  5834 I Decoder : createOrResetDecoder
,09-15 07:32:23.407   925   925 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-15 07:32:23.408  3660  3660 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-15 07:32:23.409  3660  3660 D AndroidRuntime: Shutting down VM
--------- beginning of crash
09-15 07:32:23.409  3660  3660 E AndroidRuntime: FATAL EXCEPTION: main
09-15 07:32:23.409  3660  3660 E AndroidRuntime: Process: com.google.process.gapps, PID: 3660
09-15 07:32:23.409  3660  3660 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-15 07:32:23.409  3660  3660 E AndroidRuntime: 	... 8 more
09-15 07:32:23.406    28    28 W kworker/1:1: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 07:32:23.418   925  5841 E DropBoxManagerService: Can't write: system_app_crash
09-15 07:32:23.418   925  5841 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
09-15 07:32:23.418   925  5841 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-15 07:32:23.418   925  5841 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-15 07:32:23.418   925  5841 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-15 07:32:23.418   925  5841 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-15 07:32:23.418   925  5841 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 07:32:23.418   925  5841 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 07:32:23.418   925  5841 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 07:32:23.418   925  5841 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-15 07:32:23.418   925  5841 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 07:32:23.418   925  5841 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 07:32:23.418   925  5841 E DropBoxManagerService: 	... 5 more
,09-15 07:32:23.419  3660  3660 I Process : Sending signal. PID: 3660 SIG: 9
,09-15 07:32:23.421   925   937 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-15 07:32:23.422   925   937 E PackageManager: Failed to write settings, restoring backup
09-15 07:32:23.422   925   937 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-15 07:32:23.422   925   937 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-15 07:32:23.422   925   937 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-15 07:32:23.422   925   937 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-15 07:32:23.422   925   937 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-15 07:32:23.422   925   937 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:32:23.422   925   937 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:32:23.422   925   937 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 07:32:23.424   925   938 E DropBoxManagerService: Can't write: system_server_wtf
09-15 07:32:23.424   925   938 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-15 07:32:23.424   925   938 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 07:32:23.424   925   938 E DropBoxManagerService: 	... 13 more
,09-15 07:32:23.438  3599  3755 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-15 07:32:23.439  3486  3505 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj405DA49CC) - 
,09-15 07:32:23.452   925  3840 I ActivityManager: Start proc 5842:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-15 07:32:23.452  3599  3755 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-15 07:32:23.452  3599  3755 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3599
09-15 07:32:23.452  3599  3755 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 07:32:23.452  3599  3755 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-15 07:32:23.452  3599  3755 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-15 07:32:23.452  3599  3755 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-15 07:32:23.452  3599  3755 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-15 07:32:23.452  3599  3755 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-15 07:32:23.452  3599  3755 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-15 07:32:23.452  3599  3755 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-15 07:32:23.452  3599  3755 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-15 07:32:23.452  3599  3755 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-15 07:32:23.452  3599  3755 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:32:23.452  3599  3755 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-15 07:32:23.456   925  4032 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-15 07:32:23.457   925  5848 E DropBoxManagerService: Can't write: system_app_crash
09-15 07:32:23.457   925  5848 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
09-15 07:32:23.457   925  5848 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-15 07:32:23.457   925  5848 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-15 07:32:23.457   925  5848 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-15 07:32:23.457   925  5848 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-15 07:32:23.457   925  5848 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 07:32:23.457   925  5848 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 07:32:23.457   925  5848 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 07:32:23.457   925  5848 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-15 07:32:23.457   925  5848 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 07:32:23.457   925  5848 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 07:32:23.457   925  5848 E DropBoxManagerService: 	... 5 more
,09-15 07:32:23.463   925  3204 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1868)
,09-15 07:32:23.463   925  3204 W ActivityManager: Application dead when creating service ServiceRecord{a2bbc06 u0 com.google.android.gms/.config.ConfigService}
,09-15 07:32:23.468   925  3042 D WifiService: Client connection lost with reason: 4
,09-15 07:32:23.469   925  3204 I ActivityManager: Process com.google.process.gapps (pid 3660) has died
09-15 07:32:23.470   925  3204 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
09-15 07:32:23.470   925  3204 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
09-15 07:32:23.470   925  3204 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
09-15 07:32:23.470   925  3204 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 31000ms
09-15 07:32:23.471   925  3204 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 84000ms
09-15 07:32:23.471   925  3204 W ActivityManager: Exception when starting service com.google.android.gms/.config.ConfigService
09-15 07:32:23.471   925  3204 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-15 07:32:23.471   925  3204 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-15 07:32:23.471   925  3204 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
09-15 07:32:23.471   925  3204 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
09-15 07:32:23.471   925  3204 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
09-15 07:32:23.471   925  3204 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
09-15 07:32:23.471   925  3204 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
09-15 07:32:23.471   925  3204 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
09-15 07:32:23.471   925  3204 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:985)
09-15 07:32:23.471   925  3204 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-15 07:32:23.471   925  3204 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-15 07:32:23.474  3599  3755 I Process : Sending signal. PID: 3599 SIG: 9
,09-15 07:32:23.475   925  3593 W ActivityManager: Spurious death for ProcessRecord{b03bb6 0:com.google.process.gapps/u0a12}, curProc for 3660: null

```
