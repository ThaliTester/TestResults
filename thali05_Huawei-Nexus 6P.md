#### Test 86955080a9104ac_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-28 09:58:30.412   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-28 09:58:30.412   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 09:58:30.943  5560  5560 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-28 09:58:30.949  5560  5560 D AndroidRuntime: CheckJNI is OFF
09-28 09:58:30.976  5560  5560 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-28 09:58:31.008  5560  5560 I Radio-JNI: register_android_hardware_Radio DONE
09-28 09:58:31.023  5560  5560 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-28 09:58:31.028   929  3570 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-28 09:58:31.082   929  3570 I ActivityManager: Start proc 5569:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-28 09:58:31.096  5560  5560 D AndroidRuntime: Shutting down VM
,09-28 09:58:31.430   929   940 I WindowManager: Screenshot max retries 4 of Token{926fa1d ActivityRecord{565f2f4 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{688ac8c u0 Starting com.test.thalitest} drawState=4
,09-28 09:58:31.509  5569  5569 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-28 09:58:31.545  5569  5569 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-28 09:58:31.570  5569  5569 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 9986-5)
,09-28 09:58:31.570  5569  5569 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-28 09:58:31.590  5569  5569 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8412255}
09-28 09:58:31.590  5569  5569 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-28 09:58:31.591  5569  5569 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-28 09:58:31.595  5569  5569 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-28 09:58:31.597  5569  5569 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-28 09:58:31.632  5569  5569 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-28 09:58:31.647  5569  5569 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-28 09:58:31.647  5569  5569 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-28 09:58:31.647  5569  5569 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-28 09:58:31.647  5569  5569 I Adreno  : Build Date                       : 12/06/15
09-28 09:58:31.647  5569  5569 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-28 09:58:31.647  5569  5569 I Adreno  : Local Branch                     : mybranch17112971
09-28 09:58:31.647  5569  5569 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-28 09:58:31.647  5569  5569 I Adreno  : Remote Branch                    : NONE
09-28 09:58:31.647  5569  5569 I Adreno  : Reconstruct Branch               : NOTHING
,09-28 09:58:31.704   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@80d6653:true
,09-28 09:58:31.737   405   405 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[32813]" dev="sockfs" ino=32813 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 09:58:31.737   405   405 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32813]" dev="sockfs" ino=32813 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 09:58:31.751  5569  5569 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-28 09:58:31.761  5569  5569 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-28 09:58:31.790   405   405 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32441]" dev="sockfs" ino=32441 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 09:58:31.790   405   405 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32441]" dev="sockfs" ino=32441 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-28 09:58:31.792  5569  5606 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-28 09:58:31.793  3123  3123 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32818]" dev="sockfs" ino=32818 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-28 09:58:31.793  3123  3123 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32818]" dev="sockfs" ino=32818 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-28 09:58:31.799  5569  5593 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-28 09:58:31.824  5569  5606 I OpenGLRenderer: Initialized EGL, version 1.4
,09-28 09:58:31.907   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +474ms (total +854ms)
,09-28 09:58:31.934  5569  5569 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5569
,09-28 09:58:32.035  5569  5569 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-28 09:58:32.172  5569  5609 D jxcore_app_log: JniHelper::setJavaVM(0xf537c000), pthread_self() = -581957328
,09-28 09:58:32.177  5569  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-28 09:58:32.177  5569  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-28 09:58:32.177  5569  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-28 09:58:32.177  5569  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-28 09:58:32.177  5569  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-28 09:58:32.177  5569  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8154493 added. We now have 1 listener(s)
,09-28 09:58:32.180  5569  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-28 09:58:32.181  5569  5609 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 09:58:32.182  5569  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 09:58:32.183  5569  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-28 09:58:32.186  5569  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83097ce added. We now have 1 listener(s)
09-28 09:58:32.186  5569  5609 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:58:32.191   929  2945 D WifiService: New client listening to asynchronous messages
,09-28 09:58:32.191  5569  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 09:58:32.191  5569  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-28 09:58:32.191  5569  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-28 09:58:32.191  5569  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-28 09:58:32.192  5569  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-28 09:58:32.194  5569  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 09:58:32.194  5569  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-28 09:58:32.199  5569  5609 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-28 09:58:32.200  5569  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:58:32.200  5569  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:58:32.200  5569  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:58:32.200  5569  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:58:32.200  5569  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:58:32.200  5569  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:58:32.200  5569  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:58:32.200  5569  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:58:32.200  5569  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-28 09:58:32.200  5569  5609 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:58:32.200  5569  5609 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-28 09:58:32.203  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:58:32.211  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:58:32.230  5569  5569 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-28 09:58:32.309   929  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 09:58:32.541  5569  5616 W jxcore-log: Initializing JXcore engine
09-28 09:58:32.542  5569  5616 W jxcore-log: JXcore engine is ready
,09-28 09:58:32.563  5616  5616 W Thread-62: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11805 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-28 09:58:32.563  5616  5616 W Thread-62: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13430]" dev="sockfs" ino=13430 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-28 09:58:32.563  5616  5616 W Thread-62: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-28 09:58:32.563  5616  5616 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32413]" dev="sockfs" ino=32413 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-28 09:58:32.573  5569  5616 W jxcore-log: Starting JXcore engine
,09-28 09:58:32.623  5569  5616 W jxcore-log: Platform android
09-28 09:58:32.623  5569  5616 W jxcore-log: 
,09-28 09:58:32.623  5569  5616 W jxcore-log: Process ARCH arm
09-28 09:58:32.623  5569  5616 W jxcore-log: 
,09-28 09:58:32.724  5569  5616 I jxcore-log: JXcore Cordova bridge is ready!
09-28 09:58:32.724  5569  5616 I jxcore-log: 
,09-28 09:58:32.724  5569  5616 W jxcore-log: JXcore engine is started
,09-28 09:58:32.735  5569  5609 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-28 09:58:32.743  5569  5569 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-28 09:58:40.413   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:58:41.415   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:58:42.290  5569  5616 I jxcore-log: 2016-09-28 13:58:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-28 09:58:42.290  5569  5616 I jxcore-log: 
,09-28 09:58:42.291  5569  5616 I jxcore-log: 2016-09-28 13:58:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-28 09:58:42.291  5569  5616 I jxcore-log: 
,09-28 09:58:42.295  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:58:42.295  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:58:42.295  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:58:42.295  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:58:42.295  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:58:42.295  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:58:42.295  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:58:42.295  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:58:42.297  5569  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:58:42.298  5569  5616 I jxcore-log: 2016-09-28 13:58:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-28 09:58:42.298  5569  5616 I jxcore-log: 
,09-28 09:58:42.300  5569  5616 I jxcore-log: 2016-09-28 13:58:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-28 09:58:42.300  5569  5616 I jxcore-log: 
,09-28 09:58:42.416   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:58:42.547  5569  5616 I jxcore-log: 2016-09-28 13:58:42 - DEBUG UnitTest_app: 'Running unit tests'
09-28 09:58:42.547  5569  5616 I jxcore-log: 
,09-28 09:58:42.548  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 09:58:42.548  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de4190d added. We now have 2 listener(s)
09-28 09:58:42.549  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 09:58:42.549  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 09:58:42.549  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 09:58:42.549  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:58:42.549  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ced0c2 added. We now have 2 listener(s)
,09-28 09:58:42.549  5569  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 09:58:42.550  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 09:58:42.552  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 09:58:42.555  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:58:42.555  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:58:42.555  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:58:42.555  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:58:42.555  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:58:42.555  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:58:42.555  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:58:42.555  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:58:42.556  5569  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:58:42.556  5569  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:58:42.557  5569  5616 D executeNativeTests: Running unit tests
,09-28 09:58:42.562  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:58:42.570  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:58:42.596  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 09:58:42.596  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 added. We now have 3 listener(s)
09-28 09:58:42.597  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 09:58:42.597  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 09:58:42.597  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-28 09:58:42.597  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:58:42.597  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 added. We now have 3 listener(s)
09-28 09:58:42.597  5569  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 09:58:42.597  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 09:58:42.599  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:58:42.601  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:58:42.601  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:58:42.601  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:58:42.601  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:58:42.601  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:58:42.601  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:58:42.601  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:58:42.601  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:58:42.602  5569  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:58:42.602  5569  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 09:58:42.603  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-28 09:58:42.603  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 09:58:42.603  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-28 09:58:42.603  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 09:58:42.604  5569  5616 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-28 09:58:42.604  5569  5616 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-28 09:58:42.604  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-28 09:58:42.604  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 09:58:42.604  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 09:58:42.604  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 09:58:42.604  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:58:42.605  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 09:58:42.606  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:58:42.606  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 09:58:42.606  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:58:42.606  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 09:58:42.606  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 09:58:42.606  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 removed from the list
09-28 09:58:42.606  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:58:42.606  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 removed from the list
,09-28 09:58:42.607  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:58:42.613  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:58:42.613  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:58:42.613  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:58:42.614  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:58:42.614  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:58:42.614  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:58:42.615  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:58:42.615  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:58:42.615  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:58:42.615  5569  5616 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-28 09:58:42.616  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:58:42.616  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:58:42.616  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:58:42.616  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 09:58:42.616  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:58:42.616  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:58:42.616  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:58:42.616  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:58:42.616  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:58:42.616  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 09:58:42.616  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:58:42.616  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:58:42.616  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:58:42.616  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:58:42.617  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:58:42.617  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:58:42.617  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:58:42.617  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-28 09:58:42.619  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-28 09:58:42.620  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:58:42.620  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:58:42.620  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:58:42.620  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:58:42.620  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:58:42.620  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:58:42.620  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:58:42.620  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:58:42.620  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
,09-28 09:58:42.620  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:58:42.620  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:58:42.620  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:58:42.620  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:58:42.620  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:58:42.621  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:58:42.621  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:58:42.621  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:58:42.621  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:58:42.621  5569  5616 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-28 09:58:42.622  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:58:42.624  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:58:42.624  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:58:42.624  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:58:42.624  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:58:42.624  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:58:42.624  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:58:42.624  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:58:42.624  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:58:42.625  5569  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:58:42.625  5569  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:58:42.625  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 09:58:42.625  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 09:58:42.625  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 09:58:42.625  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:58:42.625  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:58:42.627  5569  5616 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:58:42.627  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 09:58:42.630  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 09:58:42.630  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:58:42.631  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:58:42.631  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 09:58:42.633  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:58:42.633  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-28 09:58:42.634  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-28 09:58:42.635  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 09:58:42.635  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 09:58:42.635  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 09:58:42.635  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:58:42.637  4554  4798 D BtGatt.GattService: registerClient() - UUID=2f115147-95a2-443b-b5a1-00a69c12a3e0
09-28 09:58:42.638  4554  4640 D BtGatt.GattService: onClientRegistered() - UUID=2f115147-95a2-443b-b5a1-00a69c12a3e0, clientIf=5
09-28 09:58:42.639  5569  5579 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 09:58:42.641  4554  4572 D BtGatt.GattService: start scan with filters
09-28 09:58:42.647  4554  4643 D BtGatt.ScanManager: handling starting scan
09-28 09:58:42.647  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 09:58:42.648  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 09:58:42.648  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 09:58:42.648  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-28 09:58:42.649  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 09:58:42.649  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 09:58:42.649  4554  4643 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
09-28 09:58:42.649  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 09:58:42.649  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 09:58:42.652  5569  5616 I io.jxcore.node.ConnectionHelper: start: OK
09-28 09:58:42.660  4554  4640 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 09:58:42.660  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:58:42.660  4554  4643 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-28 09:58:42.667  4554  4640 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 09:58:42.667  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:58:42.668  4554  4643 D BtGatt.ScanManager: Starting BLE batch scan
09-28 09:58:42.668  4554  4643 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 09:58:42.680  4554  4640 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 09:58:42.680  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:58:42.687  4554  4640 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 09:58:42.687  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:58:43.154  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-28 09:58:43.154  5569  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 09:58:43.155  5569  5569 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 09:58:43.417   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:58:44.418   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:58:45.419   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 09:58:47.656  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:58:47.656  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 09:58:47.656  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 09:58:47.656  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:58:47.656  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 09:58:47.657  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 09:58:47.657  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 09:58:47.657  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 09:58:47.657  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-28 09:58:47.658  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 09:58:47.658  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 09:58:47.659  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:58:47.660  4554  4798 D BtGatt.GattService: stopScan() - queue size =1
09-28 09:58:47.661  4554  4572 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 09:58:47.662  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:58:47.662  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 09:58:47.662  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-28 09:58:47.662  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 09:58:47.662  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 09:58:47.663  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 09:58:47.664  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:58:47.664  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 09:58:47.664  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:58:47.665  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 09:58:47.667  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:58:47.667  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:58:47.667  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 09:58:47.667  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:58:47.668  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:58:47.668  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:58:47.668  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:58:47.668  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:58:47.668  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:58:47.668  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:58:47.668  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:58:47.670  4554  4554 D BtGatt.ScanManager: awakened up at time 236106
,09-28 09:58:47.676  4554  4640 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 09:58:47.676  5569  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:58:47.676  5569  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 09:58:47.676  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:58:47.677  4554  4643 D BtGatt.ScanManager: stopping BLe Batch
09-28 09:58:47.684  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 09:58:47.685  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:58:47.685  4554  4640 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 09:58:47.685  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 09:58:47.685  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:58:47.685  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:58:47.686  4554  4643 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 09:58:47.686  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:58:47.689  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:58:47.689  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:58:47.690  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 09:58:47.695  5569  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:58:47.695  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:58:47.696  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:58:47.698  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 09:58:47.706  4554  4640 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-28 09:58:47.706  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:58:47.707  4554  4640 D BtGatt.GattService: current time is 236142887194
09-28 09:58:47.707  4554  4640 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -77, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -78, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -80, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -79, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -71, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -73, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-28 09:58:47.709  4554  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-28 09:58:47.709  4554  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-28 09:58:47.710  4554  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-28 09:58:47.710  4554  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-28 09:58:47.710  4554  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 09:58:47.710  4554  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-28 09:58:48.200  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 09:58:50.420   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:58:51.422   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:58:52.423   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:58:52.670  5569  5616 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-28 09:58:52.677  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 09:58:52.688  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:58:52.688  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:58:52.688  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:58:52.688  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:58:52.688  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:58:52.688  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:58:52.688  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:58:52.688  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:58:52.693  5569  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:58:52.693  5569  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:58:52.693  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 09:58:52.694  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 09:58:52.694  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 09:58:52.694  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 09:58:52.694  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 09:58:52.699  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:58:52.702  5569  5616 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 09:58:52.706  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:58:52.709  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 09:58:52.709  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 09:58:52.709  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 09:58:52.711  5569  5616 D BluetoothAdapter: STATE_ON
,09-28 09:58:52.716  4554  4798 D BtGatt.GattService: registerClient() - UUID=815ac5fc-7fdf-4f19-85cd-57b7ad1da160
,09-28 09:58:52.717  4554  4640 D BtGatt.GattService: onClientRegistered() - UUID=815ac5fc-7fdf-4f19-85cd-57b7ad1da160, clientIf=5
,09-28 09:58:52.718  5569  5580 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 09:58:52.719  4554  4572 D BtGatt.GattService: start scan with filters
09-28 09:58:52.724  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 09:58:52.724  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 09:58:52.724  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 09:58:52.724  4554  4643 D BtGatt.ScanManager: handling starting scan
09-28 09:58:52.724  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 09:58:52.728  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 09:58:52.728  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 09:58:52.728  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 09:58:52.731  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 09:58:52.734  4554  4640 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 09:58:52.734  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:58:52.735  5569  5616 I io.jxcore.node.ConnectionHelper: start: OK
09-28 09:58:52.735  4554  4643 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 09:58:52.739  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:58:52.739  5569  5616 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-28 09:58:52.739  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 09:58:52.739  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 09:58:52.739  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:58:52.739  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 09:58:52.739  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 09:58:52.739  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 09:58:52.739  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-28 09:58:52.740  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 09:58:52.740  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 09:58:52.740  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 09:58:52.741  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:58:52.742  4554  4789 D BtGatt.GattService: stopScan() - queue size =1
,09-28 09:58:52.742  4554  4798 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 09:58:52.743  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:58:52.743  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 09:58:52.743  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 09:58:52.743  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-28 09:58:52.743  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 09:58:52.744  4554  4640 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 09:58:52.744  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:58:52.744  4554  4643 D BtGatt.ScanManager: Starting BLE batch scan
09-28 09:58:52.745  4554  4643 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-28 09:58:52.745  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 09:58:52.745  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:58:52.745  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 09:58:52.745  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:58:52.745  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:58:52.747  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:58:52.747  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:58:52.747  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:58:52.748  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:58:52.748  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:58:52.748  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:58:52.748  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
,09-28 09:58:52.748  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:58:52.748  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:58:52.748  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:58:52.748  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:58:52.751  5569  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:58:52.751  5569  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 09:58:52.756  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 09:58:52.756  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:58:52.757  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 09:58:52.757  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:58:52.758  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:58:52.759  4554  4640 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 09:58:52.759  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:58:52.761  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:58:52.761  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:58:52.761  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:58:52.764  5569  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:58:52.764  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:58:52.765  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:58:52.765  4554  4640 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 09:58:52.765  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:58:52.768  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 09:58:52.768  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:58:52.768  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:58:52.769  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:58:52.769  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:58:52.769  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:58:52.770  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:58:52.770  5569  5616 D BluetoothLeScanner: could not find callback wrapper
,09-28 09:58:52.770  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:58:52.770  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:58:52.770  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:58:52.771  5569  5616 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-28 09:58:52.774  4554  4640 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 09:58:52.774  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:58:52.774  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:58:52.775  4554  4643 D BtGatt.ScanManager: stopping BLe Batch
09-28 09:58:52.778  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:58:52.778  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:58:52.778  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:58:52.778  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:58:52.778  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:58:52.778  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:58:52.778  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:58:52.778  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:58:52.780  4554  4640 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 09:58:52.780  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:58:52.780  5569  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:58:52.780  4554  4643 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 09:58:52.780  5569  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:58:52.780  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 09:58:52.780  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 09:58:52.780  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 09:58:52.780  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:58:52.780  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 09:58:52.783  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:58:52.786  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:58:52.786  4554  4640 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 09:58:52.786  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:58:52.788  5569  5616 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 09:58:52.792  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 09:58:52.792  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 09:58:52.792  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 09:58:52.792  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:58:52.794  4554  4575 D BtGatt.GattService: registerClient() - UUID=db83fcb8-1eb1-4abd-8041-7b65965e1b64
,09-28 09:58:52.795  4554  4640 D BtGatt.GattService: onClientRegistered() - UUID=db83fcb8-1eb1-4abd-8041-7b65965e1b64, clientIf=5
09-28 09:58:52.795  5569  5579 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 09:58:52.795  4554  4572 D BtGatt.GattService: start scan with filters
,09-28 09:58:52.798  4554  4643 D BtGatt.ScanManager: handling starting scan
09-28 09:58:52.799  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 09:58:52.799  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 09:58:52.799  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 09:58:52.799  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 09:58:52.802  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 09:58:52.802  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 09:58:52.802  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 09:58:52.803  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 09:58:52.804  4554  4640 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 09:58:52.804  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:58:52.804  4554  4643 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 09:58:52.805  5569  5616 I io.jxcore.node.ConnectionHelper: start: OK
,09-28 09:58:52.809  4554  4640 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-28 09:58:52.809  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:58:52.809  4554  4643 D BtGatt.ScanManager: Starting BLE batch scan
09-28 09:58:52.810  4554  4643 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 09:58:52.819  4554  4640 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 09:58:52.819  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:58:52.824  4554  4640 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 09:58:52.824  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:58:53.303  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-28 09:58:53.304  5569  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-28 09:58:53.304  5569  5569 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 09:58:53.424   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:58:54.425   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:58:55.426   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 09:58:57.806  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:58:57.806  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 09:58:57.806  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-28 09:58:57.807  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:58:57.807  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 09:58:57.807  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 09:58:57.807  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-28 09:58:57.807  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 09:58:57.807  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 09:58:57.808  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 09:58:57.808  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 09:58:57.810  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:58:57.811  4554  4572 D BtGatt.GattService: stopScan() - queue size =1
,09-28 09:58:57.813  4554  4798 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 09:58:57.814  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:58:57.814  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 09:58:57.815  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 09:58:57.815  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 09:58:57.815  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 09:58:57.820  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 09:58:57.820  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:58:57.820  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 09:58:57.820  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:58:57.823  4554  4554 D BtGatt.ScanManager: awakened up at time 246258
09-28 09:58:57.823  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 09:58:57.825  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:58:57.825  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:58:57.826  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 09:58:57.828  4554  4640 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-28 09:58:57.828  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:58:57.828  4554  4643 D BtGatt.ScanManager: stopping BLe Batch
09-28 09:58:57.830  5569  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:58:57.831  5569  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 09:58:57.836  4554  4640 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 09:58:57.836  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:58:57.837  4554  4643 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 09:58:57.837  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 09:58:57.838  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:58:57.839  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 09:58:57.839  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:58:57.840  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 09:58:57.843  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:58:57.843  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:58:57.843  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 09:58:57.848  5569  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:58:57.848  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:58:57.849  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:58:57.851  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 09:58:57.860  4554  4640 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-28 09:58:57.860  4554  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:58:57.860  4554  4640 D BtGatt.GattService: current time is 246296272112
09-28 09:58:57.860  4554  4640 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -74, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -75, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -77, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -78, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -77, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -74, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-28 09:58:57.861  4554  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 09:58:57.861  4554  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-28 09:58:57.861  4554  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-28 09:58:57.861  4554  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-28 09:58:57.862  4554  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-28 09:58:57.862  4554  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-28 09:58:58.352  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 09:58:58.353  5569  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:58:58.353  5569  5569 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 09:59:02.827  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:59:02.827  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:59:02.827  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:02.828  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 09:59:02.828  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.828  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:59:02.828  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:02.828  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:59:02.828  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.829  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:02.829  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.830  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.830  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:59:02.835  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 09:59:02.835  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:02.835  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:59:02.837  5569  5616 D BluetoothAdapter: STATE_ON
,09-28 09:59:02.838  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 09:59:02.838  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 09:59:02.838  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.838  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
,09-28 09:59:02.840  5569  5616 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-28 09:59:02.842  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:59:02.842  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:59:02.842  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:02.842  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:02.842  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.843  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.843  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
,09-28 09:59:02.843  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.843  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.843  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:02.843  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.844  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.844  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.844  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:59:02.846  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:59:02.846  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:02.846  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:59:02.847  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:59:02.848  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 09:59:02.848  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 09:59:02.848  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.848  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.849  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-28 09:59:02.850  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:59:02.850  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 09:59:02.850  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:02.850  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 09:59:02.850  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.850  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.851  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:02.851  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.851  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
,09-28 09:59:02.851  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:02.851  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.851  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.851  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.851  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:59:02.853  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:59:02.853  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:02.853  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:59:02.855  5569  5616 D BluetoothAdapter: STATE_ON
,09-28 09:59:02.855  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 09:59:02.855  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:59:02.855  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:59:02.855  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.856  5569  5616 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-28 09:59:02.856  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:59:02.856  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:59:02.857  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:02.857  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:02.857  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.857  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.857  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:02.857  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.857  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.857  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:02.858  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.858  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.858  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.858  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.860  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:59:02.860  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:02.860  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:59:02.861  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:59:02.861  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 09:59:02.861  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:59:02.861  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:59:02.862  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.863  5569  5616 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-28 09:59:02.863  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:59:02.863  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 09:59:02.863  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:02.863  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:02.863  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.864  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.864  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:02.864  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:59:02.864  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.864  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:02.864  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.864  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.864  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:59:02.864  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.866  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 09:59:02.866  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:02.866  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:59:02.867  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:59:02.867  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 09:59:02.867  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 09:59:02.867  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.868  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.868  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 09:59:02.869  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 09:59:02.869  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 09:59:02.869  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 09:59:02.869  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 09:59:02.869  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 09:59:02.869  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 09:59:02.869  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-28 09:59:02.869  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 09:59:02.870  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:59:02.870  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:59:02.870  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:02.870  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:02.870  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.870  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.870  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:02.870  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.870  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.870  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:02.871  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.871  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.871  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.872  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.873  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:59:02.874  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:02.874  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:59:02.875  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:59:02.875  5569  5616 D BluetoothLeScanner: could not find callback wrapper
,09-28 09:59:02.875  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:59:02.875  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.875  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.876  5569  5616 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 09:59:02.876  5569  5616 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-28 09:59:02.876  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-28 09:59:02.880  5569  5616 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 09:59:02.880  5569  5616 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-28 09:59:02.880  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-28 09:59:02.881  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-28 09:59:02.882  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-28 09:59:02.882  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-28 09:59:02.882  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-28 09:59:02.882  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-28 09:59:02.882  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-28 09:59:02.882  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-28 09:59:02.882  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-28 09:59:02.882  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-28 09:59:02.882  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-28 09:59:02.882  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-28 09:59:02.882  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-28 09:59:02.882  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-28 09:59:02.882  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-28 09:59:02.882  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-28 09:59:02.883  5569  5616 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-28 09:59:02.883  5569  5616 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 09:59:02.883  5569  5616 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-28 09:59:02.883  5569  5616 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 09:59:02.883  5569  5616 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 09:59:02.883  5569  5616 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,09-28 09:59:02.883  5569  5616 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 09:59:02.884  5569  5616 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 09:59:02.884  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-28 09:59:02.889  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-28 09:59:02.889  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-28 09:59:02.889  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-28 09:59:02.890  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-28 09:59:02.890  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-28 09:59:02.890  5569  5616 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-28 09:59:02.890  5569  5616 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-28 09:59:02.891  5569  5616 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-28 09:59:02.891  5569  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
,09-28 09:59:02.892  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:59:02.892  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:59:02.892  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:02.892  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:02.892  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.892  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.892  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-28 09:59:02.894  5569  5617 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 09:59:02.895  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:02.895  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:59:02.897  4575  4575 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31289]" dev="sockfs" ino=31289 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-28 09:59:02.897  4575  4575 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31289]" dev="sockfs" ino=31289 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-28 09:59:02.896  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
,09-28 09:59:02.896  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:02.896  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.896  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.896  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.896  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.896  5569  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
09-28 09:59:02.896  5569  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 126)
09-28 09:59:02.896  5569  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 126)
09-28 09:59:02.897  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 09:59:02.898  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:02.898  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:59:02.898  5569  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
09-28 09:59:02.901  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:59:02.901  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 09:59:02.901  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:59:02.901  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.901  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
,09-28 09:59:02.902  5569  5616 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-28 09:59:02.902  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:59:02.903  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:59:02.903  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:02.903  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:02.903  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.903  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.903  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:02.903  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.903  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
,09-28 09:59:02.903  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:02.903  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.903  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.903  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.903  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.905  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:59:02.905  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:02.905  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:59:02.906  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:59:02.906  5569  5616 D BluetoothLeScanner: could not find callback wrapper
,09-28 09:59:02.906  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:59:02.906  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.906  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.907  5569  5616 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-28 09:59:02.907  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:59:02.908  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:59:02.908  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:02.908  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:02.908  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.908  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:59:02.908  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:02.908  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.908  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.908  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:02.908  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.908  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.908  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.908  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.910  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:59:02.910  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:02.910  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:59:02.911  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:59:02.911  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 09:59:02.911  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 09:59:02.911  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.911  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.912  5569  5616 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-28 09:59:02.912  5569  5616 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-28 09:59:02.912  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 09:59:02.912  5569  5616 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-28 09:59:02.912  5569  5616 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-28 09:59:02.913  5569  5616 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-28 09:59:02.913  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 09:59:02.913  5569  5616 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,09-28 09:59:02.913  5569  5616 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-28 09:59:02.913  5569  5616 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-28 09:59:02.913  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 09:59:02.913  5569  5616 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-28 09:59:02.913  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:59:02.913  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:59:02.913  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:02.913  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:02.913  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.913  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:59:02.913  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:02.913  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.913  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.913  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:02.913  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.913  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.914  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.914  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.915  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 09:59:02.915  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:02.915  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:59:02.916  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:59:02.916  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 09:59:02.916  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:59:02.916  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:02.916  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.917  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:02.917  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.917  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:02.917  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:02.917  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:59:02.917  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:02.917  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:02.917  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:02.917  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:59:05.427   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:06.428   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:07.429   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:07.918  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:59:07.918  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:07.918  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:07.919  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.919  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:59:07.919  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
,09-28 09:59:07.919  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:59:07.919  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 09:59:07.920  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:07.920  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:07.920  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.920  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.920  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
,09-28 09:59:07.921  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:07.921  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:07.921  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:07.921  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:59:07.921  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.921  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.921  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.925  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 09:59:07.926  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:07.926  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:59:07.929  5569  5616 D BluetoothAdapter: STATE_ON
,09-28 09:59:07.931  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 09:59:07.931  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:59:07.931  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:07.931  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
,09-28 09:59:07.934  5569  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-28 09:59:07.935  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:59:07.936  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-28 09:59:07.938  5569  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-28 09:59:07.939  5569  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-28 09:59:07.939  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-28 09:59:07.939  5569  5569 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-28 09:59:07.939  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 09:59:07.940  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:07.940  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-28 09:59:07.940  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-28 09:59:07.940  5569  5619 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 09:59:07.940  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-28 09:59:07.941  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.941  5569  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-28 09:59:07.941  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:07.941  5569  5569 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-28 09:59:07.941  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:07.941  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 09:59:07.941  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 09:59:07.941  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 09:59:07.941  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 09:59:07.942  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:59:07.943  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 09:59:07.943  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:59:07.943  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:07.943  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 09:59:07.940  4572  4572 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31291]" dev="sockfs" ino=31291 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 09:59:07.940  4572  4572 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31291]" dev="sockfs" ino=31291 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 09:59:07.943  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.943  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.944  5569  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-28 09:59:07.944  5569  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 09:59:07.944  5569  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-28 09:59:07.945  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 09:59:07.947  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:59:07.947  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:07.947  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:59:07.947  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:59:07.947  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:59:07.947  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:59:07.948  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:07.948  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:07.948  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.948  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:59:07.948  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:07.948  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:07.948  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:07.948  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:07.949  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.949  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:59:07.952  5569  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:59:07.952  5569  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 09:59:07.959  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 09:59:07.960  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:59:07.961  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 09:59:07.961  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:59:07.962  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.965  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.966  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.967  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:59:07.967  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:07.967  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:59:07.968  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:59:07.968  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 09:59:07.968  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:59:07.968  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:07.968  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:59:07.968  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:07.968  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:59:07.968  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:59:07.970  5569  5616 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-28 09:59:07.970  5569  5616 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-28 09:59:07.970  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 09:59:07.970  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 09:59:07.971  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 09:59:07.971  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:59:07.971  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:59:07.971  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:07.971  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:07.971  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.971  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:59:07.971  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:07.971  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:07.972  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:07.972  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:07.972  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.972  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:59:07.973  5569  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:59:07.973  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:59:07.974  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.978  5569  5569 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-28 09:59:07.978  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.978  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.978  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 09:59:07.980  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:59:07.980  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:07.980  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:59:07.981  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:59:07.981  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 09:59:07.981  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:59:07.982  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:07.982  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:07.986  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:59:07.986  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:59:07.986  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:07.986  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:07.987  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.987  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.987  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:07.987  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:07.987  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:07.987  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:07.987  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.987  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.987  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.987  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.988  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:59:07.988  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:07.989  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:59:07.989  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:59:07.989  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 09:59:07.989  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:59:07.989  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:07.989  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:07.991  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:59:07.991  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:59:07.991  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:59:07.991  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:59:07.991  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.991  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.991  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3527740 not in the list
09-28 09:59:07.991  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:07.991  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:07.991  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:07.991  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.991  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.992  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:07.992  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:07.993  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:59:07.993  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:59:07.993  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:59:07.994  5569  5616 D BluetoothAdapter: STATE_ON
09-28 09:59:07.994  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 09:59:07.994  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:59:07.994  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:07.994  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f27679 not in the list
09-28 09:59:07.996  5569  5616 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-28 09:59:07.996  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 09:59:07.996  5569  5616 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-28 09:59:07.996  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 09:59:07.996  5569  5616 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-28 09:59:07.996  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 09:59:07.999  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-28 09:59:07.999  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-28 09:59:08.000  5569  5616 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-28 09:59:08.000  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-28 09:59:08.000  5569  5616 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-28 09:59:08.000  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-28 09:59:08.000  5569  5616 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-28 09:59:08.001  5569  5616 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-28 09:59:08.001  5569  5616 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-28 09:59:08.001  5569  5616 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-28 09:59:08.002  5569  5616 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-28 09:59:08.002  5569  5616 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-28 09:59:08.002  5569  5616 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-28 09:59:08.003  5569  5616 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-28 09:59:08.005  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:59:08.005  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@88e6907 added. We now have 3 listener(s)
09-28 09:59:08.005  5569  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 09:59:08.007  5569  5616 D BluetoothAdapter: enable(): BT is already enabled..!
09-28 09:59:08.008   929   939 D WifiService: setWifiEnabled: true pid=5569, uid=10077
09-28 09:59:08.008   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 09:59:08.025  4554  4742 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-28 09:59:08.025  4554  4783 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-28 09:59:08.430   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:08.479  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 09:59:09.431   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:10.432   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 09:59:12.313   929  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 09:59:13.014  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 09:59:13.014  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b0d0a34 added. We now have 4 listener(s)
,09-28 09:59:13.014  5569  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:59:13.027  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:59:13.028  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b0d0a34 removed from the list
09-28 09:59:13.028  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:13.028  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:13.028  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:59:13.030  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:59:13.030  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5e1605d added. We now have 4 listener(s)
09-28 09:59:13.030  5569  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:59:13.035  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:59:13.035  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5e1605d removed from the list
09-28 09:59:13.035  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:13.035  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:13.035  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:13.036  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:59:13.036  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1408dd2 added. We now have 4 listener(s)
09-28 09:59:13.037  5569  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:59:13.040   929   940 D WifiService: setWifiEnabled: false pid=5569, uid=10077
09-28 09:59:13.040   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 09:59:13.043   929  2944 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-28 09:59:13.044   929  2944 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-28 09:59:13.044   929  2944 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 09:59:13.044   929  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 09:59:13.048  4554  4636 D BluetoothAdapterState: Current state: ON, message: 23
09-28 09:59:13.048  4554  4636 D BluetoothAdapterProperties: Setting state to 13
09-28 09:59:13.048  4554  4636 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-28 09:59:13.051  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:59:13.051  4554  4636 D BluetoothAdapterProperties: onBluetoothDisable()
09-28 09:59:13.053  4554  4636 I BluetoothAdapterState: Entering PendingCommandState
,09-28 09:59:13.056  4554  4640 D BluetoothAdapterProperties: Scan Mode:20
09-28 09:59:13.056  4554  4636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-28 09:59:13.058  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.058  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:59:13.058  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:13.058  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:13.058  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:13.058  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:13.058  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:59:13.058  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:59:13.058  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:59:13.061  4554  4554 D BluetoothMapService: onReceive
09-28 09:59:13.061  4554  4554 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 09:59:13.061  4554  4554 D BluetoothMapService: STATE_TURNING_OFF
09-28 09:59:13.061  4554  4554 D BluetoothMapService: MAP Service closeService in
,09-28 09:59:13.061  4554  4554 D BluetoothMapMasInstance0: MAP Service shutdown
09-28 09:59:13.061  4554  4554 D ObexServerSockets0: shutdown(block = true)
,09-28 09:59:13.062  4554  4554 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 09:59:13.062  4554  4554 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 09:59:13.062  4554  4799 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-28 09:59:13.062  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.062  5569  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:59:13.063  5569  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:59:13.063   929  5321 D DhcpClient: Clearing IP address
09-28 09:59:13.063   509   923 D CommandListener: Clearing all IP addresses on wlan0
09-28 09:59:13.064  4554  4800 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-28 09:59:13.065  4554  4783 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-28 09:59:13.066  4554  4554 I BtOppRfcommListener: stopping Accept Thread
09-28 09:59:13.066  4554  5233 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-28 09:59:13.066  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:13.067  4554  5233 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-28 09:59:13.071  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:13.074  3555  5391 V NativeCrypto: Read error: ssl=0x7f62fcd800: I/O error during system call, Connection timed out
09-28 09:59:13.074  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.074  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:13.074  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:13.074  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:13.074  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:13.074  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:13.074  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:59:13.074  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:59:13.074  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:59:13.075  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.075  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:59:13.076  3555  5391 V NativeCrypto: SSL shutdown failed: ssl=0x7f62fcd800: I/O error during system call, Broken pipe
,09-28 09:59:13.078   929   939 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,09-28 09:59:13.078   929  5319 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-28 09:59:13.078   929   942 I ActivityManager: Start proc 5623:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-28 09:59:13.080   929  5319 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-28 09:59:13.081   929  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-28 09:59:13.081  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.081   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-28 09:59:13.081  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:13.081  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:13.081  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:13.081  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:13.081  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:13.081  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:59:13.081  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:59:13.081  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:59:13.082  4554  4554 D HeadsetService: Received stop request...Stopping profile...
09-28 09:59:13.082  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.082  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:59:13.082   929  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-28 09:59:13.084  3759  3959 D BluetoothHeadset: Proxy object disconnected
09-28 09:59:13.084  3113  3337 D BluetoothHeadset: Proxy object disconnected
,09-28 09:59:13.084  3113  3113 D HeadsetProfile: Bluetooth service disconnected
09-28 09:59:13.084   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 09:59:13.085   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 09:59:13.085   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 09:59:13.085   509   923 D CommandListener: Setting iface cfg
,09-28 09:59:13.087  4554  4554 D A2dpService: Received stop request...Stopping profile...
,09-28 09:59:13.087  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:13.087  4554  4792 D A2dpStateMachine: Exit Disconnected: -1
09-28 09:59:13.089   929  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-28 09:59:13.089   929  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-28 09:59:13.092  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.092  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:13.092  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:13.092  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:13.092  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:13.092  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:13.092  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:13.092  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:59:13.092  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:59:13.092   535   535 E Parcel  : Reading a NULL string not supported here.
09-28 09:59:13.092  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 09:59:13.093  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:13.094   929   929 D BluetoothA2dp: Proxy object disconnected
09-28 09:59:13.094   929  2946 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-28 09:59:13.095  4554  4554 D HidService: Received stop request...Stopping profile...
09-28 09:59:13.095  4554  4554 D HidService: Stopping Bluetooth HidService
,09-28 09:59:13.096   929   929 D RttService: SCAN_AVAILABLE : 1
,09-28 09:59:13.096   929  3054 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-28 09:59:13.096  4554  4554 V BluetoothAdapterState: isTurningOff()=true
09-28 09:59:13.097  4554  4554 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:13.097  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:13.097  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:13.097  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.097  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:13.097  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:13.097  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:13.097  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:13.097  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:13.097  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:13.097  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:13.097  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:59:13.097  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.097  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:13.098  3727  3880 W QCNEJ   : |CORE| network lost: 100
09-28 09:59:13.098  3727  3880 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-28 09:59:13.098  4554  4554 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-28 09:59:13.099  4554  4554 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-28 09:59:13.099  4554  4640 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-28 09:59:13.099  4554  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:59:13.099  4554  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:59:13.099  4554  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:59:13.100  4554  4640 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-28 09:59:13.100  4554  4554 D HealthService: Received stop request...Stopping profile...
09-28 09:59:13.101   929  5322 D DhcpClient: Receive thread stopped
09-28 09:59:13.101  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.101  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:13.101  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:13.101  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:13.101  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:13.101  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:13.101  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:13.101  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:13.101  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:13.102  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.102  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 09:59:13.103  4554  4554 D PanService: Received stop request...Stopping profile...
,09-28 09:59:13.105  4554  4554 D BluetoothMapService: Received stop request...Stopping profile...
09-28 09:59:13.105  4554  4554 D BluetoothMapService: stop()
09-28 09:59:13.105  4554  4554 D BluetoothMapAppObserver: deinitObservers()
09-28 09:59:13.105  4554  4554 D BluetoothMapAppObserver: removeReceiver()
,09-28 09:59:13.107  4554  4554 V BluetoothAdapterState: isTurningOff()=true
09-28 09:59:13.107  4554  4554 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:13.107  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:13.107  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:13.107  4554  4554 D SapService: Received stop request...Stopping profile...
09-28 09:59:13.108  4554  4554 V SapService: stop()
09-28 09:59:13.108  3113  3113 D BluetoothA2dp: Proxy object disconnected
,09-28 09:59:13.108  3113  3113 D BluetoothInputDevice: Proxy object disconnected
09-28 09:59:13.108  3113  3113 D HidProfile: Bluetooth service disconnected
09-28 09:59:13.110   929  2944 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-28 09:59:13.110  3113  3113 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 09:59:13.111  3113  3113 D PanProfile: Bluetooth service disconnected
09-28 09:59:13.111  3113  3113 D BluetoothMap: Proxy object disconnected
09-28 09:59:13.111  3113  3113 D MapProfile: Bluetooth service disconnected
,09-28 09:59:13.113  4554  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:59:13.113  4554  4554 V BluetoothAdapterState: isTurningOff()=true
09-28 09:59:13.113  4554  4640 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-28 09:59:13.113  4554  4554 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:13.113  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:13.114  4554  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:59:13.114  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:13.114  4554  4742 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 09:59:13.114  4554  4742 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 09:59:13.114  4554  4742 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 09:59:13.114  4554  4742 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 09:59:13.114  4554  4554 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-28 09:59:13.114  4554  4554 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-28 09:59:13.114  4554  4640 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 09:59:13.114  4554  4554 V BluetoothAdapterState: isTurningOff()=true
09-28 09:59:13.114  4554  4554 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:13.114  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:13.114  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:13.115  4554  4554 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-28 09:59:13.115  4554  4640 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-28 09:59:13.115  4554  4554 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-28 09:59:13.115  4554  4554 V BluetoothAdapterState: isTurningOff()=true
09-28 09:59:13.115  4554  4554 V BluetoothAdapterState: isTurningOn()=false
,09-28 09:59:13.115  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:13.115  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:13.116  4554  4554 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-28 09:59:13.116  4554  4554 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-28 09:59:13.116  4554  4554 D BluetoothMapService: MAP Service closeService in
09-28 09:59:13.116  4554  4554 V BluetoothAdapterState: isTurningOff()=true
09-28 09:59:13.117  4554  4554 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:13.117  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:13.117  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:13.117  4554  4554 D BluetoothMapService: cleanup()
09-28 09:59:13.117  4554  4554 D BluetoothMapService: MAP Service closeService in
09-28 09:59:13.117  4554  4554 V BluetoothAdapterState: isTurningOff()=true
09-28 09:59:13.117  4554  4554 V BluetoothAdapterState: isTurningOn()=false
,09-28 09:59:13.117  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:13.117  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:13.117  4554  4636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-28 09:59:13.118   929  2944 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 09:59:13.118  4554  4636 D BluetoothAdapterProperties: Setting state to 15
09-28 09:59:13.119  4554  4636 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-28 09:59:13.119  4554  4636 I BluetoothAdapterState: Entering BleOnState
,09-28 09:59:13.119   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:59:13.119  3113  3125 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:59:13.120  3113  3126 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 09:59:13.120  3113  3337 D BluetoothMap: onBluetoothStateChange: up=false
09-28 09:59:13.122  3113  3125 D BluetoothPbap: onBluetoothStateChange: up=false
,09-28 09:59:13.123  3113  3939 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 09:59:13.124   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 09:59:13.124   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:59:13.124  3113  3126 D BluetoothPan: onBluetoothStateChange on: false
09-28 09:59:13.125  3759  3959 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:59:13.125   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:59:13.126  4554  4636 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-28 09:59:13.126  4554  4636 D BluetoothAdapterProperties: Setting state to 16
09-28 09:59:13.126  4554  4636 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-28 09:59:13.126  4554  4636 D BluetoothAdapterProperties: onBleDisable
09-28 09:59:13.127  4554  4636 I BluetoothAdapterState: Entering PendingCommandState
09-28 09:59:13.127  4554  4637 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-28 09:59:13.128  4554  4640 D BluetoothAdapterProperties: Scan Mode:20
09-28 09:59:13.128  4554  4742 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-28 09:59:13.129  4554  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:59:13.129   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-28 09:59:13.129  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.129  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:13.129  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:13.129  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:13.129  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:13.129  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:13.129  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:13.129  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:13.129  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:13.131  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.131  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:13.131  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:13.131  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:13.131  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:13.131  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:13.131  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:13.131  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:13.131  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:13.133  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:13.134  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:13.136  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:13.139  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:13.154   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 09:59:13.155   509   923 D CommandListener: Clearing all IP addresses on wlan0
,09-28 09:59:13.155   509   923 D TetherController: Setting IP forward enable = 0
,09-28 09:59:13.156   929  2946 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-28 09:59:13.156   929  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 09:59:13.158   929   946 D Tethering: MasterInitialState.processMessage what=3
09-28 09:59:13.159   929  2944 D DhcpClient: doQuit
09-28 09:59:13.159   929  2944 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-28 09:59:13.160   929  5321 D DhcpClient: onQuitting
09-28 09:59:13.160  5219  5219 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e87f491 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-28 09:59:13.160  3423  3423 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-28 09:59:13.160  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:13.163  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.163  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:13.163  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:13.163  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:13.163  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:13.163  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:13.163  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:13.163  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:13.163  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 09:59:13.164  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.165  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 09:59:13.166  4988  5010 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-28 09:59:13.166  4988  5010 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 09:59:13.166  4988  5010 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-28 09:59:13.166  4988  5010 E SarControlService: no key has been found,reset the power
09-28 09:59:13.166  4988  5025 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 09:59:13.166  4988  5025 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 09:59:13.166  4988  5025 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 09:59:13.167  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 09:59:13.167  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 09:59:13.167  5013  5013 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 09:59:13.167  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:13.167  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:13.167  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:13.167  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:13.167  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:13.167  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:13.167  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:13.167  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:13.168  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.168  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:13.168  4988  5025 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 09:59:13.168  4988  5025 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 09:59:13.168  4988  5025 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 09:59:13.169  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-28 09:59:13.169  5013  5013 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 09:59:13.170  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.170  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:13.170  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:13.170  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:13.170  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:13.170  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:13.170  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:13.170  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:13.170  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:13.170  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:13.170  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:13.171  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3f2c3f HexData = [00000000ea03000000000000ffffffff]
09-28 09:59:13.171  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-28 09:59:13.171  5013  5027 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-28 09:59:13.171  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:13.172  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:59:13.172  4988  4999 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 09:59:13.158  5623  5623 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-28 09:59:13.172  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:13.178  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3f2c3f HexData = [00000000eb03000000000000ffffffff]
,09-28 09:59:13.178  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:59:13.178  5013  5027 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-28 09:59:13.179  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:59:13.180  4988  4998 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-28 09:59:13.186  3423  3423 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-28 09:59:13.190  3423  3423 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-28 09:59:13.191  5623  5623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 09:59:13.197   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b05e580:true
09-28 09:59:13.199  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 09:59:13.212   929  3853 I ActivityManager: Start proc 5654:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-28 09:59:13.220   509   923 E Netd    : netlink response contains error (No such file or directory)
,09-28 09:59:13.223   929  2946 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-28 09:59:13.223   929  2946 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 09:59:13.223   509   923 D TetherController: Setting IP forward enable = 0
,09-28 09:59:13.225  5623  5623 D LocalBluetoothProfileManager: Adding local MAP profile
,09-28 09:59:13.227  5623  5623 D BluetoothMap: Create BluetoothMap proxy object
,09-28 09:59:13.232  3423  3423 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-28 09:59:13.239  5623  5623 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-28 09:59:13.242  3423  3423 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-28 09:59:13.253  4964  4964 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 09:59:13.253   929  2944 D wifi    : In wifi stop Hal
09-28 09:59:13.253   929  2944 D wifi    : halHandle = 0x7f61467400, mVM = 0x7f7da4d140, mCls = 0x100a02
09-28 09:59:13.253   929  3422 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-28 09:59:13.253   929  3422 D WifiHAL : Got a signal to exit!!!
09-28 09:59:13.253   929  3422 I WifiHAL : Exit wifi_event_loop
09-28 09:59:13.254   929  2944 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-28 09:59:13.254   929  2944 E WifiHAL : Event processing terminated
09-28 09:59:13.254   929  2944 D wifi    : In wifi cleaned up handler
09-28 09:59:13.254   929  2944 I WifiHAL : Internal cleanup completed
09-28 09:59:13.254  4056  4197 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 09:59:13.256  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:13.258  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:13.259  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:13.262  5654  5654 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-28 09:59:13.264  5623  5623 D DockEventReceiver: finishStartingService: stopping service
,09-28 09:59:13.270   929  3569 I ActivityManager: Killing 4928:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-28 09:59:13.280   929  3422 D wifi    : set interface wlan0 flags (DOWN)
,09-28 09:59:13.281   929  2944 D WifiNative-HAL: HAL event thread stopped successfully
,09-28 09:59:13.335  4554  4640 I bt_hci  : shut_down
,09-28 09:59:13.340  4554  4644 D bt_hwcfg: hw_epilog_process
,09-28 09:59:13.340  4554  4644 I bt_vendor: low_power_mode_cb
,09-28 09:59:13.342  4554  4644 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-28 09:59:13.342  4554  4644 I bt_vendor: epilog_cb
09-28 09:59:13.342  4554  4644 I bt_hci  : epilog_finished_callback
,09-28 09:59:13.344  4554  4640 I bt_hci_h4: hal_close
,09-28 09:59:13.345  4554  4640 I bt_userial_vendor: device fd = 54 close
,09-28 09:59:13.454  4554  4637 D bt_stack_manager: event_shut_down_stack finished.
,09-28 09:59:13.454  4554  4636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-28 09:59:13.456  4554  4636 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-28 09:59:13.456  4554  4554 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-28 09:59:13.457  4554  4554 D BtGatt.GattService: Received stop request...Stopping profile...
,09-28 09:59:13.457  4554  4554 D BtGatt.GattService: stop()
09-28 09:59:13.457  4554  4554 D BtGatt.AdvertiseManager: advertise clients cleared
09-28 09:59:13.459  4554  4554 V BluetoothAdapterState: isTurningOff()=false
09-28 09:59:13.459  4554  4554 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:13.459  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:13.459  4554  4554 V BluetoothAdapterState: isBleTurningOff()=true
09-28 09:59:13.459  4554  4636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-28 09:59:13.460  4554  4636 D BluetoothAdapterProperties: Setting state to 10
09-28 09:59:13.460  4554  4636 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-28 09:59:13.460  4554  4636 I BluetoothAdapterState: Entering OffState
,09-28 09:59:13.461   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-28 09:59:13.467  4554  4554 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-28 09:59:13.467  4554  4554 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-28 09:59:13.467  4554  4554 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-28 09:59:13.469  4554  4637 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-28 09:59:13.481  4554  4637 D bt_stack_manager: event_clean_up_stack finished.
,09-28 09:59:13.483   929   946 D Tethering: InitialState.processMessage what=4
09-28 09:59:13.486   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-28 09:59:13.490  4554  4554 I art     : System.exit called, status: 0
,09-28 09:59:13.490  4554  4554 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-28 09:59:13.509  5654  5654 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-28 09:59:13.509  5654  5654 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 09:59:13.509  5654  5654 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 09:59:13.509  5654  5654 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.r.e.b(PG:170)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 09:59:13.509  5654  5654 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.r.k.d(PG:583)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.r.e.b(PG:170)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:59:13.509  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 09:59:13.510  5654  5654 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 09:59:13.510  5654  5654 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 09:59:13.510  5654  5654 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:59:13.510  5654  5654 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 09:59:13.521  5623  5623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 09:59:13.523   929   940 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
09-28 09:59:13.524   929   940 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
09-28 09:59:13.524   929   940 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-28 09:59:13.524   929   940 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-28 09:59:13.524   929   940 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-28 09:59:13.524   929   940 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-28 09:59:13.524   929   940 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-28 09:59:13.524   929   940 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-28 09:59:13.524   929   940 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-28 09:59:13.524   929   940 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
09-28 09:59:13.524   929   940 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-28 09:59:13.524   929   940 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-28 09:59:13.524   929   940 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
09-28 09:59:13.546   929   940 I ActivityManager: Start proc 5689:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-28 09:59:13.547   929  3128 W ActivityManager: Spurious death for ProcessRecord{87edbed 5689:com.android.bluetooth/1002}, curProc for 4554: null
,09-28 09:59:13.548  5623  5623 D DockEventReceiver: finishStartingService: stopping service
09-28 09:59:13.549   929  3570 I ActivityManager: Killing 5349:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-28 09:59:13.602  5689  5689 D AdapterServiceConfig: Adding HeadsetService
,09-28 09:59:13.603  5689  5689 D AdapterServiceConfig: Adding A2dpService
09-28 09:59:13.603  5689  5689 D AdapterServiceConfig: Adding HidService
09-28 09:59:13.603  5689  5689 D AdapterServiceConfig: Adding HealthService
09-28 09:59:13.603  5689  5689 D AdapterServiceConfig: Adding PanService
09-28 09:59:13.603  5689  5689 D AdapterServiceConfig: Adding GattService
09-28 09:59:13.603  5689  5689 D AdapterServiceConfig: Adding BluetoothMapService
,09-28 09:59:13.604  5689  5689 D AdapterServiceConfig: Adding SapService
,09-28 09:59:13.606   929  3853 I ActivityManager: Killing 5361:com.android.chrome/u0a39 (adj 15): empty #17
,09-28 09:59:13.649  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 09:59:13.660  3832  3832 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-28 09:59:13.663  3832  3832 D SystemUpdateService: onCreate
,09-28 09:59:13.669  3832  3832 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 09:59:13.682  3832  3832 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-28 09:59:13.684  3832  5345 I iu.UploadsManager: num queued entries: 0
,09-28 09:59:13.684  3832  5345 I iu.UploadsManager: num updated entries: 0
,09-28 09:59:13.685  3832  5345 I iu.SyncManager: NEXT; no task
,09-28 09:59:13.689  3832  3832 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 09:59:13.691  3832  3832 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 09:59:13.692  3832  5701 I SystemUpdateService: active receiver: enabled
,09-28 09:59:13.702   929  3841 I ActivityManager: Start proc 5703:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-28 09:59:13.705  3832  5701 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 09:59:13.717  3832  5701 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-28 09:59:13.719  3832  5701 I SystemUpdateService: now status is 0 (complete)
,09-28 09:59:13.719  3832  5701 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 09:59:13.719  3832  5701 I SystemUpdateService: file has been verified
09-28 09:59:13.719  3832  5701 I SystemUpdateService: OTA package size = 21989297
,09-28 09:59:13.737  5703  5703 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-28 09:59:13.740  5703  5703 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 09:59:13.747  5703  5703 D SprintDMHelper: simOperator: 
09-28 09:59:13.747  5703  5703 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 09:59:13.754  3832  5701 I SystemUpdateService: showing system update notification
,09-28 09:59:13.759   929  3549 I ActivityManager: Start proc 5715:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-28 09:59:13.796  3832  3832 D SystemUpdateService: onDestroy
,09-28 09:59:13.797   929  3841 I ActivityManager: Killing 5376:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-28 09:59:13.870  4964  5729 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-28 09:59:13.875   929  3128 I ActivityManager: Start proc 5730:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-28 09:59:13.878   929  3853 I ActivityManager: Killing 5219:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-28 09:59:13.939  5730  5730 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-28 09:59:14.086  5654  5675 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-28 09:59:14.126   929  3123 I ActivityManager: Killing 4650:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-28 09:59:14.141   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6e6de3:true
,09-28 09:59:14.168   929  3128 I ActivityManager: Start proc 5744:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-28 09:59:14.202  5744  5744 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-28 09:59:14.211   929  3569 I ActivityManager: Killing 5432:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-28 09:59:18.065   929  3569 D WifiService: setWifiEnabled: true pid=5569, uid=10077
,09-28 09:59:18.066   929  3569 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 09:59:18.074   509   923 D SoftapController: Softap fwReload - Ok
,09-28 09:59:18.080   509   923 D CommandListener: Setting iface cfg
,09-28 09:59:18.081   509   923 D CommandListener: Trying to bring down wlan0
09-28 09:59:18.082   509   923 D CommandListener: Clearing all IP addresses on wlan0
,09-28 09:59:18.089   929  2944 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 09:59:18.647   929  2944 D wifi    : set interface wlan0 flags (UP)
09-28 09:59:18.647   929  2944 I WifiHAL : Initializing wifi
09-28 09:59:18.647   929  2944 I WifiHAL : Creating socket
,09-28 09:59:18.650   929  2944 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-28 09:59:18.650   929  2944 D wifi    : Did set static halHandle = 0x7f61467400
,09-28 09:59:18.650   929  2944 D wifi    : halHandle = 0x7f61467400, mVM = 0x7f7da4d140, mCls = 0x20188a
09-28 09:59:18.651   929  2944 D wifi    : array field set
09-28 09:59:18.651   929  2944 I WifiNative-HAL: interface[0] = wlan0
,09-28 09:59:18.652   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-28 09:59:18.654   929  5762 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547092853760
09-28 09:59:18.654   929  5762 D wifi    : waitForHalEvents called, vm = 0x7f7da4d140, obj = 0x20188a, env = 0x7f622d6b40
,09-28 09:59:18.723  5763  5763 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-28 09:59:18.736  5763  5763 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 09:59:18.756   929  2944 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-28 09:59:18.759  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:18.759  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:18.760  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:18.789  5763  5763 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 09:59:18.789  5763  5763 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-28 09:59:18.805   929  2944 D WifiConfigStore: Loading config and enabling all networks 
,09-28 09:59:18.805  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:18.805  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:18.805  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:18.805  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:18.805  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:18.805  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:18.805  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:18.805  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:18.805  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:18.806  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:18.806  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 09:59:18.807  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 09:59:18.808  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:18.808  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:18.808  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:18.808  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:18.808  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:18.808  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:18.808  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:18.808  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:18.808  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:18.808  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:18.809  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 09:59:18.809  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:18.809  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:18.809  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:18.809  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:18.809  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:18.809  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:18.809  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:18.809  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:18.809  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:18.809  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 09:59:18.815   929  2944 D WifiConfigStore: loaded 0 passpoint configs
,09-28 09:59:18.816   929  2944 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-28 09:59:18.816   929  2944 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-28 09:59:18.817   929  2944 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-28 09:59:18.818   929  2944 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-28 09:59:18.819   929  2944 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-28 09:59:18.819   929  2944 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-28 09:59:18.819   929  2944 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-28 09:59:18.823   929  2944 D WifiNative-HAL: Setting external_sim to 1
,09-28 09:59:18.823  4964  4964 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 09:59:18.823   929  2944 D wifi    : setting dfs flag to true, 0x7f636e3e20
,09-28 09:59:18.824   929  2944 D WifiStateMachine: Setting OUI to DA-A1-19
09-28 09:59:18.824   929  2944 D wifi    : setting scan oui 0x7f636e3e20
09-28 09:59:18.824   929  2944 D WifiHAL : Sending mac address OUI
,09-28 09:59:18.828   929  2944 E native  : do suspend false
,09-28 09:59:18.835   929  2944 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-28 09:59:18.835   929   929 D RttService: SCAN_AVAILABLE : 3
,09-28 09:59:18.835   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-28 09:59:18.835   929  3054 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-28 09:59:18.836   509   923 D CommandListener: Setting iface cfg
,09-28 09:59:18.839   929  2942 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-28 09:59:18.839   929  2942 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-28 09:59:18.847   929  2942 D WifiNative-HAL: p2pGetDeviceAddress
,09-28 09:59:18.848   929  2942 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-28 09:59:18.853   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267288 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-28 09:59:21.978  5763  5763 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:59:21.983  5763  5763 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:59:21.987  5763  5763 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:59:22.046   929  2944 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-28 09:59:22.048   929  2944 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-28 09:59:22.048   929  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 09:59:22.060   929  2944 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-28 09:59:22.094   929  2944 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-28 09:59:22.096  5763  5763 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-28 09:59:22.520  5763  5763 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-28 09:59:22.556  5763  5763 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-28 09:59:22.557  5763  5763 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-28 09:59:22.564   929  2944 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 09:59:22.564   929  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-28 09:59:22.564   929  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-28 09:59:22.580   929  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 09:59:22.590   509   923 D CommandListener: Setting iface cfg
,09-28 09:59:22.596   929  2944 D WifiStateMachine: Start Dhcp Watchdog 2
,09-28 09:59:22.602   929  5771 D DhcpClient: Receive thread started
,09-28 09:59:22.606   929  2944 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-28 09:59:22.606   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-28 09:59:22.606   929  2946 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-28 09:59:22.687   929  2944 E native  : do suspend false
,09-28 09:59:22.701   929  5770 D DhcpClient: Broadcasting DHCPDISCOVER
,09-28 09:59:22.720   929  5771 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
,09-28 09:59:22.720   929  5770 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
,09-28 09:59:22.722   929  5770 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-28 09:59:22.736   929  5771 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-28 09:59:22.737   929  5770 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-28 09:59:22.739   509   923 D CommandListener: Setting iface cfg
,09-28 09:59:22.744   929  2944 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-28 09:59:22.746   929  5770 D DhcpClient: Scheduling renewal in 86399s
,09-28 09:59:22.757   929  2944 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-28 09:59:22.758   929  2944 D WifiConfigStore: No blacklist allowed without epno enabled
09-28 09:59:22.759   929  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-28 09:59:22.761   929  2946 D ConnectivityService: Adding iface wlan0 to network 101
,09-28 09:59:22.761   929  2944 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-28 09:59:22.811   929  2946 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-28 09:59:22.811   929  2946 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-28 09:59:22.814   929  2946 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-28 09:59:22.817   929  2946 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-28 09:59:22.819   929  2946 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-28 09:59:22.828   929  2946 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-28 09:59:22.832   929  2946 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-28 09:59:22.832   929  2946 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-28 09:59:22.832   929  2946 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-28 09:59:22.832   929  2946 D ConnectivityService:    accepting network in place of null
09-28 09:59:22.832   929  2944 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-28 09:59:22.832   929  2944 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 09:59:22.833   929  2946 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 09:59:22.846   929  5769 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271281, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 09:59:22.858   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 09:59:22.879   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 09:59:22.882   929  2946 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-28 09:59:22.882   929  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-28 09:59:22.882  3727  3880 W QCNEJ   : |CORE| network available: 101
,09-28 09:59:22.883   929  2946 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-28 09:59:22.885   929   946 D Tethering: MasterInitialState.processMessage what=3
09-28 09:59:22.888  3727  3880 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-28 09:59:22.888  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:22.889  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:22.889  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:22.889  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:22.889  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:22.889  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:22.889  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:59:22.889  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:59:22.889  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:59:22.889  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:22.889  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:59:22.890  3727  3880 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-28 09:59:22.890  3727  3880 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-28 09:59:22.892  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:22.892  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:22.892  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:22.892  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:22.892  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:22.892  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:22.892  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:59:22.892  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:59:22.892  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:59:22.892  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:22.892  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:59:22.895  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 09:59:22.895  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:22.895  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:22.895  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:22.895  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:22.895  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:22.895  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:59:22.895  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:59:22.895  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:59:22.895  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:22.895  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:59:22.898  4988  5010 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 09:59:22.898  4988  5010 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 09:59:22.898  4988  5010 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-28 09:59:22.898  4988  5010 E SarControlService: no key has been found,reset the power
,09-28 09:59:22.899  4988  5025 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-28 09:59:22.899  4988  5025 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 09:59:22.899  4988  5025 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 09:59:22.899  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 09:59:22.899  5013  5013 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 09:59:22.902  4988  5025 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 09:59:22.902  4988  5025 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 09:59:22.902  4988  5025 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 09:59:22.902  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-28 09:59:22.903  5013  5013 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 09:59:22.905  3832  3832 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-28 09:59:22.908  3832  3832 D SystemUpdateService: onCreate
,09-28 09:59:22.909  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3f2c3f HexData = [00000000ec03000000000000ffffffff]
09-28 09:59:22.910  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:59:22.910  5013  5027 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-28 09:59:22.911   929  5768 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-28 09:59:22.913  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:59:22.914  4988  4999 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-28 09:59:22.918  3832  3832 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-28 09:59:22.919  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3f2c3f HexData = [00000000ed03000000000000ffffffff]
09-28 09:59:22.919  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:59:22.919  5013  5027 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-28 09:59:22.920  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:59:22.920  4988  4998 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-28 09:59:22.929  3832  3832 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-28 09:59:22.936  3832  5345 I iu.UploadsManager: num queued entries: 0
,09-28 09:59:22.936  3832  5345 I iu.UploadsManager: num updated entries: 0
09-28 09:59:22.937  3832  5345 I iu.SyncManager: NEXT; no task
,09-28 09:59:22.940  3832  5781 I SystemUpdateService: active receiver: enabled
,09-28 09:59:22.941  3832  3832 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 09:59:22.943  3832  3832 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 09:59:22.945  5703  5703 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 09:59:22.948  5703  5703 D SprintDMHelper: simOperator: 
09-28 09:59:22.948  5703  5703 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 09:59:22.980  3832  5781 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 09:59:22.988   929  5768 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 28 Sep 2016 13:59:22 GMT], X-Android-Received-Millis=[1475071162987], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475071162938]}
,09-28 09:59:22.988   929  2946 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-28 09:59:22.988   929  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-28 09:59:22.989   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-28 09:59:22.990   929  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-28 09:59:22.991  3832  5781 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-28 09:59:22.991  3832  5781 I SystemUpdateService: now status is 0 (complete)
09-28 09:59:22.991  3832  5781 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 09:59:22.991  3832  5781 I SystemUpdateService: file has been verified
09-28 09:59:22.991  3832  5781 I SystemUpdateService: OTA package size = 21989297
,09-28 09:59:22.997  3832  5781 I SystemUpdateService: showing system update notification
,09-28 09:59:23.010  3832  3832 D SystemUpdateService: onDestroy
,09-28 09:59:23.062  4964  5786 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-28 09:59:23.072   929  3123 D WifiService: setWifiEnabled: false pid=5569, uid=10077
,09-28 09:59:23.072   929  3123 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-28 09:59:23.074   929  2944 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-28 09:59:23.074   929  2944 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-28 09:59:23.074   929  2944 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 09:59:23.074   929  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 09:59:23.081   929  5770 D DhcpClient: Clearing IP address
09-28 09:59:23.081   509   923 D CommandListener: Clearing all IP addresses on wlan0
,09-28 09:59:23.083   509   923 D CommandListener: Setting iface cfg
,09-28 09:59:23.088  3555  5791 V NativeCrypto: Read error: ssl=0x7f7798ce00: I/O error during system call, Connection timed out
09-28 09:59:23.088  3555  5791 V NativeCrypto: SSL shutdown failed: ssl=0x7f7798ce00: I/O error during system call, Broken pipe
,09-28 09:59:23.093   929  3841 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
09-28 09:59:23.094   929  5768 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,09-28 09:59:23.094   929  5768 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-28 09:59:23.095   929  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-28 09:59:23.095   929  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-28 09:59:23.100   535   535 E Parcel  : Reading a NULL string not supported here.
,09-28 09:59:23.101   929  5771 D DhcpClient: Receive thread stopped
,09-28 09:59:23.104   929  5768 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-28 09:59:23.106   929  2946 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-28 09:59:23.109  3727  3880 W QCNEJ   : |CORE| network lost: 101
09-28 09:59:23.109   929   929 D RttService: SCAN_AVAILABLE : 1
,09-28 09:59:23.109   929  3054 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-28 09:59:23.109  3727  3880 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-28 09:59:23.112   929  2944 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-28 09:59:23.114   929  2944 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 09:59:23.130   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 09:59:23.148   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 09:59:23.149   929  2946 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-28 09:59:23.149   509   923 D CommandListener: Clearing all IP addresses on wlan0
09-28 09:59:23.149   929  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-28 09:59:23.151   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-28 09:59:23.153   929  2944 D DhcpClient: doQuit
,09-28 09:59:23.153   929  2944 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-28 09:59:23.153   929  5770 D DhcpClient: onQuitting
09-28 09:59:23.154  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:23.154  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:23.154  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:23.154  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:23.154  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:23.154  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:23.154  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:23.154  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:23.154  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:23.154  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:23.154  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:23.154  5763  5763 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-28 09:59:23.155  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:23.155  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:23.155  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:23.155  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:23.155  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:23.155  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:23.155  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:23.155  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:23.155  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:23.155  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 09:59:23.155  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:23.156  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:23.157  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:23.157  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:23.157  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:23.157  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:23.157  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:23.157  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:23.157  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:23.157  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:23.157  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:23.157  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:23.158  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:23.158  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:23.158  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:23.158  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:23.158  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:23.158  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:23.158  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:23.158  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:23.158  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:23.158  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:23.158  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:23.159  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:23.159  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:23.160  3832  3832 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 09:59:23.162  4988  5010 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 09:59:23.162  4988  5010 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 09:59:23.162  4988  5010 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-28 09:59:23.163  4988  5010 E SarControlService: no key has been found,reset the power
09-28 09:59:23.163  4988  5025 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 09:59:23.163  4988  5025 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 09:59:23.163  4988  5025 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-28 09:59:23.164  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 09:59:23.164  5013  5013 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 09:59:23.166  4988  5025 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-28 09:59:23.166  4988  5025 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 09:59:23.166  4988  5025 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 09:59:23.167  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 09:59:23.167  5013  5013 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 09:59:23.170  3832  3832 D SystemUpdateService: onCreate
09-28 09:59:23.171  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3f2c3f HexData = [00000000ee03000000000000ffffffff]
09-28 09:59:23.171  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:59:23.171  5013  5027 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-28 09:59:23.171  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:59:23.171  4988  4998 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 09:59:23.172  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3f2c3f HexData = [00000000ef03000000000000ffffffff]
09-28 09:59:23.172  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:59:23.172  5013  5027 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-28 09:59:23.172  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:59:23.173  4988  4999 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 09:59:23.175  5763  5763 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-28 09:59:23.176  3832  3832 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-28 09:59:23.177  5763  5763 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-28 09:59:23.185  3832  3832 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-28 09:59:23.189  3832  5345 I iu.UploadsManager: num queued entries: 0
,09-28 09:59:23.189  3832  5345 I iu.UploadsManager: num updated entries: 0
09-28 09:59:23.190  3832  5345 I iu.SyncManager: NEXT; no task
,09-28 09:59:23.191  3832  5801 I SystemUpdateService: active receiver: enabled
,09-28 09:59:23.193  3832  3832 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 09:59:23.195  3832  3832 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 09:59:23.197  5703  5703 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 09:59:23.200  5703  5703 D SprintDMHelper: simOperator: 
09-28 09:59:23.201  5703  5703 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 09:59:23.204   509   923 E Netd    : netlink response contains error (No such file or directory)
09-28 09:59:23.206   929  2946 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-28 09:59:23.206   929  2946 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 09:59:23.210  5763  5763 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-28 09:59:23.213  4964  5805 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-28 09:59:23.222  3832  5801 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 09:59:23.225  5763  5763 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-28 09:59:23.228  3832  5801 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-28 09:59:23.229  3832  5801 I SystemUpdateService: now status is 0 (complete)
09-28 09:59:23.229  3832  5801 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 09:59:23.229  3832  5801 I SystemUpdateService: file has been verified
09-28 09:59:23.229  3832  5801 I SystemUpdateService: OTA package size = 21989297
,09-28 09:59:23.234  3832  5801 I SystemUpdateService: showing system update notification
,09-28 09:59:23.243  3832  3832 D SystemUpdateService: onDestroy
,09-28 09:59:23.326   929  2944 D wifi    : In wifi stop Hal
09-28 09:59:23.326   929  2944 D wifi    : halHandle = 0x7f61467400, mVM = 0x7f7da4d140, mCls = 0x20188a
09-28 09:59:23.329   929  5762 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-28 09:59:23.329   929  5762 D WifiHAL : Got a signal to exit!!!
09-28 09:59:23.329   929  5762 I WifiHAL : Exit wifi_event_loop
09-28 09:59:23.330  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:23.332   929  2944 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-28 09:59:23.332   929  2944 E WifiHAL : Event processing terminated
09-28 09:59:23.332   929  2944 D wifi    : In wifi cleaned up handler
,09-28 09:59:23.332   929  2944 I WifiHAL : Internal cleanup completed
,09-28 09:59:23.335  4056  4197 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 09:59:23.335  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:23.336  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:23.338  4964  4964 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 09:59:23.354   929  5762 D wifi    : set interface wlan0 flags (DOWN)
,09-28 09:59:23.354   929  2944 D WifiNative-HAL: HAL event thread stopped successfully
,09-28 09:59:23.559   929   946 D Tethering: InitialState.processMessage what=4
,09-28 09:59:23.565   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-28 09:59:23.882   929  2946 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-28 09:59:25.433   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:26.434   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:27.435   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:28.107   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41498f7:true
,09-28 09:59:28.108  5689  5689 D BluetoothAdapterState: make() - Creating AdapterState
,09-28 09:59:28.113  5689  5689 I bt_bluedroid: init
,09-28 09:59:28.113  5689  5807 I BluetoothAdapterState: Entering OffState
,09-28 09:59:28.116  5689  5808 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-28 09:59:28.117  5689  5808 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-28 09:59:28.117  5689  5808 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-28 09:59:28.117  5689  5808 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-28 09:59:28.118  5689  5689 I bt_bluedroid: get_profile_interface socket
,09-28 09:59:28.121  5689  5811 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-28 09:59:28.121  5689  5689 I bt_bluedroid: get_profile_interface sdp
,09-28 09:59:28.124  5689  5811 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 09:59:28.131  5689  5700 I bt_bluedroid: config_hci_snoop_log
,09-28 09:59:28.132   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-28 09:59:28.139  5689  5807 D BluetoothAdapterState: Current state: OFF, message: 0
,09-28 09:59:28.139  5689  5807 D BluetoothAdapterProperties: Setting state to 14
09-28 09:59:28.139  5689  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-28 09:59:28.142  5689  5807 D BluetoothBondStateMachine: make
,09-28 09:59:28.144  5689  5812 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-28 09:59:28.148  5689  5807 I BluetoothAdapterState: Entering PendingCommandState
,09-28 09:59:28.149  5689  5689 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-28 09:59:28.153  5689  5689 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
,09-28 09:59:28.154  5689  5689 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-28 09:59:28.155  5689  5689 D BtGatt.GattService: Received start request. Starting profile...
,09-28 09:59:28.155  5689  5689 D BtGatt.GattService: start()
09-28 09:59:28.155  5689  5689 I bt_bluedroid: get_profile_interface gatt
09-28 09:59:28.158  5689  5689 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
,09-28 09:59:28.158  5689  5689 D BtGatt.AdvertiseManager: advertise manager created
,09-28 09:59:28.166  5689  5689 V BluetoothAdapterState: isTurningOff()=false
,09-28 09:59:28.166  5689  5689 V BluetoothAdapterState: isTurningOn()=false
,09-28 09:59:28.166  5689  5689 V BluetoothAdapterState: isBleTurningOn()=true
09-28 09:59:28.166  5689  5689 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 09:59:28.166  5689  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-28 09:59:28.168  5689  5807 I bt_bluedroid: bt_bluedroid
09-28 09:59:28.168  5689  5808 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-28 09:59:28.169  5689  5808 I bt_hci  : start_up
,09-28 09:59:28.176  5689  5808 I bt_vendor: alloc value 0xf3fec871
09-28 09:59:28.176  5689  5808 I bt_vendor: init
09-28 09:59:28.176  5689  5808 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-28 09:59:28.176  5689  5808 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-28 09:59:28.287  5689  5808 D bt_hci  : start_up starting async portion
,09-28 09:59:28.288  5689  5815 I bt_hci  : event_finish_startup
,09-28 09:59:28.288  5689  5815 I bt_hci_h4: hal_open
,09-28 09:59:28.288  5689  5815 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-28 09:59:28.287  5816  5816 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-28 09:59:28.291  5689  5815 I bt_userial_vendor: device fd = 54 open
,09-28 09:59:28.306  5689  5815 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 09:59:28.309  5689  5815 D bt_hwcfg: Chipset BCM4358A3
,09-28 09:59:28.309  5689  5815 D bt_hwcfg: Target name = [BCM4358A3]
,09-28 09:59:28.309  5689  5815 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-28 09:59:28.435   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:28.702  5689  5815 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-28 09:59:28.702  5689  5815 D bt_hwcfg: Settlement delay -- 100 ms
09-28 09:59:28.702  5689  5815 I bt_hwcfg: Setting fw settlement delay to 100 
,09-28 09:59:28.836  5689  5815 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-28 09:59:28.836  5689  5815 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-28 09:59:28.838  5689  5815 I bt_hwcfg: vendor lib fwcfg completed
,09-28 09:59:28.838  5689  5815 I bt_vendor: firmware callback
09-28 09:59:28.838  5689  5815 I bt_hci  : firmware_config_callback
09-28 09:59:28.847  5689  5820 I bt_btu  : btu_task pending for preload complete event
,09-28 09:59:28.847  5689  5820 I bt_btu_task: Bluetooth chip preload is complete
09-28 09:59:28.847  5689  5820 I bt_btu  : btu_task received preload complete event
,09-28 09:59:28.855  5689  5820 I         : BTE_InitTraceLevels -- TRC_HCI
,09-28 09:59:28.855  5689  5820 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-28 09:59:28.855  5689  5820 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-28 09:59:28.855  5689  5820 I         : BTE_InitTraceLevels -- TRC_AVDT
09-28 09:59:28.856  5689  5820 I         : BTE_InitTraceLevels -- TRC_AVRC
09-28 09:59:28.856  5689  5820 I         : BTE_InitTraceLevels -- TRC_A2D
09-28 09:59:28.856  5689  5820 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-28 09:59:28.856  5689  5820 I         : BTE_InitTraceLevels -- TRC_BTM
09-28 09:59:28.856  5689  5820 I         : BTE_InitTraceLevels -- TRC_GAP
09-28 09:59:28.856  5689  5820 I         : BTE_InitTraceLevels -- TRC_PAN
09-28 09:59:28.856  5689  5820 I         : BTE_InitTraceLevels -- TRC_SDP
09-28 09:59:28.856  5689  5820 I         : BTE_InitTraceLevels -- TRC_GATT
,09-28 09:59:28.857  5689  5820 I         : BTE_InitTraceLevels -- TRC_SMP
09-28 09:59:28.857  5689  5820 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-28 09:59:28.857  5689  5820 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-28 09:59:28.937  5689  5820 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f6a549
,09-28 09:59:28.938  5689  5820 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f6a549 
,09-28 09:59:28.956  5689  5811 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-28 09:59:28.957  5689  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-28 09:59:28.958  5689  5811 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-28 09:59:28.959  5689  5811 D BluetoothAdapterProperties: Name is: Nexus 6P
09-28 09:59:28.962  5689  5811 D BluetoothAdapterProperties: Scan Mode:20
09-28 09:59:28.962  5689  5811 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 09:59:28.963  5689  5811 D bt_hci  : do_postload posting postload work item
,09-28 09:59:28.963  5689  5815 I bt_hci  : event_postload
09-28 09:59:28.963  5689  5815 I bt_vendor: sco_config_cb
,09-28 09:59:28.963  5689  5815 I bt_hci  : sco_config_callback postload finished.
,09-28 09:59:28.968  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:28.970  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:28.973  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:28.976  5689  5811 D bt_bte_conf: Device ID record 1 : primary
,09-28 09:59:28.976  5689  5811 D bt_bte_conf:   vendorId            = 000f
09-28 09:59:28.976  5689  5815 I bt_vendor: low_power_mode_cb
09-28 09:59:28.976  5689  5811 D bt_bte_conf:   vendorIdSource      = 0001
,09-28 09:59:28.976  5689  5811 D bt_bte_conf:   product             = 1200
,09-28 09:59:28.976  5689  5811 D bt_bte_conf:   version             = 1436
09-28 09:59:28.976  5689  5811 D bt_bte_conf:   clientExecutableURL = 
09-28 09:59:28.976  5689  5811 D bt_bte_conf:   serviceDescription  = 
09-28 09:59:28.976  5689  5811 D bt_bte_conf:   documentationURL    = 
,09-28 09:59:28.976  5689  5811 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-28 09:59:28.976  5689  5808 D bt_stack_manager: event_start_up_stack finished
09-28 09:59:28.977  5689  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-28 09:59:28.978  5689  5807 D BluetoothAdapterProperties: Setting state to 15
,09-28 09:59:28.978  5689  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-28 09:59:28.979  5689  5807 I BluetoothAdapterState: Entering BleOnState
,09-28 09:59:28.983  5689  5807 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-28 09:59:28.983  5689  5807 D BluetoothAdapterProperties: Setting state to 11
09-28 09:59:28.983  5689  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-28 09:59:28.988  5689  5689 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
09-28 09:59:28.989  5689  5689 D HeadsetService: Received start request. Starting profile...
,09-28 09:59:28.992  5689  5689 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-28 09:59:28.993  5689  5689 D HeadsetStateMachine: make
,09-28 09:59:28.995  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:28.998  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:29.000  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:29.005  5689  5807 I BluetoothAdapterState: Entering PendingCommandState
,09-28 09:59:29.009  5689  5689 D HeadsetStateMachine: max_hf_connections = 1
,09-28 09:59:29.009  5689  5689 I bt_bluedroid: get_profile_interface handsfree
09-28 09:59:29.010  5689  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-28 09:59:29.010  5689  5811 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-28 09:59:29.013  5689  5689 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
09-28 09:59:29.014  5689  5689 D A2dpService: Received start request. Starting profile...
09-28 09:59:29.015  5689  5689 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-28 09:59:29.016  5689  5689 I bt_bluedroid: get_profile_interface avrcp
,09-28 09:59:29.024  5689  5689 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-28 09:59:29.024  5689  5689 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-28 09:59:29.024  5689  5689 D A2dpStateMachine: make
,09-28 09:59:29.026  5689  5689 I bt_bluedroid: get_profile_interface a2dp
,09-28 09:59:29.026  5689  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-28 09:59:29.028  5689  5829 D A2dpStateMachine: Enter Disconnected: -2
09-28 09:59:29.028  5689  5689 I BluetoothHidServiceJni: classInitNative: succeeds
09-28 09:59:29.029  5689  5689 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
09-28 09:59:29.030  5623  5623 D BluetoothInputDevice: Proxy object connected
09-28 09:59:29.031  5689  5689 D HidService: Received start request. Starting profile...
09-28 09:59:29.031  5689  5689 I bt_bluedroid: get_profile_interface hidhost
,09-28 09:59:29.031  5689  5689 D HidService: setHidService(): set to: null
09-28 09:59:29.031  5689  5811 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f4b56d
09-28 09:59:29.031  5689  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-28 09:59:29.032  5689  5689 I BluetoothHealthServiceJni: classInitNative: succeeds
09-28 09:59:29.033  5689  5689 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
09-28 09:59:29.034  5623  5623 D HidProfile: Bluetooth service connected
09-28 09:59:29.035  5689  5689 D HealthService: Received start request. Starting profile...
,09-28 09:59:29.036  5689  5689 I bt_bluedroid: get_profile_interface health
09-28 09:59:29.037  5689  5689 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-28 09:59:29.038  5689  5689 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
09-28 09:59:29.039  5689  5689 D PanService: Received start request. Starting profile...
09-28 09:59:29.039  5689  5689 D BluetoothPanServiceJni: initializeNative(L110): pan
09-28 09:59:29.040  5689  5689 I bt_bluedroid: get_profile_interface pan
09-28 09:59:29.040  5689  5811 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-28 09:59:29.043  5689  5689 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
,09-28 09:59:29.044  5623  5623 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 09:59:29.045  5689  5689 D BluetoothMapService: Received start request. Starting profile...
09-28 09:59:29.045  5689  5689 D BluetoothMapService: start()
,09-28 09:59:29.045  5623  5623 D PanProfile: Bluetooth service connected
,09-28 09:59:29.045  5623  5623 D BluetoothMap: Proxy object connected
09-28 09:59:29.046  5623  5623 D MapProfile: Bluetooth service connected
09-28 09:59:29.046  5623  5623 D BluetoothMap: getConnectedDevices()
09-28 09:59:29.047  5623  5623 D BluetoothMap: Bluetooth is Not enabled
09-28 09:59:29.048  5689  5689 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-28 09:59:29.048  5689  5689 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-28 09:59:29.049  5689  5689 D BluetoothMapAppObserver: createReceiver()
,09-28 09:59:29.050  5689  5689 D BluetoothMapAppObserver: initObservers()
,09-28 09:59:29.050  5689  5689 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-28 09:59:29.059  5689  5689 V SapService: SapBinder()
,09-28 09:59:29.059  5689  5689 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
09-28 09:59:29.060  5689  5689 D SapService: Received start request. Starting profile...
09-28 09:59:29.060  5689  5689 V SapService: start()
,09-28 09:59:29.062  5689  5689 V BluetoothAdapterState: isTurningOff()=false
09-28 09:59:29.062  5689  5689 V BluetoothAdapterState: isTurningOn()=true
09-28 09:59:29.062  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:29.062  5689  5689 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 09:59:29.062  5689  5689 V BluetoothAdapterState: isTurningOff()=false
09-28 09:59:29.062  5689  5689 V BluetoothAdapterState: isTurningOn()=true
09-28 09:59:29.062  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:29.062  5689  5825 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-28 09:59:29.062  5689  5689 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 09:59:29.063  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 09:59:29.063  5689  5689 V BluetoothAdapterState: isTurningOff()=false
09-28 09:59:29.063  5689  5689 V BluetoothAdapterState: isTurningOn()=true
09-28 09:59:29.063  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:29.063  5689  5689 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:29.063  5689  5689 V BluetoothAdapterState: isTurningOff()=false
09-28 09:59:29.063  5689  5689 V BluetoothAdapterState: isTurningOn()=true
09-28 09:59:29.063  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:29.063  5689  5689 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:29.063  5689  5689 V BluetoothAdapterState: isTurningOff()=false
,09-28 09:59:29.064  5689  5689 V BluetoothAdapterState: isTurningOn()=true
09-28 09:59:29.064  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:29.064  5689  5689 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:29.064  5689  5689 V BluetoothAdapterState: isTurningOff()=false
09-28 09:59:29.064  5689  5689 V BluetoothAdapterState: isTurningOn()=true
09-28 09:59:29.064  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:29.064  5689  5689 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:29.065  5689  5689 V BluetoothAdapterState: isTurningOff()=false
09-28 09:59:29.065  5689  5689 V BluetoothAdapterState: isTurningOn()=true
09-28 09:59:29.065  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 09:59:29.065  5689  5689 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 09:59:29.065  5689  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-28 09:59:29.065  5689  5807 D BluetoothAdapterProperties: ScanMode =  20
09-28 09:59:29.065  5689  5807 D BluetoothAdapterProperties: State =  11
,09-28 09:59:29.069  5689  5811 D BluetoothAdapterProperties: Scan Mode:21
,09-28 09:59:29.069  5689  5807 D BluetoothAdapterProperties: Setting state to 12
09-28 09:59:29.069  5689  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-28 09:59:29.070  5689  5807 I BluetoothAdapterState: Entering OnState
,09-28 09:59:29.070  5623  5641 D BluetoothMap: onBluetoothStateChange: up=true
09-28 09:59:29.070  5689  5811 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 09:59:29.070   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 09:59:29.071  3113  3939 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 09:59:29.071  3113  3337 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-28 09:59:29.074  3113  3113 D BluetoothInputDevice: Proxy object connected
09-28 09:59:29.074  3113  3125 D BluetoothMap: onBluetoothStateChange: up=true
09-28 09:59:29.074  3113  3113 D HidProfile: Bluetooth service connected
09-28 09:59:29.076  3113  3337 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 09:59:29.076  3113  3113 D BluetoothMap: Proxy object connected
09-28 09:59:29.076  3113  3113 D MapProfile: Bluetooth service connected
09-28 09:59:29.076  3113  3113 D BluetoothMap: getConnectedDevices()
09-28 09:59:29.077  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:29.077  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:29.077  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:29.077  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:29.077  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:59:29.077  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:29.077  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:29.077  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:29.077  5689  5689 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 09:59:29.077  3113  3126 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 09:59:29.078  5689  5689 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-28 09:59:29.079  5689  5689 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 09:59:29.079  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:29.080   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 09:59:29.081   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 09:59:29.081  5623  5640 D BluetoothPan: onBluetoothStateChange on: true
,09-28 09:59:29.082  5623  5641 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 09:59:29.083  3113  3939 D BluetoothPan: onBluetoothStateChange on: true
09-28 09:59:29.083  5689  5689 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 09:59:29.083  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:29.083  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:29.083  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:29.083  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:29.083  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:59:29.083  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:29.083  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:29.083  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:29.084  3113  3113 D BluetoothPan: BluetoothPAN Proxy object connected
,09-28 09:59:29.085  3113  3113 D PanProfile: Bluetooth service connected
09-28 09:59:29.085  3759  3774 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 09:59:29.085   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 09:59:29.085  5623  5640 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 09:59:29.085  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:29.086  5689  5689 D ObexServerSockets: Succeed to create listening sockets 
09-28 09:59:29.086  5689  5689 D ObexServerSockets0: startAccept()
09-28 09:59:29.086  5689  5689 D ObexServerSockets0: prepareForNewConnect()
09-28 09:59:29.087   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-28 09:59:29.088  5689  5689 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-28 09:59:29.088  5689  5689 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-28 09:59:29.090  5689  5835 D ObexServerSockets0: Accepting socket connection...
,09-28 09:59:29.090  5689  5834 D ObexServerSockets0: Accepting socket connection...
,09-28 09:59:29.090   929   929 D BluetoothA2dp: Proxy object connected
09-28 09:59:29.091  5689  5689 D BluetoothMapService: onReceive
09-28 09:59:29.091  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:29.091  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:29.091  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:29.091  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:29.091  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:59:29.091  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:29.091  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:29.091  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:29.091  3113  3113 D BluetoothA2dp: Proxy object connected
09-28 09:59:29.091  5689  5689 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 09:59:29.091  5689  5689 D BluetoothMapService: STATE_ON
09-28 09:59:29.092  5623  5623 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-28 09:59:29.095  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:29.096  5689  5837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 09:59:29.096  5623  5623 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-28 09:59:29.096  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:29.097  5689  5837 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-28 09:59:29.097  5689  5837 D BluetoothSdpJni: SDP Create record success - handle: 1
09-28 09:59:29.098  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:29.099  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:29.105  5623  5623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 09:59:29.108  5623  5623 D BluetoothA2dp: Proxy object connected
,09-28 09:59:29.112  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 09:59:29.116  5623  5623 D DockEventReceiver: finishStartingService: stopping service
,09-28 09:59:29.119  3113  3113 D BluetoothPbap: Proxy object connected
09-28 09:59:29.119  3113  3113 D PbapServerProfile: Bluetooth service connected
,09-28 09:59:29.119  5623  5623 D BluetoothPbap: Proxy object connected
,09-28 09:59:29.120  5623  5623 D PbapServerProfile: Bluetooth service connected
09-28 09:59:29.122  5689  5689 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 09:59:29.122  5689  5689 D ObexServerSockets0: prepareForNewConnect()
,09-28 09:59:29.130  5689  5842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 09:59:29.145  5689  5846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 09:59:29.146  5689  5846 I BtOppRfcommListener: Accept thread started.
,09-28 09:59:29.171  3759  3776 D BluetoothHeadset: Proxy object connected
,09-28 09:59:29.172  3113  3337 D BluetoothHeadset: Proxy object connected
,09-28 09:59:29.172  3113  3939 D BluetoothHeadset: Proxy object connected
09-28 09:59:29.172  3113  3113 D HeadsetProfile: Bluetooth service connected
09-28 09:59:29.172   929   929 D BluetoothHeadset: Proxy object connected
09-28 09:59:29.172   929   929 D BluetoothHeadset: Proxy object connected
09-28 09:59:29.172   929   929 D BluetoothHeadset: Proxy object connected
,09-28 09:59:29.174  3113  3113 D HeadsetProfile: Bluetooth service connected
,09-28 09:59:29.181   929   946 D BluetoothHeadset: Proxy object connected
,09-28 09:59:29.186  3759  5646 D BluetoothHeadset: Proxy object connected
09-28 09:59:29.186   929   946 D BluetoothHeadset: Proxy object connected
,09-28 09:59:29.199  5623  5641 D BluetoothHeadset: Proxy object connected
09-28 09:59:29.200  5623  5623 D HeadsetProfile: Bluetooth service connected
,09-28 09:59:29.436   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:30.437   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 09:59:30.839   929  2946 D ConnectivityService: handlePromptUnvalidated 101
,09-28 09:59:33.089  5689  5807 D BluetoothAdapterState: Current state: ON, message: 23
,09-28 09:59:33.090  5689  5807 D BluetoothAdapterProperties: Setting state to 13
09-28 09:59:33.090  5689  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-28 09:59:33.092  5689  5807 D BluetoothAdapterProperties: onBluetoothDisable()
,09-28 09:59:33.098  5689  5689 D BluetoothMapService: onReceive
,09-28 09:59:33.098  5689  5807 I BluetoothAdapterState: Entering PendingCommandState
,09-28 09:59:33.098  5689  5689 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-28 09:59:33.098  5689  5689 D BluetoothMapService: STATE_TURNING_OFF
09-28 09:59:33.099  5689  5689 D BluetoothMapService: MAP Service closeService in
09-28 09:59:33.099  5689  5689 D BluetoothMapMasInstance0: MAP Service shutdown
09-28 09:59:33.099  5689  5689 D ObexServerSockets0: shutdown(block = true)
09-28 09:59:33.100  5689  5689 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 09:59:33.100  5689  5689 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 09:59:33.100  5689  5822 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-28 09:59:33.100  5689  5835 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-28 09:59:33.101  5689  5834 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-28 09:59:33.102  5689  5689 I BtOppRfcommListener: stopping Accept Thread
09-28 09:59:33.103  5689  5846 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-28 09:59:33.103  5623  5623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 09:59:33.103  5689  5846 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-28 09:59:33.103  5689  5811 D BluetoothAdapterProperties: Scan Mode:20
09-28 09:59:33.104  5689  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-28 09:59:33.104  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:33.104  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:33.104  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:33.104  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:33.104  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:33.104  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:33.104  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:33.104  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:33.104  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:33.105  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:33.106  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:33.111  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:33.111  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:33.111  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:33.111  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:33.111  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:33.111  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:33.111  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:33.111  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:33.111  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:33.112  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 09:59:33.113  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:33.113  5623  5623 D DockEventReceiver: finishStartingService: stopping service
09-28 09:59:33.115  5689  5689 D HeadsetService: Received stop request...Stopping profile...
09-28 09:59:33.116  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:33.116  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:33.116  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:33.116  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:33.116  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:33.116  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:59:33.116  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:33.116  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:33.116  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:33.118  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:59:33.118  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:33.118  3759  3959 D BluetoothHeadset: Proxy object disconnected
,09-28 09:59:33.119  3113  3125 D BluetoothHeadset: Proxy object disconnected
09-28 09:59:33.119   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 09:59:33.120  5623  5640 D BluetoothHeadset: Proxy object disconnected
09-28 09:59:33.120  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:33.120   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 09:59:33.121   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 09:59:33.121  5689  5689 D A2dpService: Received stop request...Stopping profile...
,09-28 09:59:33.121  5689  5829 D A2dpStateMachine: Exit Disconnected: -1
09-28 09:59:33.121  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:33.122   929   929 D BluetoothA2dp: Proxy object disconnected
,09-28 09:59:33.123  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:33.124  5689  5689 D HidService: Received stop request...Stopping profile...
09-28 09:59:33.124  5689  5689 D HidService: Stopping Bluetooth HidService
09-28 09:59:33.125  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 09:59:33.126  5623  5623 D HeadsetProfile: Bluetooth service disconnected
09-28 09:59:33.126  5689  5689 D HealthService: Received stop request...Stopping profile...
09-28 09:59:33.126  5623  5623 D BluetoothA2dp: Proxy object disconnected
09-28 09:59:33.127  5623  5623 D BluetoothInputDevice: Proxy object disconnected
09-28 09:59:33.127  5623  5623 D HidProfile: Bluetooth service disconnected
09-28 09:59:33.128  5689  5689 D PanService: Received stop request...Stopping profile...
,09-28 09:59:33.131  5689  5689 D BluetoothMapService: Received stop request...Stopping profile...
,09-28 09:59:33.129  5623  5623 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 09:59:33.127  3113  3113 D HeadsetProfile: Bluetooth service disconnected
09-28 09:59:33.135  5689  5689 D BluetoothMapService: stop()
09-28 09:59:33.135  5623  5623 D PanProfile: Bluetooth service disconnected
09-28 09:59:33.135  3113  3113 D BluetoothA2dp: Proxy object disconnected
09-28 09:59:33.135  3113  3113 D BluetoothInputDevice: Proxy object disconnected
09-28 09:59:33.135  3113  3113 D HidProfile: Bluetooth service disconnected
09-28 09:59:33.135  3113  3113 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 09:59:33.136  3113  3113 D PanProfile: Bluetooth service disconnected
,09-28 09:59:33.136  5689  5689 D BluetoothMapAppObserver: deinitObservers()
,09-28 09:59:33.136  5689  5689 D BluetoothMapAppObserver: removeReceiver()
09-28 09:59:33.137  3113  3113 D BluetoothMap: Proxy object disconnected
09-28 09:59:33.138  3113  3113 D MapProfile: Bluetooth service disconnected
09-28 09:59:33.138  5689  5689 V BluetoothAdapterState: isTurningOff()=true
09-28 09:59:33.138  5689  5689 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:33.138  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:33.138  5623  5623 D BluetoothMap: Proxy object disconnected
,09-28 09:59:33.138  5689  5689 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:33.138  5623  5623 D MapProfile: Bluetooth service disconnected
,09-28 09:59:33.140  5689  5689 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-28 09:59:33.140  5689  5689 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-28 09:59:33.140  5689  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:59:33.140  5689  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-28 09:59:33.140  5689  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-28 09:59:33.140  5689  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-28 09:59:33.140  5689  5811 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-28 09:59:33.140  5689  5689 D SapService: Received stop request...Stopping profile...
09-28 09:59:33.140  5689  5689 V SapService: stop()
09-28 09:59:33.142  5689  5689 V BluetoothAdapterState: isTurningOff()=true
09-28 09:59:33.142  5689  5689 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:33.142  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:33.142  5689  5689 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:33.143  5689  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:59:33.143  5689  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:59:33.144  5689  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-28 09:59:33.144  5689  5820 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 09:59:33.144  5689  5820 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 09:59:33.144  5689  5820 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 09:59:33.144  5689  5820 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 09:59:33.145  5689  5689 V BluetoothAdapterState: isTurningOff()=true
09-28 09:59:33.145  5689  5689 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:33.145  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:33.145  5689  5689 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:33.145  3113  3113 D BluetoothPbap: Proxy object disconnected
09-28 09:59:33.145  5689  5689 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-28 09:59:33.145  5689  5689 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-28 09:59:33.146  5623  5623 D BluetoothPbap: Proxy object disconnected
09-28 09:59:33.146  5623  5623 D PbapServerProfile: Bluetooth service disconnected
09-28 09:59:33.146  5689  5689 V BluetoothAdapterState: isTurningOff()=true
09-28 09:59:33.146  5689  5689 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:33.146  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:33.146  5689  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 09:59:33.146  5689  5689 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:33.147  5689  5689 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-28 09:59:33.148  5689  5811 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-28 09:59:33.148  5689  5689 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-28 09:59:33.148  5689  5689 V BluetoothAdapterState: isTurningOff()=true
09-28 09:59:33.148  5689  5689 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:33.148  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:33.148  5689  5689 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:33.148  5689  5689 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-28 09:59:33.148  5689  5689 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-28 09:59:33.145  3113  3113 D PbapServerProfile: Bluetooth service disconnected
09-28 09:59:33.149  5689  5689 D BluetoothMapService: MAP Service closeService in
09-28 09:59:33.149  5689  5689 V BluetoothAdapterState: isTurningOff()=true
09-28 09:59:33.150  5689  5689 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:33.150  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:33.150  5689  5689 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:33.150  5689  5689 D BluetoothMapService: cleanup()
09-28 09:59:33.150  5689  5689 D BluetoothMapService: MAP Service closeService in
09-28 09:59:33.150  5689  5689 V BluetoothAdapterState: isTurningOff()=true
09-28 09:59:33.150  5689  5689 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:33.150  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:33.150  5689  5689 V BluetoothAdapterState: isBleTurningOff(,)=false
09-28 09:59:33.151  5689  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-28 09:59:33.151  5689  5807 D BluetoothAdapterProperties: Setting state to 15
09-28 09:59:33.151  5689  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-28 09:59:33.152  5689  5807 I BluetoothAdapterState: Entering BleOnState
09-28 09:59:33.152  5623  5641 D BluetoothMap: onBluetoothStateChange: up=false
,09-28 09:59:33.153  5623  5640 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-28 09:59:33.154   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:59:33.154  3113  3125 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:59:33.154  3113  3126 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 09:59:33.156  3113  3939 D BluetoothMap: onBluetoothStateChange: up=false
09-28 09:59:33.156  3113  3337 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 09:59:33.157  3113  3125 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-28 09:59:33.158   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 09:59:33.158   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:59:33.158  5623  5641 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:59:33.158  5623  5640 D BluetoothPan: onBluetoothStateChange on: false
09-28 09:59:33.159  5623  5641 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 09:59:33.159  3113  3126 D BluetoothPan: onBluetoothStateChange on: false
09-28 09:59:33.160  3759  3774 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:59:33.160   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-28 09:59:33.160  5623  5640 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 09:59:33.161  5689  5807 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-28 09:59:33.161  5689  5807 D BluetoothAdapterProperties: Setting state to 16
09-28 09:59:33.161  5689  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-28 09:59:33.162  5689  5807 D BluetoothAdapterProperties: onBleDisable
,09-28 09:59:33.162  5689  5807 I BluetoothAdapterState: Entering PendingCommandState
09-28 09:59:33.162  5689  5808 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-28 09:59:33.163  5689  5820 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-28 09:59:33.163  5689  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:59:33.164  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:33.164  5689  5811 D BluetoothAdapterProperties: Scan Mode:20
09-28 09:59:33.165  5623  5623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 09:59:33.166  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:33.167  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:33.169  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:33.170  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 09:59:33.171  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:33.172  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:33.173  5623  5623 D DockEventReceiver: finishStartingService: stopping service
,09-28 09:59:33.377  5689  5811 I bt_hci  : shut_down
,09-28 09:59:33.387  5689  5815 I bt_vendor: low_power_mode_cb
,09-28 09:59:33.387  5689  5815 D bt_hwcfg: hw_epilog_process
,09-28 09:59:33.390  5689  5815 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-28 09:59:33.391  5689  5815 I bt_vendor: epilog_cb
09-28 09:59:33.391  5689  5815 I bt_hci  : epilog_finished_callback
,09-28 09:59:33.395  5689  5811 I bt_hci_h4: hal_close
,09-28 09:59:33.396  5689  5811 I bt_userial_vendor: device fd = 54 close
,09-28 09:59:33.511  5689  5808 D bt_stack_manager: event_shut_down_stack finished.
,09-28 09:59:33.512  5689  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-28 09:59:33.516  5689  5807 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-28 09:59:33.516  5689  5689 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-28 09:59:33.519  5689  5689 D BtGatt.GattService: Received stop request...Stopping profile...
,09-28 09:59:33.519  5689  5689 D BtGatt.GattService: stop()
09-28 09:59:33.519  5689  5689 D BtGatt.AdvertiseManager: advertise clients cleared
,09-28 09:59:33.523  5689  5689 V BluetoothAdapterState: isTurningOff()=false
,09-28 09:59:33.523  5689  5689 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:33.523  5689  5689 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:33.523  5689  5689 V BluetoothAdapterState: isBleTurningOff()=true
,09-28 09:59:33.524  5689  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-28 09:59:33.524  5689  5807 D BluetoothAdapterProperties: Setting state to 10
09-28 09:59:33.524  5689  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-28 09:59:33.525  5689  5807 I BluetoothAdapterState: Entering OffState
,09-28 09:59:33.527   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-28 09:59:33.547  5689  5689 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-28 09:59:33.547  5689  5689 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-28 09:59:33.547  5689  5808 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-28 09:59:33.549  5689  5689 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-28 09:59:33.555  5689  5689 I art     : System.exit called, status: 0
,09-28 09:59:33.555  5689  5689 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-28 09:59:33.582   929   940 I ActivityManager: Process com.android.bluetooth (pid 5689) has died
,09-28 09:59:38.088  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 09:59:38.088  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:59:38.093  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:59:38.093  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1408dd2 removed from the list
09-28 09:59:38.093  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 09:59:38.094  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:38.094  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:38.096  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:59:38.096  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8a95a0 added. We now have 4 listener(s)
,09-28 09:59:38.097  5569  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 09:59:38.100  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:38.100  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8a95a0 removed from the list
,09-28 09:59:38.100  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:38.101  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:59:38.101  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:59:38.102  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 09:59:38.103  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@158a559 added. We now have 4 listener(s)
09-28 09:59:38.103  5569  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:59:43.113  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:43.146   929   946 I ActivityManager: Start proc 5854:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-28 09:59:43.231  5854  5854 D AdapterServiceConfig: Adding HeadsetService
,09-28 09:59:43.232  5854  5854 D AdapterServiceConfig: Adding A2dpService
09-28 09:59:43.232  5854  5854 D AdapterServiceConfig: Adding HidService
09-28 09:59:43.232  5854  5854 D AdapterServiceConfig: Adding HealthService
09-28 09:59:43.232  5854  5854 D AdapterServiceConfig: Adding PanService
09-28 09:59:43.232  5854  5854 D AdapterServiceConfig: Adding GattService
09-28 09:59:43.233  5854  5854 D AdapterServiceConfig: Adding BluetoothMapService
09-28 09:59:43.233  5854  5854 D AdapterServiceConfig: Adding SapService
,09-28 09:59:43.244   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a0794b7:true
,09-28 09:59:43.244  5854  5854 D BluetoothAdapterState: make() - Creating AdapterState
,09-28 09:59:43.247  5854  5854 I bt_bluedroid: init
,09-28 09:59:43.247  5854  5866 I BluetoothAdapterState: Entering OffState
,09-28 09:59:43.249  5854  5867 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-28 09:59:43.249  5854  5867 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-28 09:59:43.250  5854  5867 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-28 09:59:43.250  5854  5867 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-28 09:59:43.250  5854  5854 I bt_bluedroid: get_profile_interface socket
,09-28 09:59:43.252  5854  5854 I bt_bluedroid: get_profile_interface sdp
,09-28 09:59:43.252  5854  5870 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-28 09:59:43.254  5854  5870 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 09:59:43.262  5854  5865 I bt_bluedroid: config_hci_snoop_log
,09-28 09:59:43.263   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-28 09:59:43.268  5854  5866 D BluetoothAdapterState: Current state: OFF, message: 0
,09-28 09:59:43.268  5854  5866 D BluetoothAdapterProperties: Setting state to 14
09-28 09:59:43.268  5854  5866 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-28 09:59:43.270  5854  5866 D BluetoothBondStateMachine: make
09-28 09:59:43.272  5854  5871 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-28 09:59:43.275  5854  5866 I BluetoothAdapterState: Entering PendingCommandState
,09-28 09:59:43.276  5854  5854 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-28 09:59:43.279  5854  5854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
09-28 09:59:43.279  5854  5854 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 09:59:43.280  5854  5854 D BtGatt.GattService: Received start request. Starting profile...
09-28 09:59:43.280  5854  5854 D BtGatt.GattService: start()
09-28 09:59:43.280  5854  5854 I bt_bluedroid: get_profile_interface gatt
,09-28 09:59:43.281  5854  5854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
09-28 09:59:43.282  5854  5854 D BtGatt.AdvertiseManager: advertise manager created
,09-28 09:59:43.288  5854  5854 V BluetoothAdapterState: isTurningOff()=false
,09-28 09:59:43.288  5854  5854 V BluetoothAdapterState: isTurningOn()=false
09-28 09:59:43.288  5854  5854 V BluetoothAdapterState: isBleTurningOn()=true
09-28 09:59:43.288  5854  5854 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:43.289  5854  5866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-28 09:59:43.290  5854  5866 I bt_bluedroid: bt_bluedroid
09-28 09:59:43.290  5854  5867 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-28 09:59:43.291  5854  5867 I bt_hci  : start_up
,09-28 09:59:43.296  5854  5867 I bt_vendor: alloc value 0xf403d871
09-28 09:59:43.296  5854  5867 I bt_vendor: init
,09-28 09:59:43.296  5854  5867 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-28 09:59:43.296  5854  5867 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-28 09:59:43.404  5854  5867 D bt_hci  : start_up starting async portion
,09-28 09:59:43.405  5854  5874 I bt_hci  : event_finish_startup
,09-28 09:59:43.405  5854  5874 I bt_hci_h4: hal_open
,09-28 09:59:43.405  5854  5874 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-28 09:59:43.403  5875  5875 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-28 09:59:43.409  5854  5874 I bt_userial_vendor: device fd = 54 open
,09-28 09:59:43.427  5854  5874 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 09:59:43.430  5854  5874 D bt_hwcfg: Chipset BCM4358A3
,09-28 09:59:43.430  5854  5874 D bt_hwcfg: Target name = [BCM4358A3]
09-28 09:59:43.431  5854  5874 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-28 09:59:43.949  5854  5874 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-28 09:59:43.950  5854  5874 D bt_hwcfg: Settlement delay -- 100 ms
09-28 09:59:43.950  5854  5874 I bt_hwcfg: Setting fw settlement delay to 100 
,09-28 09:59:44.086  5854  5874 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-28 09:59:44.086  5854  5874 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-28 09:59:44.088  5854  5874 I bt_hwcfg: vendor lib fwcfg completed
09-28 09:59:44.089  5854  5874 I bt_vendor: firmware callback
09-28 09:59:44.089  5854  5874 I bt_hci  : firmware_config_callback
,09-28 09:59:44.099  5854  5877 I bt_btu  : btu_task pending for preload complete event
09-28 09:59:44.099  5854  5877 I bt_btu_task: Bluetooth chip preload is complete
09-28 09:59:44.099  5854  5877 I bt_btu  : btu_task received preload complete event
,09-28 09:59:44.106  5854  5877 I         : BTE_InitTraceLevels -- TRC_HCI
09-28 09:59:44.106  5854  5877 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-28 09:59:44.106  5854  5877 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-28 09:59:44.107  5854  5877 I         : BTE_InitTraceLevels -- TRC_AVDT
09-28 09:59:44.107  5854  5877 I         : BTE_InitTraceLevels -- TRC_AVRC
09-28 09:59:44.107  5854  5877 I         : BTE_InitTraceLevels -- TRC_A2D
09-28 09:59:44.107  5854  5877 I         : BTE_InitTraceLevels -- TRC_BNEP
09-28 09:59:44.107  5854  5877 I         : BTE_InitTraceLevels -- TRC_BTM
,09-28 09:59:44.107  5854  5877 I         : BTE_InitTraceLevels -- TRC_GAP
09-28 09:59:44.107  5854  5877 I         : BTE_InitTraceLevels -- TRC_PAN
09-28 09:59:44.108  5854  5877 I         : BTE_InitTraceLevels -- TRC_SDP
09-28 09:59:44.108  5854  5877 I         : BTE_InitTraceLevels -- TRC_GATT
09-28 09:59:44.108  5854  5877 I         : BTE_InitTraceLevels -- TRC_SMP
,09-28 09:59:44.108  5854  5877 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-28 09:59:44.108  5854  5877 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-28 09:59:44.203  5854  5877 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fbb549
,09-28 09:59:44.203  5854  5877 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fbb549 
,09-28 09:59:44.230  5854  5870 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-28 09:59:44.232  5854  5870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-28 09:59:44.233  5854  5870 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 09:59:44.236  5854  5870 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 09:59:44.240  5854  5870 D BluetoothAdapterProperties: Scan Mode:20
,09-28 09:59:44.240  5854  5870 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 09:59:44.240  5854  5870 D bt_hci  : do_postload posting postload work item
09-28 09:59:44.241  5854  5874 I bt_hci  : event_postload
09-28 09:59:44.241  5854  5874 I bt_vendor: sco_config_cb
,09-28 09:59:44.241  5854  5874 I bt_hci  : sco_config_callback postload finished.
,09-28 09:59:44.244  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:44.245  5854  5870 D bt_bte_conf: Device ID record 1 : primary
09-28 09:59:44.245  5854  5870 D bt_bte_conf:   vendorId            = 000f
09-28 09:59:44.246  5854  5870 D bt_bte_conf:   vendorIdSource      = 0001
09-28 09:59:44.246  5854  5870 D bt_bte_conf:   product             = 1200
09-28 09:59:44.246  5854  5870 D bt_bte_conf:   version             = 1436
09-28 09:59:44.246  5854  5870 D bt_bte_conf:   clientExecutableURL = 
09-28 09:59:44.246  5854  5870 D bt_bte_conf:   serviceDescription  = 
09-28 09:59:44.246  5854  5870 D bt_bte_conf:   documentationURL    = 
09-28 09:59:44.246  5854  5870 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-28 09:59:44.246  5854  5867 D bt_stack_manager: event_start_up_stack finished
09-28 09:59:44.247  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:44.247  5854  5866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-28 09:59:44.247  5854  5866 D BluetoothAdapterProperties: Setting state to 15
09-28 09:59:44.247  5854  5866 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-28 09:59:44.249  5854  5866 I BluetoothAdapterState: Entering BleOnState
,09-28 09:59:44.250  5854  5874 I bt_vendor: low_power_mode_cb
,09-28 09:59:44.252  5854  5866 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-28 09:59:44.252  5854  5866 D BluetoothAdapterProperties: Setting state to 11
09-28 09:59:44.252  5854  5866 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-28 09:59:44.258  5854  5854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
,09-28 09:59:44.261  5854  5854 D HeadsetService: Received start request. Starting profile...
,09-28 09:59:44.264  5854  5854 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-28 09:59:44.264  5854  5854 D HeadsetStateMachine: make
09-28 09:59:44.265  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:44.267  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:44.279  5854  5854 D HeadsetStateMachine: max_hf_connections = 1
,09-28 09:59:44.280  5854  5854 I bt_bluedroid: get_profile_interface handsfree
09-28 09:59:44.281  5854  5870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-28 09:59:44.281  5854  5870 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-28 09:59:44.281  5854  5866 I BluetoothAdapterState: Entering PendingCommandState
,09-28 09:59:44.290  5854  5854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
09-28 09:59:44.291  5854  5854 D A2dpService: Received start request. Starting profile...
,09-28 09:59:44.292  5854  5854 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-28 09:59:44.292  5854  5854 I bt_bluedroid: get_profile_interface avrcp
,09-28 09:59:44.297  5854  5854 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-28 09:59:44.298  5854  5854 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-28 09:59:44.298  5854  5854 D A2dpStateMachine: make
,09-28 09:59:44.299  5854  5854 I bt_bluedroid: get_profile_interface a2dp
09-28 09:59:44.299  5854  5870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-28 09:59:44.305  5854  5884 D A2dpStateMachine: Enter Disconnected: -2
,09-28 09:59:44.306  5854  5854 I BluetoothHidServiceJni: classInitNative: succeeds
09-28 09:59:44.308  5854  5854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
,09-28 09:59:44.308  5854  5854 D HidService: Received start request. Starting profile...
,09-28 09:59:44.309  5854  5854 I bt_bluedroid: get_profile_interface hidhost
09-28 09:59:44.309  5854  5854 D HidService: setHidService(): set to: null
09-28 09:59:44.309  5854  5870 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f9c56d
09-28 09:59:44.309  5854  5870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-28 09:59:44.309  5854  5854 I BluetoothHealthServiceJni: classInitNative: succeeds
09-28 09:59:44.310  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 09:59:44.310  5854  5854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
,09-28 09:59:44.311  5854  5854 D HealthService: Received start request. Starting profile...
,09-28 09:59:44.313  5854  5854 I bt_bluedroid: get_profile_interface health
,09-28 09:59:44.315  5854  5854 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-28 09:59:44.316  5854  5854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
09-28 09:59:44.316  5854  5854 D PanService: Received start request. Starting profile...
09-28 09:59:44.316  5854  5854 D BluetoothPanServiceJni: initializeNative(L110): pan
09-28 09:59:44.316  5854  5854 I bt_bluedroid: get_profile_interface pan
09-28 09:59:44.317  5854  5870 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-28 09:59:44.319  5854  5854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
09-28 09:59:44.319  5854  5854 D BluetoothMapService: Received start request. Starting profile...
09-28 09:59:44.319  5854  5854 D BluetoothMapService: start()
,09-28 09:59:44.323  5854  5854 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-28 09:59:44.323  5854  5854 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-28 09:59:44.323  5854  5854 D BluetoothMapAppObserver: createReceiver()
09-28 09:59:44.325  5854  5854 D BluetoothMapAppObserver: initObservers()
09-28 09:59:44.325  5854  5854 D BluetoothMapAppObserver: getEnabledAccountItems()
09-28 09:59:44.331  5854  5854 V SapService: SapBinder()
,09-28 09:59:44.331  5854  5854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
,09-28 09:59:44.332  5854  5854 D SapService: Received start request. Starting profile...
,09-28 09:59:44.332  5854  5854 V SapService: start()
09-28 09:59:44.333  5854  5854 V BluetoothAdapterState: isTurningOff()=false
09-28 09:59:44.333  5854  5854 V BluetoothAdapterState: isTurningOn()=true
09-28 09:59:44.333  5854  5882 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-28 09:59:44.333  5854  5854 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:44.334  5854  5854 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 09:59:44.334  5854  5854 V BluetoothAdapterState: isTurningOff()=false
09-28 09:59:44.334  5854  5854 V BluetoothAdapterState: isTurningOn()=true
09-28 09:59:44.334  5854  5854 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:44.334  5854  5854 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:44.335  5854  5854 V BluetoothAdapterState: isTurningOff()=false
09-28 09:59:44.335  5854  5854 V BluetoothAdapterState: isTurningOn()=true
09-28 09:59:44.335  5854  5854 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:44.335  5854  5854 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:44.335  5854  5854 V BluetoothAdapterState: isTurningOff()=false
09-28 09:59:44.336  5854  5854 V BluetoothAdapterState: isTurningOn()=true
09-28 09:59:44.336  5854  5854 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:44.336  5854  5854 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:44.336  5854  5854 V BluetoothAdapterState: isTurningOff()=false
,09-28 09:59:44.336  5854  5854 V BluetoothAdapterState: isTurningOn()=true
09-28 09:59:44.336  5854  5854 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:44.336  5854  5854 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:44.336  5854  5854 V BluetoothAdapterState: isTurningOff()=false
09-28 09:59:44.336  5854  5854 V BluetoothAdapterState: isTurningOn()=true
09-28 09:59:44.336  5854  5854 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:44.337  5854  5854 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:59:44.338  5854  5854 V BluetoothAdapterState: isTurningOff()=false
09-28 09:59:44.338  5854  5854 V BluetoothAdapterState: isTurningOn()=true
09-28 09:59:44.338  5854  5854 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:59:44.338  5854  5854 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 09:59:44.338  5854  5866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-28 09:59:44.338  5854  5866 D BluetoothAdapterProperties: ScanMode =  20
09-28 09:59:44.338  5854  5866 D BluetoothAdapterProperties: State =  11
,09-28 09:59:44.339  5854  5866 D BluetoothAdapterProperties: Setting state to 12
09-28 09:59:44.339  5854  5866 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-28 09:59:44.339  5854  5866 I BluetoothAdapterState: Entering OnState
09-28 09:59:44.339  5623  5641 D BluetoothMap: onBluetoothStateChange: up=true
09-28 09:59:44.340  5854  5870 D BluetoothAdapterProperties: Scan Mode:21
09-28 09:59:44.340  5854  5870 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-28 09:59:44.341  5623  5640 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-28 09:59:44.343   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 09:59:44.343  3113  3939 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 09:59:44.344  3113  3126 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 09:59:44.344  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:44.344  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:44.344  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:44.344  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:44.344  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:59:44.344  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:44.344  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:44.344  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:44.346  3113  3337 D BluetoothMap: onBluetoothStateChange: up=true
,09-28 09:59:44.346  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:44.346  3113  3113 D BluetoothInputDevice: Proxy object connected
09-28 09:59:44.346  3113  3113 D HidProfile: Bluetooth service connected
,09-28 09:59:44.347  3113  3939 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 09:59:44.348  5623  5623 D BluetoothMap: Proxy object connected
09-28 09:59:44.348  5623  5623 D MapProfile: Bluetooth service connected
09-28 09:59:44.348  5623  5623 D BluetoothMap: getConnectedDevices()
09-28 09:59:44.348  3113  3113 D BluetoothMap: Proxy object connected
09-28 09:59:44.349  3113  3113 D MapProfile: Bluetooth service connected
09-28 09:59:44.349  3113  3113 D BluetoothMap: getConnectedDevices()
,09-28 09:59:44.350  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:44.350  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:44.350  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:44.350  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:44.350  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:59:44.350  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:44.350  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:44.350  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:59:44.350  3113  3337 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 09:59:44.350  5854  5854 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 09:59:44.351  5854  5854 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-28 09:59:44.352  3113  3113 D BluetoothA2dp: Proxy object connected
09-28 09:59:44.352  5623  5623 D BluetoothA2dp: Proxy object connected
09-28 09:59:44.352  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 09:59:44.353   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 09:59:44.353  5854  5854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 09:59:44.353   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 09:59:44.353   929   929 D BluetoothA2dp: Proxy object connected
,09-28 09:59:44.354  5623  5640 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 09:59:44.355  5854  5854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 09:59:44.356  5623  5641 D BluetoothPan: onBluetoothStateChange on: true
,09-28 09:59:44.356  5854  5854 D ObexServerSockets: Succeed to create listening sockets 
09-28 09:59:44.356  5854  5854 D ObexServerSockets0: startAccept()
09-28 09:59:44.356  5854  5854 D ObexServerSockets0: prepareForNewConnect()
09-28 09:59:44.358  5854  5854 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-28 09:59:44.358  5854  5854 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-28 09:59:44.360  5854  5893 D ObexServerSockets0: Accepting socket connection...
09-28 09:59:44.360  5854  5894 D ObexServerSockets0: Accepting socket connection...
,09-28 09:59:44.361  5623  5889 D BluetoothPbap: onBluetoothStateChange: up=true
,09-28 09:59:44.361  5623  5623 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 09:59:44.361  5623  5623 D PanProfile: Bluetooth service connected
09-28 09:59:44.363  3113  3337 D BluetoothPan: onBluetoothStateChange on: true
,09-28 09:59:44.364  3759  3776 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 09:59:44.364  3113  3113 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 09:59:44.364  3113  3113 D PanProfile: Bluetooth service connected
09-28 09:59:44.364   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 09:59:44.365  5623  5640 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 09:59:44.367  5623  5623 D BluetoothInputDevice: Proxy object connected
09-28 09:59:44.367  5623  5623 D HidProfile: Bluetooth service connected
09-28 09:59:44.368  5854  5854 D BluetoothMapService: onReceive
09-28 09:59:44.368   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-28 09:59:44.368  5854  5854 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 09:59:44.368  5854  5854 D BluetoothMapService: STATE_ON
,09-28 09:59:44.369  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:44.371  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:44.371  5854  5895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 09:59:44.373  5854  5895 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-28 09:59:44.373  5854  5895 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-28 09:59:44.375  5623  5623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 09:59:44.378  5623  5623 D DockEventReceiver: finishStartingService: stopping service
,09-28 09:59:44.382  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 09:59:44.389  5623  5623 D BluetoothPbap: Proxy object connected
,09-28 09:59:44.389  5623  5623 D PbapServerProfile: Bluetooth service connected
,09-28 09:59:44.393  5854  5854 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-28 09:59:44.393  5854  5854 D ObexServerSockets0: prepareForNewConnect()
09-28 09:59:44.394  3113  3113 D BluetoothPbap: Proxy object connected
09-28 09:59:44.394  3113  3113 D PbapServerProfile: Bluetooth service connected
09-28 09:59:44.394  5854  5899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 09:59:44.412  5854  5903 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 09:59:44.414  5854  5903 I BtOppRfcommListener: Accept thread started.
,09-28 09:59:44.446  3759  5646 D BluetoothHeadset: Proxy object connected
,09-28 09:59:44.446  3113  3126 D BluetoothHeadset: Proxy object connected
09-28 09:59:44.446   929   929 D BluetoothHeadset: Proxy object connected
09-28 09:59:44.446  3113  3113 D HeadsetProfile: Bluetooth service connected
09-28 09:59:44.447  5623  5889 D BluetoothHeadset: Proxy object connected
09-28 09:59:44.447   929   929 D BluetoothHeadset: Proxy object connected
,09-28 09:59:44.447   929   929 D BluetoothHeadset: Proxy object connected
,09-28 09:59:44.449  5623  5623 D HeadsetProfile: Bluetooth service connected
,09-28 09:59:44.454   929   946 D BluetoothHeadset: Proxy object connected
,09-28 09:59:44.455  5623  5641 D BluetoothHeadset: Proxy object connected
,09-28 09:59:44.456  5623  5623 D HeadsetProfile: Bluetooth service connected
,09-28 09:59:44.465  3759  3959 D BluetoothHeadset: Proxy object connected
,09-28 09:59:44.465   929   946 D BluetoothHeadset: Proxy object connected
,09-28 09:59:48.129  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:48.129  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:48.129  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:48.129  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:59:48.129  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:59:48.129  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:48.129  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:48.129  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 09:59:48.136  5569  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:48.137  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:59:48.137  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@158a559 removed from the list
09-28 09:59:48.137  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:48.137  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:59:48.137  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:59:48.139  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:59:48.140  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f5b51e added. We now have 4 listener(s)
09-28 09:59:48.140  5569  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:59:48.144   929   940 D WifiService: setWifiEnabled: false pid=5569, uid=10077
09-28 09:59:48.145   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 09:59:50.438   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:51.439   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:52.441   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:53.155  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:53.156   929  3853 D WifiService: setWifiEnabled: true pid=5569, uid=10077
,09-28 09:59:53.156   929  3853 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 09:59:53.163   509   923 D SoftapController: Softap fwReload - Ok
,09-28 09:59:53.170   509   923 D CommandListener: Setting iface cfg
,09-28 09:59:53.171   509   923 D CommandListener: Trying to bring down wlan0
09-28 09:59:53.172   509   923 D CommandListener: Clearing all IP addresses on wlan0
,09-28 09:59:53.178   929  2944 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 09:59:53.443   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:53.860   929  2944 D wifi    : set interface wlan0 flags (UP)
,09-28 09:59:53.860   929  2944 I WifiHAL : Initializing wifi
,09-28 09:59:53.860   929  2944 I WifiHAL : Creating socket
,09-28 09:59:53.869   929  2944 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-28 09:59:53.869   929  2944 D wifi    : Did set static halHandle = 0x7f61467400
09-28 09:59:53.869   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-28 09:59:53.869   929  2944 D wifi    : halHandle = 0x7f61467400, mVM = 0x7f7da4d140, mCls = 0x20158a
09-28 09:59:53.869   929  2944 D wifi    : array field set
09-28 09:59:53.870   929  2944 I WifiNative-HAL: interface[0] = wlan0
09-28 09:59:53.872   929  5908 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547092853760
,09-28 09:59:53.872   929  5908 D wifi    : waitForHalEvents called, vm = 0x7f7da4d140, obj = 0x20158a, env = 0x7f622dd480
,09-28 09:59:53.874   929  2944 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-28 09:59:53.876   929  2944 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-28 09:59:53.880  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:59:53.883  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:59:53.920  5909  5909 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-28 09:59:53.940  5909  5909 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 09:59:53.980  5909  5909 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 09:59:53.980  5909  5909 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-28 09:59:54.446   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:59:54.898   929  2944 D WifiConfigStore: Loading config and enabling all networks 
,09-28 09:59:54.901  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:54.901  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:54.901  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:54.901  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:54.901  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:59:54.901  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:54.901  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:54.901  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 09:59:54.906  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 09:59:54.915  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:54.915  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:54.915  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:54.915  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:54.915  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:59:54.915  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:54.915  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:54.915  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 09:59:54.919  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 09:59:54.921   929  2944 D WifiConfigStore: loaded 0 passpoint configs
09-28 09:59:54.921   929  2944 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-28 09:59:54.922   929  2944 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-28 09:59:54.923   929  2944 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-28 09:59:54.924   929  2944 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-28 09:59:54.925   929  2944 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-28 09:59:54.925   929  2944 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-28 09:59:54.925   929  2944 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-28 09:59:54.929   929  2944 D WifiNative-HAL: Setting external_sim to 1
,09-28 09:59:54.930  4964  4964 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 09:59:54.930   929  2944 D wifi    : setting dfs flag to true, 0x7f6343f840
09-28 09:59:54.931   929  2944 D WifiStateMachine: Setting OUI to DA-A1-19
,09-28 09:59:54.931   929  2944 D wifi    : setting scan oui 0x7f6343f840
09-28 09:59:54.931   929  2944 D WifiHAL : Sending mac address OUI
,09-28 09:59:54.937   929  2944 E native  : do suspend false
,09-28 09:59:54.949   929  2944 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-28 09:59:54.950   929   929 D RttService: SCAN_AVAILABLE : 3
09-28 09:59:54.950   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-28 09:59:54.950   929  3054 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-28 09:59:54.954   509   923 D CommandListener: Setting iface cfg
,09-28 09:59:54.956   929  2942 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,09-28 09:59:54.956   929  2942 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-28 09:59:54.969   929  2942 D WifiNative-HAL: p2pGetDeviceAddress
09-28 09:59:54.969   929  2942 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-28 09:59:54.977   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303413 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=19 mControllerEnergyUsed=72 }
,09-28 09:59:55.447   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-28 09:59:58.142  5909  5909 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:59:58.153  5909  5909 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:59:58.158  5909  5909 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:59:58.165  5909  5909 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:59:58.169  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:58.169  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:58.169  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:58.169  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:58.169  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:59:58.169  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:59:58.169  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:59:58.169  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 09:59:58.172  5569  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:59:58.173  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:59:58.173  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f5b51e removed from the list
09-28 09:59:58.173  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:59:58.173  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:59:58.173  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:59:58.179  5569  5911 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-28 09:59:58.179  5569  5911 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-28 09:59:58.197   929  2944 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-28 09:59:58.198   929  2944 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-28 09:59:58.198   929  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 09:59:58.208   929  2944 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-28 09:59:58.246   929  2944 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-28 09:59:58.248  5909  5909 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-28 09:59:58.684  5909  5909 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-28 09:59:58.726  5909  5909 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-28 09:59:58.727  5909  5909 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-28 09:59:58.738   929  2944 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-28 09:59:58.739   929  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 09:59:58.739   929  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-28 09:59:58.758   929  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 09:59:58.772   509   923 D CommandListener: Setting iface cfg
,09-28 09:59:58.777   929  2944 D WifiStateMachine: Start Dhcp Watchdog 3
,09-28 09:59:58.786   929  5915 D DhcpClient: Receive thread started
,09-28 09:59:58.789   929  2944 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-28 09:59:58.789   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-28 09:59:58.789   929  2946 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-28 09:59:58.876   929  2944 E native  : do suspend false
,09-28 09:59:58.896   929  5914 D DhcpClient: Broadcasting DHCPDISCOVER
,09-28 09:59:58.909   929  5915 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,09-28 09:59:58.910   929  5914 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,09-28 09:59:58.913   929  5914 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-28 09:59:58.930   929  5915 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-28 09:59:58.931   929  5914 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-28 09:59:58.934   509   923 D CommandListener: Setting iface cfg
,09-28 09:59:58.938   929  2944 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-28 09:59:58.945   929  5914 D DhcpClient: Scheduling renewal in 86399s
,09-28 09:59:58.959   929  2944 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-28 09:59:58.959   929  2944 D WifiConfigStore: No blacklist allowed without epno enabled
09-28 09:59:58.960   929  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-28 09:59:58.962   929  2946 D ConnectivityService: Adding iface wlan0 to network 102
,09-28 09:59:58.968   929  2944 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-28 09:59:59.015   929  2946 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-28 09:59:59.016   929  2946 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-28 09:59:59.018   929  2946 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-28 09:59:59.021   929  2946 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-28 09:59:59.023   929  2946 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-28 09:59:59.035   929  2946 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 09:59:59.039   929  2946 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-28 09:59:59.040   929  2946 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-28 09:59:59.040   929  2946 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-28 09:59:59.040   929  2946 D ConnectivityService:    accepting network in place of null
,09-28 09:59:59.040   929  2944 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-28 09:59:59.040   929  2944 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 09:59:59.040   929  2946 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 09:59:59.064   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 09:59:59.071   929  5913 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307506, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 09:59:59.088   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 09:59:59.091   929  2946 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-28 09:59:59.091   929  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 09:59:59.091  3727  3880 W QCNEJ   : |CORE| network available: 102
,09-28 09:59:59.092   929  2946 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-28 09:59:59.094  3727  3880 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-28 09:59:59.095   929   946 D Tethering: MasterInitialState.processMessage what=3
09-28 09:59:59.096  3727  3880 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-28 09:59:59.096  3727  3880 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-28 09:59:59.104  4988  5010 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 09:59:59.109  4988  5010 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 09:59:59.106  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:59.106  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:59.106  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:59.106  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:59.106  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:59:59.106  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:59:59.106  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:59:59.106  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:59:59.109  4988  5010 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,09-28 09:59:59.109  4988  5010 E SarControlService: no key has been found,reset the power
09-28 09:59:59.109  4988  5025 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 09:59:59.109  4988  5025 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 09:59:59.109  4988  5025 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 09:59:59.110  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 09:59:59.110  5013  5013 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 09:59:59.108  3832  3832 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 09:59:59.111  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:59:59.112  4988  5025 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 09:59:59.112  4988  5025 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 09:59:59.112  4988  5025 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 09:59:59.112  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 09:59:59.112  5013  5013 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 09:59:59.115  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:59:59.115  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:59:59.115  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:59:59.115  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:59:59.115  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:59:59.115  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:59:59.115  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:59:59.115  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:59:59.116  3832  3832 D SystemUpdateService: onCreate
09-28 09:59:59.118  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:59:59.119  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3f2c3f HexData = [00000000f003000000000000ffffffff]
09-28 09:59:59.119  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:59:59.119  5013  5027 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,09-28 09:59:59.119  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:59:59.120  4988  4998 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 09:59:59.120  3832  3832 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-28 09:59:59.120  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3f2c3f HexData = [00000000f103000000000000ffffffff]
09-28 09:59:59.120  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:59:59.121  5013  5027 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-28 09:59:59.121  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:59:59.121  4988  4999 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-28 09:59:59.134  3832  3832 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-28 09:59:59.141   929  5912 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-28 09:59:59.144  3832  5345 I iu.UploadsManager: num queued entries: 0
,09-28 09:59:59.146  3832  5925 I SystemUpdateService: active receiver: enabled
,09-28 09:59:59.147  3832  3832 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 09:59:59.149  3832  3832 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 09:59:59.151  5703  5703 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 09:59:59.155  5703  5703 D SprintDMHelper: simOperator: 
09-28 09:59:59.155  5703  5703 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 09:59:59.167  3832  5345 I iu.UploadsManager: num updated entries: 0
,09-28 09:59:59.177  3832  5925 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 09:59:59.178  3832  5345 I iu.SyncManager: NEXT; no task
,09-28 09:59:59.189   929  5912 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 28 Sep 2016 13:59:59 GMT], X-Android-Received-Millis=[1475071199189], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475071199166]}
,09-28 09:59:59.190   929  2946 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 09:59:59.190   929  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-28 09:59:59.190   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-28 09:59:59.191   929  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-28 09:59:59.195  3832  5925 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-28 09:59:59.195  3832  5925 I SystemUpdateService: now status is 0 (complete)
09-28 09:59:59.195  3832  5925 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 09:59:59.195  3832  5925 I SystemUpdateService: file has been verified
09-28 09:59:59.195  3832  5925 I SystemUpdateService: OTA package size = 21989297
,09-28 09:59:59.202  3832  5925 I SystemUpdateService: showing system update notification
,09-28 09:59:59.213  3832  3832 D SystemUpdateService: onDestroy
,09-28 09:59:59.272  4964  5929 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-28 10:00:01.212  5569  5937 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-28 10:00:01.212  5569  5911 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-28 10:00:01.213  5569  5911 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-28 10:00:01.213  5569  5937 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-28 10:00:01.217  5569  5937 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 10:00:01.217  5569  5911 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:00:01.219  5569  5911 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:00:01.219  5569  5937 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 10:00:01.221  5569  5939 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: OutgoingSocketThread/Sender)
,09-28 10:00:01.222  5569  5911 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-28 10:00:01.223  5569  5937 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-28 10:00:01.223  5569  5940 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Sender)
,09-28 10:00:01.226  5569  5941 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: OutgoingSocketThread/Receiver)
,09-28 10:00:01.228  5569  5942 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: IncomingSocketThread/Receiver)
,09-28 10:00:01.228  5569  5941 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: OutgoingSocketThread/Receiver)
,09-28 10:00:01.229  5569  5941 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-28 10:00:01.229  5569  5941 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-28 10:00:01.230  5569  5942 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: IncomingSocketThread/Receiver)
09-28 10:00:01.230  5569  5942 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-28 10:00:01.231  5569  5942 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-28 10:00:01.811   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:00:04.186  5569  5616 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-28 10:00:04.187  5569  5616 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-28 10:00:04.193  5569  5616 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@29d0cd3 Bundle[{}]
,09-28 10:00:04.194  5569  5616 I io.jxcore.node.LifeCycleMonitor: start: OK
09-28 10:00:04.195  5569  5616 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-28 10:00:04.196  5569  5616 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-28 10:00:04.197  5569  5616 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-28 10:00:04.198  5569  5616 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-28 10:00:04.200  5569  5616 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-28 10:00:04.206  5569  5616 I System.out: Running OutgoingSocketThread
,09-28 10:00:04.209  5569  5943 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-28 10:00:04.209  5569  5943 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-28 10:00:07.045   929  2946 D ConnectivityService: handlePromptUnvalidated 102
,09-28 10:00:07.221  5569  5943 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-28 10:00:07.221  5569  5944 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-28 10:00:07.222  5569  5944 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-28 10:00:07.222  5569  5943 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-28 10:00:07.222  5569  5943 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:00:07.222  5569  5944 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 10:00:07.223  5569  5943 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:00:07.224  5569  5944 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:00:07.225  5569  5943 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-28 10:00:07.225  5569  5944 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-28 10:00:07.227  5569  5946 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: OutgoingSocketThread/Sender)
,09-28 10:00:07.229  5569  5947 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: IncomingSocketThread/Sender)
,09-28 10:00:07.231  5569  5948 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: OutgoingSocketThread/Receiver)
09-28 10:00:07.232  5569  5949 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: IncomingSocketThread/Receiver)
09-28 10:00:07.232  5569  5948 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: OutgoingSocketThread/Receiver)
,09-28 10:00:07.232  5569  5949 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 173, thread name: IncomingSocketThread/Receiver)
09-28 10:00:07.232  5569  5948 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-28 10:00:07.232  5569  5949 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-28 10:00:07.232  5569  5948 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-28 10:00:07.233  5569  5949 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 173, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-28 10:00:09.979   929  2944 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-28 10:00:10.218  5569  5616 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 182)
,09-28 10:00:10.220  5569  5616 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-28 10:00:10.220  5569  5616 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 183)
09-28 10:00:10.225  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:00:10.225  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90171ff added. We now have 3 listener(s)
,09-28 10:00:10.229  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:00:10.230  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:00:10.230  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:00:10.230  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:00:10.230  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@936bcc added. We now have 4 listener(s)
,09-28 10:00:10.230  5569  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:00:10.232  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 10:00:10.237  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:00:10.243  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:00:10.243  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:00:10.243  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:00:10.243  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:00:10.243  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:00:10.243  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:00:10.243  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:00:10.243  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:00:10.245  5569  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:00:10.245  5569  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 10:00:10.246  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:00:10.246  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:00:10.246  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:00:10.246  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:00:10.246  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:10.246  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:00:10.246  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:00:10.246  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90171ff removed from the list
09-28 10:00:10.246  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:00:10.246  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@936bcc removed from the list
,09-28 10:00:10.249  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:00:10.252  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:00:10.253  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:00:10.253  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:00:10.253  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:00:10.253  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:00:10.255  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:00:10.255  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:00:10.255  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:00:10.255  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@936bcc not in the list
09-28 10:00:10.255  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:10.255  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:00:10.256  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:00:10.256  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:00:10.256  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:00:10.256  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@936bcc not in the list
09-28 10:00:10.256  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:00:10.256  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:10.256  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:00:10.256  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90171ff not in the list
09-28 10:00:10.257  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:00:10.257  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e44052a added. We now have 3 listener(s)
,09-28 10:00:10.258  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:00:10.259  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:00:10.259  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:00:10.259  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:00:10.259  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5052f1b added. We now have 4 listener(s)
09-28 10:00:10.259  5569  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 10:00:10.260  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 10:00:10.263  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:00:10.267  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:00:10.267  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:00:10.267  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:00:10.267  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:00:10.267  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:00:10.267  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:00:10.267  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:00:10.267  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:00:10.268  5569  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:00:10.269  5569  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 10:00:10.269  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:00:10.269  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 10:00:10.269  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 10:00:10.269  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:00:10.269  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 10:00:10.273  5569  5616 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 10:00:10.273  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 10:00:10.273  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:00:10.278  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:00:10.278  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 10:00:10.279  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 10:00:10.279  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 10:00:10.282  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 10:00:10.282  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-28 10:00:10.282  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 10:00:10.283  5569  5616 D BluetoothAdapter: STATE_ON
09-28 10:00:10.285  5854  5865 D BtGatt.GattService: registerClient() - UUID=17926780-e452-478f-afda-bcf316bc04d9
09-28 10:00:10.286  5854  5870 D BtGatt.GattService: onClientRegistered() - UUID=17926780-e452-478f-afda-bcf316bc04d9, clientIf=5
09-28 10:00:10.287  5569  5671 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 10:00:10.289  5854  5892 D BtGatt.GattService: start scan with filters
,09-28 10:00:10.292  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 10:00:10.292  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 10:00:10.292  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 10:00:10.292  5854  5873 D BtGatt.ScanManager: handling starting scan
09-28 10:00:10.292  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 10:00:10.294  5854  5873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8ad9da4
,09-28 10:00:10.295  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 10:00:10.296  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 10:00:10.296  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 10:00:10.297  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 10:00:10.300  5569  5616 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-28 10:00:10.300  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 10:00:10.300  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 10:00:10.300  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:10.300  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 10:00:10.300  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 10:00:10.301  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 10:00:10.301  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:00:10.301  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 10:00:10.301  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 10:00:10.301  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 10:00:10.302  5569  5616 D BluetoothAdapter: STATE_ON
09-28 10:00:10.302  5854  5870 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 10:00:10.302  5854  5870 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:00:10.303  5854  5892 D BtGatt.GattService: stopScan() - queue size =1
,09-28 10:00:10.303  5854  5873 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 10:00:10.304  5854  5891 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 10:00:10.305  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:00:10.305  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 10:00:10.305  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 10:00:10.305  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-28 10:00:10.305  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 10:00:10.306  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:00:10.306  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:00:10.307  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 10:00:10.307  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:00:10.307  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:00:10.309  5854  5870 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 10:00:10.310  5854  5870 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:00:10.310  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:00:10.310  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:00:10.310  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 10:00:10.310  5854  5873 D BtGatt.ScanManager: Starting BLE batch scan
09-28 10:00:10.310  5854  5873 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 10:00:10.313  5569  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 10:00:10.313  5569  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 10:00:10.317  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 10:00:10.318  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 10:00:10.318  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 10:00:10.318  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:00:10.318  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 10:00:10.320  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:00:10.321  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:00:10.321  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 10:00:10.321  5854  5870 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 10:00:10.321  5854  5870 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:00:10.323  5569  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 10:00:10.324  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:00:10.324  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 10:00:10.326  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 10:00:10.327  5854  5870 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 10:00:10.327  5854  5870 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:00:10.335  5854  5870 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-28 10:00:10.335  5854  5870 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:00:10.335  5854  5873 D BtGatt.ScanManager: stopping BLe Batch
,09-28 10:00:10.341  5854  5870 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 10:00:10.341  5854  5870 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:00:10.342  5854  5873 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 10:00:10.348  5854  5870 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 10:00:10.348  5854  5870 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:00:10.828  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 10:00:10.828  5569  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:00:10.828  5569  5569 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 10:00:13.310  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 10:00:13.311  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:00:13.311  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:00:13.311  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 10:00:13.311  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:13.312  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:00:13.312  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:00:13.312  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e44052a removed from the list
09-28 10:00:13.312  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:00:13.312  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5052f1b removed from the list
09-28 10:00:13.312  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:00:13.313  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:00:13.315  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:13.316  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:00:13.319  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 10:00:13.319  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:00:13.319  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:00:13.321  5569  5616 D BluetoothAdapter: STATE_ON
09-28 10:00:13.321  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 10:00:13.322  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 10:00:13.322  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:00:13.322  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5052f1b not in the list
09-28 10:00:13.322  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:13.322  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:00:13.325  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 10:00:13.327  5569  5616 D BluetoothAdapter: STATE_ON
,09-28 10:00:13.327  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 10:00:13.328  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:00:13.328  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:00:13.328  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 10:00:13.328  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:00:13.328  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5052f1b not in the list
09-28 10:00:13.328  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:00:13.328  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:00:13.329  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:00:13.329  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e44052a not in the list
09-28 10:00:13.330  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:00:13.330  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bea6d0 added. We now have 3 listener(s)
09-28 10:00:13.333  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:00:13.333  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 10:00:13.333  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:00:13.334  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:00:13.334  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e096c9 added. We now have 4 listener(s)
09-28 10:00:13.334  5569  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:00:13.335  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 10:00:13.342  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:00:13.350  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:00:13.350  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:00:13.350  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:00:13.350  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:00:13.350  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:00:13.350  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:00:13.350  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:00:13.350  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:00:13.354  5569  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:00:13.355  5569  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 10:00:13.355  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 10:00:13.356  5569  5616 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-28 10:00:13.357  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-28 10:00:13.357  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 10:00:13.357  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-28 10:00:13.357  5569  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-28 10:00:13.357  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:00:13.359  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-28 10:00:13.360  5569  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-28 10:00:13.360  5569  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-28 10:00:13.360  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-28 10:00:13.361  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-28 10:00:13.361  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:00:13.361  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 10:00:13.361  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:00:13.365  5569  5950 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:00:13.368  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:00:13.369  5569  5569 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-28 10:00:13.367  5864  5864 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33953]" dev="sockfs" ino=33953 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:00:13.370  5569  5950 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-28 10:00:13.367  5864  5864 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33953]" dev="sockfs" ino=33953 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-28 10:00:13.371  5569  5616 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 10:00:13.371  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 10:00:13.376  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 10:00:13.377  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 10:00:13.377  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 10:00:13.379  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-28 10:00:13.380  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:00:13.380  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
,09-28 10:00:13.381  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:00:13.382  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:00:13.382  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-28 10:00:13.383  5569  5616 D BluetoothAdapter: STATE_ON
,09-28 10:00:13.388  5854  5891 D BtGatt.GattService: registerClient() - UUID=0117b256-ee2c-440d-b64d-0fdd12f84be7
09-28 10:00:13.388  5854  5870 D BtGatt.GattService: onClientRegistered() - UUID=0117b256-ee2c-440d-b64d-0fdd12f84be7, clientIf=5
,09-28 10:00:13.389  5569  5671 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-28 10:00:13.391  5854  5872 D BtGatt.AdvertiseManager: message : 0
,09-28 10:00:13.395  5854  5872 D BtGatt.AdvertiseManager: starting multi advertising
,09-28 10:00:13.405  5854  5870 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-28 10:00:13.412  5854  5870 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-28 10:00:13.413  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-28 10:00:13.413  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-28 10:00:13.414  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 10:00:13.416  5569  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 10:00:13.416  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-28 10:00:13.416  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-28 10:00:13.416  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-28 10:00:13.416  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-28 10:00:13.416  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-28 10:00:13.417  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-28 10:00:13.419  5569  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-28 10:00:13.419  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-28 10:00:13.920  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-28 10:00:13.920  5569  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-28 10:00:13.921  5569  5569 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 10:00:16.419  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:00:16.419  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-28 10:00:16.419  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 10:00:16.420  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-28 10:00:16.420  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-28 10:00:16.420  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-28 10:00:16.421  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 10:00:16.421  5569  5950 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-28 10:00:16.421  5569  5616 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-28 10:00:16.421  5569  5950 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 10:00:16.421  5569  5950 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-28 10:00:16.421  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 10:00:16.421  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-28 10:00:16.421  5569  5569 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-28 10:00:16.421  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:00:16.421  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-28 10:00:16.422  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 10:00:16.424  5569  5616 D BluetoothAdapter: STATE_ON
09-28 10:00:16.424  5569  5616 D BluetoothLeScanner: could not find callback wrapper
,09-28 10:00:16.424  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:00:16.425  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-28 10:00:16.427  5854  5872 D BtGatt.AdvertiseManager: message : 1
09-28 10:00:16.429  5854  5872 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-28 10:00:16.444  5854  5870 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-28 10:00:16.444  5854  5870 D BtGatt.GattService: Client app is not null!
,09-28 10:00:16.446  5854  5890 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 10:00:16.447  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 10:00:16.447  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-28 10:00:16.447  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-28 10:00:16.447  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-28 10:00:16.447  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-28 10:00:16.451  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 10:00:16.451  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 10:00:16.451  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:00:16.453  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 10:00:16.455  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 10:00:16.456  5569  5569 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-28 10:00:16.456  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:00:16.456  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:00:16.456  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:00:16.456  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:00:16.456  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bea6d0 removed from the list
09-28 10:00:16.456  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:00:16.456  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:00:16.456  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 10:00:16.456  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e096c9 removed from the list
09-28 10:00:16.457  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:00:16.457  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 10:00:16.463  5569  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 10:00:16.463  5569  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 10:00:16.470  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 10:00:16.471  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-28 10:00:16.471  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 10:00:16.472  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:00:16.473  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:00:16.476  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:16.476  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:00:16.478  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 10:00:16.478  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:00:16.478  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 10:00:16.479  5569  5616 D BluetoothAdapter: STATE_ON
,09-28 10:00:16.480  5569  5616 D BluetoothLeScanner: could not find callback wrapper
,09-28 10:00:16.480  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:00:16.480  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:00:16.480  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:00:16.480  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e096c9 not in the list
,09-28 10:00:16.480  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:00:16.480  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 10:00:16.486  5569  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 10:00:16.486  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:00:16.487  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:00:16.491  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:00:16.491  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:00:16.491  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:00:16.493  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:00:16.493  5569  5616 D BluetoothAdapter: STATE_ON
09-28 10:00:16.494  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 10:00:16.494  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:00:16.494  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 10:00:16.494  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:00:16.494  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 10:00:16.494  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e096c9 not in the list
09-28 10:00:16.494  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:00:16.494  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:16.494  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:00:16.495  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bea6d0 not in the list
09-28 10:00:16.496  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:00:16.496  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21ca6 added. We now have 3 listener(s)
,09-28 10:00:16.499  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 10:00:16.500  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:00:16.500  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:00:16.500  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:00:16.500  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64f6e7 added. We now have 4 listener(s)
09-28 10:00:16.500  5569  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:00:16.501  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 10:00:16.505  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:00:16.509  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:00:16.509  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:00:16.509  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:00:16.509  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:00:16.509  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:00:16.509  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:00:16.509  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:00:16.509  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:00:16.512  5569  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:00:16.512  5569  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 10:00:16.512  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-28 10:00:16.512  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 10:00:16.512  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 10:00:16.513  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:00:16.513  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 10:00:16.516  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:00:16.520  5569  5616 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 10:00:16.520  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 10:00:16.520  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:00:16.525  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 10:00:16.525  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-28 10:00:16.526  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 10:00:16.529  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 10:00:16.529  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 10:00:16.530  5569  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-28 10:00:16.530  5569  5616 D BluetoothAdapter: STATE_ON
09-28 10:00:16.532  5854  5865 D BtGatt.GattService: registerClient() - UUID=765630e7-2962-4f87-9660-f0d6e8327258
09-28 10:00:16.533  5854  5870 D BtGatt.GattService: onClientRegistered() - UUID=765630e7-2962-4f87-9660-f0d6e8327258, clientIf=5
,09-28 10:00:16.533  5569  5579 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 10:00:16.534  5854  5864 D BtGatt.GattService: start scan with filters
09-28 10:00:16.537  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 10:00:16.537  5854  5873 D BtGatt.ScanManager: handling starting scan
09-28 10:00:16.537  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-28 10:00:16.537  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-28 10:00:16.537  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-28 10:00:16.540  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 10:00:16.540  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 10:00:16.540  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 10:00:16.541  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 10:00:16.544  5854  5870 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-28 10:00:16.544  5854  5870 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:00:16.544  5854  5873 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 10:00:16.549  5854  5870 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-28 10:00:16.549  5854  5870 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:00:16.550  5854  5873 D BtGatt.ScanManager: Starting BLE batch scan
09-28 10:00:16.550  5854  5873 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 10:00:16.559  5854  5870 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 10:00:16.559  5854  5870 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:00:16.565  5854  5870 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-28 10:00:16.565  5854  5870 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:00:16.927   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:00:16.992  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 10:00:17.041  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-28 10:00:17.041  5569  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:00:17.041  5569  5569 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 10:00:19.551  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 10:00:19.552  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-28 10:00:19.552  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 10:00:19.552  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:19.552  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-28 10:00:19.552  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 10:00:19.553  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-28 10:00:19.553  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:00:19.553  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 10:00:19.553  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 10:00:19.553  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-28 10:00:19.555  5569  5616 D BluetoothAdapter: STATE_ON
09-28 10:00:19.557  5854  5891 D BtGatt.GattService: stopScan() - queue size =1
09-28 10:00:19.559  5854  5890 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 10:00:19.559  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:00:19.560  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 10:00:19.560  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-28 10:00:19.560  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 10:00:19.560  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 10:00:19.562  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 10:00:19.563  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:00:19.563  5569  5616 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 10:00:19.563  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:00:19.564  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:00:19.566  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:00:19.566  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:19.566  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:00:19.566  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:00:19.566  5854  5854 D BtGatt.ScanManager: awakened up at time 328002
09-28 10:00:19.566  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:00:19.566  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:00:19.566  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 10:00:19.566  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21ca6 removed from the list
09-28 10:00:19.567  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:00:19.567  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64f6e7 removed from the list
09-28 10:00:19.567  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:00:19.567  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 10:00:19.574  5854  5870 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 10:00:19.574  5854  5870 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:00:19.574  5854  5873 D BtGatt.ScanManager: stopping BLe Batch
09-28 10:00:19.575  5569  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 10:00:19.575  5569  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 10:00:19.580  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 10:00:19.580  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 10:00:19.581  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 10:00:19.581  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:00:19.581  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:00:19.581  5854  5870 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 10:00:19.581  5854  5870 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:00:19.582  5854  5873 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 10:00:19.583  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:19.583  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:00:19.584  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:00:19.584  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:00:19.585  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:00:19.585  5569  5616 D BluetoothAdapter: STATE_ON
09-28 10:00:19.585  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 10:00:19.585  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:00:19.585  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:00:19.586  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64f6e7 not in the list
09-28 10:00:19.586  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:00:19.586  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:00:19.586  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 10:00:19.589  5569  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 10:00:19.589  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:00:19.590  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:00:19.592  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:19.592  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:00:19.592  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:00:19.594  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 10:00:19.595  5569  5616 D BluetoothAdapter: STATE_ON
09-28 10:00:19.595  5569  5616 D BluetoothLeScanner: could not find callback wrapper
09-28 10:00:19.595  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:00:19.595  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:00:19.595  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:00:19.595  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:00:19.595  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64f6e7 not in the list
09-28 10:00:19.595  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 10:00:19.595  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:19.596  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:00:19.596  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21ca6 not in the list
09-28 10:00:19.596  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:00:19.596  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@588c02c added. We now have 3 listener(s)
09-28 10:00:19.598  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:00:19.598  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 10:00:19.598  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:00:19.598  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 10:00:19.600  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cf6af5 added. We now have 4 listener(s)
,09-28 10:00:19.600  5569  5616 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:00:19.600  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 10:00:19.603  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:00:19.605  5854  5870 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-28 10:00:19.605  5854  5870 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:00:19.606  5854  5870 D BtGatt.GattService: current time is 328041936421
09-28 10:00:19.606  5854  5870 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -77, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -78, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -70, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -73, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -80, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-28 10:00:19.607  5854  5870 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-28 10:00:19.608  5854  5870 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-28 10:00:19.608  5854  5870 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-28 10:00:19.609  5854  5870 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 10:00:19.609  5854  5870 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-28 10:00:19.609  5854  5870 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-28 10:00:19.609  5569  5616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:00:19.609  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:00:19.609  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:00:19.609  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:00:19.609  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:00:19.609  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:00:19.609  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:00:19.609  5569  5616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:00:19.612  5569  5616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:00:19.612  5569  5616 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 10:00:19.612  5569  5616 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:00:19.612  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:00:19.612  5569  5616 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:00:19.612  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:00:19.613  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:19.613  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:00:19.613  5569  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09,-28 10:00:19.613  5569  5616 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@588c02c removed from the list
09-28 10:00:19.613  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:00:19.613  5569  5616 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cf6af5 removed from the list
09-28 10:00:19.615  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:00:19.615  5569  5616 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:00:19.615  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:00:19.616  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:00:19.616  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:00:19.617  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:00:19.617  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:00:19.617  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:00:19.617  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cf6af5 not in the list
09-28 10:00:19.617  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:19.617  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:00:19.618  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:00:19.618  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:00:19.618  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 10:00:19.618  5569  5616 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:00:19.618  5569  5616 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cf6af5 not in the list
09-28 10:00:19.618  5569  5616 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:00:19.618  5569  5616 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:00:19.618  5569  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:00:19.618  5569  5616 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@588c02c not in the list
09-28 10:00:19.619  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-28 10:00:19.619  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-28 10:00:19.619  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-28 10:00:19.619  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:00:19.619  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-28 10:00:19.619  5569  5616 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-28 10:00:19.942   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:00:20.093  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 10:00:20.447   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-28 10:00:20.447   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 10:00:21.631  5569  5952 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name)
,09-28 10:00:23.629  5569  5616 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 192
,09-28 10:00:23.629  5569  5616 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 192, name: My test thread name)
,09-28 10:00:23.634  5569  5953 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: My test thread name)
09-28 10:00:23.634  5569  5953 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 193, thread name: My test thread name)
09-28 10:00:23.634  5569  5953 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-28 10:00:23.638  5569  5616 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 10:00:23.640  5569  5952 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-28 10:00:23.644  5569  5954 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: My test thread name)
,09-28 10:00:23.645  5569  5954 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 197, thread name: My test thread name): Test exception.
09-28 10:00:23.645  5569  5954 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-28 10:00:23.655  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
09-28 10:00:23.655  5569  5616 I jxcore-log: 
,09-28 10:00:23.656  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-28 10:00:23.656  5569  5616 I jxcore-log: 
09-28 10:00:23.658  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG UnitTest_app: 'Number of failed tests:  0'
09-28 10:00:23.658  5569  5616 I jxcore-log: 
,09-28 10:00:23.659  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-28 10:00:23.659  5569  5616 I jxcore-log: 
,09-28 10:00:23.662  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG UnitTest_app: 'Total duration:  101051'
09-28 10:00:23.662  5569  5616 I jxcore-log: 
,09-28 10:00:23.672  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-28 10:00:23.672  5569  5616 I jxcore-log: 
,09-28 10:00:23.682  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.682  5569  5616 I jxcore-log: 
,09-28 10:00:23.685  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.685  5569  5616 I jxcore-log: 
,09-28 10:00:23.686  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.686  5569  5616 I jxcore-log: 
09-28 10:00:23.688  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.688  5569  5616 I jxcore-log: 
,09-28 10:00:23.689  5569  5569 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-28 10:00:23.690  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 10:00:23.690  5569  5616 I jxcore-log: 
,09-28 10:00:23.692  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 10:00:23.692  5569  5616 I jxcore-log: 
,09-28 10:00:23.693  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.693  5569  5616 I jxcore-log: 
,09-28 10:00:23.694  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.694  5569  5616 I jxcore-log: 
,09-28 10:00:23.695  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 10:00:23.695  5569  5616 I jxcore-log: 
09-28 10:00:23.696  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 10:00:23.696  5569  5616 I jxcore-log: 
09-28 10:00:23.697  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 10:00:23.697  5569  5616 I jxcore-log: 
09-28 10:00:23.697  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.697  5569  5616 I jxcore-log: 
,09-28 10:00:23.699  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.699  5569  5616 I jxcore-log: 
,09-28 10:00:23.700  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 10:00:23.700  5569  5616 I jxcore-log: 
,09-28 10:00:23.701  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 10:00:23.701  5569  5616 I jxcore-log: 
,09-28 10:00:23.702  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 10:00:23.702  5569  5616 I jxcore-log: 
09-28 10:00:23.703  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.703  5569  5616 I jxcore-log: 
09-28 10:00:23.704  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.704  5569  5616 I jxcore-log: 
,09-28 10:00:23.705  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.705  5569  5616 I jxcore-log: 
,09-28 10:00:23.706  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.706  5569  5616 I jxcore-log: 
,09-28 10:00:23.707  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 10:00:23.707  5569  5616 I jxcore-log: 
,09-28 10:00:23.708  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 10:00:23.708  5569  5616 I jxcore-log: 
09-28 10:00:23.709  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 10:00:23.709  5569  5616 I jxcore-log: 
,09-28 10:00:23.712  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.712  5569  5616 I jxcore-log: 
,09-28 10:00:23.713  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.713  5569  5616 I jxcore-log: 
,09-28 10:00:23.714  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.714  5569  5616 I jxcore-log: 
,09-28 10:00:23.716  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 10:00:23.716  5569  5616 I jxcore-log: 
,09-28 10:00:23.717  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.717  5569  5616 I jxcore-log: 
,09-28 10:00:23.718  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.718  5569  5616 I jxcore-log: 
09-28 10:00:23.719  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.719  5569  5616 I jxcore-log: 
,09-28 10:00:23.719  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.719  5569  5616 I jxcore-log: 
09-28 10:00:23.719  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.719  5569  5616 I jxcore-log: 
09-28 10:00:23.720  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.720  5569  5616 I jxcore-log: 
09-28 10:00:23.720  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.720  5569  5616 I jxcore-log: 
09-28 10:00:23.721  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.721  5569  5616 I jxcore-log: 
,09-28 10:00:23.721  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.721  5569  5616 I jxcore-log: 
09-28 10:00:23.722  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.722  5569  5616 I jxcore-log: 
09-28 10:00:23.722  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.722  5569  5616 I jxcore-log: 
09-28 10:00:23.723  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 10:00:23.723  5569  5616 I jxcore-log: 
09-28 10:00:23.723  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-28 10:00:23.723  5569  5616 I jxcore-log: 
09-28 10:00:23.724  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-28 10:00:23.724  5569  5616 I jxcore-log: 
,09-28 10:00:23.725  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-28 10:00:23.725  5569  5616 I jxcore-log: 
,09-28 10:00:23.726  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.726  5569  5616 I jxcore-log: 
09-28 10:00:23.726  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.726  5569  5616 I jxcore-log: 
,09-28 10:00:23.727  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.727  5569  5616 I jxcore-log: 
,09-28 10:00:23.728  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.728  5569  5616 I jxcore-log: 
,09-28 10:00:23.729  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 10:00:23.729  5569  5616 I jxcore-log: 
,09-28 10:00:23.729  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.729  5569  5616 I jxcore-log: 
,09-28 10:00:23.730  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
09-28 10:00:23.730  5569  5616 I jxcore-log: 
,09-28 10:00:23.731  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.731  5569  5616 I jxcore-log: 
09-28 10:00:23.731  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 10:00:23.731  5569  5616 I jxcore-log: 
,09-28 10:00:23.732  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 10:00:23.732  5569  5616 I jxcore-log: 
,09-28 10:00:23.733  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:00:23.733  5569  5616 I jxcore-log: 
,09-28 10:00:23.733  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 10:00:23.733  5569  5616 I jxcore-log: 
,09-28 10:00:23.737  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-28 10:00:23.737  5569  5616 I jxcore-log: 
,09-28 10:00:23.737  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - WARN testUtils: 'myNameCallback not set!'
09-28 10:00:23.737  5569  5616 I jxcore-log: 
,09-28 10:00:23.738  5569  5616 I jxcore-log: 2016-09-28 14:00:23 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-28 10:00:23.738  5569  5616 I jxcore-log: 
,09-28 10:00:25.713  5569  5616 I jxcore-log: 2016-09-28 14:00:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-28 10:00:25.713  5569  5616 I jxcore-log: 
,09-28 10:00:26.025  5569  5616 I jxcore-log: 2016-09-28 14:00:26 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-28 10:00:26.025  5569  5616 I jxcore-log: 
,09-28 10:00:26.037  5569  5616 I jxcore-log: 2016-09-28 14:00:26 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-28 10:00:26.037  5569  5616 I jxcore-log: 
,09-28 10:00:27.110  5569  5616 I jxcore-log: 2016-09-28 14:00:27 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-28 10:00:27.110  5569  5616 I jxcore-log: 
,09-28 10:00:27.256  5569  5616 I jxcore-log: 2016-09-28 14:00:27 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-28 10:00:27.256  5569  5616 I jxcore-log: 
,09-28 10:00:27.261  5569  5616 I jxcore-log: 2016-09-28 14:00:27 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-28 10:00:27.261  5569  5616 I jxcore-log: 
,09-28 10:00:27.273  5569  5616 I jxcore-log: 2016-09-28 14:00:27 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-28 10:00:27.273  5569  5616 I jxcore-log: 
,09-28 10:00:27.793  5569  5616 I jxcore-log: 2016-09-28 14:00:27 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-28 10:00:27.793  5569  5616 I jxcore-log: 
,09-28 10:00:27.842  5569  5616 I jxcore-log: 2016-09-28 14:00:27 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-28 10:00:27.842  5569  5616 I jxcore-log: 
,09-28 10:00:27.854  5569  5616 I jxcore-log: 2016-09-28 14:00:27 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-28 10:00:27.854  5569  5616 I jxcore-log: 
,09-28 10:00:27.858  5569  5616 I jxcore-log: 2016-09-28 14:00:27 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-28 10:00:27.858  5569  5616 I jxcore-log: 
,09-28 10:00:28.111  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-28 10:00:28.111  5569  5616 I jxcore-log: 
,09-28 10:00:28.227  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-28 10:00:28.227  5569  5616 I jxcore-log: 
,09-28 10:00:28.447  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-28 10:00:28.447  5569  5616 I jxcore-log: 
,09-28 10:00:28.458  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-28 10:00:28.458  5569  5616 I jxcore-log: 
,09-28 10:00:28.465  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-28 10:00:28.465  5569  5616 I jxcore-log: 
,09-28 10:00:28.471  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-28 10:00:28.471  5569  5616 I jxcore-log: 
,09-28 10:00:28.499  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-28 10:00:28.499  5569  5616 I jxcore-log: 
,09-28 10:00:28.535  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-28 10:00:28.535  5569  5616 I jxcore-log: 
,09-28 10:00:28.542  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-28 10:00:28.542  5569  5616 I jxcore-log: 
,09-28 10:00:28.549  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-28 10:00:28.549  5569  5616 I jxcore-log: 
,09-28 10:00:28.564  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-28 10:00:28.564  5569  5616 I jxcore-log: 
,09-28 10:00:28.569  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-28 10:00:28.569  5569  5616 I jxcore-log: 
,09-28 10:00:28.574  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-28 10:00:28.574  5569  5616 I jxcore-log: 
,09-28 10:00:28.587  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-28 10:00:28.587  5569  5616 I jxcore-log: 
,09-28 10:00:28.608  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-28 10:00:28.608  5569  5616 I jxcore-log: 
,09-28 10:00:28.617  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-28 10:00:28.617  5569  5616 I jxcore-log: 
,09-28 10:00:28.628  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-28 10:00:28.628  5569  5616 I jxcore-log: 
,09-28 10:00:28.637  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-28 10:00:28.637  5569  5616 I jxcore-log: 
,09-28 10:00:28.649  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-28 10:00:28.649  5569  5616 I jxcore-log: 
,09-28 10:00:28.659  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-28 10:00:28.659  5569  5616 I jxcore-log: 
,09-28 10:00:28.664  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-28 10:00:28.664  5569  5616 I jxcore-log: 
,09-28 10:00:28.683  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js'
09-28 10:00:28.683  5569  5616 I jxcore-log: 
,09-28 10:00:28.691  5569  5616 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-28 10:00:28.692  5569  5616 I jxcore-log: 2016-09-28 14:00:28 - INFO testUtils: 'BLE multiple advertisement supported'
09-28 10:00:28.692  5569  5616 I jxcore-log: 
,09-28 10:00:29.049  5569  5616 I jxcore-log: 2016-09-28 14:00:29 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:00:29.049  5569  5616 I jxcore-log: 
,09-28 10:00:35.449   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:00:36.450   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:00:37.451   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:00:38.453   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:00:39.021   929  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 10:00:39.454   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:00:40.455   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 10:00:45.456   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:00:46.458   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:00:47.459   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:00:48.461   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:00:49.462   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:00:50.463   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 10:01:00.465   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:01.466   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:02.468   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:03.469   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:04.470   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:05.471   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 10:01:19.028   929  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 10:01:20.472   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:21.473   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:22.474   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:23.475   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:24.477   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:25.478   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 10:01:39.028   929  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 10:01:45.479   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:46.480   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:47.482   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:47.669   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:01:48.483   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:49.484   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:01:50.485   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-28 10:01:50.701   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:02:15.486   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-28 10:02:15.487   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 10:02:19.032   929  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 10:02:35.488   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:02:36.489   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:02:37.490   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:02:38.492   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:02:39.033   929  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 10:02:39.494   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:02:40.495   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 10:02:45.496   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:02:46.497   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:02:47.499   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:02:48.500   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:02:49.502   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:02:50.502   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 10:02:59.034   929  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 10:03:00.504   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:03:01.505   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:03:02.507   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:03:03.508   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:03:04.510   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:03:05.510   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 10:03:09.341   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:03:12.373   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:03:20.512   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:03:21.513  5569  5616 I jxcore-log: 2016-09-28 14:03:21 - DEBUG CoordinatedClient: 'device disconnected from the test server'
09-28 10:03:21.513  5569  5616 I jxcore-log: 
,09-28 10:03:21.513   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:03:21.810  5569  5616 I jxcore-log: 2016-09-28 14:03:21 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:21.810  5569  5616 I jxcore-log: 
,09-28 10:03:21.821  5569  5616 I jxcore-log: 2016-09-28 14:03:21 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:21.821  5569  5616 I jxcore-log: 
,09-28 10:03:22.372  5569  5616 I jxcore-log: 2016-09-28 14:03:22 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:22.372  5569  5616 I jxcore-log: 
,09-28 10:03:22.384  5569  5616 I jxcore-log: 2016-09-28 14:03:22 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:22.384  5569  5616 I jxcore-log: 
,09-28 10:03:22.514   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:03:23.037  5569  5616 I jxcore-log: 2016-09-28 14:03:23 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:23.037  5569  5616 I jxcore-log: 
,09-28 10:03:23.045  5569  5616 I jxcore-log: 2016-09-28 14:03:23 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:23.045  5569  5616 I jxcore-log: 
,09-28 10:03:23.515   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:03:24.078  5569  5616 I jxcore-log: 2016-09-28 14:03:24 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:24.078  5569  5616 I jxcore-log: 
,09-28 10:03:24.087  5569  5616 I jxcore-log: 2016-09-28 14:03:24 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:24.087  5569  5616 I jxcore-log: 
,09-28 10:03:24.484   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:03:24.516   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:03:25.131  5569  5616 I jxcore-log: 2016-09-28 14:03:25 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:25.131  5569  5616 I jxcore-log: 
,09-28 10:03:25.138  5569  5616 I jxcore-log: 2016-09-28 14:03:25 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:25.138  5569  5616 I jxcore-log: 
,09-28 10:03:25.516   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 10:03:26.178  5569  5616 I jxcore-log: 2016-09-28 14:03:26 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:26.178  5569  5616 I jxcore-log: 
,09-28 10:03:26.186  5569  5616 I jxcore-log: 2016-09-28 14:03:26 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:26.186  5569  5616 I jxcore-log: 
,09-28 10:03:27.219  5569  5616 I jxcore-log: 2016-09-28 14:03:27 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:27.219  5569  5616 I jxcore-log: 
,09-28 10:03:27.228  5569  5616 I jxcore-log: 2016-09-28 14:03:27 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:27.228  5569  5616 I jxcore-log: 
,09-28 10:03:27.505   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:03:28.268  5569  5616 I jxcore-log: 2016-09-28 14:03:28 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:28.268  5569  5616 I jxcore-log: 
,09-28 10:03:28.276  5569  5616 I jxcore-log: 2016-09-28 14:03:28 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:28.276  5569  5616 I jxcore-log: 
,09-28 10:03:29.311  5569  5616 I jxcore-log: 2016-09-28 14:03:29 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:29.311  5569  5616 I jxcore-log: 
09-28 10:03:29.316  5569  5616 I jxcore-log: 2016-09-28 14:03:29 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:29.316  5569  5616 I jxcore-log: 
,09-28 10:03:30.375  5569  5616 I jxcore-log: 2016-09-28 14:03:30 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:30.375  5569  5616 I jxcore-log: 
,09-28 10:03:30.383  5569  5616 I jxcore-log: 2016-09-28 14:03:30 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:30.383  5569  5616 I jxcore-log: 
,09-28 10:03:31.419  5569  5616 I jxcore-log: 2016-09-28 14:03:31 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:31.419  5569  5616 I jxcore-log: 
,09-28 10:03:31.430  5569  5616 I jxcore-log: 2016-09-28 14:03:31 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:31.430  5569  5616 I jxcore-log: 
,09-28 10:03:32.042   929  5913 D NetlinkSocketObserver: NeighborEvent{elapsedMs=520477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 10:03:32.467  5569  5616 I jxcore-log: 2016-09-28 14:03:32 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:32.467  5569  5616 I jxcore-log: 
,09-28 10:03:32.478  5569  5616 I jxcore-log: 2016-09-28 14:03:32 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:32.478  5569  5616 I jxcore-log: 
,09-28 10:03:33.510  5569  5616 I jxcore-log: 2016-09-28 14:03:33 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:33.510  5569  5616 I jxcore-log: 
,09-28 10:03:33.516  5569  5616 I jxcore-log: 2016-09-28 14:03:33 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:33.516  5569  5616 I jxcore-log: 
,09-28 10:03:34.549  5569  5616 I jxcore-log: 2016-09-28 14:03:34 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:34.549  5569  5616 I jxcore-log: 
,09-28 10:03:34.558  5569  5616 I jxcore-log: 2016-09-28 14:03:34 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:34.558  5569  5616 I jxcore-log: 
,09-28 10:03:35.594  5569  5616 I jxcore-log: 2016-09-28 14:03:35 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:03:35.594  5569  5616 I jxcore-log: 
,09-28 10:03:35.602  5569  5616 I jxcore-log: 2016-09-28 14:03:35 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 10:03:35.602  5569  5616 I jxcore-log: 
,09-28 10:03:37.456   929  5913 D NetlinkSocketObserver: NeighborEvent{elapsedMs=525891, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-28 10:03:39.038   929  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 10:03:39.595   929  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]

```
