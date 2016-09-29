#### Test 87277145c125592_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-29 05:54:52.155   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-29 05:54:52.156   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-29 05:54:52.627  5635  5635 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-29 05:54:52.632  5635  5635 D AndroidRuntime: CheckJNI is OFF
09-29 05:54:52.655  5635  5635 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-29 05:54:52.685  5635  5635 I Radio-JNI: register_android_hardware_Radio DONE
09-29 05:54:52.700  5635  5635 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-29 05:54:52.709   928  3405 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-29 05:54:52.758   928  3405 I ActivityManager: Start proc 5644:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-29 05:54:52.776  5635  5635 D AndroidRuntime: Shutting down VM
,09-29 05:54:53.105   928  3908 I WindowManager: Screenshot max retries 4 of Token{5b981fa ActivityRecord{2a26c25 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{732fadd u0 Starting com.test.thalitest} drawState=2
,09-29 05:54:53.171  5644  5644 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-29 05:54:53.204  5644  5644 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-29 05:54:53.227  5644  5644 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 71-89)
,09-29 05:54:53.227  5644  5644 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-29 05:54:53.247  5644  5644 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bc3987c}
,09-29 05:54:53.248  5644  5644 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-29 05:54:53.248  5644  5644 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-29 05:54:53.253  5644  5644 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-29 05:54:53.255  5644  5644 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-29 05:54:53.290  5644  5644 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-29 05:54:53.303  5644  5644 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-29 05:54:53.303  5644  5644 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-29 05:54:53.304  5644  5644 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-29 05:54:53.304  5644  5644 I Adreno  : Build Date                       : 12/06/15
09-29 05:54:53.304  5644  5644 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-29 05:54:53.304  5644  5644 I Adreno  : Local Branch                     : mybranch17112971
09-29 05:54:53.304  5644  5644 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-29 05:54:53.304  5644  5644 I Adreno  : Remote Branch                    : NONE
09-29 05:54:53.304  5644  5644 I Adreno  : Reconstruct Branch               : NOTHING
,09-29 05:54:53.360   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a54c538:true
,09-29 05:54:53.384   406   406 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33933]" dev="sockfs" ino=33933 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-29 05:54:53.384   406   406 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33933]" dev="sockfs" ino=33933 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-29 05:54:53.400  5644  5644 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-29 05:54:53.409  5644  5644 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-29 05:54:53.431   406   406 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32836]" dev="sockfs" ino=32836 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-29 05:54:53.431   406   406 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32836]" dev="sockfs" ino=32836 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-29 05:54:53.437  5644  5681 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-29 05:54:53.437  3844  3844 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33944]" dev="sockfs" ino=33944 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-29 05:54:53.437  3844  3844 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33944]" dev="sockfs" ino=33944 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-29 05:54:53.446  5644  5668 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-29 05:54:53.470  5644  5681 I OpenGLRenderer: Initialized EGL, version 1.4
,09-29 05:54:53.560   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +450ms (total +834ms)
,09-29 05:54:53.589  5644  5644 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5644
,09-29 05:54:53.692  5644  5644 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-29 05:54:53.926  5644  5684 D jxcore_app_log: JniHelper::setJavaVM(0xf4ebc000), pthread_self() = -604243664
,09-29 05:54:53.939  5644  5684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-29 05:54:53.939  5644  5684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-29 05:54:53.939  5644  5684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-29 05:54:53.939  5644  5684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-29 05:54:53.939  5644  5684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-29 05:54:53.939  5644  5684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8544872 added. We now have 1 listener(s)
,09-29 05:54:53.945  5644  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-29 05:54:53.946  5644  5684 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:54:53.947  5644  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:54:53.947  5644  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-29 05:54:53.951  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-29 05:54:53.951  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-29 05:54:53.951  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-29 05:54:53.951  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-29 05:54:53.951  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-29 05:54:53.951  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-29 05:54:53.951  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-29 05:54:53.951  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-29 05:54:53.951  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-29 05:54:53.951  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-29 05:54:53.951  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-29 05:54:53.951  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-29 05:54:53.951  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-29 05:54:53.951  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-29 05:54:53.952  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f791879 added. We now have 1 listener(s)
09-29 05:54:53.952  5644  5684 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 05:54:53.971   928  2944 D WifiService: New client listening to asynchronous messages
,09-29 05:54:53.973  5644  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 05:54:53.973  5644  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-29 05:54:53.973  5644  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-29 05:54:53.973  5644  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-29 05:54:53.973  5644  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-29 05:54:53.976  5644  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:54:53.976  5644  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-29 05:54:53.987  5644  5684 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-29 05:54:53.988  5644  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:54:53.988  5644  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:54:53.988  5644  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:54:53.988  5644  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:54:53.988  5644  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:54:53.988  5644  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:54:53.988  5644  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:54:53.988  5644  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:54:53.988  5644  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-29 05:54:53.988  5644  5684 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:54:53.989  5644  5684 I io.jxcore.node.LifeCycleMonitor: start: OK
09-29 05:54:53.991  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:54:53.995  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:54:54.019  5644  5644 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-29 05:54:54.635   928  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 05:54:54.676  5644  5690 W jxcore-log: Initializing JXcore engine
,09-29 05:54:54.677  5644  5690 W jxcore-log: JXcore engine is ready
,09-29 05:54:54.697  5690  5690 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11910 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-29 05:54:54.697  5690  5690 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16395]" dev="sockfs" ino=16395 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-29 05:54:54.697  5690  5690 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-29 05:54:54.697  5690  5690 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30601]" dev="sockfs" ino=30601 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-29 05:54:54.707  5644  5690 W jxcore-log: Starting JXcore engine
,09-29 05:54:54.756  5644  5690 W jxcore-log: Platform android
09-29 05:54:54.756  5644  5690 W jxcore-log: 
,09-29 05:54:54.756  5644  5690 W jxcore-log: Process ARCH arm
09-29 05:54:54.756  5644  5690 W jxcore-log: 
,09-29 05:54:54.853  5644  5690 I jxcore-log: JXcore Cordova bridge is ready!
09-29 05:54:54.853  5644  5690 I jxcore-log: 
,09-29 05:54:54.853  5644  5690 W jxcore-log: JXcore engine is started
,09-29 05:54:54.861  5644  5684 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-29 05:54:54.866  5644  5644 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-29 05:55:02.157   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:03.159   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:04.160   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:04.674  5644  5690 I jxcore-log: 2016-09-29 09:55:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-29 05:55:04.674  5644  5690 I jxcore-log: 
,09-29 05:55:04.676  5644  5690 I jxcore-log: 2016-09-29 09:55:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-29 05:55:04.676  5644  5690 I jxcore-log: 
,09-29 05:55:04.680  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:55:04.680  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:04.680  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:04.680  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:04.680  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:55:04.680  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:04.680  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:55:04.680  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:55:04.681  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 05:55:04.683  5644  5690 I jxcore-log: 2016-09-29 09:55:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-29 05:55:04.683  5644  5690 I jxcore-log: 
09-29 05:55:04.684  5644  5690 I jxcore-log: 2016-09-29 09:55:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-29 05:55:04.684  5644  5690 I jxcore-log: 
,09-29 05:55:04.942  5644  5690 I jxcore-log: 2016-09-29 09:55:04 - DEBUG UnitTest_app: 'Running unit tests'
09-29 05:55:04.942  5644  5690 I jxcore-log: 
,09-29 05:55:04.943  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 05:55:04.943  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d91367 added. We now have 2 listener(s)
09-29 05:55:04.943  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:55:04.944  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:55:04.944  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:55:04.944  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-29 05:55:04.944  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@300d514 added. We now have 2 listener(s)
09-29 05:55:04.944  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:55:04.944  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 05:55:04.946  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:55:04.949  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:55:04.949  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:04.949  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:04.949  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:04.949  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:55:04.949  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:04.949  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:55:04.949  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:55:04.950  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:04.950  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:55:04.951  5644  5690 D executeNativeTests: Running unit tests
,09-29 05:55:04.958  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:04.963  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:04.988  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 05:55:04.988  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 added. We now have 3 listener(s)
09-29 05:55:04.989  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:55:04.989  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-29 05:55:04.989  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:55:04.989  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:55:04.989  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 added. We now have 3 listener(s)
09-29 05:55:04.989  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:55:04.989  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 05:55:04.991  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:55:04.993  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:55:04.993  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:04.993  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:04.993  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:04.993  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:55:04.993  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:04.993  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:55:04.993  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:55:04.994  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 05:55:04.995  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:55:04.996  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-29 05:55:04.996  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-29 05:55:04.996  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 05:55:04.996  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 05:55:04.997  5644  5690 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-29 05:55:04.997  5644  5690 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-29 05:55:04.997  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-29 05:55:04.997  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:55:04.997  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:55:04.997  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:55:04.998  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 05:55:04.998  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:04.998  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:04.998  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:04.999  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 05:55:04.999  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:55:04.999  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:04.999  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-29 05:55:04.999  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 removed from the list
09-29 05:55:04.999  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:04.999  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 removed from the list
09-29 05:55:05.004  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:05.009  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:05.010  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:05.010  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:05.010  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 05:55:05.011  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:05.011  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:05.011  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:05.011  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:05.011  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
,09-29 05:55:05.012  5644  5690 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-29 05:55:05.012  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:05.012  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:05.012  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:05.012  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:05.012  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:05.012  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:05.012  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:05.012  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:05.012  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:05.013  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:05.013  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:05.013  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:05.013  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:05.013  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 05:55:05.013  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:05.013  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:05.013  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:05.013  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:05.013  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
,09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-29 05:55:05.016  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-29 05:55:05.017  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-29 05:55:05.017  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-29 05:55:05.017  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-29 05:55:05.017  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-29 05:55:05.017  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:05.017  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:05.017  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:05.017  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 05:55:05.017  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:05.017  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:05.017  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:05.017  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:05.017  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:05.017  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:05.017  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:05.017  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 05:55:05.017  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:05.017  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:05.017  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:05.018  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:05.018  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:05.018  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:55:05.018  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:05.018  5644  5690 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-29 05:55:05.019  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:55:05.021  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:55:05.021  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:05.021  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:05.021  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:05.021  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:55:05.021  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:05.021  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:55:05.021  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:55:05.022  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:05.022  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:55:05.022  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-29 05:55:05.022  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 05:55:05.022  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 05:55:05.022  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:55:05.022  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 05:55:05.024  5644  5690 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 05:55:05.024  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-29 05:55:05.026  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:05.027  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 05:55:05.029  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 05:55:05.029  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-29 05:55:05.030  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:05.032  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-29 05:55:05.039  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-29 05:55:05.040  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-29 05:55:05.041  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 05:55:05.041  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 05:55:05.041  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 05:55:05.041  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 05:55:05.041  5644  5690 D BluetoothAdapter: STATE_ON
,09-29 05:55:05.043  4579  4594 D BtGatt.GattService: registerClient() - UUID=d6ab8a6d-ffd0-434f-bac2-bd4318c9ce96
09-29 05:55:05.044  4579  4654 D BtGatt.GattService: onClientRegistered() - UUID=d6ab8a6d-ffd0-434f-bac2-bd4318c9ce96, clientIf=5
,09-29 05:55:05.045  5644  5654 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 05:55:05.046  4579  4812 D BtGatt.GattService: start scan with filters
,09-29 05:55:05.049  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 05:55:05.049  4579  4663 D BtGatt.ScanManager: handling starting scan
09-29 05:55:05.050  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 05:55:05.050  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 05:55:05.050  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-29 05:55:05.050  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 05:55:05.050  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 05:55:05.050  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-29 05:55:05.051  4579  4663 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
,09-29 05:55:05.052  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-29 05:55:05.052  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 05:55:05.052  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 05:55:05.052  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-29 05:55:05.053  5644  5690 I io.jxcore.node.ConnectionHelper: start: OK
,09-29 05:55:05.058  4579  4654 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 05:55:05.058  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 05:55:05.059  4579  4663 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-29 05:55:05.065  4579  4654 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 05:55:05.065  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 05:55:05.065  4579  4663 D BtGatt.ScanManager: Starting BLE batch scan
09-29 05:55:05.066  4579  4663 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-29 05:55:05.075  4579  4654 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-29 05:55:05.075  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 05:55:05.080  4579  4654 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-29 05:55:05.081  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 05:55:05.162   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:05.415   928  2949 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-29 05:55:05.553  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-29 05:55:05.554  5644  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-29 05:55:05.554  5644  5644 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-29 05:55:06.163   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:07.163   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-29 05:55:08.443   928  2949 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-29 05:55:10.058  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 05:55:10.058  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:10.058  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-29 05:55:10.058  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:10.058  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 05:55:10.058  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-29 05:55:10.058  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 05:55:10.058  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 05:55:10.058  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 05:55:10.059  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 05:55:10.059  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 05:55:10.059  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-29 05:55:10.060  5644  5690 D BluetoothAdapter: STATE_ON
09-29 05:55:10.061  4579  4592 D BtGatt.GattService: stopScan() - queue size =1
09-29 05:55:10.062  4579  4791 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 05:55:10.063  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 05:55:10.063  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 05:55:10.063  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-29 05:55:10.063  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 05:55:10.063  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 05:55:10.063  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 05:55:10.063  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 05:55:10.063  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-29 05:55:10.065  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:55:10.065  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 05:55:10.065  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 05:55:10.065  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 05:55:10.066  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 05:55:10.066  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:55:10.068  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:10.068  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:10.068  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:55:10.068  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:55:10.068  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:10.069  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:10.069  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:10.069  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-29 05:55:10.069  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:10.069  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:10.069  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:55:10.069  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:55:10.070  4579  4579 D BtGatt.ScanManager: awakened up at time 236932
,09-29 05:55:10.080  4579  4654 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-29 05:55:10.080  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 05:55:10.081  4579  4663 D BtGatt.ScanManager: stopping BLe Batch
,09-29 05:55:10.090  4579  4654 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-29 05:55:10.091  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:55:10.091  4579  4663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-29 05:55:10.114  4579  4654 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-29 05:55:10.114  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:55:10.115  4579  4654 D BtGatt.GattService: current time is 236977527844
09-29 05:55:10.116  4579  4654 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -74, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -73, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -9, -41, -38, 3, -84, 69, 1, -128, -95, 44, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 10, 0, 0, 116, -43, -111, -91, -20, -29, 1, -128, -80, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -78, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -71, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -75, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-29 05:55:10.118  4579  4654 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-29 05:55:10.119  4579  4654 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-29 05:55:10.119  4579  4654 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 10, 0]
09-29 05:55:10.120  4579  4654 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-29 05:55:10.120  4579  4654 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-29 05:55:10.121  4579  4654 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-29 05:55:10.122  4579  4654 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-29 05:55:10.571  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 05:55:12.164   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:13.166   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:14.167   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:15.071  5644  5690 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-29 05:55:15.076  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:55:15.087  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:55:15.087  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:15.087  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:15.087  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:15.087  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:55:15.087  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:15.087  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:55:15.087  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:55:15.092  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:15.093  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 05:55:15.093  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 05:55:15.093  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 05:55:15.093  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 05:55:15.093  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:55:15.093  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-29 05:55:15.096  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:15.097  5644  5690 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-29 05:55:15.097  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 05:55:15.099  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:15.102  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-29 05:55:15.102  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-29 05:55:15.102  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 05:55:15.106  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-29 05:55:15.106  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 05:55:15.106  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 05:55:15.106  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 05:55:15.106  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 05:55:15.107  5644  5690 D BluetoothAdapter: STATE_ON
09-29 05:55:15.109  4579  4812 D BtGatt.GattService: registerClient() - UUID=598615c0-8075-47fc-b349-7ce9d4409642
09-29 05:55:15.110  4579  4654 D BtGatt.GattService: onClientRegistered() - UUID=598615c0-8075-47fc-b349-7ce9d4409642, clientIf=5
09-29 05:55:15.111  5644  5654 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 05:55:15.111  4579  4813 D BtGatt.GattService: start scan with filters
,09-29 05:55:15.113  4579  4663 D BtGatt.ScanManager: handling starting scan
,09-29 05:55:15.113  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 05:55:15.113  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 05:55:15.114  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 05:55:15.114  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-29 05:55:15.114  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 05:55:15.114  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 05:55:15.114  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-29 05:55:15.117  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-29 05:55:15.117  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 05:55:15.117  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 05:55:15.119  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 05:55:15.121  4579  4654 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 05:55:15.121  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:55:15.121  5644  5690 I io.jxcore.node.ConnectionHelper: start: OK
09-29 05:55:15.122  4579  4663 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-29 05:55:15.126  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:15.126  5644  5690 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-29 05:55:15.127  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:15.127  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-29 05:55:15.127  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:15.127  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 05:55:15.127  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:15.127  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 05:55:15.127  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 05:55:15.127  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-29 05:55:15.127  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 05:55:15.127  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 05:55:15.127  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-29 05:55:15.127  4579  4654 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 05:55:15.127  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:55:15.127  4579  4663 D BtGatt.ScanManager: Starting BLE batch scan
09-29 05:55:15.128  4579  4663 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 05:55:15.128  5644  5690 D BluetoothAdapter: STATE_ON
09-29 05:55:15.129  4579  4791 D BtGatt.GattService: stopScan() - queue size =1
,09-29 05:55:15.130  4579  4594 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-29 05:55:15.130  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 05:55:15.130  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 05:55:15.130  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 05:55:15.130  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 05:55:15.130  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 05:55:15.131  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 05:55:15.131  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-29 05:55:15.131  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 05:55:15.132  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:55:15.132  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 05:55:15.132  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 05:55:15.132  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 05:55:15.132  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-29 05:55:15.133  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-29 05:55:15.134  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:15.134  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:15.134  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:55:15.135  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:55:15.135  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:15.135  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:55:15.135  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:15.135  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:15.135  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:55:15.135  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
,09-29 05:55:15.135  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:15.135  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:55:15.136  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 05:55:15.136  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:15.139  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:15.139  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:15.139  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:15.139  4579  4654 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 05:55:15.139  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:55:15.139  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
,09-29 05:55:15.139  5644  5690 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-29 05:55:15.142  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:55:15.144  4579  4654 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-29 05:55:15.145  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:55:15.145  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:55:15.145  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:15.145  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:15.145  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:15.145  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:55:15.145  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:15.145  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:55:15.145  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:55:15.146  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:15.147  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:55:15.147  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 05:55:15.147  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 05:55:15.147  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 05:55:15.147  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:55:15.147  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 05:55:15.150  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:15.151  4579  4654 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-29 05:55:15.151  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:55:15.151  5644  5690 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 05:55:15.151  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 05:55:15.152  4579  4663 D BtGatt.ScanManager: stopping BLe Batch
09-29 05:55:15.153  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:15.155  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 05:55:15.156  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 05:55:15.156  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-29 05:55:15.157  4579  4654 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-29 05:55:15.158  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:55:15.158  4579  4663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-29 05:55:15.161  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-29 05:55:15.161  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 05:55:15.161  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 05:55:15.161  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 05:55:15.161  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 05:55:15.162  5644  5690 D BluetoothAdapter: STATE_ON
09-29 05:55:15.162  4579  4654 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-29 05:55:15.162  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:55:15.164  4579  4813 D BtGatt.GattService: registerClient() - UUID=a3eee108-9675-4744-aa2a-1d5246f69d18
09-29 05:55:15.164  4579  4654 D BtGatt.GattService: onClientRegistered() - UUID=a3eee108-9675-4744-aa2a-1d5246f69d18, clientIf=5
09-29 05:55:15.164  5644  5654 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 05:55:15.164  4579  4592 D BtGatt.GattService: start scan with filters
09-29 05:55:15.166  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 05:55:15.166  4579  4663 D BtGatt.ScanManager: handling starting scan
09-29 05:55:15.166  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 05:55:15.166  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 05:55:15.166  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-29 05:55:15.166  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 05:55:15.166  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 05:55:15.167  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-29 05:55:15.168   538   538 I ServiceManager: Waiting for service AtCmdFwd...
09-29 05:55:15.169  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 05:55:15.169  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 05:55:15.169  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 05:55:15.170  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 05:55:15.171  4579  4654 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 05:55:15.171  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:55:15.171  4579  4663 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-29 05:55:15.172  5644  5690 I io.jxcore.node.ConnectionHelper: start: OK
09-29 05:55:15.176  4579  4654 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 05:55:15.176  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:55:15.176  4579  4663 D BtGatt.ScanManager: Starting BLE batch scan
09-29 05:55:15.176  4579  4663 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 05:55:15.185  4579  4654 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 05:55:15.185  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 05:55:15.190  4579  4654 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-29 05:55:15.190  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 05:55:15.670  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-29 05:55:15.671  5644  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-29 05:55:15.671  5644  5644 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-29 05:55:16.169   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:17.169   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-29 05:55:20.172  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 05:55:20.172  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:20.173  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-29 05:55:20.173  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:20.173  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 05:55:20.173  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-29 05:55:20.173  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 05:55:20.173  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 05:55:20.173  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-29 05:55:20.174  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 05:55:20.174  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 05:55:20.174  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-29 05:55:20.176  5644  5690 D BluetoothAdapter: STATE_ON
09-29 05:55:20.177  4579  4812 D BtGatt.GattService: stopScan() - queue size =1
,09-29 05:55:20.179  4579  4791 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-29 05:55:20.180  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 05:55:20.180  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 05:55:20.181  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 05:55:20.181  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 05:55:20.181  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,09-29 05:55:20.181  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 05:55:20.181  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-29 05:55:20.181  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 05:55:20.184  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:55:20.184  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 05:55:20.184  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 05:55:20.185  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 05:55:20.185  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 05:55:20.186  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:55:20.189  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:55:20.189  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:55:20.189  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:55:20.190  4579  4579 D BtGatt.ScanManager: awakened up at time 247052
,09-29 05:55:20.204  4579  4654 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-29 05:55:20.204  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:55:20.205  4579  4663 D BtGatt.ScanManager: stopping BLe Batch
,09-29 05:55:20.215  4579  4654 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-29 05:55:20.215  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:55:20.215  4579  4663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-29 05:55:20.233  4579  4654 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
09-29 05:55:20.233  4579  4654 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:55:20.233  4579  4654 D BtGatt.GattService: current time is 247095811281
,09-29 05:55:20.233  4579  4654 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -75, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -78, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -9, -41, -38, 3, -84, 69, 1, -128, -91, 48, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 10, 0, 0, 35, 97, 126, -92, 22, -56, 1, -128, -75, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -71, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -73, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-29 05:55:20.233  4579  4654 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-29 05:55:20.234  4579  4654 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-29 05:55:20.234  4579  4654 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-29 05:55:20.234  4579  4654 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 10, 0]
09-29 05:55:20.234  4579  4654 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-29 05:55:20.234  4579  4654 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-29 05:55:20.235  4579  4654 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-29 05:55:20.690  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 05:55:20.691  5644  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:20.691  5644  5644 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-29 05:55:25.190  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 05:55:25.190  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:25.190  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:25.191  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:25.191  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.191  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-29 05:55:25.191  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:25.191  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:25.192  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:55:25.192  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.192  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 05:55:25.192  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.193  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 05:55:25.193  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:55:25.199  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-29 05:55:25.199  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:25.199  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.199  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.202  5644  5690 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-29 05:55:25.204  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:25.204  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:25.204  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:25.205  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 05:55:25.205  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.205  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.205  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:25.205  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
,09-29 05:55:25.205  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.205  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.206  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:25.206  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.206  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.206  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.206  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:55:25.210  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:25.210  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:25.211  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:55:25.211  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.214  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-29 05:55:25.215  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:25.215  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:25.215  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:25.216  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:25.216  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.216  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.216  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:25.216  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:25.216  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.217  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.217  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:25.217  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.218  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.218  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.218  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.219  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:25.220  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:25.220  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.220  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.221  5644  5690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-29 05:55:25.221  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:25.221  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:25.221  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:25.221  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:25.221  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.221  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.221  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:25.221  5644  5690 E org.thaliproject.p2p.bt,connectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:25.221  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.222  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.222  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:25.222  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.222  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.222  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.222  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.223  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:25.223  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:25.223  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.223  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.224  5644  5690 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-29 05:55:25.224  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:25.224  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:25.224  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:25.224  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:25.224  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.225  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.225  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:25.225  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:25.225  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.225  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.225  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:25.225  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.225  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.225  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.225  5644  5690 D org.thaliproj,ect.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.227  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:25.227  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:25.227  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.227  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.228  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-29 05:55:25.228  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 05:55:25.228  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 05:55:25.228  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-29 05:55:25.228  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:55:25.229  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:55:25.229  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-29 05:55:25.229  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 05:55:25.229  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 05:55:25.229  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:25.229  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-29 05:55:25.229  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-29 05:55:25.230  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 05:55:25.230  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.230  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.230  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:25.230  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:25.230  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.230  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.230  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:25.230  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.230  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.230  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.231  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.235  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-29 05:55:25.235  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:25.235  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.235  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.236  5644  5690 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 05:55:25.236  5644  5690 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-29 05:55:25.236  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-29 05:55:25.240  5644  5690 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-29 05:55:25.240  5644  5690 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-29 05:55:25.240  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-29 05:55:25.240  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-29 05:55:25.240  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-29 05:55:25.240  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-29 05:55:25.240  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-29 05:55:25.240  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-29 05:55:25.240  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-29 05:55:25.240  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-29 05:55:25.240  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-29 05:55:25.241  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-29 05:55:25.242  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-29 05:55:25.242  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-29 05:55:25.242  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-29 05:55:25.242  5644  5690 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-29 05:55:25.242  5644  5690 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 05:55:25.242  5644  5690 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-29 05:55:25.242  5644  5690 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 05:55:25.242  5644  5690 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 05:55:25.243  5644  5690 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-29 05:55:25.243  5644  5690 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 05:55:25.243  5644  5690 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 05:55:25.243  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-29 05:55:25.247  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-29 05:55:25.248  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-29 05:55:25.248  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-29 05:55:25.249  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-29 05:55:25.249  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-29 05:55:25.249  5644  5690 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-29 05:55:25.249  5644  5690 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 05:55:25.250  5644  5690 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-29 05:55:25.250  5644  5691 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-29 05:55:25.250  5644  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
09-29 05:55:25.250  5644  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
,09-29 05:55:25.250  5644  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,09-29 05:55:25.252  5644  5691 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
,09-29 05:55:25.252  5644  5691 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:55:25.252  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:25.252  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:25.253  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:25.253  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:25.253  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.253  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.253  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:25.253  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-29 05:55:25.255  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:25.255  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.255  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.255  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:25.255  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.255  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:55:25.255  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.255  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.251  4813  4813 W Binder_5: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[29662]" dev="sockfs" ino=29662 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 05:55:25.251  4813  4813 W Binder_5: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[29662]" dev="sockfs" ino=29662 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-29 05:55:25.256  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:25.257  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:25.257  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.257  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.258  5644  5690 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-29 05:55:25.259  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:25.259  5644  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-29 05:55:25.259  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:25.259  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-29 05:55:25.259  5644  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
09-29 05:55:25.259  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:25.259  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.259  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.259  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:25.259  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:25.259  5644  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
09-29 05:55:25.259  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.259  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
,09-29 05:55:25.259  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:25.259  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.259  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.259  5644  5691 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
09-29 05:55:25.259  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.260  5644  5691 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-29 05:55:25.260  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.260  5644  5691 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
09-29 05:55:25.260  4579  4789 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
09-29 05:55:25.260  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:25.261  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-29 05:55:25.261  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.261  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
,09-29 05:55:25.261  5644  5690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-29 05:55:25.262  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:25.262  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:25.262  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:25.262  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:25.262  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.262  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.262  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:25.263  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:25.263  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.263  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.263  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:25.263  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 05:55:25.263  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.263  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.263  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.264  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:25.264  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:25.264  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.264  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.265  5644  5690 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-29 05:55:25.265  5644  5690 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-29 05:55:25.265  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-29 05:55:25.265  5644  5690 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-29 05:55:25.265  5644  5690 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-29 05:55:25.265  5644  5690 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-29 05:55:25.265  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-29 05:55:25.265  5644  5690 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-29 05:55:25.265  5644  5690 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-29 05:55:25.265  5644  5690 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-29 05:55:25.265  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-29 05:55:25.265  5644  5690 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-29 05:55:25.265  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:25.265  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:25.265  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:25.265  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:25.265  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.266  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.266  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:25.266  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
,09-29 05:55:25.266  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.266  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.266  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:25.266  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.266  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.266  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.266  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.267  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:25.267  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:25.268  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:55:25.268  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:25.268  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:25.268  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.268  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:25.268  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:25.268  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:25.268  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:25.268  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
,09-29 05:55:25.268  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:25.268  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:25.268  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:55:27.172   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:28.173   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:29.174   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:30.175   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:30.269  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:55:30.270  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
,09-29 05:55:30.270  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 05:55:30.270  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 05:55:30.270  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:55:30.270  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:30.271  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:30.271  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:30.271  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:30.271  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-29 05:55:30.271  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:30.272  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.272  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:55:30.272  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:30.272  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:30.272  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:30.273  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
,09-29 05:55:30.273  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 05:55:30.273  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.273  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:55:30.273  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.273  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:30.276  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:30.276  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-29 05:55:30.276  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:30.277  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
,09-29 05:55:30.283  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-29 05:55:30.283  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:55:30.286  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-29 05:55:30.288  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-29 05:55:30.288  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
09-29 05:55:30.288  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-29 05:55:30.289  5644  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,09-29 05:55:30.289  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-29 05:55:30.289  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 05:55:30.289  5644  5644 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-29 05:55:30.290  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:30.290  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-29 05:55:30.290  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-29 05:55:30.290  5644  5693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:55:30.290  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-29 05:55:30.291  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:30.291  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-29 05:55:30.291  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-29 05:55:30.291  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:30.291  5644  5644 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-29 05:55:30.291  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:30.291  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-29 05:55:30.291  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 05:55:30.291  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 05:55:30.292  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.292  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:30.294  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:55:30.294  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
,09-29 05:55:30.294  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:55:30.294  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-29 05:55:30.291  4812  4812 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[29664]" dev="sockfs" ino=29664 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 05:55:30.294  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-29 05:55:30.291  4812  4812 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29664]" dev="sockfs" ino=29664 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 05:55:30.294  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:30.294  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:30.294  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:30.294  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.294  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:30.295  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,09-29 05:55:30.295  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:30.295  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:30.295  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:30.295  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:30.295  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.295  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:30.295  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.295  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:30.296  5644  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-29 05:55:30.296  5644  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-29 05:55:30.296  5644  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-29 05:55:30.297  5644  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-29 05:55:30.297  5644  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:30.298  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:30.298  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:30.298  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:55:30.298  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
,09-29 05:55:30.301  5644  5690 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-29 05:55:30.301  5644  5690 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-29 05:55:30.301  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-29 05:55:30.302  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:55:30.302  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:55:30.302  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:30.302  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:30.302  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:30.303  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:30.303  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.303  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:55:30.303  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:30.303  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:30.303  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:55:30.303  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
,09-29 05:55:30.303  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:30.303  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.303  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:30.303  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 05:55:30.303  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:30.306  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:30.306  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:30.306  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:30.306  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
,09-29 05:55:30.312  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 05:55:30.312  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:55:30.312  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:30.313  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:30.313  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.313  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:30.313  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:30.313  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:30.313  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:55:30.313  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:30.313  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:30.313  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.313  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:30.313  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.313  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:55:30.314  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:55:30.314  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:30.314  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:30.315  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:30.315  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:55:30.315  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-29 05:55:30.316  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:55:30.316  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:55:30.316  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.316  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:30.316  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:55:30.316  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5063d62 not in the list
09-29 05:55:30.316  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:55:30.316  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:30.316  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:30.316  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.316  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:30.316  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:30.316  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:55:30.317  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-29 05:55:30.317  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:55:30.317  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:55:30.317  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6282ef3 not in the list
09-29 05:55:30.318  5644  5690 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-29 05:55:30.319  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-29 05:55:30.319  5644  5690 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-29 05:55:30.319  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-29 05:55:30.319  5644  5690 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-29 05:55:30.319  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-29 05:55:30.321  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-29 05:55:30.321  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-29 05:55:30.322  5644  5690 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-29 05:55:30.322  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-29 05:55:30.322  5644  5690 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-29 05:55:30.322  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-29 05:55:30.323  5644  5690 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-29 05:55:30.323  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-29 05:55:30.323  5644  5690 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-29 05:55:30.323  5644  5690 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-29 05:55:30.324  5644  5690 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-29 05:55:30.324  5644  5690 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-29 05:55:30.324  5644  5690 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-29 05:55:30.324  5644  5690 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-29 05:55:30.325  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:55:30.325  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@884229d added. We now have 3 listener(s)
09-29 05:55:30.325  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 05:55:30.326  5644  5690 D BluetoothAdapter: enable(): BT is already enabled..!
09-29 05:55:30.327   928   938 D WifiService: setWifiEnabled: true pid=5644, uid=10077
09-29 05:55:30.327   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 05:55:30.380  4579  4784 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-29 05:55:30.380  4579  4784 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-29 05:55:30.795  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 05:55:31.176   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:32.176   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-29 05:55:34.639   928  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 05:55:35.332  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-29 05:55:35.333  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@53cc312 added. We now have 4 listener(s)
,09-29 05:55:35.333  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 05:55:35.345  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:55:35.345  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@53cc312 removed from the list
09-29 05:55:35.345  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 05:55:35.346  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:35.346  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:55:35.347  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:55:35.348  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3abae3 added. We now have 4 listener(s)
,09-29 05:55:35.348  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 05:55:35.351  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:55:35.351  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3abae3 removed from the list
,09-29 05:55:35.351  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:55:35.352  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:55:35.352  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:55:35.353  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:55:35.354  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c84ece0 added. We now have 4 listener(s)
09-29 05:55:35.354  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 05:55:35.360   928   938 D WifiService: setWifiEnabled: false pid=5644, uid=10077
,09-29 05:55:35.360   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 05:55:35.366   928  2941 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-29 05:55:35.366   928  2941 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-29 05:55:35.366   928  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 05:55:35.366   928  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-29 05:55:35.371  4579  4650 D BluetoothAdapterState: Current state: ON, message: 23
09-29 05:55:35.371  4579  4650 D BluetoothAdapterProperties: Setting state to 13
09-29 05:55:35.371  4579  4650 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-29 05:55:35.372  4579  4650 D BluetoothAdapterProperties: onBluetoothDisable()
,09-29 05:55:35.373  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:55:35.373  4579  4650 I BluetoothAdapterState: Entering PendingCommandState
,09-29 05:55:35.381  4579  4579 D BluetoothMapService: onReceive
,09-29 05:55:35.381  4579  4654 D BluetoothAdapterProperties: Scan Mode:20
09-29 05:55:35.381  4579  4579 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-29 05:55:35.382  4579  4579 D BluetoothMapService: STATE_TURNING_OFF
09-29 05:55:35.382  4579  4579 D BluetoothMapService: MAP Service closeService in
09-29 05:55:35.382  4579  4579 D BluetoothMapMasInstance0: MAP Service shutdown
09-29 05:55:35.382  4579  4579 D ObexServerSockets0: shutdown(block = true)
09-29 05:55:35.381  4579  4650 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-29 05:55:35.385  4579  4579 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 05:55:35.385  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.385  4579  4579 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 05:55:35.385  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:55:35.385  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:35.385  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:35.385  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:35.385  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:35.385  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:35.385  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:55:35.385  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:55:35.385  4579  4789 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-29 05:55:35.386  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.386  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:35.386  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:55:35.386   928  5390 D DhcpClient: Clearing IP address
09-29 05:55:35.387   510   922 D CommandListener: Clearing all IP addresses on wlan0
09-29 05:55:35.389  4579  4821 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-29 05:55:35.389  4579  4822 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-29 05:55:35.390   510   922 D CommandListener: Setting iface cfg
,09-29 05:55:35.390  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:35.390  4579  4579 I BtOppRfcommListener: stopping Accept Thread
09-29 05:55:35.391  4579  5306 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-29 05:55:35.391  4579  5306 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-29 05:55:35.392  3575  5445 V NativeCrypto: Read error: ssl=0x7f8aac8b80: I/O error during system call, Connection timed out
09-29 05:55:35.393  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:35.395   928  5391 D DhcpClient: Receive thread stopped
09-29 05:55:35.395  3575  5445 V NativeCrypto: SSL shutdown failed: ssl=0x7f8aac8b80: I/O error during system call, Broken pipe
09-29 05:55:35.397  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.397  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:35.397  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:35.397  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:35.397  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:35.397  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:35.397  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:35.397  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:55:35.397  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:55:35.397  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.398  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:35.398   928  3147 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-29 05:55:35.398   928  5388 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-29 05:55:35.400   928  5388 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-29 05:55:35.401   928  2949 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-29 05:55:35.401   928  2949 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-29 05:55:35.402  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.402  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:35.402  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:35.402  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:35.402  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:35.402  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:35.402  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:35.402  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/conn,ecting to active network: true
09-29 05:55:35.402  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:55:35.402  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.402  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:55:35.402   928  2949 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-29 05:55:35.408  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:35.412  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.412  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:35.412  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:35.412  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:35.412  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:35.412  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:35.412  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:35.412  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:55:35.412  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:55:35.413  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.413  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:55:35.417  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.417   928   941 I ActivityManager: Start proc 5697:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-29 05:55:35.417  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:35.417  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:35.417  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:35.417  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:35.417  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:35.417  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:35.417  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:55:35.417  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:55:35.420  4579  4579 D HeadsetService: Received stop request...Stopping profile...
09-29 05:55:35.420  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.420  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:55:35.422   928  2949 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-29 05:55:35.422   928  2949 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-29 05:55:35.426  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.426  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:35.426  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:35.426  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:35.426  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:35.426  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:35.426  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:35.426  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:55:35.426  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:55:35.427  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.427  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:55:35.427   928   928 D RttService: SCAN_AVAILABLE : 1
09-29 05:55:35.427   928  3063 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-29 05:55:35.427   536   536 E Parcel  : Reading a NULL string not supported here.
09-29 05:55:35.429   928   928 D BluetoothHeadset: Proxy object disconnected
09-29 05:55:35.429  3133  3145 D BluetoothHeadset: Proxy object disconnected
09-29 05:55:35.430  3759  3780 D BluetoothHeadset: Proxy object disconnected
09-29 05:55:35.430   928   928 D BluetoothHeadset: Proxy object disconnected
09-29 05:55:35.430   928   928 D BluetoothHeadset: Proxy object disconnected
09-29 05:55:35.431  4579  4579 D A2dpService: Received stop request...Stopping profile...
09-29 05:55:35.431  4579  4800 D A2dpStateMachine: Exit Disconnected: -1
09-29 05:55:35.432   928   928 D BluetoothA2dp: Proxy object disconnected
09-29 05:55:35.432  4579  4579 D HidService: Received stop request...Stopping profile...
09-29 05:55:35.432  4579  4579 D HidService: Stopping Bluetooth HidService
,09-29 05:55:35.434  4579  4579 D HealthService: Received stop request...Stopping profile...
09-29 05:55:35.434   928  2941 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-29 05:55:35.434   928  2949 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-29 05:55:35.435  3716  3880 W QCNEJ   : |CORE| network lost: 100
09-29 05:55:35.436  3716  3880 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-29 05:55:35.437  4579  4579 V BluetoothAdapterState: isTurningOff()=true
09-29 05:55:35.437  4579  4579 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:35.437  4579  4579 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:35.437  4579  4579 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:35.438  4579  4579 D PanService: Received stop request...Stopping profile...
09-29 05:55:35.439   928  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 05:55:35.440  4579  4579 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-29 05:55:35.440  4579  4579 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-29 05:55:35.440  4579  4654 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-29 05:55:35.440  4579  4784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:55:35.440  4579  4784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:55:35.441  4579  4784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:55:35.441  4579  4579 D BluetoothMapService: Received stop request...Stopping profile...
09-29 05:55:35.441  4579  4579 D BluetoothMapService: stop()
09-29 05:55:35.441  3133  3133 D HeadsetProfile: Bluetooth service disconnected
09-29 05:55:35.441  4579  4654 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-29 05:55:35.443  3133  3133 D BluetoothA2dp: Proxy object disconnected
09-29 05:55:35.444  3133  3133 D BluetoothInputDevice: Proxy object disconnected
09-29 05:55:35.444  3133  3133 D HidProfile: Bluetooth service disconnected
09-29 05:55:35.446  3133  3133 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-29 05:55:35.446  3133  3133 D PanProfile: Bluetooth service disconnected
09-29 05:55:35.447  4579  4579 D BluetoothMapAppObserver: deinitObservers()
09-29 05:55:35.448  4579  4579 D BluetoothMapAppObserver: removeReceiver()
09-29 05:55:35.450  4579  4579 D SapService: Received stop request...Stopping profile...
09-29 05:55:35.450  4579  4579 V SapService: stop()
09-29 05:55:35.451  4579  4579 V BluetoothAdapterState: isTurningOff()=true
09-29 05:55:35.451  4579  4579 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:35.452  4579  4579 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:35.452  4579  4579 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:35.453  4579  4579 V BluetoothAdapterState: isTurningOff()=true
09-29 05:55:35.453  4579  4579 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:35.453  4579  4579 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:35.453  4579  4579 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:35.453  4579  4579 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-29 05:55:35.453  4579  4579 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-29 05:55:35.453  4579  4579 V BluetoothAdapterState: isTurningOff()=true
09-29 05:55:35.453  4579  4579 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:35.453  4579  4579 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:35.454  4579  4579 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:35.454  4579  4579 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-29 05:55:35.454  4579  4579 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-29 05:55:35.455  4579  4579 V BluetoothAdapterState: isTurningOff()=true
09-29 05:55:35.455  4579  4579 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:35.455  4579  4579 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:35.455  4579  4579 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:35.455  4579  4654 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-29 05:55:35.455  4579  4784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:55:35.455  4579  4654 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-29 05:55:35.455  4579  4784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:55:35.456  4579  4654 E bt_btif : L2CAP - PSM: 0x0019vice_request: Unknown service being enabled
09-29 05:55:35.456  4579  4784 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 05:55:35.456  4579  4784 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 05:55:35.456  4579  4784 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 05:55:35.456  4579  4784 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 05:55:35.455  4579  4579 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-29 05:55:35.456  4579  4579 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-29 05:55:35.457  4579  4579 D BluetoothMapService: MAP Service closeService in
09-29 05:55:35.457  4579  4579 V BluetoothAdapterState: isTurningOff()=true
09-29 05:55:35.458  4579  4579 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:35.458  4579  4579 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:35.458  4579  4579 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:35.458  4579  4579 D BluetoothMapService: cleanup()
09-29 05:55:35.458  4579  4579 D BluetoothMapService: MAP Service closeService in
09-29 05:55:35.458  4579  4579 V BluetoothAdapterState: isTurningOff()=true
09-29 05:55:35.458  4579  4579 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:35.458  4579  4579 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:35.458  4579  4579 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:35.460  4579  4650 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-29 05:55:35.461  4579  4650 D BluetoothAdapterProperties: Setting state to 15
09-29 05:55:35.461  4579  4650 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-29 05:55:35.461  4579  4650 I BluetoothAdapterState: Entering BleOnState
,09-29 05:55:35.461  3133  3146 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:55:35.462  3133  3145 D BluetoothPan: onBluetoothStateChange on: false
09-29 05:55:35.462   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:55:35.462  3133  3959 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-29 05:55:35.464  3133  3133 D BluetoothMap: Proxy object disconnected
09-29 05:55:35.464  3133  3133 D MapProfile: Bluetooth service disconnected
09-29 05:55:35.465  3133  3146 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 05:55:35.466   510   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-29 05:55:35.466   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 05:55:35.466  3133  3145 D BluetoothMap: onBluetoothStateChange: up=false
09-29 05:55:35.466   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:55:35.467  3133  3959 D BluetoothPbap: onBluetoothStateChange: up=false
09-29 05:55:35.468   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-29 05:55:35.468  5697  5697 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-29 05:55:35.468  3759  3997 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:55:35.468  4579  4650 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-29 05:55:35.468  4579  4650 D BluetoothAdapterProperties: Setting state to 16
09-29 05:55:35.468  4579  4650 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-29 05:55:35.469  4579  4650 D BluetoothAdapterProperties: onBleDisable
09-29 05:55:35.469  4579  4650 I BluetoothAdapterState: Entering PendingCommandState
09-29 05:55:35.469  4579  4651 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-29 05:55:35.470  4579  4784 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-29 05:55:35.470  4579  4784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:55:35.471  4579  4654 D BluetoothAdapterProperties: Scan Mode:20
,09-29 05:55:35.475  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 05:55:35.475  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:35.475  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:35.475  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:35.475  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:35.475  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:35.475  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:35.475  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:35.475  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:35.476  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.477  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:35.477  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:35.477  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:35.477  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:35.477  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:35.477  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:35.477  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:35.477  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:35.479  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.479  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:35.479  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:35.479  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:35.479  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:35.479  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:35.479  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:35.479  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:35.479  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:35.481  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:35.482  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:35.484  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:35.490   510   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 05:55:35.490   510   922 D CommandListener: Clearing all IP addresses on wlan0
,09-29 05:55:35.490   510   922 D TetherController: Setting IP forward enable = 0
09-29 05:55:35.491   928  2949 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-29 05:55:35.492   928  2949 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-29 05:55:35.493   928   945 D Tethering: MasterInitialState.processMessage what=3
09-29 05:55:35.494   928  2941 D DhcpClient: doQuit
09-29 05:55:35.494   928  2941 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-29 05:55:35.495   928  5390 D DhcpClient: onQuitting
,09-29 05:55:35.495  5295  5295 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@bbbcd7 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-29 05:55:35.495  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:35.496  3444  3444 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-29 05:55:35.497  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:35.497  4935  4935 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-29 05:55:35.499  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.499  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:35.499  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:35.499  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:35.499  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:55:35.499  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:35.499  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:35.499  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:35.499  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:35.500  5053  5077 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-29 05:55:35.500  5053  5077 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-29 05:55:35.500  5053  5077 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-29 05:55:35.500  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.500  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:55:35.500  5053  5077 E SarControlService: no key has been found,reset the power
09-29 05:55:35.500  5053  5090 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-29 05:55:35.501  5053  5090 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-29 05:55:35.501  5053  5090 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-29 05:55:35.501  5078  5078 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 05:55:35.501  5078  5078 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-29 05:55:35.502  5053  5090 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-29 05:55:35.503  5053  5090 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-29 05:55:35.503  5053  5090 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-29 05:55:35.504  5078  5078 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 05:55:35.504  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.504  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:35.504  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:35.504  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:35.504  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:55:35.504  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:35.504  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:35.504  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:35.504  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:35.504  5078  5078 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-29 05:55:35.505  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.505  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:55:35.507  5078  5092 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1a83e35 HexData = [00000000ea03000000000000ffffffff]
09-29 05:55:35.507  5078  5092 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 05:55:35.507  5078  5092 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-29 05:55:35.507  5078  5078 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 05:55:35.508  5053  5063 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-29 05:55:35.508  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 05:55:35.508  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:35.508  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:35.508  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:35.508  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:55:35.508  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:35.508  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:35.508  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:35.508  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:35.508  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 05:55:35.508  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:35.508  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:55:35.509  5078  5092 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1a83e35 HexData = [00000000eb03000000000000ffffffff]
09-29 05:55:35.509  5078  5092 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 05:55:35.509  5078  5092 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-29 05:55:35.509  5078  5078 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-29 05:55:35.510  5053  5064 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-29 05:55:35.510  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:35.515   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d979ee0:true
09-29 05:55:35.515  3444  3444 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-29 05:55:35.515  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 05:55:35.518  3444  3444 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-29 05:55:35.528   928  3800 I ActivityManager: Start proc 5723:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-29 05:55:35.540  5697  5697 D LocalBluetoothProfileManager: Adding local MAP profile
,09-29 05:55:35.544  5697  5697 D BluetoothMap: Create BluetoothMap proxy object
,09-29 05:55:35.562   510   922 E Netd    : netlink response contains error (No such file or directory)
,09-29 05:55:35.563   928  2949 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-29 05:55:35.563   928  2949 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-29 05:55:35.565  5697  5697 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-29 05:55:35.572  5723  5723 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-29 05:55:35.582  5697  5697 D DockEventReceiver: finishStartingService: stopping service
,09-29 05:55:35.585  3444  3444 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-29 05:55:35.588   928   939 I ActivityManager: Killing 4979:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-29 05:55:35.601  3444  3444 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-29 05:55:35.675  4579  4654 I bt_hci  : shut_down
,09-29 05:55:35.679  4579  4666 D bt_hwcfg: hw_epilog_process
,09-29 05:55:35.679  4579  4666 I bt_vendor: low_power_mode_cb
,09-29 05:55:35.682  4579  4666 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-29 05:55:35.682  4579  4666 I bt_vendor: epilog_cb
09-29 05:55:35.682  4579  4666 I bt_hci  : epilog_finished_callback
,09-29 05:55:35.684  4579  4654 I bt_hci_h4: hal_close
,09-29 05:55:35.685  4579  4654 I bt_userial_vendor: device fd = 54 close
,09-29 05:55:35.706   928  2941 D wifi    : In wifi stop Hal
,09-29 05:55:35.706   928  2941 D wifi    : halHandle = 0x7f7455b900, mVM = 0x7f90b8d140, mCls = 0x100a02
09-29 05:55:35.706  5025  5025 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 05:55:35.706   928  3443 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-29 05:55:35.706   928  3443 D WifiHAL : Got a signal to exit!!!
09-29 05:55:35.706   928  3443 I WifiHAL : Exit wifi_event_loop
09-29 05:55:35.707   928  2941 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-29 05:55:35.707   928  2941 E WifiHAL : Event processing terminated
,09-29 05:55:35.707   928  2941 D wifi    : In wifi cleaned up handler
09-29 05:55:35.707   928  2941 I WifiHAL : Internal cleanup completed
09-29 05:55:35.708  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:35.710  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:35.712  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:35.712  4102  4216 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-29 05:55:35.730   928  3443 D wifi    : set interface wlan0 flags (DOWN)
,09-29 05:55:35.730   928  2941 D WifiNative-HAL: HAL event thread stopped successfully
,09-29 05:55:35.753  5723  5723 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-29 05:55:35.753  5723  5723 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 05:55:35.753  5723  5723 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 05:55:35.753  5723  5723 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.r.e.b(PG:170)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 05:55:35.753  5723  5723 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.r.k.d(PG:583)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.r.e.b(PG:170)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 05:55:35.753  5723  5723 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:55:35.753  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 05:55:35.754  5723  5723 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 05:55:35.754  5723  5723 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:55:35.754  5723  5723 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 05:55:35.760  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 05:55:35.765  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 05:55:35.772  5697  5697 D DockEventReceiver: finishStartingService: stopping service
09-29 05:55:35.775  3901  3901 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-29 05:55:35.778  3901  3901 D SystemUpdateService: onCreate
09-29 05:55:35.780  3901  3901 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-29 05:55:35.791  4579  4651 D bt_stack_manager: event_shut_down_stack finished.
09-29 05:55:35.791  4579  4650 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-29 05:55:35.793  4579  4650 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-29 05:55:35.793  4579  4579 D BtGatt.DebugUtils: handleDebugAction() action=null
09-29 05:55:35.793  3901  3901 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-29 05:55:35.794  4579  4579 D BtGatt.GattService: Received stop request...Stopping profile...
09-29 05:55:35.794  4579  4579 D BtGatt.GattService: stop()
09-29 05:55:35.794  4579  4579 D BtGatt.AdvertiseManager: advertise clients cleared
09-29 05:55:35.795  4579  4579 V BluetoothAdapterState: isTurningOff()=false
09-29 05:55:35.795  4579  4579 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:35.795  4579  4579 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:35.795  4579  4579 V BluetoothAdapterState: isBleTurningOff()=true
,09-29 05:55:35.796  4579  4650 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-29 05:55:35.796  4579  4650 D BluetoothAdapterProperties: Setting state to 10
09-29 05:55:35.796  4579  4650 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-29 05:55:35.796  4579  4650 I BluetoothAdapterState: Entering OffState
09-29 05:55:35.797   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-29 05:55:35.802  4579  4579 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-29 05:55:35.802  4579  4579 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-29 05:55:35.802  4579  4579 I BluetoothServiceJni: cleanupNative: return from cleanup
09-29 05:55:35.804  4579  4651 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-29 05:55:35.810  3901  5416 I iu.UploadsManager: num queued entries: 0
09-29 05:55:35.816  4579  4651 D bt_stack_manager: event_clean_up_stack finished.
09-29 05:55:35.816  4579  4579 I art     : System.exit called, status: 0
09-29 05:55:35.816  4579  4579 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-29 05:55:35.835  3901  3901 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-29 05:55:35.837  3901  3901 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-29 05:55:35.839  5419  5419 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-29 05:55:35.844  5419  5419 D SprintDMHelper: simOperator: 
09-29 05:55:35.844  5419  5419 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-29 05:55:35.845  3901  5756 I SystemUpdateService: active receiver: enabled
,09-29 05:55:35.865  3901  5416 I iu.UploadsManager: num updated entries: 0
,09-29 05:55:35.866  3901  5416 I iu.SyncManager: NEXT; no task
,09-29 05:55:35.867  5025  5759 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-29 05:55:35.869   928  3794 I ActivityManager: Start proc 5760:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-29 05:55:35.875   928  3179 I ActivityManager: Process com.android.bluetooth (pid 4579) has died
,09-29 05:55:35.885  3901  5756 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-29 05:55:35.902  5760  5760 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-29 05:55:35.909   928   939 I ActivityManager: Killing 5295:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-29 05:55:35.922  3901  5756 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-29 05:55:35.923  3901  5756 I SystemUpdateService: now status is 0 (complete)
09-29 05:55:35.923  3901  5756 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-29 05:55:35.923  3901  5756 I SystemUpdateService: file has been verified
09-29 05:55:35.923  3901  5756 I SystemUpdateService: OTA package size = 21989297
,09-29 05:55:35.934   928   945 D Tethering: InitialState.processMessage what=4
,09-29 05:55:35.947   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-29 05:55:35.947  3901  5756 I SystemUpdateService: showing system update notification
,09-29 05:55:35.973  3901  3901 D SystemUpdateService: onDestroy
09-29 05:55:35.975   928  3405 I ActivityManager: Killing 4677:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-29 05:55:36.121  5723  5744 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-29 05:55:36.132   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f515d7d:true
,09-29 05:55:36.564   510   922 D TetherController: Setting IP forward enable = 0
,09-29 05:55:40.389   928  3800 D WifiService: setWifiEnabled: true pid=5644, uid=10077
,09-29 05:55:40.389   928  3800 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 05:55:40.401   510   922 D SoftapController: Softap fwReload - Ok
,09-29 05:55:40.406   510   922 D CommandListener: Setting iface cfg
,09-29 05:55:40.407   510   922 D CommandListener: Trying to bring down wlan0
,09-29 05:55:40.408   510   922 D CommandListener: Clearing all IP addresses on wlan0
,09-29 05:55:40.415   928  2941 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-29 05:55:40.983   928  2941 D wifi    : set interface wlan0 flags (UP)
,09-29 05:55:40.983   928  2941 I WifiHAL : Initializing wifi
09-29 05:55:40.983   928  2941 I WifiHAL : Creating socket
,09-29 05:55:40.986   928  2941 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-29 05:55:40.986   928  2941 D wifi    : Did set static halHandle = 0x7f7455b900
,09-29 05:55:40.987   928  2941 D wifi    : halHandle = 0x7f7455b900, mVM = 0x7f90b8d140, mCls = 0x10195a
,09-29 05:55:40.988   928  2941 D wifi    : array field set
,09-29 05:55:40.988   928  2941 I WifiNative-HAL: interface[0] = wlan0
,09-29 05:55:40.989   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-29 05:55:40.991   928  5785 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547412621568
09-29 05:55:40.991   928  5785 D wifi    : waitForHalEvents called, vm = 0x7f90b8d140, obj = 0x10195a, env = 0x7f7457ce40
,09-29 05:55:40.996   928  2941 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-29 05:55:40.999   928  2941 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-29 05:55:41.005  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:41.007  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:41.009  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:41.070  5786  5786 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-29 05:55:41.085  5786  5786 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 05:55:41.140  5786  5786 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-29 05:55:41.140  5786  5786 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-29 05:55:42.010   928  2941 D WifiConfigStore: Loading config and enabling all networks 
,09-29 05:55:42.012  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:42.012  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:42.012  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:42.012  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:42.012  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:42.012  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:42.012  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:42.012  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:42.012  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:42.013  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:42.013  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:55:42.016  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:42.016  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:42.016  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:42.016  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:42.016  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:42.016  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:42.016  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:42.016  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:42.016  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:42.016  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:42.017  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:55:42.019  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:42.019  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:42.019  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:42.019  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:42.019  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:55:42.019  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:42.019  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:42.019  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:42.019  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:42.019  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:42.019  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:55:42.032   928  2941 D WifiConfigStore: loaded 0 passpoint configs
,09-29 05:55:42.033   928  2941 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-29 05:55:42.033   928  2941 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-29 05:55:42.035   928  2941 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-29 05:55:42.036   928  2941 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-29 05:55:42.036   928  2941 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-29 05:55:42.036   928  2941 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-29 05:55:42.036   928  2941 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-29 05:55:42.041   928  2941 D WifiNative-HAL: Setting external_sim to 1
,09-29 05:55:42.041  5025  5025 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 05:55:42.041   928  2941 D wifi    : setting dfs flag to true, 0x7f75abb280
09-29 05:55:42.042   928  2941 D WifiStateMachine: Setting OUI to DA-A1-19
09-29 05:55:42.042   928  2941 D wifi    : setting scan oui 0x7f75abb280
09-29 05:55:42.042   928  2941 D WifiHAL : Sending mac address OUI
,09-29 05:55:42.046   928  2941 E native  : do suspend false
,09-29 05:55:42.054   928   928 D RttService: SCAN_AVAILABLE : 3
09-29 05:55:42.054   928  2941 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-29 05:55:42.054   510   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-29 05:55:42.054   928  3063 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-29 05:55:42.055   510   922 D CommandListener: Setting iface cfg
,09-29 05:55:42.059   928  2940 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-29 05:55:42.059   928  2940 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-29 05:55:42.068   928  2940 D WifiNative-HAL: p2pGetDeviceAddress
,09-29 05:55:42.073   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=268936 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-29 05:55:42.074   928  2940 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-29 05:55:45.205  5786  5786 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 05:55:45.209  5786  5786 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 05:55:45.215  5786  5786 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 05:55:45.269   928  2941 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-29 05:55:45.270   928  2941 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-29 05:55:45.270   928  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 05:55:45.283   928  2941 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-29 05:55:45.317   928  2941 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-29 05:55:45.319  5786  5786 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-29 05:55:45.400   928  3800 D WifiService: setWifiEnabled: false pid=5644, uid=10077
09-29 05:55:45.400   928  3800 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 05:55:45.406   928   928 D RttService: SCAN_AVAILABLE : 1
,09-29 05:55:45.407   928  3063 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-29 05:55:45.424   928  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-29 05:55:45.425   510   922 D CommandListener: Clearing all IP addresses on wlan0
,09-29 05:55:45.431   928  2941 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-29 05:55:45.433  5786  5786 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-29 05:55:45.438  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:45.439  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:45.439  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:45.439  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:45.439  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:55:45.439  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:45.439  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:45.439  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:45.439  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:45.439  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:45.439  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:55:45.443  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 05:55:45.443  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:45.443  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:45.443  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:45.443  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:55:45.443  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:45.443  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:45.443  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:45.443  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:45.443  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:45.443  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:55:45.446  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:45.446  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:45.446  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:45.446  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:45.446  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:55:45.446  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:45.446  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:45.446  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:45.446  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:55:45.446  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:45.446  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:55:45.450  5786  5786 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-29 05:55:45.454  5786  5786 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,09-29 05:55:45.469  5786  5786 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-29 05:55:45.472  5786  5786 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-29 05:55:45.578   928  2941 D wifi    : In wifi stop Hal
,09-29 05:55:45.579   928  2941 D wifi    : halHandle = 0x7f7455b900, mVM = 0x7f90b8d140, mCls = 0x10195a
09-29 05:55:45.579   928  5785 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-29 05:55:45.579   928  5785 D WifiHAL : Got a signal to exit!!!
09-29 05:55:45.579   928  5785 I WifiHAL : Exit wifi_event_loop
09-29 05:55:45.581   928  2941 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-29 05:55:45.581   928  2941 E WifiHAL : Event processing terminated
09-29 05:55:45.585  5025  5025 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-29 05:55:45.585   928  2941 D wifi    : In wifi cleaned up handler
,09-29 05:55:45.586   928  2941 I WifiHAL : Internal cleanup completed
09-29 05:55:45.588  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:45.592  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:45.593  4102  4216 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-29 05:55:45.593  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:45.614   928  5785 D wifi    : set interface wlan0 flags (DOWN)
,09-29 05:55:45.614   928  2941 D WifiNative-HAL: HAL event thread stopped successfully
,09-29 05:55:45.818   928   945 D Tethering: InitialState.processMessage what=4
,09-29 05:55:45.821   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-29 05:55:47.178   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:48.179   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:49.181   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:50.182   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:50.442   928   945 I ActivityManager: Start proc 5790:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-29 05:55:50.542  5790  5790 D AdapterServiceConfig: Adding HeadsetService
,09-29 05:55:50.543  5790  5790 D AdapterServiceConfig: Adding A2dpService
09-29 05:55:50.543  5790  5790 D AdapterServiceConfig: Adding HidService
09-29 05:55:50.543  5790  5790 D AdapterServiceConfig: Adding HealthService
09-29 05:55:50.543  5790  5790 D AdapterServiceConfig: Adding PanService
09-29 05:55:50.544  5790  5790 D AdapterServiceConfig: Adding GattService
09-29 05:55:50.544  5790  5790 D AdapterServiceConfig: Adding BluetoothMapService
09-29 05:55:50.544  5790  5790 D AdapterServiceConfig: Adding SapService
,09-29 05:55:50.556   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eb17e22:true
,09-29 05:55:50.557  5790  5790 D BluetoothAdapterState: make() - Creating AdapterState
,09-29 05:55:50.560  5790  5790 I bt_bluedroid: init
,09-29 05:55:50.561  5790  5802 I BluetoothAdapterState: Entering OffState
,09-29 05:55:50.563  5790  5803 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-29 05:55:50.564  5790  5803 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-29 05:55:50.564  5790  5803 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-29 05:55:50.564  5790  5803 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-29 05:55:50.565  5790  5790 I bt_bluedroid: get_profile_interface socket
,09-29 05:55:50.566  5790  5790 I bt_bluedroid: get_profile_interface sdp
09-29 05:55:50.566  5790  5806 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 05:55:50.568  5790  5806 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 05:55:50.572  5790  5801 I bt_bluedroid: config_hci_snoop_log
,09-29 05:55:50.573   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-29 05:55:50.578  5790  5802 D BluetoothAdapterState: Current state: OFF, message: 0
09-29 05:55:50.578  5790  5802 D BluetoothAdapterProperties: Setting state to 14
09-29 05:55:50.578  5790  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-29 05:55:50.580  5790  5802 D BluetoothBondStateMachine: make
,09-29 05:55:50.582  5790  5807 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-29 05:55:50.585  5790  5802 I BluetoothAdapterState: Entering PendingCommandState
,09-29 05:55:50.586  5790  5790 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-29 05:55:50.589  5790  5790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
,09-29 05:55:50.589  5790  5790 D BtGatt.DebugUtils: handleDebugAction() action=null
09-29 05:55:50.590  5790  5790 D BtGatt.GattService: Received start request. Starting profile...
09-29 05:55:50.590  5790  5790 D BtGatt.GattService: start()
09-29 05:55:50.590  5790  5790 I bt_bluedroid: get_profile_interface gatt
,09-29 05:55:50.591  5790  5790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
09-29 05:55:50.592  5790  5790 D BtGatt.AdvertiseManager: advertise manager created
,09-29 05:55:50.597  5790  5790 V BluetoothAdapterState: isTurningOff()=false
,09-29 05:55:50.597  5790  5790 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:50.597  5790  5790 V BluetoothAdapterState: isBleTurningOn()=true
09-29 05:55:50.597  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 05:55:50.597  5790  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-29 05:55:50.599  5790  5802 I bt_bluedroid: bt_bluedroid
,09-29 05:55:50.599  5790  5803 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-29 05:55:50.599  5790  5803 I bt_hci  : start_up
,09-29 05:55:50.605  5790  5803 I bt_vendor: alloc value 0xf3b99871
,09-29 05:55:50.605  5790  5803 I bt_vendor: init
09-29 05:55:50.605  5790  5803 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-29 05:55:50.605  5790  5803 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-29 05:55:50.718  5790  5803 D bt_hci  : start_up starting async portion
,09-29 05:55:50.718  5790  5810 I bt_hci  : event_finish_startup
,09-29 05:55:50.719  5790  5810 I bt_hci_h4: hal_open
09-29 05:55:50.719  5790  5810 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-29 05:55:50.722  5790  5810 I bt_userial_vendor: device fd = 54 open
,09-29 05:55:50.717  5811  5811 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 05:55:50.739  5790  5810 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 05:55:50.743  5790  5810 D bt_hwcfg: Chipset BCM4358A3
,09-29 05:55:50.743  5790  5810 D bt_hwcfg: Target name = [BCM4358A3]
09-29 05:55:50.744  5790  5810 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-29 05:55:51.183   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:55:51.258  5790  5810 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-29 05:55:51.258  5790  5810 D bt_hwcfg: Settlement delay -- 100 ms
,09-29 05:55:51.258  5790  5810 I bt_hwcfg: Setting fw settlement delay to 100 
,09-29 05:55:51.392  5790  5810 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 05:55:51.393  5790  5810 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-29 05:55:51.394  5790  5810 I bt_hwcfg: vendor lib fwcfg completed
,09-29 05:55:51.395  5790  5810 I bt_vendor: firmware callback
,09-29 05:55:51.395  5790  5810 I bt_hci  : firmware_config_callback
09-29 05:55:51.404  5790  5813 I bt_btu  : btu_task pending for preload complete event
,09-29 05:55:51.404  5790  5813 I bt_btu_task: Bluetooth chip preload is complete
09-29 05:55:51.404  5790  5813 I bt_btu  : btu_task received preload complete event
,09-29 05:55:51.411  5790  5813 I         : BTE_InitTraceLevels -- TRC_HCI
,09-29 05:55:51.412  5790  5813 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-29 05:55:51.412  5790  5813 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-29 05:55:51.412  5790  5813 I         : BTE_InitTraceLevels -- TRC_AVDT
09-29 05:55:51.412  5790  5813 I         : BTE_InitTraceLevels -- TRC_AVRC
09-29 05:55:51.412  5790  5813 I         : BTE_InitTraceLevels -- TRC_A2D
09-29 05:55:51.412  5790  5813 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-29 05:55:51.412  5790  5813 I         : BTE_InitTraceLevels -- TRC_BTM
09-29 05:55:51.412  5790  5813 I         : BTE_InitTraceLevels -- TRC_GAP
09-29 05:55:51.413  5790  5813 I         : BTE_InitTraceLevels -- TRC_PAN
09-29 05:55:51.413  5790  5813 I         : BTE_InitTraceLevels -- TRC_SDP
09-29 05:55:51.413  5790  5813 I         : BTE_InitTraceLevels -- TRC_GATT
,09-29 05:55:51.413  5790  5813 I         : BTE_InitTraceLevels -- TRC_SMP
09-29 05:55:51.413  5790  5813 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-29 05:55:51.413  5790  5813 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-29 05:55:51.503  5790  5813 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b17549
,09-29 05:55:51.503  5790  5813 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b17549 
,09-29 05:55:51.518  5790  5806 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-29 05:55:51.520  5790  5806 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-29 05:55:51.521  5790  5806 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 05:55:51.524  5790  5806 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 05:55:51.527  5790  5806 D BluetoothAdapterProperties: Scan Mode:20
09-29 05:55:51.528  5790  5806 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 05:55:51.528  5790  5806 D bt_hci  : do_postload posting postload work item
09-29 05:55:51.528  5790  5810 I bt_hci  : event_postload
09-29 05:55:51.528  5790  5810 I bt_vendor: sco_config_cb
09-29 05:55:51.528  5790  5810 I bt_hci  : sco_config_callback postload finished.
09-29 05:55:51.530  5790  5806 D bt_bte_conf: Device ID record 1 : primary
09-29 05:55:51.531  5790  5806 D bt_bte_conf:   vendorId            = 000f
09-29 05:55:51.531  5790  5806 D bt_bte_conf:   vendorIdSource      = 0001
09-29 05:55:51.531  5790  5806 D bt_bte_conf:   product             = 1200
09-29 05:55:51.531  5790  5806 D bt_bte_conf:   version             = 1436
09-29 05:55:51.531  5790  5806 D bt_bte_conf:   clientExecutableURL = 
09-29 05:55:51.531  5790  5806 D bt_bte_conf:   serviceDescription  = 
09-29 05:55:51.531  5790  5806 D bt_bte_conf:   documentationURL    = 
09-29 05:55:51.531  5790  5806 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-29 05:55:51.534  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:51.537  5790  5810 I bt_vendor: low_power_mode_cb
09-29 05:55:51.538  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:51.541  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:51.542  5790  5803 D bt_stack_manager: event_start_up_stack finished
,09-29 05:55:51.543  5790  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-29 05:55:51.543  5790  5802 D BluetoothAdapterProperties: Setting state to 15
09-29 05:55:51.543  5790  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-29 05:55:51.544  5790  5802 I BluetoothAdapterState: Entering BleOnState
,09-29 05:55:51.549  5790  5802 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-29 05:55:51.549  5790  5802 D BluetoothAdapterProperties: Setting state to 11
,09-29 05:55:51.549  5790  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-29 05:55:51.555  5790  5790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
,09-29 05:55:51.556  5790  5790 D HeadsetService: Received start request. Starting profile...
09-29 05:55:51.559  5790  5790 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-29 05:55:51.559  5790  5790 D HeadsetStateMachine: make
,09-29 05:55:51.563  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:51.566  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:51.569  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:51.575  5790  5790 D HeadsetStateMachine: max_hf_connections = 1
,09-29 05:55:51.575  5790  5790 I bt_bluedroid: get_profile_interface handsfree
09-29 05:55:51.577  5790  5806 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-29 05:55:51.578  5790  5806 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-29 05:55:51.578  5790  5802 I BluetoothAdapterState: Entering PendingCommandState
09-29 05:55:51.579  5790  5790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
09-29 05:55:51.580  5790  5790 D A2dpService: Received start request. Starting profile...
09-29 05:55:51.580  5790  5790 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-29 05:55:51.580  5790  5790 I bt_bluedroid: get_profile_interface avrcp
,09-29 05:55:51.586  5790  5790 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-29 05:55:51.586  5790  5790 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-29 05:55:51.586  5790  5790 D A2dpStateMachine: make
,09-29 05:55:51.588  5790  5790 I bt_bluedroid: get_profile_interface a2dp
,09-29 05:55:51.589  5790  5806 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-29 05:55:51.590  5790  5822 D A2dpStateMachine: Enter Disconnected: -2
09-29 05:55:51.590  5790  5790 I BluetoothHidServiceJni: classInitNative: succeeds
09-29 05:55:51.591  5790  5790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
,09-29 05:55:51.592  5790  5790 D HidService: Received start request. Starting profile...
,09-29 05:55:51.592  5790  5790 I bt_bluedroid: get_profile_interface hidhost
09-29 05:55:51.593  5790  5790 D HidService: setHidService(): set to: null
09-29 05:55:51.593  5790  5806 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3af856d
09-29 05:55:51.593  5790  5806 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-29 05:55:51.593  5697  5697 D BluetoothInputDevice: Proxy object connected
,09-29 05:55:51.594  5790  5790 I BluetoothHealthServiceJni: classInitNative: succeeds
09-29 05:55:51.595  5790  5790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
09-29 05:55:51.596  5697  5697 D HidProfile: Bluetooth service connected
09-29 05:55:51.596  5790  5790 D HealthService: Received start request. Starting profile...
,09-29 05:55:51.596  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 05:55:51.597  5790  5790 I bt_bluedroid: get_profile_interface health
,09-29 05:55:51.599  5790  5790 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-29 05:55:51.600  5790  5790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
,09-29 05:55:51.601  5697  5697 D BluetoothPan: BluetoothPAN Proxy object connected
,09-29 05:55:51.602  5697  5697 D PanProfile: Bluetooth service connected
,09-29 05:55:51.602  5790  5790 D PanService: Received start request. Starting profile...
09-29 05:55:51.602  5790  5790 D BluetoothPanServiceJni: initializeNative(L110): pan
09-29 05:55:51.602  5790  5790 I bt_bluedroid: get_profile_interface pan
09-29 05:55:51.603  5790  5806 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-29 05:55:51.605  5790  5790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
09-29 05:55:51.606  5790  5790 D BluetoothMapService: Received start request. Starting profile...
09-29 05:55:51.606  5697  5697 D BluetoothMap: Proxy object connected
09-29 05:55:51.607  5790  5790 D BluetoothMapService: start()
09-29 05:55:51.607  5697  5697 D MapProfile: Bluetooth service connected
09-29 05:55:51.607  5697  5697 D BluetoothMap: getConnectedDevices()
09-29 05:55:51.608  5697  5697 D BluetoothMap: Bluetooth is Not enabled
,09-29 05:55:51.609  5790  5790 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-29 05:55:51.610  5790  5790 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-29 05:55:51.610  5790  5790 D BluetoothMapAppObserver: createReceiver()
,09-29 05:55:51.611  5790  5790 D BluetoothMapAppObserver: initObservers()
,09-29 05:55:51.612  5790  5790 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-29 05:55:51.618  5790  5790 V SapService: SapBinder()
09-29 05:55:51.618  5790  5790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
09-29 05:55:51.618  5790  5790 D SapService: Received start request. Starting profile...
,09-29 05:55:51.618  5790  5790 V SapService: start()
09-29 05:55:51.619  5790  5790 V BluetoothAdapterState: isTurningOff()=false
09-29 05:55:51.620  5790  5790 V BluetoothAdapterState: isTurningOn()=true
09-29 05:55:51.620  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:51.620  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:51.620  5790  5790 V BluetoothAdapterState: isTurningOff()=false
,09-29 05:55:51.620  5790  5790 V BluetoothAdapterState: isTurningOn()=true
09-29 05:55:51.620  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:51.620  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:51.620  5790  5818 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-29 05:55:51.620  5790  5790 V BluetoothAdapterState: isTurningOff()=false
09-29 05:55:51.620  5790  5790 V BluetoothAdapterState: isTurningOn()=true
09-29 05:55:51.620  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:51.620  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:51.621  5790  5790 V BluetoothAdapterState: isTurningOff()=false
09-29 05:55:51.621  5790  5790 V BluetoothAdapterState: isTurningOn()=true
09-29 05:55:51.621  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:51.621  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:51.621  5790  5790 V BluetoothAdapterState: isTurningOff()=false
09-29 05:55:51.621  5790  5790 V BluetoothAdapterState: isTurningOn()=true
09-29 05:55:51.621  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:51.621  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:51.622  5790  5790 V BluetoothAdapterState: isTurningOff()=false
09-29 05:55:51.622  5790  5790 V BluetoothAdapterState: isTurningOn()=true
09-29 05:55:51.622  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:51.622  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:51.622  5790  5790 V BluetoothAdapterState: isTurningOff()=false
09-29 05:55:51.622  5790  5790 V BluetoothAdapterState: isTurningOn()=true
09-29 05:55:51.623  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:51.623  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:51.623  5790  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-29 05:55:51.623  5790  5802 D BluetoothAdapterProperties: ScanMode =  20
,09-29 05:55:51.623  5790  5802 D BluetoothAdapterProperties: State =  11
09-29 05:55:51.624  5790  5802 D BluetoothAdapterProperties: Setting state to 12
09-29 05:55:51.624  5790  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-29 05:55:51.624  3133  3146 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:55:51.625  3133  3959 D BluetoothPan: onBluetoothStateChange on: true
09-29 05:55:51.625  5790  5806 D BluetoothAdapterProperties: Scan Mode:21
09-29 05:55:51.625  5790  5806 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 05:55:51.626  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-29 05:55:51.627  5790  5802 I BluetoothAdapterState: Entering OnState
09-29 05:55:51.627  3133  3133 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 05:55:51.627  3133  3133 D PanProfile: Bluetooth service connected
09-29 05:55:51.627   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:55:51.627  5697  5709 D BluetoothMap: onBluetoothStateChange: up=true
09-29 05:55:51.628  3133  3145 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 05:55:51.630  3133  3133 D BluetoothInputDevice: Proxy object connected
09-29 05:55:51.630  5697  5710 D BluetoothPbap: onBluetoothStateChange: up=true
09-29 05:55:51.630  3133  3133 D HidProfile: Bluetooth service connected
09-29 05:55:51.631  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:51.631  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:51.631  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:51.631  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:55:51.631  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:55:51.631  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:51.631  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:51.631  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:51.631  3133  3146 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-29 05:55:51.633   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 05:55:51.633  3133  3145 D BluetoothMap: onBluetoothStateChange: up=true
09-29 05:55:51.633  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:55:51.634   928   928 D BluetoothA2dp: Proxy object connected
09-29 05:55:51.634  3133  3133 D BluetoothA2dp: Proxy object connected
09-29 05:55:51.635  5697  5709 D BluetoothPan: onBluetoothStateChange on: true
09-29 05:55:51.635   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:55:51.636  3133  3959 D BluetoothPbap: onBluetoothStateChange: up=true
09-29 05:55:51.636  3133  3133 D BluetoothMap: Proxy object connected
09-29 05:55:51.636  3133  3133 D MapProfile: Bluetooth service connected
09-29 05:55:51.636  3133  3133 D BluetoothMap: getConnectedDevices()
09-29 05:55:51.637  5790  5790 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-29 05:55:51.637  5697  5710 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-29 05:55:51.638   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:55:51.638  5790  5790 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-29 05:55:51.638  3759  3997 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:55:51.640   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-29 05:55:51.641  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:51.641  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:51.641  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:51.641  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:55:51.641  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:55:51.641  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:51.641  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:51.641  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:55:51.644  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:55:51.645  5697  5697 D LocalBluetoothProfileManager: Adding local A2DP profile
09-29 05:55:51.645  5790  5790 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:55:51.648  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:51.648  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:51.648  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:51.648  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:55:51.648  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:55:51.648  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:51.648  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:51.648  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:51.649  5790  5790 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 05:55:51.649  5697  5697 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-29 05:55:51.650  5790  5790 D ObexServerSockets: Succeed to create listening sockets 
09-29 05:55:51.651  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:55:51.651  5790  5790 D ObexServerSockets0: startAccept()
09-29 05:55:51.651  5790  5790 D ObexServerSockets0: prepareForNewConnect()
09-29 05:55:51.651  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-29 05:55:51.653  5790  5790 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-29 05:55:51.653  5790  5790 D BluetoothSdpJni: SDP Create record success - handle: 0
09-29 05:55:51.653  5790  5790 D BluetoothMapService: onReceive
,09-29 05:55:51.653  5790  5828 D ObexServerSockets0: Accepting socket connection...
09-29 05:55:51.653  5790  5790 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 05:55:51.653  5790  5790 D BluetoothMapService: STATE_ON
09-29 05:55:51.653  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:51.654  5790  5829 D ObexServerSockets0: Accepting socket connection...
,09-29 05:55:51.655  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:51.655  5790  5830 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:55:51.656  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:51.657  5790  5830 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-29 05:55:51.657  5790  5830 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-29 05:55:51.661  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 05:55:51.664  5697  5697 D BluetoothA2dp: Proxy object connected
,09-29 05:55:51.668  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 05:55:51.669  5697  5697 D DockEventReceiver: finishStartingService: stopping service
,09-29 05:55:51.674  5697  5697 D BluetoothPbap: Proxy object connected
,09-29 05:55:51.675  5697  5697 D PbapServerProfile: Bluetooth service connected
,09-29 05:55:51.677  3133  3133 D BluetoothPbap: Proxy object connected
,09-29 05:55:51.677  3133  3133 D PbapServerProfile: Bluetooth service connected
,09-29 05:55:51.681  5790  5790 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-29 05:55:51.681  5790  5790 D ObexServerSockets0: prepareForNewConnect()
,09-29 05:55:51.683  5790  5834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 05:55:51.697  5790  5838 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 05:55:51.698  5790  5838 I BtOppRfcommListener: Accept thread started.
,09-29 05:55:51.726   928   928 D BluetoothHeadset: Proxy object connected
,09-29 05:55:51.727  3133  3145 D BluetoothHeadset: Proxy object connected
09-29 05:55:51.727  3133  3133 D HeadsetProfile: Bluetooth service connected
09-29 05:55:51.727  3759  3780 D BluetoothHeadset: Proxy object connected
09-29 05:55:51.727   928   928 D BluetoothHeadset: Proxy object connected
09-29 05:55:51.727   928   928 D BluetoothHeadset: Proxy object connected
,09-29 05:55:51.728   928   945 D BluetoothHeadset: Proxy object connected
,09-29 05:55:51.736   928   945 D BluetoothHeadset: Proxy object connected
,09-29 05:55:51.739   928   945 D BluetoothHeadset: Proxy object connected
,09-29 05:55:51.739  3759  3781 D BluetoothHeadset: Proxy object connected
,09-29 05:55:51.759  5697  5710 D BluetoothHeadset: Proxy object connected
,09-29 05:55:51.763  5697  5697 D HeadsetProfile: Bluetooth service connected
,09-29 05:55:52.184   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-29 05:55:55.419  5790  5802 D BluetoothAdapterState: Current state: ON, message: 23
09-29 05:55:55.419  5790  5802 D BluetoothAdapterProperties: Setting state to 13
,09-29 05:55:55.419  5790  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-29 05:55:55.420  5790  5802 D BluetoothAdapterProperties: onBluetoothDisable()
09-29 05:55:55.422  5790  5802 I BluetoothAdapterState: Entering PendingCommandState
,09-29 05:55:55.426  5790  5806 D BluetoothAdapterProperties: Scan Mode:20
,09-29 05:55:55.426  5790  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-29 05:55:55.428  5790  5790 D BluetoothMapService: onReceive
09-29 05:55:55.429  5790  5790 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 05:55:55.429  5790  5790 D BluetoothMapService: STATE_TURNING_OFF,
,09-29 05:55:55.429  5790  5790 D BluetoothMapService: MAP Service closeService in
09-29 05:55:55.430  5790  5790 D BluetoothMapMasInstance0: MAP Service shutdown
,09-29 05:55:55.430  5790  5790 D ObexServerSockets0: shutdown(block = true)
09-29 05:55:55.432  5790  5790 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-29 05:55:55.432  5790  5790 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 05:55:55.433  5790  5829 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-29 05:55:55.438  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:55.438  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:55.438  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:55.438  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:55.438  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:55:55.438  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:55.438  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:55.438  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:55.438  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:55.438  5790  5828 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-29 05:55:55.437  5790  5815 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-29 05:55:55.439  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 05:55:55.439  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 05:55:55.439  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:55:55.442  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:55.442  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:55.442  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:55.442  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:55.442  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:55:55.442  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:55.442  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:55.442  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:55.442  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:55.443  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:55:55.443  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:55:55.444  5790  5790 I BtOppRfcommListener: stopping Accept Thread
09-29 05:55:55.444  5790  5838 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-29 05:55:55.445  5790  5838 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-29 05:55:55.449  5790  5790 D HeadsetService: Received stop request...Stopping profile...
09-29 05:55:55.449  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 05:55:55.449  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:55:55.449  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:55:55.449  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:55:55.449  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:55:55.449  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:55:55.449  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:55:55.449  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:55:55.449  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:55:55.450  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 05:55:55.450  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:55:55.452  5697  5710 D BluetoothHeadset: Proxy object disconnected
09-29 05:55:55.452   928   928 D BluetoothHeadset: Proxy object disconnected
09-29 05:55:55.452  5790  5790 D A2dpService: Received stop request...Stopping profile...
,09-29 05:55:55.452  5790  5822 D A2dpStateMachine: Exit Disconnected: -1
,09-29 05:55:55.452  3133  3959 D BluetoothHeadset: Proxy object disconnected
09-29 05:55:55.453  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:55.453  3759  3997 D BluetoothHeadset: Proxy object disconnected
09-29 05:55:55.453   928   928 D BluetoothHeadset: Proxy object disconnected
09-29 05:55:55.454   928   928 D BluetoothHeadset: Proxy object disconnected
09-29 05:55:55.454   928   928 D BluetoothA2dp: Proxy object disconnected
09-29 05:55:55.455  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:55.455  5790  5790 D HidService: Received stop request...Stopping profile...
09-29 05:55:55.455  5790  5790 D HidService: Stopping Bluetooth HidService
09-29 05:55:55.456  5790  5790 D HealthService: Received stop request...Stopping profile...
09-29 05:55:55.456  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:55.458  5790  5790 D PanService: Received stop request...Stopping profile...
09-29 05:55:55.461  5697  5697 D DockEventReceiver: finishStartingService: stopping service
09-29 05:55:55.462  5697  5697 D HeadsetProfile: Bluetooth service disconnected
09-29 05:55:55.463  5697  5697 D BluetoothA2dp: Proxy object disconnected
09-29 05:55:55.463  5697  5697 D BluetoothInputDevice: Proxy object disconnected
09-29 05:55:55.463  5697  5697 D HidProfile: Bluetooth service disconnected
09-29 05:55:55.464  5697  5697 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-29 05:55:55.464  5697  5697 D PanProfile: Bluetooth service disconnected
09-29 05:55:55.464  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 05:55:55.466  5790  5790 D BluetoothMapService: Received stop request...Stopping profile...
09-29 05:55:55.466  5790  5790 D BluetoothMapService: stop()
09-29 05:55:55.467  5790  5790 D BluetoothMapAppObserver: deinitObservers()
09-29 05:55:55.467  5790  5790 D BluetoothMapAppObserver: removeReceiver()
09-29 05:55:55.468  3133  3133 D HeadsetProfile: Bluetooth service disconnected
09-29 05:55:55.469  3133  3133 D BluetoothA2dp: Proxy object disconnected
09-29 05:55:55.469  5790  5790 V BluetoothAdapterState: isTurningOff()=true
,09-29 05:55:55.469  5790  5790 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:55.469  3133  3133 D BluetoothInputDevice: Proxy object disconnected
09-29 05:55:55.469  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:55.469  3133  3133 D HidProfile: Bluetooth service disconnected
09-29 05:55:55.469  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:55.469  3133  3133 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-29 05:55:55.469  3133  3133 D PanProfile: Bluetooth service disconnected
09-29 05:55:55.469  3133  3133 D BluetoothMap: Proxy object disconnected
,09-29 05:55:55.469  3133  3133 D MapProfile: Bluetooth service disconnected
09-29 05:55:55.469  5790  5790 D SapService: Received stop request...Stopping profile...
,09-29 05:55:55.470  5790  5790 V SapService: stop()
09-29 05:55:55.472  5790  5790 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-29 05:55:55.472  5790  5790 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-29 05:55:55.472  5790  5806 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-29 05:55:55.472  5790  5813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:55:55.472  5790  5790 V BluetoothAdapterState: isTurningOff()=true
09-29 05:55:55.472  5790  5813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:55:55.473  5790  5790 V BluetoothAdapterState: isTurningOn()=false
,09-29 05:55:55.473  5790  5813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:55:55.473  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:55.473  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:55.473  5790  5806 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-29 05:55:55.474  5697  5697 D BluetoothMap: Proxy object disconnected
09-29 05:55:55.474  5790  5806 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-29 05:55:55.474  5697  5697 D MapProfile: Bluetooth service disconnected
09-29 05:55:55.474  5790  5813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:55:55.474  5790  5813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:55:55.474  5790  5813 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-29 05:55:55.474  5790  5813 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 05:55:55.474  5790  5813 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 05:55:55.474  5790  5813 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-29 05:55:55.478  5790  5790 V BluetoothAdapterState: isTurningOff()=true
,09-29 05:55:55.478  5790  5790 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:55.478  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:55.478  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:55.478  5790  5790 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-29 05:55:55.478  5790  5790 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-29 05:55:55.478  5790  5790 V BluetoothAdapterState: isTurningOff()=true
09-29 05:55:55.478  5790  5790 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:55.478  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:55.478  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:55.479  5790  5806 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-29 05:55:55.479  5790  5790 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-29 05:55:55.479  5790  5806 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-29 05:55:55.479  5790  5790 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-29 05:55:55.479  5790  5790 V BluetoothAdapterState: isTurningOff()=true
09-29 05:55:55.479  5790  5790 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:55.479  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:55.479  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:55.480  5790  5790 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-29 05:55:55.480  5790  5790 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-29 05:55:55.482  3133  3133 D BluetoothPbap: Proxy object disconnected
09-29 05:55:55.482  3133  3133 D PbapServerProfile: Bluetooth service disconnected
09-29 05:55:55.483  5697  5697 D BluetoothPbap: Proxy object disconnected
09-29 05:55:55.483  5697  5697 D PbapServerProfile: Bluetooth service disconnected
09-29 05:55:55.483  5790  5790 D BluetoothMapService: MAP Service closeService in
09-29 05:55:55.483  5790  5790 V BluetoothAdapterState: isTurningOff()=true
09-29 05:55:55.483  5790  5790 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:55.483  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 05:55:55.483  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 05:55:55.483  5790  5790 D BluetoothMapService: cleanup()
09-29 05:55:55.483  5790  5790 D BluetoothMapService: MAP Service closeService in
09-29 05:55:55.483  5790  5790 V BluetoothAdapterState: isTurningOff()=true
09-29 05:55:55.483  5790  5790 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:55.483  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:55.483  5790  5790 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:55:55.484  5790  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-29 05:55:55.484  5790  5802 D BluetoothAdapterProperties: Setting state to 15
09-29 05:55:55.484  5790  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-29 05:55:55.485  5790  5802 I BluetoothAdapterState: Entering BleOnState
09-29 05:55:55.485  3133  3145 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:55:55.485  5697  5709 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:55:55.486  3133  3959 D BluetoothPan: onBluetoothStateChange on: false
09-29 05:55:55.486   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:55:55.486  5697  5710 D BluetoothMap: onBluetoothStateChange: up=false
09-29 05:55:55.487  3133  3146 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-29 05:55:55.489  5697  5709 D BluetoothPbap: onBluetoothStateChange: up=false
,09-29 05:55:55.490  3133  3145 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 05:55:55.490   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 05:55:55.490  3133  3959 D BluetoothMap: onBluetoothStateChange: up=false
09-29 05:55:55.492  5697  5710 D BluetoothPan: onBluetoothStateChange on: false
09-29 05:55:55.493  5697  5709 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-29 05:55:55.494   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-29 05:55:55.494  3133  3145 D BluetoothPbap: onBluetoothStateChange: up=false
09-29 05:55:55.495  5697  5710 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-29 05:55:55.495   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:55:55.496  3759  3780 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:55:55.496  5790  5802 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-29 05:55:55.496  5790  5802 D BluetoothAdapterProperties: Setting state to 16
09-29 05:55:55.496  5790  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-29 05:55:55.497  5790  5802 D BluetoothAdapterProperties: onBleDisable
,09-29 05:55:55.497  5790  5802 I BluetoothAdapterState: Entering PendingCommandState
09-29 05:55:55.497  5790  5803 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-29 05:55:55.499  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:55.499  5790  5813 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-29 05:55:55.499  5790  5813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:55:55.500  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 05:55:55.500  5790  5806 D BluetoothAdapterProperties: Scan Mode:20
,09-29 05:55:55.501  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:55.502  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:55.504  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:55:55.505  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:55.506  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:55:55.508  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 05:55:55.509  5697  5697 D DockEventReceiver: finishStartingService: stopping service
,09-29 05:55:55.717  5790  5806 I bt_hci  : shut_down
,09-29 05:55:55.721  5790  5810 D bt_hwcfg: hw_epilog_process
,09-29 05:55:55.722  5790  5810 I bt_vendor: low_power_mode_cb
,09-29 05:55:55.725  5790  5810 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-29 05:55:55.726  5790  5810 I bt_vendor: epilog_cb
09-29 05:55:55.726  5790  5810 I bt_hci  : epilog_finished_callback
,09-29 05:55:55.730  5790  5806 I bt_hci_h4: hal_close
,09-29 05:55:55.731  5790  5806 I bt_userial_vendor: device fd = 54 close
,09-29 05:55:55.845  5790  5803 D bt_stack_manager: event_shut_down_stack finished.
,09-29 05:55:55.845  5790  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-29 05:55:55.849  5790  5802 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-29 05:55:55.849  5790  5790 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-29 05:55:55.851  5790  5790 D BtGatt.GattService: Received stop request...Stopping profile...
09-29 05:55:55.851  5790  5790 D BtGatt.GattService: stop()
,09-29 05:55:55.851  5790  5790 D BtGatt.AdvertiseManager: advertise clients cleared
09-29 05:55:55.855  5790  5790 V BluetoothAdapterState: isTurningOff()=false
09-29 05:55:55.855  5790  5790 V BluetoothAdapterState: isTurningOn()=false
09-29 05:55:55.855  5790  5790 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:55:55.855  5790  5790 V BluetoothAdapterState: isBleTurningOff()=true
09-29 05:55:55.856  5790  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-29 05:55:55.856  5790  5802 D BluetoothAdapterProperties: Setting state to 10
,09-29 05:55:55.856  5790  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-29 05:55:55.857  5790  5802 I BluetoothAdapterState: Entering OffState
,09-29 05:55:55.858   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-29 05:55:55.873  5790  5790 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-29 05:55:55.873  5790  5790 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-29 05:55:55.874  5790  5790 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-29 05:55:55.876  5790  5803 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-29 05:55:55.882  5790  5790 I art     : System.exit called, status: 0
,09-29 05:55:55.883  5790  5790 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-29 05:55:55.914   928  3405 I ActivityManager: Process com.android.bluetooth (pid 5790) has died
,09-29 05:56:00.418  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:56:00.418  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:56:00.424  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:56:00.424  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c84ece0 removed from the list
09-29 05:56:00.424  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:56:00.424  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:00.425  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:00.427  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-29 05:56:00.427  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29ffe5e added. We now have 4 listener(s)
09-29 05:56:00.427  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:56:00.430  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:56:00.431  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29ffe5e removed from the list
,09-29 05:56:00.431  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:56:00.431  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:00.431  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:56:00.435  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-29 05:56:00.435  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@854223f added. We now have 4 listener(s)
09-29 05:56:00.436  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 05:56:05.446  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:56:05.482   928   945 I ActivityManager: Start proc 5846:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-29 05:56:05.592  5846  5846 D AdapterServiceConfig: Adding HeadsetService
09-29 05:56:05.592  5846  5846 D AdapterServiceConfig: Adding A2dpService
09-29 05:56:05.592  5846  5846 D AdapterServiceConfig: Adding HidService
09-29 05:56:05.592  5846  5846 D AdapterServiceConfig: Adding HealthService
09-29 05:56:05.593  5846  5846 D AdapterServiceConfig: Adding PanService
09-29 05:56:05.593  5846  5846 D AdapterServiceConfig: Adding GattService
09-29 05:56:05.593  5846  5846 D AdapterServiceConfig: Adding BluetoothMapService
09-29 05:56:05.593  5846  5846 D AdapterServiceConfig: Adding SapService
,09-29 05:56:05.607   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10c5873:true
,09-29 05:56:05.607  5846  5846 D BluetoothAdapterState: make() - Creating AdapterState
,09-29 05:56:05.611  5846  5846 I bt_bluedroid: init
,09-29 05:56:05.612  5846  5858 I BluetoothAdapterState: Entering OffState
,09-29 05:56:05.614  5846  5859 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-29 05:56:05.615  5846  5859 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-29 05:56:05.615  5846  5859 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-29 05:56:05.615  5846  5859 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-29 05:56:05.616  5846  5846 I bt_bluedroid: get_profile_interface socket
,09-29 05:56:05.618  5846  5862 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 05:56:05.619  5846  5846 I bt_bluedroid: get_profile_interface sdp
09-29 05:56:05.621  5846  5862 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 05:56:05.626  5846  5857 I bt_bluedroid: config_hci_snoop_log
09-29 05:56:05.627   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-29 05:56:05.633  5846  5858 D BluetoothAdapterState: Current state: OFF, message: 0
,09-29 05:56:05.633  5846  5858 D BluetoothAdapterProperties: Setting state to 14
09-29 05:56:05.634  5846  5858 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-29 05:56:05.636  5846  5858 D BluetoothBondStateMachine: make
,09-29 05:56:05.638  5846  5863 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-29 05:56:05.641  5846  5858 I BluetoothAdapterState: Entering PendingCommandState
,09-29 05:56:05.642  5846  5846 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-29 05:56:05.645  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
,09-29 05:56:05.645  5846  5846 D BtGatt.DebugUtils: handleDebugAction() action=null
09-29 05:56:05.646  5846  5846 D BtGatt.GattService: Received start request. Starting profile...
,09-29 05:56:05.646  5846  5846 D BtGatt.GattService: start()
09-29 05:56:05.646  5846  5846 I bt_bluedroid: get_profile_interface gatt
,09-29 05:56:05.648  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
09-29 05:56:05.648  5846  5846 D BtGatt.AdvertiseManager: advertise manager created
,09-29 05:56:05.654  5846  5846 V BluetoothAdapterState: isTurningOff()=false
,09-29 05:56:05.654  5846  5846 V BluetoothAdapterState: isTurningOn()=false
09-29 05:56:05.654  5846  5846 V BluetoothAdapterState: isBleTurningOn()=true
09-29 05:56:05.654  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:56:05.655  5846  5858 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-29 05:56:05.656  5846  5858 I bt_bluedroid: bt_bluedroid
09-29 05:56:05.656  5846  5859 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-29 05:56:05.657  5846  5859 I bt_hci  : start_up
,09-29 05:56:05.662  5846  5859 I bt_vendor: alloc value 0xf3b99871
09-29 05:56:05.662  5846  5859 I bt_vendor: init
09-29 05:56:05.662  5846  5859 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-29 05:56:05.662  5846  5859 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-29 05:56:05.771  5846  5859 D bt_hci  : start_up starting async portion
,09-29 05:56:05.772  5846  5866 I bt_hci  : event_finish_startup
09-29 05:56:05.772  5846  5866 I bt_hci_h4: hal_open
,09-29 05:56:05.772  5846  5866 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-29 05:56:05.775  5846  5866 I bt_userial_vendor: device fd = 54 open
,09-29 05:56:05.771  5867  5867 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 05:56:05.791  5846  5866 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 05:56:05.795  5846  5866 D bt_hwcfg: Chipset BCM4358A3
,09-29 05:56:05.795  5846  5866 D bt_hwcfg: Target name = [BCM4358A3]
09-29 05:56:05.795  5846  5866 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-29 05:56:06.301  5846  5866 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-29 05:56:06.301  5846  5866 D bt_hwcfg: Settlement delay -- 100 ms
09-29 05:56:06.301  5846  5866 I bt_hwcfg: Setting fw settlement delay to 100 
,09-29 05:56:06.437  5846  5866 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 05:56:06.437  5846  5866 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-29 05:56:06.439  5846  5866 I bt_hwcfg: vendor lib fwcfg completed
,09-29 05:56:06.439  5846  5866 I bt_vendor: firmware callback
09-29 05:56:06.439  5846  5866 I bt_hci  : firmware_config_callback
09-29 05:56:06.449  5846  5869 I bt_btu  : btu_task pending for preload complete event
09-29 05:56:06.449  5846  5869 I bt_btu_task: Bluetooth chip preload is complete
09-29 05:56:06.449  5846  5869 I bt_btu  : btu_task received preload complete event
,09-29 05:56:06.455  5846  5869 I         : BTE_InitTraceLevels -- TRC_HCI
,09-29 05:56:06.456  5846  5869 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-29 05:56:06.456  5846  5869 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-29 05:56:06.456  5846  5869 I         : BTE_InitTraceLevels -- TRC_AVDT
09-29 05:56:06.456  5846  5869 I         : BTE_InitTraceLevels -- TRC_AVRC
09-29 05:56:06.456  5846  5869 I         : BTE_InitTraceLevels -- TRC_A2D
09-29 05:56:06.456  5846  5869 I         : BTE_InitTraceLevels -- TRC_BNEP
09-29 05:56:06.456  5846  5869 I         : BTE_InitTraceLevels -- TRC_BTM
09-29 05:56:06.456  5846  5869 I         : BTE_InitTraceLevels -- TRC_GAP
09-29 05:56:06.456  5846  5869 I         : BTE_InitTraceLevels -- TRC_PAN
,09-29 05:56:06.457  5846  5869 I         : BTE_InitTraceLevels -- TRC_SDP
09-29 05:56:06.457  5846  5869 I         : BTE_InitTraceLevels -- TRC_GATT
09-29 05:56:06.457  5846  5869 I         : BTE_InitTraceLevels -- TRC_SMP
09-29 05:56:06.457  5846  5869 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-29 05:56:06.457  5846  5869 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-29 05:56:06.542  5846  5869 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b17549
,09-29 05:56:06.542  5846  5869 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b17549 
,09-29 05:56:06.565  5846  5862 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-29 05:56:06.566  5846  5862 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-29 05:56:06.566  5846  5862 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-29 05:56:06.569  5846  5862 D BluetoothAdapterProperties: Name is: Nexus 6P
09-29 05:56:06.571  5846  5862 D BluetoothAdapterProperties: Scan Mode:20
09-29 05:56:06.571  5846  5862 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 05:56:06.572  5846  5862 D bt_hci  : do_postload posting postload work item
09-29 05:56:06.572  5846  5866 I bt_hci  : event_postload
09-29 05:56:06.572  5846  5866 I bt_vendor: sco_config_cb
09-29 05:56:06.572  5846  5866 I bt_hci  : sco_config_callback postload finished.
,09-29 05:56:06.575  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:56:06.578  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:56:06.579  5846  5866 I bt_vendor: low_power_mode_cb
,09-29 05:56:06.580  5846  5862 D bt_bte_conf: Device ID record 1 : primary
09-29 05:56:06.580  5846  5862 D bt_bte_conf:   vendorId            = 000f
09-29 05:56:06.580  5846  5862 D bt_bte_conf:   vendorIdSource      = 0001
09-29 05:56:06.580  5846  5862 D bt_bte_conf:   product             = 1200
09-29 05:56:06.580  5846  5862 D bt_bte_conf:   version             = 1436
09-29 05:56:06.580  5846  5862 D bt_bte_conf:   clientExecutableURL = 
09-29 05:56:06.580  5846  5862 D bt_bte_conf:   serviceDescription  = 
09-29 05:56:06.580  5846  5862 D bt_bte_conf:   documentationURL    = 
09-29 05:56:06.580  5846  5862 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-29 05:56:06.580  5846  5859 D bt_stack_manager: event_start_up_stack finished
09-29 05:56:06.581  5846  5858 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-29 05:56:06.581  5846  5858 D BluetoothAdapterProperties: Setting state to 15
,09-29 05:56:06.581  5846  5858 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-29 05:56:06.582  5846  5858 I BluetoothAdapterState: Entering BleOnState
09-29 05:56:06.585  5846  5858 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-29 05:56:06.585  5846  5858 D BluetoothAdapterProperties: Setting state to 11
09-29 05:56:06.585  5846  5858 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-29 05:56:06.591  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
,09-29 05:56:06.592  5846  5846 D HeadsetService: Received start request. Starting profile...
,09-29 05:56:06.592  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:56:06.593  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:56:06.594  5846  5846 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-29 05:56:06.595  5846  5846 D HeadsetStateMachine: make
,09-29 05:56:06.605  5846  5858 I BluetoothAdapterState: Entering PendingCommandState
09-29 05:56:06.606  5846  5846 D HeadsetStateMachine: max_hf_connections = 1
09-29 05:56:06.606  5846  5846 I bt_bluedroid: get_profile_interface handsfree
09-29 05:56:06.607  5846  5862 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-29 05:56:06.609  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
09-29 05:56:06.610  5846  5846 D A2dpService: Received start request. Starting profile...
,09-29 05:56:06.611  5846  5846 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-29 05:56:06.611  5846  5862 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-29 05:56:06.611  5846  5846 I bt_bluedroid: get_profile_interface avrcp
,09-29 05:56:06.618  5846  5846 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-29 05:56:06.618  5846  5846 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-29 05:56:06.618  5846  5846 D A2dpStateMachine: make
09-29 05:56:06.619  5846  5846 I bt_bluedroid: get_profile_interface a2dp
09-29 05:56:06.620  5846  5862 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-29 05:56:06.621  5846  5877 D A2dpStateMachine: Enter Disconnected: -2
,09-29 05:56:06.623  5846  5846 I BluetoothHidServiceJni: classInitNative: succeeds
,09-29 05:56:06.623  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
,09-29 05:56:06.624  5846  5846 D HidService: Received start request. Starting profile...
09-29 05:56:06.624  5846  5846 I bt_bluedroid: get_profile_interface hidhost
09-29 05:56:06.624  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 05:56:06.624  5846  5846 D HidService: setHidService(): set to: null
09-29 05:56:06.625  5846  5862 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3af856d
09-29 05:56:06.625  5846  5862 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-29 05:56:06.625  5846  5846 I BluetoothHealthServiceJni: classInitNative: succeeds
09-29 05:56:06.626  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
,09-29 05:56:06.627  5846  5846 D HealthService: Received start request. Starting profile...
,09-29 05:56:06.628  5846  5846 I bt_bluedroid: get_profile_interface health
,09-29 05:56:06.629  5846  5846 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-29 05:56:06.629  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
09-29 05:56:06.630  5846  5846 D PanService: Received start request. Starting profile...
09-29 05:56:06.630  5846  5846 D BluetoothPanServiceJni: initializeNative(L110): pan
09-29 05:56:06.630  5846  5846 I bt_bluedroid: get_profile_interface pan
09-29 05:56:06.633  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
,09-29 05:56:06.634  5846  5846 D BluetoothMapService: Received start request. Starting profile...
09-29 05:56:06.634  5846  5846 D BluetoothMapService: start()
09-29 05:56:06.636  5846  5846 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-29 05:56:06.637  5846  5846 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-29 05:56:06.637  5846  5846 D BluetoothMapAppObserver: createReceiver()
09-29 05:56:06.639  5846  5846 D BluetoothMapAppObserver: initObservers()
09-29 05:56:06.639  5846  5846 D BluetoothMapAppObserver: getEnabledAccountItems()
09-29 05:56:06.640  5846  5862 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-29 05:56:06.644  5846  5846 V SapService: SapBinder()
,09-29 05:56:06.644  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
09-29 05:56:06.645  5846  5846 D SapService: Received start request. Starting profile...
09-29 05:56:06.645  5846  5846 V SapService: start()
09-29 05:56:06.646  5846  5846 V BluetoothAdapterState: isTurningOff()=false
09-29 05:56:06.646  5846  5846 V BluetoothAdapterState: isTurningOn()=true
09-29 05:56:06.646  5846  5846 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:56:06.646  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:56:06.646  5846  5846 V BluetoothAdapterState: isTurningOff()=false
,09-29 05:56:06.647  5846  5846 V BluetoothAdapterState: isTurningOn()=true
09-29 05:56:06.647  5846  5846 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:56:06.647  5846  5875 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-29 05:56:06.647  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 05:56:06.647  5846  5846 V BluetoothAdapterState: isTurningOff()=false
09-29 05:56:06.647  5846  5846 V BluetoothAdapterState: isTurningOn()=true
,09-29 05:56:06.647  5846  5846 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 05:56:06.647  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 05:56:06.647  5846  5846 V BluetoothAdapterState: isTurningOff()=false
,09-29 05:56:06.648  5846  5846 V BluetoothAdapterState: isTurningOn()=true
,09-29 05:56:06.648  5846  5846 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:56:06.648  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:56:06.648  5846  5846 V BluetoothAdapterState: isTurningOff()=false
09-29 05:56:06.648  5846  5846 V BluetoothAdapterState: isTurningOn()=true
09-29 05:56:06.648  5846  5846 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:56:06.648  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:56:06.648  5846  5846 V BluetoothAdapterState: isTurningOff()=false
09-29 05:56:06.648  5846  5846 V BluetoothAdapterState: isTurningOn()=true
09-29 05:56:06.648  5846  5846 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:56:06.648  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 05:56:06.649  5846  5846 V BluetoothAdapterState: isTurningOff()=false
09-29 05:56:06.649  5846  5846 V BluetoothAdapterState: isTurningOn()=true
09-29 05:56:06.649  5846  5846 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:56:06.649  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:56:06.649  5846  5858 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-29 05:56:06.650  5846  5858 D BluetoothAdapterProperties: ScanMode =  20
09-29 05:56:06.650  5846  5858 D BluetoothAdapterProperties: State =  11
09-29 05:56:06.650  5846  5858 D BluetoothAdapterProperties: Setting state to 12
09-29 05:56:06.650  5846  5858 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-29 05:56:06.651  5846  5858 I BluetoothAdapterState: Entering OnState
09-29 05:56:06.651  3133  3959 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:56:06.652  5697  5709 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-29 05:56:06.653  3133  3145 D BluetoothPan: onBluetoothStateChange on: true
09-29 05:56:06.653  5846  5862 D BluetoothAdapterProperties: Scan Mode:21
09-29 05:56:06.654  5846  5862 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 05:56:06.654  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-29 05:56:06.655   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:56:06.655  5697  5710 D BluetoothMap: onBluetoothStateChange: up=true
09-29 05:56:06.656  3133  3133 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 05:56:06.656  3133  3133 D PanProfile: Bluetooth service connected
09-29 05:56:06.657  3133  3959 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 05:56:06.657  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:56:06.657  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:56:06.657  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:56:06.657  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:56:06.657  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:56:06.657  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:56:06.657  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:56:06.657  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:56:06.659  5697  5710 D BluetoothPbap: onBluetoothStateChange: up=true
,09-29 05:56:06.660  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:56:06.660  3133  3133 D BluetoothInputDevice: Proxy object connected
09-29 05:56:06.660  3133  3133 D HidProfile: Bluetooth service connected
09-29 05:56:06.661  5697  5697 D BluetoothMap: Proxy object connected
09-29 05:56:06.661  5697  5697 D MapProfile: Bluetooth service connected
09-29 05:56:06.661  5697  5697 D BluetoothMap: getConnectedDevices()
09-29 05:56:06.661  3133  3146 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 05:56:06.662   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 05:56:06.663  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:56:06.663  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:56:06.663  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:56:06.663  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:56:06.663  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:56:06.663  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:56:06.663  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:56:06.663  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:56:06.663  3133  3959 D BluetoothMap: onBluetoothStateChange: up=true
09-29 05:56:06.663  5846  5846 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-29 05:56:06.664  5846  5846 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-29 05:56:06.665  3133  3133 D BluetoothMap: Proxy object connected
09-29 05:56:06.665  3133  3133 D MapProfile: Bluetooth service connected
09-29 05:56:06.665  3133  3133 D BluetoothMap: getConnectedDevices()
09-29 05:56:06.665  5697  5709 D BluetoothPan: onBluetoothStateChange on: true
09-29 05:56:06.665  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:56:06.665  5846  5846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 05:56:06.667  5697  5710 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-29 05:56:06.668  5846  5846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:56:06.668   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:56:06.669  3133  3959 D BluetoothPbap: onBluetoothStateChange: up=true
09-29 05:56:06.669  5846  5846 D ObexServerSockets: Succeed to create listening sockets 
09-29 05:56:06.669  5846  5846 D ObexServerSockets0: startAccept()
09-29 05:56:06.669  5846  5846 D ObexServerSockets0: prepareForNewConnect()
09-29 05:56:06.670  5697  5709 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 05:56:06.672   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:56:06.672  5846  5846 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-29 05:56:06.672  3759  3781 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:56:06.672  5846  5846 D BluetoothSdpJni: SDP Create record success - handle: 0
09-29 05:56:06.672  5846  5884 D ObexServerSockets0: Accepting socket connection...
09-29 05:56:06.673  5846  5885 D ObexServerSockets0: Accepting socket connection...
09-29 05:56:06.674   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,09-29 05:56:06.674  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-29 05:56:06.674  5697  5697 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 05:56:06.674  5697  5697 D PanProfile: Bluetooth service connected
09-29 05:56:06.674  5697  5697 D BluetoothInputDevice: Proxy object connected
09-29 05:56:06.674  5697  5697 D HidProfile: Bluetooth service connected
09-29 05:56:06.676   928   928 D BluetoothA2dp: Proxy object connected
09-29 05:56:06.676  3133  3133 D BluetoothA2dp: Proxy object connected
09-29 05:56:06.676  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:56:06.678  5846  5846 D BluetoothMapService: onReceive
09-29 05:56:06.678  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:56:06.678  5846  5846 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-29 05:56:06.678  5846  5846 D BluetoothMapService: STATE_ON
,09-29 05:56:06.681  5846  5888 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:56:06.682  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 05:56:06.682  5846  5888 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-29 05:56:06.682  5846  5888 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-29 05:56:06.684  5697  5697 D BluetoothA2dp: Proxy object connected
,09-29 05:56:06.687  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 05:56:06.688  5697  5697 D DockEventReceiver: finishStartingService: stopping service
,09-29 05:56:06.694  5697  5697 D BluetoothPbap: Proxy object connected
,09-29 05:56:06.695  5697  5697 D PbapServerProfile: Bluetooth service connected
,09-29 05:56:06.701  5846  5892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 05:56:06.704  3133  3133 D BluetoothPbap: Proxy object connected
09-29 05:56:06.704  3133  3133 D PbapServerProfile: Bluetooth service connected
,09-29 05:56:06.711  5846  5846 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-29 05:56:06.711  5846  5846 D ObexServerSockets0: prepareForNewConnect()
,09-29 05:56:06.717  5846  5896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:56:06.719  5846  5896 I BtOppRfcommListener: Accept thread started.
,09-29 05:56:06.753  5697  5709 D BluetoothHeadset: Proxy object connected
09-29 05:56:06.753  5697  5710 D BluetoothHeadset: Proxy object connected
,09-29 05:56:06.753   928   928 D BluetoothHeadset: Proxy object connected
09-29 05:56:06.754  3133  3959 D BluetoothHeadset: Proxy object connected
09-29 05:56:06.754  3133  3133 D HeadsetProfile: Bluetooth service connected
,09-29 05:56:06.755  3759  3997 D BluetoothHeadset: Proxy object connected
,09-29 05:56:06.755  5697  5697 D HeadsetProfile: Bluetooth service connected
09-29 05:56:06.755   928   928 D BluetoothHeadset: Proxy object connected
09-29 05:56:06.755   928   928 D BluetoothHeadset: Proxy object connected
09-29 05:56:06.756   928   945 D BluetoothHeadset: Proxy object connected
,09-29 05:56:06.757  5697  5697 D HeadsetProfile: Bluetooth service connected
,09-29 05:56:06.769   928   945 D BluetoothHeadset: Proxy object connected
,09-29 05:56:06.771   928   945 D BluetoothHeadset: Proxy object connected
,09-29 05:56:06.773  3759  3780 D BluetoothHeadset: Proxy object connected
,09-29 05:56:10.463  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:56:10.463  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:56:10.463  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:56:10.463  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:56:10.463  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:56:10.463  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:56:10.463  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:56:10.463  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:56:10.469  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:56:10.470  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:10.470  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@854223f removed from the list
09-29 05:56:10.470  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 05:56:10.470  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:10.471  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:10.472  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-29 05:56:10.473  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9fbf70c added. We now have 4 listener(s)
09-29 05:56:10.473  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:56:10.478   928  3800 D WifiService: setWifiEnabled: false pid=5644, uid=10077
09-29 05:56:10.479   928  3800 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 05:56:12.185   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:56:13.186   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:56:14.188   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:56:15.189   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:56:15.489  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:56:15.491   928  3844 D WifiService: setWifiEnabled: true pid=5644, uid=10077
09-29 05:56:15.491   928  3844 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-29 05:56:15.498   510   922 D SoftapController: Softap fwReload - Ok
,09-29 05:56:15.503   510   922 D CommandListener: Setting iface cfg
,09-29 05:56:15.504   510   922 D CommandListener: Trying to bring down wlan0
09-29 05:56:15.506   510   922 D CommandListener: Clearing all IP addresses on wlan0
,09-29 05:56:15.513   928  2941 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-29 05:56:16.127   928  2941 D wifi    : set interface wlan0 flags (UP)
09-29 05:56:16.133   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-29 05:56:16.134   928  2941 I WifiHAL : Initializing wifi
09-29 05:56:16.134   928  2941 I WifiHAL : Creating socket
,09-29 05:56:16.141   928  2941 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-29 05:56:16.141   928  2941 D wifi    : Did set static halHandle = 0x7f7455b900
09-29 05:56:16.141   928  2941 D wifi    : halHandle = 0x7f7455b900, mVM = 0x7f90b8d140, mCls = 0x2019c2
09-29 05:56:16.142   928  2941 D wifi    : array field set
09-29 05:56:16.142   928  2941 I WifiNative-HAL: interface[0] = wlan0
09-29 05:56:16.144   928  5901 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547412621568
09-29 05:56:16.144   928  5901 D wifi    : waitForHalEvents called, vm = 0x7f90b8d140, obj = 0x2019c2, env = 0x7f75a99e40
,09-29 05:56:16.189   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:56:16.213  5902  5902 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-29 05:56:16.235  5902  5902 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 05:56:16.245   928  2941 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-29 05:56:16.247  5902  5902 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 05:56:16.247  5902  5902 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-29 05:56:16.256  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:56:16.257  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:56:16.267   928  2941 D WifiConfigStore: Loading config and enabling all networks 
,09-29 05:56:16.272  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:56:16.272  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:56:16.272  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:56:16.272  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:56:16.272  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:56:16.272  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:56:16.272  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:56:16.272  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:56:16.275  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:56:16.278  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:56:16.278  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:56:16.278  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:56:16.278  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:56:16.278  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:56:16.278  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:56:16.278  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:56:16.278  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:56:16.280  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:56:16.280   928  2941 D WifiConfigStore: loaded 0 passpoint configs
09-29 05:56:16.280   928  2941 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-29 05:56:16.281   928  2941 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-29 05:56:16.282   928  2941 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-29 05:56:16.283   928  2941 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-29 05:56:16.283   928  2941 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-29 05:56:16.283   928  2941 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-29 05:56:16.284   928  2941 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-29 05:56:16.287  5025  5025 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-29 05:56:16.287   928  2941 D WifiNative-HAL: Setting external_sim to 1
09-29 05:56:16.288   928  2941 D wifi    : setting dfs flag to true, 0x7f753dc0a0
09-29 05:56:16.288   928  2941 D WifiStateMachine: Setting OUI to DA-A1-19
,09-29 05:56:16.288   928  2941 D wifi    : setting scan oui 0x7f753dc0a0
09-29 05:56:16.288   928  2941 D WifiHAL : Sending mac address OUI
,09-29 05:56:16.292   928  2941 E native  : do suspend false
,09-29 05:56:16.299   928  2941 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-29 05:56:16.299   928   928 D RttService: SCAN_AVAILABLE : 3
09-29 05:56:16.299   510   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-29 05:56:16.299   928  3063 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-29 05:56:16.300   510   922 D CommandListener: Setting iface cfg
,09-29 05:56:16.304   928  2940 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '136 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 136 Failed to set address (No such device)'
,09-29 05:56:16.304   928  2940 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-29 05:56:16.312   928  2940 D WifiNative-HAL: p2pGetDeviceAddress
,09-29 05:56:16.312   928  2940 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-29 05:56:16.316   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303179 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-29 05:56:17.190   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-29 05:56:19.469  5902  5902 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 05:56:19.539   928  2941 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-29 05:56:19.540   928  2941 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-29 05:56:19.540   928  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 05:56:19.552   928  2941 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-29 05:56:19.583   928  2941 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-29 05:56:19.585  5902  5902 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-29 05:56:20.004  5902  5902 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-29 05:56:20.037  5902  5902 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-29 05:56:20.039  5902  5902 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-29 05:56:20.048   928  2941 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-29 05:56:20.048   928  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 05:56:20.049   928  2949 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-29 05:56:20.065   928  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 05:56:20.078   510   922 D CommandListener: Setting iface cfg
,09-29 05:56:20.101   928  2941 D WifiStateMachine: Start Dhcp Watchdog 2
,09-29 05:56:20.107   928  5907 D DhcpClient: Receive thread started
,09-29 05:56:20.110   928  2949 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 05:56:20.111   928  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-29 05:56:20.111   928  2949 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-29 05:56:20.191   928  2941 E native  : do suspend false
,09-29 05:56:20.205   928  5906 D DhcpClient: Broadcasting DHCPDISCOVER
,09-29 05:56:20.218   928  5907 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172535, domain null
09-29 05:56:20.219   928  5906 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172535 seconds
,09-29 05:56:20.221   928  5906 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-29 05:56:20.243   928  5907 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-29 05:56:20.244   928  5906 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-29 05:56:20.248   510   922 D CommandListener: Setting iface cfg
,09-29 05:56:20.253   928  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-29 05:56:20.259   928  5906 D DhcpClient: Scheduling renewal in 86399s
,09-29 05:56:20.268   928  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-29 05:56:20.270   928  2941 D WifiConfigStore: No blacklist allowed without epno enabled
,09-29 05:56:20.270   928  2949 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-29 05:56:20.271   928  2949 D ConnectivityService: Adding iface wlan0 to network 101
,09-29 05:56:20.275   928  2941 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-29 05:56:20.312   928  2949 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-29 05:56:20.312   928  2949 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-29 05:56:20.315   928  2949 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-29 05:56:20.317   928  2949 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-29 05:56:20.319   928  2949 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-29 05:56:20.326   928  2949 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 05:56:20.329   928  2949 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-29 05:56:20.330   928  2949 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-29 05:56:20.330   928  2949 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-29 05:56:20.330   928  2949 D ConnectivityService:    accepting network in place of null
09-29 05:56:20.330   928  2941 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-29 05:56:20.330   928  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-29 05:56:20.331   928  2949 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-29 05:56:20.342   928  5905 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307205, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-29 05:56:20.357   510   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 05:56:20.378   510   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 05:56:20.381   928  2949 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-29 05:56:20.381  3716  3880 W QCNEJ   : |CORE| network available: 101
09-29 05:56:20.381   928  2949 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-29 05:56:20.382   928  2949 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-29 05:56:20.383   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-29 05:56:20.386  3716  3880 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-29 05:56:20.388  3716  3880 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-29 05:56:20.388  3716  3880 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-29 05:56:20.391  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:56:20.391  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:56:20.391  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:56:20.391  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:56:20.391  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:56:20.391  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:56:20.391  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:56:20.391  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:56:20.393  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 05:56:20.398  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:56:20.398  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:56:20.398  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:56:20.398  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:56:20.398  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:56:20.398  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:56:20.398  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:56:20.398  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:56:20.400  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:56:20.400  5053  5077 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-29 05:56:20.401  4935  4935 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-29 05:56:20.400  5053  5077 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-29 05:56:20.403  5053  5077 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-29 05:56:20.403  3901  3901 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-29 05:56:20.403  5053  5077 E SarControlService: no key has been found,reset the power
,09-29 05:56:20.407  5053  5090 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-29 05:56:20.407  5053  5090 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-29 05:56:20.407  5053  5090 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-29 05:56:20.408  5078  5078 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-29 05:56:20.408  5078  5078 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-29 05:56:20.409  5053  5090 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-29 05:56:20.409  5053  5090 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-29 05:56:20.409  5053  5090 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-29 05:56:20.410  5078  5078 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 05:56:20.410  5078  5078 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-29 05:56:20.411  3901  3901 D SystemUpdateService: onCreate
,09-29 05:56:20.416  5078  5092 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1a83e35 HexData = [00000000ec03000000000000ffffffff]
09-29 05:56:20.416  5078  5092 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 05:56:20.416  5078  5092 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-29 05:56:20.416  5078  5078 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 05:56:20.416  5053  5063 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-29 05:56:20.416   928  5904 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:4001:819::200e
09-29 05:56:20.417  5078  5092 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1a83e35 HexData = [00000000ed03000000000000ffffffff]
09-29 05:56:20.417  5078  5092 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 05:56:20.417  5078  5092 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-29 05:56:20.418  3901  3901 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-29 05:56:20.419  5078  5078 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 05:56:20.419  5053  5064 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-29 05:56:20.429  3901  3901 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-29 05:56:20.435  3901  5416 I iu.UploadsManager: num queued entries: 0
,09-29 05:56:20.435  3901  5416 I iu.UploadsManager: num updated entries: 0
09-29 05:56:20.436  3901  5416 I iu.SyncManager: NEXT; no task
09-29 05:56:20.437  3901  5918 I SystemUpdateService: active receiver: enabled
,09-29 05:56:20.439  3901  3901 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-29 05:56:20.440  3901  3901 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-29 05:56:20.442  5419  5419 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-29 05:56:20.445  5419  5419 D SprintDMHelper: simOperator: 
09-29 05:56:20.445  5419  5419 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-29 05:56:20.467  3901  5918 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-29 05:56:20.467   928  5904 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 29 Sep 2016 09:56:20 GMT], X-Android-Received-Millis=[1475142980466], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475142980441]}
,09-29 05:56:20.467   928  2949 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-29 05:56:20.468   928  2949 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-29 05:56:20.468   928  2949 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-29 05:56:20.469   928  2949 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-29 05:56:20.480  3901  5918 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-29 05:56:20.480  3901  5918 I SystemUpdateService: now status is 0 (complete)
09-29 05:56:20.480  3901  5918 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-29 05:56:20.480  3901  5918 I SystemUpdateService: file has been verified
09-29 05:56:20.481  3901  5918 I SystemUpdateService: OTA package size = 21989297
,09-29 05:56:20.489  3901  5918 I SystemUpdateService: showing system update notification
,09-29 05:56:20.498  3901  3901 D SystemUpdateService: onDestroy
,09-29 05:56:20.505  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:56:20.505  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:56:20.505  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:56:20.505  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:56:20.505  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:56:20.505  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:56:20.505  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:56:20.505  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:56:20.507  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 05:56:20.507  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:20.507  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9fbf70c removed from the list
09-29 05:56:20.507  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:56:20.507  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:20.507  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:56:20.510  5644  5928 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-29 05:56:20.510  5644  5928 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-29 05:56:20.555  5025  5922 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-29 05:56:21.383   928  2949 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-29 05:56:23.133   928  2949 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 05:56:23.542  5644  5928 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-29 05:56:23.542  5644  5931 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-29 05:56:23.543  5644  5931 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-29 05:56:23.543  5644  5928 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-29 05:56:23.544  5644  5931 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 05:56:23.544  5644  5928 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 05:56:23.546  5644  5931 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 05:56:23.546  5644  5928 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 05:56:23.548  5644  5933 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 05:56:23.548  5644  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-29 05:56:23.550  5644  5934 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 05:56:23.550  5644  5934 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 05:56:23.550  5644  5931 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-29 05:56:23.550  5644  5928 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-29 05:56:23.553  5644  5936 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 05:56:23.553  5644  5936 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 05:56:23.555  5644  5935 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 05:56:23.555  5644  5935 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-29 05:56:23.555  5644  5936 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 05:56:23.555  5644  5936 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 05:56:23.556  5644  5936 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 05:56:23.556  5644  5936 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 05:56:23.556  5644  5936 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 05:56:23.556  5644  5936 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-29 05:56:23.557  5644  5936 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 05:56:23.557  5644  5936 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-29 05:56:23.557  5644  5935 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 05:56:23.557  5644  5935 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-29 05:56:23.557  5644  5934 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 158, thread name: OutgoingSocketThread/Sender): Socket closed
09-29 05:56:23.557  5644  5935 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 05:56:23.557  5644  5935 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-29 05:56:23.557  5644  5935 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 05:56:23.558  5644  5934 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 158, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 05:56:23.558  5644  5934 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-29 05:56:23.558  5644  5935 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 05:56:23.558  5644  5934 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,09-29 05:56:23.558  5644  5935 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 05:56:23.558  5644  5934 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-29 05:56:23.558  5644  5935 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-29 05:56:23.558  5644  5935 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 05:56:23.558  5644  5934 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 05:56:23.558  5644  5934 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-29 05:56:23.558  5644  5935 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-29 05:56:23.558  5644  5935 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 05:56:23.558  5644  5935 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-29 05:56:23.559  5644  5933 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 157, thread name: IncomingSocketThread/Sender): Socket closed
09-29 05:56:23.560  5644  5933 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 05:56:23.560  5644  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-29 05:56:23.560  5644  5933 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-29 05:56:23.560  5644  5933 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-29 05:56:23.560  5644  5933 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 05:56:23.560  5644  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-29 05:56:23.557  5644  5936 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 05:56:23.563  5644  5936 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-29 05:56:23.563  5644  5936 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 05:56:23.563  5644  5936 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-29 05:56:26.522  5644  5690 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-29 05:56:26.523  5644  5690 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-29 05:56:26.530  5644  5690 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@145dd03 Bundle[{}]
,09-29 05:56:26.531  5644  5690 I io.jxcore.node.LifeCycleMonitor: start: OK
09-29 05:56:26.532  5644  5690 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-29 05:56:26.533  5644  5690 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-29 05:56:26.533  5644  5690 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-29 05:56:26.534  5644  5690 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-29 05:56:26.536  5644  5690 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-29 05:56:26.548  5644  5690 I System.out: Running OutgoingSocketThread
,09-29 05:56:26.551  5644  5937 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-29 05:56:26.552  5644  5937 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-29 05:56:28.335   928  2949 D ConnectivityService: handlePromptUnvalidated 101
,09-29 05:56:29.562  5644  5937 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-29 05:56:29.562  5644  5938 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-29 05:56:29.562  5644  5938 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-29 05:56:29.562  5644  5937 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-29 05:56:29.563  5644  5937 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 05:56:29.563  5644  5938 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 05:56:29.566  5644  5938 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 05:56:29.566  5644  5937 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 05:56:29.568  5644  5940 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 05:56:29.568  5644  5940 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-29 05:56:29.570  5644  5938 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-29 05:56:29.571  5644  5941 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 05:56:29.571  5644  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 05:56:29.572  5644  5942 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 05:56:29.572  5644  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-29 05:56:29.574  5644  5937 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-29 05:56:29.575  5644  5942 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 05:56:29.575  5644  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-29 05:56:29.575  5644  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 05:56:29.575  5644  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-29 05:56:29.575  5644  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 05:56:29.575  5644  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 05:56:29.576  5644  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 05:56:29.576  5644  5942 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-29 05:56:29.576  5644  5942 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 05:56:29.576  5644  5942 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-29 05:56:29.576  5644  5943 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 05:56:29.576  5644  5943 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 05:56:29.576  5644  5942 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 05:56:29.576  5644  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-29 05:56:29.577  5644  5943 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 05:56:29.577  5644  5943 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 05:56:29.578  5644  5941 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 169, thread name: OutgoingSocketThread/Sender): recvfrom failed: ECONNRESET (Connection reset by peer)
09-29 05:56:29.578  5644  5943 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 05:56:29.578  5644  5943 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 05:56:29.578  5644  5943 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-29 05:56:29.578  5644  5943 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 05:56:29.578  5644  5941 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 05:56:29.578  5644  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-29 05:56:29.578  5644  5941 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: ECONNRESET (Connection reset by peer)
,09-29 05:56:29.578  5644  5941 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-29 05:56:29.578  5644  5943 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 05:56:29.578  5644  5943 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-29 05:56:29.579  5644  5940 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 170, thread name: IncomingSocketThread/Sender): Socket closed
09-29 05:56:29.579  5644  5943 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 05:56:29.579  5644  5943 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-29 05:56:29.579  5644  5940 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 05:56:29.579  5644  5940 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-29 05:56:29.579  5644  5943 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 05:56:29.579  5644  5943 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-29 05:56:29.579  5644  5940 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-29 05:56:29.579  5644  5940 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-29 05:56:29.580  5644  5941 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 05:56:29.580  5644  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-29 05:56:29.580  5644  5940 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 05:56:29.580  5644  5940 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-29 05:56:31.313   928  2941 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 17, 18 -> obsolete
,09-29 05:56:32.561  5644  5690 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-29 05:56:32.563  5644  5690 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-29 05:56:32.563  5644  5690 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 182)
,09-29 05:56:32.570  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 05:56:32.570  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d60855 added. We now have 3 listener(s)
,09-29 05:56:32.573  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:56:32.573  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:56:32.574  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:56:32.574  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:56:32.574  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c69a26a added. We now have 4 listener(s)
09-29 05:56:32.574  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 05:56:32.576  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 05:56:32.581  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:56:32.587  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:56:32.587  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:56:32.587  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:56:32.587  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:56:32.587  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:56:32.587  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:56:32.587  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:56:32.587  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:56:32.590  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 05:56:32.591  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:56:32.591  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 05:56:32.591  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f777f8 added. We now have 4 listener(s)
09-29 05:56:32.593  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:56:32.593  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:56:32.593  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:56:32.593  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:56:32.593  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ebbd4d1 added. We now have 5 listener(s)
09-29 05:56:32.593  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:56:32.594  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:56:32.594  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:56:32.595  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-29 05:56:32.595  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:56:32.595  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.595  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:56:32.595  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:56:32.595  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:56:32.595  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 05:56:32.595  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d60855 removed from the list
09-29 05:56:32.595  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:32.595  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c69a26a removed from the list
,09-29 05:56:32.600  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:56:32.600  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:56:32.601  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:32.602  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.602  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:56:32.603  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:56:32.604  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:56:32.604  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:56:32.604  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c69a26a not in the list
09-29 05:56:32.604  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.604  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:56:32.606  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:56:32.606  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:56:32.606  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 05:56:32.606  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ebbd4d1 removed from the list
09-29 05:56:32.606  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:56:32.606  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.606  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:32.607  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:56:32.607  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 05:56:32.607  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f777f8 removed from the list
09-29 05:56:32.608  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 05:56:32.608  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b777b36 added. We now have 3 listener(s)
09-29 05:56:32.610  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:56:32.610  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-29 05:56:32.610  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:56:32.610  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:56:32.611  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2e1a37 added. We now have 4 listener(s)
09-29 05:56:32.611  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:56:32.612  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 05:56:32.617  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:56:32.622  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:56:32.622  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:56:32.622  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:56:32.622  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:56:32.622  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:56:32.622  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:56:32.622  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:56:32.622  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:56:32.625  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 05:56:32.625  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:56:32.625  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 05:56:32.625  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a57ed0d added. We now have 4 listener(s)
,09-29 05:56:32.628  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:56:32.628  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:56:32.628  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:56:32.628  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:56:32.628  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b814c2 added. We now have 5 listener(s)
09-29 05:56:32.628  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 05:56:32.628  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 05:56:32.628  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 05:56:32.629  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 05:56:32.629  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:56:32.629  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 05:56:32.629  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:56:32.632  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:56:32.633  5644  5690 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-29 05:56:32.633  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-29 05:56:32.639  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 05:56:32.639  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-29 05:56:32.640  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 05:56:32.642  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-29 05:56:32.643  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 05:56:32.643  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 05:56:32.643  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 05:56:32.643  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 05:56:32.644  5644  5690 D BluetoothAdapter: STATE_ON
09-29 05:56:32.647  5846  5887 D BtGatt.GattService: registerClient() - UUID=c2d67f66-e5df-4a71-8365-62f326912677
09-29 05:56:32.648  5846  5862 D BtGatt.GattService: onClientRegistered() - UUID=c2d67f66-e5df-4a71-8365-62f326912677, clientIf=5
09-29 05:56:32.648  5644  5654 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 05:56:32.649  5846  5886 D BtGatt.GattService: start scan with filters
,09-29 05:56:32.653  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 05:56:32.653  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 05:56:32.653  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 05:56:32.653  5846  5865 D BtGatt.ScanManager: handling starting scan
,09-29 05:56:32.653  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-29 05:56:32.653  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 05:56:32.653  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 05:56:32.653  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-29 05:56:32.655  5846  5865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@99b9167
,09-29 05:56:32.657  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 05:56:32.657  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 05:56:32.657  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-29 05:56:32.659  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 05:56:32.662  5644  5690 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-29 05:56:32.662  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-29 05:56:32.662  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-29 05:56:32.662  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.662  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 05:56:32.662  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:56:32.662  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 05:56:32.662  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 05:56:32.662  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 05:56:32.662  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 05:56:32.662  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 05:56:32.662  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-29 05:56:32.663  5644  5690 D BluetoothAdapter: STATE_ON
09-29 05:56:32.664  5846  5862 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 05:56:32.664  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.664  5846  5865 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-29 05:56:32.665  5846  5874 D BtGatt.GattService: stopScan() - queue size =1
,09-29 05:56:32.666  5846  5887 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 05:56:32.666  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 05:56:32.666  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-29 05:56:32.666  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 05:56:32.667  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 05:56:32.667  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 05:56:32.667  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 05:56:32.667  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 05:56:32.667  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 05:56:32.668  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:56:32.668  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 05:56:32.668  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 05:56:32.668  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 05:56:32.668  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 05:56:32.669  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:56:32.670  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:56:32.670  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:56:32.670  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:56:32.671  5846  5862 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 05:56:32.672  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.672  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:56:32.672  5846  5865 D BtGatt.ScanManager: Starting BLE batch scan
09-29 05:56:32.672  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:56:32.672  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:56:32.672  5846  5865 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 05:56:32.672  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:56:32.672  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.672  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:56:32.672  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:56:32.672  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 05:56:32.672  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b777b36 removed from the list
09-29 05:56,:32.672  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:32.673  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2e1a37 removed from the list
09-29 05:56:32.673  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:56:32.673  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:32.674  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.674  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:32.675  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:56:32.675  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:56:32.675  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:32.675  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2e1a37 not in the list
09-29 05:56:32.675  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.675  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:32.677  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:56:32.677  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:56:32.677  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:32.677  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b814c2 removed from the list
09-29 05:56:32.677  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:56:32.677  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.677  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:32.677  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:56:32.677  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 05:56:32.677  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a57ed0d removed from the list
09-29 05:56:32.678  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 05:56:32.678  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@376bb0e added. We now have 3 listener(s)
09-29 05:56:32.679  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:56:32.680  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:56:32.680  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:56:32.680  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSe,ttings: load: Already loaded
09-29 05:56:32.680  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@160192f added. We now have 4 listener(s)
09-29 05:56:32.680  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:56:32.681  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 05:56:32.683  5846  5862 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 05:56:32.683  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.683  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:56:32.688  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:56:32.688  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:56:32.688  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:56:32.688  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:56:32.688  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:56:32.688  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:56:32.688  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:56:32.688  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:56:32.688  5846  5862 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-29 05:56:32.688  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.691  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:56:32.691  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:56:32.691  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 05:56:32.691  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ab0c5 added. We now have 4 listener(s)
09-29 05:56:32.692  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:56:32.692  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:56:32.692  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:56:32.693  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:56:32.693  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e677a1a added. We now have 5 listener(s)
09-29 05:56:32.693  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:56:32.693  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 05:56:32.693  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:56:32.693  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 05:56:32.694  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 05:56:32.694  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 05:56:32.694  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:56:32.694  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 05:56:32.696  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:56:32.696  5846  5862 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-29 05:56:32.696  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.696  5846  5865 D BtGatt.ScanManager: stopping BLe Batch
09-29 05:56:32.698  5644  5690 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 05:56:32.698  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 05:56:32.701  5846  5862 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-29 05:56:32.701  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.702  5846  5865 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-29 05:56:32.702  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 05:56:32.702  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 05:56:32.703  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-29 05:56:32.707  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-29 05:56:32.707  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 05:56:32.707  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 05:56:32.707  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 05:56:32.707  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 05:56:32.707  5846  5862 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-29 05:56:32.708  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.709  5644  5690 D BluetoothAdapter: STATE_ON
09-29 05:56:32.711  5846  5886 D BtGatt.GattService: registerClient() - UUID=7a4030f7-b9ac-415f-a594-80d0c26ff1f9
09-29 05:56:32.712  5846  5862 D BtGatt.GattService: onClientRegistered() - UUID=7a4030f7-b9ac-415f-a594-80d0c26ff1f9, clientIf=5
09-29 05:56:32.712  5644  5738 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 05:56:32.712  5846  5856 D BtGatt.GattService: start scan with filters
09-29 05:56:32.714  5846  5865 D BtGatt.ScanManager: handling starting scan
09-29 05:56:32.714  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 05:56:32.714  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 05:56:32.714  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 05:56:32.714  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-29 05:56:32.714  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 05:56:32.714  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 05:56:32.714  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-29 05:56:32.716  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 05:56:32.716  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 05:56:32.716  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 05:56:32.718  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 05:56:32.719  5846  5862 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 05:56:32.719  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.719  5846  5865 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-29 05:56:32.720  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 05:56:32.720  5644  5690 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
09-29 05:56:32.720  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:56:32.720  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:56:32.720  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:56:32.721  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:56:32.721  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.721  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 05:56:32.721  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:56:32.721  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 05:56:32.721  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@376bb0e removed from the list
09-29 05:56:32.721  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:32.721  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@160192f removed from the list
09-29 05:56:32.721  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:56:32.721  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:56:32.721  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.721  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-29 05:56:32.721  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.721  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:56:32.722  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:56:32.722  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:56:32.722  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:32.722  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@160192f not in the list
09-29 05:56:32.722  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 05:56:32.722  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 05:56:32.723  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 05:56:32.723  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 05:56:32.723  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-29 05:56:32.723  5644  5690 D BluetoothAdapter: STATE_ON
09-29 05:56:32.724  5846  5856 D BtGatt.GattService: stopScan() - queue size =1
09-29 05:56:32.724  5846  5882 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 05:56:32.725  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 05:56:32.725  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 05:56:32.725  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 05:56:32.725  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 05:56:32.725  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 05:56:32.725  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 05:56:32.725  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 05:56:32.725  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 05:56:32.725  5846  5862 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 05:56:32.725  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.725  5846  5865 D BtGatt.ScanManager: Starting BLE batch scan
09-29 05:56:32.725  5846  5865 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 05:56:32.726  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:56:32.726  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 05:56:32.726  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 05:56:32.726  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 05:56:32.726  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 05:56:32.727  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:32.728  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:56:32.728  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:56:32.728  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:32.728  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:56:32.728  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e677a1a removed from the list
09-29 05:56:32.729  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:56:32.729  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:56:32.729  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.729  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:56:32.729  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:32.729  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:56:32.729  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 05:56:32.729  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ab0c5 removed from the list
09-29 05:56:32.730  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 05:56:32.730  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9731de6 added. We now have 3 listener(s)
09-29 05:56:32.731  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:56:32.732  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:56:32.732  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:56:32.732  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:56:32.732  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f03ff27 added. We now have 4 listener(s)
09-29 05:56:32.732  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:56:32.732  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 05:56:32.735  5846  5862 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 05:56:32.735  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.735  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:56:32.740  5846  5862 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-29 05:56:32.740  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.741  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:56:32.741  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:56:32.741  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:56:32.741  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:56:32.741  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:56:32.741  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:56:32.741  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:56:32.741  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:56:32.744  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:56:32.744  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:56:32.744  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 05:56:32.744  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ab337d added. We now have 4 listener(s)
09-29 05:56:32.745  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:56:32.745  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:56:32.745  5846  5862 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-29 05:56:32.745  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:56:32.745  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.745  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:56:32.745  5846  5865 D BtGatt.ScanManager: stopping BLe Batch
09-29 05:56:32.745  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a433272 added. We now have 5 listener(s)
09-29 05:56:32.745  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:56:32.746  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 05:56:32.746  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 05:56:32.746  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 05:56:32.746  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:56:32.746  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 05:56:32.746  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:56:32.748  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:56:32.749  5644  5690 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 05:56:32.749  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 05:56:32.750  5846  5862 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-29 05:56:32.750  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.750  5846  5865 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-29 05:56:32.754  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 05:56:32.754  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 05:56:32.754  5846  5862 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-29 05:56:32.754  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-29 05:56:32.754  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.756  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-29 05:56:32.757  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 05:56:32.757  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 05:56:32.757  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 05:56:32.757  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 05:56:32.757  5644  5690 D BluetoothAdapter: STATE_ON
09-29 05:56:32.759  5846  5886 D BtGatt.GattService: registerClient() - UUID=d7dd26f6-7d75-4af1-b5b5-f5ca5706b8a0
09-29 05:56:32.759  5846  5862 D BtGatt.GattService: onClientRegistered() - UUID=d7dd26f6-7d75-4af1-b5b5-f5ca5706b8a0, clientIf=5
09-29 05:56:32.760  5644  5655 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 05:56:32.760  5846  5856 D BtGatt.GattService: start scan with filters
09-29 05:56:32.762  5846  5865 D BtGatt.ScanManager: handling starting scan
09-29 05:56:32.763  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 05:56:32.763  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 05:56:32.763  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 05:56:32.763  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-29 05:56:32.763  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 05:56:32.763  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 05:56:32.763  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-29 05:56:32.765  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 05:56:32.765  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 05:56:32.765  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 05:56:32.766  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 05:56:32.767  5846  5862 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 05:56:32.767  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.767  5846  5865 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-29 05:56:32.770  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:56:32.770  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:56:32.770  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:56:32.770  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:56:32.770  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.770  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 05:56:32.770  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:56:32.770  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 05:56:32.770  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9731de6 removed from the list
09-29 05:56:32.770  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:32.770  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f03ff27 removed from the list
09-29 05:56:32.770  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:56:32.770  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:56:32.772  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.772  5846  5862 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 05:56:32.772  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-29 05:56:32.772  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.772  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.772  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:56:32.772  5846  5865 D BtGatt.ScanManager: Starting BLE batch scan
09-29 05:56:32.772  5846  5865 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 05:56:32.773  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:56:32.773  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:56:32.773  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:32.773  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f03ff27 not in the list
09-29 05:56:32.773  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 05:56:32.773  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 05:56:32.773  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 05:56:32.773  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 05:56:32.773  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-29 05:56:32.773  5644  5690 D BluetoothAdapter: STATE_ON
09-29 05:56:32.774  5846  5857 D BtGatt.GattService: stopScan() - queue size =1
09-29 05:56:32.774  5846  5887 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 05:56:32.775  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 05:56:32.775  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 05:56:32.775  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 05:56:32.775  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 05:56:32.775  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 05:56:32.775  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 05:56:32.775  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 05:56:32.775  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 05:56:32.777  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:56:32.777  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 05:56:32.777  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 05:56:32.777  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 05:56:32.777  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 05:56:32.778  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:32.779  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:56:32.779  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:56:32.779  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:32.779  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:56:32.779  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a433272 removed from the list
09-29 05:56:32.779  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:56:32.779  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:56:32.779  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:56:32.779  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.779  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:32.779  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:56:32.780  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 05:56:32.780  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ab337d removed from the list
09-29 05:56:32.780  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 05:56:32.780  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58e03be added. We now have 3 listener(s)
09-29 05:56:32.782  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:56:32.782  5846  5862 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 05:56:32.782  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.782  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:56:32.782  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:56:32.782  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:56:32.782  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58fac1f added. We now have 4 listener(s)
09-29 05:56:32.783  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:56:32.783  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 05:56:32.786  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:56:32.788  5846  5862 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-29 05:56:32.788  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.790  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:56:32.790  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:56:32.790  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:56:32.790  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:56:32.790  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:56:32.790  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:56:32.790  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:56:32.790  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:56:32.793  5846  5862 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-29 05:56:32.793  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.793  5846  5865 D BtGatt.ScanManager: stopping BLe Batch
,09-29 05:56:32.794  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:56:32.794  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:56:32.794  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 05:56:32.795  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f25535 added. We now have 4 listener(s)
09-29 05:56:32.796  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:56:32.796  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-29 05:56:32.796  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:56:32.796  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:56:32.796  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3229dca added. We now have 5 listener(s)
09-29 05:56:32.796  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:56:32.796  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:56:32.796  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:56:32.796  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 05:56:32.796  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:56:32.796  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.796  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:56:32.796  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:56:32.797  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 05:56:32.797  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58e03be removed from the list
09-29 05:56:32.797  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:32.797  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:56:32.797  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58fac1f removed from the list
09-29 05:56:32.797  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:56:32.797  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:32.797  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.797  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:32.798  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:56:32.798  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:56:32.798  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:32.798  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58fac1f not in the list
09-29 05:56:32.798  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.798  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:32.799  5846  5862 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-29 05:56:32.799  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:56:32.799  5644  5690 I org.,thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:56:32.799  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 05:56:32.799  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:56:32.799  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3229dca removed from the list
09-29 05:56:32.799  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:56:32.799  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:56:32.799  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:56:32.800  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 05:56:32.800  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 05:56:32.800  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f25535 removed from the list
09-29 05:56:32.800  5846  5865 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-29 05:56:32.800  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:56:32.800  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-29 05:56:32.801  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-29 05:56:32.801  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-29 05:56:32.801  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 05:56:32.801  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-29 05:56:32.801  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-29 05:56:32.804  5846  5862 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-29 05:56:32.805  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 05:56:33.172  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 05:56:33.229  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 05:56:33.280  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 05:56:34.934  5644  5944 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-29 05:56:34.934  5644  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 05:56:35.746  5644  5944 W !!      : call onHalfStreamCopied
,09-29 05:56:35.746  5644  5944 I testCopyDataAndClose: closing input stream
,09-29 05:56:36.520  5644  5944 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-29 05:56:36.520  5644  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 05:56:36.520  5644  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 05:56:36.520  5644  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 05:56:36.520  5644  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 05:56:36.520  5644  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 05:56:36.520  5644  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 05:56:36.520  5644  5944 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-29 05:56:36.520  5644  5944 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 05:56:36.520  5644  5944 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-29 05:56:36.520  5644  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-29 05:56:39.128   928  5905 D NetlinkSocketObserver: NeighborEvent{elapsedMs=325990, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-29 05:56:40.285  5644  5946 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-29 05:56:40.285  5644  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 05:56:42.191   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-29 05:56:42.191   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-29 05:56:42.285  5644  5690 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 193. Connection data: Peer properties: [null null].
09-29 05:56:42.285  5644  5690 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 05:56:42.285  5644  5690 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 193, name: My test thread name)
,09-29 05:56:42.353  5644  5946 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-29 05:56:42.353  5644  5946 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-29 05:56:42.353  5644  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-29 05:56:42.432  5644  5947 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-29 05:56:42.432  5644  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 05:56:44.047  5644  5947 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 195, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-29 05:56:44.047  5644  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 05:56:44.047  5644  5947 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 05:56:44.047  5644  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 05:56:44.047  5644  5947 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-29 05:56:44.047  5644  5947 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 05:56:44.047  5644  5947 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 05:56:44.047  5644  5947 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-29 05:56:44.047  5644  5947 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 05:56:44.047  5644  5947 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-29 05:56:44.047  5644  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-29 05:56:47.786  5644  5948 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-29 05:56:47.786  5644  5948 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 05:56:47.786  5644  5948 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 197, thread name: My test thread name). Connection data: Peer properties: [null null].
09-29 05:56:47.786  5644  5948 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 05:56:47.786  5644  5948 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 05:56:47.786  5644  5948 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 05:56:47.786  5644  5948 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 05:56:47.786  5644  5948 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 05:56:47.787  5644  5948 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,09-29 05:56:47.787  5644  5948 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-29 05:56:47.787  5644  5948 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 05:56:47.787  5644  5948 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-29 05:56:47.787  5644  5948 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-29 05:56:47.800  5644  5690 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 05:56:47.805  5644  5949 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-29 05:56:47.805  5644  5949 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 05:56:47.805  5644  5949 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 201, thread name: My test thread name): Test exception.
09-29 05:56:47.806  5644  5949 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-29 05:56:47.806  5644  5949 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-29 05:56:47.806  5644  5949 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
09-29 05:56:47.806  5644  5949 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-29 05:56:47.806  5644  5949 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-29 05:56:47.810  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-29 05:56:47.810  5644  5690 I jxcore-log: 
09-29 05:56:47.811  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-29 05:56:47.811  5644  5690 I jxcore-log: 
,09-29 05:56:47.811  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG UnitTest_app: 'Number of failed tests:  2'
09-29 05:56:47.811  5644  5690 I jxcore-log: 
09-29 05:56:47.811  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-29 05:56:47.811  5644  5690 I jxcore-log: 
09-29 05:56:47.811  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG UnitTest_app: 'Total duration:  102820'
09-29 05:56:47.811  5644  5690 I jxcore-log: 
,09-29 05:56:47.812  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG UnitTest_app: 'Failures: 
09-29 05:56:47.812  5644  5690 I jxcore-log:  OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-29 05:56:47.812  5644  5690 I jxcore-log: Expected: is "Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed."
09-29 05:56:47.812  5644  5690 I jxcore-log:      but: was ""
09-29 05:56:47.812  5644  5690 I jxcore-log: OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-29 05:56:47.812  5644  5690 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-29 05:56:47.812  5644  5690 I jxcore-log:      but: was ""
09-29 05:56:47.812  5644  5690 I jxcore-log: '
09-29 05:56:47.812  5644  5690 I jxcore-log: 
09-29 05:56:47.813  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG UnitTest_app: 'Failed to execute UT.'
09-29 05:56:47.813  5644  5690 I jxcore-log: 
09-29 05:56:47.814  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-29 05:56:47.814  5644  5690 I jxcore-log: 
,09-29 05:56:47.818  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.818  5644  5690 I jxcore-log: 
,09-29 05:56:47.822  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.822  5644  5690 I jxcore-log: 
09-29 05:56:47.823  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.823  5644  5690 I jxcore-log: 
,09-29 05:56:47.823  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.823  5644  5690 I jxcore-log: 
09-29 05:56:47.823  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-29 05:56:47.823  5644  5690 I jxcore-log: 
,09-29 05:56:47.842  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 05:56:47.842  5644  5690 I jxcore-log: 
,09-29 05:56:47.842  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.842  5644  5690 I jxcore-log: 
,09-29 05:56:47.848  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.848  5644  5690 I jxcore-log: 
,09-29 05:56:47.848  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-29 05:56:47.848  5644  5690 I jxcore-log: 
09-29 05:56:47.848  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 05:56:47.848  5644  5690 I jxcore-log: 
09-29 05:56:47.848  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 05:56:47.848  5644  5690 I jxcore-log: 
09-29 05:56:47.849  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.849  5644  5690 I jxcore-log: 
,09-29 05:56:47.849  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.849  5644  5690 I jxcore-log: 
09-29 05:56:47.849  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 05:56:47.849  5644  5690 I jxcore-log: 
09-29 05:56:47.849  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 05:56:47.849  5644  5690 I jxcore-log: 
09-29 05:56:47.850  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 05:56:47.850  5644  5690 I jxcore-log: 
09-29 05:56:47.850  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.850  5644  5690 I jxcore-log: 
09-29 05:56:47.850  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.850  5644  5690 I jxcore-log: 
09-29 05:56:47.850  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.850  5644  5690 I jxcore-log: 
09-29 05:56:47.851  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.851  5644  5690 I jxcore-log: 
09-29 05:56:47.852  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 05:56:47.852  5644  5690 I jxcore-log: 
,09-29 05:56:47.853  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 05:56:47.853  5644  5690 I jxcore-log: 
09-29 05:56:47.856  5644  5644 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-29 05:56:47.856  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 05:56:47.856  5644  5690 I jxcore-log: 
09-29 05:56:47.857  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.857  5644  5690 I jxcore-log: 
09-29 05:56:47.858  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.858  5644  5690 I jxcore-log: 
,09-29 05:56:47.858  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.858  5644  5690 I jxcore-log: 
09-29 05:56:47.859  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.859  5644  5690 I jxcore-log: 
,09-29 05:56:47.860  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.860  5644  5690 I jxcore-log: 
09-29 05:56:47.860  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.860  5644  5690 I jxcore-log: 
,09-29 05:56:47.861  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.861  5644  5690 I jxcore-log: 
09-29 05:56:47.862  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.862  5644  5690 I jxcore-log: 
,09-29 05:56:47.862  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.862  5644  5690 I jxcore-log: 
09-29 05:56:47.863  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.863  5644  5690 I jxcore-log: 
,09-29 05:56:47.864  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.864  5644  5690 I jxcore-log: 
09-29 05:56:47.864  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 05:56:47.864  5644  5690 I jxcore-log: 
,09-29 05:56:47.865  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-29 05:56:47.865  5644  5690 I jxcore-log: 
09-29 05:56:47.866  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-29 05:56:47.866  5644  5690 I jxcore-log: 
,09-29 05:56:47.866  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.866  5644  5690 I jxcore-log: 
,09-29 05:56:47.867  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.867  5644  5690 I jxcore-log: 
09-29 05:56:47.868  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.868  5644  5690 I jxcore-log: 
,09-29 05:56:47.869  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.869  5644  5690 I jxcore-log: 
09-29 05:56:47.869  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.869  5644  5690 I jxcore-log: 
09-29 05:56:47.870  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:56:47.870  5644  5690 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,09-29 05:56:47.871  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.871  5644  5690 I jxcore-log: 
09-29 05:56:47.871  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.871  5644  5690 I jxcore-log: 
09-29 05:56:47.872  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 05:56:47.872  5644  5690 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,09-29 05:56:47.872  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:56:47.872  5644  5690 I jxcore-log: 
09-29 05:56:47.872  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 05:56:47.872  5644  5690 I jxcore-log: 
09-29 05:56:47.873  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 05:56:47.873  5644  5690 I jxcore-log: 
09-29 05:56:47.873  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 05:56:47.873  5644  5690 I jxcore-log: 
,09-29 05:56:47.881  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-29 05:56:47.881  5644  5690 I jxcore-log: 
,09-29 05:56:47.881  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - WARN testUtils: 'myNameCallback not set!'
09-29 05:56:47.881  5644  5690 I jxcore-log: 
,09-29 05:56:47.883  5644  5690 I jxcore-log: 2016-09-29 09:56:47 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-29 05:56:47.883  5644  5690 I jxcore-log: 
,09-29 05:56:49.936  5644  5690 I jxcore-log: 2016-09-29 09:56:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-29 05:56:49.936  5644  5690 I jxcore-log: 
,09-29 05:56:50.271  5644  5690 I jxcore-log: 2016-09-29 09:56:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-29 05:56:50.271  5644  5690 I jxcore-log: 
,09-29 05:56:50.286  5644  5690 I jxcore-log: 2016-09-29 09:56:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-29 05:56:50.286  5644  5690 I jxcore-log: 
,09-29 05:56:51.401  5644  5690 I jxcore-log: 2016-09-29 09:56:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-29 05:56:51.401  5644  5690 I jxcore-log: 
,09-29 05:56:51.562  5644  5690 I jxcore-log: 2016-09-29 09:56:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-29 05:56:51.562  5644  5690 I jxcore-log: 
,09-29 05:56:51.566  5644  5690 I jxcore-log: 2016-09-29 09:56:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-29 05:56:51.566  5644  5690 I jxcore-log: 
,09-29 05:56:51.571  5644  5690 I jxcore-log: 2016-09-29 09:56:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-29 05:56:51.571  5644  5690 I jxcore-log: 
,09-29 05:56:52.115  5644  5690 I jxcore-log: 2016-09-29 09:56:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-29 05:56:52.115  5644  5690 I jxcore-log: 
,09-29 05:56:52.167  5644  5690 I jxcore-log: 2016-09-29 09:56:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-29 05:56:52.167  5644  5690 I jxcore-log: 
,09-29 05:56:52.179  5644  5690 I jxcore-log: 2016-09-29 09:56:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-29 05:56:52.179  5644  5690 I jxcore-log: 
,09-29 05:56:52.184  5644  5690 I jxcore-log: 2016-09-29 09:56:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-29 05:56:52.184  5644  5690 I jxcore-log: 
,09-29 05:56:52.460  5644  5690 I jxcore-log: 2016-09-29 09:56:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-29 05:56:52.460  5644  5690 I jxcore-log: 
,09-29 05:56:52.582  5644  5690 I jxcore-log: 2016-09-29 09:56:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-29 05:56:52.582  5644  5690 I jxcore-log: 
,09-29 05:56:52.804  5644  5690 I jxcore-log: 2016-09-29 09:56:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-29 05:56:52.804  5644  5690 I jxcore-log: 
,09-29 05:56:52.813  5644  5690 I jxcore-log: 2016-09-29 09:56:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
09-29 05:56:52.813  5644  5690 I jxcore-log: 
,09-29 05:56:52.818  5644  5690 I jxcore-log: 2016-09-29 09:56:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-29 05:56:52.818  5644  5690 I jxcore-log: 
,09-29 05:56:52.823  5644  5690 I jxcore-log: 2016-09-29 09:56:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-29 05:56:52.823  5644  5690 I jxcore-log: 
,09-29 05:56:52.965  5644  5690 I jxcore-log: 2016-09-29 09:56:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-29 05:56:52.965  5644  5690 I jxcore-log: 
,09-29 05:56:52.992  5644  5690 I jxcore-log: 2016-09-29 09:56:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-29 05:56:52.992  5644  5690 I jxcore-log: 
,09-29 05:56:53.027  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-29 05:56:53.027  5644  5690 I jxcore-log: 
,09-29 05:56:53.033  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-29 05:56:53.033  5644  5690 I jxcore-log: 
,09-29 05:56:53.039  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-29 05:56:53.039  5644  5690 I jxcore-log: 
,09-29 05:56:53.052  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-29 05:56:53.052  5644  5690 I jxcore-log: 
,09-29 05:56:53.056  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-29 05:56:53.056  5644  5690 I jxcore-log: 
,09-29 05:56:53.062  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-29 05:56:53.062  5644  5690 I jxcore-log: 
,09-29 05:56:53.066  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-29 05:56:53.066  5644  5690 I jxcore-log: 
,09-29 05:56:53.078  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-29 05:56:53.078  5644  5690 I jxcore-log: 
,09-29 05:56:53.097  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-29 05:56:53.097  5644  5690 I jxcore-log: 
,09-29 05:56:53.106  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-29 05:56:53.106  5644  5690 I jxcore-log: 
,09-29 05:56:53.117  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-29 05:56:53.117  5644  5690 I jxcore-log: 
,09-29 05:56:53.126  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-29 05:56:53.126  5644  5690 I jxcore-log: 
,09-29 05:56:53.138  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-29 05:56:53.138  5644  5690 I jxcore-log: 
,09-29 05:56:53.148  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-29 05:56:53.148  5644  5690 I jxcore-log: 
,09-29 05:56:53.152  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-29 05:56:53.152  5644  5690 I jxcore-log: 
,09-29 05:56:53.174  5644  5690 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-29 05:56:53.175  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - INFO testUtils: 'BLE multiple advertisement supported'
09-29 05:56:53.175  5644  5690 I jxcore-log: 
,09-29 05:56:53.296  5644  5690 I jxcore-log: 2016-09-29 09:56:53 - DEBUG CoordinatedClient: 'connected to the test server'
09-29 05:56:53.296  5644  5690 I jxcore-log: 
,09-29 05:56:53.787  5644  5690 I jxcore-log: TAP version 13
09-29 05:56:53.787  5644  5690 I jxcore-log: 
,09-29 05:56:53.830  5644  5690 I jxcore-log: # setup
09-29 05:56:53.830  5644  5690 I jxcore-log: 
,09-29 05:56:54.810  5644  5690 I jxcore-log: # calling createNativeListener directly rejects
09-29 05:56:54.810  5644  5690 I jxcore-log: 
,09-29 05:56:55.387  5644  5690 I jxcore-log: 2016-09-29 09:56:55 - DEBUG createNativeListener: 'creating native server'
09-29 05:56:55.387  5644  5690 I jxcore-log: 
,09-29 05:56:55.393  5644  5690 I jxcore-log: 2016-09-29 09:56:55 - DEBUG createNativeListener: 'listening 37382'
09-29 05:56:55.393  5644  5690 I jxcore-log: 
,09-29 05:56:55.401  5644  5690 I jxcore-log: ok 1 Should throw
09-29 05:56:55.401  5644  5690 I jxcore-log: 
,09-29 05:56:55.412  5644  5690 I jxcore-log: # teardown
09-29 05:56:55.412  5644  5690 I jxcore-log: 
,09-29 05:56:56.119  5644  5690 I jxcore-log: # setup
09-29 05:56:56.119  5644  5690 I jxcore-log: 
,09-29 05:56:56.324  5644  5690 I jxcore-log: # emits incomingConnectionState
09-29 05:56:56.324  5644  5690 I jxcore-log: 
,09-29 05:56:56.958  5644  5690 I jxcore-log: 2016-09-29 09:56:56 - DEBUG createNativeListener: 'creating native server'
09-29 05:56:56.958  5644  5690 I jxcore-log: 
,09-29 05:56:56.963  5644  5690 I jxcore-log: 2016-09-29 09:56:56 - DEBUG createNativeListener: 'listening 41533'
09-29 05:56:56.963  5644  5690 I jxcore-log: 
,09-29 05:56:56.973  5644  5690 I jxcore-log: 2016-09-29 09:56:56 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:56:56.973  5644  5690 I jxcore-log: 
,09-29 05:56:56.976  5644  5690 I jxcore-log: 2016-09-29 09:56:56 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:56:56.976  5644  5690 I jxcore-log: 
,09-29 05:56:56.986  5644  5690 I jxcore-log: 2016-09-29 09:56:56 - DEBUG createNativeListener: 'new mux'
09-29 05:56:56.986  5644  5690 I jxcore-log: 
,09-29 05:56:56.991  5644  5690 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-29 05:56:56.991  5644  5690 I jxcore-log: 
,09-29 05:56:57.011  5644  5690 I jxcore-log: 2016-09-29 09:56:57 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:56:57.011  5644  5690 I jxcore-log: 
,09-29 05:56:57.012  5644  5690 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-29 05:56:57.012  5644  5690 I jxcore-log: 
,09-29 05:56:57.019  5644  5690 I jxcore-log: # teardown
09-29 05:56:57.019  5644  5690 I jxcore-log: 
,09-29 05:56:57.192   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:56:57.963  5644  5690 I jxcore-log: # setup
09-29 05:56:57.963  5644  5690 I jxcore-log: 
,09-29 05:56:58.193   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:56:58.241   928  5905 D NetlinkSocketObserver: NeighborEvent{elapsedMs=345103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-29 05:56:58.873  5644  5690 I jxcore-log: # emits routerPortConnectionFailed
09-29 05:56:58.873  5644  5690 I jxcore-log: 
,09-29 05:56:59.194   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:56:59.405  5644  5690 I jxcore-log: 2016-09-29 09:56:59 - DEBUG createNativeListener: 'creating native server'
09-29 05:56:59.405  5644  5690 I jxcore-log: 
,09-29 05:56:59.409  5644  5690 I jxcore-log: 2016-09-29 09:56:59 - DEBUG createNativeListener: 'listening 40477'
09-29 05:56:59.409  5644  5690 I jxcore-log: 
,09-29 05:56:59.417  5644  5690 I jxcore-log: 2016-09-29 09:56:59 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:56:59.417  5644  5690 I jxcore-log: 
,09-29 05:56:59.418  5644  5690 I jxcore-log: 2016-09-29 09:56:59 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:56:59.418  5644  5690 I jxcore-log: 
,09-29 05:56:59.420  5644  5690 I jxcore-log: 2016-09-29 09:56:59 - DEBUG createNativeListener: 'new mux'
09-29 05:56:59.420  5644  5690 I jxcore-log: 
,09-29 05:56:59.450  5644  5690 I jxcore-log: 2016-09-29 09:56:59 - DEBUG createNativeListener: 'new stream: '
09-29 05:56:59.450  5644  5690 I jxcore-log: 
,09-29 05:56:59.453  5644  5690 I jxcore-log: 2016-09-29 09:56:59 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:56:59.453  5644  5690 I jxcore-log: 
,09-29 05:56:59.458  5644  5690 I jxcore-log: 2016-09-29 09:56:59 - DEBUG createNativeListener: ' $c@net.js:837:7
09-29 05:56:59.458  5644  5690 I jxcore-log: $09@net.js:829:13
09-29 05:56:59.458  5644  5690 I jxcore-log: '
09-29 05:56:59.458  5644  5690 I jxcore-log: 
,09-29 05:56:59.460  5644  5690 I jxcore-log: ok 4 tried to connect to right port
09-29 05:56:59.460  5644  5690 I jxcore-log: 
,09-29 05:56:59.461  5644  5690 I jxcore-log: ok 5 failed due to refused connection
09-29 05:56:59.461  5644  5690 I jxcore-log: 
09-29 05:56:59.461  5644  5690 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-29 05:56:59.461  5644  5690 I jxcore-log: 
,09-29 05:56:59.465  5644  5690 I jxcore-log: # teardown
09-29 05:56:59.465  5644  5690 I jxcore-log: 
,09-29 05:56:59.467  5644  5690 I jxcore-log: 2016-09-29 09:56:59 - DEBUG createNativeListener: 'stream close:'
09-29 05:56:59.467  5644  5690 I jxcore-log: 
,09-29 05:57:00.097  5644  5690 I jxcore-log: 2016-09-29 09:57:00 - DEBUG createNativeListener: 'mux close'
09-29 05:57:00.097  5644  5690 I jxcore-log: 
,09-29 05:57:00.103  5644  5690 I jxcore-log: 2016-09-29 09:57:00 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:00.103  5644  5690 I jxcore-log: 
,09-29 05:57:00.115  5644  5690 I jxcore-log: # setup
09-29 05:57:00.115  5644  5690 I jxcore-log: 
,09-29 05:57:00.195   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:00.316   928  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 05:57:00.519  5644  5690 I jxcore-log: # native server connections all up
09-29 05:57:00.519  5644  5690 I jxcore-log: 
,09-29 05:57:01.196   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:01.427  5644  5690 I jxcore-log: 2016-09-29 09:57:01 - DEBUG createNativeListener: 'creating native server'
09-29 05:57:01.427  5644  5690 I jxcore-log: 
,09-29 05:57:01.431  5644  5690 I jxcore-log: 2016-09-29 09:57:01 - DEBUG createNativeListener: 'listening 47289'
09-29 05:57:01.431  5644  5690 I jxcore-log: 
,09-29 05:57:01.442  5644  5690 I jxcore-log: 2016-09-29 09:57:01 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:01.442  5644  5690 I jxcore-log: 
,09-29 05:57:01.443  5644  5690 I jxcore-log: 2016-09-29 09:57:01 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:01.443  5644  5690 I jxcore-log: 
,09-29 05:57:01.445  5644  5690 I jxcore-log: 2016-09-29 09:57:01 - DEBUG createNativeListener: 'new mux'
09-29 05:57:01.445  5644  5690 I jxcore-log: 
,09-29 05:57:01.472  5644  5690 I jxcore-log: 2016-09-29 09:57:01 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:01.472  5644  5690 I jxcore-log: 
,09-29 05:57:01.475  5644  5690 I jxcore-log: 2016-09-29 09:57:01 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:01.475  5644  5690 I jxcore-log: 
,09-29 05:57:01.478  5644  5690 I jxcore-log: 2016-09-29 09:57:01 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:01.478  5644  5690 I jxcore-log: 
,09-29 05:57:01.481  5644  5690 I jxcore-log: 2016-09-29 09:57:01 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:01.481  5644  5690 I jxcore-log: 
,09-29 05:57:01.501  5644  5690 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-29 05:57:01.501  5644  5690 I jxcore-log: 
,09-29 05:57:01.502  5644  5690 I jxcore-log: ok 8 Send/recvd #1 should be same
09-29 05:57:01.502  5644  5690 I jxcore-log: 
09-29 05:57:01.504  5644  5690 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-29 05:57:01.504  5644  5690 I jxcore-log: 
,09-29 05:57:01.505  5644  5690 I jxcore-log: ok 10 Send/recvd #2 should be same
09-29 05:57:01.505  5644  5690 I jxcore-log: 
,09-29 05:57:01.508  5644  5690 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-29 05:57:01.508  5644  5690 I jxcore-log: 
,09-29 05:57:01.515  5644  5690 I jxcore-log: # teardown
09-29 05:57:01.515  5644  5690 I jxcore-log: 
,09-29 05:57:01.736  5644  5690 I jxcore-log: 2016-09-29 09:57:01 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:01.736  5644  5690 I jxcore-log: 
,09-29 05:57:01.739  5644  5690 I jxcore-log: 2016-09-29 09:57:01 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:01.739  5644  5690 I jxcore-log: 
,09-29 05:57:01.743  5644  5690 I jxcore-log: 2016-09-29 09:57:01 - DEBUG createNativeListener: 'mux close'
09-29 05:57:01.743  5644  5690 I jxcore-log: 
,09-29 05:57:01.749  5644  5690 I jxcore-log: 2016-09-29 09:57:01 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:01.749  5644  5690 I jxcore-log: 
,09-29 05:57:01.760  5644  5690 I jxcore-log: # setup
09-29 05:57:01.760  5644  5690 I jxcore-log: 
,09-29 05:57:02.196   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-29 05:57:02.763  5644  5690 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
09-29 05:57:02.763  5644  5690 I jxcore-log: 
,09-29 05:57:03.165  5644  5690 I jxcore-log: 2016-09-29 09:57:03 - DEBUG createNativeListener: 'creating native server'
09-29 05:57:03.165  5644  5690 I jxcore-log: 
,09-29 05:57:03.179  5644  5690 I jxcore-log: 2016-09-29 09:57:03 - DEBUG createNativeListener: 'listening 44584'
09-29 05:57:03.179  5644  5690 I jxcore-log: 
,09-29 05:57:03.188  5644  5690 I jxcore-log: 2016-09-29 09:57:03 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:03.188  5644  5690 I jxcore-log: 
,09-29 05:57:03.189  5644  5690 I jxcore-log: 2016-09-29 09:57:03 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:03.189  5644  5690 I jxcore-log: 
,09-29 05:57:03.196  5644  5690 I jxcore-log: 2016-09-29 09:57:03 - DEBUG createNativeListener: 'new mux'
09-29 05:57:03.196  5644  5690 I jxcore-log: 
,09-29 05:57:03.208  5644  5690 I jxcore-log: 2016-09-29 09:57:03 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:03.208  5644  5690 I jxcore-log: 
,09-29 05:57:03.212  5644  5690 I jxcore-log: 2016-09-29 09:57:03 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:03.212  5644  5690 I jxcore-log: 
,09-29 05:57:03.225  5644  5690 I jxcore-log: 2016-09-29 09:57:03 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:03.225  5644  5690 I jxcore-log: 
,09-29 05:57:03.239  5644  5690 I jxcore-log: ok 12 socket shouldn't close until after stream
09-29 05:57:03.239  5644  5690 I jxcore-log: 
09-29 05:57:03.239  5644  5690 I jxcore-log: ok 13 incoming remains open
09-29 05:57:03.239  5644  5690 I jxcore-log: 
,09-29 05:57:03.246  5644  5690 I jxcore-log: # teardown
09-29 05:57:03.246  5644  5690 I jxcore-log: 
,09-29 05:57:03.987  5644  5690 I jxcore-log: 2016-09-29 09:57:03 - DEBUG createNativeListener: 'mux close'
09-29 05:57:03.987  5644  5690 I jxcore-log: 
,09-29 05:57:03.998  5644  5690 I jxcore-log: 2016-09-29 09:57:03 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:03.998  5644  5690 I jxcore-log: 
,09-29 05:57:04.007  5644  5690 I jxcore-log: # setup
09-29 05:57:04.007  5644  5690 I jxcore-log: 
,09-29 05:57:04.921  5644  5690 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
09-29 05:57:04.921  5644  5690 I jxcore-log: 
,09-29 05:57:05.129  5644  5690 I jxcore-log: 2016-09-29 09:57:05 - DEBUG createNativeListener: 'creating native server'
09-29 05:57:05.129  5644  5690 I jxcore-log: 
,09-29 05:57:05.134  5644  5690 I jxcore-log: 2016-09-29 09:57:05 - DEBUG createNativeListener: 'listening 37629'
09-29 05:57:05.134  5644  5690 I jxcore-log: 
,09-29 05:57:05.142  5644  5690 I jxcore-log: 2016-09-29 09:57:05 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:05.142  5644  5690 I jxcore-log: 
,09-29 05:57:05.143  5644  5690 I jxcore-log: 2016-09-29 09:57:05 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:05.143  5644  5690 I jxcore-log: 
,09-29 05:57:05.146  5644  5690 I jxcore-log: 2016-09-29 09:57:05 - DEBUG createNativeListener: 'new mux'
09-29 05:57:05.146  5644  5690 I jxcore-log: 
,09-29 05:57:05.155  5644  5690 I jxcore-log: ok 14 we should not have gotten an error
09-29 05:57:05.155  5644  5690 I jxcore-log: 
,09-29 05:57:05.160  5644  5690 I jxcore-log: 2016-09-29 09:57:05 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:05.160  5644  5690 I jxcore-log: 
,09-29 05:57:05.164  5644  5690 I jxcore-log: 2016-09-29 09:57:05 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:05.164  5644  5690 I jxcore-log: 
,09-29 05:57:05.173  5644  5690 I jxcore-log: 2016-09-29 09:57:05 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:05.173  5644  5690 I jxcore-log: 
,09-29 05:57:05.175  5644  5690 I jxcore-log: 2016-09-29 09:57:05 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:05.175  5644  5690 I jxcore-log: 
,09-29 05:57:05.182  5644  5690 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-29 05:57:05.182  5644  5690 I jxcore-log: 
,09-29 05:57:05.183  5644  5690 I jxcore-log: ok 16 incoming is cleaned up
09-29 05:57:05.183  5644  5690 I jxcore-log: 
,09-29 05:57:05.191  5644  5690 I jxcore-log: # teardown
09-29 05:57:05.191  5644  5690 I jxcore-log: 
,09-29 05:57:06.151  5644  5690 I jxcore-log: # setup
09-29 05:57:06.151  5644  5690 I jxcore-log: 
,09-29 05:57:06.558  5644  5690 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
09-29 05:57:06.558  5644  5690 I jxcore-log: 
,09-29 05:57:07.198   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:07.264  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating native server'
09-29 05:57:07.264  5644  5690 I jxcore-log: 
,09-29 05:57:07.269  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'listening 45568'
09-29 05:57:07.269  5644  5690 I jxcore-log: 
,09-29 05:57:07.278  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:07.278  5644  5690 I jxcore-log: 
,09-29 05:57:07.280  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:07.280  5644  5690 I jxcore-log: 
,09-29 05:57:07.285  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new mux'
09-29 05:57:07.285  5644  5690 I jxcore-log: 
,09-29 05:57:07.297  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.297  5644  5690 I jxcore-log: 
,09-29 05:57:07.299  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.299  5644  5690 I jxcore-log: 
,09-29 05:57:07.313  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:07.313  5644  5690 I jxcore-log: 
,09-29 05:57:07.321  5644  5690 I jxcore-log: ok 17 stream was closed
09-29 05:57:07.321  5644  5690 I jxcore-log: 
,09-29 05:57:07.322  5644  5690 I jxcore-log: ok 18 incoming should survive
09-29 05:57:07.322  5644  5690 I jxcore-log: 
09-29 05:57:07.322  5644  5690 I jxcore-log: ok 19 mux should have no streams
09-29 05:57:07.322  5644  5690 I jxcore-log: 
,09-29 05:57:07.328  5644  5690 I jxcore-log: # teardown
09-29 05:57:07.328  5644  5690 I jxcore-log: 
,09-29 05:57:07.400  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'mux close'
09-29 05:57:07.400  5644  5690 I jxcore-log: 
,09-29 05:57:07.418  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:07.418  5644  5690 I jxcore-log: 
,09-29 05:57:07.431  5644  5690 I jxcore-log: # setup
09-29 05:57:07.431  5644  5690 I jxcore-log: 
,09-29 05:57:07.499  5644  5690 I jxcore-log: # native server - closing the whole server cleans everything up
09-29 05:57:07.499  5644  5690 I jxcore-log: 
,09-29 05:57:07.531  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating native server'
09-29 05:57:07.531  5644  5690 I jxcore-log: 
,09-29 05:57:07.536  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'listening 48253'
09-29 05:57:07.536  5644  5690 I jxcore-log: 
,09-29 05:57:07.544  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:07.544  5644  5690 I jxcore-log: 
,09-29 05:57:07.546  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:07.546  5644  5690 I jxcore-log: 
09-29 05:57:07.547  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new mux'
09-29 05:57:07.547  5644  5690 I jxcore-log: 
,09-29 05:57:07.558  5644  5690 I jxcore-log: ok 20 we should not have gotten an error
09-29 05:57:07.558  5644  5690 I jxcore-log: 
,09-29 05:57:07.566  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.566  5644  5690 I jxcore-log: 
,09-29 05:57:07.569  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.569  5644  5690 I jxcore-log: 
,09-29 05:57:07.578  5644  5690 I jxcore-log: ok 21 Buffers are identical
09-29 05:57:07.578  5644  5690 I jxcore-log: 
,09-29 05:57:07.581  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:07.581  5644  5690 I jxcore-log: 
,09-29 05:57:07.584  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'mux close'
09-29 05:57:07.584  5644  5690 I jxcore-log: 
09-29 05:57:07.587  5644  5690 I jxcore-log: ok 22 native server is nulled out
09-29 05:57:07.587  5644  5690 I jxcore-log: 
09-29 05:57:07.587  5644  5690 I jxcore-log: ok 23 native server should be closed
09-29 05:57:07.587  5644  5690 I jxcore-log: 
09-29 05:57:07.588  5644  5690 I jxcore-log: ok 24 incoming has been removed
09-29 05:57:07.588  5644  5690 I jxcore-log: 
,09-29 05:57:07.588  5644  5690 I jxcore-log: ok 25 Incoming should be done
09-29 05:57:07.588  5644  5690 I jxcore-log: 
,09-29 05:57:07.589  5644  5690 I jxcore-log: ok 26 The mux object should be closed
09-29 05:57:07.589  5644  5690 I jxcore-log: 
09-29 05:57:07.590  5644  5690 I jxcore-log: ok 27 The mux stream should be closed
09-29 05:57:07.590  5644  5690 I jxcore-log: 
,09-29 05:57:07.591  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:07.591  5644  5690 I jxcore-log: 
,09-29 05:57:07.605  5644  5690 I jxcore-log: # teardown
09-29 05:57:07.605  5644  5690 I jxcore-log: 
,09-29 05:57:07.643  5644  5690 I jxcore-log: # setup
09-29 05:57:07.643  5644  5690 I jxcore-log: 
,09-29 05:57:07.701  5644  5690 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
09-29 05:57:07.701  5644  5690 I jxcore-log: 
,09-29 05:57:07.743  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating native server'
09-29 05:57:07.743  5644  5690 I jxcore-log: 
,09-29 05:57:07.752  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'listening 46767'
09-29 05:57:07.752  5644  5690 I jxcore-log: 
,09-29 05:57:07.787  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:07.787  5644  5690 I jxcore-log: 
,09-29 05:57:07.788  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:07.788  5644  5690 I jxcore-log: 
09-29 05:57:07.789  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new mux'
09-29 05:57:07.789  5644  5690 I jxcore-log: 
,09-29 05:57:07.793  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:07.793  5644  5690 I jxcore-log: 
,09-29 05:57:07.794  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:07.794  5644  5690 I jxcore-log: 
09-29 05:57:07.795  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new mux'
09-29 05:57:07.795  5644  5690 I jxcore-log: 
09-29 05:57:07.798  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:07.798  5644  5690 I jxcore-log: 
09-29 05:57:07.799  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:07.799  5644  5690 I jxcore-log: 
09-29 05:57:07.800  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new mux'
09-29 05:57:07.800  5644  5690 I jxcore-log: 
,09-29 05:57:07.803  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:07.803  5644  5690 I jxcore-log: 
,09-29 05:57:07.804  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:07.804  5644  5690 I jxcore-log: 
,09-29 05:57:07.806  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new mux'
09-29 05:57:07.806  5644  5690 I jxcore-log: 
,09-29 05:57:07.810  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:07.810  5644  5690 I jxcore-log: 
,09-29 05:57:07.811  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:07.811  5644  5690 I jxcore-log: 
,09-29 05:57:07.814  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new mux'
09-29 05:57:07.814  5644  5690 I jxcore-log: 
,09-29 05:57:07.817  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:07.817  5644  5690 I jxcore-log: 
,09-29 05:57:07.817  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:07.817  5644  5690 I jxcore-log: 
09-29 05:57:07.819  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new mux'
09-29 05:57:07.819  5644  5690 I jxcore-log: 
,09-29 05:57:07.821  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:07.821  5644  5690 I jxcore-log: 
,09-29 05:57:07.822  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:07.822  5644  5690 I jxcore-log: 
09-29 05:57:07.823  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new mux'
09-29 05:57:07.823  5644  5690 I jxcore-log: 
,09-29 05:57:07.830  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:07.830  5644  5690 I jxcore-log: 
,09-29 05:57:07.830  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:07.830  5644  5690 I jxcore-log: 
,09-29 05:57:07.831  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new mux'
09-29 05:57:07.831  5644  5690 I jxcore-log: 
,09-29 05:57:07.832  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:07.832  5644  5690 I jxcore-log: 
09-29 05:57:07.833  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:07.833  5644  5690 I jxcore-log: 
09-29 05:57:07.833  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new mux'
09-29 05:57:07.833  5644  5690 I jxcore-log: 
,09-29 05:57:07.834  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:07.834  5644  5690 I jxcore-log: 
09-29 05:57:07.835  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:07.835  5644  5690 I jxcore-log: 
,09-29 05:57:07.835  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new mux'
09-29 05:57:07.835  5644  5690 I jxcore-log: 
,09-29 05:57:07.890  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.890  5644  5690 I jxcore-log: 
,09-29 05:57:07.892  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.892  5644  5690 I jxcore-log: 
,09-29 05:57:07.893  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.893  5644  5690 I jxcore-log: 
,09-29 05:57:07.894  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.894  5644  5690 I jxcore-log: 
,09-29 05:57:07.895  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.895  5644  5690 I jxcore-log: 
,09-29 05:57:07.896  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.896  5644  5690 I jxcore-log: 
,09-29 05:57:07.897  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.897  5644  5690 I jxcore-log: 
,09-29 05:57:07.898  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.898  5644  5690 I jxcore-log: 
,09-29 05:57:07.900  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.900  5644  5690 I jxcore-log: 
09-29 05:57:07.901  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.901  5644  5690 I jxcore-log: 
,09-29 05:57:07.902  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.902  5644  5690 I jxcore-log: 
,09-29 05:57:07.903  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.903  5644  5690 I jxcore-log: 
09-29 05:57:07.903  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.903  5644  5690 I jxcore-log: 
,09-29 05:57:07.904  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.904  5644  5690 I jxcore-log: 
09-29 05:57:07.905  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.905  5644  5690 I jxcore-log: 
,09-29 05:57:07.906  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.906  5644  5690 I jxcore-log: 
,09-29 05:57:07.907  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.907  5644  5690 I jxcore-log: 
09-29 05:57:07.908  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.908  5644  5690 I jxcore-log: 
,09-29 05:57:07.909  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.909  5644  5690 I jxcore-log: 
09-29 05:57:07.910  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.910  5644  5690 I jxcore-log: 
09-29 05:57:07.910  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.910  5644  5690 I jxcore-log: 
,09-29 05:57:07.911  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.911  5644  5690 I jxcore-log: 
09-29 05:57:07.912  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.912  5644  5690 I jxcore-log: 
,09-29 05:57:07.913  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.913  5644  5690 I jxcore-log: 
,09-29 05:57:07.914  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.914  5644  5690 I jxcore-log: 
09-29 05:57:07.915  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.915  5644  5690 I jxcore-log: 
09-29 05:57:07.916  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.916  5644  5690 I jxcore-log: 
,09-29 05:57:07.916  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.916  5644  5690 I jxcore-log: 
09-29 05:57:07.917  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.917  5644  5690 I jxcore-log: 
09-29 05:57:07.918  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.918  5644  5690 I jxcore-log: 
,09-29 05:57:07.918  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.918  5644  5690 I jxcore-log: 
09-29 05:57:07.919  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.919  5644  5690 I jxcore-log: 
,09-29 05:57:07.920  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.920  5644  5690 I jxcore-log: 
09-29 05:57:07.921  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.921  5644  5690 I jxcore-log: 
,09-29 05:57:07.922  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.922  5644  5690 I jxcore-log: 
09-29 05:57:07.923  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.923  5644  5690 I jxcore-log: 
,09-29 05:57:07.923  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.923  5644  5690 I jxcore-log: 
09-29 05:57:07.924  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.924  5644  5690 I jxcore-log: 
,09-29 05:57:07.925  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.925  5644  5690 I jxcore-log: 
09-29 05:57:07.925  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.925  5644  5690 I jxcore-log: 
,09-29 05:57:07.927  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.927  5644  5690 I jxcore-log: 
09-29 05:57:07.928  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.928  5644  5690 I jxcore-log: 
09-29 05:57:07.928  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.928  5644  5690 I jxcore-log: 
,09-29 05:57:07.929  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.929  5644  5690 I jxcore-log: 
09-29 05:57:07.930  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.930  5644  5690 I jxcore-log: 
,09-29 05:57:07.930  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.930  5644  5690 I jxcore-log: 
09-29 05:57:07.931  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.931  5644  5690 I jxcore-log: 
09-29 05:57:07.932  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.932  5644  5690 I jxcore-log: 
,09-29 05:57:07.938  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.938  5644  5690 I jxcore-log: 
,09-29 05:57:07.940  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.940  5644  5690 I jxcore-log: 
,09-29 05:57:07.941  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.941  5644  5690 I jxcore-log: 
,09-29 05:57:07.942  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.942  5644  5690 I jxcore-log: 
09-29 05:57:07.942  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.942  5644  5690 I jxcore-log: 
09-29 05:57:07.943  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.943  5644  5690 I jxcore-log: 
,09-29 05:57:07.944  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.944  5644  5690 I jxcore-log: 
09-29 05:57:07.945  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.945  5644  5690 I jxcore-log: 
,09-29 05:57:07.946  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.946  5644  5690 I jxcore-log: 
,09-29 05:57:07.947  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.947  5644  5690 I jxcore-log: 
09-29 05:57:07.948  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.948  5644  5690 I jxcore-log: 
09-29 05:57:07.948  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.948  5644  5690 I jxcore-log: 
,09-29 05:57:07.949  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.949  5644  5690 I jxcore-log: 
09-29 05:57:07.950  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.950  5644  5690 I jxcore-log: 
09-29 05:57:07.950  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.950  5644  5690 I jxcore-log: 
,09-29 05:57:07.951  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.951  5644  5690 I jxcore-log: 
,09-29 05:57:07.952  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.952  5644  5690 I jxcore-log: 
09-29 05:57:07.952  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.952  5644  5690 I jxcore-log: 
,09-29 05:57:07.953  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.953  5644  5690 I jxcore-log: 
09-29 05:57:07.954  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.954  5644  5690 I jxcore-log: 
,09-29 05:57:07.954  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.954  5644  5690 I jxcore-log: 
,09-29 05:57:07.955  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.955  5644  5690 I jxcore-log: 
09-29 05:57:07.955  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.955  5644  5690 I jxcore-log: 
,09-29 05:57:07.956  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.956  5644  5690 I jxcore-log: 
09-29 05:57:07.957  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.957  5644  5690 I jxcore-log: 
09-29 05:57:07.958  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.958  5644  5690 I jxcore-log: 
,09-29 05:57:07.958  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.958  5644  5690 I jxcore-log: 
09-29 05:57:07.959  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.959  5644  5690 I jxcore-log: 
,09-29 05:57:07.959  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.959  5644  5690 I jxcore-log: 
09-29 05:57:07.960  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.960  5644  5690 I jxcore-log: 
09-29 05:57:07.961  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:07.961  5644  5690 I jxcore-log: 
,09-29 05:57:07.961  5644  5690 I jxcore-log: 2016-09-29 09:57:07 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:07.961  5644  5690 I jxcore-log: 
,09-29 05:57:08.008  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.008  5644  5690 I jxcore-log: 
,09-29 05:57:08.010  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.010  5644  5690 I jxcore-log: 
,09-29 05:57:08.010  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.010  5644  5690 I jxcore-log: 
,09-29 05:57:08.011  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.011  5644  5690 I jxcore-log: 
09-29 05:57:08.012  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'mux close'
09-29 05:57:08.012  5644  5690 I jxcore-log: 
,09-29 05:57:08.013  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.013  5644  5690 I jxcore-log: 
09-29 05:57:08.013  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.013  5644  5690 I jxcore-log: 
,09-29 05:57:08.014  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.014  5644  5690 I jxcore-log: 
09-29 05:57:08.014  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.014  5644  5690 I jxcore-log: 
09-29 05:57:08.015  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'mux close'
09-29 05:57:08.015  5644  5690 I jxcore-log: 
,09-29 05:57:08.015  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.015  5644  5690 I jxcore-log: 
09-29 05:57:08.016  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.016  5644  5690 I jxcore-log: 
,09-29 05:57:08.016  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.016  5644  5690 I jxcore-log: 
,09-29 05:57:08.016  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.016  5644  5690 I jxcore-log: 
09-29 05:57:08.017  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'mux close'
09-29 05:57:08.017  5644  5690 I jxcore-log: 
09-29 05:57:08.018  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.018  5644  5690 I jxcore-log: 
,09-29 05:57:08.018  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.018  5644  5690 I jxcore-log: 
09-29 05:57:08.019  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.019  5644  5690 I jxcore-log: 
,09-29 05:57:08.019  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.019  5644  5690 I jxcore-log: 
09-29 05:57:08.020  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'mux close'
09-29 05:57:08.020  5644  5690 I jxcore-log: 
09-29 05:57:08.020  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.020  5644  5690 I jxcore-log: 
09-29 05:57:08.021  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.021  5644  5690 I jxcore-log: 
,09-29 05:57:08.021  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.021  5644  5690 I jxcore-log: 
09-29 05:57:08.022  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.022  5644  5690 I jxcore-log: 
09-29 05:57:08.022  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'mux close'
09-29 05:57:08.022  5644  5690 I jxcore-log: 
,09-29 05:57:08.023  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.023  5644  5690 I jxcore-log: 
09-29 05:57:08.023  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.023  5644  5690 I jxcore-log: 
,09-29 05:57:08.024  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.024  5644  5690 I jxcore-log: 
09-29 05:57:08.024  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.024  5644  5690 I jxcore-log: 
09-29 05:57:08.025  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'mux close'
09-29 05:57:08.025  5644  5690 I jxcore-log: 
,09-29 05:57:08.025  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.025  5644  5690 I jxcore-log: 
09-29 05:57:08.026  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.026  5644  5690 I jxcore-log: 
09-29 05:57:08.026  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.026  5644  5690 I jxcore-log: 
,09-29 05:57:08.026  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.026  5644  5690 I jxcore-log: 
09-29 05:57:08.027  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'mux close'
09-29 05:57:08.027  5644  5690 I jxcore-log: 
,09-29 05:57:08.027  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.027  5644  5690 I jxcore-log: 
09-29 05:57:08.028  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.028  5644  5690 I jxcore-log: 
09-29 05:57:08.028  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.028  5644  5690 I jxcore-log: 
,09-29 05:57:08.029  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.029  5644  5690 I jxcore-log: 
09-29 05:57:08.029  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'mux close'
09-29 05:57:08.029  5644  5690 I jxcore-log: 
,09-29 05:57:08.029  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.029  5644  5690 I jxcore-log: 
09-29 05:57:08.030  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.030  5644  5690 I jxcore-log: 
09-29 05:57:08.030  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.030  5644  5690 I jxcore-log: 
,09-29 05:57:08.031  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.031  5644  5690 I jxcore-log: 
,09-29 05:57:08.033  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'mux close'
09-29 05:57:08.033  5644  5690 I jxcore-log: 
,09-29 05:57:08.033  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.033  5644  5690 I jxcore-log: 
,09-29 05:57:08.034  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.034  5644  5690 I jxcore-log: 
09-29 05:57:08.034  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.034  5644  5690 I jxcore-log: 
,09-29 05:57:08.035  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:08.035  5644  5690 I jxcore-log: 
09-29 05:57:08.035  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'mux close'
09-29 05:57:08.035  5644  5690 I jxcore-log: 
,09-29 05:57:08.037  5644  5690 I jxcore-log: ok 28 native server is nulled out
09-29 05:57:08.037  5644  5690 I jxcore-log: 
,09-29 05:57:08.038  5644  5690 I jxcore-log: ok 29 native server should be closed
09-29 05:57:08.038  5644  5690 I jxcore-log: 
09-29 05:57:08.038  5644  5690 I jxcore-log: ok 30 incoming has been removed
09-29 05:57:08.038  5644  5690 I jxcore-log: 
,09-29 05:57:08.041  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:08.041  5644  5690 I jxcore-log: 
,09-29 05:57:08.042  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:08.042  5644  5690 I jxcore-log: 
,09-29 05:57:08.042  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:08.042  5644  5690 I jxcore-log: 
09-29 05:57:08.043  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:08.043  5644  5690 I jxcore-log: 
09-29 05:57:08.043  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:08.043  5644  5690 I jxcore-log: 
,09-29 05:57:08.043  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:08.043  5644  5690 I jxcore-log: 
09-29 05:57:08.043  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:08.043  5644  5690 I jxcore-log: 
09-29 05:57:08.044  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:08.044  5644  5690 I jxcore-log: 
09-29 05:57:08.044  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:08.044  5644  5690 I jxcore-log: 
09-29 05:57:08.044  5644  5690 I jxcore-log: 2016-09-29 09:57:08 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:08.044  5644  5690 I jxcore-log: 
,09-29 05:57:08.116  5644  5690 I jxcore-log: # teardown
09-29 05:57:08.116  5644  5690 I jxcore-log: 
,09-29 05:57:08.191  5644  5690 I jxcore-log: # setup
09-29 05:57:08.191  5644  5690 I jxcore-log: 
,09-29 05:57:08.198   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:09.199   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:09.928  5644  5690 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
09-29 05:57:09.928  5644  5690 I jxcore-log: 
,09-29 05:57:10.201   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:10.335  5644  5690 I jxcore-log: 2016-09-29 09:57:10 - DEBUG createNativeListener: 'creating native server'
09-29 05:57:10.335  5644  5690 I jxcore-log: 
,09-29 05:57:10.342  5644  5690 I jxcore-log: 2016-09-29 09:57:10 - DEBUG createNativeListener: 'listening 45952'
09-29 05:57:10.342  5644  5690 I jxcore-log: 
,09-29 05:57:10.350  5644  5690 I jxcore-log: 2016-09-29 09:57:10 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:10.350  5644  5690 I jxcore-log: 
,09-29 05:57:10.352  5644  5690 I jxcore-log: 2016-09-29 09:57:10 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:10.352  5644  5690 I jxcore-log: 
09-29 05:57:10.354  5644  5690 I jxcore-log: 2016-09-29 09:57:10 - DEBUG createNativeListener: 'new mux'
09-29 05:57:10.354  5644  5690 I jxcore-log: 
,09-29 05:57:10.364  5644  5690 I jxcore-log: ok 31 we should not have gotten an error
09-29 05:57:10.364  5644  5690 I jxcore-log: 
,09-29 05:57:10.368  5644  5690 I jxcore-log: 2016-09-29 09:57:10 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:10.368  5644  5690 I jxcore-log: 
,09-29 05:57:10.371  5644  5690 I jxcore-log: 2016-09-29 09:57:10 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:10.371  5644  5690 I jxcore-log: 
,09-29 05:57:10.379  5644  5690 I jxcore-log: ok 32 Buffers are identical
09-29 05:57:10.379  5644  5690 I jxcore-log: 
,09-29 05:57:10.381  5644  5690 I jxcore-log: 2016-09-29 09:57:10 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:10.381  5644  5690 I jxcore-log: 
,09-29 05:57:10.383  5644  5690 I jxcore-log: 2016-09-29 09:57:10 - DEBUG createNativeListener: 'mux close'
09-29 05:57:10.383  5644  5690 I jxcore-log: 
,09-29 05:57:10.394  5644  5690 I jxcore-log: 2016-09-29 09:57:10 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:10.394  5644  5690 I jxcore-log: 
,09-29 05:57:10.395  5644  5690 I jxcore-log: ok 33 server should be fine
09-29 05:57:10.395  5644  5690 I jxcore-log: 
09-29 05:57:10.396  5644  5690 I jxcore-log: ok 34 server should be open
09-29 05:57:10.396  5644  5690 I jxcore-log: 
09-29 05:57:10.396  5644  5690 I jxcore-log: ok 35 incoming has been removed
09-29 05:57:10.396  5644  5690 I jxcore-log: 
09-29 05:57:10.396  5644  5690 I jxcore-log: ok 36 The mux object should be closed
09-29 05:57:10.396  5644  5690 I jxcore-log: 
,09-29 05:57:10.397  5644  5690 I jxcore-log: ok 37 The mux stream should be closed
09-29 05:57:10.397  5644  5690 I jxcore-log: 
,09-29 05:57:10.403  5644  5690 I jxcore-log: # teardown
09-29 05:57:10.403  5644  5690 I jxcore-log: 
,09-29 05:57:11.202   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:11.262  5644  5690 I jxcore-log: # setup
09-29 05:57:11.262  5644  5690 I jxcore-log: 
,09-29 05:57:12.203   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-29 05:57:12.414  5644  5690 I jxcore-log: # native server - timing out the incoming connection cleans everything up
09-29 05:57:12.414  5644  5690 I jxcore-log: 
,09-29 05:57:12.446  5644  5690 I jxcore-log: 2016-09-29 09:57:12 - DEBUG createNativeListener: 'creating native server'
09-29 05:57:12.446  5644  5690 I jxcore-log: 
,09-29 05:57:12.450  5644  5690 I jxcore-log: 2016-09-29 09:57:12 - DEBUG createNativeListener: 'listening 39502'
09-29 05:57:12.450  5644  5690 I jxcore-log: 
,09-29 05:57:12.456  5644  5690 I jxcore-log: 2016-09-29 09:57:12 - DEBUG createNativeListener: 'new incoming socket'
09-29 05:57:12.456  5644  5690 I jxcore-log: 
,09-29 05:57:12.458  5644  5690 I jxcore-log: 2016-09-29 09:57:12 - DEBUG createNativeListener: 'creating incoming mux'
09-29 05:57:12.458  5644  5690 I jxcore-log: 
,09-29 05:57:12.460  5644  5690 I jxcore-log: 2016-09-29 09:57:12 - DEBUG createNativeListener: 'new mux'
09-29 05:57:12.460  5644  5690 I jxcore-log: 
,09-29 05:57:12.467  5644  5690 I jxcore-log: ok 38 we should not have gotten an error
09-29 05:57:12.467  5644  5690 I jxcore-log: 
,09-29 05:57:12.471  5644  5690 I jxcore-log: 2016-09-29 09:57:12 - DEBUG createNativeListener: 'new stream: '
09-29 05:57:12.471  5644  5690 I jxcore-log: 
,09-29 05:57:12.474  5644  5690 I jxcore-log: 2016-09-29 09:57:12 - DEBUG createNativeListener: 'new outgoing socket'
09-29 05:57:12.474  5644  5690 I jxcore-log: 
,09-29 05:57:12.481  5644  5690 I jxcore-log: ok 39 Buffers are identical
09-29 05:57:12.481  5644  5690 I jxcore-log: 
,09-29 05:57:12.486  5644  5690 I jxcore-log: 2016-09-29 09:57:12 - DEBUG createNativeListener: 'incoming socket timeout'
09-29 05:57:12.486  5644  5690 I jxcore-log: 
,09-29 05:57:12.487  5644  5690 I jxcore-log: 2016-09-29 09:57:12 - DEBUG createNativeListener: 'stream close:'
09-29 05:57:12.487  5644  5690 I jxcore-log: 
09-29 05:57:12.489  5644  5690 I jxcore-log: 2016-09-29 09:57:12 - DEBUG createNativeListener: 'mux close'
09-29 05:57:12.489  5644  5690 I jxcore-log: 
09-29 05:57:12.494  5644  5690 I jxcore-log: 2016-09-29 09:57:12 - DEBUG createNativeListener: 'incoming socket close'
09-29 05:57:12.494  5644  5690 I jxcore-log: 
09-29 05:57:12.494  5644  5690 I jxcore-log: ok 40 server should be fine
09-29 05:57:12.494  5644  5690 I jxcore-log: 
,09-29 05:57:12.495  5644  5690 I jxcore-log: ok 41 server should be open
09-29 05:57:12.495  5644  5690 I jxcore-log: 
09-29 05:57:12.496  5644  5690 I jxcore-log: ok 42 incoming has been removed
09-29 05:57:12.496  5644  5690 I jxcore-log: 
,09-29 05:57:12.496  5644  5690 I jxcore-log: ok 43 The mux object should be closed
09-29 05:57:12.496  5644  5690 I jxcore-log: 
09-29 05:57:12.497  5644  5690 I jxcore-log: ok 44 The mux stream should be closed
09-29 05:57:12.497  5644  5690 I jxcore-log: 
,09-29 05:57:12.505  5644  5690 I jxcore-log: # teardown
09-29 05:57:12.505  5644  5690 I jxcore-log: 
,09-29 05:57:13.520  5644  5690 I jxcore-log: # setup
09-29 05:57:13.520  5644  5690 I jxcore-log: 
,09-29 05:57:13.558  5644  5690 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
09-29 05:57:13.558  5644  5690 I jxcore-log: 
,09-29 05:57:13.757  5644  5690 I jxcore-log: 2016-09-29 09:57:13 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
09-29 05:57:13.757  5644  5690 I jxcore-log: 
,09-29 05:57:13.758  5644  5690 I jxcore-log: ok 45 Got right error
09-29 05:57:13.758  5644  5690 I jxcore-log: 
,09-29 05:57:13.762  5644  5690 I jxcore-log: # teardown
09-29 05:57:13.762  5644  5690 I jxcore-log: 
,09-29 05:57:13.792  5644  5690 I jxcore-log: # setup
09-29 05:57:13.792  5644  5690 I jxcore-log: 
,09-29 05:57:13.859  5644  5690 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
09-29 05:57:13.859  5644  5690 I jxcore-log: 
,09-29 05:57:13.962  5644  5690 I jxcore-log: 2016-09-29 09:57:13 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
09-29 05:57:13.962  5644  5690 I jxcore-log: 
,09-29 05:57:13.963  5644  5690 I jxcore-log: ok 46 Got socket hang up
09-29 05:57:13.963  5644  5690 I jxcore-log: 
,09-29 05:57:13.969  5644  5690 I jxcore-log: # teardown
09-29 05:57:13.969  5644  5690 I jxcore-log: 
,09-29 05:57:13.996  5644  5690 I jxcore-log: # setup
09-29 05:57:13.996  5644  5690 I jxcore-log: 
,09-29 05:57:14.058  5644  5690 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
09-29 05:57:14.058  5644  5690 I jxcore-log: 
,09-29 05:57:14.249  5644  5690 I jxcore-log: 2016-09-29 09:57:14 - DEBUG localSeqManager: 'Got an error trying to update seq []'
09-29 05:57:14.249  5644  5690 I jxcore-log: 
,09-29 05:57:14.250  5644  5690 I jxcore-log: ok 47 Got 500 as expected
09-29 05:57:14.250  5644  5690 I jxcore-log: 
,09-29 05:57:14.254  5644  5690 I jxcore-log: # teardown
09-29 05:57:14.254  5644  5690 I jxcore-log: 
,09-29 05:57:14.284  5644  5690 I jxcore-log: # setup
09-29 05:57:14.284  5644  5690 I jxcore-log: 
,09-29 05:57:14.356  5644  5690 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
09-29 05:57:14.356  5644  5690 I jxcore-log: 
,09-29 05:57:15.959  5644  5690 I jxcore-log: ok 48 should be equal
09-29 05:57:15.959  5644  5690 I jxcore-log: 
,09-29 05:57:15.959  5644  5690 I jxcore-log: ok 49 revs are equal
09-29 05:57:15.959  5644  5690 I jxcore-log: 
,09-29 05:57:15.967  5644  5690 I jxcore-log: # teardown
09-29 05:57:15.967  5644  5690 I jxcore-log: 
,09-29 05:57:16.016  5644  5690 I jxcore-log: # setup
09-29 05:57:16.016  5644  5690 I jxcore-log: 
,09-29 05:57:16.677  5644  5690 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
09-29 05:57:16.677  5644  5690 I jxcore-log: 
,09-29 05:57:17.420  5644  5690 I jxcore-log: ok 50 should be equal
09-29 05:57:17.420  5644  5690 I jxcore-log: 
,09-29 05:57:17.421  5644  5690 I jxcore-log: ok 51 revs are equal
09-29 05:57:17.421  5644  5690 I jxcore-log: 
,09-29 05:57:17.427  5644  5690 I jxcore-log: # teardown
09-29 05:57:17.427  5644  5690 I jxcore-log: 
,09-29 05:57:17.473  5644  5690 I jxcore-log: # setup
09-29 05:57:17.473  5644  5690 I jxcore-log: 
,09-29 05:57:17.527  5644  5690 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
09-29 05:57:17.527  5644  5690 I jxcore-log: 
,09-29 05:57:18.056  5644  5690 I jxcore-log: ok 52 should be equal
09-29 05:57:18.056  5644  5690 I jxcore-log: 
,09-29 05:57:18.056  5644  5690 I jxcore-log: ok 53 revs are equal
09-29 05:57:18.056  5644  5690 I jxcore-log: 
,09-29 05:57:18.219  5644  5690 I jxcore-log: ok 54 should be equal
09-29 05:57:18.219  5644  5690 I jxcore-log: 
,09-29 05:57:18.219  5644  5690 I jxcore-log: ok 55 revs are equal
09-29 05:57:18.219  5644  5690 I jxcore-log: 
,09-29 05:57:18.402  5644  5690 I jxcore-log: ok 56 should be equal
09-29 05:57:18.402  5644  5690 I jxcore-log: 
09-29 05:57:18.402  5644  5690 I jxcore-log: ok 57 revs are equal
09-29 05:57:18.402  5644  5690 I jxcore-log: 
,09-29 05:57:18.409  5644  5690 I jxcore-log: # teardown
09-29 05:57:18.409  5644  5690 I jxcore-log: 
,09-29 05:57:18.470  5644  5690 I jxcore-log: # setup
09-29 05:57:18.470  5644  5690 I jxcore-log: 
,09-29 05:57:18.503  5644  5690 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
09-29 05:57:18.503  5644  5690 I jxcore-log: 
,09-29 05:57:19.057  5644  5690 I jxcore-log: 2016-09-29 09:57:19 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-29 05:57:19.057  5644  5690 I jxcore-log: 
,09-29 05:57:19.058  5644  5690 I jxcore-log: ok 58 Our rev is old so we should fail
09-29 05:57:19.058  5644  5690 I jxcore-log: 
,09-29 05:57:19.061  5644  5690 I jxcore-log: # teardown
09-29 05:57:19.061  5644  5690 I jxcore-log: 
,09-29 05:57:19.142  5644  5690 I jxcore-log: # setup
09-29 05:57:19.142  5644  5690 I jxcore-log: 
,09-29 05:57:19.163  5644  5690 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
09-29 05:57:19.163  5644  5690 I jxcore-log: 
,09-29 05:57:19.278  5644  5690 I jxcore-log: ok 59 confirm stop caused failure
09-29 05:57:19.278  5644  5690 I jxcore-log: 
,09-29 05:57:19.289  5644  5690 I jxcore-log: # teardown
09-29 05:57:19.289  5644  5690 I jxcore-log: 
,09-29 05:57:19.317  5644  5690 I jxcore-log: # setup
09-29 05:57:19.317  5644  5690 I jxcore-log: 
,09-29 05:57:19.363  5644  5690 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
09-29 05:57:19.363  5644  5690 I jxcore-log: 
,09-29 05:57:19.671  5644  5690 I jxcore-log: 2016-09-29 09:57:19 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
09-29 05:57:19.671  5644  5690 I jxcore-log: 
09-29 05:57:19.672  5644  5690 I jxcore-log: ok 60 stop caused us to fail
09-29 05:57:19.672  5644  5690 I jxcore-log: 
09-29 05:57:19.673  5644  5690 I jxcore-log: ok 61 We specifically failed on a stop before put
09-29 05:57:19.673  5644  5690 I jxcore-log: 
,09-29 05:57:19.680  5644  5690 I jxcore-log: # teardown
09-29 05:57:19.680  5644  5690 I jxcore-log: 
,09-29 05:57:19.799  5644  5690 I jxcore-log: # setup
09-29 05:57:19.799  5644  5690 I jxcore-log: 
,09-29 05:57:19.866  5644  5690 I jxcore-log: # #update - fail if stop is called
09-29 05:57:19.866  5644  5690 I jxcore-log: 
,09-29 05:57:19.936  5644  5690 I jxcore-log: ok 62 failed due to stop
09-29 05:57:19.936  5644  5690 I jxcore-log: 
,09-29 05:57:19.937  5644  5690 I jxcore-log: ok 63 failed due to stop
09-29 05:57:19.937  5644  5690 I jxcore-log: 
,09-29 05:57:19.945  5644  5690 I jxcore-log: # teardown
09-29 05:57:19.945  5644  5690 I jxcore-log: 
,09-29 05:57:20.022  5644  5690 I jxcore-log: # setup
09-29 05:57:20.022  5644  5690 I jxcore-log: 
,09-29 05:57:20.075  5644  5690 I jxcore-log: # #update - set seq for first time
09-29 05:57:20.075  5644  5690 I jxcore-log: 
,09-29 05:57:20.318   928  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 05:57:20.500  5644  5690 I jxcore-log: ok 64 should be equal
09-29 05:57:20.500  5644  5690 I jxcore-log: 
,09-29 05:57:20.506  5644  5690 I jxcore-log: # teardown
09-29 05:57:20.506  5644  5690 I jxcore-log: 
,09-29 05:57:20.603  5644  5690 I jxcore-log: # setup
09-29 05:57:20.603  5644  5690 I jxcore-log: 
,09-29 05:57:20.645  5644  5690 I jxcore-log: # #update - Fail on bad seq value
09-29 05:57:20.645  5644  5690 I jxcore-log: 
,09-29 05:57:21.189  5644  5690 I jxcore-log: 2016-09-29 09:57:21 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
09-29 05:57:21.189  5644  5690 I jxcore-log: 
,09-29 05:57:21.190  5644  5690 I jxcore-log: ok 65 Expected bad seq error
09-29 05:57:21.190  5644  5690 I jxcore-log: 
,09-29 05:57:21.195  5644  5690 I jxcore-log: # teardown
09-29 05:57:21.195  5644  5690 I jxcore-log: 
,09-29 05:57:21.238  5644  5690 I jxcore-log: # setup
09-29 05:57:21.238  5644  5690 I jxcore-log: 
,09-29 05:57:21.280  5644  5690 I jxcore-log: # #update - do we cancel timer properly on an immediate?
09-29 05:57:21.280  5644  5690 I jxcore-log: 
,09-29 05:57:21.684  5644  5690 I jxcore-log: ok 66 Different promises
09-29 05:57:21.684  5644  5690 I jxcore-log: 
,09-29 05:57:21.686  5644  5690 I jxcore-log: ok 67 Timer was cancelled
09-29 05:57:21.686  5644  5690 I jxcore-log: 
,09-29 05:57:21.827  5644  5690 I jxcore-log: ok 68 should be equal
09-29 05:57:21.827  5644  5690 I jxcore-log: 
,09-29 05:57:21.834  5644  5690 I jxcore-log: # teardown
09-29 05:57:21.834  5644  5690 I jxcore-log: 
,09-29 05:57:22.204   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:23.205   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:23.571  5644  5690 I jxcore-log: # setup
09-29 05:57:23.571  5644  5690 I jxcore-log: 
,09-29 05:57:23.603  5644  5690 I jxcore-log: # #update - do we wait for blocked update
09-29 05:57:23.603  5644  5690 I jxcore-log: 
,09-29 05:57:23.702  5644  5690 I jxcore-log: ok 69 One go and one blocked
09-29 05:57:23.702  5644  5690 I jxcore-log: 
,09-29 05:57:23.703  5644  5690 I jxcore-log: ok 70 All blocked
09-29 05:57:23.703  5644  5690 I jxcore-log: 
09-29 05:57:23.703  5644  5690 I jxcore-log: ok 71 Still blocked
09-29 05:57:23.703  5644  5690 I jxcore-log: 
,09-29 05:57:24.131  5644  5690 I jxcore-log: ok 72 should be equal
09-29 05:57:24.131  5644  5690 I jxcore-log: 
,09-29 05:57:24.138  5644  5690 I jxcore-log: # teardown
09-29 05:57:24.138  5644  5690 I jxcore-log: 
,09-29 05:57:24.203  5644  5690 I jxcore-log: # setup
09-29 05:57:24.203  5644  5690 I jxcore-log: 
,09-29 05:57:24.206   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:24.249  5644  5690 I jxcore-log: # #update - test that we wait long enough
09-29 05:57:24.249  5644  5690 I jxcore-log: 
,09-29 05:57:25.207   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:25.628  5644  5690 I jxcore-log: ok 73 We waited long enough
09-29 05:57:25.628  5644  5690 I jxcore-log: 
,09-29 05:57:26.065  5644  5690 I jxcore-log: ok 74 should be equal
09-29 05:57:26.065  5644  5690 I jxcore-log: 
,09-29 05:57:26.071  5644  5690 I jxcore-log: # teardown
09-29 05:57:26.071  5644  5690 I jxcore-log: 
,09-29 05:57:26.105  5644  5690 I jxcore-log: # setup
09-29 05:57:26.105  5644  5690 I jxcore-log: 
,09-29 05:57:26.155  5644  5690 I jxcore-log: # #update - test that we pick up new sequences while we wait
09-29 05:57:26.155  5644  5690 I jxcore-log: 
,09-29 05:57:26.208   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:26.585  5644  5690 I jxcore-log: ok 75 Should have gotten same timer promise
09-29 05:57:26.585  5644  5690 I jxcore-log: 
,09-29 05:57:26.586  5644  5690 I jxcore-log: ok 76 Still same timer promise
09-29 05:57:26.586  5644  5690 I jxcore-log: 
,09-29 05:57:27.209   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-29 05:57:27.364  5644  5690 I jxcore-log: ok 77 We waited long enough
09-29 05:57:27.364  5644  5690 I jxcore-log: 
,09-29 05:57:27.431  5644  5690 I jxcore-log: ok 78 should be equal
09-29 05:57:27.431  5644  5690 I jxcore-log: 
,09-29 05:57:27.437  5644  5690 I jxcore-log: # teardown
09-29 05:57:27.437  5644  5690 I jxcore-log: 
,09-29 05:57:27.501  5644  5690 I jxcore-log: # setup
09-29 05:57:27.501  5644  5690 I jxcore-log: 
,09-29 05:57:27.569  5644  5690 I jxcore-log: # Coordinated seq test
09-29 05:57:27.569  5644  5690 I jxcore-log: 
,09-29 05:57:27.574  5644  5690 I jxcore-log: 2016-09-29 09:57:27 - INFO CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
09-29 05:57:27.574  5644  5690 I jxcore-log: 
,09-29 05:57:27.674  5644  5690 I jxcore-log: # teardown
09-29 05:57:27.674  5644  5690 I jxcore-log: 
,09-29 05:57:27.767  5644  5690 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-29 05:57:27.768  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:57:27.769  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:57:27.769  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-29 05:57:27.784  5644  5690 I jxcore-log: # setup
09-29 05:57:27.784  5644  5690 I jxcore-log: 
,09-29 05:57:27.814  5644  5690 I jxcore-log: # closeAll can close even when connections open
09-29 05:57:27.814  5644  5690 I jxcore-log: 
,09-29 05:57:27.985  5644  5690 I jxcore-log: ok 79 not possible to connect to the server anymore
09-29 05:57:27.985  5644  5690 I jxcore-log: 
,09-29 05:57:27.999  5644  5690 I jxcore-log: # teardown
09-29 05:57:27.999  5644  5690 I jxcore-log: 
,09-29 05:57:28.034  5644  5690 I jxcore-log: # setup
09-29 05:57:28.034  5644  5690 I jxcore-log: 
,09-29 05:57:28.070  5644  5690 I jxcore-log: # closeAll with promise
09-29 05:57:28.070  5644  5690 I jxcore-log: 
,09-29 05:57:28.225  5644  5690 I jxcore-log: ok 80 not possible to connect to the server anymore
09-29 05:57:28.225  5644  5690 I jxcore-log: 
,09-29 05:57:28.234  5644  5690 I jxcore-log: # teardown
09-29 05:57:28.234  5644  5690 I jxcore-log: 
,09-29 05:57:28.268  5644  5690 I jxcore-log: # setup
09-29 05:57:28.268  5644  5690 I jxcore-log: 
,09-29 05:57:28.312  5644  5690 I jxcore-log: # closeAll properly throws when closing a non open server with eatNotRunning set to false
09-29 05:57:28.312  5644  5690 I jxcore-log: 
,09-29 05:57:28.460  5644  5690 I jxcore-log: ok 81 Got the right error
09-29 05:57:28.460  5644  5690 I jxcore-log: 
,09-29 05:57:28.474  5644  5690 I jxcore-log: # teardown
09-29 05:57:28.474  5644  5690 I jxcore-log: 
,09-29 05:57:28.514  5644  5690 I jxcore-log: # setup
09-29 05:57:28.514  5644  5690 I jxcore-log: 
,09-29 05:57:28.545  5644  5690 I jxcore-log: # closeAll works even with a server that is not listening yet witheatNotRunning set to true
09-29 05:57:28.545  5644  5690 I jxcore-log: 
,09-29 05:57:28.694  5644  5690 I jxcore-log: # teardown
09-29 05:57:28.694  5644  5690 I jxcore-log: 
,09-29 05:57:28.760  5644  5690 I jxcore-log: # setup
09-29 05:57:28.760  5644  5690 I jxcore-log: 
,09-29 05:57:28.816  5644  5690 I jxcore-log: # onPeerLost calls jxcore
09-29 05:57:28.816  5644  5690 I jxcore-log: 
,09-29 05:57:28.898  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 05:57:28.899  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60ceb3b added. We now have 3 listener(s)
09-29 05:57:28.901  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:57:28.901  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:57:28.901  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:57:28.901  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:57:28.901  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dce5258 added. We now have 4 listener(s)
09-29 05:57:28.901  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:57:28.903  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 05:57:28.908  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:57:28.916  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:57:28.916  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:57:28.916  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:57:28.916  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:57:28.916  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:57:28.916  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:57:28.916  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:57:28.916  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:57:28.920  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 05:57:28.921  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:57:28.921  5644  5690 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
,09-29 05:57:28.921  5644  5690 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,09-29 05:57:28.924  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:57:28.927  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:57:30.924  5644  5690 I jxcore-log: onPeerLost
09-29 05:57:30.924  5644  5690 I jxcore-log: 
,09-29 05:57:30.927  5644  5690 I jxcore-log: 2016-09-29 09:57:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:57:30.927  5644  5690 I jxcore-log: 
,09-29 05:57:30.942  5644  5690 I jxcore-log: # teardown
09-29 05:57:30.942  5644  5690 I jxcore-log: 
,09-29 05:57:30.947  5644  5690 I jxcore-log: ok 82 check if callback was fired by onPeerLost
09-29 05:57:30.947  5644  5690 I jxcore-log: 
,09-29 05:57:30.949  5644  5690 I jxcore-log: ok 83 check if peerAvailable is false
09-29 05:57:30.949  5644  5690 I jxcore-log: 
,09-29 05:57:31.018  5644  5690 I jxcore-log: 2016-09-29 09:57:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-29 05:57:31.018  5644  5690 I jxcore-log: 
,09-29 05:57:31.022  5644  5690 I jxcore-log: 2016-09-29 09:57:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-29 05:57:31.022  5644  5690 I jxcore-log: 
,09-29 05:57:31.033  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:57:31.033  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:57:31.033  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:57:31.033  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:57:31.033  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:57:31.033  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:57:31.033  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:57:31.033  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:57:31.036  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 05:57:31.038  5644  5690 I jxcore-log: 2016-09-29 09:57:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-29 05:57:31.038  5644  5690 I jxcore-log: 
,09-29 05:57:31.040  5644  5690 I jxcore-log: 2016-09-29 09:57:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-29 05:57:31.040  5644  5690 I jxcore-log: 
,09-29 05:57:31.045  5644  5690 I jxcore-log: 2016-09-29 09:57:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:57:31.045  5644  5690 I jxcore-log: 
,09-29 05:57:31.049  5644  5690 I jxcore-log: # setup
09-29 05:57:31.049  5644  5690 I jxcore-log: 
,09-29 05:57:31.433  5644  5690 I jxcore-log: # onPeerDiscovered calls jxcore
09-29 05:57:31.433  5644  5690 I jxcore-log: 
,09-29 05:57:31.483  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 05:57:31.484  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b4cc96 added. We now have 4 listener(s)
,09-29 05:57:31.486  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-29 05:57:31.486  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:57:31.486  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:57:31.487  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:57:31.487  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3550017 added. We now have 5 listener(s)
09-29 05:57:31.487  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 05:57:31.489  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 05:57:31.494  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:57:31.500  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:57:31.500  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:57:31.500  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:57:31.500  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:57:31.500  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:57:31.500  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:57:31.500  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:57:31.500  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:57:31.502  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:57:31.502  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:57:31.502  5644  5690 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
09-29 05:57:31.505  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:57:31.507  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:57:33.505  5644  5690 I jxcore-log: onPeerDiscovered
09-29 05:57:33.505  5644  5690 I jxcore-log: 
,09-29 05:57:33.507  5644  5690 I jxcore-log: 2016-09-29 09:57:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:57:33.507  5644  5690 I jxcore-log: 
,09-29 05:57:33.520  5644  5690 I jxcore-log: # teardown
09-29 05:57:33.520  5644  5690 I jxcore-log: 
,09-29 05:57:33.525  5644  5690 I jxcore-log: ok 84 check if callback was fired by onPeerDiscovered
09-29 05:57:33.525  5644  5690 I jxcore-log: 
,09-29 05:57:33.526  5644  5690 I jxcore-log: ok 85 check if peerAvailable is true
09-29 05:57:33.526  5644  5690 I jxcore-log: 
,09-29 05:57:33.678  5644  5690 I jxcore-log: 2016-09-29 09:57:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-29 05:57:33.678  5644  5690 I jxcore-log: 
,09-29 05:57:33.682  5644  5690 I jxcore-log: 2016-09-29 09:57:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-29 05:57:33.682  5644  5690 I jxcore-log: 
,09-29 05:57:33.690  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:57:33.690  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:57:33.690  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:57:33.690  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:57:33.690  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:57:33.690  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:57:33.690  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:57:33.690  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:57:33.693  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 05:57:33.695  5644  5690 I jxcore-log: 2016-09-29 09:57:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-29 05:57:33.695  5644  5690 I jxcore-log: 
,09-29 05:57:33.697  5644  5690 I jxcore-log: 2016-09-29 09:57:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-29 05:57:33.697  5644  5690 I jxcore-log: 
,09-29 05:57:33.701  5644  5690 I jxcore-log: 2016-09-29 09:57:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 05:57:33.701  5644  5690 I jxcore-log: 
,09-29 05:57:33.704  5644  5690 I jxcore-log: # setup
09-29 05:57:33.704  5644  5690 I jxcore-log: 
,09-29 05:57:34.105  5644  5690 I jxcore-log: # Call of onCheckpointReached handler on a single db change
09-29 05:57:34.105  5644  5690 I jxcore-log: 
,09-29 05:57:34.457  5644  5690 I jxcore-log: # teardown
09-29 05:57:34.457  5644  5690 I jxcore-log: 
,09-29 05:57:34.539  5644  5690 I jxcore-log: # setup
09-29 05:57:34.539  5644  5690 I jxcore-log: 
,09-29 05:57:34.581  5644  5690 I jxcore-log: # Call of multiple onCheckpointReached handlers on a single db change
09-29 05:57:34.581  5644  5690 I jxcore-log: 
,09-29 05:57:34.891  5644  5690 I jxcore-log: # teardown
09-29 05:57:34.891  5644  5690 I jxcore-log: 
,09-29 05:57:34.952  5644  5690 I jxcore-log: # setup
09-29 05:57:34.952  5644  5690 I jxcore-log: 
,09-29 05:57:35.038  5644  5690 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
09-29 05:57:35.038  5644  5690 I jxcore-log: 
,09-29 05:57:36.331  5644  5690 I jxcore-log: ok 86 the checkpointReached handler should be called once. Called 1 time(s)
09-29 05:57:36.331  5644  5690 I jxcore-log: 
,09-29 05:57:36.347  5644  5690 I jxcore-log: # teardown
09-29 05:57:36.347  5644  5690 I jxcore-log: 
,09-29 05:57:36.456  5644  5690 I jxcore-log: # setup
09-29 05:57:36.456  5644  5690 I jxcore-log: 
,09-29 05:57:36.502  5644  5690 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
09-29 05:57:36.502  5644  5690 I jxcore-log: 
,09-29 05:57:37.072  5644  5690 I jxcore-log: # teardown
09-29 05:57:37.072  5644  5690 I jxcore-log: 
,09-29 05:57:37.151  5644  5690 I jxcore-log: # setup
09-29 05:57:37.151  5644  5690 I jxcore-log: 
,09-29 05:57:37.187  5644  5690 I jxcore-log: # test defaultDirectory
09-29 05:57:37.187  5644  5690 I jxcore-log: 
,09-29 05:57:37.222  5644  5690 I jxcore-log: ok 87 should be equal
09-29 05:57:37.222  5644  5690 I jxcore-log: 
,09-29 05:57:37.228  5644  5690 I jxcore-log: ok 88 should be equal
09-29 05:57:37.228  5644  5690 I jxcore-log: 
,09-29 05:57:37.232  5644  5690 I jxcore-log: ok 89 should be equal
09-29 05:57:37.232  5644  5690 I jxcore-log: 
,09-29 05:57:37.243  5644  5690 I jxcore-log: # teardown
09-29 05:57:37.243  5644  5690 I jxcore-log: 
,09-29 05:57:37.281  5644  5690 I jxcore-log: # setup
09-29 05:57:37.281  5644  5690 I jxcore-log: 
,09-29 05:57:37.309  5644  5690 I jxcore-log: # test defaultAdapter
09-29 05:57:37.309  5644  5690 I jxcore-log: 
,09-29 05:57:37.330  5644  5690 I jxcore-log: ok 90 should be equal
09-29 05:57:37.330  5644  5690 I jxcore-log: 
,09-29 05:57:37.331  5644  5690 I jxcore-log: ok 91 should be equal
09-29 05:57:37.331  5644  5690 I jxcore-log: 
09-29 05:57:37.333  5644  5690 I jxcore-log: ok 92 should be equal
09-29 05:57:37.333  5644  5690 I jxcore-log: 
09-29 05:57:37.333  5644  5690 I jxcore-log: ok 93 should be equal
09-29 05:57:37.333  5644  5690 I jxcore-log: 
,09-29 05:57:37.335  5644  5690 I jxcore-log: ok 94 should be equal
09-29 05:57:37.335  5644  5690 I jxcore-log: 
,09-29 05:57:37.336  5644  5690 I jxcore-log: ok 95 should be equal
09-29 05:57:37.336  5644  5690 I jxcore-log: 
,09-29 05:57:37.465  5644  5690 I jxcore-log: ok 96 should be equal
09-29 05:57:37.465  5644  5690 I jxcore-log: 
,09-29 05:57:37.465  5644  5690 I jxcore-log: ok 97 should be equal
09-29 05:57:37.465  5644  5690 I jxcore-log: 
,09-29 05:57:37.472  5644  5690 I jxcore-log: # teardown
09-29 05:57:37.472  5644  5690 I jxcore-log: 
,09-29 05:57:37.598  5644  5690 I jxcore-log: # setup
09-29 05:57:37.598  5644  5690 I jxcore-log: 
,09-29 05:57:37.627  5644  5690 I jxcore-log: # enqueue and run in order
09-29 05:57:37.627  5644  5690 I jxcore-log: 
,09-29 05:57:37.772  5644  5690 I jxcore-log: ok 98 firstPromise setTimeout
09-29 05:57:37.772  5644  5690 I jxcore-log: 
,09-29 05:57:37.775  5644  5690 I jxcore-log: ok 99 firstPromise result
09-29 05:57:37.775  5644  5690 I jxcore-log: 
,09-29 05:57:37.778  5644  5690 I jxcore-log: ok 100 firstPromise testValue
09-29 05:57:37.778  5644  5690 I jxcore-log: 
,09-29 05:57:37.883  5644  5690 I jxcore-log: ok 101 secondPromise setTimeout
09-29 05:57:37.883  5644  5690 I jxcore-log: 
,09-29 05:57:37.888  5644  5690 I jxcore-log: ok 102 secondPromise result
09-29 05:57:37.888  5644  5690 I jxcore-log: 
,09-29 05:57:37.891  5644  5690 I jxcore-log: ok 103 secondPromise testValue
09-29 05:57:37.891  5644  5690 I jxcore-log: 
,09-29 05:57:37.893  5644  5690 I jxcore-log: ok 104 thirdPromise in promise
09-29 05:57:37.893  5644  5690 I jxcore-log: 
,09-29 05:57:37.896  5644  5690 I jxcore-log: ok 105 thirdPromise result
09-29 05:57:37.896  5644  5690 I jxcore-log: 
,09-29 05:57:37.898  5644  5690 I jxcore-log: ok 106 thirdPromise testValue
09-29 05:57:37.898  5644  5690 I jxcore-log: 
,09-29 05:57:37.908  5644  5690 I jxcore-log: # teardown
09-29 05:57:37.908  5644  5690 I jxcore-log: 
,09-29 05:57:37.956  5644  5690 I jxcore-log: # setup
09-29 05:57:37.956  5644  5690 I jxcore-log: 
,09-29 05:57:37.996  5644  5690 I jxcore-log: # enqueueAtTop and run backwards
09-29 05:57:37.996  5644  5690 I jxcore-log: 
,09-29 05:57:38.049  5644  5690 I jxcore-log: ok 107 thirdPromise - first to run
09-29 05:57:38.049  5644  5690 I jxcore-log: 
,09-29 05:57:38.051  5644  5690 I jxcore-log: ok 108 thirdPromise - in resolve
09-29 05:57:38.051  5644  5690 I jxcore-log: 
,09-29 05:57:38.053  5644  5690 I jxcore-log: ok 109 secondPromise - second to run
09-29 05:57:38.053  5644  5690 I jxcore-log: 
,09-29 05:57:38.055  5644  5690 I jxcore-log: ok 110 secondPromise - in catch
09-29 05:57:38.055  5644  5690 I jxcore-log: 
,09-29 05:57:38.056  5644  5690 I jxcore-log: ok 111 firstPromise - third to run
09-29 05:57:38.056  5644  5690 I jxcore-log: 
,09-29 05:57:38.058  5644  5690 I jxcore-log: ok 112 firstPromise - in then
09-29 05:57:38.058  5644  5690 I jxcore-log: 
,09-29 05:57:38.060  5644  5690 I jxcore-log: ok 113 testing promises
09-29 05:57:38.060  5644  5690 I jxcore-log: 
,09-29 05:57:38.069  5644  5690 I jxcore-log: # teardown
09-29 05:57:38.069  5644  5690 I jxcore-log: 
,09-29 05:57:38.093  5644  5690 I jxcore-log: # setup
09-29 05:57:38.093  5644  5690 I jxcore-log: 
,09-29 05:57:38.131  5644  5690 I jxcore-log: # mix enqueue and enqueueAtTop
09-29 05:57:38.131  5644  5690 I jxcore-log: 
,09-29 05:57:38.166  5644  5690 I jxcore-log: ok 114 fourth
09-29 05:57:38.166  5644  5690 I jxcore-log: 
,09-29 05:57:38.180  5644  5690 I jxcore-log: ok 115 fourth
09-29 05:57:38.180  5644  5690 I jxcore-log: 
,09-29 05:57:38.182  5644  5690 I jxcore-log: ok 116 second
09-29 05:57:38.182  5644  5690 I jxcore-log: 
,09-29 05:57:38.183  5644  5690 I jxcore-log: ok 117 secondPromise - in then
09-29 05:57:38.183  5644  5690 I jxcore-log: 
,09-29 05:57:38.287  5644  5690 I jxcore-log: ok 118 first
09-29 05:57:38.287  5644  5690 I jxcore-log: 
,09-29 05:57:38.289  5644  5690 I jxcore-log: ok 119 firstPromise - in catch
09-29 05:57:38.289  5644  5690 I jxcore-log: 
,09-29 05:57:38.291  5644  5690 I jxcore-log: ok 120 third
09-29 05:57:38.291  5644  5690 I jxcore-log: 
,09-29 05:57:38.294  5644  5690 I jxcore-log: ok 121 thirdPromise - in then
09-29 05:57:38.294  5644  5690 I jxcore-log: 
09-29 05:57:38.296  5644  5690 I jxcore-log: ok 122 testingPromises
09-29 05:57:38.296  5644  5690 I jxcore-log: 
,09-29 05:57:38.309  5644  5690 I jxcore-log: # teardown
09-29 05:57:38.309  5644  5690 I jxcore-log: 
,09-29 05:57:38.336  5644  5690 I jxcore-log: # setup
09-29 05:57:38.336  5644  5690 I jxcore-log: 
,09-29 05:57:38.480  5644  5690 I jxcore-log: # queues handled independently
09-29 05:57:38.480  5644  5690 I jxcore-log: 
,09-29 05:57:38.553  5644  5690 I jxcore-log: ok 123 all short operations completed before the long resolves
09-29 05:57:38.553  5644  5690 I jxcore-log: 
,09-29 05:57:38.562  5644  5690 I jxcore-log: # teardown
09-29 05:57:38.562  5644  5690 I jxcore-log: 
,09-29 05:57:38.613  5644  5690 I jxcore-log: # setup
09-29 05:57:38.613  5644  5690 I jxcore-log: 
,09-29 05:57:38.676  5644  5690 I jxcore-log: # basic
09-29 05:57:38.676  5644  5690 I jxcore-log: 
,09-29 05:57:38.711  5644  5690 I jxcore-log: ok 124 sane
09-29 05:57:38.711  5644  5690 I jxcore-log: 
,09-29 05:57:38.727  5644  5690 I jxcore-log: # teardown
09-29 05:57:38.727  5644  5690 I jxcore-log: 
,09-29 05:57:38.766  5644  5690 I jxcore-log: # setup
09-29 05:57:38.766  5644  5690 I jxcore-log: 
,09-29 05:57:38.815  5644  5690 I jxcore-log: # another
09-29 05:57:38.815  5644  5690 I jxcore-log: 
,09-29 05:57:38.849  5644  5690 I jxcore-log: ok 125 sane
09-29 05:57:38.849  5644  5690 I jxcore-log: 
,09-29 05:57:38.857  5644  5690 I jxcore-log: # teardown
09-29 05:57:38.857  5644  5690 I jxcore-log: 
,09-29 05:57:38.896  5644  5690 I jxcore-log: # setup
09-29 05:57:38.896  5644  5690 I jxcore-log: 
,09-29 05:57:38.927  5644  5690 I jxcore-log: # can pass data in setup
09-29 05:57:38.927  5644  5690 I jxcore-log: 
,09-29 05:57:38.975  5644  5690 I jxcore-log: ok 126 test participant has uuid
09-29 05:57:38.975  5644  5690 I jxcore-log: 
,09-29 05:57:38.975  5644  5690 I jxcore-log: ok 127 participant data matches
09-29 05:57:38.975  5644  5690 I jxcore-log: 
09-29 05:57:38.976  5644  5690 I jxcore-log: ok 128 test participant has uuid
09-29 05:57:38.976  5644  5690 I jxcore-log: 
09-29 05:57:38.976  5644  5690 I jxcore-log: ok 129 participant data matches
09-29 05:57:38.976  5644  5690 I jxcore-log: 
09-29 05:57:38.976  5644  5690 I jxcore-log: ok 130 test participant has uuid
09-29 05:57:38.976  5644  5690 I jxcore-log: 
09-29 05:57:38.977  5644  5690 I jxcore-log: ok 131 participant data matches
09-29 05:57:38.977  5644  5690 I jxcore-log: 
09-29 05:57:38.977  5644  5690 I jxcore-log: ok 132 own UUID is found from the participants list
09-29 05:57:38.977  5644  5690 I jxcore-log: 
,09-29 05:57:38.985  5644  5690 I jxcore-log: # teardown
09-29 05:57:38.985  5644  5690 I jxcore-log: 
,09-29 05:57:39.023  5644  5690 I jxcore-log: # setup
09-29 05:57:39.023  5644  5690 I jxcore-log: 
,09-29 05:57:39.061  5644  5690 I jxcore-log: # test thali manager spies
09-29 05:57:39.061  5644  5690 I jxcore-log: 
,09-29 05:57:39.240  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-29 05:57:39.240  5644  5690 I jxcore-log: 
,09-29 05:57:39.245  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-29 05:57:39.245  5644  5690 I jxcore-log: 
,09-29 05:57:39.247  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'creating express pouchdb instance'
09-29 05:57:39.247  5644  5690 I jxcore-log: 
,09-29 05:57:39.263  5644  5690 I jxcore-log: ok 133 expressPouchDB was called once
09-29 05:57:39.263  5644  5690 I jxcore-log: 
09-29 05:57:39.264  5644  5690 I jxcore-log: ok 134 expressPouchDB was called with 2 arguments
09-29 05:57:39.264  5644  5690 I jxcore-log: 
09-29 05:57:39.264  5644  5690 I jxcore-log: ok 135 expressPouchDB was called with 'PouchDB' as 1-st argument
09-29 05:57:39.264  5644  5690 I jxcore-log: 
,09-29 05:57:39.264  5644  5690 I jxcore-log: ok 136 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-29 05:57:39.264  5644  5690 I jxcore-log: 
09-29 05:57:39.264  5644  5690 I jxcore-log: ok 137 PouchDB was called once
09-29 05:57:39.264  5644  5690 I jxcore-log: 
09-29 05:57:39.265  5644  5690 I jxcore-log: ok 138 PouchDB was called with 1 arguments
09-29 05:57:39.265  5644  5690 I jxcore-log: 
09-29 05:57:39.265  5644  5690 I jxcore-log: ok 139 PouchDB was called with 'dbName' as 1-st argument
09-29 05:57:39.265  5644  5690 I jxcore-log: 
09-29 05:57:39.265  5644  5690 I jxcore-log: ok 140 ThaliSendNotificationBasedOnReplication was called once
09-29 05:57:39.265  5644  5690 I jxcore-log: 
09-29 05:57:39.265  5644  5690 I jxcore-log: ok 141 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-29 05:57:39.265  5644  5690 I jxcore-log: 
09-29 05:57:39.266  5644  5690 I jxcore-log: ok 142 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-29 05:57:39.266  5644  5690 I jxcore-log: 
09-29 05:57:39.266  5644  5690 I jxcore-log: ok 143 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-29 05:57:39.266  5644  5690 I jxcore-log: 
09-29 05:57:39.266  5644  5690 I jxcore-log: ok 144 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-29 05:57:39.266  5644  5690 I jxcore-log: 
09-29 05:57:39.266  5644  5690 I jxcore-log: ok 145 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-29 05:57:39.266  5644  5690 I jxcore-log: 
09-29 05:57:39.267  5644  5690 I jxcore-log: ok 146 ThaliPullReplicationFromNotification was called once
09-29 05:57:39.267  5644  5690 I jxcore-log: 
09-29 05:57:39.267  5644  5690 I jxcore-log: ok 147 ThaliPullReplicationFromNotification was called with 4 arguments
09-29 05:57:39.267  5644  5690 I jxcore-log: 
09-29 05:57:39.268  5644  5690 I jxcore-log: ok 148 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-29 05:57:39.268  5644  5690 I jxcore-log: 
09-29 05:57:39.268  5644  5690 I jxcore-log: ok 149 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-29 05:57:39.268  5644  5690 I jxcore-log: 
09-29 05:57:39.268  5644  5690 I jxcore-log: ok 150 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-29 05:57:39.268  5644  5690 I jxcore-log: 
09-29 05:57:39.268  5644  5690 I jxcore-log: ok 151 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-29 05:57:39.268  5644  5690 I jxcore-log: 
,09-29 05:57:39.268  5644  5690 I jxcore-log: ok 152 Salti was called once
09-29 05:57:39.268  5644  5690 I jxcore-log: 
09-29 05:57:39.269  5644  5690 I jxcore-log: ok 153 Salti was called with 4 arguments
09-29 05:57:39.269  5644  5690 I jxcore-log: 
09-29 05:57:39.269  5644  5690 I jxcore-log: ok 154 Salti was called with 'dbName' as 1-st argument
09-29 05:57:39.269  5644  5690 I jxcore-log: 
09-29 05:57:39.269  5644  5690 I jxcore-log: ok 155 Salti was called with 'acl' as 2-st argument
09-29 05:57:39.269  5644  5690 I jxcore-log: 
09-29 05:57:39.270  5644  5690 I jxcore-log: ok 156 Salti was called with 'thaliIdCallback' as 3-st argument
09-29 05:57:39.270  5644  5690 I jxcore-log: 
09-29 05:57:39.270  5644  5690 I jxcore-log: ok 157 Salti was called with 'options' as 4-st argument
09-29 05:57:39.270  5644  5690 I jxcore-log: 
09-29 05:57:39.270  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 05:57:39.270  5644  5690 I jxcore-log: 
09-29 05:57:39.272  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 05:57:39.272  5644  5690 I jxcore-log: 
,09-29 05:57:39.273  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 05:57:39.273  5644  5690 I jxcore-log: 
,09-29 05:57:39.275  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'start listening for advertisements'
09-29 05:57:39.275  5644  5690 I jxcore-log: 
,09-29 05:57:39.279  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'start update advertising and listening'
09-29 05:57:39.279  5644  5690 I jxcore-log: 
,09-29 05:57:39.306  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliWifiInfrastructure: 'listening 44687'
09-29 05:57:39.306  5644  5690 I jxcore-log: 
,09-29 05:57:39.308  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 05:57:39.308  5644  5690 I jxcore-log: 
,09-29 05:57:39.328  5644  5690 I jxcore-log: ok 158 ThaliMobile.start was called once
09-29 05:57:39.328  5644  5690 I jxcore-log: 
,09-29 05:57:39.329  5644  5690 I jxcore-log: ok 159 ThaliMobile.start was called with 2 arguments
09-29 05:57:39.329  5644  5690 I jxcore-log: 
09-29 05:57:39.329  5644  5690 I jxcore-log: ok 160 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-29 05:57:39.329  5644  5690 I jxcore-log: 
09-29 05:57:39.329  5644  5690 I jxcore-log: ok 161 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-29 05:57:39.329  5644  5690 I jxcore-log: 
09-29 05:57:39.329  5644  5690 I jxcore-log: ok 162 ThaliMobile.startListeningForAdvertisements was called once
09-29 05:57:39.329  5644  5690 I jxcore-log: 
,09-29 05:57:39.330  5644  5690 I jxcore-log: ok 163 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-29 05:57:39.330  5644  5690 I jxcore-log: 
09-29 05:57:39.330  5644  5690 I jxcore-log: ok 164 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-29 05:57:39.330  5644  5690 I jxcore-log: 
09-29 05:57:39.330  5644  5690 I jxcore-log: ok 165 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-29 05:57:39.330  5644  5690 I jxcore-log: 
,09-29 05:57:39.330  5644  5690 I jxcore-log: ok 166 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-29 05:57:39.330  5644  5690 I jxcore-log: 
09-29 05:57:39.331  5644  5690 I jxcore-log: ok 167 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-29 05:57:39.331  5644  5690 I jxcore-log: 
09-29 05:57:39.331  5644  5690 I jxcore-log: ok 168 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 05:57:39.331  5644  5690 I jxcore-log: 
,09-29 05:57:39.331  5644  5690 I jxcore-log: ok 169 ThaliPullReplicationFromNotification.prototype.start was called once
09-29 05:57:39.331  5644  5690 I jxcore-log: 
09-29 05:57:39.331  5644  5690 I jxcore-log: ok 170 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-29 05:57:39.331  5644  5690 I jxcore-log: 
09-29 05:57:39.331  5644  5690 I jxcore-log: ok 171 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 05:57:39.331  5644  5690 I jxcore-log: 
09-29 05:57:39.332  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 05:57:39.332  5644  5690 I jxcore-log: 
,09-29 05:57:39.333  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 05:57:39.333  5644  5690 I jxcore-log: 
,09-29 05:57:39.335  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 05:57:39.335  5644  5690 I jxcore-log: 
,09-29 05:57:39.336  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 05:57:39.336  5644  5690 I jxcore-log: 
,09-29 05:57:39.341  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 05:57:39.341  5644  5690 I jxcore-log: 
,09-29 05:57:39.343  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 05:57:39.343  5644  5690 I jxcore-log: 
,09-29 05:57:39.345  5644  5690 I jxcore-log: ok 172 ThaliMobile.stop was called once
09-29 05:57:39.345  5644  5690 I jxcore-log: 
,09-29 05:57:39.346  5644  5690 I jxcore-log: ok 173 ThaliMobile.stop was called with 0 arguments
09-29 05:57:39.346  5644  5690 I jxcore-log: 
09-29 05:57:39.346  5644  5690 I jxcore-log: ok 174 ThaliMobile.stopListeningForAdvertisements was called once
09-29 05:57:39.346  5644  5690 I jxcore-log: 
09-29 05:57:39.346  5644  5690 I jxcore-log: ok 175 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-29 05:57:39.346  5644  5690 I jxcore-log: 
09-29 05:57:39.346  5644  5690 I jxcore-log: ok 176 ThaliMobile.stopAdvertisingAndListening was called once
09-29 05:57:39.346  5644  5690 I jxcore-log: 
,09-29 05:57:39.347  5644  5690 I jxcore-log: ok 177 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-29 05:57:39.347  5644  5690 I jxcore-log: 
09-29 05:57:39.347  5644  5690 I jxcore-log: ok 178 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-29 05:57:39.347  5644  5690 I jxcore-log: 
09-29 05:57:39.347  5644  5690 I jxcore-log: ok 179 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-29 05:57:39.347  5644  5690 I jxcore-log: 
09-29 05:57:39.347  5644  5690 I jxcore-log: ok 180 ThaliPullReplicationFromNotification.prototype.stop was called once
09-29 05:57:39.347  5644  5690 I jxcore-log: 
09-29 05:57:39.347  5644  5690 I jxcore-log: ok 181 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-29 05:57:39.347  5644  5690 I jxcore-log: 
,09-29 05:57:39.356  5644  5690 I jxcore-log: # teardown
09-29 05:57:39.356  5644  5690 I jxcore-log: 
,09-29 05:57:39.426  5644  5690 I jxcore-log: # setup
09-29 05:57:39.426  5644  5690 I jxcore-log: 
,09-29 05:57:39.466  5644  5690 I jxcore-log: # test thali manager multiple starts and stops
09-29 05:57:39.466  5644  5690 I jxcore-log: 
,09-29 05:57:39.652  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-29 05:57:39.652  5644  5690 I jxcore-log: 
,09-29 05:57:39.658  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-29 05:57:39.658  5644  5690 I jxcore-log: 
,09-29 05:57:39.660  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'creating express pouchdb instance'
09-29 05:57:39.660  5644  5690 I jxcore-log: 
,09-29 05:57:39.680  5644  5690 I jxcore-log: ok 182 expressPouchDB was called once
09-29 05:57:39.680  5644  5690 I jxcore-log: 
,09-29 05:57:39.680  5644  5690 I jxcore-log: ok 183 expressPouchDB was called with 2 arguments
09-29 05:57:39.680  5644  5690 I jxcore-log: 
09-29 05:57:39.680  5644  5690 I jxcore-log: ok 184 expressPouchDB was called with 'PouchDB' as 1-st argument
09-29 05:57:39.680  5644  5690 I jxcore-log: 
09-29 05:57:39.681  5644  5690 I jxcore-log: ok 185 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-29 05:57:39.681  5644  5690 I jxcore-log: 
09-29 05:57:39.681  5644  5690 I jxcore-log: ok 186 PouchDB was called once
09-29 05:57:39.681  5644  5690 I jxcore-log: 
,09-29 05:57:39.681  5644  5690 I jxcore-log: ok 187 PouchDB was called with 1 arguments
09-29 05:57:39.681  5644  5690 I jxcore-log: 
09-29 05:57:39.681  5644  5690 I jxcore-log: ok 188 PouchDB was called with 'dbName' as 1-st argument
09-29 05:57:39.681  5644  5690 I jxcore-log: 
09-29 05:57:39.681  5644  5690 I jxcore-log: ok 189 ThaliSendNotificationBasedOnReplication was called once
09-29 05:57:39.681  5644  5690 I jxcore-log: 
,09-29 05:57:39.682  5644  5690 I jxcore-log: ok 190 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-29 05:57:39.682  5644  5690 I jxcore-log: 
09-29 05:57:39.682  5644  5690 I jxcore-log: ok 191 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-29 05:57:39.682  5644  5690 I jxcore-log: 
09-29 05:57:39.682  5644  5690 I jxcore-log: ok 192 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-29 05:57:39.682  5644  5690 I jxcore-log: 
,09-29 05:57:39.683  5644  5690 I jxcore-log: ok 193 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-29 05:57:39.683  5644  5690 I jxcore-log: 
09-29 05:57:39.683  5644  5690 I jxcore-log: ok 194 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-29 05:57:39.683  5644  5690 I jxcore-log: 
09-29 05:57:39.683  5644  5690 I jxcore-log: ok 195 ThaliPullReplicationFromNotification was called once
09-29 05:57:39.683  5644  5690 I jxcore-log: 
09-29 05:57:39.683  5644  5690 I jxcore-log: ok 196 ThaliPullReplicationFromNotification was called with 4 arguments
09-29 05:57:39.683  5644  5690 I jxcore-log: 
09-29 05:57:39.683  5644  5690 I jxcore-log: ok 197 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-29 05:57:39.683  5644  5690 I jxcore-log: 
,09-29 05:57:39.684  5644  5690 I jxcore-log: ok 198 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-29 05:57:39.684  5644  5690 I jxcore-log: 
09-29 05:57:39.684  5644  5690 I jxcore-log: ok 199 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-29 05:57:39.684  5644  5690 I jxcore-log: 
09-29 05:57:39.684  5644  5690 I jxcore-log: ok 200 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-29 05:57:39.684  5644  5690 I jxcore-log: 
09-29 05:57:39.684  5644  5690 I jxcore-log: ok 201 Salti was called once
09-29 05:57:39.684  5644  5690 I jxcore-log: 
09-29 05:57:39.684  5644  5690 I jxcore-log: ok 202 Salti was called with 4 arguments
09-29 05:57:39.684  5644  5690 I jxcore-log: 
09-29 05:57:39.685  5644  5690 I jxcore-log: ok 203 Salti was called with 'dbName' as 1-st argument
09-29 05:57:39.685  5644  5690 I jxcore-log: 
,09-29 05:57:39.685  5644  5690 I jxcore-log: ok 204 Salti was called with 'acl' as 2-st argument
09-29 05:57:39.685  5644  5690 I jxcore-log: 
09-29 05:57:39.685  5644  5690 I jxcore-log: ok 205 Salti was called with 'thaliIdCallback' as 3-st argument
09-29 05:57:39.685  5644  5690 I jxcore-log: 
09-29 05:57:39.685  5644  5690 I jxcore-log: ok 206 Salti was called with 'options' as 4-st argument
09-29 05:57:39.685  5644  5690 I jxcore-log: 
09-29 05:57:39.686  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 05:57:39.686  5644  5690 I jxcore-log: 
,09-29 05:57:39.687  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 05:57:39.687  5644  5690 I jxcore-log: 
,09-29 05:57:39.688  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 05:57:39.688  5644  5690 I jxcore-log: 
,09-29 05:57:39.691  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'start listening for advertisements'
09-29 05:57:39.691  5644  5690 I jxcore-log: 
,09-29 05:57:39.695  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'start update advertising and listening'
09-29 05:57:39.695  5644  5690 I jxcore-log: 
,09-29 05:57:39.701  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliWifiInfrastructure: 'listening 43898'
09-29 05:57:39.701  5644  5690 I jxcore-log: 
,09-29 05:57:39.703  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 05:57:39.703  5644  5690 I jxcore-log: 
,09-29 05:57:39.753  5644  5690 I jxcore-log: ok 207 ThaliMobile.start was called once
09-29 05:57:39.753  5644  5690 I jxcore-log: 
,09-29 05:57:39.753  5644  5690 I jxcore-log: ok 208 ThaliMobile.start was called with 2 arguments
09-29 05:57:39.753  5644  5690 I jxcore-log: 
09-29 05:57:39.753  5644  5690 I jxcore-log: ok 209 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-29 05:57:39.753  5644  5690 I jxcore-log: 
09-29 05:57:39.754  5644  5690 I jxcore-log: ok 210 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-29 05:57:39.754  5644  5690 I jxcore-log: 
09-29 05:57:39.754  5644  5690 I jxcore-log: ok 211 ThaliMobile.startListeningForAdvertisements was called once
09-29 05:57:39.754  5644  5690 I jxcore-log: 
,09-29 05:57:39.754  5644  5690 I jxcore-log: ok 212 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-29 05:57:39.754  5644  5690 I jxcore-log: 
09-29 05:57:39.754  5644  5690 I jxcore-log: ok 213 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-29 05:57:39.754  5644  5690 I jxcore-log: 
09-29 05:57:39.754  5644  5690 I jxcore-log: ok 214 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-29 05:57:39.754  5644  5690 I jxcore-log: 
09-29 05:57:39.755  5644  5690 I jxcore-log: ok 215 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-29 05:57:39.755  5644  5690 I jxcore-log: 
09-29 05:57:39.755  5644  5690 I jxcore-log: ok 216 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-29 05:57:39.755  5644  5690 I jxcore-log: 
,09-29 05:57:39.755  5644  5690 I jxcore-log: ok 217 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 05:57:39.755  5644  5690 I jxcore-log: 
09-29 05:57:39.755  5644  5690 I jxcore-log: ok 218 ThaliPullReplicationFromNotification.prototype.start was called once
09-29 05:57:39.755  5644  5690 I jxcore-log: 
09-29 05:57:39.755  5644  5690 I jxcore-log: ok 219 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-29 05:57:39.755  5644  5690 I jxcore-log: 
09-29 05:57:39.755  5644  5690 I jxcore-log: ok 220 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 05:57:39.755  5644  5690 I jxcore-log: 
,09-29 05:57:39.756  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 05:57:39.756  5644  5690 I jxcore-log: 
,09-29 05:57:39.758  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 05:57:39.758  5644  5690 I jxcore-log: 
,09-29 05:57:39.761  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 05:57:39.761  5644  5690 I jxcore-log: 
,09-29 05:57:39.762  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 05:57:39.762  5644  5690 I jxcore-log: 
,09-29 05:57:39.768  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 05:57:39.768  5644  5690 I jxcore-log: 
,09-29 05:57:39.770  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 05:57:39.770  5644  5690 I jxcore-log: 
,09-29 05:57:39.776  5644  5690 I jxcore-log: ok 221 ThaliMobile.stop was called once
09-29 05:57:39.776  5644  5690 I jxcore-log: 
,09-29 05:57:39.776  5644  5690 I jxcore-log: ok 222 ThaliMobile.stop was called with 0 arguments
09-29 05:57:39.776  5644  5690 I jxcore-log: 
09-29 05:57:39.776  5644  5690 I jxcore-log: ok 223 ThaliMobile.stopListeningForAdvertisements was called once
09-29 05:57:39.776  5644  5690 I jxcore-log: 
09-29 05:57:39.777  5644  5690 I jxcore-log: ok 224 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-29 05:57:39.777  5644  5690 I jxcore-log: 
,09-29 05:57:39.777  5644  5690 I jxcore-log: ok 225 ThaliMobile.stopAdvertisingAndListening was called once
09-29 05:57:39.777  5644  5690 I jxcore-log: 
09-29 05:57:39.777  5644  5690 I jxcore-log: ok 226 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-29 05:57:39.777  5644  5690 I jxcore-log: 
,09-29 05:57:39.777  5644  5690 I jxcore-log: ok 227 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-29 05:57:39.777  5644  5690 I jxcore-log: 
09-29 05:57:39.777  5644  5690 I jxcore-log: ok 228 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-29 05:57:39.777  5644  5690 I jxcore-log: 
09-29 05:57:39.777  5644  5690 I jxcore-log: ok 229 ThaliPullReplicationFromNotification.prototype.stop was called once
09-29 05:57:39.777  5644  5690 I jxcore-log: 
09-29 05:57:39.778  5644  5690 I jxcore-log: ok 230 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-29 05:57:39.778  5644  5690 I jxcore-log: 
,09-29 05:57:39.778  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 05:57:39.778  5644  5690 I jxcore-log: 
09-29 05:57:39.779  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 05:57:39.779  5644  5690 I jxcore-log: 
09-29 05:57:39.779  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 05:57:39.779  5644  5690 I jxcore-log: 
,09-29 05:57:39.782  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'start listening for advertisements'
09-29 05:57:39.782  5644  5690 I jxcore-log: 
,09-29 05:57:39.784  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'start update advertising and listening'
09-29 05:57:39.784  5644  5690 I jxcore-log: 
,09-29 05:57:39.788  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliWifiInfrastructure: 'listening 39676'
09-29 05:57:39.788  5644  5690 I jxcore-log: 
,09-29 05:57:39.790  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 05:57:39.790  5644  5690 I jxcore-log: 
,09-29 05:57:39.792  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 05:57:39.792  5644  5690 I jxcore-log: 
,09-29 05:57:39.793  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 05:57:39.793  5644  5690 I jxcore-log: 
,09-29 05:57:39.795  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 05:57:39.795  5644  5690 I jxcore-log: 
,09-29 05:57:39.796  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 05:57:39.796  5644  5690 I jxcore-log: 
,09-29 05:57:39.801  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 05:57:39.801  5644  5690 I jxcore-log: 
,09-29 05:57:39.804  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 05:57:39.804  5644  5690 I jxcore-log: 
,09-29 05:57:39.806  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 05:57:39.806  5644  5690 I jxcore-log: 
,09-29 05:57:39.807  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 05:57:39.807  5644  5690 I jxcore-log: 
,09-29 05:57:39.808  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 05:57:39.808  5644  5690 I jxcore-log: 
,09-29 05:57:39.810  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'start listening for advertisements'
09-29 05:57:39.810  5644  5690 I jxcore-log: 
,09-29 05:57:39.813  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'start update advertising and listening'
09-29 05:57:39.813  5644  5690 I jxcore-log: 
,09-29 05:57:39.817  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliWifiInfrastructure: 'listening 38384'
09-29 05:57:39.817  5644  5690 I jxcore-log: 
,09-29 05:57:39.819  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 05:57:39.819  5644  5690 I jxcore-log: 
,09-29 05:57:39.821  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 05:57:39.821  5644  5690 I jxcore-log: 
,09-29 05:57:39.823  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 05:57:39.823  5644  5690 I jxcore-log: 
,09-29 05:57:39.825  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 05:57:39.825  5644  5690 I jxcore-log: 
,09-29 05:57:39.826  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 05:57:39.826  5644  5690 I jxcore-log: 
,09-29 05:57:39.833  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 05:57:39.833  5644  5690 I jxcore-log: 
,09-29 05:57:39.835  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 05:57:39.835  5644  5690 I jxcore-log: 
,09-29 05:57:39.837  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 05:57:39.837  5644  5690 I jxcore-log: 
,09-29 05:57:39.838  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 05:57:39.838  5644  5690 I jxcore-log: 
09-29 05:57:39.838  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 05:57:39.838  5644  5690 I jxcore-log: 
,09-29 05:57:39.840  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'start listening for advertisements'
09-29 05:57:39.840  5644  5690 I jxcore-log: 
,09-29 05:57:39.842  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'start update advertising and listening'
09-29 05:57:39.842  5644  5690 I jxcore-log: 
,09-29 05:57:39.846  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliWifiInfrastructure: 'listening 45453'
09-29 05:57:39.846  5644  5690 I jxcore-log: 
,09-29 05:57:39.848  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 05:57:39.848  5644  5690 I jxcore-log: 
,09-29 05:57:39.852  5644  5690 I jxcore-log: ok 231 ThaliMobile.start was called once
09-29 05:57:39.852  5644  5690 I jxcore-log: 
,09-29 05:57:39.852  5644  5690 I jxcore-log: ok 232 ThaliMobile.start was called with 2 arguments
09-29 05:57:39.852  5644  5690 I jxcore-log: 
09-29 05:57:39.852  5644  5690 I jxcore-log: ok 233 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-29 05:57:39.852  5644  5690 I jxcore-log: 
,09-29 05:57:39.852  5644  5690 I jxcore-log: ok 234 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-29 05:57:39.852  5644  5690 I jxcore-log: 
09-29 05:57:39.852  5644  5690 I jxcore-log: ok 235 ThaliMobile.startListeningForAdvertisements was called once
09-29 05:57:39.852  5644  5690 I jxcore-log: 
09-29 05:57:39.853  5644  5690 I jxcore-log: ok 236 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-29 05:57:39.853  5644  5690 I jxcore-log: 
,09-29 05:57:39.853  5644  5690 I jxcore-log: ok 237 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-29 05:57:39.853  5644  5690 I jxcore-log: 
09-29 05:57:39.853  5644  5690 I jxcore-log: ok 238 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-29 05:57:39.853  5644  5690 I jxcore-log: 
09-29 05:57:39.853  5644  5690 I jxcore-log: ok 239 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-29 05:57:39.853  5644  5690 I jxcore-log: 
09-29 05:57:39.854  5644  5690 I jxcore-log: ok 240 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-29 05:57:39.854  5644  5690 I jxcore-log: 
09-29 05:57:39.854  5644  5690 I jxcore-log: ok 241 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 05:57:39.854  5644  5690 I jxcore-log: 
,09-29 05:57:39.854  5644  5690 I jxcore-log: ok 242 ThaliPullReplicationFromNotification.prototype.start was called once
09-29 05:57:39.854  5644  5690 I jxcore-log: 
09-29 05:57:39.854  5644  5690 I jxcore-log: ok 243 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-29 05:57:39.854  5644  5690 I jxcore-log: 
09-29 05:57:39.854  5644  5690 I jxcore-log: ok 244 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 05:57:39.854  5644  5690 I jxcore-log: 
09-29 05:57:39.855  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 05:57:39.855  5644  5690 I jxcore-log: 
09-29 05:57:39.856  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 05:57:39.856  5644  5690 I jxcore-log: 
09-29 05:57:39.857  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 05:57:39.857  5644  5690 I jxcore-log: 
,09-29 05:57:39.858  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 05:57:39.858  5644  5690 I jxcore-log: 
,09-29 05:57:39.862  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 05:57:39.862  5644  5690 I jxcore-log: 
,09-29 05:57:39.864  5644  5690 I jxcore-log: 2016-09-29 09:57:39 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 05:57:39.864  5644  5690 I jxcore-log: 
,09-29 05:57:39.869  5644  5690 I jxcore-log: # teardown
09-29 05:57:39.869  5644  5690 I jxcore-log: 
,09-29 05:57:39.975  5644  5690 I jxcore-log: # setup
09-29 05:57:39.975  5644  5690 I jxcore-log: 
,09-29 05:57:40.075  5644  5690 I jxcore-log: # test write
09-29 05:57:40.075  5644  5690 I jxcore-log: 
,09-29 05:57:40.260  5644  5690 I jxcore-log: 2016-09-29 09:57:40 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-29 05:57:40.260  5644  5690 I jxcore-log: 
,09-29 05:57:40.263  5644  5690 I jxcore-log: 2016-09-29 09:57:40 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-29 05:57:40.263  5644  5690 I jxcore-log: 
,09-29 05:57:40.264  5644  5690 I jxcore-log: 2016-09-29 09:57:40 - DEBUG thaliManager: 'creating express pouchdb instance'
09-29 05:57:40.264  5644  5690 I jxcore-log: 
,09-29 05:57:40.288  5644  5690 I jxcore-log: 2016-09-29 09:57:40 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 05:57:40.288  5644  5690 I jxcore-log: 
,09-29 05:57:40.289  5644  5690 I jxcore-log: 2016-09-29 09:57:40 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 05:57:40.289  5644  5690 I jxcore-log: 
,09-29 05:57:40.289  5644  5690 I jxcore-log: 2016-09-29 09:57:40 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 05:57:40.289  5644  5690 I jxcore-log: 
,09-29 05:57:40.291  5644  5690 I jxcore-log: 2016-09-29 09:57:40 - DEBUG thaliManager: 'start listening for advertisements'
09-29 05:57:40.291  5644  5690 I jxcore-log: 
,09-29 05:57:40.295  5644  5690 I jxcore-log: 2016-09-29 09:57:40 - DEBUG thaliManager: 'start update advertising and listening'
09-29 05:57:40.295  5644  5690 I jxcore-log: 
,09-29 05:57:40.301  5644  5690 I jxcore-log: 2016-09-29 09:57:40 - DEBUG thaliWifiInfrastructure: 'listening 45965'
09-29 05:57:40.301  5644  5690 I jxcore-log: 
,09-29 05:57:40.305  5644  5690 I jxcore-log: 2016-09-29 09:57:40 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 05:57:40.305  5644  5690 I jxcore-log: 
,09-29 05:57:40.320   928  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 05:57:41.096  5644  5690 I jxcore-log: 2016-09-29 09:57:41 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-29 05:57:41.096  5644  5690 I jxcore-log: 
,09-29 05:57:41.119  5644  5690 I jxcore-log: 2016-09-29 09:57:41 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-29 05:57:41.119  5644  5690 I jxcore-log: 
,09-29 05:57:41.690  5644  5690 E jxcore-log: Error in .on("change", function): { [AssertionError: If beacons werepreviously updated then there has to be a refresh timer for them.]
09-29 05:57:41.690  5644  5690 E jxcore-log:   name: 'AssertionError',
09-29 05:57:41.690  5644  5690 E jxcore-log:   actual: null,
09-29 05:57:41.690  5644  5690 E jxcore-log:   expected: true,
09-29 05:57:41.690  5644  5690 E jxcore-log:   operator: '==',
09-29 05:57:41.690  5644  5690 E jxcore-log:   message: 'If beacons werepreviously updated then there has to be a refresh timer for them.',
09-29 05:57:41.690  5644  5690 E jxcore-log:   stack: 'ok@assert.js:126:1\nThaliSendNotificationBasedOnReplication.prototype._setUpChangeListener/this._replicationPromise</self._transientState.pouchDBChangesCancelObject<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/replication/thaliSendNotificationBasedOnReplication.js:358:9\nemit@events.js:82:1' }
09-29 05:57:41.690  5644  5690 E jxcore-log: 
,09-29 05:57:41.758  5644  5690 I jxcore-log: # teardown
09-29 05:57:41.758  5644  5690 I jxcore-log: 
,09-29 05:57:42.031  5644  5690 I jxcore-log: 2016-09-29 09:57:42 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
09-29 05:57:42.031  5644  5690 I jxcore-log: 
,09-29 05:57:42.085  5644  5690 I jxcore-log: 2016-09-29 09:57:42 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
09-29 05:57:42.085  5644  5690 I jxcore-log: 
,09-29 05:57:42.210   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:43.211   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:44.212   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:45.213   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:46.215   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:57:47.216   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-29 05:58:00.322   928  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 05:58:01.668   928  5905 D NetlinkSocketObserver: NeighborEvent{elapsedMs=408530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-29 05:58:07.218   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:58:08.219   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:58:09.221   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:58:10.222   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:58:11.223   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:58:11.616  5644  5690 I jxcore-log: 2016-09-29 09:58:11 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
09-29 05:58:11.616  5644  5690 I jxcore-log: 
,09-29 05:58:11.655  5644  5690 I jxcore-log: 2016-09-29 09:58:11 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
09-29 05:58:11.655  5644  5690 I jxcore-log: 
,09-29 05:58:12.224   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-29 05:58:13.375   928  5905 D NetlinkSocketObserver: NeighborEvent{elapsedMs=420237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-29 05:58:20.325   928  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 05:58:31.695   928  5905 D NetlinkSocketObserver: NeighborEvent{elapsedMs=438557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-29 05:58:37.224   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-29 05:58:37.225   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-29 05:58:38.388   928  5905 D NetlinkSocketObserver: NeighborEvent{elapsedMs=445250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-29 05:58:41.776  5644  5690 I jxcore-log: 2016-09-29 09:58:41 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
09-29 05:58:41.776  5644  5690 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-29 05:58:41.776  5644  5690 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-29 05:58:41.776  5644  5690 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-29 05:58:41.776  5644  5690 I jxcore-log:     at $9@timers.js:120:1
09-29 05:58:41.776  5644  5690 I jxcore-log: ''
09-29 05:58:41.776  5644  5690 I jxcore-log: 
,09-29 05:58:41.779  5644  5690 I jxcore-log: 2016-09-29 09:58:41 - DEBUG CoordinatedClient: 'test client failed'
09-29 05:58:41.779  5644  5690 I jxcore-log: 
,09-29 05:58:41.788  5644  5690 I jxcore-log: 2016-09-29 09:58:41 - DEBUG CoordinatedClient: 'device disconnected from the test server'
09-29 05:58:41.788  5644  5690 I jxcore-log: 
,09-29 05:58:41.791  5644  5690 I jxcore-log: 2016-09-29 09:58:41 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
09-29 05:58:41.791  5644  5690 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-29 05:58:41.791  5644  5690 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-29 05:58:41.791  5644  5690 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-29 05:58:41.791  5644  5690 I jxcore-log:     at $9@timers.js:120:1
09-29 05:58:41.791  5644  5690 I jxcore-log: ''
09-29 05:58:41.791  5644  5690 I jxcore-log: 
09-29 05:58:41.792  5644  5690 I jxcore-log: 2016-09-29 09:58:41 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
09-29 05:58:41.792  5644  5690 I jxcore-log: 
,09-29 05:58:42.388  5959  5959 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-29 05:58:42.394  5959  5959 D AndroidRuntime: CheckJNI is OFF
,09-29 05:58:42.419  5959  5959 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-29 05:58:42.448  5959  5959 I Radio-JNI: register_android_hardware_Radio DONE
,09-29 05:58:42.463  5959  5959 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-29 05:58:42.470   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-29 05:58:42.470   928   941 I ActivityManager: Killing 5644:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-29 05:58:42.547   928  3147 D GraphicsStats: Buffer count: 2
,09-29 05:58:42.547   928  3800 I WindowState: WIN DEATH: Window{61fec68 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-29 05:58:42.547   928  2944 D WifiService: Client connection lost with reason: 4
,09-29 05:58:42.601   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-29 05:58:42.603   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-29 05:58:42.604   928   941 E ActivityManager: Failure starting process com.test.thalitest
09-29 05:58:42.604   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-29 05:58:42.604   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:58:42.604   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:58:42.604   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-29 05:58:42.604   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-29 05:58:42.604   928   941 I ActivityManager:   Force finishing activity ActivityRecord{2a26c25 u0 com.test.thalitest/.MainActivity t2}
09-29 05:58:42.605   928   951 I art     : Starting a blocking GC Explicit
,09-29 05:58:42.613   928   939 W ActivityManager: Spurious death for ProcessRecord{c31955 0:com.test.thalitest/u0a77}, curProc for 5644: null
,09-29 05:58:42.617   928   946 W WindowManager: Attempted to add application window with unknown token Token{5b981fa ActivityRecord{2a26c25 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-29 05:58:42.617   928   946 W WindowManager: Token{5b981fa ActivityRecord{2a26c25 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{5b981fa ActivityRecord{2a26c25 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-29 05:58:42.618   928   946 W WindowManager: view not successfully added to wm, removing view
,09-29 05:58:42.618   928   946 W WindowManager: Exception when adding starting window
09-29 05:58:42.618   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{94c70a4 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-29 05:58:42.618   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-29 05:58:42.618   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-29 05:58:42.618   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-29 05:58:42.618   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-29 05:58:42.618   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-29 05:58:42.618   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:58:42.618   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:58:42.618   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-29 05:58:42.618   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-29 05:58:42.700   928   951 I art     : Explicit concurrent mark sweep GC freed 91075(6MB) AllocSpace objects, 52(2MB) LOS objects, 33% free, 29MB/43MB, paused 1.648ms total 95.128ms
,09-29 05:58:42.723   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-29 05:58:42.727  5959  5959 I art     : System.exit called, status: 0
,09-29 05:58:42.728  5959  5959 I AndroidRuntime: VM exiting with result code 0.
,09-29 05:58:42.732   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-29 05:58:42.736   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-29 05:58:42.740  5846  5846 D BluetoothMapAppObserver: onReceive
,09-29 05:58:42.740  5846  5846 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-29 05:58:42.752  3647  3647 I Keyboard.Facilitator: resetDictionaries() : en_US
09-29 05:58:42.754   928  2927 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-29 05:58:42.754  4102  4185 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-29 05:58:42.781  3647  5971 I Keyboard.Facilitator.DecoderInitializer: run()
,09-29 05:58:42.788  3391  5972 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-29 05:58:42.805  3759  3759 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-29 05:58:42.814  3575  3575 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-29 05:58:42.815  3575  3575 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-29 05:58:42.820  3647  5971 I Decoder : createOrResetDecoder,
,09-29 05:58:42.822   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-29 05:58:42.831  3901  5977 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-29 05:58:42.832  3901  5977 D AccountUtils: Clearing selected account for com.test.thalitest
,09-29 05:58:42.851    13    13 W kworker/1:0: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 05:58:42.857    13    13 W kworker/1:0: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 05:58:42.875  3575  3575 I ConfigService: onCreate
,09-29 05:58:42.877    13    13 W kworker/1:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 05:58:42.892  3901  5977 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-29 05:58:42.908  3647  5971 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-29 05:58:42.912  3391  3417 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj80E47D9D8) - 
,09-29 05:58:42.919  3901  5977 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:58:42.919  3901  5977 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-29 05:58:42.919  3901  5977 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:58:42.919  3901  5977 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-29 05:58:42.921  3901  5977 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-29 05:58:42.969  3901  3901 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-29 05:58:42.969  3901  3901 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-29 05:58:42.981  3901  3901 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-29 05:58:42.981  3901  3901 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-29 05:58:42.993  3391  5972 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,09-29 05:58:42.994  3391  3417 I Process : Sending signal. PID: 3391 SIG: 9
,09-29 05:58:43.012   381   381 E lowmemorykiller: Error writing /proc/3391/oom_score_adj; errno=22
,09-29 05:58:43.012   381   381 E lowmemorykiller: Error writing /proc/3391/oom_score_adj; errno=22
,09-29 05:58:43.016  4935  5986 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-29 05:58:43.029   928  3147 I ActivityManager: Start proc 5989:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,09-29 05:58:43.065  4935  5986 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-29 05:58:43.071  3901  5985 W BaseAppContext: Using Auth Proxy for data requests.
,09-29 05:58:43.082  3901  5985 W BaseAppContext: Using Auth Proxy for data requests.
,09-29 05:58:43.092   928  3147 I ActivityManager: Process android.process.acore (pid 3391) has died
,09-29 05:58:43.092   928  3147 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-29 05:58:43.105   928  3179 I ActivityManager: Start proc 5995:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-29 05:58:43.113  3901  3901 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-29 05:58:43.126  3901  6001 I GMPM-SVC: App measurement is starting up
,09-29 05:58:43.130  3901  6001 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-29 05:58:43.131  3901  6001 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-29 05:58:43.280   383   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
