#### Test 829140738685e0d_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-15 07:59:03.772   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 07:59:03.773   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 07:59:04.233  5499  5499 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-15 07:59:04.240  5499  5499 D AndroidRuntime: CheckJNI is OFF
09-15 07:59:04.272  5499  5499 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-15 07:59:04.308  5499  5499 I Radio-JNI: register_android_hardware_Radio DONE
09-15 07:59:04.323  5499  5499 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-15 07:59:04.327   929  3633 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-15 07:59:04.370   929  3633 I ActivityManager: Start proc 5508:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-15 07:59:04.375  5499  5499 D AndroidRuntime: Shutting down VM
09-15 07:59:04.469  5508  5508 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-15 07:59:04.502  5508  5508 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-15 07:59:04.524  5508  5508 I LibraryLoader: Time to load native libraries: 17 ms (timestamps 9755-9772)
09-15 07:59:04.524  5508  5508 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 07:59:04.542  5508  5508 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5de1f16}
09-15 07:59:04.543  5508  5508 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 07:59:04.543  5508  5508 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-15 07:59:04.548  5508  5508 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-15 07:59:04.549  5508  5508 E SysUtils: ApplicationContext is null in ApplicationStatus
09-15 07:59:04.583  5508  5508 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-15 07:59:04.596  5508  5508 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-15 07:59:04.596  5508  5508 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 07:59:04.596  5508  5508 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-15 07:59:04.596  5508  5508 I Adreno  : Build Date                       : 12/06/15
09-15 07:59:04.596  5508  5508 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-15 07:59:04.596  5508  5508 I Adreno  : Local Branch                     : mybranch17112971
09-15 07:59:04.596  5508  5508 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-15 07:59:04.596  5508  5508 I Adreno  : Remote Branch                    : NONE
09-15 07:59:04.596  5508  5508 I Adreno  : Reconstruct Branch               : NOTHING
,09-15 07:59:04.646   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b7ddf09:true
,09-15 07:59:04.675   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[25266]" dev="sockfs" ino=25266 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0,
09-15 07:59:04.675   407   407 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[25266]" dev="sockfs" ino=25266 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 07:59:04.692  5508  5508 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-15 07:59:04.702  5508  5508 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-15 07:59:04.721   407   407 W Binder_2: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32198]" dev="sockfs" ino=32198 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 07:59:04.721   407   407 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32198]" dev="sockfs" ino=32198 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 07:59:04.727  5508  5545 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-15 07:59:04.725  3472  3472 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[13968]" dev="sockfs" ino=13968 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 07:59:04.725  3472  3472 W Binder_5: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13968]" dev="sockfs" ino=13968 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 07:59:04.733  5508  5532 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-15 07:59:04.759  5508  5545 I OpenGLRenderer: Initialized EGL, version 1.4
,09-15 07:59:04.835   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +417ms (total +489ms)
,09-15 07:59:04.847  5508  5508 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5508
,09-15 07:59:04.933  5508  5508 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-15 07:59:05.035  5508  5546 D jxcore_app_log: JniHelper::setJavaVM(0xf4f7c000), pthread_self() = -564397776
,09-15 07:59:05.039  5508  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-15 07:59:05.039  5508  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-15 07:59:05.039  5508  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-15 07:59:05.039  5508  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-15 07:59:05.039  5508  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-15 07:59:05.039  5508  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@163df4f added. We now have 1 listener(s)
,09-15 07:59:05.041  5508  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-15 07:59:05.042  5508  5546 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 07:59:05.042  5508  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 07:59:05.043  5508  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-15 07:59:05.045  5508  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4320eba added. We now have 1 listener(s)
09-15 07:59:05.045  5508  5546 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 07:59:05.050   929  3035 D WifiService: New client listening to asynchronous messages
,09-15 07:59:05.050  5508  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 07:59:05.050  5508  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-15 07:59:05.050  5508  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-15 07:59:05.050  5508  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-15 07:59:05.050  5508  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-15 07:59:05.052  5508  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:05.052  5508  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-15 07:59:05.056  5508  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-15 07:59:05.056  5508  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:59:05.056  5508  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:05.056  5508  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:05.056  5508  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:05.056  5508  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:05.056  5508  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:59:05.056  5508  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:59:05.056  5508  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 07:59:05.056  5508  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-15 07:59:05.057  5508  5546 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:59:05.057  5508  5546 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-15 07:59:05.059  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:05.062  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:05.070  5508  5508 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-15 07:59:05.315  5508  5554 W jxcore-log: Initializing JXcore engine
,09-15 07:59:05.315  5508  5554 W jxcore-log: JXcore engine is ready
,09-15 07:59:05.335  5554  5554 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12861 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-15 07:59:05.335  5554  5554 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[14383]" dev="sockfs" ino=14383 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-15 07:59:05.335  5554  5554 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-15 07:59:05.335  5554  5554 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32175]" dev="sockfs" ino=32175 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-15 07:59:05.347  5508  5554 W jxcore-log: Starting JXcore engine
,09-15 07:59:05.398  5508  5554 W jxcore-log: Platform android
09-15 07:59:05.398  5508  5554 W jxcore-log: 
09-15 07:59:05.398  5508  5554 W jxcore-log: Process ARCH arm
09-15 07:59:05.398  5508  5554 W jxcore-log: 
,09-15 07:59:05.495  5508  5554 I jxcore-log: JXcore Cordova bridge is ready!
09-15 07:59:05.495  5508  5554 I jxcore-log: 
09-15 07:59:05.495  5508  5554 W jxcore-log: JXcore engine is started
,09-15 07:59:05.503  5508  5546 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-15 07:59:05.507  5508  5508 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-15 07:59:12.096  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-15 07:59:12.096  5508  5554 I jxcore-log: 
,09-15 07:59:12.098  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-15 07:59:12.098  5508  5554 I jxcore-log: 
,09-15 07:59:12.102  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:59:12.102  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:12.102  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:12.102  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:12.102  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:12.102  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:59:12.102  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:59:12.102  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 07:59:12.103  5508  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 07:59:12.105  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-15 07:59:12.105  5508  5554 I jxcore-log: 
,09-15 07:59:12.107  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-15 07:59:12.107  5508  5554 I jxcore-log: 
,09-15 07:59:12.468  5508  5554 D executeNativeTests: Running unit tests
,09-15 07:59:12.510  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 07:59:12.510  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f added. We now have 2 listener(s)
09-15 07:59:12.511  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 07:59:12.511  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:59:12.511  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:59:12.511  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:59:12.511  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac added. We now have 2 listener(s)
,09-15 07:59:12.511  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:59:12.512  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 07:59:12.514  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 07:59:12.517  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:59:12.517  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:12.517  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:12.517  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:12.517  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:12.517  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:59:12.517  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:59:12.517  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 07:59:12.518  5508  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 07:59:12.518  5508  5554 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 07:59:12.520  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-15 07:59:12.520  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-15 07:59:12.520  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 07:59:12.521  5508  5554 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-15 07:59:12.521  5508  5554 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 07:59:12.521  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-15 07:59:12.521  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 07:59:12.521  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 07:59:12.521  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 07:59:12.522  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.522  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.522  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 07:59:12.522  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.522  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:59:12.522  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:59:12.523  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f removed from the list
09-15 07:59:12.523  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 07:59:12.523  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac removed from the list
09-15 07:59:12.525  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.525  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.526  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:59:12.526  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.526  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.528  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.528  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.528  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.528  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.529  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.530  5508  5554 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-15 07:59:12.530  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 07:59:12.530  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.530  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.530  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.530  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.530  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.530  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.530  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.530  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
,09-15 07:59:12.530  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.531  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.531  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.531  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.531  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.532  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 07:59:12.532  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.532  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.532  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.535  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 07:59:12.535  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-15 07:59:12.535  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 07:59:12.535  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 07:59:12.535  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 07:59:12.535  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-15 07:59:12.536  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 07:59:12.536  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.536  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.536  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.536  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.537  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.537  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:59:12.537  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.537  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.537  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.537  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.537  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.537  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.537  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.537  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.537  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.537  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.537  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.537  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
,09-15 07:59:12.538  5508  5554 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 07:59:12.539  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:12.541  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:59:12.541  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:12.541  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:12.541  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:12.541  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:12.541  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:59:12.541  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:59:12.541  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 07:59:12.541  5508  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 07:59:12.542  5508  5554 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:59:12.542  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 07:59:12.542  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 07:59:12.542  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 07:59:12.542  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:12.542  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 07:59:12.544  5508  5554 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 07:59:12.544  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 07:59:12.546  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:12.548  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 07:59:12.549  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.549  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 07:59:12.549  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 07:59:12.550  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-15 07:59:12.551  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-15 07:59:12.552  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 07:59:12.552  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 07:59:12.552  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 07:59:12.552  5508  5554 D BluetoothAdapter: STATE_ON
,09-15 07:59:12.554  4543  4774 D BtGatt.GattService: registerClient() - UUID=5c9a2acc-da23-4766-82e6-9c25ea44df85
,09-15 07:59:12.556  4543  4604 D BtGatt.GattService: onClientRegistered() - UUID=5c9a2acc-da23-4766-82e6-9c25ea44df85, clientIf=5
,09-15 07:59:12.559  5508  5519 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 07:59:12.559  4543  4556 D BtGatt.GattService: start scan with filters
,09-15 07:59:12.564  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 07:59:12.564  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 07:59:12.564  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 07:59:12.564  4543  4609 D BtGatt.ScanManager: handling starting scan
09-15 07:59:12.564  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 07:59:12.566  4543  4609 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
,09-15 07:59:12.567  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:59:12.567  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 07:59:12.567  5508  5508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:59:12.568  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 07:59:12.569  5508  5554 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 07:59:12.571  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.571  5508  5554 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-15 07:59:12.571  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.571  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 07:59:12.571  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.571  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 07:59:12.571  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 07:59:12.571  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 07:59:12.571  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-15 07:59:12.571  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 07:59:12.571  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 07:59:12.571  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 07:59:12.572  5508  5554 D BluetoothAdapter: STATE_ON
,09-15 07:59:12.572  4543  4766 D BtGatt.GattService: stopScan() - queue size =1
09-15 07:59:12.572  4543  4773 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 07:59:12.573  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 07:59:12.573  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 07:59:12.573  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-15 07:59:12.573  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 07:59:12.573  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 07:59:12.573  4543  4604 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 07:59:12.573  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.574  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:59:12.574  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 07:59:12.574  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 07:59:12.574  4543  4609 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 07:59:12.574  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 07:59:12.574  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:59:12.575  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.575  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.575  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:59:12.575  5508  5508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:59:12.575  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.575  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.575  5508  5508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:59:12.575  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.575  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.575  5508  5508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:59:12.575  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:59:12.575  5508  5554 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 07:59:12.577  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:12.581  4543  4604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 07:59:12.581  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.582  4543  4609 D BtGatt.ScanManager: Starting BLE batch scan
09-15 07:59:12.582  4543  4609 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 07:59:12.584  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:59:12.584  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:12.584  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:12.584  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:12.584  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:12.584  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:59:12.584  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:59:12.584  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 07:59:12.587  5508  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 07:59:12.587  5508  5554 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:59:12.587  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:59:12.587  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 07:59:12.587  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 07:59:12.587  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:12.587  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 07:59:12.589  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.590  5508  5554 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 07:59:12.590  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 07:59:12.591  4543  4604 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 07:59:12.591  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.591  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.592  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 07:59:12.592  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 07:59:12.592  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 07:59:12.594  4543  4604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 07:59:12.594  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.596  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 07:59:12.596  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 07:59:12.596  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 07:59:12.597  5508  5554 D BluetoothAdapter: STATE_ON
09-15 07:59:12.600  4543  4604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 07:59:12.600  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.600  4543  4609 D BtGatt.ScanManager: stopping BLe Batch
09-15 07:59:12.601  4543  4556 D BtGatt.GattService: registerClient() - UUID=5c3f588f-b67c-4b57-8311-94904ab47b3d
09-15 07:59:12.601  4543  4604 D BtGatt.GattService: onClientRegistered() - UUID=5c3f588f-b67c-4b57-8311-94904ab47b3d, clientIf=5
09-15 07:59:12.601  5508  5519 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 07:59:12.602  4543  4766 D BtGatt.GattService: start scan with filters
09-15 07:59:12.604  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 07:59:12.604  4543  4604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 07:59:12.604  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 07:59:12.604  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.604  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 07:59:12.604  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 07:59:12.604  4543  4609 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 07:59:12.605  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:59:12.605  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 07:59:12.605  5508  5508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:59:12.606  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 07:59:12.607  5508  5554 I io.jxcore.node.ConnectionHelper: start: OK
09-15 07:59:12.608  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.608  5508  5554 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 07:59:12.608  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.608  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 07:59:12.608  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.608  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 07:59:12.608  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 07:59:12.608  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 07:59:12.608  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 07:59:12.608  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 07:59:12.608  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 07:59:12.608  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 07:59:12.608  5508  5554 D BluetoothAdapter: STATE_ON
09-15 07:59:12.609  4543  4773 D BtGatt.GattService: stopScan() - queue size =0
09-15 07:59:12.609  4543  4604 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 07:59:12.609  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.609  4543  4774 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 07:59:12.609  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 07:59:12.609  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 07:59:12.609  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 07:59:12.609  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 07:59:12.609  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 07:59:12.610  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:59:12.610  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 07:59:12.610  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 07:59:12.610  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 07:59:12.610  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:59:12.610  4543  4609 D BtGatt.ScanManager: handling starting scan
09-15 07:59:12.610  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.610  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.611  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:59:12.611  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.611  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.611  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.611  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.611  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.611  5508  5508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:59:12.611  5508  5508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:59:12.611  5508  5508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:59:12.611  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.611  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.612  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.612  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.612  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.612  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.613  5508  5554 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 07:59:12.614  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:12.615  4543  4604 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 07:59:12.615  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.616  4543  4609 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 07:59:12.618  4543  4604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 07:59:12.618  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.618  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:59:12.618  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:12.618  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:12.618  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:12.618  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:12.618  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:59:12.618  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:59:12.618  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 07:59:12.619  4543  4609 D BtGatt.ScanManager: Starting BLE batch scan
09-15 07:59:12.619  4543  4609 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 07:59:12.620  5508  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 07:59:12.620  5508  5554 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:59:12.620  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:59:12.620  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 07:59:12.620  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 07:59:12.620  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:12.620  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 07:59:12.621  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.622  5508  5554 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 07:59:12.622  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 07:59:12.624  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 07:59:12.624  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.625  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 07:59:12.625  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 07:59:12.626  4543  4604 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 07:59:12.626  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.629  4543  4604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 07:59:12.630  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.631  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 07:59:12.631  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 07:59:12.631  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 07:59:12.632  5508  5554 D BluetoothAdapter: STATE_ON
09-15 07:59:12.633  4543  4774 D BtGatt.GattService: registerClient() - UUID=8207a0c4-2f6f-4d1a-b54d-008934e07dfe
09-15 07:59:12.633  4543  4604 D BtGatt.GattService: onClientRegistered() - UUID=8207a0c4-2f6f-4d1a-b54d-008934e07dfe, clientIf=5
09-15 07:59:12.633  4543  4604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 07:59:12.633  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.633  5508  5518 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 07:59:12.633  4543  4609 D BtGatt.ScanManager: stopping BLe Batch
09-15 07:59:12.634  4543  4558 D BtGatt.GattService: start scan with filters
09-15 07:59:12.637  4543  4604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 07:59:12.637  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.637  4543  4609 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 07:59:12.637  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 07:59:12.637  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 07:59:12.637  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 07:59:12.637  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 07:59:12.638  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:59:12.639  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 07:59:12.639  5508  5508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:59:12.639  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 07:59:12.640  5508  5554 I io.jxcore.node.ConnectionHelper: start: OK
09-15 07:59:12.640  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.640  5508  5554 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 07:59:12.640  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.640  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 07:59:12.640  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.640  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 07:59:12.640  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 07:59:12.640  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 07:59:12.640  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 07:59:12.640  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 07:59:12.640  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 07:59:12.640  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 07:59:12.641  5508  5554 D BluetoothAdapter: STATE_ON
09-15 07:59:12.641  4543  4604 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 07:59:12.641  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.641  4543  4558 D BtGatt.GattService: stopScan() - queue size =0
09-15 07:59:12.641  4543  4766 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 07:59:12.642  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 07:59:12.642  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 07:59:12.642  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 07:59:12.642  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 07:59:12.642  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 07:59:12.642  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:59:12.642  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 07:59:12.643  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 07:59:12.643  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 07:59:12.643  4543  4609 D BtGatt.ScanManager: handling starting scan
09-15 07:59:12.644  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:59:12.647  5508  5508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:59:12.647  5508  5508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:59:12.647  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.647  5508  5508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:59:12.647  5508  5554 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 07:59:12.647  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.647  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.647  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.647  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.647  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:59:12.647  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.647  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.647  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.647  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.647  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.648  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.648  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.648  4543  4604 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 07:59:12.648  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.648  4543  4609 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 07:59:12.649  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.649  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.649  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.649  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.649  5508  5554 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-15 07:59:12.650  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.650  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.650  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.650  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.650  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.650  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.650  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.650  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.650  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.651  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.651  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.651  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.651  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.651  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.652  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.652  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.652  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.652  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.653  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 07:59:12.653  4543  4604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 07:59:12.653  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.653  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.653  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.653  4543  4609 D BtGatt.ScanManager: Starting BLE batch scan
09-15 07:59:12.653  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.653  4543  4609 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 07:59:12.653  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.653  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.653  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.653  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.653  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.653  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.654  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.654  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.654  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.654  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.654  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.655  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.655  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.655  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.655  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.655  5508  5554 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-15 07:59:12.655  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.655  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 07:59:12.655  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.655  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.655  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.655  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.655  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.655  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.655  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.655  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.655  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.655  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.656  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.656  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.658  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.658  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.658  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.658  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.658  5508  5554 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-15 07:59:12.659  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.659  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.659  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.659  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.659  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.659  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.659  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.659  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.659  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.659  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.659  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.659  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.659  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.659  4543  4604 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 07:59:12.659  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.659  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.660  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.660  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.660  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.660  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.660  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 07:59:12.660  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 07:59:12.660  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 07:59:12.660  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 07:59:12.660  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 07:59:12.660  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 07:59:12.660  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.660  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.660  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.660  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.660  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.660  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.660  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.660  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.661  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.661  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.661  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.661  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.661  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.661  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.661  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.661  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.661  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.661  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.661  5508  5554 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 07:59:12.662  5508  5554 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 07:59:12.662  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 07:59:12.663  5508  5554 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 07:59:12.663  5508  5554 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 07:59:12.663  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 07:59:12.664  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-15 07:59:12.664  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 07:59:12.664  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 07:59:12.664  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 07:59:12.664  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-15 07:59:12.664  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 07:59:12.664  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-15 07:59:12.664  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 07:59:12.664  5508  5554 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-15 07:59:12.664  5508  5554 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 07:59:12.664  5508  5554 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-15 07:59:12.664  5508  5554 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 07:59:12.664  5508  5554 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 07:59:12.664  5508  5554 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-15 07:59:12.664  5508  5554 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 07:59:12.664  5508  5554 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 07:59:12.664  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-15 07:59:12.667  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-15 07:59:12.668  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-15 07:59:12.668  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-15 07:59:12.668  4543  4604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 07:59:12.668  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.668  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-15 07:59:12.668  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-15 07:59:12.668  5508  5554 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-15 07:59:12.668  5508  5554 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 07:59:12.668  5508  5554 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-15 07:59:12.669  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.669  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.669  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.669  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.669  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.669  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.669  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-15 07:59:12.670  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.670  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.670  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.670  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.670  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.670  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.670  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.670  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.670  5508  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-15 07:59:12.671  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.671  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.671  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.671  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.670  5508  5555 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-15 07:59:12.671  5508  5554 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-15 07:59:12.671  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.671  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.672  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.672  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.672  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.672  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.672  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.672  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.672  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.672  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.672  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.672  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.672  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.672  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.672  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.672  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.672  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.672  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.672  5508  5555 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-15 07:59:12.673  5508  5554 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-15 07:59:12.673  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.673  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.673  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.673  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.673  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.673  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.673  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.673  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.673  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.673  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.673  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.673  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.673  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.673  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.674  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.674  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.674  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.674  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.674  4543  4604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 07:59:12.674  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.674  4543  4609 D BtGatt.ScanManager: stopping BLe Batch
09-15 07:59:12.675  5508  5554 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-15 07:59:12.675  5508  5554 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-15 07:59:12.675  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 07:59:12.675  5508  5554 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-15 07:59:12.675  5508  5554 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 07:59:12.675  5508  5554 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-15 07:59:12.675  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 07:59:12.675  5508  5554 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-15 07:59:12.675  5508  5554 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 07:59:12.675  5508  5554 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 07:59:12.675  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 07:59:12.675  5508  5554 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-15 07:59:12.675  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.675  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.675  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:,12.675  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.675  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.675  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.675  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.675  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.676  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.676  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.676  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.676  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.676  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.676  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.677  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.677  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.677  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.677  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.678  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.678  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.678  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.678  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.678  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.678  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.678  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.678  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.678  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.678  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.678  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.678  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.678  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.678  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.678  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.678  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.678  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.678  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.678  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.678  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.678  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.678  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.678  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.679  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.679  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.679  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.679  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.679  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.679  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.679  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.679  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.679  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.679  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.679  4543  4604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 07:59:12.679  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.679  4543  4609 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 07:59:12.680  5508  5554 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 07:59:12.680  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:12.680  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-15 07:59:12.681  5508  5554 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 07:59:12.681  5508  5554 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 07:59:12.681  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 07:59:12.681  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 07:59:12.681  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.681  5508  5508 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 07:59:12.681  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 07:59:12.681  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 07:59:12.681  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 07:59:12.681  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.681  5508  5554 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-15 07:59:12.681  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.681  5508  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 07:59:12.681  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.681  5508  5508 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 07:59:12.681  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 07:59:12.681  5508  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 07:59:12.681  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 07:59:12.681  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 07:59:12.682  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.682  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.682  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:59:12.682  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.682  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.682  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.682  5508  5508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:59:12.682  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.682  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.682  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.682  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.682  5508  5508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:59:12.682  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.682  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.682  5508  5508 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 07:59:12.683  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.683  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.683  5508  5508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:59:12.683  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.683  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.683  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.683  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.683  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.683  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.683  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.683  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.683  4543  4604 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 07:59:12.684  4543  4604 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:12.684  5508  5554 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-15 07:59:12.684  5508  5554 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 07:59:12.684  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 07:59:12.684  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 07:59:12.684  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.684  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.684  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.684  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.684  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.684  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.684  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.684  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.684  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.684  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.684  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.685  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.685  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.685  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.685  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.685  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.685  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.685  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.686  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.686  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.687  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.687  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.687  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.687  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.687  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.687  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.687  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.687  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.687  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.687  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.687  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.687  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.687  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.687  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.687  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.687  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.688  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:12.688  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:12.688  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:12.688  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:12.688  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.688  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.688  5508  5554 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@511c45f not in the list
09-15 07:59:12.688  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.688  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.688  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:12.688  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.688  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.688  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:12.688  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:12.688  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:12.689  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:12.689  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:12.689  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfbeac not in the list
09-15 07:59:12.689  5508  5554 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-15 07:59:12.689  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 07:59:12.689  5508  5554 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-15 07:59:12.689  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 07:59:12.689  5508  5554 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-15 07:59:12.689  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 07:59:12.690  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 07:59:12.690  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-15 07:59:12.690  5508  5554 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-15 07:59:12.690  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 07:59:12.690  5508  5554 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-15 07:59:12.690  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 07:59:12.690  5508  5554 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-15 07:59:12.690  5508  5554 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-15 07:59:12.691  5508  5554 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-15 07:59:12.691  5508  5554 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-15 07:59:12.691  5508  5554 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-15 07:59:12.691  5508  5554 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-15 07:59:12.691  5508  5554 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-15 07:59:12.691  5508  5554 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-15 07:59:12.691  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:59:12.691  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ccdf9ae added. We now have 2 listener(s)
09-15 07:59:12.691  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:59:12.692  5508  5554 D BluetoothAdapter: enable(): BT is already enabled..!
09-15 07:59:12.692   929   939 D WifiService: setWifiEnabled: true pid=5508, uid=10077
09-15 07:59:12.692   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 07:59:12.693  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:59:12.693  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a834f added. We now have 3 listener(s)
09-15 07:59:12.693  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:59:12.695  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:59:12.695  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8a62adc added. We now have 4 listener(s)
09-15 07:59:12.695  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:59:12.696  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:59:12.696  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f777e5 added. We now have 5 listener(s)
09-15 07:59:12.696  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 07:59:12.696   929  3595 D WifiService: setWifiEnabled: false pid=5508, uid=10077
09-15 07:59:12.696   929  3595 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 07:59:12.698   929  3034 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-15 07:59:12.698   929  3034 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-15 07:59:12.698   929  3034 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 07:59:12.698   929  3034 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-15 07:59:12.701  4543  4600 D BluetoothAdapterState: Current state: ON, message: 23
09-15 07:59:12.701  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:12.701  4543  4600 D BluetoothAdapterProperties: Setting state to 13
09-15 07:59:12.701  4543  4600 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-15 07:59:12.702  4543  4600 D BluetoothAdapterProperties: onBluetoothDisable()
09-15 07:59:12.703  4543  4600 I BluetoothAdapterState: Entering PendingCommandState
09-15 07:59:12.704  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:12.704  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:59:12.704  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:12.704  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:12.704  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:12.704  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:59:12.704  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:59:12.704  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:59:12.704  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 07:59:12.705  4543  4543 D BluetoothMapService: onReceive
09-15 07:59:12.705  4543  4543 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 07:59:12.705  4543  4543 D BluetoothMapService: STATE_TURNING_OFF
09-15 07:59:12.705  4543  4543 D BluetoothMapService: MAP Service closeService in
09-15 07:59:12.705  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:12.705  4543  4543 D BluetoothMapMasInstance0: MAP Service shutdown
09-15 07:59:12.705  4543  4543 D ObexServerSockets0: shutdown(block = true)
09-15 07:59:12.705  5508  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 07:59:12.705  5508  5554 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:59:12.705  4543  4543 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 07:59:12.705  4543  4543 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 07:59:12.705  4543  4776 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-15 07:59:12.706  4543  4777 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-15 07:59:12.706  4543  4763 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-15 07:59:12.706  4543  4543 I BtOppRfcommListener: stopping Accept Thread
09-15 07:59:12.707  4543  5184 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 07:59:12.707  4543  5184 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 07:59:12.708   929  3034 E native  : do suspend true
09-15 07:59:12.709  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.712  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.714  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:12.714  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:12.714  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:12.714  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:12.714  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:12.714  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:59:12.714  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 07:59:12.714  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 07:59:12.714  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 07:59:12.715  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:12.715  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 07:59:12.717  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.718   929   942 I ActivityManager: Start proc 5560:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-15 07:59:12.719  4543  4604 D BluetoothAdapterProperties: Scan Mode:20
09-15 07:59:12.719  4543  4600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-15 07:59:12.724  4543  4543 D HeadsetService: Received stop request...Stopping profile...
09-15 07:59:12.724  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.725  3588  3618 D BluetoothHeadset: Proxy object disconnected
09-15 07:59:12.725  4543  4543 D A2dpService: Received stop request...Stopping profile...
09-15 07:59:12.727  4543  4543 D HidService: Received stop request...Stopping profile...
09-15 07:59:12.726   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 07:59:12.727   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 07:59:12.727  4543  4543 D HidService: Stopping Bluetooth HidService
09-15 07:59:12.727   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 07:59:12.728  3186  3776 D BluetoothHeadset: Proxy object disconnected
09-15 07:59:12.726  4543  4768 D A2dpStateMachine: Exit Disconnected: -1
09-15 07:59:12.728  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.728  4543  4543 D HealthService: Received stop request...Stopping profile...
09-15 07:59:12.728   929   929 D BluetoothA2dp: Proxy object disconnected
09-15 07:59:12.730  3186  3186 D BluetoothA2dp: Proxy object disconnected
09-15 07:59:12.730  3186  3186 D BluetoothInputDevice: Proxy object disconnected
09-15 07:59:12.730  3186  3186 D HidProfile: Bluetooth service disconnected
09-15 07:59:12.731  3186  3186 D HeadsetProfile: Bluetooth service disconnected
09-15 07:59:12.731  4543  4543 D PanService: Received stop request...Stopping profile...
09-15 07:59:12.732  4543  4543 V BluetoothAdapterState: isTurningOff()=true
09-15 07:59:12.732  4543  4543 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:12.732  4543  4543 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:12.732  4543  4543 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:12.732  3186  3186 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 07:59:12.732  3186  3186 D PanProfile: Bluetooth service disconnected
09-15 07:59:12.733  4543  4543 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-15 07:59:12.733  4543  4543 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 07:59:12.733  4543  4604 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 07:59:12.733  4543  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:59:12.733  4543  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:59:12.733  4543  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:59:12.733  4543  4543 V BluetoothAdapterState: isTurningOff()=true
09-15 07:59:12.733  4543  4543 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:12.733  4543  4543 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:12.733  4543  4543 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:12.733  4543  4604 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-15 07:59:12.733  4543  4543 V BluetoothAdapterState: isTurningOff()=true
09-15 07:59:12.733  4543  4543 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:12.733  4543  4543 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:12.733  4543  4543 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:12.734  4543  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:59:12.734  4543  4543 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 07:59:12.734  4543  4543 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 07:59:12.734  4543  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:59:12.735  4543  4543 V BluetoothAdapterState: isTurningOff()=true
09-15 07:59:12.735  4543  4543 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:12.735  4543  4604 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 07:59:12.735  4543  4543 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:12.735  4543  4749 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 07:59:12.735  4543  4543 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:12.735  4543  4604 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 07:59:12.735  4543  4749 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 07:59:12.735  4543  4749 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-15 07:59:12.735  4543  4749 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 07:59:12.735  4543  4543 D BluetoothMapService: Received stop request...Stopping profile...
09-15 07:59:12.735  4543  4543 D BluetoothMapService: stop()
09-15 07:59:12.736  4543  4543 D BluetoothMapAppObserver: deinitObservers()
09-15 07:59:12.736  4543  4543 D BluetoothMapAppObserver: removeReceiver()
09-15 07:59:12.736  3186  3186 D BluetoothMap: Proxy object disconnected
09-15 07:59:12.736  3186  3186 D MapProfile: Bluetooth service disconnected
09-15 07:59:12.736  4543  4543 D SapService: Received stop request...Stopping profile...
09-15 07:59:12.737  4543  4543 V SapService: stop()
09-15 07:59:12.737   929  5243 D DhcpClient: Clearing IP address
09-15 07:59:12.737   509   923 D CommandListener: Clearing all IP addresses on wlan0
09-15 07:59:12.737  4543  4543 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-15 07:59:12.738  4543  4543 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-15 07:59:12.738  4543  4604 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 07:59:12.738  4543  4543 V BluetoothAdapterState: isTurningOff()=true
09-15 07:59:12.738  4543  4543 V BluetoothAdapterState: isTurningOn()=false
,09-15 07:59:12.738  4543  4543 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:12.738  4543  4543 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:12.738  4543  4543 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 07:59:12.738  4543  4543 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-15 07:59:12.739  4543  4543 D BluetoothMapService: MAP Service closeService in
09-15 07:59:12.739  4543  4543 V BluetoothAdapterState: isTurningOff()=true
09-15 07:59:12.739  4543  4543 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:12.739  4543  4543 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:12.739  4543  4543 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:12.739  4543  4543 D BluetoothMapService: cleanup()
09-15 07:59:12.739  4543  4543 D BluetoothMapService: MAP Service closeService in
,09-15 07:59:12.739  4543  4543 V BluetoothAdapterState: isTurningOff()=true
09-15 07:59:12.739  4543  4543 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:12.739  4543  4543 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 07:59:12.739  4543  4543 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:12.740  4543  4600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 07:59:12.740  4543  4600 D BluetoothAdapterProperties: Setting state to 15
09-15 07:59:12.740  4543  4600 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 07:59:12.740  4543  4600 I BluetoothAdapterState: Entering BleOnState
,09-15 07:59:12.742  3186  3780 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-15 07:59:12.743   509   923 D CommandListener: Setting iface cfg
09-15 07:59:12.744  3669  5296 V NativeCrypto: Read error: ssl=0x7f5f0a5000: I/O error during system call, Connection timed out
09-15 07:59:12.745  3669  5296 V NativeCrypto: SSL shutdown failed: ssl=0x7f5f0a5000: I/O error during system call, Broken pipe
09-15 07:59:12.747   929  3490 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-15 07:59:12.747   929  5241 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-15 07:59:12.749   929  5241 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-15 07:59:12.749   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:59:12.749  3186  3776 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 07:59:12.749   929  3036 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,09-15 07:59:12.749   929  3036 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-15 07:59:12.749   929  5244 D DhcpClient: Receive thread stopped
09-15 07:59:12.750  3588  3820 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:59:12.750   929  3036 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-15 07:59:12.751  3186  3780 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:59:12.751   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:59:12.752  3186  3199 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 07:59:12.752   929  3036 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-15 07:59:12.752  3186  3776 D BluetoothMap: onBluetoothStateChange: up=false
09-15 07:59:12.753   929  3036 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-15 07:59:12.755   535   535 E Parcel  : Reading a NULL string not supported here.
09-15 07:59:12.757   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 07:59:12.757   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:59:12.757   929  3036 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-15 07:59:12.757  3186  3199 D BluetoothPan: onBluetoothStateChange on: false
09-15 07:59:12.758  3547  3729 W QCNEJ   : |CORE| network lost: 100
09-15 07:59:12.758  4543  4600 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 07:59:12.758  4543  4600 D BluetoothAdapterProperties: Setting state to 16
09-15 07:59:12.758  4543  4600 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 07:59:12.758  5560  5560 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-15 07:59:12.758  3547  3729 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-15 07:59:12.761   929   929 D RttService: SCAN_AVAILABLE : 1
09-15 07:59:12.761   929  3139 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-15 07:59:12.762  4543  4600 D BluetoothAdapterProperties: onBleDisable
09-15 07:59:12.762  4543  4600 I BluetoothAdapterState: Entering PendingCommandState
,09-15 07:59:12.762  4543  4601 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-15 07:59:12.763  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:12.763  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:12.763  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:12.763  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:12.763  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:12.763  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:59:12.763  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:12.763  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:12.763  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:59:12.763  4543  4749 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-15 07:59:12.763  4543  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:59:12.764  4543  4604 D BluetoothAdapterProperties: Scan Mode:20
09-15 07:59:12.764  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:12.764  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:59:12.768  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 07:59:12.768  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:12.768  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:12.768  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:12.768  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:12.768  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:59:12.768  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:12.768  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:12.768  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:59:12.769  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:12.769  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:59:12.771  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.773  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.773  5560  5560 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 07:59:12.774   929  3034 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-15 07:59:12.774   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 07:59:12.780  3669  3669 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 07:59:12.780   929  3034 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 07:59:12.780   929  3034 E native  : do suspend true
09-15 07:59:12.783   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b9c415:true
,09-15 07:59:12.795   929  3490 I ActivityManager: Start proc 5580:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-15 07:59:12.797   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 07:59:12.797   509   923 D TetherController: Setting IP forward enable = 0
,09-15 07:59:12.798   509   923 D CommandListener: Clearing all IP addresses on wlan0
09-15 07:59:12.798   929  3036 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-15 07:59:12.798   929  3036 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-15 07:59:12.801   929  3034 D DhcpClient: doQuit
09-15 07:59:12.801   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-15 07:59:12.802   929  3034 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-15 07:59:12.803  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.803  3728  3728 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-15 07:59:12.803   929  5243 D DhcpClient: onQuitting
,09-15 07:59:12.805  4878  4878 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-15 07:59:12.806  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:12.806  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:12.806  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:12.806  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:12.806  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:59:12.806  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:59:12.806  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:12.806  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:12.806  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:59:12.807  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:12.807  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:59:12.810  4946  4961 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-15 07:59:12.810  4946  4961 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 07:59:12.810  4946  4961 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-15 07:59:12.810  4946  4961 E SarControlService: no key has been found,reset the power
09-15 07:59:12.810  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:12.810  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:12.810  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:12.810  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:12.810  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:59:12.810  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:59:12.810  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:12.810  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:12.810  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:59:12.810  4946  4984 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-15 07:59:12.810  4946  4984 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 07:59:12.811  4946  4984 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 07:59:12.811  4974  4974 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 07:59:12.811  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:12.811  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:59:12.812  4974  4974 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-15 07:59:12.813  4946  4984 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 07:59:12.813  4946  4984 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-15 07:59:12.813  4946  4984 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-15 07:59:12.813  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.814  4974  4974 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 07:59:12.814  4974  4974 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-15 07:59:12.817  4974  4989 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d9c0d8 HexData = [00000000ea03000000000000ffffffff]
09-15 07:59:12.817  4974  4989 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 07:59:12.817  4974  4989 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-15 07:59:12.817  4974  4974 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-15 07:59:12.817  4946  4959 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-15 07:59:12.823  4974  4989 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d9c0d8 HexData = [00000000eb03000000000000ffffffff]
,09-15 07:59:12.823  4974  4989 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 07:59:12.823  4974  4989 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-15 07:59:12.824  4974  4974 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 07:59:12.824  4946  4958 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-15 07:59:12.828  3728  3728 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-15 07:59:12.830  5560  5560 D LocalBluetoothProfileManager: Adding local MAP profile
09-15 07:59:12.831  3728  3728 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-15 07:59:12.837  5560  5560 D BluetoothMap: Create BluetoothMap proxy object
,09-15 07:59:12.844   509   923 E Netd    : netlink response contains error (No such file or directory)
,09-15 07:59:12.845   509   923 D TetherController: Setting IP forward enable = 0
,09-15 07:59:12.845   929  3036 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-15 07:59:12.846   929  3036 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-15 07:59:12.849  5580  5580 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-15 07:59:12.852  5560  5560 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-15 07:59:12.863  5560  5560 D DockEventReceiver: finishStartingService: stopping service
,09-15 07:59:12.869   929  3216 I ActivityManager: Killing 5283:com.android.chrome/u0a39 (adj 15): empty #17
,09-15 07:59:12.872  3728  3728 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 07:59:12.891  3728  3728 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 07:59:12.897   929  3034 D wifi    : In wifi stop Hal
09-15 07:59:12.897  4355  4355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 07:59:12.897   929  3034 D wifi    : halHandle = 0x7f6f63c880, mVM = 0x7f7a0cd140, mCls = 0x100bb2
09-15 07:59:12.897   929  3726 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 11
,09-15 07:59:12.897   929  3726 D WifiHAL : Got a signal to exit!!!
09-15 07:59:12.897   929  3726 I WifiHAL : Exit wifi_event_loop
09-15 07:59:12.898   929  3034 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 07:59:12.898   929  3034 E WifiHAL : Event processing terminated
,09-15 07:59:12.898   929  3034 D wifi    : In wifi cleaned up handler
09-15 07:59:12.898   929  3034 I WifiHAL : Internal cleanup completed
,09-15 07:59:12.899  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:12.901  3528  4093 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 07:59:12.901  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:12.917   929  3726 D wifi    : set interface wlan0 flags (DOWN)
,09-15 07:59:12.918   929  3034 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 07:59:12.969  4543  4604 I bt_hci  : shut_down
,09-15 07:59:12.973  4543  4610 D bt_hwcfg: hw_epilog_process
,09-15 07:59:12.974  4543  4610 I bt_vendor: low_power_mode_cb
,09-15 07:59:12.976  4543  4610 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-15 07:59:12.976  4543  4610 I bt_vendor: epilog_cb
09-15 07:59:12.976  4543  4610 I bt_hci  : epilog_finished_callback
,09-15 07:59:12.978  4543  4604 I bt_hci_h4: hal_close
,09-15 07:59:12.979  4543  4604 I bt_userial_vendor: device fd = 54 close
,09-15 07:59:13.045  5580  5580 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:59:13.045  5580  5580 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:59:13.045  5580  5580 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:59:13.045  5580  5580 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:59:13.045  5580  5580 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.r.k.d(PG:583)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:59:13.045  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:59:13.046  5580  5580 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:59:13.046  5580  5580 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:59:13.046  5580  5580 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 07:59:13.046  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 07:59:13.051  5560  5560 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 07:59:13.057  3669  3669 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 07:59:13.066  5560  5560 D DockEventReceiver: finishStartingService: stopping service
09-15 07:59:13.068   929  3602 I ActivityManager: Killing 4920:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-15 07:59:13.108  4543  4601 D bt_stack_manager: event_shut_down_stack finished.
09-15 07:59:13.108  4543  4600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-15 07:59:13.110  4543  4600 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-15 07:59:13.110  4543  4543 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 07:59:13.110  3963  3963 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-15 07:59:13.110  4543  4543 D BtGatt.GattService: Received stop request...Stopping profile...
09-15 07:59:13.110  4543  4543 D BtGatt.GattService: stop()
09-15 07:59:13.110  4543  4543 D BtGatt.AdvertiseManager: advertise clients cleared
09-15 07:59:13.112  4543  4543 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:13.112  4543  4543 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:13.112  4543  4543 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:13.113  4543  4543 V BluetoothAdapterState: isBleTurningOff()=true
09-15 07:59:13.113  4543  4600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 07:59:13.113  4543  4600 D BluetoothAdapterProperties: Setting state to 10
09-15 07:59:13.113  4543  4600 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 07:59:13.113  4543  4600 I BluetoothAdapterState: Entering OffState
09-15 07:59:13.115   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-15 07:59:13.116  3963  5267 I iu.UploadsManager: num queued entries: 0
09-15 07:59:13.119   929   946 D Tethering: InitialState.processMessage what=4
09-15 07:59:13.121   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-15 07:59:13.123  4543  4543 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-15 07:59:13.123  4543  4543 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 07:59:13.123  4543  4543 I BluetoothServiceJni: cleanupNative: return from cleanup
09-15 07:59:13.124  4543  4601 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 07:59:13.130  4543  4543 I art     : System.exit called, status: 0
,09-15 07:59:13.130  4543  4543 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-15 07:59:13.139  3963  3963 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-15 07:59:13.140  3963  3963 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-15 07:59:13.145  3963  5267 I iu.UploadsManager: num updated entries: 0
,09-15 07:59:13.146  3963  5267 I iu.SyncManager: NEXT; no task
,09-15 07:59:13.152   929  3216 I ActivityManager: Start proc 5626:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-15 07:59:13.166   929  3633 I ActivityManager: Process com.android.bluetooth (pid 4543) has died
,09-15 07:59:13.183  5508  5508 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 07:59:13.192  5626  5626 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-15 07:59:13.195  5626  5626 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-15 07:59:13.205  5626  5626 D SprintDMHelper: simOperator: 
,09-15 07:59:13.205  5626  5626 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-15 07:59:13.217   929   940 I ActivityManager: Start proc 5638:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-15 07:59:13.217   929   940 I ActivityManager: Killing 5031:com.google.android.deskclock/u0a66 (adj 15): empty #17
,09-15 07:59:13.325  4355  5652 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-15 07:59:13.338   929  3216 I ActivityManager: Start proc 5653:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-15 07:59:13.340   929  3602 I ActivityManager: Killing 5317:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-15 07:59:13.386  5653  5653 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-15 07:59:13.394   929  3602 I ActivityManager: Killing 4614:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-15 07:59:13.471  5580  5618 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-15 07:59:13.482   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@477ab32:true
,09-15 07:59:13.773   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:59:14.775   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:59:15.707   929  3638 D WifiService: setWifiEnabled: true pid=5508, uid=10077
,09-15 07:59:15.707   929  3638 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 07:59:15.714   509   923 D SoftapController: Softap fwReload - Ok
,09-15 07:59:15.718   509   923 D CommandListener: Setting iface cfg
,09-15 07:59:15.719   509   923 D CommandListener: Trying to bring down wlan0
,09-15 07:59:15.723   509   923 D CommandListener: Clearing all IP addresses on wlan0
,09-15 07:59:15.727   929  3034 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 07:59:15.776   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:59:16.327   929  3034 D wifi    : set interface wlan0 flags (UP)
,09-15 07:59:16.332   929  3034 I WifiHAL : Initializing wifi
,09-15 07:59:16.332   929  3034 I WifiHAL : Creating socket
,09-15 07:59:16.337   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 07:59:16.337   929  3034 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-15 07:59:16.337   929  3034 D wifi    : Did set static halHandle = 0x7f6f63c880
,09-15 07:59:16.337   929  3034 D wifi    : halHandle = 0x7f6f63c880, mVM = 0x7f7a0cd140, mCls = 0x18d2
09-15 07:59:16.338   929  3034 D wifi    : array field set
09-15 07:59:16.338   929  3034 I WifiNative-HAL: interface[0] = wlan0
09-15 07:59:16.340   929  5670 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547329656960
09-15 07:59:16.340   929  5670 D wifi    : waitForHalEvents called, vm = 0x7f7a0cd140, obj = 0x18d2, env = 0x7f5e309040
,09-15 07:59:16.419  5671  5671 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 07:59:16.441  5671  5671 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 07:59:16.442   929  3034 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-15 07:59:16.452  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:16.455  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:16.468  5671  5671 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 07:59:16.468  5671  5671 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 07:59:16.484   929  3034 D WifiConfigStore: Loading config and enabling all networks 
,09-15 07:59:16.484  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:16.485  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:16.485  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:16.485  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:16.485  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:16.485  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:59:16.485  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:16.485  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:16.485  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:59:16.485  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:16.485  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:59:16.486  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:16.486  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:16.486  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:16.486  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:16.486  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:16.486  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:59:16.486  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:16.486  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:16.486  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:59:16.486  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:16.486  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:59:16.493   929  3034 D WifiConfigStore: loaded 0 passpoint configs
,09-15 07:59:16.494   929  3034 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 07:59:16.494   929  3034 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-15 07:59:16.495   929  3034 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-15 07:59:16.496   929  3034 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-15 07:59:16.496   929  3034 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 07:59:16.496   929  3034 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-15 07:59:16.496   929  3034 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 07:59:16.500   929  3034 D WifiNative-HAL: Setting external_sim to 1
,09-15 07:59:16.500  4355  4355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 07:59:16.500   929  3034 D wifi    : setting dfs flag to true, 0x7f6031d740
09-15 07:59:16.501   929  3034 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 07:59:16.501   929  3034 D wifi    : setting scan oui 0x7f6031d740
09-15 07:59:16.501   929  3034 D WifiHAL : Sending mac address OUI
,09-15 07:59:16.515   929  3034 E native  : do suspend true
,09-15 07:59:16.521   929   929 D RttService: SCAN_AVAILABLE : 3
,09-15 07:59:16.521   929  3034 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-15 07:59:16.521   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-15 07:59:16.521   929  3139 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 07:59:16.522   509   923 D CommandListener: Setting iface cfg
,09-15 07:59:16.528   929  3033 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,09-15 07:59:16.528   929  3033 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 07:59:16.534   929  3033 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 07:59:16.539   929  3033 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 07:59:16.539   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=231787 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=7 mControllerEnergyUsed=26 }
,09-15 07:59:16.777   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:59:17.778   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:59:18.712   929   940 D WifiService: setWifiEnabled: false pid=5508, uid=10077
09-15 07:59:18.712   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 07:59:18.718   929   929 D RttService: SCAN_AVAILABLE : 1
,09-15 07:59:18.719   929  3139 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 07:59:18.734   929  3034 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-15 07:59:18.735   509   923 D CommandListener: Clearing all IP addresses on wlan0
,09-15 07:59:18.739   929  3034 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 07:59:18.740  5671  5671 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-15 07:59:18.747  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 07:59:18.747  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:18.747  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:18.747  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:18.747  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:59:18.747  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:59:18.747  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:18.747  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:18.747  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:59:18.747  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:18.747  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:59:18.749  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:18.749  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:18.749  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:18.749  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:18.749  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:59:18.749  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:59:18.749  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:18.749  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:18.749  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:59:18.750  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:18.750  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:59:18.758  5671  5671 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-15 07:59:18.776  5671  5671 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 07:59:18.778   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 07:59:18.782  5671  5671 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 07:59:18.885   929  3034 D wifi    : In wifi stop Hal
09-15 07:59:18.885   929  3034 D wifi    : halHandle = 0x7f6f63c880, mVM = 0x7f7a0cd140, mCls = 0x18d2
09-15 07:59:18.886   929  5670 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-15 07:59:18.886   929  5670 D WifiHAL : Got a signal to exit!!!
,09-15 07:59:18.886   929  5670 I WifiHAL : Exit wifi_event_loop
,09-15 07:59:18.890   929  3034 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 07:59:18.890   929  3034 E WifiHAL : Event processing terminated
09-15 07:59:18.891  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:18.892  4355  4355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 07:59:18.893   929  3034 D wifi    : In wifi cleaned up handler
09-15 07:59:18.893   929  3034 I WifiHAL : Internal cleanup completed
09-15 07:59:18.895  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:18.896  3528  4093 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 07:59:18.911   929  5670 D wifi    : set interface wlan0 flags (DOWN)
,09-15 07:59:18.911   929  3034 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 07:59:19.115   929   946 D Tethering: InitialState.processMessage what=4
,09-15 07:59:19.119   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-15 07:59:21.754   929   946 I ActivityManager: Start proc 5677:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-15 07:59:21.849  5677  5677 D AdapterServiceConfig: Adding HeadsetService
,09-15 07:59:21.850  5677  5677 D AdapterServiceConfig: Adding A2dpService
09-15 07:59:21.850  5677  5677 D AdapterServiceConfig: Adding HidService
,09-15 07:59:21.850  5677  5677 D AdapterServiceConfig: Adding HealthService
09-15 07:59:21.850  5677  5677 D AdapterServiceConfig: Adding PanService
09-15 07:59:21.850  5677  5677 D AdapterServiceConfig: Adding GattService
09-15 07:59:21.851  5677  5677 D AdapterServiceConfig: Adding BluetoothMapService
,09-15 07:59:21.851  5677  5677 D AdapterServiceConfig: Adding SapService
,09-15 07:59:21.864   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26f6073:true
,09-15 07:59:21.864  5677  5677 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 07:59:21.867  5677  5677 I bt_bluedroid: init
,09-15 07:59:21.868  5677  5689 I BluetoothAdapterState: Entering OffState
,09-15 07:59:21.870  5677  5690 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-15 07:59:21.870  5677  5690 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 07:59:21.870  5677  5690 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 07:59:21.870  5677  5690 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-15 07:59:21.871  5677  5677 I bt_bluedroid: get_profile_interface socket
,09-15 07:59:21.874  5677  5677 I bt_bluedroid: get_profile_interface sdp
09-15 07:59:21.874  5677  5693 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 07:59:21.875  5677  5693 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 07:59:21.879  5677  5688 I bt_bluedroid: config_hci_snoop_log
,09-15 07:59:21.880   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 07:59:21.884  5677  5689 D BluetoothAdapterState: Current state: OFF, message: 0
,09-15 07:59:21.885  5677  5689 D BluetoothAdapterProperties: Setting state to 14
09-15 07:59:21.885  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-15 07:59:21.886  5677  5689 D BluetoothBondStateMachine: make
,09-15 07:59:21.888  5677  5694 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 07:59:21.890  5677  5689 I BluetoothAdapterState: Entering PendingCommandState
,09-15 07:59:21.891  5677  5677 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 07:59:21.893  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
09-15 07:59:21.894  5677  5677 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 07:59:21.894  5677  5677 D BtGatt.GattService: Received start request. Starting profile...
09-15 07:59:21.894  5677  5677 D BtGatt.GattService: start()
09-15 07:59:21.894  5677  5677 I bt_bluedroid: get_profile_interface gatt
09-15 07:59:21.895  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
09-15 07:59:21.895  5677  5677 D BtGatt.AdvertiseManager: advertise manager created
,09-15 07:59:21.900  5677  5677 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:21.900  5677  5677 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:21.900  5677  5677 V BluetoothAdapterState: isBleTurningOn()=true
09-15 07:59:21.901  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:21.901  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 07:59:21.902  5677  5689 I bt_bluedroid: bt_bluedroid
,09-15 07:59:21.902  5677  5690 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 07:59:21.903  5677  5690 I bt_hci  : start_up
,09-15 07:59:21.908  5677  5690 I bt_vendor: alloc value 0xf3c35871
,09-15 07:59:21.908  5677  5690 I bt_vendor: init
09-15 07:59:21.908  5677  5690 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 07:59:21.908  5677  5690 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 07:59:22.020  5677  5690 D bt_hci  : start_up starting async portion
,09-15 07:59:22.021  5677  5697 I bt_hci  : event_finish_startup
09-15 07:59:22.021  5677  5697 I bt_hci_h4: hal_open
09-15 07:59:22.021  5677  5697 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-15 07:59:22.018  5698  5698 W irq/448-msm_hs_: type=1400 audit(0.0:112): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 07:59:22.025  5677  5697 I bt_userial_vendor: device fd = 54 open
,09-15 07:59:22.039  5677  5697 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 07:59:22.042  5677  5697 D bt_hwcfg: Chipset BCM4358A3
,09-15 07:59:22.042  5677  5697 D bt_hwcfg: Target name = [BCM4358A3]
09-15 07:59:22.042  5677  5697 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 07:59:22.440  5677  5697 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-15 07:59:22.441  5677  5697 D bt_hwcfg: Settlement delay -- 100 ms
09-15 07:59:22.441  5677  5697 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 07:59:22.575  5677  5697 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-15 07:59:22.575  5677  5697 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-15 07:59:22.577  5677  5697 I bt_hwcfg: vendor lib fwcfg completed
09-15 07:59:22.577  5677  5697 I bt_vendor: firmware callback
,09-15 07:59:22.577  5677  5697 I bt_hci  : firmware_config_callback
,09-15 07:59:22.584   929   929 E WifiNative-wlan0: set PNO failure
,09-15 07:59:22.589  5677  5700 I bt_btu  : btu_task pending for preload complete event
,09-15 07:59:22.589  5677  5700 I bt_btu_task: Bluetooth chip preload is complete
09-15 07:59:22.589  5677  5700 I bt_btu  : btu_task received preload complete event
,09-15 07:59:22.595  5677  5700 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 07:59:22.595  5677  5700 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 07:59:22.595  5677  5700 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 07:59:22.595  5677  5700 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 07:59:22.595  5677  5700 I         : BTE_InitTraceLevels -- TRC_AVRC
09-15 07:59:22.595  5677  5700 I         : BTE_InitTraceLevels -- TRC_A2D
09-15 07:59:22.595  5677  5700 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-15 07:59:22.595  5677  5700 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 07:59:22.596  5677  5700 I         : BTE_InitTraceLevels -- TRC_GAP
09-15 07:59:22.596  5677  5700 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 07:59:22.596  5677  5700 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 07:59:22.596  5677  5700 I         : BTE_InitTraceLevels -- TRC_GATT
09-15 07:59:22.596  5677  5700 I         : BTE_InitTraceLevels -- TRC_SMP
,09-15 07:59:22.596  5677  5700 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-15 07:59:22.596  5677  5700 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 07:59:22.677  5677  5700 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bb3549
09-15 07:59:22.677  5677  5700 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bb3549 
,09-15 07:59:22.697  5677  5693 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 07:59:22.699  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 07:59:22.699  5677  5693 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 07:59:22.702  5677  5693 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 07:59:22.705  5677  5693 D BluetoothAdapterProperties: Scan Mode:20
,09-15 07:59:22.705  5677  5693 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 07:59:22.705  5677  5693 D bt_hci  : do_postload posting postload work item
09-15 07:59:22.706  5677  5697 I bt_hci  : event_postload
09-15 07:59:22.706  5677  5697 I bt_vendor: sco_config_cb
09-15 07:59:22.706  5677  5697 I bt_hci  : sco_config_callback postload finished.
,09-15 07:59:22.711  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:22.713  5677  5697 I bt_vendor: low_power_mode_cb
09-15 07:59:22.714  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:22.717  5677  5693 D bt_bte_conf: Device ID record 1 : primary
,09-15 07:59:22.717  5677  5693 D bt_bte_conf:   vendorId            = 000f
09-15 07:59:22.717  5677  5693 D bt_bte_conf:   vendorIdSource      = 0001
09-15 07:59:22.717  5677  5693 D bt_bte_conf:   product             = 1200
09-15 07:59:22.717  5677  5693 D bt_bte_conf:   version             = 1436
09-15 07:59:22.717  5677  5693 D bt_bte_conf:   clientExecutableURL = 
09-15 07:59:22.717  5677  5693 D bt_bte_conf:   serviceDescription  = 
,09-15 07:59:22.717  5677  5693 D bt_bte_conf:   documentationURL    = 
09-15 07:59:22.717  5677  5693 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 07:59:22.717  5677  5690 D bt_stack_manager: event_start_up_stack finished
09-15 07:59:22.719  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-15 07:59:22.720  5677  5689 D BluetoothAdapterProperties: Setting state to 15
09-15 07:59:22.720  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-15 07:59:22.721  5677  5689 I BluetoothAdapterState: Entering BleOnState
,09-15 07:59:22.723  5677  5689 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-15 07:59:22.723  5677  5689 D BluetoothAdapterProperties: Setting state to 11
09-15 07:59:22.724  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-15 07:59:22.729  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
09-15 07:59:22.731  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:22.733  5677  5677 D HeadsetService: Received start request. Starting profile...
09-15 07:59:22.734  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:22.736  5677  5677 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 07:59:22.736  5677  5677 D HeadsetStateMachine: make
,09-15 07:59:22.744  5677  5677 D HeadsetStateMachine: max_hf_connections = 1
,09-15 07:59:22.744  5677  5677 I bt_bluedroid: get_profile_interface handsfree
09-15 07:59:22.745  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-15 07:59:22.745  5677  5693 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-15 07:59:22.746  5677  5689 I BluetoothAdapterState: Entering PendingCommandState
,09-15 07:59:22.748  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
,09-15 07:59:22.749  5677  5677 D A2dpService: Received start request. Starting profile...
,09-15 07:59:22.749  5677  5677 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-15 07:59:22.750  5677  5677 I bt_bluedroid: get_profile_interface avrcp
,09-15 07:59:22.755  5677  5677 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-15 07:59:22.755  5677  5677 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 07:59:22.755  5677  5677 D A2dpStateMachine: make
,09-15 07:59:22.756  5677  5677 I bt_bluedroid: get_profile_interface a2dp
,09-15 07:59:22.757  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 07:59:22.758  5677  5708 D A2dpStateMachine: Enter Disconnected: -2
,09-15 07:59:22.760  5677  5677 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 07:59:22.761  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
,09-15 07:59:22.761  3669  3669 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 07:59:22.762  5677  5677 D HidService: Received start request. Starting profile...
09-15 07:59:22.762  5560  5560 D BluetoothInputDevice: Proxy object connected
09-15 07:59:22.762  5677  5677 I bt_bluedroid: get_profile_interface hidhost
09-15 07:59:22.762  5677  5677 D HidService: setHidService(): set to: null
09-15 07:59:22.762  5677  5693 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b9456d
09-15 07:59:22.762  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-15 07:59:22.763  5677  5677 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 07:59:22.763  5560  5560 D HidProfile: Bluetooth service connected
09-15 07:59:22.763  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
09-15 07:59:22.764  5677  5677 D HealthService: Received start request. Starting profile...
09-15 07:59:22.765  5677  5677 I bt_bluedroid: get_profile_interface health
,09-15 07:59:22.767  5677  5677 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-15 07:59:22.768  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
09-15 07:59:22.769  5677  5677 D PanService: Received start request. Starting profile...
,09-15 07:59:22.770  5677  5677 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-15 07:59:22.770  5677  5677 I bt_bluedroid: get_profile_interface pan
09-15 07:59:22.770  5677  5693 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-15 07:59:22.772  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
09-15 07:59:22.773  5560  5560 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 07:59:22.773  5677  5677 D BluetoothMapService: Received start request. Starting profile...
09-15 07:59:22.773  5677  5677 D BluetoothMapService: start()
,09-15 07:59:22.776  5677  5677 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-15 07:59:22.777  5560  5560 D PanProfile: Bluetooth service connected
09-15 07:59:22.777  5560  5560 D BluetoothMap: Proxy object connected
09-15 07:59:22.778  5677  5677 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-15 07:59:22.778  5677  5677 D BluetoothMapAppObserver: createReceiver()
,09-15 07:59:22.780  5677  5677 D BluetoothMapAppObserver: initObservers()
,09-15 07:59:22.780  5677  5677 D BluetoothMapAppObserver: getEnabledAccountItems()
09-15 07:59:22.778  5560  5560 D MapProfile: Bluetooth service connected
,09-15 07:59:22.781  5560  5560 D BluetoothMap: getConnectedDevices()
09-15 07:59:22.782  5560  5560 D BluetoothMap: Bluetooth is Not enabled
,09-15 07:59:22.787  5677  5677 V SapService: SapBinder()
09-15 07:59:22.787  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
,09-15 07:59:22.788  5677  5677 D SapService: Received start request. Starting profile...
09-15 07:59:22.788  5677  5677 V SapService: start()
,09-15 07:59:22.789  5677  5677 V BluetoothAdapterState: isTurningOff()=false
,09-15 07:59:22.789  5677  5677 V BluetoothAdapterState: isTurningOn()=true
09-15 07:59:22.789  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:22.790  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:22.790  5677  5677 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:22.790  5677  5677 V BluetoothAdapterState: isTurningOn()=true
,09-15 07:59:22.790  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:22.790  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:22.790  5677  5706 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 07:59:22.790  5677  5677 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:22.790  5677  5677 V BluetoothAdapterState: isTurningOn()=true
09-15 07:59:22.791  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:22.791  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 07:59:22.791  5677  5677 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:22.791  5677  5677 V BluetoothAdapterState: isTurningOn()=true
09-15 07:59:22.791  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:22.792  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:22.792  5677  5677 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:22.792  5677  5677 V BluetoothAdapterState: isTurningOn()=true
09-15 07:59:22.792  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:22.792  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 07:59:22.792  5677  5677 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:22.792  5677  5677 V BluetoothAdapterState: isTurningOn()=true
09-15 07:59:22.792  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:22.792  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:22.793  5677  5677 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:22.793  5677  5677 V BluetoothAdapterState: isTurningOn()=true
09-15 07:59:22.793  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:22.793  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 07:59:22.794  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 07:59:22.794  5677  5689 D BluetoothAdapterProperties: ScanMode =  20
09-15 07:59:22.794  5677  5689 D BluetoothAdapterProperties: State =  11
09-15 07:59:22.796  5677  5693 D BluetoothAdapterProperties: Scan Mode:21
09-15 07:59:22.796  5677  5693 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 07:59:22.797  5677  5689 D BluetoothAdapterProperties: Setting state to 12
09-15 07:59:22.797  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 07:59:22.797  3186  3199 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 07:59:22.799   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:59:22.799  5677  5689 I BluetoothAdapterState: Entering OnState
09-15 07:59:22.799  5560  5570 D BluetoothMap: onBluetoothStateChange: up=true
09-15 07:59:22.800  3186  3780 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 07:59:22.800  3186  3186 D BluetoothA2dp: Proxy object connected
09-15 07:59:22.801  5560  5571 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 07:59:22.802  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:22.802  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:22.802  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:22.802  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:59:22.802  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:22.802  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:22.802  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:22.802  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:59:22.803  3588  3618 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:59:22.803  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:59:22.803  3186  3199 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:59:22.804  5560  5570 D BluetoothPan: onBluetoothStateChange on: true
09-15 07:59:22.804   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:59:22.804  3186  3203 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 07:59:22.806  3186  3186 D BluetoothInputDevice: Proxy object connected
09-15 07:59:22.806  3186  3780 D BluetoothMap: onBluetoothStateChange: up=true
09-15 07:59:22.806  3186  3186 D HidProfile: Bluetooth service connected
09-15 07:59:22.807  5677  5677 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 07:59:22.807  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:22.807  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:22.807  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:22.807  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:59:22.807  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:22.807  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:22.807  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:22.807  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:59:22.807  5560  5571 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 07:59:22.807  5677  5677 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-15 07:59:22.807   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 07:59:22.807  3186  3186 D BluetoothMap: Proxy object connected
09-15 07:59:22.808  3186  3186 D MapProfile: Bluetooth service connected
09-15 07:59:22.808  3186  3186 D BluetoothMap: getConnectedDevices()
09-15 07:59:22.808   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:59:22.808  3186  3203 D BluetoothPan: onBluetoothStateChange on: true
09-15 07:59:22.808   929   929 D BluetoothA2dp: Proxy object connected
09-15 07:59:22.808  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:59:22.810  5677  5677 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 07:59:22.811  5677  5677 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 07:59:22.812  3186  3186 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 07:59:22.812  3186  3186 D PanProfile: Bluetooth service connected
09-15 07:59:22.813   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-15 07:59:22.815  5677  5677 D ObexServerSockets: Succeed to create listening sockets 
09-15 07:59:22.815  5677  5677 D ObexServerSockets0: startAccept()
09-15 07:59:22.815  5677  5677 D ObexServerSockets0: prepareForNewConnect()
09-15 07:59:22.816  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:22.816  5560  5560 D LocalBluetoothProfileManager: Adding local A2DP profile
09-15 07:59:22.817  5677  5677 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-15 07:59:22.817  5677  5677 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 07:59:22.817  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:22.818  5677  5716 D ObexServerSockets0: Accepting socket connection...
09-15 07:59:22.818  5677  5677 D BluetoothMapService: onReceive
09-15 07:59:22.818  5677  5677 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 07:59:22.818  5677  5677 D BluetoothMapService: STATE_ON
09-15 07:59:22.818  5677  5715 D ObexServerSockets0: Accepting socket connection...
09-15 07:59:22.820  5677  5717 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 07:59:22.820  5560  5560 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-15 07:59:22.821  5677  5717 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-15 07:59:22.821  5677  5717 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-15 07:59:22.827  5560  5560 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 07:59:22.829  5560  5560 D BluetoothA2dp: Proxy object connected
09-15 07:59:22.833  3669  3669 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 07:59:22.836  5560  5560 D DockEventReceiver: finishStartingService: stopping service
09-15 07:59:22.839  5560  5560 D BluetoothPbap: Proxy object connected
09-15 07:59:22.840  5560  5560 D PbapServerProfile: Bluetooth service connected
09-15 07:59:22.843  3186  3186 D BluetoothPbap: Proxy object connected
09-15 07:59:22.843  3186  3186 D PbapServerProfile: Bluetooth service connected
09-15 07:59:22.845  5677  5677 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 07:59:22.845  5677  5677 D ObexServerSockets0: prepareForNewConnect()
09-15 07:59:22.847  5677  5721 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 07:59:22.859  5677  5725 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 07:59:22.860  5677  5725 I BtOppRfcommListener: Accept thread started.
,09-15 07:59:22.900  3588  3820 D BluetoothHeadset: Proxy object connected
,09-15 07:59:22.900   929   929 D BluetoothHeadset: Proxy object connected
09-15 07:59:22.900   929   929 D BluetoothHeadset: Proxy object connected
09-15 07:59:22.900   929   929 D BluetoothHeadset: Proxy object connected
,09-15 07:59:22.900  3186  3776 D BluetoothHeadset: Proxy object connected
,09-15 07:59:22.901  3186  3186 D HeadsetProfile: Bluetooth service connected
,09-15 07:59:22.904  3588  3614 D BluetoothHeadset: Proxy object connected
,09-15 07:59:22.904  3186  3199 D BluetoothHeadset: Proxy object connected
09-15 07:59:22.905  3186  3186 D HeadsetProfile: Bluetooth service connected
09-15 07:59:22.905   929   946 D BluetoothHeadset: Proxy object connected
,09-15 07:59:22.908   929   946 D BluetoothHeadset: Proxy object connected
,09-15 07:59:22.923  5560  5571 D BluetoothHeadset: Proxy object connected
,09-15 07:59:22.924  5560  5560 D HeadsetProfile: Bluetooth service connected
,09-15 07:59:23.779   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:59:24.729  5677  5689 D BluetoothAdapterState: Current state: ON, message: 23
,09-15 07:59:24.730  5677  5689 D BluetoothAdapterProperties: Setting state to 13
09-15 07:59:24.730  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-15 07:59:24.731  5677  5689 D BluetoothAdapterProperties: onBluetoothDisable()
,09-15 07:59:24.735  5677  5689 I BluetoothAdapterState: Entering PendingCommandState
,09-15 07:59:24.740  5677  5677 D BluetoothMapService: onReceive
,09-15 07:59:24.740  5677  5677 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-15 07:59:24.741  5677  5677 D BluetoothMapService: STATE_TURNING_OFF
,09-15 07:59:24.743  5677  5677 D BluetoothMapService: MAP Service closeService in
09-15 07:59:24.743  5677  5677 D BluetoothMapMasInstance0: MAP Service shutdown
09-15 07:59:24.743  5677  5677 D ObexServerSockets0: shutdown(block = true)
09-15 07:59:24.744  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:24.745  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:24.745  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:24.745  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:24.745  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:59:24.745  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:59:24.745  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:24.745  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:24.745  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:59:24.746  5677  5677 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 07:59:24.746  5677  5715 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-15 07:59:24.747  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:24.747  5677  5677 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 07:59:24.747  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:59:24.747  5677  5702 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-15 07:59:24.748  5677  5716 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-15 07:59:24.749  5677  5677 I BtOppRfcommListener: stopping Accept Thread
09-15 07:59:24.750  5677  5725 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 07:59:24.750  5677  5725 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 07:59:24.751  5677  5693 D BluetoothAdapterProperties: Scan Mode:20
09-15 07:59:24.753  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-15 07:59:24.753  5560  5560 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 07:59:24.755  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:24.755  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:24.755  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:24.755  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:24.755  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:59:24.755  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 07:59:24.755  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:24.755  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:24.755  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:59:24.757  5508  5508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 07:59:24.757  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:59:24.759  5677  5677 D HeadsetService: Received stop request...Stopping profile...
09-15 07:59:24.761  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:24.764  5560  5570 D BluetoothHeadset: Proxy object disconnected
09-15 07:59:24.765  3588  3618 D BluetoothHeadset: Proxy object disconnected
09-15 07:59:24.766   929   929 D BluetoothHeadset: Proxy object disconnected
,09-15 07:59:24.766  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:24.766   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 07:59:24.766   929   929 D BluetoothHeadset: Proxy object disconnected
,09-15 07:59:24.766  3186  3199 D BluetoothHeadset: Proxy object disconnected
,09-15 07:59:24.770  3186  3186 D HeadsetProfile: Bluetooth service disconnected
,09-15 07:59:24.771  5677  5677 D A2dpService: Received stop request...Stopping profile...
09-15 07:59:24.772  5677  5708 D A2dpStateMachine: Exit Disconnected: -1
,09-15 07:59:24.773   929   929 D BluetoothA2dp: Proxy object disconnected
09-15 07:59:24.773  3186  3186 D BluetoothA2dp: Proxy object disconnected
09-15 07:59:24.774  5677  5677 D HidService: Received stop request...Stopping profile...
09-15 07:59:24.774  5677  5677 D HidService: Stopping Bluetooth HidService
09-15 07:59:24.775  3186  3186 D BluetoothInputDevice: Proxy object disconnected
09-15 07:59:24.776  3186  3186 D HidProfile: Bluetooth service disconnected
09-15 07:59:24.776  5677  5677 D HealthService: Received stop request...Stopping profile...
,09-15 07:59:24.777  5560  5560 D DockEventReceiver: finishStartingService: stopping service
09-15 07:59:24.778  5677  5677 V BluetoothAdapterState: isTurningOff()=true
09-15 07:59:24.778  5677  5677 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:24.778  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:24.778  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:24.779  5560  5560 D HeadsetProfile: Bluetooth service disconnected
,09-15 07:59:24.779  5677  5677 D PanService: Received stop request...Stopping profile...
09-15 07:59:24.779  5560  5560 D BluetoothA2dp: Proxy object disconnected
09-15 07:59:24.779   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:59:24.779  5560  5560 D BluetoothInputDevice: Proxy object disconnected
09-15 07:59:24.779  5560  5560 D HidProfile: Bluetooth service disconnected
09-15 07:59:24.780  3186  3186 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 07:59:24.780  3186  3186 D PanProfile: Bluetooth service disconnected
09-15 07:59:24.781  5560  5560 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 07:59:24.781  5560  5560 D PanProfile: Bluetooth service disconnected
,09-15 07:59:24.782  5677  5677 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-15 07:59:24.783  5677  5677 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-15 07:59:24.783  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 07:59:24.783  5677  5700 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:59:24.783  5677  5700 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:59:24.783  5677  5700 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:59:24.783  5677  5693 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-15 07:59:24.783  5677  5677 D BluetoothMapService: Received stop request...Stopping profile...
09-15 07:59:24.783  5677  5677 D BluetoothMapService: stop()
09-15 07:59:24.784  5677  5677 D BluetoothMapAppObserver: deinitObservers()
09-15 07:59:24.784  5677  5677 D BluetoothMapAppObserver: removeReceiver()
09-15 07:59:24.785  3186  3186 D BluetoothMap: Proxy object disconnected
,09-15 07:59:24.785  3186  3186 D MapProfile: Bluetooth service disconnected
09-15 07:59:24.786  5677  5677 D SapService: Received stop request...Stopping profile...
09-15 07:59:24.786  5677  5677 V SapService: stop()
09-15 07:59:24.787  5677  5677 V BluetoothAdapterState: isTurningOff()=true
09-15 07:59:24.788  5677  5677 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:24.788  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:24.788  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:24.789  5560  5560 D BluetoothMap: Proxy object disconnected
09-15 07:59:24.789  3669  3669 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 07:59:24.789  5560  5560 D MapProfile: Bluetooth service disconnected
,09-15 07:59:24.789  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-15 07:59:24.789  5677  5677 V BluetoothAdapterState: isTurningOff()=true
09-15 07:59:24.789  5677  5677 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:24.789  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:24.789  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:24.789  5677  5677 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-15 07:59:24.789  5677  5677 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 07:59:24.790  5677  5677 V BluetoothAdapterState: isTurningOff()=true
09-15 07:59:24.790  5677  5677 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:24.790  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:24.790  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:24.790  5677  5700 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:59:24.790  5677  5700 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:59:24.790  5677  5677 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-15 07:59:24.790  5677  5700 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-15 07:59:24.790  5677  5700 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 07:59:24.790  5677  5700 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 07:59:24.790  5677  5700 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 07:59:24.790  5677  5677 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-15 07:59:24.790  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 07:59:24.790  5677  5677 V BluetoothAdapterState: isTurningOff()=true
09-15 07:59:24.790  5677  5677 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:24.790  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:24.791  5677  5693 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 07:59:24.791  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:24.791  5677  5677 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 07:59:24.791  5677  5677 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-15 07:59:24.792  5677  5677 D BluetoothMapService: MAP Service closeService in
09-15 07:59:24.792  5677  5677 V BluetoothAdapterState: isTurningOff()=true
09-15 07:59:24.792  5677  5677 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:24.792  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:24.792  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:24.792  5677  5677 D BluetoothMapService: cleanup()
09-15 07:59:24.792  5677  5677 D BluetoothMapService: MAP Service closeService in
09-15 07:59:24.793  5677  5677 V BluetoothAdapterState: isTurningOff()=true
09-15 07:59:24.793  5677  5677 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:24.793  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 07:59:24.793  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:24.793  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 07:59:24.793  5677  5689 D BluetoothAdapterProperties: Setting state to 15
09-15 07:59:24.793  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 07:59:24.794  5677  5689 I BluetoothAdapterState: Entering BleOnState
09-15 07:59:24.794  3186  3203 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 07:59:24.795  3186  3186 D BluetoothPbap: Proxy object disconnected
09-15 07:59:24.795  3186  3186 D PbapServerProfile: Bluetooth service disconnected
09-15 07:59:24.795  5560  5560 D BluetoothPbap: Proxy object disconnected
09-15 07:59:24.795  5560  5560 D PbapServerProfile: Bluetooth service disconnected
09-15 07:59:24.797   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 07:59:24.798  5560  5571 D BluetoothMap: onBluetoothStateChange: up=false
,09-15 07:59:24.799  3186  3776 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 07:59:24.800  5560  5570 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 07:59:24.801  3588  3820 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:59:24.802  3186  3780 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:59:24.802  5560  5571 D BluetoothPan: onBluetoothStateChange on: false
09-15 07:59:24.803   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:59:24.803  5560  5570 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-15 07:59:24.803  3186  3199 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 07:59:24.804  3186  3203 D BluetoothMap: onBluetoothStateChange: up=false
09-15 07:59:24.804  5560  5571 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:59:24.805  5560  5570 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 07:59:24.805   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 07:59:24.805   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 07:59:24.805  3186  3776 D BluetoothPan: onBluetoothStateChange on: false
,09-15 07:59:24.806  5677  5689 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 07:59:24.806  5677  5689 D BluetoothAdapterProperties: Setting state to 16
09-15 07:59:24.806  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 07:59:24.807  5677  5689 D BluetoothAdapterProperties: onBleDisable
09-15 07:59:24.807  5677  5689 I BluetoothAdapterState: Entering PendingCommandState
09-15 07:59:24.807  5677  5690 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-15 07:59:24.808  5677  5693 D BluetoothAdapterProperties: Scan Mode:20
,09-15 07:59:24.810  5677  5700 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-15 07:59:24.810  5677  5700 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 07:59:24.810  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:24.813  5560  5560 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 07:59:24.814  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:24.815  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:24.817  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:24.819  3669  3669 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 07:59:24.824  5560  5560 D DockEventReceiver: finishStartingService: stopping service
,09-15 07:59:25.022  5677  5693 I bt_hci  : shut_down
,09-15 07:59:25.027  5677  5697 D bt_hwcfg: hw_epilog_process
,09-15 07:59:25.027  5677  5697 I bt_vendor: low_power_mode_cb
,09-15 07:59:25.029  5677  5697 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-15 07:59:25.029  5677  5697 I bt_vendor: epilog_cb
09-15 07:59:25.029  5677  5697 I bt_hci  : epilog_finished_callback
,09-15 07:59:25.032  5677  5693 I bt_hci_h4: hal_close
,09-15 07:59:25.032  5677  5693 I bt_userial_vendor: device fd = 54 close
,09-15 07:59:25.150  5677  5690 D bt_stack_manager: event_shut_down_stack finished.
,09-15 07:59:25.151  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-15 07:59:25.155  5677  5689 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-15 07:59:25.156  5677  5677 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 07:59:25.157  5677  5677 D BtGatt.GattService: Received stop request...Stopping profile...
09-15 07:59:25.158  5677  5677 D BtGatt.GattService: stop()
09-15 07:59:25.158  5677  5677 D BtGatt.AdvertiseManager: advertise clients cleared
,09-15 07:59:25.162  5677  5677 V BluetoothAdapterState: isTurningOff()=false
,09-15 07:59:25.162  5677  5677 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:25.162  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:25.162  5677  5677 V BluetoothAdapterState: isBleTurningOff()=true
,09-15 07:59:25.162  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 07:59:25.163  5677  5689 D BluetoothAdapterProperties: Setting state to 10
09-15 07:59:25.163  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-15 07:59:25.164  5677  5689 I BluetoothAdapterState: Entering OffState
,09-15 07:59:25.165   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-15 07:59:25.178  5677  5677 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-15 07:59:25.178  5677  5677 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 07:59:25.178  5677  5677 I BluetoothServiceJni: cleanupNative: return from cleanup
09-15 07:59:25.181  5677  5690 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 07:59:25.189  5677  5677 I art     : System.exit called, status: 0
,09-15 07:59:25.189  5677  5677 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-15 07:59:25.218   929  3595 I ActivityManager: Process com.android.bluetooth (pid 5677) has died
,09-15 07:59:25.780   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:59:26.781   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:59:27.728  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:27.728  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:59:27.782   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 07:59:28.782   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 07:59:30.737  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 07:59:30.737  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@966056b added. We now have 6 listener(s)
09-15 07:59:30.737  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:59:30.742  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 07:59:30.742  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d918c8 added. We now have 7 listener(s)
09-15 07:59:30.742  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 07:59:30.744  5508  5554 I System.out: IsBluetoothEnabled
,09-15 07:59:30.752  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:30.773   929   946 I ActivityManager: Start proc 5733:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-15 07:59:30.839  5733  5733 D AdapterServiceConfig: Adding HeadsetService
,09-15 07:59:30.840  5733  5733 D AdapterServiceConfig: Adding A2dpService
09-15 07:59:30.840  5733  5733 D AdapterServiceConfig: Adding HidService
09-15 07:59:30.840  5733  5733 D AdapterServiceConfig: Adding HealthService
09-15 07:59:30.840  5733  5733 D AdapterServiceConfig: Adding PanService
09-15 07:59:30.840  5733  5733 D AdapterServiceConfig: Adding GattService
09-15 07:59:30.840  5733  5733 D AdapterServiceConfig: Adding BluetoothMapService
09-15 07:59:30.841  5733  5733 D AdapterServiceConfig: Adding SapService
,09-15 07:59:30.850   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5cda7f0:true
,09-15 07:59:30.851  5733  5733 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 07:59:30.854  5733  5733 I bt_bluedroid: init
,09-15 07:59:30.854  5733  5745 I BluetoothAdapterState: Entering OffState
,09-15 07:59:30.856  5733  5746 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-15 07:59:30.856  5733  5746 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 07:59:30.856  5733  5746 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 07:59:30.856  5733  5746 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-15 07:59:30.856  5733  5733 I bt_bluedroid: get_profile_interface socket
,09-15 07:59:30.858  5733  5749 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 07:59:30.859  5733  5733 I bt_bluedroid: get_profile_interface sdp
09-15 07:59:30.860  5733  5749 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 07:59:30.864  5733  5744 I bt_bluedroid: config_hci_snoop_log
,09-15 07:59:30.865   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 07:59:30.869  5733  5745 D BluetoothAdapterState: Current state: OFF, message: 0
,09-15 07:59:30.869  5733  5745 D BluetoothAdapterProperties: Setting state to 14
09-15 07:59:30.869  5733  5745 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-15 07:59:30.870  5733  5745 D BluetoothBondStateMachine: make
,09-15 07:59:30.872  5733  5750 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 07:59:30.874  5733  5745 I BluetoothAdapterState: Entering PendingCommandState
,09-15 07:59:30.875  5733  5733 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 07:59:30.877  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
09-15 07:59:30.877  5733  5733 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 07:59:30.878  5733  5733 D BtGatt.GattService: Received start request. Starting profile...
09-15 07:59:30.878  5733  5733 D BtGatt.GattService: start()
09-15 07:59:30.878  5733  5733 I bt_bluedroid: get_profile_interface gatt
,09-15 07:59:30.879  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
,09-15 07:59:30.879  5733  5733 D BtGatt.AdvertiseManager: advertise manager created
,09-15 07:59:30.884  5733  5733 V BluetoothAdapterState: isTurningOff()=false
,09-15 07:59:30.884  5733  5733 V BluetoothAdapterState: isTurningOn()=false
09-15 07:59:30.884  5733  5733 V BluetoothAdapterState: isBleTurningOn()=true
09-15 07:59:30.884  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:30.884  5733  5745 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 07:59:30.885  5733  5745 I bt_bluedroid: bt_bluedroid
09-15 07:59:30.885  5733  5746 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 07:59:30.886  5733  5746 I bt_hci  : start_up
,09-15 07:59:30.890  5733  5746 I bt_vendor: alloc value 0xf3c35871
09-15 07:59:30.891  5733  5746 I bt_vendor: init
09-15 07:59:30.891  5733  5746 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 07:59:30.891  5733  5746 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 07:59:31.002  5733  5746 D bt_hci  : start_up starting async portion
,09-15 07:59:31.002  5733  5753 I bt_hci  : event_finish_startup
09-15 07:59:31.002  5733  5753 I bt_hci_h4: hal_open
09-15 07:59:31.002  5733  5753 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-15 07:59:30.998  5754  5754 W irq/448-msm_hs_: type=1400 audit(0.0:113): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 07:59:31.006  5733  5753 I bt_userial_vendor: device fd = 54 open
,09-15 07:59:31.020  5733  5753 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 07:59:31.023  5733  5753 D bt_hwcfg: Chipset BCM4358A3
09-15 07:59:31.023  5733  5753 D bt_hwcfg: Target name = [BCM4358A3]
,09-15 07:59:31.023  5733  5753 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 07:59:31.427  5733  5753 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-15 07:59:31.428  5733  5753 D bt_hwcfg: Settlement delay -- 100 ms
,09-15 07:59:31.428  5733  5753 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 07:59:31.561  5733  5753 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 07:59:31.562  5733  5753 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-15 07:59:31.565  5733  5753 I bt_hwcfg: vendor lib fwcfg completed
09-15 07:59:31.565  5733  5753 I bt_vendor: firmware callback
09-15 07:59:31.565  5733  5753 I bt_hci  : firmware_config_callback
,09-15 07:59:31.574  5733  5756 I bt_btu  : btu_task pending for preload complete event
,09-15 07:59:31.574  5733  5756 I bt_btu_task: Bluetooth chip preload is complete
,09-15 07:59:31.574  5733  5756 I bt_btu  : btu_task received preload complete event
,09-15 07:59:31.581  5733  5756 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 07:59:31.582  5733  5756 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 07:59:31.582  5733  5756 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 07:59:31.582  5733  5756 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 07:59:31.582  5733  5756 I         : BTE_InitTraceLevels -- TRC_AVRC
09-15 07:59:31.582  5733  5756 I         : BTE_InitTraceLevels -- TRC_A2D
,09-15 07:59:31.582  5733  5756 I         : BTE_InitTraceLevels -- TRC_BNEP
09-15 07:59:31.582  5733  5756 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 07:59:31.582  5733  5756 I         : BTE_InitTraceLevels -- TRC_GAP
09-15 07:59:31.582  5733  5756 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 07:59:31.582  5733  5756 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 07:59:31.583  5733  5756 I         : BTE_InitTraceLevels -- TRC_GATT
,09-15 07:59:31.583  5733  5756 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 07:59:31.583  5733  5756 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-15 07:59:31.583  5733  5756 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 07:59:31.666  5733  5756 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bb3549
,09-15 07:59:31.666  5733  5756 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bb3549 
,09-15 07:59:31.686  5733  5749 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 07:59:31.687  5733  5749 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 07:59:31.688  5733  5749 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-15 07:59:31.690  5733  5749 D BluetoothAdapterProperties: Name is: Nexus 6P
09-15 07:59:31.693  5733  5749 D BluetoothAdapterProperties: Scan Mode:20
09-15 07:59:31.693  5733  5749 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 07:59:31.693  5733  5749 D bt_hci  : do_postload posting postload work item
09-15 07:59:31.694  5733  5753 I bt_hci  : event_postload
09-15 07:59:31.694  5733  5753 I bt_vendor: sco_config_cb
,09-15 07:59:31.694  5733  5753 I bt_hci  : sco_config_callback postload finished.
,09-15 07:59:31.699  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:31.701  5733  5749 D bt_bte_conf: Device ID record 1 : primary
,09-15 07:59:31.701  5733  5753 I bt_vendor: low_power_mode_cb
09-15 07:59:31.701  5733  5749 D bt_bte_conf:   vendorId            = 000f
09-15 07:59:31.701  5733  5749 D bt_bte_conf:   vendorIdSource      = 0001
09-15 07:59:31.701  5733  5749 D bt_bte_conf:   product             = 1200
09-15 07:59:31.701  5733  5749 D bt_bte_conf:   version             = 1436
09-15 07:59:31.701  5733  5749 D bt_bte_conf:   clientExecutableURL = 
09-15 07:59:31.701  5733  5749 D bt_bte_conf:   serviceDescription  = 
09-15 07:59:31.701  5733  5749 D bt_bte_conf:   documentationURL    = 
,09-15 07:59:31.701  5733  5749 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 07:59:31.702  5733  5746 D bt_stack_manager: event_start_up_stack finished
,09-15 07:59:31.703  5733  5745 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 07:59:31.703  5733  5745 D BluetoothAdapterProperties: Setting state to 15
09-15 07:59:31.704  5733  5745 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-15 07:59:31.706  5733  5745 I BluetoothAdapterState: Entering BleOnState
,09-15 07:59:31.710  5733  5745 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-15 07:59:31.710  5733  5745 D BluetoothAdapterProperties: Setting state to 11
09-15 07:59:31.710  5733  5745 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-15 07:59:31.715  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
,09-15 07:59:31.717  5733  5733 D HeadsetService: Received start request. Starting profile...
,09-15 07:59:31.718  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:31.720  5733  5733 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-15 07:59:31.720  5733  5733 D HeadsetStateMachine: make
,09-15 07:59:31.729  5733  5745 I BluetoothAdapterState: Entering PendingCommandState
,09-15 07:59:31.729  5733  5733 D HeadsetStateMachine: max_hf_connections = 1
09-15 07:59:31.730  5733  5733 I bt_bluedroid: get_profile_interface handsfree
,09-15 07:59:31.732  5733  5749 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-15 07:59:31.733  5733  5749 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-15 07:59:31.734  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
,09-15 07:59:31.734  5733  5733 D A2dpService: Received start request. Starting profile...
,09-15 07:59:31.735  5733  5733 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-15 07:59:31.735  5733  5733 I bt_bluedroid: get_profile_interface avrcp
,09-15 07:59:31.741  5733  5733 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-15 07:59:31.741  5733  5733 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 07:59:31.741  5733  5733 D A2dpStateMachine: make
,09-15 07:59:31.742  5733  5733 I bt_bluedroid: get_profile_interface a2dp
,09-15 07:59:31.743  5733  5749 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 07:59:31.744  5733  5764 D A2dpStateMachine: Enter Disconnected: -2
09-15 07:59:31.744  5733  5733 I BluetoothHidServiceJni: classInitNative: succeeds
09-15 07:59:31.745  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
,09-15 07:59:31.746  5733  5733 D HidService: Received start request. Starting profile...
,09-15 07:59:31.746  5733  5733 I bt_bluedroid: get_profile_interface hidhost
09-15 07:59:31.746  5733  5733 D HidService: setHidService(): set to: null
09-15 07:59:31.746  5733  5749 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b9456d
09-15 07:59:31.746  5733  5749 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 07:59:31.747  5733  5733 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 07:59:31.747  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
09-15 07:59:31.748  5733  5733 D HealthService: Received start request. Starting profile...
,09-15 07:59:31.749  5733  5733 I bt_bluedroid: get_profile_interface health
,09-15 07:59:31.750  5733  5733 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-15 07:59:31.750  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
09-15 07:59:31.751  5733  5733 D PanService: Received start request. Starting profile...
09-15 07:59:31.751  5733  5733 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 07:59:31.751  5733  5733 I bt_bluedroid: get_profile_interface pan
09-15 07:59:31.752  5733  5749 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-15 07:59:31.755  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
,09-15 07:59:31.755  5733  5733 D BluetoothMapService: Received start request. Starting profile...
,09-15 07:59:31.755  5733  5733 D BluetoothMapService: start()
09-15 07:59:31.758  5733  5733 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-15 07:59:31.759  5733  5733 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-15 07:59:31.759  5733  5733 D BluetoothMapAppObserver: createReceiver()
09-15 07:59:31.760  5733  5733 D BluetoothMapAppObserver: initObservers()
09-15 07:59:31.760  5733  5733 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 07:59:31.766  5733  5733 V SapService: SapBinder()
09-15 07:59:31.766  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
09-15 07:59:31.767  5733  5733 D SapService: Received start request. Starting profile...
09-15 07:59:31.767  5733  5733 V SapService: start()
09-15 07:59:31.769  5733  5733 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:31.769  5733  5733 V BluetoothAdapterState: isTurningOn()=true
09-15 07:59:31.769  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:31.769  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isTurningOn()=true
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:31.770  5733  5762 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isTurningOn()=true
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isTurningOn()=true
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isTurningOn()=true
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isTurningOn()=true
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:31.770  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:31.771  3669  3669 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 07:59:31.771  5733  5733 V BluetoothAdapterState: isTurningOff()=false
09-15 07:59:31.771  5733  5733 V BluetoothAdapterState: isTurningOn()=true
09-15 07:59:31.771  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-15 07:59:31.771  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-15 07:59:31.771  5733  5745 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 07:59:31.771  5733  5745 D BluetoothAdapterProperties: ScanMode =  20
09-15 07:59:31.771  5733  5745 D BluetoothAdapterProperties: State =  11
09-15 07:59:31.775  5733  5749 D BluetoothAdapterProperties: Scan Mode:21
09-15 07:59:31.776  5733  5745 D BluetoothAdapterProperties: Setting state to 12
09-15 07:59:31.776  5733  5745 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 07:59:31.776  5733  5749 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 07:59:31.776  3186  3203 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 07:59:31.777  5733  5745 I BluetoothAdapterState: Entering OnState
09-15 07:59:31.778   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:59:31.778  5560  5570 D BluetoothMap: onBluetoothStateChange: up=true
09-15 07:59:31.779  3186  3186 D BluetoothA2dp: Proxy object connected
09-15 07:59:31.780  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:31.780  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:31.780  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:31.780  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:59:31.780  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:31.780  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:31.780  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:31.780  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:59:31.780  3186  3780 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 07:59:31.783  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:59:31.783  5560  5570 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 07:59:31.784  3588  3618 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:59:31.784  3186  3776 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:59:31.785  5560  5571 D BluetoothPan: onBluetoothStateChange on: true
09-15 07:59:31.785  5733  5733 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 07:59:31.786  5733  5733 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-15 07:59:31.787   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:59:31.787  5560  5570 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 07:59:31.787  5733  5733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 07:59:31.789  5560  5560 D BluetoothMap: Proxy object connected
09-15 07:59:31.789  5560  5560 D MapProfile: Bluetooth service connected
09-15 07:59:31.789  5560  5560 D BluetoothMap: getConnectedDevices()
09-15 07:59:31.790  5733  5733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 07:59:31.790  3186  3203 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 07:59:31.791  5733  5733 D ObexServerSockets: Succeed to create listening sockets 
09-15 07:59:31.791  5733  5733 D ObexServerSockets0: startAccept()
,09-15 07:59:31.791  5733  5733 D ObexServerSockets0: prepareForNewConnect()
09-15 07:59:31.792  3186  3199 D BluetoothMap: onBluetoothStateChange: up=true
09-15 07:59:31.793  5733  5733 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-15 07:59:31.793  5733  5733 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 07:59:31.794  5733  5771 D ObexServerSockets0: Accepting socket connection...
09-15 07:59:31.794  5733  5772 D ObexServerSockets0: Accepting socket connection...
09-15 07:59:31.794  3186  3186 D BluetoothMap: Proxy object connected
09-15 07:59:31.794  3186  3186 D MapProfile: Bluetooth service connected
09-15 07:59:31.794  3186  3186 D BluetoothMap: getConnectedDevices()
09-15 07:59:31.795  5560  5570 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:59:31.796  3186  3186 D BluetoothInputDevice: Proxy object connected
09-15 07:59:31.796  5560  5571 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 07:59:31.796  3186  3186 D HidProfile: Bluetooth service connected
,09-15 07:59:31.798   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-15 07:59:31.799   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 07:59:31.799   929   929 D BluetoothA2dp: Proxy object connected
09-15 07:59:31.799  3186  3203 D BluetoothPan: onBluetoothStateChange on: true
09-15 07:59:31.800  3186  3186 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 07:59:31.801  3186  3186 D PanProfile: Bluetooth service connected
09-15 07:59:31.802   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-15 07:59:31.803  5733  5733 D BluetoothMapService: onReceive
,09-15 07:59:31.803  5733  5733 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 07:59:31.803  5733  5733 D BluetoothMapService: STATE_ON
09-15 07:59:31.803  5560  5560 D BluetoothA2dp: Proxy object connected
09-15 07:59:31.803  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:31.805  5733  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 07:59:31.805  5560  5560 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 07:59:31.805  5560  5560 D PanProfile: Bluetooth service connected
09-15 07:59:31.805  5560  5560 D BluetoothInputDevice: Proxy object connected
09-15 07:59:31.805  5560  5560 D HidProfile: Bluetooth service connected
,09-15 07:59:31.807  5733  5773 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-15 07:59:31.807  5733  5773 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-15 07:59:31.811  5560  5560 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 07:59:31.817  3669  3669 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 07:59:31.818  5560  5560 D DockEventReceiver: finishStartingService: stopping service
,09-15 07:59:31.825  5560  5560 D BluetoothPbap: Proxy object connected
,09-15 07:59:31.825  5560  5560 D PbapServerProfile: Bluetooth service connected
,09-15 07:59:31.828  3186  3186 D BluetoothPbap: Proxy object connected
09-15 07:59:31.829  3186  3186 D PbapServerProfile: Bluetooth service connected
09-15 07:59:31.829  5733  5733 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 07:59:31.829  5733  5733 D ObexServerSockets0: prepareForNewConnect()
,09-15 07:59:31.831  5733  5777 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 07:59:31.848  5733  5781 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 07:59:31.849  5733  5781 I BtOppRfcommListener: Accept thread started.
,09-15 07:59:31.881  5560  5571 D BluetoothHeadset: Proxy object connected
,09-15 07:59:31.881  3588  3820 D BluetoothHeadset: Proxy object connected
09-15 07:59:31.881   929   929 D BluetoothHeadset: Proxy object connected
09-15 07:59:31.881   929   929 D BluetoothHeadset: Proxy object connected
09-15 07:59:31.881   929   929 D BluetoothHeadset: Proxy object connected
09-15 07:59:31.882  3186  3780 D BluetoothHeadset: Proxy object connected
09-15 07:59:31.882  3186  3186 D HeadsetProfile: Bluetooth service connected
09-15 07:59:31.883  5560  5560 D HeadsetProfile: Bluetooth service connected
,09-15 07:59:31.885  3588  3614 D BluetoothHeadset: Proxy object connected
09-15 07:59:31.885  3186  3776 D BluetoothHeadset: Proxy object connected
09-15 07:59:31.885  3186  3186 D HeadsetProfile: Bluetooth service connected
,09-15 07:59:31.887   929   946 D BluetoothHeadset: Proxy object connected
,09-15 07:59:31.896  5560  5570 D BluetoothHeadset: Proxy object connected
,09-15 07:59:31.896  5560  5560 D HeadsetProfile: Bluetooth service connected
09-15 07:59:31.899   929   946 D BluetoothHeadset: Proxy object connected
,09-15 07:59:32.771  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:32.771  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:32.771  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:32.771  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 07:59:32.771  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:32.771  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:32.771  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:32.771  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:59:32.777  5508  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:59:32.781  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 07:59:32.782  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1acad61 added. We now have 8 listener(s)
09-15 07:59:32.782  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 07:59:32.790   929  3638 D WifiService: setWifiEnabled: false pid=5508, uid=10077
,09-15 07:59:32.790   929  3638 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 07:59:32.803  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:32.804   929   939 D WifiService: setWifiEnabled: true pid=5508, uid=10077
09-15 07:59:32.804   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 07:59:32.810   509   923 D SoftapController: Softap fwReload - Ok
09-15 07:59:32.814   509   923 D CommandListener: Setting iface cfg
09-15 07:59:32.815   509   923 D CommandListener: Trying to bring down wlan0
09-15 07:59:32.816   509   923 D CommandListener: Clearing all IP addresses on wlan0
,09-15 07:59:32.821   929  3034 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 07:59:33.437   929  3034 D wifi    : set interface wlan0 flags (UP)
,09-15 07:59:33.443   929  3034 I WifiHAL : Initializing wifi
09-15 07:59:33.443   929  3034 I WifiHAL : Creating socket
,09-15 07:59:33.446   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 07:59:33.452   929  3034 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-15 07:59:33.452   929  3034 D wifi    : Did set static halHandle = 0x7f6f63c880
09-15 07:59:33.452   929  3034 D wifi    : halHandle = 0x7f6f63c880, mVM = 0x7f7a0cd140, mCls = 0x1952
09-15 07:59:33.452   929  3034 D wifi    : array field set
09-15 07:59:33.452   929  3034 I WifiNative-HAL: interface[0] = wlan0
09-15 07:59:33.454   929  5786 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547329656960
,09-15 07:59:33.454   929  5786 D wifi    : waitForHalEvents called, vm = 0x7f7a0cd140, obj = 0x1952, env = 0x7f5e307cc0
,09-15 07:59:33.516  5787  5787 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 07:59:33.537  5787  5787 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 07:59:33.547  5787  5787 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 07:59:33.548  5787  5787 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 07:59:33.555   929  3034 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-15 07:59:33.567  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:33.569   929  3034 D WifiConfigStore: Loading config and enabling all networks 
,09-15 07:59:33.573  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:33.573  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:33.573  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:33.573  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:33.573  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:33.573  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:33.573  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:33.573  5508  5508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:59:33.575  5508  5508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:59:33.579   929  3034 D WifiConfigStore: loaded 0 passpoint configs
,09-15 07:59:33.580   929  3034 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-15 07:59:33.581   929  3034 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-15 07:59:33.583   929  3034 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-15 07:59:33.583   929  3034 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-15 07:59:33.584   929  3034 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 07:59:33.584   929  3034 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-15 07:59:33.584   929  3034 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 07:59:33.587   929  3034 D WifiNative-HAL: Setting external_sim to 1
,09-15 07:59:33.587  4355  4355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 07:59:33.587   929  3034 D wifi    : setting dfs flag to true, 0x7f5fc3f4c0
09-15 07:59:33.588   929  3034 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 07:59:33.588   929  3034 D wifi    : setting scan oui 0x7f5fc3f4c0
09-15 07:59:33.588   929  3034 D WifiHAL : Sending mac address OUI
,09-15 07:59:33.602   929  3034 E native  : do suspend true
,09-15 07:59:33.608   929  3034 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-15 07:59:33.608   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-15 07:59:33.608   929   929 D RttService: SCAN_AVAILABLE : 3
09-15 07:59:33.608   929  3139 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-15 07:59:33.609   509   923 D CommandListener: Setting iface cfg
,09-15 07:59:33.613   929  3033 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '75 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 75 Failed to set address (No such device)'
09-15 07:59:33.613   929  3033 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 07:59:33.619   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=248867 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,09-15 07:59:33.620   929  3033 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 07:59:33.620   929  3033 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 07:59:33.820  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 07:59:33.820  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:33.820  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:33.820  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:33.820  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:33.820  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:33.820  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:33.820  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:59:33.825  5508  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:59:33.835  5508  5554 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-15 07:59:33.836  5508  5554 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-15 07:59:33.838  5508  5554 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@48b2e1c Bundle[{}]
09-15 07:59:33.839  5508  5554 I io.jxcore.node.LifeCycleMonitor: start: OK
09-15 07:59:33.839  5508  5554 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-15 07:59:33.839  5508  5554 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-15 07:59:33.840  5508  5554 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-15 07:59:33.840  5508  5554 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-15 07:59:33.841  5508  5554 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-15 07:59:33.846  5508  5554 I System.out: Running OutgoingSocketThread
,09-15 07:59:33.848  5508  5789 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 152)
09-15 07:59:33.849  5508  5789 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46082
09-15 07:59:33.849  5508  5789 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-15 07:59:34.849  5508  5554 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 153)
,09-15 07:59:34.850  5508  5554 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 153)
,09-15 07:59:34.856  5508  5554 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,09-15 07:59:34.857  5508  5554 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-15 07:59:34.857  5508  5554 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 159)
,09-15 07:59:34.863  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 07:59:34.863  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5f9086 added. We now have 2 listener(s)
,09-15 07:59:34.866  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 07:59:34.867  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 07:59:34.867  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:59:34.867  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 07:59:34.867  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5d8d47 added. We now have 9 listener(s)
,09-15 07:59:34.867  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 07:59:34.868  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 07:59:34.871  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 07:59:34.876  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:59:34.876  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:34.876  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:34.876  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:34.876  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:34.876  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:34.876  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:34.876  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:59:34.878  5508  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:59:34.879  5508  5554 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:59:34.879  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:59:34.879  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b25be9d added. We now have 3 listener(s)
,09-15 07:59:34.880  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:34.881  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:59:34.881  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:59:34.881  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:59:34.882  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:59:34.882  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9942f12 added. We now have 10 listener(s)
,09-15 07:59:34.882  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:59:34.882  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:34.882  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:34.882  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:34.882  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:34.882  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:34.882  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 07:59:34.882  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:59:34.882  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:59:34.882  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5f9086 removed from the list
09-15 07:59:34.883  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:34.883  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5d8d47 removed from the list
09-15 07:59:34.883  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:34.883  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:34.884  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 07:59:34.884  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:34.886  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:34.886  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:34.886  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:34.887  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5d8d47 not in the list
09-15 07:59:34.887  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:34.887  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:59:34.888  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 07:59:34.888  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:34.888  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:34.888  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9942f12 removed from the list
09-15 07:59:34.888  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:34.888  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:34.888  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:34.888  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-15 07:59:34.889  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b25be9d removed from the list
09-15 07:59:34.889  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:59:34.889  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45bb6e3 added. We now have 2 listener(s)
09-15 07:59:34.891  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:59:34.891  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:59:34.891  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:59:34.891  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:59:34.891  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35838e0 added. We now have 9 listener(s)
,09-15 07:59:34.891  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:59:34.892  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 07:59:34.895  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:34.897  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:59:34.897  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:34.897  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:34.897  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:34.897  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:34.897  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:34.897  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:34.897  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:59:34.899  5508  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 07:59:34.899  5508  5554 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 07:59:34.899  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:59:34.899  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3022a5e added. We now have 3 listener(s)
09-15 07:59:34.900  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:34.901  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:59:34.901  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:59:34.901  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:59:34.901  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:59:34.901  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@388de3f added. We now have 10 listener(s)
,09-15 07:59:34.901  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:59:34.901  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:59:34.901  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 07:59:34.901  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 07:59:34.901  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:34.902  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 07:59:34.902  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:34.904  5508  5554 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 07:59:34.904  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 07:59:34.908  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 07:59:34.909  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 07:59:34.909  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 07:59:34.912  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 07:59:34.912  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 07:59:34.912  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 07:59:34.912  5508  5554 D BluetoothAdapter: STATE_ON
,09-15 07:59:34.915  5733  5744 D BtGatt.GattService: registerClient() - UUID=70d9cace-6619-483f-96c1-a985650860c8
,09-15 07:59:34.915  5733  5749 D BtGatt.GattService: onClientRegistered() - UUID=70d9cace-6619-483f-96c1-a985650860c8, clientIf=5
,09-15 07:59:34.917  5508  5519 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 07:59:34.918  5733  5761 D BtGatt.GattService: start scan with filters
09-15 07:59:34.921  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 07:59:34.921  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 07:59:34.921  5733  5752 D BtGatt.ScanManager: handling starting scan
09-15 07:59:34.921  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 07:59:34.921  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 07:59:34.923  5733  5752 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a62069
09-15 07:59:34.923  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:59:34.923  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 07:59:34.923  5508  5508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:59:34.924  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 07:59:34.928  5508  5554 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 07:59:34.928  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-15 07:59:34.928  5733  5749 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 07:59:34.928  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 07:59:34.928  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:34.929  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:34.929  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 07:59:34.929  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 07:59:34.929  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 07:59:34.929  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 07:59:34.929  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-15 07:59:34.929  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-15 07:59:34.929  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 07:59:34.929  5733  5752 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 07:59:34.930  5508  5554 D BluetoothAdapter: STATE_ON
09-15 07:59:34.930  5733  5761 D BtGatt.GattService: stopScan() - queue size =1
09-15 07:59:34.931  5733  5743 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 07:59:34.931  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-15 07:59:34.931  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 07:59:34.932  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 07:59:34.932  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 07:59:34.932  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 07:59:34.934  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:59:34.934  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 07:59:34.934  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 07:59:34.934  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 07:59:34.934  5733  5749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 07:59:34.934  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 07:59:34.934  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:59:34.935  5733  5752 D BtGatt.ScanManager: Starting BLE batch scan
09-15 07:59:34.935  5733  5752 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 07:59:34.935  5508  5508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:59:34.935  5508  5508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:59:34.935  5508  5508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:59:34.937  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:34.937  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:34.937  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:34.937  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:34.937  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:34.937  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:59:34.937  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:59:34.937  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45bb6e3 removed from the list
09-15 07:59:34.937  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:34.937  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35838e0 removed from the list
09-15 07:59:34.937  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 07:59:34.937  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:34.938  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:34.938  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:59:34.940  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 07:59:34.940  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:34.940  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:34.940  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35838e0 not in the list
09-15 07:59:34.940  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:34.940  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:34.941  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:34.941  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:34.941  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 07:59:34.941  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@388de3f removed from the list
09-15 07:59:34.941  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:34.941  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:34.941  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:34.941  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:59:34.941  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3022a5e removed from the list
09-15 07:59:34.942  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:59:34.942  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@371f5b added. We now have 2 listener(s)
09-15 07:59:34.943  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:59:34.943  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 07:59:34.943  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:59:34.943  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:59:34.943  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6843f8 added. We now have 9 listener(s)
09-15 07:59:34.943  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:59:34.944  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 07:59:34.944  5733  5749 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 07:59:34.946  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 07:59:34.945  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 07:59:34.950  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:59:34.950  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:34.950  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:34.950  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:34.950  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:34.950  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:34.950  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:34.950  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:59:34.959  5508  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:59:34.960  5508  5554 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:59:34.960  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:59:34.960  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8732736 added. We now have 3 listener(s)
09-15 07:59:34.961  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:59:34.961  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 07:59:34.961  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 07:59:34.962  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:59:34.962  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8be5637 added. We now have 10 listener(s)
09-15 07:59:34.962  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:59:34.962  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:59:34.962  5733  5749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 07:59:34.963  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:34.963  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:59:34.963  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 07:59:34.963  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-15 07:59:34.963  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:34.963  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 07:59:34.963  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:34.965  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:34.967  5508  5554 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 07:59:34.967  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 07:59:34.969  5733  5749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-15 07:59:34.969  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:34.969  5733  5752 D BtGatt.ScanManager: stopping BLe Batch
,09-15 07:59:34.971  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 07:59:34.971  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 07:59:34.971  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 07:59:34.974  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 07:59:34.974  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 07:59:34.974  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 07:59:34.974  5508  5554 D BluetoothAdapter: STATE_ON
09-15 07:59:34.974  5733  5749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 07:59:34.974  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:34.975  5733  5752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 07:59:34.976  5733  5761 D BtGatt.GattService: registerClient() - UUID=77e6da14-4697-47da-bb7f-92afe53f5071
09-15 07:59:34.976  5733  5749 D BtGatt.GattService: onClientRegistered() - UUID=77e6da14-4697-47da-bb7f-92afe53f5071, clientIf=5
,09-15 07:59:34.976  5508  5518 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 07:59:34.977  5733  5743 D BtGatt.GattService: start scan with filters
09-15 07:59:34.979  5733  5749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 07:59:34.979  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:34.980  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 07:59:34.980  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-15 07:59:34.980  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-15 07:59:34.980  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 07:59:34.980  5733  5752 D BtGatt.ScanManager: handling starting scan
09-15 07:59:34.982  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:59:34.982  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 07:59:34.982  5508  5508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 07:59:34.983  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 07:59:34.985  5733  5749 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-15 07:59:34.985  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:34.985  5733  5752 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 07:59:34.986  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:59:34.986  5508  5554 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-15 07:59:34.986  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:34.986  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:34.986  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 07:59:34.986  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:34.986  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:34.986  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 07:59:34.986  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:59:34.986  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@371f5b removed from the list
,09-15 07:59:34.986  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:34.986  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6843f8 removed from the list
09-15 07:59:34.986  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:34.986  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:59:34.987  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:34.987  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-15 07:59:34.987  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:34.987  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:59:34.988  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:34.988  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:34.988  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:34.988  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6843f8 not in the list
,09-15 07:59:34.988  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 07:59:34.988  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 07:59:34.988  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 07:59:34.988  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 07:59:34.988  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 07:59:34.989  5508  5554 D BluetoothAdapter: STATE_ON
09-15 07:59:34.989  5733  5744 D BtGatt.GattService: stopScan() - queue size =1
,09-15 07:59:34.990  5733  5761 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 07:59:34.990  5733  5749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 07:59:34.990  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:34.991  5733  5752 D BtGatt.ScanManager: Starting BLE batch scan
09-15 07:59:34.991  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 07:59:34.991  5733  5752 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 07:59:34.991  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 07:59:34.991  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 07:59:34.991  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 07:59:34.991  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-15 07:59:34.992  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:59:34.992  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-15 07:59:34.992  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 07:59:34.992  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 07:59:34.993  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:34.994  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:34.994  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:34.994  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:34.994  5508  5508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:59:34.994  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8be5637 removed from the list
09-15 07:59:34.994  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 07:59:34.994  5508  5508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:59:34.994  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:34.994  5508  5508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:59:34.994  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:34.994  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:59:34.995  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8732736 removed from the list
,09-15 07:59:34.995  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 07:59:34.995  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f181ed3 added. We now have 2 listener(s)
09-15 07:59:34.997  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:59:34.997  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:59:34.997  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:59:34.997  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:59:34.997  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9a10 added. We now have 9 listener(s)
09-15 07:59:34.997  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:59:34.997  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 07:59:35.000  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:35.000  5733  5749 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 07:59:35.000  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:35.003  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:59:35.003  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:35.003  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:35.003  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:35.003  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:35.003  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:35.003  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:35.003  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 07:59:35.004  5733  5749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-15 07:59:35.004  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 07:59:35.007  5508  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:59:35.007  5508  5554 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:59:35.007  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:59:35.007  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6bbe70e added. We now have 3 listener(s)
09-15 07:59:35.008  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:35.008  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:59:35.008  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:59:35.008  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:59:35.008  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 07:59:35.008  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13bd52f added. We now have 10 listener(s)
09-15 07:59:35.009  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:59:35.009  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:59:35.009  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 07:59:35.009  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 07:59:35.009  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:35.009  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 07:59:35.009  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:35.009  5733  5749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 07:59:35.009  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:35.009  5733  5752 D BtGatt.ScanManager: stopping BLe Batch
,09-15 07:59:35.012  5508  5554 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 07:59:35.012  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 07:59:35.015  5733  5749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 07:59:35.015  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 07:59:35.015  5733  5752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 07:59:35.016  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 07:59:35.017  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 07:59:35.017  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 07:59:35.021  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 07:59:35.021  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 07:59:35.021  5508  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 07:59:35.022  5508  5554 D BluetoothAdapter: STATE_ON
,09-15 07:59:35.023  5733  5749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-15 07:59:35.023  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:35.023  5733  5749 D BtGatt.GattService: current time is 250272358045
09-15 07:59:35.024  5733  5749 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -78, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-15 07:59:35.024  5733  5761 D BtGatt.GattService: registerClient() - UUID=7bb38604-1010-436a-82cd-67d8da781a3f
09-15 07:59:35.025  5733  5749 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-15 07:59:35.025  5733  5749 D BtGatt.GattService: onClientRegistered() - UUID=7bb38604-1010-436a-82cd-67d8da781a3f, clientIf=5
09-15 07:59:35.026  5508  5518 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 07:59:35.026  5733  5743 D BtGatt.GattService: start scan with filters
,09-15 07:59:35.028  5733  5752 D BtGatt.ScanManager: handling starting scan
,09-15 07:59:35.028  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 07:59:35.028  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 07:59:35.028  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 07:59:35.028  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 07:59:35.030  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 07:59:35.030  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 07:59:35.030  5508  5508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 07:59:35.031  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 07:59:35.033  5733  5749 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 07:59:35.033  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:35.033  5733  5752 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 07:59:35.036  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 07:59:35.036  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 07:59:35.036  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:35.036  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:35.036  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:35.036  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 07:59:35.036  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:59:35.036  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f181ed3 removed from the list
09-15 07:59:35.037  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:35.037  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9a10 removed from the list
09-15 07:59:35.037  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:35.037  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 07:59:35.037  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-15 07:59:35.037  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-15 07:59:35.037  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:35.037  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:59:35.037  5733  5749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 07:59:35.038  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:35.038  5733  5752 D BtGatt.ScanManager: Starting BLE batch scan
09-15 07:59:35.038  5733  5752 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 07:59:35.039  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:35.039  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:35.039  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:35.039  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9a10 not in the list
09-15 07:59:35.039  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 07:59:35.039  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 07:59:35.039  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 07:59:35.039  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 07:59:35.039  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-15 07:59:35.040  5508  5554 D BluetoothAdapter: STATE_ON
09-15 07:59:35.040  5733  5769 D BtGatt.GattService: stopScan() - queue size =1
09-15 07:59:35.040  5733  5761 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 07:59:35.041  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 07:59:35.041  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 07:59:35.041  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 07:59:35.041  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 07:59:35.041  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-15 07:59:35.042  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 07:59:35.042  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 07:59:35.042  5508  5554 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 07:59:35.042  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 07:59:35.043  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:35.044  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:35.044  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:35.044  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:35.044  5508  5508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:59:35.044  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13bd52f removed from the list
09-15 07:59:35.044  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:35.044  5508  5508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 07:59:35.044  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:35.044  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:35.044  5508  5508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 07:59:35.044  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:59:35.044  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6bbe70e removed from the list
09-15 07:59:35.045  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:59:35.045  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3a954b added. We now have 2 listener(s)
09-15 07:59:35.045  5733  5749 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 07:59:35.045  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 07:59:35.046  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:59:35.046  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:59:35.046  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:59:35.046  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:59:35.046  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4709b28 added. We now have 9 listener(s)
09-15 07:59:35.047  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:59:35.047  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 07:59:35.049  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 07:59:35.050  5733  5749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 07:59:35.050  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 07:59:35.052  5508  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 07:59:35.052  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 07:59:35.052  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 07:59:35.052  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 07:59:35.052  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 07:59:35.052  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 07:59:35.052  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 07:59:35.052  5508  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 07:59:35.054  5508  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 07:59:35.055  5508  5554 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 07:59:35.055  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 07:59:35.055  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b1c9e6 added. We now have 3 listener(s)
09-15 07:59:35.055  5733  5749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 07:59:35.055  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:35.055  5733  5752 D BtGatt.ScanManager: stopping BLe Batch
,09-15 07:59:35.056  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 07:59:35.056  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 07:59:35.056  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 07:59:35.057  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 07:59:35.057  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 07:59:35.057  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1b3b27 added. We now have 10 listener(s)
09-15 07:59:35.057  5508  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 07:59:35.057  5508  5508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 07:59:35.057  5508  5554 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 07:59:35.057  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 07:59:35.057  5508  5554 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 07:59:35.057  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:35.057  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:35.058  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 07:59:35.058  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:59:35.058  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3a954b removed from the list
09-15 07:59:35.058  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:35.058  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4709b28 removed from the list
09-15 07:59:35.058  5508  5554 D io.jxcore.node.ConnectivityMonitor: stop
09-15 07:59:35.058  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 07:59:35.059  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:35.059  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:59:35.060  5733  5749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 07:59:35.060  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 07:59:35.060  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:35.060  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:35.060  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 07:59:35.060  5733  5752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 07:59:35.060  5508  5554 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4709b28 not in the list
09-15 07:59:35.060  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:35.060  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:59:35.061  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 07:59:35.061  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 07:59:35.062  5508  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 07:59:35.062  5508  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1b3b27 removed from the list
09-15 07:59:35.062  5508  5554 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 07:59:35.062  5508  5554 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 07:59:35.062  5508  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 07:59:35.062  5508  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 07:59:35.062  5508  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b1c9e6 removed from the list
,09-15 07:59:35.063  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-15 07:59:35.063  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 07:59:35.063  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-15 07:59:35.063  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 07:59:35.063  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 07:59:35.063  5508  5554 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-15 07:59:35.065  5733  5749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-15 07:59:35.065  5733  5749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 07:59:35.069  5508  5790 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: My test thread name)
,09-15 07:59:35.069  5508  5790 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: My test thread name)
09-15 07:59:35.069  5508  5790 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-15 07:59:35.070  5508  5791 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name)
,09-15 07:59:35.070  5508  5791 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: My test thread name)
09-15 07:59:35.070  5508  5791 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-15 07:59:35.072  5508  5554 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-15 07:59:35.072  5508  5554 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-15 07:59:35.072  5508  5554 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-15 07:59:35.072  5508  5554 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-15 07:59:35.072  5508  5554 D com.test.thalitest.ThaliTestRunner: Total duration: 22563 ms
09-15 07:59:35.074  5508  5554 I jxcore-log: *Native tests were executed*
09-15 07:59:35.074  5508  5554 I jxcore-log: 
09-15 07:59:35.074  5508  5554 I jxcore-log: Total number of executed tests:  80
09-15 07:59:35.074  5508  5554 I jxcore-log: 
09-15 07:59:35.074  5508  5554 I jxcore-log: Number of passed tests:  80
09-15 07:59:35.074  5508  5554 I jxcore-log: 
09-15 07:59:35.074  5508  5554 I jxcore-log: Number of failed tests:  0
09-15 07:59:35.074  5508  5554 I jxcore-log: 
09-15 07:59:35.074  5508  5554 I jxcore-log: Number of ignored tests:  0
09-15 07:59:35.074  5508  5554 I jxcore-log: 
09-15 07:59:35.074  5508  5554 I jxcore-log: Total duration:  22563
09-15 07:59:35.074  5508  5554 I jxcore-log: 
,09-15 07:59:35.075  5508  5554 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-15 07:59:35.075  5508  5554 I jxcore-log: 
,09-15 07:59:35.077  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 07:59:35.077  5508  5554 I jxcore-log: 
09-15 07:59:35.080  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 07:59:35.080  5508  5554 I jxcore-log: 
09-15 07:59:35.081  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 07:59:35.081  5508  5554 I jxcore-log: 
09-15 07:59:35.082  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 07:59:35.082  5508  5554 I jxcore-log: 
09-15 07:59:35.083  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 07:59:35.083  5508  5554 I jxcore-log: 
09-15 07:59:35.085  5508  5508 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-15 07:59:35.085  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 07:59:35.085  5508  5554 I jxcore-log: 
09-15 07:59:35.087  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 07:59:35.087  5508  5554 I jxcore-log: 
09-15 07:59:35.089  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 07:59:35.089  5508  5554 I jxcore-log: 
09-15 07:59:35.089  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 07:59:35.089  5508  5554 I jxcore-log: 
09-15 07:59:35.090  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 07:59:35.090  5508  5554 I jxcore-log: 
09-15 07:59:35.091  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 07:59:35.091  5508  5554 I jxcore-log: 
09-15 07:59:35.092  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 07:59:35.092  5508  5554 I jxcore-log: 
,09-15 07:59:35.093  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 07:59:35.093  5508  5554 I jxcore-log: 
,09-15 07:59:35.094  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 07:59:35.094  5508  5554 I jxcore-log: 
,09-15 07:59:35.095  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 07:59:35.095  5508  5554 I jxcore-log: 
09-15 07:59:35.095  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 07:59:35.095  5508  5554 I jxcore-log: 
,09-15 07:59:35.096  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 07:59:35.096  5508  5554 I jxcore-log: 
,09-15 07:59:35.097  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 07:59:35.097  5508  5554 I jxcore-log: 
,09-15 07:59:35.097  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 07:59:35.097  5508  5554 I jxcore-log: 
09-15 07:59:35.098  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 07:59:35.098  5508  5554 I jxcore-log: 
,09-15 07:59:35.099  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 07:59:35.099  5508  5554 I jxcore-log: 
,09-15 07:59:35.099  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 07:59:35.099  5508  5554 I jxcore-log: 
,09-15 07:59:35.100  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 07:59:35.100  5508  5554 I jxcore-log: 
09-15 07:59:35.101  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 07:59:35.101  5508  5554 I jxcore-log: 
,09-15 07:59:35.101  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 07:59:35.101  5508  5554 I jxcore-log: 
,09-15 07:59:35.102  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 07:59:35.102  5508  5554 I jxcore-log: 
,09-15 07:59:35.103  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 07:59:35.103  5508  5554 I jxcore-log: 
,09-15 07:59:35.103  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 07:59:35.103  5508  5554 I jxcore-log: 
09-15 07:59:35.104  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 07:59:35.104  5508  5554 I jxcore-log: 
,09-15 07:59:35.436  5508  5508 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 07:59:35.440  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 07:59:35.440  5508  5554 I jxcore-log: 
,09-15 07:59:35.495  5508  5508 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 07:59:35.498  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 07:59:35.498  5508  5554 I jxcore-log: 
,09-15 07:59:35.509  5792  5792 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-15 07:59:35.515  5792  5792 D AndroidRuntime: CheckJNI is OFF
,09-15 07:59:35.545  5508  5508 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 07:59:35.546  5792  5792 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-15 07:59:35.547  5508  5554 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 07:59:35.547  5508  5554 I jxcore-log: 
,09-15 07:59:35.581  5792  5792 I Radio-JNI: register_android_hardware_Radio DONE
,09-15 07:59:35.597  5792  5792 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-15 07:59:35.604   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-15 07:59:35.604   929   942 I ActivityManager: Killing 5508:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-15 07:59:35.678   929  3595 I WindowState: WIN DEATH: Window{25f9c79 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-15 07:59:35.678   929  3472 D GraphicsStats: Buffer count: 2
,09-15 07:59:35.679   929  3035 D WifiService: Client connection lost with reason: 4
,09-15 07:59:35.733   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-15 07:59:35.734   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-15 07:59:35.734   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-15 07:59:35.734   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-15 07:59:35.734   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 07:59:35.734   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:59:35.734   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 07:59:35.734   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-15 07:59:35.735   929   942 I ActivityManager:   Force finishing activity ActivityRecord{de7ec6a u0 com.test.thalitest/.MainActivity t2}
09-15 07:59:35.737   929   952 I art     : Starting a blocking GC Explicit
,09-15 07:59:35.742   929  3489 W ActivityManager: Spurious death for ProcessRecord{9e3e60d 0:com.test.thalitest/u0a77}, curProc for 5508: null
,09-15 07:59:35.817   929   952 I art     : Explicit concurrent mark sweep GC freed 23948(1509KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 1.437ms total 80.061ms
,09-15 07:59:35.836   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-15 07:59:35.838  5792  5792 I art     : System.exit called, status: 0
,09-15 07:59:35.838  5792  5792 I AndroidRuntime: VM exiting with result code 0.
,09-15 07:59:35.844   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-15 07:59:35.855   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-15 07:59:35.857  3459  3459 I Keyboard.Facilitator: resetDictionaries() : en_US
09-15 07:59:35.860  5733  5733 D BluetoothMapAppObserver: onReceive
09-15 07:59:35.860  5733  5733 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-15 07:59:35.862  3528  4009 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-15 07:59:35.864   929  3014 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-15 07:59:35.892  3459  5803 I Keyboard.Facilitator.DecoderInitializer: run()
,09-15 07:59:35.909  3588  3588 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-15 07:59:35.919  3459  5803 I Decoder : createOrResetDecoder
,09-15 07:59:35.918  3474  5805 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-15 07:59:35.923  3669  3669 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-15 07:59:35.924  3669  3669 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-15 07:59:35.921    28    28 W kworker/2:1: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 07:59:35.925    28    28 W kworker/2:1: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 07:59:35.938  3619  3721 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-15 07:59:35.939   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-15 07:59:35.946  3963  5809 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-15 07:59:35.952   929  3472 I ActivityManager: Start proc 5810:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-15 07:59:35.952  3963  5809 D AccountUtils: Clearing selected account for com.test.thalitest
--------- beginning of crash
09-15 07:59:35.952  3619  3721 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-15 07:59:35.952  3619  3721 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3619
09-15 07:59:35.952  3619  3721 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 07:59:35.952  3619  3721 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-15 07:59:35.952  3619  3721 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-15 07:59:35.952  3619  3721 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-15 07:59:35.952  3619  3721 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-15 07:59:35.952  3619  3721 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-15 07:59:35.952  3619  3721 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-15 07:59:35.952  3619  3721 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-15 07:59:35.952  3619  3721 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-15 07:59:35.952  3619  3721 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-15 07:59:35.952  3619  3721 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-15 07:59:35.952  3619  3721 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-15 07:59:35.956   929  3595 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-15 07:59:35.955    28    28 W kworker/2:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 07:59:35.960  3619  3721 I Process : Sending signal. PID: 3619 SIG: 9
,09-15 07:59:35.968   929  5817 E DropBoxManagerService: Can't write: system_app_crash
09-15 07:59:35.968   929  5817 E DropBoxManagerService: java.io.IOException: Can't rename /data/system/dropbox/drop116.tmp to /data/system/dropbox/system_app_crash@1473940775967.txt
09-15 07:59:35.968   929  5817 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService$EntryFile.<init>(DropBoxManagerService.java:509)
09-15 07:59:35.968   929  5817 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.createEntry(DropBoxManagerService.java:690)
09-15 07:59:35.968   929  5817 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:245)
09-15 07:59:35.968   929  5817 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 07:59:35.968   929  5817 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
,09-15 07:59:35.993  3669  3669 I ConfigService: onCreate
,09-15 07:59:35.996  3669  5825 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-15 07:59:35.996  3669  5825 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-15 07:59:35.996  3474  3494 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj77AA4197C) - 
,09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-15 07:59:35.997  3669  5825 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-15 07:59:35.999  3669  5825 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-15 07:59:36.015  3459  5803 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-15 07:59:36.019  3963  5809 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-15 07:59:36.029   382   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-15 07:59:36.029   382   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
